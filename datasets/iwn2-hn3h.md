# 2012 Final ADT Counts for the State Road Network

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-final-adt-counts-for-the-state-road-network) |
| Metadata | [Link](https://data.ct.gov/api/views/iwn2-hn3h) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/iwn2-hn3h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/iwn2-hn3h/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | iwn2-hn3h |
| Name | 2012 Final ADT Counts for the State Road Network |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | traffic, adt, counts |
| Created | 2014-03-29T14:40:58Z |
| Publication Date | 2014-03-29T14:50:50Z |

## Description

2012 Final ADT Counts for the State Road Network as of 05-29-13.
Additional information is available on the Department of Transportation Website at http://www.ct.gov/dot/lib/dot/documents/dpolicy/traflog/TrafficLog12.pdf

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iwn2-hn3h d:2012-01-01T00:00:00.000Z t:route=001 m:end_mile_pt=0.03 m:begin_mile_pt=0 m:functional_class=3 m:year=2011 m:town=56 m:adt=26500

series e:iwn2-hn3h d:2012-01-01T00:00:00.000Z t:route=001 m:end_mile_pt=0.09 m:begin_mile_pt=0.03 m:functional_class=3 m:year=2011 m:town=56 m:adt=20600

series e:iwn2-hn3h d:2012-01-01T00:00:00.000Z t:route=001 m:end_mile_pt=0.21 m:begin_mile_pt=0.09 m:functional_class=3 m:year=2011 m:town=56 m:adt=18000
```

## Meta Commands

```ls
metric m:town p:integer l:Town t:dataTypeName=number

metric m:begin_mile_pt p:float l:"Begin Mile Pt" t:dataTypeName=number

metric m:end_mile_pt p:float l:"End Mile Pt" t:dataTypeName=number

metric m:functional_class p:integer l:"Functional Class" t:dataTypeName=number

metric m:adt p:integer l:ADT t:dataTypeName=number

metric m:year p:integer l:Year t:dataTypeName=number

entity e:iwn2-hn3h l:"2012 Final ADT Counts for the State Road Network" t:attribution="Department of Transportation" t:url=https://data.ct.gov/api/views/iwn2-hn3h

property e:iwn2-hn3h t:meta.view v:id=iwn2-hn3h v:category=Transportation v:attributionLink=http://www.ct.gov/dot/lib/dot/documents/dpolicy/traflog/TrafficLog12.pdf v:averageRating=0 v:name="2012 Final ADT Counts for the State Road Network" v:attribution="Department of Transportation"

property e:iwn2-hn3h t:meta.view.license v:name="Public Domain"

property e:iwn2-hn3h t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:iwn2-hn3h t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town | route | begin_mile_pt | end_mile_pt | functional_class | adt   | year | 
| ==== | ===== | ============= | =========== | ================ | ===== | ==== | 
| 56   | 001   | 0.00          | 0.03        | 3                | 26500 | 2011 | 
| 56   | 001   | 0.03          | 0.09        | 3                | 20600 | 2011 | 
| 56   | 001   | 0.09          | 0.21        | 3                | 18000 | 2011 | 
| 56   | 001   | 0.21          | 1.59        | 3                | 19100 | 2011 | 
| 56   | 001   | 1.59          | 1.75        | 3                | 20900 | 2011 | 
| 56   | 001   | 1.75          | 2.34        | 3                | 17700 | 2011 | 
| 56   | 001   | 2.34          | 2.66        | 3                | 20000 | 2011 | 
| 56   | 001   | 2.66          | 3.14        | 3                | 22700 | 2011 | 
| 56   | 001   | 3.14          | 3.21        | 3                | 27500 | 2011 | 
| 56   | 001   | 3.21          | 3.60        | 3                | 21400 | 2011 | 
```