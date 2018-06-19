# NYC Open Data Plan - Datasets Added Since The Publication NYC Open Data Plan ( September 2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-open-data-plan-datasets-added-since-the-publication-nyc-open-data-plan-september-2013-5f73f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qnuk-aubm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qnuk-aubm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qnuk-aubm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qnuk-aubm |
| Name | NYC Open Data Plan - Datasets Added Since The Publication NYC Open Data Plan ( September 2013) |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | doitt, open data plan |
| Created | 2014-07-16T14:33:18Z |
| Publication Date | 2014-07-16T14:36:28Z |

## Description

This dataset will provide the list of datasets added to the portal since the publication of the Inaugural NYC Open Data Plan ( September 2013)

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | agency              | Agency              | text      | text        |
| Yes      | series tag  | dataset             | Dataset             | text      | text        |
| Yes      | series tag  | dataset_description | Dataset Description | text      | text        |
| Yes      | series tag  | update_frequency    | Update Frequency    | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qnuk-aubm d:2013-01-01T00:00:00.000Z t:update_frequency=Annually t:dataset="Placements by Community District (CD)" t:dataset_description="Number of children placed in foster care by their CD of origin" t:agency="Administration for Children's Services (ACS)" m:row_number.qnuk-aubm=1

series e:qnuk-aubm d:2013-01-01T00:00:00.000Z t:update_frequency=Annually t:dataset="Abuse/Neglect by CD" t:dataset_description="Abuse/neglect investigations by CD of family" t:agency="Administration for Children's Services (ACS)" m:row_number.qnuk-aubm=2

series e:qnuk-aubm d:2013-01-01T00:00:00.000Z t:update_frequency=Quarterly t:dataset="Child Welfare Indicators -Annual and quarterly report indicators" t:dataset_description="Select Child Welfare indicators reported in compliance with Introduction 15 passed by the New York City Council in 2006" t:agency="Administration for Children's Services (ACS)" m:row_number.qnuk-aubm=3
```

## Meta Commands

```ls
metric m:row_number.qnuk-aubm p:long l:"Row Number"

entity e:qnuk-aubm l:"NYC Open Data Plan - Datasets Added  Since The Publication NYC Open Data Plan ( September 2013)" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/qnuk-aubm

property e:qnuk-aubm t:meta.view v:id=qnuk-aubm v:category="City Government" v:averageRating=0 v:name="NYC Open Data Plan - Datasets Added  Since The Publication NYC Open Data Plan ( September 2013)" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:qnuk-aubm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qnuk-aubm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency                                       | dataset                                                                        | dataset_description                                                                                                                                                                                                                                                                                                                                                                                                    | update_frequency | 
| ============================================ | ============================================================================== | ====================================================================================================================================================================================================================================================================================================================================================================================================================== | ================ | 
| Administration for Children's Services (ACS) | Placements by Community District (CD)                                          | Number of children placed in foster care by their CD of origin                                                                                                                                                                                                                                                                                                                                                         | Annually         | 
| Administration for Children's Services (ACS) | Abuse/Neglect by CD                                                            | Abuse/neglect investigations by CD of family                                                                                                                                                                                                                                                                                                                                                                           | Annually         | 
| Administration for Children's Services (ACS) | Child Welfare Indicators -Annual and quarterly report indicators               | Select Child Welfare indicators reported in compliance with Introduction 15 passed by the New York City Council in 2006                                                                                                                                                                                                                                                                                                | Quarterly        | 
| Department of City Planning (DCP)            | New York City Population by Borough, 1950 - 2040                               | Unadjusted decennial census data from 1950-2000 and projected figures from 2010-2040: summary table of New York City population numbers and percentage share by Borough, including school-age (5 to 17), 65 and Over, and total population.                                                                                                                                                                            | Historical Data  | 
| Department of City Planning (DCP)            | New York City?s School-Age and 65 and Over Populations by Borough, 1950 ? 2040 | Unadjusted decennial census data from 1950-2000 and projected figures from 2010-2040: summary table of New York City population numbers and percentage share by Borough, including school-age (5 to 17), 65 and Over, and total population.                                                                                                                                                                            | Historical Data  | 
| Department of City Planning (DCP)            | Archived Primary Land Use Tax Lot Output (PLUTO)                               | Archived History of Primary Land Use Tax Lot Output (PLUTO). The PLUTO tax lot data files contain over seventy data fields derived from extracts of mainframe data files maintained by the Department of City Planning (DCP), Department of Finance (DOF), Department of Citywide Administrative Services (DCAS), and from information contained in Landmarks Preservation Commission (LPC) publications and web site. | Historical Data  | 
| Department of City Planning (DCP)            | 2040 Population Projection Tables                                              | DCP 2040 population projection tables.                                                                                                                                                                                                                                                                                                                                                                                 | As Needed        | 
| Department of Correction (DOC)               | Hart Island Burial Records                                                     | Individuals buried on Hart Island with date and place of death when available                                                                                                                                                                                                                                                                                                                                          | Quarterly        | 
| Department of Education (DOE)                | Universal Pre-K (UPK) School Locations                                         | Directory of Universal Pre-K (UPK) School Locations                                                                                                                                                                                                                                                                                                                                                                    | As needed        | 
| Department of Environmental Protection (DEP) | Acceptable Reduced Pressure Detector Assemblies                                | List of acceptable reduced pressure detector assemblies                                                                                                                                                                                                                                                                                                                                                                | Annually         | 
```