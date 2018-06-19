# New York City Leading Causes of Death

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-leading-causes-of-death-ce97f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jb7j-dtam) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jb7j-dtam/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jb7j-dtam/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jb7j-dtam |
| Name | New York City Leading Causes of Death |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | death, cause, vital statistic, race, ethnicity, male, female |
| Created | 2013-11-20T16:01:36Z |
| Publication Date | 2017-01-20T17:01:39Z |

## Description

The leading causes of death by sex and ethnicity in New York City in since 2007.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | year                    | Year                    | number    | text        |
| Yes      | series tag     | leading_cause           | Leading Cause           | text      | text        |
| Yes      | series tag     | sex                     | Sex                     | text      | text        |
| Yes      | series tag     | race_ethnicity          | Race Ethnicity          | text      | text        |
| Yes      | numeric metric | deaths                  | Deaths                  | number    | text        |
| Yes      | numeric metric | death_rate              | Death Rate              | number    | text        |
| Yes      | numeric metric | age_adjusted_death_rate | Age Adjusted Death Rate | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jb7j-dtam d:2014-01-01T00:00:00.000Z t:leading_cause="Diabetes Mellitus (E10-E14)" t:age_adjusted_death_rate=. t:sex=F t:race_ethnicity="Other Race/ Ethnicity" t:death_rate=. m:deaths=11

series e:jb7j-dtam d:2011-01-01T00:00:00.000Z t:leading_cause="Cerebrovascular Disease (Stroke: I60-I69)" t:sex=M t:race_ethnicity="White Non-Hispanic" m:age_adjusted_death_rate=18.2 m:deaths=290 m:death_rate=21.7

series e:jb7j-dtam d:2008-01-01T00:00:00.000Z t:leading_cause="Malignant Neoplasms (Cancer: C00-C97)" t:age_adjusted_death_rate=. t:sex=M t:race_ethnicity="Not Stated/Unknown" t:death_rate=. m:deaths=60
```

## Meta Commands

```ls
entity e:jb7j-dtam l:"New York City Leading Causes of Death" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/jb7j-dtam

property e:jb7j-dtam t:meta.view v:id=jb7j-dtam v:category=Health v:averageRating=0 v:name="New York City Leading Causes of Death" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:jb7j-dtam t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jb7j-dtam t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | leading_cause                                               | sex | race_ethnicity        | deaths | death_rate | age_adjusted_death_rate | 
| ==== | =========================================================== | === | ===================== | ====== | ========== | ======================= | 
| 2014 | Diabetes Mellitus (E10-E14)                                 | F   | Other Race/ Ethnicity | 11     | .          | .                       | 
| 2011 | Cerebrovascular Disease (Stroke: I60-I69)                   | M   | White Non-Hispanic    | 290    | 21.7       | 18.2                    | 
| 2008 | Malignant Neoplasms (Cancer: C00-C97)                       | M   | Not Stated/Unknown    | 60     | .          | .                       | 
| 2010 | Malignant Neoplasms (Cancer: C00-C97)                       | F   | Hispanic              | 1045   | 85.9       | 98.5                    | 
| 2012 | Cerebrovascular Disease (Stroke: I60-I69)                   | M   | Black Non-Hispanic    | 170    | 19.9       | 23.3                    | 
| 2007 | Mental and Behavioral Disorders due to Use of Alcohol (F10) | M   | Not Stated/Unknown    | .      | .          | .                       | 
| 2011 | All Other Causes                                            | F   | Not Stated/Unknown    | 14     | .          | .                       | 
| 2007 | Chronic Lower Respiratory Diseases (J40-J47)                | F   | Black Non-Hispanic    | 163    | 15.5       | 14.8                    | 
| 2012 | Essential Hypertension and Renal Diseases (I10, I12)        | F   | Hispanic              | 101    | 8.2        | 9.5                     | 
| 2009 | Diseases of Heart (I00-I09, I11, I13, I20-I51)              | M   | Hispanic              | 1382   | 123.1      | 227.9                   | 
```