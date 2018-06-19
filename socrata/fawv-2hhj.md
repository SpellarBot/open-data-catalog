# 10to12 Iquery Hep Cchronic Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/10to12-iquery-hep-cchronic-data-4c064) |
| Metadata | [Link](https://data.illinois.gov/api/views/fawv-2hhj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fawv-2hhj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fawv-2hhj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fawv-2hhj |
| Name | 10to12 Iquery Hep Cchronic Data |
| Created | 2013-11-05T21:34:26Z |
| Publication Date | 2013-11-06T15:00:26Z |

## Description

Hepatitis C virus (HCV) infection is the most common chronic bloodborne infection in the United States; approximately 3.2 million persons are chronically infected.  HCV is most efficiently transmitted through large or repeated percutaneous exposure to infected blood (e.g., through transfusion of blood from unscreened donors or through use of injecting drugs). Although much less frequent, occupational, perinatal, and sexual exposures also can result in transmission of HCV. Because the clinical characteristics are similar for all types of acute viral hepatitis, the specific viral cause of illness cannot be determined solely on the basis of signs, symptoms, history, or current risk factors, but must be verified by specific serologic testing. Persons with chronic hepatitis B virus (HBV) infection may be asymptomatic. They may have no evidence of liver disease or may have a spectrum of disease ranging from chronic hepatitis to cirrhosis or liver cancer.

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
series e:fawv-2hhj d:2010-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="20-24 Years" t:gender=Female t:stateorcounty=S t:disease="Hep C chronic" t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=3

series e:fawv-2hhj d:2010-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="25-29 Years" t:gender=Female t:stateorcounty=S t:disease="Hep C chronic" t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=2

series e:fawv-2hhj d:2010-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="35-39 Years" t:gender=Female t:stateorcounty=S t:disease="Hep C chronic" t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=9
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:fawv-2hhj l:"10to12 Iquery Hep Cchronic Data" t:url=https://data.illinois.gov/api/views/fawv-2hhj

property e:fawv-2hhj t:meta.view v:id=fawv-2hhj v:averageRating=0 v:name="10to12 Iquery Hep Cchronic Data"

property e:fawv-2hhj t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:fawv-2hhj t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease       | yeartext | year | stateorcounty | il | race             | ethnicity        | gender | agegrouptext | agegroup    | count | 
| ============= | ======== | ==== | ============= | == | ================ | ================ | ====== | ============ | =========== | ===== | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 20-24 Years | 3     | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 25-29 Years | 2     | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 35-39 Years | 9     | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 40-44 Years | 25    | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 45-49 Years | 46    | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 50-54 Years | 66    | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 55-59 Years | 73    | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 60-64 Years | 36    | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Female | CD5yr        | 65 + Years  | 58    | 
| Hep C chronic | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino | Male   | CD5yr        | 15-19 Years | 1     | 
```