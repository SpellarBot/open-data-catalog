# IDOL State Construction Minority and Female Building Trades Annual Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-state-construction-minority-and-female-building-trades-annual-report-eee5c) |
| Metadata | [Link](https://data.illinois.gov/api/views/ge5i-np92) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ge5i-np92/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ge5i-np92/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ge5i-np92 |
| Name | IDOL State Construction Minority and Female Building Trades Annual Report |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | construction, apprenticeship, minority and female building trades, labor, 30 ilcs 577 |
| Created | 2014-05-15T16:09:49Z |
| Publication Date | 2014-05-15T16:17:05Z |

## Description

All construction apprenticeship programs in Illinois are required to submit a report to the Illinois Department of Labor concerning the race, gender, ethnicity and national origin of apprentices participating in their programs.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | section     | SECTION    | text      | text        |
| Yes      | series tag     | response    | RESPONSE   | text      | text        |
| Yes      | numeric metric | 2011        | 2011       | number    | number      |
| Yes      | numeric metric | 2012        | 2012       | number    | number      |
| Yes      | numeric metric | 2013        | 2013       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ge5i-np92 d:2014-05-15T09:09:51.000Z t:response="Surveys Received" t:section=RACE m:2013=132 m:2012=137 m:2011=153

series e:ge5i-np92 d:2014-05-15T09:09:51.000Z t:response="Total Number of Apprentices Reported in Surveys" t:section=RACE m:2013=8642 m:2012=9899 m:2011=11021

series e:ge5i-np92 d:2014-05-15T09:09:51.000Z t:response=Male t:section=GENDER m:2013=8281 m:2012=9500 m:2011=10603
```

## Meta Commands

```ls
metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

entity e:ge5i-np92 l:"IDOL State Construction Minority and Female Building Trades Annual Report" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/ge5i-np92

property e:ge5i-np92 t:meta.view v:id=ge5i-np92 v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL State Construction Minority and Female Building Trades Annual Report" v:attribution="Illinois Department of Labor"

property e:ge5i-np92 t:meta.view.license v:name="Public Domain"

property e:ge5i-np92 t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:ge5i-np92 t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| :updated_at | section   | response                                        | 2011  | 2012 | 2013 | 
| =========== | ========= | =============================================== | ===== | ==== | ==== | 
| 1400144991  | RACE      | Surveys Received                                | 153   | 137  | 132  | 
| 1400144991  | RACE      | Total Number of Apprentices Reported in Surveys | 11021 | 9899 | 8642 | 
| 1400144991  | GENDER    | Male                                            | 10603 | 9500 | 8281 | 
| 1400144991  | GENDER    | Female                                          | 402   | 377  | 351  | 
| 1400144991  | GENDER    | No Response                                     | 16    | 22   | 10   | 
| 1400144991  | ETHNICITY | Non-Hispanic or Latino                          | 7371  | 8002 | 6978 | 
| 1400144991  | ETHNICITY | Hispanic or Latino                              | 1557  | 1298 | 1066 | 
| 1400144991  | ETHNICITY | Unknown                                         | 292   | 414  | 469  | 
| 1400144991  | ETHNICITY | No Response                                     | 1801  | 185  | 129  | 
| 1400144991  | RACE      | Native Hawaiian or other Pacific Islander       | 45    | 16   | 13   | 
```