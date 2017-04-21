# Budget Billing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-billing) |
| Metadata | [Link](https://data.austintexas.gov/api/views/2b2e-w4kf) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/2b2e-w4kf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/2b2e-w4kf/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 2b2e-w4kf |
| Name | Budget Billing |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, budget billing |
| Created | 2015-08-17T14:00:31Z |
| Publication Date | 2016-11-07T15:55:55Z |

## Description

Budget billing is available to customers who prefer to avoid significant fluctuations in their monthly utility bills. Austin Energy calculates a monthly utility bill payment from the average of a customer's utility bills from the past 12 months. Accounts are reviewed and adjusted every six months. The averages reflect all City of Austin utilities including electric, water, wastewater, solid waste, transportation, and drainage fees. Go to austinenergy.com/go/budgetbilling to learn more.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag     | fiscal_year                         | Fiscal Year                         | text          | text          |
| Yes      | series tag     | month_and_year                      | Month and Year                      | text          | text          |
| Yes      | time           | calendar_date_utc_format            | calendar date UTC format            | calendar_date | calendar_date |
| No       |                | calendar_year                       | calendar year                       | number        | number        |
| Yes      | series tag     | calendar_month                      | calendar month                      | text          | text          |
| Yes      | numeric metric | billed_levelized_accounts_per_month | Billed Levelized Accounts Per Month | number        | number        |
| Yes      | numeric metric | average_levelized_bill_amount       | Average Levelized Bill Amount       | money         | money         |
```

## Time Field

```ls
Value = calendar_date_utc_format
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = calendar_year
```

## Data Commands

```ls
series e:2b2e-w4kf d:2012-10-01T00:00:00.000Z t:fiscal_year="FY 2013" t:calendar_month=Oct t:month_and_year=12-Oct m:billed_levelized_accounts_per_month=16352 m:average_levelized_bill_amount=190.56

series e:2b2e-w4kf d:2012-11-01T00:00:00.000Z t:fiscal_year="FY 2013" t:calendar_month=Nov t:month_and_year=12-Nov m:billed_levelized_accounts_per_month=16564 m:average_levelized_bill_amount=191.67

series e:2b2e-w4kf d:2012-12-01T00:00:00.000Z t:fiscal_year="FY 2013" t:calendar_month=Dec t:month_and_year=12-Dec m:billed_levelized_accounts_per_month=16633 m:average_levelized_bill_amount=183.2
```

## Meta Commands

```ls
metric m:billed_levelized_accounts_per_month p:integer l:"Billed Levelized Accounts Per Month" t:dataTypeName=number

metric m:average_levelized_bill_amount p:double l:"Average Levelized Bill Amount" t:dataTypeName=money

entity e:2b2e-w4kf l:"Budget Billing" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/2b2e-w4kf

property e:2b2e-w4kf t:meta.view v:id=2b2e-w4kf v:category=Utility v:averageRating=0 v:name="Budget Billing" v:attribution="Austin Energy"

property e:2b2e-w4kf t:meta.view.license v:name="Public Domain"

property e:2b2e-w4kf t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:2b2e-w4kf t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | month_and_year | calendar_date_utc_format | calendar_year | calendar_month | billed_levelized_accounts_per_month | average_levelized_bill_amount | 
| =========== | ============== | ======================== | ============= | ============== | =================================== | ============================= | 
| FY 2013     | 12-Oct         | 2012-10-01T00:00:00      | 2012          | Oct            | 16352                               | 190.56                        | 
| FY 2013     | 12-Nov         | 2012-11-01T00:00:00      | 2012          | Nov            | 16564                               | 191.67                        | 
| FY 2013     | 12-Dec         | 2012-12-01T00:00:00      | 2012          | Dec            | 16633                               | 183.20                        | 
| FY 2013     | 13-Jan         | 2013-01-01T00:00:00      | 2013          | Jan            | 16790                               | 163.48                        | 
| FY 2013     | 13-Feb         | 2013-02-01T00:00:00      | 2013          | Feb            | 17024                               | 153.17                        | 
| FY 2013     | 13-Mar         | 2013-03-01T00:00:00      | 2013          | Mar            | 16989                               | 147.47                        | 
| FY 2013     | 13-Apr         | 2013-04-01T00:00:00      | 2013          | Apr            | 16989                               | 147.47                        | 
| FY 2013     | 13-May         | 2013-05-01T00:00:00      | 2013          | May            | 16618                               | 134.12                        | 
| FY 2013     | 13-Jun         | 2013-06-01T00:00:00      | 2013          | Jun            | 16539                               | 132.67                        | 
| FY 2013     | 13-Jul         | 2013-07-01T00:00:00      | 2013          | Jul            | 16771                               | 133.04                        | 
```