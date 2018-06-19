# MEA SmartEnergy: Renewable Energy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mea-smartenergy-renewable-energy) |
| Metadata | [Link](https://data.maryland.gov/api/views/4ubg-d5ir) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4ubg-d5ir/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4ubg-d5ir/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4ubg-d5ir |
| Name | MEA SmartEnergy: Renewable Energy |
| Attribution | Maryland Energy Administration |
| Category | Energy and Environment |
| Tags | maryland, energy, administration, mea, award, cost, capacity, electricity, technology, co2, emissions, reductions |
| Created | 2015-02-25T20:29:27Z |
| Publication Date | 2015-02-25T20:32:11Z |

## Description

Renewable energy dollars awarded through Maryland Energy Administration's smart energy projects.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ====================================== | ============= | ============= |
| No       |                | id                                   | ID                                     | text          | text          |
| Yes      | series tag     | program_name                         | Program Name                           | text          | text          |
| Yes      | series tag     | link                                 | Link                                   | text          | text          |
| Yes      | series tag     | program_type                         | Program Type                           | text          | text          |
| Yes      | series tag     | project_name                         | Project Name                           | text          | text          |
| Yes      | series tag     | recipient_region_if_applicable       | Recipient Region (if applicable)       | text          | text          |
| Yes      | numeric metric | mea_award                            | MEA Award                              | money         | money         |
| Yes      | numeric metric | total_project_cost                   | Total Project Cost                     | money         | money         |
| Yes      | series tag     | sector                               | Sector                                 | text          | text          |
| Yes      | numeric metric | capacity                             | Capacity                               | number        | number        |
| Yes      | series tag     | capacity_units                       | Capacity Units                         | text          | text          |
| Yes      | series tag     | electricity_reduction_kwh            | Electricity Reduction (kWh)            | text          | text          |
| Yes      | series tag     | technology                           | Technology                             | text          | text          |
| Yes      | numeric metric | co2_emissions_reductions_metric_tons | CO2 Emissions Reductions (metric tons) | number        | number        |
| Yes      | time           | date                                 | Date                                   | calendar_date | calendar_date |
| Yes      | series tag     | notes                                | Notes                                  | text          | text          |
| Yes      | series tag     | legislative_district                 | Legislative District                   | text          | text          |
| Yes      | series tag     | congressional_district               | Congressional District                 | text          | text          |
| Yes      | series tag     | county                               | County                                 | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:4ubg-d5ir d:2008-01-01T00:00:00.000Z t:sector=Residential t:program_type="Tax Credit" t:technology=Bioheat t:county=Carroll t:capacity_units=gallons t:legislative_district=5A t:program_name="Bioheating Oil Tax Credit Program" t:link=http://energy.maryland.gov/Residential/bioheatGrant.html t:notes="Gallon ""capacity"" indicates fuel consumed" m:mea_award=16.79 m:total_project_cost=16.79 m:capacity=559.8

series e:4ubg-d5ir d:2008-01-01T00:00:00.000Z t:sector=Residential t:program_type="Tax Credit" t:technology=Bioheat t:county=Carroll t:capacity_units=gallons t:legislative_district=9B t:program_name="Bioheating Oil Tax Credit Program" t:link=http://energy.maryland.gov/Residential/bioheatGrant.html t:notes="Gallon ""capacity"" indicates fuel consumed" m:mea_award=20.77 m:total_project_cost=20.77 m:capacity=692.3

series e:4ubg-d5ir d:2008-01-01T00:00:00.000Z t:sector=Residential t:program_type="Tax Credit" t:technology=Bioheat t:county=Howard t:capacity_units=gallons t:legislative_district=13 t:program_name="Bioheating Oil Tax Credit Program" t:link=http://energy.maryland.gov/Residential/bioheatGrant.html t:notes="Gallon ""capacity"" indicates fuel consumed" m:mea_award=18.55 m:total_project_cost=18.55 m:capacity=618.4
```

## Meta Commands

```ls
metric m:mea_award p:double l:"MEA Award" t:dataTypeName=money

metric m:total_project_cost p:integer l:"Total Project Cost" t:dataTypeName=money

metric m:capacity p:double l:Capacity t:dataTypeName=number

metric m:co2_emissions_reductions_metric_tons p:float l:"CO2 Emissions Reductions (metric tons)" t:dataTypeName=number

entity e:4ubg-d5ir l:"MEA SmartEnergy: Renewable Energy" t:attribution="Maryland Energy Administration" t:url=https://data.maryland.gov/api/views/4ubg-d5ir

property e:4ubg-d5ir t:meta.view v:id=4ubg-d5ir v:category="Energy and Environment" v:attributionLink=http://energy.maryland.gov/ v:averageRating=0 v:name="MEA SmartEnergy: Renewable Energy" v:attribution="Maryland Energy Administration"

property e:4ubg-d5ir t:meta.view.license v:name="Public Domain"

property e:4ubg-d5ir t:meta.view.owner v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:displayName=ESRGC

property e:4ubg-d5ir t:meta.view.tableauthor v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:roleName=editor v:displayName=ESRGC
```

## Top Records

```ls
| id          | program_name                      | link                                                     | program_type | project_name | recipient_region_if_applicable | mea_award | total_project_cost | sector      | capacity | capacity_units | electricity_reduction_kwh | technology | co2_emissions_reductions_metric_tons | date                | notes                                     | legislative_district | congressional_district | county           | 
| =========== | ================================= | ======================================================== | ============ | ============ | ============================== | ========= | ================== | =========== | ======== | ============== | ========================= | ========== | ==================================== | =================== | ========================================= | ==================== | ====================== | ================ | 
| BIO20080001 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 16.79     | 16.79              | Residential | 559.8    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 5A                   |                        | Carroll          | 
| BIO20080002 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 20.77     | 20.77              | Residential | 692.3    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 9B                   |                        | Carroll          | 
| BIO20080003 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 18.55     | 18.55              | Residential | 618.4    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 13                   |                        | Howard           | 
| BIO20080004 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 19.54     | 19.54              | Residential | 651.3    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 5A                   |                        | Carroll          | 
| BIO20080005 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 19.08     | 19.08              | Residential | 636.0    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 10                   |                        | Baltimore County | 
| BIO20080006 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 21.23     | 21.23              | Residential | 707.6    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 9A                   |                        | Howard           | 
| BIO20080007 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 31.47     | 31.47              | Residential | 1049.0   | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 42                   |                        | Baltimore County | 
| BIO20080008 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 10.68     | 10.68              | Residential | 355.9    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 5A                   |                        | Carroll          | 
| BIO20080009 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 44.75     | 44.75              | Residential | 1491.7   | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 4B                   |                        | Frederick        | 
| BIO20080010 | Bioheating Oil Tax Credit Program | http://energy.maryland.gov/Residential/bioheatGrant.html | Tax Credit   |              |                                | 11.94     | 11.94              | Residential | 398.1    | gallons        |                           | Bioheat    |                                      | 2008-01-01T00:00:00 | Gallon "capacity" indicates fuel consumed | 42                   |                        | Baltimore County | 
```