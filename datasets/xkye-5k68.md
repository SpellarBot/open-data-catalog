# FY14 MMR Data Extract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2014-mmr-data-extract-9c6a8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xkye-5k68) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xkye-5k68/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xkye-5k68/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xkye-5k68 |
| Name | FY14 MMR Data Extract |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | fy2014 mmr data extract, mmr |
| Created | 2014-09-16T14:08:12Z |
| Publication Date | 2014-09-19T14:04:45Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | agency                 | Agency                 | text      | text        |
| Yes      | series tag     | indicator_name         | Indicator Name         | text      | text        |
| Yes      | numeric metric | indicator_sequence     | Indicator Sequence     | number    | number      |
| Yes      | series tag     | sub_indicator          | Sub-Indicator          | text      | text        |
| Yes      | numeric metric | triage                 | Triage                 | number    | number      |
| Yes      | series tag     | record_type            | Record Type            | text      | text        |
| Yes      | series tag     | kpsa_id                | KPSA ID                | text      | number      |
| Yes      | series tag     | goal_id                | Goal ID                | text      | number      |
| Yes      | series tag     | desired_direction      | Desired Direction      | text      | text        |
| Yes      | series tag     | critical_flag          | Critical Flag          | text      | text        |
| Yes      | series tag     | geography              | Geography              | text      | text        |
| Yes      | series tag     | measure_type           | Measure Type           | text      | text        |
| Yes      | time           | fiscal_year            | Fiscal Year            | number    | number      |
| Yes      | series tag     | conditional_formatting | Conditional Formatting | text      | text        |
| Yes      | numeric metric | raw_value              | Raw value              | number    | number      |
| Yes      | series tag     | format_type            | Format Type            | text      | text        |
| Yes      | numeric metric | value_percent_ff       | Value Percent FF       | percent   | percent     |
| Yes      | numeric metric | value_number_ff        | Value Number FF        | number    | number      |
| Yes      | numeric metric | value_currency_ff      | Value Currency FF      | money     | money       |
| Yes      | series tag     | value_time_ff          | Value Time FF          | text      | text        |
| Yes      | series tag     | value_ratio_ff         | Value Ratio FF         | text      | text        |
| Yes      | series tag     | indicator_id           | Indicator ID           | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xkye-5k68 d:2013-01-01T00:00:00.000Z t:geography=NA t:indicator_name="Poll Worker Assistance" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-078QYKV t:format_type=N t:agency=BOE t:kpsa_id=0 m:value_number_ff=2.52 m:raw_value=2.524638365 m:indicator_sequence=0 m:triage=0

series e:xkye-5k68 d:2014-01-01T00:00:00.000Z t:geography=NA t:indicator_name="Poll Worker Assistance" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-078QYKV t:format_type=N t:agency=BOE t:kpsa_id=0 m:value_number_ff=3.57 m:raw_value=3.566171832 m:indicator_sequence=0 m:triage=0

series e:xkye-5k68 d:2010-01-01T00:00:00.000Z t:geography=NA t:indicator_name="Division Information Provided" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-03KKXTU t:format_type=N t:agency=BPL t:kpsa_id=0 m:value_number_ff=12.8 m:raw_value=12.79789335 m:indicator_sequence=0 m:triage=0
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" t:dataTypeName=number

metric m:triage p:integer l:Triage t:dataTypeName=number

metric m:raw_value p:double l:"Raw value" t:dataTypeName=number

metric m:value_percent_ff p:float l:"Value Percent FF" t:dataTypeName=percent

metric m:value_number_ff p:integer l:"Value Number FF" t:dataTypeName=number

metric m:value_currency_ff p:double l:"Value Currency FF" t:dataTypeName=money

entity e:xkye-5k68 l:"FY14 MMR Data Extract" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/xkye-5k68

property e:xkye-5k68 t:meta.view v:id=xkye-5k68 v:category="City Government" v:averageRating=0 v:name="FY14 MMR Data Extract" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:xkye-5k68 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xkye-5k68 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | indicator_name                                           | indicator_sequence | sub_indicator | triage | record_type | kpsa_id | goal_id | desired_direction | critical_flag | geography | measure_type   | fiscal_year | conditional_formatting | raw_value   | format_type | value_percent_ff | value_number_ff | value_currency_ff | value_time_ff | value_ratio_ff | indicator_id | 
| ====== | ======================================================== | ================== | ============= | ====== | =========== | ======= | ======= | ================= | ============= | ========= | ============== | =========== | ====================== | =========== | =========== | ================ | =============== | ================= | ============= | ============== | ============ | 
| BOE    | Poll Worker Assistance                                   | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2013        |                        | 2.524638365 | N           |                  | 2.52            |                   |               |                | 1-1-078QYKV  | 
| BOE    | Poll Worker Assistance                                   | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2014        |                        | 3.566171832 | N           |                  | 3.57            |                   |               |                | 1-1-078QYKV  | 
| BPL    | Division Information Provided                            | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2010        |                        | 12.79789335 | N           |                  | 12.8            |                   |               |                | 1-1-03KKXTU  | 
| BPL    | Division Information Provided                            | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2011        |                        | 14.28137805 | N           |                  | 14.28           |                   |               |                | 1-1-03KKXTU  | 
| BPL    | Division Information Provided                            | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2012        |                        | 14.38356164 | N           |                  | 14.38           |                   |               |                | 1-1-03KKXTU  | 
| BPL    | Division Information Provided                            | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2013        |                        | 13.16931983 | N           |                  | 13.17           |                   |               |                | 1-1-03KKXTU  | 
| BPL    | Division Information Provided                            | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2014        |                        | 13.51351351 | N           |                  | 13.51           |                   |               |                | 1-1-03KKXTU  | 
| BPL    | Division Referral                                        | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2010        |                        | 1.843317972 | N           |                  | 1.84            |                   |               |                | 1-1-03KKXU4  | 
| BPL    | Elementary School Student After School Program - Drop-In | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2010        |                        | 2.580645161 | N           |                  | 2.58            |                   |               |                | 1-1-034YZM2  | 
| BPL    | Elementary School Student After School Program - Drop-In | 0                  |               | 0      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2011        |                        | 2.048869328 | N           |                  | 2.05            |                   |               |                | 1-1-034YZM2  | 
```