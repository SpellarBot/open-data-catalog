# Cook County Clerk - Taxing Agencies with Tax Rates - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-taxing-agencies-with-tax-rates-2010-2f4d4) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9sdc-hj8j) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9sdc-hj8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9sdc-hj8j/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9sdc-hj8j |
| Name | Cook County Clerk - Taxing Agencies with Tax Rates - 2010 |
| Attribution | Cook County Clerk |
| Category | Finance & Administration |
| Created | 2011-10-17T13:26:22Z |
| Publication Date | 2014-10-09T23:16:13Z |

## Description

This dataset is now depricated in favor of: https://datacatalog.cookcountyil.gov/Property-Taxation/Cook-County-Clerk-Tax-Agency-Rates/9sgn-ibhu. Cook county taxing agencies and their final 2010 tax rates.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type | Render Type |
| ======== | ============== | =========== | ============= | ========= | =========== |
| Yes      | series tag     | agency_name | Agency Name   | text      | text        |
| Yes      | numeric metric | tax_rate    | 2010 Tax Rate | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9sdc-hj8j d:2010-01-01T00:00:00.000Z t:agency_name="COUNTY OF COOK" m:tax_rate=0.423

series e:9sdc-hj8j d:2010-01-01T00:00:00.000Z t:agency_name="CONSOLIDATED ELECTIONS" m:tax_rate=0

series e:9sdc-hj8j d:2010-01-01T00:00:00.000Z t:agency_name="FOREST PRESERVE DISTRICT OF COOK COUNTY" m:tax_rate=0.051
```

## Meta Commands

```ls
metric m:tax_rate p:float l:"2010 Tax Rate" t:dataTypeName=number

entity e:9sdc-hj8j l:"Cook County Clerk - Taxing Agencies with Tax Rates - 2010" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/9sdc-hj8j

property e:9sdc-hj8j t:meta.view v:id=9sdc-hj8j v:category="Finance & Administration" v:attributionLink=http://cookcountyclerk.com v:averageRating=0 v:name="Cook County Clerk - Taxing Agencies with Tax Rates - 2010" v:attribution="Cook County Clerk"

property e:9sdc-hj8j t:meta.view.license v:name="Public Domain"

property e:9sdc-hj8j t:meta.view.owner v:id=g8dv-kipf v:screenName=malexander v:displayName=malexander

property e:9sdc-hj8j t:meta.view.tableauthor v:id=g8dv-kipf v:screenName=malexander v:roleName=publisher v:displayName=malexander
```

## Top Records

```ls
| agency_name                             | tax_rate | 
| ======================================= | ======== | 
| COUNTY OF COOK                          | 0.423    | 
| CONSOLIDATED ELECTIONS                  | 0.000    | 
| FOREST PRESERVE DISTRICT OF COOK COUNTY | 0.051    | 
| TOWN BARRINGTON                         | 0.022    | 
| GENERAL ASSISTANCE BARRINGTON           | 0.001    | 
| ROAD AND BRIDGE BARRINGTON              | 0.000    | 
| TOWN BERWYN                             | 0.032    | 
| GENERAL ASSISTANCE BERWYN               | 0.028    | 
| BERWYN TOWNSHIP COMM MENTAL HEALTH DIST | 0.048    | 
| PUBLIC HEALTH BERWYN                    | 0.060    | 
```