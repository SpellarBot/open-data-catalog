# Compensation-contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/compensation-contacts-b24aa) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/t92r-wdyh) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/t92r-wdyh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/t92r-wdyh/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | t92r-wdyh |
| Name | Compensation-contacts |
| Attribution | King County Human Resources |
| Category | Operations |
| Tags | compensation, classification, ccs |
| Created | 2014-12-09T23:13:26Z |
| Publication Date | 2014-12-10T01:30:44Z |

## Description

Contact information for King County compensation and classification staff members

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                               | Data Type | Render Type |
| ======== | =========== | ================================= | ================================== | ========= | =========== |
| No       | time        | :updated_at                       | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | department_office                 | Department/Office                  | text      | text        |
| Yes      | series tag  | ccs_contact                       | Compensation Analyst               | text      | text        |
| Yes      | series tag  | email                             | Email                              | email     | email       |
| Yes      | series tag  | telephone                         | Telephone                          | phone     | phone       |
| Yes      | series tag  | sr_compensation_analyst           | Sr. Compensation Analyst           | text      | text        |
| Yes      | series tag  | sr_compensation_analyst_email     | Sr. Compensation Analyst Email     | email     | email       |
| Yes      | series tag  | sr_compensation_analyst_telephone | Sr. Compensation Analyst Telephone | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t92r-wdyh d:2014-12-09T17:24:12.000Z t:sr_compensation_analyst_email=meredith.merriman@kingcounty.gov t:phone_number=206-477-3292 t:email=Steve.Aspiras@kingcounty.gov t:sr_compensation_analyst="Meredith Merriman" t:ccs_contact="Aspiras, Steve" t:department_office="Adult and Juvenile Detention" m:row_number.t92r-wdyh=1

series e:t92r-wdyh d:2014-12-09T17:27:18.000Z t:sr_compensation_analyst_email=meredith.merriman@kingcounty.gov t:phone_number=206-477-3292 t:email=Steve.Aspiras@kingcounty.gov t:sr_compensation_analyst="Meredith Merriman" t:ccs_contact="Aspiras, Steve" t:department_office="District Court" m:row_number.t92r-wdyh=2

series e:t92r-wdyh d:2014-12-09T17:27:23.000Z t:sr_compensation_analyst_email=meredith.merriman@kingcounty.gov t:phone_number=206-477-3292 t:email=Steve.Aspiras@kingcounty.gov t:sr_compensation_analyst="Meredith Merriman" t:ccs_contact="Aspiras, Steve" t:department_office="Judicial Administration" m:row_number.t92r-wdyh=3
```

## Meta Commands

```ls
metric m:row_number.t92r-wdyh p:long l:"Row Number"

entity e:t92r-wdyh l:Compensation-contacts t:attribution="King County Human Resources" t:url=https://data.kingcounty.gov/api/views/t92r-wdyh

property e:t92r-wdyh t:meta.view v:id=t92r-wdyh v:category=Operations v:attributionLink=http://www.kingcounty.gov/employees v:averageRating=0 v:name=Compensation-contacts v:attribution="King County Human Resources"

property e:t92r-wdyh t:meta.view.license v:name="Public Domain"

property e:t92r-wdyh t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:t92r-wdyh t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | department_office                   | ccs_contact    | email                        | telephone            | sr_compensation_analyst | sr_compensation_analyst_email    | sr_compensation_analyst_telephone | 
| =========== | =================================== | ============== | ============================ | ==================== | ======================= | ================================ | ================================= | 
| 1418145852  | Adult and Juvenile Detention        | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146038  | District Court                      | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146043  | Judicial Administration             | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146051  | Permitting and Environmental Review | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146057  | Prosecuting Attorney                | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146059  | Public Defense                      | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146061  | Sheriff                             | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146063  | Superior Court                      | Aspiras, Steve | Steve.Aspiras@kingcounty.gov | [206-477-3253, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146065  | Council                             | Farrell, Susie | Susie.Farrell@kingcounty.gov | [206-477-3254, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
| 1418146067  | Executive (Office of the)           | Farrell, Susie | Susie.Farrell@kingcounty.gov | [206-477-3254, null] | Meredith Merriman       | meredith.merriman@kingcounty.gov | [206-477-3292, null]              | 
```