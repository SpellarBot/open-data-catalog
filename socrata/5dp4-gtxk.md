# Boiler Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boiler-permits) |
| Metadata | [Link](https://data.sfgov.org/api/views/5dp4-gtxk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5dp4-gtxk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5dp4-gtxk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5dp4-gtxk |
| Name | Boiler Permits |
| Category | Housing and Buildings |
| Created | 2016-04-06T22:29:09Z |
| Publication Date | 2016-08-04T16:01:43Z |

## Description

This data set pertains to all permits to operate boilers. Data includes details on application/permit numbers, job addresses, supervisorial districts, and the current status of the applications. Data is uploaded weekly by DBI. Users can access permit information online through DBI?s Permit Tracking System which is 24/7 at www.sfdbi.org/dbipts.

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                                | Data Type | Render Type |
| ======== | =========== | ================================= | =================================== | ========= | =========== |
| Yes      | series tag  | permit_number                     | Permit Number                       | text      | text        |
| Yes      | time        | application_date                  | Application Date                    | date      | date        |
| Yes      | series tag  | block                             | Block                               | text      | text        |
| Yes      | series tag  | lot                               | Lot                                 | text      | text        |
| Yes      | series tag  | street_number                     | Street Number                       | text      | text        |
| Yes      | series tag  | street_number_suffix              | Street Number Suffix                | text      | text        |
| Yes      | series tag  | street_name                       | Street Name                         | text      | text        |
| Yes      | series tag  | street_suffix                     | Street Suffix                       | text      | text        |
| Yes      | series tag  | description                       | Description                         | text      | text        |
| Yes      | series tag  | status                            | Status                              | text      | text        |
| Yes      | series tag  | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text      | text        |
| Yes      | series tag  | supervisor_district               | Supervisor District                 | text      | text        |
| Yes      | series tag  | zipcode                           | Zipcode                             | text      | text        |
```

## Time Field

```ls
Value = application_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:5dp4-gtxk d:2016-07-14T00:00:00.000Z t:permit_number=88931 t:neighborhoods_analysis_boundaries=Tenderloin t:status=issued t:description="permit to operate boiler" t:zipcode=94109 t:street_name=Larkin t:street_suffix=St t:lot=005 t:block=0740 t:street_number=633 t:supervisor_district=6 m:row_number.5dp4-gtxk=1

series e:5dp4-gtxk d:2016-07-14T00:00:00.000Z t:permit_number=88932 t:neighborhoods_analysis_boundaries="Nob Hill" t:status=issued t:description="permit to operate boiler" t:zipcode=94108 t:street_name=Taylor t:street_suffix=St t:lot=022 t:block=0254 t:street_number=920 t:supervisor_district=3 m:row_number.5dp4-gtxk=2

series e:5dp4-gtxk d:2016-07-14T00:00:00.000Z t:permit_number=88933 t:neighborhoods_analysis_boundaries=Mission t:status=issued t:description="permit to operate boiler" t:zipcode=94110 t:street_name=Guerrero t:street_suffix=St t:lot=063 t:block=3588 t:street_number=625 t:supervisor_district=8 m:row_number.5dp4-gtxk=3
```

## Meta Commands

```ls
metric m:row_number.5dp4-gtxk p:long l:"Row Number"

entity e:5dp4-gtxk l:"Boiler Permits" t:url=https://data.sfgov.org/api/views/5dp4-gtxk

property e:5dp4-gtxk t:meta.view v:id=5dp4-gtxk v:category="Housing and Buildings" v:averageRating=0 v:name="Boiler Permits"

property e:5dp4-gtxk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5dp4-gtxk t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:5dp4-gtxk t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| permit_number | application_date | block | lot  | street_number | street_number_suffix | street_name | street_suffix | description              | status | neighborhoods_analysis_boundaries | supervisor_district | zipcode | 
| ============= | ================ | ===== | ==== | ============= | ==================== | =========== | ============= | ======================== | ====== | ================================= | =================== | ======= | 
| 88931         | 1468454400       | 0740  | 005  | 633           |                      | Larkin      | St            | permit to operate boiler | issued | Tenderloin                        | 6                   | 94109   | 
| 88932         | 1468454400       | 0254  | 022  | 920           |                      | Taylor      | St            | permit to operate boiler | issued | Nob Hill                          | 3                   | 94108   | 
| 88933         | 1468454400       | 3588  | 063  | 625           |                      | Guerrero    | St            | permit to operate boiler | issued | Mission                           | 8                   | 94110   | 
| 88934         | 1468454400       | 0843  | 008  | 600           |                      | Page        | St            | permit to operate boiler | issued | Hayes Valley                      | 5                   | 94117   | 
| 88935         | 1468454400       | 3709  | 008  | 450           |                      | Mission     | St            | permit to operate boiler | issued | Financial District/South Beach    | 6                   | 94105   | 
| 88936         | 1468454400       | 3709  | 008  | 450           |                      | Mission     | St            | permit to operate boiler | issued | Financial District/South Beach    | 6                   | 94105   | 
| 88937         | 1468454400       | 0578  | 011A | 2090          |                      | Pacific     | Ave           | permit to operate boiler | issued | Pacific Heights                   | 2                   | 94109   | 
| 88938         | 1468454400       | 0578  | 011A | 2090          |                      | Pacific     | Ave           | permit to operate boiler | issued | Pacific Heights                   | 2                   | 94109   | 
| 88939         | 1468454400       | 3730  | 051  | 73            |                      | Sumner      | St            | permit to operate boiler | issued | South of Market                   | 6                   | 94103   | 
| 88940         | 1468454400       | 3730  | 051  | 73            |                      | Sumner      | St            | permit to operate boiler | issued | South of Market                   | 6                   | 94103   | 
```