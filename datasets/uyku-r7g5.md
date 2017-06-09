# Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-ous-capital-construction-retainer-program-csr-supplements-fiscal-year-2012-05ea1) |
| Metadata | [Link](https://data.oregon.gov/api/views/uyku-r7g5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/uyku-r7g5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/uyku-r7g5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | uyku-r7g5 |
| Name | Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-18T17:02:49Z |
| Publication Date | 2012-12-18T17:03:30Z |

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
```

## Time Field

```ls
Value = issue_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:uyku-r7g5 d:2011-07-01T00:00:00.000Z t:compensation_method=Fixed t:retainer_period="June 2011 - June 2012" t:project="CARSON HALL PLASTER REPAIR PROJECT" t:organization="University of Oregon" t:contractor="Oregon Ceiling & Acoustics, LLC" t:supplement_number=UO-390-C-11-5 t:mwesb="MBE, ESB" m:price=46200

series e:uyku-r7g5 d:2011-07-05T00:00:00.000Z t:compensation_method=Fixed t:retainer_period="June 2011 - June 2012" t:project="Heritage Hall Door Replacement" t:organization="Western Oregon University" t:contractor="Robert Gray Partners, Inc." t:supplement_number=WOU-409-C-11-2 t:mwesb=No m:price=54828

series e:uyku-r7g5 d:2011-07-05T00:00:00.000Z t:compensation_method=Fixed t:retainer_period=2010-2012 t:project="Residence Hall Infrastructure Upgrade" t:organization="Oregon State University" t:contractor="Jimco Electrical Contracting, Inc." t:supplement_number=OSU-16-C-10-151 t:mwesb=No m:price=207750
```

## Meta Commands

```ls
metric m:price p:integer l:Price t:dataTypeName=money

entity e:uyku-r7g5 l:"Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/uyku-r7g5

property e:uyku-r7g5 t:meta.view d:2017-06-09T13:51:05.383Z v:id=uyku-r7g5 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012"

property e:uyku-r7g5 t:meta.view.owner d:2017-06-09T13:51:05.383Z v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1495038840 v:displayName="Paula N."

property e:uyku-r7g5 t:meta.view.tableauthor d:2017-06-09T13:51:05.383Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1495038840 v:displayName="Paula N."
```

## Top Records

```ls
| supplement_number | project                                           | organization              | contractor                                    | mwesb    | retainer_period       | issue_date | price  | compensation_method | 
| ================= | ================================================= | ========================= | ============================================= | ======== | ===================== | ========== | ====== | =================== | 
| UO-390-C-11-5     | CARSON HALL PLASTER REPAIR PROJECT                | University of Oregon      | Oregon Ceiling & Acoustics, LLC               | MBE, ESB | June 2011 - June 2012 | 7/1/11     | 46200  | Fixed               | 
| WOU-409-C-11-2    | Heritage Hall Door Replacement                    | Western Oregon University | Robert Gray Partners, Inc.                    | No       | June 2011 - June 2012 | 7/5/11     | 54828  | Fixed               | 
| OSU-16-C-10-151   | Residence Hall Infrastructure Upgrade             | Oregon State University   | Jimco Electrical Contracting, Inc.            | No       | 2010-2012             | 7/5/11     | 207750 | Fixed               | 
| OSU-157-C-10-152  | LSC Smoke Detector Install                        | Oregon State University   | Simplex Grinnell LP                           | No       | 2010-2012             | 7/5/11     | 40212  | Fixed               | 
| OSU-63-C-10-153   | Gill Coliseum Outer Stairwells Remodel            | Oregon State University   | Fortis Construction Inc.                      | No       | 2010-2012             | 7/6/11     | 229806 | Fixed               | 
| UO-76-C-10-240    | Lawrence Hall Computer Office Remodel             | University of Oregon      | Preferred Construction, Inc.                  | ESB      | 2010-2012             | 7/6/11     | 7107   | Fixed               | 
| UO-139-C-10-241   | Painting of Grad Village Exterior Siding and Trim | University of Oregon      | RW Strand, Inc. dba Carlson & Strand Painting | No       | 2010-2012             | 7/6/11     | 54889  | Fixed               | 
| WOU-38-C-10-33    | Natural Science 201 ACM Removal                   | Western Oregon University | W.L. Thomas Environmental, LLC                | No       | 2010-2012             | 7/6/11     | 2690   | Fixed               | 
| WOU-211-C-10-34   | ITC 013S HVAC Ductwork, Controls Addition         | Western Oregon University | Robert Lloyd Sheet Metal Inc.                 | No       | 2010-2012             | 7/6/11     | 4840   | Fixed               | 
| OSU-232-C-10-154  | Finley Hall Sidewalk Elevator                     | Oregon State University   | Lease Crutcher Lewis, LLC                     | No       | 2010-2012             | 7/7/11     | 137800 | Fixed               | 
```