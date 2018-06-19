# Department of Economic and Community Development ? Community Development Portfolio

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-economic-and-community-development-community-development-portfolio) |
| Metadata | [Link](https://data.ct.gov/api/views/adkf-vin2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/adkf-vin2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/adkf-vin2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | adkf-vin2 |
| Name | Department of Economic and Community Development ? Community Development Portfolio |
| Attribution | Department of Economic and Community Development |
| Category | Housing and Development |
| Tags | executive order 38, decd, department of economic and community development, community, development, grant, loan, municipality, theater, museum, non-profit, urban act, steap, public act, special ac... |
| Created | 2014-03-27T19:29:26Z |
| Publication Date | 2016-03-22T15:54:37Z |

## Description

Department of Economic and Community Development listing of direct financial assistance for community development and improvement projects from Fiscal Year 2003 through12/31/2015

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | fiscal_year         | Fiscal Year         | number        | text          |
| Yes      | series tag     | applicant           | Applicant           | text          | text          |
| No       |                | address             | Address             | text          | text          |
| Yes      | series tag     | municipality        | Municipality        | text          | text          |
| Yes      | series tag     | state               | State               | text          | text          |
| Yes      | series tag     | zip_code            | Zip Code            | text          | text          |
| Yes      | series tag     | project_name        | Project Name        | text          | text          |
| Yes      | time           | closing_date        | Closing Date        | calendar_date | calendar_date |
| Yes      | numeric metric | grant_amount        | Grant Amount        | money         | money         |
| Yes      | numeric metric | loan_amount         | Loan Amount         | money         | money         |
| Yes      | numeric metric | total_assistance    | Total Assistance    | money         | money         |
| Yes      | numeric metric | total_project_cost  | Total Project Cost  | money         | money         |
| Yes      | numeric metric | amount_leveraged    | Amount Leveraged    | money         | money         |
| Yes      | series tag     | funding_source      | Funding Source      | text          | text          |
| Yes      | series tag     | statutory_reference | Statutory Reference | text          | text          |
```

## Time Field

```ls
Value = closing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,fiscal_year
```

## Data Commands

```ls
series e:adkf-vin2 d:2003-10-06T00:00:00.000Z t:project_name="Downtown Green Development" t:zip_code=06037 t:funding_source="Small Town Economic Assistance Program" t:applicant="Berlin, Town of" t:municipality=Berlin t:state=CT t:statutory_reference="CGS Sec. 4-66g" m:loan_amount=0 m:grant_amount=500000 m:total_project_cost=950000 m:total_assistance=500000 m:amount_leveraged=450000

series e:adkf-vin2 d:2003-12-15T00:00:00.000Z t:project_name="City Center Initiative Plan" t:zip_code=06450 t:funding_source="Urban Act" t:applicant="Meriden Economic Resource Group, Inc." t:municipality=Meriden t:state=CT t:statutory_reference="CGS Sec. 4-66c" m:loan_amount=0 m:grant_amount=250000 m:total_project_cost=250000 m:total_assistance=250000 m:amount_leveraged=0

series e:adkf-vin2 d:2004-01-15T00:00:00.000Z t:project_name="Sherman Playhouse - Window Replacement" t:zip_code=06784 t:funding_source="Small Town Economic Assistance Program" t:applicant="Sherman, Town of" t:municipality=Sherman t:state=CT t:statutory_reference="CGS Sec. 4-66g" m:loan_amount=0 m:grant_amount=12000 m:total_project_cost=12000 m:total_assistance=12000 m:amount_leveraged=0
```

## Meta Commands

```ls
metric m:grant_amount p:integer l:"Grant Amount" d:"Amount of DECD grant funding being provided to the Applicant." t:dataTypeName=money

metric m:loan_amount p:double l:"Loan Amount" d:"Amount of DECD loan funding being provided to the Applicant." t:dataTypeName=money

metric m:total_assistance p:integer l:"Total Assistance" d:"Total amount of DECD funding being provided to the Applicant." t:dataTypeName=money

metric m:total_project_cost p:integer l:"Total Project Cost" d:"Total amount of DECD and non-DECD funding being used to complete the project." t:dataTypeName=money

metric m:amount_leveraged p:double l:"Amount Leveraged" d:"Amount of non-DECD funding for the project." t:dataTypeName=money

entity e:adkf-vin2 l:"Department of Economic and Community Development ? Community Development Portfolio" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/adkf-vin2

property e:adkf-vin2 t:meta.view v:id=adkf-vin2 v:category="Housing and Development" v:averageRating=0 v:name="Department of Economic and Community Development ? Community Development Portfolio" v:attribution="Department of Economic and Community Development"

property e:adkf-vin2 t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:adkf-vin2 t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| fiscal_year | applicant                             | address                        | municipality | state | zip_code | project_name                                          | closing_date        | grant_amount | loan_amount | total_assistance | total_project_cost | amount_leveraged | funding_source                         | statutory_reference | 
| =========== | ===================================== | ============================== | ============ | ===== | ======== | ===================================================== | =================== | ============ | =========== | ================ | ================== | ================ | ====================================== | =================== | 
| 2004        | Berlin, Town of                       | Town Hall, 240 Kensington Road | Berlin       | CT    | 06037    | Downtown Green Development                            | 2003-10-06T00:00:00 | 500000       | 0.0         | 500000           | 950000             | 450000           | Small Town Economic Assistance Program | CGS Sec. 4-66g      | 
| 2004        | Meriden Economic Resource Group, Inc. | P.O. Box 888                   | Meriden      | CT    | 06450    | City Center Initiative Plan                           | 2003-12-15T00:00:00 | 250000       | 0.0         | 250000           | 250000             | 0.0              | Urban Act                              | CGS Sec. 4-66c      | 
| 2004        | Sherman, Town of                      | P.O. Box 39                    | Sherman      | CT    | 06784    | Sherman Playhouse - Window Replacement                | 2004-01-15T00:00:00 | 12000        | 0.0         | 12000            | 12000              | 0.0              | Small Town Economic Assistance Program | CGS Sec. 4-66g      | 
| 2004        | Ledyard, Town of                      | Colonel Ledyard Highway        | Ledyard      | CT    | 06339    | Ledyard Infrastructure Improvements - Phase 1         | 2004-06-22T00:00:00 | 490000       | 0.0         | 490000           | 1478750            | 988750           | Small Town Economic Assistance Program | CGS Sec. 4-66g      | 
| 2005        | Hellenic Society "Paideia", Inc.      | P.O. Box 1399                  | Bristol      | CT    | 06010    | Bristol Culture & Arts Center Project                 | 2004-07-16T00:00:00 | 225000       | 0.0         | 225000           | 225000             | 0.0              | Urban Act                              | CGS Sec. 4-66c      | 
| 2005        | Derby, City of                        | One Elizabeth Street           | Derby        | CT    | 06418    | Sterling Opera House Restoration                      | 2005-01-13T00:00:00 | 1000000      | 0.0         | 1000000          | 5000000            | 4000000          | Urban Act                              | CGS Sec. 4-66c      | 
| 2005        | Hebron, Town of                       | Town Hall, 15 Gilead Street    | Hebron       | CT    | 06248    | Village Green District                                | 2005-01-20T00:00:00 | 500000       | 0.0         | 500000           | 500000             | 0.0              | Small Town Economic Assistance Program | CGS Sec. 4-66g      | 
| 2005        | Berlin, Town of                       | Town Hall, 240 Kensington Road | Berlin       | CT    | 06037    | Town Center Public Improvements                       | 2005-05-06T00:00:00 | 500000       | 0.0         | 500000           | 775000             | 275000           | Small Town Economic Assistance Program | CGS Sec. 4-66g      | 
| 2005        | Griswold, Town of                     | Town Hall, 28 Main Street      | Griswold     | CT    | 06351    | Triangle Wire & Cable Company Redevelopment Planning  | 2005-05-12T00:00:00 | 195000       | 0.0         | 195000           | 695000             | 500000           | Manufacturing Assistance Act           | Chapter 588l        | 
| 2005        | East Lyme, Town of                    | P.O. Box 519                   | Niantic      | CT    | 06357    | Hole in the Wall Environmentally Friendly Parking Lot | 2005-06-23T00:00:00 | 500000       | 0.0         | 500000           | 500000             | 0.0              | Small Town Economic Assistance Program | CGS Sec. 4-66g      | 
```