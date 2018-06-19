# PMMR 2014 Raw Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pmmr-2014-raw-data-64224) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vuae-w6cg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vuae-w6cg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vuae-w6cg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vuae-w6cg |
| Name | PMMR 2014 Raw Data |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | pmmer 2014 raw data, pmmr |
| Created | 2014-02-20T18:40:59Z |
| Publication Date | 2014-02-21T23:31:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | agency                | Agency                | text      | text        |
| Yes      | series tag     | indicator_id          | Indicator ID          | text      | text        |
| Yes      | series tag     | indicator_name        | Indicator Name        | text      | text        |
| Yes      | numeric metric | indicator_sequence    | Indicator Sequence    | number    | number      |
| Yes      | series tag     | sub_indicator         | Sub-Indicator         | text      | text        |
| Yes      | numeric metric | subindicator_sequence | Subindicator Sequence | number    | number      |
| Yes      | series tag     | record_type           | Record Type           | text      | text        |
| Yes      | series tag     | desired_direction     | Desired Direction     | text      | text        |
| Yes      | series tag     | critical_flag         | Critical Flag         | text      | text        |
| Yes      | series tag     | geography             | Geography             | text      | text        |
| Yes      | series tag     | measure_type          | Measure Type          | text      | text        |
| Yes      | time           | fiscal_year           | Fiscal Year           | number    | number      |
| Yes      | series tag     | conditional_format    | Conditional Format    | text      | text        |
| Yes      | numeric metric | raw_value             | Raw Value             | number    | number      |
| Yes      | series tag     | format_type           | Format Type           | text      | text        |
| Yes      | numeric metric | value_percent         | Value Percent         | percent   | percent     |
| Yes      | series tag     | value_number          | Value Number          | text      | number      |
| Yes      | numeric metric | value_currency        | Value Currency        | money     | money       |
| No       |                | value_time            | Value Time            | text      | text        |
| Yes      | series tag     | value_ratio           | Value Ratio           | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = value_time
```

## Data Commands

```ls
series e:vuae-w6cg d:2013-01-01T00:00:00.000Z t:value_number=6371 t:geography=Citywide t:indicator_name="311 calls (000)" t:measure_type=PMMR t:critical_flag=Y t:record_type=CSv t:desired_direction=Neutral t:format_type=N t:indicator_id=265 t:sub_indicator="311 calls (000)" t:agency=311 m:subindicator_sequence=0 m:raw_value=6371 m:indicator_sequence=1

series e:vuae-w6cg d:2014-01-01T00:00:00.000Z t:value_number=5881 t:geography=Citywide t:indicator_name="311 calls (000)" t:measure_type=PMMR t:critical_flag=Y t:record_type=CSv t:desired_direction=Neutral t:format_type=N t:indicator_id=265 t:sub_indicator="311 calls (000)" t:agency=311 m:subindicator_sequence=0 m:raw_value=5880.67 m:indicator_sequence=1

series e:vuae-w6cg d:2013-01-01T00:00:00.000Z t:value_number=19917 t:geography=Citywide t:indicator_name="311 calls (000)" t:critical_flag=Y t:record_type=CSv t:desired_direction=Neutral t:format_type=N t:indicator_id=265 t:sub_indicator="311 calls (000)" t:agency=311 m:subindicator_sequence=0 m:raw_value=19917 m:indicator_sequence=1
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" t:dataTypeName=number

metric m:subindicator_sequence p:integer l:"Subindicator Sequence" t:dataTypeName=number

metric m:raw_value p:double l:"Raw Value" t:dataTypeName=number

metric m:value_percent p:double l:"Value Percent" t:dataTypeName=percent

metric m:value_currency p:integer l:"Value Currency" t:dataTypeName=money

entity e:vuae-w6cg l:"PMMR 2014 Raw Data" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/vuae-w6cg

property e:vuae-w6cg t:meta.view v:id=vuae-w6cg v:category="City Government" v:averageRating=0 v:name="PMMR 2014 Raw Data" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:vuae-w6cg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vuae-w6cg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | indicator_id | indicator_name                                              | indicator_sequence | sub_indicator                                               | subindicator_sequence | record_type | desired_direction | critical_flag | geography | measure_type | fiscal_year | conditional_format | raw_value | format_type | value_percent | value_number | value_currency | value_time | value_ratio | 
| ====== | ============ | =========================================================== | ================== | =========================================================== | ===================== | =========== | ================= | ============= | ========= | ============ | =========== | ================== | ========= | =========== | ============= | ============ | ============== | ========== | =========== | 
| 311    | 265          | 311 calls (000)                                             | 1                  | 311 calls (000)                                             | 0                     | CSv         | Neutral           | Y             | Citywide  | PMMR         | 2013        |                    | 6371      | N           |               | 6371         |                |            |             | 
| 311    | 265          | 311 calls (000)                                             | 1                  | 311 calls (000)                                             | 0                     | CSv         | Neutral           | Y             | Citywide  | PMMR         | 2014        |                    | 5880.67   | N           |               | 5881         |                |            |             | 
| 311    | 265          | 311 calls (000)                                             | 1                  | 311 calls (000)                                             | 0                     | CSv         | Neutral           | Y             | Citywide  |              | 2013        |                    | 19917     | N           |               | 19917        |                |            |             | 
| 311    | 265          | 311 calls (000)                                             | 1                  | 311 calls (000)                                             | 0                     | CSv         | Neutral           | Y             | Citywide  |              | 2012        |                    | 18957     | N           |               | 18957        |                |            |             | 
| 311    | 265          | 311 calls (000)                                             | 1                  | 311 calls (000)                                             | 0                     | CSv         | Neutral           | Y             | Citywide  |              | 2011        |                    | 21730     | N           |               | 21730        |                |            |             | 
| HPD    | 6341         | Agency customers surveyed for overall customer satisfaction | 7                  | Agency customers surveyed for overall customer satisfaction | 0                     | CSv         | Up                | N             | Citywide  | PMMR         | 2014        |                    |           | N           |               |              |                |            |             | 
| HPD    | 6341         | Agency customers surveyed for overall customer satisfaction | 7                  | Agency customers surveyed for overall customer satisfaction | 0                     | CSv         | Up                | N             | Citywide  | PMMR         | 2013        |                    |           | N           |               |              |                |            |             | 
| DEP    | 5901         | Agency customers surveyed for overall customer satisfaction | 11                 | Agency customers surveyed for overall customer satisfaction | 0                     | CSv         | Up                | N             | Citywide  |              | 2011        |                    | 814       | N           |               | 814          |                |            |             | 
| DEP    | 5901         | Agency customers surveyed for overall customer satisfaction | 11                 | Agency customers surveyed for overall customer satisfaction | 0                     | CSv         | Up                | N             | Citywide  |              | 2012        |                    | 2205      | N           |               | 2205         |                |            |             | 
| DEP    | 5901         | Agency customers surveyed for overall customer satisfaction | 11                 | Agency customers surveyed for overall customer satisfaction | 0                     | CSv         | Up                | N             | Citywide  |              | 2013        |                    | 5655      | N           |               | 5655         |                |            |             | 
```