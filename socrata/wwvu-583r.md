# Charm City Circulator Ridership

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/charm-city-circulator-ridership-61e94) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/wwvu-583r) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/wwvu-583r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/wwvu-583r/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | wwvu-583r |
| Name | Charm City Circulator Ridership |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | circulator, bus, transportation, eco-friendly |
| Created | 2012-05-11T17:02:25Z |
| Publication Date | 2014-04-03T23:28:47Z |

## Description

The City of Baltimore is constantly seeking innovative and creative ways to alleviate traffic congestion and green house gases in our great city. A new fleet of eco-friendly buses will provide everyone with a faster, more convenient, greener way to move about Baltimore's busy downtown neighborhoods. This data reflects the daily passengers boarding and alighting for each route.  In order to get to one ??_??_??_neat??_?? ridership number, an average of the boarding and alighting numbers is calculated to get a final count. The disparity in the boarding and alighting counts can be contributed to the difficulty the sensors encounter with small children, large groups, wheelchairs, strollers, etc.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | day              | day              | text          | text          |
| Yes      | time           | date             | date             | calendar_date | calendar_date |
| Yes      | numeric metric | orangeboardings  | orangeBoardings  | number        | number        |
| Yes      | numeric metric | orangealightings | orangeAlightings | number        | number        |
| Yes      | numeric metric | orangeaverage    | orangeAverage    | number        | number        |
| Yes      | numeric metric | purpleboardings  | purpleBoardings  | number        | number        |
| Yes      | numeric metric | purplealightings | purpleAlightings | number        | number        |
| Yes      | numeric metric | purpleaverage    | purpleAverage    | number        | number        |
| Yes      | numeric metric | greenboardings   | greenBoardings   | number        | number        |
| Yes      | numeric metric | greenalightings  | greenAlightings  | number        | number        |
| Yes      | numeric metric | greenaverage     | greenAverage     | number        | number        |
| Yes      | numeric metric | bannerboardings  | bannerBoardings  | number        | number        |
| Yes      | numeric metric | banneralightings | bannerAlightings | number        | number        |
| Yes      | numeric metric | banneraverage    | bannerAverage    | number        | number        |
| Yes      | numeric metric | daily            | daily            | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:wwvu-583r d:2010-01-11T00:00:00.000Z t:day=Monday m:orangeaverage=952 m:orangealightings=1027 m:daily=952 m:orangeboardings=877

series e:wwvu-583r d:2010-01-12T00:00:00.000Z t:day=Tuesday m:orangeaverage=796 m:orangealightings=815 m:daily=796 m:orangeboardings=777

series e:wwvu-583r d:2010-01-13T00:00:00.000Z t:day=Wednesday m:orangeaverage=1211.5 m:orangealightings=1220 m:daily=1211.5 m:orangeboardings=1203
```

## Meta Commands

```ls
metric m:orangeboardings p:integer l:orangeBoardings t:dataTypeName=number

metric m:orangealightings p:integer l:orangeAlightings t:dataTypeName=number

metric m:orangeaverage p:float l:orangeAverage t:dataTypeName=number

metric m:purpleboardings p:integer l:purpleBoardings t:dataTypeName=number

metric m:purplealightings p:integer l:purpleAlightings t:dataTypeName=number

metric m:purpleaverage p:float l:purpleAverage t:dataTypeName=number

metric m:greenboardings p:integer l:greenBoardings t:dataTypeName=number

metric m:greenalightings p:integer l:greenAlightings t:dataTypeName=number

metric m:greenaverage p:double l:greenAverage t:dataTypeName=number

metric m:bannerboardings p:integer l:bannerBoardings t:dataTypeName=number

metric m:banneralightings p:integer l:bannerAlightings t:dataTypeName=number

metric m:banneraverage p:double l:bannerAverage t:dataTypeName=number

metric m:daily p:float l:daily t:dataTypeName=number

entity e:wwvu-583r l:"Charm City Circulator Ridership" t:attribution="Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/wwvu-583r

property e:wwvu-583r t:meta.view v:id=wwvu-583r v:category=Transportation v:attributionLink=http://www.charmcitycirculator.com/ v:averageRating=0 v:name="Charm City Circulator Ridership" v:attribution="Department of Transportation"

property e:wwvu-583r t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:wwvu-583r t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:wwvu-583r t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| day       | date                | orangeboardings | orangealightings | orangeaverage | purpleboardings | purplealightings | purpleaverage | greenboardings | greenalightings | greenaverage | bannerboardings | banneralightings | banneraverage | daily  | 
| ========= | =================== | =============== | ================ | ============= | =============== | ================ | ============= | ============== | =============== | ============ | =============== | ================ | ============= | ====== | 
| Monday    | 2010-01-11T00:00:00 | 877             | 1027             | 952           |                 |                  |               |                |                 |              |                 |                  |               | 952    | 
| Tuesday   | 2010-01-12T00:00:00 | 777             | 815              | 796           |                 |                  |               |                |                 |              |                 |                  |               | 796    | 
| Wednesday | 2010-01-13T00:00:00 | 1203            | 1220             | 1211.5        |                 |                  |               |                |                 |              |                 |                  |               | 1211.5 | 
| Thursday  | 2010-01-14T00:00:00 | 1194            | 1233             | 1213.5        |                 |                  |               |                |                 |              |                 |                  |               | 1213.5 | 
| Friday    | 2010-01-15T00:00:00 | 1645            | 1643             | 1644          |                 |                  |               |                |                 |              |                 |                  |               | 1644   | 
| Saturday  | 2010-01-16T00:00:00 | 1457            | 1524             | 1490.5        |                 |                  |               |                |                 |              |                 |                  |               | 1490.5 | 
| Sunday    | 2010-01-17T00:00:00 | 839             | 938              | 888.5         |                 |                  |               |                |                 |              |                 |                  |               | 888.5  | 
| Monday    | 2010-01-18T00:00:00 | 999             | 1000             | 999.5         |                 |                  |               |                |                 |              |                 |                  |               | 999.5  | 
| Tuesday   | 2010-01-19T00:00:00 | 1023            | 1047             | 1035          |                 |                  |               |                |                 |              |                 |                  |               | 1035   | 
| Wednesday | 2010-01-20T00:00:00 | 1375            | 1416             | 1395.5        |                 |                  |               |                |                 |              |                 |                  |               | 1395.5 | 
```