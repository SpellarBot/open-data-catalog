# Electric Utility Discount Program By Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electric-utility-discount-program-by-year) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gdnf-za7q) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gdnf-za7q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gdnf-za7q/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gdnf-za7q |
| Name | Electric Utility Discount Program By Year |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | electric utility, discount program, electric utility discount, customer assistance program |
| Created | 2016-09-23T14:36:05Z |
| Publication Date | 2016-11-07T14:50:55Z |

## Description

Qualifying utility customers receive waivers and discounts on their utility bills. The City of Austin has one of the most generous Customer Assistance Programs in the nation. Utility bill discounts are a key component of the program. They are provided to customers already receiving benefits through a variety of federal, state, county or city assistance programs. In February 2014, the Austin City Council voted to expand the discount program to 45,000 customers a year.  Additionally, in 2015 the Austin City Council voted to no longer have a waitlist as well as include Veterans Affairs Supportive Housing (VASH) vouchers as a qualifier.

Customers who qualify for utility bill discounts are receiving an average of $792 per year per family, $248 of which comes from Austin Energy. Total utility bill savings for the recipients is over $18 million annually. Below is a summary of electric account savings only.

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                     | Data Type | Render Type |
| ======== | ============== | ==================================================== | ======================================== | ========= | =========== |
| Yes      | time           | fiscal_year                                          | Fiscal Year                              | number    | number      |
| Yes      | numeric metric | average_customers_served_monthly                     | Average Customers Served Monthly         | number    | number      |
| Yes      | numeric metric | average_household_savings_per_month                  | Average Household Savings Per Month      | money     | money       |
| Yes      | numeric metric | average_annual_combined_customer_savings_in_millions | Average Annual Combined Customer Savings | money     | money       |
| Yes      | numeric metric | automatic_enrollment                                 | Automatic Enrollment                     | number    | number      |
| Yes      | numeric metric | manual_enrollment                                    | Manual Enrollment                        | number    | number      |
| Yes      | numeric metric | total_enrollment                                     | Total Enrollment                         | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gdnf-za7q d:2006-01-01T00:00:00.000Z m:average_household_savings_per_month=22.73 m:average_customers_served_monthly=4959 m:manual_enrollment=4959 m:average_annual_combined_customer_savings_in_millions=1352000 m:total_enrollment=4959 m:automatic_enrollment=0

series e:gdnf-za7q d:2007-01-01T00:00:00.000Z m:average_household_savings_per_month=21.44 m:average_customers_served_monthly=5134 m:manual_enrollment=5134 m:average_annual_combined_customer_savings_in_millions=1320000 m:total_enrollment=5134 m:automatic_enrollment=0

series e:gdnf-za7q d:2008-01-01T00:00:00.000Z m:average_household_savings_per_month=22.56 m:average_customers_served_monthly=4005 m:manual_enrollment=4005 m:average_annual_combined_customer_savings_in_millions=1084000 m:total_enrollment=4005 m:automatic_enrollment=0
```

## Meta Commands

```ls
metric m:average_customers_served_monthly p:integer l:"Average Customers Served Monthly" t:dataTypeName=number

metric m:average_household_savings_per_month p:double l:"Average Household Savings Per Month" t:dataTypeName=money

metric m:average_annual_combined_customer_savings_in_millions p:double l:"Average Annual Combined Customer Savings" t:dataTypeName=money

metric m:automatic_enrollment p:integer l:"Automatic Enrollment" t:dataTypeName=number

metric m:manual_enrollment p:integer l:"Manual Enrollment" t:dataTypeName=number

metric m:total_enrollment p:integer l:"Total Enrollment" t:dataTypeName=number

entity e:gdnf-za7q l:"Electric Utility Discount Program By Year" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/gdnf-za7q

property e:gdnf-za7q t:meta.view v:id=gdnf-za7q v:category=Utility v:averageRating=0 v:name="Electric Utility Discount Program By Year" v:attribution="Austin Energy"

property e:gdnf-za7q t:meta.view.license v:name="Public Domain"

property e:gdnf-za7q t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:gdnf-za7q t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year | average_customers_served_monthly | average_household_savings_per_month | average_annual_combined_customer_savings_in_millions | automatic_enrollment | manual_enrollment | total_enrollment | 
| =========== | ================================ | =================================== | ==================================================== | ==================== | ================= | ================ | 
| 2006        | 4959                             | 22.73                               | 1352000.00                                           | 0                    | 4959              | 4959             | 
| 2007        | 5134                             | 21.44                               | 1320000.00                                           | 0                    | 5134              | 5134             | 
| 2008        | 4005                             | 22.56                               | 1084000.00                                           | 0                    | 4005              | 4005             | 
| 2009        | 5137                             | 23.58                               | 1453000.00                                           | 2547                 | 2590              | 5137             | 
| 2010        | 8599                             | 23.29                               | 2402000.00                                           | 3525                 | 5074              | 8599             | 
| 2011        | 8587                             | 23.33                               | 2403000.00                                           | 2748                 | 5839              | 8587             | 
| 2012        | 6608                             | 24.05                               | 1908000.00                                           | 4505                 | 2103              | 6608             | 
| 2013        | 11728                            | 20.68                               | 2910000.00                                           | 9089                 | 2639              | 11728            | 
| 2014        | 35306                            | 21.22                               | 8992000.00                                           | 24553                | 10753             | 35306            | 
| 2015        | 42644                            | 20.65                               | 10569000.00                                          | 36190                | 6454              | 42644            | 
```