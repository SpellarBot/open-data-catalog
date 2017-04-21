# Payment Arrangements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/payment-arrangements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qhxa-cink) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qhxa-cink/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qhxa-cink/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qhxa-cink |
| Name | Payment Arrangements |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | payment arrangements, payment, installments, delinquent, energy |
| Created | 2016-09-06T18:21:35Z |
| Publication Date | 2016-10-24T13:43:24Z |

## Description

Utility payment arrangements are available to customers who fall behind on their utility bills. To enter into an arrangement, customers must make on time payments of their monthly bills which include the current billed amount plus a monthly installment of their delinquent total.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ========================================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                            | Fiscal Year                                | calendar_date | calendar_date |
| Yes      | numeric metric | avg_no_of_payment_arrangements_per_month | Avg. No. of Payment Arrangements Per Month | number        | number        |
| Yes      | numeric metric | residential_peak_per_fiscal_year         | Residential Peak $ Per Fiscal Year         | money         | money         |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qhxa-cink d:2016-01-01T00:00:00.000Z m:avg_no_of_payment_arrangements_per_month=22321 m:residential_peak_per_fiscal_year=23300000

series e:qhxa-cink d:2015-01-01T00:00:00.000Z m:avg_no_of_payment_arrangements_per_month=26587 m:residential_peak_per_fiscal_year=32000000

series e:qhxa-cink d:2014-01-01T00:00:00.000Z m:avg_no_of_payment_arrangements_per_month=22049 m:residential_peak_per_fiscal_year=29800000
```

## Meta Commands

```ls
metric m:avg_no_of_payment_arrangements_per_month p:integer l:"Avg. No. of Payment Arrangements Per Month" t:dataTypeName=number

metric m:residential_peak_per_fiscal_year p:integer l:"Residential Peak $ Per Fiscal Year" t:dataTypeName=money

entity e:qhxa-cink l:"Payment Arrangements" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/qhxa-cink

property e:qhxa-cink t:meta.view v:id=qhxa-cink v:category=Utility v:averageRating=0 v:name="Payment Arrangements" v:attribution="Austin Energy"

property e:qhxa-cink t:meta.view.license v:name="Public Domain"

property e:qhxa-cink t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:qhxa-cink t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | avg_no_of_payment_arrangements_per_month | residential_peak_per_fiscal_year | 
| =================== | ======================================== | ================================ | 
| 2016-01-01T00:00:00 | 22321                                    | 23300000                         | 
| 2015-01-01T00:00:00 | 26587                                    | 32000000                         | 
| 2014-01-01T00:00:00 | 22049                                    | 29800000                         | 
| 2013-01-01T00:00:00 | 10871                                    | 20200000                         | 
| 2012-01-01T00:00:00 | 7032                                     | 8000000                          | 
| 2011-01-01T00:00:00 | 13175                                    | 9000000                          | 
| 2010-01-01T00:00:00 | 12389                                    | 9100000                          | 
| 2009-01-01T00:00:00 | 11984                                    | 10300000                         | 
| 2008-01-01T00:00:00 | 11366                                    | 9500000                          | 
| 2007-01-01T00:00:00 | 7301                                     | 7700000                          | 
```