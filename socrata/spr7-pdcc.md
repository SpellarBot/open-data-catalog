# Citizen Participation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citizen-participation) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/spr7-pdcc) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/spr7-pdcc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/spr7-pdcc/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | spr7-pdcc |
| Name | Citizen Participation |
| Attribution | City of Jackson |
| Category | Community Development |
| Tags | citizen participation, city events, city of jackson, entertainment, culture, bold new city, vibrant |
| Created | 2016-03-07T21:23:34Z |
| Publication Date | 2016-03-07T21:24:14Z |

## Description

This dataset measures citizen participation at each City sponsored event. It is updated within 72 hours of a City sponsored major event.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name           | Data Type     | Render Type   |
| ======== | ============== | ============= | ============== | ============= | ============= |
| Yes      | series tag     | event         | Event          | text          | text          |
| Yes      | numeric metric | fy14_15       | FY14-15        | number        | number        |
| Yes      | numeric metric | fy15_16       | FY15-16        | number        | number        |
| Yes      | numeric metric | increase      | Increase       | percent       | percent       |
| Yes      | time           | date_received | Date Received: | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:spr7-pdcc d:2015-05-25T00:00:00.000Z t:event="Family Day on The Green" m:fy15_16=1500 m:fy14_15=1200 m:increase=20

series e:spr7-pdcc d:2015-06-20T00:00:00.000Z t:event="Juneteenth Jackson" m:fy15_16=600 m:fy14_15=450 m:increase=25

series e:spr7-pdcc d:2015-06-27T00:00:00.000Z t:event="We Are Jackson Day at the Zoo" m:fy15_16=323 m:fy14_15=250 m:increase=23
```

## Meta Commands

```ls
metric m:fy14_15 p:integer l:FY14-15 t:dataTypeName=number

metric m:fy15_16 p:integer l:FY15-16 t:dataTypeName=number

metric m:increase p:integer l:Increase t:dataTypeName=percent

entity e:spr7-pdcc l:"Citizen Participation" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/spr7-pdcc

property e:spr7-pdcc t:meta.view v:id=spr7-pdcc v:category="Community Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Citizen Participation" v:attribution="City of Jackson"

property e:spr7-pdcc t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:spr7-pdcc t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| event                         | fy14_15 | fy15_16 | increase | date_received       | 
| ============================= | ======= | ======= | ======== | =================== | 
| Family Day on The Green       | 1200    | 1500    | 20       | 2015-05-25T00:00:00 | 
| Juneteenth Jackson            | 450     | 600     | 25       | 2015-06-20T00:00:00 | 
| We Are Jackson Day at the Zoo | 250     | 323     | 23       | 2015-06-27T00:00:00 | 
| Red, White, and Jackson       | 776     | 1063    | 27       | 2015-07-02T00:00:00 | 
| We are Jackson Weekend        | 1795    | 2513    | 29       | 2015-10-11T00:00:00 | 
| Jackson Indie Week            | 2315    | 4121    | 44       | 2016-01-17T00:00:00 | 
| ALL YEAR                      | 6786    | 10120   | 28       | 2016-03-30T00:00:00 | 
```