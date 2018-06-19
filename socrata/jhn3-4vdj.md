# Directory Of Adult Shelter Performance Ranking FY 2011 Q3 2011 Q4

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-adult-shelter-performance-ranking-fy-2011-q3-2011-q4-7a8b2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jhn3-4vdj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jhn3-4vdj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jhn3-4vdj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jhn3-4vdj |
| Name | Directory Of Adult Shelter Performance Ranking FY 2011 Q3 2011 Q4 |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, adult, shelter, performance, ranking, q3, q4, 2011 |
| Created | 2013-01-31T14:40:37Z |
| Publication Date | 2013-01-31T14:43:12Z |

## Description

List of Facilities, Providers and their Rankings for Q3 2012 and Q4 2011

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | year_quarter     | Year & Quarter   | text      | text        |
| Yes      | series tag  | facility_name    | Facility Name    | text      | text        |
| Yes      | series tag  | provider_agency  | Provider Agency  | text      | text        |
| Yes      | series tag  | performance_tier | Performance Tier | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jhn3-4vdj d:2011-01-01T00:00:00.000Z t:provider_agency=Palladia t:year_quarter="2011 Q3" t:performance_tier="1st Performance Tier" t:facility_name="126 Street Shelter" m:row_number.jhn3-4vdj=1

series e:jhn3-4vdj d:2011-01-01T00:00:00.000Z t:provider_agency=BRC t:year_quarter="2011 Q3" t:performance_tier="1st Performance Tier" t:facility_name="85 Lexington" m:row_number.jhn3-4vdj=2

series e:jhn3-4vdj d:2011-01-01T00:00:00.000Z t:provider_agency="Create, Inc." t:year_quarter="2011 Q3" t:performance_tier="1st Performance Tier" t:facility_name="Create Young Adult" m:row_number.jhn3-4vdj=3
```

## Meta Commands

```ls
metric m:row_number.jhn3-4vdj p:long l:"Row Number"

entity e:jhn3-4vdj l:"Directory Of Adult Shelter Performance Ranking FY 2011 Q3 2011 Q4" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/jhn3-4vdj

property e:jhn3-4vdj t:meta.view v:id=jhn3-4vdj v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/adult_shelter_performance_ranking_fy_2011_q3.pdf v:averageRating=0 v:name="Directory Of Adult Shelter Performance Ranking FY 2011 Q3 2011 Q4" v:attribution="Department of Homeless Services (DHS)"

property e:jhn3-4vdj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jhn3-4vdj t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year_quarter | facility_name       | provider_agency                     | performance_tier     | 
| ============ | =================== | =================================== | ==================== | 
| 2011 Q3      | 126 Street Shelter  | Palladia                            | 1st Performance Tier | 
| 2011 Q3      | 85 Lexington        | BRC                                 | 1st Performance Tier | 
| 2011 Q3      | Create Young Adult  | Create, Inc.                        | 1st Performance Tier | 
| 2011 Q3      | HWC Assessment      | HELP USA                            | 1st Performance Tier | 
| 2011 Q3      | Kenton              | Project Renewal                     | 1st Performance Tier | 
| 2011 Q3      | Palace Men          | BRC                                 | 1st Performance Tier | 
| 2011 Q3      | Project Hospitality | Project Hospitality                 | 1st Performance Tier | 
| 2011 Q3      | Saratoga            | HELP USA                            | 1st Performance Tier | 
| 2011 Q3      | SCCW TLC            | Center for Urban Community Services | 1st Performance Tier | 
| 2011 Q3      | Turning Point       | Turning Point                       | 1st Performance Tier | 
```