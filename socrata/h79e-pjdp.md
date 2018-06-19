# 05to12 Iquery Histo Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-histo-data-0ff72) |
| Metadata | [Link](https://data.illinois.gov/api/views/h79e-pjdp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/h79e-pjdp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/h79e-pjdp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | h79e-pjdp |
| Name | 05to12 Iquery Histo Data |
| Created | 2013-11-05T20:53:14Z |
| Publication Date | 2013-11-06T15:03:15Z |

## Description

Histoplasma capsulatum is a dimorphic fungus that grows as a mold in soil, and as a yeast in humans and animals. The fungus is found in nature in soil with undisturbed droppings from birds or bats. The growth of the fungus in the soil produces very small particles that can be inhaled with dust when the soil is disturbed. A case of histoplasmosis may manifest itself as a respiratory or pulmonary illness that may be severe.

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
series e:h79e-pjdp d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="30-34 Years" t:gender=Female t:stateorcounty=S t:disease=Histoplasmosis t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:h79e-pjdp d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="35-39 Years" t:gender=Female t:stateorcounty=S t:disease=Histoplasmosis t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:h79e-pjdp d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="40-44 Years" t:gender=Female t:stateorcounty=S t:disease=Histoplasmosis t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:h79e-pjdp l:"05to12 Iquery Histo Data" t:url=https://data.illinois.gov/api/views/h79e-pjdp

property e:h79e-pjdp t:meta.view v:id=h79e-pjdp v:averageRating=0 v:name="05to12 Iquery Histo Data"

property e:h79e-pjdp t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:h79e-pjdp t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease        | yeartext | year | stateorcounty | il | race             | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ============== | ======== | ==== | ============= | == | ================ | ================== | ====== | ============ | =========== | ===== | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 30-34 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 35-39 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 40-44 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 25-29 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 35-39 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 40-44 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 45-49 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 65 + Years  | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 10-14 Years | 1     | 
| Histoplasmosis | Year     | 2005 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 15-19 Years | 1     | 
```