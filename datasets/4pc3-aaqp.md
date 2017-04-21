# Budget 2012- General Fund Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-general-fund-revenue-c06ea) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4pc3-aaqp) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4pc3-aaqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4pc3-aaqp/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4pc3-aaqp |
| Name | Budget 2012- General Fund Revenue |
| Attribution | King County |
| Category | Budget |
| Tags | budget |
| Created | 2011-09-26T02:30:18Z |
| Publication Date | 2011-09-26T02:32:04Z |

## Description

2012 Proposed revenue sources for the general fund. More at http://www.kingcounty.gov/budget

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type | Render Type |
| ======== | ============== | =========== | ============= | ========= | =========== |
| Yes      | series tag     | fund_source | Fund Source   | text      | text        |
| Yes      | numeric metric | proposed    | 2012 Proposed | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4pc3-aaqp d:2012-01-01T00:00:00.000Z t:fund_source=Taxes m:proposed=392574838

series e:4pc3-aaqp d:2012-01-01T00:00:00.000Z t:fund_source="Licenses & Permits" m:proposed=3971884

series e:4pc3-aaqp d:2012-01-01T00:00:00.000Z t:fund_source="Federal Grants-Direct" m:proposed=970488
```

## Meta Commands

```ls
metric m:proposed p:integer l:"2012 Proposed" t:dataTypeName=money

entity e:4pc3-aaqp l:"Budget 2012- General Fund Revenue" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/4pc3-aaqp

property e:4pc3-aaqp t:meta.view v:id=4pc3-aaqp v:category=Budget v:attributionLink=http://www.kingcounty.gov/exec/psb/budget v:averageRating=0 v:name="Budget 2012- General Fund Revenue" v:attribution="King County"

property e:4pc3-aaqp t:meta.view.license v:name="Public Domain"

property e:4pc3-aaqp t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:4pc3-aaqp t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| fund_source               | proposed  | 
| ========================= | ========= | 
| Taxes                     | 392574838 | 
| Licenses & Permits        | 3971884   | 
| Federal Grants-Direct     | 970488    | 
| Federal Shared Revenues   | 115000    | 
| Federal Grants-Indirect   | 8658908   | 
| State Grants              | 2297051   | 
| State Entitlements        | 9243514   | 
| Intergovernmental Payment | 85465576  | 
| Charges for Services      | 115667215 | 
| Fines & Forfeits          | 9415580   | 
```