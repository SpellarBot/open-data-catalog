# Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-polling-place-locations-2014-november-4-gubernatorial-election-d302d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3qf7-xrf4 |
| Name | Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election |
| Attribution | Cook County Clerk |
| Category | Finance & Administration |
| Tags | elections, voting, vote, polling locations |
| Created | 2014-10-17T16:18:17Z |
| Publication Date | 2014-10-27T19:46:26Z |

## Description

Data Updated 10/27/2014. This dataset contains the Polling Place locations in suburban Cook County for the 2014 Gubernatorial Election on November 4. For more information on Polling Locations see http://www.cookcountyclerk.com/elections/pollinglocations/Pages/default.aspx

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag  | precinct                    | Precinct                    | text      | number      |
| Yes      | series tag  | polling_place_id            | Polling Place ID            | text      | number      |
| Yes      | series tag  | polling_place_location_name | Polling Place Location Name | text      | text        |
| Yes      | series tag  | accessible                  | Accessible                  | text      | text        |
| No       |             | address                     | Address                     | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | zip                         | Zip                         | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:3qf7-xrf4 d:2014-01-01T00:00:00.000Z t:zip=60706 t:precinct=8400012 t:accessible=YES t:polling_place_id=1283 t:polling_place_location_name="THE MONTCLARE BUILDING" t:city="HARWOOD HEIGHTS" m:row_number.3qf7-xrf4=1

series e:3qf7-xrf4 d:2014-01-01T00:00:00.000Z t:zip=60091 t:precinct=8100032 t:accessible=YES t:polling_place_id=4091 t:polling_place_location_name="MALLINCKRODT COMMUNITY CENTER" t:city=WILMETTE m:row_number.3qf7-xrf4=2

series e:3qf7-xrf4 d:2014-01-01T00:00:00.000Z t:zip=60445 t:precinct=7200068 t:accessible=YES t:polling_place_id=284 t:polling_place_location_name="ESDA BUILDING" t:city=CRESTWOOD m:row_number.3qf7-xrf4=3
```

## Meta Commands

```ls
metric m:row_number.3qf7-xrf4 p:long l:"Row Number"

entity e:3qf7-xrf4 l:"Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4

property e:3qf7-xrf4 t:meta.view d:2017-09-25T07:30:35.858Z v:averageRating=0 v:name="Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election" v:attribution="Cook County Clerk" v:attributionLink=http://www.cookcountyclerk.com/elections/pollinglocations/Pages/default.aspx v:id=3qf7-xrf4 v:category="Finance & Administration"

property e:3qf7-xrf4 t:meta.view.license d:2017-09-25T07:30:35.858Z v:name="Public Domain"

property e:3qf7-xrf4 t:meta.view.owner d:2017-09-25T07:30:35.858Z v:displayName="Cook County Open Data" v:lastNotificationSeenAt=1503001958 v:id=u38g-hbsa v:screenName="Cook County Open Data"

property e:3qf7-xrf4 t:meta.view.tableauthor d:2017-09-25T07:30:35.858Z v:displayName="Cook County Open Data" v:lastNotificationSeenAt=1503001958 v:roleName=administrator v:id=u38g-hbsa v:screenName="Cook County Open Data"
```

## Top Records

```ls
| precinct | polling_place_id | polling_place_location_name   | accessible | address            | city             | zip   | 
| ======== | ================ | ============================= | ========== | ================== | ================ | ===== | 
| 8400012  | 1283             | THE MONTCLARE BUILDING        | YES        | 7171 W GUNNISON ST | HARWOOD HEIGHTS  | 60706 | 
| 8100032  | 4091             | MALLINCKRODT COMMUNITY CENTER | YES        | 1041A RIDGE RD     | WILMETTE         | 60091 | 
| 7200068  | 284              | ESDA BUILDING                 | YES        | 13755 S LAMON AVE  | CRESTWOOD        | 60445 | 
| 7600028  | 585              | TOWNE PLACE WEST CLUBHOUSE    | YES        | 2841 MEADOW LN     | SCHAUMBURG       | 60195 | 
| 7800026  | 697              | ELM SCHOOL                    | YES        | 7607 W CORTLAND ST | ELMWOOD PARK     | 60707 | 
| 8700035  | 3663             | PALATINE TOWNSHIP CENTER      | YES        | 721 S QUENTIN RD   | PALATINE         | 60067 | 
| 7600007  | 538              | HANOVER COUNTRYSIDE SCHOOL    | YES        | 6 S BARTLETT RD    | STREAMWOOD       | 60107 | 
| 7100016  | 170              | LYNWOOD SENIOR YOUTH CENTER   | YES        | 21490 LINCOLN HWY  | LYNWOOD          | 60411 | 
| 9500026  | 4014             | EAST HAZEL CREST FIRE STATION | YES        | 17223 THROOP ST    | EAST HAZEL CREST | 60429 | 
| 8100024  | 1038             | BETH HILLEL CONGREGATION      | YES        | 3220 BIG TREE LN   | WILMETTE         | 60091 | 
```