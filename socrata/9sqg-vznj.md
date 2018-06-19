# Cook County Clerk - Tax codes, agencies, and rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-tax-codes-agencies-and-rates-69cc1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9sqg-vznj) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9sqg-vznj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9sqg-vznj/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9sqg-vznj |
| Name | Cook County Clerk - Tax codes, agencies, and rates |
| Attribution | Cook County Clerk |
| Category | Property & Taxation |
| Created | 2014-09-11T17:40:42Z |
| Publication Date | 2014-10-09T22:50:26Z |

## Description

This dataset shows what agencies are in a tax code for each tax year along with the agency and tax code rates. Data is updated yearly. For more information on Tax codes and Tax agencies visit the Cook County Clerk's website at: http://www.cookcountyclerk.com/tsd/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | tax_year      | Tax Year      | number    | number      |
| Yes      | series tag     | tax_code      | Tax code      | text      | number      |
| Yes      | series tag     | agency        | Agency        | text      | text        |
| Yes      | series tag     | agency_name   | Agency Name   | text      | text        |
| Yes      | numeric metric | agency_rate   | Agency Rate   | number    | number      |
| Yes      | numeric metric | tax_code_rate | Tax code Rate | number    | number      |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9sqg-vznj d:2006-01-01T00:00:00.000Z t:tax_code=10001 t:agency=010010000 t:agency_name="COUNTY OF COOK" m:agency_rate=0.5 m:tax_code_rate=5.525

series e:9sqg-vznj d:2006-01-01T00:00:00.000Z t:tax_code=10001 t:agency=010010001 t:agency_name="CONSOLIDATED ELECTIONS" m:agency_rate=0 m:tax_code_rate=5.525

series e:9sqg-vznj d:2006-01-01T00:00:00.000Z t:tax_code=10001 t:agency=010020000 t:agency_name="FOREST PRESERVE DISTRICT OF COOK COUNTY" m:agency_rate=0.057 m:tax_code_rate=5.525
```

## Meta Commands

```ls
metric m:agency_rate p:float l:"Agency Rate" t:dataTypeName=number

metric m:tax_code_rate p:float l:"Tax code Rate" t:dataTypeName=number

entity e:9sqg-vznj l:"Cook County Clerk - Tax codes, agencies, and rates" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/9sqg-vznj

property e:9sqg-vznj t:meta.view v:id=9sqg-vznj v:category="Property & Taxation" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Cook County Clerk - Tax codes, agencies, and rates" v:attribution="Cook County Clerk"

property e:9sqg-vznj t:meta.view.license v:name="Public Domain"

property e:9sqg-vznj t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:9sqg-vznj t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| tax_year | tax_code | agency    | agency_name                             | agency_rate | tax_code_rate | 
| ======== | ======== | ========= | ======================================= | =========== | ============= | 
| 2006     | 10001    | 010010000 | COUNTY OF COOK                          | 0.500       | 5.525         | 
| 2006     | 10001    | 010010001 | CONSOLIDATED ELECTIONS                  | 0.000       | 5.525         | 
| 2006     | 10001    | 010020000 | FOREST PRESERVE DISTRICT OF COOK COUNTY | 0.057       | 5.525         | 
| 2006     | 10001    | 020010000 | TOWN BARRINGTON                         | 0.025       | 5.525         | 
| 2006     | 10001    | 020010002 | GENERAL ASSISTANCE BARRINGTON           | 0.002       | 5.525         | 
| 2006     | 10001    | 020010003 | ROAD AND BRIDGE BARRINGTON              | 0.000       | 5.525         | 
| 2006     | 10001    | 043060000 | HARPER COMMUNITY COLLEGE DISTRICT 512   | 0.288       | 5.525         | 
| 2006     | 10001    | 044030000 | COMMUNITY UNIT SCHOOL DISTRICT 220      | 3.460       | 5.525         | 
| 2006     | 10001    | 044030010 | LAKE CO TAX OBJ CT ORD-220              | 0.065       | 5.525         | 
| 2006     | 10001    | 050040000 | BARRINGTON PARK DISTRICT                | 0.554       | 5.525         | 
```