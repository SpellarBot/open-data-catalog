# Top Seven Service Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-six-service-requests) |
| Metadata | [Link](https://data.seattle.gov/api/views/vqnu-tyk4) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vqnu-tyk4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vqnu-tyk4/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vqnu-tyk4 |
| Name | Top Seven Service Requests |
| Category | City Business |
| Tags | csr, top 7, srs |
| Created | 2015-05-04T17:12:49Z |
| Publication Date | 2016-08-19T20:46:12Z |

## Description

This dataset includes what has consistently proven to be the top seven Service Requests the City received during the last 12 months. Six are specific (non-General Inquiry) types of Service Requests (Abandoned Vehicle, Illegal Dumping Report, Pothole, Graffiti Report, Parking Enforcement and Sign and Signal Maintenance) and the seventh, CSB-General Inquiry, represents requests for a variety of services received by the Customer Service Bureau, which are then assigned to departments accordingly.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year_month                  | Year_Month                  | text      | text        |
| Yes      | numeric metric | abandoned_vehicle           | Abandoned_Vehicle           | number    | number      |
| Yes      | numeric metric | general_inquiry             | General_Inquiry             | number    | number      |
| Yes      | numeric metric | graffiti_report             | Graffiti_Report             | number    | number      |
| Yes      | numeric metric | illegal_dumping_report      | Illegal_Dumping_Report      | number    | number      |
| Yes      | numeric metric | parking_enforcement         | Parking_Enforcement         | number    | number      |
| Yes      | numeric metric | pothole                     | Pothole                     | number    | number      |
| Yes      | numeric metric | sign_and_signal_maintenance | Sign_and_Signal_Maintenance | number    | number      |
```

## Time Field

```ls
Value = year_month
Format & Zone = yyyy-MM
```

## Data Commands

```ls
series e:vqnu-tyk4 d:2016-05-01T00:00:00.000Z m:parking_enforcement=596 m:graffiti_report=910 m:sign_and_signal_maintenance=230 m:general_inquiry=1166 m:illegal_dumping_report=973 m:abandoned_vehicle=3545 m:pothole=419

series e:vqnu-tyk4 d:2016-06-01T00:00:00.000Z m:parking_enforcement=609 m:graffiti_report=747 m:sign_and_signal_maintenance=219 m:general_inquiry=1263 m:illegal_dumping_report=1115 m:abandoned_vehicle=3449 m:pothole=392

series e:vqnu-tyk4 d:2016-07-01T00:00:00.000Z m:parking_enforcement=520 m:graffiti_report=824 m:sign_and_signal_maintenance=298 m:general_inquiry=1024 m:illegal_dumping_report=1260 m:abandoned_vehicle=3267 m:pothole=282
```

## Meta Commands

```ls
metric m:abandoned_vehicle p:integer l:Abandoned_Vehicle t:dataTypeName=number

metric m:general_inquiry p:integer l:General_Inquiry t:dataTypeName=number

metric m:graffiti_report p:integer l:Graffiti_Report t:dataTypeName=number

metric m:illegal_dumping_report p:integer l:Illegal_Dumping_Report t:dataTypeName=number

metric m:parking_enforcement p:integer l:Parking_Enforcement t:dataTypeName=number

metric m:pothole p:integer l:Pothole t:dataTypeName=number

metric m:sign_and_signal_maintenance p:integer l:Sign_and_Signal_Maintenance t:dataTypeName=number

entity e:vqnu-tyk4 l:"Top Seven Service Requests" t:url=https://data.seattle.gov/api/views/vqnu-tyk4

property e:vqnu-tyk4 t:meta.view v:id=vqnu-tyk4 v:category="City Business" v:averageRating=0 v:name="Top Seven Service Requests"

property e:vqnu-tyk4 t:meta.view.owner v:id=72yh-9d9n v:screenName="Wang, Deanna" v:displayName="Wang, Deanna"

property e:vqnu-tyk4 t:meta.view.tableauthor v:id=72yh-9d9n v:screenName="Wang, Deanna" v:roleName=publisher v:displayName="Wang, Deanna"
```

## Top Records

```ls
| year_month | abandoned_vehicle | general_inquiry | graffiti_report | illegal_dumping_report | parking_enforcement | pothole | sign_and_signal_maintenance | 
| ========== | ================= | =============== | =============== | ====================== | =================== | ======= | =========================== | 
| 2016-05    | 3545              | 1166            | 910             | 973                    | 596                 | 419     | 230                         | 
| 2016-06    | 3449              | 1263            | 747             | 1115                   | 609                 | 392     | 219                         | 
| 2016-07    | 3267              | 1024            | 824             | 1260                   | 520                 | 282     | 298                         | 
| 2016-10    | 2855              | 985             | 701             | 1233                   | 594                 | 418     | 324                         | 
| 2016-08    | 3620              | 1017            | 764             | 1463                   | 539                 | 251     | 377                         | 
| 2016-09    | 3097              | 1013            | 655             | 1393                   | 543                 | 229     | 379                         | 
| 2016-11    | 2731              | 920             | 502             | 955                    | 535                 | 662     | 294                         | 
| 2016-12    | 2444              | 668             | 617             | 795                    | 414                 | 568     | 295                         | 
| 2016-04    | 3198              | 995             | 817             | 940                    | 536                 | 557     | 242                         | 
| 2017-01    | 2847              | 931             | 709             | 1014                   | 418                 | 1129    | 286                         | 
```