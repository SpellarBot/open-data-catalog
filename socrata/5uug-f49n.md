# Harbor Water Quality

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/harbor-sampling-data-d2de8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5uug-f49n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5uug-f49n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5uug-f49n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5uug-f49n |
| Name | Harbor Water Quality |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, water, harbor, sample, sampling, harbor sampling data, healthy living |
| Created | 2013-01-31T04:28:12Z |
| Publication Date | 2017-04-13T14:56:21Z |

## Description

Harbor water sampling information

## Columns

```ls
| Included | Schema Type | Field Name                | Name                          | Data Type     | Render Type   |
| ======== | =========== | ========================= | ============================= | ============= | ============= |
| Yes      | series tag  | site                      | Site                          | text          | text          |
| Yes      | series tag  | nys_dec_waterbody_class   | NYS DEC Waterbody Class       | text          | text          |
| Yes      | time        | date                      | Date                          | calendar_date | calendar_date |
| Yes      | series tag  | do_mg_l_top               | DO (mg/L) Top                 | text          | text          |
| Yes      | series tag  | do_mg_l_bot               | DO (mg/L) Bot                 | text          | text          |
| Yes      | series tag  | fecal_coliform_100_ml_top | Fecal Coliform (#/100 mL) Top | text          | text          |
| Yes      | series tag  | fecal_coliform_100_ml_bot | Fecal Coliform (#/100 mL) Bot | text          | text          |
| Yes      | series tag  | enterococcus_100_ml_top   | Enterococcus (#/100 mL) Top   | text          | text          |
| Yes      | series tag  | enterococcus_100_ml_bot   | Enterococcus (#/100 mL) Bot   | text          | text          |
| Yes      | series tag  | transparency_secchi_ft    | Transparency (Secchi) ft.     | text          | text          |
| Yes      | series tag  | weather_dry_wet_d_w       | Weather Dry/Wet D/W           | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5uug-f49n d:2015-01-05T00:00:00.000Z t:site=E10 t:transparency_secchi_ft=4.0 t:do_mg_l_top=10.81 t:do_mg_l_bot=10.06 t:fecal_coliform_100_ml_top=28 t:weather_dry_wet_d_w=W t:fecal_coliform_100_ml_bot=NS t:nys_dec_waterbody_class=SB t:enterococcus_100_ml_bot=NS t:enterococcus_100_ml_top=16 m:row_number.5uug-f49n=1

series e:5uug-f49n d:2015-01-05T00:00:00.000Z t:site=E11 t:transparency_secchi_ft=3.0 t:do_mg_l_top=10.59 t:do_mg_l_bot=NS t:fecal_coliform_100_ml_top=256 t:weather_dry_wet_d_w=W t:fecal_coliform_100_ml_bot=NS t:nys_dec_waterbody_class=SB t:enterococcus_100_ml_bot=NS t:enterococcus_100_ml_top=72 m:row_number.5uug-f49n=2

series e:5uug-f49n d:2015-01-14T00:00:00.000Z t:site=E12 t:transparency_secchi_ft=NS t:do_mg_l_top=12.48 t:do_mg_l_bot=NS t:fecal_coliform_100_ml_top=44 t:weather_dry_wet_d_w=D t:fecal_coliform_100_ml_bot=NS t:nys_dec_waterbody_class=SB t:enterococcus_100_ml_bot=NS t:enterococcus_100_ml_top=20 m:row_number.5uug-f49n=3
```

## Meta Commands

```ls
metric m:row_number.5uug-f49n p:long l:"Row Number"

entity e:5uug-f49n l:"Harbor Water Quality" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/5uug-f49n

property e:5uug-f49n t:meta.view v:id=5uug-f49n v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/harborwater/harbor_water_sampling_results.shtml v:averageRating=0 v:name="Harbor Water Quality" v:attribution="Department of Environmental Protection (DEP)"

property e:5uug-f49n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5uug-f49n t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| site | nys_dec_waterbody_class | date                | do_mg_l_top | do_mg_l_bot | fecal_coliform_100_ml_top | fecal_coliform_100_ml_bot | enterococcus_100_ml_top | enterococcus_100_ml_bot | transparency_secchi_ft | weather_dry_wet_d_w | 
| ==== | ======================= | =================== | =========== | =========== | ========================= | ========================= | ======================= | ======================= | ====================== | =================== | 
| E10  | SB                      | 2015-01-05T00:00:00 | 10.81       | 10.06       | 28                        | NS                        | 16                      | NS                      | 4.0                    | W                   | 
| E11  | SB                      | 2015-01-05T00:00:00 | 10.59       | NS          | 256                       | NS                        | 72                      | NS                      | 3.0                    | W                   | 
| E12  | SB                      | 2015-01-14T00:00:00 | 12.48       | NS          | 44                        | NS                        | 20                      | NS                      | NS                     | D                   | 
| E7   | SB                      | 2015-01-05T00:00:00 | 10.36       | 10.62       | 132                       | NS                        | 66                      | NS                      | 3.0                    | W                   | 
| E8   | SB                      | 2015-01-05T00:00:00 | 10.29       | 10.16       | 193                       | NS                        | 75                      | NS                      | 4.0                    | W                   | 
| HR03 | SB                      | 2015-01-14T00:00:00 | NS          | NS          | NS                        | NS                        | NS                      | NS                      | NS                     | D                   | 
| HR1  | SB                      | 2015-01-14T00:00:00 | 12.78       | NS          | 208                       | NS                        | 78                      | NS                      | NS                     | D                   | 
| HR2  | SB                      | 2015-01-14T00:00:00 | NS          | NS          | NS                        | NS                        | NS                      | NS                      | NS                     | D                   | 
| J1   | SB                      | 2015-01-06T00:00:00 | 10.18       | 10.19       | 20                        | NS                        | 4                       | NS                      | 5.0                    | W                   | 
| J10  | SB                      | 2015-01-06T00:00:00 | 10.33       | 10.19       | 53                        | NS                        | 6                       | NS                      | 5.5                    | W                   | 
```