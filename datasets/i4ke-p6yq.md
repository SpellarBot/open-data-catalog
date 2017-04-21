# Citywide LED Streetlight Savings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citywide-led-streetlight-savings) |
| Metadata | [Link](https://data.lacity.org/api/views/i4ke-p6yq) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/i4ke-p6yq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/i4ke-p6yq/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | i4ke-p6yq |
| Name | Citywide LED Streetlight Savings |
| Category | A Livable and Sustainable City |
| Tags | streetlight, led, energy, savings, pollution |
| Created | 2014-05-12T22:38:50Z |
| Publication Date | 2017-03-13T21:19:00Z |

## Description

The LED Streetlight Replacement Program has replaced over 170,000 existing streetlight fixtures in the city, resulting in substantial energy and carbon emissions savings.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type | Render Type |
| ======== | ============== | ================================ | ================================== | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | council_district                 | Council District                   | text      | number      |
| Yes      | numeric metric | total_units                      | Total Units                        | number    | number      |
| Yes      | numeric metric | total_nom_watts_before_kw        | Total Nom Watts Before (kW)        | number    | number      |
| Yes      | numeric metric | total_nom_wats_tafter_kw         | Total Nom Watts After (kW)         | number    | number      |
| Yes      | numeric metric | energy_savings                   | % Energy Savings                   | percent   | percent     |
| Yes      | numeric metric | annual_c02_reduction_metric_tons | Annual C02 Reduction (Metric Tons) | number    | number      |
| Yes      | numeric metric | annual_energy_savings_gwh        | Annual Energy Savings (GWh)        | number    | number      |
| Yes      | numeric metric | annual_energy_savings            | Annual Energy Savings              | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i4ke-p6yq d:2017-03-13T21:18:41.000Z t:council_district=1 m:energy_savings=61 m:total_nom_watts_before_kw=1794.5 m:annual_c02_reduction_metric_tons=2642.7 m:annual_energy_savings=395778.6 m:annual_energy_savings_gwh=4.469 m:total_nom_wats_tafter_kw=699.1 m:total_units=7541

series e:i4ke-p6yq d:2017-03-13T21:18:41.000Z t:council_district=2 m:energy_savings=67.8 m:total_nom_watts_before_kw=1336.1 m:annual_c02_reduction_metric_tons=2184.5 m:annual_energy_savings=326727.18 m:annual_energy_savings_gwh=3.694 m:total_nom_wats_tafter_kw=430.7 m:total_units=5412

series e:i4ke-p6yq d:2017-03-13T21:18:41.000Z t:council_district=3 m:energy_savings=66.6 m:total_nom_watts_before_kw=3136.3 m:annual_c02_reduction_metric_tons=5042.8 m:annual_energy_savings=761288.97 m:annual_energy_savings_gwh=8.528 m:total_nom_wats_tafter_kw=1046 m:total_units=14148
```

## Meta Commands

```ls
metric m:total_units p:integer l:"Total Units" d:"Total number of LED fixtures replaced" t:dataTypeName=number

metric m:total_nom_watts_before_kw p:float l:"Total Nom Watts Before (kW)" d:"Total nominal watts before conversion (in kilowatts)" t:dataTypeName=number

metric m:total_nom_wats_tafter_kw p:float l:"Total Nom Watts After (kW)" d:"Total nominal watts after conversion (in kilowatts)" t:dataTypeName=number

metric m:energy_savings p:float l:"% Energy Savings" d:"Percent of energy savings" t:dataTypeName=percent

metric m:annual_c02_reduction_metric_tons p:float l:"Annual C02 Reduction (Metric Tons)" d:"Annual reduction in carbon dioxide (in metric tons)" t:dataTypeName=number

metric m:annual_energy_savings_gwh p:float l:"Annual Energy Savings (GWh)" d:"Annual energy savings (in gigawatt hours)" t:dataTypeName=number

metric m:annual_energy_savings p:double l:"Annual Energy Savings" d:"Annual energy savings (in dollars)" t:dataTypeName=money

entity e:i4ke-p6yq l:"Citywide LED Streetlight Savings" t:url=https://data.lacity.org/api/views/i4ke-p6yq

property e:i4ke-p6yq t:meta.view v:id=i4ke-p6yq v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Citywide LED Streetlight Savings"

property e:i4ke-p6yq t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:i4ke-p6yq t:meta.view.owner v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:displayName="Public Works: Street Lighting OpenData"

property e:i4ke-p6yq t:meta.view.tableauthor v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Lighting OpenData"
```

## Top Records

```ls
| :updated_at | council_district | total_units | total_nom_watts_before_kw | total_nom_wats_tafter_kw | energy_savings | annual_c02_reduction_metric_tons | annual_energy_savings_gwh | annual_energy_savings | 
| =========== | ================ | =========== | ========================= | ======================== | ============== | ================================ | ========================= | ===================== | 
| 1489439921  | 1                | 7541        | 1794.50                   | 699.1                    | 61.00          | 2642.70                          | 4.4690000000000003        | 395778.60             | 
| 1489439921  | 2                | 5412        | 1336.10                   | 430.7                    | 67.80          | 2184.50                          | 3.694                     | 326727.18             | 
| 1489439921  | 3                | 14148       | 3136.30                   | 1046.00                  | 66.60          | 5042.80                          | 8.5280000000000005        | 761288.97             | 
| 1489439921  | 4                | 9333        | 2135.70                   | 757.7                    | 64.50          | 3324.30                          | 5.6219999999999999        | 496992.31             | 
| 1489439921  | 5                | 11521       | 2905.00                   | 950.3                    | 67.30          | 4727.70                          | 7.9749999999999996        | 705015.30             | 
| 1489439921  | 6                | 8603        | 2125.80                   | 764.7                    | 64.00          | 3283.70                          | 5.5529999999999999        | 498720.75             | 
| 1489439921  | 7                | 9238        | 2142.80                   | 771.1                    | 64.00          | 3309.30                          | 5.5970000000000004        | 499602.67             | 
| 1489439921  | 8                | 16343       | 3547.20                   | 1415.50                  | 60.10          | 5142.60                          | 8.6969999999999992        | 769170.36             | 
| 1489439921  | 9                | 11185       | 2615.20                   | 983.2                    | 62.40          | 3937.20                          | 6.6589999999999998        | 599541.92             | 
| 1489439921  | 10               | 12492       | 2791.20                   | 1070.60                  | 61.60          | 4151.00                          | 7.02                      | 620571.88             | 
```