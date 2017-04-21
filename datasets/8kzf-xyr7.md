# 10to12 Iquery Flu Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/10to12-iquery-flu-data-0fc7d) |
| Metadata | [Link](https://data.illinois.gov/api/views/8kzf-xyr7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8kzf-xyr7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8kzf-xyr7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8kzf-xyr7 |
| Name | 10to12 Iquery Flu Data |
| Created | 2013-11-05T20:40:56Z |
| Publication Date | 2013-11-06T15:04:14Z |

## Description

The reported number of illnesses caused by strains of the Influenza virus that required the case to be in the Intensive Care Unit (ICU) during a hospital stay. Influenza, commonly called "the flu," is an infection of the respiratory tract caused by the influenza virus. Compared with most viral respiratory infections, such as the common cold, influenza infection often causes a more severe illness. Typical influenza illness includes fever (usually 100 degrees F to 103 degrees F in adults and often even higher in children) and respiratory symptoms, such as cough, sore throat, runny or stuffy nose, as well as headache, muscle aches and extreme fatigue. Although nausea, vomiting and diarrhea can sometimes accompany influenza infection, especially in children, these symptoms are rarely the primary symptoms. The term "stomach flu" is a misnomer that is sometimes used to describe gastrointestinal illnesses caused by organisms other than influenza viruses. During most flu seasons, which typically run from November to April, between 10 percent and 20 percent of the population is infected with influenza viruses. Most people who get the flu recover completely in 1 to 2 weeks, but some people develop serious and potentially life-threatening medical complications, such as pneumonia. Flu-related complications can occur at any age, but the elderly and people with chronic health problems are much more likely to develop serious complications after influenza infection than are young, healthier people. Since 2010, IDPH has collected information about influenza cases that required Intensive Care Unit (ICU) hospitalization as a way to measure the severity of disease.

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
series e:8kzf-xyr7 d:2010-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="20-24 Years" t:gender=Female t:stateorcounty=S t:disease=fluwICU t:ethnicity=NotHispNotLatino t:race=Asian t:agegrouptext=CD5yr m:count=1

series e:8kzf-xyr7 d:2010-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="55-59 Years" t:gender=Female t:stateorcounty=S t:disease=fluwICU t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=1

series e:8kzf-xyr7 d:2010-01-01T00:00:00.000Z t:yeartext=Year t:agegroup="60-64 Years" t:gender=Female t:stateorcounty=S t:disease=fluwICU t:ethnicity=NotHispNotLatino t:race=BlackAfricanAmer t:agegrouptext=CD5yr m:count=2
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:8kzf-xyr7 l:"10to12 Iquery Flu Data" t:url=https://data.illinois.gov/api/views/8kzf-xyr7

property e:8kzf-xyr7 t:meta.view v:id=8kzf-xyr7 v:averageRating=0 v:name="10to12 Iquery Flu Data"

property e:8kzf-xyr7 t:meta.view.owner v:id=r2ci-32dw v:screenName=rlucht v:displayName=rlucht

property e:8kzf-xyr7 t:meta.view.tableauthor v:id=r2ci-32dw v:screenName=rlucht v:roleName=publisher v:displayName=rlucht
```

## Top Records

```ls
| disease | yeartext | year | stateorcounty | il | race             | ethnicity          | gender | agegrouptext | agegroup    | count | 
| ======= | ======== | ==== | ============= | == | ================ | ================== | ====== | ============ | =========== | ===== | 
| fluwICU | Year     | 2010 | S             | IL | Asian            | NotHispNotLatino   | Female | CD5yr        | 20-24 Years | 1     | 
| fluwICU | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 55-59 Years | 1     | 
| fluwICU | Year     | 2010 | S             | IL | BlackAfricanAmer | NotHispNotLatino   | Female | CD5yr        | 60-64 Years | 2     | 
| fluwICU | Year     | 2010 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Female | CD5yr        | 15-19 Years | 1     | 
| fluwICU | Year     | 2010 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 30-34 Years | 1     | 
| fluwICU | Year     | 2010 | S             | IL | BlackAfricanAmer | UnkwnNotClassified | Male   | CD5yr        | 65 + Years  | 1     | 
| fluwICU | Year     | 2010 | S             | IL | Other            | Hispanic or Latino | Female | CD5yr        | 60-64 Years | 1     | 
| fluwICU | Year     | 2010 | S             | IL | Unknown          | Hispanic or Latino | Female | CD5yr        | 50-54 Years | 1     | 
| fluwICU | Year     | 2010 | S             | IL | Unknown          | Hispanic or Latino | Male   | CD5yr        | 0-4 Years   | 1     | 
| fluwICU | Year     | 2010 | S             | IL | Unknown          | Hispanic or Latino | Male   | CD5yr        | 10-14 Years | 1     | 
```