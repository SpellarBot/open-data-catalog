# New York State Budget Vetoes: 2015-16

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-budget-vetoes-2015-16) |
| Metadata | [Link](https://data.ny.gov/api/views/xy2c-fxc5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xy2c-fxc5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xy2c-fxc5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xy2c-fxc5 |
| Name | New York State Budget Vetoes: 2015-16 |
| Attribution | Division of Budget |
| Category | Government & Finance |
| Tags | enacted budget, budget, vetoes, veto |
| Created | 2015-05-07T21:25:21Z |
| Publication Date | 2015-06-09T19:22:46Z |

## Description

This data set includes vetoed reappropriation items from the 2015-16 Enacted budget bills by veto number, agency, bill, fund type and justification.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | veto               | Veto Number        | text      | number      |
| Yes      | series tag     | agency             | Agency             | text      | text        |
| Yes      | series tag     | bill               | Bill               | text      | text        |
| Yes      | numeric metric | from_page          | Page From          | number    | number      |
| Yes      | numeric metric | to_page            | Page To            | number    | number      |
| Yes      | numeric metric | from_line          | Line From          | number    | number      |
| Yes      | numeric metric | to_line            | Line To            | number    | number      |
| Yes      | series tag     | fund_type          | Fund Type          | text      | text        |
| Yes      | series tag     | purpose            | Purpose            | text      | text        |
| Yes      | numeric metric | amount             | Amount             | number    | number      |
| Yes      | series tag     | justification_text | Justification Text | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xy2c-fxc5 d:2015-01-01T00:00:00.000Z t:fund_type=SRF t:bill="S.2000-C
A.3000-C" t:veto=1 t:justification_text="This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget.  Accordingly, this item is disapproved." t:agency=Arts t:purpose="For administration of programs funded from the national endowment  for
    the arts federal grant award.
  Nonpersonal service ... 100,000 ....................... (re. $100,000)" m:amount=100000 m:to_page=37 m:to_line=39 m:from_page=37 m:from_line=37

series e:xy2c-fxc5 d:2015-01-01T00:00:00.000Z t:fund_type=SRO t:bill="S.2000-C
A.3000-C" t:veto=2 t:justification_text="This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget.  Accordingly, this item is disapproved." t:agency=SED t:purpose="For reimbursement of tuition payments made by or on behalf of students
    at  proprietary  institutions  registered  or  licensed  pursuant to
    section 5001 of the education law,  including  liabilities  incurred
    prior to April 1, 2014.
  Contractual services ... 1,509,000 .................... (re. $500,000)" m:amount=500000 m:to_page=137 m:to_line=32 m:from_page=137 m:from_line=28

series e:xy2c-fxc5 d:2015-01-01T00:00:00.000Z t:fund_type=SRO t:bill="S.2000-C
A.3000-C" t:veto=3 t:justification_text="This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget.  Accordingly, this item is disapproved." t:agency=SED t:purpose="For  services  and expenses for the supervision of institutions regis-
    tered pursuant to  section  5001  of  the  education  law,  and  for
    services and expenses of supervisory programs and payment of associ-
    ated indirect costs and general state charges.
  Supplies and materials ... 12,000 ....................... (re. $1,000)" m:amount=1000 m:to_page=137 m:to_line=41 m:from_page=137 m:from_line=37
```

## Meta Commands

```ls
metric m:from_page p:integer l:"Page From" d:"Starting page number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:to_page p:integer l:"Page To" d:"Ending page number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:from_line p:integer l:"Line From" d:"Starting line number of the vetoed item on the starting page (Page From)." t:dataTypeName=number

metric m:to_line p:integer l:"Line To" d:"Ending line number of the vetoed item on the ending page (Page To)." t:dataTypeName=number

metric m:amount p:integer l:Amount d:"Amount of the vetoed item." t:dataTypeName=number

entity e:xy2c-fxc5 l:"New York State Budget Vetoes: 2015-16" t:attribution="Division of Budget" t:url=https://data.ny.gov/api/views/xy2c-fxc5

property e:xy2c-fxc5 t:meta.view v:id=xy2c-fxc5 v:category="Government & Finance" v:averageRating=0 v:name="New York State Budget Vetoes: 2015-16" v:attribution="Division of Budget"

property e:xy2c-fxc5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xy2c-fxc5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:xy2c-fxc5 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| veto | agency | bill              | from_page | to_page | from_line | to_line | fund_type | purpose                                                                                                                                                                                                                                                                                                                                                                                                                             | amount  | justification_text                                                                                                                                                                                                          | 
| ==== | ====== | ================= | ========= | ======= | ========= | ======= | ========= | =================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======= | =========================================================================================================================================================================================================================== | 
| 1    | Arts   | S.2000-C A.3000-C | 37        | 37      | 37        | 39      | SRF       | For administration of programs funded from the national endowment for the arts federal grant award. Nonpersonal service ... 100,000 ....................... (re. $100,000)                                                                                                                                                                                                                                                          | 100000  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 2    | SED    | S.2000-C A.3000-C | 137       | 137     | 28        | 32      | SRO       | For reimbursement of tuition payments made by or on behalf of students at proprietary institutions registered or licensed pursuant to section 5001 of the education law, including liabilities incurred prior to April 1, 2014. Contractual services ... 1,509,000 .................... (re. $500,000)                                                                                                                              | 500000  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 3    | SED    | S.2000-C A.3000-C | 137       | 137     | 37        | 41      | SRO       | For services and expenses for the supervision of institutions regis- tered pursuant to section 5001 of the education law, and for services and expenses of supervisory programs and payment of associ- ated indirect costs and general state charges. Supplies and materials ... 12,000 ....................... (re. $1,000)                                                                                                        | 1000    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 4    | SED    | S.2000-C A.3000-C | 137       | 137     | 42        | 42      | SRO       | Travel ... 40,000 ....................................... (re. $3,000)                                                                                                                                                                                                                                                                                                                                                              | 3000    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 5    | SED    | S.2000-C A.3000-C | 137       | 137     | 43        | 43      | SRO       | Contractual services ... 1,432,000 .................... (re. $200,000)                                                                                                                                                                                                                                                                                                                                                              | 200000  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 6    | SED    | S.2000-C A.3000-C | 137       | 137     | 44        | 44      | SRO       | Equipment ... 12,000 .................................... (re. $1,000)                                                                                                                                                                                                                                                                                                                                                              | 1000    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 7    | SED    | S.2000-C A.3000-C | 139       | 140     | 45        | 5       | SRO       | For services and expenses of the office of cultural education, includ- ing but not limited to the state museum, state library, and state archives. Notwithstanding any inconsistent provision of law, a portion of this appropriation may be suballocated to other state departments and agencies, as needed to accomplish the intent of this appropriation. Personal service--regular ... 14,225,000 ............ (re. $3,000,000) | 3000000 | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 8    | SED    | S.2000-C A.3000-C | 140       | 140     | 6         | 6       | SRO       | Supplies and materials ... 2,333,000 .................. (re. $130,000)                                                                                                                                                                                                                                                                                                                                                              | 130000  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 9    | SED    | S.2000-C A.3000-C | 140       | 140     | 7         | 7       | SRO       | Contractual services ... 4,319,000 .................. (re. $1,000,000)                                                                                                                                                                                                                                                                                                                                                              | 1000000 | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 10   | SED    | S.2000-C A.3000-C | 140       | 140     | 8         | 8       | SRO       | Equipment ... 1,854,000 ............................. (re. $1,000,000)                                                                                                                                                                                                                                                                                                                                                              | 1000000 | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
```