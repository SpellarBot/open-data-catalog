# Missouri First Reports of Injury by Body Part - Miscellaneous

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-body-part-miscellaneous-28848) |
| Metadata | [Link](https://data.mo.gov/api/views/g5ud-am38) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/g5ud-am38/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/g5ud-am38/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | g5ud-am38 |
| Name | Missouri First Reports of Injury by Body Part - Miscellaneous |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-03T12:35:50Z |
| Publication Date | 2013-01-03T20:53:39Z |

## Description

First reports of injury filed reporting an injury to miscellaneous or multiple body parts.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | recordid                               | recordid                               | text      | text        |
| No       |                | year                                   | year                                   | number    | number      |
| No       |                | month                                  | month                                  | number    | number      |
| Yes      | numeric metric | insufficient_info_to_properly_identify | insufficient info to properly identify | number    | number      |
| Yes      | numeric metric | multiple_body_parts                    | multiple body parts                    | number    | number      |
| Yes      | numeric metric | other_or_unspecified                   | other or unspecified                   | number    | number      |
| Yes      | numeric metric | no_physical_injury                     | no physical injury                     | number    | number      |
| Yes      | numeric metric | whole_body                             | whole body                             | number    | number      |
| Yes      | numeric metric | body_systems                           | body systems                           | number    | number      |
| Yes      | numeric metric | artificial_appliance                   | artificial appliance                   | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:g5ud-am38 d:2005-04-01T00:00:00.000Z t:recordid=42005 m:insufficient_info_to_properly_identify=51 m:multiple_body_parts=1469 m:body_systems=81 m:no_physical_injury=43 m:artificial_appliance=3

series e:g5ud-am38 d:2004-04-01T00:00:00.000Z t:recordid=42004 m:insufficient_info_to_properly_identify=47 m:multiple_body_parts=1584 m:body_systems=61 m:no_physical_injury=90 m:artificial_appliance=2

series e:g5ud-am38 d:2007-04-01T00:00:00.000Z t:recordid=42007 m:insufficient_info_to_properly_identify=106 m:multiple_body_parts=1812 m:whole_body=4 m:body_systems=62 m:no_physical_injury=65 m:artificial_appliance=3
```

## Meta Commands

```ls
metric m:insufficient_info_to_properly_identify p:integer l:"insufficient info to properly identify" t:dataTypeName=number

metric m:multiple_body_parts p:integer l:"multiple body parts" t:dataTypeName=number

metric m:other_or_unspecified p:integer l:"other or unspecified" t:dataTypeName=number

metric m:no_physical_injury p:integer l:"no physical injury" t:dataTypeName=number

metric m:whole_body p:integer l:"whole body" t:dataTypeName=number

metric m:body_systems p:integer l:"body systems" t:dataTypeName=number

metric m:artificial_appliance p:integer l:"artificial appliance" t:dataTypeName=number

entity e:g5ud-am38 l:"Missouri First Reports of Injury by Body Part - Miscellaneous" t:url=https://data.mo.gov/api/views/g5ud-am38

property e:g5ud-am38 t:meta.view v:id=g5ud-am38 v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Body Part - Miscellaneous"

property e:g5ud-am38 t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:g5ud-am38 t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid | year | month | insufficient_info_to_properly_identify | multiple_body_parts | other_or_unspecified | no_physical_injury | whole_body | body_systems | artificial_appliance | 
| ======== | ==== | ===== | ====================================== | =================== | ==================== | ================== | ========== | ============ | ==================== | 
| 42005    | 2005 | 4     | 51                                     | 1469                |                      | 43                 |            | 81           | 3                    | 
| 42004    | 2004 | 4     | 47                                     | 1584                |                      | 90                 |            | 61           | 2                    | 
| 42007    | 2007 | 4     | 106                                    | 1812                |                      | 65                 | 4          | 62           | 3                    | 
| 42006    | 2006 | 4     | 97                                     | 1366                |                      | 66                 |            | 44           | 9                    | 
| 42009    | 2009 | 4     | 43                                     | 1366                |                      | 71                 | 3          | 67           | 3                    | 
| 42008    | 2008 | 4     | 59                                     | 1514                |                      | 51                 | 9          | 53           | 7                    | 
| 42001    | 2001 | 4     | 61                                     | 1273                |                      | 61                 |            | 55           |                      | 
| 42003    | 2003 | 4     | 117                                    | 1394                |                      | 41                 |            | 44           | 2                    | 
| 42002    | 2002 | 4     | 116                                    | 1455                |                      | 77                 |            | 107          | 2                    | 
| 102009   | 2009 | 10    | 48                                     | 1453                |                      | 51                 | 5          | 118          | 1                    | 
```