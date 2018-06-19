# Contracts: OUS: Capital Construction Retainer Program: CSR Amendments: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-ous-capital-construction-retainer-program-csr-amendments-fiscal-year-2012-ebc79) |
| Metadata | [Link](https://data.oregon.gov/api/views/cxh8-nhuj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cxh8-nhuj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cxh8-nhuj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cxh8-nhuj |
| Name | Contracts: OUS: Capital Construction Retainer Program: CSR Amendments: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-18T16:59:22Z |
| Publication Date | 2012-12-18T17:00:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | supplement_number   | Supplement Number   | text      | text        |
| Yes      | series tag     | project             | Project             | text      | text        |
| Yes      | series tag     | organization        | Organization        | text      | text        |
| Yes      | series tag     | contractor          | Contractor          | text      | text        |
| Yes      | series tag     | mwesb               | MWESB               | text      | text        |
| Yes      | series tag     | retainer_period     | Retainer Period     | text      | text        |
| Yes      | time           | issue_date          | Issue Date          | text      | text        |
| Yes      | numeric metric | price               | Price               | money     | money       |
| Yes      | series tag     | compensation_method | Compensation Method | text      | text        |
| Yes      | series tag     | amendments          | Amendments          | text      | text        |
```

## Time Field

```ls
Value = issue_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:cxh8-nhuj d:2011-07-01T00:00:00.000Z t:compensation_method=Fixed t:retainer_period=2010-2012 t:project="CORDLEY HALL ROOM 2057 ASBESTOS ABATEMENT" t:amendments=OSU-38-C-10-150-1 t:organization="Oregon State University" t:contractor="W.L. Thomas Environmental, LLC" t:supplement_number=OSU-38-C-10-150 t:mwesb=No m:price=2250

series e:cxh8-nhuj d:2011-07-06T00:00:00.000Z t:compensation_method=Fixed t:retainer_period=2010-2012 t:project="Expansion Joint Old Tunnel by Lawrence Junction" t:amendments=UO-28-C-10-242-1 t:organization="University of Oregon" t:contractor="Oregon Cascade Plumbing and Heating, Inc." t:supplement_number=UO-28-C-10-242 t:mwesb=No m:price=10648

series e:cxh8-nhuj d:2011-07-11T00:00:00.000Z t:compensation_method=Fixed t:retainer_period=2010-2012 t:project="NASH HALL ROOF ASBESTOS ABATEMENT" t:amendments=OSU-113-C-10-156-1 t:organization="Oregon State University" t:contractor="IRS Environmental of Portland Inc" t:supplement_number=OSU-113-C-10-156 t:mwesb=No m:price=31724
```

## Meta Commands

```ls
metric m:price p:double l:Price t:dataTypeName=money

entity e:cxh8-nhuj l:"Contracts: OUS: Capital Construction Retainer Program: CSR Amendments: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/cxh8-nhuj

property e:cxh8-nhuj t:meta.view v:id=cxh8-nhuj v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Capital Construction Retainer Program: CSR Amendments: Fiscal Year 2012"

property e:cxh8-nhuj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cxh8-nhuj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| supplement_number | project                                         | organization              | contractor                                          | mwesb         | retainer_period | issue_date | price     | compensation_method | amendments                                                                                    | 
| ================= | =============================================== | ========================= | =================================================== | ============= | =============== | ========== | ========= | =================== | ============================================================================================= | 
| OSU-38-C-10-150   | CORDLEY HALL ROOM 2057 ASBESTOS ABATEMENT       | Oregon State University   | W.L. Thomas Environmental, LLC                      | No            | 2010-2012       | 7/1/11     | 2250.00   | Fixed               | OSU-38-C-10-150-1                                                                             | 
| UO-28-C-10-242    | Expansion Joint Old Tunnel by Lawrence Junction | University of Oregon      | Oregon Cascade Plumbing and Heating, Inc.           | No            | 2010-2012       | 7/6/11     | 10648.00  | Fixed               | UO-28-C-10-242-1                                                                              | 
| OSU-113-C-10-156  | NASH HALL ROOF ASBESTOS ABATEMENT               | Oregon State University   | IRS Environmental of Portland Inc                   | No            | 2010-2012       | 7/11/11    | 31724.00  | Fixed               | OSU-113-C-10-156-1                                                                            | 
| UO-76-C-10-245    | Condon Hall HVAC Renovations                    | University of Oregon      | Preferred Construction, Inc.                        | ESB           | 2010-2012       | 7/12/11    | 175662.58 | Fixed               | UO-76-C-10-245-1, UO-76-C-10-245-2, UO-76-C-10-245-3                                          | 
| UO-299-C-10-249   | MISCELLANEOUS SMALL CAMPUS PROJECTS             | University of Oregon      | S2 Industrial, Inc.                                 | No            | 2010-2012       | 7/15/11    | 50000.00  | Time and Materials  | UO-299-C-10-249-1                                                                             | 
| PSU-297-C-10-88   | ASRC Room 320 Electrical                        | Portland State University | Morrow-Meadows Corporation dba Cherry City Electric | No            | 2010-2012       | 7/18/11    | 30644.00  | Fixed               | PSU-297-C-10-88-1, PSU-297-C-10-88-2, PSU-297-C-10-88-3                                       | 
| UO-330-C-10-251   | CASL NEW ROOF                                   | University of Oregon      | River Roofing Inc                                   | No            | 2010-2012       | 7/18/11    | 11115.00  | Fixed               | UO-330-C-10-251-1, UO-330-C-10-251-2                                                          | 
| OSU-93-C-10-164   | NASH HALL ROOM 454 ASBESTOS ABATEMENT           | Oregon State University   | Minority Abatement Contractors                      | DBE, MBE, WBE | 2010-2012       | 7/19/11    | 3400.00   | Fixed               | OSU-93-C-10-164-1                                                                             | 
| PSU-349-C-10-89   | Millar Library Learning Grounds                 | Portland State University | Emerick Construction Company                        | No            | 2010-2012       | 7/19/11    | 376587.37 | Fixed               | PSU-349-C-10-89-1, PSU-349-C-10-89-2, PSU-349-C-10-89-3, PSU-349-C-10-89-4, PSU-349-C-10-89-5 | 
| UO-248-C-10-255   | MNCH-Cedar Shake Replacement                    | University of Oregon      | Evergreen Roofing of Oregon                         | No            | 2010-2012       | 7/19/11    | 41678.00  | Fixed               | UO-248-C-10-255-1                                                                             | 
```