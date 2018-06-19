# 4-Year Graduation Rates by Cohort and Public School District

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/4-year-graduation-rates-by-cohort-and-public-school-district) |
| Metadata | [Link](https://data.iowa.gov/api/views/tqti-3w6t) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tqti-3w6t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tqti-3w6t/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tqti-3w6t |
| Name | 4-Year Graduation Rates by Cohort and Public School District |
| Attribution | Iowa Department of Education, Basic Educational Data Survey (BEDS) and SRI (EASIER) Files |
| Category | Education |
| Tags | student performance, graduation rates, high school |
| Created | 2014-11-26T21:19:50Z |
| Publication Date | 2015-06-17T19:35:25Z |

## Description

This dataset provides the 4-Year graduation rates by cohort (represented by graduating class) and public school district starting with the Class of 2009.  A cohort in the graduation rate calculation starts with a group of students entering ninth grade for the first time. The cohort is adjusted to add students that transfer in and subtract students that transfer out during a four year time period for calculating a graduation rate.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | numeric metric | graduating_class         | Graduating Class         | number    | number      |
| Yes      | time           | fall_freshman_year       | Fall Freshman Year       | number    | number      |
| Yes      | series tag     | district                 | District                 | text      | text        |
| Yes      | series tag     | district_name            | District Name            | text      | text        |
| Yes      | numeric metric | graduates                | Graduates                | number    | number      |
| Yes      | numeric metric | total_cohort             | Total Cohort             | number    | number      |
| Yes      | numeric metric | graduation_rate          | Graduation Rate          | number    | number      |
| Yes      | series tag     | graduation_rate_category | Graduation Rate Category | text      | text        |
```

## Time Field

```ls
Value = fall_freshman_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tqti-3w6t d:2006-01-01T00:00:00.000Z t:district_name=Earlham t:graduation_rate_category="85.01 - 90.00%" t:district=1953 m:total_cohort=49 m:graduation_rate=89.8 m:graduating_class=2010 m:graduates=44

series e:tqti-3w6t d:2008-01-01T00:00:00.000Z t:district_name=Montezuma t:graduation_rate_category="95.01 - 100.00%" t:district=4437 m:total_cohort=43 m:graduation_rate=95.35 m:graduating_class=2012 m:graduates=41

series e:tqti-3w6t d:2005-01-01T00:00:00.000Z t:district_name=Spencer t:graduation_rate_category="85.01 - 90.00%" t:district=6102 m:total_cohort=174 m:graduation_rate=87.36 m:graduating_class=2009 m:graduates=152
```

## Meta Commands

```ls
metric m:graduating_class p:integer l:"Graduating Class" d:"Year the class is expected to graduate" t:dataTypeName=number

metric m:graduates p:integer l:Graduates d:"First time freshman in year indicated in fall freshman year and transfers into the cohort in grades 9 to 12 who graduated in year indicated in graduating class or earlier. SCS (small cell size) indicates data was redacted to ensure privacy standards where met." t:dataTypeName=number

metric m:total_cohort p:integer l:"Total Cohort" d:"First time freshman in year indicated in fall freshman year and transfers into the cohort in grades 9 to 12 less those who transferred out (including deceased). SCS (small cell size) indicates data was redacted to ensure privacy standards where met." t:dataTypeName=number

metric m:graduation_rate p:double l:"Graduation Rate" d:"Graduates divided by Total Cohort multiplied by 100. SCS (small cell size) indicates data was redacted to ensure privacy standards where met." t:dataTypeName=number

entity e:tqti-3w6t l:"4-Year Graduation Rates by Cohort and Public School District" t:attribution="Iowa Department of Education, Basic Educational Data Survey (BEDS) and SRI (EASIER) Files" t:url=https://data.iowa.gov/api/views/tqti-3w6t

property e:tqti-3w6t t:meta.view v:id=tqti-3w6t v:category=Education v:averageRating=0 v:name="4-Year Graduation Rates by Cohort and Public School District" v:attribution="Iowa Department of Education, Basic Educational Data Survey (BEDS) and SRI (EASIER) Files"

property e:tqti-3w6t t:meta.view.license v:name="Public Domain"

property e:tqti-3w6t t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:tqti-3w6t t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| graduating_class | fall_freshman_year | district | district_name      | graduates | total_cohort | graduation_rate | graduation_rate_category | 
| ================ | ================== | ======== | ================== | ========= | ============ | =============== | ======================== | 
| 2010             | 2006               | 1953     | Earlham            | 44        | 49           | 89.8            | 85.01 - 90.00%           | 
| 2012             | 2008               | 4437     | Montezuma          | 41        | 43           | 95.35           | 95.01 - 100.00%          | 
| 2009             | 2005               | 6102     | Spencer            | 152       | 174          | 87.36           | 85.01 - 90.00%           | 
| 2010             | 2006               | 3154     | Iowa Valley        | 56        | 66           | 84.85           | 80.01 - 85.00%           | 
| 2011             | 2007               | 2151     | Exira              | 15        | 18           | 83.33           | 80.01 - 85.00%           | 
| 2009             | 2005               | 4491     | Moravia            | 21        | 25           | 84              | 80.01 - 85.00%           | 
| 2013             | 2009               | 4446     | Monticello         | 73        | 84           | 86.9            | 85.01 - 90.00%           | 
| 2011             | 2007               | 2556     | Graettinger-Terril | 23        | 24           | 95.83           | 95.01 - 100.00%          | 
| 2009             | 2005               | 2673     | Nodaway Valley     | 68        | 70           | 97.14           | 95.01 - 100.00%          | 
| 2012             | 2008               | 1431     | Corning            | 46        | 46           | 100             | 95.01 - 100.00%          | 
```