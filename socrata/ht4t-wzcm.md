# Taxi Improvement Fund (TIF) Medallion Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/taxi-improvement-fund-tif-medallion-payments) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ht4t-wzcm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ht4t-wzcm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ht4t-wzcm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ht4t-wzcm |
| Name | Taxi Improvement Fund (TIF) Medallion Payments |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, tlc, medallion, tif, taxi improvement fund, wheelchair vehicle, wheelchair accessible vehicle, wav, taxi improvement, wheelchair grant, $14, 000, wav grant, wav fund |
| Created | 2016-11-17T14:57:46Z |
| Publication Date | 2017-04-03T14:55:57Z |

## Description

This is a list of monthly payments made to owners of Wheelchair Accessible Vehicles (WAVs) from the Taxi Improvement Fund (TIF). Information is listed by medallion and agent number, and is updated after each payment is distributed from the Taxi Improvement Fund, approximately once per month. For more information see the TIF Owner page (http://www.nyc.gov/html/tlc/html/industry/taxi_improvement_fund_owner.shtml).

If you have questions or comments on this data set, please contact the Taxi Improvement Fund Project Team at TIF@TLC.NYC.GOV or visit the TIF Frequently Asked Questions page: http://www.nyc.gov/html/tlc/html/industry/taxi_improvement_fund_faq.shtml/.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | license_number             | License Number             | text          | text          |
| Yes      | series tag     | agent_number               | Agent Number               | text          | text          |
| Yes      | numeric metric | hackup_payment_amount      | Hackup Payment Amount      | money         | money         |
| Yes      | numeric metric | operational_payment_amount | Operational Payment Amount | money         | money         |
| Yes      | numeric metric | total_payment_amount       | Total Payment Amount       | money         | money         |
| Yes      | time           | payment_date               | Payment Date               | calendar_date | calendar_date |
| No       |                | last_date_updated          | Last Date Updated          | calendar_date | calendar_date |
| Yes      | series tag     | last_time_updated          | Last Time Updated          | text          | text          |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_date_updated
```

## Data Commands

```ls
series e:ht4t-wzcm d:2017-03-31T00:00:00.000Z t:last_time_updated=10:53:56 t:license_number=3J80 t:agent_number=A0017 m:hackup_payment_amount=0 m:total_payment_amount=1333.33 m:operational_payment_amount=1333.33

series e:ht4t-wzcm d:2017-03-31T00:00:00.000Z t:last_time_updated=10:53:56 t:license_number=3N88 t:agent_number=A0017 m:hackup_payment_amount=0 m:total_payment_amount=1333.33 m:operational_payment_amount=1333.33

series e:ht4t-wzcm d:2017-03-31T00:00:00.000Z t:last_time_updated=10:53:56 t:license_number=4A25 t:agent_number=A0017 m:hackup_payment_amount=0 m:total_payment_amount=1333.33 m:operational_payment_amount=1333.33
```

## Meta Commands

```ls
metric m:hackup_payment_amount p:double l:"Hackup Payment Amount" d:"The payment the owner or agent received, following successful hackup of a WAV vehicle, during this payment period." t:dataTypeName=money

metric m:operational_payment_amount p:double l:"Operational Payment Amount" d:"The sum of all $1,333 payments, each of which follows a successful tri-annual inspection, the owner or agent received during this payment period." t:dataTypeName=money

metric m:total_payment_amount p:double l:"Total Payment Amount" d:"The sum of all hackup and operational payments made during the listed payment period." t:dataTypeName=money

entity e:ht4t-wzcm l:"Taxi Improvement Fund (TIF) Medallion Payments" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/ht4t-wzcm

property e:ht4t-wzcm t:meta.view v:id=ht4t-wzcm v:category=Transportation v:averageRating=0 v:name="Taxi Improvement Fund (TIF) Medallion Payments" v:attribution="Taxi and Limousine Commission (TLC)"

property e:ht4t-wzcm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ht4t-wzcm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | agent_number | hackup_payment_amount | operational_payment_amount | total_payment_amount | payment_date        | last_date_updated   | last_time_updated | 
| ============== | ============ | ===================== | ========================== | ==================== | =================== | =================== | ================= | 
| 3J80           | A0017        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 3N88           | A0017        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 4A25           | A0017        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 6N58           | A0017        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 7E31           | A0017        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 8N67           | A0017        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 5A33           |              | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 2G33           |              | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 4N47           | A0206        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
| 7J23           | A0206        | 0.00                  | 1333.33                    | 1333.33              | 2017-03-31T00:00:00 | 2017-04-03T00:00:00 | 10:53:56          | 
```