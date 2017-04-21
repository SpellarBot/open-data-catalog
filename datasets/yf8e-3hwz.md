# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-state-fiscal-year-2007) |
| Metadata | [Link](https://data.ct.gov/api/views/yf8e-3hwz) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/yf8e-3hwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/yf8e-3hwz/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | yf8e-3hwz |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2007 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:25:24Z |
| Publication Date | 2015-05-06T14:53:19Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN						
STATE FISCAL YEAR 2007 						
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
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yf8e-3hwz d:2007-01-01T00:00:00.000Z t:town_code=1 t:town_name=Andover m:tfa_regular_cases=3 m:snap_cases=11 m:snap_recipients=26 m:tfa_regular_recipients=4 m:saga_med_cases=5 m:tfa_total_cases=3 m:saga_cash_recipients=0 m:saga_med_recipients=5 m:state_supplement_disabled=5 m:state_supplement_aged=1 m:total_medicaid_cases=72 m:tfa_total_recipients=4 m:state_supplement_total=6 m:total_medicaid_recipients=136

series e:yf8e-3hwz d:2007-01-01T00:00:00.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=9 m:tfa_regular_cases=156 m:snap_cases=759 m:snap_recipients=1660 m:saga_cash_cases=28 m:tfa_regular_recipients=350 m:saga_med_cases=186 m:tfa_total_cases=165 m:saga_cash_recipients=28 m:saga_med_recipients=186 m:state_supplement_disabled=38 m:tfa_two_parent_recipients=39 m:state_supplement_aged=17 m:total_medicaid_cases=1660 m:tfa_total_recipients=389 m:state_supplement_total=56 m:total_medicaid_recipients=3205

series e:yf8e-3hwz d:2007-01-01T00:00:00.000Z t:town_code=3 t:town_name=Ashford m:tfa_two_parent_cases=1 m:tfa_regular_cases=6 m:snap_cases=42 m:snap_recipients=78 m:saga_cash_cases=1 m:tfa_regular_recipients=12 m:saga_med_cases=19 m:tfa_total_cases=7 m:saga_cash_recipients=1 m:saga_med_recipients=19 m:state_supplement_disabled=13 m:tfa_two_parent_recipients=6 m:state_supplement_aged=9 m:total_medicaid_cases=188 m:tfa_total_recipients=18 m:state_supplement_total=23 m:total_medicaid_recipients=371
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

entity e:yf8e-3hwz l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2007" t:url=https://data.ct.gov/api/views/yf8e-3hwz

property e:yf8e-3hwz t:meta.view v:id=yf8e-3hwz v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2007"

property e:yf8e-3hwz t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:yf8e-3hwz t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1         | Andover      | 11         | 26              | 3                 | 4                      |                      |                           | 3               | 4                    | 1                     |                        | 5                         | 6                      | 72                   | 136                       |                 | 0                    | 5              | 5                   | 
| 2         | Ansonia      | 759        | 1660            | 156               | 350                    | 9                    | 39                        | 165             | 389                  | 17                    |                        | 38                        | 56                     | 1660                 | 3205                      | 28              | 28                   | 186            | 186                 | 
| 3         | Ashford      | 42         | 78              | 6                 | 12                     | 1                    | 6                         | 7               | 18                   | 9                     |                        | 13                        | 23                     | 188                  | 371                       | 1               | 1                    | 19             | 19                  | 
| 4         | Avon         | 38         | 58              | 5                 | 7                      | *                    | 1                         | 5               | 8                    | 8                     |                        | 10                        | 18                     | 280                  | 412                       | 1               | 1                    | 13             | 13                  | 
| 5         | Barkhamsted  | 15         | 25              | 4                 | 7                      |                      |                           | 4               | 7                    |                       |                        | 1                         | 1                      | 99                   | 185                       |                 | 0                    | 8              | 8                   | 
| 6         | Beacon Falls | 52         | 85              | 8                 | 16                     |                      |                           | 8               | 16                   | 2                     |                        | 5                         | 8                      | 161                  | 287                       | 2               | 2                    | 28             | 28                  | 
| 7         | Berlin       | 130        | 202             | 12                | 25                     | *                    | 1                         | 12              | 26                   | 25                    | 1                      | 34                        | 61                     | 456                  | 743                       | 8               | 8                    | 49             | 49                  | 
| 8         | Bethany      | 10         | 21              | 3                 | 7                      | *                    | 1                         | 3               | 8                    | 1                     |                        | 10                        | 11                     | 84                   | 149                       | 1               | 1                    | 13             | 13                  | 
| 9         | Bethel       | 151        | 235             | 15                | 33                     | *                    | 3                         | 15              | 36                   | 10                    | 0                      | 17                        | 28                     | 634                  | 1020                      | 13              | 13                   | 53             | 53                  | 
| 10        | Bethlehem    | 20         | 31              | 2                 | 3                      |                      |                           | 2               | 3                    |                       |                        | 3                         | 4                      | 94                   | 167                       | 1               | 1                    | 6              | 6                   | 
```