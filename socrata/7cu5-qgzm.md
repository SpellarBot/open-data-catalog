# SSMMA Lemont Current Vacant Property Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-lemont-current-vacant-property-listing-49b2d) |
| Metadata | [Link](https://data.illinois.gov/api/views/7cu5-qgzm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7cu5-qgzm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7cu5-qgzm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7cu5-qgzm |
| Name | SSMMA Lemont Current Vacant Property Listing |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | lemont, vacant property, housing, planning |
| Created | 2012-11-27T17:24:49Z |
| Publication Date | 2012-11-27T19:18:04Z |

## Description

This dataset is the current vacant property listing for the Village of Lemont

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | pin         | PIN         | text      | text        |
| Yes      | series tag     | owner_agent | Owner/Agent | text      | text        |
| Yes      | series tag     | contact     | Contact #   | text      | text        |
| Yes      | numeric metric | location_1  | Location 1  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7cu5-qgzm d:2012-11-27T09:24:50.000Z t:pin=22-30-207-013-0000 t:owner_agent=FNMA t:contact=972-773-4663 m:location_1=11

series e:7cu5-qgzm d:2012-11-27T09:24:50.000Z t:pin=22-30-205-010-0000 t:owner_agent="Wells Fargo" t:contact=414-214-4383 m:location_1=14

series e:7cu5-qgzm d:2012-11-27T09:24:50.000Z t:pin=22-29-234-021-0000 t:owner_agent="One West Bank/LPS" t:contact=877-841-8572 m:location_1=21
```

## Meta Commands

```ls
metric m:location_1 p:integer l:"Location 1" t:dataTypeName=number

entity e:7cu5-qgzm l:"SSMMA Lemont Current Vacant Property Listing" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/7cu5-qgzm

property e:7cu5-qgzm t:meta.view v:id=7cu5-qgzm v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Lemont Current Vacant Property Listing" v:attribution="South Suburban Mayors and Managers Association"

property e:7cu5-qgzm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7cu5-qgzm t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:7cu5-qgzm t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | pin                | owner_agent                  | contact      | location_1 | 
| =========== | ================== | ============================ | ============ | ========== | 
| 1354008290  | 22-30-207-013-0000 | FNMA                         | 972-773-4663 | 11         | 
| 1354008290  | 22-30-205-010-0000 | Wells Fargo                  | 414-214-4383 | 14         | 
| 1354008290  | 22-29-234-021-0000 | One West Bank/LPS            | 877-841-8572 | 21         | 
| 1354008290  | 22-34-104-022-0000 | Norman Sobol                 | 630-696-0780 | 22         | 
| 1354008290  | 22-31-203-022-0000 | Wells Fargo                  | 414-214-4383 | 61         | 
| 1354008290  | 22-34-212-002-0000 | Sam Daleh                    |              | 89         | 
| 1354008290  | 22-34-212-013-0000 | PNC Mortgage/Safeguard       | 877-340-0060 | 111        | 
| 1354008290  | 22-29-225-006-0000 | Nicole Evol                  | 630-739-7912 | 212        | 
| 1354008290  | 22-20-319-011-0000 | Wells Fargo                  | 414-214-4383 | 213        | 
| 1354008290  | 22-29-225-008-0000 | MidFirst Bank/MCS Properties |              | 216        | 
```