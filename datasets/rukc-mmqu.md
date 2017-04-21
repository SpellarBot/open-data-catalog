# Active Projects - Infrastructure

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-projects-infrastructure) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rukc-mmqu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rukc-mmqu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rukc-mmqu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rukc-mmqu |
| Name | Active Projects - Infrastructure |
| Attribution | Department of Design and Construction (DDC) |
| Category | Housing & Development |
| Tags | ddc, design, construction, projects, budget |
| Created | 2016-06-06T17:18:02Z |
| Publication Date | 2016-06-08T14:34:38Z |

## Description

List of currently active infrastructure projects including description and high level schedule and budget range.

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | =========== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag  | project_id                        | Project ID                        | text          | text          |
| Yes      | series tag  | description                       | Description                       | text          | text          |
| Yes      | series tag  | client_agency                     | Client Agency                     | text          | text          |
| Yes      | series tag  | division                          | Division                          | text          | text          |
| Yes      | series tag  | phase                             | Phase                             | text          | text          |
| Yes      | time        | projected_construction_completion | Projected Construction Completion | calendar_date | calendar_date |
| Yes      | series tag  | scope                             | Scope                             | text          | text          |
| Yes      | series tag  | dollar_amount                     | Dollar Amount                     | text          | text          |
| Yes      | series tag  | status                            | Status                            | text          | text          |
```

## Time Field

```ls
Value = projected_construction_completion
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rukc-mmqu d:2026-06-17T00:00:00.000Z t:scope="Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street." t:division=Infrastructure t:status=On-Going t:description="RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784" t:dollar_amount="5 M +" t:project_id=HWK614D t:phase=Design t:client_agency="Trans. & Env. Protection" m:row_number.rukc-mmqu=1

series e:rukc-mmqu d:2026-06-17T00:00:00.000Z t:scope="Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street." t:division=Infrastructure t:status=On-Going t:description="RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784" t:dollar_amount="5 M +" t:project_id=HWK614D t:phase=Design t:client_agency="Trans. & Env. Protection" m:row_number.rukc-mmqu=2

series e:rukc-mmqu d:2026-06-17T00:00:00.000Z t:scope="Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street." t:division=Infrastructure t:status=On-Going t:description="RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784" t:dollar_amount="5 M +" t:project_id=HWK614D t:phase=Design t:client_agency="Trans. & Env. Protection" m:row_number.rukc-mmqu=3
```

## Meta Commands

```ls
metric m:row_number.rukc-mmqu p:long l:"Row Number"

entity e:rukc-mmqu l:"Active Projects - Infrastructure" t:attribution="Department of Design and Construction (DDC)" t:url=https://data.cityofnewyork.us/api/views/rukc-mmqu

property e:rukc-mmqu t:meta.view v:id=rukc-mmqu v:category="Housing & Development" v:averageRating=0 v:name="Active Projects - Infrastructure" v:attribution="Department of Design and Construction (DDC)"

property e:rukc-mmqu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rukc-mmqu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| project_id | description                                        | client_agency            | division       | phase      | projected_construction_completion | scope                                                                                                                                                                                 | dollar_amount | status   | 
| ========== | ================================================== | ======================== | ============== | ========== | ================================= | ===================================================================================================================================================================================== | ============= | ======== | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
| HWQ1126C   | RECONS ARVERNE BLVD/RCKWY BEACH BLVD, ETC, ARVERNE | Transportation           | Infrastructure | Pre-Design | 2018-07-11T00:00:00               | Reconstruct streets, sewers and water mains.                                                                                                                                          | 0 - 500K      | On-Going | 
| HWK614D    | RECONSTRUCTION OF BERGEN AVE AREA, BKLYN/BED-784   | Trans. & Env. Protection | Infrastructure | Design     | 2026-06-17T00:00:00               | Roadway reconstruction Bergen Avenue and vicinity, includes sections of: Avenues N, T, U, V, W, X and Y; 66th Street and 69th through 75th Streets; Veterans Avenue and Royce Street. | 5 M +         | On-Going | 
```