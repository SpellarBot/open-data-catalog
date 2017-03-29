# WAOFM - SAEP - School District Population Estimates, 2000-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-saep-school-district-population-estimates-2000-2014-92d02) |
| Metadata | [Link](https://data.wa.gov/api/views/krb3-8st4) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/krb3-8st4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/krb3-8st4/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | krb3-8st4 |
| Name | WAOFM - SAEP - School District Population Estimates, 2000-2016 |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Divisio |
| Category | Demographics |
| Tags | wa, washington, ofm, school district, population, intercensal, postcensal |
| Created | 2014-10-08T20:42:42Z |
| Publication Date | 2016-09-24T00:17:40Z |

## Description

Small Area Estimate Program (SAEP) April 1 population estimates for school districts, 2000-present.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | unified_school_district_name              | Unified School District Name              | text      | text        |
| Yes      | series tag     | unified_school_district_code              | Unified School District Code              | text      | text        |
| Yes      | series tag     | washington_school_district_code           | Washington School District Code           | text      | text        |
| Yes      | series tag     | educational_service_district_code         | Educational Service District Code         | text      | text        |
| Yes      | numeric metric | estimated_total_population_2000           | Estimated Total Population 2000           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2001           | Estimated Total Population 2001           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2002           | Estimated Total Population 2002           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2003           | Estimated Total Population 2003           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2004           | Estimated Total Population 2004           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2005           | Estimated Total Population 2005           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2006           | Estimated Total Population 2006           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2007           | Estimated Total Population 2007           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2008           | Estimated Total Population 2008           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2009           | Estimated Total Population 2009           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2010           | Estimated Total Population 2010           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2011           | Estimated Total Population 2011           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2012           | Estimated Total Population 2012           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2013           | Estimated Total Population 2013           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2014           | Estimated Total Population 2014           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2015           | Estimated Total Population 2015           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2016           | Estimated Total Population 2016           | number    | number      |
| Yes      | numeric metric | numeric_change_in_population_2000_to_2010 | Numeric Change in Population 2000 to 2010 | number    | number      |
| Yes      | series tag     | percent_change_in_population_2000_to_2010 | Percent Change in Population 2000 to 2010 | text      | text        |
| Yes      | numeric metric | numeric_change_in_population_2010_to_2015 | Numeric Change in Population 2010 to 2016 | number    | number      |
| Yes      | numeric metric | percent_change_in_population_2010_to_2015 | Percent Change in Population 2010 to 2016 | percent   | percent     |
| Yes      | series tag     | saep_version                              | SAEP Version                              | text      | text        |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:krb3-8st4 d:2000-01-01T00:00:00.000Z t:saep_version="September 21, 2016" t:educational_service_district_code=113 t:unified_school_district_name="Aberdeen School District" t:percent_change_in_population_2000_to_2010=1.57% t:washington_school_district_code=14005 t:unified_school_district_code=30 m:numeric_change_in_population_2000_to_2010=314 m:numeric_change_in_population_2010_to_2015=-196 m:estimated_total_population_2007=20537 m:estimated_total_population_2006=20537 m:estimated_total_population_2009=20430 m:estimated_total_population_2008=20480 m:estimated_total_population_2016=20172 m:estimated_total_population_2015=20229 m:estimated_total_population_2001=20368 m:estimated_total_population_2014=20317 m:estimated_total_population_2000=20054 m:estimated_total_population_2013=20323 m:estimated_total_population_2012=20364 m:estimated_total_population_2003=20315 m:estimated_total_population_2011=20341 m:estimated_total_population_2002=20386 m:estimated_total_population_2010=20368 m:estimated_total_population_2005=20447 m:estimated_total_population_2004=20364

series e:krb3-8st4 d:2000-01-01T00:00:00.000Z t:saep_version="September 21, 2016" t:educational_service_district_code=113 t:unified_school_district_name="Adna School District" t:percent_change_in_population_2000_to_2010=30.37% t:washington_school_district_code=21226 t:unified_school_district_code=60 m:numeric_change_in_population_2000_to_2010=870 m:numeric_change_in_population_2010_to_2015=118 m:estimated_total_population_2007=3505 m:estimated_total_population_2006=3403 m:estimated_total_population_2009=3675 m:estimated_total_population_2008=3598 m:estimated_total_population_2016=3854 m:percent_change_in_population_2010_to_2015=3.15 m:estimated_total_population_2015=3838 m:estimated_total_population_2001=2956 m:estimated_total_population_2014=3805 m:estimated_total_population_2013=3795 m:estimated_total_population_2000=2866 m:estimated_total_population_2012=3799 m:estimated_total_population_2003=3115 m:estimated_total_population_2011=3791 m:estimated_total_population_2002=3045 m:estimated_total_population_2010=3736 m:estimated_total_population_2005=3289 m:estimated_total_population_2004=3201

series e:krb3-8st4 d:2000-01-01T00:00:00.000Z t:saep_version="September 21, 2016" t:educational_service_district_code=101 t:unified_school_district_name="Almira School District" t:percent_change_in_population_2000_to_2010="(  4.760%)" t:washington_school_district_code=22017 t:unified_school_district_code=90 m:numeric_change_in_population_2000_to_2010=-24 m:numeric_change_in_population_2010_to_2015=-12 m:estimated_total_population_2007=500 m:estimated_total_population_2006=499 m:estimated_total_population_2009=495 m:estimated_total_population_2008=500 m:estimated_total_population_2016=477 m:estimated_total_population_2015=484 m:estimated_total_population_2001=515 m:estimated_total_population_2014=485 m:estimated_total_population_2000=513 m:estimated_total_population_2013=490 m:estimated_total_population_2012=490 m:estimated_total_population_2003=499 m:estimated_total_population_2011=490 m:estimated_total_population_2002=509 m:estimated_total_population_2010=489 m:estimated_total_population_2005=500 m:estimated_total_population_2004=502
```

## Meta Commands

```ls
metric m:estimated_total_population_2000 p:integer l:"Estimated Total Population 2000" t:dataTypeName=number

metric m:estimated_total_population_2001 p:integer l:"Estimated Total Population 2001" t:dataTypeName=number

metric m:estimated_total_population_2002 p:integer l:"Estimated Total Population 2002" t:dataTypeName=number

metric m:estimated_total_population_2003 p:integer l:"Estimated Total Population 2003" t:dataTypeName=number

metric m:estimated_total_population_2004 p:integer l:"Estimated Total Population 2004" t:dataTypeName=number

metric m:estimated_total_population_2005 p:integer l:"Estimated Total Population 2005" t:dataTypeName=number

metric m:estimated_total_population_2006 p:integer l:"Estimated Total Population 2006" t:dataTypeName=number

metric m:estimated_total_population_2007 p:integer l:"Estimated Total Population 2007" t:dataTypeName=number

metric m:estimated_total_population_2008 p:integer l:"Estimated Total Population 2008" t:dataTypeName=number

metric m:estimated_total_population_2009 p:integer l:"Estimated Total Population 2009" t:dataTypeName=number

metric m:estimated_total_population_2010 p:integer l:"Estimated Total Population 2010" t:dataTypeName=number

metric m:estimated_total_population_2011 p:integer l:"Estimated Total Population 2011" t:dataTypeName=number

metric m:estimated_total_population_2012 p:integer l:"Estimated Total Population 2012" t:dataTypeName=number

metric m:estimated_total_population_2013 p:integer l:"Estimated Total Population 2013" t:dataTypeName=number

metric m:estimated_total_population_2014 p:integer l:"Estimated Total Population 2014" t:dataTypeName=number

metric m:estimated_total_population_2015 p:integer l:"Estimated Total Population 2015" t:dataTypeName=number

metric m:estimated_total_population_2016 p:integer l:"Estimated Total Population 2016" t:dataTypeName=number

metric m:numeric_change_in_population_2000_to_2010 p:integer l:"Numeric Change in Population 2000 to 2010" t:dataTypeName=number

metric m:numeric_change_in_population_2010_to_2015 p:integer l:"Numeric Change in Population 2010 to 2016" t:dataTypeName=number

metric m:percent_change_in_population_2010_to_2015 p:float l:"Percent Change in Population 2010 to 2016" t:dataTypeName=percent

entity e:krb3-8st4 l:"WAOFM - SAEP - School District Population Estimates, 2000-2016" t:attribution="Washington State Office of Financial Management, Forecasting and Research Divisio" t:url=https://data.wa.gov/api/views/krb3-8st4

property e:krb3-8st4 t:meta.view v:id=krb3-8st4 v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/smallarea/default.asp v:averageRating=0 v:name="WAOFM - SAEP - School District Population Estimates, 2000-2016" v:attribution="Washington State Office of Financial Management, Forecasting and Research Divisio"

property e:krb3-8st4 t:meta.view.license v:name="Public Domain"

property e:krb3-8st4 t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:krb3-8st4 t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| unified_school_district_name      | unified_school_district_code | washington_school_district_code | educational_service_district_code | estimated_total_population_2000 | estimated_total_population_2001 | estimated_total_population_2002 | estimated_total_population_2003 | estimated_total_population_2004 | estimated_total_population_2005 | estimated_total_population_2006 | estimated_total_population_2007 | estimated_total_population_2008 | estimated_total_population_2009 | estimated_total_population_2010 | estimated_total_population_2011 | estimated_total_population_2012 | estimated_total_population_2013 | estimated_total_population_2014 | estimated_total_population_2015 | estimated_total_population_2016 | numeric_change_in_population_2000_to_2010 | percent_change_in_population_2000_to_2010 | numeric_change_in_population_2010_to_2015 | percent_change_in_population_2010_to_2015 | saep_version       | 
| ================================= | ============================ | =============================== | ================================= | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | ========================================= | ========================================= | ========================================= | ========================================= | ================== | 
| Aberdeen School District          | 30                           | 14005                           | 113                               | 20054                           | 20368                           | 20386                           | 20315                           | 20364                           | 20447                           | 20537                           | 20537                           | 20480                           | 20430                           | 20368                           | 20341                           | 20364                           | 20323                           | 20317                           | 20229                           | 20172                           | 314                                       | 1.57%                                     | -196                                      |                                           | September 21, 2016 | 
| Adna School District              | 60                           | 21226                           | 113                               | 2866                            | 2956                            | 3045                            | 3115                            | 3201                            | 3289                            | 3403                            | 3505                            | 3598                            | 3675                            | 3736                            | 3791                            | 3799                            | 3795                            | 3805                            | 3838                            | 3854                            | 870                                       | 30.37%                                    | 118                                       | 3.15                                      | September 21, 2016 | 
| Almira School District            | 90                           | 22017                           | 101                               | 513                             | 515                             | 509                             | 499                             | 502                             | 500                             | 499                             | 500                             | 500                             | 495                             | 489                             | 490                             | 490                             | 490                             | 485                             | 484                             | 477                             | -24                                       | ( 4.760%)                                 | -12                                       |                                           | September 21, 2016 | 
| Anacortes School District         | 150                          | 29103                           | 189                               | 18643                           | 18790                           | 18999                           | 19059                           | 19309                           | 19494                           | 19794                           | 20030                           | 20223                           | 20356                           | 20332                           | 20447                           | 20561                           | 20716                           | 20867                           | 21038                           | 21435                           | 1689                                      | 9.06%                                     | 1103                                      | 5.42                                      | September 21, 2016 | 
| Arlington School District         | 240                          | 31016                           | 189                               | 23682                           | 24331                           | 24964                           | 25567                           | 26096                           | 26776                           | 27547                           | 28254                           | 28832                           | 29266                           | 29735                           | 29799                           | 29904                           | 30268                           | 30448                           | 30928                           | 31319                           | 6053                                      | 25.56%                                    | 1584                                      | 5.33                                      | September 21, 2016 | 
| Asotin-Anatone School District    | 280                          | 2420                            | 123                               | 2859                            | 2897                            | 2920                            | 2952                            | 2985                            | 3031                            | 3088                            | 3146                            | 3185                            | 3218                            | 3245                            | 3249                            | 3263                            | 3296                            | 3327                            | 3340                            | 3391                            | 386                                       | 13.49%                                    | 146                                       | 4.49                                      | September 21, 2016 | 
| Auburn School District            | 300                          | 17408                           | 121                               | 68680                           | 70178                           | 71822                           | 73015                           | 74296                           | 75646                           | 77660                           | 79487                           | 81049                           | 82493                           | 84053                           | 84558                           | 85136                           | 87174                           | 88787                           | 89961                           | 91831                           | 15373                                     | 22.38%                                    | 7778                                      | 9.25                                      | September 21, 2016 | 
| Bainbridge Island School District | 330                          | 18303                           | 121                               | 20308                           | 20583                           | 20927                           | 21276                           | 21497                           | 21511                           | 21991                           | 22399                           | 22718                           | 22939                           | 23025                           | 23030                           | 23090                           | 23190                           | 23360                           | 23390                           | 23760                           | 2717                                      | 13.38%                                    | 735                                       | 3.19                                      | September 21, 2016 | 
| Battle Ground School District     | 380                          | 6119                            | 112                               | 47172                           | 48899                           | 51279                           | 53261                           | 55541                           | 57533                           | 59662                           | 61472                           | 63047                           | 64357                           | 65182                           | 65834                           | 66381                           | 67244                           | 68471                           | 70354                           | 72777                           | 18010                                     | 38.18%                                    | 7595                                      | 11.65                                     | September 21, 2016 | 
| Bellevue School District          | 390                          | 17405                           | 121                               | 113798                          | 114754                          | 115945                          | 116389                          | 116974                          | 117659                          | 119380                          | 120819                          | 121879                          | 122814                          | 124003                          | 124975                          | 126227                          | 127855                          | 129988                          | 130772                          | 135329                          | 10205                                     | 8.97%                                     | 11326                                     | 9.13                                      | September 21, 2016 | 
```