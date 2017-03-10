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
| Rows Updated | 2014-10-03T18:10:49Z |

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
Excluded Fields = month,year
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

property e:rrcq-gqig t:meta.view d:2017-03-10T16:06:56.987Z v:id=rrcq-gqig v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Handicap Permits issued at DMV between Jan to Aug 2014" v:attribution="Department of Motor Vehicles"

property e:rrcq-gqig t:meta.view.owner d:2017-03-10T16:06:56.987Z v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel

property e:rrcq-gqig t:meta.view.tableauthor d:2017-03-10T16:06:56.987Z v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```