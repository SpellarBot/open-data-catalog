# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY04

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-fy04) |
| Metadata | [Link](https://data.ct.gov/api/views/g9s8-wdcq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/g9s8-wdcq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/g9s8-wdcq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | g9s8-wdcq |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY04 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:46:34Z |
| Publication Date | 2015-05-06T18:10:21Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN						
STATE FISCAL YEAR 2004  (Revised 5/05)																									
* Due to rounding some towns may not display a case but will display recipients.  This is due to most cases having more than one recipient and therefore when averaged, the recipient count will be .5 or higher, and be counted as 1.	
Note: Due to rounding, program and statewide totals may appear inaccurate.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | town_code                 | Town Code                 | text      | number      |
| Yes      | series tag     | town_name                 | Town Name                 | text      | text        |
| Yes      | numeric metric | snap_cases                | SNAP Cases                | number    | number      |
| Yes      | numeric metric | snap_recipients           | SNAP Recipients           | number    | number      |
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
series e:g9s8-wdcq d:2015-04-29T10:46:42.000Z t:town_code=1 t:town_name=Andover m:tfa_two_parent_cases=0 m:tfa_regular_cases=5 m:snap_cases=9 m:snap_recipients=18 m:saga_cash_cases=0 m:tfa_regular_recipients=10 m:saga_med_cases=3 m:tfa_total_cases=5 m:saga_cash_recipients=0 m:saga_med_recipients=3 m:state_supplement_disabled=6 m:tfa_two_parent_recipients=3 m:state_supplement_aged=2 m:total_medicaid_cases=74 m:tfa_total_recipients=13 m:state_supplement_total=8 m:total_medicaid_recipients=137

series e:g9s8-wdcq d:2015-04-29T10:46:42.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=10 m:tfa_regular_cases=184 m:snap_cases=693 m:snap_recipients=1433 m:saga_cash_cases=34 m:tfa_regular_recipients=436 m:saga_med_cases=154 m:tfa_total_cases=194 m:saga_cash_recipients=34 m:saga_med_recipients=154 m:state_supplement_disabled=53 m:tfa_two_parent_recipients=36 m:state_supplement_aged=15 m:total_medicaid_cases=1562 m:tfa_total_recipients=472 m:state_supplement_total=69 m:total_medicaid_recipients=2977

series e:g9s8-wdcq d:2015-04-29T10:46:42.000Z t:town_code=3 t:town_name=Ashford m:tfa_two_parent_cases=0 m:tfa_regular_cases=12 m:snap_cases=48 m:snap_recipients=95 m:saga_cash_cases=1 m:tfa_regular_recipients=26 m:saga_med_cases=12 m:tfa_total_cases=12 m:saga_cash_recipients=1 m:saga_med_recipients=12 m:state_supplement_disabled=14 m:tfa_two_parent_recipients=1 m:state_supplement_aged=11 m:total_medicaid_cases=217 m:tfa_total_recipients=27 m:state_supplement_total=25 m:total_medicaid_recipients=427
```

## Meta Commands

```ls
metric m:snap_cases p:integer l:"SNAP Cases" t:dataTypeName=number

metric m:snap_recipients p:integer l:"SNAP Recipients" t:dataTypeName=number

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

entity e:g9s8-wdcq l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY04" t:url=https://data.ct.gov/api/views/g9s8-wdcq

property e:g9s8-wdcq t:meta.view v:id=g9s8-wdcq v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY04"

property e:g9s8-wdcq t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:g9s8-wdcq t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1430304402  | 1         | Andover      | 9          | 18              | 5                 | 10                     | 0                    | 3                         | 5               | 13                   | 2                     |                        | 6                         | 8                      | 74                   | 137                       | 0               | 0                    | 3              | 3                   | 
| 1430304402  | 2         | Ansonia      | 693        | 1433            | 184               | 436                    | 10                   | 36                        | 194             | 472                  | 15                    |                        | 53                        | 69                     | 1562                 | 2977                      | 34              | 34                   | 154            | 154                 | 
| 1430304402  | 3         | Ashford      | 48         | 95              | 12                | 26                     | 0                    | 1                         | 12              | 27                   | 11                    |                        | 14                        | 25                     | 217                  | 427                       | 1               | 1                    | 12             | 12                  | 
| 1430304402  | 4         | Avon         | 37         | 57              | 6                 | 11                     |                      |                           | 6               | 11                   | 7                     |                        | 13                        | 21                     | 253                  | 378                       | 5               | 5                    | 20             | 20                  | 
| 1430304402  | 5         | Barkhamsted  | 16         | 36              | 6                 | 11                     |                      |                           | 6               | 11                   |                       |                        | 2                         | 2                      | 94                   | 188                       | 0               | 0                    | 9              | 9                   | 
| 1430304402  | 6         | Beacon Falls | 40         | 62              | 8                 | 17                     |                      | 2                         | 8               | 19                   | 2                     |                        | 6                         | 8                      | 138                  | 270                       | 2               | 2                    | 18             | 18                  | 
| 1430304402  | 7         | Berlin       | 95         | 142             | 18                | 35                     | 1                    | 3                         | 19              | 38                   | 30                    |                        | 39                        | 69                     | 432                  | 745                       | 7               | 7                    | 40             | 40                  | 
| 1430304402  | 8         | Bethany      | 13         | 19              | 3                 | 7                      |                      |                           | 3               | 7                    | 1                     |                        | 9                         | 10                     | 83                   | 152                       | 0               | 0                    | 13             | 13                  | 
| 1430304402  | 9         | Bethel       | 111        | 174             | 12                | 22                     |                      | 1                         | 12              | 23                   | 6                     |                        | 16                        | 23                     | 580                  | 958                       | 10              | 10                   | 36             | 36                  | 
| 1430304402  | 10        | Bethlehem    | 18         | 28              | 2                 | 2                      |                      |                           | 2               | 2                    |                       |                        | 4                         | 5                      | 100                  | 187                       | 0               | 0                    | 3              | 3                   | 
```