# Expenditures: OUS: Southern Oregon University: FY 2014

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/whnr-x36y/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/expenditures-ous-southern-oregon-university-fy-2014-f77ac)
* Id = whnr-x36y
* Name = Expenditures: OUS: Southern Oregon University: FY 2014
* Category = Revenue & Expense
* Tags = [sou expenditures, southern oregon university expenditures, ous expenditures 2014, 2014]
* Created = 2014-12-27T02:08:59Z
* Publication Date = 2014-12-29T03:09:19Z
* Rows Updated = 2014-12-27T02:09:13Z

## Description



## Columns

```ls
| Name                   | Field Name             | Data Type | Render Type | Schema Type    | Included | 
| ====================== | ====================== | ========= | =========== | ============== | ======== | 
| updated_at             | :updated_at            | meta_data | meta_data   | time           | Yes      | 
| OUS Division           | ous_division           | text      | text        | series tag     | Yes      | 
| Account Category       | account_category       | text      | text        | series tag     | Yes      | 
| Vendor Address         | vendor_address         | text      | text        |                | No       | 
| Vendor City            | vendor_city            | text      | text        | series tag     | Yes      | 
| Vendor State           | vendor_state           | text      | text        | series tag     | Yes      | 
| Vendor Zip/Postal Code | vendor_zip_postal_code | text      | number      | series tag     | Yes      | 
| Vendor Name            | vendor_name            | text      | text        | series tag     | Yes      | 
| Amount                 | amount                 | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = vendor_address
Annotation Fields = 
```

## Data Commands

```ls
series e:whnr-x36y d:2014-12-26T18:09:02.000Z t:vendor_city="GRANTS PASS" t:vendor_state=OR t:account_category="Accounting Service" t:vendor_name="Rogue Community College" t:ous_division="Southern Oregon University" m:amount=9175.25

series e:whnr-x36y d:2014-12-26T18:09:02.000Z t:vendor_city=PASADENA t:vendor_state=CA t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_name="Mail Tribune Co" t:ous_division="Southern Oregon University" m:amount=13616.19

series e:whnr-x36y d:2014-12-26T18:09:02.000Z t:vendor_city=ASHLAND t:vendor_state=OR t:account_category="Advertising-Inst Promo/Pub Rel" t:vendor_zip_postal_code=97520 t:vendor_name="Ashland Chamber of Commerce" t:ous_division="Southern Oregon University" m:amount=13125
```

## Meta Commands

```ls
entity e:whnr-x36y l:"Expenditures: OUS: Southern Oregon University: FY 2014" t:url=https://data.oregon.gov/api/views/whnr-x36y

property e:whnr-x36y t:meta.view d:2017-03-03T14:21:58.789Z v:id=whnr-x36y v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: OUS: Southern Oregon University: FY 2014"

property e:whnr-x36y t:meta.view.owner d:2017-03-03T14:21:58.789Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:whnr-x36y t:meta.view.tableauthor d:2017-03-03T14:21:58.789Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```