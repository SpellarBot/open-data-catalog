# CIP 2011-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cip-2011-2012-1056b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/pmbr-njwn) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/pmbr-njwn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/pmbr-njwn/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | pmbr-njwn |
| Name | CIP 2011-2012 |
| Attribution | OIMT |
| Category | Economic Development |
| Created | 2013-06-22T00:07:50Z |
| Publication Date | 2013-06-25T17:36:41Z |
| Rows Updated | 2013-06-25T17:36:07Z |

## Description

. Capital Improvement Projects (CIP) are renovations, repairs, and major maintenance to existing facilities, landscape improvements, new construction, land acquisition, and utility modifications. These types of projects are accounted for in a capital improvement budget code of a department.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name        | Data Type | Render Type |
| ======== | ============== | ============ | =========== | ========= | =========== |
| Yes      | time           | year         | Year        | number    | text        |
| Yes      | series tag     | agency       | Agency      | text      | text        |
| Yes      | series tag     | expenditures | Description | text      | text        |
| Yes      | numeric metric | encumbrances | Totals      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
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

property e:pmbr-njwn t:meta.view v:id=pmbr-njwn v:category="Economic Development" v:averageRating=0 v:name="CIP 2011-2012" v:attribution=OIMT

property e:pmbr-njwn t:meta.view.license v:name="Public Domain"

property e:pmbr-njwn t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"

property e:pmbr-njwn t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```