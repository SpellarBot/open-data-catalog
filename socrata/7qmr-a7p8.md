# Healthcare Taskforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthcare-taskforce) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/7qmr-a7p8) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/7qmr-a7p8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/7qmr-a7p8/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 7qmr-a7p8 |
| Name | Healthcare Taskforce |
| Attribution | Mayor's Healthcare Taskforce |
| Category | Community Development |
| Tags | healthcare awareness, mayor yarber, healthcare, taskforce, healthy, city of jackson |
| Created | 2016-03-09T19:34:01Z |
| Publication Date | 2016-12-03T17:57:55Z |

## Description

This data tabulates the number of people touched at each event hosted by the Mayor's Healthcare Task-force. This data is updated within 72 hours of a Healthcare Task-force event.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name           | Data Type     | Render Type   |
| ======== | ============== | ============ | ============== | ============= | ============= |
| Yes      | series tag     | event_name   | Event Name     | text          | text          |
| Yes      | time           | meeting_date | Meeting Date   | calendar_date | calendar_date |
| Yes      | numeric metric | of_attendees | # of Attendees | number        | number        |
```

## Time Field

```ls
Value = meeting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7qmr-a7p8 d:2015-01-24T00:00:00.000Z t:event_name="Word and Worship" m:of_attendees=44

series e:7qmr-a7p8 d:2015-02-22T00:00:00.000Z t:event_name="Lynch Street CME Church" m:of_attendees=40

series e:7qmr-a7p8 d:2015-03-01T00:00:00.000Z t:event_name="Relevant Empowerment Church" m:of_attendees=51
```

## Meta Commands

```ls
metric m:of_attendees p:integer l:"# of Attendees" t:dataTypeName=number

entity e:7qmr-a7p8 l:"Healthcare Taskforce" t:attribution="Mayor's Healthcare Taskforce" t:url=https://data.jacksonms.gov/api/views/7qmr-a7p8

property e:7qmr-a7p8 t:meta.view v:id=7qmr-a7p8 v:category="Community Development" v:attributionLink=http://www.mayorstaskforce.com v:averageRating=0 v:name="Healthcare Taskforce" v:attribution="Mayor's Healthcare Taskforce"

property e:7qmr-a7p8 t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:7qmr-a7p8 t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| event_name                   | meeting_date        | of_attendees | 
| ============================ | =================== | ============ | 
| Word and Worship             | 2015-01-24T00:00:00 | 44           | 
| Lynch Street CME Church      | 2015-02-22T00:00:00 | 40           | 
| Relevant Empowerment Church  | 2015-03-01T00:00:00 | 51           | 
| Revival Center Church        | 2015-03-08T00:00:00 | 34           | 
| New Horizon Church           | 2015-03-15T00:00:00 | 53           | 
| Cannery Creek Baptist Church | 2015-03-22T00:00:00 | 34           | 
| Grove Baptist Church         | 2015-03-29T00:00:00 | 34           | 
| College Hill MB Church       | 2015-05-17T00:00:00 | 42           | 
| Progressive MB Church        | 2015-05-24T00:00:00 | 53           | 
| Tabernacle of Praise Church  | 2015-09-20T00:00:00 | 50           | 
```