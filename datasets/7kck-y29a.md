# 2012 Dec Top Ten Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-dec-top-ten-sites-f6f58) |
| Metadata | [Link](https://data.honolulu.gov/api/views/7kck-y29a) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/7kck-y29a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/7kck-y29a/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 7kck-y29a |
| Name | 2012 Dec Top Ten Sites |
| Created | 2012-12-12T01:52:50Z |
| Publication Date | 2012-12-12T01:54:06Z |

## Description

Top Ten Sites from each department in Dec 2012

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | department  | Department  | text      | text        |
| Yes      | series tag     | host        | Host        | text      | text        |
| Yes      | series tag     | category    | Category    | text      | text        |
| Yes      | numeric metric | page_views  | Page Views  | number    | number      |
| Yes      | numeric metric | total_bytes | Total Bytes | number    | number      |
| Yes      | numeric metric | requests    | Requests    | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7kck-y29a d:2012-01-01T00:00:00.000Z t:category="Search Engines/Portals" t:host=desktop2.google.com t:department=BFS m:requests=512633 m:total_bytes=1174185909 m:page_views=512633

series e:7kck-y29a d:2012-01-01T00:00:00.000Z t:category=Computers/Internet t:host=desktop.google.com t:department=BFS m:requests=256310 m:total_bytes=497957681 m:page_views=256310

series e:7kck-y29a d:2012-01-01T00:00:00.000Z t:category="Audio/Video Clips" t:host=77.67.85.103 t:department=BFS m:requests=169410 m:total_bytes=250716708 m:page_views=169410
```

## Meta Commands

```ls
metric m:page_views p:integer l:"Page Views" t:dataTypeName=number

metric m:total_bytes p:long l:"Total Bytes" t:dataTypeName=number

metric m:requests p:integer l:Requests t:dataTypeName=number

entity e:7kck-y29a l:"2012 Dec Top Ten Sites" t:url=https://data.honolulu.gov/api/views/7kck-y29a

property e:7kck-y29a t:meta.view v:id=7kck-y29a v:averageRating=0 v:name="2012 Dec Top Ten Sites"

property e:7kck-y29a t:meta.view.owner v:id=ygsi-kpdp v:screenName=kchan2 v:displayName=kchan2

property e:7kck-y29a t:meta.view.tableauthor v:id=ygsi-kpdp v:screenName=kchan2 v:roleName=publisher v:displayName=kchan2
```

## Top Records

```ls
| department | host                         | category               | page_views | total_bytes | requests | 
| ========== | ============================ | ====================== | ========== | =========== | ======== | 
| BFS        | desktop2.google.com          | Search Engines/Portals | 512633     | 1174185909  | 512633   | 
| BFS        | desktop.google.com           | Computers/Internet     | 256310     | 497957681   | 256310   | 
| BFS        | 77.67.85.103                 | Audio/Video Clips      | 169410     | 250716708   | 169410   | 
| BFS        | www.facebook.com             | Social Networking      | 101942     | 3211856684  | 203858   | 
| BFS        | www.google.com               | Search Engines/Portals | 56537      | 4055768793  | 185143   | 
| BFS        | www.staradvertiser.com       | News/Media             | 52951      | 13149368809 | 1816277  | 
| BFS        | seekingalpha.com             | Financial Services     | 49600      | 420964034   | 74141    | 
| BFS        | urs.microsoft.com            | Computers/Internet     | 45980      | 318650853   | 45980    | 
| BFS        | qb22bgpatchsp.quickbooks.com | Financial Services     | 45329      | 1920938832  | 45329    | 
| BFS        | platform.twitter.com         | Social Networking      | 42699      | 739665995   | 112371   | 
```