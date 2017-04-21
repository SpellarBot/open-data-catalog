# Table 18.25 PUBLIC TRANSIT, FOR OAHU 1993 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-18-25-public-transit-for-oahu-1993-to-2013) |
| Metadata | [Link](https://data.hawaii.gov/api/views/88uj-hez9) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/88uj-hez9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/88uj-hez9/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 88uj-hez9 |
| Name | Table 18.25 PUBLIC TRANSIT, FOR OAHU 1993 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Transportation Facilities |
| Tags | bus, transit |
| Created | 2012-08-28T19:18:43Z |
| Publication Date | 2015-10-13T02:12:02Z |

## Description

* As of June 30.  Service provided by City and County of Honolulu bus system							
* Number of buses refers to number of buses in active fleet.							
* Vehicle miles and total passengers are estimated.							
* Bus strike for 34 days in 2004.							
     Source:  City and County of Honolulu, Department of Transportation Services, Public Transit Division, records.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type | Render Type |
| ======== | ============== | ================ | ================== | ========= | =========== |
| Yes      | time           | year             | Year               | number    | text        |
| Yes      | numeric metric | number_of_buses  | Number of buses    | number    | number      |
| Yes      | numeric metric | bus_mileage      | Bus mileage        | number    | number      |
| Yes      | numeric metric | total_passengers | Total passengers   | number    | number      |
| Yes      | numeric metric | revenues_dollars | Revenues (dollars) | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:88uj-hez9 d:1993-01-01T00:00:00.000Z m:revenues_dollars=19837616 m:bus_mileage=18120044 m:number_of_buses=470 m:total_passengers=76136390

series e:88uj-hez9 d:1994-01-01T00:00:00.000Z m:revenues_dollars=23897154 m:bus_mileage=18396694 m:number_of_buses=501 m:total_passengers=77338147

series e:88uj-hez9 d:1995-01-01T00:00:00.000Z m:revenues_dollars=25058736 m:bus_mileage=19031466 m:number_of_buses=508 m:total_passengers=72745086
```

## Meta Commands

```ls
metric m:number_of_buses p:integer l:"Number of buses" t:dataTypeName=number

metric m:bus_mileage p:integer l:"Bus mileage" t:dataTypeName=number

metric m:total_passengers p:integer l:"Total passengers" t:dataTypeName=number

metric m:revenues_dollars p:integer l:"Revenues (dollars)" t:dataTypeName=money

entity e:88uj-hez9 l:"Table 18.25 PUBLIC TRANSIT, FOR OAHU  1993 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/88uj-hez9

property e:88uj-hez9 t:meta.view v:id=88uj-hez9 v:category="Transportation Facilities" v:attributionLink=http://hawaii.gov/dbedt/economic/databook v:averageRating=0 v:name="Table 18.25 PUBLIC TRANSIT, FOR OAHU  1993 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:88uj-hez9 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:88uj-hez9 t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:88uj-hez9 t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | number_of_buses | bus_mileage | total_passengers | revenues_dollars | 
| ==== | =============== | =========== | ================ | ================ | 
| 1993 | 470             | 18120044    | 76136390         | 19837616         | 
| 1994 | 501             | 18396694    | 77338147         | 23897154         | 
| 1995 | 508             | 19031466    | 72745086         | 25058736         | 
| 1996 | 523             | 19090912    | 68923459         | 30420976         | 
| 1997 | 524             | 19452526    | 68634884         | 29804091         | 
| 1998 | 525             | 19665805    | 71822553         | 29197402         | 
| 1999 | 525             | 19639602    | 66236147         | 27819265         | 
| 2000 | 525             | 20359607    | 66602820         | 27055656         | 
| 2001 | 529             | 21710838    | 70384025         | 26963518         | 
| 2002 | 525             | 21800354    | 73524474         | 30602648         | 
```