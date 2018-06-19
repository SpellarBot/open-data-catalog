# Cannabis Pesticide Guidelist

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cannabis-pesticide-guidelist) |
| Metadata | [Link](https://data.oregon.gov/api/views/b8ki-p9ef) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/b8ki-p9ef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/b8ki-p9ef/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | b8ki-p9ef |
| Name | Cannabis Pesticide Guidelist |
| Category | Natural Resources |
| Tags | cannabis, pesticides |
| Created | 2016-04-11T17:50:41Z |
| Publication Date | 2017-03-07T19:03:19Z |

## Description

The intent of the list is to assist growers in distinguishing those pesticide products whose labels do not legally prohibit use on cannabis from those that clearly do not allow use. The list is not an endorsement or recommendation to use these products in the production of cannabis in Oregon. Do not hesitate to contact Pesticides staff with questions or for label clarification.

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | =========== | ===================================== | ===================================== | ========= | =========== |
| No       | time        | :updated_at                           | updated_at                            | meta_data | meta_data   |
| Yes      | series tag  | product_name                          | PRODUCT NAME                          | text      | text        |
| Yes      | series tag  | company                               | COMPANY                               | text      | text        |
| Yes      | series tag  | epa_reg_no                            | EPA REG NO                            | text      | text        |
| Yes      | series tag  | alert                                 | *                                     | flag      | flag        |
| Yes      | series tag  | note                                  | NOTE                                  | text      | text        |
| Yes      | series tag  | active_ingredient                     | ACTIVE INGREDIENT                     | text      | text        |
| Yes      | series tag  | pesticide_type                        | PESTICIDE TYPE                        | text      | text        |
| Yes      | series tag  | ag_worker_protection_standard_applies | AG WORKER PROTECTION STANDARD APPLIES | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b8ki-p9ef d:2017-03-07T18:58:00.000Z t:active_ingredient="AMMONIUM SOAPS OF HIGHER FATTY ACIDS" t:pesticide_type="VERTEBRATE REPELLENT" t:company="GRANT LABORATORIES  INC." t:product_name="R-T-U RO-PEL DEER & RABBIT REPELLENT" t:ag_worker_protection_standard_applies=No t:epa_reg_no=8119-8-1663 m:row_number.b8ki-p9ef=1

series e:b8ki-p9ef d:2017-03-07T18:58:00.000Z t:active_ingredient=AZADIRACHTIN t:pesticide_type="INSECTICIDE, NEMATICIDE" t:company="AMVAC CHEMICAL CORP" t:product_name="AMAZIN 1.2% ME PLUS" t:ag_worker_protection_standard_applies=Yes t:epa_reg_no=5481-559 m:row_number.b8ki-p9ef=2

series e:b8ki-p9ef d:2017-03-07T18:58:00.000Z t:active_ingredient=AZADIRACHTIN t:pesticide_type="INSECTICIDE, INSECT REPELLENT" t:company="GOWAN CO." t:product_name="AZA-DIRECT BOTANICAL INSECTICIDE" t:ag_worker_protection_standard_applies=Yes t:epa_reg_no=71908-1-10163 m:row_number.b8ki-p9ef=3
```

## Meta Commands

```ls
metric m:row_number.b8ki-p9ef p:long l:"Row Number"

entity e:b8ki-p9ef l:"Cannabis Pesticide Guidelist" t:url=https://data.oregon.gov/api/views/b8ki-p9ef

property e:b8ki-p9ef t:meta.view v:id=b8ki-p9ef v:category="Natural Resources" v:averageRating=0 v:name="Cannabis Pesticide Guidelist"

property e:b8ki-p9ef t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:b8ki-p9ef t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| :updated_at | product_name                                       | company                 | epa_reg_no     | alert | note | active_ingredient                    | pesticide_type                            | ag_worker_protection_standard_applies | 
| =========== | ================================================== | ======================= | ============== | ===== | ==== | ==================================== | ========================================= | ===================================== | 
| 1488913080  | R-T-U RO-PEL DEER & RABBIT REPELLENT               | GRANT LABORATORIES INC. | 8119-8-1663    |       |      | AMMONIUM SOAPS OF HIGHER FATTY ACIDS | VERTEBRATE REPELLENT                      | No                                    | 
| 1488913080  | AMAZIN 1.2% ME PLUS                                | AMVAC CHEMICAL CORP     | 5481-559       |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE                   | Yes                                   | 
| 1488913080  | AZA-DIRECT BOTANICAL INSECTICIDE                   | GOWAN CO.               | 71908-1-10163  |       |      | AZADIRACHTIN                         | INSECTICIDE, INSECT REPELLENT             | Yes                                   | 
| 1488913080  | AZAGUARD                                           | BIOSAFE SYSTEMS LLC     | 70299-17       |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE                   | Yes                                   | 
| 1488913080  | AZAMAX BOTANICAL INSECTICIDE MITICIDE & NEMATICIDE | PARRY AMERICA           | 71908-1-81268  |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE, INSECT REPELLENT | Yes                                   | 
| 1488913080  | AZASOL                                             | ARBORJET INC            | 81899-4-74578  |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE                   | Yes                                   | 
| 1488913080  | AZATIN XL BIOLOGICAL INSECTICIDE                   | OHP INC.                | 70051-27-59807 |       |      | AZADIRACHTIN                         | INSECTICIDE                               | Yes                                   | 
| 1488913080  | AZATROL HYDRO BOTANICAL INSECTICIDE                | PBI/GORDON CORPORATION  | 2217-836       |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE, INSECT REPELLENT | No                                    | 
| 1488913080  | ECOZIN PLUS 1.2% ME                                | AMVAC CHEMICAL CORP     | 5481-559       |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE                   | Yes                                   | 
| 1488913080  | GORDONS PRO T&O AZATROL EC INSECTICIDE             | PBI/GORDON CORPORATION  | 2217-836       |       |      | AZADIRACHTIN                         | INSECTICIDE, NEMATICIDE, INSECT REPELLENT | Yes                                   | 
```