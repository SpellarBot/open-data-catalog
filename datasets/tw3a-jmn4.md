# Connecticut Airport Authority Financial Data FY 15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-airport-authority-financial-data-fy-15) |
| Metadata | [Link](https://data.ct.gov/api/views/tw3a-jmn4) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/tw3a-jmn4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/tw3a-jmn4/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | tw3a-jmn4 |
| Name | Connecticut Airport Authority Financial Data FY 15 |
| Attribution | Connecticut Airport Authority |
| Tags | checkbook, vendor payments, transparency, airport authority |
| Created | 2016-06-28T13:55:29Z |
| Publication Date | 2016-06-28T13:58:19Z |

## Description

Checkbook level vendor payment data from the Connecticut Airport Authority for FY 15

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | voucher_number   | Voucher Number   | text          | text          |
| Yes      | series tag     | vendor_id        | Vendor ID        | text          | text          |
| Yes      | series tag     | vendor_name      | Vendor Name      | text          | text          |
| Yes      | time           | g_l_date         | G/L Date         | calendar_date | calendar_date |
| Yes      | series tag     | expense_category | Expense Category | text          | text          |
| Yes      | numeric metric | amount           | Amount           | money         | money         |
```

## Time Field

```ls
Value = g_l_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:tw3a-jmn4 d:2014-07-09T00:00:00.000Z t:expense_category="Office Supplies" t:vendor_id=0000137633 t:vendor_name="A & M BADGING SUPPLIES INC" t:voucher_number=00004035 m:amount=56.95

series e:tw3a-jmn4 d:2014-07-09T00:00:00.000Z t:expense_category="Consultant Services" t:vendor_id=0000024840 t:vendor_name="CP SYSTEMS LLC" t:voucher_number=00004041 m:amount=11962.49

series e:tw3a-jmn4 d:2014-07-09T00:00:00.000Z t:expense_category="Rental motor pool" t:vendor_id=DASS1 t:vendor_name="DEPT OF ADMINISTRATIVE SERVICES" t:voucher_number=00004037 m:amount=1782
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:tw3a-jmn4 l:"Connecticut Airport Authority Financial Data FY 15" t:attribution="Connecticut Airport Authority" t:url=https://data.ct.gov/api/views/tw3a-jmn4

property e:tw3a-jmn4 t:meta.view v:id=tw3a-jmn4 v:attributionLink=http://www.ctairports.org/ v:averageRating=0 v:name="Connecticut Airport Authority Financial Data FY 15" v:attribution="Connecticut Airport Authority"

property e:tw3a-jmn4 t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:tw3a-jmn4 t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| voucher_number | vendor_id  | vendor_name                     | g_l_date            | expense_category       | amount   | 
| ============== | ========== | =============================== | =================== | ====================== | ======== | 
| 00004035       | 0000137633 | A & M BADGING SUPPLIES INC      | 2014-07-09T00:00:00 | Office Supplies        | 56.95    | 
| 00004041       | 0000024840 | CP SYSTEMS LLC                  | 2014-07-09T00:00:00 | Consultant Services    | 11962.49 | 
| 00004037       | DASS1      | DEPT OF ADMINISTRATIVE SERVICES | 2014-07-09T00:00:00 | Rental motor pool      | 1782     | 
| 00004043       | 0000154609 | LAVI INDUSTRIES                 | 2014-07-09T00:00:00 | Office Equip           | 3191.64  | 
| 00004038       | 0000054470 | MAKIARIS MEDIA SERVICES         | 2014-07-09T00:00:00 | Consultant Services    | 2400     | 
| 00004036       | 0000089611 | METROCAST COMMUNICATIONS OF     | 2014-07-09T00:00:00 | Telephone              | 199.95   | 
| 00004042       | 0000010268 | MURPHY SECURITY SERVICE LLC     | 2014-07-09T00:00:00 | Fees, Non-Professional | 22063.53 | 
| 00004046       | 0000013614 | PULLMAN & COMLEY LLC            | 2014-07-09T00:00:00 | Consultant Services    | 10288.82 | 
| 00004044       | 0000034087 | SHERATON BRADLEY INTERNATIONAL  | 2014-07-09T00:00:00 | Food                   | 150      | 
| 00004045       | 0000034087 | SHERATON BRADLEY INTERNATIONAL  | 2014-07-09T00:00:00 | Food                   | 242      | 
```