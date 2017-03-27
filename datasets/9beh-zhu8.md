# Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-ous-capital-construction-retainer-program-pc-amendments-fiscal-year-2012-b5279) |
| Metadata | [Link](https://data.oregon.gov/api/views/9beh-zhu8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9beh-zhu8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9beh-zhu8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9beh-zhu8 |
| Name | Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-18T16:56:02Z |
| Publication Date | 2012-12-18T16:56:50Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | supplement_number | Supplement Number | text      | text        |
| Yes      | series tag     | project           | Project           | text      | text        |
| Yes      | series tag     | organization      | Organization      | text      | text        |
| Yes      | series tag     | consultant        | Consultant        | text      | text        |
| Yes      | series tag     | mwesb             | MWESB             | text      | text        |
| Yes      | series tag     | retainer_period   | Retainer Period   | text      | text        |
| Yes      | time           | issue_date        | Issue Date        | text      | text        |
| Yes      | numeric metric | price             | Price             | money     | money       |
| Yes      | series tag     | amendments        | Amendments        | text      | text        |
```

## Time Field

```ls
Value = issue_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:9beh-zhu8 d:2011-07-07T00:00:00.000Z t:retainer_period=2011-2013 t:project="Allen Hall Add.& Renovations-MEPF Coordination Plans" t:amendments=UO-54-P-11-58-1 t:organization="University of Oregon" t:consultant="CADD Connection LLC" t:supplement_number=UO-54-P-11-58 t:mwesb="DBE, MBE, ESB" m:price=49844

series e:9beh-zhu8 d:2011-07-11T00:00:00.000Z t:retainer_period=2011-2013 t:project="Arbuthnot Hall Demolition Inspection Services" t:amendments=WOU-113-P-11-14-1 t:organization="Western Oregon University" t:consultant="FEI Testing & Inspection, Inc." t:supplement_number=WOU-113-P-11-14 t:mwesb=No m:price=3347

series e:9beh-zhu8 d:2011-07-14T00:00:00.000Z t:retainer_period=2011-2013 t:project="Gill Coliseum Hardscape-Landscape Improvements" t:amendments=OSU-230-P-11-63-1 t:organization="Oregon State University" t:consultant="Schwartz Landscape Architecture" t:supplement_number=OSU-230-P-11-63 t:mwesb=ESB m:price=51341
```

## Meta Commands

```ls
metric m:price p:double l:Price t:dataTypeName=money

entity e:9beh-zhu8 l:"Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/9beh-zhu8

property e:9beh-zhu8 t:meta.view v:id=9beh-zhu8 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Capital Construction Retainer Program: PC Amendments: Fiscal Year 2012"

property e:9beh-zhu8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:9beh-zhu8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```