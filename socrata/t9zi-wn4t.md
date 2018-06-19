# 2014 Expenditures by Category

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-expenditures-by-category-8017e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/t9zi-wn4t) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/t9zi-wn4t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/t9zi-wn4t/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | t9zi-wn4t |
| Name | 2014 Expenditures by Category |
| Attribution | Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending, elections |
| Created | 2015-01-13T21:10:32Z |
| Publication Date | 2015-01-13T21:35:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | expenditure_category      | Expenditure Category      | text      | text        |
| Yes      | numeric metric | count                     | Count                     | number    | number      |
| Yes      | numeric metric | percentage_of_total_count | Percentage of Total Count | percent   | percent     |
| Yes      | numeric metric | total_amount              | Total Amount              | money     | money       |
| Yes      | numeric metric | percentage_of_total       | Percentage of Total       | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t9zi-wn4t d:2014-01-01T00:00:00.000Z t:expenditure_category=Advertising m:total_amount=6756209.45 m:count=3653 m:percentage_of_total_count=16.74 m:percentage_of_total=42.86

series e:t9zi-wn4t d:2014-01-01T00:00:00.000Z t:expenditure_category="Bank Charges & Adjustments" m:total_amount=58568.1 m:count=1536 m:percentage_of_total_count=7.04 m:percentage_of_total=0.37

series e:t9zi-wn4t d:2014-01-01T00:00:00.000Z t:expenditure_category="Candidate Fundraiser Tickets" m:total_amount=122752.61 m:count=253 m:percentage_of_total_count=1.16 m:percentage_of_total=0.78
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

metric m:percentage_of_total_count p:float l:"Percentage of Total Count" t:dataTypeName=percent

metric m:total_amount p:double l:"Total Amount" t:dataTypeName=money

metric m:percentage_of_total p:float l:"Percentage of Total" t:dataTypeName=percent

entity e:t9zi-wn4t l:"2014 Expenditures by Category" t:attribution="Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/t9zi-wn4t

property e:t9zi-wn4t t:meta.view v:id=t9zi-wn4t v:category=Community v:averageRating=0 v:name="2014 Expenditures by Category" v:attribution="Campaign Spending Commission"

property e:t9zi-wn4t t:meta.view.license v:name="Public Domain"

property e:t9zi-wn4t t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:t9zi-wn4t t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| expenditure_category                   | count | percentage_of_total_count | total_amount | percentage_of_total | 
| ====================================== | ===== | ========================= | ============ | =================== | 
| Advertising                            | 3653  | 16.74                     | 6756209.45   | 42.86               | 
| Bank Charges & Adjustments             | 1536  | 7.04                      | 58568.1      | 0.37                | 
| Candidate Fundraiser Tickets           | 253   | 1.16                      | 122752.61    | 0.78                | 
| Contribution to Community Organization | 286   | 1.31                      | 55648.91     | 0.35                | 
| Contribution to Political Party        | 121   | 0.55                      | 90292.73     | 0.57                | 
| Durable Assets                         | 70    | 0.32                      | 45986.51     | 0.29                | 
| Employee Services                      | 84    | 0.38                      | 114796.37    | 0.73                | 
| Filing Fee                             | 209   | 0.96                      | 35355.73     | 0.22                | 
| Food & Beverages                       | 4673  | 21.42                     | 1173014.38   | 7.44                | 
| Hawaii Election Campaign Fund          | 79    | 0.36                      | 28761.53     | 0.18                | 
```