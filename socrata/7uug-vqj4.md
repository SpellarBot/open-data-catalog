# Iquery Measles Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iquery-measles-data-eb3b3) |
| Metadata | [Link](https://data.illinois.gov/api/views/7uug-vqj4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7uug-vqj4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7uug-vqj4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7uug-vqj4 |
| Name | Iquery Measles Data |
| Created | 2013-11-05T21:44:11Z |
| Publication Date | 2013-11-06T14:59:33Z |

## Description

Measles is a highly contagious viral infection that is spread by the dissemination of the Measles virus in respiratory droplets by infected individuals. The most notable symptom is a red blotchy rash, but this is usually preceded by fever, runny nose, or cough. Quite common before immunization began, measles is typically not a severe disease, but grave illness and even death may occur. Those most susceptible to contracting measles are infants too young to be vaccinated, other unvaccinated adults and children, and immunocompromised individuals. Measles can be readily spread in enclosed recirculating air environments such as airplanes or classrooms, but any close contact with an infected case may lead to infection.

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
series e:7uug-vqj4 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="5-9 Years" t:gender=Female t:stateorcounty=S t:disease=Measles t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:7uug-vqj4 d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="10-14 Years" t:gender=Male t:stateorcounty=S t:disease=Measles t:ethnicity=UnkwnNotClassified t:race=Unknown t:agegrouptext=CD5yr m:count=1

series e:7uug-vqj4 d:2007-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="50-54 Years" t:gender=Female t:stateorcounty=S t:disease=Measles t:ethnicity=UnkwnNotClassified t:race=White t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:7uug-vqj4 l:"Iquery Measles Data" t:url=https://data.illinois.gov/api/views/7uug-vqj4

property e:7uug-vqj4 t:meta.view v:id=7uug-vqj4 v:averageRating=0 v:name="Iquery Measles Data"

property e:7uug-vqj4 t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:7uug-vqj4 t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease | yeartext | year | stateorcounty | il | race    | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ======= | ======== | ==== | ============= | == | ======= | ================== | ====== | ============ | =========== | ===== | 
| Measles | Year     | 2005 | S             | IL | Asian   | NotHispNotLatino   | Female | CD5yr        | 5-9 Years   | 1     | 
| Measles | Year     | 2005 | S             | IL | Unknown | UnkwnNotClassified | Male   | CD5yr        | 10-14 Years | 1     | 
| Measles | Year     | 2007 | S             | IL | White   | UnkwnNotClassified | Female | CD5yr        | 50-54 Years | 1     | 
| Measles | Year     | 2008 | S             | IL | Unknown | NotHispNotLatino   | Female | CD5yr        | 15-19 Years | 1     | 
| Measles | Year     | 2008 | S             | IL | Unknown | UnkwnNotClassified | Female | CD5yr        | 10-14 Years | 1     | 
| Measles | Year     | 2008 | S             | IL | White   | Hispanic or Latino | Female | CD5yr        | 0-4 Years   | 1     | 
| Measles | Year     | 2008 | S             | IL | White   | Hispanic or Latino | Female | CD5yr        | 10-14 Years | 1     | 
| Measles | Year     | 2008 | S             | IL | White   | Hispanic or Latino | Female | CD5yr        | 15-19 Years | 1     | 
| Measles | Year     | 2008 | S             | IL | White   | Hispanic or Latino | Male   | CD5yr        | 5-9 Years   | 2     | 
| Measles | Year     | 2008 | S             | IL | White   | NotHispNotLatino   | Female | CD5yr        | 0-4 Years   | 1     | 
```