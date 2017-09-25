# Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sept-2014-ecy-stations-with-exceeded-criteria-for-fecal-bacteria-temperature-oxygen-and-ph-f89c7) |
| Metadata | [Link](https://data.wa.gov/api/views/spy8-d7us) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/spy8-d7us/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/spy8-d7us/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | spy8-d7us |
| Name | Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH |
| Attribution | Washingotn State Department of Ecology |
| Category | Natural Resources & Environment |
| Created | 2014-11-10T17:17:47Z |
| Publication Date | 2014-11-10T17:20:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | station                  | Station                  | text          | text          |
| Yes      | series tag     | station_name             | Station Name             | text          | text          |
| Yes      | time           | wq_violation_date        | WQ Violation Date        | calendar_date | calendar_date |
| No       |                | time                     | Time                     | calendar_date | calendar_date |
| Yes      | series tag     | variable_units           | Variable/Units           | text          | text          |
| Yes      | numeric metric | sample_result_or_geo_mn  | Sample Result or geo.mn  | number        | number        |
| Yes      | numeric metric | criterion                | Criterion                | number        | number        |
| Yes      | numeric metric | percent_exceeds_standard | Percent exceeds standard | number        | number        |
```

## Time Field

```ls
Value = wq_violation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = time
```

## Data Commands

```ls
series e:spy8-d7us d:2014-09-09T00:00:00.000Z t:station_name="Pend Oreille R @ Newport" t:station=62A150 t:variable_units="pH (pH)" m:criterion=8.5 m:percent_exceeds_standard=0.6 m:sample_result_or_geo_mn=8.6

series e:spy8-d7us d:2014-09-09T00:00:00.000Z t:station_name="Pend Oreille R @ Metaline Falls" t:station=62A090 t:variable_units="pH (pH)" m:criterion=8.5 m:percent_exceeds_standard=1.3 m:sample_result_or_geo_mn=8.6

series e:spy8-d7us d:2014-09-08T00:00:00.000Z t:station_name="Columbia R @ Northport" t:station=61A070 t:variable_units="Oxygen (mg/L)" m:criterion=9.5 m:percent_exceeds_standard=7.8 m:sample_result_or_geo_mn=8.8
```

## Meta Commands

```ls
metric m:sample_result_or_geo_mn p:double l:"Sample Result or geo.mn" t:dataTypeName=number

metric m:criterion p:double l:Criterion t:dataTypeName=number

metric m:percent_exceeds_standard p:double l:"Percent exceeds standard" t:dataTypeName=number

entity e:spy8-d7us l:"Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH" t:attribution="Washingotn State Department of Ecology" t:url=https://data.wa.gov/api/views/spy8-d7us

property e:spy8-d7us t:meta.view d:2017-09-25T07:27:40.679Z v:averageRating=0 v:name="Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH" v:attribution="Washingotn State Department of Ecology" v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html v:id=spy8-d7us v:category="Natural Resources & Environment"

property e:spy8-d7us t:meta.view.owner d:2017-09-25T07:27:40.679Z v:displayName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:id=q8y9-svx9 v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB

property e:spy8-d7us t:meta.view.tableauthor d:2017-09-25T07:27:40.679Z v:displayName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:id=q8y9-svx9 v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB
```

## Top Records

```ls
| station | station_name                    | wq_violation_date   | time | variable_units      | sample_result_or_geo_mn | criterion | percent_exceeds_standard | 
| ======= | =============================== | =================== | ==== | =================== | ======================= | ========= | ======================== | 
| 62A150  | Pend Oreille R @ Newport        | 2014-09-09T00:00:00 |      | pH (pH)             | 8.6                     | 8.5       | 0.6                      | 
| 62A090  | Pend Oreille R @ Metaline Falls | 2014-09-09T00:00:00 |      | pH (pH)             | 8.6                     | 8.5       | 1.3                      | 
| 61A070  | Columbia R @ Northport          | 2014-09-08T00:00:00 |      | Oxygen (mg/L)       | 8.8                     | 9.5       | 7.8                      | 
| 61A070  | Columbia R @ Northport          | 2014-09-08T00:00:00 |      | Temperature (deg C) | 17.5                    | 16        | 9.4                      | 
| 60A070  | Kettle R nr Barstow             | 2014-09-08T00:00:00 |      | Fecal Coliform      |                         | 100       | 60                       | 
| 60A070  | Kettle R nr Barstow             | 2014-09-08T00:00:00 |      | Oxygen (mg/L)       | 9.2                     | 9.5       | 3.7                      | 
| 60A070  | Kettle R nr Barstow             | 2014-09-08T00:00:00 |      | Temperature (deg C) | 17                      | 16        | 6.3                      | 
| 59A080  | Colville R @ Greenwood          | 2014-09-08T00:00:00 |      | pH (pH)             | 8.6                     | 8.5       | 1.3                      | 
| 56A070  | Hangman Cr @ Mouth              | 2014-09-09T00:00:00 |      | pH (pH)             | 8.7                     | 8.5       | 2                        | 
| 55B070  | Little Spokane R nr             | 2014-09-09T00:00:00 |      | Oxygen (mg/L)       | 9.4                     | 9.5       | 0.5                      | 
```