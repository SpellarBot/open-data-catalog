# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY03

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-fy03) |
| Metadata | [Link](https://data.ct.gov/api/views/d2gy-qyu3) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/d2gy-qyu3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/d2gy-qyu3/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | d2gy-qyu3 |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY03 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:50:32Z |
| Publication Date | 2015-05-06T18:13:31Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2003 * Counts are estimated due to AU/recipient address correction. Figures may not add due to rounding.

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
series e:d2gy-qyu3 d:2015-04-29T10:50:40.000Z t:town_code=1 t:town_name=Andover m:tfa_two_parent_cases=0 m:tfa_regular_cases=5 m:snap_cases=9 m:snap_recipients=16 m:tfa_regular_recipients=8 m:saga_med_cases=4 m:tfa_total_cases=5 m:saga_med_recipients=4 m:state_supplement_disabled=8 m:tfa_two_parent_recipients=2 m:state_supplement_aged=2 m:state_supplement_blind=0 m:total_medicaid_cases=72 m:tfa_total_recipients=10 m:state_supplement_total=10 m:total_medicaid_recipients=119

series e:d2gy-qyu3 d:2015-04-29T10:50:40.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=11 m:tfa_regular_cases=173 m:snap_cases=661 m:snap_recipients=1329 m:saga_cash_cases=40 m:tfa_regular_recipients=408 m:saga_med_cases=157 m:tfa_total_cases=184 m:saga_cash_recipients=40 m:saga_med_recipients=157 m:state_supplement_disabled=57 m:tfa_two_parent_recipients=44 m:state_supplement_aged=17 m:total_medicaid_cases=1501 m:tfa_total_recipients=452 m:state_supplement_total=75 m:total_medicaid_recipients=2784

series e:d2gy-qyu3 d:2015-04-29T10:50:40.000Z t:town_code=3 t:town_name=Ashford m:tfa_regular_cases=14 m:snap_cases=43 m:snap_recipients=87 m:saga_cash_cases=2 m:tfa_regular_recipients=28 m:saga_med_cases=10 m:tfa_total_cases=14 m:saga_cash_recipients=2 m:saga_med_recipients=10 m:state_supplement_disabled=12 m:state_supplement_aged=15 m:total_medicaid_cases=197 m:tfa_total_recipients=28 m:state_supplement_total=27 m:total_medicaid_recipients=387
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

entity e:d2gy-qyu3 l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY03" t:url=https://data.ct.gov/api/views/d2gy-qyu3

property e:d2gy-qyu3 t:meta.view v:id=d2gy-qyu3 v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY03"

property e:d2gy-qyu3 t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:d2gy-qyu3 t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1430304640  | 1         | Andover      | 9          | 16              | 5                 | 8                      | 0                    | 2                         | 5               | 10                   | 2                     | 0                      | 8                         | 10                     | 72                   | 119                       |                 |                      | 4              | 4                   | 
| 1430304640  | 2         | Ansonia      | 661        | 1329            | 173               | 408                    | 11                   | 44                        | 184             | 452                  | 17                    |                        | 57                        | 75                     | 1501                 | 2784                      | 40              | 40                   | 157            | 157                 | 
| 1430304640  | 3         | Ashford      | 43         | 87              | 14                | 28                     |                      |                           | 14              | 28                   | 15                    |                        | 12                        | 27                     | 197                  | 387                       | 2               | 2                    | 10             | 10                  | 
| 1430304640  | 4         | Avon         | 33         | 57              | 4                 | 7                      | 0                    | 1                         | 4               | 8                    | 8                     |                        | 14                        | 22                     | 242                  | 335                       | 5               | 5                    | 23             | 23                  | 
| 1430304640  | 5         | Barkhamsted  | 13         | 34              | 7                 | 16                     |                      |                           | 7               | 16                   |                       |                        | 2                         | 2                      | 86                   | 181                       | 0               | 0                    | 6              | 6                   | 
| 1430304640  | 6         | Beacon Falls | 32         | 53              | 8                 | 12                     |                      | 3                         | 8               | 15                   | 2                     |                        | 7                         | 10                     | 127                  | 236                       | 1               | 1                    | 15             | 15                  | 
| 1430304640  | 7         | Berlin       | 85         | 115             | 17                | 29                     | 1                    | 2                         | 18              | 31                   | 33                    |                        | 38                        | 71                     | 401                  | 663                       | 12              | 12                   | 39             | 39                  | 
| 1430304640  | 8         | Bethany      | 10         | 17              | 4                 | 7                      |                      |                           | 4               | 7                    | 1                     |                        | 9                         | 10                     | 82                   | 138                       | 1               | 3                    | 8              | 8                   | 
| 1430304640  | 9         | Bethel       | 94         | 140             | 14                | 27                     | 0                    | 1                         | 14              | 28                   | 10                    |                        | 17                        | 28                     | 540                  | 864                       | 8               | 8                    | 33             | 33                  | 
| 1430304640  | 10        | Bethlehem    | 12         | 16              | 2                 | 2                      |                      |                           | 2               | 2                    | 1                     |                        | 3                         | 4                      | 92                   | 171                       |                 |                      | 2              | 2                   | 
```