# PC TSSB WKLY

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pc-tssb-wkly-14b09) |
| Metadata | [Link](https://data.hawaii.gov/api/views/4rpu-rhfz) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/4rpu-rhfz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/4rpu-rhfz/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 4rpu-rhfz |
| Name | PC TSSB WKLY |
| Created | 2014-01-24T00:15:54Z |
| Publication Date | 2014-01-24T00:21:50Z |

## Description

ICSD

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | transaction_no    | Transaction_No    | text          | text          |
| Yes      | time           | transaction_date  | Transaction_Date  | calendar_date | calendar_date |
| No       |                | post_date         | Post_Date         | calendar_date | calendar_date |
| Yes      | series tag     | department        | Department        | text          | text          |
| Yes      | series tag     | settlement_sign   | Settlement_Sign   | text          | text          |
| Yes      | numeric metric | settlement_amount | Settlement_Amount | number        | number        |
| Yes      | series tag     | vendor_name       | Vendor_Name       | text          | text          |
| Yes      | series tag     | category          | Category          | text          | text          |
| Yes      | series tag     | fund              | Fund              | text          | text          |
| No       |                | fy                | FY                | number        | text          |
| Yes      | numeric metric | appr              | Appr              | number        | number        |
| Yes      | series tag     | cost_center       | Cost_Center       | text          | number        |
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
series e:4rpu-rhfz d:2013-10-01T00:00:00.000Z t:cost_center=3 t:category="TRANSPORTATION, INTRA-STATE" t:department=AGRICULTURE t:fund=S t:transaction_no=212951613 t:settlement_sign=+ t:vendor_name=MOKULELE m:appr=307 m:settlement_amount=145.5

series e:4rpu-rhfz d:2013-10-01T00:00:00.000Z t:cost_center=90 t:category="TELEPHONE AND TELEGRAPH" t:department=AGRICULTURE t:fund=S t:transaction_no=212951614 t:settlement_sign=+ t:vendor_name="VZWRLSS IVR VB" m:appr=302 m:settlement_amount=61.77

series e:4rpu-rhfz d:2013-09-30T00:00:00.000Z t:cost_center=1 t:category="OFFICE SUPPLIES" t:department="BUSINESS, ECONOMIC DEVELOPMENT," t:fund=G t:transaction_no=212951652 t:settlement_sign=+ t:vendor_name="HAWAII STATIONERY" m:appr=144 m:settlement_amount=30.84
```

## Meta Commands

```ls
metric m:settlement_amount p:float l:Settlement_Amount t:dataTypeName=number

metric m:appr p:integer l:Appr t:dataTypeName=number

entity e:4rpu-rhfz l:"PC TSSB WKLY" t:url=https://data.hawaii.gov/api/views/4rpu-rhfz

property e:4rpu-rhfz t:meta.view v:id=4rpu-rhfz v:averageRating=0 v:name="PC TSSB WKLY"

property e:4rpu-rhfz t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:4rpu-rhfz t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| transaction_no | transaction_date    | post_date           | department                      | settlement_sign | settlement_amount | vendor_name            | category                        | fund | fy   | appr | cost_center | 
| ============== | =================== | =================== | =============================== | =============== | ================= | ====================== | =============================== | ==== | ==== | ==== | =========== | 
| 212951613      | 2013-10-01T00:00:00 | 2013-10-01T00:00:00 | AGRICULTURE                     | +               | 145.5             | MOKULELE               | TRANSPORTATION, INTRA-STATE     | S    | 2014 | 307  | 3           | 
| 212951614      | 2013-10-01T00:00:00 | 2013-10-01T00:00:00 | AGRICULTURE                     | +               | 61.77             | VZWRLSS IVR VB         | TELEPHONE AND TELEGRAPH         | S    | 2014 | 302  | 90          | 
| 212951652      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | BUSINESS, ECONOMIC DEVELOPMENT, | +               | 30.84             | HAWAII STATIONERY      | OFFICE SUPPLIES                 | G    | 2014 | 144  | 1           | 
| 212951681      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | +               | 333.26            | ALLIED MACHINERY-MAIN  | REPAIR AND MAINTENANCE SUPPLIES | S    | 2014 | 60   | 2185        | 
| 212951682      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | +               | 26.42             | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951683      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | +               | 51.84             | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951684      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | +               | 14.49             | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951685      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | TRANSPORTATION                  | +               | 51.84             | HITELCOM IVR PMT       | TELEPHONE AND TELEGRAPH         | S    | 2014 | 60   | 2185        | 
| 212951696      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | DEFENSE                         | +               | 31.34             | HAWAIIAN EARTH PRODUCT | OTHER UTILITIES                 | S    | 2014 | 217  |             | 
| 212951696      | 2013-09-30T00:00:00 | 2013-10-01T00:00:00 | DEFENSE                         | +               | 86.43             | HAWAIIAN EARTH PRODUCT | OTHER UTILITIES                 | S    | 2014 | 217  |             | 
```