# IDHS - Fy11-hsp-served-by-county

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy11-hsp-served-by-county-07552) |
| Metadata | [Link](https://data.illinois.gov/api/views/zcdc-h4pz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/zcdc-h4pz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/zcdc-h4pz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | zcdc-h4pz |
| Name | IDHS - Fy11-hsp-served-by-county |
| Category | Social/Healthcare |
| Created | 2011-11-02T13:46:52Z |
| Publication Date | 2011-11-02T13:49:01Z |

## Description

Number of Persons with Disabilities Receiving In-Home Care Through the Home Services Program by County in FY2011

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| No       | time           | :updated_at                                                | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag     | county                                                     | County                                                     | text      | text        |
| Yes      | numeric metric | number_of_persons_with_disabilities_receiving_in_home_care | Number of Persons with Disabilities Receiving In-Home Care | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:zcdc-h4pz d:2011-11-02T06:47:08.000Z t:county=ADAMS m:number_of_persons_with_disabilities_receiving_in_home_care=385

series e:zcdc-h4pz d:2011-11-02T06:47:08.000Z t:county=ALEXANDER m:number_of_persons_with_disabilities_receiving_in_home_care=103

series e:zcdc-h4pz d:2011-11-02T06:47:08.000Z t:county=BOND m:number_of_persons_with_disabilities_receiving_in_home_care=110
```

## Meta Commands

```ls
metric m:number_of_persons_with_disabilities_receiving_in_home_care p:integer l:"Number of Persons with Disabilities Receiving In-Home Care" t:dataTypeName=number

entity e:zcdc-h4pz l:"IDHS - Fy11-hsp-served-by-county" t:url=https://data.illinois.gov/api/views/zcdc-h4pz

property e:zcdc-h4pz t:meta.view v:id=zcdc-h4pz v:category=Social/Healthcare v:averageRating=0 v:name="IDHS - Fy11-hsp-served-by-county"

property e:zcdc-h4pz t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:zcdc-h4pz t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | county    | number_of_persons_with_disabilities_receiving_in_home_care | 
| =========== | ========= | ========================================================== | 
| 1320216428  | ADAMS     | 385                                                        | 
| 1320216428  | ALEXANDER | 103                                                        | 
| 1320216428  | BOND      | 110                                                        | 
| 1320216428  | BOONE     | 158                                                        | 
| 1320216428  | BROWN     | 9                                                          | 
| 1320216428  | BUREAU    | 44                                                         | 
| 1320216428  | CALHOUN   | 29                                                         | 
| 1320216428  | CARROLL   | 73                                                         | 
| 1320216428  | CASS      | 41                                                         | 
| 1320216428  | CHAMPAIGN | 303                                                        | 
```