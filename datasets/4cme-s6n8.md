# Equity and Social Justice Inter-Branch Team roster

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/equity-and-social-justice-inter-branch-team-roster-e70a2) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4cme-s6n8) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4cme-s6n8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4cme-s6n8/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4cme-s6n8 |
| Name | Equity and Social Justice Inter-Branch Team roster |
| Attribution | King County Executive |
| Category | Operations |
| Tags | esj |
| Created | 2014-05-21T19:31:15Z |
| Publication Date | 2015-02-11T01:27:23Z |

## Description

King County Equity and Social Justice Inter-Branch Team roster

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | department         | Department         | text      | text        |
| Yes      | series tag  | delegate_alternate | Delegate/Alternate | text      | text        |
| Yes      | series tag  | email              | Email              | email     | email       |
| Yes      | series tag  | telephone          | Telephone          | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4cme-s6n8 d:2015-02-10T17:27:08.000Z t:phone_number=206-205-9620 t:email=Pam.Jones@kingcounty.gov t:department="Adult & Juvenile Detention" t:delegate_alternate="Pam Jones" m:row_number.4cme-s6n8=1

series e:4cme-s6n8 d:2015-02-10T17:27:08.000Z t:phone_number=206-296-1034 t:email=Runette.Mitchell@kingcounty.gov t:department="Adult & Juvenile Detention" t:delegate_alternate="Runette Mitchell" m:row_number.4cme-s6n8=2

series e:4cme-s6n8 d:2015-02-10T17:27:08.000Z t:phone_number=206-296-5141 t:email=Phillip.Sit@kingcounty.gov t:department=Assessor t:delegate_alternate="Phillip Sit" m:row_number.4cme-s6n8=3
```

## Meta Commands

```ls
metric m:row_number.4cme-s6n8 p:long l:"Row Number"

entity e:4cme-s6n8 l:"Equity and Social Justice Inter-Branch Team roster" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/4cme-s6n8

property e:4cme-s6n8 t:meta.view v:id=4cme-s6n8 v:category=Operations v:attributionLink=http://www.kingcounty.gov/elected/exec v:averageRating=0 v:name="Equity and Social Justice Inter-Branch Team roster" v:attribution="King County Executive"

property e:4cme-s6n8 t:meta.view.license v:name="Public Domain"

property e:4cme-s6n8 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:4cme-s6n8 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | department                 | delegate_alternate | email                             | telephone            | 
| =========== | ========================== | ================== | ================================= | ==================== | 
| 1423589228  | Adult & Juvenile Detention | Pam Jones          | Pam.Jones@kingcounty.gov          | [206-205-9620, null] | 
| 1423589228  | Adult & Juvenile Detention | Runette Mitchell   | Runette.Mitchell@kingcounty.gov   | [206-296-1034, null] | 
| 1423589228  | Assessor                   | Phillip Sit        | Phillip.Sit@kingcounty.gov        | [206-296-5141, null] | 
| 1423589228  | Assessor                   | Rose Dotson        | Rose.Dotson@kingcounty.gov        | [206-296-5136, null] | 
| 1423589228  | Community & Human Services | Denise Rothleutner | Denise.Rothleutner@kingcounty.gov | [206-263-8988, null] | 
| 1423589228  | Community & Human Services | Marlon Brown       | Marlon.Brown@kingcounty.gov       | [206-263-8924, null] | 
| 1423589228  | Council                    | Amy Tsai           | Amy.Tsai@kingcounty.gov           | [206-296-1638, null] | 
| 1423589228  | Council                    | Cindy Domingo      | Cindy.Domingo@kingcounty.gov      | [206-296-0312, null] | 
| 1423589228  | Council                    | Larry Evans        | Larry.Evans@kingcounty.gov        | [206-296-0396, null] | 
| 1423589228  | Council                    | Mike Reed          | Mike.Reed@kingcounty.gov          | [206-296-1627, null] | 
```