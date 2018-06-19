# State of Maryland Payments Data: FY2008 to FY2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-maryland-payments-data-fy2008-to-fy2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/gja3-vy5r) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/gja3-vy5r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/gja3-vy5r/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | gja3-vy5r |
| Name | State of Maryland Payments Data: FY2008 to FY2016 |
| Attribution | Department of Budget and Management (DBM) |
| Category | Budget |
| Tags | budget, spending, fiscal, vendors, payments, department of budget and management, dbm, tax |
| Created | 2016-01-13T19:29:29Z |
| Publication Date | 2017-02-21T15:22:00Z |

## Description

This dataset shows all payments made by state agencies from Fiscal Years 2008 to 2016 which were $25,000 or more. All parties receiving funds are shown: private businesses, local governments, non-profit organizations, and individuals. If you have any questions please contact service.desk@maryland.gov.
This dataset combines multiple data sources from the Department of Budget and Management to show spending across multiple years. Source data can be found at spending.dbm.maryland.gov. This same data is mirrored in pre-existing datasets on data.maryland.gov, one for each fiscal year.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | time           | fiscal_year | Fiscal Year | calendar_date | calendar_date |
| Yes      | series tag     | agency_name | Agency Name | text          | text          |
| Yes      | series tag     | vendor_name | Vendor Name | text          | text          |
| Yes      | series tag     | vendor_zip  | Vendor Zip  | text          | text          |
| Yes      | numeric metric | amount      | Amount      | money         | money         |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gja3-vy5r d:2008-01-01T00:00:00.000Z t:vendor_zip=21273 t:agency_name="AID TO UNIVERSITY OF MD MEDICAL SYSTEM" t:vendor_name="U M M S" m:amount=9701191

series e:gja3-vy5r d:2008-01-01T00:00:00.000Z t:vendor_zip=10001 t:agency_name="BALTIMORE CITY COMMUNITY COLLEGE" t:vendor_name="B & H PHOTO VIDEO PRO AUDIO" m:amount=10437.75

series e:gja3-vy5r d:2008-01-01T00:00:00.000Z t:vendor_zip=10087 t:agency_name="BALTIMORE CITY COMMUNITY COLLEGE" t:vendor_name="COLLEGE BOARD" m:amount=18600
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:gja3-vy5r l:"State of Maryland Payments Data: FY2008 to FY2016" t:attribution="Department of Budget and Management (DBM)" t:url=https://data.maryland.gov/api/views/gja3-vy5r

property e:gja3-vy5r t:meta.view v:id=gja3-vy5r v:category=Budget v:attributionLink=http://spending.dbm.maryland.gov v:averageRating=0 v:name="State of Maryland Payments Data: FY2008 to FY2016" v:attribution="Department of Budget and Management (DBM)"

property e:gja3-vy5r t:meta.view.license v:name="Public Domain"

property e:gja3-vy5r t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:gja3-vy5r t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| fiscal_year         | agency_name                            | vendor_name                 | vendor_zip | amount     | 
| =================== | ====================================== | =========================== | ========== | ========== | 
| 2008-01-01T00:00:00 | AID TO UNIVERSITY OF MD MEDICAL SYSTEM | U M M S                     | 21273      | 9701191.00 | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | B & H PHOTO VIDEO PRO AUDIO | 10001      | 10437.75   | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | COLLEGE BOARD               | 10087      | 18600.00   | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | SCREENVISION DIRECT         | 14692      | 10242.00   | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | HENRY SCHEIN INC            | 15250      | 2363.12    | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | 3M PHJ3884                  | 15250      | 6212.00    | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | VERIZON BUSINESS            | 15250      | 23226.96   | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | FEDEX                       | 15250      | 128.34     | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | CONEDISON SOLUTIONS         | 15251      | 24876.41   | 
| 2008-01-01T00:00:00 | BALTIMORE CITY COMMUNITY COLLEGE       | SHARP ELECTRONICS CORP      | 15264      | 25165.69   | 
```