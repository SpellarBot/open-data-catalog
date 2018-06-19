# Campaign Consultants - Vendor Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-consultants-vendor-payments-066bd) |
| Metadata | [Link](https://data.sfgov.org/api/views/ewuz-v3y2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ewuz-v3y2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ewuz-v3y2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ewuz-v3y2 |
| Name | Campaign Consultants - Vendor Payments |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign consultant, ethics, vendors, sub-vendors, payments |
| Created | 2013-07-19T23:10:46Z |
| Publication Date | 2013-07-22T22:49:57Z |

## Description

Campaign consultants must report economic consideration promised to or received by the filer during the reporting period from vendors and sub-vendors who provide campaign-related goods or services to the filer�۪s current clients.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | consultant             | Consultant             | text          | text          |
| Yes      | series tag     | vendor_sub_vendor_name | Vendor/Sub-vendor Name | text          | text          |
| Yes      | numeric metric | payments_promised      | Payments promised      | money         | money         |
| Yes      | numeric metric | payments_received      | Payments received      | money         | money         |
| Yes      | time           | quarter_start_date     | Quarter Start Date     | calendar_date | calendar_date |
| No       |                | quarter_end_date       | Quarter End Date       | calendar_date | calendar_date |
| No       |                | quarter                | Quarter                | number        | text          |
| No       |                | year                   | Year                   | number        | text          |
```

## Time Field

```ls
Value = quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_end_date,quarter,year
```

## Data Commands

```ls
series e:ewuz-v3y2 d:2016-03-01T00:00:00.000Z t:consultant="Muir Consulting" t:vendor_sub_vendor_name="Spot On" m:payments_promised=3250 m:payments_received=3250

series e:ewuz-v3y2 d:2014-09-01T00:00:00.000Z t:consultant="Lester Connect" t:vendor_sub_vendor_name="Pacific Print Resource" m:payments_promised=630.5 m:payments_received=630.5

series e:ewuz-v3y2 d:2014-09-01T00:00:00.000Z t:consultant="Lester Connect" t:vendor_sub_vendor_name="Lizard Press" m:payments_promised=875 m:payments_received=875
```

## Meta Commands

```ls
metric m:payments_promised p:double l:"Payments promised" t:dataTypeName=money

metric m:payments_received p:double l:"Payments received" t:dataTypeName=money

entity e:ewuz-v3y2 l:"Campaign Consultants - Vendor Payments" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/ewuz-v3y2

property e:ewuz-v3y2 t:meta.view d:2017-09-25T07:25:39.396Z v:averageRating=0 v:name="Campaign Consultants - Vendor Payments" v:attribution="San Francisco Ethics Commission" v:attributionLink=http://www.sfethics.org v:id=ewuz-v3y2 v:category="City Management and Ethics"

property e:ewuz-v3y2 t:meta.view.license d:2017-09-25T07:25:39.396Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ewuz-v3y2 t:meta.view.owner d:2017-09-25T07:25:39.396Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"

property e:ewuz-v3y2 t:meta.view.tableauthor d:2017-09-25T07:25:39.396Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:roleName=publisher v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"
```

## Top Records

```ls
| consultant           | vendor_sub_vendor_name                        | payments_promised | payments_received | quarter_start_date  | quarter_end_date    | quarter | year | 
| ==================== | ============================================= | ================= | ================= | =================== | =================== | ======= | ==== | 
| Muir Consulting      | Spot On                                       | 3250.00           | 3250.00           | 2016-03-01T00:00:00 | 2016-05-31T00:00:00 | 2       | 2016 | 
| Lester Connect       | Pacific Print Resource                        | 630.50            | 630.50            | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Lester Connect       | Lizard Press                                  | 875.00            | 875.00            | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Lester Connect       | Campaign Grid                                 | 9500.00           | 9500.00           | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Tourk, Alex          | Pacific Printing                              | 7671.76           | 7671.76           | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Rodriguez Strategies | Goddard Gunster                               | 0.00              | 48666.12          | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Rodriguez Strategies | Barnes, Mosher, Whitehurst, Lauter & Partners | 0.00              | 13096.97          | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Goddard Gunster Inc. | Amplified Strategies                          | 0.00              | 148032.00         | 2014-09-01T00:00:00 | 2014-11-30T00:00:00 | 4       | 2014 | 
| Goddard Gunster Inc. | Amplified Strategies                          | 61962.00          | 0.00              | 2014-06-01T00:00:00 | 2014-08-31T00:00:00 | 3       | 2014 | 
| Rodriguez Strategies | Goddard Gunster                               | 0.00              | 1693.64           | 2014-06-01T00:00:00 | 2014-08-31T00:00:00 | 3       | 2014 | 
```