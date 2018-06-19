# Wind Energy Projects: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wind-energy-projects-beginning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/jmxa-iz8m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jmxa-iz8m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jmxa-iz8m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jmxa-iz8m |
| Name | Wind Energy Projects: Beginning 2004 |
| Attribution | New York State Public Service Commission |
| Category | Energy & Environment |
| Tags | wind, wind energy projects |
| Created | 2013-02-27T19:52:58Z |
| Publication Date | 2015-12-15T21:47:34Z |

## Description

Table lists existing and proposed major wind projects in NYS, their locations, relative electric generating potential (project nameplate size), and project status (proposed, in-construction, or operational).

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | psc_case_number   | PSC Case Number   | text      | text        |
| Yes      | series tag     | project_name      | Project Name      | text      | text        |
| Yes      | series tag     | project_developer | Project Developer | text      | text        |
| Yes      | series tag     | location_town     | Location Town     | text      | text        |
| Yes      | series tag     | location_county   | Location County   | text      | text        |
| Yes      | numeric metric | no_of_turbines    | No. of Turbines   | number    | number      |
| Yes      | series tag     | project_mw        | Project MW        | text      | text        |
| Yes      | series tag     | status            | Status            | text      | text        |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jmxa-iz8m d:2004-01-01T00:00:00.000Z t:psc_case_number=12-F-0575 t:location_county=Jefferson t:project_name="Horse Creek Windpower (Clayton Wind)" t:status="Article 10 opt-in filed" t:location_town="Clayton & Orleans" t:project_mw=126 t:project_developer="PPM Energy (Iberdrola Renewables)" m:no_of_turbines=50

series e:jmxa-iz8m d:2004-01-01T00:00:00.000Z t:psc_case_number=15-F-0327 t:location_county=Jefferson t:project_name="Galloo Island Wind Energy" t:status="Article 10 PIP filing" t:location_town=Hounsfield t:project_mw=102.3 t:project_developer="Hudson North Country Wind 1, LLC" m:no_of_turbines=30

series e:jmxa-iz8m d:2004-01-01T00:00:00.000Z t:psc_case_number=07-E-0138 t:location_county=Steuben t:project_name="Cohocton (Canandaigua) Windfarm" t:status=Operational t:location_town=Cohocton t:project_mw=136 t:project_developer="UPC Wind Management LLC" m:no_of_turbines=50
```

## Meta Commands

```ls
metric m:no_of_turbines p:integer l:"No. of Turbines" d:"The number of turbines in the project." t:dataTypeName=number

entity e:jmxa-iz8m l:"Wind Energy Projects: Beginning 2004" t:attribution="New York State Public Service Commission" t:url=https://data.ny.gov/api/views/jmxa-iz8m

property e:jmxa-iz8m t:meta.view v:id=jmxa-iz8m v:category="Energy & Environment" v:averageRating=0 v:name="Wind Energy Projects: Beginning 2004" v:attribution="New York State Public Service Commission"

property e:jmxa-iz8m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jmxa-iz8m t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jmxa-iz8m t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| psc_case_number | project_name                         | project_developer                     | location_town                                                          | location_county   | no_of_turbines | project_mw | status                  | 
| =============== | ==================================== | ===================================== | ====================================================================== | ================= | ============== | ========== | ======================= | 
| 12-F-0575       | Horse Creek Windpower (Clayton Wind) | PPM Energy (Iberdrola Renewables)     | Clayton & Orleans                                                      | Jefferson         | 50             | 126        | Article 10 opt-in filed | 
| 13-F-0111       | Rolling Upland wind Farm             | EDPR-NA, LLC                          | Madison                                                                | Madison           |                | 60         | Article 10 opt-in filed | 
| 15-F-0122       | Baron Winds                          | Everpower                             | Avoca, Cohocoton, Dansville, Fremont, Hornellsville, Howard, & Wayland | Steuben           |                | 300        | Article 10 PIP filing   | 
| 15-F-0377       | Bull Run Wind Farm                   | Bull Run Energy, LLC - Invenergy      | Altona, Clinton, Ellenburg & Mooers                                    | Clinton           |                | 300        | Article 10 PIP filing   | 
| 14-F-0490       | Cassadaga Wind                       | Everpower                             | Arkwright, Charlotte, Cherry Creek, Stockton                           | Chatauqua         |                | 126        | Article 10 PSS filing   | 
| 12-F-0365       | Dry Lots Wind                        | Dry Lots Wind, LLC - Ridgeline Energy | Litchfield                                                             | Herkimer          |                | 33         | Article 10 PIP filing   | 
| 15-F-0327       | Galloo Island Wind Energy            | Hudson North Country Wind 1, LLC      | Hounsfield                                                             | Jefferson         | 30             | 102.3      | Article 10 PIP filing   | 
| 14-F-0485       | Lighthouse Wind                      | Apex Clean Energy                     | Somerset & Yates                                                       | Niagara & Orleans |                | 201        | Article 10 PSS filing   | 
| N/A             | LI-NYC Offshore Collaborative        | NYPA, LIPA, ConEd                     |                                                                        | Off-Shore         |                | 350-700    | Federal Process Started | 
| 07-E-0138       | Cohocton (Canandaigua) Windfarm      | UPC Wind Management LLC               | Cohocton                                                               | Steuben           | 50             | 136        | Operational             | 
```