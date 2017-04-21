# DNR-WPP-Chronic Violators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dnr-wpp-chronic-violators) |
| Metadata | [Link](https://data.mo.gov/api/views/szw8-jbqy) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/szw8-jbqy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/szw8-jbqy/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | szw8-jbqy |
| Name | DNR-WPP-Chronic Violators |
| Attribution | DNR Water Pollution Program |
| Category | Natural Resources |
| Created | 2016-03-15T13:21:40Z |
| Publication Date | 2017-04-06T15:01:33Z |

## Description

Listing of Chronic Violators for DNR

## Columns

```ls
| Included | Schema Type | Field Name                                                 | Name                                                                | Data Type | Render Type |
| ======== | =========== | ========================================================== | =================================================================== | ========= | =========== |
| No       | time        | :updated_at                                                | updated_at                                                          | meta_data | meta_data   |
| Yes      | series tag  | county                                                     | County                                                              | text      | text        |
| Yes      | series tag  | population_served                                          | System Name:Population Served                                       | text      | text        |
| Yes      | series tag  | location_or_nearest_town                                   | Location or Nearest Town                                            | text      | text        |
| Yes      | series tag  | pws_id                                                     | PWS ID#                                                             | text      | text        |
| Yes      | series tag  | months_of_major_monitoring_violations_feb_2015_to_jan_2016 | Months of Major Monitoring Violations (March 2016 to February 2017) | text      | text        |
| Yes      | series tag  | recent_results_ending_jan_2016                             | Recent Results                                                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:szw8-jbqy d:2017-02-03T20:46:21.000Z t:county=Camden t:months_of_major_monitoring_violations_feb_2015_to_jan_2016="May 2016, July 2016, August 2016, September 2016, October 2016" t:recent_results_ending_jan_2016="Samples collected in June 2016 tested absent for total coliform bacteria" t:population_served="Niangua Falls: 25" t:pws_id=MO3218236 t:location_or_nearest_town="Wharf Place; Camdenton" m:row_number.szw8-jbqy=1

series e:szw8-jbqy d:2017-03-15T19:41:51.000Z t:county=Camden t:months_of_major_monitoring_violations_feb_2015_to_jan_2016="June 2016, July 2016, September 2016, October 2016, December 2016" t:recent_results_ending_jan_2016="Samples collected in February 2017 tested absent for total coliform bacteria" t:population_served="Osage Village Inn: 25" t:pws_id=MO3191738 t:location_or_nearest_town="Highway 54; Osage Beach" m:row_number.szw8-jbqy=2

series e:szw8-jbqy d:2017-03-15T19:45:16.000Z t:county=Perry t:months_of_major_monitoring_violations_feb_2015_to_jan_2016="April 2016, July 2016, September 2016, October 2016" t:recent_results_ending_jan_2016="Samples collected in February 2017 tested absent for total coliform bacteria" t:population_served="Bills Place: 40" t:pws_id=MO4218555 t:location_or_nearest_town="Hwy B; Perryville" m:row_number.szw8-jbqy=3
```

## Meta Commands

```ls
metric m:row_number.szw8-jbqy p:long l:"Row Number"

entity e:szw8-jbqy l:"DNR-WPP-Chronic Violators" t:attribution="DNR Water Pollution Program" t:url=https://data.mo.gov/api/views/szw8-jbqy

property e:szw8-jbqy t:meta.view v:id=szw8-jbqy v:category="Natural Resources" v:attributionLink=http://dnr.mo.gov/env/wpp/chronic/ v:averageRating=0 v:name="DNR-WPP-Chronic Violators" v:attribution="DNR Water Pollution Program"

property e:szw8-jbqy t:meta.view.owner v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:displayName="Renee Wright"

property e:szw8-jbqy t:meta.view.tableauthor v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:roleName=editor v:displayName="Renee Wright"
```

## Top Records

```ls
| :updated_at | county | population_served            | location_or_nearest_town     | pws_id    | months_of_major_monitoring_violations_feb_2015_to_jan_2016                                                                                                   | recent_results_ending_jan_2016                                                      | 
| =========== | ====== | ============================ | ============================ | ========= | ============================================================================================================================================================ | =================================================================================== | 
| 1486154781  | Camden | Niangua Falls: 25            | Wharf Place; Camdenton       | MO3218236 | May 2016, July 2016, August 2016, September 2016, October 2016                                                                                               | Samples collected in June 2016 tested absent for total coliform bacteria            | 
| 1489606911  | Camden | Osage Village Inn: 25        | Highway 54; Osage Beach      | MO3191738 | June 2016, July 2016, September 2016, October 2016, December 2016                                                                                            | Samples collected in February 2017 tested absent for total coliform bacteria        | 
| 1489607116  | Perry  | Bills Place: 40              | Hwy B; Perryville            | MO4218555 | April 2016, July 2016, September 2016, October 2016                                                                                                          | Samples collected in February 2017 tested absent for total coliform bacteria        | 
| 1491488997  | Andrew | Amazonia: 312                | State Highway K; Amazonia    | MO1010013 | March 2016, June 2016, July 2016, August 2016                                                                                                                | Samples collected in March 2017 tested absent for total coliform bacteria           | 
| 1491489089  | Barry  | Fox Fitness 24               | State Highway 39; Shell Knob | MO5203145 | April 2016, June 2016, July 2016, August 2016, September 2016, October 2016, November 2016, January 2017, February 2017                                      | Samples collected in March 2017 tested absent for total coliform bacteria           | 
| 1491489199  | Benton | Hidden Valley MHP: 60        | RR 2; Warsaw                 | MO3262156 | March 2016, April 2016, May 2016, June 2016, July 2016, August 2016, September 2016, October 2016, November 2016, December 2016, January 2017, February 2017 | (Special) Samples collected in April 2015 tested absent for total coliform bacteria | 
| 1491489441  | Benton | American Legion Post 217: 28 | MM Highway; Warsaw           | MO3281109 | March 2016, April 2016, June 2016, July 2016, August 2016                                                                                                    | Samples collected in March 2017 tested absent for total coliform bacteria           | 
| 1491489500  | Benton | TT Campground: 25            | T T Highway; Warsaw          | MO1242804 | March 2016, April 2016, May 2016, June 2016, July 2016, August 2016, September 2016, October 2016, November 2016, December 2016, January 2017, February 2017 | (Special) Samples collected in May 2016 tested absent for total coliform bacteria   | 
| 1491489659  | Butler | Stop & Go: 120               | Highway 60 W; Poplar Bluff   | MO4292680 | March 2016, June 2016, August 2016, February 2017                                                                                                            | Samples collected in April 2017 tested absent for total coliform bacteria           | 
| 1491489817  | Dallas | Ridgeview Estates: 39        | Crestview Lane; Fair Grove   | MO5033116 | April 2016, June 2016, July 2016, September 2016                                                                                                             | Samples collected in March 2017 tested absent for total coliform bacteria           | 
```