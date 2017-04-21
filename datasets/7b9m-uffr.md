# Committee to End Homelessness Governing Board

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/committee-to-end-homelessness-governing-board) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/7b9m-uffr) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/7b9m-uffr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/7b9m-uffr/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 7b9m-uffr |
| Name | Committee to End Homelessness Governing Board |
| Attribution | Committee to End Homelessness |
| Category | Human Services |
| Tags | homelessness |
| Created | 2015-02-03T00:22:04Z |
| Publication Date | 2015-02-03T00:23:45Z |

## Description

The Governing Board provides high-level oversight to the Committee to End Homelessness. It is made up of more than 20 top level community leaders and two individuals who have experienced homelessness. The Governing Board helps  sustain the vision and leadership of the plan, and guides planning, coordinates current funding, and works to create additional resources.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | representation_category     | Representation Category     | text      | text        |
| Yes      | series tag  | member_name_and_affiliation | Member Name and Affiliation | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7b9m-uffr d:2015-02-02T16:22:06.000Z t:member_name_and_affiliation="Ed Murray (Mayor)" t:representation_category="City of Seattle Government" m:row_number.7b9m-uffr=1

series e:7b9m-uffr d:2015-02-02T16:22:06.000Z t:member_name_and_affiliation="Kathy Lambert (Councilmember)" t:representation_category="King County Council" m:row_number.7b9m-uffr=2

series e:7b9m-uffr d:2015-02-02T16:22:06.000Z t:member_name_and_affiliation="Joseph McDermott (Councilmember)" t:representation_category="King County Council" m:row_number.7b9m-uffr=3
```

## Meta Commands

```ls
metric m:row_number.7b9m-uffr p:long l:"Row Number"

entity e:7b9m-uffr l:"Committee to End Homelessness Governing Board" t:attribution="Committee to End Homelessness" t:url=https://data.kingcounty.gov/api/views/7b9m-uffr

property e:7b9m-uffr t:meta.view v:id=7b9m-uffr v:category="Human Services" v:attributionLink=http://www.cehkc.org v:averageRating=0 v:name="Committee to End Homelessness Governing Board" v:attribution="Committee to End Homelessness"

property e:7b9m-uffr t:meta.view.license v:name="Public Domain"

property e:7b9m-uffr t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:7b9m-uffr t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | representation_category    | member_name_and_affiliation                 | 
| =========== | ========================== | =========================================== | 
| 1422894126  | City of Seattle Government | Ed Murray (Mayor)                           | 
| 1422894126  | King County Council        | Kathy Lambert (Councilmember)               | 
| 1422894126  | King County Council        | Joseph McDermott (Councilmember)            | 
| 1422894126  | Seattle City Council       | Sally Clark (Councilmember)                 | 
| 1422894126  | Bellevue City Council      | John Chelminiak (Councilmember)             | 
| 1422894126  | Suburban Government        | Lydia Assefa-Dawson                         | 
| 1422894126  | Suburban Government        | Doreen Marchione, Kirkland (Deputy Mayor)   | 
| 1422894126  | Funders/Foundations        | Jon Fine (United Way of King County)        | 
| 1422894126  | Funders/Foundations        | David Bley (Bill & Melinda Gates Foundation | 
| 1422894126  | Business Community         | Dan Brettler (Car Toys, Inc.)               | 
```