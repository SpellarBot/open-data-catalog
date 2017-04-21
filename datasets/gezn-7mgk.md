# CEQR Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ceqr-projects) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gezn-7mgk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gezn-7mgk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gezn-7mgk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gezn-7mgk |
| Name | CEQR Projects |
| Attribution | Mayor's Office of Sustainability (MOS) |
| Category | City Government |
| Tags | sustainability, mos, ceqr, environment, project |
| Created | 2015-11-25T20:53:18Z |
| Publication Date | 2017-04-20T14:12:22Z |

## Description

CEQR Open Data contains information on projects that are undergoing or have completed review through the City Environmental Quality Review (CEQR) process. Project information available at the Open Data Portal includes the CEQR Number, Project Name, the Project Description, the Lead Agency, project milestones, and geographical locations. CEQR Open Data contains information on CEQR projects, which were filed with the Mayor?s Office from January 1, 2005 to the present.  For associated documents, please follow the links to the CEQR Access Database.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | ceqr                | CEQR                | text      | text        |
| Yes      | series tag  | project_name        | Project Name        | text      | text        |
| Yes      | series tag  | project_description | Project Description | text      | text        |
| Yes      | series tag  | borough             | Borough             | text      | text        |
| Yes      | series tag  | lead_agency         | Lead Agency         | text      | text        |
| Yes      | series tag  | url                 | URL                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gezn-7mgk d:2017-04-20T14:12:14.000Z t:project_name="Le Triumphe" t:lead_agency="NYC Departments of Environmental Protection and City Planning (co-lead)" t:ceqr=79-069M t:borough=Manhattan t:url=https://a002-ceqraccess.nyc.gov/ceqr t:project_description="Modification to Permit Allowable Uses in Cellar of Building." m:row_number.gezn-7mgk=1

series e:gezn-7mgk d:2017-04-20T14:12:14.000Z t:project_name="46-50 Ganesvoort Street Project" t:lead_agency="NYC Departments of Environmental Protection and City Planning (co-lead)" t:ceqr=82-270M t:borough=Manhattan t:url=https://a002-ceqraccess.nyc.gov/ceqr t:project_description="Proposed Modification to the Restrictive Declaration. To modify the use restrictions of the Restrictive Declaration to allow Use Group 6 and 9 uses." m:row_number.gezn-7mgk=2

series e:gezn-7mgk d:2017-04-20T14:12:14.000Z t:project_name="Proposed East 34th Street Heliport" t:lead_agency="NYC Departments of Environmental Protection and City Planning (co-lead)" t:ceqr=83-078M t:borough=Manhattan t:url=https://a002-ceqraccess.nyc.gov/ceqr t:project_description="A 10 year special permit for the continued operation of the East 34th Street Heliport." m:row_number.gezn-7mgk=3
```

## Meta Commands

```ls
metric m:row_number.gezn-7mgk p:long l:"Row Number"

entity e:gezn-7mgk l:"CEQR Projects" t:attribution="Mayor's Office of Sustainability (MOS)" t:url=https://data.cityofnewyork.us/api/views/gezn-7mgk

property e:gezn-7mgk t:meta.view v:id=gezn-7mgk v:category="City Government" v:averageRating=0 v:name="CEQR Projects" v:attribution="Mayor's Office of Sustainability (MOS)"

property e:gezn-7mgk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gezn-7mgk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | ceqr    | project_name                       | project_description                                                                                                                                                                                                | borough   | lead_agency                                                             | url                                  | 
| =========== | ======= | ================================== | ================================================================================================================================================================================================================== | ========= | ======================================================================= | ==================================== | 
| 1492697534  | 79-069M | Le Triumphe                        | Modification to Permit Allowable Uses in Cellar of Building.                                                                                                                                                       | Manhattan | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 82-270M | 46-50 Ganesvoort Street Project    | Proposed Modification to the Restrictive Declaration. To modify the use restrictions of the Restrictive Declaration to allow Use Group 6 and 9 uses.                                                               | Manhattan | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 83-078M | Proposed East 34th Street Heliport | A 10 year special permit for the continued operation of the East 34th Street Heliport.                                                                                                                             | Manhattan | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 85-212M | Solow Management Corp              | Rezoning for Garage on a Wide Street ( minor modification issued)                                                                                                                                                  | Manhattan | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 86-032K | East 43rd Street                   |                                                                                                                                                                                                                    | Brooklyn  | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 86-082M | 7th Avenue Rezoning                | A zoning text amendment that would establish a new zoning district 'C6-3X and a zoning map amendment that would map the proposed C6-3X district for a depth of 100 feet on either side of 7th Avenue in Manhattan. | Manhattan | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 86-226Q | 70-05 35th Avenue                  |                                                                                                                                                                                                                    | Queens    | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 87-086K | Silver Rod Drug Store              |                                                                                                                                                                                                                    | Brooklyn  | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 87-141K | Brooklyn City Railroad             |                                                                                                                                                                                                                    | Brooklyn  | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
| 1492697534  | 87-281Q | Powells Cove Demapping             |                                                                                                                                                                                                                    | Queens    | NYC Departments of Environmental Protection and City Planning (co-lead) | https://a002-ceqraccess.nyc.gov/ceqr | 
```