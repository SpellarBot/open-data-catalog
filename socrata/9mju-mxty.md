# Washington Anadromous Fish Harvest Data 1974 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/washington-anadromous-fish-harvest-data-1974-2012-f94d5) |
| Metadata | [Link](https://data.wa.gov/api/views/9mju-mxty) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9mju-mxty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9mju-mxty/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9mju-mxty |
| Name | Washington Anadromous Fish Harvest Data 1974 - 2012 |
| Attribution | WDFW |
| Category | Natural Resources & Environment |
| Tags | salmon, steelhead, chinook, sockeye, pink, chum, coho, harvest, fisheries |
| Created | 2013-10-07T22:19:25Z |
| Publication Date | 2013-10-07T22:54:13Z |

## Description

WDFW combined Sport/ Commercial/ Treaty salmon harvest data.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year                 | Year                 | number    | number      |
| Yes      | series tag     | fisher_type          | Fisher Type          | text      | text        |
| Yes      | numeric metric | chinook              | CHINOOK              | number    | number      |
| Yes      | numeric metric | coho                 | COHO                 | number    | number      |
| Yes      | numeric metric | chum                 | CHUM                 | number    | number      |
| Yes      | numeric metric | pink                 | PINK                 | number    | number      |
| Yes      | numeric metric | sockeye              | SOCKEYE              | number    | number      |
| Yes      | numeric metric | steelhead            | STEELHEAD            | number    | number      |
| Yes      | numeric metric | jacks                | JACKS                | number    | number      |
| Yes      | numeric metric | unknown              | UNKNOWN              | number    | number      |
| Yes      | series tag     | total_by_fisher_type | Total by Fisher Type | text      | number      |
| Yes      | numeric metric | total_by_year        | Total by Year        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9mju-mxty d:1974-01-01T00:00:00.000Z t:total_by_fisher_type=1437249 t:fisher_type=Sport m:chinook=491034 m:sockeye=8863 m:pink=159 m:coho=790981 m:jacks=25072 m:steelhead=116829 m:chum=4311

series e:9mju-mxty d:1974-01-01T00:00:00.000Z t:total_by_fisher_type=4827208 t:fisher_type=Non-Treaty m:chinook=464073 m:sockeye=2452416 m:pink=1170 m:coho=1619193 m:steelhead=927 m:chum=289429

series e:9mju-mxty d:1974-01-01T00:00:00.000Z t:total_by_fisher_type=860006 t:fisher_type=Treaty m:chinook=142707 m:sockeye=59857 m:total_by_year=7124463 m:pink=25 m:coho=479473 m:steelhead=4885 m:chum=173059
```

## Meta Commands

```ls
metric m:chinook p:integer l:CHINOOK t:dataTypeName=number

metric m:coho p:integer l:COHO t:dataTypeName=number

metric m:chum p:integer l:CHUM t:dataTypeName=number

metric m:pink p:integer l:PINK t:dataTypeName=number

metric m:sockeye p:integer l:SOCKEYE t:dataTypeName=number

metric m:steelhead p:integer l:STEELHEAD t:dataTypeName=number

metric m:jacks p:integer l:JACKS t:dataTypeName=number

metric m:unknown p:integer l:UNKNOWN t:dataTypeName=number

metric m:total_by_year p:integer l:"Total by Year" t:dataTypeName=number

entity e:9mju-mxty l:"Washington Anadromous Fish Harvest Data 1974 - 2012" t:attribution=WDFW t:url=https://data.wa.gov/api/views/9mju-mxty

property e:9mju-mxty t:meta.view v:id=9mju-mxty v:category="Natural Resources & Environment" v:averageRating=0 v:name="Washington Anadromous Fish Harvest Data 1974 - 2012" v:attribution=WDFW

property e:9mju-mxty t:meta.view.owner v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:displayName="Brodie Cox"

property e:9mju-mxty t:meta.view.tableauthor v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:roleName=publisher v:displayName="Brodie Cox"
```

## Top Records

```ls
| year | fisher_type | chinook | coho    | chum   | pink    | sockeye | steelhead | jacks | unknown | total_by_fisher_type | total_by_year | 
| ==== | =========== | ======= | ======= | ====== | ======= | ======= | ========= | ===== | ======= | ==================== | ============= | 
| 1974 | Sport       | 491034  | 790981  | 4311   | 159     | 8863    | 116829    | 25072 |         | 1437249              |               | 
| 1974 | Non-Treaty  | 464073  | 1619193 | 289429 | 1170    | 2452416 | 927       |       |         | 4827208              |               | 
| 1974 | Treaty      | 142707  | 479473  | 173059 | 25      | 59857   | 4885      |       |         | 860006               | 7124463       | 
| 1975 | Sport       | 616975  | 701721  | 771    | 21284   | 639     | 67932     | 57497 | 488     | 1467307              |               | 
| 1975 | Non-Treaty  | 443682  | 1368932 | 135052 | 1301226 | 1558893 |           |       |         | 4807785              |               | 
| 1975 | Treaty      | 227073  | 454455  | 80625  | 105227  | 133661  |           |       |         | 1001041              | 7276133       | 
| 1976 | Sport       | 503877  | 1195579 | 3024   | 722     | 673     | 84876     | 44130 | 1555    | 1834436              |               | 
| 1976 | Non-Treaty  | 505866  | 1786393 | 524491 | 1353    | 1223641 |           |       |         | 4041744              |               | 
| 1976 | Treaty      | 267965  | 345912  | 298825 | 42      | 110508  | 12066     |       |         | 1035318              | 6911498       | 
| 1977 | Sport       | 398494  | 683108  | 1362   | 53883   | 13689   | 158005    | 38155 | 2723    | 1349419              |               | 
```