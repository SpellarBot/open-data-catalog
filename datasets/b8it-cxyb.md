# DBEDT Currently Proposed Renewable Energy Projects In Hawaii

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-currently-proposed-renewable-energy-projects-in-hawaii-49ecf) |
| Metadata | [Link](https://data.hawaii.gov/api/views/b8it-cxyb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/b8it-cxyb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/b8it-cxyb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | b8it-cxyb |
| Name | DBEDT Currently Proposed Renewable Energy Projects In Hawaii |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy |
| Created | 2012-08-28T19:32:55Z |
| Publication Date | 2012-08-29T01:25:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | x_values    | X Values    | text      | text        |
| Yes      | numeric metric | wind        | Wind        | number    | number      |
| Yes      | numeric metric | solar       | Solar       | number    | text        |
| Yes      | numeric metric | otec        | OTEC        | number    | text        |
| Yes      | numeric metric | hydro       | Hydro       | number    | text        |
| Yes      | numeric metric | geothermal  | Geothermal  | number    | text        |
| Yes      | numeric metric | combination | Combination | number    | text        |
| Yes      | numeric metric | bioenergy   | Bioenergy   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b8it-cxyb d:2012-08-28T12:32:56.000Z t:x_values=Hawaii m:wind=2 m:geothermal=1 m:bioenergy=11

series e:b8it-cxyb d:2012-08-28T12:32:56.000Z t:x_values=Kauai m:solar=3 m:hydro=7 m:bioenergy=4

series e:b8it-cxyb d:2012-08-28T12:32:56.000Z t:x_values=Lanai m:wind=1
```

## Meta Commands

```ls
metric m:wind p:integer l:Wind t:dataTypeName=number

metric m:solar p:integer l:Solar t:dataTypeName=number

metric m:otec p:integer l:OTEC t:dataTypeName=number

metric m:hydro p:integer l:Hydro t:dataTypeName=number

metric m:geothermal p:integer l:Geothermal t:dataTypeName=number

metric m:combination p:integer l:Combination t:dataTypeName=number

metric m:bioenergy p:integer l:Bioenergy t:dataTypeName=number

entity e:b8it-cxyb l:"DBEDT Currently Proposed Renewable Energy Projects In Hawaii" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/b8it-cxyb

property e:b8it-cxyb t:meta.view v:id=b8it-cxyb v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Currently Proposed Renewable Energy Projects In Hawaii" v:attribution="Department of Economic Development and Tourism"

property e:b8it-cxyb t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:b8it-cxyb t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:b8it-cxyb t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| :updated_at | x_values | wind | solar | otec | hydro | geothermal | combination | bioenergy | 
| =========== | ======== | ==== | ===== | ==== | ===== | ========== | =========== | ========= | 
| 1346157176  | Hawaii   | 2    |       |      |       | 1          |             | 11        | 
| 1346157176  | Kauai    |      | 3     |      | 7     |            |             | 4         | 
| 1346157176  | Lanai    | 1    |       |      |       |            |             |           | 
| 1346157176  | Maui     | 2    |       | 1    | 1     | 1          |             | 3         | 
| 1346157176  | Molokai  | 2    |       |      |       |            |             |           | 
| 1346157176  | Oahu     | 1    | 12    | 3    |       |            | 1           | 9         | 
| 1346157176  | TBD      |      |       |      |       |            |             | 1         | 
```