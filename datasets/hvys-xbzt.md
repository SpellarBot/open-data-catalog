# Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-ous-captial-construction-retainer-program-crs-supplements-fy2013-aa4c2) |
| Metadata | [Link](https://data.oregon.gov/api/views/hvys-xbzt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hvys-xbzt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hvys-xbzt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hvys-xbzt |
| Name | Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013 |
| Category | Revenue & Expense |
| Tags | ous capital construction retainer program, crs supplements, capital construction retainer program |
| Created | 2013-11-21T16:44:01Z |
| Publication Date | 2013-11-21T16:45:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | supplement_number   | Supplement Number   | text          | text          |
| Yes      | series tag     | project             | Project             | text          | text          |
| Yes      | series tag     | organization        | Organization        | text          | text          |
| Yes      | series tag     | contractor          | Contractor          | text          | text          |
| Yes      | series tag     | mwesb               | MWESB               | text          | text          |
| Yes      | series tag     | retainer_period     | Retainer Period     | text          | text          |
| Yes      | time           | issue_date          | Issue Date          | calendar_date | calendar_date |
| Yes      | numeric metric | price               | Price               | number        | number        |
| Yes      | series tag     | compensation_method | Compensation Method | text          | text          |
| Yes      | series tag     | amendments          | Amendments          | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hvys-xbzt d:2012-07-02T00:00:00.000Z t:compensation_method="Time and Materials" t:retainer_period="July 2012 - June 2014" t:project="Miscellaneous Small Campus Projects" t:organization="University of Oregon" t:contractor="Stedman Sheet Metal, Inc." t:supplement_number=UO-636-C-12-1 t:mwesb=No m:price=50000

series e:hvys-xbzt d:2012-07-05T00:00:00.000Z t:compensation_method=Fixed t:retainer_period="July 2012 - June 2014" t:project="Magruder Hall Chiller Replacement" t:organization="Oregon State University" t:contractor="Hammerquist, Inc." t:supplement_number=OSU-131-C-12-1 t:mwesb=No m:price=56801

series e:hvys-xbzt d:2012-07-06T00:00:00.000Z t:compensation_method="Time and Materials" t:retainer_period="July 2012 - June 2014" t:project="Miscellaneous Small Campus Projects" t:organization="University of Oregon" t:contractor="Office World, Inc." t:supplement_number=UO-574-C-12-2 t:mwesb=No m:price=50000
```

## Meta Commands

```ls
metric m:price p:double l:Price t:dataTypeName=number

entity e:hvys-xbzt l:"Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013" t:url=https://data.oregon.gov/api/views/hvys-xbzt

property e:hvys-xbzt t:meta.view d:2017-06-09T13:58:43.889Z v:id=hvys-xbzt v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013"

property e:hvys-xbzt t:meta.view.owner d:2017-06-09T13:58:43.889Z v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1495038840 v:displayName="Paula N."

property e:hvys-xbzt t:meta.view.tableauthor d:2017-06-09T13:58:43.889Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1495038840 v:displayName="Paula N."
```

## Top Records

```ls
| supplement_number | project                                              | organization               | contractor                                | mwesb | retainer_period       | issue_date          | price    | compensation_method | amendments      | 
| ================= | ==================================================== | ========================== | ========================================= | ===== | ===================== | =================== | ======== | =================== | =============== | 
| UO-636-C-12-1     | Miscellaneous Small Campus Projects                  | University of Oregon       | Stedman Sheet Metal, Inc.                 | No    | July 2012 - June 2014 | 2012-07-02T00:00:00 | 50000.00 | Time and Materials  |                 | 
| OSU-131-C-12-1    | Magruder Hall Chiller Replacement                    | Oregon State University    | Hammerquist, Inc.                         | No    | July 2012 - June 2014 | 2012-07-05T00:00:00 | 56801.00 | Fixed               |                 | 
| UO-574-C-12-2     | Miscellaneous Small Campus Projects                  | University of Oregon       | Office World, Inc.                        | No    | July 2012 - June 2014 | 2012-07-06T00:00:00 | 50000.00 | Time and Materials  |                 | 
| WOU-28-C-12-1     | Barnum Hall Re-Pipe                                  | Western Oregon University  | Oregon Cascade Plumbing and Heating, Inc. | No    | July 2012 - June 2014 | 2012-07-09T00:00:00 | 1700.00  | Fixed               |                 | 
| WOU-211-C-12-2    | Barnum Hall Exhaust Fan Replacement and Cleaning     | Western Oregon University  | Robert Lloyd Sheet Metal Inc.             | No    | July 2012 - June 2014 | 2012-07-09T00:00:00 | 6600.00  | Fixed               |                 | 
| WOU-31-C-12-3     | Physical Plant Compactor Slab-Driveway               | Western Oregon University  | Greg Aldrich Construction Co, Inc         | No    | July 2012 - June 2014 | 2012-07-09T00:00:00 | 8000.00  | Fixed               | WOU-31-C-12-3-1 | 
| PCC-710-C-12-1    | Kitchen Flooring - Sylvania Campus                   | Portland Community College | Floor Factors Inc.                        | No    | July 2012 - June 2014 | 2012-07-11T00:00:00 | 85894.00 | Time and Materials  |                 | 
| OSU-224-C-12-2    | LANGTON / MORELAND HALL TUNNEL ABATEMENT AND CLEANUP | Oregon State University    | Pacific Environmental Group, Inc.         | ESB   | July 2012 - June 2014 | 2012-07-11T00:00:00 | 5990.00  | Fixed               |                 | 
| OSU-224-C-12-3    | WENIGER 379 ABATEMENT                                | Oregon State University    | Pacific Environmental Group, Inc.         | ESB   | July 2012 - June 2014 | 2012-07-11T00:00:00 | 2560.00  | Fixed               |                 | 
| OSU-224-C-12-4    | CORDLEY RM. 3030 ABATEMENT                           | Oregon State University    | Pacific Environmental Group, Inc.         | ESB   | July 2012 - June 2014 | 2012-07-11T00:00:00 | 2560.00  | Fixed               |                 | 
```