# Handicap Permits issued at DMV between Jan to Aug 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/handicap-permits-issued-at-dmv-between-jan-to-aug-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/rrcq-gqig) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rrcq-gqig/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rrcq-gqig/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rrcq-gqig |
| Name | Handicap Permits issued at DMV between Jan to Aug 2014 |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-10-03T18:10:42Z |
| Publication Date | 2014-10-03T18:19:33Z |

## Description

Number of Handicap Permits processed at DMV

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       |                | year              | Year              | number    | number      |
| No       |                | month             | Month             | text      | text        |
| Yes      | numeric metric | permits_processed | Permits Processed | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:rrcq-gqig d:2014-01-01T00:00:00.000Z m:permits_processed=2747

series e:rrcq-gqig d:2014-02-01T00:00:00.000Z m:permits_processed=1020

series e:rrcq-gqig d:2014-03-01T00:00:00.000Z m:permits_processed=2238
```

## Meta Commands

```ls
metric m:permits_processed p:integer l:"Permits Processed" t:dataTypeName=number

entity e:rrcq-gqig l:"Handicap Permits issued at DMV between Jan to Aug 2014" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/rrcq-gqig

property e:rrcq-gqig t:meta.view v:id=rrcq-gqig v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Handicap Permits issued at DMV between Jan to Aug 2014" v:attribution="Department of Motor Vehicles"

property e:rrcq-gqig t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:rrcq-gqig t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| year | month | permits_processed | 
| ==== | ===== | ================= | 
| 2014 | Jan   | 2747              | 
| 2014 | Feb   | 1020              | 
| 2014 | Mar   | 2238              | 
| 2014 | Apr   | 2765              | 
| 2014 | May   | 2478              | 
| 2014 | Jun   | 2509              | 
| 2014 | Jul   | 2729              | 
| 2014 | Aug   | 2392              | 
```