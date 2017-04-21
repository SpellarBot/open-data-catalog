# Poverty Rate With Margin Of Error, 2006-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/poverty-rate-with-margin-of-error-2006-2012-84226) |
| Metadata | [Link](https://data.maryland.gov/api/views/qnk2-m5pz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qnk2-m5pz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qnk2-m5pz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qnk2-m5pz |
| Name | Poverty Rate With Margin Of Error, 2006-2013 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | poverty rate |
| Created | 2014-09-03T16:37:35Z |
| Publication Date | 2015-11-17T17:30:50Z |

## Description

The data consist of the poverty rate by the year in Maryland and the margin of error of the poverty rate from 2006 to 2013. MOE= Margin of Error for the 90% confidence interval. Source from the U.S. Census Bureau, Small Area Income and Poverty Estimates, July 2014.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| Yes      | series tag     | year                 | Year                  | text      | text        |
| Yes      | numeric metric | poverty_rate_2006    | Poverty Rate, 2006    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2006 | Margin of Error, 2006 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2007    | Poverty Rate, 2007    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2007 | Margin of Error, 2007 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2008    | Poverty Rate, 2008    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2008 | Margin of Error, 2008 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2009    | Poverty Rate, 2009    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2009 | Margin of Error, 2009 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2010    | Poverty Rate, 2010    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2010 | Margin of Error, 2010 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2011    | Poverty Rate, 2011    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2011 | Margin of Error, 2011 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2012    | Poverty Rate, 2012    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2012 | Margin of Error, 2012 | percent   | percent     |
| Yes      | numeric metric | poverty_rate_2013    | Poverty Rate, 2013    | percent   | percent     |
| Yes      | numeric metric | margin_of_error_2013 | Margin of Error, 2013 | percent   | percent     |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qnk2-m5pz d:2006-01-01T00:00:00.000Z t:year=MARYLAND m:poverty_rate_2013=10.2 m:poverty_rate_2012=10.4 m:poverty_rate_2008=8.2 m:poverty_rate_2007=8.3 m:poverty_rate_2006=8 m:margin_of_error_2012=0.3 m:margin_of_error_2011=0.3 m:margin_of_error_2013=0.3 m:poverty_rate_2011=10.2 m:margin_of_error_2010=0.3 m:poverty_rate_2010=9.9 m:margin_of_error_2006=0.2 m:margin_of_error_2007=0.2 m:margin_of_error_2008=0.3 m:margin_of_error_2009=0.3 m:poverty_rate_2009=9.2

series e:qnk2-m5pz d:2006-01-01T00:00:00.000Z t:year="Allegany County" m:poverty_rate_2013=18.6 m:poverty_rate_2012=18.1 m:poverty_rate_2008=15.3 m:poverty_rate_2007=14.2 m:poverty_rate_2006=14.9 m:margin_of_error_2012=2.8 m:margin_of_error_2011=3.4 m:margin_of_error_2013=3.3 m:poverty_rate_2011=19.1 m:margin_of_error_2010=3 m:poverty_rate_2010=17.1 m:margin_of_error_2006=2.3 m:margin_of_error_2007=2.1 m:margin_of_error_2008=2.8 m:margin_of_error_2009=3.3 m:poverty_rate_2009=16.6

series e:qnk2-m5pz d:2006-01-01T00:00:00.000Z t:year="Anne Arundel County" m:poverty_rate_2013=7.3 m:poverty_rate_2012=6.3 m:poverty_rate_2008=5 m:poverty_rate_2007=5 m:poverty_rate_2006=4.8 m:margin_of_error_2012=1 m:margin_of_error_2011=1.2 m:margin_of_error_2013=1.1 m:poverty_rate_2011=6.5 m:margin_of_error_2010=1.1 m:poverty_rate_2010=6.6 m:margin_of_error_2006=0.6 m:margin_of_error_2007=0.7 m:margin_of_error_2008=0.8 m:margin_of_error_2009=1 m:poverty_rate_2009=6.8
```

## Meta Commands

```ls
metric m:poverty_rate_2006 p:double l:"Poverty Rate, 2006" t:dataTypeName=percent

metric m:margin_of_error_2006 p:double l:"Margin of Error, 2006" t:dataTypeName=percent

metric m:poverty_rate_2007 p:double l:"Poverty Rate, 2007" t:dataTypeName=percent

metric m:margin_of_error_2007 p:double l:"Margin of Error, 2007" t:dataTypeName=percent

metric m:poverty_rate_2008 p:double l:"Poverty Rate, 2008" t:dataTypeName=percent

metric m:margin_of_error_2008 p:double l:"Margin of Error, 2008" t:dataTypeName=percent

metric m:poverty_rate_2009 p:double l:"Poverty Rate, 2009" t:dataTypeName=percent

metric m:margin_of_error_2009 p:double l:"Margin of Error, 2009" t:dataTypeName=percent

metric m:poverty_rate_2010 p:double l:"Poverty Rate, 2010" t:dataTypeName=percent

metric m:margin_of_error_2010 p:double l:"Margin of Error, 2010" t:dataTypeName=percent

metric m:poverty_rate_2011 p:double l:"Poverty Rate, 2011" t:dataTypeName=percent

metric m:margin_of_error_2011 p:double l:"Margin of Error, 2011" t:dataTypeName=percent

metric m:poverty_rate_2012 p:double l:"Poverty Rate, 2012" t:dataTypeName=percent

metric m:margin_of_error_2012 p:double l:"Margin of Error, 2012" t:dataTypeName=percent

metric m:poverty_rate_2013 p:double l:"Poverty Rate, 2013" t:dataTypeName=percent

metric m:margin_of_error_2013 p:double l:"Margin of Error, 2013" t:dataTypeName=percent

entity e:qnk2-m5pz l:"Poverty Rate With Margin Of Error, 2006-2013" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/qnk2-m5pz

property e:qnk2-m5pz t:meta.view v:id=qnk2-m5pz v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/poverty/poverty.shtml v:averageRating=0 v:name="Poverty Rate With Margin Of Error, 2006-2013" v:attribution="Maryland Department of Planning"

property e:qnk2-m5pz t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:qnk2-m5pz t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year                | poverty_rate_2006 | margin_of_error_2006 | poverty_rate_2007 | margin_of_error_2007 | poverty_rate_2008 | margin_of_error_2008 | poverty_rate_2009 | margin_of_error_2009 | poverty_rate_2010 | margin_of_error_2010 | poverty_rate_2011 | margin_of_error_2011 | poverty_rate_2012 | margin_of_error_2012 | poverty_rate_2013 | margin_of_error_2013 | 
| =================== | ================= | ==================== | ================= | ==================== | ================= | ==================== | ================= | ==================== | ================= | ==================== | ================= | ==================== | ================= | ==================== | ================= | ==================== | 
| MARYLAND            | 8.0               | 0.2                  | 8.3               | 0.2                  | 8.2               | 0.3                  | 9.2               | 0.3                  | 9.9               | 0.3                  | 10.2              | 0.3                  | 10.4              | 0.3                  | 10.2              | 0.3                  | 
| Allegany County     | 14.9              | 2.3                  | 14.2              | 2.1                  | 15.3              | 2.8                  | 16.6              | 3.3                  | 17.1              | 3.0                  | 19.1              | 3.4                  | 18.1              | 2.8                  | 18.6              | 3.3                  | 
| Anne Arundel County | 4.8               | 0.6                  | 5.0               | 0.7                  | 5.0               | 0.8                  | 6.8               | 1.0                  | 6.6               | 1.1                  | 6.5               | 1.2                  | 6.3               | 1.0                  | 7.3               | 1.1                  | 
| Baltimore City      | 19.2              | 1.5                  | 19.9              | 1.6                  | 19.2              | 1.6                  | 20.9              | 1.7                  | 24.7              | 1.8                  | 24.5              | 1.7                  | 24.5              | 1.7                  | 22.7              | 1.6                  | 
| Baltimore County    | 8.0               | 0.8                  | 7.6               | 0.9                  | 7.9               | 0.9                  | 8.3               | 1.0                  | 8.2               | 1.2                  | 9.6               | 1.2                  | 9.7               | 1.0                  | 9.5               | 1.0                  | 
| Calvert County      | 4.4               | 0.9                  | 5.2               | 1.1                  | 5.6               | 1.0                  | 5.4               | 1.4                  | 6.2               | 1.4                  | 6.1               | 1.5                  | 7.0               | 1.3                  | 6.9               | 1.4                  | 
| Caroline County     | 11.0              | 2.1                  | 11.7              | 2.3                  | 10.8              | 2.0                  | 13.2              | 2.9                  | 13.0              | 2.8                  | 13.1              | 2.7                  | 15.7              | 2.7                  | 16.7              | 2.8                  | 
| Carroll County      | 4.0               | 0.7                  | 4.7               | 0.9                  | 5.6               | 0.9                  | 5.9               | 1.1                  | 5.4               | 1.1                  | 5.5               | 1.2                  | 6.3               | 1.1                  | 6.8               | 1.2                  | 
| Cecil County        | 7.8               | 1.5                  | 9.3               | 1.7                  | 7.2               | 1.3                  | 10.0              | 1.8                  | 10.5              | 2.0                  | 9.7               | 2.2                  | 11.9              | 1.9                  | 9.8               | 2.0                  | 
| Charles County      | 6.2               | 1.1                  | 5.9               | 1.3                  | 6.2               | 1.0                  | 6.4               | 1.6                  | 6.2               | 1.4                  | 7.7               | 1.5                  | 8.6               | 1.3                  | 8.0               | 1.5                  | 
```