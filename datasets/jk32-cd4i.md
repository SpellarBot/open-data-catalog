# WIC Authorized Vendors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wic-authorized-vendors) |
| Metadata | [Link](https://data.ct.gov/api/views/jk32-cd4i) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/jk32-cd4i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/jk32-cd4i/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | jk32-cd4i |
| Name | WIC Authorized Vendors |
| Attribution | Connecticut WIC Program |
| Category | Health and Human Services |
| Tags | wic, authorized vendors, vendors |
| Created | 2015-04-02T15:29:26Z |
| Publication Date | 2016-07-18T12:27:57Z |

## Description

A list of food stores and pharmacies that are currently authorized by the Connecticut WIC Program to accept WIC checks as of July 5, 2016.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | vendor      | Vendor     | text      | text        |
| Yes      | series tag  | phone       | Agency     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jk32-cd4i d:2016-07-18T05:25:58.000Z t:phone=Bridgeport-021 t:vendor="BIG Y WORLD CLASS MARKET #35" m:row_number.jk32-cd4i=1

series e:jk32-cd4i d:2016-07-18T05:25:58.000Z t:phone=Bridgeport-021 t:vendor="CVS #1941" m:row_number.jk32-cd4i=2

series e:jk32-cd4i d:2016-07-18T05:25:58.000Z t:phone="Bristol-190/New Britain-180" t:vendor="CVS #0954" m:row_number.jk32-cd4i=3
```

## Meta Commands

```ls
metric m:row_number.jk32-cd4i p:long l:"Row Number"

entity e:jk32-cd4i l:"WIC Authorized Vendors" t:attribution="Connecticut WIC Program" t:url=https://data.ct.gov/api/views/jk32-cd4i

property e:jk32-cd4i t:meta.view v:id=jk32-cd4i v:category="Health and Human Services" v:attributionLink=http://www.ct.gov/dph/wic v:averageRating=0 v:name="WIC Authorized Vendors" v:attribution="Connecticut WIC Program"

property e:jk32-cd4i t:meta.view.license v:name="Public Domain"

property e:jk32-cd4i t:meta.view.owner v:id=dby8-627v v:screenName="Gary Archambault" v:displayName="Gary Archambault"

property e:jk32-cd4i t:meta.view.tableauthor v:id=dby8-627v v:screenName="Gary Archambault" v:roleName=editor v:displayName="Gary Archambault"
```

## Top Records

```ls
| :updated_at | vendor                       | phone                       | 
| =========== | ============================ | =========================== | 
| 1468819558  | BIG Y WORLD CLASS MARKET #35 | Bridgeport-021              | 
| 1468819558  | CVS #1941                    | Bridgeport-021              | 
| 1468819558  | CVS #0954                    | Bristol-190/New Britain-180 | 
| 1468819558  | GEISSLER'S SUPERMARKET       | Bristol-190/New Britain-180 | 
| 1468819558  | TARGET T-2434 (no pharmacy)  | Bristol-190/New Britain-180 | 
| 1468819559  | CHEERS DELI & GROCERY        | TVCCA-010                   | 
| 1468819585  | BARGAIN FOOD CENTER          | Waterbury-090/Naugatuck-120 | 
| 1468819585  | POLLA SUPERMARKET            | Danbury-200                 | 
| 1468819585  | BIG Y WORLD CLASS MARKET #87 | New Haven-100               | 
| 1468819585  | GRADE A SHOPRITE #398        | Waterbury-090/Naugatuck-120 | 
```