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
| Rows Updated | 2014-12-27T02:09:13Z |

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
Value = 
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

property e:whnr-x36y t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:whnr-x36y t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```