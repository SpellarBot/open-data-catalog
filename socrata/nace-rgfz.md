# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-state-fiscal-year-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/nace-rgfz) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nace-rgfz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nace-rgfz/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nace-rgfz |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2012 |
| Category | Health and Human Services |
| Tags | monthly, assistance, units, recipients, town |
| Created | 2015-04-24T18:38:54Z |
| Publication Date | 2015-05-06T12:49:52Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN
STATE FISCAL YEAR 2012 
* Due to rounding some towns may not display a case but will display recipients.  This is due to most cases having more than one recipient and therefore when averaged, the recipient count will be .5 or higher, and be counted as 1. Note: Due to rounding, program and statewide totals may appear inaccurate.

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
| Yes      | numeric metric | medicaid_lia_cases        | Medicaid-LIA Cases        | number    | number      |
| Yes      | numeric metric | medicaid_lia_recipients   | Medicaid-LIA Recipients   | number    | number      |
| Yes      | numeric metric | saga_cash_cases           | SAGA-Cash Cases           | number    | number      |
| Yes      | numeric metric | saga_cash_recipients      | SAGA-Cash Recipients      | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nace-rgfz d:2012-01-01T00:00:00.000Z t:town_code=1 t:town_name=Andover m:tfa_two_parent_cases=1 m:tfa_regular_cases=3 m:snap_cases=54 m:snap_recipients=110 m:medicaid_lia_cases=22 m:tfa_regular_recipients=6 m:tfa_total_cases=4 m:saga_cash_recipients=0 m:state_supplement_disabled=5 m:tfa_two_parent_recipients=5 m:state_supplement_aged=1 m:medicaid_lia_recipients=22 m:total_medicaid_cases=127 m:tfa_total_recipients=11 m:state_supplement_total=6 m:total_medicaid_recipients=249

series e:nace-rgfz d:2012-01-01T00:00:00.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=8 m:tfa_regular_cases=125 m:snap_cases=1473 m:snap_recipients=2998 m:medicaid_lia_cases=490 m:saga_cash_cases=31 m:tfa_regular_recipients=256 m:tfa_total_cases=133 m:saga_cash_recipients=31 m:state_supplement_disabled=46 m:tfa_two_parent_recipients=33 m:state_supplement_aged=11 m:medicaid_lia_recipients=490 m:total_medicaid_cases=2493 m:tfa_total_recipients=289 m:state_supplement_total=58 m:total_medicaid_recipients=4504

series e:nace-rgfz d:2012-01-01T00:00:00.000Z t:town_code=3 t:town_name=Ashford m:tfa_two_parent_cases=1 m:tfa_regular_cases=8 m:snap_cases=149 m:snap_recipients=308 m:medicaid_lia_cases=50 m:saga_cash_cases=4 m:tfa_regular_recipients=15 m:tfa_total_cases=9 m:saga_cash_recipients=4 m:state_supplement_disabled=12 m:tfa_two_parent_recipients=6 m:state_supplement_aged=4 m:medicaid_lia_recipients=50 m:total_medicaid_cases=299 m:tfa_total_recipients=21 m:state_supplement_total=17 m:total_medicaid_recipients=586
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

metric m:medicaid_lia_cases p:integer l:"Medicaid-LIA Cases" t:dataTypeName=number

metric m:medicaid_lia_recipients p:integer l:"Medicaid-LIA Recipients" t:dataTypeName=number

metric m:saga_cash_cases p:integer l:"SAGA-Cash Cases" t:dataTypeName=number

metric m:saga_cash_recipients p:integer l:"SAGA-Cash Recipients" t:dataTypeName=number

entity e:nace-rgfz l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2012" t:url=https://data.ct.gov/api/views/nace-rgfz

property e:nace-rgfz t:meta.view v:id=nace-rgfz v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2012"

property e:nace-rgfz t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:nace-rgfz t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | medicaid_lia_cases | medicaid_lia_recipients | saga_cash_cases | saga_cash_recipients | 
| ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | ================== | ======================= | =============== | ==================== | 
| 1         | Andover      | 54         | 110             | 3                 | 6                      | 1                    | 5                         | 4               | 11                   | 1                     |                        | 5                         | 6                      | 127                  | 249                       | 22                 | 22                      |                 | 0                    | 
| 2         | Ansonia      | 1473       | 2998            | 125               | 256                    | 8                    | 33                        | 133             | 289                  | 11                    |                        | 46                        | 58                     | 2493                 | 4504                      | 490                | 490                     | 31              | 31                   | 
| 3         | Ashford      | 149        | 308             | 8                 | 15                     | 1                    | 6                         | 9               | 21                   | 4                     |                        | 12                        | 17                     | 299                  | 586                       | 50                 | 50                      | 4               | 4                    | 
| 4         | Avon         | 141        | 241             | 7                 | 12                     | *                    | 2                         | 7               | 14                   | 8                     |                        | 12                        | 20                     | 452                  | 692                       | 60                 | 60                      | 7               | 7                    | 
| 5         | Barkhamsted  | 57         | 117             | 3                 | 4                      |                      |                           | 3               | 4                    |                       |                        | 1                         | 1                      | 166                  | 312                       | 25                 | 25                      |                 | 0                    | 
| 6         | Beacon Falls | 136        | 240             | 10                | 17                     | 1                    | 7                         | 11              | 24                   | 3                     |                        | 5                         | 8                      | 266                  | 472                       | 56                 | 56                      | 3               | 3                    | 
| 7         | Berlin       | 399        | 637             | 12                | 23                     | 2                    | 9                         | 14              | 32                   | 26                    | 1                      | 30                        | 57                     | 820                  | 1299                      | 188                | 188                     | 11              | 11                   | 
| 8         | Bethany      | 58         | 95              | 5                 | 8                      | 1                    | 5                         | 6               | 13                   | 4                     |                        | 9                         | 13                     | 161                  | 263                       | 31                 | 31                      | 1               | 1                    | 
| 9         | Bethel       | 403        | 748             | 19                | 38                     | 1                    | 5                         | 20              | 43                   | 13                    |                        | 12                        | 25                     | 1007                 | 1719                      | 169                | 169                     | 11              | 11                   | 
| 10        | Bethlehem    | 60         | 104             |                   | 1                      |                      |                           |                 | 1                    |                       |                        | 5                         | 5                      | 159                  | 288                       | 25                 | 25                      | 1               | 1                    | 
```