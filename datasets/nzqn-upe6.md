# Grant Information Collection Act - 4th Quarter - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-4th-quarter-2014-18686) |
| Metadata | [Link](https://data.illinois.gov/api/views/nzqn-upe6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nzqn-upe6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nzqn-upe6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nzqn-upe6 |
| Name | Grant Information Collection Act - 4th Quarter - 2014 |
| Attribution | Illinois Arts Council Agency |
| Category | Recreation |
| Tags | illinois arts council, illinois arts council agency, arts |
| Created | 2015-01-21T15:41:52Z |
| Publication Date | 2015-01-21T15:48:03Z |

## Description

4th Quarter 2014 data for Illinois Arts Council Agency

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type     | Render Type   |
| ======== | ============== | ========== | ====== | ============= | ============= |
| No       |                | fy         | FY     | number        | number        |
| Yes      | series tag     | flname     | FLName | text          | text          |
| Yes      | series tag     | title      | Title  | text          | text          |
| Yes      | numeric metric | grant      | Grant  | money         | money         |
| Yes      | time           | dvo        | Dvo    | calendar_date | calendar_date |
| No       |                | beg        | Beg    | calendar_date | calendar_date |
| No       |                | end        | End    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dvo
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,beg,end
```

## Data Commands

```ls
series e:nzqn-upe6 d:2014-10-22T00:00:00.000Z t:title="for general operating support" t:flname="Emerald City Theatre" m:grant=11350

series e:nzqn-upe6 d:2014-12-19T00:00:00.000Z t:title="for Story Week Fest project support" t:flname="Columbia College Chicago" m:grant=6000

series e:nzqn-upe6 d:2014-12-03T00:00:00.000Z t:title="for Community Arts Access Program" t:flname="Buchanan Center for the Arts" m:grant=5600
```

## Meta Commands

```ls
metric m:grant p:integer l:Grant t:dataTypeName=money

entity e:nzqn-upe6 l:"Grant Information Collection Act - 4th Quarter - 2014" t:attribution="Illinois Arts Council Agency" t:url=https://data.illinois.gov/api/views/nzqn-upe6

property e:nzqn-upe6 t:meta.view v:id=nzqn-upe6 v:category=Recreation v:attributionLink=http://www.arts.illinois.gov/ v:averageRating=0 v:name="Grant Information Collection Act - 4th Quarter - 2014" v:attribution="Illinois Arts Council Agency"

property e:nzqn-upe6 t:meta.view.license v:name="Public Domain"

property e:nzqn-upe6 t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:nzqn-upe6 t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| fy | flname                             | title                                         | grant | dvo                 | beg                 | end                 | 
| == | ================================== | ============================================= | ===== | =================== | =================== | =================== | 
| 15 | Emerald City Theatre               | for general operating support                 | 11350 | 2014-10-22T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Columbia College Chicago           | for Story Week Fest project support           | 6000  | 2014-12-19T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Buchanan Center for the Arts       | for Community Arts Access Program             | 5600  | 2014-12-03T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | St Charles Singers                 | for general operating support                 | 6750  | 2014-10-24T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Lake Forest Symphony Assn Inc      | for general operating support                 | 11350 | 2014-10-29T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Chicago Improv Productions NFP     | for general operating support                 | 3650  | 2014-10-10T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | The Chicago Ensemble               | for general operating support                 | 1350  | 2014-10-31T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Mother McAuley Lib Art High School | for Summer Theatre Festival operating support | 1025  | 2014-10-22T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Barrel of Monkeys Productions      | for general operating support                 | 7275  | 2014-12-01T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Midwest Young Artists              | for general operating support                 | 11350 | 2014-12-05T00:00:00 | 2014-09-15T00:00:00 | 2015-08-31T00:00:00 | 
```