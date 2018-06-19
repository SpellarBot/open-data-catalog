# 05to12 Iquery Leg Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-leg-data-4a7d1) |
| Metadata | [Link](https://data.illinois.gov/api/views/iyx8-kpar) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/iyx8-kpar/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/iyx8-kpar/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | iyx8-kpar |
| Name | 05to12 Iquery Leg Data |
| Created | 2013-11-05T20:57:17Z |
| Publication Date | 2013-11-06T15:03:06Z |

## Description

Legionellosis is a respiratory disease caused by the Legionella pneumophilia bacteria, and may manifest itself in two different ways. Pontiac fever, the milder condition, is a self-limited febrile illness that may be accompanied by anorexia, malaise, myalgia, and headache. In addition to these symptoms, Legionnaires? disease, the more serious condition, is a common cause of pneumonia which may be severe and lead to respiratory failure and death. Pontiac fever and Legionnaires? disease cases are counted together in this file.  Legionella pneumophilia bacteria are widely distributed in our environment. They have been found in natural bodies of water, but also in plumbing systems such as hot water tanks, water in cooling towers, fountains, and whirlpool spas. Most people contract the disease by inhaling mist from a water source contaminated with the bacteria.

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
series e:iyx8-kpar d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="50-54 Years" t:gender=Male t:stateorcounty=S t:disease=Legionellosis t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:iyx8-kpar d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="35-39 Years" t:gender=Female t:stateorcounty=S t:disease=Legionellosis t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:iyx8-kpar d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="40-44 Years" t:gender=Female t:stateorcounty=S t:disease=Legionellosis t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=2
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:iyx8-kpar l:"05to12 Iquery Leg Data" t:url=https://data.illinois.gov/api/views/iyx8-kpar

property e:iyx8-kpar t:meta.view v:id=iyx8-kpar v:averageRating=0 v:name="05to12 Iquery Leg Data"

property e:iyx8-kpar t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:iyx8-kpar t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease       | yeartext | year | stateorcounty | il | race             | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ============= | ======== | ==== | ============= | == | ================ | ================== | ====== | ============ | =========== | ===== | 
| Legionellosis | Year     | 2005 | S             | IL | Asian            | NotHispNotLatino   | Male   | CD5yr        | 50-54 Years | 1     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 35-39 Years | 1     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 40-44 Years | 2     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 60-64 Years | 2     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 40-44 Years | 1     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 45-49 Years | 1     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 50-54 Years | 2     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 45-49 Years | 1     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 35-39 Years | 1     | 
| Legionellosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 65 + Years  | 1     | 
```