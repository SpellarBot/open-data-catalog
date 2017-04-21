# Economic Development Projects - Not Proceeding

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/economic-development-projects-not-proceeding) |
| Metadata | [Link](https://data.iowa.gov/api/views/5fqa-vy76) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/5fqa-vy76/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/5fqa-vy76/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 5fqa-vy76 |
| Name | Economic Development Projects - Not Proceeding |
| Attribution | Iowa Economic Development Authority, Contract Compliance Team |
| Category | Economy |
| Tags | economic development, projects, declined, terminated, rescinded |
| Created | 2015-01-15T19:29:35Z |
| Publication Date | 2016-03-29T18:32:33Z |

## Description

This dataset includes information on economic development projects that were awarded incentives through Iowa Economic Development Authority programs as early as FY 2003, but selected not to move forward in receiving funding.  This doesn?t necessarily mean that the project didn?t or won't take place.  Projects include those whose awards were declined, rescinded or terminated.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type     | Render Type   |
| ======== | ============== | ============================== | ================================ | ============= | ============= |
| Yes      | series tag     | contract_name                  | Company Name                     | text          | text          |
| Yes      | series tag     | county                         | County                           | text          | text          |
| Yes      | series tag     | city                           | City                             | text          | text          |
| Yes      | series tag     | status                         | Status                           | text          | text          |
| Yes      | series tag     | primary_funding_agreement      | Primary Funding Agreement        | text          | text          |
| Yes      | time           | award_date                     | Award Date                       | calendar_date | calendar_date |
| Yes      | numeric metric | total_project_cost             | Total Project Cost               | money         | money         |
| Yes      | numeric metric | capital_investment             | Capital Investment               | money         | money         |
| Yes      | numeric metric | direct_assistance_awarded      | Direct Assistance Awarded        | money         | money         |
| Yes      | numeric metric | tax_benefits_awarded           | Tax Benefits Awarded             | money         | money         |
| Yes      | numeric metric | projected_jobs_created         | Projected Jobs - Created         | number        | number        |
| Yes      | numeric metric | projected_jobs_retained        | Projected Jobs - Retained        | number        | number        |
| Yes      | numeric metric | projected_jobs_other           | Projected Jobs - Other           | number        | number        |
| Yes      | numeric metric | projected_jobs_total           | Projected Jobs - Total           | number        | number        |
| Yes      | numeric metric | projected_qualifying_wage      | Projected Qualifying Wage        | money         | money         |
| Yes      | numeric metric | contracted_jobs_created        | Contracted Jobs - Created        | number        | number        |
| Yes      | numeric metric | contracted_jobs_retained       | Contracted Jobs - Retained       | number        | number        |
| Yes      | numeric metric | contracted_jobs_other_created  | Contracted Jobs - Other Created  | number        | number        |
| Yes      | numeric metric | contracted_jobs_other_retained | Contracted Jobs - Other Retained | number        | number        |
| Yes      | numeric metric | contracted_jobs_total          | Contracted Jobs - Total          | number        | number        |
| Yes      | numeric metric | contracted_qualifying_wage     | Contracted Qualifying Wage       | money         | money         |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5fqa-vy76 d:2007-08-16T00:00:00.000Z t:contract_name="Midwest Chlor-Alkali, LLC" t:county=Wapello t:status="Contract Terminated" t:primary_funding_agreement=08-HQJC-011 t:city=Eddyville m:contracted_jobs_other_created=0 m:total_project_cost=88975000 m:projected_jobs_other=0 m:contracted_jobs_created=13 m:contracted_qualifying_wage=17.63 m:projected_qualifying_wage=0 m:contracted_jobs_other_retained=0 m:tax_benefits_awarded=3000000 m:projected_jobs_retained=0 m:capital_investment=80097000 m:projected_jobs_total=13 m:contracted_jobs_total=13 m:contracted_jobs_retained=0 m:projected_jobs_created=13

series e:5fqa-vy76 d:2008-08-21T00:00:00.000Z t:contract_name="Quad County Corn Processors" t:county=Ida t:status="Declined or Rescinded" t:primary_funding_agreement=09-VAP-001 t:city=Galva m:contracted_jobs_other_created=4 m:total_project_cost=30000000 m:projected_jobs_other=4 m:contracted_jobs_created=6 m:contracted_qualifying_wage=19.85 m:projected_qualifying_wage=19.98 m:contracted_jobs_other_retained=0 m:tax_benefits_awarded=3219565 m:projected_jobs_retained=0 m:capital_investment=29800000 m:projected_jobs_total=10 m:contracted_jobs_total=10 m:contracted_jobs_retained=0 m:projected_jobs_created=6 m:direct_assistance_awarded=250000

series e:5fqa-vy76 d:2005-09-15T00:00:00.000Z t:contract_name="Loparex Inc." t:county=Johnson t:status="Declined or Rescinded" t:primary_funding_agreement=06-CEBA-011 t:city="Iowa City" m:contracted_jobs_other_created=0 m:total_project_cost=6320443 m:projected_jobs_other=0 m:contracted_jobs_created=15 m:contracted_qualifying_wage=0 m:projected_qualifying_wage=19.56 m:contracted_jobs_other_retained=0 m:tax_benefits_awarded=154150 m:projected_jobs_retained=0 m:capital_investment=5265443 m:projected_jobs_total=15 m:contracted_jobs_total=15 m:contracted_jobs_retained=0 m:projected_jobs_created=15 m:direct_assistance_awarded=75000
```

## Meta Commands

```ls
metric m:total_project_cost p:double l:"Total Project Cost" d:"Total projected cost of the project at time of award" t:dataTypeName=money

metric m:capital_investment p:double l:"Capital Investment" d:"Total projected capital investment at time of award" t:dataTypeName=money

metric m:direct_assistance_awarded p:double l:"Direct Assistance Awarded" d:"Amount of direct assistance awarded to the company to complete project" t:dataTypeName=money

metric m:tax_benefits_awarded p:double l:"Tax Benefits Awarded" d:"Amount of maximum tax benefits awarded to company to complete project" t:dataTypeName=money

metric m:projected_jobs_created p:integer l:"Projected Jobs - Created" d:"Number of jobs projected to be created above projected qualifying wage at time of award. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:projected_jobs_retained p:integer l:"Projected Jobs - Retained" d:"Number of jobs projected to be retained above projected qualifying wage at time of award. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:projected_jobs_other p:integer l:"Projected Jobs - Other" d:"Number of other jobs projected at time of award which fall below the projected qualifying wage. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:projected_jobs_total p:integer l:"Projected Jobs - Total" d:"Sum of projected created, retained and other jobs. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:projected_qualifying_wage p:double l:"Projected Qualifying Wage" d:"Projected threshold/required wage at time of award. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=money

metric m:contracted_jobs_created p:integer l:"Contracted Jobs - Created" d:"Number of jobs to be created above contracted qualifying wage as agreed to in the contract. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:contracted_jobs_retained p:integer l:"Contracted Jobs - Retained" d:"Number of jobs to be retained above the contracted qualifying wage as agreed to in the contract. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:contracted_jobs_other_created p:integer l:"Contracted Jobs - Other Created" d:"Number of other jobs to be created below contracted qualifying wage as noted in the contract. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:contracted_jobs_other_retained p:integer l:"Contracted Jobs - Other Retained" d:"Number of other jobs to be retained below contracted qualifying wage as noted in the contract. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:contracted_jobs_total p:integer l:"Contracted Jobs - Total" d:"Sum of contracted created, retained and other jobs. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=number

metric m:contracted_qualifying_wage p:double l:"Contracted Qualifying Wage" d:"Contracted threshold/required wage as agreed to in the contract for contracted created and retained jobs. NA indicates the data was not available for the project - likely the result of changing program requirements." t:dataTypeName=money

entity e:5fqa-vy76 l:"Economic Development Projects - Not Proceeding" t:attribution="Iowa Economic Development Authority, Contract Compliance Team" t:url=https://data.iowa.gov/api/views/5fqa-vy76

property e:5fqa-vy76 t:meta.view v:id=5fqa-vy76 v:category=Economy v:averageRating=0 v:name="Economic Development Projects - Not Proceeding" v:attribution="Iowa Economic Development Authority, Contract Compliance Team"

property e:5fqa-vy76 t:meta.view.license v:name="Public Domain"

property e:5fqa-vy76 t:meta.view.owner v:id=w4fy-85t2 v:profileImageUrlMedium=/api/users/w4fy-85t2/profile_images/THUMB v:profileImageUrlLarge=/api/users/w4fy-85t2/profile_images/LARGE v:screenName="Iowa Economic Development Authority" v:profileImageUrlSmall=/api/users/w4fy-85t2/profile_images/TINY v:displayName="Iowa Economic Development Authority"

property e:5fqa-vy76 t:meta.view.tableauthor v:id=w4fy-85t2 v:profileImageUrlMedium=/api/users/w4fy-85t2/profile_images/THUMB v:profileImageUrlLarge=/api/users/w4fy-85t2/profile_images/LARGE v:screenName="Iowa Economic Development Authority" v:profileImageUrlSmall=/api/users/w4fy-85t2/profile_images/TINY v:roleName=editor v:displayName="Iowa Economic Development Authority"
```

## Top Records

```ls
| contract_name                         | county     | city        | status                | primary_funding_agreement | award_date          | total_project_cost | capital_investment | direct_assistance_awarded | tax_benefits_awarded | projected_jobs_created | projected_jobs_retained | projected_jobs_other | projected_jobs_total | projected_qualifying_wage | contracted_jobs_created | contracted_jobs_retained | contracted_jobs_other_created | contracted_jobs_other_retained | contracted_jobs_total | contracted_qualifying_wage | 
| ===================================== | ========== | =========== | ===================== | ========================= | =================== | ================== | ================== | ========================= | ==================== | ====================== | ======================= | ==================== | ==================== | ========================= | ======================= | ======================== | ============================= | ============================== | ===================== | ========================== | 
| Midwest Chlor-Alkali, LLC             | Wapello    | Eddyville   | Contract Terminated   | 08-HQJC-011               | 2007-08-16T00:00:00 | 88975000.00        | 80097000.00        |                           | 3000000.00           | 13                     | 0                       | 0                    | 13                   | 0.00                      | 13                      | 0                        | 0                             | 0                              | 13                    | 17.63                      | 
| Quad County Corn Processors           | Ida        | Galva       | Declined or Rescinded | 09-VAP-001                | 2008-08-21T00:00:00 | 30000000.00        | 29800000.00        | 250000.00                 | 3219565.00           | 6                      | 0                       | 4                    | 10                   | 19.98                     | 6                       | 0                        | 4                             | 0                              | 10                    | 19.85                      | 
| Loparex Inc.                          | Johnson    | Iowa City   | Declined or Rescinded | 06-CEBA-011               | 2005-09-15T00:00:00 | 6320443.00         | 5265443.00         | 75000.00                  | 154150.00            | 15                     | 0                       | 0                    | 15                   | 19.56                     | 15                      | 0                        | 0                             | 0                              | 15                    | 0.00                       | 
| Kolman Conveyor Company, Inc.         | Clay       | Spencer     | Declined or Rescinded | 06-CEBA-019               | 2005-10-20T00:00:00 | 2145000.00         | 1795000.00         | 300000.00                 | 90600.00             | 0                      | 0                       | 0                    | 0                    | 21.99                     | 0                       | 0                        | 0                             | 0                              | 0                     | 0.00                       | 
| Eagle Point Software Corporation      | Dubuque    | Dubuque     | Declined or Rescinded | 11-130-019                | 2010-12-16T00:00:00 | 638000.00          | 107000.00          | 105000.00                 | 83050.00             | 15                     | 45                      | 0                    | 60                   | 20.07                     | 15                      |                          | 0                             |                                | 15                    | 20.07                      | 
| T8Design, LLC                         | Black Hawk | Cedar Falls | Declined or Rescinded | 07-CEBA-029               | 2007-02-15T00:00:00 | 2643906.00         | 171000.00          | 100000.00                 |                      | 21                     | 0                       | 16                   | 37                   | 0.00                      | 21                      | 0                        | 16                            | 0                              | 37                    | 20.77                      | 
| United Suppliers, Inc.                | Hardin     | Iowa Falls  | Contract Terminated   | 12-HQJP-038               | 2012-04-20T00:00:00 | 5845000.00         | 5770000.00         |                           | 43075.00             | 1                      | 0                       | 0                    | 1                    | 19.99                     | 1                       | 0                        | 0                             | 0                              | 1                     | 19.99                      | 
| Alternative Energy Sources, Inc.      | Boone      | Ogden       | Declined or Rescinded | 07-HQJC-040               | 2007-05-17T00:00:00 | 279300000.00       | 218300000.00       |                           | 11270000.00          | 39                     | 0                       | 11                   | 50                   | 0.00                      | 39                      | 0                        | 11                            | 0                              | 50                    | 22.56                      | 
| E-Ject Systems, LC                    | Clayton    | Elkader     | Contract Terminated   | 05-EZ-014                 | 2004-10-13T00:00:00 | 2250000.00         | 995830.00          |                           | 275000.00            | 10                     | 0                       | 0                    | 10                   | 0.00                      | 10                      | 0                        | 0                             | 0                              | 10                    | 10.15                      | 
| Geneseo Communications Services, Inc. | Scott      | Davenport   | Declined or Rescinded | 12-130-018                | 2011-12-16T00:00:00 | 15090000.00        | 14990000.00        | 96000.00                  | 568700.00            | 12                     | 0                       | 1                    | 13                   | 22.54                     | 12                      |                          | 1                             |                                | 13                    | 22.54                      | 
```