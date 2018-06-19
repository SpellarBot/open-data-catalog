# Revaluation Years by Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revaluation-years-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/2se9-jnuq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2se9-jnuq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2se9-jnuq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2se9-jnuq |
| Name | Revaluation Years by Town |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | towns, revaluation |
| Created | 2014-03-05T15:58:17Z |
| Publication Date | 2014-03-05T18:41:24Z |

## Description

A revaluation program is undertaken to secure a more equitable distribution of the tax burden, to bring the assessment level up to date, and to modernize assessment procedures. Furthermore, Connecticut law requires that all property be revalued for assessment purposes periodically. A revaluation is required to be completed every five years. The purpose of this requirement is to insure uniformity in real property valuations by eliminating inequities that may have developed since the previous revaluation. Updated September 2013

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | series tag  | town_code       | TOWN CODE       | text      | number      |
| Yes      | series tag  | town            | TOWN            | text      | text        |
| Yes      | time        | next_reval_year | NEXT REVAL YEAR | number    | number      |
```

## Time Field

```ls
Value = next_reval_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:2se9-jnuq l:"Revaluation Years by Town" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/2se9-jnuq

property e:2se9-jnuq t:meta.view v:id=2se9-jnuq v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?A=2987&Q=385050" v:averageRating=0 v:name="Revaluation Years by Town" v:attribution="Office of Policy and Management"

property e:2se9-jnuq t:meta.view.license v:name="Public Domain"

property e:2se9-jnuq t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:2se9-jnuq t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town_code | town         | next_reval_year | 
| ========= | ============ | =============== | 
| 1         | Andover      | 2016            | 
| 2         | Ansonia      | 2017            | 
| 3         | Ashford      | 2016            | 
| 4         | Avon         | 2013            | 
| 5         | Barkhamsted  | 2013            | 
| 6         | Beacon Falls | 2016            | 
| 7         | Berlin       | 2017            | 
| 8         | Bethany      | 2013            | 
| 9         | Bethel       | 2017            | 
| 10        | Bethlehem    | 2013            | 
```