# Monthly Recipients Assistance Units FY01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-recipients-assistance-units-fy01) |
| Metadata | [Link](https://data.ct.gov/api/views/6eai-w4xp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/6eai-w4xp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/6eai-w4xp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 6eai-w4xp |
| Name | Monthly Recipients Assistance Units FY01 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T18:04:06Z |
| Publication Date | 2015-05-07T17:17:22Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 2001 * Counts are estimated due to AU/recipient address correction. Figures may not add due to rounding.

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
series e:6eai-w4xp d:2015-04-29T11:04:13.000Z t:tfa_regular_cases="* 3" t:snap_cases="* 11" t:town_code=1 t:snap_recipients="* 20" t:town_name=Andover t:tfa_regular_recipients="* 6" t:saga_med_cases="* 6" t:tfa_total_cases="* 3" t:saga_med_recipients="* 6" t:state_supplement_disabled="* 9" t:state_supplement_aged="* 2" t:total_medicaid_cases="* 55" t:tfa_total_recipients="* 6" t:total_medicaid_recipients="* 76" t:state_supplement_total="* 11" m:row_number.6eai-w4xp=1

series e:6eai-w4xp d:2015-04-29T11:04:13.000Z t:tfa_two_parent_cases="* 9" t:tfa_regular_cases="* 188" t:snap_cases="* 577" t:town_code=2 t:snap_recipients="* 1,166" t:town_name=Ansonia t:saga_cash_cases="* 24" t:tfa_regular_recipients="* 454" t:saga_med_cases="* 120" t:tfa_total_cases="* 197" t:saga_cash_recipients="* 24" t:saga_med_recipients="* 120" t:state_supplement_disabled="* 67" t:tfa_two_parent_recipients="* 37" t:state_supplement_aged="* 22" t:total_medicaid_cases="* 1,334" t:tfa_total_recipients="* 491" t:total_medicaid_recipients="* 2,263" t:state_supplement_total="* 89" m:row_number.6eai-w4xp=2

series e:6eai-w4xp d:2015-04-29T11:04:13.000Z t:tfa_regular_cases="* 13" t:snap_cases="* 33" t:town_code=3 t:snap_recipients="* 64" t:town_name=Ashford t:saga_cash_cases="* 2" t:tfa_regular_recipients="* 28" t:saga_med_cases="* 10" t:tfa_total_cases="* 13" t:saga_cash_recipients="* 2" t:saga_med_recipients="* 10" t:state_supplement_disabled="* 10" t:tfa_two_parent_recipients="* 1" t:state_supplement_aged="* 11" t:total_medicaid_cases="* 146" t:tfa_total_recipients="* 29" t:total_medicaid_recipients="* 255" t:state_supplement_total="* 21" m:row_number.6eai-w4xp=3
```

## Meta Commands

```ls
metric m:row_number.6eai-w4xp p:long l:"Row Number"

entity e:6eai-w4xp l:"Monthly Recipients Assistance Units FY01" t:url=https://data.ct.gov/api/views/6eai-w4xp

property e:6eai-w4xp t:meta.view v:id=6eai-w4xp v:category="Health and Human Services" v:averageRating=0 v:name="Monthly Recipients Assistance Units FY01"

property e:6eai-w4xp t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:6eai-w4xp t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | saga_cash_cases | saga_cash_recipients | saga_med_cases | saga_med_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | =============== | ==================== | ============== | =================== | 
| 1430305453  | 1         | Andover      | * 11       | * 20            | * 3               | * 6                    |                      |                           | * 3             | * 6                  | * 2                   |                        | * 9                       | * 11                   | * 55                 | * 76                      |                 |                      | * 6            | * 6                 | 
| 1430305453  | 2         | Ansonia      | * 577      | * 1,166         | * 188             | * 454                  | * 9                  | * 37                      | * 197           | * 491                | * 22                  |                        | * 67                      | * 89                   | * 1,334              | * 2,263                   | * 24            | * 24                 | * 120          | * 120               | 
| 1430305453  | 3         | Ashford      | * 33       | * 64            | * 13              | * 28                   |                      | * 1                       | * 13            | * 29                 | * 11                  |                        | * 10                      | * 21                   | * 146                | * 255                     | * 2             | * 2                  | * 10           | * 10                | 
| 1430305453  | 4         | Avon         | * 23       | * 30            | * 3               | * 4                    |                      | * 1                       | * 3             | * 5                  | * 10                  |                        | * 15                      | * 25                   | * 200                | * 231                     |                 |                      | * 11           | * 11                | 
| 1430305453  | 5         | Barkhamsted  | * 8        | * 17            | * 4               | * 8                    |                      |                           | * 4             | * 8                  |                       |                        | * 2                       | * 2                    | * 53                 | * 88                      | * 3             | * 3                  | * 5            | * 5                 | 
| 1430305453  | 6         | Beacon Falls | * 29       | * 44            | * 11              | * 19                   |                      |                           | * 11            | * 19                 | * 2                   |                        | * 10                      | * 12                   | * 117                | * 179                     | * 1             | * 1                  | * 10           | * 10                | 
| 1430305453  | 7         | Berlin       | * 71       | * 100           | * 15              | * 27                   | * 1                  | * 6                       | * 16            | * 33                 | * 32                  |                        | * 42                      | * 75                   | * 351                | * 496                     | * 12            | * 12                 | * 34           | * 34                | 
| 1430305453  | 8         | Bethany      | * 11       | * 23            | * 4               | * 10                   |                      |                           | * 4             | * 10                 | * 1                   |                        | * 6                       | * 8                    | * 59                 | * 96                      | * 1             | * 3                  | * 3            | * 3                 | 
| 1430305453  | 9         | Bethel       | * 83       | * 111           | * 17              | * 29                   | * 1                  | * 4                       | * 18            | * 33                 | * 12                  |                        | * 17                      | * 30                   | * 426                | * 606                     | * 9             | * 9                  | * 26           | * 26                | 
| 1430305453  | 10        | Bethlehem    | * 13       | * 19            | * 4               | * 6                    |                      |                           | * 4             | * 6                  | * 1                   |                        | * 5                       | * 7                    | * 75                 | * 106                     | * 1             | * 1                  | * 3            | * 3                 | 
```