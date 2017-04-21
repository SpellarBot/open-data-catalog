# Correctional Community Program Daily Population Count By Community Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/correctional-community-program-daily-population-count-by-community-program) |
| Metadata | [Link](https://data.ct.gov/api/views/5d7h-at3x) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/5d7h-at3x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/5d7h-at3x/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 5d7h-at3x |
| Name | Correctional Community Program Daily Population Count By Community Program |
| Attribution | Department of Corrections |
| Category | Public Safety |
| Tags | correction, community program, population count, usodcensus |
| Created | 2014-04-24T15:12:20Z |
| Publication Date | 2017-04-03T18:47:06Z |

## Description

CT Department of Correction Community Program Population Count by Date, By Gender

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | date              | Date              | calendar_date | calendar_date |
| Yes      | series tag     | community_program | Community Program | text          | text          |
| Yes      | numeric metric | male_count        | Male Count        | number        | number        |
| Yes      | numeric metric | female_count      | Female Count      | number        | number        |
| Yes      | numeric metric | total_count       | Total Count       | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5d7h-at3x d:1993-12-26T00:00:00.000Z t:community_program="DUI/DRUG HOME CONFINEMENT" m:female_count=0 m:male_count=0 m:total_count=0

series e:5d7h-at3x d:1993-12-26T00:00:00.000Z t:community_program="HALFWAY HOUSE-COMMUNITY RELEASE" m:female_count=56 m:male_count=282 m:total_count=338

series e:5d7h-at3x d:1993-12-26T00:00:00.000Z t:community_program="HALFWAY HOUSE-PAROLE" m:female_count=0 m:male_count=0 m:total_count=0
```

## Meta Commands

```ls
metric m:male_count p:integer l:"Male Count" t:dataTypeName=number

metric m:female_count p:integer l:"Female Count" t:dataTypeName=number

metric m:total_count p:integer l:"Total Count" t:dataTypeName=number

entity e:5d7h-at3x l:"Correctional Community Program Daily Population Count By Community Program" t:attribution="Department of Corrections" t:url=https://data.ct.gov/api/views/5d7h-at3x

property e:5d7h-at3x t:meta.view v:id=5d7h-at3x v:category="Public Safety" v:attributionLink=http://www.ct.gov/doc v:averageRating=0 v:name="Correctional Community Program Daily Population Count By Community Program" v:attribution="Department of Corrections"

property e:5d7h-at3x t:meta.view.license v:name="Public Domain"

property e:5d7h-at3x t:meta.view.owner v:id=qb87-kyg8 v:screenName="Peiti Lee" v:displayName="Peiti Lee"

property e:5d7h-at3x t:meta.view.tableauthor v:id=qb87-kyg8 v:screenName="Peiti Lee" v:displayName="Peiti Lee"
```

## Top Records

```ls
| date                | community_program                      | male_count | female_count | total_count | 
| =================== | ====================================== | ========== | ============ | =========== | 
| 1993-12-26T00:00:00 | DUI/DRUG HOME CONFINEMENT              | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | HALFWAY HOUSE-COMMUNITY RELEASE        | 282        | 56           | 338         | 
| 1993-12-26T00:00:00 | HALFWAY HOUSE-PAROLE                   | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | HALFWAY HOUSE-SPECIAL PAROLE           | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | HALFWAY HOUSE-TRANSFER PAROLE          | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | HALFWAY HOUSE-TRANSITIONAL SUPERVISION | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | NURSING HOME                           | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | PAROLE-PAROLE                          | 574        | 48           | 622         | 
| 1993-12-26T00:00:00 | PAROLE-PAROLE COMPACT AT CONNECTICUT   | 0          | 0            | 0           | 
| 1993-12-26T00:00:00 | PAROLE-SPECIAL PAROLE                  | 0          | 0            | 0           | 
```