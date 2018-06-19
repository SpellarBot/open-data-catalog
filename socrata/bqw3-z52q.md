# Food Vendor Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-vendor-locations-d4ff1) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/bqw3-z52q) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/bqw3-z52q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/bqw3-z52q/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | bqw3-z52q |
| Name | Food Vendor Locations |
| Attribution | EGIS |
| Tags | vendor, food, street, street food, vendors |
| Created | 2013-11-22T18:38:25Z |
| Publication Date | 2013-11-25T16:27:54Z |

## Description

Street Food Vendors

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | Id         | text      | number      |
| Yes      | series tag  | licensenum  | LicenseNum | text      | text        |
| Yes      | series tag  | vendorname  | VendorName | text      | text        |
| Yes      | series tag  | vendoraddr  | VendorAddr | text      | text        |
| Yes      | series tag  | itemssold   | ItemsSold  | text      | text        |
| Yes      | series tag  | cart_descr  | Cart_Descr | text      | text        |
| No       |             | st          | St         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,st
```

## Data Commands

```ls
series e:bqw3-z52q d:2013-11-22T10:38:27.000Z t:vendorname="Abdul-Ghani, Christina, ""The Bullpen Bar""" t:cart_descr="Two add'l tables to be added to current 6' table in U shape, with grill & warming pans, Tent" t:licensenum=DF000166 t:vendoraddr="508 Washington Blvd, confined within 10 x 10 space" t:itemssold="Grilled food, pizza slices, gyro sandwiches" m:row_number.bqw3-z52q=1

series e:bqw3-z52q d:2013-11-22T10:38:27.000Z t:vendorname="Ali, Fathi" t:cart_descr=Pushcart t:licensenum=DF000075 t:vendoraddr="SEC Calvert & Madison on Calvert" t:itemssold="Hot Dogs, Sausage, Snacks, Gum, Candies, Drinks" m:row_number.bqw3-z52q=2

series e:bqw3-z52q d:2013-11-22T10:38:27.000Z t:vendorname="Ali, Fathi" t:cart_descr=Pushcart t:licensenum=DF000133 t:vendoraddr="NEC Baltimore & Pine Sts" t:itemssold="Hot dogs, Sausage, drinks, snacks, gum, & candy" m:row_number.bqw3-z52q=3
```

## Meta Commands

```ls
metric m:row_number.bqw3-z52q p:long l:"Row Number"

entity e:bqw3-z52q l:"Food Vendor Locations" t:attribution=EGIS t:url=https://data.baltimorecity.gov/api/views/bqw3-z52q

property e:bqw3-z52q t:meta.view v:id=bqw3-z52q v:attributionLink=http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/InformationTechnology/EnterpriseGeographicInformationServices.aspx v:averageRating=0 v:name="Food Vendor Locations" v:attribution=EGIS

property e:bqw3-z52q t:meta.view.license v:name="Public Domain"

property e:bqw3-z52q t:meta.view.owner v:id=jp5u-a9z8 v:profileImageUrlMedium=/api/users/jp5u-a9z8/profile_images/THUMB v:profileImageUrlLarge=/api/users/jp5u-a9z8/profile_images/LARGE v:screenName="brad chranko" v:profileImageUrlSmall=/api/users/jp5u-a9z8/profile_images/TINY v:displayName="brad chranko"

property e:bqw3-z52q t:meta.view.tableauthor v:id=jp5u-a9z8 v:profileImageUrlMedium=/api/users/jp5u-a9z8/profile_images/THUMB v:profileImageUrlLarge=/api/users/jp5u-a9z8/profile_images/LARGE v:screenName="brad chranko" v:profileImageUrlSmall=/api/users/jp5u-a9z8/profile_images/TINY v:displayName="brad chranko"
```

## Top Records

```ls
| :updated_at | id | licensenum | vendorname                                | vendoraddr                                                                                                                                                                                            | itemssold                                                                | cart_descr                                                                                   | st | 
| =========== | == | ========== | ========================================= | ===================================================================================================================================================================================================== | ======================================================================== | ============================================================================================ | == | 
| 1385116707  | 0  | DF000166   | Abdul-Ghani, Christina, "The Bullpen Bar" | 508 Washington Blvd, confined within 10 x 10 space                                                                                                                                                    | Grilled food, pizza slices, gyro sandwiches                              | Two add'l tables to be added to current 6' table in U shape, with grill & warming pans, Tent | MD | 
| 1385116707  | 0  | DF000075   | Ali, Fathi                                | SEC Calvert & Madison on Calvert                                                                                                                                                                      | Hot Dogs, Sausage, Snacks, Gum, Candies, Drinks                          | Pushcart                                                                                     | MD | 
| 1385116707  | 0  | DF000133   | Ali, Fathi                                | NEC Baltimore & Pine Sts                                                                                                                                                                              | Hot dogs, Sausage, drinks, snacks, gum, & candy                          | Pushcart                                                                                     | MD | 
| 1385116707  | 0  | DF000136   | Ali, Fathi                                | NEC Light & Redwood Sts                                                                                                                                                                               | Hot dogs, sausages, chips, snacks, drinks, gum                           | Pushcart                                                                                     | MD | 
| 1385116707  | 0  | DF000001   | Ali, Yusuf                                | On Hamburg St across from the rear end of the Ravens Stadium (Johnny Unitis Plaza). The cart is facing the back parking lots of the baseball stadium. SITE IS NOT TO BE WORKED DURING FOOTBALL GAMES. | Large & Small beef franks, soft drinks, water, all types of nuts & chips | grey pushcart on three wheels                                                                | MD | 
| 1385116707  | 0  | DF000078   | Amatullah, Maidah                         | NWC Charles & Chase Sts                                                                                                                                                                               | Hot dogs, Sodas, Chips                                                   | pushcart with hot/cold running water                                                         | MD | 
| 1385116707  | 0  | DF000068   | Amer, Mohamed                             | SEC Lombard & Light Sts.                                                                                                                                                                              | Hot dogs, Sausages, Prepackaged snacks, Sodas, Water, Juice, Coffee      | Hot dog cart                                                                                 | MD | 
| 1385116707  | 0  | DF000002   | Blimline, Lisa                            | SW Ostend St & Sharp (Under the bridge)                                                                                                                                                               | Hot dogs, snacks, coffee and soda                                        | 2 Carts on wheels, 4 tables on wheels                                                        | MD | 
| 1385116707  | 0  | DF000004   | Paul & Elizabeth Carter                   | SWC Washington & Paca                                                                                                                                                                                 | Hot Dogs, Burgers, Sausage, Chips, Soda, Water, Pretzels                 | Hot Dog Cart & Grill                                                                         | MD | 
| 1385116707  | 0  | DF000005   | Paul & Elizabeth Carter                   | NEC Ostend & Ridgely on Ostend (along fence on E side of Ostend facing lot)                                                                                                                           | Hot Dogs, Burgers, Sausage, Chips, Soda, Water, Pretzels                 | Hot Dog Cart & Grill                                                                         | MD | 
```