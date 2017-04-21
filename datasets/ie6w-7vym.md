# DNR Fishing License Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dnr-fishing-license-sales-9c2f0) |
| Metadata | [Link](https://data.illinois.gov/api/views/ie6w-7vym) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ie6w-7vym/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ie6w-7vym/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ie6w-7vym |
| Name | DNR Fishing License Sales |
| Attribution | IDNR |
| Category | Recreation |
| Tags | fishing, license, sales, county |
| Created | 2012-01-26T20:46:47Z |
| Publication Date | 2012-01-26T20:50:09Z |

## Description

Fishing License sales from Illinois Department of Natural Resources by County

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | txnl_licn_year | TXNL_LICN_YEAR | text      | text        |
| Yes      | series tag  | county         | COUNTY         | text      | text        |
| Yes      | series tag  | license        | License        | text      | text        |
| Yes      | series tag  | number_sold    | Number Sold    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ie6w-7vym d:2012-01-26T12:46:59.000Z t:county=COUNTY t:number_sold="Number Sold" t:txnl_licn_year=TXNL_LICN_YEAR t:license=License m:row_number.ie6w-7vym=1

series e:ie6w-7vym d:2012-01-26T12:46:59.000Z t:county=ADAMS t:number_sold=3570 t:txnl_licn_year=2006 t:license="INLAND TROUT STAMP" m:row_number.ie6w-7vym=2

series e:ie6w-7vym d:2012-01-26T12:46:59.000Z t:county=ADAMS t:number_sold=4144 t:txnl_licn_year=2007 t:license="INLAND TROUT STAMP" m:row_number.ie6w-7vym=3
```

## Meta Commands

```ls
metric m:row_number.ie6w-7vym p:long l:"Row Number"

entity e:ie6w-7vym l:"DNR Fishing License Sales" t:attribution=IDNR t:url=https://data.illinois.gov/api/views/ie6w-7vym

property e:ie6w-7vym t:meta.view v:id=ie6w-7vym v:category=Recreation v:averageRating=0 v:name="DNR Fishing License Sales" v:attribution=IDNR

property e:ie6w-7vym t:meta.view.license v:name="Public Domain"

property e:ie6w-7vym t:meta.view.owner v:id=dzgj-hnvs v:screenName=Chris.Hill@illinois.gov v:displayName=Chris.Hill@illinois.gov

property e:ie6w-7vym t:meta.view.tableauthor v:id=dzgj-hnvs v:screenName=Chris.Hill@illinois.gov v:roleName=publisher v:displayName=Chris.Hill@illinois.gov
```

## Top Records

```ls
| :updated_at | txnl_licn_year | county | license                    | number_sold | 
| =========== | ============== | ====== | ========================== | =========== | 
| 1327582019  | TXNL_LICN_YEAR | COUNTY | License                    | Number Sold | 
| 1327582019  | 2006           | ADAMS  | INLAND TROUT STAMP         | 3570        | 
| 1327582019  | 2007           | ADAMS  | INLAND TROUT STAMP         | 4144        | 
| 1327582019  | 2008           | ADAMS  | INLAND TROUT STAMP         | 4312        | 
| 1327582019  | 2009           | ADAMS  | INLAND TROUT STAMP         | 4557        | 
| 1327582019  | 2010           | ADAMS  | INLAND TROUT STAMP         | 4452        | 
| 1327582019  | 2011           | ADAMS  | INLAND TROUT STAMP         | 3815        | 
| 1327582019  | 2006           | ADAMS  | LAKE MICHIGAN SALMON STAMP | 35          | 
| 1327582019  | 2007           | ADAMS  | LAKE MICHIGAN SALMON STAMP | 63          | 
| 1327582019  | 2008           | ADAMS  | LAKE MICHIGAN SALMON STAMP | 28          | 
```