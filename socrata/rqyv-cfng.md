# Waterbodies In Rank Order

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waterbodies-in-rank-order-15a71) |
| Metadata | [Link](https://data.oregon.gov/api/views/rqyv-cfng) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rqyv-cfng/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rqyv-cfng/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rqyv-cfng |
| Name | Waterbodies In Rank Order |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | waterbody, fishing, hunting, cruising, sailing, activities, trips, uses, marine, boat, boating, boats, lake, reservoir, river, county, days |
| Created | 2011-10-31T15:35:46Z |
| Publication Date | 2011-10-31T15:43:29Z |

## Description

Triennial Survey Results -2008

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | name_of_water_body | NAME OF WATER BODY | text      | text        |
| Yes      | numeric metric | days               | DAYS               | number    | number      |
| Yes      | numeric metric | trips              | TRIPS              | number    | number      |
| Yes      | numeric metric | activity_days      | ACTIVITY DAYS      | number    | number      |
| Yes      | numeric metric | fishing            | FISHING            | number    | number      |
| Yes      | numeric metric | sailing            | SAILING            | number    | number      |
| Yes      | numeric metric | pwc                | PWC                | number    | number      |
| Yes      | numeric metric | waterskiing        | WATERSKIING        | number    | number      |
| Yes      | numeric metric | cruising           | CRUISING           | number    | number      |
| Yes      | numeric metric | hunting            | HUNTING            | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rqyv-cfng d:2011-10-31T08:36:08.000Z t:name_of_water_body="Columbia River" m:cruising=91071 m:pwc=9239 m:days=410640 m:trips=307665 m:sailing=30131 m:hunting=8071 m:fishing=231955 m:activity_days=382949 m:waterskiing=12482

series e:rqyv-cfng d:2011-10-31T08:36:08.000Z t:name_of_water_body="Willamette River" m:cruising=104829 m:pwc=11730 m:days=374560 m:trips=246978 m:sailing=5007 m:hunting=3965 m:fishing=210020 m:activity_days=383976 m:waterskiing=48425

series e:rqyv-cfng d:2011-10-31T08:36:08.000Z t:name_of_water_body="Emigrant Lake" m:cruising=779 m:pwc=533 m:days=153278 m:trips=10360 m:sailing=0 m:hunting=0 m:fishing=810 m:activity_days=10718 m:waterskiing=8596
```

## Meta Commands

```ls
metric m:days p:integer l:DAYS t:dataTypeName=number

metric m:trips p:integer l:TRIPS t:dataTypeName=number

metric m:activity_days p:integer l:"ACTIVITY DAYS" t:dataTypeName=number

metric m:fishing p:integer l:FISHING t:dataTypeName=number

metric m:sailing p:integer l:SAILING t:dataTypeName=number

metric m:pwc p:integer l:PWC t:dataTypeName=number

metric m:waterskiing p:integer l:WATERSKIING t:dataTypeName=number

metric m:cruising p:integer l:CRUISING t:dataTypeName=number

metric m:hunting p:integer l:HUNTING t:dataTypeName=number

entity e:rqyv-cfng l:"Waterbodies In Rank Order" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/rqyv-cfng

property e:rqyv-cfng t:meta.view v:id=rqyv-cfng v:category=Recreation v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="Waterbodies In Rank Order" v:attribution="Oregon State Marine Board"

property e:rqyv-cfng t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:rqyv-cfng t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | name_of_water_body     | days   | trips  | activity_days | fishing | sailing | pwc   | waterskiing | cruising | hunting | 
| =========== | ====================== | ====== | ====== | ============= | ======= | ======= | ===== | =========== | ======== | ======= | 
| 1320050168  | Columbia River         | 410640 | 307665 | 382949        | 231955  | 30131   | 9239  | 12482       | 91071    | 8071    | 
| 1320050168  | Willamette River       | 374560 | 246978 | 383976        | 210020  | 5007    | 11730 | 48425       | 104829   | 3965    | 
| 1320050168  | Emigrant Lake          | 153278 | 10360  | 10718         | 810     | 0       | 533   | 8596        | 779      | 0       | 
| 1320050168  | Detroit Reservoir/Lake | 90452  | 44889  | 106995        | 19007   | 15974   | 7021  | 21064       | 43816    | 113     | 
| 1320050168  | Pacific Ocean          | 76960  | 57820  | 72084         | 67881   | 29      | 1655  | 0           | 2519     | 0       | 
| 1320050168  | Lake Billy Chinook     | 72658  | 54088  | 78973         | 35833   | 0       | 2692  | 20197       | 20239    | 12      | 
| 1320050168  | Rogue River            | 61788  | 60734  | 26962         | 21743   | 0       | 27    | 0           | 5191     | 0       | 
| 1320050168  | No Response            | 51090  | 43303  | 50758         | 37267   | 0       | 469   | 5052        | 3769     | 4200    | 
| 1320050168  | Fern Ridge Reservoir   | 48826  | 20494  | 45918         | 3813    | 29508   | 0     | 9488        | 3109     | 0       | 
| 1320050168  | Multnomah Channel      | 42452  | 24970  | 32583         | 20689   | 0       | 0     | 847         | 11047    | 0       | 
```