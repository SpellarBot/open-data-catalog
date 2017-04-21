# Youth Behavior Risk Survey

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youth-behavioral-risk-survey) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3qty-g4aq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3qty-g4aq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3qty-g4aq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3qty-g4aq |
| Name | Youth Behavior Risk Survey |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | survey, risk, health, youth, dohmh |
| Created | 2016-10-28T13:42:48Z |
| Publication Date | 2017-01-20T17:10:30Z |

## Description

Summary results from YRBS 2011, 2013 
Source: Youth Risk Behavior Survey (2011, 2013) 

Data are weighted to the NYC public high school student population 
Data prepared by Bureau of Epidemiology Services, New York City Department of Health and Mental Hygiene, April 2016

The NYC Youth Risk Behavior Survey (YRBS) is conducted through an ongoing collaboration between the New York City Department of Health and Mental Hygiene (DOHMH), the Department of Education (DOE), and the National Centers for Disease Control and Prevention (CDC). The New York City's YRBS is part of the CDC's National Youth Risk Behavior Surveillance System (YRBSS). The survey's primary purpose is to monitor priority health risk behaviors that contribute to the leading causes of mortality, morbidity, and social problems among youth in New York City. For more information see EpiQuery, https://a816-healthpsi.nyc.gov/epiquery/YRBS/yrbsIndex.html.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| Yes      | series tag  | survey     | Survey     | text      | text        |
| Yes      | series tag  | question   | Question   | text      | text        |
| Yes      | time        | year       | Year       | number    | number      |
| Yes      | series tag  | prevalence | Prevalence | text      | text        |
| Yes      | series tag  | lower95_ci | Lower95%CI | text      | text        |
| Yes      | series tag  | upper95_ci | Upper95%CI | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:3qty-g4aq l:"Youth Behavior Risk Survey" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/3qty-g4aq

property e:3qty-g4aq t:meta.view v:id=3qty-g4aq v:category=Health v:averageRating=0 v:name="Youth Behavior Risk Survey" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:3qty-g4aq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3qty-g4aq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| survey | question                                                     | year | prevalence | lower95_ci | upper95_ci | 
| ====== | ============================================================ | ==== | ========== | ========== | ========== | 
| YRBS   | Physically active 60 minutes per day                         | 2011 | 20.3       | 19.1       | 21.6       | 
| YRBS   | Drank five or more alcoholic drinks in a row in past 30 days | 2011 | 12.7       | 11.7       | 13.9       | 
| YRBS   | Physically active 60 minutes per day                         | 2013 | 18.7       | 17.1       | 20.5       | 
| YRBS   | Got help from a counselor in past 12 months                  | 2013 | 17.9       | 16.5       | 19.4       | 
| YRBS   | Adolescent obesity                                           | 2011 | 11.6       | 10.6       | 12.8       | 
| YRBS   | Smoked at least once past 30 days                            | 2013 | 8.2        | 6.9        | 9.7        | 
| YRBS   | Drinks 1 or more sodas per day in past 7 days                | 2013 | 15.7       | 14.6       | 16.9       | 
| YRBS   | Smoked at least once past 30 days                            | 2011 | 8.5        | 7.5        | 9.6        | 
| YRBS   | Drank five or more alcoholic drinks in a row in past 30 days | 2013 | 10.8       | 9.8        | 11.8       | 
| YRBS   | Adolescent obesity                                           | 2013 | 11.8       | 10.6       | 13.2       | 
```