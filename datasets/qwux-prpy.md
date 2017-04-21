# "Clear" Gasoline locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/clear-gasoline-locations-c0249) |
| Metadata | [Link](https://data.oregon.gov/api/views/qwux-prpy) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qwux-prpy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qwux-prpy/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qwux-prpy |
| Name | "Clear" Gasoline locations |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | gas, marina, e-10, ethanol, fuel, fueling, clear, gasoline, non-ethanol |
| Created | 2011-09-26T17:16:20Z |
| Publication Date | 2017-03-17T18:23:23Z |

## Description

Where to buy clear gasoline in Oregon.  "Clear" gasoline is defined as a non-ethanol blended gas, generally produced with 91 octane and sold asa  premium blend.  Clear gasoline is a much better fuel for boats, ATV's, 1990 era and earlier car models, chainsaws, and yard equipment because of the rubber hoses, fuel lines, gaskets, etc. that can easily deteriorate with the use of ethanol-blended fuel.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | name               | NAME               | text      | text        |
| No       |             | address            | ADDRESS            | text      | text        |
| Yes      | series tag  | city               | CITY               | text      | text        |
| Yes      | series tag  | zipcode            | ZIPCODE            | text      | text        |
| Yes      | series tag  | phone              | PHONE              | phone     | phone       |
| Yes      | series tag  | county             | COUNTY             | text      | text        |
| Yes      | series tag  | type               | TYPE               | text      | text        |
| Yes      | series tag  | purchasing_options | PURCHASING OPTIONS | text      | text        |
| Yes      | series tag  | web                | WEB                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:qwux-prpy d:2011-07-13T13:14:25.000Z t:phone_number="(541) 347-1901" t:county=Coos t:purchasing_options="fuel dock" t:zipcode=97411 t:name="Port of Bandon" t:web=http://www.portofbandon.com/marina.htm t:type=retailer t:city=Bandon m:row_number.qwux-prpy=1

series e:qwux-prpy d:2011-07-13T13:08:54.000Z t:phone_number=N/A t:county=Jackson t:purchasing_options="cardlock with pacific pride 24 hours" t:zipcode=97501 t:name="N. Medford Pacific Pride" t:type=wholesaler t:city=Medford m:row_number.qwux-prpy=2

series e:qwux-prpy d:2011-07-13T13:42:24.000Z t:phone_number="(541) 383-2652" t:county=Deschutes t:zipcode=97701 t:name="Red Carpet Car Wash" t:type=retailer t:city=Bend m:row_number.qwux-prpy=3
```

## Meta Commands

```ls
metric m:row_number.qwux-prpy p:long l:"Row Number"

entity e:qwux-prpy l:"""Clear"" Gasoline locations" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/qwux-prpy

property e:qwux-prpy t:meta.view v:id=qwux-prpy v:category=Recreation v:attributionLink=http://www.boatoregon.com/ v:averageRating=0 v:name="""Clear"" Gasoline locations" v:attribution="Oregon State Marine Board"

property e:qwux-prpy t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:qwux-prpy t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | name                                 | address                 | city       | zipcode | phone                  | county     | type                    | purchasing_options                   | web                                             | 
| =========== | ==================================== | ======================= | ========== | ======= | ====================== | ========== | ======================= | ==================================== | =============================================== | 
| 1310562865  | Port of Bandon                       | High Dock, First St. Se | Bandon     | 97411   | [(541) 347-1901, null] | Coos       | retailer                | fuel dock                            | [http://www.portofbandon.com/marina.htm, null]  | 
| 1310562534  | N. Medford Pacific Pride             | 3680 N Pacific Hwy      | Medford    | 97501   | [N/A, null]            | Jackson    | wholesaler              | cardlock with pacific pride 24 hours | [null, null]                                    | 
| 1310564544  | Red Carpet Car Wash                  | 1144 NE 3rd             | Bend       | 97701   | [(541) 383-2652, null] | Deschutes  | retailer                |                                      | [null, null]                                    | 
| 1310564458  | Port of Brookings                    | 16408 Lower Harbor Rd   | Brookings  | 97415   | [(541) 469-2218, null] | Curry      | retailer                |                                      | [http://www.port-brookings-harbor.org, null]    | 
| 1310565237  | Triangle Farm Supply Inc.            | 2500 Cedar St           | Baker City | 97814   | [(541) 523-3336, null] | Baker      | wholesaler/ distributor |                                      | [null, null]                                    | 
| 1310562847  | Port Of Astoria                      | 10 Pier1, Suite 102     | Astoria    | 97103   | [(503) 325-8279, null] | Clatsop    | retailer                |                                      | [http://www.portofastoria.com/index.html, null] | 
| 1310562855  | Port Of Astoria Moor Basin           | 352 Industry            | Astoria    | 97103   | [(503) 325-8278, null] | Clatsop    | retailer                | fuel dock                            | [http://www.portofastoria.com/index.html, null] | 
| 1317028633  | Carson Oil Company Inc. - Hood River | 2660 Dock Rd            | Hood River | 97031   | [(503) 471-4305, null] | Hood River | retailer                |                                      | [http://www.carsonoil.com, null]                | 
| 1317028641  | Vanwormer Service                    | 94244 Kerber St         | Langlois   | 97450   | [(541) 348-2431, null] | Curry      | retailer                |                                      | [null, null]                                    | 
| 1317028728  | Wamic Store Inc                      | 57016 Wamic Mkt Rd      | Wamic      | 97063   | [(541) 544-2333, null] | Wasco      | retailer                |                                      | [null, null]                                    | 
```