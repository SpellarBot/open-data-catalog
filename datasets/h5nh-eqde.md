# Columbus Avenue BID Businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/columbus-avenue-bid-businesses-4c7fd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h5nh-eqde) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h5nh-eqde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h5nh-eqde/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h5nh-eqde |
| Name | Columbus Avenue BID Businesses |
| Attribution | Columbus Avenue BID |
| Category | Business |
| Tags | columbus avenue, business improvement district, bid, merchant, merchandise, shop, shopping, business, sales, food, coffee, tea, shoes, services, hotels, entertainment, children?s store, clothing, ... |
| Created | 2011-09-09T20:29:29Z |
| Publication Date | 2013-06-21T19:29:27Z |

## Description

A listing of all the shops in the Columbus Avenue Business Improvement District (BID) which runs along Columbus Avenue from  W 82nd St to W 67th (only to 68th on the west side of the street).
Update Frequency: As needed

## Columns

```ls
| Included | Schema Type | Field Name            | Name                    | Data Type | Render Type |
| ======== | =========== | ===================== | ======================= | ========= | =========== |
| No       | time        | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | shop_name             | Shop Name               | text      | text        |
| Yes      | series tag  | telephone             | Telephone               | text      | text        |
| Yes      | series tag  | store_type_category_1 | Store Type (category 1) | text      | text        |
| Yes      | series tag  | store_type_category_2 | Store Type (category 2) | text      | text        |
| Yes      | series tag  | store_type_category_3 | Store Type (category 3) | text      | text        |
| Yes      | series tag  | website               | website                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h5nh-eqde d:2011-09-09T13:29:31.000Z t:website=new.lincolncenter.org/ t:telephone=212.875.5456 t:store_type_category_1="Museums & Cultural Institutions" t:shop_name="Lincoln Center for the Preforming Arts" m:row_number.h5nh-eqde=1

series e:h5nh-eqde d:2011-09-09T13:29:33.000Z t:website=www.aerosoles.com t:telephone="212 579-8659" t:store_type_category_1="Clothing Shops, Shoes & Accessories" t:shop_name=Aerosoles m:row_number.h5nh-eqde=2

series e:h5nh-eqde d:2011-09-09T13:29:33.000Z t:telephone="212 769-0368" t:store_type_category_1="Clothing Shops, Shoes & Accessories" t:shop_name="A Tempo" m:row_number.h5nh-eqde=3
```

## Meta Commands

```ls
metric m:row_number.h5nh-eqde p:long l:"Row Number"

entity e:h5nh-eqde l:"Columbus Avenue BID Businesses" t:attribution="Columbus Avenue BID" t:url=https://data.cityofnewyork.us/api/views/h5nh-eqde

property e:h5nh-eqde t:meta.view v:id=h5nh-eqde v:category=Business v:averageRating=0 v:name="Columbus Avenue BID Businesses" v:attribution="Columbus Avenue BID"

property e:h5nh-eqde t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h5nh-eqde t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | shop_name                              | telephone    | store_type_category_1               | store_type_category_2 | store_type_category_3 | website                       | 
| =========== | ====================================== | ============ | =================================== | ===================== | ===================== | ============================= | 
| 1315574971  | Lincoln Center for the Preforming Arts | 212.875.5456 | Museums & Cultural Institutions     |                       |                       | new.lincolncenter.org/        | 
| 1315574973  | Aerosoles                              | 212 579-8659 | Clothing Shops, Shoes & Accessories |                       |                       | www.aerosoles.com             | 
| 1315574973  | A Tempo                                | 212 769-0368 | Clothing Shops, Shoes & Accessories |                       |                       |                               | 
| 1315574973  | Artiste Jewelers                       | 212 877-3320 | Clothing Shops, Shoes & Accessories |                       |                       |                               | 
| 1315574973  | AG Adriano Goldschmied                 | 212 496-5692 | Clothing Shops, Shoes & Accessories |                       |                       | www.agjeans.com               | 
| 1315574973  | Brief Encounters                       | 212 496-5649 | Clothing Shops, Shoes & Accessories |                       |                       |                               | 
| 1315574973  | Berkley Girl                           | 212 877-4770 | Clothing Shops, Shoes & Accessories | Childrens Stores      |                       | www.berkleygirl.com           | 
| 1315574973  | Alskling                               | 212 787-7066 | Clothing Shops, Shoes & Accessories |                       |                       |                               | 
| 1315574973  | Bit'z Kids                             | 212 724-1415 | Clothing Shops, Shoes & Accessories | Childrens Stores      |                       | www.bitzkidsnyc.com           | 
| 1315574973  | Comptoirs des Cotonniers               | 212 874-0983 | Clothing Shops, Shoes & Accessories |                       |                       | www.mothers-and-daughters.com | 
```