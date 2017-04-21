# Polling Place Locations - 2016 March 15 Presidential Primary Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/polling-place-locations-2016-march-15-presidential-primary-election) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/r52m-fyu3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/r52m-fyu3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/r52m-fyu3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | r52m-fyu3 |
| Name | Polling Place Locations - 2016 March 15 Presidential Primary Election |
| Attribution | Cook County Clerk |
| Category | Finance & Administration |
| Tags | election, voting, precincts, polling place |
| Created | 2016-03-04T20:58:32Z |
| Publication Date | 2016-03-04T21:14:09Z |

## Description

This dataset contains the Polling Place locations in suburban Cook County for the 2016 Presidential Primary Election on March 15. For more information on Polling Locations see http://www.cookcountyclerk.com/elections/pollinglocations/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | location_name | Location Name | text      | text        |
| Yes      | series tag     | accessible    | Accessible    | text      | text        |
| Yes      | series tag     | precinct      | PRECINCT      | text      | number      |
| Yes      | numeric metric | precinct2     | PRECINCT2     | number    | number      |
| Yes      | numeric metric | precinct3     | PRECINCT3     | number    | number      |
| Yes      | numeric metric | precinct4     | PRECINCT4     | number    | number      |
| Yes      | numeric metric | precinct5     | PRECINCT5     | number    | number      |
| Yes      | numeric metric | precinct6     | PRECINCT6     | number    | number      |
| No       |                | address       | Address       | text      | text        |
| Yes      | series tag     | city          | City          | text      | text        |
| No       |                | x             | X             | number    | number      |
| No       |                | y             | Y             | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,x,y
```

## Data Commands

```ls
series e:r52m-fyu3 d:2016-01-01T00:00:00.000Z t:precinct=7000004 t:location_name="WILLOW CREEK COMM CHURCH" t:accessible=Y t:city="SOUTH BARRINGTON" m:precinct3=7000010 m:precinct2=7000008 m:precinct4=7000011

series e:r52m-fyu3 d:2016-01-01T00:00:00.000Z t:precinct=7000006 t:location_name="ST MICHAELS EPISCOPAL CHURCH" t:accessible=Y t:city=BARRINGTON m:precinct2=7000009

series e:r52m-fyu3 d:2016-01-01T00:00:00.000Z t:precinct=9901004 t:location_name="IRVING SCHOOL" t:accessible=Y t:city=BERWYN m:precinct2=9901005
```

## Meta Commands

```ls
metric m:precinct2 p:integer l:PRECINCT2 t:dataTypeName=number

metric m:precinct3 p:integer l:PRECINCT3 t:dataTypeName=number

metric m:precinct4 p:integer l:PRECINCT4 t:dataTypeName=number

metric m:precinct5 p:integer l:PRECINCT5 t:dataTypeName=number

metric m:precinct6 p:integer l:PRECINCT6 t:dataTypeName=number

entity e:r52m-fyu3 l:"Polling Place Locations - 2016 March 15 Presidential Primary Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/r52m-fyu3

property e:r52m-fyu3 t:meta.view v:id=r52m-fyu3 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Polling Place Locations - 2016 March 15 Presidential Primary Election" v:attribution="Cook County Clerk"

property e:r52m-fyu3 t:meta.view.license v:name="Public Domain"

property e:r52m-fyu3 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:r52m-fyu3 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| location_name                  | accessible | precinct | precinct2 | precinct3 | precinct4 | precinct5 | precinct6 | address             | city             | x              | y             | 
| ============================== | ========== | ======== | ========= | ========= | ========= | ========= | ========= | =================== | ================ | ============== | ============= | 
| COMMUNITY CHURCH OF BARRINGTON | Y          | 7000001  |           |           |           |           |           | 301 E LINCOLN AVE   | BARRINGTON       | -88.1329760796 | 42.1513724857 | 
| BARRINGTON VILLLAGE HALL       | Y          | 7000002  |           |           |           |           |           | 200 S HOUGH ST      | BARRINGTON       | -88.1365093064 | 42.1527805465 | 
| GROVE AVENUE SCHOOL            | Y          | 7000003  |           |           |           |           |           | 900 GROVE ST        | BARRINGTON       | -88.1333437857 | 42.1428312099 | 
| WILLOW CREEK COMM CHURCH       | Y          | 7000004  | 7000008   | 7000010   | 7000011   |           |           | 67 E ALGONQUIN RD   | SOUTH BARRINGTON | -88.135819315  | 42.0920689372 | 
| ST MICHAELS EPISCOPAL CHURCH   | Y          | 7000006  | 7000009   |           |           |           |           | 647 DUNDEE AVE      | BARRINGTON       | -88.1407127553 | 42.1472452857 | 
| VILLAGE OF BARRINGTON HILLS    | Y          | 7000007  |           |           |           |           |           | 112 ALGONQUIN RD    | BARRINGTON       | -88.1750371822 | 42.11224305   | 
| THE PRESBYTERIAN CHURCH        | Y          | 7000005  |           |           |           |           |           | 6 BRINKER RD        | BARRINGTON HILLS | -88.1757973668 | 42.1524664247 | 
| CITIZENS COMMUNITY BANK        | Y          | 9901001  |           |           |           |           |           | 3322 S OAK PARK AVE | BERWYN           | -87.7932716679 | 41.8313793024 | 
| MOOSE LODGE                    | Y          | 9901002  |           |           |           |           |           | 3625 HARLEM AVE     | BERWYN           | -87.8022713505 | 41.8259615448 | 
| IRVING SCHOOL                  | Y          | 9901004  | 9901005   |           |           |           |           | 3501 S CLINTON AVE  | BERWYN           | -87.7958011117 | 41.8281712409 | 
```