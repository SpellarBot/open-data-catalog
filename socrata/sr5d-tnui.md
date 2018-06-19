# Addresses - Enterprise Addressing System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/addresses-enterprise-addressing-system-25546) |
| Metadata | [Link](https://data.sfgov.org/api/views/sr5d-tnui) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sr5d-tnui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sr5d-tnui/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sr5d-tnui |
| Name | Addresses - Enterprise Addressing System |
| Attribution | City and County of San Francisco |
| Category | Geographic Locations and Boundaries |
| Tags | eas, addresses, dbi, enterprise addressing system |
| Created | 2016-08-12T00:27:00Z |
| Publication Date | 2016-08-26T19:03:52Z |

## Description

Active base addresses from San Francisco's Enterprise Addressing System, This does not include sub-addresses, such as units. Updated nightly. See eas_addresses_with_units for records with units.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | eas_baseid            | EAS BaseID            | text      | number      |
| Yes      | numeric metric | cnn                   | CNN                   | number    | text        |
| No       |                | address               | Address               | text      | text        |
| No       |                | address_number        | Address Number        | text      | text        |
| No       |                | address_number_suffix | Address Number Suffix | text      | text        |
| Yes      | series tag     | street_name           | Street Name           | text      | text        |
| Yes      | series tag     | street_type           | Street Type           | text      | text        |
| Yes      | series tag     | zipcode               | Zipcode               | text      | text        |
| No       |                | longitude             | Longitude             | number    | number      |
| No       |                | latitude              | Latitude              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_number,address_number_suffix,longitude,latitude
```

## Data Commands

```ls
series e:sr5d-tnui d:2016-08-23T12:31:34.000Z t:eas_baseid=275531 t:zipcode=94115 t:street_name=SUTTER t:street_type=ST m:cnn=12338000

series e:sr5d-tnui d:2016-08-23T12:33:14.000Z t:eas_baseid=300312 t:zipcode=94121 t:street_name=CLEMENT t:street_type=ST m:cnn=4189000

series e:sr5d-tnui d:2016-08-23T12:35:39.000Z t:eas_baseid=366924 t:zipcode=94107 t:street_name=17TH t:street_type=ST m:cnn=779000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

entity e:sr5d-tnui l:"Addresses - Enterprise Addressing System" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/sr5d-tnui

property e:sr5d-tnui t:meta.view v:id=sr5d-tnui v:category="Geographic Locations and Boundaries" v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Addresses - Enterprise Addressing System" v:attribution="City and County of San Francisco"

property e:sr5d-tnui t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sr5d-tnui t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:sr5d-tnui t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | eas_baseid | cnn      | address            | address_number | address_number_suffix | street_name | street_type | zipcode | longitude     | latitude    | 
| =========== | ========== | ======== | ================== | ============== | ===================== | =========== | =========== | ======= | ============= | =========== | 
| 1471955494  | 275531     | 12338000 | 1901 SUTTER ST     | 1901           |                       | SUTTER      | ST          | 94115   |               |             | 
| 1471955594  | 300312     | 4189000  | 4150 CLEMENT ST    | 4150           |                       | CLEMENT     | ST          | 94121   |               |             | 
| 1471955739  | 366924     | 779000   | 1717 17TH ST       | 1717           |                       | 17TH        | ST          | 94107   |               |             | 
| 1492691691  | 274588     | 8246000  | 850 LEAVENWORTH ST | 850            |                       | LEAVENWORTH | ST          | 94109   | -122.41503808 | 37.78907653 | 
| 1492691691  | 274589     | 7575000  | 850 JONES ST       | 850            |                       | JONES       | ST          | 94109   | -122.41348647 | 37.78931973 | 
| 1492691691  | 274503     | 7597000  | 2436 JONES ST      | 2436           |                       | JONES       | ST          | 94133   | -122.41647271 | 37.80410557 | 
| 1471955967  | 483344     | 4631000  | 405 DE HARO ST     | 405            |                       | DE HARO     | ST          | 94107   |               |             | 
| 1471869935  | 485382     | 9123000  | 2560 MISSION ST    | 2560           |                       | MISSION     | ST          | 94110   |               |             | 
| 1471869935  | 485383     | 9123000  | 2564 MISSION ST    | 2564           |                       | MISSION     | ST          | 94110   |               |             | 
| 1471869935  | 485384     | 9123000  | 2568 MISSION ST    | 2568           |                       | MISSION     | ST          | 94110   |               |             | 
```