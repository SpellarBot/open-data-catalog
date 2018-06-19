# Film Locations in San Francisco

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/film-locations-in-san-francisco-b217a) |
| Metadata | [Link](https://data.sfgov.org/api/views/yitu-d5am) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/yitu-d5am/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/yitu-d5am/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | yitu-d5am |
| Name | Film Locations in San Francisco |
| Attribution | San Francisco Film Commission |
| Category | Culture and Recreation |
| Tags | film, locations, movies, actors, directors |
| Created | 2011-11-10T18:13:33Z |
| Publication Date | 2016-10-27T21:18:11Z |

## Description

If you love movies, and you love San Francisco, you're bound to love this -- a listing of filming locations of movies shot in San Francisco starting from 1924. You'll find the titles, locations, fun facts, names of the director, writer, actors, and studio for most of these films.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | title              | Title              | text      | text        |
| Yes      | time        | release_year       | Release Year       | number    | number      |
| Yes      | series tag  | locations          | Locations          | text      | text        |
| Yes      | series tag  | fun_facts          | Fun Facts          | text      | text        |
| Yes      | series tag  | production_company | Production Company | text      | text        |
| Yes      | series tag  | distributor        | Distributor        | text      | text        |
| Yes      | series tag  | director           | Director           | text      | text        |
| Yes      | series tag  | writer             | Writer             | text      | text        |
| Yes      | series tag  | actor_1            | Actor 1            | text      | text        |
| Yes      | series tag  | actor_2            | Actor 2            | text      | text        |
| Yes      | series tag  | actor_3            | Actor 3            | text      | text        |
```

## Time Field

```ls
Value = release_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:yitu-d5am l:"Film Locations in San Francisco" t:attribution="San Francisco Film Commission" t:url=https://data.sfgov.org/api/views/yitu-d5am

property e:yitu-d5am t:meta.view v:id=yitu-d5am v:category="Culture and Recreation" v:attributionLink=http://www.filmsf.org/ v:averageRating=0 v:name="Film Locations in San Francisco" v:attribution="San Francisco Film Commission"

property e:yitu-d5am t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yitu-d5am t:meta.view.owner v:id=qp74-qyt9 v:profileImageUrlMedium=/api/users/qp74-qyt9/profile_images/THUMB v:profileImageUrlLarge=/api/users/qp74-qyt9/profile_images/LARGE v:screenName="Film SF" v:profileImageUrlSmall=/api/users/qp74-qyt9/profile_images/TINY v:displayName="Film SF"

property e:yitu-d5am t:meta.view.tableauthor v:id=qp74-qyt9 v:profileImageUrlMedium=/api/users/qp74-qyt9/profile_images/THUMB v:profileImageUrlLarge=/api/users/qp74-qyt9/profile_images/LARGE v:screenName="Film SF" v:profileImageUrlSmall=/api/users/qp74-qyt9/profile_images/TINY v:roleName=editor v:displayName="Film SF"
```

## Top Records

```ls
| title                  | release_year | locations                             | fun_facts                                                                           | production_company      | distributor     | director              | writer                                           | actor_1       | actor_2           | actor_3     | 
| ====================== | ============ | ===================================== | =================================================================================== | ======================= | =============== | ===================== | ================================================ | ============= | ================= | =========== | 
| 180                    | 2011         | Epic Roasthouse (399 Embarcadero)     |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | Mason & California Streets (Nob Hill) |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | Justin Herman Plaza                   |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | 200 block Market Street               |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | City Hall                             |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | Polk & Larkin Streets                 |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | Randall Museum                        |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 180                    | 2011         | 555 Market St.                        |                                                                                     | SPI Cinemas             |                 | Jayendra              | Umarji Anuradha, Jayendra, Aarthi Sriram, & Suba | Siddarth      | Nithya Menon      | Priya Anand | 
| 24 Hours on Craigslist | 2005         |                                       |                                                                                     | Yerba Buena Productions | Zealot Pictures | Michael Ferris Gibson | N/A                                              | Craig Newmark |                   |             | 
| 40 Days and 40 Nights  | 2002         | The Walden House, Buena Vista Park    | Established in 1867, Buena Vista Park is the oldest official park in San Francisco. | Miramax Films           | Miramax Films   | Michael Lehmann       | Robert Perez                                     | Josh Hartnett | Shaynnyn Sossamon |             | 
```