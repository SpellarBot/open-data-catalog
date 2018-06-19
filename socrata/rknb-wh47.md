# Cumulative Violent Crime Reduction Since 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cumulative-violent-crime-reduction-since-2006-b80f1) |
| Metadata | [Link](https://data.maryland.gov/api/views/rknb-wh47) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/rknb-wh47/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/rknb-wh47/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | rknb-wh47 |
| Name | Cumulative Violent Crime Reduction Since 2006 |
| Attribution | MSAC |
| Category | Public Safety |
| Tags | violent crime, crime, public safety, maryland state police, msp, homicide, goccp, governor's office of crime control and prevention |
| Created | 2012-09-05T18:42:14Z |
| Publication Date | 2015-01-09T16:34:45Z |

## Description

This dataset tracks the cumulative statewide reductions in violent crime since 2006. Data are reported each year by MSAC, the Maryland Statistical Analysis Center, within GOCCP, the Governor's Office of Crime Control and Prevention.

## Columns

```ls
| Included | Schema Type    | Field Name                                                       | Name                                                                   | Data Type | Render Type |
| ======== | ============== | ================================================================ | ====================================================================== | ========= | =========== |
| Yes      | time           | year                                                             | Year                                                                   | number    | text        |
| Yes      | numeric metric | total_violent_crime                                              | Total Violent Crime                                                    | number    | number      |
| Yes      | numeric metric | change_since_2006                                                | Total Violent Crime, % Change Since 2006                               | percent   | percent     |
| Yes      | numeric metric | female_homicide_victims                                          | Female Homicide Victims                                                | number    | number      |
| Yes      | numeric metric | female_homicides_change_since_2006                               | Female Homicides, % Change Since 2006                                  | percent   | percent     |
| Yes      | numeric metric | youth_homicide_victims                                           | Juvenile Homicide Victims                                              | number    | number      |
| Yes      | numeric metric | youth_homicide_victims_change_since_2006                         | Juvenile Homicide Victims, % Change Since 2006                         | percent   | percent     |
| Yes      | numeric metric | female_homicide_victims_youth_homicide_victims                   | Female Homicide Victims+Juvenile Homicide Victims                      | number    | number      |
| Yes      | numeric metric | female_homicide_victims_youth_homicide_victims_change_since_2006 | Female Homicide Victims+Juvenile Homicide Victims, % Change Since 2006 | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rknb-wh47 d:2006-01-01T00:00:00.000Z m:female_homicide_victims=76 m:female_homicide_victims_youth_homicide_victims=126 m:total_violent_crime=38111 m:female_homicide_victims_youth_homicide_victims_change_since_2006=0 m:youth_homicide_victims_change_since_2006=0 m:change_since_2006=0 m:female_homicides_change_since_2006=0 m:youth_homicide_victims=50

series e:rknb-wh47 d:2007-01-01T00:00:00.000Z m:female_homicide_victims=81 m:female_homicide_victims_youth_homicide_victims=135 m:total_violent_crime=36062 m:female_homicide_victims_youth_homicide_victims_change_since_2006=7.1 m:youth_homicide_victims_change_since_2006=8 m:change_since_2006=-5.4 m:female_homicides_change_since_2006=6.6 m:youth_homicide_victims=54

series e:rknb-wh47 d:2008-01-01T00:00:00.000Z m:female_homicide_victims=87 m:female_homicide_victims_youth_homicide_victims=139 m:total_violent_crime=35394 m:female_homicide_victims_youth_homicide_victims_change_since_2006=10.3 m:youth_homicide_victims_change_since_2006=4 m:change_since_2006=-7.1 m:female_homicides_change_since_2006=14.5 m:youth_homicide_victims=52
```

## Meta Commands

```ls
metric m:total_violent_crime p:integer l:"Total Violent Crime" t:dataTypeName=number

metric m:change_since_2006 p:double l:"Total Violent Crime, % Change Since 2006" t:dataTypeName=percent

metric m:female_homicide_victims p:integer l:"Female Homicide Victims" t:dataTypeName=number

metric m:female_homicides_change_since_2006 p:float l:"Female Homicides, % Change Since 2006" t:dataTypeName=percent

metric m:youth_homicide_victims p:integer l:"Juvenile Homicide Victims" t:dataTypeName=number

metric m:youth_homicide_victims_change_since_2006 p:double l:"Juvenile Homicide Victims, % Change Since 2006" t:dataTypeName=percent

metric m:female_homicide_victims_youth_homicide_victims p:integer l:"Female Homicide Victims+Juvenile Homicide Victims" t:dataTypeName=number

metric m:female_homicide_victims_youth_homicide_victims_change_since_2006 p:float l:"Female Homicide Victims+Juvenile Homicide Victims, % Change Since 2006" t:dataTypeName=percent

entity e:rknb-wh47 l:"Cumulative Violent Crime Reduction Since 2006" t:attribution=MSAC t:url=https://data.maryland.gov/api/views/rknb-wh47

property e:rknb-wh47 t:meta.view v:id=rknb-wh47 v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Cumulative Violent Crime Reduction Since 2006" v:attribution=MSAC

property e:rknb-wh47 t:meta.view.license v:name="Public Domain"

property e:rknb-wh47 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:rknb-wh47 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| year | total_violent_crime | change_since_2006 | female_homicide_victims | female_homicides_change_since_2006 | youth_homicide_victims | youth_homicide_victims_change_since_2006 | female_homicide_victims_youth_homicide_victims | female_homicide_victims_youth_homicide_victims_change_since_2006 | 
| ==== | =================== | ================= | ======================= | ================================== | ====================== | ======================================== | ============================================== | ================================================================ | 
| 2006 | 38111               | 0                 | 76                      | 0                                  | 50                     | 0                                        | 126                                            | 0                                                                | 
| 2007 | 36062               | -5.4              | 81                      | 6.6                                | 54                     | 8                                        | 135                                            | 7.1                                                              | 
| 2008 | 35394               | -7.1              | 87                      | 14.5                               | 52                     | 4                                        | 139                                            | 10.3                                                             | 
| 2009 | 33626               | -11.8             | 70                      | -7.9                               | 39                     | -22                                      | 109                                            | -13.5                                                            | 
| 2010 | 31605               | -17.1             | 68                      | -10.5                              | 31                     | -38.1                                    | 99                                             | -21.4                                                            | 
| 2011 | 28798               | -24.4             | 67                      | -11.8                              | 32                     | -36                                      | 99                                             | -21.4                                                            | 
| 2012 | 28079               | -26.3             | 63                      | -17.1                              | 24                     | -52                                      | 87                                             | -31                                                              | 
| 2013 | 27720               | -27.3             | 67                      | -11.8                              | 26                     | -48                                      | 93                                             | -26.1                                                            | 
| 2014 |                     |                   | 72                      | -5.2                               | 30                     | -40                                      | 102                                            | -19                                                              | 
```