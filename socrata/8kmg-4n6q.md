# Monthly Recipients Assistance Units FY02

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-recipients-assistance-units-fy02) |
| Metadata | [Link](https://data.ct.gov/api/views/8kmg-4n6q) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/8kmg-4n6q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/8kmg-4n6q/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 8kmg-4n6q |
| Name | Monthly Recipients Assistance Units FY02 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:55:28Z |
| Publication Date | 2015-05-07T17:12:33Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2002 * Counts are estimated due to AU/recipient address correction. Figures may not add due to rounding.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | town_code                 | Town Code                 | text      | number      |
| Yes      | series tag     | town_name                 | Town Name                 | text      | text        |
| Yes      | numeric metric | snap_recipients           | SNAP Recipients           | number    | number      |
| Yes      | numeric metric | snap_cases                | SNAP Cases                | number    | number      |
| Yes      | numeric metric | tfa_regular_cases         | TFA-Regular Cases         | number    | number      |
| Yes      | numeric metric | tfa_regular_recipients    | TFA-Regular Recipients    | number    | number      |
| Yes      | numeric metric | tfa_two_parent_cases      | TFA-Two Parent Cases      | number    | number      |
| Yes      | numeric metric | tfa_two_parent_recipients | TFA-Two Parent Recipients | number    | number      |
| Yes      | numeric metric | tfa_total_cases           | TFA-Total Cases           | number    | number      |
| Yes      | numeric metric | tfa_total_recipients      | TFA-Total Recipients      | number    | number      |
| Yes      | numeric metric | state_supplement_aged     | State Supplement-Aged     | number    | number      |
| Yes      | numeric metric | state_supplement_blind    | State Supplement-Blind    | number    | number      |
| Yes      | numeric metric | state_supplement_disabled | State Supplement-Disabled | number    | number      |
| Yes      | numeric metric | state_supplement_total    | State Supplement-Total    | number    | number      |
| Yes      | numeric metric | total_medicaid_cases      | Total Medicaid Cases      | number    | number      |
| Yes      | numeric metric | total_medicaid_recipients | Total Medicaid Recipients | number    | number      |
| Yes      | numeric metric | saga_cash_cases           | SAGA-Cash Cases           | number    | number      |
| Yes      | numeric metric | saga_cash_recipients      | SAGA-Cash Recipients      | number    | number      |
| Yes      | numeric metric | saga_med_cases            | SAGA-Med Cases            | number    | number      |
| Yes      | numeric metric | saga_med_recipients       | SAGA-Med Recipients       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8kmg-4n6q d:2015-04-29T10:55:35.000Z t:town_code=1 t:town_name=Andover m:tfa_regular_cases=4 m:snap_cases=6 m:snap_recipients=10 m:tfa_regular_recipients=7 m:saga_med_cases=4 m:tfa_total_cases=4 m:saga_med_recipients=4 m:state_supplement_disabled=9 m:state_supplement_aged=2 m:total_medicaid_cases=62 m:tfa_total_recipients=7 m:state_supplement_total=11 m:total_medicaid_recipients=97

series e:8kmg-4n6q d:2015-04-29T10:55:35.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=6 m:tfa_regular_cases=186 m:snap_cases=631 m:snap_recipients=1259 m:saga_cash_cases=39 m:tfa_regular_recipients=424 m:saga_med_cases=152 m:tfa_total_cases=192 m:saga_cash_recipients=39 m:saga_med_recipients=152 m:state_supplement_disabled=60 m:tfa_two_parent_recipients=28 m:state_supplement_aged=19 m:total_medicaid_cases=1446 m:tfa_total_recipients=452 m:state_supplement_total=79 m:total_medicaid_recipients=2610

series e:8kmg-4n6q d:2015-04-29T10:55:35.000Z t:town_code=3 t:town_name=Ashford m:tfa_regular_cases=13 m:snap_cases=37 m:snap_recipients=75 m:saga_cash_cases=1 m:tfa_regular_recipients=26 m:saga_med_cases=7 m:tfa_total_cases=13 m:saga_cash_recipients=1 m:saga_med_recipients=7 m:state_supplement_disabled=10 m:state_supplement_aged=12 m:state_supplement_blind=0 m:total_medicaid_cases=169 m:tfa_total_recipients=26 m:state_supplement_total=22 m:total_medicaid_recipients=312
```

## Meta Commands

```ls
metric m:snap_recipients p:integer l:"SNAP Recipients" t:dataTypeName=number

metric m:snap_cases p:integer l:"SNAP Cases" t:dataTypeName=number

metric m:tfa_regular_cases p:integer l:"TFA-Regular Cases" t:dataTypeName=number

metric m:tfa_regular_recipients p:integer l:"TFA-Regular Recipients" t:dataTypeName=number

metric m:tfa_two_parent_cases p:integer l:"TFA-Two Parent Cases" t:dataTypeName=number

metric m:tfa_two_parent_recipients p:integer l:"TFA-Two Parent Recipients" t:dataTypeName=number

metric m:tfa_total_cases p:integer l:"TFA-Total Cases" t:dataTypeName=number

metric m:tfa_total_recipients p:integer l:"TFA-Total Recipients" t:dataTypeName=number

metric m:state_supplement_aged p:integer l:"State Supplement-Aged" t:dataTypeName=number

metric m:state_supplement_blind p:integer l:"State Supplement-Blind" t:dataTypeName=number

metric m:state_supplement_disabled p:integer l:"State Supplement-Disabled" t:dataTypeName=number

metric m:state_supplement_total p:integer l:"State Supplement-Total" t:dataTypeName=number

metric m:total_medicaid_cases p:integer l:"Total Medicaid Cases" t:dataTypeName=number

metric m:total_medicaid_recipients p:integer l:"Total Medicaid Recipients" t:dataTypeName=number

metric m:saga_cash_cases p:integer l:"SAGA-Cash Cases" t:dataTypeName=number

metric m:saga_cash_recipients p:integer l:"SAGA-Cash Recipients" t:dataTypeName=number

metric m:saga_med_cases p:integer l:"SAGA-Med Cases" t:dataTypeName=number

metric m:saga_med_recipients p:integer l:"SAGA-Med Recipients" t:dataTypeName=number

entity e:8kmg-4n6q l:"Monthly Recipients Assistance Units FY02" t:url=https://data.ct.gov/api/views/8kmg-4n6q

property e:8kmg-4n6q t:meta.view v:id=8kmg-4n6q v:category="Health and Human Services" v:averageRating=0 v:name="Monthly Recipients Assistance Units FY02"

property e:8kmg-4n6q t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:8kmg-4n6q t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_recipients | snap_cases | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| =========== | ========= | ============ | =============== | ========== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1430304935  | 1         | Andover      | 10              | 6          | 4                 | 7                      |                      |                           | 4               | 7                    | 2                     |                        | 9                         | 11                     | 62                   | 97                        |                 |                      | 4              | 4                   | 
| 1430304935  | 2         | Ansonia      | 1259            | 631        | 186               | 424                    | 6                    | 28                        | 192             | 452                  | 19                    |                        | 60                        | 79                     | 1446                 | 2610                      | 39              | 39                   | 152            | 152                 | 
| 1430304935  | 3         | Ashford      | 75              | 37         | 13                | 26                     |                      |                           | 13              | 26                   | 12                    | 0                      | 10                        | 22                     | 169                  | 312                       | 1               | 1                    | 7              | 7                   | 
| 1430304935  | 4         | Avon         | 42              | 26         | 3                 | 5                      |                      |                           | 3               | 5                    | 9                     |                        | 14                        | 23                     | 217                  | 273                       | 3               | 3                    | 19             | 19                  | 
| 1430304935  | 5         | Barkhamsted  | 36              | 13         | 6                 | 14                     |                      |                           | 6               | 14                   |                       | 0                      | 2                         | 2                      | 79                   | 163                       | 1               | 1                    | 4              | 4                   | 
| 1430304935  | 6         | Beacon Falls | 49              | 29         | 7                 | 12                     |                      |                           | 7               | 12                   | 2                     |                        | 8                         | 10                     | 122                  | 204                       | 1               | 1                    | 12             | 12                  | 
| 1430304935  | 7         | Berlin       | 117             | 85         | 20                | 37                     | 1                    | 4                         | 21              | 41                   | 31                    |                        | 42                        | 74                     | 383                  | 590                       | 10              | 10                   | 37             | 37                  | 
| 1430304935  | 8         | Bethany      | 25              | 12         | 4                 | 9                      |                      |                           | 4               | 9                    | 1                     |                        | 8                         | 9                      | 78                   | 129                       | 1               | 3                    | 6              | 6                   | 
| 1430304935  | 9         | Bethel       | 134             | 92         | 20                | 37                     |                      | 1                         | 20              | 38                   | 14                    |                        | 17                        | 31                     | 485                  | 746                       | 7               | 7                    | 30             | 30                  | 
| 1430304935  | 10        | Bethlehem    | 18              | 12         | 2                 | 2                      |                      | 2                         | 2               | 4                    | 1                     |                        | 3                         | 4                      | 77                   | 129                       | 1               | 1                    | 4              | 4                   | 
```