# Assertive Community Treatment (ACT) Admissions Summary (Baseline)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assertive-community-treatment-act-admissions-summary-baseline) |
| Metadata | [Link](https://data.ny.gov/api/views/x5gj-r3vh) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/x5gj-r3vh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/x5gj-r3vh/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | x5gj-r3vh |
| Name | Assertive Community Treatment (ACT) Admissions Summary (Baseline) |
| Attribution | Office of Mental Health |
| Category | Human Services |
| Tags | mental health; assertive community treatment |
| Created | 2014-02-06T15:47:47Z |
| Publication Date | 2017-03-01T23:02:51Z |

## Description

This dataset contains the number of ACT consumers within each demographic, risk, and service utilization category at baseline; by ACT team/program, county, region, and statewide.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | time           | row_created_date_time                    | Row Created Date Time                    | calendar_date | calendar_date |
| Yes      | series tag     | data_level_indicator                     | Data Level Indicator                     | text          | text          |
| Yes      | series tag     | team_county_or_region_name               | Team County or Region Name               | text          | text          |
| Yes      | series tag     | county                                   | County                                   | text          | text          |
| Yes      | series tag     | omh_region                               | OMH Region                               | text          | text          |
| Yes      | numeric metric | team_capacity                            | Team Capacity                            | number        | number        |
| Yes      | numeric metric | census                                   | Census                                   | number        | number        |
| Yes      | numeric metric | percent_of_capacity_on_census            | Percent of Capacity on Census            | percent       | percent       |
| Yes      | numeric metric | average_age                              | Average Age                              | number        | number        |
| Yes      | numeric metric | number_of_males                          | Number of Males                          | number        | number        |
| Yes      | numeric metric | number_of_females                        | Number of Females                        | number        | number        |
| Yes      | numeric metric | number_white                             | Number White                             | number        | number        |
| Yes      | numeric metric | number_black                             | Number Black                             | number        | number        |
| Yes      | numeric metric | number_hispanic                          | Number Hispanic                          | number        | number        |
| Yes      | numeric metric | number_asian                             | Number Asian                             | number        | number        |
| Yes      | numeric metric | number_other_race                        | Number Other Race                        | number        | number        |
| Yes      | numeric metric | number_with_schizophrenia                | Number with Schizophrenia                | number        | number        |
| Yes      | numeric metric | number_with_bipolar                      | Number with Bipolar                      | number        | number        |
| Yes      | numeric metric | number_with_depression                   | Number with Depression                   | number        | number        |
| Yes      | numeric metric | number_with_substance_abuse              | Number with Substance Abuse              | number        | number        |
| Yes      | numeric metric | number_in_aot                            | Number in AOT                            | number        | number        |
| Yes      | numeric metric | number_in_aot_enhanced                   | Number in AOT Service Enhancement        | number        | number        |
| Yes      | numeric metric | number_with_criminal_justice_activity    | Number with Criminal Justice Activity    | number        | number        |
| Yes      | numeric metric | number_homeless                          | Number Homeless                          | number        | number        |
| Yes      | numeric metric | number_hospitalized                      | Number Hospitalized                      | number        | number        |
| Yes      | numeric metric | number_with_psychiatric_er_visits        | Number with Psychiatric ER Visits        | number        | number        |
| Yes      | numeric metric | number_meeting_high_utilization_criteria | Number Meeting High Utilization Criteria | number        | number        |
| Yes      | numeric metric | number_enrolled_0_to_1_year              | Number Enrolled 0 to 1 Year              | number        | number        |
| Yes      | numeric metric | number_enrolled_1_to_3_years             | Number Enrolled 1 to 3 Years             | number        | number        |
| Yes      | numeric metric | number_enrolled_3_to_5_years             | Number Enrolled 3 to 5 Years             | number        | number        |
| Yes      | numeric metric | number_enrolled_5_plus_years             | Number Enrolled 5 Plus Years             | number        | number        |
```

## Time Field

```ls
Value = row_created_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:x5gj-r3vh d:2016-10-12T09:59:53.000Z t:omh_region="New York City" t:county=Region t:team_county_or_region_name="New York City" t:data_level_indicator=Region m:number_with_criminal_justice_activity=253 m:number_with_psychiatric_er_visits=808 m:number_hispanic=682 m:team_capacity=2992 m:number_of_males=1749 m:number_in_aot_enhanced=29 m:number_white=514 m:number_in_aot=1093 m:percent_of_capacity_on_census=95 m:number_enrolled_0_to_1_year=506 m:number_with_bipolar=343 m:number_asian=122 m:number_with_depression=82 m:census=2830 m:average_age=45 m:number_meeting_high_utilization_criteria=1832 m:number_with_substance_abuse=1615 m:number_of_females=1082 m:number_black=1354 m:number_enrolled_5_plus_years=865 m:number_homeless=193 m:number_enrolled_1_to_3_years=891 m:number_enrolled_3_to_5_years=568 m:number_other_race=145 m:number_with_schizophrenia=2254 m:number_hospitalized=679

series e:x5gj-r3vh d:2016-10-12T09:59:53.000Z t:omh_region="Western New York" t:county=Region t:team_county_or_region_name="Western New York" t:data_level_indicator=Region m:number_with_criminal_justice_activity=106 m:number_with_psychiatric_er_visits=180 m:number_hispanic=35 m:team_capacity=580 m:number_of_males=360 m:number_in_aot_enhanced=25 m:number_white=302 m:number_in_aot=161 m:percent_of_capacity_on_census=96 m:number_enrolled_0_to_1_year=156 m:number_with_bipolar=50 m:number_asian=4 m:number_with_depression=10 m:census=555 m:average_age=47 m:number_meeting_high_utilization_criteria=350 m:number_with_substance_abuse=355 m:number_of_females=195 m:number_black=191 m:number_enrolled_5_plus_years=108 m:number_homeless=36 m:number_enrolled_1_to_3_years=194 m:number_enrolled_3_to_5_years=97 m:number_other_race=15 m:number_with_schizophrenia=436 m:number_hospitalized=150

series e:x5gj-r3vh d:2016-10-12T09:59:53.000Z t:omh_region=Statewide t:county=State t:team_county_or_region_name=Statewide t:data_level_indicator=State m:number_with_criminal_justice_activity=558 m:number_with_psychiatric_er_visits=1253 m:number_hispanic=838 m:team_capacity=5220 m:number_of_males=3015 m:number_in_aot_enhanced=87 m:number_white=1680 m:number_in_aot=1641 m:percent_of_capacity_on_census=93 m:number_enrolled_0_to_1_year=1005 m:number_with_bipolar=641 m:number_asian=146 m:number_with_depression=141 m:census=4861 m:average_age=46 m:number_meeting_high_utilization_criteria=2910 m:number_with_substance_abuse=2767 m:number_of_females=1847 m:number_black=1963 m:number_enrolled_5_plus_years=1362 m:number_homeless=328 m:number_enrolled_1_to_3_years=1587 m:number_enrolled_3_to_5_years=907 m:number_other_race=196 m:number_with_schizophrenia=3759 m:number_hospitalized=1087
```

## Meta Commands

```ls
metric m:team_capacity p:integer l:"Team Capacity" d:"Number of recipients the team is licensed to serve" t:dataTypeName=number

metric m:census p:integer l:Census d:"Number of individuals currently receiving services from ACT programs, census from CAIRS system" t:dataTypeName=number

metric m:percent_of_capacity_on_census p:float l:"Percent of Capacity on Census" d:"Percentage of capacity on census" t:dataTypeName=percent

metric m:average_age p:float l:"Average Age" d:"Average age of individuals on census" t:dataTypeName=number

metric m:number_of_males p:integer l:"Number of Males" d:"Number of males on census" t:dataTypeName=number

metric m:number_of_females p:integer l:"Number of Females" d:"Number of females on census" t:dataTypeName=number

metric m:number_white p:integer l:"Number White" d:"Number of white individuals on census. Note: Individuals can indicate more than one race/ethnicity. As a result, the total across ethnicities could be greater than the number of enrollees." t:dataTypeName=number

metric m:number_black p:integer l:"Number Black" d:"Number of black individuals on census. Note: Individuals can indicate more than one race/ethnicity. As a result, the total across ethnicities could be greater than the number of enrollees." t:dataTypeName=number

metric m:number_hispanic p:integer l:"Number Hispanic" d:"Number of Hispanic individuals on census. Note: Individuals can indicate more than one race/ethnicity. As a result, the total across ethnicities could be greater than the number of enrollees." t:dataTypeName=number

metric m:number_asian p:integer l:"Number Asian" d:"Number of Asian individuals on census. Note: Individuals can indicate more than one race/ethnicity. As a result, the total across ethnicities could be greater than the number of enrollees." t:dataTypeName=number

metric m:number_other_race p:integer l:"Number Other Race" d:"Number of Other race individuals on census. Note: Individuals can indicate more than one race/ethnicity. As a result, the total across ethnicities could be greater than the number of enrollees." t:dataTypeName=number

metric m:number_with_schizophrenia p:float l:"Number with Schizophrenia" d:"Number of individuals with a schizophrenia dx at admission" t:dataTypeName=number

metric m:number_with_bipolar p:float l:"Number with Bipolar" d:"Number of individuals with a bipolar dx at admission" t:dataTypeName=number

metric m:number_with_depression p:float l:"Number with Depression" d:"Number of individuals with a depression dx at admission" t:dataTypeName=number

metric m:number_with_substance_abuse p:float l:"Number with Substance Abuse" d:"Number of individual with Coexisting Alcohol and/or Substance Abuse" t:dataTypeName=number

metric m:number_in_aot p:float l:"Number in AOT" d:"Number of those individuals who have an AOT court order" t:dataTypeName=number

metric m:number_in_aot_enhanced p:float l:"Number in AOT Service Enhancement" d:"Number of those assessed who have AOT service enhancement" t:dataTypeName=number

metric m:number_with_criminal_justice_activity p:float l:"Number with Criminal Justice Activity" d:"Number of ACT recipients with ANY criminal justice status, arrests or incarcerations within six months of baseline" t:dataTypeName=number

metric m:number_homeless p:float l:"Number Homeless" d:"Number of individuals who were homeless (parks, streets, shelters, or other undomiciled) or have experienced any days homeless six months prior to baseline" t:dataTypeName=number

metric m:number_hospitalized p:float l:"Number Hospitalized" d:"Number of recipients with two or more psychiatric hospitalizations, 12 months prior to baseline or hospitalized for 60 days, six months prior to baseline" t:dataTypeName=number

metric m:number_with_psychiatric_er_visits p:float l:"Number with Psychiatric ER Visits" d:"Number of recipients with two or more psychiatric ER visits, 12 months prior to baseline" t:dataTypeName=number

metric m:number_meeting_high_utilization_criteria p:float l:"Number Meeting High Utilization Criteria" d:"Number of recipients meeting ANY of the following high utilization criteria at baseline: AOT, forensic involvement, episodes of homelessness, 2 or more psychiatric hospitalizations, 2 or more psychiatric ER visits" t:dataTypeName=number

metric m:number_enrolled_0_to_1_year p:float l:"Number Enrolled 0 to 1 Year" d:"Number of currently enrolled recipients who have been enrolled for 0-1yr" t:dataTypeName=number

metric m:number_enrolled_1_to_3_years p:float l:"Number Enrolled 1 to 3 Years" d:"Number of currently enrolled recipients who have been enrolled for 1-3yrs" t:dataTypeName=number

metric m:number_enrolled_3_to_5_years p:float l:"Number Enrolled 3 to 5 Years" d:"Number of currently enrolled recipients who have been enrolled for 3-5 yrs" t:dataTypeName=number

metric m:number_enrolled_5_plus_years p:float l:"Number Enrolled 5 Plus Years" d:"Number of currently enrolled recipients who have been enrolled for 5+yrs" t:dataTypeName=number

entity e:x5gj-r3vh l:"Assertive Community Treatment (ACT) Admissions Summary (Baseline)" t:attribution="Office of Mental Health" t:url=https://data.ny.gov/api/views/x5gj-r3vh

property e:x5gj-r3vh t:meta.view v:id=x5gj-r3vh v:category="Human Services" v:attributionLink="http://bi.omh.ny.gov/act/statistics?p=team-summary" v:averageRating=0 v:name="Assertive Community Treatment (ACT) Admissions Summary (Baseline)" v:attribution="Office of Mental Health"

property e:x5gj-r3vh t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:x5gj-r3vh t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:x5gj-r3vh t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | data_level_indicator | team_county_or_region_name | county  | omh_region       | team_capacity | census | percent_of_capacity_on_census | average_age        | number_of_males | number_of_females | number_white | number_black | number_hispanic | number_asian | number_other_race | number_with_schizophrenia | number_with_bipolar | number_with_depression | number_with_substance_abuse | number_in_aot | number_in_aot_enhanced | number_with_criminal_justice_activity | number_homeless     | number_hospitalized  | number_with_psychiatric_er_visits | number_meeting_high_utilization_criteria | number_enrolled_0_to_1_year | number_enrolled_1_to_3_years | number_enrolled_3_to_5_years | number_enrolled_5_plus_years | 
| ===================== | ==================== | ========================== | ======= | ================ | ============= | ====== | ============================= | ================== | =============== | ================= | ============ | ============ | =============== | ============ | ================= | ========================= | =================== | ====================== | =========================== | ============= | ====================== | ===================================== | =================== | ==================== | ================================= | ======================================== | =========================== | ============================ | ============================ | ============================ | 
| 2016-10-12T09:59:53   | Region               | New York City              | Region  | New York City    | 2992          | 2830   | 95.000000000000000            | 45.000000000000000 | 1749            | 1082              | 514          | 1354         | 682             | 122          | 145               | 2254.000000000000000      | 343.000000000000000 | 82.000000000000000     | 1615.000000000000000        | 1093.00000    | 29.0000000             | 253.000000000000000                   | 193.000000000000000 | 679.000000000000000  | 808.000000000000000               | 1832.000000000000000                     | 506.000000000000000         | 891.000000000000000          | 568.000000000000000          | 865.000000000000000          | 
| 2016-10-12T09:59:53   | Region               | Western New York           | Region  | Western New York | 580           | 555    | 96.000000000000000            | 47.000000000000000 | 360             | 195               | 302          | 191          | 35              | 4            | 15                | 436.000000000000000       | 50.000000000000000  | 10.000000000000000     | 355.000000000000000         | 161.000000    | 25.0000000             | 106.000000000000000                   | 36.000000000000000  | 150.000000000000000  | 180.000000000000000               | 350.000000000000000                      | 156.000000000000000         | 194.000000000000000          | 97.000000000000000           | 108.000000000000000          | 
| 2016-10-12T09:59:53   | State                | Statewide                  | State   | Statewide        | 5220          | 4861   | 93.000000000000000            | 46.000000000000000 | 3015            | 1847              | 1680         | 1963         | 838             | 146          | 196               | 3759.000000000000000      | 641.000000000000000 | 141.000000000000000    | 2767.000000000000000        | 1641.00000    | 87.0000000             | 558.000000000000000                   | 328.000000000000000 | 1087.000000000000000 | 1253.000000000000000              | 2910.000000000000000                     | 1005.000000000000000        | 1587.000000000000000         | 907.000000000000000          | 1362.000000000000000         | 
| 2016-10-12T09:59:53   | Region               | Long Island                | Region  | Long Island      | 728           | 669    | 92.000000000000000            | 47.000000000000000 | 413             | 256               | 389          | 195          | 53              | 12           | 17                | 473.000000000000000       | 129.000000000000000 | 24.000000000000000     | 337.000000000000000         | 247.000000    | 14.0000000             | 81.000000000000000                    | 23.000000000000000  | 134.000000000000000  | 152.000000000000000               | 379.000000000000000                      | 155.000000000000000         | 213.000000000000000          | 110.000000000000000          | 191.000000000000000          | 
| 2016-10-12T09:59:53   | Region               | Central New York           | Region  | Central New York | 300           | 247    | 82.000000000000000            | 47.000000000000000 | 151             | 96                | 191          | 44           | 4               | 1            | 4                 | 191.000000000000000       | 31.000000000000000  | 7.000000000000000      | 137.000000000000000         | 40.0000000    | 7.00000000             | 32.000000000000000                    | 14.000000000000000  | 37.000000000000000   | 49.000000000000000                | 100.000000000000000                      | 66.000000000000000          | 83.000000000000000           | 47.000000000000000           | 51.000000000000000           | 
| 2016-10-12T09:59:53   | Region               | Hudson River               | Region  | Hudson River     | 620           | 560    | 90.000000000000000            | 47.000000000000000 | 342             | 218               | 284          | 179          | 64              | 7            | 15                | 405.000000000000000       | 88.000000000000000  | 18.000000000000000     | 323.000000000000000         | 100.000000    | 12.0000000             | 86.000000000000000                    | 62.000000000000000  | 87.000000000000000   | 64.000000000000000                | 249.000000000000000                      | 122.000000000000000         | 206.000000000000000          | 85.000000000000000           | 147.000000000000000          | 
| 2016-10-12T10:00:05   | Program              | PSCH Brooklyn              | Kings   | New York City    | 68            | 67     | 99.000000000000000            | 42.000000000000000 | 40              | 27                | 13           | 39           | 5               | 5            | 3                 | 60                        | 5                   | 2                      | 28                          | 17            | 0                      |                                       | 1                   |                      |                                   | 18                                       | 10                          | 22                           | 11                           | 24                           | 
| 2016-10-12T10:00:05   | Program              | JBFCS Suffolk ACT          | Suffolk | Long Island      | 68            |        |                               |                    |                 |                   |              |              |                 |              |                   |                           |                     |                        |                             |               |                        |                                       |                     |                      |                                   |                                          |                             |                              |                              |                              | 
| 2016-10-12T10:00:05   | Program              | SUS Brooklyn ACT           | Kings   | New York City    | 68            | 66     | 97.000000000000000            | 45.000000000000000 | 42              | 24                | 13           | 33           | 18              | 2            |                   | 52                        | 11                  | 1                      | 39                          | 22            | 0                      |                                       | 5                   |                      |                                   | 23                                       | 17                          | 13                           | 10                           | 26                           | 
| 2016-10-12T10:00:05   | Program              | Pilgrim PC ACT             | Suffolk | Long Island      | 68            | 68     | 100.000000000000000           | 47.000000000000000 | 42              | 26                | 48           | 13           | 5               |              | 1                 | 54                        | 12                  |                        | 37                          | 41            | 7                      | 14                                    | 2                   | 26                   | 32                                | 52                                       | 13                          | 18                           | 10                           | 27                           | 
```