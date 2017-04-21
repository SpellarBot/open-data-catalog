# Economic Development Subsidies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/economic-development-subsidies) |
| Metadata | [Link](https://data.hawaii.gov/api/views/hk5u-xz4u) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/hk5u-xz4u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/hk5u-xz4u/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | hk5u-xz4u |
| Name | Economic Development Subsidies |
| Created | 2016-01-14T00:54:20Z |
| Publication Date | 2016-01-14T00:56:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | company                             | Company                             | text      | text        |
| Yes      | series tag     | parent_company                      | Parent Company                      | text      | text        |
| Yes      | series tag     | location                            | Location                            | text      | text        |
| Yes      | series tag     | county                              | County                              | text      | text        |
| Yes      | series tag     | project_description                 | Project Description                 | text      | text        |
| Yes      | series tag     | naics_industry_code                 | NAICS Industry Code                 | text      | text        |
| Yes      | time           | year                                | Year                                | number    | number      |
| Yes      | numeric metric | subsidy_value                       | Subsidy Value                       | money     | money       |
| Yes      | numeric metric | megadeal_contribution               | Megadeal Contribution               | money     | money       |
| Yes      | numeric metric | subsidy_value_adjusted_for_megadeal | Subsidy Value Adjusted For Megadeal | money     | money       |
| Yes      | series tag     | program_name                        | Program Name                        | text      | text        |
| Yes      | series tag     | awarding_agency                     | Awarding Agency                     | text      | text        |
| Yes      | series tag     | type_of_subsidy                     | Type of Subsidy                     | text      | text        |
| Yes      | series tag     | number_of_jobs_or_training_slots    | Number of Jobs or Training Slots    | text      | text        |
| Yes      | series tag     | wage_data                           | Wage Data                           | text      | text        |
| Yes      | series tag     | wage_data_type                      | Wage Data Type                      | text      | text        |
| Yes      | series tag     | investment_data                     | Investment Data                     | text      | text        |
| Yes      | series tag     | source_of_data                      | Source of Data                      | text      | text        |
| Yes      | series tag     | notes                               | Notes                               | text      | text        |
| Yes      | series tag     | subsidy_source                      | Subsidy Source                      | text      | text        |
| Yes      | series tag     | cfda_program_number                 | CFDA Program Number                 | text      | text        |
| Yes      | numeric metric | loan_value                          | Loan Value                          | money     | money       |
| Yes      | numeric metric | state_in_which_facility_is_located  | State in Which Facility Is Located  | number    | number      |
| Yes      | series tag     | major_industry_of_parent            | Major Industry of Parent            | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hk5u-xz4u d:2009-01-01T00:00:00.000Z t:subsidy_source=state t:location=Hawaii t:major_industry_of_parent="""""" t:awarding_agency="Department of Taxation" t:company="Zero Emissions Leasing LLC" t:program_name="Qualified High Technology Businesses" t:source_of_data=http://www6.hawaii.gov/tax/a5_1annual.htm t:type_of_subsidy="tax credit/rebate" t:notes="Company name is from listing of firms filing for the tax credit in 2009. Credit amounts are not disclosed." m:subsidy_value_adjusted_for_megadeal=0 m:megadeal_contribution=0 m:loan_value=0

series e:hk5u-xz4u d:2016-01-01T00:00:00.000Z t:subsidy_source=state t:county=Honolulu t:location=Hawaii t:major_industry_of_parent="""hotels""" t:awarding_agency="Department of Labor & Industrial Relations" t:company="Starwood Hotels & Resorts in Waikiki" t:program_name="Employment and Training Fund Statewide Grants" t:source_of_data="direct from agency; not on web" t:type_of_subsidy="training reimbursement" t:notes="Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available" t:parent_company="Starwood Hotels & Resorts" m:subsidy_value_adjusted_for_megadeal=820 m:megadeal_contribution=0 m:subsidy_value=820 m:loan_value=0

series e:hk5u-xz4u d:2016-01-01T00:00:00.000Z t:subsidy_source=state t:county=Hawaii t:location=Hawaii t:major_industry_of_parent="""financial services""" t:awarding_agency="Department of Labor & Industrial Relations" t:company="First Hawaiian Bank" t:program_name="Employment and Training Fund Statewide Grants" t:source_of_data="direct from agency; not on web" t:type_of_subsidy="training reimbursement" t:notes="Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available" t:parent_company="BNP Paribas" m:subsidy_value_adjusted_for_megadeal=740 m:megadeal_contribution=0 m:subsidy_value=740 m:loan_value=0
```

## Meta Commands

```ls
metric m:subsidy_value p:integer l:"Subsidy Value" t:dataTypeName=money

metric m:megadeal_contribution p:integer l:"Megadeal Contribution" t:dataTypeName=money

metric m:subsidy_value_adjusted_for_megadeal p:integer l:"Subsidy Value Adjusted For Megadeal" t:dataTypeName=money

metric m:loan_value p:integer l:"Loan Value" t:dataTypeName=money

metric m:state_in_which_facility_is_located p:long l:"State in Which Facility Is Located" t:dataTypeName=number

entity e:hk5u-xz4u l:"Economic Development Subsidies" t:url=https://data.hawaii.gov/api/views/hk5u-xz4u

property e:hk5u-xz4u t:meta.view v:id=hk5u-xz4u v:averageRating=0 v:name="Economic Development Subsidies"

property e:hk5u-xz4u t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:hk5u-xz4u t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| company                               | parent_company            | location | county   | project_description | naics_industry_code | year | subsidy_value | megadeal_contribution | subsidy_value_adjusted_for_megadeal | program_name                                  | awarding_agency                                        | type_of_subsidy        | number_of_jobs_or_training_slots | wage_data | wage_data_type | investment_data | source_of_data                                         | notes                                                                                                                                    | subsidy_source | cfda_program_number | loan_value | state_in_which_facility_is_located | major_industry_of_parent | 
| ===================================== | ========================= | ======== | ======== | =================== | =================== | ==== | ============= | ===================== | =================================== | ============================================= | ====================================================== | ====================== | ================================ | ========= | ============== | =============== | ====================================================== | ======================================================================================================================================== | ============== | =================== | ========== | ================================== | ======================== | 
| Zero Emissions Leasing LLC            |                           | Hawaii   |          |                     |                     | 2009 |               | 0                     | 0                                   | Qualified High Technology Businesses          | Department of Taxation                                 | tax credit/rebate      |                                  |           |                |                 | http://www6.hawaii.gov/tax/a5_1annual.htm              | Company name is from listing of firms filing for the tax credit in 2009. Credit amounts are not disclosed.                               | state          |                     | 0          |                                    | ""                       | 
| Starwood Hotels & Resorts in Waikiki  | Starwood Hotels & Resorts | Hawaii   | Honolulu |                     |                     |      | 820           | 0                     | 820                                 | Employment and Training Fund Statewide Grants | Department of Labor & Industrial Relations             | training reimbursement |                                  |           |                |                 | direct from agency; not on web                         | Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available                                    | state          |                     | 0          |                                    | "hotels"                 | 
| First Hawaiian Bank                   | BNP Paribas               | Hawaii   | Hawaii   |                     |                     |      | 740           | 0                     | 740                                 | Employment and Training Fund Statewide Grants | Department of Labor & Industrial Relations             | training reimbursement |                                  |           |                |                 | direct from agency; not on web                         | Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available                                    | state          |                     | 0          |                                    | "financial services"     | 
| Aumakua Holdings Inc.                 |                           | Hawaii   | Maui     |                     |                     | 2007 |               | 0                     | 0                                   | Enterprise Zones                              | Department of Business, Economic Development & Tourism | enterprise zone        |                                  |           |                |                 | http://invest.hawaii.gov/business/ez/ez-annual-reports | Company name from list of firms enrolled in the EZ Partnership Program in CY 2007. The state does not disclose the value of EZ benefits. | state          |                     | 0          |                                    | ""                       | 
| Del Monte Fresh Produce (Hawaii) Inc. | Fresh Del Monte Produce   | Hawaii   |          |                     |                     | 2012 |               | 0                     | 0                                   | Enterprise Zones                              | Department of Business, Economic Development & Tourism | enterprise zone        |                                  |           |                |                 | http://invest.hawaii.gov/business/ez/ez-annual-reports | Company appears on a list of EZ firms as of December 31, 2012. The state does not disclose the value of EZ benefits.                     | state          |                     | 0          |                                    | "food products"          | 
| Associated Producers Corp.            |                           | Hawaii   | Honolulu |                     |                     | 2007 |               | 0                     | 0                                   | Enterprise Zones                              | Department of Business, Economic Development & Tourism | enterprise zone        |                                  |           |                |                 | http://invest.hawaii.gov/business/ez/ez-annual-reports | Company name from list of firms enrolled in the EZ Partnership Program in CY 2007. The state does not disclose the value of EZ benefits. | state          |                     | 0          |                                    | ""                       | 
| Nuuanu Hale                           |                           | Hawaii   | Honolulu |                     |                     |      | 82            | 0                     | 82                                  | Employment and Training Fund Statewide Grants | Department of Labor & Industrial Relations             | training reimbursement |                                  |           |                |                 | direct from agency; not on web                         | Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available                                    | state          |                     | 0          |                                    | ""                       | 
| Designer Built Systems, Inc.          |                           | Hawaii   | Honolulu |                     |                     |      | 573           | 0                     | 573                                 | Employment and Training Fund Statewide Grants | Department of Labor & Industrial Relations             | training reimbursement |                                  |           |                |                 | direct from agency; not on web                         | Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available                                    | state          |                     | 0          |                                    | ""                       | 
| Engineering Concepts Inc              |                           | Hawaii   | Honolulu |                     |                     |      | 1750          | 0                     | 1750                                | Employment and Training Fund Statewide Grants | Department of Labor & Industrial Relations             | training reimbursement |                                  |           |                |                 | direct from agency; not on web                         | Subsidy value is total reimbursement in the period 2007-2011; individual annual amounts not available                                    | state          |                     | 0          |                                    | ""                       | 
| Base 10, Inc dba Oils of Aloha        |                           | Hawaii   |          |                     |                     | 2012 |               | 0                     | 0                                   | Enterprise Zones                              | Department of Business, Economic Development & Tourism | enterprise zone        |                                  |           |                |                 | http://invest.hawaii.gov/business/ez/ez-annual-reports | Company appears on a list of EZ firms as of December 31, 2012. The state does not disclose the value of EZ benefits.                     | state          |                     | 0          |                                    | ""                       | 
```