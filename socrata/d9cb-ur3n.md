# MDAg - Financial Investments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdag-financial-investments) |
| Metadata | [Link](https://data.maryland.gov/api/views/d9cb-ur3n) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/d9cb-ur3n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/d9cb-ur3n/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | d9cb-ur3n |
| Name | MDAg - Financial Investments |
| Attribution | MDA |
| Category | Agriculture |
| Created | 2015-05-08T19:13:24Z |
| Publication Date | 2016-01-12T13:26:05Z |

## Description

State cost-share agreements, including federal partners, for structural BMP implementation from 1984-2015 (May) in support of Maryland's Watershed Implementation Plan (WIP) goals for the Chesapeake Bay.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | date_paid                  | Date Paid                  | calendar_date | calendar_date |
| Yes      | series tag     | county                     | County                     | text          | text          |
| Yes      | series tag     | watershed_no               | Watershed No.              | text          | text          |
| Yes      | series tag     | watershed_name             | Watershed Name             | text          | text          |
| Yes      | numeric metric | total_project_claim_amount | Total Project Claim Amount | number        | number        |
| Yes      | numeric metric | state_macs_payment         | State MACS Payment         | number        | number        |
| Yes      | numeric metric | federal_co_payment         | Federal Co-payment         | number        | number        |
| Yes      | numeric metric | farmer_amount              | Farmer Amount              | number        | number        |
```

## Time Field

```ls
Value = date_paid
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:d9cb-ur3n d:1986-09-29T00:00:00.000Z t:watershed_name="Wye River" t:county=Talbot t:watershed_no=02-13-05-03 m:farmer_amount=390 m:federal_co_payment=0 m:total_project_claim_amount=780 m:state_macs_payment=390

series e:d9cb-ur3n d:1983-10-12T00:00:00.000Z t:watershed_name="Sassafras River" t:county=Kent t:watershed_no=02-13-06-10 m:farmer_amount=7680 m:federal_co_payment=0 m:total_project_claim_amount=12680 m:state_macs_payment=5000

series e:d9cb-ur3n d:1983-10-13T00:00:00.000Z t:watershed_name="Youghiogheny River" t:county=Garrett t:watershed_no=05-02-02-01 m:farmer_amount=5699.35 m:federal_co_payment=3500 m:total_project_claim_amount=14199.35 m:state_macs_payment=5000
```

## Meta Commands

```ls
metric m:total_project_claim_amount p:double l:"Total Project Claim Amount" t:dataTypeName=number

metric m:state_macs_payment p:float l:"State MACS Payment" t:dataTypeName=number

metric m:federal_co_payment p:float l:"Federal Co-payment" t:dataTypeName=number

metric m:farmer_amount p:double l:"Farmer Amount" t:dataTypeName=number

entity e:d9cb-ur3n l:"MDAg - Financial Investments" t:attribution=MDA t:url=https://data.maryland.gov/api/views/d9cb-ur3n

property e:d9cb-ur3n t:meta.view v:id=d9cb-ur3n v:category=Agriculture v:averageRating=0 v:name="MDAg - Financial Investments" v:attribution=MDA

property e:d9cb-ur3n t:meta.view.license v:name="Public Domain"

property e:d9cb-ur3n t:meta.view.owner v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:displayName="Alisha Mulkey"

property e:d9cb-ur3n t:meta.view.tableauthor v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:roleName=editor v:displayName="Alisha Mulkey"
```

## Top Records

```ls
| date_paid           | county    | watershed_no | watershed_name       | total_project_claim_amount | state_macs_payment | federal_co_payment | farmer_amount | 
| =================== | ========= | ============ | ==================== | ========================== | ================== | ================== | ============= | 
| 1986-09-29T00:00:00 | Talbot    | 02-13-05-03  | Wye River            | 780.00                     | 390.00             | 0.00               | 390.00        | 
| 1983-10-12T00:00:00 | Kent      | 02-13-06-10  | Sassafras River      | 12680.00                   | 5000.00            | 0.00               | 7680.00       | 
| 1983-10-13T00:00:00 | Garrett   | 05-02-02-01  | Youghiogheny River   | 14199.35                   | 5000.00            | 3500.00            | 5699.35       | 
| 1983-10-25T00:00:00 | Kent      | 02-13-06-10  | Sassafras River      | 600.00                     | 525.00             | 0.00               | 75.00         | 
| 1983-10-25T00:00:00 | Kent      | 02-13-06-10  | Sassafras River      | 3836.25                    | 3356.72            | 0.00               | 479.53        | 
| 1983-10-25T00:00:00 | Kent      | 02-13-06-10  | Sassafras River      | 4902.92                    | 4290.05            | 0.00               | 612.87        | 
| 1983-10-25T00:00:00 | Kent      | 02-13-06-10  | Sassafras River      | 5261.25                    | 6407.18            | 0.00               | 657.66        | 
| 1983-10-26T00:00:00 | Kent      | 02-13-06-11  | Stillpond-Fairlee    | 5685.00                    | 4974.38            | 0.00               | 710.62        | 
| 1983-10-28T00:00:00 | Baltimore | 02-13-08-05  | Loch Raven Reservoir | 972.18                     | 850.65             | 0.00               | 121.53        | 
| 1983-10-28T00:00:00 | Kent      | 02-13-06-11  | Stillpond-Fairlee    | 2301.21                    | 2013.56            | 0.00               | 287.65        | 
```