# Maryland Funding FY09 Payments Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-funding-fy09-payments-data-a75d5) |
| Metadata | [Link](https://data.maryland.gov/api/views/6m3w-wpyf) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6m3w-wpyf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6m3w-wpyf/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6m3w-wpyf |
| Name | Maryland Funding FY09 Payments Data |
| Attribution | Maryland Department of Budget and Management; Maryland Department of Information Technolgoy |
| Category | Budget |
| Tags | spending, budget, vendor, payments |
| Created | 2013-01-18T17:28:41Z |
| Publication Date | 2014-08-22T15:56:09Z |

## Description

Summary information of payments to vendors that received $25,000 or more for a respective fiscal year also published on spending.dbm.maryland.gov website..

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | text        |
| Yes      | series tag     | agency_name | Agency Name | text      | text        |
| Yes      | series tag     | vendor_name | Vendor Name | text      | text        |
| Yes      | series tag     | vendor_zip  | Vendor Zip  | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6m3w-wpyf d:2009-01-01T00:00:00.000Z t:vendor_zip=21625 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="MARTINEZ HAULING INC" m:amount=71660

series e:6m3w-wpyf d:2009-01-01T00:00:00.000Z t:vendor_zip=20604 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="BELTWAY PAVING" m:amount=47380

series e:6m3w-wpyf d:2009-01-01T00:00:00.000Z t:vendor_zip=21221 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="KING MULCH" m:amount=195455.4
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:6m3w-wpyf l:"Maryland Funding FY09 Payments Data" t:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technolgoy" t:url=https://data.maryland.gov/api/views/6m3w-wpyf

property e:6m3w-wpyf t:meta.view v:id=6m3w-wpyf v:category=Budget v:attributionLink=http://spending.dbm.maryland.gov v:averageRating=0 v:name="Maryland Funding FY09 Payments Data" v:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technolgoy"

property e:6m3w-wpyf t:meta.view.license v:name="Public Domain"

property e:6m3w-wpyf t:meta.view.owner v:id=kkuv-jqse v:screenName="Teri Greene" v:displayName="Teri Greene"

property e:6m3w-wpyf t:meta.view.tableauthor v:id=kkuv-jqse v:screenName="Teri Greene" v:roleName=editor v:displayName="Teri Greene"
```

## Top Records

```ls
| year | agency_name                     | vendor_name          | vendor_zip | amount   | 
| ==== | =============================== | ==================== | ========== | ======== | 
| 2009 | STATE HIGHWAY ADMIN             | MARTINEZ HAULING INC | 21625      | 71660    | 
| 2009 | STATE HIGHWAY ADMIN             | BELTWAY PAVING       | 20604      | 47380    | 
| 2009 | STATE HIGHWAY ADMIN             | KING MULCH           | 21221      | 195455.4 | 
| 2009 | STATE BOARD OF ELECTIONS        | GIS SOLUTIONS        | 21013      | 2065     | 
| 2009 | MARYLAND STADIUM AUTHORITY      | TEL-NET GROUP        | 21237      | 1180     | 
| 2009 | DEPARTMENT OF HUMAN RESOURCES   | RAVI PASSI MD PC     | 20898      | 31.2     | 
| 2009 | STATE HIGHWAY ADMIN             | WORLD WIDE CORP      | 21207      | 9028.49  | 
| 2009 | STATE HIGHWAY ADMIN             | BRITTAIN INC         | 21154      | 31062.5  | 
| 2009 | DEPARTMENT OF JUVENILE SERVICES | MAXIMUS INC          | 20190      | 16200    | 
| 2009 | DEPARTMENT OF HUMAN RESOURCES   | THE PINES            | 23704      | 2520     | 
```