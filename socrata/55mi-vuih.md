# Expenditures: OUS: University of Oregon: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-ous-university-of-oregon-fy-2014-eb76f) |
| Metadata | [Link](https://data.oregon.gov/api/views/55mi-vuih) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/55mi-vuih/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/55mi-vuih/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 55mi-vuih |
| Name | Expenditures: OUS: University of Oregon: FY 2014 |
| Category | Revenue & Expense |
| Tags | uo expenditures, u of o expenditures, university of oregon expenditures, ous expenditures 2014, 2014 |
| Created | 2014-12-27T01:55:49Z |
| Publication Date | 2014-12-29T03:08:36Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | ous_division           | OUS Division           | text      | text        |
| Yes      | series tag     | account_category       | Account Category       | text      | text        |
| Yes      | series tag     | vendor_name            | Vendor Name            | text      | text        |
| No       |                | vendor_address         | Vendor Address         | text      | text        |
| Yes      | series tag     | vendor_city            | Vendor City            | text      | text        |
| Yes      | series tag     | vendor_state           | Vendor State           | text      | text        |
| Yes      | series tag     | vendor_zip_postal_code | Vendor Zip/Postal Code | text      | text        |
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
series e:55mi-vuih d:2014-01-01T00:00:00.000Z t:vendor_city=Cincinnati t:vendor_state=OH t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_zip_postal_code=45241-2398 t:vendor_name="Hobsons Inc" t:ous_division="University of Oregon" m:amount=244651.54

series e:55mi-vuih d:2014-01-01T00:00:00.000Z t:vendor_city=Eugene t:vendor_state=OR t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_zip_postal_code=97403-5275 t:vendor_name="Emerald Media Group Inc/dba Oregon" t:ous_division="University of Oregon" m:amount=138912.7

series e:55mi-vuih d:2014-01-01T00:00:00.000Z t:vendor_city="Saint Louis" t:vendor_state=MO t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_zip_postal_code=63150-0001 t:vendor_name="Hobsons Inc" t:ous_division="University of Oregon" m:amount=118834.5
```

## Meta Commands

```ls
metric m:amount p:decimal l:Amount t:dataTypeName=number

entity e:55mi-vuih l:"Expenditures: OUS: University of Oregon: FY 2014" t:url=https://data.oregon.gov/api/views/55mi-vuih

property e:55mi-vuih t:meta.view v:id=55mi-vuih v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: OUS: University of Oregon: FY 2014"

property e:55mi-vuih t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:55mi-vuih t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| ous_division         | account_category               | vendor_name                         | vendor_address            | vendor_city   | vendor_state | vendor_zip_postal_code | amount             | 
| ==================== | ============================== | =================================== | ========================= | ============= | ============ | ====================== | ================== | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Hobsons Inc                         | 50 E Business Way Ste 300 | Cincinnati    | OH           | 45241-2398             | 244651.54          | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Emerald Media Group Inc/dba Oregon  | 1222 E 13th Ave Apt 300   | Eugene        | OR           | 97403-5275             | 138912.70000000001 | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Hobsons Inc                         | PO Box 505208             | Saint Louis   | MO           | 63150-0001             | 118834.5           | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Adams Hull + MacCleur Incorporated/ | 860 W Park St Ste 100     | Eugene        | OR           | 97401-3064             | 115837             | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Lamar Texas Limited Partnership/dba | Lamar Companies           | Baton Rouge   | LA           | 70896-9030             | 68430              | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Oregon Public Broadcasting          | 7140 Sw Macadam Ave       | Portland      | OR           | 97219-3013             | 65403              | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Alliance Corporation                | 8945 W Russell Rd Ste 150 | Las Vegas     | NV           | 89148-1228             | 62250.01           | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Higher Edge Marketing Services Inc  | 98 Battery St Ste 601     | San Francisco | CA           | 94111-5529             | 61650              | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | Balancing Act TV LLC                | 2001 W Sample Rd Ste 101  | Pompano Beach | FL           | 33064-1342             | 54700              | 
| University of Oregon | Advertising-Inst Promo/Pub Rel | What's Happening Inc/dba Eugene Wee | 1251 Lincoln              | Eugene        | OR           | 97401-3418             | 52294.78           | 
```