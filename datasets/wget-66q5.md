# DBEDT Hawaii Cumulative Hybrid And Electric Vehicles Registered 2000-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-cumulative-hybrid-and-electric-vehicles-registered-2000-2010-fa209) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wget-66q5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wget-66q5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wget-66q5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wget-66q5 |
| Name | DBEDT Hawaii Cumulative Hybrid And Electric Vehicles Registered 2000-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity, energy, hybrid |
| Created | 2012-08-28T19:42:39Z |
| Publication Date | 2012-08-29T01:27:45Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | numeric metric | x_values                 | X Values                 | number    | number      |
| Yes      | numeric metric | hybrid_electric_vehicles | Hybrid Electric Vehicles | number    | number      |
| Yes      | numeric metric | electric_vehicles        | Electric Vehicles*       | number    | number      |
| Yes      | numeric metric | total                    | Total                    | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wget-66q5 d:2000-01-01T00:00:00.000Z m:total=10 m:hybrid_electric_vehicles=0 m:electric_vehicles=10 m:x_values=1999

series e:wget-66q5 d:2000-01-01T00:00:00.000Z m:total=73 m:hybrid_electric_vehicles=48 m:electric_vehicles=25 m:x_values=2000

series e:wget-66q5 d:2000-01-01T00:00:00.000Z m:total=199 m:hybrid_electric_vehicles=165 m:electric_vehicles=34 m:x_values=2001
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:hybrid_electric_vehicles p:integer l:"Hybrid Electric Vehicles" t:dataTypeName=number

metric m:electric_vehicles p:integer l:"Electric Vehicles*" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:wget-66q5 l:"DBEDT Hawaii Cumulative Hybrid And Electric Vehicles Registered 2000-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/wget-66q5

property e:wget-66q5 t:meta.view v:id=wget-66q5 v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Cumulative Hybrid And Electric Vehicles Registered 2000-2010" v:attribution="Department of Economic Development and Tourism"

property e:wget-66q5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:wget-66q5 t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:wget-66q5 t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | hybrid_electric_vehicles | electric_vehicles | total | 
| ======== | ======================== | ================= | ===== | 
| 1999     | 0                        | 10                | 10    | 
| 2000     | 48                       | 25                | 73    | 
| 2001     | 165                      | 34                | 199   | 
| 2002     | 267                      | 58                | 325   | 
| 2003     | 510                      | 70                | 580   | 
| 2004     | 1078                     | 83                | 1161  | 
| 2005     | 2254                     | 107               | 2361  | 
| 2006     | 3719                     | 122               | 3841  | 
| 2007     | 5251                     | 156               | 5407  | 
| 2008     | 6841                     | 176               | 7017  | 
```