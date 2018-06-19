# Illinois Fire Service Directory As Of 9-26-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-fire-service-directory-as-of-9-26-2012-da1f8) |
| Metadata | [Link](https://data.illinois.gov/api/views/6q7j-pmr6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6q7j-pmr6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6q7j-pmr6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6q7j-pmr6 |
| Name | Illinois Fire Service Directory As Of 9-26-2012 |
| Category | Public Safety |
| Tags | illinois, state fire marshal, fire service |
| Created | 2012-09-26T15:30:22Z |
| Publication Date | 2012-09-26T17:08:06Z |

## Description

Illinois Office of the State Fire Marshal Personnel Standards and Education Division For more information, please see our website at http://www.sfm.illinois.gov

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | entity_name_chr      | entity_name_chr      | text      | text        |
| Yes      | series tag  | chief_last_name_chr  | chief_last_name_chr  | text      | text        |
| Yes      | series tag  | chief_first_name_chr | chief_first_name_chr | text      | text        |
| Yes      | series tag  | addr_line_1_chr      | addr_line_1_chr      | text      | text        |
| Yes      | series tag  | addr_line_2_chr      | addr_line_2_chr      | text      | text        |
| Yes      | series tag  | city_chr             | city_chr             | text      | text        |
| Yes      | series tag  | zip_cd_chr           | zip_cd_chr           | text      | number      |
| Yes      | series tag  | fdid_chr             | fdid_chr             | text      | text        |
| Yes      | series tag  | cnty_chr             | cnty_chr             | text      | text        |
| Yes      | series tag  | type_chr             | type_chr             | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6q7j-pmr6 d:2012-01-01T00:00:00.000Z t:cnty_chr="St. Clair" t:city_chr=Belleville t:zip_cd_chr=62221 t:addr_line_1_chr="2500 Carlyle Avenue" t:type_chr="Fire College" t:fdid_chr=ZA038 t:entity_name_chr="Southwestern Illinois College" m:row_number.6q7j-pmr6=1

series e:6q7j-pmr6 d:2012-01-01T00:00:00.000Z t:cnty_chr=Kankakee t:city_chr=Bradley t:zip_cd_chr=60915 t:addr_line_1_chr="% Greg Glidewell" t:type_chr="Fire College" t:fdid_chr=ZA014 t:entity_name_chr="Kankakee Valley Fire Academy" t:addr_line_2_chr="147 S. Michigan Ave." m:row_number.6q7j-pmr6=2

series e:6q7j-pmr6 d:2012-01-01T00:00:00.000Z t:cnty_chr=(None) t:city_chr="South Holland" t:zip_cd_chr=60473 t:addr_line_1_chr="16230 Wausau Avenue" t:type_chr="Fire College" t:fdid_chr=ZA040 t:entity_name_chr="Third (3rd) District Training Academy" m:row_number.6q7j-pmr6=3
```

## Meta Commands

```ls
metric m:row_number.6q7j-pmr6 p:long l:"Row Number"

entity e:6q7j-pmr6 l:"Illinois Fire Service Directory As Of 9-26-2012" t:url=https://data.illinois.gov/api/views/6q7j-pmr6

property e:6q7j-pmr6 t:meta.view v:id=6q7j-pmr6 v:category="Public Safety" v:averageRating=0 v:name="Illinois Fire Service Directory As Of 9-26-2012"

property e:6q7j-pmr6 t:meta.view.owner v:id=4sdw-c9ng v:screenName=ILOSFM v:displayName=ILOSFM

property e:6q7j-pmr6 t:meta.view.tableauthor v:id=4sdw-c9ng v:screenName=ILOSFM v:roleName=publisher v:displayName=ILOSFM
```

## Top Records

```ls
| entity_name_chr                       | chief_last_name_chr | chief_first_name_chr | addr_line_1_chr                  | addr_line_2_chr      | city_chr      | zip_cd_chr | fdid_chr | cnty_chr   | type_chr     | 
| ===================================== | =================== | ==================== | ================================ | ==================== | ============= | ========== | ======== | ========== | ============ | 
| Southwestern Illinois College         |                     |                      | 2500 Carlyle Avenue              |                      | Belleville    | 62221      | ZA038    | St. Clair  | Fire College | 
| Kankakee Valley Fire Academy          |                     |                      | % Greg Glidewell                 | 147 S. Michigan Ave. | Bradley       | 60915      | ZA014    | Kankakee   | Fire College | 
| Third (3rd) District Training Academy |                     |                      | 16230 Wausau Avenue              |                      | South Holland | 60473      | ZA040    | (None)     | Fire College | 
| Coal Belt Training                    |                     |                      | 300 North Division Street        |                      | Carterville   | 62918      |          | Williamson | Fire College | 
| Nalco Chemicals                       |                     |                      | 6216 West 66th Place             |                      | Chicago       | 60638      |          | (None)     | Fire Brigade | 
| Waubonsee Community College           |                     |                      | Illinois Route 47 At Harter Road |                      | Sugar Grove   | 60544      | ZA041    |            | Fire College | 
| District 2 Academy                    |                     |                      | 8815 West 123rd                  |                      | Palos Park    | 60464      |          | Cook       | Fire College | 
| Black Hawk College                    |                     |                      | 6600 34th Avenue                 |                      | Moline        | 61265      | ZA003    |            | Fire College | 
| Joliet Junior College                 |                     |                      | 1216 Houbolt                     |                      | Joliet        | 60436      | ZA013    |            | Fire College | 
| Morton College                        |                     |                      | 1510 Parkside Dr.                |                      | Plainfield    | 60586      | ZA022    | (None)     | Fire College | 
```