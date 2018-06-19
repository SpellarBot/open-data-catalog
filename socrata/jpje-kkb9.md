# Unemployment Insurance Claims And Payments (Statewide - Monthly)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-claims-and-payments-statewide-monthly) |
| Metadata | [Link](https://data.iowa.gov/api/views/jpje-kkb9) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/jpje-kkb9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/jpje-kkb9/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | jpje-kkb9 |
| Name | Unemployment Insurance Claims And Payments (Statewide - Monthly) |
| Attribution | Iowa Workforce Development, Labor Market Information Division, ETA-5159 |
| Category | Economy |
| Tags | unemployment insurance, benefits, ui, claims, initial claims |
| Created | 2014-12-23T19:02:45Z |
| Publication Date | 2017-03-02T19:39:02Z |

## Description

This dataset contains statewide Unemployment Insurance claims and payment activities. This data is based on the ETA-5159 report that IWD submits to the US Department of Labor, Employment and Training Administration. (The number of UI recipients is the only exception.)

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                   | Data Type     | Render Type   |
| ======== | ============== | ======================= | ====================== | ============= | ============= |
| Yes      | time           | month                   | Month                  | calendar_date | calendar_date |
| Yes      | numeric metric | initial_claims          | Initial Claims         | number        | number        |
| Yes      | numeric metric | continued_weeks_claimed | Continued Weeks        | number        | number        |
| Yes      | numeric metric | benefits_paid           | Benefits Paid          | money         | money         |
| Yes      | numeric metric | weeks_compensated       | Weeks Compen.          | number        | number        |
| Yes      | numeric metric | average_weekly_benefit  | Average Weekly Benefit | money         | money         |
| Yes      | numeric metric | ui_recipients           | Recipients             | number        | number        |
| Yes      | numeric metric | first_payments          | First Payments         | number        | number        |
| Yes      | numeric metric | final_payments          | Final Payments         | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jpje-kkb9 d:2000-01-31T00:00:00.000Z m:weeks_compensated=118252 m:first_payments=19299 m:benefits_paid=27275634 m:average_weekly_benefit=230.66 m:ui_recipients=42635 m:initial_claims=18783 m:continued_weeks_claimed=151465 m:final_payments=1259

series e:jpje-kkb9 d:2000-02-29T00:00:00.000Z m:weeks_compensated=118309 m:first_payments=8279 m:benefits_paid=27480496 m:average_weekly_benefit=232.28 m:ui_recipients=36151 m:initial_claims=10557 m:continued_weeks_claimed=122461 m:final_payments=1143

series e:jpje-kkb9 d:2000-03-31T00:00:00.000Z m:weeks_compensated=122987 m:first_payments=5523 m:benefits_paid=28419193 m:average_weekly_benefit=231.07 m:ui_recipients=34406 m:initial_claims=9223 m:continued_weeks_claimed=101975 m:final_payments=1814
```

## Meta Commands

```ls
metric m:initial_claims p:integer l:"Initial Claims" d:"Initial Claim: Initial claims include new claims and additional claims. A new claim is any notice of unemployment filed to request a determination of entitlement to and eligibility for compensation. An additional claim is a notice of unemployment filed to begin a second or subsequent period of eligibility within a benefit year or period of eligibility. ETA-5159 (101-1)" t:dataTypeName=number

metric m:continued_weeks_claimed p:integer l:"Continued Weeks" d:"Continued Weeks Claimed: Number of weeks of UI benefits claimed. ETA-5159 [(201-10) plus (201-11)]" t:dataTypeName=number

metric m:benefits_paid p:integer l:"Benefits Paid" d:"Benefits Paid: Unemployment benefits paid to individuals under the regular state UI program. ETA-5159 (302-14)" t:dataTypeName=money

metric m:weeks_compensated p:integer l:"Weeks Compen." d:"Weeks Compensated: The number of weeks claimed for which UI benefits are paid. Weeks compensated for partial unemployment are included. ETA-5159 (301-14)" t:dataTypeName=number

metric m:average_weekly_benefit p:double l:"Average Weekly Benefit" d:"Average Weekly Benefit: UI benefits paid divided by the number of weeks compensated. Benefits paid for partial unemployment are included." t:dataTypeName=money

metric m:ui_recipients p:integer l:Recipients d:"Benefit Recipients: The number of claimants receiving at least one UI benefit payment during the month. State report: [NX.UI.P001.NVSAM.CNTY.BENEFITS (Recipients - UI)]" t:dataTypeName=number

metric m:first_payments p:integer l:"First Payments" d:"First Payment: The number of claimants receiving their the UI benefit first payment in a benefit year for a week of unemployment claimed under the state UI program. ETA-5159 (303-21)" t:dataTypeName=number

metric m:final_payments p:integer l:"Final Payments" d:"Final Payment: Number of claimants drawing the final payment of their original entitlement of regular Unemployment Insurance (exhaustees). ETA-5159 (303-26)" t:dataTypeName=number

entity e:jpje-kkb9 l:"Unemployment Insurance Claims And Payments (Statewide - Monthly)" t:attribution="Iowa Workforce Development, Labor Market Information Division, ETA-5159" t:url=https://data.iowa.gov/api/views/jpje-kkb9

property e:jpje-kkb9 t:meta.view v:id=jpje-kkb9 v:category=Economy v:averageRating=0 v:name="Unemployment Insurance Claims And Payments (Statewide - Monthly)" v:attribution="Iowa Workforce Development, Labor Market Information Division, ETA-5159"

property e:jpje-kkb9 t:meta.view.license v:name="Public Domain"

property e:jpje-kkb9 t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:jpje-kkb9 t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| month               | initial_claims | continued_weeks_claimed | benefits_paid | weeks_compensated | average_weekly_benefit | ui_recipients | first_payments | final_payments | 
| =================== | ============== | ======================= | ============= | ================= | ====================== | ============= | ============== | ============== | 
| 2000-01-31T00:00:00 | 18783          | 151465                  | 27275634      | 118252            | 230.66                 | 42635         | 19299          | 1259           | 
| 2000-02-29T00:00:00 | 10557          | 122461                  | 27480496      | 118309            | 232.28                 | 36151         | 8279           | 1143           | 
| 2000-03-31T00:00:00 | 9223           | 101975                  | 28419193      | 122987            | 231.07                 | 34406         | 5523           | 1814           | 
| 2000-04-30T00:00:00 | 7503           | 70895                   | 16819391      | 73892             | 227.62                 | 25243         | 3810           | 1582           | 
| 2000-05-31T00:00:00 | 7917           | 71082                   | 12773144      | 57295             | 222.94                 | 19246         | 4218           | 1190           | 
| 2000-06-30T00:00:00 | 9723           | 60078                   | 14611532      | 66187             | 220.76                 | 19507         | 5332           | 1307           | 
| 2000-07-31T00:00:00 | 11583          | 77524                   | 13312987      | 59632             | 223.25                 | 21904         | 6759           | 1112           | 
| 2000-08-31T00:00:00 | 7961           | 59478                   | 14991345      | 67027             | 223.66                 | 18807         | 4385           | 1229           | 
| 2000-09-30T00:00:00 | 7404           | 51761                   | 10992082      | 48149             | 228.29                 | 15859         | 3366           | 1023           | 
| 2000-10-31T00:00:00 | 9762           | 65629                   | 11551020      | 49773             | 232.07                 | 17089         | 4655           | 1010           | 
```