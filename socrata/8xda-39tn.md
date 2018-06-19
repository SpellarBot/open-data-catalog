# FY14 Payments Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy14-payments-data-f0968) |
| Metadata | [Link](https://data.maryland.gov/api/views/8xda-39tn) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8xda-39tn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8xda-39tn/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8xda-39tn |
| Name | FY14 Payments Data |
| Attribution | Maryland Department of Budget and Management |
| Category | Budget |
| Tags | budget, spending, fiscal, vendors, payments, department of budget and management, dbm, tax |
| Created | 2015-01-12T17:17:03Z |
| Publication Date | 2015-01-22T14:24:10Z |

## Description

This dataset shows all payments made by state agencies from Fiscal Years 2008 to 2015 which were $25,000 or more. All parties receiving funds are shown: private businesses, local governments, non-profit organizations, and individuals.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
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
series e:8xda-39tn d:2014-01-01T00:00:00.000Z t:vendor_zip=21403 t:agency_name="COMPTROLLER OF MARYLAND" t:vendor_name="AUTOMATED CONCEPTS LLC" m:amount=7580

series e:8xda-39tn d:2014-01-01T00:00:00.000Z t:vendor_zip=19801 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="EASTERN HIGHWAY SPECIALISTS" m:amount=534659.65

series e:8xda-39tn d:2014-01-01T00:00:00.000Z t:vendor_zip=20689 t:agency_name="STATE HIGHWAY ADMIN" t:vendor_name="JW GRANER INC" m:amount=62515
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:8xda-39tn l:"FY14 Payments Data" t:attribution="Maryland Department of Budget and Management" t:url=https://data.maryland.gov/api/views/8xda-39tn

property e:8xda-39tn t:meta.view v:id=8xda-39tn v:category=Budget v:attributionLink=http://spending.dbm.maryland.gov v:averageRating=0 v:name="FY14 Payments Data" v:attribution="Maryland Department of Budget and Management"

property e:8xda-39tn t:meta.view.license v:name="Public Domain"

property e:8xda-39tn t:meta.view.owner v:id=w7ik-gssi v:screenName="Lan Pasek" v:displayName="Lan Pasek"

property e:8xda-39tn t:meta.view.tableauthor v:id=w7ik-gssi v:screenName="Lan Pasek" v:roleName=publisher v:displayName="Lan Pasek"
```

## Top Records

```ls
| year | agency_name                             | vendor_name                 | vendor_zip | amount    | 
| ==== | ======================================= | =========================== | ========== | ========= | 
| 2014 | COMPTROLLER OF MARYLAND                 | AUTOMATED CONCEPTS LLC      | 21403      | 7580      | 
| 2014 | STATE HIGHWAY ADMIN                     | EASTERN HIGHWAY SPECIALISTS | 19801      | 534659.65 | 
| 2014 | STATE HIGHWAY ADMIN                     | JW GRANER INC               | 20689      | 62515     | 
| 2014 | STATE HIGHWAY ADMIN                     | RONALD REED                 | 20711      | 404412.5  | 
| 2014 | STATE HIGHWAY ADMIN                     | BEN POSEY                   | 21613      | 25065     | 
| 2014 | OFFICE OF THE ATTORNEY GENERAL          | BNA                         | 21297      | 9972.14   | 
| 2014 | DHMH-GENERAL ACCOUNTING                 | SHAWN DHILLON MD PC         | 21218      | 54365.36  | 
| 2014 | MARYLAND STATE DEPARTMENT OF EDUCATION  | DEBORAH O'DONNELL           | 20653      | 25444.25  | 
| 2014 | MARYLAND PORT ADMINISTRATION            | CIANBRO CORPORATION         | 02125      | 303366.92 | 
| 2014 | DEPARTMENT OF GENERAL SERVICES- CAPITAL | CIANBRO CORPORATION         | 02125      | 201257.01 | 
```