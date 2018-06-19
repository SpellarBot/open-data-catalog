# EMS - Administrative Measures - Finance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-administrative-measures-finance) |
| Metadata | [Link](https://data.austintexas.gov/api/views/uc3g-2rk9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/uc3g-2rk9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/uc3g-2rk9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | uc3g-2rk9 |
| Name | EMS - Administrative Measures - Finance |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Created | 2016-07-29T16:18:57Z |
| Publication Date | 2016-07-29T16:24:14Z |

## Description

*** TEMPORARY DATASET !! *** This is a temporary dataset that is being used for prototyping and testing and may be REMOVED without notice.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                            | Data Type     | Render Type   |
| ======== | ============== | ==================================== | =============================== | ============= | ============= |
| Yes      | numeric metric | month_key                            | Month_Key                       | number        | number        |
| Yes      | time           | month_start_date                     | Month                           | calendar_date | calendar_date |
| Yes      | series tag     | month_name                           | Month Name                      | text          | text          |
| Yes      | numeric metric | percent_actual_revenue_county        | Revenue Percent of Goal -- FYTD | percent       | percent       |
| Yes      | numeric metric | percent_actual_revenue_county_target | Performance Target              | percent       | percent       |
| Yes      | numeric metric | count_accounts_billed                | Accounts Billed                 | number        | number        |
| Yes      | numeric metric | average_billing_interval_days        | Average Billing Interval (days) | number        | number        |
| Yes      | numeric metric | average_billing_interval_target      | Billing Interval Target         | number        | number        |
| Yes      | numeric metric | percent_customer_satisfaction        | Customer Satisfaction Rate      | percent       | percent       |
| Yes      | numeric metric | percent_customer_satisfaction_target | Customer Satisfaction Target    | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:uc3g-2rk9 d:2013-10-01T00:00:00.000Z t:month_name="October 2013" m:percent_actual_revenue_county_target=100 m:percent_customer_satisfaction_target=95 m:average_billing_interval_days=4.783252522605 m:percent_actual_revenue_county=115.17 m:percent_customer_satisfaction=96.64 m:month_key=201310 m:count_accounts_billed=7631 m:average_billing_interval_target=10

series e:uc3g-2rk9 d:2013-11-01T00:00:00.000Z t:month_name="November 2013" m:percent_actual_revenue_county_target=100 m:percent_customer_satisfaction_target=95 m:average_billing_interval_days=5.444501191692 m:percent_actual_revenue_county=100.67 m:percent_customer_satisfaction=91.92 m:month_key=201311 m:count_accounts_billed=5874 m:average_billing_interval_target=10

series e:uc3g-2rk9 d:2013-12-01T00:00:00.000Z t:month_name="December 2013" m:percent_actual_revenue_county_target=100 m:percent_customer_satisfaction_target=95 m:average_billing_interval_days=6.345419564895 m:percent_actual_revenue_county=105.45 m:percent_customer_satisfaction=98.15 m:month_key=201312 m:count_accounts_billed=6757 m:average_billing_interval_target=10
```

## Meta Commands

```ls
metric m:month_key p:integer l:Month_Key t:dataTypeName=number

metric m:percent_actual_revenue_county p:float l:"Revenue Percent of Goal -- FYTD" t:dataTypeName=percent

metric m:percent_actual_revenue_county_target p:integer l:"Performance Target" t:dataTypeName=percent

metric m:count_accounts_billed p:integer l:"Accounts Billed" t:dataTypeName=number

metric m:average_billing_interval_days p:double l:"Average Billing Interval (days)" t:dataTypeName=number

metric m:average_billing_interval_target p:integer l:"Billing Interval Target" t:dataTypeName=number

metric m:percent_customer_satisfaction p:float l:"Customer Satisfaction Rate" t:dataTypeName=percent

metric m:percent_customer_satisfaction_target p:float l:"Customer Satisfaction Target" t:dataTypeName=percent

entity e:uc3g-2rk9 l:"EMS - Administrative Measures - Finance" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/uc3g-2rk9

property e:uc3g-2rk9 t:meta.view v:id=uc3g-2rk9 v:category="Public Safety" v:averageRating=0 v:name="EMS - Administrative Measures - Finance" v:attribution="Austin-Travis County EMS"

property e:uc3g-2rk9 t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:uc3g-2rk9 t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | month_name    | percent_actual_revenue_county | percent_actual_revenue_county_target | count_accounts_billed | average_billing_interval_days | average_billing_interval_target | percent_customer_satisfaction | percent_customer_satisfaction_target | 
| ========= | =================== | ============= | ============================= | ==================================== | ===================== | ============================= | =============================== | ============================= | ==================================== | 
| 201310    | 2013-10-01T00:00:00 | October 2013  | 115.17                        | 100                                  | 7631                  | 4.7832525226050002            | 10                              | 96.64                         | 95.00                                | 
| 201311    | 2013-11-01T00:00:00 | November 2013 | 100.67                        | 100                                  | 5874                  | 5.4445011916919999            | 10                              | 91.92                         | 95.00                                | 
| 201312    | 2013-12-01T00:00:00 | December 2013 | 105.45                        | 100                                  | 6757                  | 6.3454195648949998            | 10                              | 98.15                         | 95.00                                | 
| 201401    | 2014-01-01T00:00:00 | January 2014  | 108.82                        | 100                                  | 7884                  | 6.2091577879240001            | 10                              | 99.25                         | 95.00                                | 
| 201402    | 2014-02-01T00:00:00 | February 2014 | 104.90                        | 100                                  | 6485                  | 5.1512721665379999            | 10                              | 93.98                         | 95.00                                | 
| 201403    | 2014-03-01T00:00:00 | March 2014    | 106.22                        | 100                                  | 6348                  | 4.8412098298670001            | 10                              | 97.90                         | 95.00                                | 
| 201404    | 2014-04-01T00:00:00 | April 2014    | 106.54                        | 100                                  | 7029                  | 5.5731967562950002            | 10                              | 99.29                         | 95.00                                | 
| 201405    | 2014-05-01T00:00:00 | May 2014      | 106.91                        | 100                                  | 7514                  | 5.2053500133080002            | 10                              | 98.39                         | 95.00                                | 
| 201406    | 2014-06-01T00:00:00 | June 2014     | 107.28                        | 100                                  | 6937                  | 5.0632838402760001            | 10                              | 98.26                         | 95.00                                | 
| 201407    | 2014-07-01T00:00:00 | July 2014     | 107.02                        | 100                                  | 7815                  | 5.985412667946                | 10                              | 97.27                         | 95.00                                | 
```