# CT Department of Children and Families Offices and Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-department-of-children-and-families-offices-and-facilities) |
| Metadata | [Link](https://data.ct.gov/api/views/nhvj-awym) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nhvj-awym/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nhvj-awym/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nhvj-awym |
| Name | CT Department of Children and Families Offices and Facilities |
| Attribution | DCF Office for Research and Evaluation; Fred North, Program Manager |
| Category | Health and Human Services |
| Tags | dcf, offices, facilities |
| Created | 2014-06-23T20:11:09Z |
| Publication Date | 2014-06-24T18:36:53Z |

## Description

Location, telephone and parking information for all DCF offices and facilities as of 7/1/2014.  This file does not include any of our licensed foster homes or congregate care facilities, or other contracted services provider locations.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | type        | Record Type | text      | text        |
| Yes      | series tag  | region      | DCF Region  | text      | text        |
| Yes      | series tag  | name        | Name        | text      | text        |
| Yes      | series tag  | main_phone  | Main Phone  | text      | text        |
| Yes      | series tag  | fax         | Fax         | text      | text        |
| Yes      | series tag  | tdd1        | TDD1        | text      | text        |
| Yes      | series tag  | tdd2        | TDD2        | text      | text        |
| Yes      | series tag  | parking     | Parking     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nhvj-awym d:2014-06-23T13:11:23.000Z t:region="Region 4" t:parking=On-Site t:fax="(860) 533-3750" t:main_phone="(860) 533-3600" t:name="Manchester Area Office" t:tdd2="(800) 315-4415" t:tdd1="(860) 533-3896" t:type="Area Office" m:row_number.nhvj-awym=1

series e:nhvj-awym d:2014-06-23T13:11:23.000Z t:region="Region 1" t:parking="On-Site (Behind building)" t:fax="(203) 853-3821" t:main_phone="(203) 899-1400" t:name="Norwalk Area Office" t:tdd1="(203) 899-1491" t:type="Area Office" m:row_number.nhvj-awym=2

series e:nhvj-awym d:2014-06-23T13:11:23.000Z t:region=Statewide t:parking="Grove Street Municipal Garage-Upper Level Only" t:main_phone="(203) 427-2828" t:name="Central Office Satellite" t:type="State Office" m:row_number.nhvj-awym=3
```

## Meta Commands

```ls
metric m:row_number.nhvj-awym p:long l:"Row Number"

entity e:nhvj-awym l:"CT Department of Children and Families Offices and Facilities" t:attribution="DCF Office for Research and Evaluation; Fred North, Program Manager" t:url=https://data.ct.gov/api/views/nhvj-awym

property e:nhvj-awym t:meta.view v:id=nhvj-awym v:category="Health and Human Services" v:averageRating=0 v:name="CT Department of Children and Families Offices and Facilities" v:attribution="DCF Office for Research and Evaluation; Fred North, Program Manager"

property e:nhvj-awym t:meta.view.license v:name="Public Domain"

property e:nhvj-awym t:meta.view.owner v:id=hd87-ziyn v:screenName="Fred North" v:displayName="Fred North"

property e:nhvj-awym t:meta.view.tableauthor v:id=hd87-ziyn v:screenName="Fred North" v:roleName=editor v:displayName="Fred North"
```

## Top Records

```ls
| :updated_at | type         | region    | name                                                              | main_phone     | fax            | tdd1           | tdd2           | parking                                        | 
| =========== | ============ | ========= | ================================================================= | ============== | ============== | ============== | ============== | ============================================== | 
| 1403529083  | Area Office  | Region 4  | Manchester Area Office                                            | (860) 533-3600 | (860) 533-3750 | (860) 533-3896 | (800) 315-4415 | On-Site                                        | 
| 1403529083  | Area Office  | Region 1  | Norwalk Area Office                                               | (203) 899-1400 | (203) 853-3821 | (203) 899-1491 |                | On-Site (Behind building)                      | 
| 1403529083  | State Office | Statewide | Central Office Satellite                                          | (203) 427-2828 |                |                |                | Grove Street Municipal Garage-Upper Level Only | 
| 1403529083  | Area Office  | Region 5  | Torrington Area Office                                            | (860) 496-5700 | (860) 496-5746 | (860) 496-5798 |                | On-Site                                        | 
| 1403529083  | Residential  | Statewide | Albert J. Solnit South Campus (Psychiatric Residential Treatment) | (860) 704-4000 | (860) 704-4123 |                |                | On-Site                                        | 
| 1403529083  | Area Office  | Region 4  | Hartford Area Office                                              | (860) 418-8000 | (860) 418-8327 | (860) 418-8366 | (800) 315-4082 | On-Site (Limited)                              | 
| 1403529083  | Area Office  | Region 5  | Danbury Area Office                                               | (203) 207-5100 | (203) 207-5170 | (203) 748-8325 |                | On-Site                                        | 
| 1403529083  | Area Office  | Region 1  | Bridgeport Area Office                                            | (203) 384-5300 | (203) 384-5307 | (203) 384-5399 |                | Metered On-Street                              | 
| 1403529083  | Residential  | Statewide | Albert J. Solnit North Campus (Psychiatric Residential Treatment) | (860) 292-4000 | (860) 292-4030 |                |                | On-Site                                        | 
| 1403529083  | State Office | Statewide | Central Office Training Academy                                   | (860) 550-6418 |                |                |                | See training announcements for instructions    | 
```