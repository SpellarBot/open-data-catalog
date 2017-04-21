# Citywide HRA- Administered Medicaid Enrollees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citywide-hra-administered-medicaid-enrollees) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/33db-aeds) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/33db-aeds/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/33db-aeds/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 33db-aeds |
| Name | Citywide HRA- Administered Medicaid Enrollees |
| Attribution | Human Resource Administration (HRA) |
| Category | Social Services |
| Created | 2016-01-14T17:37:54Z |
| Publication Date | 2016-11-04T14:09:02Z |

## Description

Total number of enrollees in Medicaid

## Columns

```ls
| Included | Schema Type    | Field Name                                        | Name                                              | Data Type | Render Type |
| ======== | ============== | ================================================= | ================================================= | ========= | =========== |
| Yes      | time           | month                                             | Month                                             | text      | text        |
| Yes      | numeric metric | cash_assistance_medical_assistance                | Cash Assistance - Medical Assistance              | number    | number      |
| Yes      | numeric metric | supplemental_security_income_medical_assistance   | Supplemental Security Income - Medical Assistance | number    | number      |
| Yes      | numeric metric | nursing_home_medical_assistance                   | Nursing Home - Medical Assistance                 | number    | number      |
| Yes      | numeric metric | medical_assistance_only                           | Medical Assistance Only                           | number    | number      |
| Yes      | numeric metric | total_hra_enrolled_medical_assistance_individuals | Total HRA-Enrolled Medical Assistance Individuals | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:33db-aeds d:2007-01-01T00:00:00.000Z m:supplemental_security_income_medical_assistance=407863 m:nursing_home_medical_assistance=40943 m:cash_assistance_medical_assistance=369672 m:total_hra_enrolled_medical_assistance_individuals=2553064 m:medical_assistance_only=1775529

series e:33db-aeds d:2007-02-01T00:00:00.000Z m:supplemental_security_income_medical_assistance=407459 m:nursing_home_medical_assistance=40536 m:cash_assistance_medical_assistance=363960 m:total_hra_enrolled_medical_assistance_individuals=2533062 m:medical_assistance_only=1761643

series e:33db-aeds d:2007-03-01T00:00:00.000Z m:supplemental_security_income_medical_assistance=408022 m:nursing_home_medical_assistance=40276 m:cash_assistance_medical_assistance=363130 m:total_hra_enrolled_medical_assistance_individuals=2560715 m:medical_assistance_only=1789563
```

## Meta Commands

```ls
metric m:cash_assistance_medical_assistance p:integer l:"Cash Assistance - Medical Assistance" t:dataTypeName=number

metric m:supplemental_security_income_medical_assistance p:integer l:"Supplemental Security Income - Medical Assistance" t:dataTypeName=number

metric m:nursing_home_medical_assistance p:integer l:"Nursing Home - Medical Assistance" t:dataTypeName=number

metric m:medical_assistance_only p:integer l:"Medical Assistance Only" t:dataTypeName=number

metric m:total_hra_enrolled_medical_assistance_individuals p:integer l:"Total HRA-Enrolled Medical Assistance Individuals" t:dataTypeName=number

entity e:33db-aeds l:"Citywide HRA- Administered Medicaid Enrollees" t:attribution="Human Resource Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/33db-aeds

property e:33db-aeds t:meta.view v:id=33db-aeds v:category="Social Services" v:averageRating=0 v:name="Citywide HRA- Administered Medicaid Enrollees" v:attribution="Human Resource Administration (HRA)"

property e:33db-aeds t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:33db-aeds t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| month  | cash_assistance_medical_assistance | supplemental_security_income_medical_assistance | nursing_home_medical_assistance | medical_assistance_only | total_hra_enrolled_medical_assistance_individuals | 
| ====== | ================================== | =============================================== | =============================== | ======================= | ================================================= | 
| Jan-07 | 369672                             | 407863                                          | 40943                           | 1775529                 | 2553064                                           | 
| Feb-07 | 363960                             | 407459                                          | 40536                           | 1761643                 | 2533062                                           | 
| Mar-07 | 363130                             | 408022                                          | 40276                           | 1789563                 | 2560715                                           | 
| Apr-07 | 358717                             | 407465                                          | 40087                           | 1772670                 | 2538852                                           | 
| May-07 | 355795                             | 408011                                          | 39707                           | 1786408                 | 2550214                                           | 
| Jun-07 | 356232                             | 408190                                          | 39923                           | 1795555                 | 2559977                                           | 
| Jul-07 | 351704                             | 407474                                          | 39954                           | 1806509                 | 2565687                                           | 
| Aug-07 | 353144                             | 407284                                          | 40046                           | 1821868                 | 2582296                                           | 
| Sep-07 | 353802                             | 408391                                          | 39998                           | 1824960                 | 2587153                                           | 
| Oct-07 | 350510                             | 407217                                          | 39594                           | 1827385                 | 2585112                                           | 
```