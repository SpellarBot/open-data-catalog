# 2014 Maryland State Police Accident Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-maryland-state-police-accident-reporting-d62d5) |
| Metadata | [Link](https://data.maryland.gov/api/views/jjf7-k22c) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/jjf7-k22c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/jjf7-k22c/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | jjf7-k22c |
| Name | 2014 Maryland State Police Accident Reporting |
| Attribution | Maryland State Police |
| Category | Public Safety |
| Tags | msp, accidents, traffic accidents, crashes, collisions |
| Created | 2014-10-16T14:39:32Z |
| Publication Date | 2014-10-19T22:06:17Z |

## Description

Dataset shows the total number of traffic accidents handled by the Maryland State Police for calendar year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                           | Data Type | Render Type |
| ======== | ============== | ================================= | ============================================== | ========= | =========== |
| Yes      | series tag     | 2014_month                        | 2014 Month                                     | text      | text        |
| Yes      | numeric metric | accident_report_filed             | Number of Accident Reports Filed               | number    | number      |
| Yes      | numeric metric | accident_report_not_filed_code_89 | Number of Accident Reports Not Filed (Code 89) | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jjf7-k22c d:2014-01-01T00:00:00.000Z t:2014_month=January m:accident_report_filed=1450 m:accident_report_not_filed_code_89=1005

series e:jjf7-k22c d:2014-01-01T00:00:00.000Z t:2014_month=February m:accident_report_filed=1028 m:accident_report_not_filed_code_89=642

series e:jjf7-k22c d:2014-01-01T00:00:00.000Z t:2014_month=March m:accident_report_filed=1189 m:accident_report_not_filed_code_89=793
```

## Meta Commands

```ls
metric m:accident_report_filed p:integer l:"Number of Accident Reports Filed" t:dataTypeName=number

metric m:accident_report_not_filed_code_89 p:integer l:"Number of Accident Reports Not Filed (Code 89)" t:dataTypeName=number

entity e:jjf7-k22c l:"2014 Maryland State Police Accident Reporting" t:attribution="Maryland State Police" t:url=https://data.maryland.gov/api/views/jjf7-k22c

property e:jjf7-k22c t:meta.view v:id=jjf7-k22c v:category="Public Safety" v:averageRating=0 v:name="2014 Maryland State Police Accident Reporting" v:attribution="Maryland State Police"

property e:jjf7-k22c t:meta.view.license v:name="Public Domain"

property e:jjf7-k22c t:meta.view.owner v:id=v448-7imn v:screenName=Jimmy v:displayName=Jimmy

property e:jjf7-k22c t:meta.view.tableauthor v:id=v448-7imn v:screenName=Jimmy v:roleName=editor v:displayName=Jimmy
```

## Top Records

```ls
| 2014_month            | accident_report_filed | accident_report_not_filed_code_89 | 
| ===================== | ===================== | ================================= | 
| January               | 1450                  | 1005                              | 
| February              | 1028                  | 642                               | 
| March                 | 1189                  | 793                               | 
| April                 | 1211                  | 788                               | 
| May                   | 1357                  | 938                               | 
| June                  | 1504                  | 1050                              | 
| July                  | 1423                  | 1022                              | 
| August                | 1481                  | 1099                              | 
| September             | 1344                  | 971                               | 
| YTD - Total Statewide | 11987                 | 8308                              | 
```