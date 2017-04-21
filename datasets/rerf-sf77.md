# Excelsior Jobs Program - Businesses Admitted: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/excelsior-jobs-program-businesses-admitted-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/rerf-sf77) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rerf-sf77/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rerf-sf77/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rerf-sf77 |
| Name | Excelsior Jobs Program - Businesses Admitted: Beginning 2010 |
| Attribution | Empire State Development |
| Category | Economic Development |
| Tags | excelsior, tax credits |
| Created | 2014-01-29T18:25:37Z |
| Publication Date | 2016-08-02T19:40:05Z |

## Description

Empire State Development produces a quarterly report with a cumulative list of businesses admitted to the Excelsior Jobs Program.  The dataset displays the name and type of business, the location, job and investment commitments, and the dollar amount of tax credits allocated to each business.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | applicant_name                      | Applicant Name                      | text      | text        |
| Yes      | series tag     | esd_region                          | ESD Region                          | text      | text        |
| Yes      | series tag     | type_of_business                    | Type of Business                    | text      | text        |
| Yes      | series tag     | track                               | Track                               | text      | text        |
| Yes      | numeric metric | jobs_when_certified                 | Jobs When Certified                 | number    | number      |
| Yes      | numeric metric | net_new_jobs_commitment             | Net New Jobs Commitment             | number    | number      |
| Yes      | numeric metric | investment_commitment               | Investment Commitment               | money     | money       |
| Yes      | numeric metric | research_and_development_commitment | Research and Development Commitment | money     | money       |
| Yes      | numeric metric | maximum_tax_credits                 | Maximum Tax Credits                 | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rerf-sf77 d:2010-01-01T00:00:00.000Z t:track="Investment Track" t:esd_region=CD t:type_of_business=Distribution t:applicant_name="Ace Hardware Corporation" m:investment_commitment=18000000 m:net_new_jobs_commitment=25 m:maximum_tax_credits=500000 m:jobs_when_certified=292 m:research_and_development_commitment=0

series e:rerf-sf77 d:2010-01-01T00:00:00.000Z t:track="Jobs Track" t:esd_region=CD t:type_of_business="Software Dev" t:applicant_name="Apprenda, Inc." m:investment_commitment=0 m:net_new_jobs_commitment=29 m:maximum_tax_credits=400000 m:jobs_when_certified=92 m:research_and_development_commitment=0

series e:rerf-sf77 d:2010-01-01T00:00:00.000Z t:track="Jobs Track" t:esd_region=CD t:type_of_business=Manufacturing t:applicant_name="Bimbo Bakeries USA" m:investment_commitment=0 m:net_new_jobs_commitment=50 m:maximum_tax_credits=450000 m:jobs_when_certified=1531 m:research_and_development_commitment=0
```

## Meta Commands

```ls
metric m:jobs_when_certified p:integer l:"Jobs When Certified" d:"Number of full time permanent employees at all NYS locations as of the eligibility date" t:dataTypeName=number

metric m:net_new_jobs_commitment p:integer l:"Net New Jobs Commitment" d:"Projected number of full time permanent jobs a business commits to creating." t:dataTypeName=number

metric m:investment_commitment p:double l:"Investment Commitment" d:"Dollar amount of projected capital investments a business commits to investing." t:dataTypeName=money

metric m:research_and_development_commitment p:double l:"Research and Development Commitment" d:"Dollar amount of projected research and development expenditures committed to by a business." t:dataTypeName=money

metric m:maximum_tax_credits p:double l:"Maximum Tax Credits" d:"Maximum dollar amount of tax credits allocated to the business." t:dataTypeName=money

entity e:rerf-sf77 l:"Excelsior Jobs Program - Businesses Admitted: Beginning 2010" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/rerf-sf77

property e:rerf-sf77 t:meta.view v:id=rerf-sf77 v:category="Economic Development" v:attributionLink=http://esd.ny.gov/BusinessPrograms/Excelsior.html v:averageRating=0 v:name="Excelsior Jobs Program - Businesses Admitted: Beginning 2010" v:attribution="Empire State Development"

property e:rerf-sf77 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rerf-sf77 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rerf-sf77 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| applicant_name                       | esd_region | type_of_business | track            | jobs_when_certified | net_new_jobs_commitment | investment_commitment | research_and_development_commitment | maximum_tax_credits | 
| ==================================== | ========== | ================ | ================ | =================== | ======================= | ===================== | =================================== | =================== | 
| Ace Hardware Corporation             | CD         | Distribution     | Investment Track | 292                 | 25                      | 18000000.00           | 0.00                                | 500000.00           | 
| Apprenda, Inc.                       | CD         | Software Dev     | Jobs Track       | 92                  | 29                      | 0.00                  | 0.00                                | 400000.00           | 
| Bimbo Bakeries USA                   | CD         | Manufacturing    | Jobs Track       | 1531                | 50                      | 0.00                  | 0.00                                | 450000.00           | 
| Ferguson Enterprises, Inc.           | CD         | Distribution     | Investment Track | 483                 | 95                      | 40500000.00           | 0.00                                | 1200000.00          | 
| Ginsberg's Institutional Foods, Inc. | CD         | Distribution     | Investment Track | 233                 | 51                      | 7725000.00            | 0.00                                | 995000.00           | 
| Green Renewable, Inc.                | CD         | Manufacturing    | Jobs Track       | 18                  | 35                      | 0.00                  | 0.00                                | 300000.00           | 
| Hacker Boat Company, Inc.            | CD         | Manufacturing    | Jobs Track       | 44                  | 40                      | 0.00                  | 0.00                                | 600000.00           | 
| Hudson River Foods Corporation       | CD         | Manufacturing    | Jobs Track       | 0                   | 64                      | 0.00                  | 0.00                                | 200000.00           | 
| M & G DuraVent, Inc. (#1)            | CD         | Manufacturing    | Jobs Track       | 64                  | 103                     | 0.00                  | 0.00                                | 1000000.00          | 
| Precisionaire, Inc.                  | CD         | Manufacturing    | Jobs Track       | 0                   | 180                     | 0.00                  | 0.00                                | 500000.00           | 
```