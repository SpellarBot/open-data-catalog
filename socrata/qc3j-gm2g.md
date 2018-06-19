# Iquery2012 Typh Fvr

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iquery2012-typh-fvr-8b059) |
| Metadata | [Link](https://data.illinois.gov/api/views/qc3j-gm2g) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qc3j-gm2g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qc3j-gm2g/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qc3j-gm2g |
| Name | Iquery2012 Typh Fvr |
| Created | 2013-11-05T21:49:43Z |
| Publication Date | 2013-11-06T14:58:52Z |

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
series e:qc3j-gm2g d:2012-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="0-4 Years" t:gender=Male t:stateorcounty=S t:disease="Typhoid Fever" t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:qc3j-gm2g d:2012-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="10-14 Years" t:gender=Male t:stateorcounty=S t:disease="Typhoid Fever" t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:qc3j-gm2g d:2012-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="20-24 Years" t:gender=Male t:stateorcounty=S t:disease="Typhoid Fever" t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:qc3j-gm2g l:"Iquery2012 Typh Fvr" t:url=https://data.illinois.gov/api/views/qc3j-gm2g

property e:qc3j-gm2g t:meta.view v:id=qc3j-gm2g v:averageRating=0 v:name="Iquery2012 Typh Fvr"

property e:qc3j-gm2g t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:qc3j-gm2g t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease       | yeartext | year | stateorcounty | il | race             | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ============= | ======== | ==== | ============= | == | ================ | ================== | ====== | ============ | =========== | ===== | 
| Typhoid Fever | Year     | 2012 | S             | IL | Asian            | NotHispNotLatino   | Male   | CD5yr        | 0-4 Years   | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Asian            | NotHispNotLatino   | Male   | CD5yr        | 10-14 Years | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Asian            | NotHispNotLatino   | Male   | CD5yr        | 20-24 Years | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Asian            | NotHispNotLatino   | Male   | CD5yr        | 50-54 Years | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Asian            | UnkwnNotClassified | Female | CD5yr        | 0-4 Years   | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Asian            | UnkwnNotClassified | Male   | CD5yr        | 0-4 Years   | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Male   | CD5yr        | 45-49 Years | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Other            | NotHispNotLatino   | Female | CD5yr        | 0-4 Years   | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Other            | NotHispNotLatino   | Female | CD5yr        | 35-39 Years | 1     | 
| Typhoid Fever | Year     | 2012 | S             | IL | Other            | NotHispNotLatino   | Male   | CD5yr        | 30-34 Years | 1     | 
```