# OASAS Medicaid Trend Recipient Summary Profile: Beginning State Fiscal Year 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oasas-medicaid-trend-recipient-summary-profile-beginning-state-fiscal-year-2003) |
| Metadata | [Link](https://data.ny.gov/api/views/g4vm-hyyi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/g4vm-hyyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/g4vm-hyyi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | g4vm-hyyi |
| Name | OASAS Medicaid Trend Recipient Summary Profile: Beginning State Fiscal Year 2003 |
| Attribution | New York State Office of Alcoholism and Substance Abuse Services (OASAS) |
| Category | Human Services |
| Tags | medicaid, chemical dependence, substance abuse, claims |
| Created | 2014-12-02T20:46:44Z |
| Publication Date | 2017-02-06T23:09:18Z |

## Description

This profile shows a summary of recipients, paid claims, and claim dollars spent for services reimbursed by the Medicaid Fee for Service billing system by type of chemical dependence and non-chemical dependence services received per State Fiscal Year.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | claims     | Claims     | number    | number      |
| Yes      | series tag     | county     | County     | text      | text        |
| Yes      | numeric metric | dollars    | Dollars    | money     | money       |
| Yes      | numeric metric | recipients | Recipients | number    | number      |
| Yes      | series tag     | service    | Service    | text      | text        |
| Yes      | time           | year       | Year       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g4vm-hyyi d:2003-01-01T00:00:00.000Z t:county=Albany t:service=All_ASA_Services m:claims=75869 m:recipients=1927 m:dollars=9345008

series e:g4vm-hyyi d:2004-01-01T00:00:00.000Z t:county=Albany t:service=All_ASA_Services m:claims=78596 m:recipients=2054 m:dollars=10033140

series e:g4vm-hyyi d:2005-01-01T00:00:00.000Z t:county=Albany t:service=All_ASA_Services m:claims=82482 m:recipients=2126 m:dollars=10216681
```

## Meta Commands

```ls
metric m:claims p:integer l:Claims d:"The number of service units (e.g. days, visits, weeks) for which Medicaid Fee-for-Service (FFS) paid during a state fiscal year" t:dataTypeName=number

metric m:dollars p:long l:Dollars d:"The dollar amount paid by Medicaid FFS for services rendered during the state fiscal year based on date of service" t:dataTypeName=money

metric m:recipients p:integer l:Recipients d:"The number of unique Medicaid enrollees for whom a claim was paid for a type of service received during the state fiscal year" t:dataTypeName=number

entity e:g4vm-hyyi l:"OASAS Medicaid Trend Recipient Summary Profile: Beginning State Fiscal Year 2003" t:attribution="New York State Office of Alcoholism and Substance Abuse Services (OASAS)" t:url=https://data.ny.gov/api/views/g4vm-hyyi

property e:g4vm-hyyi t:meta.view v:id=g4vm-hyyi v:category="Human Services" v:attributionLink=http://www.oasas.ny.gov/admin/hcf/index.cfm v:averageRating=0 v:name="OASAS Medicaid Trend Recipient Summary Profile: Beginning State Fiscal Year 2003" v:attribution="New York State Office of Alcoholism and Substance Abuse Services (OASAS)"

property e:g4vm-hyyi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:g4vm-hyyi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:g4vm-hyyi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| claims | county | dollars  | recipients | service          | year | 
| ====== | ====== | ======== | ========== | ================ | ==== | 
| 75869  | Albany | 9345008  | 1927       | All_ASA_Services | 2003 | 
| 78596  | Albany | 10033140 | 2054       | All_ASA_Services | 2004 | 
| 82482  | Albany | 10216681 | 2126       | All_ASA_Services | 2005 | 
| 82981  | Albany | 10308965 | 2165       | All_ASA_Services | 2006 | 
| 82845  | Albany | 9866236  | 2118       | All_ASA_Services | 2007 | 
| 80113  | Albany | 9912364  | 2187       | All_ASA_Services | 2008 | 
| 89295  | Albany | 10991829 | 2407       | All_ASA_Services | 2009 | 
| 89525  | Albany | 10456183 | 2587       | All_ASA_Services | 2010 | 
| 86006  | Albany | 9539652  | 2546       | All_ASA_Services | 2011 | 
| 74101  | Albany | 7724115  | 2432       | All_ASA_Services | 2012 | 
```