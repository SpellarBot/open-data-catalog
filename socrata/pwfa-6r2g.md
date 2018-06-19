# 05to12 Iquery Hep Bchronic Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/05to12-iquery-hep-bchronic-data-96e4a) |
| Metadata | [Link](https://data.illinois.gov/api/views/pwfa-6r2g) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pwfa-6r2g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pwfa-6r2g/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pwfa-6r2g |
| Name | 05to12 Iquery Hep Bchronic Data |
| Created | 2013-11-05T21:37:51Z |
| Publication Date | 2013-11-06T14:59:51Z |

## Description

Hepatitis B is caused by infection with the Hepatitis B virus (HBV). The incubation period from the time of exposure to onset of symptoms is 6 weeks to 6 months. HBV is found in highest concentrations in blood and in lower concentrations in other body fluids (e.g., semen, vaginal secretions, and wound exudates). HBV infection can be self-limited or chronic. Persons with chronic hepatitis B virus (HBV) infection may be asymptomatic. They may have no evidence of liver disease or may have a spectrum of disease ranging from chronic hepatitis to cirrhosis or liver cancer. Laboratory confirmation is used to confirm that a person is chronically infected and therefore, infectious.

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
series e:pwfa-6r2g d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="50-54 Years" t:gender=Male t:stateorcounty=S t:disease="Hep B chronic" t:ethnicity="Hispanic or Latino" t:race=Other t:agegrouptext=CD5yr m:count=5

series e:pwfa-6r2g d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="55-59 Years" t:gender=Male t:stateorcounty=S t:disease="Hep B chronic" t:ethnicity="Hispanic or Latino" t:race=Other t:agegrouptext=CD5yr m:count=3

series e:pwfa-6r2g d:2005-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="65 + Years" t:gender=Male t:stateorcounty=S t:disease="Hep B chronic" t:ethnicity="Hispanic or Latino" t:race=Other t:agegrouptext=CD5yr m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:pwfa-6r2g l:"05to12 Iquery Hep Bchronic Data" t:url=https://data.illinois.gov/api/views/pwfa-6r2g

property e:pwfa-6r2g t:meta.view v:id=pwfa-6r2g v:averageRating=0 v:name="05to12 Iquery Hep Bchronic Data"

property e:pwfa-6r2g t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:pwfa-6r2g t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease       | yeartext | year | stateorcounty | il | race  | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ============= | ======== | ==== | ============= | == | ===== | ================== | ====== | ============ | =========== | ===== | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 50-54 Years | 5     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 55-59 Years | 3     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | Hispanic or Latino | Male   | CD5yr        | 65 + Years  | 1     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 20-24 Years | 1     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 25-29 Years | 1     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 40-44 Years | 2     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | NotHispNotLatino   | Male   | CD5yr        | 65 + Years  | 1     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | UnkwnNotClassified | Female | CD5yr        | 30-34 Years | 2     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | UnkwnNotClassified | Female | CD5yr        | 35-39 Years | 1     | 
| Hep B chronic | Year     | 2005 | S             | IL | Other | UnkwnNotClassified | Female | CD5yr        | 50-54 Years | 1     | 
```