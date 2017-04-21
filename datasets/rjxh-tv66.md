# 05to12 Iquery Hep AData

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-hep-adata-669b0) |
| Metadata | [Link](https://data.illinois.gov/api/views/rjxh-tv66) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rjxh-tv66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rjxh-tv66/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rjxh-tv66 |
| Name | 05to12 Iquery Hep AData |
| Created | 2013-11-05T20:49:12Z |
| Publication Date | 2013-11-06T15:03:30Z |

## Description

Hepatitis A is an acute, severe illness with a distinct onset of symptoms consistent with any acute viral hepatitis. The most distinctive symptom is jaundice, a yellowish pigmentation of the skin, tissues, or body fluids. Other symptoms may include fever, headache, malaise, anorexia, nausea, vomiting, diarrhea, and abdominal pain. These symptoms are the same for all types of viral hepatitis, but Hepatitis A is spread by the fecal-oral route of transmission, so it may be dispersed by infected food handlers. The illness caused by Hepatitis A may last several weeks to several months, but complete recovery is almost always achieved.

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
series e:rjxh-tv66 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="10-14 Years" t:gender=Female t:stateorcounty=S t:disease=HepA t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1

series e:rjxh-tv66 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="25-29 Years" t:gender=Female t:stateorcounty=S t:disease=HepA t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1

series e:rjxh-tv66 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="35-39 Years" t:gender=Female t:stateorcounty=S t:disease=HepA t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:rjxh-tv66 l:"05to12 Iquery Hep AData" t:url=https://data.illinois.gov/api/views/rjxh-tv66

property e:rjxh-tv66 t:meta.view v:id=rjxh-tv66 v:averageRating=0 v:name="05to12 Iquery Hep AData"

property e:rjxh-tv66 t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:rjxh-tv66 t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease | yeartext | year | stateorcounty | il | race  | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ======= | ======== | ==== | ============= | == | ===== | ================== | ====== | ============ | =========== | ===== | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Female | CD5yr        | 10-14 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Female | CD5yr        | 25-29 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Female | CD5yr        | 35-39 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Female | CD5yr        | 60-64 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Male   | CD5yr        | 20-24 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Male   | CD5yr        | 35-39 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Male   | CD5yr        | 50-54 Years | 2     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Male   | CD5yr        | 55-59 Years | 1     | 
| HepA    | Year     | 2005 | S             | IL | White | UnkwnNotClassified | Male   | CD5yr        | 5-9 Years   | 1     | 
| HepA    | Year     | 2006 | S             | IL | Asian | NotHispNotLatino   | Female | CD5yr        | 0-4 Years   | 1     | 
```