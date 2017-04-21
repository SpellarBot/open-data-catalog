# School Budget Overview

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-budget-overview) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ven4-h25u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ven4-h25u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ven4-h25u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ven4-h25u |
| Name | School Budget Overview |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | education, funding |
| Created | 2015-10-15T21:16:21Z |
| Publication Date | 2015-10-19T19:35:32Z |

## Description

This budget overview represents the New York City Fair Student Formula school budget allocation from July 2014 - June 2015.
Click Here for further information- http://schools.nyc.gov/offices/d_chanc_oper/budget/dbor/allocationmemo/fy14_15/Fair_School_Funding_FY2015.html

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================== | ============= | ============= |
| No       |                | fiscal_year                      | Fiscal_Year                        | number        | text          |
| Yes      | series tag     | location                         | Location                           | text          | text          |
| Yes      | numeric metric | s1_label_a_fy14_revised_base     | S1: Label a: FY14 Revised Base     | money         | money         |
| Yes      | numeric metric | s1_label_b_fsf_tl_09_c4e_ctt     | S1: Label b: FSF & TL 09 C4E CTT   | money         | money         |
| Yes      | numeric metric | s1_label_c_fsf_over_formula      | S1: Label c: FSF Over Formula      | money         | money         |
| Yes      | numeric metric | s2_label_d_fsf_preliminary       | S2: Label d: FSF Preliminary       | money         | money         |
| Yes      | numeric metric | s2_label_a_fy14_revised_base     | S2: Label a: FY14 Revised Base     | money         | money         |
| Yes      | numeric metric | s2_label_f_register_change       | S2: Label f: Register Change       | money         | money         |
| Yes      | numeric metric | s2_label_g_teacher_salary_growth | S2: Label g: Teacher Salary Growth | money         | money         |
| Yes      | numeric metric | s2_label_h_new_school_foundation | S2: Label h: New School Foundation | money         | money         |
| Yes      | numeric metric | s3_label_i_fy14_fsf_at_100       | S3: Label i: FY14 FSF at 100%      | money         | money         |
| Yes      | numeric metric | s3_foundation                    | S3: Foundation                     | money         | money         |
| Yes      | numeric metric | s3_label_d_foundation            | S3: Label d - Foundation           | money         | money         |
| Yes      | numeric metric | s3_label_i_foundation            | S3: Label i - Foundation           | money         | money         |
| Yes      | numeric metric | s3_label_j_fsf_final             | S3: Label j: FSF Final%            | number        | number        |
| Yes      | numeric metric | s4_label_d_fy14_fsf_initial      | S4: Label d: FY14 FSF Initial      | money         | money         |
| Yes      | numeric metric | s4_ac_name_fsf_hs                | S4: AC Name: FSF (HS)              | money         | money         |
| Yes      | numeric metric | s4_ac_name_tl09_c4e_ctt_hs       | S4: AC Name: TL09 C4E CTT (HS)     | money         | money         |
| Yes      | numeric metric | s4_ac_name_funds_over_formula    | S4: AC Name: Funds Over Formula    | money         | money         |
| Yes      | numeric metric | s5_tl_se_transitional_funding    | S5: TL SE Transitional Funding     | money         | money         |
| Yes      | time           | as_of_date                       | As_Of_Date                         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:ven4-h25u d:2014-05-29T00:00:00.000Z t:location=K001 m:s1_label_a_fy14_revised_base=5957603 m:s3_label_i_fy14_fsf_at_100=7081416.99 m:s4_ac_name_fsf_hs=5858476 m:s5_tl_se_transitional_funding=0 m:s4_ac_name_tl09_c4e_ctt_hs=0 m:s2_label_a_fy14_revised_base=5957603 m:s1_label_b_fsf_tl_09_c4e_ctt=5957603 m:s3_label_i_foundation=6856416.99 m:s3_foundation=225000 m:s1_label_c_fsf_over_formula=0 m:s4_label_d_fy14_fsf_initial=5858476 m:s2_label_h_new_school_foundation=0 m:s2_label_d_fsf_preliminary=5858476.18 m:s3_label_j_fsf_final=0.8216 m:s3_label_d_foundation=5633476.18 m:s4_ac_name_funds_over_formula=0 m:s2_label_g_teacher_salary_growth=0 m:s2_label_f_register_change=-99126.82

series e:ven4-h25u d:2014-05-29T00:00:00.000Z t:location=K002 m:s1_label_a_fy14_revised_base=2565500 m:s3_label_i_fy14_fsf_at_100=3037276.59 m:s4_ac_name_fsf_hs=2514001 m:s5_tl_se_transitional_funding=104611 m:s4_ac_name_tl09_c4e_ctt_hs=0 m:s2_label_a_fy14_revised_base=2565500 m:s1_label_b_fsf_tl_09_c4e_ctt=2565500 m:s3_label_i_foundation=2812276.59 m:s3_foundation=225000 m:s1_label_c_fsf_over_formula=0 m:s4_label_d_fy14_fsf_initial=2514001 m:s2_label_h_new_school_foundation=0 m:s2_label_d_fsf_preliminary=2514000.62 m:s3_label_j_fsf_final=0.8139 m:s3_label_d_foundation=2289000.62 m:s4_ac_name_funds_over_formula=0 m:s2_label_g_teacher_salary_growth=0 m:s2_label_f_register_change=-51499.38

series e:ven4-h25u d:2014-05-29T00:00:00.000Z t:location=K003 m:s1_label_a_fy14_revised_base=2364807 m:s3_label_i_fy14_fsf_at_100=2450195.3 m:s4_ac_name_fsf_hs=2104797 m:s5_tl_se_transitional_funding=37397 m:s4_ac_name_tl09_c4e_ctt_hs=71738 m:s2_label_a_fy14_revised_base=2364807 m:s1_label_b_fsf_tl_09_c4e_ctt=2364807 m:s3_label_i_foundation=2225195.3 m:s3_foundation=225000 m:s1_label_c_fsf_over_formula=0 m:s4_label_d_fy14_fsf_initial=2176535 m:s2_label_h_new_school_foundation=0 m:s2_label_d_fsf_preliminary=2176535.16 m:s3_label_j_fsf_final=0.877 m:s3_label_d_foundation=1951535.16 m:s4_ac_name_funds_over_formula=0 m:s2_label_g_teacher_salary_growth=0 m:s2_label_f_register_change=-188271.84
```

## Meta Commands

```ls
metric m:s1_label_a_fy14_revised_base p:double l:"S1: Label a: FY14 Revised Base" t:dataTypeName=money

metric m:s1_label_b_fsf_tl_09_c4e_ctt p:double l:"S1: Label b: FSF & TL 09 C4E CTT" t:dataTypeName=money

metric m:s1_label_c_fsf_over_formula p:double l:"S1: Label c: FSF Over Formula" t:dataTypeName=money

metric m:s2_label_d_fsf_preliminary p:double l:"S2: Label d: FSF Preliminary" t:dataTypeName=money

metric m:s2_label_a_fy14_revised_base p:double l:"S2: Label a: FY14 Revised Base" t:dataTypeName=money

metric m:s2_label_f_register_change p:double l:"S2: Label f: Register Change" t:dataTypeName=money

metric m:s2_label_g_teacher_salary_growth p:double l:"S2: Label g: Teacher Salary Growth" t:dataTypeName=money

metric m:s2_label_h_new_school_foundation p:double l:"S2: Label h: New School Foundation" t:dataTypeName=money

metric m:s3_label_i_fy14_fsf_at_100 p:double l:"S3: Label i: FY14 FSF at 100%" t:dataTypeName=money

metric m:s3_foundation p:double l:"S3: Foundation" t:dataTypeName=money

metric m:s3_label_d_foundation p:double l:"S3: Label d - Foundation" t:dataTypeName=money

metric m:s3_label_i_foundation p:double l:"S3: Label i - Foundation" t:dataTypeName=money

metric m:s3_label_j_fsf_final p:float l:"S3: Label j: FSF Final%" t:dataTypeName=number

metric m:s4_label_d_fy14_fsf_initial p:double l:"S4: Label d: FY14 FSF Initial" t:dataTypeName=money

metric m:s4_ac_name_fsf_hs p:double l:"S4: AC Name: FSF (HS)" t:dataTypeName=money

metric m:s4_ac_name_tl09_c4e_ctt_hs p:double l:"S4: AC Name: TL09 C4E CTT (HS)" t:dataTypeName=money

metric m:s4_ac_name_funds_over_formula p:double l:"S4: AC Name: Funds Over Formula" t:dataTypeName=money

metric m:s5_tl_se_transitional_funding p:double l:"S5: TL SE Transitional Funding" t:dataTypeName=money

entity e:ven4-h25u l:"School Budget Overview" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ven4-h25u

property e:ven4-h25u t:meta.view v:id=ven4-h25u v:category=Education v:averageRating=0 v:name="School Budget Overview" v:attribution="Department of Education (DOE)"

property e:ven4-h25u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ven4-h25u t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| fiscal_year | location | s1_label_a_fy14_revised_base | s1_label_b_fsf_tl_09_c4e_ctt | s1_label_c_fsf_over_formula | s2_label_d_fsf_preliminary | s2_label_a_fy14_revised_base | s2_label_f_register_change | s2_label_g_teacher_salary_growth | s2_label_h_new_school_foundation | s3_label_i_fy14_fsf_at_100 | s3_foundation | s3_label_d_foundation | s3_label_i_foundation | s3_label_j_fsf_final | s4_label_d_fy14_fsf_initial | s4_ac_name_fsf_hs | s4_ac_name_tl09_c4e_ctt_hs | s4_ac_name_funds_over_formula | s5_tl_se_transitional_funding | as_of_date          | 
| =========== | ======== | ============================ | ============================ | =========================== | ========================== | ============================ | ========================== | ================================ | ================================ | ========================== | ============= | ===================== | ===================== | ==================== | =========================== | ================= | ========================== | ============================= | ============================= | =================== | 
| 2015        | K001     | 5957603.00                   | 5957603.00                   | 0.00                        | 5858476.18                 | 5957603.00                   | -99126.82                  | 0.00                             | 0.00                             | 7081416.99                 | 225000.00     | 5633476.18            | 6856416.99            | 0.8216               | 5858476.00                  | 5858476.00        | 0.00                       | 0.00                          | 0.00                          | 2014-05-29T00:00:00 | 
| 2015        | K002     | 2565500.00                   | 2565500.00                   | 0.00                        | 2514000.62                 | 2565500.00                   | -51499.38                  | 0.00                             | 0.00                             | 3037276.59                 | 225000.00     | 2289000.62            | 2812276.59            | 0.8139               | 2514001.00                  | 2514001.00        | 0.00                       | 0.00                          | 104611.00                     | 2014-05-29T00:00:00 | 
| 2015        | K003     | 2364807.00                   | 2364807.00                   | 0.00                        | 2176535.16                 | 2364807.00                   | -188271.84                 | 0.00                             | 0.00                             | 2450195.30                 | 225000.00     | 1951535.16            | 2225195.30            | 0.877                | 2176535.00                  | 2104797.00        | 71738.00                   | 0.00                          | 37397.00                      | 2014-05-29T00:00:00 | 
| 2015        | K005     | 1711158.00                   | 1711158.00                   | 0.00                        | 1589001.81                 | 1711158.00                   | -122156.19                 | 0.00                             | 0.00                             | 1707282.85                 | 225000.00     | 1364001.81            | 1482282.85            | 0.9202               | 1589002.00                  | 1589002.00        | 0.00                       | 0.00                          | 18339.00                      | 2014-05-29T00:00:00 | 
| 2015        | K006     | 3771012.00                   | 3771012.00                   | 0.00                        | 3634372.42                 | 3771012.00                   | -136639.58                 | 0.00                             | 0.00                             | 4124758.11                 | 225000.00     | 3409372.42            | 3899758.11            | 0.8743               | 3634373.00                  | 3562635.00        | 71738.00                   | 0.00                          | 15830.00                      | 2014-05-29T00:00:00 | 
| 2015        | K007     | 4782292.00                   | 4782292.00                   | 0.00                        | 4770204.36                 | 4782292.00                   | -12087.64                  | 0.00                             | 0.00                             | 5763700.52                 | 225000.00     | 4545204.36            | 5538700.52            | 0.8206               | 4770205.00                  | 4770205.00        | 0.00                       | 0.00                          | 23172.00                      | 2014-05-29T00:00:00 | 
| 2015        | K008     | 3578829.00                   | 3578829.00                   | 0.00                        | 4014764.53                 | 3578829.00                   | 435935.53                  | 0.00                             | 0.00                             | 4701192.14                 | 225000.00     | 3789764.53            | 4476192.14            | 0.8466               | 4014765.00                  | 4014765.00        | 0.00                       | 0.00                          | 0.00                          | 2014-05-29T00:00:00 | 
| 2015        | K009     | 3065347.00                   | 3065347.00                   | 0.00                        | 3197867.30                 | 3065347.00                   | 132520.30                  | 0.00                             | 0.00                             | 3771140.74                 | 225000.00     | 2972867.30            | 3546140.74            | 0.8383               | 3197867.00                  | 3197867.00        | 0.00                       | 0.00                          | 61339.00                      | 2014-05-29T00:00:00 | 
| 2015        | K010     | 4345806.00                   | 4345806.00                   | 0.00                        | 4354146.06                 | 4345806.00                   | 8340.06                    | 0.00                             | 0.00                             | 5171803.29                 | 225000.00     | 4129146.06            | 4946803.29            | 0.8347               | 4354146.00                  | 4354146.00        | 0.00                       | 0.00                          | 4066.00                       | 2014-05-29T00:00:00 | 
| 2015        | K011     | 3268172.00                   | 3268172.00                   | 0.00                        | 3401865.35                 | 3268172.00                   | 133693.35                  | 0.00                             | 0.00                             | 3569565.49                 | 225000.00     | 3176865.35            | 3344565.49            | 0.9499               | 3401865.00                  | 3401865.00        | 0.00                       | 0.00                          | 0.00                          | 2014-05-29T00:00:00 | 
```