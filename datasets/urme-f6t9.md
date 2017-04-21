# IDPH Infant Mortality, by County, 2006-2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-infant-mortality-by-county-2006-2008-d1362) |
| Metadata | [Link](https://data.illinois.gov/api/views/urme-f6t9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/urme-f6t9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/urme-f6t9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | urme-f6t9 |
| Name | IDPH Infant Mortality, by County, 2006-2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | infant, mortality |
| Created | 2012-01-17T22:09:49Z |
| Publication Date | 2012-01-23T21:45:10Z |

## Description

Rates are per 1,000 live births ** Rate does not meet standards of reliability or precision. -0- Rate zero corresponding to "--" in frequency counts

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                 | Data Type | Render Type |
| ======== | ============== | =============== | ==================== | ========= | =========== |
| Yes      | series tag     | county          | County               | text      | text        |
| Yes      | numeric metric | births_1        | 2006 - Births        | number    | number      |
| Yes      | series tag     | infant_deaths_1 | 2006 - Infant Deaths | text      | text        |
| Yes      | series tag     | im_rate_1       | 2006 - IM Rate       | text      | text        |
| Yes      | numeric metric | births_2        | 2007 - Births        | number    | number      |
| Yes      | series tag     | infant_deaths_2 | 2007 - Infant Deaths | text      | text        |
| Yes      | series tag     | im_rate_2       | 2007 - IM Rate       | text      | text        |
| Yes      | numeric metric | births_3        | 2008 - Births        | number    | number      |
| Yes      | series tag     | infant_deaths_3 | 2008 - Infant Deaths | text      | text        |
| Yes      | series tag     | im_rate_3       | 2008 - IM Rate       | text      | text        |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:urme-f6t9 d:2006-01-01T00:00:00.000Z t:infant_deaths_3=6 t:infant_deaths_2=4 t:infant_deaths_1=5 t:county=ADAMS t:im_rate_1=** t:im_rate_2=** t:im_rate_3=** m:births_1=805 m:births_2=890 m:births_3=817

series e:urme-f6t9 d:2006-01-01T00:00:00.000Z t:infant_deaths_3=1 t:infant_deaths_2=1 t:infant_deaths_1=-- t:county=ALEXANDER t:im_rate_1=-0- t:im_rate_2=** t:im_rate_3=** m:births_1=112 m:births_2=136 m:births_3=120

series e:urme-f6t9 d:2006-01-01T00:00:00.000Z t:infant_deaths_3=1 t:infant_deaths_2=-- t:infant_deaths_1=1 t:county=BOND t:im_rate_1=** t:im_rate_2=-0- t:im_rate_3=** m:births_1=215 m:births_2=185 m:births_3=173
```

## Meta Commands

```ls
metric m:births_1 p:integer l:"2006 - Births" t:dataTypeName=number

metric m:births_2 p:integer l:"2007 - Births" t:dataTypeName=number

metric m:births_3 p:integer l:"2008 - Births" t:dataTypeName=number

entity e:urme-f6t9 l:"IDPH Infant Mortality, by County, 2006-2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/urme-f6t9

property e:urme-f6t9 t:meta.view v:id=urme-f6t9 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Infant Mortality, by County, 2006-2008" v:attribution="Illinois Center for Health Statistics"

property e:urme-f6t9 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:urme-f6t9 t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | births_1 | infant_deaths_1 | im_rate_1 | births_2 | infant_deaths_2 | im_rate_2 | births_3 | infant_deaths_3 | im_rate_3 | 
| ========= | ======== | =============== | ========= | ======== | =============== | ========= | ======== | =============== | ========= | 
| ADAMS     | 805      | 5               | **        | 890      | 4               | **        | 817      | 6               | **        | 
| ALEXANDER | 112      | --              | -0-       | 136      | 1               | **        | 120      | 1               | **        | 
| BOND      | 215      | 1               | **        | 185      | --              | -0-       | 173      | 1               | **        | 
| BOONE     | 737      | 3               | **        | 736      | 4               | **        | 676      | 5               | **        | 
| BROWN     | 57       | --              | -0-       | 60       | --              | -0-       | 64       | --              | -0-       | 
| BUREAU    | 392      | 2               | **        | 413      | 1               | **        | 409      | --              | -0-       | 
| CALHOUN   | 55       | --              | -0-       | 49       | --              | -0-       | 59       | --              | -0-       | 
| CARROLL   | 140      | 1               | **        | 163      | 1               | **        | 142      | 2               | **        | 
| CASS      | 177      | 2               | **        | 195      | --              | -0-       | 200      | 1               | **        | 
| CHAMPAIGN | 2455     | 24              | 9.8       | 2508     | 17              | 6.8       | 2482     | 15              | 6.0       | 
```