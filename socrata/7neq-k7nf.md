# Economic Development Compliance: Family Business Loans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/economic-development-compliance-family-business-loans) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7neq-k7nf) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7neq-k7nf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7neq-k7nf/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7neq-k7nf |
| Name | Economic Development Compliance: Family Business Loans |
| Created | 2014-02-10T22:39:17Z |
| Publication Date | 2016-09-22T14:02:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | firm                    | Firm                    | text      | text        |
| Yes      | numeric metric | loan                    | Loan                    | money     | money       |
| Yes      | series tag     | repayment_terms         | Repayment Terms         | text      | text        |
| Yes      | numeric metric | job_creation_commitment | Job Creation Commitment | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7neq-k7nf d:2015-07-21T12:52:16.000Z t:repayment_terms="7 years" t:firm="Sweet Victoria, LLC" m:job_creation_commitment=4 m:loan=35000

series e:7neq-k7nf d:2015-07-21T12:52:20.000Z t:repayment_terms="20 years" t:firm="Eastern Diner, LLC" m:job_creation_commitment=19 m:loan=519000

series e:7neq-k7nf d:2015-07-21T12:52:25.000Z t:repayment_terms="20 years" t:firm="Rosa Santis" m:job_creation_commitment=12 m:loan=150000
```

## Meta Commands

```ls
metric m:loan p:integer l:Loan t:dataTypeName=money

metric m:job_creation_commitment p:integer l:"Job Creation Commitment" t:dataTypeName=number

entity e:7neq-k7nf l:"Economic Development Compliance: Family Business Loans" t:url=https://data.austintexas.gov/api/views/7neq-k7nf

property e:7neq-k7nf t:meta.view v:id=7neq-k7nf v:averageRating=0 v:name="Economic Development Compliance: Family Business Loans"

property e:7neq-k7nf t:meta.view.owner v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:displayName="Melissa Alvarado"

property e:7neq-k7nf t:meta.view.tableauthor v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:roleName=editor v:displayName="Melissa Alvarado"
```

## Top Records

```ls
| :updated_at | firm                 | loan   | repayment_terms | job_creation_commitment | 
| =========== | ==================== | ====== | =============== | ======================= | 
| 1437483136  | Sweet Victoria, LLC  | 35000  | 7 years         | 4                       | 
| 1437483140  | Eastern Diner, LLC   | 519000 | 20 years        | 19                      | 
| 1437483145  | Rosa Santis          | 150000 | 20 years        | 12                      | 
| 1437483150  | Eastside Music LLC   |        | 7 years         | 2                       | 
| 1437483153  | Home2Suites          |        | 7 years         | 15                      | 
| 1437483168  | Austin Fit Centro    |        | 10 years        | 24                      | 
| 1454663102  | Jose Luis Salon Inc. |        | 15 years        | 16                      | 
| 1454673567  | Fair Market          |        | 15 years        | 7                       | 
| 1454673571  | Fair Market          |        | 7 years         | 7                       | 
| 1454673576  | Hip Haven            |        | 7 years         | 1                       | 
```