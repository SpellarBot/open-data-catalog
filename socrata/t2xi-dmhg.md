# Department of Economic and Community Development - Brownfield Portfolio

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-economic-and-community-development-brownfield-portfolio) |
| Metadata | [Link](https://data.ct.gov/api/views/t2xi-dmhg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/t2xi-dmhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/t2xi-dmhg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | t2xi-dmhg |
| Name | Department of Economic and Community Development - Brownfield Portfolio |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | brownfield, executive order 38, decd, department of economic and community development |
| Created | 2014-03-20T20:11:06Z |
| Publication Date | 2017-02-03T23:47:02Z |

## Description

This is a list of financial assistance agreements for brownfield projects from April 5, 2005 through December 31, 2016.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| No       |                | fiscal_year             | Fiscal Year             | number        | text          |
| Yes      | series tag     | applicant               | Applicant               | text          | text          |
| No       |                | applicant_address       | Applicant Address       | text          | text          |
| Yes      | series tag     | applicant_municipality  | Applicant Municipality  | text          | text          |
| Yes      | series tag     | applicant_state         | Applicant State         | text          | text          |
| Yes      | series tag     | applicant_zip_code      | Applicant Zip Code      | text          | text          |
| Yes      | series tag     | project_municipality    | Project Municipality    | text          | text          |
| Yes      | series tag     | project_zip_code        | Project Zip Code        | text          | text          |
| Yes      | series tag     | project_county          | Project County          | text          | text          |
| Yes      | series tag     | project_name            | Project Name            | text          | text          |
| Yes      | time           | contract_execution_date | Contract Execution Date | calendar_date | calendar_date |
| Yes      | numeric metric | grant_amount            | Grant Amount            | money         | money         |
| Yes      | numeric metric | loan_amount             | Loan Amount             | money         | money         |
| Yes      | numeric metric | total_assistance        | Total Assistance        | money         | money         |
| Yes      | numeric metric | other_project_funds     | Other Project Funds     | money         | money         |
| Yes      | numeric metric | total_project_cost      | Total Project Cost      | money         | money         |
| Yes      | series tag     | funding_source          | Funding Source          | text          | text          |
| Yes      | series tag     | statutory_reference     | Statutory Reference     | text          | text          |
| Yes      | numeric metric | remediated_acreage      | Remediated Acreage      | number        | number        |
| Yes      | numeric metric | count                   | Count                   | number        | number        |
```

## Time Field

```ls
Value = contract_execution_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applicant_address,fiscal_year
```

## Data Commands

```ls
series e:t2xi-dmhg d:2014-08-07T00:00:00.000Z t:applicant_zip_code=06604 t:project_zip_code=06607 t:project_name="Bootcamp Farms" t:project_county=Fairfield t:funding_source="Brownfield Remediation Program" t:applicant_state=CT t:applicant="Bridgeport, City of" t:statutory_reference="CGS Sec. 32-763" t:project_municipality=Bridgeport t:applicant_municipality=Bridgeport m:grant_amount=1000000 m:count=1 m:total_project_cost=3000000 m:total_assistance=1000000 m:remediated_acreage=3 m:other_project_funds=2000000

series e:t2xi-dmhg d:2014-02-24T00:00:00.000Z t:applicant_zip_code=06413 t:project_zip_code=06413 t:project_name="Clinton Ice Facility /Landfill Remediation and Reuse" t:project_county=Middlesex t:funding_source="Brownfield Remediation Program" t:applicant_state=CT t:applicant="Clinton, Town of" t:statutory_reference="CGS Sec. 32-763" t:project_municipality=Clinton t:applicant_municipality=Clinton m:loan_amount=0 m:grant_amount=200000 m:count=1 m:total_project_cost=200000 m:total_assistance=200000 m:remediated_acreage=9 m:other_project_funds=0

series e:t2xi-dmhg d:2016-12-19T00:00:00.000Z t:applicant_zip_code=06415 t:project_zip_code=06415 t:project_name="Municipal Brownfield Grant - Round 9" t:project_county="New London" t:funding_source="Brownfield Remediation Program" t:applicant_state=CT t:applicant="Colchester, Town of" t:statutory_reference="CGS Sec. 32-763" t:project_municipality=Colchester t:applicant_municipality=Colchester m:grant_amount=518000 m:count=1 m:total_project_cost=645501 m:total_assistance=518000 m:remediated_acreage=2 m:other_project_funds=127501
```

## Meta Commands

```ls
metric m:grant_amount p:integer l:"Grant Amount" d:"Amount of DECD grant funding being provided to the Applicant." t:dataTypeName=money

metric m:loan_amount p:double l:"Loan Amount" d:"Amount of DECD loan funding being provided to the Applicant." t:dataTypeName=money

metric m:total_assistance p:integer l:"Total Assistance" d:"Total amount of DECD funding being provided to the Applicant." t:dataTypeName=money

metric m:other_project_funds p:double l:"Other Project Funds" d:"Amount of non-DECD funding for the project." t:dataTypeName=money

metric m:total_project_cost p:integer l:"Total Project Cost" d:"Total amount of DECD and non-DECD funding being used to complete the project." t:dataTypeName=money

metric m:remediated_acreage p:integer l:"Remediated Acreage" d:"Acres being cleaned or assessed with project funding." t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:t2xi-dmhg l:"Department of Economic and Community Development - Brownfield Portfolio" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/t2xi-dmhg

property e:t2xi-dmhg t:meta.view v:id=t2xi-dmhg v:category=Business v:averageRating=0 v:name="Department of Economic and Community Development - Brownfield Portfolio" v:attribution="Department of Economic and Community Development"

property e:t2xi-dmhg t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:t2xi-dmhg t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| fiscal_year | applicant                                 | applicant_address    | applicant_municipality | applicant_state | applicant_zip_code | project_municipality | project_zip_code | project_county | project_name                                         | contract_execution_date | grant_amount | loan_amount | total_assistance | other_project_funds | total_project_cost | funding_source                 | statutory_reference | remediated_acreage | count | 
| =========== | ========================================= | ==================== | ====================== | =============== | ================== | ==================== | ================ | ============== | ==================================================== | ======================= | ============ | =========== | ================ | =================== | ================== | ============================== | =================== | ================== | ===== | 
| 2015        | Bridgeport, City of                       | 999 Broad Street     | Bridgeport             | CT              | 06604              | Bridgeport           | 06607            | Fairfield      | Bootcamp Farms                                       | 2014-08-07T00:00:00     | 1000000      |             | 1000000          | 2000000             | 3000000            | Brownfield Remediation Program | CGS Sec. 32-763     | 3                  | 1     | 
| 2014        | Clinton, Town of                          | 54 East Main Street  | Clinton                | CT              | 06413              | Clinton              | 06413            | Middlesex      | Clinton Ice Facility /Landfill Remediation and Reuse | 2014-02-24T00:00:00     | 200000       | 0.0         | 200000           | 0.0                 | 200000             | Brownfield Remediation Program | CGS Sec. 32-763     | 9                  | 1     | 
| 2017        | Colchester, Town of                       | 127 Norwich Avenue   | Colchester             | CT              | 06415              | Colchester           | 06415            | New London     | Municipal Brownfield Grant - Round 9                 | 2016-12-19T00:00:00     | 518000       |             | 518000           | 127501              | 645501             | Brownfield Remediation Program | CGS Sec. 32-763     | 2                  | 1     | 
| 2016        | East Hartford, Town of                    | 740 Main Street      | East Hartford          | CT              | 06108              | East Hartford        | 06108            | Hartford       | BAR Plan Silver Lane Corridor                        | 2016-02-23T00:00:00     | 200000       |             | 200000           |                     | 200000             | Brownfield Remediation Program | CGS Sec. 32-763     | 1                  | 1     | 
| 2015        | Grace Community & Development Corporation | One Bosco Drive      | New Britain            | CT              | 06050              | New Britain          | 06050            | Hartford       | Targeted Brownfield Development Loan                 | 2015-06-09T00:00:00     |              | 350000      | 350000           | 5855000             |                    | Brownfield Remediation Program | CGS Sec. 32-765     | 2                  | 1     | 
| 2015        | Groton, Town of                           | 45 Fort Hill Road    | Groton                 | CT              | 06340              | Groton               | 06340            | New London     | Municipal Brownfield Grant                           | 2015-03-21T00:00:00     | 200000       |             | 200000           | 0.0                 | 200000             | Brownfield Remediation Program | CGS Sec.32-763      | 4                  | 1     | 
| 2016        | Haddam, Town of                           | 30 Field Park Drive  | Haddam                 | CT              | 06438              | Haddam               | 06438            | Middlesex      | Brownfield Historic Grant                            | 2015-09-01T00:00:00     | 300000       |             | 300000           |                     | 300000             | Brownfield Remediation Program | CGS Sec. 32-763     | 51                 | 1     | 
| 2017        | Meriden, City of                          | 144 Mills Memorial   | Meriden                | CT              | 06450              | Meriden              | 06450            | New Haven      | Municipal Brownfield Grant Round 8                   | 2016-09-29T00:00:00     | 2000000      |             | 2000000          | 6020052             | 8220052            | Brownfield Remediation Program | CGS Sec. 32-763     | 3                  | 1     | 
| 2016        | Meriden, City of                          | 142 East Main Street | Meriden                | CT              | 06450              | Meriden              | 06450            | New Haven      | BAR Plan - Historic (TOD) Sub-district               | 2016-03-03T00:00:00     | 200000       |             | 200000           |                     | 200000             | Brownfield Remediation Program | CGS Sec. 32-763     | 1                  | 1     | 
| 2017        | Meriden, City of                          | 144 Mills Memorial   | Meriden                | CT              | 06450              | Meriden              | 06450            | New Haven      | Municipal Brownfield Grant Round 8                   | 2016-09-29T00:00:00     | 2000000      |             | 2000000          | 6020052             | 8220052            | Brownfield Remediation Program | CGS Sec. 32-763     | 3                  | 1     | 
```