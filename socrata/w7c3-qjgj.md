# Housing and Economic Development Payment Receipts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-and-economic-development-payment-receipts-67977) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/w7c3-qjgj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/w7c3-qjgj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/w7c3-qjgj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | w7c3-qjgj |
| Name | Housing and Economic Development Payment Receipts |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | invoices |
| Created | 2013-01-08T04:39:30Z |
| Publication Date | 2016-01-29T17:15:31Z |

## Description

Pro forma invoices with required receipt numbers for submission to Department of Housing and Economic Development.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | invoice               | INVOICE               | text          | text          |
| Yes      | series tag     | vendor_number         | VENDOR NUMBER         | text          | text          |
| Yes      | series tag     | vendor_name           | VENDOR NAME           | text          | text          |
| Yes      | series tag     | purchase_order_number | PURCHASE ORDER NUMBER | text          | text          |
| Yes      | series tag     | release_number        | RELEASE NUMBER        | text          | number        |
| Yes      | series tag     | receipt_number        | RECEIPT NUMBER        | text          | number        |
| Yes      | time           | receipt_date          | RECEIPT DATE          | calendar_date | calendar_date |
| Yes      | numeric metric | receipt_line_amount   | RECEIPT LINE AMOUNT   | money         | money         |
```

## Time Field

```ls
Value = receipt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:w7c3-qjgj d:2016-11-09T00:00:00.000Z t:vendor_number=1063960 t:release_number=8 t:purchase_order_number=26684 t:invoice="SEAN WIEDEL" t:receipt_number=695230 t:vendor_name="WRD ENVIRONMENTAL" m:receipt_line_amount=1097.09

series e:w7c3-qjgj d:2016-11-09T00:00:00.000Z t:vendor_number=1063960 t:release_number=28 t:purchase_order_number=26684 t:invoice="SEAN WIEDEL" t:receipt_number=695232 t:vendor_name="WRD ENVIRONMENTAL" m:receipt_line_amount=24960.79

series e:w7c3-qjgj d:2016-11-09T00:00:00.000Z t:vendor_number=1063960 t:release_number=25 t:purchase_order_number=26684 t:invoice="SEAN WIEDEL" t:receipt_number=695233 t:vendor_name="WRD ENVIRONMENTAL" m:receipt_line_amount=23464.65
```

## Meta Commands

```ls
metric m:receipt_line_amount p:double l:"RECEIPT LINE AMOUNT" t:dataTypeName=money

entity e:w7c3-qjgj l:"Housing and Economic Development Payment Receipts" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/w7c3-qjgj

property e:w7c3-qjgj t:meta.view v:id=w7c3-qjgj v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Housing and Economic Development Payment Receipts" v:attribution="City of Chicago"

property e:w7c3-qjgj t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:w7c3-qjgj t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| invoice         | vendor_number | vendor_name             | purchase_order_number | release_number | receipt_number | receipt_date        | receipt_line_amount | 
| =============== | ============= | ======================= | ===================== | ============== | ============== | =================== | =================== | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 8              | 695230         | 2016-11-09T00:00:00 | 1097.09             | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 28             | 695232         | 2016-11-09T00:00:00 | 24960.79            | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 25             | 695233         | 2016-11-09T00:00:00 | 23464.65            | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 17             | 695229         | 2016-11-09T00:00:00 | 1932.18             | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 25             | 700048         | 2016-12-09T00:00:00 | 4900.21             | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 28             | 700047         | 2016-12-09T00:00:00 | 6685.37             | 
| Moira Coughling | 1040749       | PATRICK ENGINEERING INC | 30531                 | 1              | 704946         | 2017-01-10T00:00:00 | 4722.36             | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 25             | 705426         | 2017-01-11T00:00:00 | 3269.01             | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 28             | 705428         | 2017-01-11T00:00:00 | 4383.1              | 
| SEAN WIEDEL     | 1063960       | WRD ENVIRONMENTAL       | 26684                 | 8              | 706955         | 2017-01-19T00:00:00 | 844.43              | 
```