# Libraries Expenditures FY2007 - FY2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-expenditures-fy2007-fy2010-27d68) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cqxe-ukdd) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cqxe-ukdd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cqxe-ukdd/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cqxe-ukdd |
| Name | Libraries Expenditures FY2007 - FY2010 |
| Attribution | Hawaii State Public Library System |
| Category | Formal Education |
| Tags | library, expenditure |
| Created | 2012-07-26T20:02:43Z |
| Publication Date | 2012-07-26T20:03:45Z |

## Description

Expenditure information for items procured by the State Libraries

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | numeric metric | fy_2007     | FY 2007     | money     | money       |
| Yes      | numeric metric | fy_2008     | FY 2008     | money     | money       |
| Yes      | numeric metric | fy_2009     | FY 2009     | money     | money       |
| Yes      | numeric metric | fy_2010     | FY 2010     | money     | money       |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cqxe-ukdd d:2007-01-01T00:00:00.000Z t:description=Payroll m:fy_2010=20341195 m:fy_2008=22609655 m:fy_2009=22895321 m:fy_2007=21446107

series e:cqxe-ukdd d:2007-01-01T00:00:00.000Z t:description=Supplies m:fy_2010=301854 m:fy_2008=454646 m:fy_2009=318636 m:fy_2007=466078

series e:cqxe-ukdd d:2007-01-01T00:00:00.000Z t:description=Dues/Subscriptions m:fy_2010=49692 m:fy_2008=88217 m:fy_2009=19891 m:fy_2007=254397
```

## Meta Commands

```ls
metric m:fy_2007 p:integer l:"FY 2007" t:dataTypeName=money

metric m:fy_2008 p:integer l:"FY 2008" t:dataTypeName=money

metric m:fy_2009 p:integer l:"FY 2009" t:dataTypeName=money

metric m:fy_2010 p:integer l:"FY 2010" t:dataTypeName=money

entity e:cqxe-ukdd l:"Libraries Expenditures FY2007 - FY2010" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/cqxe-ukdd

property e:cqxe-ukdd t:meta.view v:id=cqxe-ukdd v:category="Formal Education" v:attributionLink=http://www.librarieshawaii.org/ v:averageRating=0 v:name="Libraries Expenditures FY2007 - FY2010" v:attribution="Hawaii State Public Library System"

property e:cqxe-ukdd t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:cqxe-ukdd t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:cqxe-ukdd t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| description           | fy_2007  | fy_2008  | fy_2009  | fy_2010  | 
| ===================== | ======== | ======== | ======== | ======== | 
| Payroll               | 21446107 | 22609655 | 22895321 | 20341195 | 
| Supplies              | 466078   | 454646   | 318636   | 301854   | 
| Dues/Subscriptions    | 254397   | 88217    | 19891    | 49692    | 
| Postage/Freight       | 401434   | 371059   | 876595   | 124540   | 
| Telephone             | 63699    | 330900   | 51890    | 278935   | 
| Travel                | 114463   | 98187    | 58581    | 45800    | 
| Utilities             | 1907912  | 2438936  | 2070592  | 2005413  | 
| Equipment Rentals     | 290916   | 156554   | 33073    | 26589    | 
| Repair/Maintenance    | 146611   | 289724   | 145021   | 255514   | 
| Workers' Compensation | 189609   | 146101   | 255002   | 187813   | 
```