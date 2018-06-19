# Nutmeg Network Site List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nutmeg-network-site-list) |
| Metadata | [Link](https://data.ct.gov/api/views/dhpd-c9cf) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/dhpd-c9cf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/dhpd-c9cf/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | dhpd-c9cf |
| Name | Nutmeg Network Site List |
| Category | Government |
| Tags | btop, nutmeg, fiber, cen, psdn |
| Created | 2014-03-26T12:50:11Z |
| Publication Date | 2014-03-26T13:02:07Z |

## Description

On September 13, 2010, the Bureau of Enterprise Systems and Technology (BEST) received approval of its application for federal stimulus funding to expand state broadband access and network capacity.
 
The application, created and submitted in partnership with the Department of Public Safety (DPS) and the Connecticut Education Network (CEN), will enable the State to enhance network connections between schools and libraries to the high speed Connecticut Education Network (CEN) and improve public safety communications capability across the state.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | poi_site_id   | POI Site ID   | text      | number      |
| Yes      | series tag  | geocode_label | GEOCODE_LABEL | text      | text        |
| Yes      | series tag  | site_name     | Site Name     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dhpd-c9cf d:2014-03-26T05:50:27.000Z t:geocode_label=Fire t:poi_site_id=1548 t:site_name="Middletown Fire Dept" m:row_number.dhpd-c9cf=1

series e:dhpd-c9cf d:2014-03-26T05:50:27.000Z t:geocode_label=PSAP t:poi_site_id=1101 t:site_name="West Hartford Police Dept" m:row_number.dhpd-c9cf=2

series e:dhpd-c9cf d:2014-03-26T05:50:27.000Z t:geocode_label=CEN-HUBSITE t:poi_site_id=2124 t:site_name="U Conn Stamford Hub Site" m:row_number.dhpd-c9cf=3
```

## Meta Commands

```ls
metric m:row_number.dhpd-c9cf p:long l:"Row Number"

entity e:dhpd-c9cf l:"Nutmeg Network Site List" t:url=https://data.ct.gov/api/views/dhpd-c9cf

property e:dhpd-c9cf t:meta.view v:id=dhpd-c9cf v:category=Government v:attributionLink="http://www.ct.gov/best/cwp/view.asp?a=3790&Q=446266" v:averageRating=0 v:name="Nutmeg Network Site List"

property e:dhpd-c9cf t:meta.view.license v:name="Public Domain"

property e:dhpd-c9cf t:meta.view.owner v:id=cttg-mwt7 v:profileImageUrlMedium=/api/users/cttg-mwt7/profile_images/THUMB v:profileImageUrlLarge=/api/users/cttg-mwt7/profile_images/LARGE v:screenName="John Vittner" v:profileImageUrlSmall=/api/users/cttg-mwt7/profile_images/TINY v:displayName="John Vittner"

property e:dhpd-c9cf t:meta.view.tableauthor v:id=cttg-mwt7 v:profileImageUrlMedium=/api/users/cttg-mwt7/profile_images/THUMB v:profileImageUrlLarge=/api/users/cttg-mwt7/profile_images/LARGE v:screenName="John Vittner" v:profileImageUrlSmall=/api/users/cttg-mwt7/profile_images/TINY v:roleName=publisher v:displayName="John Vittner"
```

## Top Records

```ls
| :updated_at | poi_site_id | geocode_label  | site_name                 | 
| =========== | =========== | ============== | ========================= | 
| 1395813027  | 1548        | Fire           | Middletown Fire Dept      | 
| 1395813027  | 1101        | PSAP           | West Hartford Police Dept | 
| 1395813027  | 2124        | CEN-HUBSITE    | U Conn Stamford Hub Site  | 
| 1395813027  | 1576        | DESPP Facility | North Central CMED        | 
| 1395813027  | 1393        | Fire           | Old Lyme Fire             | 
| 1395813027  | 2109        | Library        | East Lyme Public Library  | 
| 1395813027  | 2002        | K-12           | Barkhamsted Elementary    | 
| 1395813027  | 1447        | Fire           | Quinebaug Fire            | 
| 1395813027  | 1498        | Fire           | Wolcott Fire FD Co 1      | 
| 1395813027  | 2021        | K-12           | Granby BOE                | 
```