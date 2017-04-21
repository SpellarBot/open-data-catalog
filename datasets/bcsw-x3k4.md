# Fiscal Year 2012-13 Projected Total Compensation for All City Employees (Current as of June 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2012-13-projected-total-compensation-for-all-city-employees-current-as-of-june-0ac45) |
| Metadata | [Link](https://data.illinois.gov/api/views/bcsw-x3k4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/bcsw-x3k4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/bcsw-x3k4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | bcsw-x3k4 |
| Name | Fiscal Year 2012-13 Projected Total Compensation for All City Employees (Current as of June 2012) |
| Attribution | City of Champaign |
| Category | Municipality |
| Tags | champaign |
| Created | 2012-12-05T16:50:21Z |
| Publication Date | 2012-12-05T17:24:09Z |

## Description

Note that this is current as of June 2012, so it will include people who have left employment, and will not include people who have been hired since then.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | series tag     | name                            | Name                            | text      | text        |
| Yes      | series tag     | position_title                  | Position Title                  | text      | text        |
| Yes      | series tag     | group                           | Group                           | text      | text        |
| Yes      | numeric metric | projected_salary_as_of_7_1_2012 | Projected Salary as of 7/1/2012 | money     | money       |
| Yes      | numeric metric | health_insurance                | Health Insurance                | money     | money       |
| Yes      | numeric metric | housing                         | Housing                         | money     | money       |
| Yes      | numeric metric | vehicle                         | Vehicle                         | money     | money       |
| Yes      | numeric metric | clothing_allowance              | Clothing Allowance              | money     | money       |
| Yes      | numeric metric | bonus                           | Bonus                           | money     | money       |
| Yes      | numeric metric | loans                           | Loans                           | money     | money       |
| Yes      | numeric metric | annual_earned_vacation_days     | Annual Earned Vacation Days     | number    | number      |
| Yes      | numeric metric | annual_earned_sick_days         | Annual Earned Sick Days         | number    | number      |
| Yes      | numeric metric | budgeted_pension                | Budgeted Pension                | money     | money       |
| Yes      | numeric metric | budgeted_social_security        | Budgeted Social Security        | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bcsw-x3k4 d:2012-01-01T00:00:00.000Z t:name="ALLEN, AARON S" t:position_title="STREET MAINTENANCE WORKER II" t:group=AFSCME m:loans=0 m:clothing_allowance=0 m:annual_earned_sick_days=12 m:housing=0 m:health_insurance=9400 m:vehicle=0 m:projected_salary_as_of_7_1_2012=55267.05 m:bonus=0 m:budgeted_pension=6311.5 m:budgeted_social_security=3426.56 m:annual_earned_vacation_days=18

series e:bcsw-x3k4 d:2012-01-01T00:00:00.000Z t:name="ALLEN, HANNA L" t:position_title="TELECOMMUNICATOR I" t:group=AFSCME m:loans=0 m:clothing_allowance=0 m:annual_earned_sick_days=12 m:housing=0 m:health_insurance=9400 m:vehicle=0 m:projected_salary_as_of_7_1_2012=45209.17 m:bonus=0 m:budgeted_pension=5162.89 m:budgeted_social_security=2802.97 m:annual_earned_vacation_days=12

series e:bcsw-x3k4 d:2012-01-01T00:00:00.000Z t:name="AUSMUS, JEREMY J" t:position_title="TELECOMMUNICATOR I" t:group=AFSCME m:loans=0 m:clothing_allowance=0 m:annual_earned_sick_days=12 m:housing=0 m:health_insurance=9400 m:vehicle=0 m:projected_salary_as_of_7_1_2012=47510.9 m:bonus=0 m:budgeted_pension=5425.74 m:budgeted_social_security=2945.68 m:annual_earned_vacation_days=13.5
```

## Meta Commands

```ls
metric m:projected_salary_as_of_7_1_2012 p:double l:"Projected Salary as of 7/1/2012" d:"Salaries may include longevity pay. The amount is determined by the employee's years of service." t:dataTypeName=money

metric m:health_insurance p:double l:"Health Insurance" d:"Health insurance is budgeted at $783.33 per month as a blend of the options available to employees (family, single plus spouse, single plus child(ren), and single). The cost to the City for these options ranges from $580 per month to $1,433 per employee" t:dataTypeName=money

metric m:housing p:double l:Housing t:dataTypeName=money

metric m:vehicle p:double l:Vehicle d:"Vehicle allowance for personal use is projected based on actual figures from calendar year 2011." t:dataTypeName=money

metric m:clothing_allowance p:double l:"Clothing Allowance" d:"The Police and Fire Chiefs are eligible for reimbursement for the cost of a dress uniform and other related clothing/equipment as required for the performance of duties. Actual amounts will vary." t:dataTypeName=money

metric m:bonus p:double l:Bonus t:dataTypeName=money

metric m:loans p:double l:Loans t:dataTypeName=money

metric m:annual_earned_vacation_days p:float l:"Annual Earned Vacation Days" t:dataTypeName=number

metric m:annual_earned_sick_days p:float l:"Annual Earned Sick Days" t:dataTypeName=number

metric m:budgeted_pension p:double l:"Budgeted Pension" d:"IMRF percent is the calendar year 2012 rate at 11.42%, and SURS percent is the fiscal year 12/13 rate at 12.04%. Police pension rate of 50.46% and the Firefighters' pension rate of 50.99% are based on their respective actuarial valuation reports year end" t:dataTypeName=money

metric m:budgeted_social_security p:double l:"Budgeted Social Security" d:"Social Security employer contribution is 6.2% for participating employees at a maximum amount of $110,100 annually. Employees in the Police and Firefighters' pension plans do not participate. FICA is based on earnings. Employees in the NBU-TEMP employe" t:dataTypeName=money

entity e:bcsw-x3k4 l:"Fiscal Year 2012-13 Projected Total Compensation for All City Employees (Current as of June 2012)" t:attribution="City of Champaign" t:url=https://data.illinois.gov/api/views/bcsw-x3k4

property e:bcsw-x3k4 t:meta.view v:id=bcsw-x3k4 v:category=Municipality v:averageRating=0 v:name="Fiscal Year 2012-13 Projected Total Compensation for All City Employees (Current as of June 2012)" v:attribution="City of Champaign"

property e:bcsw-x3k4 t:meta.view.license v:name="Public Domain"

property e:bcsw-x3k4 t:meta.view.owner v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"

property e:bcsw-x3k4 t:meta.view.tableauthor v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"
```

## Top Records

```ls
| name                | position_title                 | group  | projected_salary_as_of_7_1_2012 | health_insurance | housing | vehicle | clothing_allowance | bonus | loans | annual_earned_vacation_days | annual_earned_sick_days | budgeted_pension | budgeted_social_security | 
| =================== | ============================== | ====== | =============================== | ================ | ======= | ======= | ================== | ===== | ===== | =========================== | ======================= | ================ | ======================== | 
| ALLEN, AARON S      | STREET MAINTENANCE WORKER II   | AFSCME | 55267.05                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 18.00                       | 12.00                   | 6311.50          | 3426.56                  | 
| ALLEN, HANNA L      | TELECOMMUNICATOR I             | AFSCME | 45209.17                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 12.00                       | 12.00                   | 5162.89          | 2802.97                  | 
| AUSMUS, JEREMY J    | TELECOMMUNICATOR I             | AFSCME | 47510.90                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 13.50                       | 12.00                   | 5425.74          | 2945.68                  | 
| BARR, AMELIA E      | TELECOMMUNICATOR I             | AFSCME | 39014.53                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 12.00                       | 12.00                   | 4455.46          | 2418.90                  | 
| BECKMAN, STEPHEN    | CONCRETE MAINTENANCE WORKER II | AFSCME | 59311.02                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 22.00                       | 12.00                   | 6773.32          | 3677.28                  | 
| BELLMORE, DAVID P   | TELECOMMUNICATOR I             | AFSCME | 42999.74                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 12.00                       | 12.00                   | 4910.57          | 2665.98                  | 
| BIGHAM, DENNIS      | LEAD MAINTENANCE WORKER        | AFSCME | 63321.70                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 19.00                       | 12.00                   | 7231.34          | 3925.95                  | 
| BOTHWELL, JOHN      | ELECTRICAL TECHNICIAN          | AFSCME | 64794.09                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 25.00                       | 12.00                   | 7399.49          | 4017.23                  | 
| BRAZELTON, DEANNE L | TELECOMMUNICATOR I             | AFSCME | 47510.90                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 13.50                       | 12.00                   | 5425.74          | 2945.68                  | 
| BREWER, SETH M      | ACCOUNT CLERK II               | AFSCME | 46818.19                        | 9400.00          | 0.00    | 0.00    | 0.00               | 0.00  | 0.00  | 18.00                       | 12.00                   | 5346.64          | 2902.73                  | 
```