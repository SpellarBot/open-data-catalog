# Directory Of NYCHA NORC Program Core Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-nycha-norc-program-core-services-5670f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/39pe-uzy3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/39pe-uzy3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/39pe-uzy3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 39pe-uzy3 |
| Name | Directory Of NYCHA NORC Program Core Services |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, senior, norc, nycha, service |
| Created | 2013-02-13T19:51:19Z |
| Publication Date | 2013-06-21T20:45:52Z |

## Description

Details about the NYCHA NORC Program Core Services

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | text        |
| Yes      | series tag     | type_of_service  | Type of Service  | text      | text        |
| Yes      | numeric metric | units_of_service | Units of Service | number    | text        |
| Yes      | numeric metric | residents        | Residents        | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:39pe-uzy3 d:2011-01-01T00:00:00.000Z t:type_of_service="Case Management" m:units_of_service=10197

series e:39pe-uzy3 d:2011-01-01T00:00:00.000Z t:type_of_service="Case Management Assistance" m:units_of_service=10212 m:residents=1245

series e:39pe-uzy3 d:2011-01-01T00:00:00.000Z t:type_of_service="Health Care Management" m:units_of_service=2259 m:residents=304
```

## Meta Commands

```ls
metric m:units_of_service p:long l:"Units of Service" t:dataTypeName=number

metric m:residents p:integer l:Residents t:dataTypeName=number

entity e:39pe-uzy3 l:"Directory Of NYCHA NORC Program Core Services" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/39pe-uzy3

property e:39pe-uzy3 t:meta.view v:id=39pe-uzy3 v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/pub/conplan12_amended_vol2.pdf v:averageRating=0 v:name="Directory Of NYCHA NORC Program Core Services" v:attribution="Department of City Planning (DCP)"

property e:39pe-uzy3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:39pe-uzy3 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year | type_of_service                   | units_of_service | residents | 
| ==== | ================================= | ================ | ========= | 
| 2011 | Case Management                   | 10,197           |           | 
| 2011 | Case Management Assistance        | 10,212           | 1245      | 
| 2011 | Health Care Management            | 2,259            | 304       | 
| 2011 | Health Care Assistance            | 2,040            |           | 
| 2011 | Residents receiving Core Services | 8,334            | 1373      | 
| 2011 | New This Fiscal Year for 2011     | 555              | 33        | 
```