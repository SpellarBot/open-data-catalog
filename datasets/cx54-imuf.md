# Incentive Housing Zone Applicants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/incentive-housing-zone-applicants) |
| Metadata | [Link](https://data.ct.gov/api/views/cx54-imuf) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/cx54-imuf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/cx54-imuf/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | cx54-imuf |
| Name | Incentive Housing Zone Applicants |
| Category | Housing and Development |
| Tags | incentive, housing, zone, zoning |
| Created | 2014-05-21T19:04:06Z |
| Publication Date | 2014-05-21T19:08:44Z |

## Description

This table identifies municipalities that received state funding under the Incentive Housing Zone Program (CGS Section 8-13 (m-x)).

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | municipality    | Municipality    | text      | text        |
| Yes      | numeric metric | amount_approved | Amount approved | money     | money       |
| Yes      | series tag     | status_of_ihz   | Status of IHZ * | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cx54-imuf d:2014-05-21T12:04:09.000Z t:municipality="Beacon Falls" m:amount_approved=50000

series e:cx54-imuf d:2014-05-21T12:04:09.000Z t:municipality=Berlin m:amount_approved=20000

series e:cx54-imuf d:2014-05-21T12:04:09.000Z t:municipality=Bolton m:amount_approved=20000
```

## Meta Commands

```ls
metric m:amount_approved p:integer l:"Amount approved" t:dataTypeName=money

entity e:cx54-imuf l:"Incentive Housing Zone Applicants" t:url=https://data.ct.gov/api/views/cx54-imuf

property e:cx54-imuf t:meta.view v:id=cx54-imuf v:category="Housing and Development" v:averageRating=0 v:name="Incentive Housing Zone Applicants"

property e:cx54-imuf t:meta.view.owner v:id=bdhz-s7cj v:screenName="Dimple Desai" v:displayName="Dimple Desai"

property e:cx54-imuf t:meta.view.tableauthor v:id=bdhz-s7cj v:screenName="Dimple Desai" v:roleName=editor v:displayName="Dimple Desai"
```

## Top Records

```ls
| :updated_at | municipality           | amount_approved | status_of_ihz                                                                                                                                                                                                   | 
| =========== | ====================== | =============== | =============================================================================================================================================================================================================== | 
| 1400673849  |                        |                 | * All the municipalities except identified below are at various stages starting from RFP for hiring consultants to conducting public informational meetings to drafting of IHZ regulations and design standards | 
| 1400673849  | Beacon Falls           | 50000           |                                                                                                                                                                                                                 | 
| 1400673849  | Berlin                 | 20000           |                                                                                                                                                                                                                 | 
| 1400673849  | Bolton                 | 20000           |                                                                                                                                                                                                                 | 
| 1400673849  | Branford               | 50000           |                                                                                                                                                                                                                 | 
| 1400673849  | Bridgeport             | 35000           |                                                                                                                                                                                                                 | 
| 1400673849  | Bristol                | 20000           |                                                                                                                                                                                                                 | 
| 1400673849  | Cannan (Falls Village) | 43000           | DOH provided final approval of their adopted IHZ                                                                                                                                                                | 
| 1400673849  | Canterbury             | 50000           |                                                                                                                                                                                                                 | 
| 1400673849  | Colchester             | 50000           |                                                                                                                                                                                                                 | 
```