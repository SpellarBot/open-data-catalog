# Navigator Entities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/navigator-entities-0ffd2) |
| Metadata | [Link](https://data.mo.gov/api/views/n7d6-s7dn) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/n7d6-s7dn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/n7d6-s7dn/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | n7d6-s7dn |
| Name | Navigator Entities |
| Attribution | Missouri Department of Insurance, Financial Institutions & Professional (DIFP) |
| Category | Insurance |
| Tags | health, insurance, navigators, navigator, licensed navigators, health insurance, navigator phone, navigators phone |
| Created | 2013-10-04T20:41:49Z |
| Publication Date | 2017-04-19T19:42:51Z |

## Description

Navigator Entities licensed in Missouri.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | Name       | text      | text        |
| Yes      | series tag     | city        | City       | text      | text        |
| Yes      | numeric metric | phone       | Phone      | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:n7d6-s7dn d:2017-04-19T19:42:42.000Z t:name="BIG SPRINGS MEDICAL ASSOCIATION INC DBA MISSOURI HIGHLANDS HEALTH CARE" t:city=ELLINGTON m:phone=5736632313

series e:n7d6-s7dn d:2017-04-19T19:42:42.000Z t:name="CENTRAL MISSOURI AREA AGENCY ON AGING" t:city=COLUMBIA m:phone=5734435823

series e:n7d6-s7dn d:2017-04-19T19:42:42.000Z t:name="MISSOURI ALLIANCE OF AREA AGENCIES ON AGING" t:city=COLUMBIA m:phone=5736196185
```

## Meta Commands

```ls
metric m:phone p:long l:Phone t:dataTypeName=number

entity e:n7d6-s7dn l:"Navigator Entities" t:attribution="Missouri Department of Insurance, Financial Institutions & Professional (DIFP)" t:url=https://data.mo.gov/api/views/n7d6-s7dn

property e:n7d6-s7dn t:meta.view v:id=n7d6-s7dn v:category=Insurance v:averageRating=0 v:name="Navigator Entities" v:attribution="Missouri Department of Insurance, Financial Institutions & Professional (DIFP)"

property e:n7d6-s7dn t:meta.view.owner v:id=byu7-dn9b v:screenName=DIFP v:displayName=DIFP

property e:n7d6-s7dn t:meta.view.tableauthor v:id=byu7-dn9b v:screenName=DIFP v:roleName=editor v:displayName=DIFP
```

## Top Records

```ls
| :updated_at | name                                                                            | city           | phone      | 
| =========== | =============================================================================== | ============== | ========== | 
| 1492630962  | BIG SPRINGS MEDICAL ASSOCIATION INC DBA MISSOURI HIGHLANDS HEALTH CARE          | ELLINGTON      | 5736632313 | 
| 1492630962  | CENTRAL MISSOURI AREA AGENCY ON AGING                                           | COLUMBIA       | 5734435823 | 
| 1492630962  | MISSOURI ALLIANCE OF AREA AGENCIES ON AGING                                     | COLUMBIA       | 5736196185 | 
| 1492630962  | CERTIFIED PROCESSING CORPORATION                                                | ST LOUIS       | 3149617077 | 
| 1492630962  | COMMUNITY HEALTH CENTER OF CENTRAL MISSOURI                                     | JEFFERSON CITY | 5736322777 | 
| 1492630962  | COMPASS HEALTH INC                                                              | WENTZVILLE     | 6363328305 | 
| 1492630962  | DELTA AREA ECONOMIC OPPORTUNITY CORPORATION                                     | PORTAGEVILLE   | 5733793851 | 
| 1492630962  | FAMILY CARE HEALTH CENTERS                                                      | ST LOUIS       | 3144811615 | 
| 1492630962  | FAMILY HEALTH CENTER OF BOONE COUNTY                                            | COLUMBIA       | 5732142314 | 
| 1492630962  | ADVOCATES FOR A HEALTHY COMMUNITY INC DBA JORDAN VALLEY COMMUNITY HEALTH CENTER | SPRINGFIELD    | 4178310150 | 
```