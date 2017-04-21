# LASAN: Solid Resources Tonnages - Bulky Item, E-Waste, and White Goods

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lasan-solid-resources-tonnages-bulky-item-e-waste-and-white-goods) |
| Metadata | [Link](https://data.lacity.org/api/views/qwh3-ax8z) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qwh3-ax8z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qwh3-ax8z/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qwh3-ax8z |
| Name | LASAN: Solid Resources Tonnages - Bulky Item, E-Waste, and White Goods |
| Attribution | LA Sanitation |
| Category | A Livable and Sustainable City |
| Tags | lasan, tonnage, waste, garbage, solid resources, sanitation, bulky item, e-waste, white goods |
| Created | 2015-12-01T02:06:31Z |
| Publication Date | 2017-03-20T16:04:19Z |

## Description

Monthly tonnages reported by district yards. White goods include large household appliances such as refrigerators, washers, and dryers.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | district         | District         | text          | text          |
| Yes      | series tag     | route            | Route            | text          | text          |
| Yes      | time           | datetime         | DateTime         | calendar_date | calendar_date |
| Yes      | series tag     | site             | Site             | text          | text          |
| Yes      | series tag     | ticketnumber     | TicketNumber     | text          | text          |
| Yes      | numeric metric | tons             | Tons             | number        | number        |
| Yes      | series tag     | commoditycode    | CommodityCode    | text          | text          |
| Yes      | series tag     | generalcommodity | GeneralCommodity | text          | text          |
```

## Time Field

```ls
Value = datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qwh3-ax8z d:2015-11-01T00:00:00.000Z t:site="City of Los Angeles Refuse Transfer Station (CLARTS)" t:route=RCA2 t:generalcommodity=Refuse t:district="South Central" t:commoditycode=CA t:ticketnumber=4640666 m:tons=4.76

series e:qwh3-ax8z d:2015-11-01T00:00:00.000Z t:site="City of Los Angeles Refuse Transfer Station (CLARTS)" t:route=RCA2 t:generalcommodity=Refuse t:district="South Central" t:commoditycode=CA t:ticketnumber=4640667 m:tons=6.97

series e:qwh3-ax8z d:2015-11-01T00:00:00.000Z t:site="City of Los Angeles Refuse Transfer Station (CLARTS)" t:route=FCA1 t:generalcommodity=Refuse t:district="South Central" t:commoditycode=CA t:ticketnumber=4640671 m:tons=8.92
```

## Meta Commands

```ls
metric m:tons p:double l:Tons t:dataTypeName=number

entity e:qwh3-ax8z l:"LASAN:  Solid Resources Tonnages - Bulky Item, E-Waste, and White Goods" t:attribution="LA Sanitation" t:url=https://data.lacity.org/api/views/qwh3-ax8z

property e:qwh3-ax8z t:meta.view v:id=qwh3-ax8z v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LASAN:  Solid Resources Tonnages - Bulky Item, E-Waste, and White Goods" v:attribution="LA Sanitation"

property e:qwh3-ax8z t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qwh3-ax8z t:meta.view.owner v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:displayName="Public Works: Sanitation OpenData"

property e:qwh3-ax8z t:meta.view.tableauthor v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Sanitation OpenData"
```

## Top Records

```ls
| district      | route | datetime            | site                                                 | ticketnumber | tons               | commoditycode | generalcommodity | 
| ============= | ===== | =================== | ==================================================== | ============ | ================== | ============= | ================ | 
| South Central | RCA2  | 2015-11-01T00:00:00 | City of Los Angeles Refuse Transfer Station (CLARTS) | 4640666      | 4.76               | CA            | Refuse           | 
| South Central | RCA2  | 2015-11-01T00:00:00 | City of Los Angeles Refuse Transfer Station (CLARTS) | 4640667      | 6.97               | CA            | Refuse           | 
| South Central | FCA1  | 2015-11-01T00:00:00 | City of Los Angeles Refuse Transfer Station (CLARTS) | 4640671      | 8.92               | CA            | Refuse           | 
| South Central | RCA2  | 2015-11-01T00:00:00 | City of Los Angeles Refuse Transfer Station (CLARTS) | 4640668      | 5.76               | CA            | Refuse           | 
| North Central | MA70  | 2015-11-01T00:00:00 | East LA Transfer Station                             | 974424       | 0.33               | R             | Recycling        | 
| North Central | MA70  | 2015-11-01T00:00:00 | East LA Transfer Station                             | 974424       | 0.33               | R             | Recycling        | 
| North Central | MA70  | 2015-11-01T00:00:00 | East LA Transfer Station                             | 974424       | 0.34               | R             | Recycling        | 
| Harbor        | DD1   | 2015-11-01T00:00:00 | West Coast Rendering                                 | 11810        | 0.26               | D             | Refuse           | 
| South Central | RCA1  | 2015-11-02T00:00:00 | City of Los Angeles Refuse Transfer Station (CLARTS) | 4640669      | 8.7899999999999991 | CA            | Refuse           | 
| South Central | RCA2  | 2015-11-02T00:00:00 | City of Los Angeles Refuse Transfer Station (CLARTS) | 4640670      | 9.07               | CA            | Refuse           | 
```