# Bid data on projects for the past 10 years

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bid-data-on-projects-for-the-past-10-years-23396) |
| Metadata | [Link](https://data.illinois.gov/api/views/u8e9-ci8g) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u8e9-ci8g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u8e9-ci8g/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u8e9-ci8g |
| Name | Bid data on projects for the past 10 years |
| Attribution | Capital Development Board |
| Category | Social/Healthcare |
| Tags | cdb, capital development board, firms, project, bid |
| Created | 2014-01-07T20:12:59Z |
| Publication Date | 2017-02-27T15:04:33Z |

## Description

Lists all the firms that bid on projects from 2004 to present

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | project_number                       | Project Number                       | text      | text        |
| Yes      | series tag     | project_description                  | Project Description                  | text      | text        |
| Yes      | numeric metric | phase                                | Phase                                | number    | text        |
| Yes      | numeric metric | bid_amt                              | Bid Amt                              | money     | money       |
| Yes      | series tag     | awarded                              | Awarded?                             | text      | text        |
| Yes      | series tag     | bid_date                             | Bid Date                             | html      | html        |
| Yes      | series tag     | contr_firm_legal_name                | Contr Firm Legal Name                | text      | text        |
| Yes      | series tag     | contr_firm_street_address_line_1     | Contr Firm Street Address Line 1     | text      | text        |
| Yes      | series tag     | city_description                     | City Description                     | text      | text        |
| Yes      | series tag     | contr_firm_street_state_id           | Contr Firm Street State ID           | text      | text        |
| Yes      | series tag     | contr_firm_street_zip_code           | Contr Firm Street Zip Code           | text      | text        |
| Yes      | series tag     | county_name                          | County Name                          | text      | text        |
| Yes      | series tag     | contr_firm_minority_code_description | Contr Firm Minority Code Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u8e9-ci8g d:2017-02-27T15:04:16.000Z t:contr_firm_street_zip_code=61550 t:contr_firm_legal_name="Core Construction Services of Illinois, Inc." t:contr_firm_street_address_line_1="866 N Main Street" t:bid_date=8/18/11 t:contr_firm_minority_code_description="Non-Minority Male" t:contr_firm_street_state_id=IL t:project_number=006-100-004 t:awarded=Y t:county_name=Tazewell t:city_description=Morton t:project_description="HVAC System Upgrade" m:phase=2 m:bid_amt=41940000

series e:u8e9-ci8g d:2017-02-27T15:04:16.000Z t:contr_firm_street_zip_code=62230 t:contr_firm_legal_name="Poettker Construction Company" t:contr_firm_street_address_line_1="380 S Germantown Road" t:bid_date=8/18/11 t:contr_firm_minority_code_description="Non-Minority Male" t:contr_firm_street_state_id=IL t:project_number=006-100-004 t:awarded=N t:county_name=Clinton t:city_description=Breese t:project_description="HVAC System Upgrade" m:phase=2 m:bid_amt=43343000

series e:u8e9-ci8g d:2017-02-27T15:04:16.000Z t:contr_firm_street_zip_code=61611 t:contr_firm_legal_name="River City Construction, L.L.C." t:contr_firm_street_address_line_1="101 Hoffer Lane" t:bid_date=8/18/11 t:contr_firm_minority_code_description="Non-Minority Male" t:contr_firm_street_state_id=IL t:project_number=006-100-004 t:awarded=N t:county_name=Peoria t:city_description="East Peoria" t:project_description="HVAC System Upgrade" m:phase=2 m:bid_amt=43747000
```

## Meta Commands

```ls
metric m:phase p:integer l:Phase t:dataTypeName=number

metric m:bid_amt p:double l:"Bid Amt" t:dataTypeName=money

entity e:u8e9-ci8g l:"Bid data on projects for the past 10 years" t:attribution="Capital Development Board" t:url=https://data.illinois.gov/api/views/u8e9-ci8g

property e:u8e9-ci8g t:meta.view v:id=u8e9-ci8g v:category=Social/Healthcare v:attributionLink=http://www.illinois.gov/cdb/Pages/default.aspx v:averageRating=0 v:name="Bid data on projects for the past 10 years" v:attribution="Capital Development Board"

property e:u8e9-ci8g t:meta.view.license v:name="Public Domain"

property e:u8e9-ci8g t:meta.view.owner v:id=stwr-tj4y v:profileImageUrlMedium=/api/users/stwr-tj4y/profile_images/THUMB v:profileImageUrlLarge=/api/users/stwr-tj4y/profile_images/LARGE v:screenName=Scott v:profileImageUrlSmall=/api/users/stwr-tj4y/profile_images/TINY v:displayName=Scott

property e:u8e9-ci8g t:meta.view.tableauthor v:id=stwr-tj4y v:profileImageUrlMedium=/api/users/stwr-tj4y/profile_images/THUMB v:profileImageUrlLarge=/api/users/stwr-tj4y/profile_images/LARGE v:screenName=Scott v:profileImageUrlSmall=/api/users/stwr-tj4y/profile_images/TINY v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| :updated_at | project_number | project_description | phase | bid_amt     | awarded | bid_date | contr_firm_legal_name                        | contr_firm_street_address_line_1 | city_description | contr_firm_street_state_id | contr_firm_street_zip_code | county_name | contr_firm_minority_code_description | 
| =========== | ============== | =================== | ===== | =========== | ======= | ======== | ============================================ | ================================ | ================ | ========================== | ========================== | =========== | ==================================== | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 2     | 41940000.00 | Y       | 8/18/11  | Core Construction Services of Illinois, Inc. | 866 N Main Street                | Morton           | IL                         | 61550                      | Tazewell    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 2     | 43343000.00 | N       | 8/18/11  | Poettker Construction Company                | 380 S Germantown Road            | Breese           | IL                         | 62230                      | Clinton     | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 2     | 43747000.00 | N       | 8/18/11  | River City Construction, L.L.C.              | 101 Hoffer Lane                  | East Peoria      | IL                         | 61611                      | Peoria      | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 5     | 429000.00   | Y       | 4/22/10  | Evans Construction Co.                       | 1900 E Washington Street         | Springfield      | IL                         | 62703                      | Sangamon    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 5     | 504850.00   | N       | 4/22/10  | R.D. Lawrence Construction Company, Ltd.     | 603 North  Amos Avenue           | Springfield      | IL                         | 62702                      | Sangamon    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 5     | 588000.00   | N       | 4/22/10  | Core Construction Services of Illinois, Inc. | 866 N Main Street                | Morton           | IL                         | 61550                      | Tazewell    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 5     | 634000.00   | N       | 4/22/10  | V H Builders Inc                             | P O Box 228                      | Carlinville      | IL                         | 62626                      | Macoupin    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 6     | 512000.00   | Y       | 9/8/10   | R. L. Vollintine Construction, Inc.          | 1621 East Georgia Street         | Springfield      | IL                         | 62703                      | Sangamon    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 6     | 530000.00   | N       | 9/8/10   | Core Construction Services of Illinois, Inc. | 866 N Main Street                | Morton           | IL                         | 61550                      | Tazewell    | Non-Minority Male                    | 
| 1488207856  | 006-100-004    | HVAC System Upgrade | 6     | 553658.00   | N       | 9/8/10   | Halverson Construction Co., Inc.             | 620 North 19th Street            | Springfield      | IL                         | 62702                      | Sangamon    | Non-Minority Male                    | 
```