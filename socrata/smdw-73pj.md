# Steam Consumption And Cost (2010 - 2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/steam-consumption-and-cost-2010-2016) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/smdw-73pj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/smdw-73pj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/smdw-73pj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | smdw-73pj |
| Name | Steam Consumption And Cost (2010 - 2016) |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | steam consumption and cost |
| Created | 2016-07-15T22:51:40Z |
| Publication Date | 2017-02-21T20:54:35Z |

## Description

Monthly consumption and cost data by borough and development. Data set includes utility vendor and meter information.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | development_name   | Development Name   | text          | text          |
| Yes      | series tag     | borough            | Borough            | text          | text          |
| Yes      | series tag     | account_name       | Account Name       | text          | text          |
| Yes      | series tag     | location           | Location           | text          | text          |
| Yes      | series tag     | meter_amr          | Meter AMR          | text          | text          |
| Yes      | series tag     | meter_scope        | Meter Scope        | text          | text          |
| Yes      | numeric metric | tds                | TDS #              | number        | number        |
| Yes      | numeric metric | edp                | EDP                | number        | number        |
| Yes      | series tag     | rc_code            | RC Code            | text          | text          |
| Yes      | series tag     | funding_source     | Funding Source     | text          | text          |
| Yes      | series tag     | amp                | AMP #              | text          | text          |
| Yes      | series tag     | vendor_name        | Vendor Name        | text          | text          |
| Yes      | series tag     | umis_bill_id       | UMIS BILL ID       | text          | number        |
| Yes      | time           | revenue_month      | Revenue Month      | calendar_date | calendar_date |
| No       |                | service_start_date | Service Start Date | calendar_date | calendar_date |
| No       |                | service_end_date   | Service End Date   | calendar_date | calendar_date |
| Yes      | numeric metric | days               | # days             | number        | number        |
| Yes      | series tag     | meter_number       | Meter Number       | text          | text          |
| Yes      | series tag     | estimated          | Estimated          | text          | text          |
| Yes      | numeric metric | current_charges    | Current Charges    | money         | money         |
| Yes      | series tag     | rate_class         | Rate Class         | text          | text          |
| Yes      | series tag     | bill_analyzed      | Bill Analyzed      | text          | text          |
| Yes      | numeric metric | consumption_mlbs   | Consumption (Mlbs) | number        | number        |
```

## Time Field

```ls
Value = revenue_month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = service_start_date,service_end_date
```

## Data Commands

```ls
series e:smdw-73pj d:2010-01-01T00:00:00.000Z t:location="BLD 01" t:borough=MANHATTAN t:umis_bill_id=1831828 t:rate_class=SC3 t:meter_number=321060 t:account_name="AMSTERDAM ADDITION" t:estimated=N t:funding_source="MIXED FINANCE/LLC1" t:bill_analyzed=Yes t:development_name="AMSTERDAM ADDITION" t:rc_code=M018700 t:meter_amr=AMR t:amp=NY005021870P t:vendor_name="CONSOLIDATED EDISON COMPANY OF NY" m:days=31 m:current_charges=50213.25 m:edp=453 m:consumption_mlbs=1612.64 m:tds=187

series e:smdw-73pj d:2010-01-01T00:00:00.000Z t:location="BLD 01" t:borough=MANHATTAN t:umis_bill_id=1831828 t:rate_class=SC3 t:meter_number=331048 t:account_name="AMSTERDAM ADDITION" t:estimated=N t:funding_source="MIXED FINANCE/LLC1" t:bill_analyzed=Yes t:development_name="AMSTERDAM ADDITION" t:rc_code=M018700 t:meter_amr=AMR t:amp=NY005021870P t:vendor_name="CONSOLIDATED EDISON COMPANY OF NY" m:days=31 m:current_charges=21201.7 m:edp=453 m:consumption_mlbs=680.91 m:tds=187

series e:smdw-73pj d:2010-02-01T00:00:00.000Z t:location="BLD 01" t:borough=MANHATTAN t:umis_bill_id=1831865 t:rate_class=SC3 t:meter_number=321060 t:account_name="AMSTERDAM ADDITION" t:estimated=N t:funding_source="MIXED FINANCE/LLC1" t:bill_analyzed=Yes t:development_name="AMSTERDAM ADDITION" t:rc_code=M018700 t:meter_amr=AMR t:amp=NY005021870P t:vendor_name="CONSOLIDATED EDISON COMPANY OF NY" m:days=29 m:current_charges=22119.58 m:edp=453 m:consumption_mlbs=706.22 m:tds=187
```

## Meta Commands

```ls
metric m:tds p:integer l:"TDS #" d:"TDS (Tenant Data System) number is the unique identifier for all NCYHA developments. It is recommended to use it in order to run analysis by development. The TDS is also the unique link between NYCHA data sets." t:dataTypeName=number

metric m:edp p:integer l:EDP d:"NYCHA Electronic Data Processing. Number used to identify individual NYCHA developments. EDP is used by NYCHA only to link data issued from a different system (the energy management system that was used by NYCHA before 2010). It is recommended to use the TDS # as a unique identifier of each development." t:dataTypeName=number

metric m:days p:integer l:"# days" d:"Number of days on bill" t:dataTypeName=number

metric m:current_charges p:double l:"Current Charges" d:"Total costs" t:dataTypeName=money

metric m:consumption_mlbs p:float l:"Consumption (Mlbs)" d:"Total Mlbs consumption" t:dataTypeName=number

entity e:smdw-73pj l:"Steam Consumption And Cost (2010 - 2016)" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/smdw-73pj

property e:smdw-73pj t:meta.view v:id=smdw-73pj v:category="Housing & Development" v:averageRating=0 v:name="Steam Consumption And Cost (2010 - 2016)" v:attribution="New York City Housing Authority (NYCHA)"

property e:smdw-73pj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:smdw-73pj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| development_name   | borough   | account_name       | location | meter_amr | meter_scope | tds | edp | rc_code | funding_source     | amp          | vendor_name                       | umis_bill_id | revenue_month       | service_start_date  | service_end_date    | days | meter_number | estimated | current_charges | rate_class | bill_analyzed | consumption_mlbs | 
| ================== | ========= | ================== | ======== | ========= | =========== | === | === | ======= | ================== | ============ | ================================= | ============ | =================== | =================== | =================== | ==== | ============ | ========= | =============== | ========== | ============= | ================ | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831828      | 2010-01-01T00:00:00 | 2009-12-21T00:00:00 | 2010-01-21T00:00:00 | 31   | 321060       | N         | 50213.25        | SC3        | Yes           | 1612.64          | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831828      | 2010-01-01T00:00:00 | 2009-12-21T00:00:00 | 2010-01-21T00:00:00 | 31   | 331048       | N         | 21201.70        | SC3        | Yes           | 680.91           | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831865      | 2010-02-01T00:00:00 | 2010-01-21T00:00:00 | 2010-02-19T00:00:00 | 29   | 321060       | N         | 22119.58        | SC3        | Yes           | 706.22           | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831865      | 2010-02-01T00:00:00 | 2010-01-21T00:00:00 | 2010-02-19T00:00:00 | 29   | 331048       | N         | 40960.48        | SC3        | Yes           | 1307.76          | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831915      | 2010-03-01T00:00:00 | 2010-02-19T00:00:00 | 2010-03-23T00:00:00 | 32   | 321060       | N         | 29303.60        | SC3        | Yes           | 947.68           | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831915      | 2010-03-01T00:00:00 | 2010-02-19T00:00:00 | 2010-03-23T00:00:00 | 32   | 331048       | N         | 26002.43        | SC3        | Yes           | 840.92           | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831923      | 2010-04-01T00:00:00 | 2010-03-23T00:00:00 | 2010-04-21T00:00:00 | 29   | 321060       | N         | 25469.36        | SC3        | Yes           | 802.30           | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831923      | 2010-04-01T00:00:00 | 2010-03-23T00:00:00 | 2010-04-21T00:00:00 | 29   | 331048       | N         | 0.00            | SC3        | Yes           | 0.00             | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831931      | 2010-05-01T00:00:00 | 2010-04-21T00:00:00 | 2010-05-19T00:00:00 | 28   | 321060       | N         | 11050.62        | SC3        | Yes           | 540.61           | 
| AMSTERDAM ADDITION | MANHATTAN | AMSTERDAM ADDITION | BLD 01   | AMR       |             | 187 | 453 | M018700 | MIXED FINANCE/LLC1 | NY005021870P | CONSOLIDATED EDISON COMPANY OF NY | 1831931      | 2010-05-01T00:00:00 | 2010-04-21T00:00:00 | 2010-05-19T00:00:00 | 28   | 331048       | N         | 1797.17         | SC3        | Yes           | 87.92            | 
```