# Department of Revenue Services- FY 2013-14 Tax Credits By Industry Sector

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-fy-2013-14-tax-credits-by-industry-sector) |
| Metadata | [Link](https://data.ct.gov/api/views/7dmn-4s5d) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/7dmn-4s5d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/7dmn-4s5d/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 7dmn-4s5d |
| Name | Department of Revenue Services- FY 2013-14 Tax Credits By Industry Sector |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2015-03-03T20:06:44Z |
| Publication Date | 2015-03-03T20:07:51Z |

## Description

Department of Revenue Services - Tax Credits Claimed during Fiscal Year 2013-14 (July 1, 2013 through June 30, 2104) by NAICS (North American Industry Classification System)

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | naics_code                         | NAICS Code                           | text      | text        |
| Yes      | series tag     | naics_industry_group               | NAICS Industry Group                 | text      | text        |
| Yes      | numeric metric | digital_animation                  | Digital Animation                    | number    | number      |
| Yes      | numeric metric | electronic_data_processing         | Electronic Data Processing           | number    | number      |
| Yes      | numeric metric | film_production                    | Film Production                      | number    | number      |
| Yes      | numeric metric | film_infrastructure                | Film Infrastructure                  | number    | number      |
| Yes      | numeric metric | fixed_cap_investment               | Fixed Cap Investment                 | number    | number      |
| Yes      | numeric metric | job_expansion                      | Job Expansion                        | number    | number      |
| Yes      | numeric metric | research_development               | Research & Development               | number    | number      |
| Yes      | numeric metric | research_experimentation           | Research & Experimentation           | number    | number      |
| Yes      | numeric metric | urban_industrial_site_reinvestment | Urban & Industrial Site Reinvestment | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7dmn-4s5d d:2013-01-01T00:00:00.000Z t:naics_industry_group="Agriculture, Forestry, Fishing and Hunting" t:naics_code=11 m:job_expansion=0 m:research_development=0 m:digital_animation=0 m:electronic_data_processing=5636 m:urban_industrial_site_reinvestment=0 m:research_experimentation=172026 m:film_infrastructure=0 m:film_production=0 m:fixed_cap_investment=15357

series e:7dmn-4s5d d:2013-01-01T00:00:00.000Z t:naics_industry_group=Mining t:naics_code=21 m:job_expansion=0 m:research_development=0 m:digital_animation=0 m:electronic_data_processing=2301 m:urban_industrial_site_reinvestment=0 m:research_experimentation=7016 m:film_infrastructure=0 m:film_production=0 m:fixed_cap_investment=1423

series e:7dmn-4s5d d:2013-01-01T00:00:00.000Z t:naics_industry_group=Utilities t:naics_code=22 m:job_expansion=0 m:research_development=2486 m:digital_animation=0 m:electronic_data_processing=253378 m:urban_industrial_site_reinvestment=7500000 m:research_experimentation=0 m:film_infrastructure=0 m:film_production=0 m:fixed_cap_investment=12430698
```

## Meta Commands

```ls
metric m:digital_animation p:integer l:"Digital Animation" t:dataTypeName=number

metric m:electronic_data_processing p:integer l:"Electronic Data Processing" t:dataTypeName=number

metric m:film_production p:integer l:"Film Production" t:dataTypeName=number

metric m:film_infrastructure p:integer l:"Film Infrastructure" t:dataTypeName=number

metric m:fixed_cap_investment p:integer l:"Fixed Cap Investment" t:dataTypeName=number

metric m:job_expansion p:integer l:"Job Expansion" t:dataTypeName=number

metric m:research_development p:integer l:"Research & Development" t:dataTypeName=number

metric m:research_experimentation p:integer l:"Research & Experimentation" t:dataTypeName=number

metric m:urban_industrial_site_reinvestment p:integer l:"Urban & Industrial Site Reinvestment" t:dataTypeName=number

entity e:7dmn-4s5d l:"Department of Revenue Services-  FY 2013-14 Tax Credits By Industry Sector" t:url=https://data.ct.gov/api/views/7dmn-4s5d

property e:7dmn-4s5d t:meta.view v:id=7dmn-4s5d v:averageRating=0 v:name="Department of Revenue Services-  FY 2013-14 Tax Credits By Industry Sector"

property e:7dmn-4s5d t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:7dmn-4s5d t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| naics_code | naics_industry_group                       | digital_animation | electronic_data_processing | film_production | film_infrastructure | fixed_cap_investment | job_expansion | research_development | research_experimentation | urban_industrial_site_reinvestment | 
| ========== | ========================================== | ================= | ========================== | =============== | =================== | ==================== | ============= | ==================== | ======================== | ================================== | 
| 11         | Agriculture, Forestry, Fishing and Hunting | 0                 | 5636                       | 0               | 0                   | 15357                | 0             | 0                    | 172026                   | 0                                  | 
| 21         | Mining                                     | 0                 | 2301                       | 0               | 0                   | 1423                 | 0             | 0                    | 7016                     | 0                                  | 
| 22         | Utilities                                  | 0                 | 253378                     | 0               | 0                   | 12430698             | 0             | 2486                 | 0                        | 7500000                            | 
| 23         | Construction                               | 0                 | 54367                      | 0               | 0                   | 156570               | 54763         | 896                  | 11127                    | 0                                  | 
| 31-33      | Manufacturing                              | 685167            | 4074414                    | 9222352         | 0                   | 9468436              | 1372625       | 3964471              | 11127670                 | 1771435                            | 
| 42         | Wholesale Trade                            | 0                 | 530815                     | 570718          | 0                   | 3049924              | 67300         | 40609                | 494760                   | 728895                             | 
| 44-45      | Retail Trade                               | 0                 | 1574075                    | 4570869         | 1478407             | 5941600              | 21500         | 311469               | 348713                   | 2806113                            | 
| 48-49      | Transporting and Warehousing               | 0                 | 187068                     | 255213          | 0                   | 693548               | 61900         | 13913                | 0                        | 1200000                            | 
| 51         | Information                                | 0                 | 10047521                   | 10006049        | 0                   | 6303836              | 0             | 61030                | 369805                   | 1622704                            | 
| 52         | Finance and Insurance                      | 15445835          | 9047969                    | 24074932        | 8057516             | 1428665              | 240845        | 8916                 | 3226                     | 4423325                            | 
```