# DBEDT New Distributed Renewable Energy Systems Installed In Hawaii Annually 2001-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-new-distributed-renewable-energy-systems-installed-in-hawaii-annually-2001-2010-b428e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mp64-qiad) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mp64-qiad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mp64-qiad/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mp64-qiad |
| Name | DBEDT New Distributed Renewable Energy Systems Installed In Hawaii Annually 2001-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy, renewable |
| Created | 2012-08-28T20:33:30Z |
| Publication Date | 2012-08-29T01:34:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | x_values       | X Values       | number    | number      |
| Yes      | numeric metric | heco           | HECO           | number    | number      |
| Yes      | numeric metric | helco          | HELCO          | number    | number      |
| Yes      | numeric metric | meco           | MECO           | number    | number      |
| Yes      | numeric metric | kiuc           | KIUC           | number    | number      |
| Yes      | numeric metric | state_total    | State Total    | number    | number      |
| Yes      | numeric metric | state_capacity | State Capacity | number    | number      |
```

## Time Field

```ls
Value = 2001
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mp64-qiad d:2001-01-01T00:00:00.000Z m:state_total=7 m:helco=2 m:state_capacity=29 m:kiuc=2 m:meco=2 m:heco=1 m:x_values=2001

series e:mp64-qiad d:2001-01-01T00:00:00.000Z m:state_total=18 m:helco=3 m:state_capacity=52 m:kiuc=9 m:meco=5 m:heco=1 m:x_values=2002

series e:mp64-qiad d:2001-01-01T00:00:00.000Z m:state_total=21 m:helco=6 m:state_capacity=65 m:kiuc=4 m:meco=3 m:heco=8 m:x_values=2003
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:heco p:integer l:HECO t:dataTypeName=number

metric m:helco p:integer l:HELCO t:dataTypeName=number

metric m:meco p:integer l:MECO t:dataTypeName=number

metric m:kiuc p:integer l:KIUC t:dataTypeName=number

metric m:state_total p:integer l:"State Total" t:dataTypeName=number

metric m:state_capacity p:integer l:"State Capacity" t:dataTypeName=number

entity e:mp64-qiad l:"DBEDT New Distributed Renewable Energy Systems Installed In Hawaii Annually 2001-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/mp64-qiad

property e:mp64-qiad t:meta.view v:id=mp64-qiad v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT New Distributed Renewable Energy Systems Installed In Hawaii Annually 2001-2010" v:attribution="Department of Economic Development and Tourism"

property e:mp64-qiad t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:mp64-qiad t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:mp64-qiad t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | heco | helco | meco | kiuc | state_total | state_capacity | 
| ======== | ==== | ===== | ==== | ==== | =========== | ============== | 
| 2001     | 1    | 2     | 2    | 2    | 7           | 29             | 
| 2002     | 1    | 3     | 5    | 9    | 18          | 52             | 
| 2003     | 8    | 6     | 3    | 4    | 21          | 65             | 
| 2004     | 3    | 4     | 8    | 8    | 23          | 77             | 
| 2005     | 0    | 10    | 16   | 4    | 30          | 166            | 
| 2006     | 10   | 35    | 50   | 14   | 109         | 646            | 
| 2007     | 73   | 35    | 64   | 35   | 207         | 1907           | 
| 2008     | 221  | 115   | 135  | 96   | 567         | 5864           | 
| 2009     | 511  | 265   | 298  | 92   | 1166        | 7525           | 
| 2010     | 1326 | 371   | 342  | 149  | 2188        | 12324          | 
```