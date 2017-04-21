# Maryland Department of the Environment GOPI Performance Measure Dashboard

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-department-of-the-environment-gopi-performance-measure-dashboard) |
| Metadata | [Link](https://data.maryland.gov/api/views/tk5h-jegj) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tk5h-jegj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tk5h-jegj/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tk5h-jegj |
| Name | Maryland Department of the Environment GOPI Performance Measure Dashboard |
| Attribution | Maryland Department of the Environment |
| Category | Energy and Environment |
| Created | 2016-06-28T15:54:25Z |
| Publication Date | 2016-10-25T02:52:28Z |

## Description

This data set reports the performance measures for the Maryland Department of the Environment that are being reported to the Governor's Office of Performance Improvement.  These measures are updated annually for the fiscal year.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                                      | Name                                                                                                                                            | Data Type     | Render Type   |
| ======== | ============== | =============================================================================================================================================== | =============================================================================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                                                                                            | Date                                                                                                                                            | calendar_date | calendar_date |
| No       |                | year                                                                                                                                            | Year                                                                                                                                            | number        | number        |
| Yes      | numeric metric | percent_of_required_phosphorous_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load | Percent of required phosphorous reduction achieved relative to the 2025 pollution reductions set by the Chesapeake Bay Total Maximum Daily Load | percent       | percent       |
| Yes      | numeric metric | percent_of_required_nitrogen_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load    | Percent of required nitrogen reduction achieved relative to the 2025 pollution reductions set by the Chesapeake Bay Total Maximum Daily Load    | percent       | percent       |
| Yes      | numeric metric | percent_of_required_sediment_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load    | Percent of required sediment reduction achieved relative to the 2025 pollution reductions set by the Chesapeake Bay Total Maximum Daily Load    | percent       | percent       |
| Yes      | numeric metric | percentage_of_marylanders_served_by_public_water_systems_that_are_in_significant_compliance_with_all_new_and_existing_regulations               | Percentage of Marylanders served by public water systems that are in significant compliance with all new and existing regulations               | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:tk5h-jegj d:2010-06-30T00:00:00.000Z m:percent_of_required_nitrogen_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=-7.5 m:percentage_of_marylanders_served_by_public_water_systems_that_are_in_significant_compliance_with_all_new_and_existing_regulations=80 m:percent_of_required_phosphorous_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=0.15 m:percent_of_required_sediment_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=42.46

series e:tk5h-jegj d:2011-06-30T00:00:00.000Z m:percent_of_required_nitrogen_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=16.68 m:percentage_of_marylanders_served_by_public_water_systems_that_are_in_significant_compliance_with_all_new_and_existing_regulations=83 m:percent_of_required_phosphorous_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=35.06 m:percent_of_required_sediment_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=139.82

series e:tk5h-jegj d:2012-06-30T00:00:00.000Z m:percent_of_required_nitrogen_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=18.43 m:percentage_of_marylanders_served_by_public_water_systems_that_are_in_significant_compliance_with_all_new_and_existing_regulations=92 m:percent_of_required_phosphorous_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=24.37 m:percent_of_required_sediment_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load=48.71
```

## Meta Commands

```ls
metric m:percent_of_required_phosphorous_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load p:float l:"Percent of required phosphorous reduction achieved relative to the 2025 pollution reductions set by the Chesapeake Bay Total Maximum Daily Load" t:dataTypeName=percent

metric m:percent_of_required_nitrogen_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load p:float l:"Percent of required nitrogen reduction achieved relative to the 2025 pollution reductions set by the Chesapeake Bay Total Maximum Daily Load" t:dataTypeName=percent

metric m:percent_of_required_sediment_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load p:float l:"Percent of required sediment reduction achieved relative to the 2025 pollution reductions set by the Chesapeake Bay Total Maximum Daily Load" t:dataTypeName=percent

metric m:percentage_of_marylanders_served_by_public_water_systems_that_are_in_significant_compliance_with_all_new_and_existing_regulations p:integer l:"Percentage of Marylanders served by public water systems that are in significant compliance with all new and existing regulations" t:dataTypeName=percent

entity e:tk5h-jegj l:"Maryland Department of the Environment GOPI Performance Measure Dashboard" t:attribution="Maryland Department of the Environment" t:url=https://data.maryland.gov/api/views/tk5h-jegj

property e:tk5h-jegj t:meta.view v:id=tk5h-jegj v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Department of the Environment GOPI Performance Measure Dashboard" v:attribution="Maryland Department of the Environment"

property e:tk5h-jegj t:meta.view.license v:name="Public Domain"

property e:tk5h-jegj t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:tk5h-jegj t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | year | percent_of_required_phosphorous_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load | percent_of_required_nitrogen_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load | percent_of_required_sediment_reduction_achieved_relative_to_the_2025_pollution_reductions_set_by_the_chesapeake_bay_total_maximum_daily_load | percentage_of_marylanders_served_by_public_water_systems_that_are_in_significant_compliance_with_all_new_and_existing_regulations | 
| =================== | ==== | =============================================================================================================================================== | ============================================================================================================================================ | ============================================================================================================================================ | ================================================================================================================================= | 
| 2010-06-30T00:00:00 | 2010 | 0.15                                                                                                                                            | -7.50                                                                                                                                        | 42.46                                                                                                                                        | 80                                                                                                                                | 
| 2011-06-30T00:00:00 | 2011 | 35.06                                                                                                                                           | 16.68                                                                                                                                        | 139.82                                                                                                                                       | 83                                                                                                                                | 
| 2012-06-30T00:00:00 | 2012 | 24.37                                                                                                                                           | 18.43                                                                                                                                        | 48.71                                                                                                                                        | 92                                                                                                                                | 
| 2013-06-30T00:00:00 | 2013 | 61.62                                                                                                                                           | 40.63                                                                                                                                        | 313.19                                                                                                                                       | 98                                                                                                                                | 
| 2014-06-30T00:00:00 | 2014 | 77.83                                                                                                                                           | 19.79                                                                                                                                        | 211.96                                                                                                                                       | 96                                                                                                                                | 
| 2015-06-30T00:00:00 | 2015 | 101.44                                                                                                                                          | 35.80                                                                                                                                        | 325.74                                                                                                                                       | 90                                                                                                                                | 
| 2016-06-30T00:00:00 | 2016 |                                                                                                                                                 |                                                                                                                                              |                                                                                                                                              | 98                                                                                                                                | 
```