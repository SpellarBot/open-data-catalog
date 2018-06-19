# Department of Revenue Services - Tax Credits Claimed during Fiscal Year 2012-13 by Industry Sector

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-during-fiscal-year-2012-13-by-industry-) |
| Metadata | [Link](https://data.ct.gov/api/views/bd2s-5fne) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bd2s-5fne/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bd2s-5fne/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bd2s-5fne |
| Name | Department of Revenue Services - Tax Credits Claimed during Fiscal Year 2012-13 by Industry Sector |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, naics, decd, department of economic and community development |
| Created | 2014-03-21T19:12:36Z |
| Publication Date | 2014-03-25T19:16:50Z |

## Description

Department of Revenue Services - Tax Credits Claimed during Fiscal Year 2012-13 (July 1, 2012 through June 30, 2103) by NAICS (North American Industry Classification System)

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | naics_code                         | NAICS Code                           | text      | text        |
| Yes      | series tag     | naics_industry_group               | NAICS Industry Group                 | text      | text        |
| Yes      | numeric metric | digital_animation                  | Digital Animation                    | money     | money       |
| Yes      | numeric metric | electronic_data_processing         | Electronic Data Processing           | money     | money       |
| Yes      | numeric metric | film_production                    | Film Production                      | money     | money       |
| Yes      | numeric metric | film_infrastructure                | Film Infrastructure                  | money     | money       |
| Yes      | numeric metric | fixed_cap_investment               | Fixed Capital Investment             | money     | money       |
| Yes      | numeric metric | job_expansion                      | Job Expansion                        | money     | money       |
| Yes      | numeric metric | research_development               | Research & Development               | money     | money       |
| Yes      | numeric metric | research_experimentation           | Research & Experimentation           | money     | money       |
| Yes      | numeric metric | urban_industrial_site_reinvestment | Urban & Industrial Site Reinvestment | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bd2s-5fne d:2012-01-01T00:00:00.000Z t:naics_industry_group="Agriculture, Forestry, Fishing and Hunting" t:naics_code=11 m:job_expansion=0 m:research_development=0 m:digital_animation=0 m:electronic_data_processing=2539 m:urban_industrial_site_reinvestment=0 m:research_experimentation=0 m:film_infrastructure=0 m:film_production=0 m:fixed_cap_investment=146499

series e:bd2s-5fne d:2012-01-01T00:00:00.000Z t:naics_industry_group=Mining t:naics_code=21 m:job_expansion=0 m:research_development=0 m:digital_animation=0 m:electronic_data_processing=5541 m:urban_industrial_site_reinvestment=0 m:research_experimentation=8949 m:film_infrastructure=0 m:film_production=0 m:fixed_cap_investment=5964

series e:bd2s-5fne d:2012-01-01T00:00:00.000Z t:naics_industry_group=Utilities t:naics_code=22 m:job_expansion=7500 m:research_development=0 m:digital_animation=0 m:electronic_data_processing=89524 m:urban_industrial_site_reinvestment=0 m:research_experimentation=2008 m:film_infrastructure=0 m:film_production=0 m:fixed_cap_investment=6309608
```

## Meta Commands

```ls
metric m:digital_animation p:integer l:"Digital Animation" t:dataTypeName=money

metric m:electronic_data_processing p:integer l:"Electronic Data Processing" t:dataTypeName=money

metric m:film_production p:integer l:"Film Production" t:dataTypeName=money

metric m:film_infrastructure p:integer l:"Film Infrastructure" t:dataTypeName=money

metric m:fixed_cap_investment p:integer l:"Fixed Capital Investment" t:dataTypeName=money

metric m:job_expansion p:integer l:"Job Expansion" t:dataTypeName=money

metric m:research_development p:integer l:"Research & Development" t:dataTypeName=money

metric m:research_experimentation p:integer l:"Research & Experimentation" t:dataTypeName=money

metric m:urban_industrial_site_reinvestment p:integer l:"Urban & Industrial Site Reinvestment" t:dataTypeName=money

entity e:bd2s-5fne l:"Department of Revenue Services - Tax Credits Claimed during Fiscal Year 2012-13 by Industry Sector" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/bd2s-5fne

property e:bd2s-5fne t:meta.view v:id=bd2s-5fne v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed during Fiscal Year 2012-13 by Industry Sector" v:attribution="Department of Economic and Community Development"

property e:bd2s-5fne t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:bd2s-5fne t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| naics_code | naics_industry_group                       | digital_animation | electronic_data_processing | film_production | film_infrastructure | fixed_cap_investment | job_expansion | research_development | research_experimentation | urban_industrial_site_reinvestment | 
| ========== | ========================================== | ================= | ========================== | =============== | =================== | ==================== | ============= | ==================== | ======================== | ================================== | 
| 11         | Agriculture, Forestry, Fishing and Hunting | 0                 | 2539                       | 0               | 0                   | 146499               | 0             | 0                    | 0                        | 0                                  | 
| 21         | Mining                                     | 0                 | 5541                       | 0               | 0                   | 5964                 | 0             | 0                    | 8949                     | 0                                  | 
| 22         | Utilities                                  | 0                 | 89524                      | 0               | 0                   | 6309608              | 7500          | 0                    | 2008                     | 0                                  | 
| 23         | Construction                               | 0                 | 38677                      | 0               | 0                   | 181819               | 0             | 0                    | 15652                    | 0                                  | 
| 31-33      | Manufacturing                              | 528394            | 1886814                    | 4674045         | 0                   | 19750239             | 46723         | 3342424              | 6837522                  | 3093205                            | 
| 42         | Wholesale Trade                            | 0                 | 345872                     | 100000          | 0                   | 2195120              | 980           | 164218               | 350079                   | 635919                             | 
| 44-45      | Retail Trade                               | 0                 | 2003198                    | 489461          | 0                   | 4996612              | 0             | 8351                 | 1063223                  | 2680336                            | 
| 48-49      | Transporting and Warehousing               | 0                 | 312109                     | 217271          | 0                   | 295973               | 0             | 31028                | 0                        | 294627                             | 
| 51         | Information                                | 3074419           | 6646185                    | 9495135         | 525581              | 16077767             | 0             | 23692                | 356940                   | 627281                             | 
| 52         | Finance and Insurance                      | 13332559          | 8603619                    | 22832991        | 793426              | 870454               | 196593        | 6647                 | 87404                    | 2234772                            | 
```