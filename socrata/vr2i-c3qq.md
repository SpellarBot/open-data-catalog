# Citiwide Service Desk Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citiwide-service-desk-statistics-b25b0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vr2i-c3qq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vr2i-c3qq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vr2i-c3qq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vr2i-c3qq |
| Name | Citiwide Service Desk Statistics |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | doitt, service, desk, statistics, citiwide |
| Created | 2013-02-08T14:45:01Z |
| Publication Date | 2013-06-26T17:15:53Z |

## Description

NYC Service Desk Statistics

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | series tag     | citiwide_service_desk_tasks | Citiwide Service Desk Tasks | text      | text        |
| Yes      | numeric metric | number                      | Number                      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vr2i-c3qq d:2010-01-01T00:00:00.000Z t:citiwide_service_desk_tasks="Agencies, offices and organizations served" m:number=185

series e:vr2i-c3qq d:2010-01-01T00:00:00.000Z t:citiwide_service_desk_tasks="Total incidents created in 2010" m:number=138898

series e:vr2i-c3qq d:2007-01-01T00:00:00.000Z t:citiwide_service_desk_tasks="Average time to resolve (days) incidents" m:number=4.07
```

## Meta Commands

```ls
metric m:number p:double l:Number t:dataTypeName=number

entity e:vr2i-c3qq l:"Citiwide Service Desk Statistics" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/vr2i-c3qq

property e:vr2i-c3qq t:meta.view v:id=vr2i-c3qq v:category="City Government" v:attributionLink=http://www.nyc.gov/html/doitt/downloads/pdf/doitt_2010_annual_report.pdf v:averageRating=0 v:name="Citiwide Service Desk Statistics" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:vr2i-c3qq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vr2i-c3qq t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year | citiwide_service_desk_tasks                | number | 
| ==== | ========================================== | ====== | 
| 2010 | Agencies, offices and organizations served | 185    | 
| 2010 | Total incidents created in 2010            | 138898 | 
| 2007 | Average time to resolve (days) incidents   | 4.07   | 
| 2008 | Average time to resolve (days) incidents   | 2.16   | 
| 2009 | Average time to resolve (days) incidents   | 2.56   | 
| 2010 | Average time to resolve (days) incidents   | 1.71   | 
```