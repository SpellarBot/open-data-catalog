# 05to12 Iquery STECData

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-stecdata-b3da9) |
| Metadata | [Link](https://data.illinois.gov/api/views/f55m-q7ae) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/f55m-q7ae/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/f55m-q7ae/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | f55m-q7ae |
| Name | 05to12 Iquery STECData |
| Created | 2013-11-05T21:12:19Z |
| Publication Date | 2013-11-06T15:01:42Z |

## Description

The reported number of illnesses caused by strains of the Escherichia coli bacteria that produce shiga toxin. Shiga toxin-producing E. coli (STEC) strains are a very small subset of the numerous Escherichia coli bacteria strains. These strains produce the powerful Shiga toxin as a byproduct of their infection. The most common strain that does this is E. coli O157:H7, but there are several other closely related strains that also produce Shiga toxin. The major symptom of illness is diarrhea, which may be bloody. Severe cases of STEC may result in hemolytic uremic syndrome (HUS) which, in turn, may lead to acute renal dysfunction necessitating the use of dialysis. While anyone may contract illness, children under age 5 and the elderly seem to be most prone to serious complications.

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
series e:f55m-q7ae d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="25-29 Years" t:gender=Male t:stateorcounty=S t:disease=STEC t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1

series e:f55m-q7ae d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="40-44 Years" t:gender=Male t:stateorcounty=S t:disease=STEC t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1

series e:f55m-q7ae d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="65 + Years" t:gender=Male t:stateorcounty=S t:disease=STEC t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=2
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:f55m-q7ae l:"05to12 Iquery STECData" t:url=https://data.illinois.gov/api/views/f55m-q7ae

property e:f55m-q7ae t:meta.view v:id=f55m-q7ae v:averageRating=0 v:name="05to12 Iquery STECData"

property e:f55m-q7ae t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:f55m-q7ae t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease | yeartext | year | stateorcounty | il | race                 | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ======= | ======== | ==== | ============= | == | ==================== | ================== | ====== | ============ | =========== | ===== | 
| STEC    | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 25-29 Years | 1     | 
| STEC    | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 40-44 Years | 1     | 
| STEC    | Year     | 2005 | S             | IL | White                | UnkwnNotClassified | Male   | CD5yr        | 65 + Years  | 2     | 
| STEC    | Year     | 2006 | S             | IL | AmericanIndianAlaskn | NotHispNotLatino   | Male   | CD5yr        | 55-59 Years | 1     | 
| STEC    | Year     | 2006 | S             | IL | Asian                | NotHispNotLatino   | Female | CD5yr        | 65 + Years  | 1     | 
| STEC    | Year     | 2006 | S             | IL | Asian                | NotHispNotLatino   | Male   | CD5yr        | 5-9 Years   | 1     | 
| STEC    | Year     | 2006 | S             | IL | Asian                | UnkwnNotClassified | Male   | CD5yr        | 0-4 Years   | 1     | 
| STEC    | Year     | 2006 | S             | IL | BlackAfricanAmer     | NotHispNotLatino   | Female | CD5yr        | 0-4 Years   | 1     | 
| STEC    | Year     | 2006 | S             | IL | BlackAfricanAmer     | NotHispNotLatino   | Female | CD5yr        | 40-44 Years | 1     | 
| STEC    | Year     | 2006 | S             | IL | BlackAfricanAmer     | NotHispNotLatino   | Female | CD5yr        | 60-64 Years | 1     | 
```