# MARINE BOARD PERMITTED EVENTS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/marine-board-permitted-events-010e8) |
| Metadata | [Link](https://data.oregon.gov/api/views/7zxm-9fbf) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7zxm-9fbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7zxm-9fbf/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7zxm-9fbf |
| Name | MARINE BOARD PERMITTED EVENTS |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | events, regattas, races, boats, parades, tournaments, exhibits, log races, cruises, sponsored, marine |
| Created | 2011-09-22T20:13:52Z |
| Publication Date | 2017-04-14T18:16:26Z |

## Description

This is a list of all events permitted by the Oregon State Marine Board for the current year on Oregon waterways.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | time        | event_start_date | EVENT START DATE | calendar_date | calendar_date |
| No       |             | event_end_date   | EVENT END DATE   | calendar_date | calendar_date |
| Yes      | series tag  | location         | LOCATION         | text          | text          |
| Yes      | series tag  | event            | EVENT            | text          | text          |
| Yes      | series tag  | sponsor          | SPONSOR          | text          | text          |
| Yes      | series tag  | contact          | CONTACT          | text          | text          |
| Yes      | series tag  | permit_number    | PERMIT NUMBER    | text          | text          |
```

## Time Field

```ls
Value = event_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = event_end_date
```

## Data Commands

```ls
series e:7zxm-9fbf d:2013-02-01T06:00:00.000Z t:permit_number=13-002 t:location="Umpqua River" t:event="Fishing Derby" t:sponsor="Umpqua Fishery" t:contact="Sgt Withers" m:row_number.7zxm-9fbf=1

series e:7zxm-9fbf d:2013-01-31T08:00:00.000Z t:permit_number=13-001 t:location="Cooper Creek Reservoir" t:event="Fishery Derby-Kids Day" t:sponsor="Umpqua Fishery" t:contact="Sgt Withers" m:row_number.7zxm-9fbf=2

series e:7zxm-9fbf d:2013-08-03T05:30:00.000Z t:permit_number=13-004 t:location="Ten Mile Lake" t:event="Bass Tournament" t:sponsor="Ten Mile Bass Club" t:contact="Larry Robison" m:row_number.7zxm-9fbf=3
```

## Meta Commands

```ls
metric m:row_number.7zxm-9fbf p:long l:"Row Number"

entity e:7zxm-9fbf l:"MARINE BOARD PERMITTED EVENTS" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/7zxm-9fbf

property e:7zxm-9fbf t:meta.view v:id=7zxm-9fbf v:category=Recreation v:attributionLink=http://www.boatoregon.com/ v:averageRating=0 v:name="MARINE BOARD PERMITTED EVENTS" v:attribution="Oregon State Marine Board"

property e:7zxm-9fbf t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:7zxm-9fbf t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| event_start_date    | event_end_date      | location                     | event                          | sponsor                  | contact         | permit_number | 
| =================== | =================== | ============================ | ============================== | ======================== | =============== | ============= | 
| 2013-02-01T06:00:00 | 2013-02-02T18:00:00 | Umpqua River                 | Fishing Derby                  | Umpqua Fishery           | Sgt Withers     | 13-002        | 
| 2013-01-31T08:00:00 | 2013-01-31T14:00:00 | Cooper Creek Reservoir       | Fishery Derby-Kids Day         | Umpqua Fishery           | Sgt Withers     | 13-001        | 
| 2013-08-03T05:30:00 | 2013-08-04T15:30:00 | Ten Mile Lake                | Bass Tournament                | Ten Mile Bass Club       | Larry Robison   | 13-004        | 
| 2013-08-29T04:30:00 | 2013-09-01T18:00:00 | Pacific Ocean                | Slam'n Salmon Derby            | Port of Brookings        | Jean Day        | 13-003        | 
| 2013-02-09T10:30:00 | 2013-02-09T13:00:00 | Willamette River             | Barge Launch                   | Gunderson Marine         |                 | USCG          | 
| 2013-03-09T05:30:00 | 2013-03-09T16:00:00 | Ten Mile Lake                | Bass Tournament                | ABA North Tenmile        | Jim Gaither     | 13-005        | 
| 2013-02-23T04:30:00 | 2013-02-23T06:00:00 | Ten Mile Lake                | Frostbite Open-Bass Tournament | Emerald Bass Club        | Ed Hodges       | 13-006        | 
| 2013-05-18T04:30:00 | 2013-05-18T16:00:00 | Willamette River - Newberg   | Bass Tournament                | Cascade Bass Masters     | Joey McCain     | 13-010        | 
| 2013-04-12T16:00:00 | 2013-04-14T14:00:00 | Dexter Lake                  | Covered Bridge Regatta         | OR Association of Rowers | Lisa Bee-Wilson | 13-011        | 
| 2013-08-10T05:30:00 | 2013-08-10T16:00:00 | Columbia River - McNary Pool | Bass Tournament                | ABA North Hat Rock       | Jim Gaither     | 13-012        | 
```