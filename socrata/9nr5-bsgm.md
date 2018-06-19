# 09to12 Iquery Chkn Pox Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/09to12-iquery-chkn-pox-data-38168) |
| Metadata | [Link](https://data.illinois.gov/api/views/9nr5-bsgm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9nr5-bsgm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9nr5-bsgm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9nr5-bsgm |
| Name | 09to12 Iquery Chkn Pox Data |
| Created | 2013-11-05T20:36:52Z |
| Publication Date | 2013-11-06T15:04:29Z |

## Description

Varicella (Chickenpox), a highly contagious disease caused by the varicella-zoster virus, is one of the most commonly reported childhood diseases. Typical symptoms are fever and a generalized rash. Usually mild and not life-threatening to otherwise healthy children, it may be severe in infants, adults and persons with impaired immune systems. Individual cases of chickenpox became reportable to IDPH in 2009. The varicella-zoster virus also causes shingles in adults. After initial infection which resulted in chickenpox, the varicella-zoster virus can remain dormant for years in nerve tissue. When reactivation of latent varicella infection occurs, it results in localized pain and rash. Cases of shingles are not reportable to IDPH.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | disease       | Disease       | text      | text        |
| Yes      | series tag     | yeartext      | YearText      | text      | text        |
| Yes      | time           | year          | Year          | number    | number      |
| Yes      | series tag     | stateorcounty | StateOrCounty | text      | text        |
| No       |                | il            | IL            | text      | text        |
| Yes      | series tag     | race          | Race          | text      | text        |
| Yes      | series tag     | ethnicity     | Ethnicity     | text      | text        |
| Yes      | series tag     | gender        | Gender        | text      | text        |
| Yes      | series tag     | agegrouptext  | AgeGroupText  | text      | text        |
| Yes      | series tag     | agegroup      | AgeGroup      | text      | text        |
| Yes      | numeric metric | count         | Count         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = il
```

## Data Commands

```ls
series e:9nr5-bsgm d:2009-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="10-14 Years" t:gender=Male t:stateorcounty=S t:disease="Varicella (Chicken Pox)" t:ethnicity="Hispanic or Latino" t:race=Other t:agegrouptext=CD5yr m:count=3

series e:9nr5-bsgm d:2009-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="15-19 Years" t:gender=Male t:stateorcounty=S t:disease="Varicella (Chicken Pox)" t:ethnicity="Hispanic or Latino" t:race=Other t:agegrouptext=CD5yr m:count=5

series e:9nr5-bsgm d:2009-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="25-29 Years" t:gender=Male t:stateorcounty=S t:disease="Varicella (Chicken Pox)" t:ethnicity="Hispanic or Latino" t:race=Other t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:9nr5-bsgm l:"09to12 Iquery Chkn Pox Data" t:url=https://data.illinois.gov/api/views/9nr5-bsgm

property e:9nr5-bsgm t:meta.view v:id=9nr5-bsgm v:averageRating=0 v:name="09to12 Iquery Chkn Pox Data"

property e:9nr5-bsgm t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:9nr5-bsgm t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease                 | yeartext | year | stateorcounty | il | race  | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ======================= | ======== | ==== | ============= | == | ===== | ================== | ====== | ============ | =========== | ===== | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 10-14 Years | 3     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 15-19 Years | 5     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 25-29 Years | 1     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 5-9 Years   | 5     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | NotHispNotLatino   | Female | CD5yr        | 30-34 Years | 1     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | NotHispNotLatino   | Female | CD5yr        | 5-9 Years   | 4     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 10-14 Years | 1     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 15-19 Years | 1     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 40-44 Years | 1     | 
| Varicella (Chicken Pox) | Year     | 2009 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 5-9 Years   | 2     | 
```