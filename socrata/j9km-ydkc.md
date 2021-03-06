# Seattle Parks and Recreation Parks With Features

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-parks-and-recreation-parks-with-features) |
| Metadata | [Link](https://data.seattle.gov/api/views/j9km-ydkc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/j9km-ydkc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/j9km-ydkc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | j9km-ydkc |
| Name | Seattle Parks and Recreation Parks With Features |
| Attribution | Seattle Parks and Recreation |
| Category | Parks and Recreation |
| Tags | parks, features |
| Created | 2016-03-19T22:28:07Z |
| Publication Date | 2016-03-19T22:58:21Z |

## Description

Listing all parks that have at least one of a particular kind of feature.  EX:  if a park has one or more tennis court it is included.

PMAID is the Property Management Area ID. It is used by the City of Seattle to reference a group of adjoined land parcels into a larger area such as a park. This coding works well for Parks because most parks consist of multiple parcels. This number is assigned by the city. Other cities likely use a similar identifier, but not the same method as Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | numeric metric | pmaid        | pmaid        | number    | number      |
| Yes      | series tag     | name         | name         | text      | text        |
| Yes      | series tag     | feature_desc | feature_desc | text      | text        |
| Yes      | series tag     | hours        | hours        | text      | text        |
| Yes      | numeric metric | xpos         | xpos         | number    | number      |
| Yes      | numeric metric | ypos         | ypos         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j9km-ydkc d:2016-03-19T15:28:11.000Z t:feature_desc=Golf t:hours="24 Hours" t:name="Green Lake Park" m:pmaid=307 m:ypos=47.678938 m:xpos=-122.330394

series e:j9km-ydkc d:2016-03-19T15:28:11.000Z t:feature_desc="Play Area (ADA Compliant)" t:hours="4 a.m. - 11:30 p.m." t:name="Kirke Park" m:pmaid=4468

series e:j9km-ydkc d:2016-03-19T15:28:11.000Z t:feature_desc="Restrooms (ADA Compliant)" t:hours="4 a.m. - 11:30 p.m." t:name="Hiawatha Playfield" m:pmaid=456 m:ypos=47.57827243 m:xpos=-122.3849647
```

## Meta Commands

```ls
metric m:pmaid p:integer l:pmaid t:dataTypeName=number

metric m:xpos p:double l:xpos t:dataTypeName=number

metric m:ypos p:double l:ypos t:dataTypeName=number

entity e:j9km-ydkc l:"Seattle Parks and Recreation Parks With Features" t:attribution="Seattle Parks and Recreation" t:url=https://data.seattle.gov/api/views/j9km-ydkc

property e:j9km-ydkc t:meta.view d:2017-09-25T07:24:15.876Z v:averageRating=0 v:name="Seattle Parks and Recreation Parks With Features" v:attribution="Seattle Parks and Recreation" v:attributionLink=http://www.seattle.gov/parks/ v:id=j9km-ydkc v:category="Parks and Recreation"

property e:j9km-ydkc t:meta.view.owner d:2017-09-25T07:24:15.876Z v:displayName="Blood, Bruce" v:id=fs78-6jsr v:screenName="Blood, Bruce"

property e:j9km-ydkc t:meta.view.tableauthor d:2017-09-25T07:24:15.876Z v:displayName="Blood, Bruce" v:id=fs78-6jsr v:screenName="Blood, Bruce"
```

## Top Records

```ls
| :updated_at | pmaid | name                  | feature_desc              | hours                                                                                                         | xpos         | ypos        | 
| =========== | ===== | ===================== | ========================= | ============================================================================================================= | ============ | =========== | 
| 1458401291  | 307   | Green Lake Park       | Golf                      | 24 Hours                                                                                                      | -122.330394  | 47.678938   | 
| 1458401291  | 4468  | Kirke Park            | Play Area (ADA Compliant) | 4 a.m. - 11:30 p.m.                                                                                           |              |             | 
| 1458401291  | 456   | Hiawatha Playfield    | Restrooms (ADA Compliant) | 4 a.m. - 11:30 p.m.                                                                                           | -122.3849647 | 47.57827243 | 
| 1458401291  | 310   | Discovery Park        | Basketball (Full)         | Park Hours: Daily 4 a.m. - 11:30 p.m.
Visitor Center Hours: Tuesday-Sunday 8:30 a.m. - 5 p.m.
Closed holidays | -122.415282  | 47.66083    | 
| 1458401291  | 3023  | Interlaken Park       | Bike Trail                | 4 a.m. - 11:30 p.m.                                                                                           | -122.308316  | 47.636257   | 
| 1458401291  | 435   | University Playground | Soccer                    | 6 a.m. - 10 p.m.                                                                                              | -122.3193123 | 47.66444741 | 
| 1458401291  | 367   | Leschi Park           | Play Area                 | 4 a.m. - 11:30 p.m.                                                                                           | -122.286548  | 47.600931   | 
| 1458401291  | 3703  | Bar-S Playground      | Baseball/Softball         | 4 a.m. - 11:30 p.m.                                                                                           | -122.4160544 | 47.57519512 | 
| 1458401291  | 404   | Cleveland Playfield   | Football                  | 4 a.m. - 11:30 p.m.                                                                                           | -122.315542  | 47.55201155 | 
| 1458401291  | 371   | Madrona Playground    | Baseball/Softball         | 6 a.m. - 10 p.m.                                                                                              | -122.2898852 | 47.61102165 | 
```