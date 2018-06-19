# City Tax Revenue Financial Plan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-tax-revenue-financial-plan-20ae2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ye26-g8nx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ye26-g8nx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ye26-g8nx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ye26-g8nx |
| Name | City Tax Revenue Financial Plan |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | revenue, tax, financial plan, city tax, property tax |
| Created | 2013-02-13T21:36:59Z |
| Publication Date | 2013-06-26T17:10:11Z |

## Description

The table presents records of the source for City Tax Revenue generated from the year 2013 thro 2017.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | tax_type_year                | Year \ Tax Type              | text      | text        |
| Yes      | numeric metric | property_tax                 | Property Tax                 | number    | number      |
| Yes      | numeric metric | economically_sensitive_taxes | Economically Sensitive Taxes | number    | number      |
| Yes      | numeric metric | non_tax_revenue              | Non-Tax Revenue              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ye26-g8nx d:2013-02-13T13:37:01.000Z t:tax_type_year="FY 2012 ($ in Millions)" m:property_tax=17945 m:economically_sensitive_taxes=24166 m:non_tax_revenue=5438

series e:ye26-g8nx d:2013-02-13T13:37:01.000Z t:tax_type_year="FY 2013f ($ in Millions)" m:property_tax=18440 m:economically_sensitive_taxes=25631 m:non_tax_revenue=4794

series e:ye26-g8nx d:2013-02-13T13:37:01.000Z t:tax_type_year="FY 2014f ($ in Millions)" m:property_tax=19365 m:economically_sensitive_taxes=26077 m:non_tax_revenue=5252
```

## Meta Commands

```ls
metric m:property_tax p:integer l:"Property Tax" t:dataTypeName=number

metric m:economically_sensitive_taxes p:integer l:"Economically Sensitive Taxes" t:dataTypeName=number

metric m:non_tax_revenue p:integer l:"Non-Tax Revenue" t:dataTypeName=number

entity e:ye26-g8nx l:"City Tax Revenue Financial Plan" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/ye26-g8nx

property e:ye26-g8nx t:meta.view v:id=ye26-g8nx v:category="City Government" v:attributionLink=http://www.nyc.gov/html/omb/downloads/pdf/sum1_13.pdf v:averageRating=0 v:name="City Tax Revenue Financial Plan" v:attribution="Office of the Mayor (OTM)"

property e:ye26-g8nx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ye26-g8nx t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | tax_type_year            | property_tax | economically_sensitive_taxes | non_tax_revenue | 
| =========== | ======================== | ============ | ============================ | =============== | 
| 1360762621  | FY 2012 ($ in Millions)  | 17945        | 24166                        | 5438            | 
| 1360762621  | FY 2013f ($ in Millions) | 18440        | 25631                        | 4794            | 
| 1360762621  | FY 2014f ($ in Millions) | 19365        | 26077                        | 5252            | 
| 1360762621  | FY 2015f ($ in Millions) | 20176        | 27348                        | 5132            | 
| 1360762621  | FY 2016f ($ in Millions) | 21105        | 28428                        | 5084            | 
| 1360762621  | FY 2017f ($ in Millions) | 21870        | 29724                        | 4830            | 
```