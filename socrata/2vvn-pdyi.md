# NYS Lottery Retailers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-lottery-retailers) |
| Metadata | [Link](https://data.ny.gov/api/views/2vvn-pdyi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2vvn-pdyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2vvn-pdyi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2vvn-pdyi |
| Name | NYS Lottery Retailers |
| Attribution | Gaming Commission |
| Category | Government & Finance |
| Tags | new york lottery, retailers, quick draw, lotto |
| Created | 2016-02-16T19:22:08Z |
| Publication Date | 2017-04-20T10:13:12Z |

## Description

Listing of all active licensed retailers that sell lottery products in New York state.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | retailer    | Retailer   | text      | text        |
| Yes      | series tag     | name        | Name       | text      | text        |
| Yes      | series tag     | street      | Street     | text      | text        |
| Yes      | series tag     | city        | City       | text      | text        |
| Yes      | series tag     | state       | State      | text      | text        |
| Yes      | series tag     | zip         | Zip        | text      | text        |
| Yes      | series tag     | quick_draw  | Quick Draw | text      | text        |
| Yes      | numeric metric | latitude    | Latitude   | number    | number      |
| Yes      | numeric metric | longitude   | Longitude  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2vvn-pdyi d:2017-04-20T10:12:54.000Z t:zip=11204 t:street="6317 20TH AVE" t:name="RADFAN INC" t:state=NY t:retailer=000049 t:city=BROOKLYN m:longitude=-73.985037 m:latitude=40.617307

series e:2vvn-pdyi d:2017-04-20T10:12:54.000Z t:zip=10036 t:street="25 W 43RD ST" t:name="B&J NEWSSTAND" t:state=NY t:retailer=000186 t:city="NEW YORK" m:longitude=-73.981179 m:latitude=40.754479

series e:2vvn-pdyi d:2017-04-20T10:12:54.000Z t:quick_draw=Y t:zip=11220 t:street="185 BAY RIDGE AVE" t:name="P & K GIFT SHOP" t:state=NY t:retailer=000213 t:city=BROOKLYN m:longitude=-74.029159 m:latitude=40.636702
```

## Meta Commands

```ls
metric m:latitude p:long l:Latitude d:"Latitude of record for retailer location." t:dataTypeName=number

metric m:longitude p:long l:Longitude d:"Longitude of record for retailer location." t:dataTypeName=number

entity e:2vvn-pdyi l:"NYS Lottery Retailers" t:attribution="Gaming Commission" t:url=https://data.ny.gov/api/views/2vvn-pdyi

property e:2vvn-pdyi t:meta.view v:id=2vvn-pdyi v:category="Government & Finance" v:attributionLink=http://nylottery.ny.gov/ v:averageRating=0 v:name="NYS Lottery Retailers" v:attribution="Gaming Commission"

property e:2vvn-pdyi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2vvn-pdyi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | retailer | name                        | street                    | city          | state | zip   | quick_draw | latitude  | longitude  | 
| =========== | ======== | =========================== | ========================= | ============= | ===== | ===== | ========== | ========= | ========== | 
| 1492683174  | 000049   | RADFAN INC                  | 6317 20TH AVE             | BROOKLYN      | NY    | 11204 |            | 40.617307 | -73.985037 | 
| 1492683174  | 000186   | B&J NEWSSTAND               | 25 W 43RD ST              | NEW YORK      | NY    | 10036 |            | 40.754479 | -73.981179 | 
| 1492683174  | 000213   | P & K GIFT SHOP             | 185 BAY RIDGE AVE         | BROOKLYN      | NY    | 11220 | Y          | 40.636702 | -74.029159 | 
| 1492683174  | 000448   | STATEN ISL HOSP GIFT SHOPPE | 475 SEAVIEW AV MAIN LOBBY | STATEN ISLAND | NY    | 10305 |            | 40.594406 | -74.071136 | 
| 1492683174  | 000456   | M & N SMOKE & CARD INC      | 129 E 28TH ST             | NEW YORK      | NY    | 10016 |            | 40.742654 | -73.982502 | 
| 1492683174  | 000529   | LEE & LIN CO INC            | 59-18 MAIN ST             | FLUSHING      | NY    | 11355 |            | 40.743728 | -73.825662 | 
| 1492683174  | 000614   | HILLSIDE PHARMACY           | 184-20 HILLSIDE AVE       | JAMAICA       | NY    | 11432 | Y          | 40.714045 | -73.777803 | 
| 1492683174  | 000708   | RUBEX DRUGS INC             | 81-19 41ST AVE            | ELMHURST      | NY    | 11373 |            | 40.745881 | -73.884415 | 
| 1492683174  | 000711   | PARK PEOPLE NEWS (SIDEWALK) | 866 3RD AVE               | NEW YORK      | NY    | 10022 |            | 40.757710 | -73.969375 | 
| 1492683174  | 000733   | ADAM'S BAGEL & DELI         | 63-56 WOODHAVEN BLVD      | REGO PARK     | NY    | 11374 | Y          | 40.723040 | -73.868176 | 
```