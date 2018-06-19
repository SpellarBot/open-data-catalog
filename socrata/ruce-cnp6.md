# PMMR FY 2015 Data Extract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pmmr-fy-2015-data-extract) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ruce-cnp6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ruce-cnp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ruce-cnp6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ruce-cnp6 |
| Name | PMMR FY 2015 Data Extract |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Created | 2015-02-25T03:18:50Z |
| Publication Date | 2015-02-28T02:45:35Z |

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
| Yes      | numeric metric | service_sequence      | Service Sequence      | number    | number      |
| Yes      | series tag     | goal_sequence         | Goal Sequence         | text      | text        |
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
series e:ruce-cnp6 d:2014-01-01T00:00:00.000Z t:value_number=29.58 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:format_type=N t:indicator_id=1-1-033SHF4 t:agency=3-1-1 m:subindicator_sequence=0 m:raw_value=29.5782257992691 m:indicator_sequence=0

series e:ruce-cnp6 d:2015-01-01T00:00:00.000Z t:value_number=34.80 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:format_type=N t:indicator_id=1-1-033SHF4 t:agency=3-1-1 m:subindicator_sequence=0 m:raw_value=34.7959424392545 m:indicator_sequence=0

series e:ruce-cnp6 d:2014-01-01T00:00:00.000Z t:value_number=1 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type=Rank t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:format_type=N t:indicator_id=1-1-033SHF4 t:agency=3-1-1 m:subindicator_sequence=0 m:raw_value=1 m:indicator_sequence=0
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" t:dataTypeName=number

metric m:subindicator_sequence p:integer l:"Subindicator Sequence" t:dataTypeName=number

metric m:raw_value p:double l:"Raw Value" t:dataTypeName=number

metric m:value_percent p:float l:"Value Percent" t:dataTypeName=percent

metric m:value_currency p:double l:"Value Currency" t:dataTypeName=money

metric m:service_sequence p:integer l:"Service Sequence" t:dataTypeName=number

entity e:ruce-cnp6 l:"PMMR FY 2015 Data Extract" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/ruce-cnp6

property e:ruce-cnp6 t:meta.view v:id=ruce-cnp6 v:category="City Government" v:averageRating=0 v:name="PMMR FY 2015 Data Extract" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:ruce-cnp6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ruce-cnp6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | indicator_id | indicator_name              | indicator_sequence | sub_indicator | subindicator_sequence | record_type | desired_direction | critical_flag | geography | measure_type   | fiscal_year | conditional_format | raw_value        | format_type | value_percent | value_number | value_currency | value_time | value_ratio | service_sequence | goal_sequence | 
| ====== | ============ | =========================== | ================== | ============= | ===================== | =========== | ================= | ============= | ========= | ============== | =========== | ================== | ================ | =========== | ============= | ============ | ============== | ========== | =========== | ================ | ============= | 
| 3-1-1  | 1-1-033SHF4  | Caller Hung Up              | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2014        |                    | 29.5782257992691 | N           |               | 29.58        |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHF4  | Caller Hung Up              | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2015        |                    | 34.7959424392545 | N           |               | 34.80        |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHF4  | Caller Hung Up              | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | Rank           | 2014        |                    | 1                | N           |               | 1            |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHF4  | Caller Hung Up              | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | Rank           | 2015        |                    | 1                | N           |               | 1            |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHF4  | Caller Hung Up              | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | Total          | 2014        |                    | 99631            | N           |               | 99631        |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHF4  | Caller Hung Up              | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | Total          | 2015        |                    | 113575           | N           |               | 113575       |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHFO  | Outside of 311 Jurisdiction | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2014        |                    | 6.01563358162208 | N           |               | 6.02         |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHFO  | Outside of 311 Jurisdiction | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2015        |                    | 6.54221928107278 | N           |               | 6.54         |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHFO  | Outside of 311 Jurisdiction | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | Rank           | 2014        |                    | 5                | N           |               | 5            |                |            |             |                  |               | 
| 3-1-1  | 1-1-033SHFO  | Outside of 311 Jurisdiction | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | Rank           | 2015        |                    | 5                | N           |               | 5            |                |            |             |                  |               | 
```