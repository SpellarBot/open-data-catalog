# DBEDT Electricity Consumption By State Agencies FY05- FY10

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-electricity-consumption-by-state-agencies-fy05-fy10-7c177) |
| Metadata | [Link](https://data.hawaii.gov/api/views/64np-vcjy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/64np-vcjy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/64np-vcjy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 64np-vcjy |
| Name | DBEDT Electricity Consumption By State Agencies FY05- FY10 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity, energy |
| Created | 2012-08-28T19:36:34Z |
| Publication Date | 2012-08-29T01:26:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | x_values    | X Values   | text      | text        |
| Yes      | numeric metric | fy05        | FY05       | number    | number      |
| Yes      | numeric metric | fy06        | FY06       | number    | number      |
| Yes      | numeric metric | fy07        | FY07       | number    | number      |
| Yes      | numeric metric | fy08        | FY08       | number    | number      |
| Yes      | numeric metric | fy09        | FY09       | number    | number      |
| Yes      | numeric metric | fy10        | FY10       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:64np-vcjy d:2012-08-28T12:36:35.000Z t:x_values=UH m:fy10=180442127 m:fy07=195556630 m:fy08=193639569 m:fy05=185299794 m:fy06=200215505 m:fy09=182226984

series e:64np-vcjy d:2012-08-28T12:36:35.000Z t:x_values=DOE m:fy10=133201033 m:fy07=148414237 m:fy08=147987700 m:fy05=143384951 m:fy06=144128064 m:fy09=138938440

series e:64np-vcjy d:2012-08-28T12:36:35.000Z t:x_values="DOT Airports" m:fy10=128111323 m:fy07=131269766 m:fy08=133988212 m:fy05=128101116 m:fy06=129604326 m:fy09=129019506
```

## Meta Commands

```ls
metric m:fy05 p:integer l:FY05 t:dataTypeName=number

metric m:fy06 p:integer l:FY06 t:dataTypeName=number

metric m:fy07 p:integer l:FY07 t:dataTypeName=number

metric m:fy08 p:integer l:FY08 t:dataTypeName=number

metric m:fy09 p:integer l:FY09 t:dataTypeName=number

metric m:fy10 p:integer l:FY10 t:dataTypeName=number

entity e:64np-vcjy l:"DBEDT Electricity Consumption By State Agencies FY05- FY10" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/64np-vcjy

property e:64np-vcjy t:meta.view v:id=64np-vcjy v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Electricity Consumption By State Agencies FY05- FY10" v:attribution="Department of Economic Development and Tourism"

property e:64np-vcjy t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:64np-vcjy t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:64np-vcjy t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| :updated_at | x_values     | fy05      | fy06      | fy07      | fy08      | fy09      | fy10      | 
| =========== | ============ | ========= | ========= | ========= | ========= | ========= | ========= | 
| 1346157395  | UH           | 185299794 | 200215505 | 195556630 | 193639569 | 182226984 | 180442127 | 
| 1346157395  | DOE          | 143384951 | 144128064 | 148414237 | 147987700 | 138938440 | 133201033 | 
| 1346157395  | DOT Airports | 128101116 | 129604326 | 131269766 | 133988212 | 129019506 | 128111323 | 
| 1346157395  | DAGS         | 49230992  | 49779316  | 51797308  | 52245047  | 45709217  | 42576283  | 
| 1346157395  | DOT Highways | 28804170  | 28203362  | 28303605  | 27941938  | 26439690  | 25754283  | 
| 1346157395  | DOH          | 25726039  | 25496454  | 25404262  | 25887669  | 26223535  | 24971054  | 
| 1346157395  | HPHA         | 18456206  | 18567636  | 19235873  | 18884841  | 18481773  | 18553412  | 
| 1346157395  | HHSC         | 20127174  | 18553340  | 18804930  | 18146647  | 17914301  | 18172891  | 
| 1346157395  | PSD          | 21966423  | 21584032  | 20839695  | 20431439  | 19074360  | 17861470  | 
| 1346157395  | DOT Harbors  | 10315113  | 10702082  | 11374639  | 11325990  | 9552067   | 8123410   | 
```