# Active Projects - Public Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-projects-buildings) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g9ub-hrve) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g9ub-hrve/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g9ub-hrve/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g9ub-hrve |
| Name | Active Projects - Public Buildings |
| Attribution | Department of Design and Construction (DDC) |
| Category | Housing & Development |
| Tags | ddc, design, construction, projects, budget |
| Created | 2016-06-06T17:18:04Z |
| Publication Date | 2016-06-08T14:34:37Z |

## Description

List of currently active buildings projects including description and high level schedule and budget range.

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
series e:g9ub-hrve d:2017-07-04T00:00:00.000Z t:scope="Construction work includes new electrical, HVAC, plumbing and communications systems." t:division="Public Buildings" t:status=On-Going t:description="77th Pct. Annex Renovation" t:dollar_amount="0 - 500K" t:project_id=PO79-77AX t:phase=Design t:client_agency=Police m:row_number.g9ub-hrve=1

series e:g9ub-hrve d:2018-03-07T00:00:00.000Z t:scope="Restoration of building facades." t:division="Public Buildings" t:status=On-Going t:description="1 Police Plaza and Police Academy Exterior Facade" t:dollar_amount="0 - 500K" t:project_id=PO79BMAHJ t:phase=Design t:client_agency=Police m:row_number.g9ub-hrve=2

series e:g9ub-hrve d:2018-03-07T00:00:00.000Z t:scope="Restoration of building facades." t:division="Public Buildings" t:status=On-Going t:description="1 Police Plaza and Police Academy Exterior Facade" t:dollar_amount="0 - 500K" t:project_id=PO79BMAHJ t:phase=Design t:client_agency=Police m:row_number.g9ub-hrve=3
```

## Meta Commands

```ls
metric m:row_number.g9ub-hrve p:long l:"Row Number"

entity e:g9ub-hrve l:"Active Projects - Public Buildings" t:attribution="Department of Design and Construction (DDC)" t:url=https://data.cityofnewyork.us/api/views/g9ub-hrve

property e:g9ub-hrve t:meta.view v:id=g9ub-hrve v:category="Housing & Development" v:averageRating=0 v:name="Active Projects - Public Buildings" v:attribution="Department of Design and Construction (DDC)"

property e:g9ub-hrve t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g9ub-hrve t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| project_id | description                                       | client_agency            | division         | phase  | projected_construction_completion | scope                                                                                 | dollar_amount | status   | 
| ========== | ================================================= | ======================== | ================ | ====== | ================================= | ===================================================================================== | ============= | ======== | 
| PO79-77AX  | 77th Pct. Annex Renovation                        | Police                   | Public Buildings | Design | 2017-07-04T00:00:00               | Construction work includes new electrical, HVAC, plumbing and communications systems. | 0 - 500K      | On-Going | 
| PO79BMAHJ  | 1 Police Plaza and Police Academy Exterior Facade | Police                   | Public Buildings | Design | 2018-03-07T00:00:00               | Restoration of building facades.                                                      | 0 - 500K      | On-Going | 
| PO79BMAHJ  | 1 Police Plaza and Police Academy Exterior Facade | Police                   | Public Buildings | Design | 2018-03-07T00:00:00               | Restoration of building facades.                                                      | 0 - 500K      | On-Going | 
| PO79BMAHQ  | One Police Plaza Paving and Landscaping           | Police                   | Public Buildings | Design | 2017-11-22T00:00:00               | Restoration of plaza at One Police Plaza.                                             | 0 - 500K      | On-Going | 
| PW348-63   | Remediation of Petroleum Contaminated Sites       | Mayors Office Operations | Public Buildings | Design | 2017-12-27T00:00:00               | Remediation and monitoring of petroleum contaminated sites on city owned property.    | 5 M +         | On-Going | 
| PW348-63   | Remediation of Petroleum Contaminated Sites       | Mayors Office Operations | Public Buildings | Design | 2017-12-27T00:00:00               | Remediation and monitoring of petroleum contaminated sites on city owned property.    | 5 M +         | On-Going | 
| PW348-63   | Remediation of Petroleum Contaminated Sites       | Mayors Office Operations | Public Buildings | Design | 2017-12-27T00:00:00               | Remediation and monitoring of petroleum contaminated sites on city owned property.    | 5 M +         | On-Going | 
| PW348-63   | Remediation of Petroleum Contaminated Sites       | Mayors Office Operations | Public Buildings | Design | 2017-12-27T00:00:00               | Remediation and monitoring of petroleum contaminated sites on city owned property.    | 5 M +         | On-Going | 
| PW348-63   | Remediation of Petroleum Contaminated Sites       | Mayors Office Operations | Public Buildings | Design | 2017-12-27T00:00:00               | Remediation and monitoring of petroleum contaminated sites on city owned property.    | 5 M +         | On-Going | 
| PW348-63   | Remediation of Petroleum Contaminated Sites       | Mayors Office Operations | Public Buildings | Design | 2017-12-27T00:00:00               | Remediation and monitoring of petroleum contaminated sites on city owned property.    | 5 M +         | On-Going | 
```