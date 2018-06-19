# DBEDT Hawaii Renewable Energy Generation 2005-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-renewable-energy-generation-2005-2010-5c5b0) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vvr4-p4an) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vvr4-p4an/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vvr4-p4an/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vvr4-p4an |
| Name | DBEDT Hawaii Renewable Energy Generation 2005-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy |
| Created | 2012-08-28T19:51:05Z |
| Publication Date | 2012-08-29T01:30:55Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | numeric metric | x_values    | X Values    | number    | number      |
| Yes      | numeric metric | heco        | HECO        | percent   | percent     |
| Yes      | numeric metric | helco       | HELCO       | percent   | percent     |
| Yes      | numeric metric | meco        | MECO        | percent   | percent     |
| Yes      | numeric metric | kiuc        | KIUC        | percent   | percent     |
| Yes      | numeric metric | state_total | State Total | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vvr4-p4an d:2005-01-01T00:00:00.000Z m:state_total=6.8 m:helco=24.2 m:kiuc=8 m:meco=6 m:heco=4.3 m:x_values=2005

series e:vvr4-p4an d:2005-01-01T00:00:00.000Z m:state_total=8.2 m:helco=25.7 m:kiuc=7.9 m:meco=10.8 m:heco=5.1 m:x_values=2006

series e:vvr4-p4an d:2005-01-01T00:00:00.000Z m:state_total=8.9 m:helco=33.8 m:kiuc=5.5 m:meco=15.4 m:heco=4.3 m:x_values=2007
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:heco p:float l:HECO t:dataTypeName=percent

metric m:helco p:float l:HELCO t:dataTypeName=percent

metric m:meco p:float l:MECO t:dataTypeName=percent

metric m:kiuc p:float l:KIUC t:dataTypeName=percent

metric m:state_total p:float l:"State Total" t:dataTypeName=percent

entity e:vvr4-p4an l:"DBEDT Hawaii Renewable Energy Generation 2005-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/vvr4-p4an

property e:vvr4-p4an t:meta.view v:id=vvr4-p4an v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Renewable Energy Generation 2005-2010" v:attribution="Department of Economic Development and Tourism"

property e:vvr4-p4an t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:vvr4-p4an t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:vvr4-p4an t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | heco | helco | meco | kiuc | state_total | 
| ======== | ==== | ===== | ==== | ==== | =========== | 
| 2005     | 4.3  | 24.2  | 6.0  | 8.0  | 6.8         | 
| 2006     | 5.1  | 25.7  | 10.8 | 7.9  | 8.2         | 
| 2007     | 4.3  | 33.8  | 15.4 | 5.5  | 8.9         | 
| 2008     | 4.8  | 35.4  | 13.9 | 8.3  | 9.4         | 
| 2009     | 5.1  | 33.7  | 13.9 | 9.1  | 9.5         | 
| 2010     | 4.7  | 34.6  | 15.3 | 8.7  | 9.5         | 
```