# 05to12 Iquery Lyme Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-lyme-data-abb1f) |
| Metadata | [Link](https://data.illinois.gov/api/views/wcrd-n5pw) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wcrd-n5pw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wcrd-n5pw/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wcrd-n5pw |
| Name | 05to12 Iquery Lyme Data |
| Created | 2013-11-05T21:26:32Z |
| Publication Date | 2013-11-06T15:00:56Z |
| Rows Updated | 2013-11-05T21:26:40Z |

## Description

Lyme disease is caused by the bacterium Borrelia burgdorferi and is transmitted to humans through the bite of infected blacklegged ticks. Typical symptoms include fever, headache, fatigue, and a characteristic skin rash called erythema migrans. If left untreated, infection can spread to joints, the heart, and the nervous system. Lyme disease is diagnosed based on symptoms, physical findings (e.g., rash), and the possibility of exposure to infected ticks; laboratory testing is helpful if used correctly and performed with validated methods. Most cases of Lyme disease can be treated successfully with a few weeks of antibiotics.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | disease       | Disease       | text      | text        |
| Yes      | series tag     | yeartext      | YearText      | text      | text        |
| Yes      | time           | year          | Year          | number    | number      |
| Yes      | numeric metric | stateorcounty | StateOrCounty | number    | text        |
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
series e:wcrd-n5pw d:2011-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="50-54 Years" t:gender=Male t:stateorcounty=S t:disease="Lyme Disease" t:ethnicity=UnkwnNotClassified t:race=Unknown t:agegrouptext=CD5yr m:count=1

series e:wcrd-n5pw d:2011-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="55-59 Years" t:gender=Male t:stateorcounty=S t:disease="Lyme Disease" t:ethnicity=UnkwnNotClassified t:race=Unknown t:agegrouptext=CD5yr m:count=5

series e:wcrd-n5pw d:2011-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="5-9 Years" t:gender=Male t:stateorcounty=S t:disease="Lyme Disease" t:ethnicity=UnkwnNotClassified t:race=Unknown t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:wcrd-n5pw l:"05to12 Iquery Lyme Data" t:url=https://data.illinois.gov/api/views/wcrd-n5pw

property e:wcrd-n5pw t:meta.view v:id=wcrd-n5pw v:averageRating=0 v:name="05to12 Iquery Lyme Data"

property e:wcrd-n5pw t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht

property e:wcrd-n5pw t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```