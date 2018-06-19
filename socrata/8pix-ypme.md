# CTA - System Information - List of 'L' Stops

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-system-information-list-of-l-stops-55287) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8pix-ypme) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8pix-ypme/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8pix-ypme/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8pix-ypme |
| Name | CTA - System Information - List of 'L' Stops |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, rail, stations, sustainability |
| Created | 2011-08-04T19:53:20Z |
| Publication Date | 2015-05-01T00:46:20Z |

## Description

This list of 'L' stops provides location and basic service availability information for each place on the CTA system where a train stops, along with formal station names and stop descriptions.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | stop_id                  | STOP_ID                  | text      | number      |
| Yes      | series tag  | direction_id             | DIRECTION_ID             | text      | text        |
| Yes      | series tag  | stop_name                | STOP_NAME                | text      | text        |
| Yes      | series tag  | station_name             | STATION_NAME             | text      | text        |
| Yes      | series tag  | station_descriptive_name | STATION_DESCRIPTIVE_NAME | text      | text        |
| Yes      | series tag  | map_id                   | MAP_ID                   | text      | number      |
| Yes      | series tag  | ada                      | ADA                      | checkbox  | checkbox    |
| Yes      | series tag  | red                      | RED                      | checkbox  | checkbox    |
| Yes      | series tag  | blue                     | BLUE                     | checkbox  | checkbox    |
| No       |             | g                        | G                        | checkbox  | checkbox    |
| Yes      | series tag  | brn                      | BRN                      | checkbox  | checkbox    |
| No       |             | p                        | P                        | checkbox  | checkbox    |
| Yes      | series tag  | pexp                     | Pexp                     | checkbox  | checkbox    |
| No       |             | y                        | Y                        | checkbox  | checkbox    |
| Yes      | series tag  | pnk                      | Pnk                      | checkbox  | checkbox    |
| No       |             | o                        | O                        | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = g,p,y,o
```

## Data Commands

```ls
series e:8pix-ypme d:2012-05-17T22:43:57.000Z t:stop_id=30162 t:ada=true t:pnk=true t:station_name=18th t:direction_id=W t:map_id=40830 t:red=false t:blue=false t:brn=false t:pexp=false t:stop_name="18th (54th/Cermak-bound)" t:station_descriptive_name="18th (Pink Line)" m:row_number.8pix-ypme=1

series e:8pix-ypme d:2012-05-17T22:43:57.000Z t:stop_id=30161 t:ada=true t:pnk=true t:station_name=18th t:direction_id=E t:map_id=40830 t:red=false t:blue=false t:brn=false t:pexp=false t:stop_name="18th (Loop-bound)" t:station_descriptive_name="18th (Pink Line)" m:row_number.8pix-ypme=2

series e:8pix-ypme d:2012-05-17T22:43:57.000Z t:stop_id=30022 t:ada=true t:pnk=false t:station_name=35th/Archer t:direction_id=N t:map_id=40120 t:red=false t:blue=false t:brn=false t:pexp=false t:stop_name="35th/Archer (Loop-bound)" t:station_descriptive_name="35th/Archer (Orange Line)" m:row_number.8pix-ypme=3
```

## Meta Commands

```ls
metric m:row_number.8pix-ypme p:long l:"Row Number"

entity e:8pix-ypme l:"CTA - System Information - List of 'L' Stops" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/8pix-ypme

property e:8pix-ypme t:meta.view v:id=8pix-ypme v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - System Information - List of 'L' Stops" v:attribution="Chicago Transit Authority"

property e:8pix-ypme t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:8pix-ypme t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| :updated_at | stop_id | direction_id | stop_name                         | station_name         | station_descriptive_name          | map_id | ada  | red   | blue  | g     | brn   | p     | pexp  | y     | pnk   | o     | 
| =========== | ======= | ============ | ================================= | ==================== | ================================= | ====== | ==== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| 1337294637  | 30162   | W            | 18th (54th/Cermak-bound)          | 18th                 | 18th (Pink Line)                  | 40830  | true | false | false | false | false | false | false | false | true  | false | 
| 1337294637  | 30161   | E            | 18th (Loop-bound)                 | 18th                 | 18th (Pink Line)                  | 40830  | true | false | false | false | false | false | false | false | true  | false | 
| 1337294637  | 30022   | N            | 35th/Archer (Loop-bound)          | 35th/Archer          | 35th/Archer (Orange Line)         | 40120  | true | false | false | false | false | false | false | false | false | true  | 
| 1337294637  | 30023   | S            | 35th/Archer (Midway-bound)        | 35th/Archer          | 35th/Archer (Orange Line)         | 40120  | true | false | false | false | false | false | false | false | false | true  | 
| 1337294637  | 30214   | S            | 35-Bronzeville-IIT (63rd-bound)   | 35th-Bronzeville-IIT | 35th-Bronzeville-IIT (Green Line) | 41120  | true | false | false | true  | false | false | false | false | false | false | 
| 1337294637  | 30213   | N            | 35-Bronzeville-IIT (Harlem-bound) | 35th-Bronzeville-IIT | 35th-Bronzeville-IIT (Green Line) | 41120  | true | false | false | true  | false | false | false | false | false | false | 
| 1337294637  | 30246   | S            | 43rd (63rd-bound)                 | 43rd                 | 43rd (Green Line)                 | 41270  | true | false | false | true  | false | false | false | false | false | false | 
| 1337294637  | 30245   | N            | 43rd (Harlem-bound)               | 43rd                 | 43rd (Green Line)                 | 41270  | true | false | false | true  | false | false | false | false | false | false | 
| 1337294637  | 30025   | S            | 51st (63rd-bound)                 | 51st                 | 51st (Green Line)                 | 40130  | true | false | false | true  | false | false | false | false | false | false | 
| 1337294637  | 30024   | N            | 51st (Harlem-bound)               | 51st                 | 51st (Green Line)                 | 40130  | true | false | false | true  | false | false | false | false | false | false | 
```