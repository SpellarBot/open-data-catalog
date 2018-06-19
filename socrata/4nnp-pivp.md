# Temporary Family Assistance Payments 2004 - Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/temporary-family-assistance-payments-2004-present) |
| Metadata | [Link](https://data.ct.gov/api/views/4nnp-pivp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4nnp-pivp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4nnp-pivp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4nnp-pivp |
| Name | Temporary Family Assistance Payments 2004 - Present |
| Attribution | CT Department of Social Services |
| Category | Health and Human Services |
| Tags | temporary family assistance, tfa |
| Created | 2014-09-23T15:46:50Z |
| Publication Date | 2015-09-21T14:30:45Z |

## Description

Temporary Family Assistance

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | ============== | ================================= | =================================== | ============= | ============= |
| No       |                | date                              | Date                                | calendar_date | calendar_date |
| Yes      | numeric metric | total_tfa_payments_incl_diversion | Total TFA Payments (Incl Diversion) | money         | money         |
| Yes      | series tag     | tfa_paid_cases_unduplicated       | TFA Paid Cases, Unduplicated        | text          | text          |
| Yes      | numeric metric | tfa_average_cost_per_case         | TFA Average Cost per Case           | money         | money         |
| Yes      | numeric metric | tfa_no_of_adults_paid             | TFA No. of Adults Paid              | number        | number        |
| Yes      | numeric metric | tfa_no_of_children_paid           | TFA No. of Children Paid            | number        | number        |
| Yes      | numeric metric | tfa_total_persons_paid            | TFA Total Persons Paid              | number        | number        |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:4nnp-pivp d:2004-01-01T00:00:00.000Z t:tfa_paid_cases_unduplicated="* 24,535" m:tfa_average_cost_per_case=430.55 m:tfa_no_of_adults_paid=17143 m:total_tfa_payments_incl_diversion=10563646 m:tfa_total_persons_paid=54331 m:tfa_no_of_children_paid=37188

series e:4nnp-pivp d:2004-01-01T00:00:00.000Z t:tfa_paid_cases_unduplicated="* 24,629" m:tfa_average_cost_per_case=431.43 m:tfa_no_of_adults_paid=17281 m:total_tfa_payments_incl_diversion=10625569 m:tfa_total_persons_paid=54655 m:tfa_no_of_children_paid=37374

series e:4nnp-pivp d:2004-01-01T00:00:00.000Z t:tfa_paid_cases_unduplicated="* 24,639" m:tfa_average_cost_per_case=430.41 m:tfa_no_of_adults_paid=17289 m:total_tfa_payments_incl_diversion=10604887 m:tfa_total_persons_paid=54702 m:tfa_no_of_children_paid=37413
```

## Meta Commands

```ls
metric m:total_tfa_payments_incl_diversion p:integer l:"Total TFA Payments (Incl Diversion)" t:dataTypeName=money

metric m:tfa_average_cost_per_case p:double l:"TFA Average Cost per Case" t:dataTypeName=money

metric m:tfa_no_of_adults_paid p:integer l:"TFA No. of Adults Paid" t:dataTypeName=number

metric m:tfa_no_of_children_paid p:integer l:"TFA No. of Children Paid" t:dataTypeName=number

metric m:tfa_total_persons_paid p:integer l:"TFA Total Persons Paid" t:dataTypeName=number

entity e:4nnp-pivp l:"Temporary Family Assistance Payments 2004 - Present" t:attribution="CT Department of Social Services" t:url=https://data.ct.gov/api/views/4nnp-pivp

property e:4nnp-pivp t:meta.view v:id=4nnp-pivp v:category="Health and Human Services" v:averageRating=0 v:name="Temporary Family Assistance Payments 2004 - Present" v:attribution="CT Department of Social Services"

property e:4nnp-pivp t:meta.view.license v:name="Public Domain"

property e:4nnp-pivp t:meta.view.owner v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"

property e:4nnp-pivp t:meta.view.tableauthor v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"
```

## Top Records

```ls
| date | total_tfa_payments_incl_diversion | tfa_paid_cases_unduplicated  | tfa_average_cost_per_case | tfa_no_of_adults_paid | tfa_no_of_children_paid | tfa_total_persons_paid | 
| ==== | ================================= | ============================ | ========================= | ===================== | ======================= | ====================== | 
|      |                                   | TFA Paid Cases, Unduplicated |                           |                       |                         |                        | 
|      | 10563646                          | * 24,535                     | 430.55                    | 17143                 | 37188                   | 54331                  | 
|      | 10625569                          | * 24,629                     | 431.43                    | 17281                 | 37374                   | 54655                  | 
|      | 10604887                          | * 24,639                     | 430.41                    | 17289                 | 37413                   | 54702                  | 
|      | 11067756                          | * 24,647                     | 449.05                    | 17242                 | 37420                   | 54662                  | 
|      | 10967465                          | * 24,370                     | 450.04                    | 16998                 | 36994                   | 53992                  | 
|      | 10978393                          | * 24,271                     | 452.33                    | 16937                 | 36941                   | 53878                  | 
|      | 10789998                          | * 24,120                     | 447.35                    | 16740                 | 36518                   | 53258                  | 
|      | 10623706                          | * 23,815                     | 446.09                    | 16490                 | 35932                   | 52422                  | 
|      | 10532559                          | * 23,799                     | 442.56                    | 16363                 | 35867                   | 52230                  | 
```