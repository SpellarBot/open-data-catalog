# Procurement Report for Industrial Development Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-report-for-industrial-development-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/p3p6-xqr5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/p3p6-xqr5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/p3p6-xqr5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | p3p6-xqr5 |
| Name | Procurement Report for Industrial Development Agencies |
| Attribution | Individual Industrial Development Agencies submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | idas, procurement, contracts, public authorities |
| Created | 2014-12-04T18:55:07Z |
| Publication Date | 2016-10-19T22:05:04Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include procurement contracts data.  The dataset consists of procurement contracts data reported by Industrial Development Agencies beginning with fiscal years ending in 2011. Authorities are required to report procurement transactions that have an actual or estimated value of $5,000 or more.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | authority_name                  | Authority Name                  | text          | text          |
| Yes      | time           | fiscal_year_end_date            | Fiscal Year End Date            | calendar_date | calendar_date |
| Yes      | series tag     | procurements                    | Procurements                    | text          | text          |
| Yes      | series tag     | vendor_name                     | Vendor Name                     | text          | text          |
| Yes      | series tag     | vendor_city                     | Vendor City                     | text          | text          |
| Yes      | series tag     | vendor_state                    | Vendor State                    | text          | text          |
| Yes      | series tag     | vendor_postal_code              | Vendor Postal Code              | text          | text          |
| Yes      | series tag     | vendor_province_region          | Vendor Province/Region          | text          | text          |
| Yes      | series tag     | vendor_country                  | Vendor Country                  | text          | text          |
| Yes      | series tag     | procurement_description         | Procurement Description         | text          | text          |
| Yes      | series tag     | type_of_procurement             | Type of Procurement             | text          | text          |
| Yes      | series tag     | award_process                   | Award Process                   | text          | text          |
| No       |                | award_date                      | Award Date                      | calendar_date | calendar_date |
| No       |                | end_date                        | End Date                        | calendar_date | calendar_date |
| Yes      | numeric metric | contract_amount                 | Contract Amount                 | money         | money         |
| Yes      | numeric metric | amount_expended_for_fiscal_year | Amount Expended for Fiscal Year | money         | money         |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = award_date,end_date
```

## Data Commands

```ls
series e:p3p6-xqr5 d:2011-12-31T00:00:00.000Z t:vendor_city=ALBANY t:authority_name="Albany City Industrial Development Agency" t:vendor_state=NY t:vendor_country="United States" t:type_of_procurement="Legal Services" t:award_process="Non Contract Procurement/Purchase Order" t:vendor_postal_code=12207 t:procurement_description="Legal Services" t:vendor_name="City of Albany" m:amount_expended_for_fiscal_year=18000

series e:p3p6-xqr5 d:2011-12-31T00:00:00.000Z t:vendor_city=ALBANY t:authority_name="Albany City Industrial Development Agency" t:vendor_state=NY t:vendor_country="United States" t:type_of_procurement="Other Professional Services" t:award_process="Authority Contract - Non-Competitive Bid" t:vendor_postal_code=12207 t:procurement_description="Professional Services" t:vendor_name="Capitalize Albany Corporation" m:contract_amount=73969.35 m:amount_expended_for_fiscal_year=73969.35

series e:p3p6-xqr5 d:2011-12-31T00:00:00.000Z t:vendor_city=ALBANY t:authority_name="Albany City Industrial Development Agency" t:vendor_state=NY t:vendor_country="United States" t:type_of_procurement="Financial Services" t:award_process="Authority Contract - Non-Competitive Bid" t:vendor_postal_code=12205 t:procurement_description="Auditing Services" t:vendor_name="Teal, Becker, and Chiaramonte CPAs, PC" m:contract_amount=6600 m:amount_expended_for_fiscal_year=6600
```

## Meta Commands

```ls
metric m:contract_amount p:double l:"Contract Amount" d:"Total value of the contract. This field is blank if the contract is open ended, if the award process is either Non Contract Procurement/Purchase Order or State Contract or if the authority didn?t enter any information." t:dataTypeName=money

metric m:amount_expended_for_fiscal_year p:double l:"Amount Expended for Fiscal Year" d:"Amount expended under the contract during fiscal year" t:dataTypeName=money

entity e:p3p6-xqr5 l:"Procurement Report for Industrial Development Agencies" t:attribution="Individual Industrial Development Agencies submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/p3p6-xqr5

property e:p3p6-xqr5 t:meta.view v:id=p3p6-xqr5 v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Procurement Report for Industrial Development Agencies" v:attribution="Individual Industrial Development Agencies submitted to Authorities Budget Office"

property e:p3p6-xqr5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:p3p6-xqr5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:p3p6-xqr5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                            | fiscal_year_end_date | procurements | vendor_name                            | vendor_city | vendor_state | vendor_postal_code | vendor_province_region | vendor_country | procurement_description | type_of_procurement         | award_process                            | award_date          | end_date            | contract_amount | amount_expended_for_fiscal_year | 
| ========================================= | ==================== | ============ | ====================================== | =========== | ============ | ================== | ====================== | ============== | ======================= | =========================== | ======================================== | =================== | =================== | =============== | =============================== | 
| Albany City Industrial Development Agency | 2011-12-31T00:00:00  |              | City of Albany                         | ALBANY      | NY           | 12207              |                        | United States  | Legal Services          | Legal Services              | Non Contract Procurement/Purchase Order  |                     |                     |                 | 18000.00                        | 
| Albany City Industrial Development Agency | 2011-12-31T00:00:00  |              | Capitalize Albany Corporation          | ALBANY      | NY           | 12207              |                        | United States  | Professional Services   | Other Professional Services | Authority Contract - Non-Competitive Bid | 2011-03-17T00:00:00 | 2011-12-31T00:00:00 | 73969.35        | 73969.35                        | 
| Albany City Industrial Development Agency | 2011-12-31T00:00:00  |              | Teal, Becker, and Chiaramonte CPAs, PC | ALBANY      | NY           | 12205              |                        | United States  | Auditing Services       | Financial Services          | Authority Contract - Non-Competitive Bid | 2011-11-17T00:00:00 | 2011-12-31T00:00:00 | 6600.00         | 6600.00                         | 
| Albany City Industrial Development Agency | 2012-12-31T00:00:00  |              | City of Albany                         | ALBANY      | NY           | 12207              |                        | United States  | Legal Services          | Legal Services              | Non Contract Procurement/Purchase Order  |                     |                     |                 | 42000.00                        | 
| Albany City Industrial Development Agency | 2012-12-31T00:00:00  |              | Capitalize Albany Corporation          | ALBANY      | NY           | 12207              |                        | United States  | Professional Services   | Other Professional Services | Authority Contract - Non-Competitive Bid | 2012-03-27T00:00:00 | 2012-12-31T00:00:00 | 250000.00       | 250000.00                       | 
| Albany City Industrial Development Agency | 2012-12-31T00:00:00  |              | Teal, Becker, and Chiaramonte CPAs, PC | ALBANY      | NY           | 12205              |                        | United States  | Auditing Services       | Financial Services          | Authority Contract - Non-Competitive Bid | 2012-11-15T00:00:00 | 2013-03-31T00:00:00 | 7000.00         | 1500.00                         | 
| Albany City Industrial Development Agency | 2013-12-31T00:00:00  |              | City of Albany                         | ALBANY      | NY           | 12207              |                        | United States  | Legal Services          | Legal Services              | Non Contract Procurement/Purchase Order  |                     |                     |                 | 42000.00                        | 
| Albany City Industrial Development Agency | 2013-12-31T00:00:00  |              | Capitalize Albany Corporation          | ALBANY      | NY           | 12207              |                        | United States  | Professional Services   | Other Professional Services | Authority Contract - Non-Competitive Bid | 2013-03-25T00:00:00 | 2013-12-31T00:00:00 | 250000.00       | 250000.00                       | 
| Albany City Industrial Development Agency | 2013-12-31T00:00:00  |              | Teal, Becker, and Chiaramonte CPAs, PC | ALBANY      | NY           | 12205              |                        | United States  | Auditing Services       | Financial Services          | Authority Contract - Non-Competitive Bid | 2013-12-19T00:00:00 | 2014-03-31T00:00:00 | 7000.00         | 0.00                            | 
| Albany City Industrial Development Agency | 2014-12-31T00:00:00  |              | City of Albany                         | ALBANY      | NY           | 12207              |                        | United States  | Legal Services          | Legal Services              | Non Contract Procurement/Purchase Order  |                     |                     |                 | 42000.00                        | 
```