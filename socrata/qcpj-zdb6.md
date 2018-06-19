# Air Monitoring Station Locations & Attributes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-monitoring-station-locations-attributes) |
| Metadata | [Link](https://data.ny.gov/api/views/qcpj-zdb6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qcpj-zdb6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qcpj-zdb6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qcpj-zdb6 |
| Name | Air Monitoring Station Locations & Attributes |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | air monitoring, site locations, sites, statewide, new york |
| Created | 2014-02-10T17:35:36Z |
| Publication Date | 2015-12-15T20:19:44Z |

## Description

Location maps of monitoring sites and measured parameters in the NY State Ambient Air Monitoring Network

## Columns

```ls
| Included | Schema Type | Field Name                                     | Name                  | Data Type | Render Type |
| ======== | =========== | ============================================== | ===================== | ========= | =========== |
| No       | time        | :updated_at                                    | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | region                                         | Region                | text      | number      |
| Yes      | series tag  | site_id                                        | Site ID               | text      | text        |
| Yes      | series tag  | monitor_type                                   | Monitor Type          | text      | text        |
| Yes      | series tag  | county                                         | County                | text      | text        |
| Yes      | series tag  | site_name                                      | Site Name             | text      | text        |
| Yes      | series tag  | air_quality_system_id                          | Air Quality System ID | text      | number      |
| No       |             | latitude                                       | Latitude              | number    | number      |
| No       |             | longitude                                      | Longitude             | number    | number      |
| Yes      | series tag  | ozone                                          | Ozone                 | text      | text        |
| Yes      | series tag  | sulfur_dioxide_so2                             | SO2                   | text      | text        |
| Yes      | series tag  | nitrogen_oxides_nox                            | NOX                   | text      | text        |
| Yes      | series tag  | carbon_monoxide_co                             | CO                    | text      | text        |
| Yes      | series tag  | manual_pm_2_5                                  | PM-2.5                | text      | text        |
| Yes      | series tag  | continuous_pm_2_5                              | CPM-2.5               | text      | text        |
| Yes      | series tag  | manual_pm_10                                   | PM-10                 | text      | text        |
| Yes      | series tag  | continuous_pm_10                               | CPM-10                | text      | text        |
| Yes      | series tag  | tsp_lead                                       | Lead                  | text      | text        |
| Yes      | series tag  | manual_pm_2_5_chemical_speciation              | Speciation            | text      | text        |
| Yes      | series tag  | manual_pm_2_5_continuous_speciation            | Continuous Speciation | text      | text        |
| Yes      | series tag  | metals                                         | Metals                | text      | text        |
| Yes      | series tag  | toxics                                         | Toxics                | text      | text        |
| Yes      | series tag  | carbonyls                                      | Carbonyls             | text      | text        |
| Yes      | series tag  | acid_rain                                      | Acid Rain             | text      | text        |
| Yes      | series tag  | photochemical_assessment_ozone_precursors_pams | PAMS                  | text      | text        |
| Yes      | series tag  | mercury                                        | Mercury               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:qcpj-zdb6 d:2015-12-01T15:00:25.000Z t:region=1 t:continuous_pm_2_5=Y t:county=Nassau t:sulfur_dioxide_so2=Y t:air_quality_system_id=360590005 t:site_id=2950-10 t:site_name="Eisenhower Park" t:monitor_type=C m:row_number.qcpj-zdb6=1

series e:qcpj-zdb6 d:2015-12-01T15:00:25.000Z t:region=1 t:manual_pm_2_5=Y t:ozone=Y t:county=Suffolk t:air_quality_system_id=361030002 t:site_id=5150-02 t:site_name=Babylon t:monitor_type=MC m:row_number.qcpj-zdb6=2

series e:qcpj-zdb6 d:2015-12-01T15:00:25.000Z t:region=1 t:ozone=Y t:continuous_pm_2_5=Y t:county=Suffolk t:sulfur_dioxide_so2=Y t:air_quality_system_id=361030009 t:site_id=5150-10 t:site_name=Holtsville t:monitor_type=C m:row_number.qcpj-zdb6=3
```

## Meta Commands

```ls
metric m:row_number.qcpj-zdb6 p:long l:"Row Number"

entity e:qcpj-zdb6 l:"Air Monitoring Station Locations & Attributes" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/qcpj-zdb6

property e:qcpj-zdb6 t:meta.view v:id=qcpj-zdb6 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8540.html v:averageRating=0 v:name="Air Monitoring Station Locations & Attributes" v:attribution="Department of Environmental Conservation"

property e:qcpj-zdb6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qcpj-zdb6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | region | site_id | monitor_type | county   | site_name       | air_quality_system_id | latitude | longitude | ozone | sulfur_dioxide_so2 | nitrogen_oxides_nox | carbon_monoxide_co | manual_pm_2_5 | continuous_pm_2_5 | manual_pm_10 | continuous_pm_10 | tsp_lead | manual_pm_2_5_chemical_speciation | manual_pm_2_5_continuous_speciation | metals | toxics | carbonyls | acid_rain | photochemical_assessment_ozone_precursors_pams | mercury | 
| =========== | ====== | ======= | ============ | ======== | =============== | ===================== | ======== | ========= | ===== | ================== | =================== | ================== | ============= | ================= | ============ | ================ | ======== | ================================= | =================================== | ====== | ====== | ========= | ========= | ============================================== | ======= | 
| 1448982025  | 1      | 2950-10 | C            | Nassau   | Eisenhower Park | 360590005             | 40.74316 | -73.58549 |       | Y                  |                     |                    |               | Y                 |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 1      | 5150-02 | MC           | Suffolk  | Babylon         | 361030002             | 40.74529 | -73.41919 | Y     |                    |                     |                    | Y             |                   |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 1      | 5150-10 | C            | Suffolk  | Holtsville      | 361030009             | 40.82799 | -73.05754 | Y     | Y                  |                     |                    |               | Y                 |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 1      | 5155-01 | C            | Suffolk  | Riverhead       | 361030004             | 40.96078 | -72.71238 | Y     |                    |                     |                    |               |                   |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 2      | 7093-08 | M            | New York | JHS #45         | 360610079             | 40.7997  | -73.93432 |       |                    |                     |                    | Y             |                   |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 2      | 7093-15 | C            | New York | IS #143         | 360610115             | 40.84888 | -73.93059 |       |                    |                     |                    |               | Y                 |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 2      | 7093-21 | MC           | New York | PS #19          | 360610128             | 40.73    | -73.98446 |       |                    |                     |                    | Y             | Y                 | Y            |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 2      | 7093-24 | MC           | New York | Division St     | 360610134             | 40.71436 | -73.99518 |       |                    |                     |                    | Y             | Y                 | Y            |                  |          | Y                                 |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 2      | 7093-25 | C            | New York | CCNY            | 360610135             | 40.81976 | -73.94825 | Y     |                    |                     | Y                  |               | Y                 |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
| 1448982025  | 2      | 7094-05 | C            | Bronx    | Morrisania II   | 360050080             | 40.83606 | -73.92009 |       |                    |                     |                    |               | Y                 |              |                  |          |                                   |                                     |        |        |           |           |                                                |         | 
```