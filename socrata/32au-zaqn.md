# Procurement - Bid Tabulations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-bid-tabulations-3dbd6) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/32au-zaqn) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/32au-zaqn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/32au-zaqn/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 32au-zaqn |
| Name | Procurement - Bid Tabulations |
| Attribution | Office of the Chief Procurement Officer |
| Category | Finance & Administration |
| Tags | procurement, purchase, contract, bid, rfp, rfi, award, bid tab, bid tabs |
| Created | 2016-03-22T18:43:36Z |
| Publication Date | 2017-02-21T04:57:54Z |

## Description

The bid tabulations provided herein are preliminary and are for informational purposes only. The purpose of providing this preliminary information is to improve process transparency. The information contained in the preliminary bid tabulations is subject to change pending math review, analysis of all bids, and review of documentation provided.
Bids: All bids estimated at $25,000 or more are publicly opened and read at the time, date, and place specified in the bid document.
RFP/RFQ/RFI: Responses to RFP/RFQ/RFI are not publicly opened. Names of respondents will be made available based on the names identified on the sealed package and is, therefore, subject to change.

For bid tabulations before June 2016 see https://datacatalog.cookcountyil.gov/d/pn38-yupm

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | bid_opening_date    | Bid Opening Date    | calendar_date | calendar_date |
| Yes      | series tag     | procurement_type    | Procurement Type    | text          | text          |
| Yes      | series tag     | contract_number     | Contract Number     | text          | text          |
| Yes      | series tag     | project_name        | Project Name        | text          | text          |
| Yes      | series tag     | department_name     | Department Name     | text          | text          |
| Yes      | series tag     | procurement_contact | Procurement Contact | text          | text          |
| Yes      | series tag     | no_responses        | No Responses        | checkbox      | checkbox      |
| Yes      | series tag     | company_name        | Company Name        | text          | text          |
| Yes      | series tag     | city                | City                | text          | text          |
| Yes      | series tag     | state               | State               | text          | text          |
| Yes      | numeric metric | bid_amount          | Bid Amount          | money         | money         |
| Yes      | series tag     | notes               | Notes               | text          | text          |
```

## Time Field

```ls
Value = bid_opening_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:32au-zaqn d:2017-02-10T00:00:00.000Z t:project_name="LARGE FORMAT COLOR PLOTTER SCANNER AND COPIER" t:company_name="KIP AMERICA, INC," t:contract_number=1645-15768 t:procurement_contact="DAN GIZZI" t:procurement_type="Bid-Formal > $25K" t:department_name="DEPARTMENT OF FACILITIES MANAGEMENT" t:city=NOVI m:bid_amount=33615

series e:32au-zaqn d:2017-03-03T00:00:00.000Z t:project_name="STEAMFITTER SUPPLIES" t:company_name="JOHNSON PIPE & SUPPLY" t:no_responses=false t:state=IL t:contract_number=1645-15735 t:procurement_contact="DAN GIZZI" t:procurement_type="Bid-Formal > $25K" t:department_name="DEPARTMENT OF FACILITIES MANAGEMENT" t:city=CHICAGO m:bid_amount=1167485.31

series e:32au-zaqn d:2017-03-03T00:00:00.000Z t:project_name="STEAMFITTER SUPPLIES" t:company_name="CHICAGO UNITED INDUSTRIES, LTD." t:no_responses=false t:state=IL t:contract_number=1645-15735 t:procurement_contact="DAN GIZZI" t:procurement_type="Bid-Formal > $25K" t:department_name="DEPARTMENT OF FACILITIES MANAGEMENT" t:city=CHICAGO m:bid_amount=1488045.34
```

## Meta Commands

```ls
metric m:bid_amount p:double l:"Bid Amount" t:dataTypeName=money

entity e:32au-zaqn l:"Procurement - Bid Tabulations" t:attribution="Office of the Chief Procurement Officer" t:url=https://datacatalog.cookcountyil.gov/api/views/32au-zaqn

property e:32au-zaqn t:meta.view v:id=32au-zaqn v:category="Finance & Administration" v:averageRating=0 v:name="Procurement - Bid Tabulations" v:attribution="Office of the Chief Procurement Officer"

property e:32au-zaqn t:meta.view.license v:name="Public Domain"

property e:32au-zaqn t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:32au-zaqn t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| bid_opening_date    | procurement_type       | contract_number | project_name                                                                                                                                  | department_name                      | procurement_contact | no_responses | company_name                    | city        | state | bid_amount | notes | 
| =================== | ====================== | =============== | ============================================================================================================================================= | ==================================== | =================== | ============ | =============================== | =========== | ===== | ========== | ===== | 
| 2017-02-10T00:00:00 | Bid-Formal > $25K      | 1645-15768      | LARGE FORMAT COLOR PLOTTER SCANNER AND COPIER                                                                                                 | DEPARTMENT OF FACILITIES MANAGEMENT  | DAN GIZZI           |              | KIP AMERICA, INC,               | NOVI        |       | 33615.00   |       | 
| 2016-06-01T00:00:00 | Bid-Small Order < $25K | 1545-15174R     | Glass Supplies                                                                                                                                | Dept. of Facilities/Mgmt - 200       | Dan Gizzi           | true         |                                 |             |       |            |       | 
| 2017-03-03T00:00:00 | Bid-Formal > $25K      | 1645-15735      | STEAMFITTER SUPPLIES                                                                                                                          | DEPARTMENT OF FACILITIES MANAGEMENT  | DAN GIZZI           | false        | JOHNSON PIPE & SUPPLY           | CHICAGO     | IL    | 1167485.31 |       | 
| 2016-07-08T00:00:00 | Bid-Formal > $25K      | 1625-15353      | Telecommunication Materials                                                                                                                   | Office of Chief Info. Officer - 009  | Hermine Wise        | true         |                                 |             |       |            |       | 
| 2017-04-05T00:00:00 | RFP/RFQ/RFI            | 1730-16416      | EMPLOYER-SPONSORED VISION CARE BENEFITS                                                                                                       | DEPARTMENT OF RISK MANAGEMENT        | NICOLE LARGE        | false        | METLIFE                         | CHICAGO     | IL    |            |       | 
| 2017-03-01T00:00:00 | RFP/RFQ/RFI            | 1618-15644      | HEALTHCARE FLEXIBLE SPENDING ACCOUNT (HFSA), DEPENDANT CARE FLEXIBLE SPENDING ACCOUNT (DCFSA), HEALTH SAVINGS ACCOUNT (HSA) COMMUTER BENEFITS | DEPARTMENT OF RISK MANAGEMENT        | RICHARD SANCHEZ     | false        | NAVIA BENEFIT SOLUTIONS         | BELLEVUE    | WA    |            |       | 
| 2017-03-03T00:00:00 | Bid-Formal > $25K      | 1645-15735      | STEAMFITTER SUPPLIES                                                                                                                          | DEPARTMENT OF FACILITIES MANAGEMENT  | DAN GIZZI           | false        | CHICAGO UNITED INDUSTRIES, LTD. | CHICAGO     | IL    | 1488045.34 |       | 
| 2017-03-01T00:00:00 | RFP/RFQ/RFI            | 1618-15644      | HEALTHCARE FLEXIBLE SPENDING ACCOUNT (HFSA), DEPENDANT CARE FLEXIBLE SPENDING ACCOUNT (DCFSA), HEALTH SAVINGS ACCOUNT (HSA) COMMUTER BENEFITS | DEPARTMENT OF RISK MANAGEMENT        | RICHARD SANCHEZ     | false        | PNC                             | CHICAGO     | IL    |            |       | 
| 2017-03-01T00:00:00 | RFP/RFQ/RFI            | 1618-15644      | HEALTHCARE FLEXIBLE SPENDING ACCOUNT (HFSA), DEPENDANT CARE FLEXIBLE SPENDING ACCOUNT (DCFSA), HEALTH SAVINGS ACCOUNT (HSA) COMMUTER BENEFITS | DEPARTMENT OF RISK MANAGEMENT        | RICHARD SANCHEZ     | false        | CONNECT YOUR CARE               | HUNT VALLEY | MD    |            |       | 
| 2016-08-03T00:00:00 | Bid-Small Order < $25K | 1626-15617      | Lapel Pins                                                                                                                                    | County Clerk Election Div.Fund - 524 | Monika Sadowski     |              | China Maple Leaf                | Jiangsu     | China | 2999.20    |       | 
```