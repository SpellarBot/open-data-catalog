# Sales and Use Tax per Town by NAICS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sales-and-use-tax-per-town-by-naics-2013-and-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/rkm7-uwkb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rkm7-uwkb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rkm7-uwkb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rkm7-uwkb |
| Name | Sales and Use Tax per Town by NAICS |
| Attribution | Department of Revenue Services |
| Category | Government |
| Tags | tax, sales, towns, naics, sales tax |
| Created | 2015-07-15T18:39:10Z |
| Publication Date | 2017-02-16T14:20:23Z |

## Description

Sales and use tax data, by quarter, by town, disaggreagted by North America Industrial Classification (NAICS) groups.  The data available is unique to each municipality as detailed NAICS information is only provided where there are ten or more taxpayers in a given category.  This data will be updated annually so that all four quarters of a calendar year are available at once.  This list reflects the tax collected at the 6.35%, 7% and 7.75% rates, where applicable

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                   | Data Type | Render Type |
| ======== | ============== | ===================== | ====================== | ========= | =========== |
| Yes      | time           | calendar_year         | Calendar Year          | number    | number      |
| No       |                | periods_ending        | Periods Ending         | text      | text        |
| Yes      | series tag     | municipality          | Municipality           | text      | text        |
| Yes      | series tag     | naics_industry_code   | NAICS Industry Code    | text      | text        |
| Yes      | numeric metric | taxpayer_count        | Taxpayer Count         | number    | number      |
| Yes      | numeric metric | retail_sales_of_goods | Retail Sales of Goods  | number    | number      |
| Yes      | numeric metric | total_tax_due_at_6_35 | Total Tax Due at 6.35% | number    | number      |
| Yes      | numeric metric | total_tax_due_at_7    | Total Tax Due at 7%    | number    | number      |
| Yes      | numeric metric | total_tax_due_at_7_75 | Total Tax Due at 7.75% | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = periods_ending
```

## Data Commands

```ls
series e:rkm7-uwkb d:2014-01-01T00:00:00.000Z t:naics_industry_code="510 Information" t:municipality="OUT OF COUNTRY" m:taxpayer_count=14 m:retail_sales_of_goods=196658 m:total_tax_due_at_7=0 m:total_tax_due_at_6_35=24874.35

series e:rkm7-uwkb d:2014-01-01T00:00:00.000Z t:naics_industry_code="540 Professional, Scientific and Technical Services" t:municipality="OUT OF COUNTRY" m:taxpayer_count=33 m:retail_sales_of_goods=691364 m:total_tax_due_at_7=265.09 m:total_tax_due_at_6_35=35848.04

series e:rkm7-uwkb d:2014-01-01T00:00:00.000Z t:naics_industry_code="All NAICS Codes" t:municipality="OUT OF COUNTRY" m:taxpayer_count=235 m:retail_sales_of_goods=10049848 m:total_tax_due_at_7=265.09 m:total_tax_due_at_6_35=393222.99
```

## Meta Commands

```ls
metric m:taxpayer_count p:integer l:"Taxpayer Count" t:dataTypeName=number

metric m:retail_sales_of_goods p:double l:"Retail Sales of Goods" t:dataTypeName=number

metric m:total_tax_due_at_6_35 p:double l:"Total Tax Due at 6.35%" t:dataTypeName=number

metric m:total_tax_due_at_7 p:double l:"Total Tax Due at 7%" t:dataTypeName=number

metric m:total_tax_due_at_7_75 p:double l:"Total Tax Due at 7.75%" d:"Tax Due at 7.75% Rate" t:dataTypeName=number

entity e:rkm7-uwkb l:"Sales and Use Tax per Town by NAICS" t:attribution="Department of Revenue Services" t:url=https://data.ct.gov/api/views/rkm7-uwkb

property e:rkm7-uwkb t:meta.view v:id=rkm7-uwkb v:category=Government v:attributionLink="http://www.ct.gov/drs/cwp/view.asp?a=4128&q=483506" v:averageRating=0 v:name="Sales and Use Tax per Town by NAICS" v:attribution="Department of Revenue Services"

property e:rkm7-uwkb t:meta.view.license v:name="Public Domain"

property e:rkm7-uwkb t:meta.view.owner v:id=cfih-kat9 v:screenName="Mike Galliher" v:displayName="Mike Galliher"

property e:rkm7-uwkb t:meta.view.tableauthor v:id=cfih-kat9 v:screenName="Mike Galliher" v:roleName=editor v:displayName="Mike Galliher"
```

## Top Records

```ls
| calendar_year | periods_ending         | municipality   | naics_industry_code                                 | taxpayer_count | retail_sales_of_goods | total_tax_due_at_6_35 | total_tax_due_at_7 | total_tax_due_at_7_75 | 
| ============= | ====================== | ============== | =================================================== | ============== | ===================== | ===================== | ================== | ===================== | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF COUNTRY | 510 Information                                     | 14             | 196658.00             | 24874.35              | 0.00               |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF COUNTRY | 540 Professional, Scientific and Technical Services | 33             | 691364.00             | 35848.04              | 265.09             |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF COUNTRY | All NAICS Codes                                     | 235            | 10049848.00           | 393222.99             | 265.09             |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF COUNTRY | All Other Businesses                                | 13             | 12932.00              | 784.86                | 0.00               |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF STATE   | 110 Agriculture, Forestry, Fishing and Hunting      | 66             | 1795488.43            | 122390.56             | 0.00               |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF STATE   | 220 Utilities                                       | 122            | 209639792.00          | 5627577.26            | 0.00               |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF STATE   | 230 Construction                                    | 3000           | 102559478.05          | 4407717.02            | 28047.32           |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF STATE   | 310 Manufacturing                                   | 4875           | 776751556.06          | 19276727.01           | 39410.42           |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF STATE   | 420 Wholesale Trade                                 | 3317           | 1134914528.92         | 20679051.65           | 97495.86           |                       | 
| 2014          | Quarter 1 - JAN to MAR | OUT OF STATE   | 441 Motor vehicle and parts dealers                 | 153            | 88345485.00           | 3303254.70            | 240457.84          |                       | 
```