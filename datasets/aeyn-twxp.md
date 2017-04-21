# Unemployment Insurance Recipients and UI Benefit Payments by County (Monthly)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-recipients-and-ui-benefit-payments-by-county-monthly) |
| Metadata | [Link](https://data.iowa.gov/api/views/aeyn-twxp) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/aeyn-twxp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/aeyn-twxp/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | aeyn-twxp |
| Name | Unemployment Insurance Recipients and UI Benefit Payments by County (Monthly) |
| Attribution | Iowa Workforce Development - Labor Market Information Division |
| Category | Economy |
| Tags | unemployment insurance, benefits, ui, county, recipients |
| Created | 2014-12-24T14:15:32Z |
| Publication Date | 2016-04-01T15:08:54Z |

## Description

This dataset contains Iowa unemployment insurance benefit payments, weeks compensated, and number of benefit recipients by county. County data is based on the recipient?s place of residence.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | month_ending      | Month             | calendar_date | calendar_date |
| Yes      | series tag     | county_name       | County Name       | text          | text          |
| Yes      | numeric metric | benefits_paid     | Benefits Paid     | money         | money         |
| Yes      | numeric metric | weeks_compensated | Weeks Compensated | number        | number        |
| Yes      | numeric metric | recipients        | Recipients        | number        | number        |
| Yes      | numeric metric | first_payments    | First Payments    | number        | number        |
| Yes      | numeric metric | final_payments    | Final Payments    | number        | number        |
| Yes      | numeric metric | county_fip        | County FIP        | number        | number        |
| Yes      | series tag     | gnis_feature_id   | GNIS Feature ID   | text          | number        |
| No       |                | primary_lat_dec   | Primary Lat Dec   | number        | number        |
| No       |                | primary_long_dec  | Primary Long Dec  | number        | number        |
```

## Time Field

```ls
Value = month_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = primary_lat_dec,primary_long_dec
```

## Data Commands

```ls
series e:aeyn-twxp d:2000-01-31T00:00:00.000Z t:gnis_feature_id=465190 t:county_name=Adair m:weeks_compensated=406 m:first_payments=70 m:county_fip=19001 m:benefits_paid=93947 m:recipients=153 m:final_payments=3

series e:aeyn-twxp d:2000-01-31T00:00:00.000Z t:gnis_feature_id=465191 t:county_name=Adams m:weeks_compensated=193 m:first_payments=39 m:county_fip=19003 m:benefits_paid=44922 m:recipients=77 m:final_payments=1

series e:aeyn-twxp d:2000-01-31T00:00:00.000Z t:gnis_feature_id=465192 t:county_name=Allamakee m:weeks_compensated=1069 m:first_payments=178 m:county_fip=19005 m:benefits_paid=244534 m:recipients=312 m:final_payments=6
```

## Meta Commands

```ls
metric m:benefits_paid p:integer l:"Benefits Paid" d:"Unemployment benefits paid to individuals residing in the county under the state UI program for the month" t:dataTypeName=money

metric m:weeks_compensated p:integer l:"Weeks Compensated" d:"The number of weeks claimed by recipients residing in county for which UI benefits are paid. Weeks compensated for partial unemployment are included." t:dataTypeName=number

metric m:recipients p:integer l:Recipients d:"The number of claimants residing in the county receiving at least one UI benefit payment during the month. The recipients column cannot be summed over multiple time periods. Summing months into a year will cause a duplicate count since some recipients will be be counted in several months" t:dataTypeName=number

metric m:first_payments p:integer l:"First Payments" d:"The number of claimants residing in the county receiving their the first payment in a benefit year for a week of unemployment claimed under the state UI program." t:dataTypeName=number

metric m:final_payments p:integer l:"Final Payments" d:"Number of claimants residing in the county drawing the final payment of their original entitlement of UI (exhaustees)." t:dataTypeName=number

metric m:county_fip p:integer l:"County FIP" d:"A five-digit Federal Information Processing Series code to ensure uniform identification of counties. Code based on recipients place of residence." t:dataTypeName=number

entity e:aeyn-twxp l:"Unemployment Insurance Recipients and UI Benefit Payments by County (Monthly)" t:attribution="Iowa Workforce Development - Labor Market Information Division" t:url=https://data.iowa.gov/api/views/aeyn-twxp

property e:aeyn-twxp t:meta.view v:id=aeyn-twxp v:category=Economy v:averageRating=0 v:name="Unemployment Insurance Recipients and UI Benefit Payments by County (Monthly)" v:attribution="Iowa Workforce Development - Labor Market Information Division"

property e:aeyn-twxp t:meta.view.license v:name="Public Domain"

property e:aeyn-twxp t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:aeyn-twxp t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| month_ending        | county_name | benefits_paid | weeks_compensated | recipients | first_payments | final_payments | county_fip | gnis_feature_id | primary_lat_dec | primary_long_dec | 
| =================== | =========== | ============= | ================= | ========== | ============== | ============== | ========== | =============== | =============== | ================ | 
| 2000-01-31T00:00:00 | Adair       | 93947         | 406               | 153        | 70             | 3              | 19001      | 465190          | 41.3307464      | -94.4709413      | 
| 2000-01-31T00:00:00 | Adams       | 44922         | 193               | 77         | 39             | 1              | 19003      | 465191          | 41.0289839      | -94.6991849      | 
| 2000-01-31T00:00:00 | Allamakee   | 244534        | 1069              | 312        | 178            | 6              | 19005      | 465192          | 43.2842838      | -91.3780923      | 
| 2000-01-31T00:00:00 | Appanoose   | 155771        | 760               | 274        | 135            | 18             | 19007      | 465193          | 40.7431635      | -92.8686104      | 
| 2000-01-31T00:00:00 | Audubon     | 75825         | 337               | 111        | 54             | 1              | 19009      | 465194          | 41.6845893      | -94.9058222      | 
| 2000-01-31T00:00:00 | Benton      | 228769        | 928               | 301        | 124            | 8              | 19011      | 465195          | 42.0801864      | -92.0656912      | 
| 2000-01-31T00:00:00 | Black Hawk  | 1505287       | 6684              | 3111       | 1443           | 61             | 19013      | 465196          | 42.4700957      | -92.3088197      | 
| 2000-01-31T00:00:00 | Boone       | 133218        | 573               | 201        | 92             | 1              | 19015      | 465197          | 42.0365493      | -93.931671       | 
| 2000-01-31T00:00:00 | Bremer      | 250602        | 1043              | 463        | 203            | 6              | 19017      | 465198          | 42.7745873      | -92.3180548      | 
| 2000-01-31T00:00:00 | Buchanan    | 257533        | 1093              | 410        | 168            | 12             | 19019      | 465199          | 42.4707777      | -91.8378392      | 
```