# Spending And Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spending-and-revenue-8cc3d) |
| Metadata | [Link](https://data.sfgov.org/api/views/bpnb-jwfb) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/bpnb-jwfb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/bpnb-jwfb/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | bpnb-jwfb |
| Name | Spending And Revenue |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | spending, revenue, amount, sfopenbook, open book, openbook |
| Created | 2013-04-02T20:46:47Z |
| Publication Date | 2014-10-07T16:15:22Z |

## Description

The San Francisco Controller's Office maintains a database of spending and revenue data sourced from it's citywide financial system. This data is presented on the Spending and Revenue report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on a weekly basis, and is available from fiscal year 2000 forward.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | revenue_or_spending     | Revenue or Spending     | text      | text        |
| Yes      | series tag     | related_gov_t_units     | Related Gov’t Units     | text      | text        |
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
series e:bpnb-jwfb d:1999-01-01T00:00:00.000Z t:department_code=ADP t:fund_type_code=1G t:character_code=250 t:fund_type="General Fund" t:organization_group="Public Protection" t:fund_category_code=1 t:program="Community Services" t:fund_code=1GAGF t:related_gov_t_units=No t:character="Fines, Forfeitures & Penalties" t:program_code=AKB t:sub_object_code=25210 t:fund="General Fund" t:sub_object="Court Fines" t:revenue_or_spending=Revenue t:organization_group_code=01 t:object_code=252 t:fund_category=Operating t:department="Adult Probation" t:object="Court Fines-Non Traffic" m:amount=22409.06

series e:bpnb-jwfb d:1999-01-01T00:00:00.000Z t:department_code=ADP t:fund_type_code=1G t:character_code=250 t:fund_type="General Fund" t:organization_group="Public Protection" t:fund_category_code=1 t:program="Community Services" t:fund_code=1GAGF t:related_gov_t_units=No t:character="Fines, Forfeitures & Penalties" t:program_code=AKB t:sub_object_code=25220 t:fund="General Fund" t:sub_object="Court Fines Superior" t:revenue_or_spending=Revenue t:organization_group_code=01 t:object_code=252 t:fund_category=Operating t:department="Adult Probation" t:object="Court Fines-Non Traffic" m:amount=8027.68

series e:bpnb-jwfb d:1999-01-01T00:00:00.000Z t:department_code=ADP t:fund_type_code=2S t:character_code=400 t:fund_type="Special Revenue Funds" t:organization_group="Public Protection" t:fund_category_code=4 t:program="Community Services" t:fund_code=2SPPF t:related_gov_t_units=No t:character="Intergovernmental Revenues-Federal" t:program_code=AKB t:sub_object_code=44931 t:fund="Public Protection Fund" t:sub_object="Federal Grants Pass-Through State/Other" t:revenue_or_spending=Revenue t:organization_group_code=01 t:object_code=449 t:fund_category=Grants t:department="Adult Probation" t:object=Federal-Other m:amount=131977.11
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"The amount earned (Revenue) or spent (Spending) by the City and County of San Francisco." t:dataTypeName=number

entity e:bpnb-jwfb l:"Spending And Revenue" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/bpnb-jwfb

property e:bpnb-jwfb t:meta.view d:2017-09-25T07:32:17.763Z v:averageRating=0 v:name="Spending And Revenue" v:attribution="SF Controller's Office" v:attributionLink=http://openbook.sfgov.org v:id=bpnb-jwfb v:category="City Management and Ethics"

property e:bpnb-jwfb t:meta.view.license d:2017-09-25T07:32:17.763Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:bpnb-jwfb t:meta.view.owner d:2017-09-25T07:32:17.763Z v:displayName="Alex Levitsky" v:id=9ufn-6bwh v:screenName="Alex Levitsky"

property e:bpnb-jwfb t:meta.view.tableauthor d:2017-09-25T07:32:17.763Z v:displayName="Alex Levitsky" v:roleName=editor v:id=9ufn-6bwh v:screenName="Alex Levitsky"
```

## Top Records

```ls
| fiscal_year | revenue_or_spending | related_gov_t_units | organization_group_code | organization_group | department_code | department      | program_code | program            | character_code | character                          | object_code | object                      | sub_object_code | sub_object                              | fund_type_code | fund_type             | fund_code | fund                   | fund_category_code | fund_category | amount    | 
| =========== | =================== | =================== | ======================= | ================== | =============== | =============== | ============ | ================== | ============== | ================================== | =========== | =========================== | =============== | ======================================= | ============== | ===================== | ========= | ====================== | ================== | ============= | ========= | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 250            | Fines, Forfeitures & Penalties     | 252         | Court Fines-Non Traffic     | 25210           | Court Fines                             | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 22409.06  | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 250            | Fines, Forfeitures & Penalties     | 252         | Court Fines-Non Traffic     | 25220           | Court Fines Superior                    | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 8027.68   | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 400            | Intergovernmental Revenues-Federal | 449         | Federal-Other               | 44931           | Federal Grants Pass-Through State/Other | 2S             | Special Revenue Funds | 2SPPF     | Public Protection Fund | 4                  | Grants        | 131977.11 | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 450            | Intergovernmental Revenues-State   | 489         | State - Other               | 48999           | Other State Grants & Subventions        | 2S             | Special Revenue Funds | 2SGSF     | General Services Fund  | 4                  | Grants        | -87333.00 | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 450            | Intergovernmental Revenues-State   | 489         | State - Other               | 48999           | Other State Grants & Subventions        | 2S             | Special Revenue Funds | 2SPPF     | Public Protection Fund | 4                  | Grants        | 75298.00  | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 600            | Charges for Services               | 601         | General Government Services | 60103           | Diversion Fees                          | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 28860.00  | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 600            | Charges for Services               | 601         | General Government Services | 60104           | Installment Fees                        | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 11255.00  | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 600            | Charges for Services               | 601         | General Government Services | 60107           | Court Reimbursements                    | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 1130.00   | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 600            | Charges for Services               | 601         | General Government Services | 60112           | Probation Cost                          | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 308829.14 | 
| 1999        | Revenue             | No                  | 01                      | Public Protection  | ADP             | Adult Probation | AKB          | Community Services | 600            | Charges for Services               | 601         | General Government Services | 60113           | Investigation Costs                     | 1G             | General Fund          | 1GAGF     | General Fund           | 1                  | Operating     | 38582.94  | 
```