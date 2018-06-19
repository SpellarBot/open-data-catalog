# Iowa Liquor Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-liquor-sales) |
| Metadata | [Link](https://data.iowa.gov/api/views/m3tr-qhgy) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/m3tr-qhgy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/m3tr-qhgy/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | m3tr-qhgy |
| Name | Iowa Liquor Sales |
| Attribution | Iowa Department of Commerce, Alcoholic Beverages Division |
| Category | Economy |
| Tags | liquor sales, spirit sales, store sales, liquor licensees |
| Created | 2014-11-07T18:19:41Z |
| Publication Date | 2015-12-30T20:11:32Z |

## Description

This dataset contains the spirits purchase information of Iowa Class ?E? liquor licensees by product and date of purchase from January 1, 2012 to current.  The dataset can be used to analyze total spirits sales in Iowa of individual products at the store level.

Class E liquor license, for grocery stores, liquor stores, convenience stores, etc., allows commercial establishments to sell liquor for off-premises consumption in original unopened containers.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type     | Render Type   |
| ======== | ============== | =================== | ===================== | ============= | ============= |
| Yes      | series tag     | invoice_line_no     | Invoice/Item Number   | text          | text          |
| Yes      | time           | date                | Date                  | calendar_date | calendar_date |
| Yes      | series tag     | store               | Store Number          | text          | text          |
| Yes      | series tag     | name                | Store Name            | text          | text          |
| No       |                | address             | Address               | text          | text          |
| Yes      | series tag     | city                | City                  | text          | text          |
| Yes      | series tag     | zipcode             | Zip Code              | text          | text          |
| Yes      | series tag     | county_number       | County Number         | text          | text          |
| Yes      | series tag     | county              | County                | text          | text          |
| Yes      | numeric metric | category            | Category              | number        | text          |
| Yes      | series tag     | category_name       | Category Name         | text          | text          |
| Yes      | series tag     | vendor_no           | Vendor Number         | text          | text          |
| Yes      | series tag     | vendor_name         | Vendor Name           | text          | text          |
| Yes      | series tag     | itemno              | Item Number           | text          | text          |
| Yes      | series tag     | im_desc             | Item Description      | text          | text          |
| Yes      | numeric metric | pack                | Pack                  | number        | number        |
| Yes      | numeric metric | bottle_volume_ml    | Bottle Volume (ml)    | number        | number        |
| Yes      | numeric metric | state_bottle_cost   | State Bottle Cost     | money         | money         |
| Yes      | numeric metric | state_bottle_retail | State Bottle Retail   | money         | money         |
| Yes      | numeric metric | sale_bottles        | Bottles Sold          | number        | number        |
| Yes      | numeric metric | sale_dollars        | Sale (Dollars)        | money         | money         |
| Yes      | numeric metric | sale_liters         | Volume Sold (Liters)  | number        | number        |
| Yes      | numeric metric | sale_gallons        | Volume Sold (Gallons) | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:m3tr-qhgy d:2015-11-20T00:00:00.000Z t:im_desc="Templeton Rye w/Flask" t:store=2191 t:county_number=56 t:county=Lee t:name="Keokuk Spirits" t:zipcode=52632 t:itemno=297 t:invoice_line_no=S29198800001 t:vendor_name="Wilson Daniels Ltd." t:vendor_no=255 t:city=KEOKUK m:sale_bottles=6 m:sale_gallons=1.18877423561 m:state_bottle_cost=18.09 m:sale_liters=4.5 m:sale_dollars=162.84 m:bottle_volume_ml=750 m:pack=6 m:state_bottle_retail=27.14

series e:m3tr-qhgy d:2015-11-21T00:00:00.000Z t:im_desc="Templeton Rye w/Flask" t:store=2205 t:county_number=73 t:county=Page t:name="Ding's Honk And Holler" t:zipcode=51632 t:itemno=297 t:invoice_line_no=S29195400002 t:vendor_name="Wilson Daniels Ltd." t:vendor_no=255 t:city=CLARINDA m:sale_bottles=12 m:sale_gallons=2.37754847122 m:state_bottle_cost=18.09 m:sale_liters=9 m:sale_dollars=325.68 m:bottle_volume_ml=750 m:pack=6 m:state_bottle_retail=27.14

series e:m3tr-qhgy d:2015-11-16T00:00:00.000Z t:im_desc="Disaronno Amaretto Cavalli Mignon 3-50ml Pack" t:store=3549 t:county_number=56 t:county=Lee t:name="Quicker Liquor Store" t:zipcode=52627 t:itemno=249 t:invoice_line_no=S29050300001 t:vendor_name="Disaronno International LLC" t:vendor_no=130 t:city="FORT MADISON" m:sale_bottles=2 m:sale_gallons=0.0792516157 m:state_bottle_cost=6.4 m:sale_liters=0.3 m:sale_dollars=19.2 m:bottle_volume_ml=150 m:pack=20 m:state_bottle_retail=9.6
```

## Meta Commands

```ls
metric m:category p:integer l:Category d:"Category code associated with the liquor ordered" t:dataTypeName=number

metric m:pack p:integer l:Pack d:"The number of bottles in a case for the liquor ordered" t:dataTypeName=number

metric m:bottle_volume_ml p:integer l:"Bottle Volume (ml)" d:"Volume of each liquor bottle ordered in milliliters." t:dataTypeName=number

metric m:state_bottle_cost p:double l:"State Bottle Cost" d:"The amount that Alcoholic Beverages Division paid for each bottle of liquor ordered" t:dataTypeName=money

metric m:state_bottle_retail p:double l:"State Bottle Retail" d:"The amount the store paid for each bottle of liquor ordered" t:dataTypeName=money

metric m:sale_bottles p:integer l:"Bottles Sold" d:"The number of bottles of liquor ordered by the store" t:dataTypeName=number

metric m:sale_dollars p:double l:"Sale (Dollars)" d:"Total cost of liquor order (number of bottles multiplied by the state bottle retail)" t:dataTypeName=money

metric m:sale_liters p:double l:"Volume Sold (Liters)" d:"Total volume of liquor ordered in liters. (i.e. (Bottle Volume (ml) x Bottles Sold)/1,000)" t:dataTypeName=number

metric m:sale_gallons p:double l:"Volume Sold (Gallons)" d:"Total volume of liquor ordered in gallons. (i.e. (Bottle Volume (ml) x Bottles Sold)/3785.411784)" t:dataTypeName=number

entity e:m3tr-qhgy l:"Iowa Liquor Sales" t:attribution="Iowa Department of Commerce, Alcoholic Beverages Division" t:url=https://data.iowa.gov/api/views/m3tr-qhgy

property e:m3tr-qhgy t:meta.view v:id=m3tr-qhgy v:category=Economy v:averageRating=0 v:name="Iowa Liquor Sales" v:attribution="Iowa Department of Commerce, Alcoholic Beverages Division"

property e:m3tr-qhgy t:meta.view.license v:name="Public Domain"

property e:m3tr-qhgy t:meta.view.owner v:id=nj4v-jwef v:profileImageUrlMedium=/api/users/nj4v-jwef/profile_images/THUMB v:profileImageUrlLarge=/api/users/nj4v-jwef/profile_images/LARGE v:screenName="Alcoholic Beverages Division (Commerce)" v:profileImageUrlSmall=/api/users/nj4v-jwef/profile_images/TINY v:displayName="Alcoholic Beverages Division (Commerce)"

property e:m3tr-qhgy t:meta.view.tableauthor v:id=nj4v-jwef v:profileImageUrlMedium=/api/users/nj4v-jwef/profile_images/THUMB v:profileImageUrlLarge=/api/users/nj4v-jwef/profile_images/LARGE v:screenName="Alcoholic Beverages Division (Commerce)" v:profileImageUrlSmall=/api/users/nj4v-jwef/profile_images/TINY v:roleName=editor v:displayName="Alcoholic Beverages Division (Commerce)"
```

## Top Records

```ls
| invoice_line_no | date                | store | name                              | address               | city         | zipcode | county_number | county     | category | category_name                  | vendor_no | vendor_name                       | itemno | im_desc                                       | pack | bottle_volume_ml | state_bottle_cost | state_bottle_retail | sale_bottles | sale_dollars | sale_liters | sale_gallons  | 
| =============== | =================== | ===== | ================================= | ===================== | ============ | ======= | ============= | ========== | ======== | ============================== | ========= | ================================= | ====== | ============================================= | ==== | ================ | ================= | =================== | ============ | ============ | =========== | ============= | 
| S29198800001    | 2015-11-20T00:00:00 | 2191  | Keokuk Spirits                    | 1013 MAIN             | KEOKUK       | 52632   | 56            | Lee        |          |                                | 255       | Wilson Daniels Ltd.               | 297    | Templeton Rye w/Flask                         | 6    | 750              | 18.09             | 27.14               | 6            | 162.84       | 4.5         | 1.18877423561 | 
| S29195400002    | 2015-11-21T00:00:00 | 2205  | Ding's Honk And Holler            | 900 E WASHINGTON      | CLARINDA     | 51632   | 73            | Page       |          |                                | 255       | Wilson Daniels Ltd.               | 297    | Templeton Rye w/Flask                         | 6    | 750              | 18.09             | 27.14               | 12           | 325.68       | 9           | 2.37754847122 | 
| S29050300001    | 2015-11-16T00:00:00 | 3549  | Quicker Liquor Store              | 1414 48TH ST          | FORT MADISON | 52627   | 56            | Lee        |          |                                | 130       | Disaronno International LLC       | 249    | Disaronno Amaretto Cavalli Mignon 3-50ml Pack | 20   | 150              | 6.4               | 9.6                 | 2            | 19.2         | 0.3         | 0.0792516157  | 
| S28867700001    | 2015-11-04T00:00:00 | 2513  | Hy-Vee Food Store #2 / Iowa City  | 812 S 1ST AVE         | IOWA CITY    | 52240   | 52            | Johnson    |          |                                | 65        | Jim Beam Brands                   | 237    | Knob Creek w/ Crystal Decanter                | 3    | 1750             | 35.55             | 53.34               | 3            | 160.02       | 5.25        | 1.38690327488 | 
| S29050800001    | 2015-11-17T00:00:00 | 3942  | Twin Town Liquor                  | 104 HIGHWAY 30 WEST   | TOLEDO       | 52342   | 86            | Tama       |          |                                | 130       | Disaronno International LLC       | 249    | Disaronno Amaretto Cavalli Mignon 3-50ml Pack | 20   | 150              | 6.4               | 9.6                 | 2            | 19.2         | 0.3         | 0.0792516157  | 
| S28869200001    | 2015-11-11T00:00:00 | 3650  | Spirits, Stogies and Stuff        | 118 South Main St.    | HOLSTEIN     | 51025   | 47            | Ida        |          |                                | 65        | Jim Beam Brands                   | 237    | Knob Creek w/ Crystal Decanter                | 3    | 1750             | 35.55             | 53.34               | 1            | 53.34        | 1.75        | 0.46230109162 | 
| S28865700001    | 2015-11-09T00:00:00 | 2538  | Hy-Vee Food Store #3 / Waterloo   | 1422 FLAMMANG DR      | WATERLOO     | 50702   | 07            | Black Hawk | 1701100  | DECANTERS & SPECIALTY PACKAGES | 962       | Duggan's Distillers Products Corp | 238    | Forbidden Secret Coffee Pack                  | 6    | 1500             | 11.62             | 17.43               | 6            | 104.58       | 9           | 2.37754847122 | 
| S28869500001    | 2015-11-10T00:00:00 | 3942  | Twin Town Liquor                  | 104 HIGHWAY 30 WEST   | TOLEDO       | 52342   | 86            | Tama       |          |                                | 65        | Jim Beam Brands                   | 237    | Knob Creek w/ Crystal Decanter                | 3    | 1750             | 35.55             | 53.34               | 2            | 106.68       | 3.5         | 0.92460218325 | 
| S29339300091    | 2015-11-30T00:00:00 | 2662  | Hy-Vee Wine & Spirits / Muscatine | 522 MULBERRY, SUITE A | MUSCATINE    | 52761   | 70            | Muscatine  | 1701100  | DECANTERS & SPECIALTY PACKAGES | 65        | Jim Beam Brands                   | 173    | Laphroaig w/ Whiskey Stones                   | 12   | 750              | 19.58             | 29.37               | 4            | 117.48       | 3           | 0.79251615707 | 
| S29050900001    | 2015-11-16T00:00:00 | 4307  | Crossroads Wine and Liquor        | 117 IOWA AVE          | DUNLAP       | 712-2   | 43            | Harrison   |          |                                | 130       | Disaronno International LLC       | 249    | Disaronno Amaretto Cavalli Mignon 3-50ml Pack | 20   | 150              | 6.4               | 9.6                 | 2            | 19.2         | 0.3         | 0.0792516157  | 
```