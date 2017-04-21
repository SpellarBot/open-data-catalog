# Vacants to Value - Middle Market

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vacants-to-value-middle-market-30d45) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/2nea-5tsk) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/2nea-5tsk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/2nea-5tsk/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 2nea-5tsk |
| Name | Vacants to Value - Middle Market |
| Attribution | Baltimore Housing |
| Category | Housing & Development |
| Tags | vacant, value |
| Created | 2012-01-03T19:55:11Z |
| Publication Date | 2014-04-03T23:42:13Z |

## Description

Transitional blocks are predominantly occupied but are challenged by a small number of vacant, boarded buildings. http://www.baltimorehousing.org/vacants_to_value.aspx

## Columns

```ls
| Included | Schema Type    | Field Name | Name         | Data Type     | Render Type   |
| ======== | ============== | ========== | ============ | ============= | ============= |
| Yes      | series tag     | block      | block        | text          | text          |
| Yes      | series tag     | lot        | lot          | text          | text          |
| No       |                | nb         | neighborhood | text          | text          |
| Yes      | numeric metric | phase      | phase        | number        | number        |
| Yes      | time           | datestart  | dateStart    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = datestart
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = nb
```

## Data Commands

```ls
series e:2nea-5tsk d:2011-06-24T00:00:00.000Z t:lot=6 t:block=5864M m:phase=2

series e:2nea-5tsk d:2011-06-24T00:00:00.000Z t:lot=33 t:block=6299B m:phase=2

series e:2nea-5tsk d:2011-06-24T00:00:00.000Z t:lot=22 t:block=5764 m:phase=2
```

## Meta Commands

```ls
metric m:phase p:integer l:phase d:"Used to group neighborhoods by start date" t:dataTypeName=number

entity e:2nea-5tsk l:"Vacants to Value - Middle Market" t:attribution="Baltimore Housing" t:url=https://data.baltimorecity.gov/api/views/2nea-5tsk

property e:2nea-5tsk t:meta.view v:id=2nea-5tsk v:category="Housing & Development" v:attributionLink=http://www.baltimorehousing.org/ v:averageRating=0 v:name="Vacants to Value - Middle Market" v:attribution="Baltimore Housing"

property e:2nea-5tsk t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:2nea-5tsk t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:2nea-5tsk t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| block | lot  | nb              | phase | datestart           | 
| ===== | ==== | =============== | ===== | =================== | 
| 5864M | 6    | MORAVIA-WALTHER | 2     | 2011-06-24T00:00:00 | 
| 6299B | 33   | HIGHLANDTOWN    | 2     | 2011-06-24T00:00:00 | 
| 5764  | 22   | GLENHAM-BELFORD | 2     | 2011-06-24T00:00:00 | 
| 5341  | 17   | LAURAVILLE      | 2     | 2011-06-24T00:00:00 | 
| 6043  | 7    | FRANKFORD       | 2     | 2011-06-24T00:00:00 | 
| 3059A | 70   | Hanlon-Longwood | 1     | 2010-11-29T00:00:00 | 
| 8245  | 001D | HOWARD PARK     | 3     | 2011-11-21T00:00:00 | 
| 5391  | 25   | LAURAVILLE      | 2     | 2011-06-24T00:00:00 | 
| 5896A | 17   | ARCADIA         | 2     | 2011-06-24T00:00:00 | 
| 6573  | 31   | GREEKTOWN       | 2     | 2011-06-24T00:00:00 | 
```