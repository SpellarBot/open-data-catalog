# Unemployment Insurance Claims And Payments (Statewide - Annual)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-claims-and-payments-statewide-annual) |
| Metadata | [Link](https://data.iowa.gov/api/views/rmcb-sifx) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rmcb-sifx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rmcb-sifx/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rmcb-sifx |
| Name | Unemployment Insurance Claims And Payments (Statewide - Annual) |
| Attribution | Iowa Workforce Development, Labor Market Information Division, ETA-5159 |
| Category | Economy |
| Tags | unemployment insurance, benefits, ui, claims, initial claims |
| Created | 2015-07-21T14:39:50Z |
| Publication Date | 2017-03-02T19:42:52Z |

## Description

This dataset contains an annual summary of the statewide Unemployment Insurance claims and payment activities. This data is based on the ETA-5159 report that IWD submits to the US Department of Labor, Employment and Training Administration. (The number of UI recipients is the only exception.)

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                   | Data Type | Render Type |
| ======== | ============== | ======================= | ====================== | ========= | =========== |
| Yes      | time           | year                    | Year                   | number    | number      |
| Yes      | numeric metric | initial_claims          | Initial Claims         | number    | number      |
| Yes      | numeric metric | continued_weeks_claimed | Continued Weeks        | number    | number      |
| Yes      | numeric metric | benefits_paid           | Benefits Paid          | money     | money       |
| Yes      | numeric metric | weeks_compensated       | Weeks Compen.          | number    | number      |
| Yes      | numeric metric | average_weekly_benefit  | Average Weekly Benefit | money     | money       |
| Yes      | numeric metric | ui_recipients           | UI Recipients          | number    | number      |
| Yes      | numeric metric | first_payments          | First Payments         | number    | number      |
| Yes      | numeric metric | final_payments          | Final Payments         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rmcb-sifx d:2000-01-01T00:00:00.000Z m:weeks_compensated=949794 m:first_payments=84455 m:benefits_paid=217740932 m:average_weekly_benefit=229.25 m:ui_recipients=104390 m:initial_claims=153331 m:continued_weeks_claimed=1009148 m:final_payments=15626

series e:rmcb-sifx d:2001-01-01T00:00:00.000Z m:weeks_compensated=1324644 m:first_payments=113983 m:benefits_paid=317145149 m:average_weekly_benefit=239.42 m:ui_recipients=140487 m:initial_claims=211769 m:continued_weeks_claimed=1460075 m:final_payments=21356

series e:rmcb-sifx d:2002-01-01T00:00:00.000Z m:weeks_compensated=1498185 m:first_payments=111411 m:benefits_paid=366698460 m:average_weekly_benefit=244.76 m:ui_recipients=145128 m:initial_claims=209114 m:continued_weeks_claimed=1630182 m:final_payments=32038
```

## Meta Commands

```ls
metric m:initial_claims p:integer l:"Initial Claims" d:"Initial Claim: Initial claims include new claims and additional claims. A new claim is any notice of unemployment filed to request a determination of entitlement to and eligibility for compensation. An additional claim is a notice of unemployment filed to begin a second or subsequent period of eligibility within a benefit year or period of eligibility. ETA-5159 (101-1)" t:dataTypeName=number

metric m:continued_weeks_claimed p:integer l:"Continued Weeks" d:"Continued Weeks Claimed: Number of weeks of UI benefits claimed. ETA-5159 [(201-10) plus (201-11)]" t:dataTypeName=number

metric m:benefits_paid p:integer l:"Benefits Paid" d:"Benefits Paid: Unemployment benefits paid to individuals under the regular state UI program. ETA-5159 (302-14)" t:dataTypeName=money

metric m:weeks_compensated p:integer l:"Weeks Compen." d:"Weeks Compensated: The number of weeks claimed for which UI benefits are paid. Weeks compensated for partial unemployment are included. ETA-5159 (301-14)" t:dataTypeName=number

metric m:average_weekly_benefit p:double l:"Average Weekly Benefit" d:"Average Weekly Benefit: UI benefits paid divided by the number of weeks compensated. Benefits paid for partial unemployment are included." t:dataTypeName=money

metric m:ui_recipients p:integer l:"UI Recipients" d:"Benefit Recipients: The number of claimants receiving at least one UI benefit payment during the year. State report: [NX.UI.P001.NVSAM.CNTY.BENEFITS (Recipients - UI)]" t:dataTypeName=number

metric m:first_payments p:integer l:"First Payments" d:"First Payment: The number of claimants receiving their the UI benefit first payment in a benefit year for a week of unemployment claimed under the state UI program. ETA-5159 (303-21)" t:dataTypeName=number

metric m:final_payments p:integer l:"Final Payments" d:"Final Payment: Number of claimants drawing the final payment of their original entitlement of regular Unemployment Insurance (exhaustees). ETA-5159 (303-26)" t:dataTypeName=number

entity e:rmcb-sifx l:"Unemployment Insurance Claims And Payments (Statewide - Annual)" t:attribution="Iowa Workforce Development, Labor Market Information Division, ETA-5159" t:url=https://data.iowa.gov/api/views/rmcb-sifx

property e:rmcb-sifx t:meta.view v:id=rmcb-sifx v:category=Economy v:averageRating=0 v:name="Unemployment Insurance Claims And Payments (Statewide - Annual)" v:attribution="Iowa Workforce Development, Labor Market Information Division, ETA-5159"

property e:rmcb-sifx t:meta.view.license v:name="Public Domain"

property e:rmcb-sifx t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:rmcb-sifx t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| year | initial_claims | continued_weeks_claimed | benefits_paid | weeks_compensated | average_weekly_benefit | ui_recipients | first_payments | final_payments | 
| ==== | ============== | ======================= | ============= | ================= | ====================== | ============= | ============== | ============== | 
| 2000 | 153331         | 1009148                 | 217740932     | 949794            | 229.25                 | 104390        | 84455          | 15626          | 
| 2001 | 211769         | 1460075                 | 317145149     | 1324644           | 239.42                 | 140487        | 113983         | 21356          | 
| 2002 | 209114         | 1630182                 | 366698460     | 1498185           | 244.76                 | 145128        | 111411         | 32038          | 
| 2003 | 199123         | 1642973                 | 381483335     | 1532402           | 248.94                 | 142309        | 113570         | 33690          | 
| 2004 | 167879         | 1380342                 | 312492801     | 1253028           | 249.39                 | 117876        | 88976          | 26896          | 
| 2005 | 173402         | 1271099                 | 296315121     | 1141540           | 259.57                 | 115300        | 91540          | 22399          | 
| 2006 | 179609         | 1255251                 | 312894095     | 1161526           | 269.38                 | 117267        | 92610          | 21901          | 
| 2007 | 176742         | 1282938                 | 329639456     | 1176569           | 280.17                 | 119264        | 91367          | 22305          | 
| 2008 | 264683         | 1521570                 | 421486477     | 1459395           | 288.81                 | 145771        | 126309         | 26425          | 
| 2009 | 401554         | 2724672                 | 788089658     | 2571688           | 306.45                 | 212710        | 165030         | 63657          | 
```