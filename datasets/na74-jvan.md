# Maryland Funding FY11 Payments Data

## Dataset

* [Dataset URL](https://data.maryland.gov/api/views/na74-jvan/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/maryland-funding-fy11-payments-data-6fda1)
* Id = na74-jvan
* Name = Maryland Funding FY11 Payments Data
* Attribution = Maryland Department of Budget and Management; Maryland Department of Information Technology
* Attribution Link = http://www.spending.dbm.maryland.gov
* Category = Budget
* Tags = [spending, budget, vendor, payments]
* Created = 2013-01-18T17:42:56Z
* Publication Date = 2014-08-22T15:52:22Z
* Rows Updated = 2014-08-22T15:51:51Z

## Description

This dataset contains summary information on payments made to vendors that received $25,000 or more in fiscal year 2012.  The data is also published and searchable online on the www.spending.dbm.maryland.gov website.

## Columns

```ls
| Name        | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| =========== | =========== | ========= | =========== | ============== | ======== | 
| Year        | year        | number    | text        | time           | Yes      | 
| Agency Name | agency_name | text      | text        | series tag     | Yes      | 
| Vendor Name | vendor_name | text      | text        | series tag     | Yes      | 
| Vendor Zip  | vendor_zip  | text      | text        | series tag     | Yes      | 
| Amount      | amount      | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:na74-jvan d:2011-01-01T00:00:00.000Z t:vendor_zip=21802 t:agency_name="DHMH-GENERAL ACCOUNTING" t:vendor_name="PROCOAT, INC." m:amount=2390

series e:na74-jvan d:2011-01-01T00:00:00.000Z t:vendor_zip=21201 t:agency_name="ENERGY ADMINISTRATION" t:vendor_name=BITHENERGY,INC. m:amount=42750.2

series e:na74-jvan d:2011-01-01T00:00:00.000Z t:vendor_zip=60197 t:agency_name="MILITARY DEPARTMENT" t:vendor_name="SPRINT PCS" m:amount=28470.56
```

## Meta Commands

```ls
entity e:na74-jvan l:"Maryland Funding FY11 Payments Data" t:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technology" t:url=https://data.maryland.gov/api/views/na74-jvan

property e:na74-jvan t:meta.view d:2017-03-03T14:09:21.598Z v:id=na74-jvan v:category=Budget v:attributionLink=http://www.spending.dbm.maryland.gov v:averageRating=0 v:name="Maryland Funding FY11 Payments Data" v:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technology"

property e:na74-jvan t:meta.view.license d:2017-03-03T14:09:21.598Z v:name="Public Domain"

property e:na74-jvan t:meta.view.owner d:2017-03-03T14:09:21.598Z v:id=kkuv-jqse v:screenName="Teri Greene" v:roleName=editor v:displayName="Teri Greene"

property e:na74-jvan t:meta.view.tableauthor d:2017-03-03T14:09:21.598Z v:id=kkuv-jqse v:screenName="Teri Greene" v:roleName=editor v:displayName="Teri Greene"
```