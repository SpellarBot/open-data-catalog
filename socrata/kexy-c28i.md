# Contracts: OUS: Captial Construction Retainer Program: PC Amendments: FY2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-ous-captial-construction-retainer-program-pc-amendments-fy2013-afa9a) |
| Metadata | [Link](https://data.oregon.gov/api/views/kexy-c28i) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kexy-c28i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kexy-c28i/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kexy-c28i |
| Name | Contracts: OUS: Captial Construction Retainer Program: PC Amendments: FY2013 |
| Category | Revenue & Expense |
| Tags | ous capital construction retainer program, pc amendments, pc, amendments, ous, retainer programs |
| Created | 2013-11-21T16:48:45Z |
| Publication Date | 2013-11-21T16:50:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | supplement_number | Supplement Number | text          | text          |
| Yes      | series tag     | project           | Project           | text          | text          |
| Yes      | series tag     | organization      | Organization      | text          | text          |
| Yes      | series tag     | consultant        | Consultant        | text          | text          |
| Yes      | series tag     | mwesb             | MWESB             | text          | text          |
| Yes      | series tag     | self_certified    | Self-Certified    | text          | text          |
| Yes      | series tag     | retainer_period   | Retainer Period   | text          | text          |
| Yes      | time           | issue_date        | Issue Date        | calendar_date | calendar_date |
| Yes      | numeric metric | price             | Price             | number        | number        |
| Yes      | series tag     | amendments        | Amendments        | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kexy-c28i d:2011-02-01T00:00:00.000Z t:retainer_period=2011-2013 t:project="First Year Student Residence Survey" t:amendments="OSU-70-P-11-5-1, OSU-70-P-11-5-2, OSU-70-P-11-5-3" t:organization="Oregon State University" t:consultant="Devco Engineering, Inc." t:supplement_number=OSU-70-P-11-5 t:mwesb=No m:price=11730

series e:kexy-c28i d:2011-02-04T00:00:00.000Z t:retainer_period=2011-2013 t:project="Baker Downtown Center Heating System Replacement" t:amendments="UO-72-P-11-7-1, UO-72-P-11-7-2, UO-72-P-11-7-3, UO-72-P-11-7-4" t:organization="University of Oregon" t:consultant="Evergreen Engineering, Inc." t:supplement_number=UO-72-P-11-7 t:mwesb=No m:price=62879.83

series e:kexy-c28i d:2011-02-24T00:00:00.000Z t:retainer_period=2011-2013 t:project="Neuberger Hall Roof Repair and Restoration" t:amendments="PSU-303-P-11-5-1, PSU-303-P-11-5-2, PSU-303-P-11-5-3" t:organization="Portland State University" t:consultant="Carleton/Hart Architecture, P.C." t:supplement_number=PSU-303-P-11-5 t:mwesb="DBE, MBE" m:price=63574
```

## Meta Commands

```ls
metric m:price p:double l:Price t:dataTypeName=number

entity e:kexy-c28i l:"Contracts: OUS: Captial Construction Retainer Program: PC Amendments: FY2013" t:url=https://data.oregon.gov/api/views/kexy-c28i

property e:kexy-c28i t:meta.view v:id=kexy-c28i v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Captial Construction Retainer Program: PC Amendments: FY2013"

property e:kexy-c28i t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kexy-c28i t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| supplement_number | project                                                          | organization              | consultant                                                                                        | mwesb    | self_certified | retainer_period | issue_date          | price    | amendments                                                                               | 
| ================= | ================================================================ | ========================= | ================================================================================================= | ======== | ============== | =============== | =================== | ======== | ======================================================================================== | 
| OSU-70-P-11-5     | First Year Student Residence Survey                              | Oregon State University   | Devco Engineering, Inc.                                                                           | No       |                | 2011-2013       | 2011-02-01T00:00:00 | 11730.00 | OSU-70-P-11-5-1, OSU-70-P-11-5-2, OSU-70-P-11-5-3                                        | 
| UO-72-P-11-7      | Baker Downtown Center Heating System Replacement                 | University of Oregon      | Evergreen Engineering, Inc.                                                                       | No       |                | 2011-2013       | 2011-02-04T00:00:00 | 62879.83 | UO-72-P-11-7-1, UO-72-P-11-7-2, UO-72-P-11-7-3, UO-72-P-11-7-4                           | 
| PSU-303-P-11-5    | Neuberger Hall Roof Repair and Restoration                       | Portland State University | Carleton/Hart Architecture, P.C.                                                                  | DBE, MBE |                | 2011-2013       | 2011-02-24T00:00:00 | 63574.00 | PSU-303-P-11-5-1, PSU-303-P-11-5-2, PSU-303-P-11-5-3                                     | 
| OSU-357-P-11-12   | OSU NATIVE AMERICAN CULTURAL CENTER COMMISSIONING                | Oregon State University   | PAE Consulting Engineers, Inc.                                                                    | No       |                | 2011-2013       | 2011-03-03T00:00:00 | 21175.00 | OSU-357-P-11-12-1, OSU-357-P-11-12-2                                                     | 
| UO-66-P-11-14     | Miscellaneous Small Campus Projects                              | University of Oregon      | Air Introduction & Regulation of Eugene, Inc. a Subsidiary of Northwest Engineering Service, Inc. | No       |                | 2011-2013       | 2011-03-10T00:00:00 | 50000.00 | UO-66-P-11-14-1                                                                          | 
| UO-200-P-11-18    | Klamath/Willamette 1hr Wall - Phase 1                            | University of Oregon      | Rowell Brokaw Architects, PC                                                                      | No       |                | 2011-2013       | 2011-03-10T00:00:00 | 71656.20 | UO-200-P-11-18-1, UO-200-P-11-18-2, UO-200-P-11-18-3, UO-200-P-11-18-4, UO-200-P-11-18-5 | 
| OSU-199-P-11-29   | AG EDUCATION & FARM SERVICES SHOP STRUCTURAL AND PLUMBING DESIGN | Oregon State University   | CSE Engineering, Inc.                                                                             | No       |                | 2011-2013       | 2011-04-19T00:00:00 | 18460.00 | OSU-199-P-11-29-1                                                                        | 
| OSU-168-P-11-30   | AG EDUCATION & FARM SERVICES SHOP CIVIL ENGINEERING DESIGN       | Oregon State University   | Pillar Consulting Group, Inc.                                                                     | ESB      |                | 2011-2013       | 2011-04-19T00:00:00 | 40565.00 | OSU-168-P-11-30-1, OSU-168-P-11-30-2                                                     | 
| UO-27-P-11-32     | Green Building & LEED Recertification of Existing Buildings      | University of Oregon      | Green Building Services, Inc.                                                                     | No       |                | 2011-2013       | 2011-04-26T00:00:00 | 98696.00 | UO-27-P-11-32-1, UO-27-P-11-32-2, UO-27-P-11-32-3, UO-27-P-11-32-4, UO-27-P-11-32-5      | 
| OSU-209-P-11-38   | Student Experience Center Arborist Services                      | Oregon State University   | Sperry Tree Care Co.                                                                              | No       |                | 2011-2013       | 2011-05-06T00:00:00 | 8666.00  | OSU-209-P-11-38-1                                                                        | 
```