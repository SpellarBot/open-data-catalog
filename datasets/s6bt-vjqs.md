# MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-assistance-units-and-recipients-by-town-fy14) |
| Metadata | [Link](https://data.ct.gov/api/views/s6bt-vjqs) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/s6bt-vjqs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/s6bt-vjqs/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | s6bt-vjqs |
| Name | MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY14 |
| Attribution | DSS |
| Category | Health and Human Services |
| Tags | dss average monthly assistance units/ recipients by town |
| Created | 2015-04-24T17:49:17Z |
| Publication Date | 2015-05-05T13:00:06Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN
* Due to rounding some towns may not display a case but will display recipients.  This is due to most cases having more than one recipient and therefore when averaged, the recipient count will be .5 or higher, and be counted as 1.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | town_code                      | Town Code                      | text      | number      |
| Yes      | series tag     | town_name                      | Town Name                      | text      | text        |
| Yes      | numeric metric | snap_cases                     | SNAP Cases                     | number    | number      |
| Yes      | numeric metric | snap_recipients                | SNAP Recipients                | number    | number      |
| Yes      | numeric metric | tfa_regular_cases              | TFA-Regular Cases              | number    | number      |
| Yes      | numeric metric | tfa_regular_recipients         | TFA-Regular Recipients         | number    | number      |
| Yes      | numeric metric | tfa_two_parent_cases           | TFA-Two Parent Cases           | number    | text        |
| Yes      | numeric metric | tfa_two_parent_recipients      | TFA-Two Parent Recipients      | number    | number      |
| Yes      | numeric metric | tfa_total_cases                | TFA-Total Cases                | number    | number      |
| Yes      | numeric metric | tfa_total_recipients           | TFA-Total Recipients           | number    | number      |
| Yes      | numeric metric | state_supplement_aged          | State Supplement-Aged          | number    | number      |
| Yes      | numeric metric | state_supplement_blind         | State Supplement-Blind         | number    | number      |
| Yes      | numeric metric | state_supplement_disabled      | State Supplement-Disabled      | number    | number      |
| Yes      | numeric metric | state_supplement_total         | State Supplement-Total         | number    | number      |
| Yes      | numeric metric | msp_qmb_cases_recipients       | MSP-QMB Cases/Recipients       | number    | number      |
| Yes      | numeric metric | msp_slmb_almb_cases_recipients | MSP-SLMB/ALMB Cases/Recipients | number    | number      |
| Yes      | numeric metric | medicaid_lip_cases             | Medicaid-LIP Cases             | number    | number      |
| Yes      | numeric metric | medicaid_lip_recipients        | Medicaid-LIP Recipients        | number    | number      |
| Yes      | numeric metric | aca_cases                      | ACA Cases                      | number    | number      |
| Yes      | numeric metric | aca_recipients                 | ACA Recipients                 | number    | number      |
| Yes      | numeric metric | total_medicaid_cases           | Total Medicaid Cases           | number    | number      |
| Yes      | numeric metric | total_medicaid_recipients      | Total Medicaid Recipients      | number    | number      |
| Yes      | numeric metric | saga_cash_cases                | SAGA-Cash Cases                | number    | number      |
| Yes      | numeric metric | saga_cash_recipients           | SAGA-Cash Recipients           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s6bt-vjqs d:2015-04-24T10:49:25.000Z t:town_code=1 t:town_name=Andover m:tfa_regular_cases=1 m:snap_cases=71 m:snap_recipients=128 m:saga_cash_cases=2 m:tfa_regular_recipients=2 m:saga_cash_recipients=2 m:msp_slmb_almb_cases_recipients=10 m:tfa_total_cases=1 m:medicaid_lip_recipients=34 m:state_supplement_disabled=8 m:medicaid_lip_cases=34 m:aca_cases=47 m:total_medicaid_cases=236 m:tfa_total_recipients=2 m:aca_recipients=59 m:state_supplement_total=8 m:total_medicaid_recipients=364 m:msp_qmb_cases_recipients=36

series e:s6bt-vjqs d:2015-04-24T10:49:25.000Z t:town_code=2 t:town_name=Ansonia m:tfa_regular_cases=107 m:tfa_two_parent_cases=13 m:snap_cases=1600 m:snap_recipients=3177 m:saga_cash_cases=31 m:tfa_regular_recipients=206 m:saga_cash_recipients=31 m:medicaid_lip_recipients=658 m:msp_slmb_almb_cases_recipients=68 m:tfa_total_cases=120 m:state_supplement_disabled=36 m:aca_cases=510 m:medicaid_lip_cases=658 m:tfa_two_parent_recipients=45 m:state_supplement_aged=13 m:state_supplement_blind=1 m:total_medicaid_cases=3651 m:tfa_total_recipients=251 m:aca_recipients=608 m:state_supplement_total=50 m:total_medicaid_recipients=5782 m:msp_qmb_cases_recipients=444

series e:s6bt-vjqs d:2015-04-24T10:49:25.000Z t:tfa_two_parent_cases=* t:town_code=3 t:town_name=Ashford m:tfa_regular_cases=12 m:snap_cases=163 m:snap_recipients=332 m:saga_cash_cases=7 m:tfa_regular_recipients=28 m:saga_cash_recipients=7 m:medicaid_lip_recipients=63 m:msp_slmb_almb_cases_recipients=13 m:tfa_total_cases=12 m:state_supplement_disabled=10 m:medicaid_lip_cases=63 m:aca_cases=89 m:tfa_two_parent_recipients=2 m:state_supplement_aged=8 m:total_medicaid_cases=509 m:tfa_total_recipients=30 m:aca_recipients=110 m:state_supplement_total=18 m:total_medicaid_recipients=826 m:msp_qmb_cases_recipients=64
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

metric m:msp_qmb_cases_recipients p:integer l:"MSP-QMB Cases/Recipients" t:dataTypeName=number

metric m:msp_slmb_almb_cases_recipients p:integer l:"MSP-SLMB/ALMB Cases/Recipients" t:dataTypeName=number

metric m:medicaid_lip_cases p:integer l:"Medicaid-LIP Cases" t:dataTypeName=number

metric m:medicaid_lip_recipients p:integer l:"Medicaid-LIP Recipients" t:dataTypeName=number

metric m:aca_cases p:integer l:"ACA Cases" t:dataTypeName=number

metric m:aca_recipients p:integer l:"ACA Recipients" t:dataTypeName=number

metric m:total_medicaid_cases p:integer l:"Total Medicaid Cases" t:dataTypeName=number

metric m:total_medicaid_recipients p:integer l:"Total Medicaid Recipients" t:dataTypeName=number

metric m:saga_cash_cases p:integer l:"SAGA-Cash Cases" t:dataTypeName=number

metric m:saga_cash_recipients p:integer l:"SAGA-Cash Recipients" t:dataTypeName=number

entity e:s6bt-vjqs l:"MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY14" t:attribution=DSS t:url=https://data.ct.gov/api/views/s6bt-vjqs

property e:s6bt-vjqs t:meta.view v:id=s6bt-vjqs v:category="Health and Human Services" v:averageRating=0 v:name="MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN FY14" v:attribution=DSS

property e:s6bt-vjqs t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:s6bt-vjqs t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | msp_qmb_cases_recipients | msp_slmb_almb_cases_recipients | medicaid_lip_cases | medicaid_lip_recipients | aca_cases | aca_recipients | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ======================== | ============================== | ================== | ======================= | ========= | ============== | ==================== | ========================= | =============== | ==================== | 
| 1429872565  | 1         | Andover      | 71         | 128             | 1                 | 2                      |                      |                           | 1               | 2                    |                       |                        | 8                         | 8                      | 36                       | 10                             | 34                 | 34                      | 47        | 59             | 236                  | 364                       | 2               | 2                    | 
| 1429872565  | 2         | Ansonia      | 1600       | 3177            | 107               | 206                    | 13                   | 45                        | 120             | 251                  | 13                    | 1                      | 36                        | 50                     | 444                      | 68                             | 658                | 658                     | 510       | 608            | 3651                 | 5782                      | 31              | 31                   | 
| 1429872565  | 3         | Ashford      | 163        | 332             | 12                | 28                     | *                    | 2                         | 12              | 30                   | 8                     |                        | 10                        | 18                     | 64                       | 13                             | 63                 | 63                      | 89        | 110            | 509                  | 826                       | 7               | 7                    | 
| 1429872565  | 4         | Avon         | 170        | 258             | 6                 | 10                     | 2                    | 7                         | 8               | 17                   | 11                    |                        | 9                         | 20                     | 166                      | 34                             | 76                 | 76                      | 136       | 163            | 835                  | 1109                      | 7               | 7                    | 
| 1429872565  | 5         | Barkhamsted  | 66         | 122             | 1                 | 2                      | *                    | 1                         | 1               | 3                    |                       |                        | 6                         | 6                      | 41                       | 9                              | 37                 | 37                      | 65        | 81             | 280                  | 418                       |                 | 0                    | 
| 1429872565  | 6         | Beacon Falls | 167        | 274             | 8                 | 16                     | 2                    | 7                         | 10              | 23                   | 3                     |                        | 9                         | 12                     | 85                       | 19                             | 88                 | 88                      | 77        | 91             | 484                  | 701                       | 2               | 2                    | 
| 1429872565  | 7         | Berlin       | 514        | 831             | 22                | 51                     | 4                    | 16                        | 26              | 67                   | 24                    |                        | 33                        | 57                     | 327                      | 80                             | 219                | 219                     | 236       | 276            | 1574                 | 2271                      | 9               | 9                    | 
| 1429872565  | 8         | Bethany      | 67         | 100             |                   | 1                      |                      |                           |                 | 1                    | 5                     |                        | 9                         | 14                     | 42                       | 10                             | 32                 | 32                      | 53        | 63             | 260                  | 369                       | 2               | 2                    | 
| 1429872565  | 9         | Bethel       | 453        | 826             | 19                | 35                     | 2                    | 9                         | 21              | 44                   | 11                    |                        | 13                        | 24                     | 260                      | 36                             | 227                | 227                     | 270       | 337            | 1660                 | 2498                      | 11              | 11                   | 
| 1429872565  | 10        | Bethlehem    | 63         | 99              | 1                 | 2                      |                      |                           | 1               | 2                    |                       |                        | 5                         | 5                      | 50                       | 3                              | 41                 | 41                      | 51        | 59             | 280                  | 427                       |                 | 0                    | 
```