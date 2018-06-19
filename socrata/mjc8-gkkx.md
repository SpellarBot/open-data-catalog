# Licensee Excise Tax Reported

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensee-excise-tax-reported) |
| Metadata | [Link](https://data.mo.gov/api/views/mjc8-gkkx) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/mjc8-gkkx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/mjc8-gkkx/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | mjc8-gkkx |
| Name | Licensee Excise Tax Reported |
| Attribution | MO Department of Public Safety - Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | missouri excise tax gallons |
| Created | 2015-01-26T16:23:39Z |
| Publication Date | 2016-10-13T16:31:13Z |

## Description

Excise Tax data reported by number of gallons per product type. Dataset consists of the last 6 reporting months.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | numeric metric | licensenum      | LicenseNum      | number    | text        |
| Yes      | series tag     | licensecodetxt  | LicenseType     | text      | text        |
| Yes      | series tag     | licenseenametxt | BusinessName    | text      | text        |
| Yes      | series tag     | statetxt        | State           | text      | text        |
| No       |                | taxperioddate   | ReportingPeriod | text      | text        |
| Yes      | series tag     | taxgroupkey     | Category        | text      | text        |
| Yes      | numeric metric | gallonsnum      | Gallons         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = taxperioddate
```

## Data Commands

```ls
series e:mjc8-gkkx d:2017-04-17T13:31:01.000Z t:licenseenametxt="STONE HILL WINE COMPANY INC." t:statetxt=MO t:licensecodetxt=DOMW t:taxgroupkey=L m:gallonsnum=0 m:licensenum=13754

series e:mjc8-gkkx d:2017-04-17T13:31:01.000Z t:licenseenametxt="STONE HILL WINE COMPANY INC." t:statetxt=MO t:licensecodetxt=DOMW t:taxgroupkey=M m:gallonsnum=0 m:licensenum=13754

series e:mjc8-gkkx d:2017-04-17T13:31:01.000Z t:licenseenametxt="STONE HILL WINE COMPANY INC." t:statetxt=MO t:licensecodetxt=DOMW t:taxgroupkey=W m:gallonsnum=0 m:licensenum=13754
```

## Meta Commands

```ls
metric m:licensenum p:integer l:LicenseNum d:"Missouri license number of the business." t:dataTypeName=number

metric m:gallonsnum p:double l:Gallons d:"Number of gallons reported for the Group type and reporting period." t:dataTypeName=number

entity e:mjc8-gkkx l:"Licensee Excise Tax Reported" t:attribution="MO Department of Public Safety - Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/mjc8-gkkx

property e:mjc8-gkkx t:meta.view v:id=mjc8-gkkx v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="Licensee Excise Tax Reported" v:attribution="MO Department of Public Safety - Division of Alcohol and Tobacco Control"

property e:mjc8-gkkx t:meta.view.license v:name="Public Domain"

property e:mjc8-gkkx t:meta.view.owner v:id=hxwx-y8az v:profileImageUrlMedium=/api/users/hxwx-y8az/profile_images/THUMB v:profileImageUrlLarge=/api/users/hxwx-y8az/profile_images/LARGE v:screenName="Missouri Department of Public Safety" v:profileImageUrlSmall=/api/users/hxwx-y8az/profile_images/TINY v:displayName="Missouri Department of Public Safety"

property e:mjc8-gkkx t:meta.view.tableauthor v:id=hxwx-y8az v:profileImageUrlMedium=/api/users/hxwx-y8az/profile_images/THUMB v:profileImageUrlLarge=/api/users/hxwx-y8az/profile_images/LARGE v:screenName="Missouri Department of Public Safety" v:profileImageUrlSmall=/api/users/hxwx-y8az/profile_images/TINY v:roleName=editor v:displayName="Missouri Department of Public Safety"
```

## Top Records

```ls
| :updated_at | licensenum | licensecodetxt | licenseenametxt              | statetxt | taxperioddate | taxgroupkey | gallonsnum | 
| =========== | ========== | ============== | ============================ | ======== | ============= | =========== | ========== | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-09       | L           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-09       | M           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-09       | W           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-10       | L           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-10       | M           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-10       | W           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-11       | L           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-11       | M           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-11       | W           | 0.00       | 
| 1492435861  | 13754      | DOMW           | STONE HILL WINE COMPANY INC. | MO       | 2016-12       | L           | 0.00       | 
```