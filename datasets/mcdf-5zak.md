# IDHS - Fy11-vr-outcomes-by-county

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy11-vr-outcomes-by-county-4af7a) |
| Metadata | [Link](https://data.illinois.gov/api/views/mcdf-5zak) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mcdf-5zak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mcdf-5zak/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mcdf-5zak |
| Name | IDHS - Fy11-vr-outcomes-by-county |
| Category | Social/Healthcare |
| Created | 2011-11-02T16:11:22Z |
| Publication Date | 2011-11-02T16:13:07Z |

## Description

Number of Persons with Disabilities Successfully Employed Through the Vocational Rehabilitation Program by County in FY2011

## Columns

```ls
| Included | Schema Type    | Field Name                                                | Name                                                      | Data Type | Render Type |
| ======== | ============== | ========================================================= | ========================================================= | ========= | =========== |
| No       | time           | :updated_at                                               | updated_at                                                | meta_data | meta_data   |
| Yes      | series tag     | county                                                    | County                                                    | text      | text        |
| Yes      | numeric metric | number_of_persons_with_disabilities_successfully_employed | Number of Persons with Disabilities Successfully Employed | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mcdf-5zak d:2011-11-02T09:11:49.000Z t:county=ADAMS m:number_of_persons_with_disabilities_successfully_employed=116

series e:mcdf-5zak d:2011-11-02T09:11:49.000Z t:county=ALEXANDER m:number_of_persons_with_disabilities_successfully_employed=9

series e:mcdf-5zak d:2011-11-02T09:11:49.000Z t:county=BOND m:number_of_persons_with_disabilities_successfully_employed=7
```

## Meta Commands

```ls
metric m:number_of_persons_with_disabilities_successfully_employed p:integer l:"Number of Persons with Disabilities Successfully Employed" t:dataTypeName=number

entity e:mcdf-5zak l:"IDHS - Fy11-vr-outcomes-by-county" t:url=https://data.illinois.gov/api/views/mcdf-5zak

property e:mcdf-5zak t:meta.view v:id=mcdf-5zak v:category=Social/Healthcare v:averageRating=0 v:name="IDHS - Fy11-vr-outcomes-by-county"

property e:mcdf-5zak t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:mcdf-5zak t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | county    | number_of_persons_with_disabilities_successfully_employed | 
| =========== | ========= | ========================================================= | 
| 1320225109  | ADAMS     | 116                                                       | 
| 1320225109  | ALEXANDER | 9                                                         | 
| 1320225109  | BOND      | 7                                                         | 
| 1320225109  | BOONE     | 6                                                         | 
| 1320225109  | BROWN     | 1                                                         | 
| 1320225109  | BUREAU    | 24                                                        | 
| 1320225109  | CALHOUN   | 3                                                         | 
| 1320225109  | CARROLL   | 13                                                        | 
| 1320225109  | CASS      | 8                                                         | 
| 1320225109  | CHAMPAIGN | 90                                                        | 
```