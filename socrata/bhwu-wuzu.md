# Heating Oil Consumption And Cost (2010 - November 2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/heating-oil-consumption-and-cost) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bhwu-wuzu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bhwu-wuzu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bhwu-wuzu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bhwu-wuzu |
| Name | Heating Oil Consumption And Cost (2010 - November 2016) |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | heating oil consumption and cost |
| Created | 2016-07-15T22:51:38Z |
| Publication Date | 2017-02-21T22:27:14Z |

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
| Yes      | numeric metric | consumption_gal    | Consumption (GAL)  | number        | number        |
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
series e:bhwu-wuzu d:2010-01-01T00:00:00.000Z t:estimated=N t:funding_source=FEDERAL t:development_name=ADAMS t:borough=BRONX t:rc_code=B011800 t:umis_bill_id=2897085 t:meter_amr="Not Applicable" t:amp=NY005001180P t:vendor_name="S.J. Fuel Co., Inc." t:meter_number=395416152700002-OIL t:account_name=ADAMS m:consumption_gal=148 m:days=33 m:current_charges=303.47 m:edp=248 m:tds=118

series e:bhwu-wuzu d:2010-02-01T00:00:00.000Z t:estimated=N t:funding_source=FEDERAL t:development_name=ADAMS t:borough=BRONX t:rc_code=B011800 t:umis_bill_id=2897086 t:meter_amr="Not Applicable" t:amp=NY005001180P t:vendor_name="S.J. Fuel Co., Inc." t:meter_number=395416152700002-OIL t:account_name=ADAMS m:consumption_gal=246 m:days=30 m:current_charges=504.41 m:edp=248 m:tds=118

series e:bhwu-wuzu d:2010-03-01T00:00:00.000Z t:estimated=N t:funding_source=FEDERAL t:development_name=ADAMS t:borough=BRONX t:rc_code=B011800 t:umis_bill_id=2897087 t:meter_amr="Not Applicable" t:amp=NY005001180P t:vendor_name="S.J. Fuel Co., Inc." t:meter_number=395416152700002-OIL t:account_name=ADAMS m:consumption_gal=98 m:days=29 m:current_charges=200.94 m:edp=248 m:tds=118
```

## Meta Commands

```ls
metric m:tds p:integer l:"TDS #" d:"TDS (Tenant Data System) number is the unique identifier for all NCYHA developments. It is recommended to use it in order to run analysis by development. The TDS is also the unique link between NYCHA data sets." t:dataTypeName=number

metric m:edp p:integer l:EDP d:"NYCHA Electronic Data Processing. Number used to identify individual NYCHA developments. EDP is used by NYCHA only to link data issued from a different system (the energy management system that was used by NYCHA before 2010). It is recommended to use the TDS # as a unique identifier of each development." t:dataTypeName=number

metric m:days p:integer l:"# days" d:"Number of days on bill" t:dataTypeName=number

metric m:current_charges p:double l:"Current Charges" d:"Total costs, calculated from oil delivery charges" t:dataTypeName=money

metric m:consumption_gal p:float l:"Consumption (GAL)" d:"Total Number 2 oil gallons consumption" t:dataTypeName=number

entity e:bhwu-wuzu l:"Heating Oil Consumption And Cost (2010 - November 2016)" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/bhwu-wuzu

property e:bhwu-wuzu t:meta.view v:id=bhwu-wuzu v:category="Housing & Development" v:averageRating=0 v:name="Heating Oil Consumption And Cost (2010 - November 2016)" v:attribution="New York City Housing Authority (NYCHA)"

property e:bhwu-wuzu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bhwu-wuzu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| development_name | borough | account_name | location | meter_amr      | meter_scope | tds | edp | rc_code | funding_source | amp          | vendor_name         | umis_bill_id | revenue_month       | service_start_date  | service_end_date    | days | meter_number        | estimated | current_charges | consumption_gal | 
| ================ | ======= | ============ | ======== | ============== | =========== | === | === | ======= | ============== | ============ | =================== | ============ | =================== | =================== | =================== | ==== | =================== | ========= | =============== | =============== | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897085      | 2010-01-01T00:00:00 | 2009-12-24T00:00:00 | 2010-01-26T00:00:00 | 33   | 395416152700002-OIL | N         | 303.47          | 148.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897086      | 2010-02-01T00:00:00 | 2010-01-26T00:00:00 | 2010-02-25T00:00:00 | 30   | 395416152700002-OIL | N         | 504.41          | 246.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897087      | 2010-03-01T00:00:00 | 2010-02-25T00:00:00 | 2010-03-26T00:00:00 | 29   | 395416152700002-OIL | N         | 200.94          | 98.00           | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897088      | 2010-05-01T00:00:00 | 2010-04-26T00:00:00 | 2010-05-24T00:00:00 | 28   | 395416152700002-OIL | N         | 789.42          | 385.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897089      | 2010-06-01T00:00:00 | 2010-05-24T00:00:00 | 2010-06-23T00:00:00 | 30   | 395416152700002-OIL | N         | 488.01          | 238.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897090      | 2010-07-01T00:00:00 | 2010-06-23T00:00:00 | 2010-07-23T00:00:00 | 30   | 395416152700002-OIL | N         | 982.63          | 422.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897091      | 2010-08-01T00:00:00 | 2010-07-23T00:00:00 | 2010-08-23T00:00:00 | 31   | 395416152700002-OIL | N         | 710.19          | 305.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897092      | 2010-09-01T00:00:00 | 2010-08-23T00:00:00 | 2010-09-22T00:00:00 | 30   | 395416152700002-OIL | N         | 246.82          | 106.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897093      | 2010-10-01T00:00:00 | 2010-09-22T00:00:00 | 2010-10-22T00:00:00 | 30   | 395416152700002-OIL | N         | 1336.56         | 574.00          | 
| ADAMS            | BRONX   | ADAMS        |          | Not Applicable |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | S.J. Fuel Co., Inc. | 2897094      | 2010-11-01T00:00:00 | 2010-10-22T00:00:00 | 2010-11-22T00:00:00 | 31   | 395416152700002-OIL | N         | 498.30          | 214.00          | 
```