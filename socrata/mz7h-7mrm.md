# Iquery Typh Fever Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iquery-typh-fever-data-568b7) |
| Metadata | [Link](https://data.illinois.gov/api/views/mz7h-7mrm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mz7h-7mrm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mz7h-7mrm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mz7h-7mrm |
| Name | Iquery Typh Fever Data |
| Created | 2013-11-05T21:47:23Z |
| Publication Date | 2013-11-06T14:59:11Z |

## Description

Typhoid fever is an enteric fever caused by the bacteria Salmonella enterica serotype Typhi (S. Typhi). While this bacterium is a member of the Salmonella species, this serotype produces an illness that is more severe than the gastrointestinal symptoms caused by the other serotypes of Salmonella. Illnesses caused by these other serotypes, known collectively as non-typhoidal Salmonella, are reported as Salmonellosis. In severe cases of Typhoid fever, delirium may occur during the course of disease. In fact, the term typhoid is derived from the Greek word for hazy, which described the mental state of cases during this phase. Other common symptoms of typhoid fever may include one or more of weakness, stomach aches, head-ache and loss of appetite. When not treated properly, typhoid fever can cause severe illness and even death.

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
series e:mz7h-7mrm d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="0-4 Years" t:gender=Female t:stateorcounty=S t:disease="Typhoid Fever" t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:mz7h-7mrm d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="15-19 Years" t:gender=Female t:stateorcounty=S t:disease="Typhoid Fever" t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:mz7h-7mrm d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="20-24 Years" t:gender=Female t:stateorcounty=S t:disease="Typhoid Fever" t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:mz7h-7mrm l:"Iquery Typh Fever Data" t:url=https://data.illinois.gov/api/views/mz7h-7mrm

property e:mz7h-7mrm t:meta.view v:id=mz7h-7mrm v:averageRating=0 v:name="Iquery Typh Fever Data"

property e:mz7h-7mrm t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:mz7h-7mrm t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease       | yeartext | year | stateorcounty | il | race  | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ============= | ======== | ==== | ============= | == | ===== | ================== | ====== | ============ | =========== | ===== | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Female | CD5yr        | 0-4 Years   | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Female | CD5yr        | 15-19 Years | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Female | CD5yr        | 20-24 Years | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Female | CD5yr        | 25-29 Years | 2     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Male   | CD5yr        | 10-14 Years | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Male   | CD5yr        | 20-24 Years | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Male   | CD5yr        | 25-29 Years | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Male   | CD5yr        | 40-44 Years | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | NotHispNotLatino   | Male   | CD5yr        | Unknown     | 1     | 
| Typhoid Fever | Year     | 2005 | S             | IL | Asian | UnkwnNotClassified | Male   | CD5yr        | 5-9 Years   | 1     | 
```