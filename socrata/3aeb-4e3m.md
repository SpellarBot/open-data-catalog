# ESD Contracts 2016 - Composite Dataset - V1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esd-contracts-2016-composite-dataset-v1) |
| Metadata | [Link](https://data.oregon.gov/api/views/3aeb-4e3m) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3aeb-4e3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3aeb-4e3m/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3aeb-4e3m |
| Name | ESD Contracts 2016 - Composite Dataset - V1 |
| Category | Revenue & Expense |
| Tags | 2016; contracts; esd, fiscal year 2016, esd contracts, education service districts |
| Created | 2017-01-02T00:56:18Z |
| Publication Date | 2017-01-02T06:47:24Z |

## Description

This is a composite listing of contract data from all ESD's per SB250 for Fiscal Year 2016. For more information go to: http://www.oregon.gov/transparency/Pages/ESDTransparency.aspx

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | time           | fiscal_year                                   | FISCAL YEAR                                   | number    | number      |
| Yes      | series tag     | esd_id                                        | ESD ID                                        | text      | number      |
| Yes      | series tag     | esd_name                                      | ESD Name                                      | text      | text        |
| Yes      | series tag     | award_number_w_amendments                     | Award Number w/Amendments                     | text      | text        |
| Yes      | series tag     | award_title                                   | Award Title                                   | text      | text        |
| Yes      | series tag     | award_type                                    | Award Type                                    | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract                  | Type of Contract/Subcontract                  | text      | text        |
| Yes      | series tag     | contractor_s_name                             | Contractor's Name                             | text      | text        |
| Yes      | series tag     | contractor_street_address                     | Contractor_Street Address                     | text      | text        |
| Yes      | series tag     | contractor_city                               | Contractor_ City                              | text      | text        |
| Yes      | series tag     | contractor_state                              | Contractor_State                              | text      | text        |
| Yes      | series tag     | contractor_zip                                | Contractor_Zip                                | text      | text        |
| No       |                | original_start_amendment_date_expiration_date | Original Start/Amendment Date/Expiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                          | Original Award Value                          | money     | money       |
| Yes      | numeric metric | amendment_value                               | Amendment Value                               | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments                | Total Award Value w/Amendments                | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = original_start_amendment_date_expiration_date
```

## Data Commands

```ls
series e:3aeb-4e3m d:2016-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:contractor_s_name="Northwest Surveying, Inc" t:esd_id=1902 t:award_number_w_amendments=160699 t:contractor_state=OR t:type_of_contract_subcontract=Professional t:contractor_city=Beaverton t:award_type="Personal Services" t:award_title="Auxiliary Services" t:contractor_zip=97006 t:contractor_street_address="1815 NW 169th Place, Suite 2090" m:amendment_value=0 m:total_award_value_w_amendments=13900 m:original_award_value=13900

series e:3aeb-4e3m d:2016-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:contractor_s_name="Sunrise Water Authority" t:esd_id=1902 t:award_number_w_amendments=160029 t:contractor_state=OR t:type_of_contract_subcontract=Professional t:contractor_city="Happy Valley" t:award_type="Trade Services" t:award_title="Auxiliary Services" t:contractor_zip=97086-6218 t:contractor_street_address="10602 SE 129th Ave" m:amendment_value=-159.8 m:total_award_value_w_amendments=6159.8 m:original_award_value=6000

series e:3aeb-4e3m d:2016-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:contractor_s_name="Neopost USA Inc. d/b/a Hasler" t:esd_id=1902 t:award_number_w_amendments=160020 t:contractor_state=CT t:type_of_contract_subcontract=Material t:contractor_city=Milford t:award_type="Work Order" t:award_title="Auxiliary Services" t:contractor_zip=06461-9105 t:contractor_street_address="478 Wheelers Farms Rd." m:amendment_value=385.42 m:total_award_value_w_amendments=438.46 m:original_award_value=823.88
```

## Meta Commands

```ls
metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:3aeb-4e3m l:"ESD Contracts 2016 - Composite Dataset - V1" t:url=https://data.oregon.gov/api/views/3aeb-4e3m

property e:3aeb-4e3m t:meta.view v:id=3aeb-4e3m v:category="Revenue & Expense" v:averageRating=0 v:name="ESD Contracts 2016 - Composite Dataset - V1"

property e:3aeb-4e3m t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:3aeb-4e3m t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | esd_id | esd_name      | award_number_w_amendments | award_title        | award_type        | type_of_contract_subcontract | contractor_s_name             | contractor_street_address       | contractor_city | contractor_state | contractor_zip | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| =========== | ====== | ============= | ========================= | ================== | ================= | ============================ | ============================= | =============================== | =============== | ================ | ============== | ============================================= | ==================== | =============== | ============================== | 
| 2016        | 1902   | Clackamas ESD | 160699                    | Auxiliary Services | Personal Services | Professional                 | Northwest Surveying, Inc      | 1815 NW 169th Place, Suite 2090 | Beaverton       | OR               | 97006          | 2/11/2016                                     | 13900.00             | 0.00            | 13900.00                       | 
| 2016        | 1902   | Clackamas ESD | 160029                    | Auxiliary Services | Trade Services    | Professional                 | Sunrise Water Authority       | 10602 SE 129th Ave              | Happy Valley    | OR               | 97086-6218     | 7/14/2015                                     | 6000.00              | -159.80         | 6159.80                        | 
| 2016        | 1902   | Clackamas ESD | 160020                    | Auxiliary Services | Work Order        | Material                     | Neopost USA Inc. d/b/a Hasler | 478 Wheelers Farms Rd.          | Milford         | CT               | 06461-9105     | 7/14/2015                                     | 823.88               | 385.42          | 438.46                         | 
| 2016        | 1902   | Clackamas ESD | 160019                    | Auxiliary Services | Work Order        | Material                     | Neopost USA Inc. d/b/a Hasler | 478 Wheelers Farms Rd.          | Milford         | CT               | 06461-9105     | 7/14/2015                                     | 357.78               | 0.00            | 357.78                         | 
| 2016        | 1902   | Clackamas ESD | 160005                    | Auxiliary Services | Trade Services    | Professional                 | KONE INC.                     | One Kone Court                  | Moline          | IL               | 61625          | 6/25/2015                                     | 1766.25              | -18.18          | 1784.43                        | 
| 2016        | 1902   | Clackamas ESD | 160003                    | Auxiliary Services | Trade Services    | Professional                 | American Security Alarms Co.  | 5411 S.E. Mc Loughlin Blvd.     | Portland        | OR               | 97202          | 6/25/2015                                     | 693.80               | 0.00            | 693.80                         | 
| 2016        | 1902   | Clackamas ESD | 160026                    | Auxiliary Services | Trade Services    | Professional                 | Securitas Security Services   | 103 SW 4th Ave.                 | Portland        | OR               | 97204-1840     | 7/14/2015                                     | 3744.40              | 60.72           | 3683.68                        | 
| 2016        | 1902   | Clackamas ESD | 160033                    | Auxiliary Services | Trade Services    | Professional                 | Waste Management Of Oregon    | 7227 NE 55th Ave.               | Portland        | OR               | 97218-1215     | 7/14/2015                                     | 6892.76              | 200.00          | 6692.76                        | 
| 2016        | 1902   | Clackamas ESD | 160016                    | Auxiliary Services | Trade Services    | Professional                 | Water Environment Services    | PO Box 6940                     | Portland        | OR               | 97228          | 7/14/2015                                     | 6342.00              | -162.00         | 6504.00                        | 
| 2016        | 1902   | Clackamas ESD | 160025                    | Auxiliary Services | Trade Services    | Professional                 | Portland General Electric     | PO Box 4438                     | Portland        | OR               | 97208-4438     | 7/14/2015                                     | 67500.00             | 2671.38         | 64828.62                       | 
```