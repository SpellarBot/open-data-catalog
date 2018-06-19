# DBEDT Cost Of Electricity For State Agencies FY05- FY10

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-cost-of-electricity-for-state-agencies-fy05-fy10-b2d01) |
| Metadata | [Link](https://data.hawaii.gov/api/views/igkv-isiz) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/igkv-isiz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/igkv-isiz/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | igkv-isiz |
| Name | DBEDT Cost Of Electricity For State Agencies FY05- FY10 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity, energy |
| Created | 2012-08-28T19:28:35Z |
| Publication Date | 2012-08-29T01:24:20Z |

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
series e:igkv-isiz d:2012-08-28T12:28:36.000Z t:x_values=UH m:fy10=36468378 m:fy07=34221881 m:fy08=41121936 m:fy05=25206974 m:fy06=33613946 m:fy09=41486486

series e:igkv-isiz d:2012-08-28T12:28:36.000Z t:x_values=DOE m:fy10=33966349 m:fy07=31805744 m:fy08=38173389 m:fy05=25567384 m:fy06=30610076 m:fy09=38407151

series e:igkv-isiz d:2012-08-28T12:28:36.000Z t:x_values="DOT Airports" m:fy10=26676871 m:fy07=22920171 m:fy08=28641831 m:fy05=17761072 m:fy06=22259323 m:fy09=30078400
```

## Meta Commands

```ls
metric m:fy05 p:integer l:FY05 t:dataTypeName=number

metric m:fy06 p:integer l:FY06 t:dataTypeName=number

metric m:fy07 p:integer l:FY07 t:dataTypeName=number

metric m:fy08 p:integer l:FY08 t:dataTypeName=number

metric m:fy09 p:integer l:FY09 t:dataTypeName=number

metric m:fy10 p:integer l:FY10 t:dataTypeName=number

entity e:igkv-isiz l:"DBEDT Cost Of Electricity For State Agencies FY05- FY10" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/igkv-isiz

property e:igkv-isiz t:meta.view v:id=igkv-isiz v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Cost Of Electricity For State Agencies FY05- FY10" v:attribution="Department of Economic Development and Tourism"

property e:igkv-isiz t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:igkv-isiz t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:igkv-isiz t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| :updated_at | x_values     | fy05     | fy06     | fy07     | fy08     | fy09     | fy10     | 
| =========== | ============ | ======== | ======== | ======== | ======== | ======== | ======== | 
| 1346156916  | UH           | 25206974 | 33613946 | 34221881 | 41121936 | 41486486 | 36468378 | 
| 1346156916  | DOE          | 25567384 | 30610076 | 31805744 | 38173389 | 38407151 | 33966349 | 
| 1346156916  | DOT Airports | 17761072 | 22259323 | 22920171 | 28641831 | 30078400 | 26676871 | 
| 1346156916  | DAGS         | 7482710  | 9092737  | 9310630  | 11667310 | 11226894 | 9499992  | 
| 1346156916  | DOT Highways | 5010087  | 5905006  | 5782916  | 6979978  | 6883710  | 6318805  | 
| 1346156916  | DOH          | 3934069  | 4728875  | 4759470  | 6022990  | 6682947  | 5771076  | 
| 1346156916  | HPHA         | 2726530  | 3308536  | 3427260  | 4229350  | 4314939  | 4023549  | 
| 1346156916  | HHSC         | 3982094  | 4415497  | 4801818  | 5866179  | 6007542  | 5181870  | 
| 1346156916  | PSD          | 3264187  | 3951300  | 3848077  | 4689674  | 4634448  | 3897747  | 
| 1346156916  | DOT Harbors  | 1648777  | 2044297  | 2136409  | 2663999  | 2422545  | 1939602  | 
```