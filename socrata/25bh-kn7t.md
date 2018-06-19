# 2011 Final ADT Counts for the State Road Network

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-final-adt-counts-for-the-state-road-network) |
| Metadata | [Link](https://data.ct.gov/api/views/25bh-kn7t) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/25bh-kn7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/25bh-kn7t/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 25bh-kn7t |
| Name | 2011 Final ADT Counts for the State Road Network |
| Attribution | Department of Transportations |
| Category | Transportation |
| Tags | traffic, counts, adt, dot |
| Created | 2014-03-29T19:34:24Z |
| Publication Date | 2014-03-29T19:38:00Z |

## Description

2011 Final ADT Counts for the State Road Network as of 06-06-12
Additional Info:    Additional information is available on the Department of Transportation Website at http://www.ct.gov/dot/lib/dot/documents/dpolicy/traflog/TrafficLog12.pdf

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | numeric metric | town             | Town             | number    | number      |
| Yes      | series tag     | route            | Route            | text      | text        |
| Yes      | numeric metric | begin_mile_pt    | Begin Mile Pt    | number    | number      |
| Yes      | numeric metric | end_mile_pt      | End Mile Pt      | number    | number      |
| Yes      | numeric metric | functional_class | Functional Class | number    | number      |
| Yes      | numeric metric | adt              | ADT              | number    | number      |
| Yes      | numeric metric | year             | Year             | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:25bh-kn7t d:2011-01-01T00:00:00.000Z t:route=001 m:end_mile_pt=0.03 m:begin_mile_pt=0 m:functional_class=3 m:year=2011 m:town=56 m:adt=26600

series e:25bh-kn7t d:2011-01-01T00:00:00.000Z t:route=001 m:end_mile_pt=0.09 m:begin_mile_pt=0.03 m:functional_class=3 m:year=2011 m:town=56 m:adt=20700

series e:25bh-kn7t d:2011-01-01T00:00:00.000Z t:route=001 m:end_mile_pt=0.21 m:begin_mile_pt=0.09 m:functional_class=3 m:year=2011 m:town=56 m:adt=18000
```

## Meta Commands

```ls
metric m:town p:integer l:Town t:dataTypeName=number

metric m:begin_mile_pt p:float l:"Begin Mile Pt" t:dataTypeName=number

metric m:end_mile_pt p:float l:"End Mile Pt" t:dataTypeName=number

metric m:functional_class p:integer l:"Functional Class" t:dataTypeName=number

metric m:adt p:integer l:ADT t:dataTypeName=number

metric m:year p:integer l:Year t:dataTypeName=number

entity e:25bh-kn7t l:"2011 Final ADT Counts for the State Road Network" t:attribution="Department of Transportations" t:url=https://data.ct.gov/api/views/25bh-kn7t

property e:25bh-kn7t t:meta.view v:id=25bh-kn7t v:category=Transportation v:attributionLink=http://www.ct.gov/dot/lib/dot/documents/dpolicy/traflog/TrafficLog12.pdf v:averageRating=0 v:name="2011 Final ADT Counts for the State Road Network" v:attribution="Department of Transportations"

property e:25bh-kn7t t:meta.view.license v:name="Public Domain"

property e:25bh-kn7t t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:25bh-kn7t t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town | route | begin_mile_pt | end_mile_pt | functional_class | adt   | year | 
| ==== | ===== | ============= | =========== | ================ | ===== | ==== | 
| 56   | 001   | 0             | 0.03        | 3                | 26600 | 2011 | 
| 56   | 001   | 0.03          | 0.09        | 3                | 20700 | 2011 | 
| 56   | 001   | 0.09          | 0.21        | 3                | 18000 | 2011 | 
| 56   | 001   | 0.21          | 1.59        | 3                | 19200 | 2011 | 
| 56   | 001   | 1.59          | 1.75        | 3                | 21000 | 2011 | 
| 56   | 001   | 1.75          | 2.34        | 3                | 17700 | 2011 | 
| 56   | 001   | 2.34          | 2.66        | 3                | 20100 | 2011 | 
| 56   | 001   | 2.66          | 3.14        | 3                | 22800 | 2011 | 
| 56   | 001   | 3.14          | 3.21        | 3                | 27600 | 2011 | 
| 56   | 001   | 3.21          | 3.6         | 3                | 21500 | 2011 | 
```