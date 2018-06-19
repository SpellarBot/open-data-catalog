# Passenger-Commercial Revenue Analysis, New York State Bridge Authority Facilities: Beginning 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/passenger-commercial-revenue-analysis-new-york-state-bridge-authority-facilities-beginning) |
| Metadata | [Link](https://data.ny.gov/api/views/chh6-mt9c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/chh6-mt9c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/chh6-mt9c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | chh6-mt9c |
| Name | Passenger-Commercial Revenue Analysis, New York State Bridge Authority Facilities: Beginning 1995 |
| Attribution | New York State Bridge Authority |
| Category | Transportation |
| Tags | traffic, tolls, bridge |
| Created | 2013-05-01T19:51:24Z |
| Publication Date | 2016-01-27T23:03:03Z |

## Description

Revenue Comparison between passenger and commercial vehicles on all New York State Bridge Authority facilities from 1995 to 2012

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | bridge     | Bridge     | text      | text        |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | numeric metric | passenger  | Passenger  | money     | money       |
| Yes      | numeric metric | commercial | Commercial | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:chh6-mt9c d:2012-01-01T00:00:00.000Z t:bridge="Bear Mountain" m:passenger=4466404 m:commercial=469955

series e:chh6-mt9c d:2012-01-01T00:00:00.000Z t:bridge="Kingston - Rhinecliff" m:passenger=4973698 m:commercial=737729

series e:chh6-mt9c d:2012-01-01T00:00:00.000Z t:bridge=Mid-Hudson m:passenger=8737020 m:commercial=1324442
```

## Meta Commands

```ls
metric m:passenger p:double l:Passenger t:dataTypeName=money

metric m:commercial p:double l:Commercial t:dataTypeName=money

entity e:chh6-mt9c l:"Passenger-Commercial Revenue Analysis, New York State Bridge Authority Facilities: Beginning 1995" t:attribution="New York State Bridge Authority" t:url=https://data.ny.gov/api/views/chh6-mt9c

property e:chh6-mt9c t:meta.view v:id=chh6-mt9c v:category=Transportation v:attributionLink=http://www.nysba.net/Index%20Page/General%20Info.html v:averageRating=0 v:name="Passenger-Commercial Revenue Analysis, New York State Bridge Authority Facilities: Beginning 1995" v:attribution="New York State Bridge Authority"

property e:chh6-mt9c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:chh6-mt9c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:chh6-mt9c t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bridge                | year | passenger   | commercial  | 
| ===================== | ==== | =========== | =========== | 
| Bear Mountain         | 2012 | 4466404.00  | 469955.00   | 
| Kingston - Rhinecliff | 2012 | 4973698.00  | 737729.00   | 
| Mid-Hudson            | 2012 | 8737020.00  | 1324442.00  | 
| Newburgh-Beacon       | 2012 | 15228458.00 | 13554969.00 | 
| Rip Van Winkle        | 2012 | 3440113.00  | 890389.00   | 
| Bear Mountain         | 2011 | 3132646.00  | 321513.00   | 
| Kingston - Rhinecliff | 2011 | 3570680.00  | 479743.00   | 
| Mid-Hudson            | 2011 | 6030191.00  | 851540.00   | 
| Newburgh-Beacon       | 2011 | 10810597.00 | 9089175.00  | 
| Rip Van Winkle        | 2011 | 2399236.00  | 557987.00   | 
```