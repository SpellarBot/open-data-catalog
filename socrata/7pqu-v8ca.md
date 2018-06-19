# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-state-fiscal-year-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/7pqu-v8ca) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/7pqu-v8ca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/7pqu-v8ca/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 7pqu-v8ca |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2010 |
| Category | Health and Human Services |
| Tags | dss average monthly assistance units/ recipients by town |
| Created | 2015-04-24T18:52:04Z |
| Publication Date | 2015-05-06T14:18:39Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2010
* Due to rounding some towns may not display a case but will display recipients.  This is due to most cases having more than one recipient and therefore when averaged,the recipient count will be .5 or higher, and be counted as 1.Note: Due to rounding, program and statewide totals may appear inaccurate.

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
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7pqu-v8ca d:2010-01-01T00:00:00.000Z t:town_code=1 t:town_name=Andover m:tfa_regular_cases=3 m:snap_cases=33 m:snap_recipients=62 m:saga_cash_cases=3 m:tfa_regular_recipients=8 m:saga_med_cases=8 m:tfa_total_cases=3 m:saga_cash_recipients=3 m:saga_med_recipients=8 m:state_supplement_disabled=4 m:state_supplement_aged=1 m:total_medicaid_cases=91 m:tfa_total_recipients=8 m:state_supplement_total=5 m:total_medicaid_recipients=195

series e:7pqu-v8ca d:2010-01-01T00:00:00.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=6 m:tfa_regular_cases=134 m:snap_cases=1164 m:snap_recipients=2429 m:saga_cash_cases=29 m:tfa_regular_recipients=275 m:saga_med_cases=250 m:tfa_total_cases=140 m:saga_cash_recipients=29 m:saga_med_recipients=250 m:state_supplement_disabled=51 m:tfa_two_parent_recipients=27 m:state_supplement_aged=15 m:total_medicaid_cases=1895 m:tfa_total_recipients=302 m:state_supplement_total=67 m:total_medicaid_recipients=3718

series e:7pqu-v8ca d:2010-01-01T00:00:00.000Z t:town_code=3 t:town_name=Ashford m:tfa_two_parent_cases=3 m:tfa_regular_cases=8 m:snap_cases=104 m:snap_recipients=203 m:saga_cash_cases=5 m:tfa_regular_recipients=16 m:saga_med_cases=36 m:tfa_total_cases=11 m:saga_cash_recipients=5 m:saga_med_recipients=36 m:state_supplement_disabled=12 m:tfa_two_parent_recipients=16 m:state_supplement_aged=8 m:total_medicaid_cases=224 m:tfa_total_recipients=32 m:state_supplement_total=20 m:total_medicaid_recipients=465
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

entity e:7pqu-v8ca l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2010" t:url=https://data.ct.gov/api/views/7pqu-v8ca

property e:7pqu-v8ca t:meta.view v:id=7pqu-v8ca v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2010"

property e:7pqu-v8ca t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:7pqu-v8ca t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1         | Andover      | 33         | 62              | 3                 | 8                      |                      |                           | 3               | 8                    | 1                     |                        | 4                         | 5                      | 91                   | 195                       | 3               | 3                    | 8              | 8                   | 
| 2         | Ansonia      | 1164       | 2429            | 134               | 275                    | 6                    | 27                        | 140             | 302                  | 15                    |                        | 51                        | 67                     | 1895                 | 3718                      | 29              | 29                   | 250            | 250                 | 
| 3         | Ashford      | 104        | 203             | 8                 | 16                     | 3                    | 16                        | 11              | 32                   | 8                     |                        | 12                        | 20                     | 224                  | 465                       | 5               | 5                    | 36             | 36                  | 
| 4         | Avon         | 83         | 137             | 8                 | 13                     | *                    | 1                         | 8               | 14                   | 8                     |                        | 9                         | 17                     | 342                  | 517                       | 5               | 5                    | 19             | 19                  | 
| 5         | Barkhamsted  | 48         | 88              | 4                 | 7                      |                      |                           | 4               | 7                    |                       |                        | 2                         | 2                      | 136                  | 278                       | 1               | 1                    | 12             | 12                  | 
| 6         | Beacon Falls | 103        | 182             | 9                 | 15                     | 1                    | 5                         | 10              | 20                   | 4                     |                        | 6                         | 10                     | 202                  | 405                       | 1               | 1                    | 27             | 27                  | 
| 7         | Berlin       | 267        | 421             | 12                | 26                     | 1                    | 3                         | 13              | 29                   | 28                    | 1                      | 33                        | 62                     | 565                  | 973                       | 13              | 13                   | 87             | 87                  | 
| 8         | Bethany      | 32         | 49              | 1                 | 4                      |                      |                           | 1               | 4                    | 2                     |                        | 9                         | 11                     | 104                  | 195                       | 1               | 1                    | 20             | 20                  | 
| 9         | Bethel       | 291        | 540             | 20                | 43                     | 5                    | 22                        | 25              | 65                   | 12                    |                        | 11                        | 23                     | 757                  | 1378                      | 20              | 20                   | 84             | 84                  | 
| 10        | Bethlehem    | 44         | 84              | 3                 | 7                      | 1                    | 7                         | 4               | 14                   |                       |                        | 3                         | 4                      | 126                  | 248                       | 2               | 2                    | 12             | 12                  | 
```