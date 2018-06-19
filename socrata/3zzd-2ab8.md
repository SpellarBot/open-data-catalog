# Expenditures OUS: Oregon State University: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-ous-oregon-state-university-fy-2014-06384) |
| Metadata | [Link](https://data.oregon.gov/api/views/3zzd-2ab8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3zzd-2ab8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3zzd-2ab8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3zzd-2ab8 |
| Name | Expenditures OUS: Oregon State University: FY 2014 |
| Category | Revenue & Expense |
| Tags | ous expenditures, osu expenditures, oregon state university expenditures 2014, 2014 |
| Created | 2014-12-27T01:23:32Z |
| Publication Date | 2014-12-29T03:06:32Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | ous_division           | OUS Division           | text      | text        |
| Yes      | series tag     | account_category       | Account Category       | text      | text        |
| No       |                | vendor_address         | Vendor Address         | text      | text        |
| Yes      | series tag     | vendor_city            | Vendor City            | text      | text        |
| Yes      | series tag     | vendor_state           | Vendor State           | text      | text        |
| Yes      | series tag     | vendor_zip_postal_code | Vendor Zip/Postal Code | text      | text        |
| Yes      | series tag     | vendor_name            | Vendor Name            | text      | text        |
| Yes      | numeric metric | amount                 | Amount                 | number    | number      |
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
series e:3zzd-2ab8 d:2014-01-01T00:00:00.000Z t:vendor_city=Waterloo t:vendor_state=IA t:account_category="Accounting Service" t:vendor_zip_postal_code=50701-4017 t:vendor_name="Shorts Travel Management" t:ous_division="Oregon State University" m:amount=5687.5

series e:3zzd-2ab8 d:2014-01-01T00:00:00.000Z t:vendor_city="Oregon City" t:vendor_state=OR t:account_category="Accounting Service" t:vendor_zip_postal_code=97045-4035 t:vendor_name="Clackamas County" t:ous_division="Oregon State University" m:amount=3000

series e:3zzd-2ab8 d:2014-01-01T00:00:00.000Z t:vendor_city=Corvallis t:vendor_state=OR t:account_category="Accounting Service" t:vendor_zip_postal_code=97339-1832 t:vendor_name="Anne H White CPA LLC" t:ous_division="Oregon State University" m:amount=760
```

## Meta Commands

```ls
metric m:amount p:decimal l:Amount t:dataTypeName=number

entity e:3zzd-2ab8 l:"Expenditures OUS: Oregon State University: FY 2014" t:url=https://data.oregon.gov/api/views/3zzd-2ab8

property e:3zzd-2ab8 t:meta.view v:id=3zzd-2ab8 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures OUS: Oregon State University: FY 2014"

property e:3zzd-2ab8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:3zzd-2ab8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| ous_division            | account_category               | vendor_address                | vendor_city | vendor_state | vendor_zip_postal_code | vendor_name                         | amount    | 
| ======================= | ============================== | ============================= | =========== | ============ | ====================== | =================================== | ========= | 
| Oregon State University | Accounting Service             | Attn: NCAA Travel Dept        | Waterloo    | IA           | 50701-4017             | Shorts Travel Management            | 5687.5    | 
| Oregon State University | Accounting Service             | 2051 Kaen Rd # 470            | Oregon City | OR           | 97045-4035             | Clackamas County                    | 3000      | 
| Oregon State University | Accounting Service             | PO Box 1832                   | Corvallis   | OR           | 97339-1832             | Anne H White CPA LLC                | 760       | 
| Oregon State University | Accounting Service             | Public Works                  | Corvallis   | OR           | 97333-1139             | Benton County                       | 468.43    | 
| Oregon State University | Accounting Service             | PO Box 1510                   | Albany      | OR           | 97321-0455             | D&M Saw & Mfg Inc                   | 21        | 
| Oregon State University | Advertising-Inst Promo/Pub Rel | 1900 NE 3rd St Ste 106-290    | Bend        | OR           | 97701-3854             | Lisa A Canady dba Eclipse Marketing | 694703.92 | 
| Oregon State University | Advertising-Inst Promo/Pub Rel | 2290 Commercial St SE Ste 101 | Salem       | OR           | 97302-5374             | Graymerson Inc dba Fastsigns 285    | 96414.37  | 
| Oregon State University | Advertising-Inst Promo/Pub Rel | PO Box 742316                 | Los Angeles | CA           | 90074-2316             | The Business Journal of Portland    | 50711     | 
| Oregon State University | Advertising-Inst Promo/Pub Rel | P O Box 505208                | Saint Louis | MO           | 63150-0001             | Hobsons Inc                         | 49941     | 
| Oregon State University | Advertising-Inst Promo/Pub Rel | dba Blue Dawg Promotions      | Corvallis   | OR           | 97330                  | Innovative Business Promotions      | 47599.33  | 
```