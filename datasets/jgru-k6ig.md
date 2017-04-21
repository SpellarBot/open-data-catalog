# Youth Initiatives Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youth-initiatives-summary) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/jgru-k6ig) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/jgru-k6ig/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/jgru-k6ig/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | jgru-k6ig |
| Name | Youth Initiatives Summary |
| Attribution | City of Jackson |
| Category | Schools and Education |
| Tags | youth, education, i need you to make it, involvement, engagement |
| Created | 2016-03-09T23:47:59Z |
| Publication Date | 2016-03-09T23:49:20Z |

## Description

This data compiles events, partnerships, and participation that flow through the Youth Initiatives Division of the Mayor's Office. This information is updated within 72 hours of an event.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ====================================== | ============= | ============= |
| Yes      | series tag     | events_and_partnerships              | Events and Partnerships                | text          | text          |
| Yes      | time           | as_of_date                           | As of Date                             | calendar_date | calendar_date |
| Yes      | numeric metric | of_youth_participation               | # of Youth Participation               | number        | number        |
| Yes      | numeric metric | of_service_projects_directly_related | # of Service Projects Directly Related | number        | number        |
| Yes      | numeric metric | of_meetings                          | # of Meetings                          | number        | number        |
```

## Time Field

```ls
Value = as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jgru-k6ig d:2016-01-05T00:00:00.000Z t:events_and_partnerships="Mayor's Youth Council" m:of_service_projects_directly_related=7 m:of_meetings=11 m:of_youth_participation=34

series e:jgru-k6ig d:2016-03-05T00:00:00.000Z t:events_and_partnerships="Mayor's School Tour" m:of_service_projects_directly_related=0 m:of_meetings=6 m:of_youth_participation=1300

series e:jgru-k6ig d:2015-10-15T00:00:00.000Z t:events_and_partnerships="Back to School Event" m:of_service_projects_directly_related=1 m:of_meetings=1 m:of_youth_participation=5023
```

## Meta Commands

```ls
metric m:of_youth_participation p:integer l:"# of Youth Participation" t:dataTypeName=number

metric m:of_service_projects_directly_related p:integer l:"# of Service Projects Directly Related" t:dataTypeName=number

metric m:of_meetings p:integer l:"# of Meetings" t:dataTypeName=number

entity e:jgru-k6ig l:"Youth Initiatives Summary" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/jgru-k6ig

property e:jgru-k6ig t:meta.view v:id=jgru-k6ig v:category="Schools and Education" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Youth Initiatives Summary" v:attribution="City of Jackson"

property e:jgru-k6ig t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:jgru-k6ig t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| events_and_partnerships          | as_of_date          | of_youth_participation | of_service_projects_directly_related | of_meetings | 
| ================================ | =================== | ====================== | ==================================== | =========== | 
| Mayor's Youth Council            | 2016-01-05T00:00:00 | 34                     | 7                                    | 11          | 
| Mayor's School Tour              | 2016-03-05T00:00:00 | 1300                   | 0                                    | 6           | 
| Back to School Event             | 2015-10-15T00:00:00 | 5023                   | 1                                    | 1           | 
| TechJXN                          | 2015-05-30T00:00:00 | 312                    | 9                                    |             | 
| Alignment Jackson                | 2016-02-01T00:00:00 | 2200                   | 20                                   | 50          | 
| Poindexter Elementary            | 2016-01-01T00:00:00 | 500                    | 0                                    | 5           | 
| JPS Summer Reading Program       | 2015-10-01T00:00:00 | 30000                  | 0                                    | 5           | 
| A-Team Partnership               | 2016-02-28T00:00:00 | 25                     | 1                                    | 8           | 
| Operation Shoestring Partnership | 2016-02-25T00:00:00 | 50                     | 0                                    | 0           | 
```