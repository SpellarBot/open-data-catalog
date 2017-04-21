# State Administered General Assistance: Department of Social Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-administered-general-assistance-department-of-social-services) |
| Metadata | [Link](https://data.ct.gov/api/views/xzpw-v9uv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/xzpw-v9uv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/xzpw-v9uv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | xzpw-v9uv |
| Name | State Administered General Assistance: Department of Social Services |
| Attribution | CT Department of Social Services |
| Category | Health and Human Services |
| Tags | saga |
| Created | 2014-09-23T16:52:26Z |
| Publication Date | 2015-09-21T14:02:00Z |

## Description

CT State Administered General Assistance

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================= | ============= | ============= |
| No       | time           | :updated_at                  | updated_at                    | meta_data     | meta_data     |
| No       |                | date                         | Date                          | calendar_date | calendar_date |
| Yes      | numeric metric | saga_payments                | SAGA Payments                 | money         | money         |
| Yes      | numeric metric | saga_paid_cases_unduplicated | SAGA Paid Cases, Unduplicated | number        | number        |
| Yes      | numeric metric | saga_average_cost_per_case   | SAGA Average Cost per Case    | money         | money         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:xzpw-v9uv d:2015-09-21T07:01:15.000Z m:saga_average_cost_per_case=159.71 m:saga_payments=739495

series e:xzpw-v9uv d:2015-09-21T07:01:15.000Z m:saga_average_cost_per_case=182.63 m:saga_payments=853090

series e:xzpw-v9uv d:2015-09-21T07:01:15.000Z m:saga_average_cost_per_case=191.08 m:saga_payments=873467
```

## Meta Commands

```ls
metric m:saga_payments p:integer l:"SAGA Payments" t:dataTypeName=money

metric m:saga_paid_cases_unduplicated p:long l:"SAGA Paid Cases, Unduplicated" t:dataTypeName=number

metric m:saga_average_cost_per_case p:double l:"SAGA Average Cost per Case" t:dataTypeName=money

entity e:xzpw-v9uv l:"State Administered General Assistance: Department of Social Services" t:attribution="CT Department of Social Services" t:url=https://data.ct.gov/api/views/xzpw-v9uv

property e:xzpw-v9uv t:meta.view v:id=xzpw-v9uv v:category="Health and Human Services" v:averageRating=0 v:name="State Administered General Assistance: Department of Social Services" v:attribution="CT Department of Social Services"

property e:xzpw-v9uv t:meta.view.license v:name="Public Domain"

property e:xzpw-v9uv t:meta.view.owner v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"

property e:xzpw-v9uv t:meta.view.tableauthor v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"
```

## Top Records

```ls
| :updated_at | date | saga_payments | saga_paid_cases_unduplicated | saga_average_cost_per_case | 
| =========== | ==== | ============= | ============================ | ========================== | 
| 1442818875  |      |               |                              |                            | 
| 1442818875  |      | 739495        |                              | 159.71                     | 
| 1442818875  |      | 853090        |                              | 182.63                     | 
| 1442818875  |      | 873467        |                              | 191.08                     | 
| 1442818875  |      | 748449        |                              | 164.24                     | 
| 1442818875  |      | 894493        |                              | 199.97                     | 
| 1442818875  |      | 873215        |                              | 193.53                     | 
| 1442818875  |      | 761005        |                              | 167.25                     | 
| 1442818875  |      | 808226        |                              | 177.04                     | 
| 1442818875  |      | 874847        |                              | 190.47                     | 
```