# Directory Of Family Shelter Performance Ranking FY 2012 Q4 and 2013 Q1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-family-shelter-performance-ranking-fy-2012-q4-and-2013-q1-ab8b0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/y7z5-rhh5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/y7z5-rhh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/y7z5-rhh5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | y7z5-rhh5 |
| Name | Directory Of Family Shelter Performance Ranking FY 2012 Q4 and 2013 Q1 |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, family, shelter, performance, ranking, q4, 2012, q1, 2013 |
| Created | 2013-01-31T14:48:42Z |
| Publication Date | 2013-01-31T14:51:18Z |

## Description

List of Facilities, Providers and their Rankings for Q4 2012 and Q1 2013

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y7z5-rhh5 d:2012-01-01T00:00:00.000Z t:provider_agency="Homes for the Homeless" t:year_quarter="2012 Q4" t:performance_tier="1st Performance Tier" t:facility_name="Clinton Family Inn" m:row_number.y7z5-rhh5=1

series e:y7z5-rhh5 d:2012-01-01T00:00:00.000Z t:provider_agency="Children's Rescue Fund" t:year_quarter="2012 Q4" t:performance_tier="1st Performance Tier" t:facility_name="CRF House East" m:row_number.y7z5-rhh5=2

series e:y7z5-rhh5 d:2012-01-01T00:00:00.000Z t:provider_agency="Housing Bridge, Inc." t:year_quarter="2012 Q4" t:performance_tier="1st Performance Tier" t:facility_name="HB - LaGuardia Family Center" m:row_number.y7z5-rhh5=3
```

## Meta Commands

```ls
metric m:row_number.y7z5-rhh5 p:long l:"Row Number"

entity e:y7z5-rhh5 l:"Directory Of Family Shelter Performance Ranking FY 2012 Q4 and 2013 Q1" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/y7z5-rhh5

property e:y7z5-rhh5 t:meta.view v:id=y7z5-rhh5 v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/family_shelter_performance_ranking_fy_2012_q4.pdf v:averageRating=0 v:name="Directory Of Family Shelter Performance Ranking FY 2012 Q4 and 2013 Q1" v:attribution="Department of Homeless Services (DHS)"

property e:y7z5-rhh5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:y7z5-rhh5 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year_quarter | facility_name                     | provider_agency                              | performance_tier     | 
| ============ | ================================= | ============================================ | ==================== | 
| 2012 Q4      | Clinton Family Inn                | Homes for the Homeless                       | 1st Performance Tier | 
| 2012 Q4      | CRF House East                    | Children's Rescue Fund                       | 1st Performance Tier | 
| 2012 Q4      | HB - LaGuardia Family Center      | Housing Bridge, Inc.                         | 1st Performance Tier | 
| 2012 Q4      | HB - New Broadway                 | Housing Bridge, Inc.                         | 1st Performance Tier | 
| 2012 Q4      | HELP- Bronx Morris                | HELP U.S.A                                   | 1st Performance Tier | 
| 2012 Q4      | Kianga House                      | Brooklyn Neighborhood Improvement Associates | 1st Performance Tier | 
| 2012 Q4      | Lehman Brothers Residence         | Women In Need, Inc.                          | 1st Performance Tier | 
| 2012 Q4      | Lydia E. Hoffman Family Residence | Volunteers of America                        | 1st Performance Tier | 
| 2012 Q4      | Monica House II                   | Women In Need, Inc.                          | 1st Performance Tier | 
| 2012 Q4      | Park Avenue Manor                 | Bushwick Economic Development Corp.          | 1st Performance Tier | 
```