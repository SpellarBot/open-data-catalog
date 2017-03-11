# Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/uyku-r7g5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/contracts-ous-capital-construction-retainer-program-csr-supplements-fiscal-year-2012-05ea1)
* [Metadata URL](https://data.oregon.gov/api/views/uyku-r7g5)
* Id = uyku-r7g5
* Name = Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012
* Category = Revenue & Expense
* Created = 2012-12-18T17:02:49Z
* Publication Date = 2012-12-18T17:03:30Z
* Rows Updated = 2012-12-18T17:02:53Z

## Description



## Columns

```ls
| Name                | Field Name          | Data Type | Render Type | Schema Type    | Included | 
| =================== | =================== | ========= | =========== | ============== | ======== | 
| updated_at          | :updated_at         | meta_data | meta_data   | time           | No       | 
| Supplement Number   | supplement_number   | text      | text        | series tag     | Yes      | 
| Project             | project             | text      | text        | series tag     | Yes      | 
| Organization        | organization        | text      | text        | series tag     | Yes      | 
| Contractor          | contractor          | text      | text        | series tag     | Yes      | 
| MWESB               | mwesb               | text      | text        | series tag     | Yes      | 
| Retainer Period     | retainer_period     | text      | text        | series tag     | Yes      | 
| Issue Date          | issue_date          | text      | text        | series tag     | Yes      | 
| Price               | price               | money     | money       | numeric metric | Yes      | 
| Compensation Method | compensation_method | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:uyku-r7g5 d:2012-12-18T09:02:51.000Z t:compensation_method=Fixed t:retainer_period="June 2011 - June 2012" t:project="CARSON HALL PLASTER REPAIR PROJECT" t:organization="University of Oregon" t:contractor="Oregon Ceiling & Acoustics, LLC" t:supplement_number=UO-390-C-11-5 t:issue_date=7/1/11 t:mwesb="MBE, ESB" m:price=46200

series e:uyku-r7g5 d:2012-12-18T09:02:51.000Z t:compensation_method=Fixed t:retainer_period="June 2011 - June 2012" t:project="Heritage Hall Door Replacement" t:organization="Western Oregon University" t:contractor="Robert Gray Partners, Inc." t:supplement_number=WOU-409-C-11-2 t:issue_date=7/5/11 t:mwesb=No m:price=54828

series e:uyku-r7g5 d:2012-12-18T09:02:51.000Z t:compensation_method=Fixed t:retainer_period=2010-2012 t:project="Residence Hall Infrastructure Upgrade" t:organization="Oregon State University" t:contractor="Jimco Electrical Contracting, Inc." t:supplement_number=OSU-16-C-10-151 t:issue_date=7/5/11 t:mwesb=No m:price=207750
```

## Meta Commands

```ls
entity e:uyku-r7g5 l:"Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/uyku-r7g5

property e:uyku-r7g5 t:meta.view d:2017-03-07T19:55:31.289Z v:id=uyku-r7g5 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012"

property e:uyku-r7g5 t:meta.view.owner d:2017-03-07T19:55:31.289Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:uyku-r7g5 t:meta.view.tableauthor d:2017-03-07T19:55:31.289Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```