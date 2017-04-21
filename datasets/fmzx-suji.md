# Total Occupied Housing Units By Household Size By Borough

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-occupied-housing-units-by-household-size-by-borough-de0e9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fmzx-suji) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fmzx-suji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fmzx-suji/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fmzx-suji |
| Name | Total Occupied Housing Units By Household Size By Borough |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, population, growth, household |
| Created | 2013-02-21T14:57:42Z |
| Publication Date | 2013-06-21T20:45:03Z |

## Description

Details of Occupied Housing Unit numbers by Household size by Borough

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                     | text      | text        |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | numeric metric | 1_person_households         | 1 Person Households         | number    | number      |
| Yes      | numeric metric | 2_person_households         | 2 Person Households         | number    | number      |
| Yes      | numeric metric | 3_person_households         | 3 Person Households         | number    | number      |
| Yes      | numeric metric | 4_person_households         | 4 Person Households         | number    | number      |
| Yes      | numeric metric | 5_person_households         | 5 Person Households         | number    | number      |
| Yes      | numeric metric | 6_person_households         | 6 Person Households         | number    | number      |
| Yes      | numeric metric | 7_or_more_person_households | 7 or more Person Households | number    | number      |
| Yes      | numeric metric | average_household_size      | Average Household Size      | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fmzx-suji d:2010-01-01T00:00:00.000Z t:borough=Bronx m:7_or_more_person_households=16159 m:2_person_households=118775 m:5_person_households=38827 m:1_person_households=136482 m:3_person_households=87693 m:4_person_households=67596 m:average_household_size=2.77 m:6_person_households=17917

series e:fmzx-suji d:2010-01-01T00:00:00.000Z t:borough=Brooklyn m:7_or_more_person_households=33848 m:2_person_households=255615 m:5_person_households=62100 m:1_person_households=266236 m:3_person_households=154530 m:4_person_households=113355 m:average_household_size=2.69 m:6_person_households=31172

series e:fmzx-suji d:2010-01-01T00:00:00.000Z t:borough=Manhattan m:7_or_more_person_households=7737 m:2_person_households=229856 m:5_person_households=22006 m:1_person_households=353569 m:3_person_households=87262 m:4_person_households=54543 m:average_household_size=1.99 m:6_person_households=8873
```

## Meta Commands

```ls
metric m:1_person_households p:integer l:"1 Person Households" t:dataTypeName=number

metric m:2_person_households p:integer l:"2 Person Households" t:dataTypeName=number

metric m:3_person_households p:integer l:"3 Person Households" t:dataTypeName=number

metric m:4_person_households p:integer l:"4 Person Households" t:dataTypeName=number

metric m:5_person_households p:integer l:"5 Person Households" t:dataTypeName=number

metric m:6_person_households p:integer l:"6 Person Households" t:dataTypeName=number

metric m:7_or_more_person_households p:integer l:"7 or more Person Households" t:dataTypeName=number

metric m:average_household_size p:float l:"Average Household Size" t:dataTypeName=number

entity e:fmzx-suji l:"Total Occupied Housing Units By Household Size By Borough" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/fmzx-suji

property e:fmzx-suji t:meta.view v:id=fmzx-suji v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/census/census_brief2_051012.pdf v:averageRating=0 v:name="Total Occupied Housing Units By Household Size By Borough" v:attribution="Department of City Planning (DCP)"

property e:fmzx-suji t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fmzx-suji t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| borough       | year | 1_person_households | 2_person_households | 3_person_households | 4_person_households | 5_person_households | 6_person_households | 7_or_more_person_households | average_household_size | 
| ============= | ==== | =================== | =================== | =================== | =================== | =================== | =================== | =========================== | ====================== | 
| Bronx         | 2010 | 136482              | 118775              | 87693               | 67596               | 38827               | 17917               | 16159                       | 2.77                   | 
| Brooklyn      | 2010 | 266236              | 255615              | 154530              | 113355              | 62100               | 31172               | 33848                       | 2.69                   | 
| Manhattan     | 2010 | 353569              | 229856              | 87262               | 54543               | 22006               | 8873                | 7737                        | 1.99                   | 
| Queens        | 2010 | 199461              | 209249              | 137480              | 114363              | 61876               | 29415               | 28273                       | 2.82                   | 
| Staten Island | 2010 | 40007               | 45286               | 29678               | 27832               | 13706               | 5257                | 3750                        | 2.78                   | 
```