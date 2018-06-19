# New York State Budget Vetoes: 2016-17

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-budget-vetoes-2016-17) |
| Metadata | [Link](https://data.ny.gov/api/views/ht4x-zbvr) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ht4x-zbvr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ht4x-zbvr/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ht4x-zbvr |
| Name | New York State Budget Vetoes: 2016-17 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | enacted budget, budget, vetoes, veto |
| Created | 2016-06-02T21:16:40Z |
| Publication Date | 2016-06-02T21:27:35Z |

## Description

This data set includes vetoed reappropriation items from the 2016-17 Enacted budget bills by veto number, agency, bill, fund type and justification.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | veto_number        | Veto Number        | text      | number      |
| Yes      | series tag     | agency             | Agency             | text      | text        |
| Yes      | series tag     | bill               | Bill               | text      | text        |
| Yes      | numeric metric | page_from          | Page From          | number    | number      |
| Yes      | numeric metric | page_to            | Page To            | number    | number      |
| Yes      | numeric metric | line_from          | Line From          | number    | number      |
| Yes      | numeric metric | line_to            | Line To            | number    | number      |
| Yes      | series tag     | fund_type          | Fund Type          | text      | text        |
| Yes      | series tag     | purpose            | Purpose            | text      | text        |
| Yes      | numeric metric | amount             | Amount             | number    | number      |
| Yes      | series tag     | justification_text | Justification Text | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ht4x-zbvr d:2016-01-01T00:00:00.000Z t:fund_type=SRO t:bill="S.6400--D
A.9000--D" t:justification_text="This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget.  Accordingly, this item is disapproved." t:agency=SED t:veto_number=1 t:purpose="For reimbursement of tuition payments made by or on behalf of students
    at proprietary  institutions  registered  or  licensed  pursuant  to
    section  5001  of  the education law, including liabilities incurred
    prior to April 1, 2015.
  Fringe benefits ... 1,309,000 ....................... (re. $1,272,000)" m:amount=1272000 m:page_to=124 m:line_from=22 m:line_to=26 m:page_from=124

series e:ht4x-zbvr d:2016-01-01T00:00:00.000Z t:fund_type=SRO t:bill="S.6400--D
A.9000--D" t:justification_text="This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget.  Accordingly, this item is disapproved." t:agency=SED t:veto_number=2 t:purpose="For services and expenses for the supervision of  institutions  regis-
    tered  pursuant  to  section  5001  of  the  education  law, and for
    services and expenses of supervisory programs and payment of associ-
    ated indirect costs and general state charges.
  Personal service--regular ... 1,747,000 ............... (re. $200,000)" m:amount=200000 m:page_to=124 m:line_from=31 m:line_to=35 m:page_from=124

series e:ht4x-zbvr d:2016-01-01T00:00:00.000Z t:fund_type=SRO t:bill="S.6400--D
A.9000--D" t:justification_text="This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget.  Accordingly, this item is disapproved." t:agency=SED t:veto_number=3 t:purpose="Supplies and materials ... 12,000 ....................... (re. $2,700)" m:amount=2700 m:page_to=124 m:line_from=36 m:line_to=36 m:page_from=124
```

## Meta Commands

```ls
metric m:page_from p:integer l:"Page From" d:"Starting page number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:page_to p:integer l:"Page To" d:"Ending page number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:line_from p:integer l:"Line From" d:"Starting line number of the vetoed item on the starting page (Page From)." t:dataTypeName=number

metric m:line_to p:integer l:"Line To" d:"Ending line number of the vetoed item on the ending page (Page To)." t:dataTypeName=number

metric m:amount p:integer l:Amount d:"Amount of the vetoed item." t:dataTypeName=number

entity e:ht4x-zbvr l:"New York State Budget Vetoes: 2016-17" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/ht4x-zbvr

property e:ht4x-zbvr t:meta.view v:id=ht4x-zbvr v:category="Government & Finance" v:averageRating=0 v:name="New York State Budget Vetoes: 2016-17" v:attribution="Division of the Budget"

property e:ht4x-zbvr t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ht4x-zbvr t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| veto_number | agency | bill                | page_from | page_to | line_from | line_to | fund_type | purpose                                                                                                                                                                                                                                                                                                                      | amount  | justification_text                                                                                                                                                                                                          | 
| =========== | ====== | =================== | ========= | ======= | ========= | ======= | ========= | ============================================================================================================================================================================================================================================================================================================================ | ======= | =========================================================================================================================================================================================================================== | 
| 1           | SED    | S.6400--D A.9000--D | 124       | 124     | 22        | 26      | SRO       | For reimbursement of tuition payments made by or on behalf of students at proprietary institutions registered or licensed pursuant to section 5001 of the education law, including liabilities incurred prior to April 1, 2015. Fringe benefits ... 1,309,000 ....................... (re. $1,272,000)                       | 1272000 | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 2           | SED    | S.6400--D A.9000--D | 124       | 124     | 31        | 35      | SRO       | For services and expenses for the supervision of institutions regis- tered pursuant to section 5001 of the education law, and for services and expenses of supervisory programs and payment of associ- ated indirect costs and general state charges. Personal service--regular ... 1,747,000 ............... (re. $200,000) | 200000  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 3           | SED    | S.6400--D A.9000--D | 124       | 124     | 36        | 36      | SRO       | Supplies and materials ... 12,000 ....................... (re. $2,700)                                                                                                                                                                                                                                                       | 2700    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 4           | SED    | S.6400--D A.9000--D | 124       | 124     | 37        | 37      | SRO       | Travel ... 40,000 ...................................... (re. $18,400)                                                                                                                                                                                                                                                       | 18400   | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 5           | SED    | S.6400--D A.9000--D | 124       | 124     | 38        | 38      | SRO       | Contractual services ... 1,432,000 .................... (re. $597,000)                                                                                                                                                                                                                                                       | 597000  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 6           | SED    | S.6400--D A.9000--D | 124       | 124     | 39        | 39      | SRO       | Equipment ... 12,000 .................................... (re. $6,900)                                                                                                                                                                                                                                                       | 6900    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 7           | SED    | S.6400--D A.9000--D | 124       | 124     | 40        | 40      | SRO       | Fringe benefits ... 857,000 ........................... (re. $310,600)                                                                                                                                                                                                                                                       | 310600  | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 8           | SED    | S.6400--D A.9000--D | 124       | 124     | 41        | 41      | SRO       | Indirect costs ... 57,000 .............................. (re. $33,000)                                                                                                                                                                                                                                                       | 33000   | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 9           | SED    | S.6400--D A.9000--D | 125       | 125     | 2         | 4       | SRO       | For services and expenses of the special workers' compensation program. Supplies and materials ... 2,000 ........................ (re. $2,000)                                                                                                                                                                               | 2000    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
| 10          | SED    | S.6400--D A.9000--D | 125       | 125     | 5         | 5       | SRO       | Travel ... 4,000 ........................................ (re. $4,000)                                                                                                                                                                                                                                                       | 4000    | This item passed by the Legislature, to which I object and do not approve, is not needed because adequate funding for State agency operations is already provided for in the budget. Accordingly, this item is disapproved. | 
```