# Annual Crime 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-crime-2014) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7g8v-xxja) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7g8v-xxja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7g8v-xxja/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7g8v-xxja |
| Name | Annual Crime 2014 |
| Created | 2015-10-29T14:46:56Z |
| Publication Date | 2015-10-29T16:03:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ===================================== | ============= | ============= |
| Yes      | numeric metric | go_primary_key                        | GO Primary Key                        | number        | number        |
| Yes      | series tag     | council_district                      | Council District                      | text          | number        |
| Yes      | series tag     | go_highest_offense_desc               | GO Highest Offense Desc               | text          | text          |
| Yes      | series tag     | highest_nibrs_ucr_offense_description | Highest NIBRS/UCR Offense Description | text          | text          |
| Yes      | time           | go_report_date                        | GO Report Date                        | calendar_date | calendar_date |
| Yes      | series tag     | go_location                           | GO Location                           | text          | text          |
| Yes      | series tag     | clearance_status                      | Clearance Status                      | text          | text          |
| No       |                | clearance_date                        | Clearance Date                        | calendar_date | calendar_date |
| Yes      | series tag     | go_district                           | GO District                           | text          | text          |
| Yes      | series tag     | go_location_zip                       | GO Location Zip                       | text          | number        |
| Yes      | numeric metric | go_census_tract                       | GO Census Tract                       | number        | number        |
| Yes      | numeric metric | go_x_coordinate                       | GO X Coordinate                       | number        | number        |
| Yes      | numeric metric | go_y_coordinate                       | GO Y Coordinate                       | number        | number        |
```

## Time Field

```ls
Value = go_report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = clearance_date
```

## Data Commands

```ls
series e:7g8v-xxja d:2014-04-17T00:00:00.000Z t:go_location_zip=78753 t:go_highest_offense_desc="AGG ROBBERY/DEADLY WEAPON" t:go_location="12151 N IH 35 SVRD NB" t:council_district=1 t:highest_nibrs_ucr_offense_description=Robbery t:clearance_status=N t:go_district=E m:go_primary_key=20141061920 m:go_y_coordinate=10117220 m:go_x_coordinate=3135985 m:go_census_tract=18.35

series e:7g8v-xxja d:2014-04-25T00:00:00.000Z t:go_location_zip=78723 t:go_highest_offense_desc="ROBBERY BY ASSAULT" t:go_location="3300 BLOCK ROCKHURST LN" t:council_district=1 t:highest_nibrs_ucr_offense_description=Robbery t:clearance_status=N t:go_district=I m:go_primary_key=20141150937 m:go_y_coordinate=10087946 m:go_x_coordinate=3137985 m:go_census_tract=21.13

series e:7g8v-xxja d:2014-05-11T00:00:00.000Z t:go_location_zip=78702 t:go_highest_offense_desc="ROBBERY BY THREAT" t:go_location="E 7TH ST / CHICON ST" t:council_district=3 t:highest_nibrs_ucr_offense_description=Robbery t:clearance_status=N t:go_district=C m:go_primary_key=20141310316 m:go_y_coordinate=10068910 m:go_x_coordinate=3120890 m:go_census_tract=9.02
```

## Meta Commands

```ls
metric m:go_primary_key p:long l:"GO Primary Key" t:dataTypeName=number

metric m:go_census_tract p:double l:"GO Census Tract" t:dataTypeName=number

metric m:go_x_coordinate p:integer l:"GO X Coordinate" t:dataTypeName=number

metric m:go_y_coordinate p:integer l:"GO Y Coordinate" t:dataTypeName=number

entity e:7g8v-xxja l:"Annual Crime 2014" t:url=https://data.austintexas.gov/api/views/7g8v-xxja

property e:7g8v-xxja t:meta.view v:id=7g8v-xxja v:averageRating=0 v:name="Annual Crime 2014"

property e:7g8v-xxja t:meta.view.owner v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"

property e:7g8v-xxja t:meta.view.tableauthor v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"
```

## Top Records

```ls
| go_primary_key | council_district | go_highest_offense_desc   | highest_nibrs_ucr_offense_description | go_report_date      | go_location              | clearance_status | clearance_date      | go_district | go_location_zip | go_census_tract    | go_x_coordinate | go_y_coordinate | 
| ============== | ================ | ========================= | ===================================== | =================== | ======================== | ================ | =================== | =========== | =============== | ================== | =============== | =============== | 
| 20141061920    | 1                | AGG ROBBERY/DEADLY WEAPON | Robbery                               | 2014-04-17T00:00:00 | 12151 N IH 35 SVRD NB    | N                | 2014-04-28T00:00:00 | E           | 78753           | 18.350000000000001 | 3135985         | 10117220        | 
| 20141150937    | 1                | ROBBERY BY ASSAULT        | Robbery                               | 2014-04-25T00:00:00 | 3300 BLOCK ROCKHURST LN  | N                | 2014-05-20T00:00:00 | I           | 78723           | 21.13              | 3137985         | 10087946        | 
| 20141310316    | 3                | ROBBERY BY THREAT         | Robbery                               | 2014-05-11T00:00:00 | E 7TH ST / CHICON ST     | N                | 2014-05-13T00:00:00 | C           | 78702           | 9.02               | 3120890         | 10068910        | 
| 20141670098    | 1                | AGG ROBBERY/DEADLY WEAPON | Robbery                               | 2014-06-16T00:00:00 | WHELESS LN / BERKMAN DR  | C                | 2015-03-24T00:00:00 | I           | 78723           | 21.04              | 3130566         | 10089446        | 
| 20142070292    | 3                | AGG ROBBERY/DEADLY WEAPON | Robbery                               | 2014-07-26T00:00:00 | WALLER ST / E 2ND ST     | N                | 2014-10-02T00:00:00 | G           | 78702           | 9.02               | 3117732         | 10068195        | 
| 2014210105     | 1                | ROBBERY BY ASSAULT        | Robbery                               | 2014-01-21T00:00:00 | 1900 BLOCK MAPLE AVE     | C                | 2014-02-03T00:00:00 | C           | 78722           | 4.0199999999999996 | 3122536         | 10075649        | 
| 20142321602    | 9                | ROBBERY BY ASSAULT        | Robbery                               | 2014-08-20T00:00:00 | E 6TH ST / CONGRESS AVE  | N                | 2014-08-27T00:00:00 | G           | 78701           | 11                 | 3114310         | 10070753        | 
| 20142571748    | 4                | ROBBERY BY THREAT         | Robbery                               | 2014-09-15T00:00:00 | 7800 N IH 35 SVRD SB     | C                | 2014-11-18T00:00:00 | E           | 78753           | 18.04              | 3127097         | 10097584        | 
| 20142610771    | 3                | AGG ROBBERY/DEADLY WEAPON | Robbery                               | 2014-09-18T00:00:00 | 1900 BLOCK MONTOPOLIS DR | N                | 2014-10-22T00:00:00 | H           | 78741           | 23.18              | 3127162         | 10055519        | 
| 20142640694    | 9                | ROBBERY BY ASSAULT        | Robbery                               | 2014-09-21T00:00:00 | 700 BLOCK E 6TH ST       | N                | 2014-10-14T00:00:00 | G           | 78701           | 11                 | 3116520         | 10070158        | 
```