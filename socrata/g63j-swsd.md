# Distribution Sites LCR Monitoring Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/distribution-sites-lcr-monitoring-results) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g63j-swsd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g63j-swsd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g63j-swsd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g63j-swsd |
| Name | Distribution Sites LCR Monitoring Results |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Created | 2015-02-24T18:23:05Z |
| Publication Date | 2016-08-18T17:57:42Z |

## Description

Monthly results from the distribution sites for orthophosphate, pH, temperature, conductivity and monthly alkalinity, calcium, lead and copper - Bi annually updated

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                         | Data Type     | Render Type   |
| ======== | ============== | ========================= | ============================ | ============= | ============= |
| Yes      | numeric metric | sample_site               | Sample Site                  | number        | number        |
| Yes      | time           | sample_date               | Sample Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | ph_unit                   | pH ?(Unit)                   | number        | number        |
| Yes      | numeric metric | alkalinity_mg_l_caco3     | Alkalinity (mg/L CaCO3)      | number        | number        |
| Yes      | numeric metric | calcium_mg_l              | Calcium (mg/L)               | number        | number        |
| Yes      | numeric metric | specific_conductance_s_cm | Specific Conductance (?S/cm) | number        | number        |
| Yes      | numeric metric | temperature_f             | Temperature ? (?F)           | number        | number        |
| Yes      | numeric metric | ortho_phosphate_mg_l      | ortho-Phosphate ?? (mg/L)    | number        | number        |
| Yes      | numeric metric | lead_g_l                  | Lead (?g/L)                  | number        | number        |
| Yes      | numeric metric | copper_mg_l               | Copper (mg/L)                | number        | number        |
```

## Time Field

```ls
Value = sample_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:g63j-swsd d:2014-07-08T00:00:00.000Z m:ortho_phosphate_mg_l=2.07 m:sample_site=10750 m:temperature_f=63 m:calcium_mg_l=5.58 m:copper_mg_l=0.005 m:lead_g_l=0 m:ph_unit=7.18 m:specific_conductance_s_cm=84 m:alkalinity_mg_l_caco3=14

series e:g63j-swsd d:2014-07-08T00:00:00.000Z m:ortho_phosphate_mg_l=2.18 m:sample_site=21550 m:temperature_f=65 m:calcium_mg_l=5.56 m:copper_mg_l=0.008 m:lead_g_l=0 m:ph_unit=7.25 m:specific_conductance_s_cm=85 m:alkalinity_mg_l_caco3=14.3

series e:g63j-swsd d:2014-07-08T00:00:00.000Z m:ortho_phosphate_mg_l=2.14 m:sample_site=22250 m:temperature_f=64 m:calcium_mg_l=5.69 m:copper_mg_l=0.008 m:lead_g_l=0 m:ph_unit=7.24 m:specific_conductance_s_cm=87 m:alkalinity_mg_l_caco3=15
```

## Meta Commands

```ls
metric m:sample_site p:integer l:"Sample Site" t:dataTypeName=number

metric m:ph_unit p:float l:"pH ?(Unit)" t:dataTypeName=number

metric m:alkalinity_mg_l_caco3 p:float l:"Alkalinity (mg/L CaCO3)" t:dataTypeName=number

metric m:calcium_mg_l p:float l:"Calcium (mg/L)" t:dataTypeName=number

metric m:specific_conductance_s_cm p:integer l:"Specific Conductance (?S/cm)" t:dataTypeName=number

metric m:temperature_f p:integer l:"Temperature ? (?F)" t:dataTypeName=number

metric m:ortho_phosphate_mg_l p:float l:"ortho-Phosphate ?? (mg/L)" t:dataTypeName=number

metric m:lead_g_l p:float l:"Lead (?g/L)" t:dataTypeName=number

metric m:copper_mg_l p:float l:"Copper (mg/L)" t:dataTypeName=number

entity e:g63j-swsd l:"Distribution Sites LCR Monitoring Results" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/g63j-swsd

property e:g63j-swsd t:meta.view v:id=g63j-swsd v:category=Environment v:averageRating=0 v:name="Distribution Sites LCR Monitoring Results" v:attribution="Department of Environmental Protection (DEP)"

property e:g63j-swsd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g63j-swsd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| sample_site | sample_date         | ph_unit | alkalinity_mg_l_caco3 | calcium_mg_l | specific_conductance_s_cm | temperature_f | ortho_phosphate_mg_l | lead_g_l | copper_mg_l | 
| =========== | =================== | ======= | ===================== | ============ | ========================= | ============= | ==================== | ======== | =========== | 
| 10750       | 2014-07-08T00:00:00 | 7.18    | 14.0                  | 5.58         | 84                        | 63            | 2.07                 | 0        | 0.005       | 
| 21550       | 2014-07-08T00:00:00 | 7.25    | 14.3                  | 5.56         | 85                        | 65            | 2.18                 | 0        | 0.008       | 
| 22250       | 2014-07-08T00:00:00 | 7.24    | 15.0                  | 5.69         | 87                        | 64            | 2.14                 | 0        | 0.008       | 
| 22950       | 2014-07-08T00:00:00 | 7.21    | 14.3                  | 5.57         | 85                        | 63            | 2.16                 | 0        | 0.008       | 
| 26850       | 2014-07-08T00:00:00 | 7.25    | 14.8                  | 5.81         | 87                        | 63            | 2.11                 | 0        | 0.006       | 
| 30150       | 2014-07-08T00:00:00 | 7.45    | 16.1                  | 5.82         | 90                        | 66            | 2.04                 | 0        | 0.005       | 
| 31050       | 2014-07-08T00:00:00 | 7.82    | 18.0                  | 6.47         | 93                        | 69            | 2.10                 | 0        | 0.005       | 
| 31650       | 2014-07-08T00:00:00 | 7.60    | 16.1                  | 5.61         | 89                        | 62            | 1.95                 | 0        | 0.007       | 
| 31950       | 2014-07-08T00:00:00 | 7.46    | 14.5                  | 5.61         | 87                        | 64            | 2.07                 | 0        | 0.007       | 
| 33550       | 2014-07-08T00:00:00 | 7.46    | 15.8                  | 5.69         | 89                        | 63            | 1.98                 | 0        | 0.007       | 
```