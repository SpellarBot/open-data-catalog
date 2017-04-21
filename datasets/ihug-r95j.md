# SSMMA Homewood General Revenue - FINAL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-homewood-general-revenue-final-89837) |
| Metadata | [Link](https://data.illinois.gov/api/views/ihug-r95j) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ihug-r95j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ihug-r95j/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ihug-r95j |
| Name | SSMMA Homewood General Revenue - FINAL |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | budgeting, municipal, budget, finance |
| Created | 2012-11-27T18:15:05Z |
| Publication Date | 2012-11-27T18:54:06Z |

## Description

This dataset details Village of Homewood, Illinois General Revenue for the 2012-2013 fiscal year.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | account_number      | Account Number      | text      | text        |
| Yes      | series tag  | account_description | Account Description | text      | text        |
| Yes      | series tag  | account_type        | Account Type        | text      | text        |
| Yes      | series tag  | prior_actual        | Prior Actual        | text      | text        |
| Yes      | series tag  | space               | Space               | text      | text        |
| Yes      | series tag  | budgeted            | Budgeted            | text      | text        |
| Yes      | series tag  | actual              | Actual              | text      | text        |
| Yes      | series tag  | projected           | Projected           | text      | text        |
| Yes      | series tag  | space0              | Space0              | text      | text        |
| Yes      | series tag  | budget              | 2012-2013 Budget    | text      | text        |
| Yes      | series tag  | space1              | Space1              | text      | text        |
| Yes      | series tag  | budgetamount        | BudgetAmount        | text      | text        |
| Yes      | series tag  | space2              | Space2              | text      | text        |
| Yes      | series tag  | budgetchange        | BudgetChange        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ihug-r95j d:2012-11-27T10:15:07.000Z t:budgetchange="% Change" t:budgeted="2011-2012 Budget" t:budget="2012-2013 Budget" t:account_description="Account Description" t:actual="8 mos. Actual" t:prior_actual="2009-2010 Actual" t:budgetamount=Incr/(Decr) t:projected="2010-2011 Estimated" m:row_number.ihug-r95j=1

series e:ihug-r95j d:2012-11-27T10:15:07.000Z t:budgeted=BudgetedCytd t:budget=CurrentBudget t:space0=Column1 t:account_number=AccountNum t:account_description=AccountDesc t:actual=ActualCytd t:space=Column2 t:prior_actual=PriorActual t:projected=ProjectedCytd t:account_type=AccountType m:row_number.ihug-r95j=2

series e:ihug-r95j d:2012-11-27T10:15:07.000Z t:budgetchange=0 t:budgeted="* 40,000" t:budget="* 40,000" t:account_number=10000400000 t:account_description="PERSONAL PROPERTY REPL TAX" t:actual="* 29,814" t:prior_actual=66674.429999999993 t:budgetamount=0.0 t:projected="* 40,000" t:account_type=R m:row_number.ihug-r95j=3
```

## Meta Commands

```ls
metric m:row_number.ihug-r95j p:long l:"Row Number"

entity e:ihug-r95j l:"SSMMA Homewood General Revenue - FINAL" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/ihug-r95j

property e:ihug-r95j t:meta.view v:id=ihug-r95j v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Homewood General Revenue - FINAL" v:attribution="South Suburban Mayors and Managers Association"

property e:ihug-r95j t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:ihug-r95j t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | account_number | account_description        | account_type | prior_actual       | space   | budgeted         | actual        | projected           | space0  | budget           | space1 | budgetamount | space2 | budgetchange       | 
| =========== | ============== | ========================== | ============ | ================== | ======= | ================ | ============= | =================== | ======= | ================ | ====== | ============ | ====== | ================== | 
| 1354011307  |                | Account Description        |              | 2009-2010 Actual   |         | 2011-2012 Budget | 8 mos. Actual | 2010-2011 Estimated |         | 2012-2013 Budget |        | Incr/(Decr)  |        | % Change           | 
| 1354011307  | AccountNum     | AccountDesc                | AccountType  | PriorActual        | Column2 | BudgetedCytd     | ActualCytd    | ProjectedCytd       | Column1 | CurrentBudget    |        |              |        |                    | 
| 1354011307  | 10000400000    | PERSONAL PROPERTY REPL TAX | R            | 66674.429999999993 |         | * 40,000         | * 29,814      | * 40,000            |         | * 40,000         |        | 0.0          |        | 0                  | 
| 1354011307  | 10000401000    | REAL ESTATE TAXES          | R            | 2889717.34         |         | * 3,050,000      | * 1,215,377   | * 2,895,781         |         | * 2,818,730      |        | * (231,270)  |        | -0.075826229508197 | 
| 1354011307  | 10000401510    | RET FOR POLICE PENSION     | R            | 545000             |         | * 875,000        | 0.0           | * 875,000           |         | * 963,089        |        | * 88,089     |        | 0.100673142857143  | 
| 1354011307  | 10000401520    | RET FOR FIRE PENSION       | R            | 305000             |         | * 435,000        | 0.0           | * 435,000           |         | * 451,176        |        | * 16,176     |        | 0.037186206896552  | 
| 1354011307  | 10000402000    | SALES TAX                  | R            | 3789652            |         | * 3,950,000      | * 2,184,475   | * 3,950,000         |         | * 4,100,000      |        | * 150,000    |        | 0.037974683544304  | 
| 1354011307  | 10000402100    | USE TAX                    | R            | 277467.59000000003 |         | * 239,400        | * 156,777     | * 239,400           |         | * 250,000        |        | * 10,600     |        | 0.044277360066834  | 
| 1354011307  | 10000403000    | TOWNSHIP ROAD & BRIDGE     | R            | 67440              |         | * 70,000         | * 34,752      | * 70,000            |         | * 70,000         |        | 0.0          |        | 0                  | 
| 1354011307  | 10000404400    | HOTEL TAX                  | R            | 16723.759999999998 |         | * 15,000         | * 7,778       | * 10,000            |         | * 5,000          |        | * (10,000)   |        | -0.666666666666667 | 
```