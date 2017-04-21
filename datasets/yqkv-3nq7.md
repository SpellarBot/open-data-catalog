# 2014 Highway Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-highway-log) |
| Metadata | [Link](https://data.ct.gov/api/views/yqkv-3nq7) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/yqkv-3nq7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/yqkv-3nq7/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | yqkv-3nq7 |
| Name | 2014 Highway Log |
| Attribution | Al Iallonardo - Systems Inventory Section of the Bureau of Policy and Planning, CT Department of Transportation |
| Category | Transportation |
| Tags | 2014 highway log |
| Created | 2015-10-15T11:49:38Z |
| Publication Date | 2015-10-15T11:53:30Z |

## Description

2014 Highway Log

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | numeric metric | twn                        | TWN #                        | number    | number      |
| Yes      | series tag     | route_location_description | ROUTE & LOCATION DESCRIPTION | text      | text        |
| Yes      | numeric metric | intch                      | INTCH                        | number    | number      |
| Yes      | numeric metric | cum_miles                  | CUM MILES                    | number    | number      |
| Yes      | numeric metric | kilo_meters                | KILO METERS                  | number    | number      |
| Yes      | series tag     | hpms                       | HPMS                         | text      | text        |
| Yes      | series tag     | area                       | AREA #                       | text      | text        |
| Yes      | series tag     | maint                      | MAINT                        | text      | text        |
| Yes      | series tag     | sta                        | STA                          | text      | text        |
| Yes      | series tag     | nhs                        | NHS                          | text      | text        |
| Yes      | series tag     | r_u                        | R - U                        | text      | text        |
| Yes      | series tag     | funct_class                | FUNCT CLASS                  | text      | text        |
| Yes      | numeric metric | actl                       | ACTL                         | number    | number      |
| Yes      | numeric metric | rev_lns                    | REV LNS                      | number    | number      |
| Yes      | numeric metric | log_lns                    | LOG LNS                      | number    | number      |
| Yes      | series tag     | div                        | DIV                          | text      | text        |
| Yes      | numeric metric | bridge                     | BRIDGE                       | number    | number      |
| Yes      | series tag     | bridge_suf                 | BRIDGE SUF                   | text      | text        |
| Yes      | series tag     | dist                       | DIST                         | text      | text        |
| Yes      | numeric metric | exit                       | EXIT                         | number    | number      |
| Yes      | series tag     | exitsuf                    | EXITSUF                      | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yqkv-3nq7 d:2014-01-01T00:00:00.000Z t:maint=S t:r_u=U t:sta=S t:route_location_description="(US 1 - WEST PUTNAM AVE)" t:div=D t:funct_class="O PRI ART" t:nhs=N t:dist=3 m:log_lns=2 m:twn=56 m:actl=1 m:rev_lns=2 m:kilo_meters=0 m:cum_miles=0

series e:yqkv-3nq7 d:2014-01-01T00:00:00.000Z t:route_location_description="NEW YORK SL" m:kilo_meters=0 m:cum_miles=0

series e:yqkv-3nq7 d:2014-01-01T00:00:00.000Z t:route_location_description="NORTH ABUTMENT OP BYRAM RV" m:kilo_meters=0 m:cum_miles=0
```

## Meta Commands

```ls
metric m:twn p:integer l:"TWN #" t:dataTypeName=number

metric m:intch p:long l:INTCH t:dataTypeName=number

metric m:cum_miles p:float l:"CUM MILES" t:dataTypeName=number

metric m:kilo_meters p:float l:"KILO METERS" t:dataTypeName=number

metric m:actl p:integer l:ACTL t:dataTypeName=number

metric m:rev_lns p:integer l:"REV LNS" t:dataTypeName=number

metric m:log_lns p:integer l:"LOG LNS" t:dataTypeName=number

metric m:bridge p:integer l:BRIDGE t:dataTypeName=number

metric m:exit p:integer l:EXIT t:dataTypeName=number

entity e:yqkv-3nq7 l:"2014 Highway Log" t:attribution="Al Iallonardo - Systems Inventory Section of the Bureau of Policy and Planning, CT Department of Transportation" t:url=https://data.ct.gov/api/views/yqkv-3nq7

property e:yqkv-3nq7 t:meta.view v:id=yqkv-3nq7 v:category=Transportation v:averageRating=0 v:name="2014 Highway Log" v:attribution="Al Iallonardo - Systems Inventory Section of the Bureau of Policy and Planning, CT Department of Transportation"

property e:yqkv-3nq7 t:meta.view.owner v:id=krit-g9ue v:screenName="James Spencer" v:displayName="James Spencer"

property e:yqkv-3nq7 t:meta.view.tableauthor v:id=krit-g9ue v:screenName="James Spencer" v:roleName=editor v:displayName="James Spencer"
```

## Top Records

```ls
| twn | route_location_description      | intch | cum_miles | kilo_meters | hpms | area | maint | sta | nhs | r_u | funct_class | actl | rev_lns | log_lns | div | bridge | bridge_suf | dist | exit | exitsuf | 
| === | =============================== | ===== | ========= | =========== | ==== | ==== | ===== | === | === | === | =========== | ==== | ======= | ======= | === | ====== | ========== | ==== | ==== | ======= | 
|     | BEGIN US 1                      |       |           |             |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | US 1 - (US 1 - WEST PUTNAM AVE) |       |           |             |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | FR NEW YORK SL - GREENWICH      |       |           |             |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | TO RHODE ISLAND SL - STONINGTON |       |           |             |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | LOG DIR / NORTH                 |       |           |             |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
| 56  | (US 1 - WEST PUTNAM AVE)        |       | 0         | 0           |      |      | S     | S   | N   | U   | O PRI ART   | 1    | 2       | 2       | D   |        |            | 3    |      |         | 
|     | NEW YORK SL                     |       | 0         | 0           |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | NORTH ABUTMENT OP BYRAM RV      |       | 0         | 0           |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | US 1(NB)(NEW YORK)              |       | 0         | 0           |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
|     | US 1(SB)(NEW YORK)              |       | 0         | 0           |      |      |       |     |     |     |             |      |         |         |     |        |            |      |      |         | 
```