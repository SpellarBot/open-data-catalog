# Waste Collection & Diversion Report (daily)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waste-collection-diversion-report-daily) |
| Metadata | [Link](https://data.austintexas.gov/api/views/mbnu-4wq9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/mbnu-4wq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/mbnu-4wq9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | mbnu-4wq9 |
| Name | Waste Collection & Diversion Report (daily) |
| Attribution | Austin Resource Recovery |
| Tags | waste, collection, arr, load, resource, recovery, recycling, disposal, diversion |
| Created | 2015-09-10T22:11:57Z |
| Publication Date | 2017-01-11T13:09:58Z |

## Description

Austin Resource Recovery daily report providing waste collection information based on the following categories:
Report Date: The date collections information was recorded.
Load Type: The specific type of load that is being collected on that day. 
Load Weight: The weight (in pounds) collected for each service on the day it was delivered to a diversion facility
Drop off Site: The location where each type of waste is delivered for disposal, recycling or reuse: TDS Landfill indicates the Texas Disposal System landfill located at 12200 Carl Rd, Creedmoor, TX 78610; Balcones Recycling is a recycling facility located at  9301 Johnny Morris Road Austin, TX 78724; MRF is a Materials Recycling Facility (such as Texas Disposal Systems or Balcones Recycling);  Hornsby Bend is located at 2210 FM 973, Austin, TX 78725  and accepts food scraps, yard trimmings, food-soiled paper and other materials collected by ARR, and combined with other waste to produce nutrient-rich dillo dirt,  used for landscaping.
Route Type:  The general category of collection service provided by Austin Resource Recovery 
This information is used to help ARR reach its goals to transform waste into resources while keeping our community clean. For more information, visit www.austintexas.gov/department/austin-resource-recovery

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | time           | report_date  | REPORT_DATE  | calendar_date | calendar_date |
| Yes      | series tag     | load_type    | LOAD_TYPE    | text          | text          |
| No       |                | load_time    | LOAD_TIME    | calendar_date | calendar_date |
| Yes      | numeric metric | load_weight  | LOAD_WEIGHT  | number        | number        |
| Yes      | series tag     | dropoff_site | DROPOFF_SITE | text          | text          |
| Yes      | series tag     | route_type   | ROUTE_TYPE   | text          | text          |
| Yes      | series tag     | route_number | ROUTE_NUMBER | text          | text          |
| Yes      | series tag     | load_id      | LOAD_ID      | text          | number        |
```

## Time Field

```ls
Value = report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = load_time
```

## Data Commands

```ls
series e:mbnu-4wq9 d:2011-02-11T00:00:00.000Z t:route_number=PAH70 t:route_type="GARBAGE COLLECTION" t:load_id=398759 t:dropoff_site="TDS LANDFILL" t:load_type="GARBAGE COLLECTIONS" m:load_weight=13340

series e:mbnu-4wq9 d:2011-02-11T00:00:00.000Z t:route_number=PAH09 t:route_type="GARBAGE COLLECTION" t:load_id=398760 t:dropoff_site="TDS LANDFILL" t:load_type="GARBAGE COLLECTIONS" m:load_weight=3020

series e:mbnu-4wq9 d:2011-02-11T00:00:00.000Z t:route_number=PAH70 t:route_type="GARBAGE COLLECTION" t:load_id=398761 t:dropoff_site="TDS LANDFILL" t:load_type="GARBAGE COLLECTIONS" m:load_weight=19000
```

## Meta Commands

```ls
metric m:load_weight p:integer l:LOAD_WEIGHT t:dataTypeName=number

entity e:mbnu-4wq9 l:"Waste Collection & Diversion Report (daily)" t:attribution="Austin Resource Recovery" t:url=https://data.austintexas.gov/api/views/mbnu-4wq9

property e:mbnu-4wq9 t:meta.view v:id=mbnu-4wq9 v:attributionLink=http://www.austintexas.gov/department/austin-resource-recovery v:averageRating=0 v:name="Waste Collection & Diversion Report (daily)" v:attribution="Austin Resource Recovery"

property e:mbnu-4wq9 t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:mbnu-4wq9 t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| report_date         | load_type           | load_time           | load_weight | dropoff_site | route_type         | route_number | load_id | 
| =================== | =================== | =================== | =========== | ============ | ================== | ============ | ======= | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T13:54:00 | 13340       | TDS LANDFILL | GARBAGE COLLECTION | PAH70        | 398759  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T11:40:00 | 3020        | TDS LANDFILL | GARBAGE COLLECTION | PAH09        | 398760  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T15:45:00 | 19000       | TDS LANDFILL | GARBAGE COLLECTION | PAH70        | 398761  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T12:53:00 | 24200       | TDS LANDFILL | GARBAGE COLLECTION | PAH71        | 398762  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T13:47:00 | 18920       | TDS LANDFILL | GARBAGE COLLECTION | PAH72        | 398763  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T13:15:00 | 22940       | TDS LANDFILL | GARBAGE COLLECTION | PAH73        | 398764  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T13:57:00 | 20960       | TDS LANDFILL | GARBAGE COLLECTION | PAH74        | 398765  | 
| 2011-02-11T00:00:00 | GARBAGE COLLECTIONS | 2011-02-11T13:42:00 | 23200       | TDS LANDFILL | GARBAGE COLLECTION | PAH75        | 398766  | 
| 2011-02-10T00:00:00 | GARBAGE COLLECTIONS | 2011-02-10T16:49:00 | 5580        | TDS LANDFILL | GARBAGE COLLECTION | PAW06        | 398769  | 
| 2011-02-10T00:00:00 | GARBAGE COLLECTIONS | 2011-02-10T13:48:00 | 20780       | TDS LANDFILL | GARBAGE COLLECTION | PAW06        | 398767  | 
```