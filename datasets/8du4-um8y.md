# Anne Arundel County Employment Figures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/anne-arundel-county-employment-figures-dcbb2) |
| Metadata | [Link](https://data.maryland.gov/api/views/8du4-um8y) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8du4-um8y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8du4-um8y/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8du4-um8y |
| Name | Anne Arundel County Employment Figures |
| Attribution | DLLR, BLS |
| Category | Business and Economy |
| Tags | anne arundel, employment, unemployment, jobs |
| Created | 2014-07-25T17:31:30Z |
| Publication Date | 2014-07-25T17:40:56Z |

## Description

Employment figures and unemployment rate, 2009 - present. (Non-seasonally adjusted.)

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | month                      | Month                      | text      | text        |
| Yes      | numeric metric | labor_force                | Labor Force                | number    | number      |
| Yes      | numeric metric | employment                 | Employment                 | number    | number      |
| Yes      | numeric metric | unemployment               | Unemployment               | number    | number      |
| Yes      | numeric metric | unemployment_rate          | Unemployment Rate          | number    | number      |
| Yes      | numeric metric | percent_change             | Percent Change             | percent   | percent     |
| Yes      | numeric metric | maryland_unemployment_rate | Maryland Unemployment Rate | number    | number      |
| Yes      | numeric metric | aa_vs_md                   | AA vs MD                   | number    | number      |
| Yes      | numeric metric | national_unemployment_rate | National Unemployment Rate | number    | number      |
| Yes      | numeric metric | aa_vs_us                   | AA vs US                   | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8du4-um8y d:2009-01-01T00:00:00.000Z t:month="01 - January" m:aa_vs_us=-2.6 m:aa_vs_md=-0.8 m:employment=268400 m:unemployment=16752 m:labor_force=285152

series e:8du4-um8y d:2009-01-01T00:00:00.000Z t:month="02 - February" m:aa_vs_us=-2.5 m:aa_vs_md=-0.8 m:employment=266826 m:unemployment=18387 m:percent_change=8.5 m:labor_force=285213

series e:8du4-um8y d:2009-01-01T00:00:00.000Z t:month="03 - March" m:aa_vs_us=-2.6 m:aa_vs_md=-0.7 m:employment=267718 m:unemployment=18270 m:percent_change=0 m:labor_force=285988
```

## Meta Commands

```ls
metric m:labor_force p:integer l:"Labor Force" t:dataTypeName=number

metric m:employment p:integer l:Employment t:dataTypeName=number

metric m:unemployment p:integer l:Unemployment t:dataTypeName=number

metric m:unemployment_rate p:long l:"Unemployment Rate" t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" t:dataTypeName=percent

metric m:maryland_unemployment_rate p:long l:"Maryland Unemployment Rate" t:dataTypeName=number

metric m:aa_vs_md p:float l:"AA vs MD" t:dataTypeName=number

metric m:national_unemployment_rate p:long l:"National Unemployment Rate" t:dataTypeName=number

metric m:aa_vs_us p:float l:"AA vs US" t:dataTypeName=number

entity e:8du4-um8y l:"Anne Arundel County Employment Figures" t:attribution="DLLR, BLS" t:url=https://data.maryland.gov/api/views/8du4-um8y

property e:8du4-um8y t:meta.view v:id=8du4-um8y v:category="Business and Economy" v:attributionLink=http://www.dllr.state.md.us/lmi/laus/annearundel.shtml v:averageRating=0 v:name="Anne Arundel County Employment Figures" v:attribution="DLLR, BLS"

property e:8du4-um8y t:meta.view.license v:name="Public Domain"

property e:8du4-um8y t:meta.view.owner v:id=wdx2-yd94 v:screenName="Scott Shaffer" v:displayName="Scott Shaffer"

property e:8du4-um8y t:meta.view.tableauthor v:id=wdx2-yd94 v:screenName="Scott Shaffer" v:roleName=editor v:displayName="Scott Shaffer"
```

## Top Records

```ls
| year | month          | labor_force | employment | unemployment | unemployment_rate | percent_change | maryland_unemployment_rate | aa_vs_md | national_unemployment_rate | aa_vs_us | 
| ==== | ============== | =========== | ========== | ============ | ================= | ============== | ========================== | ======== | ========================== | ======== | 
| 2009 | 01 - January   | 285152      | 268400     | 16752        |                   |                |                            | -0.8     |                            | -2.6     | 
| 2009 | 02 - February  | 285213      | 266826     | 18387        |                   | 8.5            |                            | -0.8     |                            | -2.5     | 
| 2009 | 03 - March     | 285988      | 267718     | 18270        |                   | 0.0            |                            | -0.7     |                            | -2.6     | 
| 2009 | 04 - April     | 286376      | 268789     | 17587        |                   | -4.7           |                            | -0.7     |                            | -2.5     | 
| 2009 | 05 - May       | 287207      | 268166     | 19041        |                   | 8.2            |                            | -0.7     |                            | -2.5     | 
| 2009 | 06 - June      | 289690      | 269280     | 20410        |                   | 6.1            |                            | -0.7     |                            | -2.7     | 
| 2009 | 07 - July      | 291091      | 270543     | 20548        |                   | 1.4            |                            | -0.5     |                            | -2.6     | 
| 2009 | 08 - August    | 287253      | 267253     | 20000        |                   | -1.4           |                            | -0.5     |                            | -2.6     | 
| 2009 | 09 - September | 286025      | 266394     | 19631        |                   | -1.4           |                            | -0.6     |                            | -2.6     | 
| 2009 | 10 - October   | 287129      | 267099     | 20030        |                   | 1.4            |                            | -0.6     |                            | -2.5     | 
```