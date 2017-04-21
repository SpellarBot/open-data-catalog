# Capital District Bus Stops

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-district-bus-stops) |
| Metadata | [Link](https://data.ny.gov/api/views/wgnh-hpq9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wgnh-hpq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wgnh-hpq9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wgnh-hpq9 |
| Name | Capital District Bus Stops |
| Attribution | Capital District Transportation Authority |
| Category | Transportation |
| Tags | cdta, bus, stops, routes |
| Created | 2013-05-22T20:13:49Z |
| Publication Date | 2016-02-08T17:07:45Z |

## Description

Bus stops from the Capital District Transportation Authority

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | description          | Description          | text      | text        |
| Yes      | series tag  | stop_id              | Stop ID              | text      | number      |
| No       |             | longitude            | Longitude            | number    | number      |
| No       |             | latitude             | Latitude             | number    | number      |
| Yes      | series tag  | routes               | Routes               | text      | text        |
| Yes      | series tag  | municipality         | Municipality         | text      | text        |
| Yes      | series tag  | nearest_intersection | Nearest Intersection | text      | text        |
| Yes      | series tag  | bikerack             | Bikerack             | text      | text        |
| Yes      | series tag  | bench                | Bench                | text      | text        |
| Yes      | series tag  | shelter              | Shelter              | text      | text        |
| Yes      | series tag  | info_booth           | Info Booth           | text      | text        |
| Yes      | series tag  | signpost             | Signpost             | text      | text        |
| Yes      | series tag  | discontinued         | Discontinued         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:wgnh-hpq9 d:2016-02-08T09:06:45.000Z t:stop_id=1 t:shelter=No t:bench=No t:routes=22 t:description="550 BROADWAY (BRITISH AMERICAN REALTY)" t:bikerack=No t:municipality=COLONIE t:signpost=Yes t:info_booth=No t:discontinued=No t:nearest_intersection=UNKNOWN m:row_number.wgnh-hpq9=1

series e:wgnh-hpq9 d:2016-02-08T09:06:45.000Z t:stop_id=3 t:shelter=No t:bench=No t:routes=6 t:description="2ND AVE & S BERTHA ST" t:bikerack=No t:municipality=ALBANY t:signpost=Yes t:info_booth=No t:discontinued=No t:nearest_intersection=BERTHA m:row_number.wgnh-hpq9=2

series e:wgnh-hpq9 d:2016-02-08T09:06:45.000Z t:stop_id=5 t:shelter=No t:bench=No t:routes=6 t:description="2ND AVE & JEANETTE ST" t:bikerack=No t:municipality=ALBANY t:signpost=Yes t:info_booth=No t:discontinued=No t:nearest_intersection=JEANETTE m:row_number.wgnh-hpq9=3
```

## Meta Commands

```ls
metric m:row_number.wgnh-hpq9 p:long l:"Row Number"

entity e:wgnh-hpq9 l:"Capital District Bus Stops" t:attribution="Capital District Transportation Authority" t:url=https://data.ny.gov/api/views/wgnh-hpq9

property e:wgnh-hpq9 t:meta.view v:id=wgnh-hpq9 v:category=Transportation v:averageRating=0 v:name="Capital District Bus Stops" v:attribution="Capital District Transportation Authority"

property e:wgnh-hpq9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wgnh-hpq9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:wgnh-hpq9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | description                            | stop_id | longitude | latitude | routes  | municipality | nearest_intersection | bikerack | bench | shelter | info_booth | signpost | discontinued | 
| =========== | ====================================== | ======= | ========= | ======== | ======= | ============ | ==================== | ======== | ===== | ======= | ========== | ======== | ============ | 
| 1454922405  | 550 BROADWAY (BRITISH AMERICAN REALTY) | 1       | -73.71619 | 42.70225 | 22      | COLONIE      | UNKNOWN              | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | 2ND AVE & S BERTHA ST                  | 3       | -73.77847 | 42.63922 | 6       | ALBANY       | BERTHA               | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | 2ND AVE & JEANETTE ST                  | 5       | -73.78055 | 42.63931 | 6       | ALBANY       | JEANETTE             | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | 3RD AVE & 4TH ST                       | 6       | -73.70974 | 42.71027 | 22      | WATERVLIET   | 4TH                  | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | 3RD AVE & 5TH ST                       | 7       | -73.70847 | 42.71185 | 22      | WATERVLIET   | 5TH                  | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | 3RD AVE & 7TH ST                       | 10      | -73.70626 | 42.71447 | 22      | WATERVLIET   | 7TH                  | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | BROADWAY & 1ST                         | 11      | -73.71184 | 42.70737 | 22      | COLONIE      | SCHUYLER             | No       | Yes   | Yes     | No         | Yes      | No           | 
| 1454922405  | SOUTHERN BLVD & DELAWARE AVE           | 13      | -73.78548 | 42.6392  | 18      | ALBANY       | DELAWARE             | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | BROADWAY & 14TH ST                     | 14      | -73.70039 | 42.72444 | 22      | WATERVLIET   | 14TH                 | No       | No    | No      | No         | Yes      | No           | 
| 1454922405  | 1541 BROADWAY (SENIOR CITIZEN CENTER)  | 15      | -73.70014 | 42.72651 | 22, 815 | WATERVLIET   | BROADWAY             | No       | Yes   | Yes     | No         | Yes      | No           | 
```