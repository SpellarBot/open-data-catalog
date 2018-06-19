# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY05

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-fy05) |
| Metadata | [Link](https://data.ct.gov/api/views/ffti-3zst) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ffti-3zst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ffti-3zst/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ffti-3zst |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY05 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T17:42:35Z |
| Publication Date | 2015-05-06T15:42:05Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN						
STATE FISCAL YEAR 2005						
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
| Yes      | numeric metric | tfa_two_parent_cases      | TFA-Two Parent Cases      | number    | text        |
| Yes      | numeric metric | tfa_two_parent_recipients | TFA-Two Parent Recipients | number    | number      |
| Yes      | numeric metric | tfa_total_cases           | TFA-Total Cases           | number    | number      |
| Yes      | numeric metric | tfa_total_recipients      | TFA-Total Recipients      | number    | number      |
| Yes      | numeric metric | state_supplement_aged     | State Supplement-Aged     | number    | number      |
| Yes      | numeric metric | state_supplement_blind    | State Supplement-Blind    | number    | number      |
| Yes      | numeric metric | state_supplement_disabled | State Supplement-Disabled | number    | number      |
| Yes      | numeric metric | state_supplement_total    | State Supplement-Total    | number    | number      |
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
series e:ffti-3zst d:2015-04-29T10:42:41.000Z t:tfa_two_parent_cases=* t:town_code=1 t:town_name=Andover m:tfa_regular_cases=3 m:snap_cases=10 m:snap_recipients=17 m:saga_cash_cases=0 m:tfa_regular_recipients=9 m:saga_med_cases=5 m:tfa_total_cases=3 m:saga_cash_recipients=0 m:saga_med_recipients=5 m:state_supplement_disabled=5 m:tfa_two_parent_recipients=1 m:state_supplement_aged=2 m:state_supplement_blind=0 m:tfa_total_recipients=10 m:state_supplement_total=8

series e:ffti-3zst d:2015-04-29T10:42:41.000Z t:town_code=2 t:town_name=Ansonia m:tfa_two_parent_cases=14 m:tfa_regular_cases=182 m:snap_cases=740 m:snap_recipients=1548 m:saga_cash_cases=32 m:tfa_regular_recipients=435 m:saga_med_cases=183 m:tfa_total_cases=196 m:saga_cash_recipients=32 m:saga_med_recipients=183 m:state_supplement_disabled=42 m:tfa_two_parent_recipients=46 m:state_supplement_aged=17 m:tfa_total_recipients=481 m:state_supplement_total=59

series e:ffti-3zst d:2015-04-29T10:42:41.000Z t:tfa_two_parent_cases=* t:town_code=3 t:town_name=Ashford m:tfa_regular_cases=8 m:snap_cases=52 m:snap_recipients=104 m:tfa_two_parent_recipients=1 m:saga_cash_cases=2 m:state_supplement_aged=9 m:tfa_regular_recipients=15 m:saga_med_cases=13 m:tfa_total_cases=8 m:saga_cash_recipients=2 m:saga_med_recipients=13 m:tfa_total_recipients=16 m:state_supplement_disabled=11 m:state_supplement_total=21
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

metric m:saga_cash_cases p:integer l:"SAGA-Cash Cases" t:dataTypeName=number

metric m:saga_cash_recipients p:integer l:"SAGA-Cash Recipients" t:dataTypeName=number

metric m:saga_med_cases p:integer l:"SAGA-Med Cases" t:dataTypeName=number

metric m:saga_med_recipients p:integer l:"SAGA-Med Recipients" t:dataTypeName=number

entity e:ffti-3zst l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY05" t:url=https://data.ct.gov/api/views/ffti-3zst

property e:ffti-3zst t:meta.view v:id=ffti-3zst v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY05"

property e:ffti-3zst t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:ffti-3zst t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | =============== | ==================== | ============== | =================== | 
| 1430304161  | 1         | Andover      | 10         | 17              | 3                 | 9                      | *                    | 1                         | 3               | 10                   | 2                     | 0                      | 5                         | 8                      | 0               | 0                    | 5              | 5                   | 
| 1430304161  | 2         | Ansonia      | 740        | 1548            | 182               | 435                    | 14                   | 46                        | 196             | 481                  | 17                    |                        | 42                        | 59                     | 32              | 32                   | 183            | 183                 | 
| 1430304161  | 3         | Ashford      | 52         | 104             | 8                 | 15                     | *                    | 1                         | 8               | 16                   | 9                     |                        | 11                        | 21                     | 2               | 2                    | 13             | 13                  | 
| 1430304161  | 4         | Avon         | 38         | 55              | 10                | 21                     | *                    | 1                         | 10              | 22                   | 5                     |                        | 12                        | 17                     | 2               | 2                    | 13             | 13                  | 
| 1430304161  | 5         | Barkhamsted  | 18         | 35              | 5                 | 8                      |                      |                           | 5               | 8                    |                       |                        | 2                         | 2                      | 1               | 1                    | 10             | 10                  | 
| 1430304161  | 6         | Beacon Falls | 46         | 75              | 11                | 22                     | 2                    | 8                         | 13              | 30                   | 2                     |                        | 5                         | 8                      | 2               | 2                    | 20             | 20                  | 
| 1430304161  | 7         | Berlin       | 120        | 189             | 16                | 32                     | 3                    | 12                        | 19              | 44                   | 29                    |                        | 37                        | 67                     | 5               | 5                    | 48             | 48                  | 
| 1430304161  | 8         | Bethany      | 14         | 20              | 2                 | 5                      | 0                    | 0                         | 2               | 5                    | 1                     | 0                      | 9                         | 10                     |                 |                      | 12             | 12                  | 
| 1430304161  | 9         | Bethel       | 122        | 185             | 9                 | 12                     |                      |                           | 9               | 12                   | 7                     | 0                      | 15                        | 22                     | 12              | 12                   | 44             | 44                  | 
| 1430304161  | 10        | Bethlehem    | 20         | 30              | 2                 | 3                      | 0                    | 0                         | 2               | 3                    |                       |                        | 4                         | 4                      | 2               | 2                    | 7              | 7                   | 
```