# Maryland Department of Public Safety and Correctional Services (DPSCS) Dashboard Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-department-of-public-safety-and-correctional-services-dpscs-dashboard-measures) |
| Metadata | [Link](https://data.maryland.gov/api/views/6swu-cddu) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6swu-cddu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6swu-cddu/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6swu-cddu |
| Name | Maryland Department of Public Safety and Correctional Services (DPSCS) Dashboard Measures |
| Attribution | Maryland Department of Public Safety and Correctional Services Grants Policy and Statistics Unit |
| Category | Public Safety |
| Tags | justice reinvestment, recidivism, corrections, community supervision, inmate, offender, 911, ensb emergency numbers system board |
| Created | 2016-06-30T03:24:36Z |
| Publication Date | 2017-01-11T23:13:44Z |

## Description

Data Sources: Percentage of sentenced offenders returned to correctional or community supervision for a new offense within one year of release; Text-to-911 Implementation by County

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                                 | Data Type     | Render Type   |
| ======== | ============== | ================================================ | ==================================================== | ============= | ============= |
| Yes      | time           | date                                             | Date                                                 | calendar_date | calendar_date |
| No       |                | fiscal_year                                      | Fiscal Year                                          | number        | text          |
| Yes      | numeric metric | all_releases_with_new_offense                    | All releases - % with new offense                    | percent       | percent       |
| Yes      | numeric metric | parolees_with_new_offense                        | Parolees - % with new offense                        | percent       | percent       |
| Yes      | numeric metric | mandatory_releases_with_new_offense              | Mandatory Releases - % with new offense              | percent       | percent       |
| Yes      | numeric metric | expiration_of_sentence_releases_with_new_offense | Expiration of Sentence releases - % with new offense | percent       | percent       |
| Yes      | numeric metric | text_to_911_counties                             | Text-to-911 Counties                                 | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:6swu-cddu d:2011-06-30T00:00:00.000Z m:all_releases_with_new_offense=15.5 m:parolees_with_new_offense=9.5 m:mandatory_releases_with_new_offense=12.9 m:expiration_of_sentence_releases_with_new_offense=23.3

series e:6swu-cddu d:2012-06-30T00:00:00.000Z m:all_releases_with_new_offense=16.6 m:parolees_with_new_offense=7.8 m:mandatory_releases_with_new_offense=13.6 m:expiration_of_sentence_releases_with_new_offense=24.3

series e:6swu-cddu d:2013-06-30T00:00:00.000Z m:all_releases_with_new_offense=16.9 m:parolees_with_new_offense=8.3 m:mandatory_releases_with_new_offense=14.7 m:expiration_of_sentence_releases_with_new_offense=25.4
```

## Meta Commands

```ls
metric m:all_releases_with_new_offense p:float l:"All releases - % with new offense" t:dataTypeName=percent

metric m:parolees_with_new_offense p:float l:"Parolees - % with new offense" t:dataTypeName=percent

metric m:mandatory_releases_with_new_offense p:float l:"Mandatory Releases - % with new offense" d:"Mandatory Release is the result of an inmate being released prior to the end of his sentence due to dimunition (good time) credits. The inmate must remain under Community Supervison until the expiration of their sentence." t:dataTypeName=percent

metric m:expiration_of_sentence_releases_with_new_offense p:float l:"Expiration of Sentence releases - % with new offense" d:"For an inmate to be released on expiration of sentence they either did not qualify for or earn dimunition (good time) credits." t:dataTypeName=percent

metric m:text_to_911_counties p:float l:"Text-to-911 Counties" d:"Percentage of 911 call centers that have the technology and are receiving and responding to text-to-911 emergency messages" t:dataTypeName=percent

entity e:6swu-cddu l:"Maryland Department of Public Safety and Correctional Services (DPSCS) Dashboard Measures" t:attribution="Maryland Department of Public Safety and Correctional Services Grants Policy and Statistics Unit" t:url=https://data.maryland.gov/api/views/6swu-cddu

property e:6swu-cddu t:meta.view v:id=6swu-cddu v:category="Public Safety" v:attributionLink=http://www.dpscs.state.md.us/ v:averageRating=0 v:name="Maryland Department of Public Safety and Correctional Services (DPSCS) Dashboard Measures" v:attribution="Maryland Department of Public Safety and Correctional Services Grants Policy and Statistics Unit"

property e:6swu-cddu t:meta.view.owner v:id=7jzz-xryq v:screenName="Jay Miller" v:displayName="Jay Miller"

property e:6swu-cddu t:meta.view.tableauthor v:id=7jzz-xryq v:screenName="Jay Miller" v:roleName=editor v:displayName="Jay Miller"
```

## Top Records

```ls
| date                | fiscal_year | all_releases_with_new_offense | parolees_with_new_offense | mandatory_releases_with_new_offense | expiration_of_sentence_releases_with_new_offense | text_to_911_counties | 
| =================== | =========== | ============================= | ========================= | =================================== | ================================================ | ==================== | 
| 2011-06-30T00:00:00 | 2011        | 15.5                          | 9.5                       | 12.9                                | 23.3                                             |                      | 
| 2012-06-30T00:00:00 | 2012        | 16.6                          | 7.8                       | 13.6                                | 24.3                                             |                      | 
| 2013-06-30T00:00:00 | 2013        | 16.9                          | 8.3                       | 14.7                                | 25.4                                             |                      | 
```