# Department of Economic and Community Development ? Business Assistance Portfolio

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-economic-and-community-development-business-assistance-portfolio) |
| Metadata | [Link](https://data.ct.gov/api/views/xnw3-nytd) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/xnw3-nytd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/xnw3-nytd/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | xnw3-nytd |
| Name | Department of Economic and Community Development ? Business Assistance Portfolio |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, decd, department of economic and community development, business assistance, grant, loan |
| Created | 2014-03-26T17:11:03Z |
| Publication Date | 2017-03-24T22:41:43Z |

## Description

Department of Economic and Community Development's listing of active, direct financial assistance to businesses from Fiscal Year 1993 through 12/31/16. This list also includes out of business projects and inactive (repaid/contract no longer active) projects from the last five years.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ================================================ | ================================================= | ============= | ============= |
| No       |                | fiscal_year                                      | Fiscal Year                                       | number        | text          |
| Yes      | series tag     | company                                          | Company                                           | text          | text          |
| No       |                | address                                          | Address                                           | text          | text          |
| Yes      | series tag     | municipality                                     | Municipality                                      | text          | text          |
| Yes      | series tag     | county_1                                         | County 1                                          | text          | text          |
| Yes      | series tag     | state                                            | State                                             | text          | text          |
| Yes      | series tag     | zip_code                                         | Zip Code                                          | text          | text          |
| Yes      | series tag     | industry                                         | Industry                                          | text          | text          |
| Yes      | series tag     | naics_code                                       | NAICS Code                                        | text          | text          |
| Yes      | series tag     | minority_or_women_owned                          | Minority or Women Owned                           | text          | text          |
| Yes      | time           | contract_execution_date                          | Contract Execution Date                           | calendar_date | calendar_date |
| Yes      | numeric metric | grant_amount                                     | Grant Amount                                      | money         | money         |
| Yes      | numeric metric | loan_amount                                      | Loan Amount                                       | money         | money         |
| Yes      | numeric metric | total_assistance                                 | Total Assistance                                  | money         | money         |
| Yes      | numeric metric | total_project_cost                               | Total Project Cost                                | money         | money         |
| Yes      | numeric metric | amount_leveraged                                 | Amount Leveraged                                  | money         | money         |
| Yes      | series tag     | funding_source                                   | Funding Source                                    | text          | text          |
| Yes      | series tag     | statutory_reference                              | Statutory Reference                               | text          | text          |
| Yes      | numeric metric | contract_requirement_jobs_to_be_retained         | Contract Requirement:Jobs to be Retained          | number        | number        |
| Yes      | numeric metric | contract_requirement_jobs_to_be_created          | Contract Requirement: Jobs to be Created          | number        | number        |
| No       |                | contract_requirement_target_date                 | Contract Requirement: Target Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | actual_jobs_at_time_of_review                    | Actual Jobs at Time of Review                     | number        | number        |
| Yes      | series tag     | job_obligation_status                            | Job Obligation Status                             | text          | text          |
| Yes      | series tag     | job_penalty_if_applicable                        | Job Penalty(if applicable)                        | text          | text          |
| Yes      | numeric metric | forgiveness_credit_if_applicable                 | Forgiveness Credit(if applicable)                 | money         | money         |
| Yes      | numeric metric | per_application_full_time_ct_jobs_at_application | Per Application: Full Time CT Jobs at Application | number        | number        |
| Yes      | numeric metric | per_application_full_time_jobs_to_be_created     | Per Application: Full Time Jobs to be Created     | number        | number        |
| Yes      | numeric metric | per_application_part_time_ct_jobs_at_application | Per Application: Part Time CT Jobs at Application | number        | number        |
| Yes      | numeric metric | per_application_part_time_jobs_to_be_created     | Per Application: Part Time Jobs to be Created     | number        | number        |
| Yes      | series tag     | status                                           | Status                                            | text          | text          |
| Yes      | numeric metric | count                                            | Count                                             | number        | number        |
```

## Time Field

```ls
Value = contract_execution_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,contract_requirement_target_date,fiscal_year
```

## Data Commands

```ls
series e:xnw3-nytd d:2016-09-16T00:00:00.000Z t:zip_code=06206 t:county_1=Windham t:status=Active t:minority_or_women_owned=no t:company="1st Alliance Lending, LLC" t:funding_source="Manufacturing Assistance Act" t:state=CT t:municipality=Putnam t:statutory_reference="CH 588l" t:job_obligation_status=Pending t:industry="Financial Services" t:job_penalty_if_applicable=n/a t:naics_code=522310 m:loan_amount=6000000 m:per_application_full_time_jobs_to_be_created=168 m:grant_amount=0 m:contract_requirement_jobs_to_be_retained=132 m:per_application_full_time_ct_jobs_at_application=132 m:total_project_cost=11451931 m:per_application_part_time_jobs_to_be_created=0 m:per_application_part_time_ct_jobs_at_application=0 m:total_assistance=6000000 m:amount_leveraged=5451931 m:contract_requirement_jobs_to_be_created=168

series e:xnw3-nytd d:2012-10-03T00:00:00.000Z t:zip_code=06082 t:county_1=Hartford t:status=Active t:minority_or_women_owned=no t:company="Advance Stores Company, Incorporated" t:funding_source="Manufacturing Assistance Act" t:state=CT t:municipality=Enfield t:statutory_reference="CH 588l" t:job_obligation_status=Met t:industry="Retail Trade" t:job_penalty_if_applicable=n/a t:naics_code=441310 m:loan_amount=5000000 m:per_application_full_time_jobs_to_be_created=0 m:grant_amount=0 m:contract_requirement_jobs_to_be_retained=0 m:per_application_full_time_ct_jobs_at_application=0 m:total_project_cost=33000000 m:per_application_part_time_jobs_to_be_created=0 m:per_application_part_time_ct_jobs_at_application=0 m:total_assistance=5000000 m:forgiveness_credit_if_applicable=3000000 m:amount_leveraged=28000000 m:contract_requirement_jobs_to_be_created=107 m:actual_jobs_at_time_of_review=240

series e:xnw3-nytd d:2005-11-03T00:00:00.000Z t:zip_code=06109 t:county_1=Hartford t:status=Active t:minority_or_women_owned=no t:company="Americus Dental Labs, Inc." t:funding_source="Manufacturing Assistance Act" t:state=CT t:municipality=Wethersfield t:statutory_reference="CH 588l" t:job_obligation_status="Not Met" t:industry=Manufacturing t:job_penalty_if_applicable="$16,000 paid" t:naics_code=339114 m:loan_amount=153950 m:per_application_full_time_jobs_to_be_created=25 m:grant_amount=0 m:contract_requirement_jobs_to_be_retained=54 m:per_application_full_time_ct_jobs_at_application=54 m:total_project_cost=5440000 m:per_application_part_time_jobs_to_be_created=5 m:per_application_part_time_ct_jobs_at_application=17 m:total_assistance=153950 m:amount_leveraged=5286050 m:contract_requirement_jobs_to_be_created=21 m:actual_jobs_at_time_of_review=59
```

## Meta Commands

```ls
metric m:grant_amount p:integer l:"Grant Amount" d:"Amount of DECD grant funding being provided to the Company." t:dataTypeName=money

metric m:loan_amount p:integer l:"Loan Amount" d:"Amount of DECD loan funding being provided to the Company." t:dataTypeName=money

metric m:total_assistance p:integer l:"Total Assistance" d:"Total amount of DECD funding being provided to the Company." t:dataTypeName=money

metric m:total_project_cost p:integer l:"Total Project Cost" d:"Total amount of DECD and non-DECD funding being used to complete the project." t:dataTypeName=money

metric m:amount_leveraged p:integer l:"Amount Leveraged" d:"Amount of non-DECD funding for the project." t:dataTypeName=money

metric m:contract_requirement_jobs_to_be_retained p:integer l:"Contract Requirement:Jobs to be Retained" d:"Contractual obligation for job retention." t:dataTypeName=number

metric m:contract_requirement_jobs_to_be_created p:integer l:"Contract Requirement: Jobs to be Created" d:"Contractual obligation for job creation." t:dataTypeName=number

metric m:actual_jobs_at_time_of_review p:integer l:"Actual Jobs at Time of Review" d:"Actual jobs created and/or retained as determined by DECD job review or outside accounting firm review." t:dataTypeName=number

metric m:forgiveness_credit_if_applicable p:integer l:"Forgiveness Credit(if applicable)" d:"Amount of loan forgiven if contractual employment requirements are met." t:dataTypeName=money

metric m:per_application_full_time_ct_jobs_at_application p:integer l:"Per Application: Full Time CT Jobs at Application" d:"Employment levels provided by the Company at time of Application." t:dataTypeName=number

metric m:per_application_full_time_jobs_to_be_created p:integer l:"Per Application: Full Time Jobs to be Created" d:"Employment levels provided by the Company at time of Application." t:dataTypeName=number

metric m:per_application_part_time_ct_jobs_at_application p:integer l:"Per Application: Part Time CT Jobs at Application" d:"Employment levels provided by the Company at time of Application." t:dataTypeName=number

metric m:per_application_part_time_jobs_to_be_created p:integer l:"Per Application: Part Time Jobs to be Created" d:"Employment levels provided by the Company at time of Application." t:dataTypeName=number

metric m:count p:long l:Count t:dataTypeName=number

entity e:xnw3-nytd l:"Department of Economic and Community Development ? Business Assistance Portfolio" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/xnw3-nytd

property e:xnw3-nytd t:meta.view v:id=xnw3-nytd v:category=Business v:averageRating=0 v:name="Department of Economic and Community Development ? Business Assistance Portfolio" v:attribution="Department of Economic and Community Development"

property e:xnw3-nytd t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:xnw3-nytd t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| fiscal_year | company                                    | address                                             | municipality | county_1   | state | zip_code | industry                | naics_code | minority_or_women_owned | contract_execution_date | grant_amount | loan_amount | total_assistance | total_project_cost | amount_leveraged | funding_source               | statutory_reference | contract_requirement_jobs_to_be_retained | contract_requirement_jobs_to_be_created | contract_requirement_target_date | actual_jobs_at_time_of_review | job_obligation_status | job_penalty_if_applicable     | forgiveness_credit_if_applicable | per_application_full_time_ct_jobs_at_application | per_application_full_time_jobs_to_be_created | per_application_part_time_ct_jobs_at_application | per_application_part_time_jobs_to_be_created | status | count | 
| =========== | ========================================== | =================================================== | ============ | ========== | ===== | ======== | ======================= | ========== | ======================= | ======================= | ============ | =========== | ================ | ================== | ================ | ============================ | =================== | ======================================== | ======================================= | ================================ | ============================= | ===================== | ============================= | ================================ | ================================================ | ============================================ | ================================================ | ============================================ | ====== | ===== | 
| 2017        | 1st Alliance Lending, LLC                  | 111 Founders Plaza, Suite 1300 East Hartford, 06108 | Putnam       | Windham    | CT    | 06206    | Financial Services      | 522310     | no                      | 2016-09-16T00:00:00     | 0            | 6000000     | 6000000          | 11451931           | 5451931          | Manufacturing Assistance Act | CH 588l             | 132                                      | 168                                     | 2018-12-31T00:00:00              |                               | Pending               | n/a                           |                                  | 132                                              | 168                                          | 0                                                | 0                                            | Active |       | 
| 2013        | Advance Stores Company, Incorporated       | 5008 Airport Road                                   | Enfield      | Hartford   | CT    | 06082    | Retail Trade            | 441310     | no                      | 2012-10-03T00:00:00     | 0            | 5000000     | 5000000          | 33000000           | 28000000         | Manufacturing Assistance Act | CH 588l             | 0                                        | 107                                     | 2015-12-31T00:00:00              | 240                           | Met                   | n/a                           | 3000000                          | 0                                                | 0                                            | 0                                                | 0                                            | Active |       | 
| 2006        | Americus Dental Labs, Inc.                 | 36 Mills Street                                     | Wethersfield | Hartford   | CT    | 06109    | Manufacturing           | 339114     | no                      | 2005-11-03T00:00:00     | 0            | 153950      | 153950           | 5440000            | 5286050          | Manufacturing Assistance Act | CH 588l             | 54                                       | 21                                      | 2005-12-31T00:00:00              | 59                            | Not Met               | $16,000 paid                  |                                  | 54                                               | 25                                           | 17                                               | 5                                            | Active |       | 
| 2014        | Applango USA, Inc.                         | 175 Atlantic Street                                 | Thomaston    | Litchfield | CT    | 06878    | Service                 | 519130     | no                      | 2014-01-14T00:00:00     | 100000       | 0           | 100000           | 200000             | 100000           | Manufacturing Assistance Act | CH 588l             | 0                                        | 4                                       | 2016-01-14T00:00:00              |                               | Pending               | n/a                           |                                  | 4                                                | 4                                            | 0                                                | 0                                            | Active |       | 
| 2008        | Blue Sky Studios, Inc.*                    | One American Lane, #210                             | Greenwich    | Fairfield  | CT    | 06830    | Media and Entertainment | 512110     | no                      | 2008-06-30T00:00:00     | 0            | 8000000     | 8000000          | 65000000           | 57000000         | Manufacturing Assistance Act | CH 588l             | 0                                        | 300                                     | 2012-06-30T00:00:00              | 360                           | Met                   | n/a                           | 6960000                          | 0                                                | 300                                          | 0                                                | 0                                            | Active |       | 
| 2006        | Fairfield Crystal Technologies, LLC        | 8 South End Plaza/Old Town Road                     | New Milford  | Litchfield | CT    | 06776    | Manufacturing           | 334419     | no                      | 2005-12-28T00:00:00     | 0            | 200000      | 200000           | 637000             | 437000           | Manufacturing Assistance Act | CH 588l             | 2                                        | 25                                      | 2010-12-28T00:00:00              | 2                             | Not Met               | Rate increase from 2% to 4.5% |                                  | 2                                                | 25                                           | 0                                                | 0                                            | Active |       | 
| 2007        | ING Life Insurance and Annuity Company     | One Orange Way C4-N                                 | Windsor      | Hartford   | CT    | 06095    | Financial Services      | 524113     | no                      | 2007-06-01T00:00:00     | 0            | 9900000     | 9900000          | 101675000          | 91775000         | Manufacturing Assistance Act | CH 588l             | 1700                                     | 0                                       | 2012-09-26T00:00:00              | 1907                          | Met                   | n/a                           | 5000000                          | 1634                                             | 0                                            | 101                                              | 0                                            | Active |       | 
| 1993        | Kaman Aerospace Corporation                | Old Windsor Road                                    | Bloomfield   | Hartford   | CT    | 06002    | Manufacturing           | 336411     | no                      | 1992-11-19T00:00:00     | 3000000      | 0           | 3000000          | 6000000            | 3000000          | Manufacturing Assistance Act | CH 588l             |                                          |                                         |                                  |                               | n/a                   | n/a                           |                                  | 1349                                             | 252                                          | 0                                                | 0                                            | Active |       | 
| 2015        | Keno Graphic Services, Inc.                | One Parrott Drive                                   | Shelton      | Fairfield  | CT    | 06848    | Commercial Printing     | 323100     | no                      | 2015-06-29T00:00:00     | 0            | 975000      | 975000           | 1950000            | 975000           | Manufacturing Assistance Act | CH 588l             | 20                                       | 4                                       | 2017-09-01T00:00:00              |                               | Pending               | n/a                           |                                  | 20                                               | 4                                            | 0                                                | 0                                            | Active |       | 
| 2014        | Starwood Hotels & Resorts Worldwide, Inc.* | One Star Point                                      | Stamford     | Fairfield  | CT    | 06902    | Service                 | 561110     | no                      | 2014-04-30T00:00:00     | 0            | 5000000     | 5000000          | 30000000           | 25000000         | Manufacturing Assistance Act | CH 588l             | 980                                      | 340                                     | 2017-12-31T00:00:00              |                               | Pending               | n/a                           |                                  | 980                                              | 340                                          | 0                                                | 0                                            | Active |       | 
```