# 05to12 Iquery Crypto Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-crypto-data-51603) |
| Metadata | [Link](https://data.illinois.gov/api/views/5cng-jyjz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5cng-jyjz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5cng-jyjz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5cng-jyjz |
| Name | 05to12 Iquery Crypto Data |
| Created | 2013-11-05T20:45:45Z |
| Publication Date | 2013-11-06T15:03:45Z |

## Description

Cryptosporidiosis is a disease caused by ingesting or swallowing the intestinal parasite Cryptosporidium parvum. Watery diarrhea and abdominal cramping are the most common major symptoms, while other symptoms may include nausea, vomiting, fatigue, weight loss and low-grade fever. Symptoms may last as long as 30 days in otherwise healthy individuals, but in persons with weakened immune systems symptoms can persist indefinitely and possibly lead to serious illness and death. The parasite Cryptosporidium parvum is found in the feces of infected animals and people. Inadequate disposal of feces and water run-off from animal habitats may also contaminate drinking water supplies and recreational water sites.

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
series e:5cng-jyjz d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="25-29 Years" t:gender=Male t:stateorcounty=S t:disease=Cryptosporidiosis t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1

series e:5cng-jyjz d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="30-34 Years" t:gender=Male t:stateorcounty=S t:disease=Cryptosporidiosis t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1

series e:5cng-jyjz d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="35-39 Years" t:gender=Male t:stateorcounty=S t:disease=Cryptosporidiosis t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=4
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:5cng-jyjz l:"05to12 Iquery Crypto Data" t:url=https://data.illinois.gov/api/views/5cng-jyjz

property e:5cng-jyjz t:meta.view v:id=5cng-jyjz v:averageRating=0 v:name="05to12 Iquery Crypto Data"

property e:5cng-jyjz t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:5cng-jyjz t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease           | yeartext | year | stateorcounty | il | race                 | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ================= | ======== | ==== | ============= | == | ==================== | ================== | ====== | ============ | =========== | ===== | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 25-29 Years | 1     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 30-34 Years | 1     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 35-39 Years | 4     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 40-44 Years | 3     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 50-54 Years | 1     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 5-9 Years   | 1     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 60-64 Years | 1     | 
| Cryptosporidiosis | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 65 + Years  | 1     | 
| Cryptosporidiosis | Year     | 2006 | S             | IL | AmericanIndianAlaskn | NotHispNotLatino   | Male   | CD5yr        | 50-54 Years | 1     | 
| Cryptosporidiosis | Year     | 2006 | S             | IL | Asian                | NotHispNotLatino   | Female | CD5yr        | 0-4 Years   | 2     | 
```