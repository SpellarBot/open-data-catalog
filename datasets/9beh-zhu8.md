# Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/9beh-zhu8/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/contracts-ous-capital-construction-retainer-program-pc-amendments-fiscal-year-2012-b5279)
* Id = 9beh-zhu8
* Name = Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012
* Category = Revenue & Expense
* Created = 2012-12-18T16:56:02Z
* Publication Date = 2012-12-18T16:56:50Z
* Rows Updated = 2012-12-18T16:56:06Z

## Description



## Columns

```ls
| Name              | Field Name        | Data Type | Render Type | Schema Type    | Included | 
| ================= | ================= | ========= | =========== | ============== | ======== | 
| updated_at        | :updated_at       | meta_data | meta_data   | time           | Yes      | 
| Supplement Number | supplement_number | text      | text        | series tag     | Yes      | 
| Project           | project           | text      | text        | series tag     | Yes      | 
| Organization      | organization      | text      | text        | series tag     | Yes      | 
| Consultant        | consultant        | text      | text        | series tag     | Yes      | 
| MWESB             | mwesb             | text      | text        | series tag     | Yes      | 
| Retainer Period   | retainer_period   | text      | text        | series tag     | Yes      | 
| Issue Date        | issue_date        | text      | text        | series tag     | Yes      | 
| Price             | price             | money     | money       | numeric metric | Yes      | 
| Amendments        | amendments        | text      | text        | series tag     | Yes      | 
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
series e:9beh-zhu8 d:2012-12-18T08:56:03.000Z t:retainer_period=2011-2013 t:project="Allen Hall Add.& Renovations-MEPF Coordination Plans" t:amendments=UO-54-P-11-58-1 t:organization="University of Oregon" t:consultant="CADD Connection LLC" t:supplement_number=UO-54-P-11-58 t:issue_date=7/7/11 t:mwesb="DBE, MBE, ESB" m:price=49844

series e:9beh-zhu8 d:2012-12-18T08:56:03.000Z t:retainer_period=2011-2013 t:project="Arbuthnot Hall Demolition Inspection Services" t:amendments=WOU-113-P-11-14-1 t:organization="Western Oregon University" t:consultant="FEI Testing & Inspection, Inc." t:supplement_number=WOU-113-P-11-14 t:issue_date=7/11/11 t:mwesb=No m:price=3347

series e:9beh-zhu8 d:2012-12-18T08:56:03.000Z t:retainer_period=2011-2013 t:project="Gill Coliseum Hardscape-Landscape Improvements" t:amendments=OSU-230-P-11-63-1 t:organization="Oregon State University" t:consultant="Schwartz Landscape Architecture" t:supplement_number=OSU-230-P-11-63 t:issue_date=7/14/11 t:mwesb=ESB m:price=51341
```

## Meta Commands

```ls
entity e:9beh-zhu8 l:"Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/9beh-zhu8

property e:9beh-zhu8 t:meta.view d:2017-03-03T14:02:03.830Z v:id=9beh-zhu8 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012"

property e:9beh-zhu8 t:meta.view.owner d:2017-03-03T14:02:03.830Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:9beh-zhu8 t:meta.view.tableauthor d:2017-03-03T14:02:03.830Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```