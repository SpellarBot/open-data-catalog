# Transportation Fuels Inventory: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-fuels-inventory-beginning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/7rev-x3j5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7rev-x3j5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7rev-x3j5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7rev-x3j5 |
| Name | Transportation Fuels Inventory: Beginning 2004 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | inventories, gasoline, ethanol, diesel, crude oil |
| Created | 2014-08-27T20:49:45Z |
| Publication Date | 2017-04-07T22:02:36Z |

## Description

The Transportation Fuels Inventory dataset contains weekly stock amounts of  Central Atlantic diesel as well as gasoline from the Central Atlantic region (PADD 1B), East Coast (PADD 1) and the total U.S.  The dataset also contains fuel ethanol stocks for the East Coast and U.S. crude oil stocks. The data is collected on a weekly basis and measured in terms of thousands of barrels beginning in April 2004.

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                              | Data Type     | Render Type   |
| ======== | ============== | =============================================== | ================================================= | ============= | ============= |
| Yes      | time           | date                                            | Date                                              | calendar_date | calendar_date |
| Yes      | numeric metric | mid_atlantic_uls_diesel_stocks_thousand_barrels | Mid-Atlantic ULS Diesel Stocks (Thousand Barrels) | number        | number        |
| Yes      | numeric metric | mid_atlantic_gasoline_stocks_thousand_barrels   | Mid-Atlantic Gasoline Stocks (Thousand Barrels)   | number        | number        |
| Yes      | numeric metric | east_coast_gasoline_stocks_thousand_barrels     | East Coast Gasoline Stocks (Thousand Barrels)     | number        | number        |
| Yes      | numeric metric | east_coast_ethanol_stocks_thousand_barrels      | East Coast Ethanol Stocks (Thousand Barrels)      | number        | number        |
| Yes      | numeric metric | u_s_gasoline_stocks_thousand_barrels            | U.S. Gasoline Stocks (Thousand Barrels)           | number        | number        |
| Yes      | numeric metric | u_s_crude_oil_stocks_thousand_barrels           | U.S. Crude Oil Stocks (Thousand Barrels)          | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7rev-x3j5 d:2017-03-31T00:00:00.000Z m:east_coast_gasoline_stocks_thousand_barrels=65929 m:u_s_crude_oil_stocks_thousand_barrels=535543 m:mid_atlantic_uls_diesel_stocks_thousand_barrels=28807 m:mid_atlantic_gasoline_stocks_thousand_barrels=35256 m:east_coast_ethanol_stocks_thousand_barrels=8183 m:u_s_gasoline_stocks_thousand_barrels=239103

series e:7rev-x3j5 d:2017-03-24T00:00:00.000Z m:east_coast_gasoline_stocks_thousand_barrels=65648 m:u_s_crude_oil_stocks_thousand_barrels=533977 m:mid_atlantic_uls_diesel_stocks_thousand_barrels=29523 m:mid_atlantic_gasoline_stocks_thousand_barrels=35803 m:east_coast_ethanol_stocks_thousand_barrels=8028 m:u_s_gasoline_stocks_thousand_barrels=239721

series e:7rev-x3j5 d:2017-03-17T00:00:00.000Z m:east_coast_gasoline_stocks_thousand_barrels=68184 m:u_s_crude_oil_stocks_thousand_barrels=533110 m:mid_atlantic_uls_diesel_stocks_thousand_barrels=30055 m:mid_atlantic_gasoline_stocks_thousand_barrels=36189 m:east_coast_ethanol_stocks_thousand_barrels=7567 m:u_s_gasoline_stocks_thousand_barrels=243468
```

## Meta Commands

```ls
metric m:mid_atlantic_uls_diesel_stocks_thousand_barrels p:integer l:"Mid-Atlantic ULS Diesel Stocks (Thousand Barrels)" d:"Weekly Central Atlantic (PADD 1B) stocks of 0-15 ppm Sulfur Distillate. (Thousand Barrels)" t:dataTypeName=number

metric m:mid_atlantic_gasoline_stocks_thousand_barrels p:integer l:"Mid-Atlantic Gasoline Stocks (Thousand Barrels)" d:"Weekly Central Atlantic (PADD 1B) ending stocks of total gasoline (includes finished motor gasoline and motor gasoline blending components). (Thousand Barrels)" t:dataTypeName=number

metric m:east_coast_gasoline_stocks_thousand_barrels p:integer l:"East Coast Gasoline Stocks (Thousand Barrels)" d:"Weekly East Coast (PADD 1) ending stocks of total gasoline (includes finished motor gasoline and motor gasoline blending components). (Thousand Barrels)" t:dataTypeName=number

metric m:east_coast_ethanol_stocks_thousand_barrels p:integer l:"East Coast Ethanol Stocks (Thousand Barrels)" d:"Weekly East Coast (PADD 1) ending stocks of fuel ethanol. (Thousand Barrels)" t:dataTypeName=number

metric m:u_s_gasoline_stocks_thousand_barrels p:integer l:"U.S. Gasoline Stocks (Thousand Barrels)" d:"Weekly U.S. stocks of total gasoline (includes finished motor gasoline and motor gasoline blending components). (Thousand Barrels)" t:dataTypeName=number

metric m:u_s_crude_oil_stocks_thousand_barrels p:integer l:"U.S. Crude Oil Stocks (Thousand Barrels)" d:"Weekly U.S. stocks of crude oil excluding SPR stocks. (Thousand Barrels)" t:dataTypeName=number

entity e:7rev-x3j5 l:"Transportation Fuels Inventory: Beginning 2004" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/7rev-x3j5

property e:7rev-x3j5 t:meta.view v:id=7rev-x3j5 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Data-and-Prices-Planning-and-Policy/Energy-Prices-Data-and-Reports/EA-Reports-and-Studies/Weekly-Transportation-Fuels-Report.aspx v:averageRating=0 v:name="Transportation Fuels Inventory: Beginning 2004" v:attribution="New York State Energy Research and Development Authority"

property e:7rev-x3j5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7rev-x3j5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | mid_atlantic_uls_diesel_stocks_thousand_barrels | mid_atlantic_gasoline_stocks_thousand_barrels | east_coast_gasoline_stocks_thousand_barrels | east_coast_ethanol_stocks_thousand_barrels | u_s_gasoline_stocks_thousand_barrels | u_s_crude_oil_stocks_thousand_barrels | 
| =================== | =============================================== | ============================================= | =========================================== | ========================================== | ==================================== | ===================================== | 
| 2017-03-31T00:00:00 | 28807                                           | 35256                                         | 65929                                       | 8183                                       | 239103                               | 535543                                | 
| 2017-03-24T00:00:00 | 29523                                           | 35803                                         | 65648                                       | 8028                                       | 239721                               | 533977                                | 
| 2017-03-17T00:00:00 | 30055                                           | 36189                                         | 68184                                       | 7567                                       | 243468                               | 533110                                | 
| 2017-03-10T00:00:00 | 31365                                           | 38464                                         | 69442                                       | 7788                                       | 246279                               | 528156                                | 
| 2017-03-03T00:00:00 | 31997                                           | 39313                                         | 71217                                       | 7806                                       | 249334                               | 528393                                | 
| 2017-02-24T00:00:00 | 32545                                           | 40270                                         | 75041                                       | 7815                                       | 255889                               | 520184                                | 
| 2017-02-17T00:00:00 | 32754                                           | 41410                                         | 75488                                       | 7895                                       | 256435                               | 518683                                | 
| 2017-02-10T00:00:00 | 33399                                           | 42343                                         | 76285                                       | 7675                                       | 259063                               | 518119                                | 
| 2017-02-03T00:00:00 | 35024                                           | 40101                                         | 73845                                       | 7678                                       | 256217                               | 508592                                | 
| 2017-01-27T00:00:00 | 35961                                           | 39686                                         | 73540                                       | 7571                                       | 257086                               | 494762                                | 
```