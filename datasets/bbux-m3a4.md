# Unemployment Compensation Fund Status - Benefits Paid

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-compensation-fund-status-benefits-paid) |
| Metadata | [Link](https://data.iowa.gov/api/views/bbux-m3a4) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/bbux-m3a4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/bbux-m3a4/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | bbux-m3a4 |
| Name | Unemployment Compensation Fund Status - Benefits Paid |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | unemployment insurance, ui benefits, ui trust fund |
| Created | 2015-05-01T19:51:38Z |
| Publication Date | 2017-02-27T20:49:45Z |

## Description

This dataset contains annual Unemployment Insurance Benefits data. This data is analyzed in the "Status Report on the Iowa Unemployment Compensation Trust Fund" report.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | first_payments          | First Payments          | number    | number      |
| Yes      | numeric metric | final_paymants          | Final Paymants          | number    | number      |
| Yes      | numeric metric | average_duration        | Average Duration        | number    | number      |
| Yes      | numeric metric | exhaustion_rate         | Exhaustion Rate         | percent   | percent     |
| Yes      | numeric metric | weeks_compensated       | Weeks Compensated       | number    | number      |
| Yes      | numeric metric | ui_benefits_paid        | UI Benefits Paid        | money     | money       |
| Yes      | numeric metric | average_weekly_benefits | Average Weekly Benefits | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bbux-m3a4 d:1980-01-01T00:00:00.000Z m:ui_benefits_paid=191363265 m:weeks_compensated=1679090 m:average_weekly_benefits=113.97 m:first_payments=141617 m:final_paymants=32190 m:average_duration=11.9 m:exhaustion_rate=31.2

series e:bbux-m3a4 d:1981-01-01T00:00:00.000Z m:ui_benefits_paid=174383395 m:weeks_compensated=1472111 m:average_weekly_benefits=118.46 m:first_payments=111712 m:final_paymants=33523 m:average_duration=13.2 m:exhaustion_rate=26.7

series e:bbux-m3a4 d:1982-01-01T00:00:00.000Z m:ui_benefits_paid=292906783 m:weeks_compensated=2218692 m:average_weekly_benefits=132.02 m:first_payments=151520 m:final_paymants=58240 m:average_duration=14.6 m:exhaustion_rate=38.7
```

## Meta Commands

```ls
metric m:first_payments p:integer l:"First Payments" d:"The number of claimants receiving their the first payment in a benefit year for a week of unemployment claimed under the state UI program. [ETA-5159 (303-21)]" t:dataTypeName=number

metric m:final_paymants p:integer l:"Final Paymants" d:"The number of claimants drawing the final payment of their original UI entitlement. This is also called benefit exhaustions. [ETA-5159 (303-24)]" t:dataTypeName=number

metric m:average_duration p:float l:"Average Duration" d:"The number of weeks compensated divided by the number of first payments." t:dataTypeName=number

metric m:exhaustion_rate p:float l:"Exhaustion Rate" d:"A rate computed by dividing the average monthly final payments by the average monthly first payments. To allow for the normal flow of claimants through the program, the numerator lags the denominator by 26 weeks," t:dataTypeName=percent

metric m:weeks_compensated p:integer l:"Weeks Compensated" d:"The number of weeks claimed for which UI benefits are paid. Weeks compensated for partial unemployment are included. [ETA-5159 (301-14)" t:dataTypeName=number

metric m:ui_benefits_paid p:integer l:"UI Benefits Paid" d:"Unemployment benefits paid under the regular unemployment program. [ETA-5159 (302-14)]" t:dataTypeName=money

metric m:average_weekly_benefits p:double l:"Average Weekly Benefits" d:"UI benefits paid divided by the number of weeks compensated." t:dataTypeName=money

entity e:bbux-m3a4 l:"Unemployment Compensation Fund Status - Benefits Paid" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/bbux-m3a4

property e:bbux-m3a4 t:meta.view v:id=bbux-m3a4 v:category=Economy v:attributionLink=https://www.iowaworkforcedevelopment.gov/sites/search.iowaworkforcedevelopment.gov/files/unemploymentcomp_trustfund_statusreport_1.pdf v:averageRating=0 v:name="Unemployment Compensation Fund Status - Benefits Paid" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:bbux-m3a4 t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:bbux-m3a4 t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| year | first_payments | final_paymants | average_duration | exhaustion_rate | weeks_compensated | ui_benefits_paid | average_weekly_benefits | 
| ==== | ============== | ============== | ================ | =============== | ================= | ================ | ======================= | 
| 1980 | 141617         | 32190          | 11.9             | 31.2            | 1679090           | 191363265        | 113.97                  | 
| 1981 | 111712         | 33523          | 13.2             | 26.7            | 1472111           | 174383395        | 118.46                  | 
| 1982 | 151520         | 58240          | 14.6             | 38.7            | 2218692           | 292906783        | 132.02                  | 
| 1983 | 117681         | 55158          | 15.1             | 40.1            | 1781786           | 239456114        | 134.39                  | 
| 1984 | 97603          | 31219          | 13               | 33.3            | 1265144           | 155970412        | 123.28                  | 
| 1985 | 97124          | 32174          | 14.4             | 32.9            | 1401655           | 178994810        | 127.70                  | 
| 1986 | 84882          | 26739          | 14.7             | 28.9            | 1250942           | 168408195        | 134.63                  | 
| 1987 | 66865          | 21999          | 14.3             | 29.2            | 955227            | 130657789        | 136.78                  | 
| 1988 | 67023          | 16125          | 12.4             | 24.9            | 831553            | 118739602        | 142.79                  | 
| 1989 | 73393          | 15970          | 11.9             | 23.1            | 874264            | 130014218        | 148.71                  | 
```