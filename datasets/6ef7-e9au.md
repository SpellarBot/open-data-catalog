# Purchasing Card Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/purchasing-card-expenditures-b291a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6ef7-e9au) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6ef7-e9au/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6ef7-e9au/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6ef7-e9au |
| Name | Purchasing Card Expenditures |
| Category | Government-Wide Support |
| Created | 2014-02-02T03:37:10Z |
| Publication Date | 2014-02-02T04:41:33Z |

## Description

uploaded 2013.01.23

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | transaction_no   | Transaction_No   | text          | text          |
| Yes      | time           | transaction_date | Transaction_Date | calendar_date | calendar_date |
| No       |                | post_date        | Post_Date        | calendar_date | calendar_date |
| Yes      | series tag     | department       | Department       | text          | text          |
| Yes      | numeric metric | amount           | Amount           | money         | money         |
| Yes      | series tag     | vendor_name      | Vendor_Name      | text          | text          |
| Yes      | series tag     | category         | Category         | text          | text          |
| Yes      | series tag     | fund             | Fund             | text          | text          |
| No       |                | fy               | FY               | number        | text          |
| Yes      | numeric metric | appr             | Appr             | number        | text          |
| Yes      | series tag     | cost_center      | Cost_Center      | text          | text          |
```

## Time Field

```ls
Value = transaction_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = post_date,fy
```

## Data Commands

```ls
series e:6ef7-e9au d:2013-10-01T00:00:00.000Z t:cost_center=3 t:category="TRANSPORTATION, INTRA-STATE" t:department=AGRICULTURE t:fund=S t:transaction_no=212951613 t:vendor_name=MOKULELE m:amount=145.5 m:appr=307

series e:6ef7-e9au d:2013-10-01T00:00:00.000Z t:cost_center=90 t:category="TELEPHONE AND TELEGRAPH" t:department=AGRICULTURE t:fund=S t:transaction_no=212951614 t:vendor_name="VZWRLSS IVR VB" m:amount=61.77 m:appr=302

series e:6ef7-e9au d:2013-09-30T00:00:00.000Z t:cost_center=1 t:category="OFFICE SUPPLIES" t:department="BUSINESS, ECONOMIC DEVELOPMENT," t:fund=G t:transaction_no=212951652 t:vendor_name="HAWAII STATIONERY" m:amount=30.84 m:appr=144
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:appr p:integer l:Appr t:dataTypeName=number

entity e:6ef7-e9au l:"Purchasing Card Expenditures" t:url=https://data.hawaii.gov/api/views/6ef7-e9au

property e:6ef7-e9au t:meta.view v:id=6ef7-e9au v:category="Government-Wide Support" v:averageRating=0 v:name="Purchasing Card Expenditures"

property e:6ef7-e9au t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:6ef7-e9au t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| transaction_no | transaction_date    | post_date           | department                      | amount | vendor_name            | category                        | fund | fy   | appr | cost_center | 
| ============== | =================== | =================== | =============================== | ====== | ====================== | =============================== | ==== | ==== | ==== | =========== | 
| 212951613      | 2013-10-01T00:00:00 | 2013-10-01T00:00:00 | AGRICULTURE                     | 145.5  | MOKULELE               | TRANSPORTATION, INTRA-STATE     | S    | 2014 | 307  | 3           | 
| 212951614      | 2013-10-01T00:00:00 | 2013-10-01T00:00:00 | AGRICULTURE                     | 61.77  | VZWRLSS IVR VB         | TELEPHONE AND TELEGRAPH         | S    | 2014 | 302  | 90          | 
| 212951652      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | BUSINESS, ECONOMIC DEVELOPMENT, | 30.84  | HAWAII STATIONERY      | OFFICE SUPPLIES                 | G    | 2014 | 144  | 1           | 
| 212951681      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | 333.26 | ALLIED MACHINERY-MAIN  | REPAIR AND MAINTENANCE SUPPLIES | S    | 2014 | 60   | 2185        | 
| 212951682      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | 26.42  | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951683      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | 51.84  | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951684      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | 14.49  | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951685      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | 51.84  | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951696      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | DEFENSE                         | 31.34  | HAWAIIAN EARTH PRODUCT | OTHER UTILITIES                 | S    | 2014 | 217  | ROMA        | 
| 212951696      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | DEFENSE                         | 86.43  | HAWAIIAN EARTH PRODUCT | OTHER UTILITIES                 | S    | 2014 | 217  | ROMA        | 
```