# 2014 Elections - Loans by Loan Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-loans-by-loan-type-75023) |
| Metadata | [Link](https://data.hawaii.gov/api/views/k8dq-uuxc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/k8dq-uuxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/k8dq-uuxc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | k8dq-uuxc |
| Name | 2014 Elections - Loans by Loan Type |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-13T00:11:23Z |
| Publication Date | 2015-01-13T00:17:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | loan_type                  | Loan Type                  | text      | text        |
| Yes      | numeric metric | count                      | Count                      | number    | number      |
| Yes      | numeric metric | percentage_of_count_total  | Percentage of Count Total  | percent   | percent     |
| Yes      | numeric metric | total_amount               | Total Amount               | money     | money       |
| Yes      | numeric metric | percentage_of_total_amount | Percentage of Total Amount | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k8dq-uuxc d:2014-01-01T00:00:00.000Z t:loan_type=Candidate m:total_amount=436095.45 m:count=301 m:percentage_of_total_amount=75.29 m:percentage_of_count_total=85.27

series e:k8dq-uuxc d:2014-01-01T00:00:00.000Z t:loan_type="Immediate Family" m:total_amount=116634.31 m:count=40 m:percentage_of_total_amount=20.14 m:percentage_of_count_total=11.33

series e:k8dq-uuxc d:2014-01-01T00:00:00.000Z t:loan_type="Other Entity" m:total_amount=26513.57 m:count=12 m:percentage_of_total_amount=4.58 m:percentage_of_count_total=3.4
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

metric m:percentage_of_count_total p:float l:"Percentage of Count Total" t:dataTypeName=percent

metric m:total_amount p:double l:"Total Amount" t:dataTypeName=money

metric m:percentage_of_total_amount p:float l:"Percentage of Total Amount" t:dataTypeName=percent

entity e:k8dq-uuxc l:"2014 Elections - Loans by Loan Type" t:url=https://data.hawaii.gov/api/views/k8dq-uuxc

property e:k8dq-uuxc t:meta.view v:id=k8dq-uuxc v:category=Community v:averageRating=0 v:name="2014 Elections - Loans by Loan Type"

property e:k8dq-uuxc t:meta.view.license v:name="Public Domain"

property e:k8dq-uuxc t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:k8dq-uuxc t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| loan_type        | count | percentage_of_count_total | total_amount | percentage_of_total_amount | 
| ================ | ===== | ========================= | ============ | ========================== | 
| Candidate        | 301   | 85.27                     | 436095.45    | 75.29                      | 
| Immediate Family | 40    | 11.33                     | 116634.31    | 20.14                      | 
| Other Entity     | 12    | 3.4                       | 26513.57     | 4.58                       | 
```