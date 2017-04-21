# State University Construction Fund (SUCF) Contracts: Beginning 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-contracts-beginning-1995) |
| Metadata | [Link](https://data.ny.gov/api/views/cfjm-ii27) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cfjm-ii27/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cfjm-ii27/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cfjm-ii27 |
| Name | State University Construction Fund (SUCF) Contracts: Beginning 1995 |
| Attribution | State University Construction Fund - IS Department |
| Category | Education |
| Tags | state university construction fund, sucf, construction, contract, education, capital, suny |
| Created | 2014-03-05T22:27:08Z |
| Publication Date | 2017-04-01T10:09:50Z |

## Description

Capital Contracts (Design, Construction and associated services) including expended and encumbrance values.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | project_number      | Project Number      | text          | text          |
| Yes      | series tag     | contract_number     | Contract Number     | text          | text          |
| Yes      | series tag     | title               | Title               | text          | text          |
| Yes      | series tag     | status              | Status              | text          | text          |
| Yes      | series tag     | procurement_type    | Procurement Type    | text          | text          |
| Yes      | series tag     | award_type          | Award Type          | text          | text          |
| Yes      | time           | contract_award_date | Contract Award Date | calendar_date | calendar_date |
| No       |                | contract_end_date   | Contract End Date   | calendar_date | calendar_date |
| Yes      | numeric metric | contract_amount     | Contract Amount     | money         | money         |
| Yes      | numeric metric | expended_amount_ytd | Expended Amount YTD | money         | money         |
| Yes      | numeric metric | expended_amount_ltd | Expended Amount LTD | money         | money         |
| Yes      | numeric metric | remaining_balance   | Remaining Balance   | money         | money         |
| Yes      | numeric metric | number_of_bids      | Number of Bids      | number        | number        |
| Yes      | series tag     | mwbe                | MWBE                | text          | text          |
| Yes      | numeric metric | mwbe_proposals      | MWBE Proposals      | number        | number        |
| Yes      | series tag     | vendor_name         | Vendor Name         | text          | text          |
| No       |                | address_line_1      | Address Line 1      | text          | text          |
| No       |                | address_line_2      | Address Line 2      | text          | text          |
| Yes      | series tag     | city                | City                | text          | text          |
| Yes      | series tag     | state               | State               | text          | text          |
| Yes      | series tag     | zip_code            | Zip Code            | text          | number        |
| Yes      | series tag     | country             | Country             | text          | text          |
```

## Time Field

```ls
Value = contract_award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_end_date,address_line_1,address_line_2
```

## Data Commands

```ls
series e:cfjm-ii27 d:2015-11-13T00:00:00.000Z t:title="DESIGN: Upgrade Central Plant" t:zip_code=10121 t:status=Active t:mwbe=Y t:state=NY t:contract_number=T006185 t:project_number=011006 t:procurement_type="Design and Construction/Maintenance" t:award_type="Authority Contract - Best Value" t:vendor_name="WM Group Engineers, P.C." t:country=USA t:city="New York" m:expended_amount_ltd=362302.68 m:mwbe_proposals=4 m:contract_amount=1914000 m:number_of_bids=19 m:remaining_balance=1551697.32 m:expended_amount_ytd=0

series e:cfjm-ii27 d:2016-07-29T00:00:00.000Z t:title="DESIGN: Upgrade Controls Study/Pilot Campus Wide" t:zip_code=14202 t:status=Active t:mwbe=N t:state=NY t:contract_number=T006260 t:project_number=011009 t:procurement_type="Design and Construction/Maintenance" t:award_type="Authority Contract - Best Value" t:vendor_name="M/E Engineering, P.C." t:country=USA t:city=Buffalo m:expended_amount_ltd=13435.82 m:mwbe_proposals=1 m:contract_amount=261669 m:number_of_bids=7 m:remaining_balance=248233.18 m:expended_amount_ytd=0

series e:cfjm-ii27 d:2007-01-19T00:00:00.000Z t:title="CONSTR: Rehabilitate Husted Hall, Downtown Campus, Building No. 3" t:zip_code=14607 t:status=Closed t:mwbe=N t:state=NY t:contract_number=T005224 t:project_number=01X470 t:procurement_type="Design and Construction/Maintenance" t:award_type="Authority Contract - Competitive Bid" t:vendor_name="The Pike Company Inc" t:country=USA t:city=Rochester m:expended_amount_ltd=15326785 m:mwbe_proposals=0 m:contract_amount=15326785.5 m:number_of_bids=2 m:remaining_balance=0.5 m:expended_amount_ytd=0
```

## Meta Commands

```ls
metric m:contract_amount p:double l:"Contract Amount" d:"Amount of Contract" t:dataTypeName=money

metric m:expended_amount_ytd p:double l:"Expended Amount YTD" d:"Amount Expended for Fiscal Year" t:dataTypeName=money

metric m:expended_amount_ltd p:double l:"Expended Amount LTD" d:"Amount Expended Life to Date" t:dataTypeName=money

metric m:remaining_balance p:double l:"Remaining Balance" d:"Current or Outstanding Balance" t:dataTypeName=money

metric m:number_of_bids p:integer l:"Number of Bids" d:"Number of Vendors that bid on contract" t:dataTypeName=number

metric m:mwbe_proposals p:integer l:"MWBE Proposals" d:"Number of MWBE Firms solicited as part of Procurement Process" t:dataTypeName=number

entity e:cfjm-ii27 l:"State University Construction Fund (SUCF) Contracts: Beginning 1995" t:attribution="State University Construction Fund - IS Department" t:url=https://data.ny.gov/api/views/cfjm-ii27

property e:cfjm-ii27 t:meta.view v:id=cfjm-ii27 v:category=Education v:attributionLink=http://sucf.suny.edu v:averageRating=0 v:name="State University Construction Fund (SUCF) Contracts: Beginning 1995" v:attribution="State University Construction Fund - IS Department"

property e:cfjm-ii27 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cfjm-ii27 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cfjm-ii27 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project_number | contract_number | title                                                             | status       | procurement_type                    | award_type                           | contract_award_date | contract_end_date   | contract_amount | expended_amount_ytd | expended_amount_ltd | remaining_balance | number_of_bids | mwbe | mwbe_proposals | vendor_name                      | address_line_1         | address_line_2          | city      | state | zip_code | country | 
| ============== | =============== | ================================================================= | ============ | =================================== | ==================================== | =================== | =================== | =============== | =================== | =================== | ================= | ============== | ==== | ============== | ================================ | ====================== | ======================= | ========= | ===== | ======== | ======= | 
| 011006         | T006185         | DESIGN: Upgrade Central Plant                                     | Active       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2015-11-13T00:00:00 | 2020-12-10T00:00:00 | 1914000.00      | 0.00                | 362302.68           | 1551697.32        | 19             | Y    | 4              | WM Group Engineers, P.C.         | Two Penn Plaza,        | 380 Seventh Avenue #552 | New York  | NY    | 10121    | USA     | 
| 011009         | T006260         | DESIGN: Upgrade Controls Study/Pilot Campus Wide                  | Active       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2016-07-29T00:00:00 | 2017-09-24T00:00:00 | 261669.00       | 0.00                | 13435.82            | 248233.18         | 7              | N    | 1              | M/E Engineering, P.C.            | Suite 320              | 60 Lakefront Boulevard  | Buffalo   | NY    | 14202    | USA     | 
| 01X470         | T005224         | CONSTR: Rehabilitate Husted Hall, Downtown Campus, Building No. 3 | Closed       | Design and Construction/Maintenance | Authority Contract - Competitive Bid | 2007-01-19T00:00:00 | 2013-01-01T00:00:00 | 15326785.50     | 0.00                | 15326785.00         | 0.50              | 2              | N    | 0              | The Pike Company Inc             | One Circle Street      |                         | Rochester | NY    | 14607    | USA     | 
| 01X844         | T005697         | DESIGN: Facilities Master Plan - Albany                           | Closed       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2010-08-04T00:00:00 | 2012-01-27T00:00:00 | 1614592.67      | 963421.03           | 1614592.67          | 0.00              | 30             | N    | 1              | Perkins & Will Architects P.C.   | 4th Floor              | 215 Park Avenue South   | New York  | NY    | 10003    | USA     | 
| 01X850         | T005855         | DESIGN: Linear Accelerator Upgrades - Study                       | Closed       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2012-06-01T00:00:00 | 2014-08-19T00:00:00 | 142226.27       | 71113.14            | 142226.27           | 0.00              | 0              | N    | 0              | Perkins & Will Architects P.C.   | 4th Floor              | 215 Park Avenue South   | New York  | NY    | 10003    | USA     | 
| 01X854         | T005855         | DESIGN: Classroom Improvement Study                               | Closed       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2012-05-08T00:00:00 | 2014-08-19T00:00:00 | 67290.00        | 37682.26            | 67290.00            | 0.00              | 0              | N    | 0              | Perkins & Will Architects P.C.   | 4th Floor              | 215 Park Avenue South   | New York  | NY    | 10003    | USA     | 
| 01XA40         | T005639         | CONSTR: Install Podium Sky Light Domes, Phase 1                   | Closed       | Design and Construction/Maintenance | Authority Contract - Competitive Bid | 2010-02-05T00:00:00 | 2013-12-30T00:00:00 | 3382292.00      | 253785.00           | 3344037.00          | 38255.00          | 7              | N    | 0              | Sano-Rubin Construction Co, Inc. | P.O. Box 9078          | 624 Delaware Avenue     | Albany    | NY    | 12209    | USA     | 
| 01XA49         | T005474         | DESIGN: Relocate University Data Center                           | Active       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2009-03-20T00:00:00 | 2016-10-15T00:00:00 | 2580444.65      | 483935.72           | 2549252.29          | 31192.36          | 10             | N    | 1              | EYP Mission Critical Facilities  | 3rd Floor              | 54 State Street         | Albany    | NY    | 12207    | USA     | 
| 01XA49         | T005605         | DESIGN: Commissioning - Relocate University Data Center           | Active       | Design and Construction/Maintenance | Authority Contract - Best Value      | 2010-01-21T00:00:00 | 2015-01-10T00:00:00 | 358623.00       | 124408.77           | 325719.70           | 32903.30          | 16             | N    | 0              | Cosentini Associates             | Two Pennsylvania Plaza |                         | New York  | NY    | 10121    | USA     | 
| 01XA51         | T005473         | DESIGN: Construct New Business School                             | In Guarantee | Design and Construction/Maintenance | Authority Contract - Best Value      | 2009-03-17T00:00:00 | 2015-08-15T00:00:00 | 3357091.37      | 405753.40           | 3173761.12          | 183330.25         | 28             | N    | 0              | Perkins & Will Architects P.C.   | 4th Floor              | 215 Park Avenue South   | New York  | NY    | 10003    | USA     | 
```