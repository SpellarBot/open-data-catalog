# Iowa Liquor Products

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-liquor-products) |
| Metadata | [Link](https://data.iowa.gov/api/views/gckp-fe7r) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/gckp-fe7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/gckp-fe7r/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | gckp-fe7r |
| Name | Iowa Liquor Products |
| Attribution | Iowa Department of Commerce, Alcoholic Beverages Division |
| Category | Economy |
| Tags | liquor, alcohol, products |
| Created | 2014-12-19T21:45:13Z |
| Publication Date | 2015-12-08T15:48:28Z |

## Description

This dataset provides a list of liquor products.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | itemno              | Item Number         | text          | text          |
| Yes      | series tag     | category_name       | Category Name       | text          | text          |
| Yes      | series tag     | im_desc             | Item Description    | text          | text          |
| Yes      | series tag     | vendor_no           | Vendor              | text          | text          |
| Yes      | series tag     | vendor_name         | Vendor Name         | text          | text          |
| Yes      | numeric metric | bottle_volume_ml    | Bottle Volume (ml)  | number        | number        |
| Yes      | numeric metric | pack                | Pack                | number        | number        |
| Yes      | numeric metric | innerpack           | Inner Pack          | number        | number        |
| Yes      | numeric metric | age                 | Age                 | number        | text          |
| Yes      | numeric metric | proof               | Proof               | number        | number        |
| Yes      | time           | listdate            | List Date           | calendar_date | calendar_date |
| Yes      | series tag     | upc                 | UPC                 | text          | number        |
| Yes      | numeric metric | scc                 | SCC                 | number        | number        |
| Yes      | numeric metric | state_bottle_cost   | State Bottle Cost   | money         | money         |
| Yes      | numeric metric | state_case_cost     | State Case Cost     | money         | money         |
| Yes      | numeric metric | state_bottle_retail | State Bottle Retail | money         | money         |
| No       |                | date                | Report Date         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = listdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:gckp-fe7r d:2016-06-01T00:00:00.000Z t:category_name="Iowa Distilleries" t:im_desc=Rumcoqui t:itemno=80447 t:upc=40232125720 t:vendor_name="Rumcoqui and Co" t:vendor_no=216 m:scc=10855037005071 m:state_bottle_cost=10 m:state_case_cost=60 m:age=0 m:bottle_volume_ml=750 m:proof=30 m:innerpack=1 m:pack=6 m:state_bottle_retail=15

series e:gckp-fe7r d:2015-06-01T00:00:00.000Z t:category_name="Iowa Distilleries" t:im_desc="Canadian Ltd" t:itemno=12409 t:upc=82928223501 t:vendor_name="SAZERAC NORTH AMERICA" t:vendor_no=055 m:scc=10720815920108 m:state_bottle_cost=0.89 m:state_case_cost=42.72 m:age=0 m:bottle_volume_ml=100 m:proof=80 m:innerpack=1 m:pack=48 m:state_bottle_retail=1.34

series e:gckp-fe7r d:2010-08-01T00:00:00.000Z t:category_name="Iowa Distilleries" t:im_desc="Cedar Ridge Bourbon" t:itemno=17206 t:upc=87236565374 t:vendor_name="CEDAR RIDGE VINEYARDS LL" t:vendor_no=125 m:scc=10059824001806 m:state_bottle_cost=18.1 m:state_case_cost=108.6 m:age=0 m:bottle_volume_ml=750 m:proof=80 m:innerpack=1 m:pack=6 m:state_bottle_retail=27.15
```

## Meta Commands

```ls
metric m:bottle_volume_ml p:integer l:"Bottle Volume (ml)" d:"Volume of individual liquor bottles in milliliters." t:dataTypeName=number

metric m:pack p:integer l:Pack d:"The number of bottles in a case" t:dataTypeName=number

metric m:innerpack p:integer l:"Inner Pack" t:dataTypeName=number

metric m:age p:integer l:Age t:dataTypeName=number

metric m:proof p:integer l:Proof t:dataTypeName=number

metric m:scc p:long l:SCC t:dataTypeName=number

metric m:state_bottle_cost p:double l:"State Bottle Cost" d:"The amount that Alcoholic Beverages Division paid for each bottle" t:dataTypeName=money

metric m:state_case_cost p:double l:"State Case Cost" d:"The amount that Alcoholic Beverages Division paid for each case" t:dataTypeName=money

metric m:state_bottle_retail p:double l:"State Bottle Retail" d:"The purchase price for stores ordering the product" t:dataTypeName=money

entity e:gckp-fe7r l:"Iowa Liquor Products" t:attribution="Iowa Department of Commerce, Alcoholic Beverages Division" t:url=https://data.iowa.gov/api/views/gckp-fe7r

property e:gckp-fe7r t:meta.view v:id=gckp-fe7r v:category=Economy v:averageRating=0 v:name="Iowa Liquor Products" v:attribution="Iowa Department of Commerce, Alcoholic Beverages Division"

property e:gckp-fe7r t:meta.view.license v:name="Public Domain"

property e:gckp-fe7r t:meta.view.owner v:id=nj4v-jwef v:profileImageUrlMedium=/api/users/nj4v-jwef/profile_images/THUMB v:profileImageUrlLarge=/api/users/nj4v-jwef/profile_images/LARGE v:screenName="Alcoholic Beverages Division (Commerce)" v:profileImageUrlSmall=/api/users/nj4v-jwef/profile_images/TINY v:displayName="Alcoholic Beverages Division (Commerce)"

property e:gckp-fe7r t:meta.view.tableauthor v:id=nj4v-jwef v:profileImageUrlMedium=/api/users/nj4v-jwef/profile_images/THUMB v:profileImageUrlLarge=/api/users/nj4v-jwef/profile_images/LARGE v:screenName="Alcoholic Beverages Division (Commerce)" v:profileImageUrlSmall=/api/users/nj4v-jwef/profile_images/TINY v:roleName=editor v:displayName="Alcoholic Beverages Division (Commerce)"
```

## Top Records

```ls
| itemno | category_name     | im_desc                                | vendor_no | vendor_name              | bottle_volume_ml | pack | innerpack | age | proof | listdate            | upc          | scc            | state_bottle_cost | state_case_cost | state_bottle_retail | date                | 
| ====== | ================= | ====================================== | ========= | ======================== | ================ | ==== | ========= | === | ===== | =================== | ============ | ============== | ================= | =============== | =================== | =================== | 
| 80447  | Iowa Distilleries | Rumcoqui                               | 216       | Rumcoqui and Co          | 750              | 6    | 1         | 0   | 30    | 2016-06-01T00:00:00 | 40232125720  | 10855037005071 | 10                | 60              | 15                  | 2017-04-01T00:00:00 | 
| 12409  | Iowa Distilleries | Canadian Ltd                           | 055       | SAZERAC NORTH AMERICA    | 100              | 48   | 1         | 0   | 80    | 2015-06-01T00:00:00 | 82928223501  | 10720815920108 | 0.89              | 42.72           | 1.34                | 2017-04-01T00:00:00 | 
| 17206  | Iowa Distilleries | Cedar Ridge Bourbon                    | 125       | CEDAR RIDGE VINEYARDS LL | 750              | 6    | 1         | 0   | 80    | 2010-08-01T00:00:00 | 87236565374  | 10059824001806 | 18.1              | 108.6           | 27.15               | 2017-04-01T00:00:00 | 
| 27014  | Iowa Distilleries | Cedar Ridge Malted Rye                 | 125       | CEDAR RIDGE VINEYARDS LL | 750              | 6    | 1         | 2   | 86    | 2014-09-01T00:00:00 | 13964820294  | 10059824001134 | 19.67             | 118             | 29.51               | 2017-04-01T00:00:00 | 
| 27027  | Iowa Distilleries | Cody Road Rye                          | 306       | MISSISSIPPI RIVER DISTIL | 750              | 6    | 1         | 0   | 80    | 2012-10-01T00:00:00 | 22099147794  | 10059824001134 | 19.17             | 115             | 28.76               | 2017-04-01T00:00:00 | 
| 100083 | Iowa Distilleries | SWELL Vodka - Mary Me Bloody Mary Pack | 195       | Swell Liquor LLC         | 750              | 6    | 1         | 0   | 80    | 2016-10-01T00:00:00 | 854781004548 | 10854781004040 | 12.38             | 74.28           | 18.57               | 2017-04-01T00:00:00 | 
| 27102  | Iowa Distilleries | Templeton Rye                          | 255       | WILSON DANIELS LTD       | 750              | 6    | 1         | 0   | 80    | 2006-11-01T00:00:00 | 40232301810  | 10720815920108 | 18.09             | 108.54          | 27.14               | 2017-04-01T00:00:00 | 
| 27125  | Iowa Distilleries | Templeton 6YR Rye                      | 255       | WILSON DANIELS LTD       | 750              | 6    | 1         | 6   | 92    | 2016-07-01T00:00:00 | 40232301810  | 10720815920238 | 22.75             | 136.5           | 34.13               | 2017-04-01T00:00:00 | 
| 27138  | Iowa Distilleries | Cody Road Single Barrel Rye            | 306       | MISSISSIPPI RIVER DISTIL | 750              | 6    | 1         | 0   | 92    | 2016-09-01T00:00:00 | 855037005104 | 10720815920238 | 25                | 150             | 37.5                | 2017-04-01T00:00:00 | 
| 27246  | Iowa Distilleries | Artisan Grain Original Moonshine       | 101       | ARTISAN GRAIN DISTILLERY | 750              | 6    | 1         | 0   | 92    | 2015-02-01T00:00:00 | 855037005104 | 868887000007   | 12.67             | 76              | 19.01               | 2017-04-01T00:00:00 | 
```