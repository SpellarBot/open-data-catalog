# IDHS Fy11-hsp-spending-by-county

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy11-hsp-spending-by-county-295ea) |
| Metadata | [Link](https://data.illinois.gov/api/views/mnfr-wxni) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mnfr-wxni/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mnfr-wxni/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mnfr-wxni |
| Name | IDHS Fy11-hsp-spending-by-county |
| Category | Social/Healthcare |
| Created | 2011-11-02T13:51:26Z |
| Publication Date | 2011-11-02T14:00:52Z |

## Description

Spending on In-Home Care for People with Disabilities Through the Home Services Program by County in FY2011

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================== | ============================================================== | ========= | =========== |
| No       | time           | :updated_at                                                    | updated_at                                                     | meta_data | meta_data   |
| Yes      | series tag     | county                                                         | County                                                         | text      | text        |
| Yes      | numeric metric | spending_on_in_home_care_services_for_people_with_disabilities | Spending on In-Home Care Services for People with Disabilities | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mnfr-wxni d:2011-11-02T06:51:35.000Z t:county=ADAMS m:spending_on_in_home_care_services_for_people_with_disabilities=3902119.83

series e:mnfr-wxni d:2011-11-02T06:51:35.000Z t:county=BOND m:spending_on_in_home_care_services_for_people_with_disabilities=992822.76

series e:mnfr-wxni d:2011-11-02T06:51:35.000Z t:county=BOONE m:spending_on_in_home_care_services_for_people_with_disabilities=2392021.35
```

## Meta Commands

```ls
metric m:spending_on_in_home_care_services_for_people_with_disabilities p:double l:"Spending on In-Home Care Services for People with Disabilities" t:dataTypeName=money

entity e:mnfr-wxni l:"IDHS Fy11-hsp-spending-by-county" t:url=https://data.illinois.gov/api/views/mnfr-wxni

property e:mnfr-wxni t:meta.view v:id=mnfr-wxni v:category=Social/Healthcare v:averageRating=0 v:name="IDHS Fy11-hsp-spending-by-county"

property e:mnfr-wxni t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:mnfr-wxni t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | county    | spending_on_in_home_care_services_for_people_with_disabilities | 
| =========== | ========= | ============================================================== | 
| 1320216695  | ADAMS     | 3902119.83                                                     | 
| 1320216695  | BOND      | 992822.76                                                      | 
| 1320216695  | BOONE     | 2392021.35                                                     | 
| 1320216695  | BROWN     | 103564.68                                                      | 
| 1320216695  | BUREAU    | 374866.58                                                      | 
| 1320216695  | CALHOUN   | 393515.37                                                      | 
| 1320216695  | CARROLL   | 904856.52                                                      | 
| 1320216695  | CASS      | 404224.39                                                      | 
| 1320216695  | CHAMPAIGN | 4247699.71                                                     | 
| 1320216695  | CHRISTIAN | 828932.92                                                      | 
```