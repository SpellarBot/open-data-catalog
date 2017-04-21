# 2013: ECAD Commercial Portfolio Manager Reported Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-ecad-commercial-portfolio-manager-reported-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/rka3-mjzi) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/rka3-mjzi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/rka3-mjzi/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | rka3-mjzi |
| Name | 2013: ECAD Commercial Portfolio Manager Reported Data |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | ecad, commercial, audit, ordinance, building type, score, energy star score, rating, btu/sqft, eui, 20110421-002, austin, climate protection |
| Created | 2014-04-01T15:14:16Z |
| Publication Date | 2014-04-01T17:10:48Z |

## Description

This report is the result of the Austin City Code 6-7?s Energy Conservation Audit and Disclosure Ordinance approved in November 2008 (amended in April 2011) to improve the energy efficiency of homes and buildings that receive electricity from Austin Energy. The ordinance meets one of the goals of the Austin Climate Protection Plan, which is to offset 800 megawatts of peak energy demand by 2020. This report contains information on commercial facilities that have reported the EPA?s Energy Star Portfolio Manager benchmarking results in 2013 (*) to the City of Austin. For information on ECAD exemptions and other requirements, see Austin City Code Chapter 6-7. Note ? (*) Data reported by Commercial Customers.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ============================================ | ============================================ | ============= | ============= |
| Yes      | series tag     | tcad_or_wcad_property_id_s                   | TCAD or WCAD Property ID(s)                  | text          | text          |
| Yes      | numeric metric | floor_area_sqft                              | Floor Area (sqft)                            | number        | number        |
| Yes      | series tag     | building_type                                | Building Type                                | text          | text          |
| Yes      | numeric metric | reported_portfolio_manager_energy_star_score | Reported Portfolio Manager Energy Star Score | number        | number        |
| Yes      | numeric metric | reported_portfolio_manager_site_kbtu_sqft    | Reported Portfolio Manager Site kBTU/sqft    | number        | number        |
| Yes      | time           | as_of                                        | As of                                        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rka3-mjzi d:2014-03-13T00:00:00.000Z t:building_type=Office t:tcad_or_wcad_property_id_s=196874 m:floor_area_sqft=92749 m:reported_portfolio_manager_site_kbtu_sqft=42.8 m:reported_portfolio_manager_energy_star_score=86.5

series e:rka3-mjzi d:2014-03-13T00:00:00.000Z t:building_type=Office t:tcad_or_wcad_property_id_s=289708 m:floor_area_sqft=42863 m:reported_portfolio_manager_site_kbtu_sqft=46.2 m:reported_portfolio_manager_energy_star_score=70.8

series e:rka3-mjzi d:2014-03-13T00:00:00.000Z t:building_type=Office t:tcad_or_wcad_property_id_s=105335 m:floor_area_sqft=120000
```

## Meta Commands

```ls
metric m:floor_area_sqft p:integer l:"Floor Area (sqft)" t:dataTypeName=number

metric m:reported_portfolio_manager_energy_star_score p:double l:"Reported Portfolio Manager Energy Star Score" t:dataTypeName=number

metric m:reported_portfolio_manager_site_kbtu_sqft p:float l:"Reported Portfolio Manager Site kBTU/sqft" t:dataTypeName=number

entity e:rka3-mjzi l:"2013: ECAD Commercial Portfolio Manager Reported Data" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/rka3-mjzi

property e:rka3-mjzi t:meta.view v:id=rka3-mjzi v:category=Utility v:attributionLink=http://www.Austinenergy.com v:averageRating=0 v:name="2013: ECAD Commercial Portfolio Manager Reported Data" v:attribution="Austin Energy"

property e:rka3-mjzi t:meta.view.license v:name="Public Domain"

property e:rka3-mjzi t:meta.view.owner v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:displayName="Michael McCarthy"

property e:rka3-mjzi t:meta.view.tableauthor v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:roleName=editor v:displayName="Michael McCarthy"
```

## Top Records

```ls
| tcad_or_wcad_property_id_s | floor_area_sqft | building_type                           | reported_portfolio_manager_energy_star_score | reported_portfolio_manager_site_kbtu_sqft | as_of               | 
| ========================== | =============== | ======================================= | ============================================ | ========================================= | =================== | 
| 196874                     | 92749           | Office                                  | 86.5                                         | 42.8                                      | 2014-03-13T00:00:00 | 
| 289708                     | 42863           | Office                                  | 70.8                                         | 46.2                                      | 2014-03-13T00:00:00 | 
| 105335                     | 120000          | Office                                  |                                              |                                           | 2014-03-13T00:00:00 | 
| 250865                     | 310613          | K-12 School                             | 31.8                                         | 61.6                                      | 2014-03-13T00:00:00 | 
| 262091                     | 79157           | Office                                  |                                              |                                           | 2014-03-13T00:00:00 | 
| 727226                     | 526915          | Hospital (General Medical and Surgical) | 72.7                                         | 269                                       | 2014-03-13T00:00:00 | 
| 203760                     | 30980           | Residence Hall/Dormitory                | 54.5                                         | 57.9                                      | 2014-03-13T00:00:00 | 
| 715485                     | 33679           | Retail                                  | 1                                            | 236.3                                     | 2014-03-13T00:00:00 | 
| 252833                     | 51557           | Retail                                  |                                              |                                           | 2014-03-13T00:00:00 | 
| 503131                     | 29769           | K-12 School                             | 98                                           | 24.5                                      | 2014-03-13T00:00:00 | 
```