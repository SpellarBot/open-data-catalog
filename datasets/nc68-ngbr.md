# City Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-facilities-ecad6) |
| Metadata | [Link](https://data.sfgov.org/api/views/nc68-ngbr) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nc68-ngbr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nc68-ngbr/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nc68-ngbr |
| Name | City Facilities |
| Attribution | City and County of San Francisco |
| Category | City Infrastructure |
| Tags | facility, public buildings |
| Created | 2016-09-02T20:58:27Z |
| Publication Date | 2017-02-03T19:45:45Z |

## Description

City-owned and leased facilities maintained in the City's Facility System of Record (FSR). This dataset was developed through a process involving some of the primary stewards for the facility data and their stakeholders. It is meant to be a living reference and will be maintained and updated through established workflows and processes over time.  You can access the attached User Guide for more detail by clicking the red About button and scrolling to attachments.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | facility_id     | facility_id     | text      | number      |
| Yes      | series tag     | common_name     | common_name     | text      | text        |
| No       |                | address         | address         | text      | text        |
| Yes      | series tag     | city            | city            | text      | text        |
| Yes      | series tag     | zip_code        | zip_code        | text      | text        |
| Yes      | series tag     | block_lot       | block_lot       | text      | text        |
| Yes      | series tag     | owned_leased    | owned_leased    | text      | text        |
| Yes      | series tag     | dept_id         | dept_id         | text      | number      |
| Yes      | series tag     | department_name | department_name | text      | text        |
| Yes      | numeric metric | gross_sq_ft     | gross_sq_ft     | number    | number      |
| Yes      | series tag     | longitude       | longitude       | text      | text        |
| Yes      | series tag     | latitude        | latitude        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:nc68-ngbr d:2017-03-10T22:59:12.000Z t:dept_id=38 t:zip_code=94158 t:owned_leased=Own t:block_lot=8719007 t:common_name="Bureau of Fire Investigation" t:longitude=-122.389375556 t:latitude=37.772271403 t:department_name="Fire Department" t:facility_id=139 t:city="San Francisco" m:gross_sq_ft=60000

series e:nc68-ngbr d:2017-03-10T22:59:12.000Z t:dept_id=77 t:zip_code=94124 t:owned_leased=Own t:block_lot=4711006 t:common_name="Earl P. Mills Community Center" t:longitude=-122.384001886 t:latitude=37.73416123 t:department_name="Dept Of Public Works" t:facility_id=625 t:city="San Francisco" m:gross_sq_ft=15000

series e:nc68-ngbr d:2017-03-10T22:59:12.000Z t:dept_id=38 t:zip_code=94133 t:owned_leased=Own t:block_lot=0077024 t:common_name="Fire Station #28" t:longitude=-122.409351508 t:latitude=37.802547875 t:department_name="Fire Department" t:facility_id=710 t:city="San Francisco" m:gross_sq_ft=9350
```

## Meta Commands

```ls
metric m:gross_sq_ft p:integer l:gross_sq_ft d:"Gross square footage of facility (original source: FRRM). Note: Incomplete data, updating as values are determined." t:dataTypeName=number

entity e:nc68-ngbr l:"City Facilities" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/nc68-ngbr

property e:nc68-ngbr t:meta.view v:id=nc68-ngbr v:category="City Infrastructure" v:attributionLink=http://data.sfgov.org v:averageRating=0 v:name="City Facilities" v:attribution="City and County of San Francisco"

property e:nc68-ngbr t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nc68-ngbr t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:nc68-ngbr t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | facility_id | common_name                        | address                   | city          | zip_code | block_lot | owned_leased | dept_id | department_name      | gross_sq_ft | longitude      | latitude     | 
| =========== | =========== | ================================== | ========================= | ============= | ======== | ========= | ============ | ======= | ==================== | =========== | ============== | ============ | 
| 1489186752  | 352         | Cabin 31                           | 32560 Mather Rd           | Groveland     | 95321    |           | Own          | 49      | Rec And Park Com     |             | -119.853737731 | 37.880830367 | 
| 1489186752  | 216         | Building 1071                      | 1071 North Access Road    | San Francisco | 94128    |           | Own          | 34      | Airport Commission   |             | -122.386244533 | 37.616302147 | 
| 1489186752  | 139         | Bureau of Fire Investigation       | 1275 3rd St               | San Francisco | 94158    | 8719007   | Own          | 38      | Fire Department      | 60000       | -122.389375556 | 37.772271403 | 
| 1489186752  | 301         | Cabin #27                          | 32560 Mather Rd           | Groveland     | 95321    |           | Own          | 49      | Rec And Park Com     |             | -119.853737731 | 37.880830367 | 
| 1489186752  | 563         | Harry Tracy Water Filtration       | 2901 Crystal Springs Rd   | San Mateo     | 94066    |           | Own          | 47      | Public Utilities Com |             | -122.4244692   | 37.6020742   | 
| 1489186752  | 625         | Earl P. Mills Community Center     | 100 Whitney Young Circle  | San Francisco | 94124    | 4711006   | Own          | 77      | Dept Of Public Works | 15000       | -122.384001886 | 37.73416123  | 
| 1489186752  | 710         | Fire Station #28                   | 1814 Stockton St          | San Francisco | 94133    | 0077024   | Own          | 38      | Fire Department      | 9350        | -122.409351508 | 37.802547875 | 
| 1489186752  | 1664        | Structural Maint Multi-trade Bldg. | 100 Martin Luther King Dr | San Francisco | 94117    | 1263011   | Own          | 49      | Rec And Park Com     |             | -122.481026721 | 37.769068782 | 
| 1489186752  | 3210        | LAGUNA HONDA - Utils/Equipment     | 375 Laguna Honda Blvd     | San Francisco | 94131    | 2842007   | Own          | 73      | Public Health        |             | -122.456415728 | 37.749624065 | 
| 1489186752  | 591         | Douglass Restrooms                 | 1100 Douglass St          | San Francisco | 94131    | 7500001   | Own          | 49      | Rec And Park Com     |             | -122.438435938 | 37.747820793 | 
```