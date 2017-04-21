# Monthly Recipient Assistance Units FY00

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-recipient-assistance-units-fy00) |
| Metadata | [Link](https://data.ct.gov/api/views/bkzu-kfvt) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bkzu-kfvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bkzu-kfvt/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bkzu-kfvt |
| Name | Monthly Recipient Assistance Units FY00 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T18:08:22Z |
| Publication Date | 2015-05-07T17:21:46Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2000 * Counts are estimated due to AU/recipient address correction. Figures may not add due to rounding.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | town_code                 | Town Code                 | text      | number      |
| Yes      | series tag  | town_name                 | Town Name                 | text      | text        |
| Yes      | series tag  | snap_cases                | SNAP Cases                | text      | text        |
| Yes      | series tag  | snap_recipients           | SNAP Recipients           | text      | text        |
| Yes      | series tag  | tfa_regular_cases         | TFA-Regular Cases         | text      | text        |
| Yes      | series tag  | tfa_regular_recipients    | TFA-Regular Recipients    | text      | text        |
| Yes      | series tag  | tfa_two_parent_cases      | TFA-Two Parent Cases      | text      | text        |
| Yes      | series tag  | tfa_two_parent_recipients | TFA-Two Parent Recipients | text      | text        |
| Yes      | series tag  | tfa_total_cases           | TFA-Total Cases           | text      | text        |
| Yes      | series tag  | tfa_total_recipients      | TFA-Total Recipients      | text      | text        |
| Yes      | series tag  | state_supplement_aged     | State Supplement-Aged     | text      | text        |
| Yes      | series tag  | state_supplement_blind    | State Supplement-Blind    | text      | text        |
| Yes      | series tag  | state_supplement_disabled | State Supplement-Disabled | text      | text        |
| Yes      | series tag  | state_supplement_total    | State Supplement-Total    | text      | text        |
| Yes      | series tag  | total_medicaid_cases      | Total Medicaid Cases      | text      | text        |
| Yes      | series tag  | total_medicaid_recipients | Total Medicaid Recipients | text      | text        |
| Yes      | series tag  | saga_cash_cases           | SAGA-Cash Cases           | text      | text        |
| Yes      | series tag  | saga_cash_recipients      | SAGA-Cash Recipients      | text      | text        |
| Yes      | series tag  | saga_med_cases            | SAGA-Med Cases            | text      | text        |
| Yes      | series tag  | saga_med_recipients       | SAGA-Med Recipients       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bkzu-kfvt d:2015-04-29T11:08:29.000Z t:tfa_two_parent_cases=0.0 t:tfa_regular_cases="* 4" t:snap_cases="* 11" t:town_code=1 t:snap_recipients="* 23" t:town_name=Andover t:saga_cash_cases="* 1" t:tfa_regular_recipients="* 9" t:saga_med_cases="* 1" t:tfa_total_cases="* 4" t:saga_cash_recipients="* 1" t:saga_med_recipients="* 1" t:state_supplement_disabled="* 5" t:tfa_two_parent_recipients=0.0 t:state_supplement_aged="* 2" t:state_supplement_blind=0.0 t:total_medicaid_cases="* 54" t:tfa_total_recipients="* 9" t:total_medicaid_recipients="* 73" t:state_supplement_total="* 8" m:row_number.bkzu-kfvt=1

series e:bkzu-kfvt d:2015-04-29T11:08:29.000Z t:tfa_two_parent_cases="* 8" t:tfa_regular_cases="* 213" t:snap_cases="* 594" t:town_code=2 t:snap_recipients="* 1,227" t:town_name=Ansonia t:saga_cash_cases="* 24" t:tfa_regular_recipients="* 527" t:saga_med_cases="* 98" t:tfa_total_cases="* 221" t:saga_cash_recipients="* 24" t:saga_med_recipients="* 98" t:state_supplement_disabled="* 75" t:tfa_two_parent_recipients="* 32" t:state_supplement_aged="* 20" t:state_supplement_blind=0.0 t:total_medicaid_cases="* 1,298" t:tfa_total_recipients="* 559" t:total_medicaid_recipients="* 2,184" t:state_supplement_total="* 95" m:row_number.bkzu-kfvt=2

series e:bkzu-kfvt d:2015-04-29T11:08:29.000Z t:tfa_two_parent_cases=0.0 t:tfa_regular_cases="* 14" t:snap_cases="* 28" t:town_code=3 t:snap_recipients="* 62" t:town_name=Ashford t:saga_cash_cases="* 2" t:tfa_regular_recipients="* 29" t:saga_med_cases="* 6" t:tfa_total_cases="* 14" t:saga_cash_recipients="* 2" t:saga_med_recipients="* 6" t:state_supplement_disabled="* 9" t:tfa_two_parent_recipients="* 3" t:state_supplement_aged="* 10" t:state_supplement_blind=0.0 t:total_medicaid_cases="* 140" t:tfa_total_recipients="* 32" t:total_medicaid_recipients="* 230" t:state_supplement_total="* 20" m:row_number.bkzu-kfvt=3
```

## Meta Commands

```ls
metric m:row_number.bkzu-kfvt p:long l:"Row Number"

entity e:bkzu-kfvt l:"Monthly Recipient Assistance Units FY00" t:url=https://data.ct.gov/api/views/bkzu-kfvt

property e:bkzu-kfvt t:meta.view v:id=bkzu-kfvt v:category="Health and Human Services" v:averageRating=0 v:name="Monthly Recipient Assistance Units FY00"

property e:bkzu-kfvt t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:bkzu-kfvt t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1430305709  | 1         | Andover      | * 11       | * 23            | * 4               | * 9                    | 0.0                  | 0.0                       | * 4             | * 9                  | * 2                   | 0.0                    | * 5                       | * 8                    | * 54                 | * 73                      | * 1             | * 1                  | * 1            | * 1                 | 
| 1430305709  | 2         | Ansonia      | * 594      | * 1,227         | * 213             | * 527                  | * 8                  | * 32                      | * 221           | * 559                | * 20                  | 0.0                    | * 75                      | * 95                   | * 1,298              | * 2,184                   | * 24            | * 24                 | * 98           | * 98                | 
| 1430305709  | 3         | Ashford      | * 28       | * 62            | * 14              | * 29                   | 0.0                  | * 3                       | * 14            | * 32                 | * 10                  | 0.0                    | * 9                       | * 20                   | * 140                | * 230                     | * 2             | * 2                  | * 6            | * 6                 | 
| 1430305709  | 4         | Avon         | * 26       | * 39            | * 4               | * 8                    | 0.0                  | 0.0                       | * 4             | * 8                  | * 7                   | 0.0                    | * 16                      | * 23                   | * 186                | * 212                     | * 1             | * 1                  | * 8            | * 8                 | 
| 1430305709  | 5         | Barkhamsted  | * 7        | * 11            | * 4               | * 6                    | 0.0                  | 0.0                       | * 4             | * 6                  | 0.0                   | 0.0                    | * 2                       | * 3                    | * 38                 | * 54                      | * 3             | * 3                  | * 7            | * 7                 | 
| 1430305709  | 6         | Beacon Falls | * 31       | * 55            | * 12              | * 23                   | 0.0                  | 0.0                       | * 12            | * 23                 | * 2                   | 0.0                    | * 10                      | * 13                   | * 127                | * 189                     | * 1             | * 1                  | * 6            | * 6                 | 
| 1430305709  | 7         | Berlin       | * 65       | * 100           | * 21              | * 39                   | * 1                  | * 4                       | * 22            | * 43                 | * 30                  | 0.0                    | * 36                      | * 67                   | * 321                | * 452                     | * 9             | * 9                  | * 33           | * 33                | 
| 1430305709  | 8         | Bethany      | * 11       | * 26            | * 4               | * 13                   | 0.0                  | 0.0                       | * 4             | * 13                 | * 1                   | 0.0                    | * 6                       | * 7                    | * 48                 | * 79                      | * 1             | * 3                  | * 3            | * 3                 | 
| 1430305709  | 9         | Bethel       | * 89       | * 134           | * 26              | * 45                   | * 1                  | * 5                       | * 27            | * 50                 | * 17                  | 0.0                    | * 22                      | * 39                   | * 411                | * 570                     | * 11            | * 11                 | * 29           | * 29                | 
| 1430305709  | 10        | Bethlehem    | * 11       | * 15            | * 4               | * 8                    | 0.0                  | * 1                       | * 4             | * 9                  | * 1                   | 0.0                    | * 5                       | * 6                    | * 71                 | * 98                      | * 1             | * 1                  | * 2            | * 2                 | 
```