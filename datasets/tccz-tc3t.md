# Highway Mileage: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/highway-mileage-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/tccz-tc3t) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tccz-tc3t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tccz-tc3t/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tccz-tc3t |
| Name | Highway Mileage: Beginning 2008 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | mileage, jurisdiction, highway, road |
| Created | 2013-02-15T20:40:13Z |
| Publication Date | 2016-10-21T22:00:46Z |

## Description

The Highway Mileage Report is an annual publication that lists the mileage of roadway and maintenance jurisdiction/ownership of roadways within each municipality of New York State. Information is current as of the publication date.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | time           | year                             | Year                             | number    | number      |
| Yes      | series tag     | county                           | County                           | text      | text        |
| Yes      | series tag     | municipality                     | Municipality                     | text      | text        |
| Yes      | series tag     | nysdot_geocode                   | NYSDOT Geocode                   | text      | number      |
| Yes      | numeric metric | touring_route_mileage            | Touring Route Mileage            | number    | number      |
| Yes      | numeric metric | total_centerline_highway_mileage | Total Centerline Highway Mileage | number    | number      |
| Yes      | numeric metric | local_mileage                    | Local Mileage                    | number    | number      |
| Yes      | numeric metric | county_mileage                   | County Mileage                   | number    | number      |
| Yes      | numeric metric | nysdot_mileage                   | NYSDOT Mileage                   | number    | number      |
| Yes      | numeric metric | other_mileage                    | Other Mileage                    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tccz-tc3t d:2008-01-01T00:00:00.000Z t:county=ALBANY t:municipality="City of Albany" t:nysdot_geocode=2001 m:county_mileage=2.2 m:touring_route_mileage=44 m:other_mileage=23 m:total_centerline_highway_mileage=287.3 m:nysdot_mileage=24.2 m:local_mileage=237.9

series e:tccz-tc3t d:2009-01-01T00:00:00.000Z t:county=ALBANY t:municipality="City of Albany" t:nysdot_geocode=2001 m:county_mileage=2.24 m:touring_route_mileage=43.98 m:other_mileage=22.98 m:total_centerline_highway_mileage=287.96 m:nysdot_mileage=24.18 m:local_mileage=238.56

series e:tccz-tc3t d:2010-01-01T00:00:00.000Z t:county=ALBANY t:municipality="City of Albany" t:nysdot_geocode=2001 m:county_mileage=2.2 m:touring_route_mileage=44 m:other_mileage=23 m:total_centerline_highway_mileage=287.9 m:nysdot_mileage=24.2 m:local_mileage=238.4
```

## Meta Commands

```ls
metric m:touring_route_mileage p:float l:"Touring Route Mileage" d:"Touring route numbers are posted along a route and are used primarily as a motorist aid." t:dataTypeName=number

metric m:total_centerline_highway_mileage p:float l:"Total Centerline Highway Mileage" d:"The sum of all local and state highway mileage appears in this column." t:dataTypeName=number

metric m:local_mileage p:float l:"Local Mileage" d:"The sum of the town, village, city and county highway mileage for each minor civil division within the county." t:dataTypeName=number

metric m:county_mileage p:float l:"County Mileage" d:"County-owned highway centerline mileage that is located within each city, town, and village" t:dataTypeName=number

metric m:nysdot_mileage p:float l:"NYSDOT Mileage" d:"Highway centerline mileage for all roadway sections owned by the New York State Department of Transportation (NYSDOT)" t:dataTypeName=number

metric m:other_mileage p:float l:"Other Mileage" d:"Various other agencies, authorities, and commissions have responsibility for highways in the State, in addition to those owned by NYSDOT. These include non-DOT parkways, Reservation roads, Federal agency roads, institutional roads, and toll roads such as" t:dataTypeName=number

entity e:tccz-tc3t l:"Highway Mileage: Beginning 2008" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/tccz-tc3t

property e:tccz-tc3t t:meta.view v:id=tccz-tc3t v:category=Transportation v:attributionLink=https://www.dot.ny.gov/highway-data-services v:averageRating=0 v:name="Highway Mileage: Beginning 2008" v:attribution="New York State Department of Transportation"

property e:tccz-tc3t t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tccz-tc3t t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tccz-tc3t t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | county | municipality       | nysdot_geocode | touring_route_mileage | total_centerline_highway_mileage | local_mileage | county_mileage | nysdot_mileage | other_mileage | 
| ==== | ====== | ================== | ============== | ===================== | ================================ | ============= | ============== | ============== | ============= | 
| 2008 | ALBANY | City of Albany     | 2001           | 44                    | 287.3                            | 237.9         | 2.2            | 24.2           | 23            | 
| 2009 | ALBANY | City of Albany     | 2001           | 43.98                 | 287.96                           | 238.56        | 2.24           | 24.18          | 22.98         | 
| 2010 | ALBANY | City of Albany     | 2001           | 44                    | 287.9                            | 238.4         | 2.2            | 24.2           | 23            | 
| 2011 | ALBANY | City of Albany     | 2001           | 44.03                 | 288.25                           | 238.8         | 2.24           | 24.23          | 22.98         | 
| 2008 | ALBANY | City of Cohoes     | 2009           | 6.3                   | 63.5                             | 61.8          | 0              | 1.7            | 0             | 
| 2009 | ALBANY | City of Cohoes     | 2009           | 6.28                  | 63.43                            | 61.7          | 0              | 1.73           | 0             | 
| 2010 | ALBANY | City of Cohoes     | 2009           | 6.3                   | 63.6                             | 61.8          | 0              | 1.7            | 0             | 
| 2011 | ALBANY | City of Cohoes     | 2009           | 6.28                  | 63.56                            | 61.83         | 0              | 1.73           | 0             | 
| 2008 | ALBANY | City of Watervliet | 2060           | 6.2                   | 46.5                             | 37.2          | 0              | 2.6            | 6.7           | 
| 2009 | ALBANY | City of Watervliet | 2060           | 6.15                  | 46.25                            | 36.98         | 0              | 2.59           | 6.68          | 
```