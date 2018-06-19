# Electric Consumption And Cost (2010 - 2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electric-consumption-and-cost-2010) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jr24-e7cr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jr24-e7cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jr24-e7cr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jr24-e7cr |
| Name | Electric Consumption And Cost (2010 - 2016) |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | electric consumption and cost |
| Created | 2016-07-15T22:45:51Z |
| Publication Date | 2017-02-22T15:15:37Z |

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
| Yes      | series tag     | current_charges    | Current Charges    | text          | text          |
| Yes      | series tag     | rate_class         | Rate Class         | text          | text          |
| Yes      | series tag     | bill_analyzed      | Bill Analyzed      | text          | text          |
| Yes      | numeric metric | consumption_kwh    | Consumption (KWH)  | number        | text          |
| Yes      | numeric metric | kwh_charges        | KWH Charges        | money         | text          |
| Yes      | numeric metric | consumption_kw     | Consumption (KW)   | number        | number        |
| Yes      | numeric metric | kw_charges         | KW Charges         | money         | text          |
| Yes      | series tag     | other_charges      | Other charges      | text          | text          |
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
series e:jr24-e7cr d:2010-01-01T00:00:00.000Z t:location="BLD 05" t:borough=BRONX t:current_charges=$15,396.82 t:umis_bill_id=1842037 t:meter_scope="BLD 01 to 07" t:rate_class=GOV/NYC/068 t:meter_number=7223256 t:other_charges=$5,200.85 t:account_name=ADAMS t:estimated=N t:funding_source=FEDERAL t:bill_analyzed=Yes t:development_name=ADAMS t:rc_code=B011800 t:amp=NY005001180P t:meter_amr=NONE t:vendor_name="NEW YORK POWER AUTHORITY" m:days=33 m:consumption_kw=216 m:consumption_kwh=128800 m:edp=248 m:kwh_charges=7387.97 m:kw_charges=2808 m:tds=118

series e:jr24-e7cr d:2010-02-01T00:00:00.000Z t:location="BLD 05" t:borough=BRONX t:current_charges=$14,556.34 t:umis_bill_id=1844205 t:meter_scope="BLD 01 to 07" t:rate_class=GOV/NYC/068 t:meter_number=7223256 t:other_charges=$5,036.47 t:account_name=ADAMS t:estimated=N t:funding_source=FEDERAL t:bill_analyzed=Yes t:development_name=ADAMS t:rc_code=B011800 t:amp=NY005001180P t:meter_amr=NONE t:vendor_name="NEW YORK POWER AUTHORITY" m:days=30 m:consumption_kw=224 m:consumption_kwh=115200 m:edp=248 m:kwh_charges=6607.87 m:kw_charges=2912 m:tds=118

series e:jr24-e7cr d:2010-03-01T00:00:00.000Z t:location="BLD 05" t:borough=BRONX t:current_charges=$13,904.98 t:umis_bill_id=1841378 t:meter_scope="BLD 01 to 07" t:rate_class=GOV/NYC/068 t:meter_number=7223256 t:other_charges=$5,177.43 t:account_name=ADAMS t:estimated=N t:funding_source=FEDERAL t:bill_analyzed=Yes t:development_name=ADAMS t:rc_code=B011800 t:amp=NY005001180P t:meter_amr=NONE t:vendor_name="NEW YORK POWER AUTHORITY" m:days=29 m:consumption_kw=216 m:consumption_kwh=103200 m:edp=248 m:kwh_charges=5919.55 m:kw_charges=2808 m:tds=118
```

## Meta Commands

```ls
metric m:tds p:integer l:"TDS #" d:"TDS (Tenant Data System) number is the unique identifier for all NCYHA developments. It is recommended to use it in order to run analysis by development. The TDS is also the unique link between NYCHA data sets." t:dataTypeName=number

metric m:edp p:integer l:EDP d:"NYCHA Electronic Data Processing. Number used to identify individual NYCHA developments. EDP is used by NYCHA only to link data issued from a different system (the energy management system that was used by NYCHA before 2010). It is recommended to use the TDS # as a unique identifier of each development." t:dataTypeName=number

metric m:days p:integer l:"# days" d:"Number of days on bill" t:dataTypeName=number

metric m:consumption_kwh p:integer l:"Consumption (KWH)" d:"Total KWH consumption" t:dataTypeName=number

metric m:kwh_charges p:double l:"KWH Charges" d:"Total KWH charges" t:dataTypeName=money

metric m:consumption_kw p:float l:"Consumption (KW)" d:"Total KW consumption" t:dataTypeName=number

metric m:kw_charges p:double l:"KW Charges" d:"Total KW charges" t:dataTypeName=money

entity e:jr24-e7cr l:"Electric Consumption And Cost (2010 -  2016)" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/jr24-e7cr

property e:jr24-e7cr t:meta.view v:id=jr24-e7cr v:category="Housing & Development" v:averageRating=0 v:name="Electric Consumption And Cost (2010 -  2016)" v:attribution="New York City Housing Authority (NYCHA)"

property e:jr24-e7cr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jr24-e7cr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| development_name | borough | account_name | location | meter_amr | meter_scope  | tds | edp | rc_code | funding_source | amp          | vendor_name              | umis_bill_id | revenue_month       | service_start_date  | service_end_date    | days | meter_number | estimated | current_charges | rate_class  | bill_analyzed | consumption_kwh | kwh_charges | consumption_kw | kw_charges | other_charges | 
| ================ | ======= | ============ | ======== | ========= | ============ | === | === | ======= | ============== | ============ | ======================== | ============ | =================== | =================== | =================== | ==== | ============ | ========= | =============== | =========== | ============= | =============== | =========== | ============== | ========== | ============= | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1842037      | 2010-01-01T00:00:00 | 2009-12-24T00:00:00 | 2010-01-26T00:00:00 | 33   | 7223256      | N         | $15,396.82      | GOV/NYC/068 | Yes           | 128800          | $7,387.97   | 216            | $2,808.00  | $5,200.85     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1844205      | 2010-02-01T00:00:00 | 2010-01-26T00:00:00 | 2010-02-25T00:00:00 | 30   | 7223256      | N         | $14,556.34      | GOV/NYC/068 | Yes           | 115200          | $6,607.87   | 224            | $2,912.00  | $5,036.47     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1841378      | 2010-03-01T00:00:00 | 2010-02-25T00:00:00 | 2010-03-26T00:00:00 | 29   | 7223256      | N         | $13,904.98      | GOV/NYC/068 | Yes           | 103200          | $5,919.55   | 216            | $2,808.00  | $5,177.43     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1847148      | 2010-04-01T00:00:00 | 2010-03-26T00:00:00 | 2010-04-26T00:00:00 | 31   | 7223256      | N         | $14,764.04      | GOV/NYC/068 | Yes           | 105600          | $6,057.22   | 208            | $2,704.00  | $6,002.82     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1848672      | 2010-05-01T00:00:00 | 2010-04-26T00:00:00 | 2010-05-24T00:00:00 | 28   | 7223256      | N         | $13,729.54      | GOV/NYC/068 | Yes           | 97600           | $5,598.34   | 216            | $2,808.00  | $5,323.20     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1850070      | 2010-06-01T00:00:00 | 2010-05-24T00:00:00 | 2010-06-23T00:00:00 | 30   | 7223256      | N         | $16,689.19      | GOV/NYC/068 | Yes           | 124000          | $7,112.64   | 240            | $3,120.00  | $6,456.55     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1853250      | 2010-07-01T00:00:00 | 2010-06-23T00:00:00 | 2010-07-23T00:00:00 | 30   | 7223256      | N         | $20,563.52      | GOV/NYC/068 | Yes           | 156000          | $8,948.16   | 296            | $3,848.00  | $7,767.36     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1854710      | 2010-08-01T00:00:00 | 2010-07-23T00:00:00 | 2010-08-23T00:00:00 | 31   | 7223256      | N         | $19,675.94      | GOV/NYC/068 | Yes           | 151200          | $8,672.83   | 272            | $3,536.00  | $7,467.11     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1868915      | 2010-09-01T00:00:00 | 2010-08-23T00:00:00 | 2010-09-22T00:00:00 | 30   | 7223256      | N         | $17,716.94      | GOV/NYC/068 | Yes           | 119200          | $6,837.31   | 280            | $3,640.00  | $7,239.63     | 
| ADAMS            | BRONX   | ADAMS        | BLD 05   | NONE      | BLD 01 to 07 | 118 | 248 | B011800 | FEDERAL        | NY005001180P | NEW YORK POWER AUTHORITY | 1856223      | 2010-10-01T00:00:00 | 2010-09-22T00:00:00 | 2010-10-22T00:00:00 | 30   | 7223256      | N         | $14,742.21      | GOV/NYC/068 | Yes           | 103200          | $5,919.55   | 224            | $2,912.00  | $5,910.66     | 
```