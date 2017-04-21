# Farmers Markets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/farmers-markets) |
| Metadata | [Link](https://data.ct.gov/api/views/qkcc-8trv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qkcc-8trv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qkcc-8trv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qkcc-8trv |
| Name | Farmers Markets |
| Attribution | Department of Agriculutre |
| Tags | farmers, markets, agriculture |
| Created | 2014-03-21T20:15:37Z |
| Publication Date | 2016-11-18T14:06:55Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | fmid        | FMID        | text      | number      |
| Yes      | series tag     | marketname  | MarketName  | text      | text        |
| Yes      | series tag     | website     | Website     | url       | url         |
| Yes      | series tag     | county      | County      | text      | text        |
| No       |                | season1date | Season1Date | text      | text        |
| Yes      | series tag     | season1time | Season1Time | text      | text        |
| No       |                | season2date | Season2Date | text      | text        |
| Yes      | series tag     | season2time | Season2Time | text      | text        |
| No       |                | season3date | Season3Date | text      | text        |
| Yes      | series tag     | season3time | Season3Time | text      | text        |
| No       |                | season4date | Season4Date | text      | text        |
| Yes      | series tag     | season4time | Season4Time | text      | text        |
| No       |                | x           | x           | number    | number      |
| No       |                | y           | y           | number    | number      |
| Yes      | series tag     | location    | Location    | text      | text        |
| Yes      | series tag     | credit      | Credit      | text      | text        |
| Yes      | series tag     | wic         | WIC         | text      | text        |
| Yes      | series tag     | wiccash     | WICcash     | text      | text        |
| Yes      | series tag     | sfmnp       | SFMNP       | text      | text        |
| Yes      | series tag     | snap        | SNAP        | text      | text        |
| Yes      | series tag     | bakedgoods  | Bakedgoods  | text      | text        |
| Yes      | series tag     | cheese      | Cheese      | text      | text        |
| Yes      | series tag     | crafts      | Crafts      | text      | text        |
| Yes      | series tag     | flowers     | Flowers     | text      | text        |
| Yes      | series tag     | eggs        | Eggs        | text      | text        |
| Yes      | series tag     | seafood     | Seafood     | text      | text        |
| Yes      | series tag     | herbs       | Herbs       | text      | text        |
| Yes      | series tag     | vegetables  | Vegetables  | text      | text        |
| Yes      | series tag     | honey       | Honey       | text      | text        |
| Yes      | series tag     | jams        | Jams        | text      | text        |
| Yes      | series tag     | maple       | Maple       | text      | text        |
| Yes      | series tag     | meat        | Meat        | text      | text        |
| Yes      | series tag     | nursery     | Nursery     | text      | text        |
| Yes      | series tag     | nuts        | Nuts        | text      | text        |
| Yes      | series tag     | plants      | Plants      | text      | text        |
| Yes      | series tag     | poultry     | Poultry     | text      | text        |
| Yes      | series tag     | prepared    | Prepared    | text      | text        |
| Yes      | series tag     | soap        | Soap        | text      | text        |
| Yes      | series tag     | trees       | Trees       | text      | text        |
| Yes      | series tag     | wine        | Wine        | text      | text        |
| Yes      | numeric metric | updatetime  | updateTime  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = season1date,season2date,season3date,season4date,x,y
```

## Data Commands

```ls
series e:qkcc-8trv d:2014-03-21T13:15:44.000Z t:poultry=N t:marketname="ASHFORD FARMERS? MARKET" t:herbs=N t:snap=N t:plants=N t:nursery=N t:cheese=N t:honey=N t:crafts=N t:sfmnp=N t:meat=N t:credit=Y t:flowers=N t:fmid=1007501 t:wine=N t:bakedgoods=N t:wic=N t:vegetables=N t:nuts=N t:wiccash=N t:maple=N t:jams=N t:eggs=N t:county=Windham t:seafood=N t:trees=N t:soap=N t:prepared=N m:updatetime=2009

series e:qkcc-8trv d:2014-03-21T13:15:44.000Z t:poultry=N t:marketname="BERLIN FARMERS? MARKET" t:herbs=N t:snap=N t:plants=N t:nursery=N t:cheese=N t:honey=N t:crafts=N t:sfmnp=N t:meat=N t:credit=Y t:flowers=N t:fmid=1007515 t:wine=N t:bakedgoods=N t:wic=N t:vegetables=N t:nuts=N t:wiccash=N t:maple=N t:jams=N t:eggs=N t:county=Hartford t:seafood=N t:trees=N t:soap=N t:prepared=N m:updatetime=40956.59315972222

series e:qkcc-8trv d:2014-03-21T13:15:44.000Z t:poultry=N t:marketname=BethanyFarmersMarket t:herbs=Y t:location="Local government building grounds" t:snap=N t:plants=N t:nursery=Y t:cheese=Y t:honey=Y t:crafts=Y t:sfmnp=Y t:season1time="Sat:9:00 AM - 1:00 PM;" t:meat=N t:credit=Y t:flowers=N t:fmid=1005277 t:wine=N t:bakedgoods=Y t:website=http://www.bethanyfarmersmarket.com t:wic=Y t:vegetables=Y t:nuts=N t:wiccash=N t:maple=Y t:jams=Y t:eggs=Y t:county="New Haven" t:seafood=N t:trees=N t:soap=Y t:prepared=Y m:updatetime=41030.50226851852
```

## Meta Commands

```ls
metric m:updatetime p:double l:updateTime t:dataTypeName=number

entity e:qkcc-8trv l:"Farmers Markets" t:attribution="Department of Agriculutre" t:url=https://data.ct.gov/api/views/qkcc-8trv

property e:qkcc-8trv t:meta.view v:id=qkcc-8trv v:averageRating=0 v:name="Farmers Markets" v:attribution="Department of Agriculutre"

property e:qkcc-8trv t:meta.view.license v:name="Public Domain"

property e:qkcc-8trv t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:qkcc-8trv t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | fmid    | marketname                                  | website                                     | county         | season1date              | season1time            | season2date | season2time | season3date | season3time | season4date | season4time | x                   | y                  | location                          | credit | wic | wiccash | sfmnp | snap | bakedgoods | cheese | crafts | flowers | eggs | seafood | herbs | vegetables | honey | jams | maple | meat | nursery | nuts | plants | poultry | prepared | soap | trees | wine | updatetime         | 
| =========== | ======= | =========================================== | =========================================== | ============== | ======================== | ====================== | =========== | =========== | =========== | =========== | =========== | =========== | =================== | ================== | ================================= | ====== | === | ======= | ===== | ==== | ========== | ====== | ====== | ======= | ==== | ======= | ===== | ========== | ===== | ==== | ===== | ==== | ======= | ==== | ====== | ======= | ======== | ==== | ===== | ==== | ================== | 
| 1395407744  | 1007501 | ASHFORD FARMERS? MARKET                     | [null, null]                                | Windham        |                          |                        |             |             |             |             |             |             | -72.164599999999993 | 41.866300000000003 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2009               | 
| 1395407744  | 1007515 | BERLIN FARMERS? MARKET                      | [null, null]                                | Hartford       |                          |                        |             |             |             |             |             |             | -72.772499999999994 | 41.613900000000001 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 40956.593159722222 | 
| 1395407744  | 1005277 | BethanyFarmersMarket                        | [http://www.bethanyfarmersmarket.com, null] | New Haven      | June to October          | Sat:9:00 AM - 1:00 PM; |             |             |             |             |             |             | -72.991190000000003 | 41.44012           | Local government building grounds | Y      | Y   | N       | Y     | N    | Y          | Y      | Y      | N       | Y    | N       | Y     | Y          | Y     | Y    | Y     | N    | Y       | N    | N      | N       | Y        | Y    | N     | N    | 41030.502268518518 | 
| 1395407744  | 1007462 | Bethel Farmers Market                       | [null, null]                                | Fairfield      |                          |                        |             |             |             |             |             |             | -73.383799999999994 | 41.414900000000003 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2009               | 
| 1395407744  | 1007473 | Bloomfield Farmers Market                   | [null, null]                                | Hartford       |                          |                        |             |             |             |             |             |             | -72.736999999999995 | 41.829900000000002 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2009               | 
| 1395407744  | 1000162 | Bozrah Farmers Market                       | [http://www.bozrahfarmersmarket.org, null]  | New London     | 07/05/2013 to 10/11/2013 | Fri: 4:00 PM-7:00 PM;  |             |             |             |             |             |             | -72.168330999999995 | 41.552173000000003 | Other                             | Y      | Y   | N       | Y     | N    | Y          | Y      | Y      | Y       | Y    | Y       | N     | Y          | Y     | Y    | Y     | Y    | N       | N    | Y      | Y       | Y        | Y    | Y     | N    | 41445.53329861111  | 
| 1395407744  | 1007463 | Bridgeport Farmers Market I                 | [null, null]                                | Fairfield      |                          |                        |             |             |             |             |             |             | -73.2               | 41.176499999999997 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2009               | 
| 1395407744  | 1007502 | Bristol - Housing Authority Farmers? Market | [null, null]                                | Hartford       |                          |                        |             |             |             |             |             |             | -72.927300000000002 | 41.694000000000003 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2011               | 
| 1395407744  | 1007474 | Bristol Farmers Market                      | [null, null]                                | Hartford       |                          |                        |             |             |             |             |             |             | -72.945300000000003 | 41.673000000000002 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2009               | 
| 1395407744  | 1007767 | Brooklyn FM                                 | [http://www.nectfarmersmarket.org, null]    | Windham County |                          |                        |             |             |             |             |             |             | -71.95              | 41.788200000000003 |                                   | Y      | N   | N       | N     | N    | N          | N      | N      | N       | N    | N       | N     | N          | N     | N    | N     | N    | N       | N    | N      | N       | N        | N    | N     | N    | 2011               | 
```