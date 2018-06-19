# 05to12 Iquery Salm Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-salm-data-2485e) |
| Metadata | [Link](https://data.illinois.gov/api/views/y9yg-u5x4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/y9yg-u5x4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/y9yg-u5x4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | y9yg-u5x4 |
| Name | 05to12 Iquery Salm Data |
| Created | 2013-11-05T21:07:56Z |
| Publication Date | 2013-11-06T15:02:36Z |

## Description

Salmonellosis: A case of salmonellosis is caused by one of the numerous serotypes of Salmonella bacteria, and is most often manifested by diarrhea, abdominal pain, nausea, and sometimes vomiting. However, asymptomatic cases may occur. A case of salmonellosis may be considered confirmed or probable. A confirmed case has been proven by laboratory testing, while a probable case is symptomatic and can be epidemiologically linked to a confirmed case. Both of these types of cases are counted in the reported case counts.

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
series e:y9yg-u5x4 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="5-9 Years" t:gender=Female t:stateorcounty=S t:disease=Salmonellosis t:ethnicity=UnkwnNotClassified t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:y9yg-u5x4 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="60-64 Years" t:gender=Female t:stateorcounty=S t:disease=Salmonellosis t:ethnicity=UnkwnNotClassified t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:y9yg-u5x4 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="65 + Years" t:gender=Female t:stateorcounty=S t:disease=Salmonellosis t:ethnicity=UnkwnNotClassified t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:y9yg-u5x4 l:"05to12 Iquery Salm Data" t:url=https://data.illinois.gov/api/views/y9yg-u5x4

property e:y9yg-u5x4 t:meta.view v:id=y9yg-u5x4 v:averageRating=0 v:name="05to12 Iquery Salm Data"

property e:y9yg-u5x4 t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:y9yg-u5x4 t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease       | yeartext | year | stateorcounty | il | race             | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ============= | ======== | ==== | ============= | == | ================ | ================== | ====== | ============ | =========== | ===== | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 5-9 Years   | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 60-64 Years | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 65 + Years  | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 0-4 Years   | 5     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 10-14 Years | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 25-29 Years | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 35-39 Years | 3     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 45-49 Years | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | Unknown     | 1     | 
| Salmonellosis | Year     | 2005 | S             | IL | Multiple Races   | Hispanic or Latino | Female | CD5yr        | 15-19 Years | 1     | 
```