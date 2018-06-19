# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-state-fiscal-year-2011) |
| Metadata | [Link](https://data.ct.gov/api/views/eijt-q8ip) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/eijt-q8ip/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/eijt-q8ip/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | eijt-q8ip |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2011 |
| Category | Health and Human Services |
| Tags | dss average monthly assistance units/ recipients by town |
| Created | 2015-04-24T18:46:02Z |
| Publication Date | 2015-05-06T14:06:28Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2011 

	* Due to rounding some towns may not display a case but will display recipients.  This is due to most cases having more than one recipient and therefore when averaged, the recipient count will be .5 or higher, and be counted as 1.  Due to rounding, program and statewide totals may appear inaccurate.

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eijt-q8ip d:2011-01-01T00:00:00.000Z t:town_code=1 t:town_name=Andover m:tfa_two_parent_cases=1 m:tfa_regular_cases=3 m:snap_cases=42 m:snap_recipients=79 m:saga_cash_cases=3 m:tfa_regular_recipients=7 m:saga_med_cases=15 m:tfa_total_cases=4 m:saga_cash_recipients=3 m:saga_med_recipients=15 m:state_supplement_disabled=5 m:tfa_two_parent_recipients=4 m:state_supplement_aged=1 m:total_medicaid_cases=92 m:tfa_total_recipients=11 m:state_supplement_total=6 m:total_medicaid_recipients=201

series e:eijt-q8ip d:2011-01-01T00:00:00.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=15 m:tfa_regular_cases=136 m:snap_cases=1387 m:snap_recipients=2830 m:saga_cash_cases=36 m:tfa_regular_recipients=281 m:saga_med_cases=377 m:tfa_total_cases=151 m:saga_cash_recipients=36 m:saga_med_recipients=377 m:state_supplement_disabled=52 m:tfa_two_parent_recipients=60 m:state_supplement_aged=14 m:total_medicaid_cases=2033 m:tfa_total_recipients=341 m:state_supplement_total=67 m:total_medicaid_recipients=3999

series e:eijt-q8ip d:2011-01-01T00:00:00.000Z t:town_code=3 t:town_name=Ashford m:tfa_two_parent_cases=1 m:tfa_regular_cases=9 m:snap_cases=135 m:snap_recipients=261 m:saga_cash_cases=8 m:tfa_regular_recipients=18 m:saga_med_cases=45 m:tfa_total_cases=10 m:saga_cash_recipients=8 m:saga_med_recipients=45 m:state_supplement_disabled=13 m:tfa_two_parent_recipients=8 m:state_supplement_aged=6 m:total_medicaid_cases=244 m:tfa_total_recipients=26 m:state_supplement_total=20 m:total_medicaid_recipients=518
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

entity e:eijt-q8ip l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2011" t:url=https://data.ct.gov/api/views/eijt-q8ip

property e:eijt-q8ip t:meta.view v:id=eijt-q8ip v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN-STATE FISCAL YEAR 2011"

property e:eijt-q8ip t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:eijt-q8ip t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1         | Andover      | 42         | 79              | 3                 | 7                      | 1                    | 4                         | 4               | 11                   | 1                     |                        | 5                         | 6                      | 92                   | 201                       | 3               | 3                    | 15             | 15                  | 
| 2         | Ansonia      | 1387       | 2830            | 136               | 281                    | 15                   | 60                        | 151             | 341                  | 14                    |                        | 52                        | 67                     | 2033                 | 3999                      | 36              | 36                   | 377            | 377                 | 
| 3         | Ashford      | 135        | 261             | 9                 | 18                     | 1                    | 8                         | 10              | 26                   | 6                     |                        | 13                        | 20                     | 244                  | 518                       | 8               | 8                    | 45             | 45                  | 
| 4         | Avon         | 121        | 214             | 7                 | 13                     | *                    | 2                         | 7               | 15                   | 7                     |                        | 8                         | 16                     | 391                  | 623                       | 6               | 6                    | 45             | 45                  | 
| 5         | Barkhamsted  | 52         | 110             | 2                 | 4                      | 0                    |                           | 2               | 4                    |                       |                        | 1                         | 1                      | 137                  | 289                       |                 | 0                    | 19             | 19                  | 
| 6         | Beacon Falls | 121        | 221             | 8                 | 12                     | 1                    | 5                         | 9               | 17                   | 3                     |                        | 5                         | 9                      | 218                  | 432                       | 3               | 3                    | 39             | 39                  | 
| 7         | Berlin       | 346        | 551             | 11                | 23                     | 1                    | 5                         | 12              | 28                   | 26                    |                        | 31                        | 58                     | 601                  | 1057                      | 15              | 15                   | 153            | 153                 | 
| 8         | Bethany      | 47         | 69              | 2                 | 3                      | *                    | 1                         | 2               | 4                    | 2                     |                        | 10                        | 12                     | 111                  | 207                       | 2               | 2                    | 29             | 29                  | 
| 9         | Bethel       | 345        | 627             | 23                | 46                     | 3                    | 14                        | 26              | 60                   | 13                    |                        | 11                        | 24                     | 814                  | 1517                      | 11              | 11                   | 125            | 125                 | 
| 10        | Bethlehem    | 56         | 107             |                   | 1                      |                      |                           |                 | 1                    | 1                     |                        | 3                         | 5                      | 138                  | 269                       | 1               | 1                    | 19             | 19                  | 
```