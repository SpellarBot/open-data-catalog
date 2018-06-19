# Jamica Center BID businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jamica-center-bid-businesses-f0fc6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/x84u-rirx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/x84u-rirx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/x84u-rirx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | x84u-rirx |
| Name | Jamica Center BID businesses |
| Attribution | Jamaica Center BID |
| Category | Business |
| Tags | jamaica, queens, stores, retail, businesses, directory |
| Created | 2011-10-06T17:46:47Z |
| Publication Date | 2013-06-21T19:29:34Z |

## Description

Directory of businesses in the Jamaica Center business district

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | store          | Store          | text      | text        |
| Yes      | series tag  | bus_city       | Bus City       | text      | text        |
| Yes      | series tag  | bus_zip        | Bus Zip        | text      | number      |
| Yes      | time        | year_opened    | Year Opened    | number    | text        |
| Yes      | series tag  | business_size  | Business Size  | text      | text        |
| Yes      | series tag  | category       | Category       | text      | text        |
| Yes      | series tag  | business_phone | Business Phone | text      | text        |
```

## Time Field

```ls
Value = year_opened
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:x84u-rirx l:"Jamica Center BID businesses" t:attribution="Jamaica Center BID" t:url=https://data.cityofnewyork.us/api/views/x84u-rirx

property e:x84u-rirx t:meta.view v:id=x84u-rirx v:category=Business v:averageRating=0 v:name="Jamica Center BID businesses" v:attribution="Jamaica Center BID"

property e:x84u-rirx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:x84u-rirx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| store                      | bus_city | bus_zip | year_opened | business_size | category              | business_phone | 
| ========================== | ======== | ======= | =========== | ============= | ===================== | ============== | 
| L.B. Gifts & Lamps Variety | Jamaica  | 11435   |             |               |                       |                | 
| C.H. Martin                | Jamaica  | 11435   |             |               |                       |                | 
| No frontage on Jamaica Ave | Jamaica  | 11432   |             | Vacant        |                       |                | 
| No frontage on Jamaica Ave | Jamaica  | 11432   |             |               |                       |                | 
| Kanna's Nail Studio        | Jamaica  | 11435   |             | Mom and Pop   | HAIR & NAILS          | 718-526-8883   | 
| Rafael & Co. Jewelry       | Jamaica  | 11435   |             | Mom and Pop   | JEWELRY & ACCESSORIES |                | 
| Bank of America            | Jamaica  | 11435   |             | National      | BANKING               | 800-841-4000   | 
| GG's Convenience Store     | Jamaica  | 11435   |             | Mom and Pop   | FOOD & BEVERAGE       | (718) 658-1052 | 
| A&J Unisex                 | Jamaica  | 11435   |             | Mom and Pop   | HAIR & NAILS          | (718) 558-4306 | 
| Friendly Uniform & More    | Jamaica  | 11435   |             | Mom and Pop   | APPAREL               |                | 
```