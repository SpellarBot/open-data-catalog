# Cooking Gas Consumption And Cost (2010 - 2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cooking-gas-consumption-and-cost) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/avhb-5jhc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/avhb-5jhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/avhb-5jhc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | avhb-5jhc |
| Name | Cooking Gas Consumption And Cost (2010 - 2016) |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | cooking gas consumption and cost |
| Created | 2016-07-15T22:08:05Z |
| Publication Date | 2017-02-21T19:56:16Z |

## Description

Monthly consumption and cost data by borough and development. Data set includes utility vendor and meter information.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | series tag     | development_name   | Development Name     | text          | text          |
| Yes      | series tag     | borough            | Borough              | text          | text          |
| Yes      | series tag     | account_name       | Account Name         | text          | text          |
| Yes      | series tag     | location           | Location             | text          | text          |
| Yes      | series tag     | meter_amr          | Meter AMR            | text          | text          |
| Yes      | series tag     | meter_scope        | Meter Scope          | text          | text          |
| Yes      | numeric metric | tds                | TDS #                | number        | number        |
| Yes      | numeric metric | edp                | EDP                  | number        | number        |
| Yes      | series tag     | rc_code            | RC Code              | text          | text          |
| Yes      | series tag     | funding_source     | Funding Source       | text          | text          |
| Yes      | series tag     | amp                | AMP #                | text          | text          |
| Yes      | series tag     | vendor_name        | Vendor Name          | text          | text          |
| Yes      | series tag     | umis_bill_id       | UMIS BILL ID         | text          | number        |
| Yes      | time           | revenue_month      | Revenue Month        | calendar_date | calendar_date |
| No       |                | service_start_date | Service Start Date   | calendar_date | calendar_date |
| No       |                | service_end_date   | Service End Date     | calendar_date | calendar_date |
| Yes      | numeric metric | days               | # days               | number        | number        |
| Yes      | series tag     | meter_number       | Meter Number         | text          | number        |
| Yes      | series tag     | estimated          | Estimated            | text          | text          |
| Yes      | numeric metric | current_charges    | Current Charges      | money         | money         |
| Yes      | series tag     | rate_class         | Rate Class           | text          | text          |
| Yes      | series tag     | bill_analyzed      | Bill Analyzed        | text          | text          |
| Yes      | numeric metric | consumption_therms | Consumption (Therms) | number        | number        |
| Yes      | series tag     | es_commodity       | ES Commodity         | text          | text          |
| Yes      | series tag     | underlying_utility | Underlying Utility   | text          | text          |
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
series e:avhb-5jhc d:2010-01-01T00:00:00.000Z t:underlying_utility=ConEd t:location=05 t:borough=BRONX t:umis_bill_id=2006571 t:rate_class="Trans Gen Non-Res" t:meter_number=3377402 t:account_name=ADAMS t:estimated=N t:funding_source=FEDERAL t:bill_analyzed=Yes t:development_name=ADAMS t:es_commodity="UTILITY GAS" t:rc_code=B011800 t:amp=NY005001180P t:meter_amr=NONE t:vendor_name="CONSOLIDATED EDISON COMPANY OF NY" m:consumption_therms=0 m:days=33 m:current_charges=0 m:edp=248 m:tds=118

series e:avhb-5jhc d:2010-01-01T00:00:00.000Z t:underlying_utility=ConEd t:location=05 t:borough=BRONX t:umis_bill_id=2006571 t:rate_class="Trans Gen Non-Res" t:meter_number=3564594 t:account_name=ADAMS t:estimated=N t:funding_source=FEDERAL t:bill_analyzed=Yes t:development_name=ADAMS t:es_commodity="UTILITY GAS" t:rc_code=B011800 t:amp=NY005001180P t:meter_amr=NONE t:vendor_name="CONSOLIDATED EDISON COMPANY OF NY" m:consumption_therms=3002 m:days=33 m:current_charges=1672.75 m:edp=248 m:tds=118

series e:avhb-5jhc d:2010-02-01T00:00:00.000Z t:underlying_utility=ConEd t:location=05 t:borough=BRONX t:umis_bill_id=2004571 t:rate_class="Trans Gen Non-Res" t:meter_number=3377402 t:account_name=ADAMS t:estimated=N t:funding_source=FEDERAL t:bill_analyzed=Yes t:development_name=ADAMS t:es_commodity="UTILITY GAS" t:rc_code=B011800 t:amp=NY005001180P t:meter_amr=NONE t:vendor_name="CONSOLIDATED EDISON COMPANY OF NY" m:consumption_therms=0 m:days=30 m:current_charges=0 m:edp=248 m:tds=118
```

## Meta Commands

```ls
metric m:tds p:integer l:"TDS #" d:"TDS (Tenant Data System) number is the unique identifier for all NCYHA developments. It is recommended to use it in order to run analysis by development. The TDS is also the unique link between NYCHA data sets." t:dataTypeName=number

metric m:edp p:integer l:EDP d:"NYCHA Electronic Data Processing. Number used to identify individual NYCHA developments. EDP is used by NYCHA only to link data issued from a different system (the energy management system that was used by NYCHA before 2010). It is recommended to use the TDS # as a unique identifier of each development." t:dataTypeName=number

metric m:days p:integer l:"# days" d:"Number of days on bill" t:dataTypeName=number

metric m:current_charges p:double l:"Current Charges" d:"Total costs of the bill." t:dataTypeName=money

metric m:consumption_therms p:float l:"Consumption (Therms)" d:"Total therm consumption" t:dataTypeName=number

entity e:avhb-5jhc l:"Cooking Gas Consumption And Cost (2010 - 2016)" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/avhb-5jhc

property e:avhb-5jhc t:meta.view v:id=avhb-5jhc v:category="Housing & Development" v:averageRating=0 v:name="Cooking Gas Consumption And Cost (2010 - 2016)" v:attribution="New York City Housing Authority (NYCHA)"

property e:avhb-5jhc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:avhb-5jhc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| development_name | borough | account_name | location | meter_amr | meter_scope | tds | edp | rc_code | funding_source | amp          | vendor_name                       | umis_bill_id | revenue_month       | service_start_date  | service_end_date    | days | meter_number | estimated | current_charges | rate_class        | bill_analyzed | consumption_therms | es_commodity | underlying_utility | 
| ================ | ======= | ============ | ======== | ========= | =========== | === | === | ======= | ============== | ============ | ================================= | ============ | =================== | =================== | =================== | ==== | ============ | ========= | =============== | ================= | ============= | ================== | ============ | ================== | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2006571      | 2010-01-01T00:00:00 | 2009-12-24T00:00:00 | 2010-01-26T00:00:00 | 33   | 3377402      | N         | 0.00            | Trans Gen Non-Res | Yes           | 0.00               | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2006571      | 2010-01-01T00:00:00 | 2009-12-24T00:00:00 | 2010-01-26T00:00:00 | 33   | 3564594      | N         | 1672.75         | Trans Gen Non-Res | Yes           | 3002.00            | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2004571      | 2010-02-01T00:00:00 | 2010-01-26T00:00:00 | 2010-02-25T00:00:00 | 30   | 3377402      | N         | 0.00            | Trans Gen Non-Res | Yes           | 0.00               | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2004571      | 2010-02-01T00:00:00 | 2010-01-26T00:00:00 | 2010-02-25T00:00:00 | 30   | 3564594      | N         | 1630.19         | Trans Gen Non-Res | Yes           | 2961.00            | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2039129      | 2010-03-01T00:00:00 | 2010-02-25T00:00:00 | 2010-03-26T00:00:00 | 29   | 3377402      | N         | 0.00            | Trans Gen Non-Res | Yes           | 0.00               | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2039129      | 2010-03-01T00:00:00 | 2010-02-25T00:00:00 | 2010-03-26T00:00:00 | 29   | 3564594      | N         | 1307.01         | Trans Gen Non-Res | Yes           | 2345.00            | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2031838      | 2010-04-01T00:00:00 | 2010-03-26T00:00:00 | 2010-04-26T00:00:00 | 31   | 3377402      | N         | 0.00            | Trans Gen Non-Res | Yes           | 0.00               | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 2031838      | 2010-04-01T00:00:00 | 2010-03-26T00:00:00 | 2010-04-26T00:00:00 | 31   | 3564594      | N         | 1282.94         | Trans Gen Non-Res | Yes           | 2234.00            | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 1998379      | 2010-05-01T00:00:00 | 2010-04-26T00:00:00 | 2010-05-24T00:00:00 | 28   | 3377402      | N         | 0.00            | Trans Gen Non-Res | Yes           | 0.00               | UTILITY GAS  | ConEd              | 
| ADAMS            | BRONX   | ADAMS        | 05       | NONE      |             | 118 | 248 | B011800 | FEDERAL        | NY005001180P | CONSOLIDATED EDISON COMPANY OF NY | 1998379      | 2010-05-01T00:00:00 | 2010-04-26T00:00:00 | 2010-05-24T00:00:00 | 28   | 3564594      | N         | 1119.57         | Trans Gen Non-Res | Yes           | 1928.00            | UTILITY GAS  | ConEd              | 
```