# Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fd792) |
| Metadata | [Link](https://data.sfgov.org/api/views/xdgd-c79v) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/xdgd-c79v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/xdgd-c79v/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | xdgd-c79v |
| Name | Budget |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | budget, sfopenbook, open book, openbook |
| Created | 2013-05-30T18:58:52Z |
| Publication Date | 2014-10-07T16:07:36Z |

## Description

The San Francisco Controller's Office maintains a database of budgetary data that appears in summarized form in each Annual Appropriation Ordinance (AAO). This data is presented on the Budget report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on an annual basis when the AAO is published for each new fiscal year. Data is available from fiscal year 2010 forward.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | revenue_or_spending     | Revenue or Spending     | text      | text        |
| Yes      | series tag     | related_gov_t_unit      | Related Gov't Unit      | text      | text        |
| Yes      | series tag     | organization_group_code | Organization Group Code | text      | text        |
| Yes      | series tag     | organization_group      | Organization Group      | text      | text        |
| Yes      | series tag     | department_code         | Department Code         | text      | text        |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | series tag     | program_code            | Program Code            | text      | text        |
| Yes      | series tag     | program                 | Program                 | text      | text        |
| Yes      | series tag     | character_code          | Character Code          | text      | text        |
| Yes      | series tag     | character               | Character               | text      | text        |
| Yes      | series tag     | object_code             | Object Code             | text      | text        |
| Yes      | series tag     | object                  | Object                  | text      | text        |
| Yes      | series tag     | sub_object_code         | Sub-object Code         | text      | text        |
| Yes      | series tag     | sub_object              | Sub-object              | text      | text        |
| Yes      | series tag     | fund_type_code          | Fund Type Code          | text      | text        |
| Yes      | series tag     | fund_type               | Fund Type               | text      | text        |
| Yes      | series tag     | fund_code               | Fund Code               | text      | text        |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | series tag     | fund_category_code      | Fund Category Code      | text      | text        |
| Yes      | series tag     | fund_category           | Fund Category           | text      | text        |
| Yes      | numeric metric | amount                  | Amount                  | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xdgd-c79v d:2013-01-01T00:00:00.000Z t:organization_group="General Administration & Finance" t:fund_type="General Fund" t:fund_code=1GAGF t:program_code=FDL t:department=Assessor/Recorder t:revenue_or_spending=Spending t:sub_object="Office Machine Rental" t:object="Rents & Leases-Equipment" t:object_code=031 t:fund_type_code=1G t:character="Non Personnel Services" t:character_code=021 t:fund_category_code=1 t:program="Technical Services" t:fund_category=Operating t:sub_object_code=03131 t:fund="General Fund" t:department_code=ASR t:organization_group_code=06 t:related_gov_t_unit=No m:amount=28840

series e:xdgd-c79v d:2015-01-01T00:00:00.000Z t:organization_group="Human Welfare & Neighborhood Development" t:fund_type="General Fund" t:fund_code=1GAGF t:program_code=XXX t:department="Human Services" t:revenue_or_spending=Spending t:sub_object="Transfer Adjustments-Uses" t:object="Transfer Adjustments-Uses" t:object_code=ELU t:fund_type_code=1G t:character="Transfer Adjustments-Uses" t:character_code=ELU t:fund_category_code=1 t:program="No Program Defined" t:fund_category=Operating t:sub_object_code=ELIMUD t:fund="General Fund" t:department_code=DSS t:organization_group_code=03 t:related_gov_t_unit=No m:amount=-17045799

series e:xdgd-c79v d:2013-01-01T00:00:00.000Z t:organization_group="General Administration & Finance" t:fund_type="Special Revenue Funds" t:fund_code=2SGSF t:program_code=FDE t:department="Human Resources" t:revenue_or_spending=Spending t:sub_object=Misc-Regular t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=2S t:character=Salaries t:character_code=001 t:fund_category_code=1 t:program="Workers Compensation" t:fund_category=Operating t:sub_object_code=00101 t:fund="General Services Fund" t:department_code=HRD t:organization_group_code=06 t:related_gov_t_unit=No m:amount=3547603
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount d:"The amount published in the City and County of San Francisco's Annual Appropriation Ordinance." t:dataTypeName=number

entity e:xdgd-c79v l:Budget t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/xdgd-c79v

property e:xdgd-c79v t:meta.view v:id=xdgd-c79v v:category="City Management and Ethics" v:attributionLink=http://openbook.sfgov.org v:averageRating=0 v:name=Budget v:attribution="SF Controller's Office"

property e:xdgd-c79v t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:xdgd-c79v t:meta.view.owner v:id=9ufn-6bwh v:screenName="Jeff Pera" v:displayName="Jeff Pera"

property e:xdgd-c79v t:meta.view.tableauthor v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```

## Top Records

```ls
| fiscal_year | revenue_or_spending | related_gov_t_unit | organization_group_code | organization_group                       | department_code | department                     | program_code | program                    | character_code | character                    | object_code | object                              | sub_object_code | sub_object                           | fund_type_code | fund_type             | fund_code | fund                                  | fund_category_code | fund_category | amount    | 
| =========== | =================== | ================== | ======================= | ======================================== | =============== | ============================== | ============ | ========================== | ============== | ============================ | =========== | =================================== | =============== | ==================================== | ============== | ===================== | ========= | ===================================== | ================== | ============= | ========= | 
| 2013        | Spending            | No                 | 06                      | General Administration & Finance         | ASR             | Assessor/Recorder              | FDL          | Technical Services         | 021            | Non Personnel Services       | 031         | Rents & Leases-Equipment            | 03131           | Office Machine Rental                | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | 28840     | 
| 2015        | Spending            | No                 | 03                      | Human Welfare & Neighborhood Development | DSS             | Human Services                 | XXX          | No Program Defined         | ELU            | Transfer Adjustments-Uses    | ELU         | Transfer Adjustments-Uses           | ELIMUD          | Transfer Adjustments-Uses            | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | -17045799 | 
| 2013        | Spending            | No                 | 06                      | General Administration & Finance         | HRD             | Human Resources                | FDE          | Workers Compensation       | 001            | Salaries                     | 001         | Permanent Salaries-Misc             | 00101           | Misc-Regular                         | 2S             | Special Revenue Funds | 2SGSF     | General Services Fund                 | 1                  | Operating     | 3547603   | 
| 2016        | Spending            | No                 | 05                      | Culture & Recreation                     | REC             | Recreation and Park Commission | EAP          | Parks                      | 013            | Mandatory Fringe Benefits    | 014         | Social Security                     | 01402           | Social Security - Medicare (HI Only) | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | 198703    | 
| 2016        | Spending            | No                 | 03                      | Human Welfare & Neighborhood Development | ENV             | Environment                    | CIG          | Environment                | 021            | Non Personnel Services       | 035         | Other Current Expenses              | 03581           | Advertising                          | 2S             | Special Revenue Funds | 2SENV     | Environmental Protection Program Fund | 1                  | Operating     | 598       | 
| 2015        | Revenue             | No                 | 03                      | Human Welfare & Neighborhood Development | DSS             | Human Services                 | XXX          | No Program Defined         | ELS            | Transfer Adjustments-Sources | ELS         | Transfer Adjustments-Sources        | ELIMSD          | Transfer Adjustments-Sources         | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | -17045799 | 
| 2016        | Spending            | No                 | 01                      | Public Protection                        | ADP             | Adult Probation                | AOS          | One Stop Re Entry Services | 013            | Mandatory Fringe Benefits    | 017         | Unemployment Insurance              | 01701           | Unemployment Insurance               | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | 2004      | 
| 2015        | Spending            | No                 | 03                      | Human Welfare & Neighborhood Development | DSS             | Human Services                 | XXX          | No Program Defined         | 091            | Operating Transfers Out      | 093         | Other Operating Transfers Out (Oto) | 0932K           | OTO to 2S/HWF-Human Welfare Fund     | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | 2680915   | 
| 2013        | Revenue             | No                 | 03                      | Human Welfare & Neighborhood Development | DSS             | Human Services                 | XXX          | No Program Defined         | ELS            | Transfer Adjustments-Sources | ELS         | Transfer Adjustments-Sources        | ELIMSD          | Transfer Adjustments-Sources         | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | -16190156 | 
| 2015        | Spending            | No                 | 03                      | Human Welfare & Neighborhood Development | DSS             | Human Services                 | XXX          | No Program Defined         | 095            | Intrafund Transfers Out      | 095         | Intrafund Transfers Out (Ito)       | 0951G           | ITO to 1G-General Fund               | 1G             | General Fund          | 1GAGF     | General Fund                          | 1                  | Operating     | 14364884  | 
```