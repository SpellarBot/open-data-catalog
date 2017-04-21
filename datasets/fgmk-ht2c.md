# CT OSC - State Employee Payroll (2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-osc-state-employee-payroll-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/fgmk-ht2c) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fgmk-ht2c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fgmk-ht2c/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fgmk-ht2c |
| Name | CT OSC - State Employee Payroll (2015) |
| Attribution | Office of the State Comptroller |
| Category | Government |
| Tags | state employee, payroll, connecticut, salary, salaries, employee |
| Created | 2015-12-21T19:56:47Z |
| Publication Date | 2015-12-21T20:35:16Z |

## Description

Payments to businesses and other entities are at the core of State spending transparency. This data allows citizens to view who received payments from the State for goods or services and how much they received. Data from the CORE-CT Financial Accounting System are summarized by Agency, Payee, and Expense Account. Certain Payee Names have been removed in order to protect the privacy of individuals, in accordance with Health Insurance Portability and Accountability Act (HIPAA) regulations or where it might be a violation of protected information, in the case of Department of Criminal Justice Investigations. These redacted names appear as "REMOVED FOR PRIVACY." This data is static and is not live-updated.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | name              | NAME              | text      | text        |
| Yes      | series tag     | agency            | AGENCY            | text      | text        |
| Yes      | series tag     | department        | DEPARTMENT        | text      | text        |
| Yes      | series tag     | job_title         | JOB TITLE         | text      | text        |
| Yes      | series tag     | compensation_type | COMPENSATION TYPE | text      | text        |
| Yes      | numeric metric | amount            | AMOUNT            | money     | money       |
| Yes      | time           | fiscal_year       | FISCAL YEAR       | number    | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fgmk-ht2c d:2015-01-01T00:00:00.000Z t:department=UCHC t:job_title="Licensed Practical Nurse" t:name="Adjei,vida F" t:agency="UConn Health Center" t:compensation_type="Meal Allowance" m:amount=1680

series e:fgmk-ht2c d:2015-01-01T00:00:00.000Z t:department=UCHC t:job_title="U C H C Faculty" t:name="Alerte,anton M." t:agency="UConn Health Center" t:compensation_type="Longevity Payments" m:amount=820

series e:fgmk-ht2c d:2015-01-01T00:00:00.000Z t:department="Southern CSU" t:job_title="SU Admin 6" t:name="Allen,elaine E." t:agency="Board of Regents" t:compensation_type="Longevity Payments" m:amount=811.49
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:fgmk-ht2c l:"CT OSC - State Employee Payroll (2015)" t:attribution="Office of the State Comptroller" t:url=https://data.ct.gov/api/views/fgmk-ht2c

property e:fgmk-ht2c t:meta.view v:id=fgmk-ht2c v:category=Government v:averageRating=0 v:name="CT OSC - State Employee Payroll (2015)" v:attribution="Office of the State Comptroller"

property e:fgmk-ht2c t:meta.view.license v:name="Public Domain"

property e:fgmk-ht2c t:meta.view.owner v:id=qkr3-bs6f v:profileImageUrlMedium=/api/users/qkr3-bs6f/profile_images/THUMB v:profileImageUrlLarge=/api/users/qkr3-bs6f/profile_images/LARGE v:screenName="Office of the State Comptroller" v:profileImageUrlSmall=/api/users/qkr3-bs6f/profile_images/TINY v:displayName="Office of the State Comptroller"

property e:fgmk-ht2c t:meta.view.tableauthor v:id=qkr3-bs6f v:profileImageUrlMedium=/api/users/qkr3-bs6f/profile_images/THUMB v:profileImageUrlLarge=/api/users/qkr3-bs6f/profile_images/LARGE v:screenName="Office of the State Comptroller" v:profileImageUrlSmall=/api/users/qkr3-bs6f/profile_images/TINY v:roleName=editor v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| name                  | agency                    | department      | job_title                      | compensation_type   | amount  | fiscal_year | 
| ===================== | ========================= | =============== | ============================== | =================== | ======= | =========== | 
| Adjei,vida F          | UConn Health Center       | UCHC            | Licensed Practical Nurse       | Meal Allowance      | 1680    | 2015        | 
| Alerte,anton M.       | UConn Health Center       | UCHC            | U C H C Faculty                | Longevity Payments  | 820     | 2015        | 
| Allen,elaine E.       | Board of Regents          | Southern CSU    | SU Admin 6                     | Longevity Payments  | 811.49  | 2015        | 
| Allen,robert          | University of Connecticut | UCONN           | Police Sgt ( Uncl )            | Overtime            | 3726.4  | 2015        | 
| Altomari-nelson,karen | UConn Health Center       | UCHC            | U C H C University Health Prof | Overtime            | 1135.03 | 2015        | 
| Alves,moises          | Board of Regents          | Western CSU     | Custodian                      | Overtime            | 51.24   | 2015        | 
| Andalibi,ali          | University of Connecticut | UCONN           | U Conn Faculty / Staff         | Accumulated Leave   | 8538.47 | 2015        | 
| Andrade,david J.      | UConn Health Center       | UCHC            | Storekeeper                    | Overtime            | 942.39  | 2015        | 
| Arce,jose E.          | Board of Regents          | Capital CC      | CC Educ Asst < 9               | Graduate Assistants | 570     | 2015        | 
| Arre,sherry E.        | Judicial Department       | Judicial Branch | Judicial Employee              | Longevity Payments  | 1298    | 2015        | 
```