# 05to12 Iquery Mumps Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-mumps-data-bfa87) |
| Metadata | [Link](https://data.illinois.gov/api/views/jshf-mnjc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jshf-mnjc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jshf-mnjc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jshf-mnjc |
| Name | 05to12 Iquery Mumps Data |
| Created | 2013-11-05T20:30:14Z |
| Publication Date | 2013-11-06T15:04:41Z |

## Description

Mumps is caused by infection by the mumps virus. Common symptoms of mumps include fever, headache, muscle aches, tiredness, loss of appetite, and later in the course of infection the characteristic swelling of salivary glands. Mumps is spread by droplets of saliva or mucus from an infected person, usually when that person coughs, sneezes, or talks.

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
series e:jshf-mnjc d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="10-14 Years" t:gender=Female t:stateorcounty=S t:disease=Mumps t:ethnicity=NotHispNotLatino t:race=Other t:agegrouptext=CD5yr m:count=1

series e:jshf-mnjc d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="0-4 Years" t:gender=Male t:stateorcounty=S t:disease=Mumps t:ethnicity=UnkwnNotClassified t:race=Other t:agegrouptext=CD5yr m:count=1

series e:jshf-mnjc d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="0-4 Years" t:gender=Female t:stateorcounty=S t:disease=Mumps t:ethnicity="Hispanic or Latino" t:race=Unknown t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:jshf-mnjc l:"05to12 Iquery Mumps Data" t:url=https://data.illinois.gov/api/views/jshf-mnjc

property e:jshf-mnjc t:meta.view v:id=jshf-mnjc v:averageRating=0 v:name="05to12 Iquery Mumps Data"

property e:jshf-mnjc t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:jshf-mnjc t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease | yeartext | year | stateorcounty | il | race    | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ======= | ======== | ==== | ============= | == | ======= | ================== | ====== | ============ | =========== | ===== | 
| Mumps   | Year     | 2005 | S             | IL | Other   | NotHispNotLatino   | Female | CD5yr        | 10-14 Years | 1     | 
| Mumps   | Year     | 2005 | S             | IL | Other   | UnkwnNotClassified | Male   | CD5yr        | 0-4 Years   | 1     | 
| Mumps   | Year     | 2005 | S             | IL | Unknown | Hispanic or Latino | Female | CD5yr        | 0-4 Years   | 1     | 
| Mumps   | Year     | 2005 | S             | IL | Unknown | Hispanic or Latino | Male   | CD5yr        | 0-4 Years   | 1     | 
| Mumps   | Year     | 2005 | S             | IL | Unknown | UnkwnNotClassified | Male   | CD5yr        | 15-19 Years | 1     | 
| Mumps   | Year     | 2005 | S             | IL | Unknown | UnkwnNotClassified | Male   | CD5yr        | 5-9 Years   | 1     | 
| Mumps   | Year     | 2005 | S             | IL | White   | Hispanic or Latino | Female | CD5yr        | 30-34 Years | 1     | 
| Mumps   | Year     | 2005 | S             | IL | White   | Hispanic or Latino | Male   | CD5yr        | 10-14 Years | 1     | 
| Mumps   | Year     | 2005 | S             | IL | White   | NotHispNotLatino   | Male   | CD5yr        | 25-29 Years | 1     | 
| Mumps   | Year     | 2005 | S             | IL | White   | NotHispNotLatino   | Male   | CD5yr        | 5-9 Years   | 1     | 
```