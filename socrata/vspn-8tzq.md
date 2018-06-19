# Office Of Adult And Continuing Education Location Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-adult-and-continuing-education-location-directory-3c572) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vspn-8tzq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vspn-8tzq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vspn-8tzq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vspn-8tzq |
| Name | Office Of Adult And Continuing Education Location Directory |
| Attribution | Mayor's Office of Adult Education (ADULTED) |
| Category | Social Services |
| Tags | office of adult and continuing education location directory, jobs and economic mobility |
| Created | 2013-03-19T20:27:55Z |
| Publication Date | 2013-03-19T20:30:56Z |

## Description

Listing of adult and continuing education program locations

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | region       | Region       | text      | text        |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | phone_number | Phone Number | text      | text        |
| Yes      | series tag  | locations    | Locations    | text      | text        |
| Yes      | series tag  | notes        | Notes        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vspn-8tzq d:2013-03-19T13:27:56.000Z t:region=1 t:phone_number=718-863-4057 t:locations="Fordham, Hunts Point, Morrisania, Mott Haven, Norwood, Parkchester, Wakefield, West Bronx, West Farms," t:name="Bronx Adult Learning Center(BxALC)" t:notes="Room 323" m:row_number.vspn-8tzq=1

series e:vspn-8tzq d:2013-03-19T13:27:56.000Z t:region=2 t:phone_number=718-361-9480 t:locations="Astoria, Elmhurst, Flushing, Jackson Heights, Long Island City, Sunnyside" t:name="Queens Adult Learning Center(QALC)" t:notes="7th floor" m:row_number.vspn-8tzq=2

series e:vspn-8tzq d:2013-03-19T13:27:56.000Z t:region=3 t:phone_number=718-557-2567 t:locations="Bellerose, Briarwood, Far Rockaway,  Glendale, Hollis, Jamaica, Kew Gardens, Laurelton, Ozone Park, Queens Village, Richmond Hill,  Ridgewood, Rochdale Village, Rockaway, Rosedale, South Jamaica, South Ozone Park, St. Albans" t:name="Educational Services" t:notes="The entrance is on 90th Avenue -Rufus King Avenue" m:row_number.vspn-8tzq=3
```

## Meta Commands

```ls
metric m:row_number.vspn-8tzq p:long l:"Row Number"

entity e:vspn-8tzq l:"Office Of Adult And Continuing Education Location Directory" t:attribution="Mayor's Office of Adult Education (ADULTED)" t:url=https://data.cityofnewyork.us/api/views/vspn-8tzq

property e:vspn-8tzq t:meta.view v:id=vspn-8tzq v:category="Social Services" v:averageRating=0 v:name="Office Of Adult And Continuing Education Location Directory" v:attribution="Mayor's Office of Adult Education (ADULTED)"

property e:vspn-8tzq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vspn-8tzq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | region              | name                                        | phone_number | locations                                                                                                                                                                                                                        | notes                                             | 
| =========== | =================== | =========================================== | ============ | ================================================================================================================================================================================================================================ | ================================================= | 
| 1363699676  | 1                   | Bronx Adult Learning Center(BxALC)          | 718-863-4057 | Fordham, Hunts Point, Morrisania, Mott Haven, Norwood, Parkchester, Wakefield, West Bronx, West Farms,                                                                                                                           | Room 323                                          | 
| 1363699676  | 2                   | Queens Adult Learning Center(QALC)          | 718-361-9480 | Astoria, Elmhurst, Flushing, Jackson Heights, Long Island City, Sunnyside                                                                                                                                                        | 7th floor                                         | 
| 1363699676  | 3                   | Educational Services                        | 718-557-2567 | Bellerose, Briarwood, Far Rockaway,  Glendale, Hollis, Jamaica, Kew Gardens, Laurelton, Ozone Park, Queens Village, Richmond Hill,  Ridgewood, Rochdale Village, Rockaway, Rosedale, South Jamaica, South Ozone Park, St. Albans | The entrance is on 90th Avenue -Rufus King Avenue | 
| 1363699676  | 4                   | Alternative Education Complex               | 212-868-1650 | Manhattan, below 119th Street                                                                                                                                                                                                    | entrance at 269 West 35th Street, 10th floor      | 
| 1363699676  | 5                   | Mid-Manhattan Adult Learning Center (MMALC) | 212-666-1919 | Manhattan, 119th Street and above                                                                                                                                                                                                |                                                   | 
| 1363699676  | 6                   | P.S. 13                                     | 718-240-2770 | Bay Ridge, Bensonhurst, Borough Park, Canarsie, Coney Island, Crown Heights, East Flatbush, East New York, Flatbush, Midwood, Ocean Hill- Brownsville, Sheepshead Bay, Sunset Park                                               | 718-240-2770                                      | 
| 1363699676  | 7                   | Brooklyn Adult Learning Center(BALC)        | 718-789-2223 | Bedford-Stuyvesant, Bushwick, Clinton Hill, Crown Heights, East New York,  Flatbush, Fort Greene,  Greenpoint, Prospect Heights,  Ridgewood, Williamsburg                                                                        | 718-789-2223                                      | 
| 1363699676  | 8                   | Brooklyn Adult Learning Center              | 718-638-2635 | Bedford-Stuyvesant and Staten Island                                                                                                                                                                                             | 718-638-2635                                      | 
| 1363699676  | OACE Central Office | Brooklyn Adult Learning Center              | 718-638-2635 |                                                                                                                                                                                                                                  | 718-638-2635                                      | 
```