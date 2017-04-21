# Water Point Source Sample Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-point-source-sample-results-41e0f) |
| Metadata | [Link](https://data.maryland.gov/api/views/eqs6-savc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/eqs6-savc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/eqs6-savc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | eqs6-savc |
| Name | Water Point Source Sample Results |
| Category | Energy and Environment |
| Tags | water, nutrients, sample results, mde |
| Created | 2014-05-09T17:01:24Z |
| Publication Date | 2014-07-11T20:10:52Z |

## Description

Discharge monitoring reports (DMRs) and monthly operating reports (MORs) for the 58 major WWTPs, 215 minor WWTPs, and 10 major industrial point sources within the State of Maryland and are stored in MDE?s point source database.  This data set contains results for nutrients such as phosphorous and nitrogen that may impact water quality in the Chesapeake Bay.   This dataset covers the time period from 2008 to 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | org_name                  | Org Name                  | text          | text          |
| Yes      | series tag     | station_id                | Station ID                | text          | text          |
| Yes      | series tag     | county                    | County                    | text          | text          |
| Yes      | numeric metric | huc                       | HUC                       | number        | number        |
| Yes      | series tag     | station_horizontal_datum  | Station Horizontal Datum  | text          | text          |
| Yes      | series tag     | activity_id               | Activity ID               | text          | text          |
| Yes      | time           | activity_start            | Activity Start            | calendar_date | calendar_date |
| Yes      | series tag     | activity_medium           | Activity Medium           | text          | text          |
| Yes      | series tag     | activity_type             | Activity Type             | text          | text          |
| Yes      | series tag     | activity_category_rep_num | Activity Category-Rep Num | text          | text          |
| Yes      | series tag     | characteristic_name       | Characteristic Name       | text          | text          |
| Yes      | series tag     | sample_fraction           | Sample Fraction           | text          | text          |
| Yes      | series tag     | value_type                | Value Type                | text          | text          |
| Yes      | series tag     | result_value_status       | Result Value Status       | text          | text          |
| Yes      | numeric metric | result_value              | Result Value              | number        | number        |
| Yes      | series tag     | units                     | Units                     | text          | text          |
| Yes      | series tag     | analytical_proc_id        | Analytical Proc ID        | text          | text          |
```

## Time Field

```ls
Value = activity_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:eqs6-savc d:2012-03-01T00:00:00.000Z t:analytical_proc_id=MDPOINTSOURCE~MDE-DMR t:value_type=Actual t:org_name="Maryland Point data" t:activity_category_rep_num=Sample-Routine t:result_value_status=Final t:activity_id=FY12-PS903 t:county=ALLEGANY t:characteristic_name="Biochemical oxygen demand, standard conditions" t:activity_medium=Water t:sample_fraction=Total t:station_id=MD0021598 t:station_horizontal_datum=NAD83 t:activity_type=Sample-Routine t:units=mg/l m:result_value=4 m:huc=2070002

series e:eqs6-savc d:2012-03-01T00:00:00.000Z t:analytical_proc_id=MDPOINTSOURCE~MDE-DMR t:value_type=Actual t:org_name="Maryland Point data" t:activity_category_rep_num=Sample-Routine t:result_value_status=Final t:activity_id=FY12-PS903 t:county=ALLEGANY t:characteristic_name="Total suspended solids" t:activity_medium=Water t:sample_fraction=Suspended t:station_id=MD0021598 t:station_horizontal_datum=NAD83 t:activity_type=Sample-Routine t:units=mg/l m:result_value=2 m:huc=2070002

series e:eqs6-savc d:2012-03-01T00:00:00.000Z t:analytical_proc_id=MDPOINTSOURCE~MDE-DMR t:value_type=Actual t:org_name="Maryland Point data" t:activity_category_rep_num=Sample-Routine t:result_value_status=Final t:activity_id=FY12-PS903 t:county=ALLEGANY t:characteristic_name="Dissolved oxygen (DO)" t:activity_medium=Water t:sample_fraction=Dissolved t:station_id=MD0021598 t:station_horizontal_datum=NAD83 t:activity_type=Sample-Routine t:units=mg/l m:result_value=6 m:huc=2070002
```

## Meta Commands

```ls
metric m:huc p:integer l:HUC t:dataTypeName=number

metric m:result_value p:float l:"Result Value" t:dataTypeName=number

entity e:eqs6-savc l:"Water Point Source Sample Results" t:url=https://data.maryland.gov/api/views/eqs6-savc

property e:eqs6-savc t:meta.view v:id=eqs6-savc v:category="Energy and Environment" v:averageRating=0 v:name="Water Point Source Sample Results"

property e:eqs6-savc t:meta.view.license v:name="Public Domain"

property e:eqs6-savc t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:eqs6-savc t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| org_name            | station_id | county   | huc     | station_horizontal_datum | activity_id | activity_start      | activity_medium | activity_type  | activity_category_rep_num | characteristic_name                            | sample_fraction | value_type | result_value_status | result_value | units | analytical_proc_id    | 
| =================== | ========== | ======== | ======= | ======================== | =========== | =================== | =============== | ============== | ========================= | ============================================== | =============== | ========== | =================== | ============ | ===== | ===================== | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS903  | 2012-03-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Biochemical oxygen demand, standard conditions | Total           | Actual     | Final               | 4            | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS903  | 2012-03-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Total suspended solids                         | Suspended       | Actual     | Final               | 2            | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS903  | 2012-03-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Dissolved oxygen (DO)                          | Dissolved       | Actual     | Final               | 6            | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS903  | 2012-03-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Ammonia-nitrogen                               | Total           | Actual     | Final               | 0            | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS902  | 2012-02-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Phosphorus                                     | Total           | Actual     | Final               | 0.3          | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS902  | 2012-02-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Flow                                           | Total           | Actual     | Final               | 11.925       | mgd   | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS909  | 2011-09-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Inorganic nitrogen (nitrate and nitrite)       | Total           | Actual     | Final               | 0.7          | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS909  | 2011-09-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Nitrogen                                       | Total           | Actual     | Final               | 1.2          | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS909  | 2011-09-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Orthophosphate                                 | Total           | Actual     | Final               | 0.1          | mg/l  | MDPOINTSOURCE~MDE-DMR | 
| Maryland Point data | MD0021598  | ALLEGANY | 2070002 | NAD83                    | FY12-PS909  | 2011-09-01T00:00:00 | Water           | Sample-Routine | Sample-Routine            | Phosphorus                                     | Total           | Actual     | Final               | 0.3          | mg/l  | MDPOINTSOURCE~MDE-DMR | 
```