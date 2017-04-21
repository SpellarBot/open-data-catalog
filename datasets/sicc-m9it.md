# Multi-Use Trails

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multi-use-trails-a9634) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/sicc-m9it) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/sicc-m9it/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/sicc-m9it/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | sicc-m9it |
| Name | Multi-Use Trails |
| Attribution | Baltimore City Department of Transportation |
| Category | Transportation |
| Tags | trails, transportation |
| Created | 2013-04-05T18:19:17Z |
| Publication Date | 2014-04-04T00:24:12Z |

## Description

The data shows all current and proposed multiuse trails within the Baltimore City limits. Every reasonable effort has been made to ensure the accuracy of this data. The City of Baltimore makes no representations nor warranties, either expressed or implied, regarding the accuracy of this information or its suitability for any particular purpose whatsoever. The data is licensed "as is" and the City of Baltimore will not be liable for its use or misuse by any party.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | phase       | phase      | text      | text        |
| Yes      | series tag  | trail       | trail      | text      | text        |
| Yes      | series tag  | type        | type       | text      | text        |
| Yes      | series tag  | surface     | surface    | text      | text        |
| Yes      | series tag  | onroad      | onRoad     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sicc-m9it d:2013-04-05T11:19:18.000Z t:surface=ASH-HMA t:trail="Jones Falls" t:type=Path t:phase=Proposed m:row_number.sicc-m9it=1

series e:sicc-m9it d:2013-04-05T11:19:18.000Z t:surface=ASH-HMA t:trail="Jones Falls" t:type=Path t:phase="Long Term" m:row_number.sicc-m9it=2

series e:sicc-m9it d:2013-04-05T11:19:18.000Z t:surface=ASH-HMA t:trail="Herring Run" t:type=Path t:phase=Completed m:row_number.sicc-m9it=3
```

## Meta Commands

```ls
metric m:row_number.sicc-m9it p:long l:"Row Number"

entity e:sicc-m9it l:"Multi-Use Trails" t:attribution="Baltimore City Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/sicc-m9it

property e:sicc-m9it t:meta.view v:id=sicc-m9it v:category=Transportation v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Transportation.aspx v:averageRating=0 v:name="Multi-Use Trails" v:attribution="Baltimore City Department of Transportation"

property e:sicc-m9it t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:sicc-m9it t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:sicc-m9it t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | phase     | trail        | type | surface     | onroad | 
| =========== | ========= | ============ | ==== | =========== | ====== | 
| 1365160758  | Proposed  | Jones Falls  | Path | ASH-HMA     |        | 
| 1365160758  | Long Term | Jones Falls  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | ASH-HMA     |        | 
| 1365160758  | Completed | Herring Run  | Path | Crusher Run |        | 
| 1365160758  | Completed | Gwynns Falls | Path | ASH-HMA     |        | 
```