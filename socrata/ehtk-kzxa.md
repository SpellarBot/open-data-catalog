# Farm Product Dealer Licenses Currently Issued

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/farm-product-dealer-licenses-currently-issued) |
| Metadata | [Link](https://data.ny.gov/api/views/ehtk-kzxa) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ehtk-kzxa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ehtk-kzxa/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ehtk-kzxa |
| Name | Farm Product Dealer Licenses Currently Issued |
| Attribution | NYS Department of Agriculture and Markets (DAM) |
| Category | Economic Development |
| Tags | produce, farm goods, resellers |
| Created | 2016-02-22T13:21:35Z |
| Publication Date | 2016-11-14T21:32:35Z |

## Description

NYS Department of Agriculture and Markets (DAM) licenses dealers who buy or receive an excess of $10,000 of New York farm products from New York State producers for resale. Dealers are licensed annually on May 1st of every year until April 30th of the next year. This list of Licensed Dealers includes Business Name, Trade Name (where different), Address, Phone Number and Commodities dealt.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | county            | County            | text      | text        |
| Yes      | series tag  | business_name     | Business Name     | text      | text        |
| Yes      | series tag  | trade_name        | Trade Name        | text      | text        |
| Yes      | series tag  | street            | Street Address    | text      | text        |
| Yes      | series tag  | city              | City              | text      | text        |
| Yes      | series tag  | state             | State             | text      | text        |
| Yes      | series tag  | zip_code          | Zip Code          | text      | text        |
| Yes      | series tag  | phone_number      | Phone Number      | phone     | phone       |
| Yes      | series tag  | commodity_listing | Commodity Listing | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ehtk-kzxa d:2016-11-14T21:06:04.000Z t:business_name="5 KINDER FARM, LLC" t:phone_number=585-690-0140 t:zip_code=14512-9202 t:county=ONTARIO t:street="197 N MAIN ST" t:state=NY t:trade_name="INSPIRE MOORE WINERY & VINEYARD" t:commodity_listing="Grapes, Raspberries" t:city=NAPLES m:row_number.ehtk-kzxa=1

series e:ehtk-kzxa d:2016-11-14T21:06:04.000Z t:business_name="ADIRONDACK WINERY LLC" t:phone_number=518-668-9463 t:zip_code=12804-7854 t:county=WARREN t:street="395 BIG BAY RD" t:state=NY t:commodity_listing=Grapes t:city=QUEENSBURY m:row_number.ehtk-kzxa=2

series e:ehtk-kzxa d:2016-11-14T21:06:04.000Z t:business_name="ADM MILLING CO" t:phone_number=913-491-9400 t:zip_code=12534 t:county=ERIE t:street="ROUTE 23B" t:state=NY t:commodity_listing="Grain-Soft Red Winter Wheat" t:city=HUDSON m:row_number.ehtk-kzxa=3
```

## Meta Commands

```ls
metric m:row_number.ehtk-kzxa p:long l:"Row Number"

entity e:ehtk-kzxa l:"Farm Product Dealer Licenses Currently Issued" t:attribution="NYS Department of Agriculture and Markets (DAM)" t:url=https://data.ny.gov/api/views/ehtk-kzxa

property e:ehtk-kzxa t:meta.view v:id=ehtk-kzxa v:category="Economic Development" v:attributionLink=http://www.agriculture.ny.gov/programs/apsf.html v:averageRating=0 v:name="Farm Product Dealer Licenses Currently Issued" v:attribution="NYS Department of Agriculture and Markets (DAM)"

property e:ehtk-kzxa t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ehtk-kzxa t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | county   | business_name                   | trade_name                      | street              | city          | state | zip_code   | phone_number         | commodity_listing                                                                                                                                           | 
| =========== | ======== | =============================== | =============================== | =================== | ============= | ===== | ========== | ==================== | =========================================================================================================================================================== | 
| 1479157564  | ONTARIO  | 5 KINDER FARM, LLC              | INSPIRE MOORE WINERY & VINEYARD | 197 N MAIN ST       | NAPLES        | NY    | 14512-9202 | [585-690-0140, null] | Grapes, Raspberries                                                                                                                                         | 
| 1479157564  | WARREN   | ADIRONDACK WINERY LLC           |                                 | 395 BIG BAY RD      | QUEENSBURY    | NY    | 12804-7854 | [518-668-9463, null] | Grapes                                                                                                                                                      | 
| 1479157564  | ERIE     | ADM MILLING CO                  |                                 | ROUTE 23B           | HUDSON        | NY    | 12534      | [913-491-9400, null] | Grain-Soft Red Winter Wheat                                                                                                                                 | 
| 1479157564  | JOHNSON  | AGREX INC                       | F.G.D.I.                        | 10975 GRANDVIEW DR  | OVERLAND PARK | KS    | 66210-1564 | [913-851-6391, null] | Corn                                                                                                                                                        | 
| 1479157564  | ULSTER   | ALLSTATE APPLE EXCHANGE INCT/A  | HUDSON RIVER FRUIT DISTS.       | 65 OLD INDIAN RD    | MILTON        | NY    | 12547-5411 | [845-795-2121, null] | Apples, Apples-cider , Fruits-Pears, Fruits-Plums, Peaches                                                                                                  | 
| 1479157564  | WAYNE    | AMEELE, MICHAEL                 | AMEELE FARMS, LLC               | 4552 HALL CENTER RD | WALWORTH      | NY    | 14568-9794 | [315-926-0809, null] | Corn, Grain, Livestock, Soybeans                                                                                                                            | 
| 1479157564  | MONROE   | AMERICAN FRUIT&VEGETABLE CO INC |                                 | 205 MUSHROOM BLVD   | ROCHESTER     | NY    | 14623      | [585-427-7716, null] | Apples, Cabbage, Corn, Onions, Potatoes, Squash-all available , Tomatoes (in the open), Vegetables-Broccoli , Vegetables-Cauliflower , Vegetables-Cucumbers | 
| 1479157564  | SUFFOLK  | AMPCO DISTRIBUTION SERVICES LLC |                                 | 889 HARRISON AVE    | RIVERHEAD     | NY    | 11901-2090 | [631-591-5209, null] | Onions, Potatoes                                                                                                                                            | 
| 1479157564  | ONONDAGA | ANDYS PRODUCE INC               |                                 | 101 W COURT ST      | SYRACUSE      | NY    | 13204-1328 | [315-471-3332, null] | Cabbage, Onions, Other-EGGS, Potatoes, Squash, Tomatoes (in the open), Vegetables-LEAFY, CARROTS                                                            | 
| 1479157564  | COLUMBIA | ANGELLO'S DISTRIBUTING, INC     |                                 | 1931 ROUTE 9        | GERMANTOWN    | NY    | 12526-5515 | [518-537-7900, null] | Fruits and Vegetables-produce, Other-milk, eggs                                                                                                             | 
```