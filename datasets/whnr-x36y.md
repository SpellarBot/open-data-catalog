# Expenditures: OUS: Southern Oregon University: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-ous-southern-oregon-university-fy-2014-f77ac) |
| Metadata | [Link](https://data.oregon.gov/api/views/whnr-x36y) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/whnr-x36y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/whnr-x36y/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | whnr-x36y |
| Name | Expenditures: OUS: Southern Oregon University: FY 2014 |
| Category | Revenue & Expense |
| Tags | sou expenditures, southern oregon university expenditures, ous expenditures 2014, 2014 |
| Created | 2014-12-27T02:08:59Z |
| Publication Date | 2014-12-29T03:09:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | ous_division           | OUS Division           | text      | text        |
| Yes      | series tag     | account_category       | Account Category       | text      | text        |
| No       |                | vendor_address         | Vendor Address         | text      | text        |
| Yes      | series tag     | vendor_city            | Vendor City            | text      | text        |
| Yes      | series tag     | vendor_state           | Vendor State           | text      | text        |
| Yes      | series tag     | vendor_zip_postal_code | Vendor Zip/Postal Code | text      | number      |
| Yes      | series tag     | vendor_name            | Vendor Name            | text      | text        |
| Yes      | numeric metric | amount                 | Amount                 | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:whnr-x36y d:2014-01-01T00:00:00.000Z t:vendor_city="GRANTS PASS" t:vendor_state=OR t:account_category="Accounting Service" t:vendor_name="Rogue Community College" t:ous_division="Southern Oregon University" m:amount=9175.25

series e:whnr-x36y d:2014-01-01T00:00:00.000Z t:vendor_city=PASADENA t:vendor_state=CA t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_name="Mail Tribune Co" t:ous_division="Southern Oregon University" m:amount=13616.19

series e:whnr-x36y d:2014-01-01T00:00:00.000Z t:vendor_city=ASHLAND t:vendor_state=OR t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_zip_postal_code=97520 t:vendor_name="Ashland Chamber of Commerce" t:ous_division="Southern Oregon University" m:amount=13125
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:whnr-x36y l:"Expenditures: OUS: Southern Oregon University: FY 2014" t:url=https://data.oregon.gov/api/views/whnr-x36y

property e:whnr-x36y t:meta.view v:id=whnr-x36y v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: OUS: Southern Oregon University: FY 2014"

property e:whnr-x36y t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:whnr-x36y t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| ous_division               | account_category               | vendor_address           | vendor_city | vendor_state | vendor_zip_postal_code | vendor_name                         | amount   | 
| ========================== | ============================== | ======================== | =========== | ============ | ====================== | =================================== | ======== | 
| Southern Oregon University | Accounting Service             | ATTN ACCOUNTS PAYABLE    | GRANTS PASS | OR           |                        | Rogue Community College             | 9175.25  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | ACCTS RECEIVABLE         | PASADENA    | CA           |                        | Mail Tribune Co                     | 13616.19 | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | PO BOX 1360              | ASHLAND     | OR           | 97520                  | Ashland Chamber of Commerce         | 13125.00 | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | PO BOX 158               | ASHLAND     | OR           | 97520                  | Oregon Shakespeare Festival         | 8870.00  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | 230 W MONROE ST STE 1200 | CHICAGO     | IL           | 60606                  | Cappex.com LLC                      | 8500.00  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | C/O SOU                  | ASHLAND     | OR           | 97520                  | JPR Foundation Inc                  | 5585.35  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | HERALD AND NEWS          | POCATELLO   | ID           | 83204                  | Klamath Publishing LLC              | 2000.40  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | PO BOX 22109             | PORTLAND    | OR           |                        | OR Pub Corp DBA Community Newspaper | 1125.00  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | 5443 FREMONTIA LANE      | SAN DIEGO   | CA           | 92115                  | Jobelephant.com Inc                 | 1090.00  | 
| Southern Oregon University | Advertising-Inst Promo/Pub Rel | PO BOX 1108              | MEDFORD     | OR           |                        | Mail Tribune Co                     | 1074.28  | 
```