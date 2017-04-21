# Building Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-complaints) |
| Metadata | [Link](https://data.sfgov.org/api/views/gm2e-bten) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/gm2e-bten/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/gm2e-bten/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | gm2e-bten |
| Name | Building Complaints |
| Category | Housing and Buildings |
| Created | 2016-04-06T17:15:43Z |
| Publication Date | 2016-11-10T19:07:11Z |

## Description

These are complaints from Housing, Building, Electrical, Plumbing, and Code Enforcement divisions within the Department of Building Inspection. Routine and non-routine inspections from the housing division are tracked using complaints only if violations are found during the inspections. The NOVTYPE field can be used to determine the source of the complaint.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | ============== | ================================= | =================================== | ============= | ============= |
| Yes      | series tag     | complaint_number                  | Complaint Number                    | text          | text          |
| Yes      | time           | date_filed                        | Date Filed                          | date          | date          |
| Yes      | series tag     | block                             | Block                               | text          | text          |
| Yes      | series tag     | lot                               | Lot                                 | text          | text          |
| Yes      | series tag     | street_number                     | Street Number                       | text          | text          |
| Yes      | series tag     | street_name                       | Street Name                         | text          | text          |
| Yes      | series tag     | street_suffix                     | Street Suffix                       | text          | text          |
| Yes      | numeric metric | unit                              | Unit                                | number        | text          |
| Yes      | series tag     | complaint_description             | Complaint Description               | text          | text          |
| Yes      | series tag     | status                            | Status                              | text          | text          |
| Yes      | series tag     | nov_type                          | NOV Type                            | text          | text          |
| Yes      | series tag     | receiving_division                | Receiving Division                  | text          | text          |
| Yes      | series tag     | assigned_division                 | Assigned Division                   | text          | text          |
| No       |                | date_1st_nov_issued               | Date 1st NOV Issued                 | calendar_date | calendar_date |
| No       |                | date_2nd_nov_issued               | Date 2nd NOV Issued                 | calendar_date | calendar_date |
| No       |                | date_referred_to_city_attorney    | Date Referred to City Attorney      | calendar_date | calendar_date |
| No       |                | director_hearing_date             | Director Hearing Date               | calendar_date | calendar_date |
| No       |                | last_inspection_date              | Last Inspection Date                | calendar_date | calendar_date |
| No       |                | date_abated                       | Date Abated                         | calendar_date | calendar_date |
| No       |                | closed_date                       | Closed Date                         | calendar_date | calendar_date |
| Yes      | series tag     | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text          | text          |
| Yes      | series tag     | supervisor_district               | Supervisor District                 | text          | text          |
| Yes      | series tag     | zipcode                           | Zipcode                             | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_1st_nov_issued,date_2nd_nov_issued,date_referred_to_city_attorney,director_hearing_date,last_inspection_date,date_abated,closed_date
```

## Data Commands

```ls
series e:gm2e-bten d:2016-12-06T00:00:00.000Z t:complaint_description="complaint generated routine inspection initiated by cts 201648971" t:nov_type=routine t:neighborhoods_analysis_boundaries=Sunset/Parkside t:status=active t:complaint_number=201649911 t:zipcode=94116 t:street_name=Taraval t:street_suffix=St t:lot=015 t:block=2371 t:street_number=3232 t:assigned_division="Housing Inspection Services" t:supervisor_district=4 t:receiving_division="Housing Inspection Services" m:unit=0

series e:gm2e-bten d:2003-01-02T00:00:00.000Z t:complaint_description="routine inspection" t:nov_type=routine t:neighborhoods_analysis_boundaries="Nob Hill" t:status="not active" t:complaint_number=200336563 t:zipcode=94108 t:street_name=Powell t:street_suffix=St t:lot=008 t:block=0212 t:street_number=1005 t:assigned_division="Housing Inspection Services" t:supervisor_district=3 t:receiving_division="Housing Inspection Services" m:unit=0

series e:gm2e-bten d:2011-02-15T00:00:00.000Z t:complaint_description="boarded up ground floor entry door; window unreplaced." t:nov_type=complaint t:neighborhoods_analysis_boundaries=Chinatown t:status="not active" t:complaint_number=201196806 t:zipcode=94108 t:street_name=Stone t:street_suffix=St t:lot=026 t:block=0192 t:street_number=21 t:assigned_division="Housing Inspection Services" t:supervisor_district=3 t:receiving_division="Housing Inspection Services" m:unit=0
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

entity e:gm2e-bten l:"Building Complaints" t:url=https://data.sfgov.org/api/views/gm2e-bten

property e:gm2e-bten t:meta.view v:id=gm2e-bten v:category="Housing and Buildings" v:averageRating=0 v:name="Building Complaints"

property e:gm2e-bten t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:gm2e-bten t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:gm2e-bten t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| complaint_number | date_filed | block | lot | street_number | street_name | street_suffix | unit | complaint_description                                                                                                                                                                                                                              | status     | nov_type  | receiving_division           | assigned_division           | date_1st_nov_issued | date_2nd_nov_issued | date_referred_to_city_attorney | director_hearing_date | last_inspection_date | date_abated         | closed_date         | neighborhoods_analysis_boundaries | supervisor_district | zipcode | 
| ================ | ========== | ===== | === | ============= | =========== | ============= | ==== | ================================================================================================================================================================================================================================================== | ========== | ========= | ============================ | =========================== | =================== | =================== | ============================== | ===================== | ==================== | =================== | =================== | ================================= | =================== | ======= | 
| H9400938         | 762739200  | 5946  | 013 | 66            | Valmar      | Tr            |      | private entrance door bell;possible illegal unit.                                                                                                                                                                                                  | not active | complaint | Housing Inspection Services  | Housing Inspection Services | 1994-06-16T00:00:00 |                     |                                |                       | 1994-03-08T00:00:00  | 1994-07-15T00:00:00 |                     | Excelsior                         | 11                  | 94112   | 
| 201649911        | 1480982400 | 2371  | 015 | 3232          | Taraval     | St            | 0    | complaint generated routine inspection initiated by cts 201648971                                                                                                                                                                                  | active     | routine   | Housing Inspection Services  | Housing Inspection Services | 2016-12-06T00:00:00 |                     |                                | 2017-03-02T00:00:00   | 2017-03-16T00:00:00  |                     |                     | Sunset/Parkside                   | 4                   | 94116   | 
| 200733361        | 1196640000 | 0088  | 056 | 534           | Filbert     | St            |      | routine inspection.                                                                                                                                                                                                                                | not active |           | Housing Inspection Services  | Housing Inspection Services |                     |                     |                                |                       |                      | 2007-12-03T00:00:00 |                     | North Beach                       | 3                   | 94133   | 
| 200922113        | 1253059200 | 0928  | 006 | 3425          | Scott       | St            |      | routine inspection of common areas of subject property.                                                                                                                                                                                            | not active | routine   | Housing Inspection Services  | Housing Inspection Services | 2009-09-16T00:00:00 |                     |                                |                       | 2009-09-16T00:00:00  | 2009-10-16T00:00:00 |                     | Marina                            | 2                   | 94123   | 
| H9400668         | 763689600  | 1424  | 046 | 280           | 10th        | Av            |      | fire alarm box is broken (8-9 mos) water leaks from sink in bathroom and kitchen. bathroom fan has water in it. fire escapes hard to find. no fire extinguishers on each stairwell ceiling in bathroom has water damage and a hole in the ceiling. | not active | complaint | Housing Inspection Services  | Housing Inspection Services | 1994-04-08T00:00:00 |                     |                                |                       | 1994-03-17T00:00:00  | 1994-05-25T00:00:00 |                     | Inner Richmond                    | 1                   | 94118   | 
| 200670610        | 1150243200 | 0860  | 062 | 555           | Haight      | St            |      | windows needs to be replaced.                                                                                                                                                                                                                      | not active |           | Housing Inspection Services  | Housing Inspection Services | 2006-06-27T00:00:00 |                     |                                |                       | 2006-06-15T00:00:00  | 2006-07-12T00:00:00 |                     | Hayes Valley                      | 5                   | 94117   | 
| 201460921        | 1395619200 | 0282  | 002 | 749           | Taylor      | St            |      | residential hotel survey and routine safety inspection of common areas.                                                                                                                                                                            | not active | routine   | Housing Inspection Services  | Housing Inspection Services |                     |                     |                                |                       | 2014-03-24T00:00:00  |                     | 2014-03-24T00:00:00 | Nob Hill                          | 3                   | 94109   | 
| 200875335        | 1223510400 | 0862  | 013 | 650           | Waller      | St            |      | routine                                                                                                                                                                                                                                            | not active | routine   | Housing Inspection Services  | Housing Inspection Services |                     |                     |                                |                       | 2008-10-09T00:00:00  | 2008-10-09T00:00:00 |                     | Haight Ashbury                    | 5                   | 94117   | 
| 201622294        | 1465862400 | 3610  | 029 | 3491          | 20th        | St            |      | work w/o permit unsafe condition                                                                                                                                                                                                                   | active     |           | Building Inspection Division | Code Enforcement Section    | 2016-06-15T00:00:00 | 2016-07-26T00:00:00 |                                | 2016-12-06T00:00:00   |                      |                     |                     | Mission                           | 9                   | 94110   | 
| 200003864        | 955411200  | 0820  | 002 | 600           | Fell        | St            |      | refrigerator and stove don't work.                                                                                                                                                                                                                 | not active |           | Housing Inspection Services  | Housing Inspection Services |                     |                     |                                |                       |                      | 2000-04-11T00:00:00 |                     | Hayes Valley                      | 5                   | 94102   | 
```