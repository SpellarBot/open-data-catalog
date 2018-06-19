# Electrical Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electrical-permits) |
| Metadata | [Link](https://data.sfgov.org/api/views/ftty-kx6y) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ftty-kx6y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ftty-kx6y/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ftty-kx6y |
| Name | Electrical Permits |
| Category | Housing and Buildings |
| Created | 2016-04-06T17:57:54Z |
| Publication Date | 2016-08-04T15:59:51Z |

## Description

This data set pertains to all types of electrical permits. Data includes details on application/permit numbers, job addresses, supervisorial districts, and the current status of the applications. Data is uploaded weekly by DBI. Users can access permit information online through DBI?s Permit Tracking System which is 24/7 at www.sfdbi.org/dbipts.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type | Render Type |
| ======== | ============== | ================================= | =================================== | ========= | =========== |
| Yes      | series tag     | permit_number                     | Permit Number                       | text      | text        |
| Yes      | time           | application_creation_date         | Application Creation Date           | date      | date        |
| Yes      | series tag     | block                             | Block                               | text      | text        |
| Yes      | series tag     | lot                               | Lot                                 | text      | text        |
| Yes      | series tag     | street_number                     | Street Number                       | text      | text        |
| Yes      | series tag     | street_number_suffix              | Street Number Suffix                | text      | text        |
| Yes      | series tag     | street_name                       | Street Name                         | text      | text        |
| Yes      | series tag     | street_suffix                     | Street Suffix                       | text      | text        |
| Yes      | numeric metric | unit                              | Unit                                | number    | text        |
| Yes      | series tag     | unit_suffix                       | Unit Suffix                         | text      | text        |
| Yes      | series tag     | description                       | Description                         | text      | text        |
| Yes      | series tag     | status                            | Status                              | text      | text        |
| Yes      | series tag     | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text      | text        |
| Yes      | series tag     | supervisor_district               | Supervisor District                 | text      | text        |
| Yes      | series tag     | zipcode                           | Zipcode                             | text      | text        |
```

## Time Field

```ls
Value = application_creation_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:ftty-kx6y d:2003-05-29T00:00:00.000Z t:permit_number=E200305298470 t:neighborhoods_analysis_boundaries=Marina t:status=complete t:description="1 light  1 switch  1 service feeders: 19/40  19 meters" t:zipcode=94123 t:street_name=Toledo t:street_suffix=Wy t:lot=027 t:block=0466A t:street_number=96 t:supervisor_district=2 m:unit=0

series e:ftty-kx6y d:2006-10-27T00:00:00.000Z t:permit_number=EW20061027721 t:neighborhoods_analysis_boundaries="Inner Richmond" t:status=complete t:description="temporary office plug. one plug. approximately [scope of work does not include residential electric space heater installation.]" t:zipcode=94118 t:street_name=12th t:street_suffix=Av t:lot=009 t:block=1346 t:street_number=3 t:supervisor_district=2 m:unit=3

series e:ftty-kx6y d:2006-09-26T00:00:00.000Z t:permit_number=EW20060926983 t:status=complete t:description="install new subfeed from existing main panel; install new 30 circuit panel; install 21 circuits; install 34 switches; install 44 receptacles; install 24 fixtures [scope of work does not include residential electric space heater installation.]" t:street_name="Buena Vista East" t:street_suffix=Av t:lot=005 t:block=1258 t:street_number=145 m:unit=0
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

entity e:ftty-kx6y l:"Electrical Permits" t:url=https://data.sfgov.org/api/views/ftty-kx6y

property e:ftty-kx6y t:meta.view v:id=ftty-kx6y v:category="Housing and Buildings" v:averageRating=0 v:name="Electrical Permits"

property e:ftty-kx6y t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ftty-kx6y t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:ftty-kx6y t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| permit_number | application_creation_date | block | lot  | street_number | street_number_suffix | street_name  | street_suffix | unit | unit_suffix | description                                                                                                                                                                                                        | status   | neighborhoods_analysis_boundaries | supervisor_district | zipcode | 
| ============= | ========================= | ===== | ==== | ============= | ==================== | ============ | ============= | ==== | =========== | ================================================================================================================================================================================================================== | ======== | ================================= | =================== | ======= | 
| E200409037102 | 1094169600                | 0526  | 021  | 2550          |                      | Van Ness     | Av            |      |             | install 3p/50a load center for utility room.                                                                                                                                                                       | complete | Russian Hill                      | 2                   | 94109   | 
| E200303285827 | 1048809600                | 3252  | 010A | 261           |                      | San Fernando | Wy            |      |             | 200 amp. service & rewiring the whole house                                                                                                                                                                        | complete | West of Twin Peaks                | 7                   | 94127   | 
| EW20090507045 | 1241654400                | 3076A | 008  | 55            |                      | Yerba Buena  | Av            |      |             | install four new fluorescent fixtures in garage area.                                                                                                                                                              | expired  | West of Twin Peaks                | 7                   | 94127   | 
| E200305298470 | 1054166400                | 0466A | 027  | 96            |                      | Toledo       | Wy            | 0    |             | 1 light 1 switch 1 service feeders: 19/40 19 meters                                                                                                                                                                | complete | Marina                            | 2                   | 94123   | 
| EW20120405321 | 1333584000                | 3010  | 061  | 733           |                      | Myra         | Wy            |      |             | main electrical service upgrade to 100 amp                                                                                                                                                                         | complete | West of Twin Peaks                | 7                   | 94127   | 
| E200311175693 | 1069027200                | 1566  | 006  | 525           | A                    | 23rd         | Av            |      |             | install 200amp service two meters overhead                                                                                                                                                                         | complete | Outer Richmond                    | 1                   | 94121   | 
| E200403311061 | 1080691200                | 1437  | 016  | 4100          |                      | Geary        | Bl            |      |             | 4 lights 4 switches 6 receptacles                                                                                                                                                                                  | complete | Inner Richmond                    | 1                   | 94118   | 
| EW20061027721 | 1161907200                | 1346  | 009  | 3             |                      | 12th         | Av            | 3    |             | temporary office plug. one plug. approximately [scope of work does not include residential electric space heater installation.]                                                                                    | complete | Inner Richmond                    | 2                   | 94118   | 
| E201203121388 | 1331510400                | 2078  | 004  | 1843          |                      | 41st         | Av            |      |             | change out 2 old subpanels 100a + 80amp.                                                                                                                                                                           | complete | Sunset/Parkside                   | 4                   | 94122   | 
| E200408236626 | 1093219200                | 1798  | 011  | 1343          |                      | 43rd         | Av            |      |             | at 1343 43rd: install enlarged panel box to install arc fault intercept headers new box breakers to match additional gr rod pull meters. superceding permit 200305057452 per inspector. garage box upgrade service | complete | Sunset/Parkside                   | 4                   | 94122   | 
```