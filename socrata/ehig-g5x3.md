# Procurement Report for State Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-report-for-state-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/ehig-g5x3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ehig-g5x3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ehig-g5x3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ehig-g5x3 |
| Name | Procurement Report for State Authorities |
| Attribution | Individual State Authorities submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | state authorities, procurement, contracts |
| Created | 2014-12-05T16:38:43Z |
| Publication Date | 2016-10-17T15:28:19Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include procurement contracts data.  The dataset consists of procurement contracts data reported by State Authorities beginning with fiscal years ending in 2011. Authorities are required to report procurement transactions that have an actual or estimated value of $5,000 or more.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | authority_name                       | Authority Name                       | text          | text          |
| Yes      | time           | fiscal_year_end_date                 | Fiscal Year End Date                 | calendar_date | calendar_date |
| Yes      | series tag     | procurements                         | Procurements                         | text          | text          |
| Yes      | series tag     | vendor_name                          | Vendor Name                          | text          | text          |
| Yes      | series tag     | vendor_city                          | Vendor City                          | text          | text          |
| Yes      | series tag     | vendor_state                         | Vendor State                         | text          | text          |
| Yes      | series tag     | vendor_postal_code                   | Vendor Postal Code                   | text          | text          |
| Yes      | series tag     | vendor_province_region               | Vendor Province/Region               | text          | text          |
| Yes      | series tag     | vendor_country                       | Vendor Country                       | text          | text          |
| Yes      | series tag     | procurement_description              | Procurement Description              | text          | text          |
| Yes      | series tag     | type_of_procurement                  | Type of Procurement                  | text          | text          |
| Yes      | series tag     | award_process                        | Award Process                        | text          | text          |
| Yes      | numeric metric | number_of_bids_or_proposals_received | Number of Bids or Proposals Received | number        | number        |
| Yes      | series tag     | vendor_is_a_mwbe                     | Vendor is a MWBE                     | text          | text          |
| Yes      | series tag     | solicited_mwbe                       | Solicited MWBE                       | text          | text          |
| Yes      | numeric metric | number_of_mwbe_proposals             | Number of MWBE Proposals             | number        | number        |
| No       |                | award_date                           | Award Date                           | calendar_date | calendar_date |
| No       |                | begin_date                           | Begin Date                           | calendar_date | calendar_date |
| No       |                | end_date                             | End Date                             | calendar_date | calendar_date |
| Yes      | numeric metric | contract_amount                      | Contract Amount                      | money         | money         |
| Yes      | numeric metric | amount_expended_for_fiscal_year      | Amount Expended for Fiscal Year      | money         | money         |
| No       |                | amount_expended_to_date              | Amount Expended to Date              | text          | money         |
| Yes      | numeric metric | current_or_outstanding_balance       | Current or Outstanding Balance       | money         | money         |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = award_date,begin_date,end_date,amount_expended_to_date
```

## Data Commands

```ls
series e:ehig-g5x3 d:2011-12-31T00:00:00.000Z t:vendor_city=COLUMBUS t:authority_name="Agriculture and New York State Horse Breeding Development Fund" t:vendor_state=OH t:vendor_country="United States" t:type_of_procurement="Consulting Services" t:award_process="Non Contract Procurement/Purchase Order" t:vendor_is_a_mwbe=N t:vendor_postal_code=43220 t:procurement_description=consulting t:vendor_name="Hoffman Communications LLC" m:amount_expended_for_fiscal_year=8026.85

series e:ehig-g5x3 d:2011-12-31T00:00:00.000Z t:vendor_city=SCHENECTADY t:authority_name="Agriculture and New York State Horse Breeding Development Fund" t:vendor_state=NY t:vendor_country="United States" t:type_of_procurement="Technology - Software" t:award_process="Authority Contract - Competitive Bid" t:vendor_is_a_mwbe=N t:vendor_postal_code=12309 t:solicited_mwbe=Y t:procurement_description="Website design & maintenance" t:vendor_name="3GS, Inc." m:current_or_outstanding_balance=29634 m:number_of_bids_or_proposals_received=3 m:contract_amount=49999 m:amount_expended_for_fiscal_year=565 m:number_of_mwbe_proposals=0

series e:ehig-g5x3 d:2011-12-31T00:00:00.000Z t:vendor_city="TINTON FALLS" t:authority_name="Agriculture and New York State Horse Breeding Development Fund" t:vendor_state=NJ t:vendor_country="United States" t:type_of_procurement=Commodities/Supplies t:award_process="Authority Contract - Competitive Bid" t:vendor_is_a_mwbe=N t:vendor_postal_code=7724 t:solicited_mwbe=Y t:procurement_description="Awards  horse blankets" t:vendor_name="Curvon Corporation" m:current_or_outstanding_balance=0 m:number_of_bids_or_proposals_received=3 m:contract_amount=23293.41 m:amount_expended_for_fiscal_year=20566.11 m:number_of_mwbe_proposals=0
```

## Meta Commands

```ls
metric m:number_of_bids_or_proposals_received p:integer l:"Number of Bids or Proposals Received" d:"Number of bids or proposals received prior to award of contract. This field is blank if the authority didn?t enter any information. Specific details for any procurement transaction would need to be clarified by the reporting authority." t:dataTypeName=number

metric m:number_of_mwbe_proposals p:integer l:"Number of MWBE Proposals" d:"Indicates the number of bids or proposals received from MWBE firms. This field may be blank if the award process is either Non Contract Procurement/Purchase Order or State Contract or if the authority didn?t enter any information." t:dataTypeName=number

metric m:contract_amount p:double l:"Contract Amount" d:"Total value of the contract. This field is blank if the contract is open ended, if the award process is either Non Contract Procurement/Purchase Order or State Contract or if the authority didn?t enter any information." t:dataTypeName=money

metric m:amount_expended_for_fiscal_year p:double l:"Amount Expended for Fiscal Year" d:"Amount expended under the contract during fiscal year" t:dataTypeName=money

metric m:current_or_outstanding_balance p:double l:"Current or Outstanding Balance" d:"Amount from contract remaining to be expended. Current balance is negative when the amount expended to date exceeds the original contract amount. This field is blank if the authority didn?t enter any information. Specific details for any procurement transaction would need to be clarified by the reporting authority." t:dataTypeName=money

entity e:ehig-g5x3 l:"Procurement Report for State Authorities" t:attribution="Individual State Authorities submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/ehig-g5x3

property e:ehig-g5x3 t:meta.view v:id=ehig-g5x3 v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Procurement Report for State Authorities" v:attribution="Individual State Authorities submitted to Authorities Budget Office"

property e:ehig-g5x3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ehig-g5x3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ehig-g5x3 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                                 | fiscal_year_end_date | procurements | vendor_name                         | vendor_city      | vendor_state | vendor_postal_code | vendor_province_region | vendor_country | procurement_description      | type_of_procurement   | award_process                            | number_of_bids_or_proposals_received | vendor_is_a_mwbe | solicited_mwbe | number_of_mwbe_proposals | award_date          | begin_date          | end_date            | contract_amount | amount_expended_for_fiscal_year | amount_expended_to_date | current_or_outstanding_balance | 
| ============================================================== | ==================== | ============ | =================================== | ================ | ============ | ================== | ====================== | ============== | ============================ | ===================== | ======================================== | ==================================== | ================ | ============== | ======================== | =================== | =================== | =================== | =============== | =============================== | ======================= | ============================== | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Hoffman Communications LLC          | COLUMBUS         | OH           | 43220              |                        | United States  | consulting                   | Consulting Services   | Non Contract Procurement/Purchase Order  |                                      | N                |                |                          |                     |                     |                     |                 | 8026.85                         |                         |                                | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | 3GS, Inc.                           | SCHENECTADY      | NY           | 12309              |                        | United States  | Website design & maintenance | Technology - Software | Authority Contract - Competitive Bid     | 3                                    | N                | Y              | 0                        | 2008-04-21T00:00:00 | 2008-04-21T00:00:00 |                     | 49999.00        | 565.00                          | 20365.00                | 29634.00                       | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Curvon Corporation                  | TINTON FALLS     | NJ           | 7724               |                        | United States  | Awards horse blankets        | Commodities/Supplies  | Authority Contract - Competitive Bid     | 3                                    | N                | Y              | 0                        | 2011-04-19T00:00:00 | 2011-04-19T00:00:00 |                     | 23293.41        | 20566.11                        | 20566.11                | 0.00                           | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | imPress Printing and Graphics, Inc. | ALBANY           | NY           | 12206              |                        | United States  | Promotional items            | Commodities/Supplies  | Non Contract Procurement/Purchase Order  |                                      | Y                |                |                          |                     |                     |                     |                 | 6561.82                         |                         |                                | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Harness Horse Breeders of NYS, Inc. | LATHAM           | NY           | 12110              |                        | United States  | Consulting services          | Consulting Services   | Authority Contract - Non-Competitive Bid | 1                                    | N                | N              |                          | 2010-10-28T00:00:00 | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | 142500.00       | 141309.33                       | 141309.33               | 141309.33                      | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Saratoga Casino and Raceway         | SARATOGA SPRINGS | NY           | 12866              |                        | United States  | Night of Champions promotion | Other                 | Non Contract Procurement/Purchase Order  |                                      | N                |                |                          |                     |                     |                     |                 | 30396.32                        |                         |                                | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Ellen Miller's Accounting Service   | ALBANY           | NY           | 12203              |                        | United States  | Accounting Services          | Financial Services    | Authority Contract - Competitive Bid     | 3                                    | Y                | Y              | 1                        | 2011-08-30T00:00:00 | 2011-08-31T00:00:00 |                     | 199999.00       | 21312.43                        | 21312.43                | 178686.57                      | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Harmony Mills South LLC             | ALBANY           | NY           | 12207              |                        | United States  | Office Rental                | Other                 | Authority Contract - Non-Competitive Bid | 1                                    | N                | N              |                          | 2009-02-01T00:00:00 | 2009-02-01T00:00:00 | 2014-01-31T00:00:00 | 93000.00        | 18597.52                        | 44497.93                | 48502.07                       | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Peter Goold                         | CASTLETON        | NY           | 12033              |                        | United States  | Transtion Staffing           | Staffing Services     | Non Contract Procurement/Purchase Order  |                                      | N                |                |                          |                     |                     |                     |                 | 15000.00                        |                         |                                | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  |              | Paul Miller                         | ALBANY           | NY           | 12203              |                        | United States  | Transition Staffing          | Financial Services    | Non Contract Procurement/Purchase Order  |                                      | N                |                |                          |                     |                     |                     |                 | 14995.50                        |                         |                                | 
```