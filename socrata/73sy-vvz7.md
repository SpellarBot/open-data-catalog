# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-fy-2006) |
| Metadata | [Link](https://data.ct.gov/api/views/73sy-vvz7) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/73sy-vvz7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/73sy-vvz7/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 73sy-vvz7 |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY 2006 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:35:00Z |
| Publication Date | 2015-05-06T15:31:01Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN						
STATE FISCAL YEAR 2006						
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
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:73sy-vvz7 d:2006-01-01T00:00:00.000Z t:town_code=1 t:town_name=Andover m:tfa_regular_cases=3 m:snap_cases=15 m:snap_recipients=22 m:tfa_regular_recipients=6 m:saga_med_cases=8 m:tfa_total_cases=3 m:saga_med_recipients=8 m:state_supplement_disabled=6 m:state_supplement_aged=2 m:total_medicaid_cases=75 m:tfa_total_recipients=6 m:state_supplement_total=8 m:total_medicaid_recipients=138

series e:73sy-vvz7 d:2006-01-01T00:00:00.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=14 m:tfa_regular_cases=163 m:snap_cases=762 m:snap_recipients=1624 m:saga_cash_cases=27 m:tfa_regular_recipients=378 m:saga_med_cases=184 m:tfa_total_cases=177 m:saga_cash_recipients=27 m:saga_med_recipients=184 m:state_supplement_disabled=39 m:tfa_two_parent_recipients=53 m:state_supplement_aged=18 m:total_medicaid_cases=1663 m:tfa_total_recipients=431 m:state_supplement_total=57 m:total_medicaid_recipients=3249

series e:73sy-vvz7 d:2006-01-01T00:00:00.000Z t:tfa_two_parent_cases=* t:town_code=3 t:town_name=Ashford m:tfa_regular_cases=9 m:snap_cases=42 m:snap_recipients=80 m:saga_cash_cases=1 m:tfa_regular_recipients=16 m:saga_med_cases=12 m:tfa_total_cases=9 m:saga_cash_recipients=1 m:saga_med_recipients=12 m:state_supplement_disabled=10 m:tfa_two_parent_recipients=1 m:state_supplement_aged=11 m:total_medicaid_cases=201 m:tfa_total_recipients=17 m:state_supplement_total=21 m:total_medicaid_recipients=411
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

entity e:73sy-vvz7 l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN  FY 2006" t:url=https://data.ct.gov/api/views/73sy-vvz7

property e:73sy-vvz7 t:meta.view v:id=73sy-vvz7 v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN  FY 2006"

property e:73sy-vvz7 t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:73sy-vvz7 t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1         | Andover      | 15         | 22              | 3                 | 6                      |                      |                           | 3               | 6                    | 2                     |                        | 6                         | 8                      | 75                   | 138                       |                 |                      | 8              | 8                   | 
| 2         | Ansonia      | 762        | 1624            | 163               | 378                    | 14                   | 53                        | 177             | 431                  | 18                    |                        | 39                        | 57                     | 1663                 | 3249                      | 27              | 27                   | 184            | 184                 | 
| 3         | Ashford      | 42         | 80              | 9                 | 16                     | *                    | 1                         | 9               | 17                   | 11                    |                        | 10                        | 21                     | 201                  | 411                       | 1               | 1                    | 12             | 12                  | 
| 4         | Avon         | 43         | 65              | 8                 | 16                     | 1                    | 3                         | 9               | 19                   | 6                     |                        | 12                        | 18                     | 284                  | 419                       |                 |                      | 17             | 17                  | 
| 5         | Barkhamsted  | 16         | 36              | 4                 | 6                      |                      |                           | 4               | 6                    |                       |                        | 1                         | 1                      | 100                  | 194                       | 1               | 1                    | 8              | 8                   | 
| 6         | Beacon Falls | 46         | 67              | 10                | 17                     | *                    | 2                         | 10              | 19                   | 2                     |                        | 6                         | 9                      | 156                  | 277                       | 2               | 2                    | 27             | 27                  | 
| 7         | Berlin       | 130        | 202             | 14                | 30                     | 2                    | 7                         | 16              | 37                   | 26                    |                        | 40                        | 67                     | 444                  | 746                       | 7               | 7                    | 47             | 47                  | 
| 8         | Bethany      | 14         | 19              | 2                 | 5                      |                      |                           | 2               | 5                    | 1                     |                        | 9                         | 10                     | 78                   | 127                       |                 |                      | 13             | 13                  | 
| 9         | Bethel       | 149        | 240             | 11                | 22                     | *                    | 2                         | 11              | 24                   | 8                     |                        | 16                        | 24                     | 636                  | 1042                      | 11              | 11                   | 51             | 51                  | 
| 10        | Bethlehem    | 23         | 32              | 4                 | 6                      |                      |                           | 4               | 6                    |                       |                        | 4                         | 4                      | 111                  | 187                       | 2               | 2                    | 8              | 8                   | 
```