# IDOR 2009 Illinois Individual Income Tax - Web Returns by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-2009-illinois-individual-income-tax-web-returns-by-county-d2905) |
| Metadata | [Link](https://data.illinois.gov/api/views/yyri-n7jj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/yyri-n7jj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/yyri-n7jj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | yyri-n7jj |
| Name | IDOR 2009 Illinois Individual Income Tax - Web Returns by County |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, income, tax |
| Created | 2011-06-15T21:31:33Z |
| Publication Date | 2011-06-15T21:31:33Z |

## Description

This report is created twice a year, usually in January as a PRELIMINARY reporting and then in August for a FINAL reporting.

ILLINOIS DEPARTMENT OF REVENUE
COUNTY REPORT
ILLINOIS INDIVIDUAL INCOME TAX
COUNTY REPORT  -  Tax Year: 2009 - PRELIMINARY
"Source: Preliminary 1040 IIT Return File Dated Jan, 2011"

Report ID: TDWR-IITEOY-008
Data Source: 2009
Report Date: 05/27/2011 11:32:55 AM

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | county     | COUNTY    | text      | text        |
| Yes      | numeric metric | returns    | Returns   | number    | number      |
| Yes      | numeric metric | total_tax  | Total Tax | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yyri-n7jj d:2009-01-01T00:00:00.000Z t:county=ADAMS m:returns=30631 m:total_tax=33754840

series e:yyri-n7jj d:2009-01-01T00:00:00.000Z t:county=ALEXANDER m:returns=2493 m:total_tax=1823961

series e:yyri-n7jj d:2009-01-01T00:00:00.000Z t:county=BOND m:returns=6786 m:total_tax=6876279
```

## Meta Commands

```ls
metric m:returns p:integer l:Returns t:dataTypeName=number

metric m:total_tax p:long l:"Total Tax" t:dataTypeName=money

entity e:yyri-n7jj l:"IDOR 2009 Illinois Individual Income Tax - Web Returns by County" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/yyri-n7jj

property e:yyri-n7jj t:meta.view v:id=yyri-n7jj v:category=Economics v:averageRating=0 v:name="IDOR 2009 Illinois Individual Income Tax - Web Returns by County" v:attribution="Illinois Department of Revenue"

property e:yyri-n7jj t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:yyri-n7jj t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| county    | returns | total_tax | 
| ========= | ======= | ========= | 
| ADAMS     | 30631   | 33754840  | 
| ALEXANDER | 2493    | 1823961   | 
| BOND      | 6786    | 6876279   | 
| BOONE     | 22684   | 29531837  | 
| BROWN     | 2286    | 2428032   | 
| BUREAU    | 16005   | 16940426  | 
| CALHOUN   | 2097    | 2224878   | 
| CARROLL   | 7569    | 7148717   | 
| CASS      | 6128    | 6061846   | 
| CHAMPAIGN | 78146   | 103415225 | 
```