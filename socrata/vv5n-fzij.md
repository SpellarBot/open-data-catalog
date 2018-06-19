# Hudson River Park Public Facilities & Points of Interest

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hudson-river-park-public-facilities-points-of-interest) |
| Metadata | [Link](https://data.ny.gov/api/views/vv5n-fzij) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vv5n-fzij/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vv5n-fzij/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vv5n-fzij |
| Name | Hudson River Park Public Facilities & Points of Interest |
| Attribution | Hudson River Park Trust (HRPT) |
| Category | Recreation |
| Tags | hrpt, public facilities |
| Created | 2014-11-04T15:36:26Z |
| Publication Date | 2015-12-23T17:50:32Z |

## Description

A list of facilities and points of interest within Hudson River Park that are open to the public, along with a description of what each is used for, and its location.  The list is organized by the facility?s use.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | facility_use            | Facility Use            | text      | text        |
| Yes      | series tag  | facility_operator       | Facility Operator       | text      | text        |
| Yes      | series tag  | facility_name           | Facility Name           | text      | text        |
| Yes      | series tag  | facility_locale         | Facility Locale         | text      | text        |
| Yes      | series tag  | facility_street_address | Facility Street Address | text      | text        |
| Yes      | series tag  | facility_city           | Facility City           | text      | text        |
| Yes      | series tag  | facility_state          | Facility State          | text      | text        |
| Yes      | series tag  | facility_zip_code       | Facility Zip Code       | text      | number      |
| No       |             | latitude                | Latitude                | number    | number      |
| No       |             | longitude               | Longitude               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:vv5n-fzij d:2015-12-18T11:53:38.000Z t:facility_city="New York" t:facility_name="Village Community Boathouse" t:facility_street_address="343 West St." t:facility_zip_code=10014 t:facility_operator="Village Community Boathouse" t:facility_use="Boat Building" t:facility_locale="Pier 40" t:facility_state=NY m:row_number.vv5n-fzij=1

series e:vv5n-fzij d:2015-12-18T11:53:38.000Z t:facility_city="New York" t:facility_name="The Pier, Park & Playground Baseball Diamonds" t:facility_street_address="343 West St." t:facility_zip_code=10014 t:facility_operator="The Pier, Park & Playground Association" t:facility_use=Baseball t:facility_locale="Pier 40" t:facility_state=NY m:row_number.vv5n-fzij=2

series e:vv5n-fzij d:2015-12-18T11:53:38.000Z t:facility_city="New York" t:facility_name="Basketball court at Chelsea Waterside" t:facility_street_address="23rd st. & 11th ave" t:facility_zip_code=10011 t:facility_operator="Hudson River Park Trust" t:facility_use=Basketball t:facility_locale="Chelsea Waterside" t:facility_state=NY m:row_number.vv5n-fzij=3
```

## Meta Commands

```ls
metric m:row_number.vv5n-fzij p:long l:"Row Number"

entity e:vv5n-fzij l:"Hudson River Park Public Facilities & Points of Interest" t:attribution="Hudson River Park Trust (HRPT)" t:url=https://data.ny.gov/api/views/vv5n-fzij

property e:vv5n-fzij t:meta.view v:id=vv5n-fzij v:category=Recreation v:attributionLink=http://www.hudsonriverpark.org/explore-the-park v:averageRating=0 v:name="Hudson River Park Public Facilities & Points of Interest" v:attribution="Hudson River Park Trust (HRPT)"

property e:vv5n-fzij t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vv5n-fzij t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vv5n-fzij t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | facility_use     | facility_operator                       | facility_name                                 | facility_locale               | facility_street_address | facility_city | facility_state | facility_zip_code | latitude  | longitude  | 
| =========== | ================ | ======================================= | ============================================= | ============================= | ======================= | ============= | ============== | ================= | ========= | ========== | 
| 1450439618  | Boat Building    | Village Community Boathouse             | Village Community Boathouse                   | Pier 40                       | 343 West St.            | New York      | NY             | 10014             | 40.728472 | -74.013719 | 
| 1450439618  | Baseball         | The Pier, Park & Playground Association | The Pier, Park & Playground Baseball Diamonds | Pier 40                       | 343 West St.            | New York      | NY             | 10014             | 40.729472 | -74.012664 | 
| 1450439618  | Basketball       | Hudson River Park Trust                 | Basketball court at Chelsea Waterside         | Chelsea Waterside             | 23rd st. & 11th ave     | New York      | NY             | 10011             | 40.749542 | -74.007158 | 
| 1450439618  | Basketball       | Hudson River Park Trust                 | Basketball court at Harrison Street           | West St. & Harrison st. court | West St. & Harrison st  | New York      | NY             | 10013             | 40.718792 | -74.012931 | 
| 1450439618  | Basketball       | Hudson River Park Trust                 | Basketball court at Canal Street              | West st. & Canal st. court    | West st. & Canal st     | New York      | NY             | 10013             | 40.725614 | -74.011525 | 
| 1450439618  | Batting cages    | Chelsea Piers                           | Chelsea Piers Batting cages                   | Chelsea Piers                 | 62 Chelsea Piers        | New York      | NY             | 10011             | 40.746814 | -74.0086   | 
| 1450439618  | Beach Volleyball | Manhattan Youth                         | Manhattan Youth Beach Volleyball Court        | Pier 25                       | 225 West St             | New York      | NY             | 10013             | 40.720392 | -74.014811 | 
| 1450439618  | Bicycle Rental   | Blazing Saddles                         | Blazing Saddles Bike Rentals and Tours        | Pier 84                       | W. 44th Street          | New York      | NY             | 10036             | 40.7635   | -74.0004   | 
| 1450439618  | Boat Excursions  | Spirit Cruises                          | Spirit Cruises                                | Chelsea Piers                 | 62 Chelsea Piers        | New York      | NY             | 10011             | 40.746814 | -74.0086   | 
| 1450439618  | Boat Excursions  | Bateaux New York                        | Bateaux New York                              | Chelsea Piers                 | 62 Chelsea Piers        | New York      | NY             | 10011             | 40.746814 | -74.0086   | 
```