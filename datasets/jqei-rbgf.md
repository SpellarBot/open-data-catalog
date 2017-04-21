# 2015 King County Diabetes Screenings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-king-county-diabetes-screenings-1d73d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/jqei-rbgf) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/jqei-rbgf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/jqei-rbgf/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | jqei-rbgf |
| Name | 2015 King County Diabetes Screenings |
| Attribution | King County employee health |
| Category | Employees |
| Created | 2014-11-24T19:01:56Z |
| Publication Date | 2014-11-24T21:01:59Z |

## Description

On-site diabetes screenings for King County employees

## Columns

```ls
| Included | Schema Type | Field Name    | Name       | Data Type | Render Type |
| ======== | =========== | ============= | ========== | ========= | =========== |
| Yes      | time        | start_time    | Start time | date      | date        |
| No       |             | end_time      | End time   | date      | date        |
| Yes      | series tag  | event_name    | Workplace  | text      | text        |
| Yes      | series tag  | location_name | Room       | text      | text        |
| Yes      | series tag  | url           | URL        | url       | url         |
```

## Time Field

```ls
Value = start_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_time
```

## Data Commands

```ls
series e:jqei-rbgf d:2015-01-28T22:00:00.000Z t:location_name="Classroom A" t:event_name="Atlantic/Central Base" m:row_number.jqei-rbgf=1

series e:jqei-rbgf d:2015-01-29T21:00:00.000Z t:location_name=Classroom t:event_name="East Base" m:row_number.jqei-rbgf=2

series e:jqei-rbgf d:2015-01-28T15:00:00.000Z t:location_name="Snoqualmie Conference Room" t:event_name="Snoqualmie Ridge" m:row_number.jqei-rbgf=3
```

## Meta Commands

```ls
metric m:row_number.jqei-rbgf p:long l:"Row Number"

entity e:jqei-rbgf l:"2015 King County Diabetes Screenings" t:attribution="King County employee health" t:url=https://data.kingcounty.gov/api/views/jqei-rbgf

property e:jqei-rbgf t:meta.view v:id=jqei-rbgf v:category=Employees v:attributionLink=http://www.kingcounty.gov/employees v:averageRating=0 v:name="2015 King County Diabetes Screenings" v:attribution="King County employee health"

property e:jqei-rbgf t:meta.view.license v:name="Public Domain"

property e:jqei-rbgf t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:jqei-rbgf t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| start_time | end_time   | event_name              | location_name              | url          | 
| ========== | ========== | ======================= | ========================== | ============ | 
| 1422482400 | 1422491400 | Atlantic/Central Base   | Classroom A                | [null, null] | 
| 1422565200 | 1422576000 | East Base               | Classroom                  | [null, null] | 
| 1422457200 | 1422468000 | Snoqualmie Ridge        | Snoqualmie Conference Room | [null, null] | 
| 1422568800 | 1422577800 | South Base              | Classroom                  | [null, null] | 
| 1421328600 | 1421343000 | South Base              | Classroom                  | [null, null] | 
| 1421933400 | 1421949600 | North Base              | Classroom                  | [null, null] | 
| 1421791200 | 1421800200 | North Base              | Classroom                  | [null, null] | 
| 1422365400 | 1422379800 | Atlantic/Central Base   | Classroom A                | [null, null] | 
| 1421348400 | 1421355600 | Elections               | 1st floor conference room  | [null, null] | 
| 1422036000 | 1422050400 | Regional Justice Center | Community Room             | [null, null] | 
```