# DBEDT Hawaii Energy Star Buildings 2003-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-energy-star-buildings-2003-2011-806e1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vd5c-qe52) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vd5c-qe52/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vd5c-qe52/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vd5c-qe52 |
| Name | DBEDT Hawaii Energy Star Buildings 2003-2011 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | building, energy |
| Created | 2012-08-28T19:47:45Z |
| Publication Date | 2012-08-29T01:29:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | x_values   | X Values | text      | text        |
| Yes      | numeric metric | private    | Private  | number    | text        |
| Yes      | numeric metric | public     | Public   | number    | text        |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vd5c-qe52 d:2003-01-01T00:00:00.000Z t:x_values="Bank/Financial Institution" m:private=3

series e:vd5c-qe52 d:2003-01-01T00:00:00.000Z t:x_values=Courthouse m:public=1

series e:vd5c-qe52 d:2003-01-01T00:00:00.000Z t:x_values=Hotel m:private=9
```

## Meta Commands

```ls
metric m:private p:integer l:Private t:dataTypeName=number

metric m:public p:integer l:Public t:dataTypeName=number

entity e:vd5c-qe52 l:"DBEDT Hawaii Energy Star Buildings 2003-2011" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/vd5c-qe52

property e:vd5c-qe52 t:meta.view v:id=vd5c-qe52 v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Energy Star Buildings 2003-2011" v:attribution="Department of Economic Development and Tourism"

property e:vd5c-qe52 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:vd5c-qe52 t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:vd5c-qe52 t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values                   | private | public | 
| ========================== | ======= | ====== | 
| Bank/Financial Institution | 3       |        | 
| Courthouse                 |         | 1      | 
| Hotel                      | 9       |        | 
| K-12 School                |         | 1      | 
| Medical Office             |         | 1      | 
| Office                     | 17      | 19     | 
| Retail                     | 1       |        | 
```