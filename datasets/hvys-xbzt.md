# Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/hvys-xbzt/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/contracts-ous-captial-construction-retainer-program-crs-supplements-fy2013-aa4c2)
* [Metadata URL](https://data.oregon.gov/api/views/hvys-xbzt)
* Id = hvys-xbzt
* Name = Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013
* Category = Revenue & Expense
* Tags = [ous capital construction retainer program, crs supplements, capital construction retainer program]
* Created = 2013-11-21T16:44:01Z
* Publication Date = 2013-11-21T16:45:35Z
* Rows Updated = 2013-11-21T16:44:10Z

## Description



## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | =================== | ============= | ============= | ============== | ======== | 
| Supplement Number   | supplement_number   | text          | text          | series tag     | Yes      | 
| Project             | project             | text          | text          | series tag     | Yes      | 
| Organization        | organization        | text          | text          | series tag     | Yes      | 
| Contractor          | contractor          | text          | text          | series tag     | Yes      | 
| MWESB               | mwesb               | text          | text          | series tag     | Yes      | 
| Retainer Period     | retainer_period     | text          | text          | series tag     | Yes      | 
| Issue Date          | issue_date          | calendar_date | calendar_date | time           | Yes      | 
| Price               | price               | number        | number        | numeric metric | Yes      | 
| Compensation Method | compensation_method | text          | text          | series tag     | Yes      | 
| Amendments          | amendments          | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
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
series e:hvys-xbzt d:2012-07-02T00:00:00.000Z t:compensation_method="Time and Materials" t:retainer_period="July 2012 - June 2014" t:project="Miscellaneous Small Campus Projects" t:organization="University of Oregon" t:contractor="Stedman Sheet Metal, Inc." t:supplement_number=UO-636-C-12-1 t:mwesb=No m:price=50000

series e:hvys-xbzt d:2012-07-05T00:00:00.000Z t:compensation_method=Fixed t:retainer_period="July 2012 - June 2014" t:project="Magruder Hall Chiller Replacement" t:organization="Oregon State University" t:contractor="Hammerquist, Inc." t:supplement_number=OSU-131-C-12-1 t:mwesb=No m:price=56801

series e:hvys-xbzt d:2012-07-06T00:00:00.000Z t:compensation_method="Time and Materials" t:retainer_period="July 2012 - June 2014" t:project="Miscellaneous Small Campus Projects" t:organization="University of Oregon" t:contractor="Office World, Inc." t:supplement_number=UO-574-C-12-2 t:mwesb=No m:price=50000
```

## Meta Commands

```ls
metric m:price l:Price t:dataTypeName=number

entity e:hvys-xbzt l:"Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013" t:url=https://data.oregon.gov/api/views/hvys-xbzt

property e:hvys-xbzt t:meta.view d:2017-03-07T16:54:42.885Z v:id=hvys-xbzt v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Captial Construction Retainer Program: CRS Supplements: FY2013"

property e:hvys-xbzt t:meta.view.owner d:2017-03-07T16:54:42.885Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:hvys-xbzt t:meta.view.tableauthor d:2017-03-07T16:54:42.885Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```