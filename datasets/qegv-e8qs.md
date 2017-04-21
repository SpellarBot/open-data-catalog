# Maryland Department of the Environment GOPI Calendar Year Performance Measure Dashboard

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-department-of-the-environment-gopi-calendar-year-performance-measure-dashboard) |
| Metadata | [Link](https://data.maryland.gov/api/views/qegv-e8qs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qegv-e8qs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qegv-e8qs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qegv-e8qs |
| Name | Maryland Department of the Environment GOPI Calendar Year Performance Measure Dashboard |
| Attribution | Maryland Department of the Environment |
| Category | Energy and Environment |
| Tags | performance, environment, lead |
| Created | 2016-09-27T20:50:33Z |
| Publication Date | 2016-10-25T19:35:40Z |

## Description

This data set reports the performance measures for the Maryland Department of the Environment that are being reported to the Governor's Office of Performance Improvement.  These measures are updated annually for the calendar year.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                         | Name                                                                                  | Data Type     | Render Type   |
| ======== | ============== | ================================================================================== | ===================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                               | Date                                                                                  | calendar_date | calendar_date |
| No       |                | year                                                                               | Year                                                                                  | number        | number        |
| Yes      | numeric metric | number_of_children_under_six_years_of_age_with_elevated_blood_lead_levels_10_ug_dl | Number of children under six years of age with elevated blood lead levels (?10 ug/dl) | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:qegv-e8qs d:2010-12-31T00:00:00.000Z m:number_of_children_under_six_years_of_age_with_elevated_blood_lead_levels_10_ug_dl=531

series e:qegv-e8qs d:2011-12-31T00:00:00.000Z m:number_of_children_under_six_years_of_age_with_elevated_blood_lead_levels_10_ug_dl=452

series e:qegv-e8qs d:2012-12-31T00:00:00.000Z m:number_of_children_under_six_years_of_age_with_elevated_blood_lead_levels_10_ug_dl=364
```

## Meta Commands

```ls
metric m:number_of_children_under_six_years_of_age_with_elevated_blood_lead_levels_10_ug_dl p:integer l:"Number of children under six years of age with elevated blood lead levels (?10 ug/dl)" t:dataTypeName=number

entity e:qegv-e8qs l:"Maryland Department of the Environment GOPI Calendar Year Performance Measure Dashboard" t:attribution="Maryland Department of the Environment" t:url=https://data.maryland.gov/api/views/qegv-e8qs

property e:qegv-e8qs t:meta.view v:id=qegv-e8qs v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Department of the Environment GOPI Calendar Year Performance Measure Dashboard" v:attribution="Maryland Department of the Environment"

property e:qegv-e8qs t:meta.view.license v:name="Public Domain"

property e:qegv-e8qs t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:qegv-e8qs t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | year | number_of_children_under_six_years_of_age_with_elevated_blood_lead_levels_10_ug_dl | 
| =================== | ==== | ================================================================================== | 
| 2010-12-31T00:00:00 | 2010 | 531                                                                                | 
| 2011-12-31T00:00:00 | 2011 | 452                                                                                | 
| 2012-12-31T00:00:00 | 2012 | 364                                                                                | 
| 2013-12-31T00:00:00 | 2013 | 371                                                                                | 
| 2014-12-31T00:00:00 | 2014 | 355                                                                                | 
| 2015-12-31T00:00:00 | 2015 | 377                                                                                | 
```