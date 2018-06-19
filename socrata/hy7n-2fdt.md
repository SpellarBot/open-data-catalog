# Freight Cars Moved in Carfloat Operations, Port Authority of NY NJ: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freight-cars-moved-in-carfloat-operations-port-authority-of-ny-nj-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/hy7n-2fdt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hy7n-2fdt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hy7n-2fdt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hy7n-2fdt |
| Name | Freight Cars Moved in Carfloat Operations, Port Authority of NY NJ: Beginning 2009 |
| Attribution | Port Authority of New York and New Jersey |
| Category | Transportation |
| Tags | rail, nynjr, carfloat, port authority |
| Created | 2013-05-10T12:53:19Z |
| Publication Date | 2016-03-15T17:44:15Z |

## Description

This dataset provides volume of loaded freight rail cars transported between NY and NJ by New York New Jersey Rail, a carfloat operation owned by the Port Authority of NY & NJ. Total volume, including empty cars, is estimated at twice the volume of loaded.  2013 entry is year-to-date volume at this time

## Columns

```ls
| Included | Schema Type    | Field Name                                                      | Name                             | Data Type | Render Type |
| ======== | ============== | =============================================================== | ================================ | ========= | =========== |
| No       |                | year                                                            | Year                             | number    | number      |
| No       |                | quarter                                                         | Quarter                          | text      | text        |
| Yes      | numeric metric | volume_number_of_loaded_rail_cars                               | Volume of Loaded Rail Cars Moved | number    | number      |
| Yes      | numeric metric | floats_number_of_roundtrips_of_nynjr_carfloat_across_the_harbor | Floats - Number of Round Trips   | number    | number      |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:hy7n-2fdt d:2008-10-01T00:00:00.000Z m:volume_number_of_loaded_rail_cars=873 m:floats_number_of_roundtrips_of_nynjr_carfloat_across_the_harbor=126

series e:hy7n-2fdt d:2009-10-01T00:00:00.000Z m:volume_number_of_loaded_rail_cars=1229 m:floats_number_of_roundtrips_of_nynjr_carfloat_across_the_harbor=164

series e:hy7n-2fdt d:2010-10-01T00:00:00.000Z m:volume_number_of_loaded_rail_cars=1514 m:floats_number_of_roundtrips_of_nynjr_carfloat_across_the_harbor=193
```

## Meta Commands

```ls
metric m:volume_number_of_loaded_rail_cars p:integer l:"Volume of Loaded Rail Cars Moved" d:"Number of loaded rail cars" t:dataTypeName=number

metric m:floats_number_of_roundtrips_of_nynjr_carfloat_across_the_harbor p:double l:"Floats - Number of Round Trips" d:"Number of round trips of NYNJR carfloat across the harbor" t:dataTypeName=number

entity e:hy7n-2fdt l:"Freight Cars Moved in Carfloat Operations, Port Authority of NY NJ:  Beginning 2009" t:attribution="Port Authority of New York and New Jersey" t:url=https://data.ny.gov/api/views/hy7n-2fdt

property e:hy7n-2fdt t:meta.view v:id=hy7n-2fdt v:category=Transportation v:averageRating=0 v:name="Freight Cars Moved in Carfloat Operations, Port Authority of NY NJ:  Beginning 2009" v:attribution="Port Authority of New York and New Jersey"

property e:hy7n-2fdt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hy7n-2fdt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:hy7n-2fdt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | quarter | volume_number_of_loaded_rail_cars | floats_number_of_roundtrips_of_nynjr_carfloat_across_the_harbor | 
| ==== | ======= | ================================= | =============================================================== | 
| 2009 |         | 873                               | 126                                                             | 
| 2010 |         | 1229                              | 164                                                             | 
| 2011 |         | 1514                              | 193                                                             | 
| 2012 |         | 1495                              | 181                                                             | 
| 2013 | Q1      | 554                               | 62.5                                                            | 
| 2013 | Q2      | 906                               | 103.5                                                           | 
| 2013 | Q3      | 745                               | 71                                                              | 
| 2013 | Q4      | 810                               | 71.5                                                            | 
| 2014 | Q1      | 1070                              | 89                                                              | 
| 2014 | Q2      | 1025                              | 77                                                              | 
```