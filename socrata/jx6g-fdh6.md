# NCHS - Drug Poisoning Mortality, U.S. and State Trends: United States, 1999?2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/drug-poisoning-mortality-u-s-and-state-trends-united-states-20022014) |
| Metadata | [Link](https://data.cdc.gov/api/views/jx6g-fdh6) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/jx6g-fdh6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/jx6g-fdh6/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | jx6g-fdh6 |
| Name | NCHS - Drug Poisoning Mortality, U.S. and State Trends: United States, 1999?2015 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | drug poisoning, state, national, united states, nchs |
| Created | 2016-01-07T20:09:15Z |
| Publication Date | 2017-04-11T01:30:22Z |

## Description

Drug poisoning deaths at the national and state levels by selected demographic characteristics, and depicts U.S. and state trends in age-adjusted death rates for drug poisoning from 1999 to 2015.
https://www.cdc.gov/nchs/data-visualization/drug-poisoning-mortality/

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| Yes      | time           | year                                         | Year                                         | number    | number      |
| Yes      | series tag     | sex                                          | Sex                                          | text      | text        |
| Yes      | series tag     | age                                          | Age                                          | text      | text        |
| Yes      | series tag     | race_hispanic_origin                         | Race & Hispanic Origin                       | text      | text        |
| Yes      | series tag     | state                                        | State                                        | text      | text        |
| Yes      | numeric metric | deaths                                       | Deaths                                       | number    | number      |
| Yes      | numeric metric | population                                   | Population                                   | number    | number      |
| Yes      | numeric metric | crude_death_rate                             | Crude Death Rate                             | number    | number      |
| Yes      | numeric metric | standard_error_for_crude_rate                | Standard Error for Crude Rate                | number    | number      |
| Yes      | numeric metric | low_confidence_limit_for_crude_rate          | Low Confidence Limit for Crude Rate          | number    | number      |
| Yes      | numeric metric | upper_confidence_limit_for_crude_rate        | Upper Confidence Limit for Crude Rate        | number    | number      |
| Yes      | numeric metric | age_adjusted_rate                            | Age-adjusted Rate                            | number    | number      |
| Yes      | numeric metric | standard_error_age_adjusted_rate             | Standard Error Age-adjusted Rate             | number    | number      |
| Yes      | numeric metric | lower_confidence_limit_for_age_adjusted_rate | Lower Confidence Limit for Age-adjusted rate | number    | number      |
| Yes      | numeric metric | upper_confidence_limit_for_age_adjusted_rate | Upper Confidence Limit for Age-adjusted Rate | number    | number      |
| Yes      | series tag     | state_crude_rate_in_range                    | State Crude Rate in Range                    | text      | text        |
| Yes      | numeric metric | us_crude_rate                                | US Crude Rate                                | number    | number      |
| Yes      | numeric metric | us_age_adjusted_rate                         | US Age-adjusted Rate                         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jx6g-fdh6 d:1999-01-01T00:00:00.000Z t:sex="Both Sexes" t:state_crude_rate_in_range=1.8?7 t:age="All Ages" t:state=Alabama t:race_hispanic_origin="All Races-All Origins" m:us_crude_rate=6.0382 m:upper_confidence_limit_for_age_adjusted_rate=4.4334 m:deaths=169 m:upper_confidence_limit_for_crude_rate=4.3899 m:standard_error_age_adjusted_rate=0.29657 m:age_adjusted_rate=3.8521 m:crude_death_rate=3.8148 m:low_confidence_limit_for_crude_rate=3.2396 m:standard_error_for_crude_rate=0.29344 m:lower_confidence_limit_for_age_adjusted_rate=3.2708 m:us_age_adjusted_rate=6.057 m:population=4430143

series e:jx6g-fdh6 d:2000-01-01T00:00:00.000Z t:sex="Both Sexes" t:state_crude_rate_in_range=1.8?7 t:age="All Ages" t:state=Alabama t:race_hispanic_origin="All Races-All Origins" m:us_crude_rate=6.1882 m:upper_confidence_limit_for_age_adjusted_rate=5.1126 m:deaths=197 m:upper_confidence_limit_for_crude_rate=5.0485 m:standard_error_age_adjusted_rate=0.31985 m:age_adjusted_rate=4.4857 m:crude_death_rate=4.4299 m:low_confidence_limit_for_crude_rate=3.8112 m:standard_error_for_crude_rate=0.31561 m:lower_confidence_limit_for_age_adjusted_rate=3.8588 m:us_age_adjusted_rate=6.1749 m:population=4447100

series e:jx6g-fdh6 d:2001-01-01T00:00:00.000Z t:sex="Both Sexes" t:state_crude_rate_in_range=1.8?7 t:age="All Ages" t:state=Alabama t:race_hispanic_origin="All Races-All Origins" m:us_crude_rate=6.8057 m:upper_confidence_limit_for_age_adjusted_rate=5.5447 m:deaths=216 m:upper_confidence_limit_for_crude_rate=5.4795 m:standard_error_age_adjusted_rate=0.33329 m:age_adjusted_rate=4.8915 m:crude_death_rate=4.8348 m:low_confidence_limit_for_crude_rate=4.19 m:standard_error_for_crude_rate=0.32896 m:lower_confidence_limit_for_age_adjusted_rate=4.2382 m:us_age_adjusted_rate=6.7922 m:population=4467634
```

## Meta Commands

```ls
metric m:deaths p:integer l:Deaths t:dataTypeName=number

metric m:population p:integer l:Population t:dataTypeName=number

metric m:crude_death_rate p:float l:"Crude Death Rate" t:dataTypeName=number

metric m:standard_error_for_crude_rate p:float l:"Standard Error for Crude Rate" t:dataTypeName=number

metric m:low_confidence_limit_for_crude_rate p:float l:"Low Confidence Limit for Crude Rate" t:dataTypeName=number

metric m:upper_confidence_limit_for_crude_rate p:float l:"Upper Confidence Limit for Crude Rate" t:dataTypeName=number

metric m:age_adjusted_rate p:float l:"Age-adjusted Rate" t:dataTypeName=number

metric m:standard_error_age_adjusted_rate p:float l:"Standard Error Age-adjusted Rate" t:dataTypeName=number

metric m:lower_confidence_limit_for_age_adjusted_rate p:float l:"Lower Confidence Limit for Age-adjusted rate" t:dataTypeName=number

metric m:upper_confidence_limit_for_age_adjusted_rate p:float l:"Upper Confidence Limit for Age-adjusted Rate" t:dataTypeName=number

metric m:us_crude_rate p:float l:"US Crude Rate" t:dataTypeName=number

metric m:us_age_adjusted_rate p:float l:"US Age-adjusted Rate" t:dataTypeName=number

entity e:jx6g-fdh6 l:"NCHS - Drug Poisoning Mortality, U.S. and State Trends: United States, 1999?2015" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/jx6g-fdh6

property e:jx6g-fdh6 t:meta.view v:id=jx6g-fdh6 v:category=NCHS v:averageRating=0 v:name="NCHS - Drug Poisoning Mortality, U.S. and State Trends: United States, 1999?2015" v:attribution="National Center for Health Statistics"

property e:jx6g-fdh6 t:meta.view.license v:name="Public Domain"

property e:jx6g-fdh6 t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:jx6g-fdh6 t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:jx6g-fdh6 t:meta.view.metadata.custom_fields.common_core v:Publisher=NCHS v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | sex        | age      | race_hispanic_origin  | state   | deaths | population | crude_death_rate | standard_error_for_crude_rate | low_confidence_limit_for_crude_rate | upper_confidence_limit_for_crude_rate | age_adjusted_rate | standard_error_age_adjusted_rate | lower_confidence_limit_for_age_adjusted_rate | upper_confidence_limit_for_age_adjusted_rate | state_crude_rate_in_range | us_crude_rate | us_age_adjusted_rate | 
| ==== | ========== | ======== | ===================== | ======= | ====== | ========== | ================ | ============================= | =================================== | ===================================== | ================= | ================================ | ============================================ | ============================================ | ========================= | ============= | ==================== | 
| 1999 | Both Sexes | All Ages | All Races-All Origins | Alabama | 169    | 4430143    | 3.8148           | 0.29344                       | 3.2396                              | 4.3899                                | 3.8521            | 0.29657                          | 3.2708                                       | 4.4334                                       | 1.8?7                     | 6.0382        | 6.0570               | 
| 2000 | Both Sexes | All Ages | All Races-All Origins | Alabama | 197    | 4447100    | 4.4299           | 0.31561                       | 3.8112                              | 5.0485                                | 4.4857            | 0.31985                          | 3.8588                                       | 5.1126                                       | 1.8?7                     | 6.1882        | 6.1749               | 
| 2001 | Both Sexes | All Ages | All Races-All Origins | Alabama | 216    | 4467634    | 4.8348           | 0.32896                       | 4.1900                              | 5.4795                                | 4.8915            | 0.33329                          | 4.2382                                       | 5.5447                                       | 1.8?7                     | 6.8057        | 6.7922               | 
| 2002 | Both Sexes | All Ages | All Races-All Origins | Alabama | 211    | 4480089    | 4.7097           | 0.32423                       | 4.0742                              | 5.3452                                | 4.7619            | 0.32868                          | 4.1177                                       | 5.4062                                       | 1.8?7                     | 8.1766        | 8.1957               | 
| 2003 | Both Sexes | All Ages | All Races-All Origins | Alabama | 197    | 4503491    | 4.3744           | 0.31166                       | 3.7635                              | 4.9852                                | 4.4333            | 0.31701                          | 3.8120                                       | 5.0547                                       | 1.8?7                     | 8.8881        | 8.8765               | 
| 2004 | Both Sexes | All Ages | All Races-All Origins | Alabama | 283    | 4530729    | 6.2462           | 0.37130                       | 5.5185                              | 6.9740                                | 6.3542            | 0.37944                          | 5.6105                                       | 7.0979                                       | 1.8?7                     | 9.3660        | 9.3831               | 
| 2005 | Both Sexes | All Ages | All Races-All Origins | Alabama | 283    | 4569805    | 6.1928           | 0.36813                       | 5.4713                              | 6.9143                                | 6.3330            | 0.37832                          | 5.5915                                       | 7.0745                                       | 1.8?7                     | 10.0884       | 10.0699              | 
| 2006 | Both Sexes | All Ages | All Races-All Origins | Alabama | 398    | 4628981    | 8.5980           | 0.43098                       | 7.7533                              | 9.4427                                | 8.7498            | 0.44162                          | 7.8842                                       | 9.6154                                       | 7?9.8                     | 11.5373       | 11.4883              | 
| 2007 | Both Sexes | All Ages | All Races-All Origins | Alabama | 511    | 4672840    | 10.9355          | 0.48376                       | 9.9874                              | 11.8837                               | 11.0885           | 0.49516                          | 10.1180                                      | 12.0590                                      | 9.9?12.3                  | 11.9543       | 11.8775              | 
| 2008 | Both Sexes | All Ages | All Races-All Origins | Alabama | 607    | 4718206    | 12.8651          | 0.52218                       | 11.8416                             | 13.8885                               | 12.9811           | 0.53292                          | 11.9366                                      | 14.0256                                      | 12.3?15.2                 | 11.9864       | 11.8947              | 
```