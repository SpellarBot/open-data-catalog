# Expenditures: Lottery: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-lottery-as-of-june-30-2010-f39ea) |
| Metadata | [Link](https://data.oregon.gov/api/views/n747-smpw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/n747-smpw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/n747-smpw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | n747-smpw |
| Name | Expenditures: Lottery: As of June 30, 2010 |
| Category | Revenue & Expense |
| Created | 2011-02-09T23:35:35Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | agency           | Agency           | text      | text        |
| Yes      | series tag     | account_category | Account Category | text      | text        |
| Yes      | series tag     | state            | State            | text      | text        |
| Yes      | series tag     | vendor_name      | Vendor Name      | text      | text        |
| Yes      | numeric metric | payment          | Payment          | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n747-smpw d:2010-01-01T00:00:00.000Z t:account_category="8430-Other Services and Supplies" t:state=NY t:agency="177-OREGON STATE LOTTERY" t:vendor_name="123 SECURITY PRODUCTS" m:payment=3028

series e:n747-smpw d:2010-01-01T00:00:00.000Z t:account_category="8445-Non-Capitalized Assets" t:state=NY t:agency="177-OREGON STATE LOTTERY" t:vendor_name="123 SECURITY PRODUCTS" m:payment=1006

series e:n747-smpw d:2010-01-01T00:00:00.000Z t:account_category="7820-Technology Supplies" t:state=NJ t:agency="177-OREGON STATE LOTTERY" t:vendor_name="3R1 TECHNOLOGIES LLC" m:payment=150
```

## Meta Commands

```ls
metric m:payment p:double l:Payment t:dataTypeName=money

entity e:n747-smpw l:"Expenditures: Lottery: As of June 30, 2010" t:url=https://data.oregon.gov/api/views/n747-smpw

property e:n747-smpw t:meta.view v:id=n747-smpw v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: Lottery: As of June 30, 2010"

property e:n747-smpw t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:n747-smpw t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency                   | account_category                    | state | vendor_name                              | payment            | 
| ======================== | =================================== | ===== | ======================================== | ================== | 
| 177-OREGON STATE LOTTERY | 8430-Other Services and Supplies    | NY    | 123 SECURITY PRODUCTS                    | 3028               | 
| 177-OREGON STATE LOTTERY | 8445-Non-Capitalized Assets         | NY    | 123 SECURITY PRODUCTS                    | 1006               | 
| 177-OREGON STATE LOTTERY | 7820-Technology Supplies            | NJ    | 3R1 TECHNOLOGIES LLC                     | 150                | 
| 177-OREGON STATE LOTTERY | 7810-Technology Equipment           | CO    | 42U DIRECTNET                            | 2897               | 
| 177-OREGON STATE LOTTERY | 1170-Prepaid Expenses               | OR    | A STORAGE PLACE OF KEIZER                | 2280               | 
| 177-OREGON STATE LOTTERY | 8460-Research                       | OR    | #267569 CARLY'S                          | 100                | 
| 177-OREGON STATE LOTTERY | 1170-Prepaid Expenses               | OR    | A-1 MINI STORAGE                         | 792                | 
| 177-OREGON STATE LOTTERY | 1170-Prepaid Expenses               | OR    | A-1 MINI STORAGE / GRANTS PASS           | 3840               | 
| 177-OREGON STATE LOTTERY | 8330-Building Maintenance - Grounds | OR    | A-1 STRAIGHT LINE STRIPING COMPANY, INC. | 900                | 
| 177-OREGON STATE LOTTERY | 8320-Janitorial - Services          | OR    | ABM JANITORIAL NORTHWEST                 | 80046.679999999993 | 
```