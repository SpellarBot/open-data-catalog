# Bicycle & Pedestrian Counts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bicycle-pedestrian-counts) |
| Metadata | [Link](https://data.somervillema.gov/api/views/qu9x-4xq5) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/qu9x-4xq5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/qu9x-4xq5/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | qu9x-4xq5 |
| Name | Bicycle & Pedestrian Counts |
| Attribution | City of Somerville Transportation & Infrastructure Department |
| Tags | transportation, mobility, bicycle, pedestrian |
| Created | 2017-01-06T15:06:45Z |
| Publication Date | 2017-01-06T15:09:09Z |

## Description

Results of the City's bicycle and pedestrian counts from 2010-2016

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | year          | Year          | number    | number      |
| Yes      | numeric metric | location      | Location #    | number    | number      |
| Yes      | series tag     | location_name | Location Name | text      | text        |
| Yes      | series tag     | am_pm         | AM/PM         | text      | text        |
| Yes      | numeric metric | movement      | Movement      | number    | number      |
| Yes      | numeric metric | bike          | Bike          | number    | number      |
| Yes      | numeric metric | ped           | Ped           | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qu9x-4xq5 d:2010-01-01T00:00:00.000Z t:location_name="Webster Ave & Prospect St" t:am_pm=AM m:bike=1 m:location=1 m:movement=1 m:ped=22

series e:qu9x-4xq5 d:2010-01-01T00:00:00.000Z t:location_name="Webster Ave & Prospect St" t:am_pm=AM m:bike=3 m:location=1 m:movement=2 m:ped=17

series e:qu9x-4xq5 d:2010-01-01T00:00:00.000Z t:location_name="Webster Ave & Prospect St" t:am_pm=AM m:bike=58 m:location=1 m:movement=3 m:ped=59
```

## Meta Commands

```ls
metric m:location p:integer l:"Location #" t:dataTypeName=number

metric m:movement p:integer l:Movement t:dataTypeName=number

metric m:bike p:integer l:Bike t:dataTypeName=number

metric m:ped p:integer l:Ped t:dataTypeName=number

entity e:qu9x-4xq5 l:"Bicycle & Pedestrian Counts" t:attribution="City of Somerville Transportation & Infrastructure Department" t:url=https://data.somervillema.gov/api/views/qu9x-4xq5

property e:qu9x-4xq5 t:meta.view v:id=qu9x-4xq5 v:averageRating=0 v:name="Bicycle & Pedestrian Counts" v:attribution="City of Somerville Transportation & Infrastructure Department"

property e:qu9x-4xq5 t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:qu9x-4xq5 t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:qu9x-4xq5 t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| year | location | location_name                  | am_pm | movement | bike | ped | 
| ==== | ======== | ============================== | ===== | ======== | ==== | === | 
| 2010 | 1        | Webster Ave & Prospect St      | AM    | 1        | 1    | 22  | 
| 2010 | 1        | Webster Ave & Prospect St      | AM    | 2        | 3    | 17  | 
| 2010 | 1        | Webster Ave & Prospect St      | AM    | 3        | 58   | 59  | 
| 2010 | 1        | Webster Ave & Prospect St      | AM    | 4        | 5    | 26  | 
| 2010 | 2        | Washington St & Somerville Ave | AM    | 1        | 73   | 146 | 
| 2010 | 2        | Washington St & Somerville Ave | AM    | 2        | 14   | 70  | 
| 2010 | 2        | Washington St & Somerville Ave | AM    | 3        | 19   | 43  | 
| 2010 | 2        | Washington St & Somerville Ave | AM    | 4        | 17   | 39  | 
| 2010 | 3        | Somerville Ave & Prospect St   | AM    | 1        | 15   | 35  | 
| 2010 | 3        | Somerville Ave & Prospect St   | AM    | 2        | 16   | 47  | 
```