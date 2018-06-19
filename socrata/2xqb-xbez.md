# SNAP (Supplemental Nutrition Assistance Program) Authorized Retailers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snap-supplemental-nutrition-assistance-program-authorized-retailers) |
| Metadata | [Link](https://data.ct.gov/api/views/2xqb-xbez) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2xqb-xbez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2xqb-xbez/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2xqb-xbez |
| Name | SNAP (Supplemental Nutrition Assistance Program) Authorized Retailers |
| Attribution | U.S. Dept.of Agriculture Food and Nutrition Service |
| Category | Health and Human Services |
| Tags | snap, food, benefits, ebt |
| Created | 2015-06-23T18:42:18Z |
| Publication Date | 2017-03-29T17:50:15Z |

## Description

A listing of retailers in Conneticut authorized to accept SNAP EBT benefits. The Supplemental Nutrition Assistance Program (SNAP), formerly known as Food Stamps, helps eligible individuals and families afford the cost of food at supermarkets, grocery stores and farmers? markets.

## Columns

```ls
| Included | Schema Type | Field Name     | Name            | Data Type | Render Type |
| ======== | =========== | ============== | =============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | store_name     | Store_Name      | text      | text        |
| No       |             | address        | Address         | text      | text        |
| Yes      | series tag  | city           | City            | text      | text        |
| No       |             | address_line_2 | Address Line #2 | text      | text        |
| Yes      | series tag  | state          | State           | text      | text        |
| Yes      | series tag  | zip5           | Zip             | text      | number      |
| Yes      | series tag  | zip4           | Zip4            | text      | number      |
| No       |             | longitude      | Longitude       | number    | number      |
| No       |             | latitude       | Latitude        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_line_2,longitude,latitude
```

## Data Commands

```ls
series e:2xqb-xbez d:2017-03-29T17:49:38.000Z t:zip5=6513 t:zip4=1007 t:state=CT t:store_name="S B MART Convenience Store" t:city="New Haven" m:row_number.2xqb-xbez=1

series e:2xqb-xbez d:2017-03-29T17:49:38.000Z t:zip5=6112 t:zip4=2198 t:state=CT t:store_name="Rite Aid 3203" t:city=Hartford m:row_number.2xqb-xbez=2

series e:2xqb-xbez d:2017-03-29T17:49:38.000Z t:zip5=6112 t:zip4=1208 t:state=CT t:store_name="Collado Food Market" t:city=Hartford m:row_number.2xqb-xbez=3
```

## Meta Commands

```ls
metric m:row_number.2xqb-xbez p:long l:"Row Number"

entity e:2xqb-xbez l:"SNAP (Supplemental Nutrition Assistance Program) Authorized Retailers" t:attribution="U.S. Dept.of Agriculture Food and Nutrition Service" t:url=https://data.ct.gov/api/views/2xqb-xbez

property e:2xqb-xbez t:meta.view v:id=2xqb-xbez v:category="Health and Human Services" v:attributionLink=http://www.fns.usda.gov/snap/retailerlocator v:averageRating=0 v:name="SNAP (Supplemental Nutrition Assistance Program) Authorized Retailers" v:attribution="U.S. Dept.of Agriculture Food and Nutrition Service"

property e:2xqb-xbez t:meta.view.license v:name="Public Domain"

property e:2xqb-xbez t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:2xqb-xbez t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | store_name                   | address            | city        | address_line_2           | state | zip5 | zip4 | longitude  | latitude  | 
| =========== | ============================ | ================== | =========== | ======================== | ===== | ==== | ==== | ========== | ========= | 
| 1490809778  | S B MART Convenience Store   | 411 Middletown Ave | New Haven   |                          | CT    | 6513 | 1007 | -72.878052 | 41.328117 | 
| 1490809778  | Rite Aid 3203                | 1291 Albany Ave    | Hartford    |                          | CT    | 6112 | 2198 | -72.698181 | 41.782837 | 
| 1490809778  | Collado Food Market          | 655 Blue Hills Ave | Hartford    |                          | CT    | 6112 | 1208 | -72.695595 | 41.805309 | 
| 1490809778  | PRICE CHOPPER 205            | 35 Talcottville Rd | Vernon      | Tri City Shopping Center | CT    | 6066 | 5261 | -72.497017 | 41.826569 | 
| 1490809778  | 7 - Eleven Food Store 19960  | 276 S Main St      | New Britain |                          | CT    | 6051 | 3531 | -72.777023 | 41.657104 | 
| 1490809778  | Brook Market                 | 139 Brook St       | Hartford    |                          | CT    | 6120 | 2501 | -72.682877 | 41.779781 | 
| 1490809778  | TURNPIKE BP, Inc.            | 750 1st Ave        | West Haven  |                          | CT    | 6516 | 2711 | -72.952057 | 41.284569 | 
| 1490809778  | Three Corners Grocery        | 453 Huntington St  | New Haven   |                          | CT    | 6511 | 1108 | -72.928879 | 41.332214 | 
| 1490809778  | Deangely Market              | 362 Oakville Ave   | Waterbury   |                          | CT    | 6708 | 1228 | -73.081757 | 41.580196 | 
| 1490809778  | Quick Stop Convenience Store | 916 Stafford Ave   | Bristol     |                          | CT    | 6010 | 3858 | -72.910652 | 41.701603 | 
```