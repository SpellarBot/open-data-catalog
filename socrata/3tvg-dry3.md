# DSS Assistance Units and Recipients by Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dss-assistance-units-and-recipients-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/3tvg-dry3) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/3tvg-dry3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/3tvg-dry3/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 3tvg-dry3 |
| Name | DSS Assistance Units and Recipients by Town |
| Attribution | CT Department of Social Services |
| Category | Health and Human Services |
| Tags | dss, snap, medicaid, tfa, cash |
| Created | 2014-05-23T16:59:05Z |
| Publication Date | 2014-05-23T17:06:12Z |

## Description

By major Department of Social Services program categories, this report shows the number of assistance units (cases) and total recipients by town.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                              | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================= | ========= | =========== |
| No       | time           | :updated_at                                      | updated_at                                        | meta_data | meta_data   |
| Yes      | series tag     | town_name                                        | Town Name                                         | text      | text        |
| Yes      | numeric metric | snap_cases                                       | SNAP CASES                                        | number    | number      |
| Yes      | numeric metric | snap_recip                                       | SNAP RECIP.                                       | number    | number      |
| Yes      | numeric metric | tfa_regular_cases                                | TFA Regular CASES                                 | number    | number      |
| Yes      | numeric metric | tfa_regular_recip                                | TFA Regular RECIP.                                | number    | number      |
| Yes      | numeric metric | tfa_unemployed_parent_cases                      | TFA Unemployed Parent CASES                       | number    | number      |
| Yes      | numeric metric | tfa_unemployed_parent_recip                      | TFA Unemployed Parent RECIP.                      | number    | number      |
| Yes      | numeric metric | tfa_total_cases                                  | TFA TOTAL CASES                                   | number    | number      |
| Yes      | numeric metric | tfa_total_recip                                  | TFA TOTAL RECIP.                                  | number    | number      |
| Yes      | numeric metric | state_supplement_aged                            | State Supplement AGED                             | number    | number      |
| Yes      | numeric metric | state_supplement_blind                           | State Supplement BLIND                            | number    | number      |
| Yes      | numeric metric | state_supplement_disabled                        | State Supplement DISABLED                         | number    | number      |
| Yes      | numeric metric | state_supplement_total                           | State Supplement TOTAL                            | number    | number      |
| Yes      | numeric metric | total_medicaid_cases                             | Total Medicaid CASES                              | number    | number      |
| Yes      | numeric metric | total_medicaid_recip                             | Total Medicaid RECIP.                             | number    | number      |
| Yes      | numeric metric | medicaid_low_income_adults_lia_cases             | Medicaid Low-Income Adults (LIA) CASES            | number    | number      |
| Yes      | numeric metric | medicaid_low_income_adults_lia_recip             | Medicaid Low-Income Adults (LIA) RECIP.           | number    | number      |
| Yes      | numeric metric | state_administered_general_assistance_cash_cases | State Administered General Assistance Cash CASES  | number    | number      |
| Yes      | numeric metric | state_administered_general_assistance_cash_recip | State Administered General Assistance Cash RECIP. | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3tvg-dry3 d:2014-05-23T09:59:09.000Z t:town_name=Andover m:tfa_regular_recip=4 m:tfa_regular_cases=2 m:snap_cases=60 m:tfa_unemployed_parent_recip=6 m:medicaid_low_income_adults_lia_recip=26 m:tfa_total_cases=3 m:medicaid_low_income_adults_lia_cases=26 m:state_supplement_disabled=7 m:snap_recip=117 m:total_medicaid_recip=283 m:state_administered_general_assistance_cash_recip=0 m:total_medicaid_cases=145 m:tfa_total_recip=10 m:state_supplement_total=7 m:tfa_unemployed_parent_cases=1

series e:3tvg-dry3 d:2014-05-23T09:59:09.000Z t:town_name=Ansonia m:tfa_regular_recip=233 m:tfa_regular_cases=117 m:snap_cases=1547 m:tfa_unemployed_parent_recip=52 m:medicaid_low_income_adults_lia_recip=610 m:tfa_total_cases=132 m:medicaid_low_income_adults_lia_cases=610 m:state_supplement_disabled=37 m:snap_recip=3102 m:total_medicaid_recip=4707 m:state_supplement_aged=11 m:state_administered_general_assistance_cash_cases=30 m:state_administered_general_assistance_cash_recip=30 m:total_medicaid_cases=2683 m:tfa_total_recip=285 m:state_supplement_total=49 m:tfa_unemployed_parent_cases=15

series e:3tvg-dry3 d:2014-05-23T09:59:09.000Z t:town_name=Ashford m:tfa_regular_recip=25 m:tfa_regular_cases=12 m:snap_cases=162 m:tfa_unemployed_parent_recip=1 m:medicaid_low_income_adults_lia_recip=69 m:tfa_total_cases=12 m:medicaid_low_income_adults_lia_cases=69 m:state_supplement_disabled=11 m:snap_recip=329 m:total_medicaid_recip=613 m:state_supplement_aged=5 m:state_administered_general_assistance_cash_cases=6 m:state_administered_general_assistance_cash_recip=6 m:total_medicaid_cases=329 m:tfa_total_recip=26 m:state_supplement_total=17
```

## Meta Commands

```ls
metric m:snap_cases p:integer l:"SNAP CASES" t:dataTypeName=number

metric m:snap_recip p:integer l:"SNAP RECIP." t:dataTypeName=number

metric m:tfa_regular_cases p:integer l:"TFA Regular CASES" t:dataTypeName=number

metric m:tfa_regular_recip p:integer l:"TFA Regular RECIP." t:dataTypeName=number

metric m:tfa_unemployed_parent_cases p:integer l:"TFA Unemployed Parent CASES" t:dataTypeName=number

metric m:tfa_unemployed_parent_recip p:integer l:"TFA Unemployed Parent RECIP." t:dataTypeName=number

metric m:tfa_total_cases p:integer l:"TFA TOTAL CASES" t:dataTypeName=number

metric m:tfa_total_recip p:integer l:"TFA TOTAL RECIP." t:dataTypeName=number

metric m:state_supplement_aged p:integer l:"State Supplement AGED" t:dataTypeName=number

metric m:state_supplement_blind p:integer l:"State Supplement BLIND" t:dataTypeName=number

metric m:state_supplement_disabled p:integer l:"State Supplement DISABLED" t:dataTypeName=number

metric m:state_supplement_total p:integer l:"State Supplement TOTAL" t:dataTypeName=number

metric m:total_medicaid_cases p:integer l:"Total Medicaid CASES" t:dataTypeName=number

metric m:total_medicaid_recip p:integer l:"Total Medicaid RECIP." t:dataTypeName=number

metric m:medicaid_low_income_adults_lia_cases p:integer l:"Medicaid Low-Income Adults (LIA) CASES" t:dataTypeName=number

metric m:medicaid_low_income_adults_lia_recip p:integer l:"Medicaid Low-Income Adults (LIA) RECIP." t:dataTypeName=number

metric m:state_administered_general_assistance_cash_cases p:integer l:"State Administered General Assistance Cash CASES" t:dataTypeName=number

metric m:state_administered_general_assistance_cash_recip p:integer l:"State Administered General Assistance Cash RECIP." t:dataTypeName=number

entity e:3tvg-dry3 l:"DSS Assistance Units and Recipients by Town" t:attribution="CT Department of Social Services" t:url=https://data.ct.gov/api/views/3tvg-dry3

property e:3tvg-dry3 t:meta.view v:id=3tvg-dry3 v:category="Health and Human Services" v:averageRating=0 v:name="DSS Assistance Units and Recipients by Town" v:attribution="CT Department of Social Services"

property e:3tvg-dry3 t:meta.view.owner v:id=snsj-rtrj v:screenName="Alexis Fedorjaczenko" v:displayName="Alexis Fedorjaczenko"

property e:3tvg-dry3 t:meta.view.tableauthor v:id=snsj-rtrj v:screenName="Alexis Fedorjaczenko" v:displayName="Alexis Fedorjaczenko"
```

## Top Records

```ls
| :updated_at | town_name    | snap_cases | snap_recip | tfa_regular_cases | tfa_regular_recip | tfa_unemployed_parent_cases | tfa_unemployed_parent_recip | tfa_total_cases | tfa_total_recip | state_supplement_aged | state_supplement_blind | state_supplement_disabled | state_supplement_total | total_medicaid_cases | total_medicaid_recip | medicaid_low_income_adults_lia_cases | medicaid_low_income_adults_lia_recip | state_administered_general_assistance_cash_cases | state_administered_general_assistance_cash_recip | 
| =========== | ============ | ========== | ========== | ================= | ================= | =========================== | =========================== | =============== | =============== | ===================== | ====================== | ========================= | ====================== | ==================== | ==================== | ==================================== | ==================================== | ================================================ | ================================================ | 
| 1400839149  | Andover      | 60         | 117        | 2                 | 4                 | 1                           | 6                           | 3               | 10              |                       |                        | 7                         | 7                      | 145                  | 283                  | 26                                   | 26                                   |                                                  | 0                                                | 
| 1400839149  | Ansonia      | 1547       | 3102       | 117               | 233               | 15                          | 52                          | 132             | 285             | 11                    |                        | 37                        | 49                     | 2683                 | 4707                 | 610                                  | 610                                  | 30                                               | 30                                               | 
| 1400839149  | Ashford      | 162        | 329        | 12                | 25                |                             | 1                           | 12              | 26              | 5                     |                        | 11                        | 17                     | 329                  | 613                  | 69                                   | 69                                   | 6                                                | 6                                                | 
| 1400839149  | Avon         | 165        | 253        | 7                 | 10                |                             | 3                           | 7               | 13              | 7                     |                        | 8                         | 16                     | 480                  | 714                  | 82                                   | 82                                   | 6                                                | 6                                                | 
| 1400839149  | Barkhamsted  | 61         | 121        | 2                 | 3                 |                             | 1                           | 2               | 4               |                       |                        | 4                         | 4                      | 175                  | 313                  | 32                                   | 32                                   |                                                  | 0                                                | 
| 1400839149  | Beacon Falls | 137        | 239        | 7                 | 12                | 3                           | 13                          | 10              | 25              | 3                     |                        | 4                         | 7                      | 284                  | 501                  | 66                                   | 66                                   | 2                                                | 2                                                | 
| 1400839149  | Berlin       | 482        | 764        | 18                | 40                | 2                           | 7                           | 20              | 47              | 23                    |                        | 30                        | 55                     | 930                  | 1450                 | 224                                  | 224                                  | 7                                                | 7                                                | 
| 1400839149  | Bethany      | 62         | 101        | 3                 | 4                 |                             |                             | 3               | 4               | 5                     |                        | 8                         | 13                     | 158                  | 274                  | 29                                   | 29                                   | 1                                                | 1                                                | 
| 1400839149  | Bethel       | 425        | 777        | 22                | 40                | 2                           | 8                           | 24              | 48              | 12                    |                        | 11                        | 24                     | 1076                 | 1847                 | 218                                  | 218                                  | 13                                               | 13                                               | 
| 1400839149  | Bethlehem    | 67         | 108        |                   | 1                 |                             |                             |                 | 1               |                       |                        | 7                         | 7                      | 174                  | 313                  | 29                                   | 29                                   |                                                  | 0                                                | 
```