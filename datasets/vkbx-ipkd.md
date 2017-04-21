# City of Somerville Weekly Payroll Gross Wages Over 50K_2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-somerville-weekly-payroll-gross-wages-over-50k-2014) |
| Metadata | [Link](https://data.somervillema.gov/api/views/vkbx-ipkd) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/vkbx-ipkd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/vkbx-ipkd/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | vkbx-ipkd |
| Name | City of Somerville Weekly Payroll Gross Wages Over 50K_2014 |
| Attribution | Somerville Personnel Department, Payroll Division |
| Category | Finance |
| Tags | wages, payroll, personnel, budget, salaries, salary, 2014 |
| Created | 2015-11-13T16:10:20Z |
| Publication Date | 2015-11-13T16:37:55Z |

## Description

Under Massachusetts G. L. c. 66, ? 10(d), an employee?s name and place of employment may be exempt from public records disclosure if the employee or a family member was a victim of an adjudicated crime or is a victim of domestic violence, including but not limited to sexual assault or rape, or provide family planning services or provide training in family planning services, or have a court order protecting you from having your name disclosed in such a manner

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | name              | Name              | text      | text        |
| Yes      | series tag     | department_name   | Department Name   | text      | text        |
| Yes      | series tag     | title             | Title             | text      | text        |
| Yes      | numeric metric | total_gross_wages | Total Gross Wages | money     | money       |
| Yes      | numeric metric | 5_2_bb            | 5/2 BB            | money     | money       |
| Yes      | numeric metric | perf_att          | Perf Att          | money     | money       |
| Yes      | numeric metric | auto_allow        | Auto Allow        | money     | money       |
| Yes      | numeric metric | birthday          | Birthday          | money     | money       |
| Yes      | numeric metric | clothing          | Clothing          | money     | money       |
| No       |                | court_time        | Court Time        | money     | money       |
| Yes      | numeric metric | cpr               | CPR               | money     | money       |
| Yes      | numeric metric | defib_pay         | Defib Pay         | money     | money       |
| Yes      | numeric metric | detail            | Detail            | money     | money       |
| Yes      | numeric metric | shift_diff        | Shift Diff        | money     | money       |
| No       |                | dt                | DT                | money     | money       |
| Yes      | numeric metric | educ_inc          | Educ Inc          | money     | money       |
| Yes      | numeric metric | elect_pay         | Elect Pay         | money     | money       |
| Yes      | numeric metric | emd               | EMD               | money     | money       |
| Yes      | numeric metric | ex_other          | Ex Other          | money     | money       |
| Yes      | numeric metric | fluen_bon         | Fluen Bon         | money     | money       |
| Yes      | numeric metric | fsd               | FSD               | money     | money       |
| Yes      | numeric metric | gas_allowance     | Gas Allowance     | money     | money       |
| Yes      | numeric metric | o_g               | O/G               | money     | money       |
| Yes      | numeric metric | grant_ot          | Grant OT          | money     | money       |
| Yes      | numeric metric | haz_duty          | Haz Duty          | money     | money       |
| Yes      | numeric metric | hol               | Hol               | money     | money       |
| Yes      | numeric metric | matron_pay        | Matron Pay        | money     | money       |
| Yes      | numeric metric | meals             | Meals             | money     | money       |
| Yes      | numeric metric | master_fao        | Master FAO        | money     | money       |
| Yes      | numeric metric | master_ff         | Master FF         | money     | money       |
| No       |                | ot                | OT                | money     | money       |
| Yes      | numeric metric | ot2               | OT2               | money     | money       |
| Yes      | numeric metric | personal          | Personal          | money     | money       |
| Yes      | numeric metric | reg               | Reg               | money     | money       |
| Yes      | numeric metric | retro             | Retro             | money     | money       |
| Yes      | numeric metric | sick              | Sick              | money     | money       |
| Yes      | numeric metric | sick_buy_back     | Sick Buy Back     | money     | money       |
| Yes      | numeric metric | stipr             | StipR             | money     | money       |
| Yes      | numeric metric | stipnr            | StipNR            | money     | money       |
| Yes      | numeric metric | uniform           | Uniform           | money     | money       |
| Yes      | numeric metric | vacation          | Vacation          | money     | money       |
| Yes      | numeric metric | weapons           | Weapons           | money     | money       |
| Yes      | numeric metric | wmd               | WMD               | money     | money       |
| Yes      | numeric metric | extra_hol_nr      | Extra Hol NR      | money     | money       |
| Yes      | numeric metric | senior_longevity  | Senior Longevity  | money     | money       |
| Yes      | numeric metric | longevity         | Longevity         | money     | money       |
| Yes      | numeric metric | service_recog     | Service Recog     | money     | money       |
| Yes      | numeric metric | adm_leave         | Adm Leave         | money     | money       |
| Yes      | numeric metric | training_ot       | Training OT       | money     | money       |
| Yes      | numeric metric | snow_ot           | Snow OT           | money     | money       |
| Yes      | numeric metric | snow_ot2          | Snow OT2          | money     | money       |
| Yes      | numeric metric | snow_dt           | Snow DT           | money     | money       |
| Yes      | numeric metric | gym_reim          | Gym Reim          | money     | money       |
| Yes      | numeric metric | opti              | OptI              | money     | money       |
| Yes      | numeric metric | optf              | OptF              | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = court_time,dt,ot
```

## Data Commands

```ls
series e:vkbx-ipkd d:2014-01-01T00:00:00.000Z t:title="Captian + 25%" t:name="Femino, Charles" t:department_name=Police m:shift_diff=356.78 m:personal=5243.78 m:vacation=18615.41 m:total_gross_wages=207994.49 m:5_2_bb=2779.2 m:reg=140851.62 m:sick_buy_back=40147.69

series e:vkbx-ipkd d:2014-01-01T00:00:00.000Z t:title="Police Lieutenant + 25%" t:name="Vivolo, Carmine" t:department_name=Police m:hol=7809.86 m:shift_diff=7800.56 m:grant_ot=7280.04 m:total_gross_wages=206149.42 m:training_ot=8367.75 m:reg=108441.32 m:weapons=600 m:perf_att=500 m:wmd=500

series e:vkbx-ipkd d:2014-01-01T00:00:00.000Z t:title="Acting Lieutenant + 25%" t:name="Campbell, Bruce" t:department_name=Police m:hol=7228.27 m:detail=63778.28 m:shift_diff=7183.33 m:grant_ot=730.75 m:total_gross_wages=190511.43 m:training_ot=569.72 m:reg=94837.48 m:weapons=300 m:perf_att=300 m:o_g=731.14 m:wmd=500
```

## Meta Commands

```ls
metric m:total_gross_wages p:double l:"Total Gross Wages" t:dataTypeName=money

metric m:5_2_bb p:double l:"5/2 BB" t:dataTypeName=money

metric m:perf_att p:double l:"Perf Att" t:dataTypeName=money

metric m:auto_allow p:double l:"Auto Allow" t:dataTypeName=money

metric m:birthday p:double l:Birthday t:dataTypeName=money

metric m:clothing p:integer l:Clothing t:dataTypeName=money

metric m:cpr p:integer l:CPR t:dataTypeName=money

metric m:defib_pay p:double l:"Defib Pay" t:dataTypeName=money

metric m:detail p:double l:Detail t:dataTypeName=money

metric m:shift_diff p:double l:"Shift Diff" t:dataTypeName=money

metric m:educ_inc p:double l:"Educ Inc" t:dataTypeName=money

metric m:elect_pay p:integer l:"Elect Pay" t:dataTypeName=money

metric m:emd p:integer l:EMD t:dataTypeName=money

metric m:ex_other p:double l:"Ex Other" t:dataTypeName=money

metric m:fluen_bon p:integer l:"Fluen Bon" t:dataTypeName=money

metric m:fsd p:integer l:FSD t:dataTypeName=money

metric m:gas_allowance p:double l:"Gas Allowance" t:dataTypeName=money

metric m:o_g p:double l:O/G t:dataTypeName=money

metric m:grant_ot p:double l:"Grant OT" t:dataTypeName=money

metric m:haz_duty p:integer l:"Haz Duty" t:dataTypeName=money

metric m:hol p:double l:Hol t:dataTypeName=money

metric m:matron_pay p:double l:"Matron Pay" t:dataTypeName=money

metric m:meals p:integer l:Meals t:dataTypeName=money

metric m:master_fao p:integer l:"Master FAO" t:dataTypeName=money

metric m:master_ff p:integer l:"Master FF" t:dataTypeName=money

metric m:ot2 p:double l:OT2 t:dataTypeName=money

metric m:personal p:double l:Personal t:dataTypeName=money

metric m:reg p:double l:Reg t:dataTypeName=money

metric m:retro p:double l:Retro t:dataTypeName=money

metric m:sick p:double l:Sick t:dataTypeName=money

metric m:sick_buy_back p:double l:"Sick Buy Back" t:dataTypeName=money

metric m:stipr p:double l:StipR t:dataTypeName=money

metric m:stipnr p:integer l:StipNR t:dataTypeName=money

metric m:uniform p:integer l:Uniform t:dataTypeName=money

metric m:vacation p:double l:Vacation t:dataTypeName=money

metric m:weapons p:integer l:Weapons t:dataTypeName=money

metric m:wmd p:integer l:WMD t:dataTypeName=money

metric m:extra_hol_nr p:integer l:"Extra Hol NR" t:dataTypeName=money

metric m:senior_longevity p:integer l:"Senior Longevity" t:dataTypeName=money

metric m:longevity p:double l:Longevity t:dataTypeName=money

metric m:service_recog p:integer l:"Service Recog" t:dataTypeName=money

metric m:adm_leave p:double l:"Adm Leave" t:dataTypeName=money

metric m:training_ot p:double l:"Training OT" t:dataTypeName=money

metric m:snow_ot p:double l:"Snow OT" t:dataTypeName=money

metric m:snow_ot2 p:double l:"Snow OT2" t:dataTypeName=money

metric m:snow_dt p:double l:"Snow DT" t:dataTypeName=money

metric m:gym_reim p:integer l:"Gym Reim" t:dataTypeName=money

metric m:opti p:double l:OptI t:dataTypeName=money

metric m:optf p:double l:OptF t:dataTypeName=money

entity e:vkbx-ipkd l:"City of Somerville Weekly Payroll Gross Wages Over 50K_2014" t:attribution="Somerville Personnel Department, Payroll Division" t:url=https://data.somervillema.gov/api/views/vkbx-ipkd

property e:vkbx-ipkd t:meta.view v:id=vkbx-ipkd v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/personnel v:averageRating=0 v:name="City of Somerville Weekly Payroll Gross Wages Over 50K_2014" v:attribution="Somerville Personnel Department, Payroll Division"

property e:vkbx-ipkd t:meta.view.owner v:id=x7b9-bdhv v:screenName=SStewart v:displayName=SStewart

property e:vkbx-ipkd t:meta.view.tableauthor v:id=x7b9-bdhv v:screenName=SStewart v:roleName=administrator v:displayName=SStewart
```

## Top Records

```ls
| name                  | department_name | title                    | total_gross_wages | 5_2_bb | perf_att | auto_allow | birthday | clothing | court_time | cpr | defib_pay | detail   | shift_diff | dt | educ_inc | elect_pay | emd | ex_other | fluen_bon | fsd | gas_allowance | o_g    | grant_ot | haz_duty | hol     | matron_pay | meals | master_fao | master_ff | ot       | ot2 | personal | reg       | retro | sick | sick_buy_back | stipr | stipnr | uniform | vacation | weapons | wmd | extra_hol_nr | senior_longevity | longevity | service_recog | adm_leave | training_ot | snow_ot | snow_ot2 | snow_dt | gym_reim | opti | optf    | 
| ===================== | =============== | ======================== | ================= | ====== | ======== | ========== | ======== | ======== | ========== | === | ========= | ======== | ========== | == | ======== | ========= | === | ======== | ========= | === | ============= | ====== | ======== | ======== | ======= | ========== | ===== | ========== | ========= | ======== | === | ======== | ========= | ===== | ==== | ============= | ===== | ====== | ======= | ======== | ======= | === | ============ | ================ | ========= | ============= | ========= | =========== | ======= | ======== | ======= | ======== | ==== | ======= | 
| Femino, Charles       | Police          | Captian + 25%            | 207994.49         | 2779.2 |          |            |          |          |            |     |           |          | 356.78     |    |          |           |     |          |           |     |               |        |          |          |         |            |       |            |           |          |     | 5243.78  | 140851.62 |       |      | 40147.69      |       |        |         | 18615.41 |         |     |              |                  |           |               |           |             |         |          |         |          |      |         | 
| Vivolo, Carmine       | Police          | Police Lieutenant + 25%  | 206149.42         |        | 500      |            |          |          | 1338.84    |     |           |          | 7800.56    |    |          |           |     |          |           |     |               |        | 7280.04  |          | 7809.86 |            |       |            |           | 63511.05 |     |          | 108441.32 |       |      |               |       |        |         |          | 600     | 500 |              |                  |           |               |           | 8367.75     |         |          |         |          |      |         | 
| Campbell, Bruce       | Police          | Acting Lieutenant + 25%  | 190511.43         |        | 300      |            |          |          | 640.92     |     |           | 63778.28 | 7183.33    |    |          |           |     |          |           |     |               | 731.14 | 730.75   |          | 7228.27 |            |       |            |           | 13711.54 |     |          | 94837.48  |       |      |               |       |        |         |          | 300     | 500 |              |                  |           |               |           | 569.72      |         |          |         |          |      |         | 
| Hallinan, William     | Fire            | Deputy Chief             | 188290.40         |        | 500      |            |          |          |            |     |           | 5698     |            |    |          |           |     |          |           |     |               |        | 3775.24  | 9000     | 8389.04 |            |       |            |           | 30152.72 |     |          | 124752.67 |       |      |               |       |        |         |          |         |     |              |                  |           |               |           | 6022.74     |         |          |         |          |      |         | 
| Marino, John          | Police          | Interim Lieutenant + 20% | 186437.19         |        |          |            |          |          | 1799.73    |     |           | 34009.58 | 8057.95    |    |          |           |     |          |           |     |               | 829.51 | 642.64   |          | 7497.46 |            |       |            |           | 29550.89 |     |          | 101121.52 |       |      |               |       |        |         |          | 500     | 500 |              |                  |           |               |           | 1927.91     |         |          |         |          |      |         | 
| Fallon, David         | Police          | Police Chief             | 183189.41         | 2779.2 | 300      |            |          |          |            |     |           | 4911.72  |            |    |          |           |     |          |           |     |               |        |          |          |         |            |       |            |           |          |     |          | 171198.53 |       |      |               |       |        |         |          |         |     |              |                  |           |               |           |             |         |          |         |          |      | 3999.96 | 
| Jean-Jacques Jr, Yvon | Police          | Police Officer           | 180157.75         |        |          |            |          |          |            |     |           | 80628.14 | 7848.96    |    |          |           |     |          |           |     |               |        | 885.74   |          | 5381.93 |            |       |            |           | 9632.28  |     |          | 74337.84  |       |      |               |       |        |         |          | 500     | 500 |              |                  |           |               |           | 442.86      |         |          |         |          |      |         | 
| Cicerone, Fernando    | Police          | Police Officer           | 175072.45         |        |          |            |          |          | 7207.85    |     |           | 60823.28 | 7848.96    |    |          |           |     |          |           |     |               |        | 2652.36  |          | 5381.94 |            |       |            |           | 13147.31 |     |          | 74729.2   |       |      |               |       |        |         |          | 475     | 500 |              |                  |           |               |           | 2306.55     |         |          |         |          |      |         | 
| Cabral, Michael       | Police          | Captain                  | 170513.49         |        |          |            |          |          |            |     |           | 6375     | 1783.86    |    |          |           |     |          |           |     |               |        |          |          | 3277.36 |            |       |            |           | 1474.81  |     |          | 157102.46 |       |      |               |       |        |         |          |         | 500 |              |                  |           |               |           |             |         |          |         |          |      |         | 
| Trant, Paul           | Police          | Deputy Chief             | 167563.15         | 5558.4 | 500      |            |          |          |            |     |           | 10015    | 5351.58    |    |          |           |     |          |           |     |               |        |          |          | 6554.72 |            |       |            |           | 1769.76  |     |          | 136813.69 |       |      |               |       |        |         |          | 1000    |     |              |                  |           |               |           |             |         |          |         |          |      |         | 
```