# All HACLA Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/all-hacla-properties-25a59) |
| Metadata | [Link](https://data.lacity.org/api/views/uzyn-z273) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/uzyn-z273/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/uzyn-z273/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | uzyn-z273 |
| Name | All HACLA Properties |
| Category | A Prosperous City |
| Tags | housing, hacla, housing authority, public housing |
| Created | 2015-01-15T18:59:19Z |
| Publication Date | 2015-01-26T23:47:44Z |

## Description

List of Properties owned by the Housing Authority of the City of Los Angeles. Updated January 2015.

## Columns

```ls
| Included | Schema Type | Field Name     | Name       | Data Type | Render Type |
| ======== | =========== | ============== | ========== | ========= | =========== |
| No       | time        | :updated_at    | updated_at | meta_data | meta_data   |
| Yes      | series tag  | liph           | GROUP      | text      | text        |
| Yes      | series tag  | ramona_gardens | SITE NAME  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uzyn-z273 d:2015-01-15T10:59:46.000Z t:ramona_gardens="NICKERSON GARDENS" t:liph=LIPH m:row_number.uzyn-z273=1

series e:uzyn-z273 d:2015-01-15T10:59:46.000Z t:ramona_gardens="MANHATTAN GARDENS (CHFA)" t:liph=UaFAM m:row_number.uzyn-z273=2

series e:uzyn-z273 d:2015-01-15T10:59:46.000Z t:ramona_gardens="INDEPENDENT SQUARE" t:liph=SrPBS8 m:row_number.uzyn-z273=3
```

## Meta Commands

```ls
metric m:row_number.uzyn-z273 p:long l:"Row Number"

entity e:uzyn-z273 l:"All HACLA Properties" t:url=https://data.lacity.org/api/views/uzyn-z273

property e:uzyn-z273 t:meta.view v:id=uzyn-z273 v:category="A Prosperous City" v:averageRating=0 v:name="All HACLA Properties"

property e:uzyn-z273 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uzyn-z273 t:meta.view.owner v:id=c4gd-54mz v:screenName=HACLA v:displayName=HACLA

property e:uzyn-z273 t:meta.view.tableauthor v:id=c4gd-54mz v:screenName=HACLA v:roleName=publisher v:displayName=HACLA
```

## Top Records

```ls
| :updated_at | liph    | ramona_gardens           | 
| =========== | ======= | ======================== | 
| 1421319586  | LIPH    | NICKERSON GARDENS        | 
| 1421319586  | UaFAM   | MANHATTAN GARDENS (CHFA) | 
| 1421319586  | SrPBS8  | INDEPENDENT SQUARE       | 
| 1421319586  | MKMFH   | PARTHENIA                | 
| 1421319586  | UaFAM   | SYLMAR AVE.              | 
| 1421319586  | PrivPH  | WILMINGTON TOWNHOMES     | 
| 1421319586  | ScaSite | Former PH                | 
| 1421319586  | ScaSite | Former PH                | 
| 1421319586  | SrNCS8  | RESEDA MANOR             | 
| 1421319586  | ScaSite | Former PH                | 
```