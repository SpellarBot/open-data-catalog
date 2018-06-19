# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-state-fiscal-year-2008) |
| Metadata | [Link](https://data.ct.gov/api/views/c9fg-6zhq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/c9fg-6zhq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/c9fg-6zhq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | c9fg-6zhq |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2008 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:21:49Z |
| Publication Date | 2015-05-06T14:38:52Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN						
STATE FISCAL YEAR 2008							
* Due to rounding some towns may not display a case but will display recipients.  This is due to most cases having more than one recipient and therefore when averaged, the recipient count will be .5 or higher, and be counted as 1.	
Note: Due to rounding, program and statewide totals may appear inaccurate.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | town_code                 | Town Code                 | text      | number      |
| Yes      | series tag     | town_name                 | Town Name                 | text      | text        |
| Yes      | numeric metric | snap_cases                | SNAP Cases                | number    | number      |
| Yes      | numeric metric | snap_recipients           | SNAP Recipients           | number    | number      |
| Yes      | numeric metric | tfa_regular_cases         | TFA-Regular Cases         | number    | number      |
| Yes      | numeric metric | tfa_regular_recipients    | TFA-Regular Recipients    | number    | number      |
| Yes      | numeric metric | tfa_two_parent_cases      | TFA-Two Parent Cases      | number    | text        |
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
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c9fg-6zhq d:2008-01-01T00:00:00.000Z t:town_code=1 t:town_name=Andover m:tfa_regular_cases=1 m:snap_cases=15 m:snap_recipients=34 m:tfa_regular_recipients=3 m:saga_med_cases=5 m:tfa_total_cases=1 m:saga_med_recipients=5 m:state_supplement_disabled=4 m:state_supplement_aged=1 m:total_medicaid_cases=76 m:tfa_total_recipients=3 m:state_supplement_total=6 m:total_medicaid_recipients=157

series e:c9fg-6zhq d:2008-01-01T00:00:00.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=7 m:tfa_regular_cases=149 m:snap_cases=788 m:snap_recipients=1702 m:saga_cash_cases=27 m:tfa_regular_recipients=324 m:saga_med_cases=186 m:tfa_total_cases=156 m:saga_cash_recipients=27 m:saga_med_recipients=186 m:state_supplement_disabled=42 m:tfa_two_parent_recipients=28 m:state_supplement_aged=16 m:total_medicaid_cases=1695 m:tfa_total_recipients=352 m:state_supplement_total=59 m:total_medicaid_recipients=3276

series e:c9fg-6zhq d:2008-01-01T00:00:00.000Z t:town_code=3 t:town_name=Ashford m:tfa_two_parent_cases=1 m:tfa_regular_cases=9 m:snap_cases=53 m:snap_recipients=99 m:saga_cash_cases=5 m:tfa_regular_recipients=21 m:saga_med_cases=19 m:tfa_total_cases=10 m:saga_cash_recipients=5 m:saga_med_recipients=19 m:state_supplement_disabled=14 m:tfa_two_parent_recipients=4 m:state_supplement_aged=9 m:total_medicaid_cases=186 m:tfa_total_recipients=25 m:state_supplement_total=23 m:total_medicaid_recipients=370
```

## Meta Commands

```ls
metric m:snap_cases p:integer l:"SNAP Cases" t:dataTypeName=number

metric m:snap_recipients p:integer l:"SNAP Recipients" t:dataTypeName=number

metric m:tfa_regular_cases p:integer l:"TFA-Regular Cases" t:dataTypeName=number

metric m:tfa_regular_recipients p:integer l:"TFA-Regular Recipients" t:dataTypeName=number

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

entity e:c9fg-6zhq l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2008" t:url=https://data.ct.gov/api/views/c9fg-6zhq

property e:c9fg-6zhq t:meta.view v:id=c9fg-6zhq v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2008"

property e:c9fg-6zhq t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:c9fg-6zhq t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1         | Andover      | 15         | 34              | 1                 | 3                      |                      |                           | 1               | 3                    | 1                     |                        | 4                         | 6                      | 76                   | 157                       |                 |                      | 5              | 5                   | 
| 2         | Ansonia      | 788        | 1702            | 149               | 324                    | 7                    | 28                        | 156             | 352                  | 16                    |                        | 42                        | 59                     | 1695                 | 3276                      | 27              | 27                   | 186            | 186                 | 
| 3         | Ashford      | 53         | 99              | 9                 | 21                     | 1                    | 4                         | 10              | 25                   | 9                     |                        | 14                        | 23                     | 186                  | 370                       | 5               | 5                    | 19             | 19                  | 
| 4         | Avon         | 45         | 75              | 5                 | 11                     |                      |                           | 5               | 11                   | 7                     |                        | 8                         | 16                     | 297                  | 434                       | 2               | 2                    | 12             | 12                  | 
| 5         | Barkhamsted  | 15         | 31              | 4                 | 7                      | *                    | 1                         | 4               | 8                    |                       |                        | 2                         | 2                      | 110                  | 206                       |                 |                      | 8              | 8                   | 
| 6         | Beacon Falls | 56         | 97              | 7                 | 13                     |                      |                           | 7               | 13                   | 1                     |                        | 5                         | 7                      | 167                  | 311                       |                 |                      | 30             | 30                  | 
| 7         | Berlin       | 141        | 224             | 12                | 27                     | *                    | 2                         | 12              | 29                   | 23                    |                        | 31                        | 55                     | 486                  | 789                       | 4               | 4                    | 47             | 47                  | 
| 8         | Bethany      | 15         | 27              | 2                 | 5                      |                      |                           | 2               | 5                    | 1                     |                        | 10                        | 11                     | 86                   | 160                       | 1               | 1                    | 11             | 11                  | 
| 9         | Bethel       | 163        | 261             | 16                | 36                     | 1                    | 5                         | 17              | 41                   | 12                    |                        | 15                        | 28                     | 646                  | 1096                      | 13              | 13                   | 66             | 66                  | 
| 10        | Bethlehem    | 24         | 43              | 1                 | 3                      |                      |                           | 1               | 3                    | 1                     |                        | 4                         | 5                      | 107                  | 188                       | 2               | 2                    | 8              | 8                   | 
```