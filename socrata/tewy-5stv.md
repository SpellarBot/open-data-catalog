# Monthly Recipients Assistance Units FY99

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-recipients-assistance-units-fy99) |
| Metadata | [Link](https://data.ct.gov/api/views/tewy-5stv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/tewy-5stv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/tewy-5stv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | tewy-5stv |
| Name | Monthly Recipients Assistance Units FY99 |
| Category | Health and Human Services |
| Tags | dss, average, monthly, assistance units, recipients by town |
| Created | 2015-04-29T19:03:24Z |
| Publication Date | 2015-05-07T17:35:18Z |

## Description

AVERAGE MONTHLY ASSISTANCE UNITS AND RECIPIENTS BY TOWN STATE FISCAL YEAR 99 * Counts are estimated due to AU/recipient address correction. Figures may not add due to rounding.

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
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tewy-5stv d:2015-04-29T12:03:31.000Z t:tfa_two_parent_cases=0.0 t:tfa_regular_cases="* 5" t:snap_cases="* 10" t:town_code=1 t:snap_recipients="* 22" t:town_name=Andover t:tfa_regular_recipients="* 10" t:tfa_total_cases="* 3" t:state_supplement_disabled="* 37" t:tfa_two_parent_recipients=0.0 t:state_supplement_aged="* 6" t:state_supplement_blind="* 9" t:total_medicaid_cases="* 51" t:tfa_total_recipients=0.0 t:total_medicaid_recipients="* 70" t:state_supplement_total="* 51" m:row_number.tewy-5stv=1

series e:tewy-5stv d:2015-04-29T12:03:31.000Z t:tfa_two_parent_cases="* 8" t:tfa_regular_cases="* 254" t:snap_cases="* 608" t:town_code=2 t:snap_recipients="* 1,281" t:town_name=Ansonia t:tfa_regular_recipients="* 634" t:tfa_total_cases="* 21" t:state_supplement_disabled="* 899" t:tfa_two_parent_recipients="* 34" t:state_supplement_aged="* 83" t:state_supplement_blind="* 105" t:total_medicaid_cases="* 1,266" t:tfa_total_recipients=0.0 t:total_medicaid_recipients="* 2,101" t:state_supplement_total="* 1,328" m:row_number.tewy-5stv=2

series e:tewy-5stv d:2015-04-29T12:03:31.000Z t:tfa_two_parent_cases=0.0 t:tfa_regular_cases="* 15" t:snap_cases="* 30" t:town_code=3 t:snap_recipients="* 65" t:town_name=Ashford t:tfa_regular_recipients="* 33" t:tfa_total_cases="* 11" t:state_supplement_disabled="* 100" t:tfa_two_parent_recipients=0.0 t:state_supplement_aged="* 7" t:state_supplement_blind="* 19" t:total_medicaid_cases="* 134" t:tfa_total_recipients=0.0 t:total_medicaid_recipients="* 210" t:state_supplement_total="* 158" m:row_number.tewy-5stv=3
```

## Meta Commands

```ls
metric m:row_number.tewy-5stv p:long l:"Row Number"

entity e:tewy-5stv l:"Monthly Recipients Assistance Units FY99" t:url=https://data.ct.gov/api/views/tewy-5stv

property e:tewy-5stv t:meta.view v:id=tewy-5stv v:category="Health and Human Services" v:averageRating=0 v:name="Monthly Recipients Assistance Units FY99"

property e:tewy-5stv t:meta.view.owner v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"

property e:tewy-5stv t:meta.view.tableauthor v:id=ee3v-iqmq v:screenName="Shirin Khan" v:displayName="Shirin Khan"
```

## Top Records

```ls
| :updated_at | town_code | town_name    | snap_cases | snap_recipients | tfa_regular_cases | tfa_regular_recipients | tfa_two_parent_cases | tfa_two_parent_recipients | tfa_total_cases | tfa_total_recipients | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recipients | 
| =========== | ========= | ============ | ========== | =============== | ================= | ====================== | ==================== | ========================= | =============== | ==================== | ===================== | ====================== | ========================= | ====================== | ==================== | ========================= | 
| 1430309011  | 1         | Andover      | * 10       | * 22            | * 5               | * 10                   | 0.0                  | 0.0                       | * 3             | 0.0                  | * 6                   | * 9                    | * 37                      | * 51                   | * 51                 | * 70                      | 
| 1430309011  | 2         | Ansonia      | * 608      | * 1,281         | * 254             | * 634                  | * 8                  | * 34                      | * 21            | 0.0                  | * 83                  | * 105                  | * 899                     | * 1,328                | * 1,266              | * 2,101                   | 
| 1430309011  | 3         | Ashford      | * 30       | * 65            | * 15              | * 33                   | 0.0                  | 0.0                       | * 11            | 0.0                  | * 7                   | * 19                   | * 100                     | * 158                  | * 134                | * 210                     | 
| 1430309011  | 4         | Avon         | * 18       | * 30            | * 2               | * 4                    | 0.0                  | 0.0                       | * 6             | 0.0                  | * 16                  | * 23                   | * 151                     | * 170                  | * 176                | * 197                     | 
| 1430309011  | 5         | Barkhamsted  | * 5        | * 8             | * 5               | * 6                    | 0.0                  | 0.0                       | 0.0             | 0.0                  | * 3                   | * 3                    | * 25                      | * 39                   | * 33                 | * 48                      | 
| 1430309011  | 6         | Beacon Falls | * 33       | * 59            | * 14              | * 31                   | 0.0                  | 0.0                       | * 3             | 0.0                  | * 10                  | * 14                   | * 84                      | * 126                  | * 112                | * 171                     | 
| 1430309011  | 7         | Berlin       | * 73       | * 126           | * 27              | * 56                   | 0.0                  | 0.0                       | * 25            | 0.0                  | * 39                  | * 64                   | * 229                     | * 320                  | * 320                | * 440                     | 
| 1430309011  | 8         | Bethany      | * 13       | * 32            | * 6               | * 19                   | 0.0                  | 0.0                       | * 1             | 0.0                  | * 7                   | * 8                    | * 31                      | * 46                   | * 45                 | * 73                      | 
| 1430309011  | 9         | Bethel       | * 89       | * 152           | * 31              | * 60                   | * 1                  | * 3                       | * 16            | 0.0                  | * 24                  | * 41                   | * 308                     | * 420                  | * 381                | * 524                     | 
| 1430309011  | 10        | Bethlehem    | * 4        | * 5             | * 3               | * 6                    | 0.0                  | 0.0                       | * 1             | 0.0                  | * 3                   | * 4                    | * 47                      | * 64                   | * 54                 | * 74                      | 
```