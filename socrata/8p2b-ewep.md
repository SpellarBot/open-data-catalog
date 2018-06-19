# Campaign Finance Data - Direct Campaign Expenditure Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-data-direct-campaign-expenditure-dataset) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8p2b-ewep) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8p2b-ewep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8p2b-ewep/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8p2b-ewep |
| Name | Campaign Finance Data - Direct Campaign Expenditure Dataset |
| Created | 2016-10-05T14:23:26Z |
| Publication Date | 2016-10-05T16:41:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | payee                | Payee                | text          | text          |
| Yes      | series tag     | paid_by              | Paid_By              | text          | text          |
| Yes      | time           | payment_date         | Payment_Date         | calendar_date | calendar_date |
| Yes      | numeric metric | payment_amount       | Payment_Amount       | money         | money         |
| Yes      | series tag     | candidate_or_measure | Candidate_Or_Measure | text          | text          |
| Yes      | series tag     | office_held_info     | Office_Held_Info     | text          | text          |
| Yes      | series tag     | office_sought_info   | Office_sought_Info   | text          | text          |
| Yes      | series tag     | correction           | Correction           | text          | text          |
| Yes      | series tag     | view_report          | View_Report          | url           | url           |
| Yes      | series tag     | parent_transaction   | Parent_Transaction   | text          | text          |
| Yes      | series tag     | dce_id               | DCE_ID               | text          | text          |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8p2b-ewep d:2016-09-14T00:00:00.000Z t:paid_by="Austin Forward" t:payee="OfficeMax / Office Depot" t:parent_transaction=R20160922165921-F0001 t:dce_id=R20160922165921-F0001-DCE0001 t:candidate_or_measure="Support City of Austin Prop 1" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=263528" m:payment_amount=60.61

series e:8p2b-ewep d:2016-09-14T00:00:00.000Z t:paid_by="Austin Forward" t:payee="Ortiz, Cruz" t:parent_transaction=R20160922165921-F0002 t:dce_id=R20160922165921-F0002-DCE0002 t:candidate_or_measure="Support City of Austin Prop 1" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=263528" m:payment_amount=6000

series e:8p2b-ewep d:2016-09-14T00:00:00.000Z t:paid_by="Austin Forward" t:payee="Travis County Democratic Party" t:parent_transaction=R20160922165921-F0003 t:dce_id=R20160922165921-F0003-DCE0003 t:candidate_or_measure="Support City of Austin Prop 1" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=263528" m:payment_amount=2500
```

## Meta Commands

```ls
metric m:payment_amount p:double l:Payment_Amount t:dataTypeName=money

entity e:8p2b-ewep l:"Campaign Finance Data - Direct Campaign Expenditure Dataset" t:url=https://data.austintexas.gov/api/views/8p2b-ewep

property e:8p2b-ewep t:meta.view v:id=8p2b-ewep v:averageRating=0 v:name="Campaign Finance Data - Direct Campaign Expenditure Dataset"

property e:8p2b-ewep t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:8p2b-ewep t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| payee                                  | paid_by        | payment_date        | payment_amount | candidate_or_measure          | office_held_info | office_sought_info | correction | view_report                                                            | parent_transaction    | dce_id                        | 
| ====================================== | ============== | =================== | ============== | ============================= | ================ | ================== | ========== | ====================================================================== | ===================== | ============================= | 
| OfficeMax / Office Depot               | Austin Forward | 2016-09-14T00:00:00 | 60.61          | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0001 | R20160922165921-F0001-DCE0001 | 
| Ortiz, Cruz                            | Austin Forward | 2016-09-14T00:00:00 | 6000.00        | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0002 | R20160922165921-F0002-DCE0002 | 
| Travis County Democratic Party         | Austin Forward | 2016-09-14T00:00:00 | 2500.00        | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0003 | R20160922165921-F0003-DCE0003 | 
| New Fortune Chinese Seafood Restaurant | Austin Forward | 2016-09-15T00:00:00 | 2400.99        | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0004 | R20160922165921-F0004-DCE0004 | 
| Time Warner Cable                      | Austin Forward | 2016-09-15T00:00:00 | 313.45         | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0005 | R20160922165921-F0005-DCE0005 | 
| Wick, Jim                              | Austin Forward | 2016-09-15T00:00:00 | 3851.15        | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0006 | R20160922165921-F0006-DCE0006 | 
| Worley Printing                        | Austin Forward | 2016-09-15T00:00:00 | 325.83         | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0007 | R20160922165921-F0007-DCE0007 | 
| McDonald, Patrick                      | Austin Forward | 2016-09-15T00:00:00 | 1750.00        | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0008 | R20160922165921-F0008-DCE0008 | 
| Smith, Christian                       | Austin Forward | 2016-09-15T00:00:00 | 1500.00        | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0009 | R20160922165921-F0009-DCE0009 | 
| Chincanchan, David                     | Austin Forward | 2016-09-15T00:00:00 | 19.00          | Support City of Austin Prop 1 |                  |                    |            | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | R20160922165921-F0010 | R20160922165921-F0010-DCE0010 | 
```