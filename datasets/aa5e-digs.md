# Entry Point LCR Monitoring Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/entry-point-lcr-monitoring-results) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/aa5e-digs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/aa5e-digs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/aa5e-digs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | aa5e-digs |
| Name | Entry Point LCR Monitoring Results |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | lcr, monitoring, entry point |
| Created | 2015-02-24T18:25:50Z |
| Publication Date | 2017-01-23T21:18:54Z |

## Description

Daily results from the entry points for orthophosphate, pH, temperature, conductivity and monthly alkalinity, calcium, lead and copper - Bi annually updated

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                          | Data Type     | Render Type   |
| ======== | ============== | ========================= | ============================= | ============= | ============= |
| Yes      | series tag     | sample_site               | Sample Site                   | text          | text          |
| Yes      | time           | sample_date               | Sample Date                   | calendar_date | calendar_date |
| Yes      | numeric metric | ph_unit                   | pH ?(Unit)                    | number        | number        |
| Yes      | numeric metric | alkalinity_mg_l_caco3     | Alkalinity (mg/L CaCO3)       | number        | number        |
| Yes      | numeric metric | calcium_mg_l              | Calcium (mg/L)                | number        | number        |
| Yes      | numeric metric | specific_conductance_s_cm | Specific Conductance ( ?S/cm) | number        | number        |
| Yes      | numeric metric | temperature_f             | Temperature ? (?F)            | number        | number        |
| Yes      | numeric metric | ortho_phosphate_mg_l      | ortho-Phosphate ?? (mg/L)     | number        | number        |
| Yes      | numeric metric | lead_g_l                  | Lead (?g/L)                   | number        | number        |
| Yes      | numeric metric | copper_mg_l               | Copper (mg/L)                 | number        | number        |
```

## Time Field

```ls
Value = sample_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:aa5e-digs d:2014-07-01T00:00:00.000Z t:sample_site=1S04 m:ortho_phosphate_mg_l=1.99 m:temperature_f=62 m:ph_unit=7.24 m:specific_conductance_s_cm=85

series e:aa5e-digs d:2014-07-02T00:00:00.000Z t:sample_site=1S04 m:ortho_phosphate_mg_l=1.99 m:temperature_f=63 m:ph_unit=7.34 m:specific_conductance_s_cm=86

series e:aa5e-digs d:2014-07-03T00:00:00.000Z t:sample_site=1S04 m:ortho_phosphate_mg_l=2.08 m:temperature_f=62 m:ph_unit=7.31 m:specific_conductance_s_cm=85
```

## Meta Commands

```ls
metric m:ph_unit p:float l:"pH ?(Unit)" t:dataTypeName=number

metric m:alkalinity_mg_l_caco3 p:float l:"Alkalinity (mg/L CaCO3)" t:dataTypeName=number

metric m:calcium_mg_l p:float l:"Calcium (mg/L)" t:dataTypeName=number

metric m:specific_conductance_s_cm p:integer l:"Specific Conductance ( ?S/cm)" t:dataTypeName=number

metric m:temperature_f p:integer l:"Temperature ? (?F)" t:dataTypeName=number

metric m:ortho_phosphate_mg_l p:float l:"ortho-Phosphate ?? (mg/L)" t:dataTypeName=number

metric m:lead_g_l p:integer l:"Lead (?g/L)" t:dataTypeName=number

metric m:copper_mg_l p:float l:"Copper (mg/L)" t:dataTypeName=number

entity e:aa5e-digs l:"Entry Point LCR Monitoring Results" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/aa5e-digs

property e:aa5e-digs t:meta.view v:id=aa5e-digs v:category=Environment v:averageRating=0 v:name="Entry Point LCR Monitoring Results" v:attribution="Department of Environmental Protection (DEP)"

property e:aa5e-digs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:aa5e-digs t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| sample_site | sample_date         | ph_unit | alkalinity_mg_l_caco3 | calcium_mg_l | specific_conductance_s_cm | temperature_f | ortho_phosphate_mg_l | lead_g_l | copper_mg_l | 
| =========== | =================== | ======= | ===================== | ============ | ========================= | ============= | ==================== | ======== | =========== | 
| 1S04        | 2014-07-01T00:00:00 | 7.24    |                       |              | 85                        | 62            | 1.99                 |          |             | 
| 1S04        | 2014-07-02T00:00:00 | 7.34    |                       |              | 86                        | 63            | 1.99                 |          |             | 
| 1S04        | 2014-07-03T00:00:00 | 7.31    |                       |              | 85                        | 62            | 2.08                 |          |             | 
| 1S04        | 2014-07-04T00:00:00 | 7.27    |                       |              | 84                        | 62            | 1.98                 |          |             | 
| 1S04        | 2014-07-05T00:00:00 | 7.27    |                       |              | 86                        | 60            | 1.94                 |          |             | 
| 1S04        | 2014-07-06T00:00:00 | 7.21    |                       |              | 86                        | 60            | 1.94                 |          |             | 
| 1S04        | 2014-07-07T00:00:00 | 7.29    |                       |              | 86                        | 62            | 2.09                 |          |             | 
| 1S04        | 2014-07-08T00:00:00 | 7.16    |                       |              | 86                        | 62            | 2.07                 |          |             | 
| 1S07*       | 2014-07-08T00:00:00 | 7.21    | 14.8                  | 5.52         | 86                        | 61            | 1.86                 | 0        | 0.006       | 
| 1S04        | 2014-07-09T00:00:00 | 7.28    |                       |              | 85                        | 61            | 2.07                 |          |             | 
```