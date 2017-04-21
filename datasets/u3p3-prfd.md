# Vendor Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vendor-payments-11e95) |
| Metadata | [Link](https://data.illinois.gov/api/views/u3p3-prfd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u3p3-prfd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u3p3-prfd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u3p3-prfd |
| Name | Vendor Payments |
| Category | Municipality |
| Created | 2013-03-13T22:49:40Z |
| Publication Date | 2013-03-13T23:12:37Z |

## Description

City of Rockford Vendor Payments 2013

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | series tag     | check_no   | CHECK NO | text          | number        |
| Yes      | time           | chk_date   | CHK DATE | calendar_date | calendar_date |
| Yes      | numeric metric | vendor     | VENDOR   | number        | number        |
| Yes      | series tag     | name       | NAME     | text          | text          |
| Yes      | series tag     | invoice    | INVOICE  | text          | text          |
| No       |                | inv_date   | INV DATE | calendar_date | calendar_date |
| No       |                | po         | PO       | number        | number        |
| Yes      | series tag     | warrant    | WARRANT  | text          | text          |
| Yes      | numeric metric | amount     | AMOUNT   | number        | number        |
| Yes      | numeric metric | org        | ORG      | number        | number        |
| Yes      | numeric metric | object     | OBJECT   | number        | number        |
| Yes      | series tag     | project    | PROJECT  | text          | text          |
| Yes      | series tag     | desc       | DESC     | text          | text          |
```

## Time Field

```ls
Value = chk_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = inv_date,po
```

## Data Commands

```ls
series e:u3p3-prfd d:2013-01-04T00:00:00.000Z t:warrant=M130104A t:desc="PHARMACY SCRIPT-SAVE" t:invoice=10673121A t:name="MEDCO HEALTH SOLUTIONS INC" t:check_no=200181 m:amount=1028.78 m:vendor=708574 m:object=72234 m:org=35306880

series e:u3p3-prfd d:2013-01-04T00:00:00.000Z t:warrant=M130104A t:desc="PHARMACY SCRIPT-SAVE" t:invoice=17711261C t:name="MEDCO HEALTH SOLUTIONS INC" t:check_no=200181 m:amount=93086.2 m:vendor=708574 m:object=72234 m:org=35306880

series e:u3p3-prfd d:2013-01-10T00:00:00.000Z t:warrant=M130110B t:desc="PHARMACY SCRIPT-SAVE" t:invoice=17780661C t:name="MEDCO HEALTH SOLUTIONS INC" t:check_no=200182 m:amount=85692.84 m:vendor=708574 m:object=72234 m:org=35306880
```

## Meta Commands

```ls
metric m:vendor p:integer l:VENDOR t:dataTypeName=number

metric m:amount p:double l:AMOUNT t:dataTypeName=number

metric m:org p:integer l:ORG t:dataTypeName=number

metric m:object p:integer l:OBJECT t:dataTypeName=number

entity e:u3p3-prfd l:"Vendor Payments" t:url=https://data.illinois.gov/api/views/u3p3-prfd

property e:u3p3-prfd t:meta.view v:id=u3p3-prfd v:category=Municipality v:averageRating=0 v:name="Vendor Payments"

property e:u3p3-prfd t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:u3p3-prfd t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| check_no | chk_date            | vendor | name                                | invoice             | inv_date            | po | warrant  | amount    | org      | object | project | desc                 | 
| ======== | =================== | ====== | =================================== | =================== | =================== | == | ======== | ========= | ======== | ====== | ======= | ==================== | 
| 200181   | 2013-01-04T00:00:00 | 708574 | MEDCO HEALTH SOLUTIONS INC          | 10673121A           | 2012-12-25T00:00:00 |    | M130104A | 1028.78   | 35306880 | 72234  |         | PHARMACY SCRIPT-SAVE | 
| 200181   | 2013-01-04T00:00:00 | 708574 | MEDCO HEALTH SOLUTIONS INC          | 17711261C           | 2012-12-25T00:00:00 |    | M130104A | 93086.20  | 35306880 | 72234  |         | PHARMACY SCRIPT-SAVE | 
| 200182   | 2013-01-10T00:00:00 | 708574 | MEDCO HEALTH SOLUTIONS INC          | 17780661C           | 2013-01-08T00:00:00 |    | M130110B | 85692.84  | 35306880 | 72234  |         | PHARMACY SCRIPT-SAVE | 
| 200183   | 2013-01-10T00:00:00 | 702859 | ROCKFORD MUNICIPAL EMPLOYEES CREDIT | 01-11-13            | 2013-01-11T00:00:00 |    | M130110D | 217336.00 | 10101060 | 22251  |         | CREDIT UNION         | 
| 200184   | 2013-01-10T00:00:00 | 706024 | ROCKFORD FIRE FIGHTERS              | 01-11-13            | 2013-01-11T00:00:00 |    | M130110D | 1622.40   | 10101060 | 22243  |         | FIRE UNION DUES      | 
| 200185   | 2013-01-10T00:00:00 | 707878 | PNC BANK                            | PCARD-JAN2013-CITY  | 2013-01-04T00:00:00 |    | M130110E | 110438.49 | 10101030 | 10053  |         | PNC BANK - PCARD     | 
| 200185   | 2013-01-10T00:00:00 | 707878 | PNC BANK                            | PCARD-JAN2013-RMAP  | 2013-01-04T00:00:00 |    | M130110E | 1573.07   | 10101030 | 10053  |         | PNC BANK - PCARD     | 
| 200185   | 2013-01-10T00:00:00 | 707878 | PNC BANK                            | PCARD-JAN2013-WATER | 2013-01-04T00:00:00 |    | M130110E | 5026.43   | 10101030 | 10053  |         | PNC BANK - PCARD     | 
| 200186   | 2013-01-16T00:00:00 | 707878 | PNC BANK                            | VISA0652-130110     | 2013-01-10T00:00:00 |    | M130116B | 6047.06   | 10101060 | 22976  |         | CREDIT CARD PAYABLE  | 
| 200186   | 2013-01-16T00:00:00 | 707878 | PNC BANK                            | VISA0652-130110     | 2013-01-10T00:00:00 |    | M130116B | 57527.48  | 11101060 | 22976  |         | CREDIT CARD PAYABLE  | 
```