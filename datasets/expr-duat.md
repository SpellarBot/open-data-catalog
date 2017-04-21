# IDHA - Fy11-vr-served-by-county

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idha-fy11-vr-served-by-county-04b34) |
| Metadata | [Link](https://data.illinois.gov/api/views/expr-duat) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/expr-duat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/expr-duat/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | expr-duat |
| Name | IDHA - Fy11-vr-served-by-county |
| Category | Social/Healthcare |
| Created | 2011-11-02T16:14:39Z |
| Publication Date | 2011-11-02T16:16:15Z |

## Description

Number of Persons with Disabilities Receiving Employment Services Through the Vocational Rehabilitation Program by County in FY2011

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                                              | Data Type | Render Type |
| ======== | ============== | ================================================================= | ================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                       | updated_at                                                        | meta_data | meta_data   |
| Yes      | series tag     | county                                                            | County                                                            | text      | text        |
| Yes      | numeric metric | number_of_persons_with_disabilities_receiving_employment_services | Number of Persons with Disabilities Receiving Employment Services | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:expr-duat d:2011-11-02T09:14:50.000Z t:county=ADAMS m:number_of_persons_with_disabilities_receiving_employment_services=737

series e:expr-duat d:2011-11-02T09:14:50.000Z t:county=ALEXANDER m:number_of_persons_with_disabilities_receiving_employment_services=77

series e:expr-duat d:2011-11-02T09:14:50.000Z t:county=BOND m:number_of_persons_with_disabilities_receiving_employment_services=50
```

## Meta Commands

```ls
metric m:number_of_persons_with_disabilities_receiving_employment_services p:integer l:"Number of Persons with Disabilities Receiving Employment Services" t:dataTypeName=number

entity e:expr-duat l:"IDHA - Fy11-vr-served-by-county" t:url=https://data.illinois.gov/api/views/expr-duat

property e:expr-duat t:meta.view v:id=expr-duat v:category=Social/Healthcare v:averageRating=0 v:name="IDHA - Fy11-vr-served-by-county"

property e:expr-duat t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:expr-duat t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | county    | number_of_persons_with_disabilities_receiving_employment_services | 
| =========== | ========= | ================================================================= | 
| 1320225290  | ADAMS     | 737                                                               | 
| 1320225290  | ALEXANDER | 77                                                                | 
| 1320225290  | BOND      | 50                                                                | 
| 1320225290  | BOONE     | 70                                                                | 
| 1320225290  | BROWN     | 15                                                                | 
| 1320225290  | BUREAU    | 155                                                               | 
| 1320225290  | CALHOUN   | 35                                                                | 
| 1320225290  | CARROLL   | 56                                                                | 
| 1320225290  | CASS      | 86                                                                | 
| 1320225290  | CHAMPAIGN | 816                                                               | 
```