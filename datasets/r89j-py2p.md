# Fiscal Year 2013 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2013-budget-9d416) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/r89j-py2p) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/r89j-py2p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/r89j-py2p/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | r89j-py2p |
| Name | Fiscal Year 2013 Budget |
| Category | Government |
| Tags | budget, operating budget, county budget, fiscal year |
| Created | 2012-09-11T15:58:40Z |
| Publication Date | 2012-10-05T13:57:17Z |
| Rows Updated | 2012-09-27T15:19:49Z |

## Description

This dataset includes the Fiscal Year* 2013 Council-approved operating budget for Montgomery County.  The dataset does not include revenues and agency budget information; each agency, such as Montgomery County Public Schools, maintain their individual budget information.   The data can be sorted, filtered, and exported by the following elements:  Function (grouping, such as ?Public Safety?), Department, Program, Cost Center (activity within a program), Fund Type , Fund Subtype, Fund Name, Subfund Name, Personnel & Operating Expenses, Object Name, and Account Name.


*The 12-month period to which the annual operating and capital budgets and their respective appropriations apply.  The Montgomery County fiscal year starts on July 1st and ends on June 30th.

Update Frequency:  Annually

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | function                           | Function                             | text      | text        |
| Yes      | series tag     | department                         | Department                           | text      | text        |
| Yes      | series tag     | program_name                       | Program Name                         | text      | text        |
| Yes      | series tag     | cost_center_name                   | Cost Center Name                     | text      | text        |
| Yes      | series tag     | fund_type                          | Fund Type                            | text      | text        |
| Yes      | series tag     | fund_subtype                       | Fund Subtype                         | text      | text        |
| Yes      | series tag     | subfund_name                       | Subfund Name                         | text      | text        |
| Yes      | series tag     | fund_name                          | Fund Name                            | text      | text        |
| Yes      | series tag     | personnel_costs_operating_expenses | Personnel Costs & Operating Expenses | text      | text        |
| Yes      | series tag     | object_name                        | Object Name                          | text      | text        |
| Yes      | series tag     | account_name                       | Account Name                         | text      | text        |
| Yes      | numeric metric | amount                             | Amount                               | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r89j-py2p d:2012-09-11T08:58:47.000Z t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:personnel_costs_operating_expenses="Personnel Costs" t:cost_center_name=ACS t:subfund_name="General Fund" t:department="Correction and Rehabilitation" t:program_name="Pre-Trial Services" t:object_name=Retirement t:fund_subtype="General Fund" t:function="Public Safety" t:account_name=RSP m:amount=4295

series e:r89j-py2p d:2012-09-11T08:58:47.000Z t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:personnel_costs_operating_expenses="Personnel Costs" t:cost_center_name="5th District S.A.T" t:subfund_name="General Fund" t:department=Police t:program_name="Field Services" t:object_name=Retirement t:fund_subtype="General Fund" t:function="Public Safety" t:account_name=ERS m:amount=193146

series e:r89j-py2p d:2012-09-11T08:58:47.000Z t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:personnel_costs_operating_expenses="Personnel Costs" t:cost_center_name="C.I.D-Auto Theft" t:subfund_name="General Fund" t:department=Police t:program_name="Investigative Services" t:object_name=Retirement t:fund_subtype="General Fund" t:function="Public Safety" t:account_name=ERS m:amount=229661
```

## Meta Commands

```ls
entity e:r89j-py2p l:"Fiscal Year 2013 Budget" t:url=https://data.montgomerycountymd.gov/api/views/r89j-py2p

property e:r89j-py2p t:meta.view d:2017-03-10T16:21:10.962Z v:id=r89j-py2p v:category=Government v:averageRating=0 v:name="Fiscal Year 2013 Budget"

property e:r89j-py2p t:meta.view.owner d:2017-03-10T16:21:10.962Z v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"

property e:r89j-py2p t:meta.view.tableauthor d:2017-03-10T16:21:10.962Z v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"
```