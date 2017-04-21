# DBEDT Hawaii Energy Efficiency Improvements 2005-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-energy-efficiency-improvements-2005-2010-2c776) |
| Metadata | [Link](https://data.hawaii.gov/api/views/a7ub-k7sa) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/a7ub-k7sa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/a7ub-k7sa/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | a7ub-k7sa |
| Name | DBEDT Hawaii Energy Efficiency Improvements 2005-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy |
| Created | 2012-08-28T19:46:28Z |
| Publication Date | 2012-08-29T01:28:55Z |

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
series e:a7ub-k7sa d:2005-01-01T00:00:00.000Z m:state_total=5 m:helco=5.3 m:kiuc=4.4 m:meco=8 m:heco=4.4 m:x_values=2005

series e:a7ub-k7sa d:2005-01-01T00:00:00.000Z m:state_total=5.7 m:helco=5.7 m:kiuc=4.5 m:meco=8.5 m:heco=5.2 m:x_values=2006

series e:a7ub-k7sa d:2005-01-01T00:00:00.000Z m:state_total=6.9 m:helco=6 m:kiuc=4.4 m:meco=9.2 m:heco=6.8 m:x_values=2007
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:heco p:float l:HECO t:dataTypeName=percent

metric m:helco p:float l:HELCO t:dataTypeName=percent

metric m:meco p:float l:MECO t:dataTypeName=percent

metric m:kiuc p:float l:KIUC t:dataTypeName=percent

metric m:state_total p:float l:"State Total" t:dataTypeName=percent

entity e:a7ub-k7sa l:"DBEDT Hawaii Energy Efficiency Improvements 2005-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/a7ub-k7sa

property e:a7ub-k7sa t:meta.view v:id=a7ub-k7sa v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Energy Efficiency Improvements 2005-2010" v:attribution="Department of Economic Development and Tourism"

property e:a7ub-k7sa t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:a7ub-k7sa t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:a7ub-k7sa t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | heco | helco | meco | kiuc | state_total | 
| ======== | ==== | ===== | ==== | ==== | =========== | 
| 2005     | 4.4  | 5.3   | 8.0  | 4.4  | 5.0         | 
| 2006     | 5.2  | 5.7   | 8.5  | 4.5  | 5.7         | 
| 2007     | 6.8  | 6.0   | 9.2  | 4.4  | 6.9         | 
| 2008     | 9.0  | 5.3   | 8.7  | 4.0  | 8.3         | 
| 2009     | 10.0 | 5.7   | 9.8  | 4.2  | 9.2         | 
| 2010     | 11.8 | 7.4   | 10.8 | 3.7  | 10.8        | 
```