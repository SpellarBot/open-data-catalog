# Transportation Fuels Spot Prices: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-fuels-spot-prices-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/k7gz-mn77) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/k7gz-mn77/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/k7gz-mn77/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | k7gz-mn77 |
| Name | Transportation Fuels Spot Prices: Beginning 2006 |
| Attribution | New York State Energy Research and Development Authority Performance Management and Evaluation Services Group |
| Category | Energy & Environment |
| Tags | gasoline, diesel, spot prices, crude oil |
| Created | 2014-08-28T15:22:43Z |
| Publication Date | 2017-04-07T22:00:31Z |

## Description

Transportation Fuels Spot Prices dataset provides weekly average spot price information for New York Harbor Conventional Gasoline, New York Harbor Ultra-Low Sulfur Diesel as well as Western Texas Intermediate (WTI) and Brent crude oil. The data is presented as a weekly average from June 2006 through current.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                          | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ============================================= | ============= | ============= |
| Yes      | time           | date                                      | Date                                          | calendar_date | calendar_date |
| Yes      | numeric metric | ny_conventional_gasoline_spot_price_gal   | NY Conventional Gasoline Spot Price ($/gal)   | number        | number        |
| Yes      | numeric metric | ny_ultra_low_sulfur_diesel_spot_price_gal | NY Ultra-Low Sulfur Diesel Spot Price ($/gal) | number        | number        |
| Yes      | numeric metric | wti_crude_oil_spot_price_barrel           | WTI Crude Oil Spot Price ($/barrel)           | number        | number        |
| Yes      | numeric metric | brent_crude_oil_spot_price_barrel         | Brent Crude Oil Spot Price ($/barrel)         | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:k7gz-mn77 d:2017-03-31T00:00:00.000Z m:ny_conventional_gasoline_spot_price_gal=1.565 m:brent_crude_oil_spot_price_barrel=51.33 m:wti_crude_oil_spot_price_barrel=49.14 m:ny_ultra_low_sulfur_diesel_spot_price_gal=1.535

series e:k7gz-mn77 d:2017-03-24T00:00:00.000Z m:ny_conventional_gasoline_spot_price_gal=1.491 m:brent_crude_oil_spot_price_barrel=50.1 m:wti_crude_oil_spot_price_barrel=47.28 m:ny_ultra_low_sulfur_diesel_spot_price_gal=1.495

series e:k7gz-mn77 d:2017-03-17T00:00:00.000Z m:ny_conventional_gasoline_spot_price_gal=1.454 m:brent_crude_oil_spot_price_barrel=50.29 m:wti_crude_oil_spot_price_barrel=48.03 m:ny_ultra_low_sulfur_diesel_spot_price_gal=1.498
```

## Meta Commands

```ls
metric m:ny_conventional_gasoline_spot_price_gal p:float l:"NY Conventional Gasoline Spot Price ($/gal)" d:"Weekly average conventional gasoline spot price for New York Harbor ($/gal)." t:dataTypeName=number

metric m:ny_ultra_low_sulfur_diesel_spot_price_gal p:float l:"NY Ultra-Low Sulfur Diesel Spot Price ($/gal)" d:"Weekly average ultra-low sulfur diesel fuel spot price for New York Harbor ($/gal)." t:dataTypeName=number

metric m:wti_crude_oil_spot_price_barrel p:float l:"WTI Crude Oil Spot Price ($/barrel)" d:"Weekly average Cushing, Oklahoma WTI crude oil spot price ($/barrel)." t:dataTypeName=number

metric m:brent_crude_oil_spot_price_barrel p:float l:"Brent Crude Oil Spot Price ($/barrel)" d:"Weekly average Europe Brent crude oil spot price ($/barrel)." t:dataTypeName=number

entity e:k7gz-mn77 l:"Transportation Fuels Spot Prices: Beginning 2006" t:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group" t:url=https://data.ny.gov/api/views/k7gz-mn77

property e:k7gz-mn77 t:meta.view v:id=k7gz-mn77 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Data-and-Prices-Planning-and-Policy/Energy-Prices-Data-and-Reports/EA-Reports-and-Studies/Weekly-Transportation-Fuels-Report.aspx. v:averageRating=0 v:name="Transportation Fuels Spot Prices: Beginning 2006" v:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group"

property e:k7gz-mn77 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:k7gz-mn77 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | ny_conventional_gasoline_spot_price_gal | ny_ultra_low_sulfur_diesel_spot_price_gal | wti_crude_oil_spot_price_barrel | brent_crude_oil_spot_price_barrel | 
| =================== | ======================================= | ========================================= | =============================== | ================================= | 
| 2017-03-31T00:00:00 | 1.565                                   | 1.535                                     | 49.14                           | 51.33                             | 
| 2017-03-24T00:00:00 | 1.491                                   | 1.495                                     | 47.28                           | 50.10                             | 
| 2017-03-17T00:00:00 | 1.454                                   | 1.498                                     | 48.03                           | 50.29                             | 
| 2017-03-10T00:00:00 | 1.484                                   | 1.552                                     | 50.50                           | 52.78                             | 
| 2017-03-03T00:00:00 | 1.492                                   | 1.606                                     | 53.56                           | 54.40                             | 
| 2017-02-24T00:00:00 | 1.533                                   | 1.63                                      | 54.03                           | 55.4                              | 
| 2017-02-17T00:00:00 | 1.547                                   | 1.607                                     | 53.22                           | 54.46                             | 
| 2017-02-10T00:00:00 | 1.536                                   | 1.617                                     | 52.88                           | 54.48                             | 
| 2017-02-03T00:00:00 | 1.563                                   | 1.621                                     | 53.33                           | 55.53                             | 
| 2017-01-27T00:00:00 | 1.574                                   | 1.594                                     | 52.74                           | 54.91                             | 
```