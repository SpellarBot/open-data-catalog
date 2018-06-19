# DCEO County Retail Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-county-retail-sales-5d7ae) |
| Metadata | [Link](https://data.illinois.gov/api/views/q9xi-hgtu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/q9xi-hgtu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/q9xi-hgtu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | q9xi-hgtu |
| Name | DCEO County Retail Sales |
| Attribution | Illinois Department of Commerce and Economic Opportunity |
| Category | Economics |
| Tags | county, retail, sales |
| Created | 2011-06-15T01:50:32Z |
| Publication Date | 2011-06-15T01:50:32Z |

## Description

Historical data of Illinois County Retail Sales

## Columns

```ls
| Included | Schema Type    | Field Name     | Name             | Data Type | Render Type |
| ======== | ============== | ============== | ================ | ========= | =========== |
| Yes      | time           | year           | Year             | number    | number      |
| No       |                | time_period    | Time Period      | text      | text        |
| Yes      | series tag     | county         | County           | text      | text        |
| Yes      | numeric metric | sales_millions | Sales (Millions) | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = time_period
```

## Data Commands

```ls
series e:q9xi-hgtu d:1995-01-01T00:00:00.000Z t:county=Adams m:sales_millions=640

series e:q9xi-hgtu d:1995-01-01T00:00:00.000Z t:county=Alexander m:sales_millions=37

series e:q9xi-hgtu d:1995-01-01T00:00:00.000Z t:county=Bond m:sales_millions=79
```

## Meta Commands

```ls
metric m:sales_millions p:double l:"Sales (Millions)" t:dataTypeName=money

entity e:q9xi-hgtu l:"DCEO County Retail Sales" t:attribution="Illinois Department of Commerce and Economic Opportunity" t:url=https://data.illinois.gov/api/views/q9xi-hgtu

property e:q9xi-hgtu t:meta.view v:id=q9xi-hgtu v:category=Economics v:averageRating=0 v:name="DCEO County Retail Sales" v:attribution="Illinois Department of Commerce and Economic Opportunity"

property e:q9xi-hgtu t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:q9xi-hgtu t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| year | time_period | county    | sales_millions | 
| ==== | =========== | ========= | ============== | 
| 1995 | Annual      | Adams     | 640.00         | 
| 1995 | Annual      | Alexander | 37.00          | 
| 1995 | Annual      | Bond      | 79.00          | 
| 1995 | Annual      | Boone     | 222.00         | 
| 1995 | Annual      | Brown     | 19.00          | 
| 1995 | Annual      | Bureau    | 216.00         | 
| 1995 | Annual      | Calhoun   | 23.00          | 
| 1995 | Annual      | Carroll   | 90.00          | 
| 1995 | Annual      | Cass      | 79.00          | 
| 1995 | Annual      | Champaign | 1629.00        | 
```