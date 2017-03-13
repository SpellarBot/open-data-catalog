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
| Rows Updated | 2016-09-24T00:14:21Z |

## Description

Small Area Estimate Program (SAEP) April 1 population estimates for school districts, 2000-present.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                | meta_data | meta_data   |
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
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:krb3-8st4 d:2016-09-24T00:14:08.000Z t:saep_version="September 21, 2016" t:educational_service_district_code=113 t:unified_school_district_name="Aberdeen School District" t:percent_change_in_population_2000_to_2010=1.57% t:washington_school_district_code=14005 t:unified_school_district_code=30 m:numeric_change_in_population_2000_to_2010=314 m:numeric_change_in_population_2010_to_2015=-196 m:estimated_total_population_2007=20537 m:estimated_total_population_2006=20537 m:estimated_total_population_2009=20430 m:estimated_total_population_2008=20480 m:estimated_total_population_2016=20172 m:estimated_total_population_2015=20229 m:estimated_total_population_2001=20368 m:estimated_total_population_2014=20317 m:estimated_total_population_2000=20054 m:estimated_total_population_2013=20323 m:estimated_total_population_2012=20364 m:estimated_total_population_2003=20315 m:estimated_total_population_2011=20341 m:estimated_total_population_2002=20386 m:estimated_total_population_2010=20368 m:estimated_total_population_2005=20447 m:estimated_total_population_2004=20364

series e:krb3-8st4 d:2016-09-24T00:14:08.000Z t:saep_version="September 21, 2016" t:educational_service_district_code=113 t:unified_school_district_name="Adna School District" t:percent_change_in_population_2000_to_2010=30.37% t:washington_school_district_code=21226 t:unified_school_district_code=60 m:numeric_change_in_population_2000_to_2010=870 m:numeric_change_in_population_2010_to_2015=118 m:estimated_total_population_2007=3505 m:estimated_total_population_2006=3403 m:estimated_total_population_2009=3675 m:estimated_total_population_2008=3598 m:estimated_total_population_2016=3854 m:percent_change_in_population_2010_to_2015=3.15 m:estimated_total_population_2015=3838 m:estimated_total_population_2001=2956 m:estimated_total_population_2014=3805 m:estimated_total_population_2013=3795 m:estimated_total_population_2000=2866 m:estimated_total_population_2012=3799 m:estimated_total_population_2003=3115 m:estimated_total_population_2011=3791 m:estimated_total_population_2002=3045 m:estimated_total_population_2010=3736 m:estimated_total_population_2005=3289 m:estimated_total_population_2004=3201

series e:krb3-8st4 d:2016-09-24T00:14:08.000Z t:saep_version="September 21, 2016" t:educational_service_district_code=101 t:unified_school_district_name="Almira School District" t:percent_change_in_population_2000_to_2010="(  4.760%)" t:washington_school_district_code=22017 t:unified_school_district_code=90 m:numeric_change_in_population_2000_to_2010=-24 m:numeric_change_in_population_2010_to_2015=-12 m:estimated_total_population_2007=500 m:estimated_total_population_2006=499 m:estimated_total_population_2009=495 m:estimated_total_population_2008=500 m:estimated_total_population_2016=477 m:estimated_total_population_2015=484 m:estimated_total_population_2001=515 m:estimated_total_population_2014=485 m:estimated_total_population_2000=513 m:estimated_total_population_2013=490 m:estimated_total_population_2012=490 m:estimated_total_population_2003=499 m:estimated_total_population_2011=490 m:estimated_total_population_2002=509 m:estimated_total_population_2010=489 m:estimated_total_population_2005=500 m:estimated_total_population_2004=502
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

metric m:numeric_change_in_population_2000_to_2010 l:"Numeric Change in Population 2000 to 2010" t:dataTypeName=number

metric m:numeric_change_in_population_2010_to_2015 l:"Numeric Change in Population 2010 to 2016" t:dataTypeName=number

entity e:krb3-8st4 l:"WAOFM - SAEP - School District Population Estimates, 2000-2016" t:attribution="Washington State Office of Financial Management, Forecasting and Research Divisio" t:url=https://data.wa.gov/api/views/krb3-8st4

property e:krb3-8st4 t:meta.view v:id=krb3-8st4 v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/smallarea/default.asp v:averageRating=0 v:name="WAOFM - SAEP - School District Population Estimates, 2000-2016" v:attribution="Washington State Office of Financial Management, Forecasting and Research Divisio"

property e:krb3-8st4 t:meta.view.license v:name="Public Domain"

property e:krb3-8st4 t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"

property e:krb3-8st4 t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```