# FY15 MMR Data Extract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy-2015-mmr-data-extract) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xn73-3kak) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xn73-3kak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xn73-3kak/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xn73-3kak |
| Name | FY15 MMR Data Extract |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | City Government |
| Created | 2015-09-18T02:48:33Z |
| Publication Date | 2015-09-22T19:17:05Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | agency                 | Agency                 | text      | text        |
| Yes      | series tag     | indicator_name         | Indicator Name         | text      | text        |
| Yes      | numeric metric | indicator_sequence     | Indicator Sequence     | number    | number      |
| Yes      | series tag     | sub_indicator          | Sub-Indicator          | text      | text        |
| Yes      | numeric metric | sub_indicator_sequence | Sub-Indicator Sequence | number    | number      |
| Yes      | series tag     | record_type            | Record Type            | text      | text        |
| Yes      | series tag     | kpsa_id                | KPSA ID                | text      | text        |
| Yes      | series tag     | goal_id                | Goal ID                | text      | text        |
| Yes      | series tag     | desired_direction      | Desired Direction      | text      | text        |
| Yes      | series tag     | critical_flag          | Critical Flag          | text      | text        |
| Yes      | series tag     | geography              | Geography              | text      | text        |
| Yes      | series tag     | measure_type           | Measure Type           | text      | text        |
| Yes      | time           | fiscal_year            | Fiscal Year            | number    | number      |
| Yes      | series tag     | conditional_format     | Conditional Format     | text      | text        |
| Yes      | numeric metric | value                  | Value                  | number    | number      |
| Yes      | series tag     | value_type             | Value Type             | text      | text        |
| Yes      | numeric metric | value_percent          | Value Percent          | percent   | percent     |
| Yes      | series tag     | value_number           | Value Number           | text      | number      |
| Yes      | numeric metric | value_currency         | Value Currency         | money     | money       |
| No       |                | value_time             | Value Time             | text      | text        |
| Yes      | series tag     | value_ratio            | Value Ratio            | text      | text        |
| Yes      | series tag     | indicator_id           | Indicator ID           | text      | text        |
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
series e:xn73-3kak d:2011-01-01T00:00:00.000Z t:value_type=N t:value_number=24.53 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-033SHF4 t:agency=3-1-1 t:kpsa_id=0 m:sub_indicator_sequence=0 m:indicator_sequence=0 m:value=24.5253760129408

series e:xn73-3kak d:2012-01-01T00:00:00.000Z t:value_type=N t:value_number=27.88 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-033SHF4 t:agency=3-1-1 t:kpsa_id=0 m:sub_indicator_sequence=0 m:indicator_sequence=0 m:value=27.8849152510749

series e:xn73-3kak d:2013-01-01T00:00:00.000Z t:value_type=N t:value_number=28.11 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-033SHF4 t:agency=3-1-1 t:kpsa_id=0 m:sub_indicator_sequence=0 m:indicator_sequence=0 m:value=28.1068162926018
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" t:dataTypeName=number

metric m:sub_indicator_sequence p:integer l:"Sub-Indicator Sequence" t:dataTypeName=number

metric m:value p:integer l:Value t:dataTypeName=number

metric m:value_percent p:double l:"Value Percent" t:dataTypeName=percent

metric m:value_currency p:double l:"Value Currency" t:dataTypeName=money

entity e:xn73-3kak l:"FY15 MMR Data Extract" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/xn73-3kak

property e:xn73-3kak t:meta.view v:id=xn73-3kak v:category="City Government" v:averageRating=0 v:name="FY15 MMR Data Extract" v:attribution="Mayor's Office of Operations (OPS)"

property e:xn73-3kak t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xn73-3kak t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | indicator_name                                | indicator_sequence | sub_indicator | sub_indicator_sequence | record_type | kpsa_id | goal_id | desired_direction | critical_flag | geography | measure_type   | fiscal_year | conditional_format | value            | value_type | value_percent | value_number | value_currency | value_time | value_ratio | indicator_id | 
| ====== | ============================================= | ================== | ============= | ====================== | =========== | ======= | ======= | ================= | ============= | ========= | ============== | =========== | ================== | ================ | ========== | ============= | ============ | ============== | ========== | =========== | ============ | 
| 3-1-1  | Caller Hung Up                                | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2011        |                    | 24.5253760129408 | N          |               | 24.53        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up                                | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 27.8849152510749 | N          |               | 27.88        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up                                | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 28.1068162926018 | N          |               | 28.11        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up                                | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2014        |                    | 33.2054537558367 | N          |               | 33.21        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up                                | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2015        |                    | 32.4282999144731 | N          |               | 32.43        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | City Worker or Agency Complaint or Compliment | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2011        |                    | 6.3262719114056  | N          |               | 6.33         |                |            |             | 1-38WD       | 
| 3-1-1  | City Worker or Agency Complaint or Compliment | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 6.77778162791504 | N          |               | 6.78         |                |            |             | 1-38WD       | 
| 3-1-1  | City Worker or Agency Complaint or Compliment | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 6.5039502383642  | N          |               | 6.50         |                |            |             | 1-38WD       | 
| 3-1-1  | City Worker or Agency Complaint or Compliment | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2014        |                    | 7.80180976564719 | N          |               | 7.80         |                |            |             | 1-38WD       | 
| 3-1-1  | City Worker or Agency Complaint or Compliment | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2015        |                    | 8.56257721182172 | N          |               | 8.56         |                |            |             | 1-38WD       | 
```