# Water Right Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-right-applications-7e256) |
| Metadata | [Link](https://data.wa.gov/api/views/9ubz-5r4b) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9ubz-5r4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9ubz-5r4b/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9ubz-5r4b |
| Name | Water Right Applications |
| Attribution | Washington Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | ecology, water rights |
| Created | 2012-10-11T23:32:24Z |
| Publication Date | 2016-06-17T21:05:58Z |

## Description

Pending Water Right Applications in Washington State. Includes both applications for new water rights and to change existing water rights. Updated weekly.    Live data available at: https://fortress.wa.gov/ecy/waterresources/map/QuantityReport.aspx and https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | wr_doc_id                        | WR_DOC_ID                        | text          | number        |
| Yes      | series tag     | document_number                  | DOCUMENT_NUMBER                  | text          | text          |
| Yes      | series tag     | document_type                    | DOCUMENT_TYPE                    | text          | text          |
| Yes      | series tag     | purpose_code_list                | PURPOSE_CODE_LIST                | text          | text          |
| Yes      | series tag     | person_last_or_organization_name | PERSON_LAST_OR_ORGANIZATION_NAME | text          | text          |
| Yes      | time           | priority_date                    | PRIORITY_DATE                    | calendar_date | calendar_date |
| No       |                | year_applied                     | YEAR_APPLIED                     | number        | number        |
| Yes      | numeric metric | cfs                              | CFS                              | number        | number        |
| Yes      | numeric metric | gpm                              | GPM                              | number        | number        |
| Yes      | numeric metric | domestic_units                   | DOMESTIC_UNITS                   | number        | number        |
| Yes      | numeric metric | acre_feet                        | ACRE_FEET                        | number        | number        |
| Yes      | numeric metric | acre_irr                         | ACRE_IRR                         | number        | number        |
| Yes      | series tag     | county_name                      | COUNTY_NAME                      | text          | text          |
| Yes      | series tag     | wria                             | WRIA_NUMBER                      | text          | number        |
| Yes      | series tag     | wria_nm                          | WATERSHED                        | text          | text          |
| Yes      | series tag     | cert_num                         | CERT_NUM                         | text          | text          |
| Yes      | series tag     | trs                              | TRS                              | text          | text          |
| Yes      | series tag     | quad_designation                 | QUAD_DESIGNATION                 | text          | text          |
| Yes      | series tag     | source_name                      | SOURCE_NAME                      | text          | text          |
| Yes      | series tag     | tributary_name                   | TRIBUTARY_NAME                   | text          | text          |
| Yes      | series tag     | image_url                        | IMAGE_URL                        | url           | url           |
| Yes      | series tag     | map_url                          | MAP_URL                          | url           | url           |
| No       |                | latitude1                        | Latitude1                        | number        | text          |
| No       |                | longitude1                       | Longitude1                       | number        | text          |
```

## Time Field

```ls
Value = priority_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude1,longitude1,year_applied
```

## Data Commands

```ls
series e:9ubz-5r4b d:2016-05-27T00:00:00.000Z t:purpose_code_list=MU t:wria_nm="Upper Skagit" t:quad_designation=SW/SE t:tributary_name="SKAGIT RIVER" t:person_last_or_organization_name="Seattle City Light" t:wria=4 t:map_url="https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799476" t:document_type=ChangeApplication t:trs=T38N/R13E-35 t:document_number=CS1-*04465C t:image_url="https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799476&wr_doc_file_nr=CS1-*04465C" t:wr_doc_id=6799476 t:source_name="ROSS LAKE" t:county_name=Whatcom m:cfs=5

series e:9ubz-5r4b d:2016-05-27T00:00:00.000Z t:purpose_code_list=IR t:wria_nm="Lower Crab" t:quad_designation=SE/NW t:person_last_or_organization_name="North 40 Cherries LLC" t:wria=41 t:map_url="https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799468" t:document_type=ChangeApplication t:trs=T21N/R24E-26 t:document_number=CG3-23865C(A)@3 t:image_url="https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799468&wr_doc_file_nr=CG3-23865C(A)@3" t:wr_doc_id=6799468 t:source_name=GROUNDWATER t:county_name=Grant m:acre_feet=70 m:acre_irr=20 m:gpm=80

series e:9ubz-5r4b d:2016-05-27T00:00:00.000Z t:purpose_code_list=FP,IR t:wria_nm="Lower Crab" t:quad_designation=SE/NW t:person_last_or_organization_name="North 40 Cherries LLC" t:wria=41 t:map_url="https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799469" t:document_type=ChangeApplication t:trs=T21N/R24E-26 t:document_number=CG3-28551C@4 t:image_url="https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799469&wr_doc_file_nr=CG3-28551C@4" t:wr_doc_id=6799469 t:source_name=GROUNDWATER t:county_name=Grant m:acre_feet=157 m:acre_irr=45 m:gpm=470
```

## Meta Commands

```ls
metric m:cfs p:double l:CFS d:"Cubic feet per second" t:dataTypeName=number

metric m:gpm p:integer l:GPM d:"Gallons Per Minute" t:dataTypeName=number

metric m:domestic_units p:long l:DOMESTIC_UNITS d:"Number of residential connections" t:dataTypeName=number

metric m:acre_feet p:double l:ACRE_FEET t:dataTypeName=number

metric m:acre_irr p:double l:ACRE_IRR t:dataTypeName=number

entity e:9ubz-5r4b l:"Water Right Applications" t:attribution="Washington Department of Ecology" t:url=https://data.wa.gov/api/views/9ubz-5r4b

property e:9ubz-5r4b t:meta.view v:id=9ubz-5r4b v:category="Natural Resources & Environment" v:attributionLink=http://ecy.wa.gov v:averageRating=40 v:name="Water Right Applications" v:attribution="Washington Department of Ecology"

property e:9ubz-5r4b t:meta.view.license v:name="Public Domain"

property e:9ubz-5r4b t:meta.view.owner v:id=m4wk-vfvn v:profileImageUrlMedium=/api/users/m4wk-vfvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/m4wk-vfvn/profile_images/LARGE v:screenName="Jeff Marti" v:profileImageUrlSmall=/api/users/m4wk-vfvn/profile_images/TINY v:lastNotificationSeenAt=1492023518 v:displayName="Jeff Marti"

property e:9ubz-5r4b t:meta.view.tableauthor v:id=m4wk-vfvn v:profileImageUrlMedium=/api/users/m4wk-vfvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/m4wk-vfvn/profile_images/LARGE v:screenName="Jeff Marti" v:profileImageUrlSmall=/api/users/m4wk-vfvn/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492023518 v:displayName="Jeff Marti"
```

## Top Records

```ls
| wr_doc_id | document_number | document_type     | purpose_code_list | person_last_or_organization_name | priority_date       | year_applied | cfs   | gpm | domestic_units | acre_feet | acre_irr | county_name  | wria | wria_nm               | cert_num | trs          | quad_designation | source_name        | tributary_name | image_url                                                                                                                | map_url                                                                                               | latitude1 | longitude1 | 
| ========= | =============== | ================= | ================= | ================================ | =================== | ============ | ===== | === | ============== | ========= | ======== | ============ | ==== | ===================== | ======== | ============ | ================ | ================== | ============== | ======================================================================================================================== | ===================================================================================================== | ========= | ========== | 
| 6799476   | CS1-*04465C     | ChangeApplication | MU                | Seattle City Light               | 2016-05-27T00:00:00 | 2016         | 5     |     |                |           |          | Whatcom      | 4    | Upper Skagit          |          | T38N/R13E-35 | SW/SE            | ROSS LAKE          | SKAGIT RIVER   | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799476&wr_doc_file_nr=CS1-*04465C, null]     | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799476, null] | 48.73508  | -121.07443 | 
| 6799468   | CG3-23865C(A)@3 | ChangeApplication | IR                | North 40 Cherries LLC            | 2016-05-27T00:00:00 | 2016         |       | 80  |                | 70        | 20       | Grant        | 41   | Lower Crab            |          | T21N/R24E-26 | SE/NW            | GROUNDWATER        |                | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799468&wr_doc_file_nr=CG3-23865C(A)@3, null] | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799468, null] | 47.28742  | -119.78228 | 
| 6799469   | CG3-28551C@4    | ChangeApplication | FP,IR             | North 40 Cherries LLC            | 2016-05-27T00:00:00 | 2016         |       | 470 |                | 157       | 45       | Grant        | 41   | Lower Crab            |          | T21N/R24E-26 | SE/NW            | GROUNDWATER        |                | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799469&wr_doc_file_nr=CG3-28551C@4, null]    | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799469, null] | 47.28742  | -119.78228 | 
| 6799475   | CS1-*07665C@1   | ChangeApplication | IR                | C D HILLIS & SONS                | 2016-05-27T00:00:00 | 2016         | 0.2   |     |                |           | 20       | Snohomish    | 5    | Stillaguamish         |          | T32N/R6E-11  | NW/SW            | GROUNDWATER        |                | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799475&wr_doc_file_nr=CS1-*07665C@1, null]   | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799475, null] | 48.27552  | -121.9991  | 
| 6799474   | CS3-29207       | ChangeApplication | IR,ST             | Doyle                            | 2016-05-25T00:00:00 | 2016         | 0.15  |     |                | 15.98     | 7        | Pend Oreille | 62   | Pend Oreille          |          | T37N/R43E-8  | SW/SW            | PEND OREILLE RIVER |                | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799474&wr_doc_file_nr=CS3-29207, null]       | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799474, null] | 48.7159   | -117.40806 | 
| 6799471   | S1-28820        | NewApp            | DS                | Quickstad                        | 2016-05-19T00:00:00 | 2016         | 0.011 |     |                |           |          | Skagit       | 5    | Stillaguamish         |          | T33N/R6E-27  | /                | LAKE CAVANAUGH     |                | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799471&wr_doc_file_nr=S1-28820, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799471, null] | 0         | 0          | 
| 6799422   | S2-30684        | NewApp            | IR                | Hickey                           | 2016-05-19T00:00:00 | 2016         | 0.44  |     |                |           | 2.5      | Clark        | 28   | Salmon-Washougal      |          | T1N/R4E-16   | /NE              | GIBBONS CREEK      | COLUMBIA RIVER | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799422&wr_doc_file_nr=S2-30684, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799422, null] | 0         | 0          | 
| 6799445   | S3-30761        | NewApp            | IR                | Sampson                          | 2016-05-19T00:00:00 | 2016         | 0.23  |     |                | 0.5       | 12       | Stevens      | 58   | Middle Lake Roosevelt |          | T31N/R37E-23 | NE/SW            | HARVEY CREEK       | COLUMBIA RIVER | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799445&wr_doc_file_nr=S3-30761, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799445, null] | 0         | 0          | 
| 6799444   | S3-30760        | NewApp            | IR                | Sampson                          | 2016-05-19T00:00:00 | 2016         | 1.07  |     |                | 5         | 80       | Stevens      | 58   | Middle Lake Roosevelt |          | T31N/R37E-22 | SE/SE            | HARVEY CREEK       | COLUMBIA RIVER | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799444&wr_doc_file_nr=S3-30760, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799444, null] | 0         | 0          | 
| 6799477   | G4-35856        | NewApp            | DS                | Burchak *                        | 2016-05-18T00:00:00 | 2016         |       |     |                | 0.392     |          | Kittitas     | 39   | Upper Yakima          |          | T19N/R15E-4  | /                | GROUNDWATER        |                | [https://fortress.wa.gov/ecy/waterresources/map/imageviewer.aspx?wr_doc_id=6799477&wr_doc_file_nr=G4-35856, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer2.aspx?wr_doc_id=6799477, null] | 0         | 0          | 
```