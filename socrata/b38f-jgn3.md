# Unemployment Insurance Benefit Payments by Industry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-benefit-payments-by-industry) |
| Metadata | [Link](https://data.iowa.gov/api/views/b38f-jgn3) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/b38f-jgn3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/b38f-jgn3/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | b38f-jgn3 |
| Name | Unemployment Insurance Benefit Payments by Industry |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | unemployment insurance, benefits, industry, ui |
| Created | 2015-02-17T19:50:53Z |
| Publication Date | 2016-05-03T14:54:55Z |

## Description

This dataset contains statewide Unemployment Insurance payment activities by industry group. Industry groups are based on NAICS sectors (North American Industry Classification System).

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | month_ending       | Month              | calendar_date | calendar_date |
| Yes      | series tag     | naics_code         | Sector             | text          | text          |
| Yes      | series tag     | naics_sector_title | NAICS Sector Title | text          | text          |
| Yes      | numeric metric | benefitpayments    | Benefit Paid       | money         | money         |
| Yes      | numeric metric | weeks_compensated  | Weeks Compensated  | number        | number        |
| Yes      | numeric metric | first_payments     | First Payments     | number        | number        |
| Yes      | numeric metric | final_payments     | Final Payments     | number        | number        |
```

## Time Field

```ls
Value = month_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:b38f-jgn3 d:2011-01-31T00:00:00.000Z t:naics_sector_title=Utilities t:naics_code=22 m:weeks_compensated=347 m:first_payments=38 m:benefitpayments=124593.23 m:final_payments=7

series e:b38f-jgn3 d:2015-01-31T00:00:00.000Z t:naics_sector_title="Educational Services" t:naics_code=61 m:weeks_compensated=1630 m:first_payments=85 m:benefitpayments=528119.27 m:final_payments=59

series e:b38f-jgn3 d:2010-01-31T00:00:00.000Z t:naics_sector_title="Agriculture, Forestry, Fishing and Hunting" t:naics_code=11 m:weeks_compensated=1629 m:first_payments=107 m:benefitpayments=486346.71 m:final_payments=46
```

## Meta Commands

```ls
metric m:benefitpayments p:double l:"Benefit Paid" d:"BenefitPayments: Unemployment benefits paid to individuals under the state UI program." t:dataTypeName=money

metric m:weeks_compensated p:integer l:"Weeks Compensated" d:"Weeks Compensated: The number of weeks claimed for which UI benefits are paid." t:dataTypeName=number

metric m:first_payments p:integer l:"First Payments" d:"First Payments: The number of claimants receiving their the first payment in a benefit year for a week of unemployment claimed under the state UI program." t:dataTypeName=number

metric m:final_payments p:integer l:"Final Payments" d:"Final Payments: (Exhaustees): Number of claimants drawing the final payment of their original entitlement of UI benefits." t:dataTypeName=number

entity e:b38f-jgn3 l:"Unemployment Insurance Benefit Payments by Industry" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/b38f-jgn3

property e:b38f-jgn3 t:meta.view v:id=b38f-jgn3 v:category=Economy v:averageRating=0 v:name="Unemployment Insurance Benefit Payments by Industry" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:b38f-jgn3 t:meta.view.license v:name="Public Domain"

property e:b38f-jgn3 t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:b38f-jgn3 t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| month_ending        | naics_code | naics_sector_title                            | benefitpayments | weeks_compensated | first_payments | final_payments | 
| =================== | ========== | ============================================= | =============== | ================= | ============== | ============== | 
| 2011-01-31T00:00:00 | 22         | Utilities                                     | 124593.23       | 347               | 38             | 7              | 
| 2015-01-31T00:00:00 | 61         | Educational Services                          | 528119.27       | 1630              | 85             | 59             | 
| 2010-01-31T00:00:00 | 11         | Agriculture, Forestry, Fishing and Hunting    | 486346.71       | 1629              | 107            | 46             | 
| 2010-01-31T00:00:00 | 21         | Mining, Quarrying, and Oil and Gas Extraction | 1075353.00      | 2933              | 416            | 7              | 
| 2010-01-31T00:00:00 | 22         | Utilities                                     | 177073.34       | 492               | 36             | 7              | 
| 2010-01-31T00:00:00 | 23         | Construction                                  | 23005089.19     | 64923             | 6431           | 952            | 
| 2010-01-31T00:00:00 | 31         | Manufacturing                                 | 19328353.90     | 58864             | 7657           | 1251           | 
| 2010-01-31T00:00:00 | 42         | Wholesale Trade                               | 2564831.66      | 8229              | 583            | 260            | 
| 2010-01-31T00:00:00 | 44         | Retail Trade                                  | 3325516.04      | 12805             | 945            | 373            | 
| 2010-01-31T00:00:00 | 48         | Transportation and Warehousing                | 2492611.86      | 8009              | 715            | 184            | 
```