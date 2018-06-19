# Water Use Restrictions - Summary of 15 RCNY Chapters 20 and 21

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-use-restrictions-summary-of-15-rcny-chapters-20-and-21-9a99f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/27vb-augk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/27vb-augk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/27vb-augk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 27vb-augk |
| Name | Water Use Restrictions - Summary of 15 RCNY Chapters 20 and 21 |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, water, use, restrictions, restriction, water use restrictions, healthy living |
| Created | 2013-02-01T20:33:32Z |
| Publication Date | 2013-06-21T19:45:41Z |

## Description

A summary of the restrictions placed on water use during non-emergency and drought emergency conditions.

## Columns

```ls
| Included | Schema Type | Field Name                                                                               | Name                                                                                        | Data Type | Render Type |
| ======== | =========== | ======================================================================================== | =========================================================================================== | ========= | =========== |
| No       | time        | :updated_at                                                                              | updated_at                                                                                  | meta_data | meta_data   |
| Yes      | series tag  | activity                                                                                 | Activity                                                                                    | text      | text        |
| Yes      | series tag  | non_emergency_restrictions_including_normal_drought_watch_and_drought_warning_conditions | Non Emergency Restrictions (including Normal, Drought Watch and Drought Warning conditions) | text      | text        |
| Yes      | series tag  | drought_emergency_stage_i                                                                | Drought Emergency - Stage I                                                                 | text      | text        |
| Yes      | series tag  | drought_emergency_stage_ii                                                               | Drought Emergency - Stage II                                                                | text      | text        |
| Yes      | series tag  | drought_emergency_stage_iii                                                              | Drought Emergency - Stage III                                                               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:27vb-augk d:2013-02-01T12:33:33.000Z t:drought_emergency_stage_i="Prohibited, greater fines" t:non_emergency_restrictions_including_normal_drought_watch_and_drought_warning_conditions=Prohibited t:drought_emergency_stage_iii="Same as Stage I" t:drought_emergency_stage_ii="Same as Stage I" t:activity="Leaks and Waste" m:row_number.27vb-augk=1

series e:27vb-augk d:2013-02-01T12:33:33.000Z t:drought_emergency_stage_i="Prohibited except where required by law or health and safety rules, or if well water is used" t:non_emergency_restrictions_including_normal_drought_watch_and_drought_warning_conditions="Non-commercial: Hose must have a self-closing nozzle.  Commercial: At least 75% of water must be recirculated or well water" t:drought_emergency_stage_iii="Same as Stage I" t:drought_emergency_stage_ii="Same as Stage I" t:activity="Vehicle Washing" m:row_number.27vb-augk=2

series e:27vb-augk d:2013-02-01T12:33:33.000Z t:drought_emergency_stage_i="Prohibited, except as required by Code or health and safety rules" t:non_emergency_restrictions_including_normal_drought_watch_and_drought_warning_conditions="Prohibited November 1 -  March 31, and also during other months from 11 am to 7 pm." t:drought_emergency_stage_iii=Prohibited t:drought_emergency_stage_ii=Prohibited t:activity="Washing Sidewalks, Driveways, Streets" m:row_number.27vb-augk=3
```

## Meta Commands

```ls
metric m:row_number.27vb-augk p:long l:"Row Number"

entity e:27vb-augk l:"Water Use Restrictions - Summary of 15 RCNY Chapters 20 and 21" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/27vb-augk

property e:27vb-augk t:meta.view v:id=27vb-augk v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/residents/waterrest_wide.shtml v:averageRating=0 v:name="Water Use Restrictions - Summary of 15 RCNY Chapters 20 and 21" v:attribution="Department of Environmental Protection (DEP)"

property e:27vb-augk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:27vb-augk t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | activity                              | non_emergency_restrictions_including_normal_drought_watch_and_drought_warning_conditions                                                               | drought_emergency_stage_i                                                                                                                                                        | drought_emergency_stage_ii                                                                                                                                                       | drought_emergency_stage_iii                                                                                                                                                      | 
| =========== | ===================================== | ====================================================================================================================================================== | ================================================================================================================================================================================ | ================================================================================================================================================================================ | ================================================================================================================================================================================ | 
| 1359722013  | Leaks and Waste                       | Prohibited                                                                                                                                             | Prohibited, greater fines                                                                                                                                                        | Same as Stage I                                                                                                                                                                  | Same as Stage I                                                                                                                                                                  | 
| 1359722013  | Vehicle Washing                       | Non-commercial: Hose must have a self-closing nozzle.  Commercial: At least 75% of water must be recirculated or well water                            | Prohibited except where required by law or health and safety rules, or if well water is used                                                                                     | Same as Stage I                                                                                                                                                                  | Same as Stage I                                                                                                                                                                  | 
| 1359722013  | Washing Sidewalks, Driveways, Streets | Prohibited November 1 -  March 31, and also during other months from 11 am to 7 pm.                                                                    | Prohibited, except as required by Code or health and safety rules                                                                                                                | Prohibited                                                                                                                                                                       | Prohibited                                                                                                                                                                       | 
| 1359722013  | Watering Lawns/Turf                   | Hoses and sprinklers prohibited November 1 -  March 31, and also during other months from 11 am to 7 pm. Automatic sprinklers must have a rain sensor. | Further restricted to 7-9 am and 7-9 pm, even number addresses on even dates, odd number addresses on odd dates. Golf courses may water only tees and greens.                    | Prohibited                                                                                                                                                                       | Prohibited                                                                                                                                                                       | 
| 1359722013  | Watering Non-Turf Plants              | Hoses and sprinklers prohibited November 1 -  March 31, and also during other months from 11am to 7 pm. Automatic sprinklers must have a rain sensor.  | Only hand-held watering containers, hoses restricted to less than 5 gpm, or low-pressure/low-flow irrigation can be used                                                         | Same as Stage I except use of hand-held containers is limited to recycled water or (if not feasible) to the minimum amount necessary to prevent permanent plant damage.          | Same as Stage II except wherever possible use recycled or well water (before using City water) for watering all plant material.                                                  | 
| 1359722013  | Ornamental Fountains                  | Water must be recirculated                                                                                                                             | Prohibited                                                                                                                                                                       | Prohibited                                                                                                                                                                       | Prohibited                                                                                                                                                                       | 
| 1359722013  | Water/Sewer Rates                     | none                                                                                                                                                   | DEP Commissioner may ask the New York City Water Board to consider a "Drought Emergency Contingency Rate Plan" to increase rates to encourage conservation during the Emergency. | DEP Commissioner may ask the New York City Water Board to consider a "Drought Emergency Contingency Rate Plan" to increase rates to encourage conservation during the Emergency. | DEP Commissioner may ask the New York City Water Board to consider a "Drought Emergency Contingency Rate Plan" to increase rates to encourage conservation during the Emergency. | 
| 1359722013  | Water Served In Restaurants           | Only if requested by patron                                                                                                                            | same                                                                                                                                                                             | same                                                                                                                                                                             | same                                                                                                                                                                             | 
| 1359722013  | Swimming Pools                        | none                                                                                                                                                   | Must recirculate, fill 1 time per year, top off minimally as needed                                                                                                              | Only pools open to the public may be filled or maintained                                                                                                                        | same                                                                                                                                                                             | 
| 1359722013  | Showerheads                           | Sale or installation of products using more than 2.5 gpm is prohibited                                                                                 | All showerheads in use must use 2.5 gpm or less                                                                                                                                  | same                                                                                                                                                                             | same                                                                                                                                                                             | 
```