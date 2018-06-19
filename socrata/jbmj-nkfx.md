# Object Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/object-codes-c5a86) |
| Metadata | [Link](https://data.illinois.gov/api/views/jbmj-nkfx) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jbmj-nkfx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jbmj-nkfx/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jbmj-nkfx |
| Name | Object Codes |
| Category | Municipality |
| Created | 2013-03-21T16:12:26Z |
| Publication Date | 2013-03-21T16:13:27Z |

## Description

City of Rockford Finance Object Codes

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | object      | Object      | number    | number      |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | series tag     | short_desc  | Short Desc  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jbmj-nkfx d:2013-03-21T09:12:27.000Z t:description="PAYROLL CASH" t:short_desc="PAYROLL CA" m:object=10011

series e:jbmj-nkfx d:2013-03-21T09:12:27.000Z t:description="CASH CIP" t:short_desc="CASH CIP" m:object=10015

series e:jbmj-nkfx d:2013-03-21T09:12:27.000Z t:description="CASH COLLECTER'S-MVP" t:short_desc="CASH COLLE" m:object=10016
```

## Meta Commands

```ls
metric m:object p:integer l:Object t:dataTypeName=number

entity e:jbmj-nkfx l:"Object Codes" t:url=https://data.illinois.gov/api/views/jbmj-nkfx

property e:jbmj-nkfx t:meta.view v:id=jbmj-nkfx v:category=Municipality v:averageRating=0 v:name="Object Codes"

property e:jbmj-nkfx t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:jbmj-nkfx t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| :updated_at | object | description              | short_desc | 
| =========== | ====== | ======================== | ========== | 
| 1363857147  | 10011  | PAYROLL CASH             | PAYROLL CA | 
| 1363857147  | 10015  | CASH CIP                 | CASH CIP   | 
| 1363857147  | 10016  | CASH COLLECTER'S-MVP     | CASH COLLE | 
| 1363857147  | 10020  | CASH WITH FISCAL AGENT   | CASH W/FA  | 
| 1363857147  | 10021  | CASH INCOME TAX AGENT    | CASH TA    | 
| 1363857147  | 10024  | SA NATIONAL CITY         | SA NAT CTY | 
| 1363857147  | 10025  | CASH SPECIAL DEPOSIT     | CASH SPEC  | 
| 1363857147  | 10029  | CASH ON HAND HIS PRESERV | CASH ON HP | 
| 1363857147  | 10030  | CASH ON HAND             | CASH ON HD | 
| 1363857147  | 10031  | CASH REFUND ACCOUNT      | CASH RFND  | 
```