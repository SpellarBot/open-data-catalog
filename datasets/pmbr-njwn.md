# CIP 2011-2012

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/pmbr-njwn/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/cip-2011-2012-1056b)
* [Metadata URL](https://data.hawaii.gov/api/views/pmbr-njwn)
* Id = pmbr-njwn
* Name = CIP 2011-2012
* Attribution = OIMT
* Category = Economic Development
* Created = 2013-06-22T00:07:50Z
* Publication Date = 2013-06-25T17:36:41Z
* Rows Updated = 2013-06-25T17:36:07Z

## Description

. Capital Improvement Projects (CIP) are renovations, repairs, and major maintenance to existing facilities, landscape improvements, new construction, land acquisition, and utility modifications. These types of projects are accounted for in a capital improvement budget code of a department.

## Columns

```ls
| Name        | Field Name   | Data Type | Render Type | Schema Type    | Included | 
| =========== | ============ | ========= | =========== | ============== | ======== | 
| Year        | year         | number    | text        | time           | Yes      | 
| Agency      | agency       | text      | text        | series tag     | Yes      | 
| Description | expenditures | text      | text        | series tag     | Yes      | 
| Totals      | encumbrances | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
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
series e:pmbr-njwn d:2012-01-01T00:00:00.000Z t:expenditures=Expenditure t:agency=Transportation m:encumbrances=108719118.34

series e:pmbr-njwn d:2012-01-01T00:00:00.000Z t:expenditures=Encumbrance t:agency=Transportation m:encumbrances=104647637.54

series e:pmbr-njwn d:2012-01-01T00:00:00.000Z t:expenditures=Expenditure t:agency="University of Hawaii" m:encumbrances=50720338.9
```

## Meta Commands

```ls
metric m:encumbrances l:Totals t:dataTypeName=number

entity e:pmbr-njwn l:"CIP 2011-2012" t:attribution=OIMT t:url=https://data.hawaii.gov/api/views/pmbr-njwn

property e:pmbr-njwn t:meta.view d:2017-03-08T00:41:21.328Z v:id=pmbr-njwn v:category="Economic Development" v:averageRating=0 v:name="CIP 2011-2012" v:attribution=OIMT

property e:pmbr-njwn t:meta.view.license d:2017-03-08T00:41:21.328Z v:name="Public Domain"

property e:pmbr-njwn t:meta.view.owner d:2017-03-08T00:41:21.328Z v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"

property e:pmbr-njwn t:meta.view.tableauthor d:2017-03-08T00:41:21.328Z v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```