# Uniform Chart of Accounts - Municipal Spending Data 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/uniform-chart-of-accounts-municipal-spending-data-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/94fn-fqds) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/94fn-fqds/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/94fn-fqds/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 94fn-fqds |
| Name | Uniform Chart of Accounts - Municipal Spending Data 2014 |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | ucoa, spending, municipal, expenditures |
| Created | 2016-09-02T18:13:10Z |
| Publication Date | 2016-10-12T15:07:23Z |

## Description

For a simplified view please visit: https://ucoa.ct.gov/benchmarking/#/
The Connecticut Uniform Chart of Accounts project enables the annual collection of municipal trial balance data at the local account level, along with a mapping, or ?cross walk? of that data to a standard, uniform chart of accounts for comparative purposes.  This data is collected and stored in a system of databases developed for the Office of Policy and Management (OPM), including a Data Warehouse of all approved and certified financial balances.  These balances are recorded at the account level and contain both local and uniform account metadata.
The Following "UniformFund" values are included in this raw data release, but are not reflected in the benchmarking tool:
Permanent Fund
Library Fund
Internal Service Fund
Medical & Health Insurance
Other Internal Service Funds
Trust Fund
Scholarship Funds
Agency Funds
Student Activities Fund
Other Agency Funds
Pooled Cash/Treasury
Governmental Fixed Assets

Additional details can be found here: http://www.ct.gov/opm/cwp/view.asp?a=2984&q=576636

Some Municipalities are not included in this release. They can be found here: https://ucoa.ct.gov/benchmarking/#/

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | fiscalyear         | FiscalYear         | number    | number      |
| Yes      | series tag     | municipality       | Municipality       | text      | text        |
| Yes      | series tag     | localaccount       | LocalAccount       | text      | text        |
| Yes      | series tag     | localfund          | LocalFund          | text      | text        |
| Yes      | series tag     | localfunction      | LocalFunction      | text      | text        |
| Yes      | series tag     | localdepartment    | LocalDepartment    | text      | text        |
| Yes      | series tag     | localsubdepartment | LocalSubDepartment | text      | text        |
| Yes      | series tag     | localobject        | LocalObject        | text      | text        |
| Yes      | series tag     | localproject       | LocalProject       | text      | text        |
| Yes      | series tag     | uniformaccount     | UniformAccount     | text      | text        |
| Yes      | series tag     | uniformfund        | UniformFund        | text      | text        |
| Yes      | series tag     | uniformfunction    | UniformFunction    | text      | text        |
| Yes      | series tag     | uniformdepartment  | UniformDepartment  | text      | text        |
| Yes      | series tag     | uniformobject      | UniformObject      | text      | text        |
| Yes      | series tag     | uniformprojectname | UniformProjectName | text      | text        |
| Yes      | numeric metric | debit              | Debit              | money     | money       |
| Yes      | numeric metric | credit             | Credit             | money     | money       |
```

## Time Field

```ls
Value = fiscalyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:94fn-fqds d:2014-01-01T00:00:00.000Z t:uniformobject="Employee Benefits" t:uniformaccount=1005-42-4201-00000-52000-000 t:uniformfunction="Public Safety" t:uniformfund="Town General Fund" t:uniformprojectname="Undefined Project" t:localdepartment=0301 t:municipality=Ansonia t:localobject=243 t:uniformdepartment=Police t:localaccount=10010301122430005 t:localfund=001 t:localfunction=12 m:debit=500

series e:94fn-fqds d:2014-01-01T00:00:00.000Z t:uniformobject="Intergovernmental Revenues" t:uniformaccount=1005-00-0000-00000-43000-000 t:uniformfunction="Undefined Function" t:uniformfund="Town General Fund" t:uniformprojectname="Undefined Project" t:municipality=Ansonia t:localobject=20313 t:uniformdepartment="Undefined Department" t:localaccount=20010313190100005 t:localfund=001 m:credit=-245055.15

series e:94fn-fqds d:2014-01-01T00:00:00.000Z t:uniformobject=Liability t:uniformaccount=1005-00-0000-00000-20000-000 t:uniformfunction="Undefined Function" t:uniformfund="Town General Fund" t:uniformprojectname="Undefined Project" t:municipality=Ansonia t:localobject=L0202 t:uniformdepartment="Undefined Department" t:localaccount=L0010202001100000 t:localfund=001 m:credit=0
```

## Meta Commands

```ls
metric m:debit p:double l:Debit d:"The Account Balance, for Asset and Expenditure accounts" t:dataTypeName=money

metric m:credit p:double l:Credit d:"The Account Balance, for Liabilities, Fund Balance and Revenue accounts. Balances are typically negative." t:dataTypeName=money

entity e:94fn-fqds l:"Uniform Chart of Accounts - Municipal Spending Data 2014" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/94fn-fqds

property e:94fn-fqds t:meta.view v:id=94fn-fqds v:category=Government v:attributionLink=https://ucoa.ct.gov/benchmarking v:averageRating=0 v:name="Uniform Chart of Accounts - Municipal Spending Data 2014" v:attribution="Office of Policy and Management"

property e:94fn-fqds t:meta.view.license v:name="Public Domain"

property e:94fn-fqds t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:94fn-fqds t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| fiscalyear | municipality | localaccount      | localfund | localfunction | localdepartment | localsubdepartment | localobject | localproject | uniformaccount               | uniformfund       | uniformfunction    | uniformdepartment    | uniformobject              | uniformprojectname | debit    | credit      | 
| ========== | ============ | ================= | ========= | ============= | =============== | ================== | =========== | ============ | ============================ | ================= | ================== | ==================== | ========================== | ================== | ======== | =========== | 
| 2014       | Ansonia      | 10010301122430005 | 001       | 12            | 0301            |                    | 243         |              | 1005-42-4201-00000-52000-000 | Town General Fund | Public Safety      | Police               | Employee Benefits          | Undefined Project  | 500.00   |             | 
| 2014       | Ansonia      | 20010313190100005 | 001       |               |                 |                    | 20313       |              | 1005-00-0000-00000-43000-000 | Town General Fund | Undefined Function | Undefined Department | Intergovernmental Revenues | Undefined Project  |          | -245055.15  | 
| 2014       | Ansonia      | L0010202001100000 | 001       |               |                 |                    | L0202       |              | 1005-00-0000-00000-20000-000 | Town General Fund | Undefined Function | Undefined Department | Liability                  | Undefined Project  |          | 0.00        | 
| 2014       | Ansonia      | 10010216111100001 | 001       | 11            | 0216            |                    | 110         |              | 1005-41-4107-00000-51000-000 | Town General Fund | General Government | Executive            | Wages                      | Undefined Project  | 69438.43 |             | 
| 2014       | Ansonia      | A0010101000030000 | 001       |               |                 |                    | A0101       |              | 1005-00-0000-00000-10000-000 | Town General Fund | Undefined Function | Undefined Department | Asset                      | Undefined Project  | 9660.55  |             | 
| 2014       | Ansonia      | 10010401126170001 | 001       | 12            | 0401            |                    | 617         |              | 1005-42-4203-00000-50000-000 | Town General Fund | Public Safety      | Fire                 | Expenditure                | Undefined Project  | 19939.46 |             | 
| 2014       | Ansonia      | L1082000005000003 | 108       |               |                 |                    | L2000       |              | 6001-00-0000-00000-20000-000 | Wastewater        | Undefined Function | Undefined Department | Liability                  | Undefined Project  |          | -1548038.00 | 
| 2014       | Ansonia      | 10010801122410002 | 001       | 12            | 0801            |                    | 241         |              | 1005-42-4299-00000-50000-000 | Town General Fund | Public Safety      | Other Public Safety  | Expenditure                | Undefined Project  | 1100.00  |             | 
| 2014       | Ansonia      | 10010216115210001 | 001       | 11            | 0216            |                    | 521         |              | 1005-41-4107-00000-50000-000 | Town General Fund | General Government | Executive            | Expenditure                | Undefined Project  | 0.00     |             | 
| 2014       | Ansonia      | L0010201000010003 | 001       |               |                 |                    | L0201       |              | 1005-00-0000-00000-20000-000 | Town General Fund | Undefined Function | Undefined Department | Liability                  | Undefined Project  |          | -203586.90  | 
```