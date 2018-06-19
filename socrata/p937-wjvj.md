# Rodent Inspection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rodent-inspection) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/p937-wjvj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/p937-wjvj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/p937-wjvj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | p937-wjvj |
| Name | Rodent Inspection |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | rodent, inspection, health, dohmh |
| Created | 2015-11-23T16:34:42Z |
| Publication Date | 2017-02-21T16:08:11Z |

## Description

Dataset contains information on rat inspections.

Rat Information Portal Data Release Notes        April 20, 2015

The Rat Information Portal (RIP) is a web-based mapping application where users can view rat inspection data. 

Data sources: NYC Department of Health and Mental Hygiene (DOHMH), Division of Environmental Health Pest Control Database

Notes on data limitations: Please note that if a property/taxlot does not appear in the file, that does not indicate an absence of rats - rather just that it has not been inspected. Similarly, neighborhoods with higher rates of active rat signs may not actually have higher rat populations but simply have more inspections. 

See our Data Disclaimer:
http://www.nyc.gov/html/doh/html/environmental/disclaimer.shtml

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | inspection_type             | INSPECTION_TYPE             | text          | text          |
| Yes      | series tag     | job_ticket_or_work_order_id | JOB_TICKET_OR_WORK_ORDER_ID | text          | number        |
| Yes      | series tag     | job_id                      | JOB_ID                      | text          | text          |
| Yes      | numeric metric | job_progress                | JOB_PROGRESS                | number        | number        |
| Yes      | numeric metric | bbl                         | BBL                         | number        | number        |
| Yes      | series tag     | boro_code                   | BORO_CODE                   | text          | number        |
| Yes      | series tag     | block                       | BLOCK                       | text          | text          |
| Yes      | series tag     | lot                         | LOT                         | text          | text          |
| Yes      | series tag     | house_number                | HOUSE_NUMBER                | text          | text          |
| Yes      | series tag     | street_name                 | STREET_NAME                 | text          | text          |
| Yes      | series tag     | zip_code                    | ZIP_CODE                    | text          | text          |
| Yes      | numeric metric | x_coord                     | X_COORD                     | number        | number        |
| Yes      | numeric metric | y_coord                     | Y_COORD                     | number        | number        |
| No       |                | latitude                    | LATITUDE                    | number        | number        |
| No       |                | longitude                   | LONGITUDE                   | number        | number        |
| Yes      | series tag     | borough                     | BOROUGH                     | text          | text          |
| No       |                | inspection_date             | INSPECTION_DATE             | calendar_date | calendar_date |
| Yes      | series tag     | result                      | RESULT                      | text          | text          |
| Yes      | time           | approved_date               | APPROVED_DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = approved_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,inspection_date
```

## Data Commands

```ls
series e:p937-wjvj d:2009-10-14T15:01:46.000Z t:result="Bait applied" t:house_number=104 t:job_ticket_or_work_order_id=1 t:boro_code=1 t:zip_code=10023 t:street_name="WEST 76 STREET" t:inspection_type=BAIT t:lot=0035 t:block=01147 t:borough=Manhattan t:job_id=PO12965 m:bbl=1011470035 m:y_coord=223527 m:job_progress=3 m:x_coord=990505

series e:p937-wjvj d:2009-10-14T15:02:30.000Z t:result="Bait applied" t:house_number=102 t:job_ticket_or_work_order_id=2 t:boro_code=1 t:zip_code=10023 t:street_name="WEST 76 STREET" t:inspection_type=BAIT t:lot=0034 t:block=01147 t:borough=Manhattan t:job_id=PO12966 m:bbl=1011470034 m:y_coord=223521 m:job_progress=3 m:x_coord=990516

series e:p937-wjvj d:2009-11-10T14:54:52.000Z t:result="Bait applied" t:house_number=620 t:job_ticket_or_work_order_id=30 t:boro_code=2 t:zip_code=10467 t:street_name="THWAITES PLACE" t:inspection_type=BAIT t:lot=0027 t:block=04337 t:borough=Bronx t:job_id=PO16966 m:bbl=2043370027 m:y_coord=252216 m:job_progress=3 m:x_coord=1020110
```

## Meta Commands

```ls
metric m:job_progress p:integer l:JOB_PROGRESS d:"An indicator of the progress made in the job. Jobs may involve multiple inspections or other actions, and the progress indicator shows the order in which they took place." t:dataTypeName=number

metric m:bbl p:long l:BBL d:"Borough, Block, and Lot code, which is a unique identifier of NYC Taxlots. Every NYC property has its own BBL code, and inspections are conducted at the taxlot level. This dataset can be mapped by joining these inspectional results to a taxlot geography file such as the Department of City Planning?s PLUTO dataset." t:dataTypeName=number

metric m:x_coord p:integer l:X_COORD d:"X coordinate of the inspected taxlot in NY State Plane Long Island Coordinate system" t:dataTypeName=number

metric m:y_coord p:integer l:Y_COORD d:"Y coordinate of the inspected taxlot in NY State Plane Long Island Coordinate system" t:dataTypeName=number

entity e:p937-wjvj l:"Rodent Inspection" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/p937-wjvj

property e:p937-wjvj t:meta.view v:id=p937-wjvj v:category=Health v:averageRating=0 v:name="Rodent Inspection" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:p937-wjvj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:p937-wjvj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| inspection_type | job_ticket_or_work_order_id | job_id  | job_progress | bbl        | boro_code | block | lot  | house_number | street_name      | zip_code | x_coord | y_coord | latitude                | longitude                | borough   | inspection_date     | result       | approved_date       | 
| =============== | =========================== | ======= | ============ | ========== | ========= | ===== | ==== | ============ | ================ | ======== | ======= | ======= | ======================= | ======================== | ========= | =================== | ============ | =================== | 
| BAIT            | 1                           | PO12965 | 3            | 1011470035 | 1         | 01147 | 0035 | 104          | WEST 76 STREET   | 10023    | 990505  | 223527  | 40.78020397924710000000 | -73.97741447094560000000 | Manhattan | 2009-10-14T12:00:27 | Bait applied | 2009-10-14T15:01:46 | 
| BAIT            | 2                           | PO12966 | 3            | 1011470034 | 1         | 01147 | 0034 | 102          | WEST 76 STREET   | 10023    | 990516  | 223521  | 40.78018750304380000000 | -73.97737475778700000000 | Manhattan | 2009-10-14T12:51:21 | Bait applied | 2009-10-14T15:02:30 | 
| BAIT            | 30                          | PO16966 | 3            | 2043370027 | 2         | 04337 | 0027 | 620          | THWAITES PLACE   | 10467    | 1020110 | 252216  | 40.85887657819720000000 | -73.87036364220230000000 | Bronx     | 2009-11-09T12:59:55 | Bait applied | 2009-11-10T14:54:52 | 
| BAIT            | 31                          | PO13665 | 3            | 2037670077 | 2         | 03767 | 0077 | 1227         | WHITEPLAINS ROAD | 10472    | 1022441 | 242180  | 40.83132096261480000000 | -73.86199408989900000000 | Bronx     | 2009-11-09T11:10:16 | Bait applied | 2009-11-10T14:56:42 | 
| BAIT            | 38                          | PO11291 | 3            | 1011690057 | 1         | 01169 | 0057 | 2199         | BROADWAY         | 10024    | 989641  | 224567  | 40.78305907258330000000 | -73.98053336406880000000 | Manhattan | 2009-11-10T08:40:42 | Bait applied | 2009-11-17T11:39:11 | 
| BAIT            | 39                          | PO12483 | 3            | 1015340012 | 1         | 01534 | 0012 | 232          | EAST 89 STREET   | 10128    | 997617  | 223597  | 40.78038821631300000000 | -73.95173435425670000000 | Manhattan | 2009-11-10T09:53:06 | Bait applied | 2009-11-17T11:39:42 | 
| BAIT            | 41                          | PO25356 | 3            | 1015860005 | 1         | 01586 | 0005 | 515          | EAST 89 STREET   | 10128    | 999449  | 222589  | 40.77761856260370000000 | -73.94512163923820000000 | Manhattan | 2009-11-10T09:00:51 | Bait applied | 2009-11-17T11:35:04 | 
| BAIT            | 46                          | PO16381 | 3            | 2028140048 | 2         | 02814 | 0048 | 1952         | ANTHONY AVENUE   | 10457    | 1011143 | 249042  | 40.85019676891450000000 | -73.90279266377060000000 | Bronx     | 2009-11-16T12:59:45 | Bait applied | 2009-11-16T16:20:18 | 
| BAIT            | 48                          | PO11801 | 3            | 2026930022 | 2         | 02693 | 0022 | 1230         | PROSPECT AVENUE  | 10459    | 1012333 | 240622  | 40.82708262593870000000 | -73.89852655408850000000 | Bronx     | 2009-11-16T12:06:24 | Bait applied | 2009-11-16T16:19:27 | 
| BAIT            | 50                          | PO11803 | 3            | 2026930008 | 2         | 02693 | 0008 | 1198         | PROSPECT AVENUE  | 10459    | 1012297 | 240506  | 40.82676435361030000000 | -73.89865711915570000000 | Bronx     | 2009-11-16T11:50:25 | Bait applied | 2009-11-16T16:20:04 | 
```