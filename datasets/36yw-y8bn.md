# 05to12 Iquery NMen Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-nmen-data-2d137) |
| Metadata | [Link](https://data.illinois.gov/api/views/36yw-y8bn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/36yw-y8bn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/36yw-y8bn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 36yw-y8bn |
| Name | 05to12 Iquery NMen Data |
| Created | 2013-11-05T21:03:47Z |
| Publication Date | 2013-11-06T15:02:46Z |

## Description

Infection caused by the Neisseria Meningitidis bacteria results in acute illness that may include symptoms such as sudden onset of fever, headache, nausea, stiff neck, photophobia, and, in most cases, a rash. Invasive disease may manifest itself as one or more syndromes including bacteremia, sepsis, and meningitis. Meningitis is the most common form, while sepsis, also known as Meningococcemia, is the most severe form of illness. While advances in medicine have improved survivability, some cases may still result in long-term aftereffects or death.

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
series e:36yw-y8bn d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="45-49 Years" t:gender=Female t:stateorcounty=S t:disease="N Men Inv Disease" t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:36yw-y8bn d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="15-19 Years" t:gender=Male t:stateorcounty=S t:disease="N Men Inv Disease" t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:36yw-y8bn d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="40-44 Years" t:gender=Male t:stateorcounty=S t:disease="N Men Inv Disease" t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=2
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:36yw-y8bn l:"05to12 Iquery NMen Data" t:url=https://data.illinois.gov/api/views/36yw-y8bn

property e:36yw-y8bn t:meta.view v:id=36yw-y8bn v:averageRating=0 v:name="05to12 Iquery NMen Data"

property e:36yw-y8bn t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:36yw-y8bn t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease           | yeartext | year | stateorcounty | il | race             | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ================= | ======== | ==== | ============= | == | ================ | ================== | ====== | ============ | =========== | ===== | 
| N Men Inv Disease | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 45-49 Years | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 15-19 Years | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 40-44 Years | 2     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 65 + Years  | 2     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | Other            | Hispanic or Latino | Female | CD5yr        | 0-4 Years   | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | Other            | Hispanic or Latino | Female | CD5yr        | 55-59 Years | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | Other            | Hispanic or Latino | Male   | CD5yr        | 30-34 Years | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | Other            | Hispanic or Latino | Male   | CD5yr        | 35-39 Years | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | Unknown          | UnkwnNotClassified | Male   | CD5yr        | 25-29 Years | 1     | 
| N Men Inv Disease | Year     | 2005 | S             | IL | Unknown          | UnkwnNotClassified | Male   | CD5yr        | 45-49 Years | 1     | 
```