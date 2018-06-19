# Water Quality Sampling Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-quality-sampling-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5tye-7ray) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5tye-7ray/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5tye-7ray/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5tye-7ray |
| Name | Water Quality Sampling Data |
| Attribution | City of Austin Watershed Protection Environmental Resource Management |
| Category | Environmental |
| Tags | water quality, eii, ali, barton springs, lady bird lake, lake austin, salamanders, barton creek, bull creek, bacteria, coli |
| Created | 2012-01-03T14:55:34Z |
| Publication Date | 2015-03-11T20:03:09Z |

## Description

Data collected to assess water quality conditions in the natural creeks, aquifers and lakes in the Austin area. This is raw data, provided directly from our Field Sample database (FSDB) and should be considered provisional. Data may or may not have been reviewed by project staff.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | watershed       | WATERSHED       | text          | text          |
| Yes      | time           | sample_date     | SAMPLE_DATE     | calendar_date | calendar_date |
| Yes      | series tag     | site_name       | SITE_NAME       | text          | text          |
| Yes      | series tag     | site_type       | SITE_TYPE       | text          | text          |
| Yes      | series tag     | medium          | MEDIUM          | text          | text          |
| Yes      | series tag     | param_type      | PARAM_TYPE      | text          | text          |
| Yes      | series tag     | parameter       | PARAMETER       | text          | text          |
| Yes      | series tag     | qualifier       | QUALIFIER       | text          | text          |
| Yes      | numeric metric | result          | RESULT          | number        | number        |
| Yes      | series tag     | unit            | UNIT            | text          | text          |
| Yes      | series tag     | filter          | FILTER          | text          | text          |
| Yes      | series tag     | sample_id       | SAMPLE_ID       | text          | text          |
| Yes      | series tag     | sample_site_no  | SAMPLE_SITE_NO  | text          | number        |
| Yes      | numeric metric | depth_in_meters | DEPTH_IN_METERS | number        | number        |
| Yes      | series tag     | method          | METHOD          | text          | text          |
| Yes      | series tag     | qc_flag         | QC_FLAG         | text          | text          |
| Yes      | series tag     | project         | PROJECT         | text          | text          |
| Yes      | series tag     | ref_no          | DATA_REF_NO     | text          | number        |
| No       |                | lat_dd_wgs84    | LAT_DD_WGS84    | number        | number        |
| Yes      | numeric metric | lon_dd_wgs84    | LON_DD_WGS84    | number        | number        |
| Yes      | series tag     | sample_ref_no   | SAMPLE_REF_NO   | text          | number        |
| No       |                | time_null       | TIME_NULL       | text          | text          |
| Yes      | series tag     | qc_type         | QC_TYPE         | text          | text          |
```

## Time Field

```ls
Value = sample_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lat_dd_wgs84,time_null
```

## Data Commands

```ls
series e:5tye-7ray d:2013-07-18T14:58:00.000Z t:sample_id=CW t:site_name="Old Mill (Sunken Gardens) Spring" t:medium="Benthic Cover" t:watershed="Barton Creek" t:unit="1=Present; 0=Absent" t:project="Barton Springs Salamander" t:sample_ref_no=440459 t:parameter="ANNELIDA (WORM/LEECHES/PLANARIA)" t:qc_flag=U t:param_type="Benthic Macroinvertebrates" t:ref_no=2227594 t:sample_site_no=422 t:site_type=Spring t:method="VISUAL ASSESSMENT" t:filter=Total m:lon_dd_wgs84=-97.7680757366172 m:result=1 m:depth_in_meters=0.4968

series e:5tye-7ray d:2013-07-18T14:58:00.000Z t:sample_id=CW t:site_name="Old Mill (Sunken Gardens) Spring" t:medium="Benthic Cover" t:watershed="Barton Creek" t:unit="Relative Abundance (1): <20 (2): 21-50 (3): >50" t:project="Barton Springs Salamander" t:sample_ref_no=440459 t:parameter="CRAYFISH (ADULT)" t:qc_flag=U t:param_type="Benthic Macroinvertebrates" t:ref_no=2227586 t:sample_site_no=422 t:site_type=Spring t:method="VISUAL ASSESSMENT" t:filter=Total m:lon_dd_wgs84=-97.7680757366172 m:result=2 m:depth_in_meters=0.4968

series e:5tye-7ray d:2013-07-18T14:58:00.000Z t:sample_id=CW t:site_name="Old Mill (Sunken Gardens) Spring" t:medium="Benthic Cover" t:watershed="Barton Creek" t:unit="Relative Abundance (1): <20 (2): 21-50 (3): >50" t:project="Barton Springs Salamander" t:sample_ref_no=440459 t:parameter="CRAYFISH (JUVENILE)" t:qc_flag=U t:param_type="Benthic Macroinvertebrates" t:ref_no=2227585 t:sample_site_no=422 t:site_type=Spring t:method="VISUAL ASSESSMENT" t:filter=Total m:lon_dd_wgs84=-97.7680757366172 m:result=1 m:depth_in_meters=0.4968
```

## Meta Commands

```ls
metric m:result p:double l:RESULT d:"This is the ""RESULT.""" t:dataTypeName=number

metric m:depth_in_meters p:double l:DEPTH_IN_METERS d:"The depth at which the sample was collected in meters. This is a useful field for Lake data (specifically our Lady Bird Lake data collection) and is null for other samples." t:dataTypeName=number

metric m:lon_dd_wgs84 p:double l:LON_DD_WGS84 d:"X coordinate in WGS_1984 decimal degrees (Commonly referred to as Longitude)" t:dataTypeName=number

entity e:5tye-7ray l:"Water Quality Sampling Data" t:attribution="City of Austin Watershed Protection Environmental Resource Management" t:url=https://data.austintexas.gov/api/views/5tye-7ray

property e:5tye-7ray t:meta.view v:id=5tye-7ray v:category=Environmental v:averageRating=0 v:name="Water Quality Sampling Data" v:attribution="City of Austin Watershed Protection Environmental Resource Management"

property e:5tye-7ray t:meta.view.owner v:id=buxt-jupg v:profileImageUrlMedium=/api/users/buxt-jupg/profile_images/THUMB v:profileImageUrlLarge=/api/users/buxt-jupg/profile_images/LARGE v:screenName=Rob v:profileImageUrlSmall=/api/users/buxt-jupg/profile_images/TINY v:displayName=Rob

property e:5tye-7ray t:meta.view.tableauthor v:id=buxt-jupg v:profileImageUrlMedium=/api/users/buxt-jupg/profile_images/THUMB v:profileImageUrlLarge=/api/users/buxt-jupg/profile_images/LARGE v:screenName=Rob v:profileImageUrlSmall=/api/users/buxt-jupg/profile_images/TINY v:roleName=publisher v:displayName=Rob
```

## Top Records

```ls
| watershed    | sample_date         | site_name                        | site_type | medium        | param_type                 | parameter                        | qualifier | result | unit                                            | filter | sample_id | sample_site_no | depth_in_meters | method            | qc_flag | project                   | ref_no  | lat_dd_wgs84     | lon_dd_wgs84      | sample_ref_no | time_null | qc_type | 
| ============ | =================== | ================================ | ========= | ============= | ========================== | ================================ | ========= | ====== | =============================================== | ====== | ========= | ============== | =============== | ================= | ======= | ========================= | ======= | ================ | ================= | ============= | ========= | ======= | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | ANNELIDA (WORM/LEECHES/PLANARIA) |           | 1      | 1=Present; 0=Absent                             | Total  | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227594 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | CRAYFISH (ADULT)                 |           | 2      | Relative Abundance (1): <20 (2): 21-50 (3): >50 | Total  | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227586 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | CRAYFISH (JUVENILE)              |           | 1      | Relative Abundance (1): <20 (2): 21-50 (3): >50 | Total  | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227585 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | DIPTERA (MIDGE/FLY)              |           | 1      | 1=Present; 0=Absent                             | Larvae | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227591 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | EPHEMEROPTERA (MAYFLY)           |           | 1      | 1=Present; 0=Absent                             | Larvae | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227589 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | MOLLUSCA                         |           | 1      | 1=Present; 0=Absent                             | Total  | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227595 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | ODONATA (DAMSELFLY/DRAGONFLY)    |           | 1      | 1=Present; 0=Absent                             | Larvae | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227593 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | OTHER INVERTEBRATES              |           | 0      | 1=Present; 0=Absent                             | Total  | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227598 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | PETROPHILA (MOTH)                |           | 0      | 1=Present; 0=Absent                             | Larvae | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227592 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
| Barton Creek | 2013-07-18T14:58:00 | Old Mill (Sunken Gardens) Spring | Spring    | Benthic Cover | Benthic Macroinvertebrates | PSEPHENIDAE (WATER PENNIES)      |           | 1      | 1=Present; 0=Absent                             | Total  | CW        | 422            | 0.4968          | VISUAL ASSESSMENT | U       | Barton Springs Salamander | 2227588 | 30.2635848609854 | -97.7680757366172 | 440459        | false     |         | 
```