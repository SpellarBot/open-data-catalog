# Elevation Benchmarks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/elevation-benchmarks-a8a8f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zgvr-7yfd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zgvr-7yfd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zgvr-7yfd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zgvr-7yfd |
| Name | Elevation Benchmarks |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | benchmarks, gis |
| Created | 2011-09-29T20:21:22Z |
| Publication Date | 2011-09-29T20:22:10Z |

## Description

The following dataset includes "Active Benchmarks," which are provided to facilitate the identification of City-managed standard benchmarks. Standard benchmarks are for public and private use in establishing a point in space. Note: The benchmarks are referenced to the Chicago City Datum = 0.00, (CCD = 579.88 feet above mean tide New York). The City of Chicago Department of Water Management?s (DWM) Topographic Benchmark is the source of the benchmark information contained in this online database. The information contained in the index card system was compiled by scanning the original cards, then transcribing some of this information to prepare a table and map. Over time, the DWM will contract services to field verify the data and update the index card system and this online database.This dataset was last updated September 2011. Coordinates are estimated. To view map, go to https://data.cityofchicago.org/Buildings/Elevation-Benchmarks-Map/kmt9-pg57 or for PDF map, go to http://cityofchicago.org/content/dam/city/depts/water/supp_info/Benchmarks/BMMap.pdf. Please read the Terms of Use: http://www.cityofchicago.org/city/en/narr/foia/data_disclaimer.html.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | benchmark_number               | BENCHMARK NUMBER               | text      | number      |
| Yes      | numeric metric | northing                       | NORTHING                       | number    | number      |
| Yes      | numeric metric | easting                        | EASTING                        | number    | number      |
| Yes      | numeric metric | elevation                      | ELEVATION                      | number    | number      |
| Yes      | series tag     | location_description           | LOCATION DESCRIPTION           | text      | text        |
| Yes      | series tag     | location_description_2         | LOCATION DESCRIPTION 2         | text      | text        |
| Yes      | series tag     | mark_description               | MARK DESCRIPTION               | text      | text        |
| Yes      | numeric metric | year_benchmark_elevation_fixed | YEAR BENCHMARK ELEVATION FIXED | number    | number      |
| Yes      | series tag     | book_number                    | BOOK NUMBER                    | text      | number      |
| No       |                | latitude                       | LATITUDE                       | number    | number      |
| No       |                | longitude                      | LONGITUDE                      | number    | number      |
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
series e:zgvr-7yfd d:2011-09-29T13:21:41.000Z t:book_number=0.000000 t:mark_description="THIS BENCH MADE PRIMARY BENCH FOR THE CITY OF CHICAGO. SEE ORDINANCE OF SEPT. 12, 1928, PAGE 3460 OF COUNCIL PROCEEDINGS." t:benchmark_number=1.000000 t:location_description="MARK CUT ON TOP OF BOTTOM STONE OF GRANITE BASE AT S.E. CORNER OF NORTHERN TRUST CO. BANK BUILDING 3.22' ABOVE SIDEWALK. CAISSONS TO ROCK." m:elevation=17.64 m:year_benchmark_elevation_fixed=1928 m:northing=1899922.177 m:easting=1175111.006

series e:zgvr-7yfd d:2011-09-29T13:21:41.000Z t:location_description_2="19 FEET S. OF THE N. LINE OF  E. CHICAGO AVENUE" t:book_number=482.000000 t:mark_description="BENCH SETTLED ABOUT 0.046 FEET BETWEEN 1920 AND 1931, ELEVATION PREVIOUS TO 1966 WAS 12.906
TOWER COURT WAS CHANGED TO N. MICHIGAN (TO THE WEST)" t:benchmark_number=9.000000 t:location_description="4 FEET E. OF E. LINE OF  MICHIGAN TO W." m:elevation=12.892 m:year_benchmark_elevation_fixed=1966 m:northing=1905789.999 m:easting=1177362.234

series e:zgvr-7yfd d:2011-09-29T13:21:41.000Z t:location_description_2="21.5 FEET N. OF E. PERSHING ROAD." t:book_number=68.000000 t:mark_description="ELEVATION PREVIOUS TO 1966 WAS 16.420" t:benchmark_number=13.000000 t:location_description="13 FEET E. OF THE W. LINE OF S. MICHIGAN AVENUE." m:elevation=16.307 m:year_benchmark_elevation_fixed=1966 m:northing=1879222.6 m:easting=1177801.084
```

## Meta Commands

```ls
metric m:northing p:double l:NORTHING t:dataTypeName=number

metric m:easting p:double l:EASTING t:dataTypeName=number

metric m:elevation p:float l:ELEVATION t:dataTypeName=number

metric m:year_benchmark_elevation_fixed p:float l:"YEAR BENCHMARK ELEVATION FIXED" t:dataTypeName=number

entity e:zgvr-7yfd l:"Elevation Benchmarks" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/zgvr-7yfd

property e:zgvr-7yfd t:meta.view v:id=zgvr-7yfd v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=100 v:name="Elevation Benchmarks" v:attribution="City of Chicago"

property e:zgvr-7yfd t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:zgvr-7yfd t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | benchmark_number | northing       | easting        | elevation | location_description                                                                                                                       | location_description_2                                                        | mark_description                                                                                                                                 | year_benchmark_elevation_fixed | book_number | latitude       | longitude       | 
| =========== | ================ | ============== | ============== | ========= | ========================================================================================================================================== | ============================================================================= | ================================================================================================================================================ | ============================== | =========== | ============== | =============== | 
| 1317302501  | 1.000000         | 1899922.177000 | 1175111.006000 | 17.640000 | MARK CUT ON TOP OF BOTTOM STONE OF GRANITE BASE AT S.E. CORNER OF NORTHERN TRUST CO. BANK BUILDING 3.22' ABOVE SIDEWALK. CAISSONS TO ROCK. |                                                                               | THIS BENCH MADE PRIMARY BENCH FOR THE CITY OF CHICAGO. SEE ORDINANCE OF SEPT. 12, 1928, PAGE 3460 OF COUNCIL PROCEEDINGS.                        | 1928.000000                    | 0.000000    | 41.88077079670 | -87.63246380610 | 
| 1317302501  | 9.000000         | 1905789.999000 | 1177362.234000 | 12.892000 | 4 FEET E. OF E. LINE OF MICHIGAN TO W.                                                                                                     | 19 FEET S. OF THE N. LINE OF E. CHICAGO AVENUE                                | BENCH SETTLED ABOUT 0.046 FEET BETWEEN 1920 AND 1931, ELEVATION PREVIOUS TO 1966 WAS 12.906 TOWER COURT WAS CHANGED TO N. MICHIGAN (TO THE WEST) | 1966.000000                    | 482.000000  | 41.89682165290 | -87.62401947060 | 
| 1317302501  | 13.000000        | 1879222.600000 | 1177801.084000 | 16.307000 | 13 FEET E. OF THE W. LINE OF S. MICHIGAN AVENUE.                                                                                           | 21.5 FEET N. OF E. PERSHING ROAD.                                             | ELEVATION PREVIOUS TO 1966 WAS 16.420                                                                                                            | 1966.000000                    | 68.000000   | 41.82390904620 | -87.62321473050 | 
| 1317302501  | 14.000000        | 1873844.031000 | 1177537.629000 | 16.222000 | 19 FEET W. OF E. LINE OF S. WABASH AVENUE.                                                                                                 | 6 FEET S. OF E. 47TH STREET.                                                  |                                                                                                                                                  | 1969.000000                    | 314.000000  | 41.80915576300 | -87.62434405390 | 
| 1317302501  | 16.000000        | 1868652.746000 | 1182490.604000 | 13.902000 | 76.5 FEET W. OF THE E. LINE OF COTTAGE GROVE AVENUE                                                                                        | 18 FEET S. OF THE S. LINE OF E. 55TH STREET TO THE EAST                       |                                                                                                                                                  | 1898.000000                    | 0.000000    | 41.79479689040 | -87.60633871640 | 
| 1317302501  | 19.000000        | 1884621.531000 | 1172107.075000 | 13.203000 | 10.6 FEET E. OF THE W. LINE OF S. UNION AVE.                                                                                               | 249.7 FEET N. OF W. 31 STREET                                                 | ELEVATION PREVIOUS TO 1966 WAS 13.205                                                                                                            | 1966.000000                    | 271.000000  | 41.83885144310 | -87.64394502040 | 
| 1317302501  | 23.000000        | 1868110.638000 | 1187896.299000 | 9.054000  | 5 FEET E. OF STONY ISLAND AVENUE                                                                                                           | 43 FEET S. OF E. 56TH STREET (6 FEET E. CURB OF STONY ISLAND AVENUE)          |                                                                                                                                                  | 1899.000000                    | 0.000000    | 41.79318214980 | -87.58653364070 | 
| 1317302501  | 25.000000        | 1860206.539000 | 1186739.434000 | 7.643000  | 12.7 FEET W. OF E. LINE OF DORCHESTER AVE                                                                                                  | 13.8 FEET S. OF N. LINE OF E. 68TH STREET. PRODUCED W.                        |                                                                                                                                                  | 1899.000000                    | 0.000000    | 41.77152015420 | -87.59102589200 | 
| 1317302501  | 28.000000        | 1856367.956000 | 1194705.084000 | 7.957000  | 9.5 FEET N. OF S. LINE OF E. 74TH ST.                                                                                                      | 5.8 FEET WESTERNLY AT RIGHT ANGLES FROM SOUTHWESTERLY LINE OF EXCHANGE AVENUE | MONUMENT BEDDED ON ROCK                                                                                                                          | 1973.000000                    | 368.000000  | 41.76079443690 | -87.56195325130 | 
| 1317302501  | 30.000000        | 1853176.397000 | 1198818.729000 | 9.138000  | 4 FEET W. OF BRANDON AVENUE                                                                                                                | 10 FEET N. OF S. LINE OF E. 79TH STREET                                       |                                                                                                                                                  | 1925.000000                    | 369.000000  | 41.75193437490 | -87.54698379840 | 
```