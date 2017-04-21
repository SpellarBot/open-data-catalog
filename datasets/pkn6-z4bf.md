# FY16 MMR Data Extract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy-2016-mmr-data-extract) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pkn6-z4bf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pkn6-z4bf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pkn6-z4bf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pkn6-z4bf |
| Name | FY16 MMR Data Extract |
| Category | City Government |
| Created | 2016-09-19T14:45:58Z |
| Publication Date | 2016-09-24T00:11:44Z |

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
series e:pkn6-z4bf d:2012-01-01T00:00:00.000Z t:value_type=N t:value_number=27.88 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-033SHF4 t:agency=3-1-1 t:kpsa_id=0 m:sub_indicator_sequence=0 m:indicator_sequence=0 m:value=27.8849152510749

series e:pkn6-z4bf d:2013-01-01T00:00:00.000Z t:value_type=N t:value_number=28.11 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-033SHF4 t:agency=3-1-1 t:kpsa_id=0 m:sub_indicator_sequence=0 m:indicator_sequence=0 m:value=28.1068162926018

series e:pkn6-z4bf d:2014-01-01T00:00:00.000Z t:value_type=N t:value_number=33.21 t:geography=NA t:indicator_name="Caller Hung Up" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:goal_id=0 t:indicator_id=1-1-033SHF4 t:agency=3-1-1 t:kpsa_id=0 m:sub_indicator_sequence=0 m:indicator_sequence=0 m:value=33.2054537558367
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" t:dataTypeName=number

metric m:sub_indicator_sequence p:integer l:"Sub-Indicator Sequence" t:dataTypeName=number

metric m:value p:double l:Value t:dataTypeName=number

metric m:value_percent p:double l:"Value Percent" t:dataTypeName=percent

metric m:value_currency p:double l:"Value Currency" t:dataTypeName=money

entity e:pkn6-z4bf l:"FY16 MMR Data Extract" t:url=https://data.cityofnewyork.us/api/views/pkn6-z4bf

property e:pkn6-z4bf t:meta.view v:id=pkn6-z4bf v:category="City Government" v:averageRating=0 v:name="FY16 MMR Data Extract"

property e:pkn6-z4bf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pkn6-z4bf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | indicator_name | indicator_sequence | sub_indicator | sub_indicator_sequence | record_type | kpsa_id | goal_id | desired_direction | critical_flag | geography | measure_type   | fiscal_year | conditional_format | value            | value_type | value_percent | value_number | value_currency | value_time | value_ratio | indicator_id | 
| ====== | ============== | ================== | ============= | ====================== | =========== | ======= | ======= | ================= | ============= | ========= | ============== | =========== | ================== | ================ | ========== | ============= | ============ | ============== | ========== | =========== | ============ | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 27.8849152510749 | N          |               | 27.88        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 28.1068162926018 | N          |               | 28.11        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2014        |                    | 33.2054537558367 | N          |               | 33.21        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2015        |                    | 32.4282999144731 | N          |               | 32.43        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | % of Inquiries | 2016        |                    | 29.7541165685824 | N          |               | 29.75        |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | Rank           | 2012        |                    | 1                | N          |               | 1            |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | Rank           | 2013        |                    | 1                | N          |               | 1            |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | Rank           | 2014        |                    | 1                | N          |               | 1            |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | Rank           | 2015        |                    | 1                | N          |               | 1            |                |            |             | 1-1-033SHF4  | 
| 3-1-1  | Caller Hung Up | 0                  |               | 0                      | INQ         | 0       | 0       | NA                | NA            | NA        | Rank           | 2016        |                    | 1                | N          |               | 1            |                |            |             | 1-1-033SHF4  | 
```