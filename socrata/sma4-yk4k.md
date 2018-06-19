# King County Commodities Buyers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-commodities-buyers) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/sma4-yk4k) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/sma4-yk4k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/sma4-yk4k/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | sma4-yk4k |
| Name | King County Commodities Buyers |
| Attribution | King County Procurement and Payables |
| Category | Business |
| Tags | procurement |
| Created | 2016-09-09T17:23:49Z |
| Publication Date | 2017-03-27T23:27:17Z |

## Description

Look up King County employees in charge of buying certain commodities and services.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | commodity   | Commodity  | text      | text        |
| Yes      | series tag  | buyer       | Buyer      | text      | text        |
| Yes      | series tag  | title       | Title      | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | email       | Email      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sma4-yk4k d:2016-09-09T17:23:50.000Z t:phone="(206) 263-9306" t:title="Lead Senior Buyer" t:commodity="Property Management" t:email=amon.billups@kingcounty.gov t:buyer="Amon Billups" m:row_number.sma4-yk4k=1

series e:sma4-yk4k d:2016-09-09T17:23:50.000Z t:phone="(206) 263-9306" t:title="Lead Senior Buyer" t:commodity="Office Spaces" t:email=amon.billups@kingcounty.gov t:buyer="Amon Billups" m:row_number.sma4-yk4k=2

series e:sma4-yk4k d:2016-09-09T17:23:50.000Z t:phone="(206) 263-9306" t:title="Lead Senior Buyer" t:commodity="Temporary Personnel" t:email=amon.billups@kingcounty.gov t:buyer="Amon Billups" m:row_number.sma4-yk4k=3
```

## Meta Commands

```ls
metric m:row_number.sma4-yk4k p:long l:"Row Number"

entity e:sma4-yk4k l:"King County Commodities Buyers" t:attribution="King County Procurement and Payables" t:url=https://data.kingcounty.gov/api/views/sma4-yk4k

property e:sma4-yk4k t:meta.view v:id=sma4-yk4k v:category=Business v:averageRating=0 v:name="King County Commodities Buyers" v:attribution="King County Procurement and Payables"

property e:sma4-yk4k t:meta.view.owner v:id=vni2-xngb v:screenName=pryorli v:displayName=pryorli

property e:sma4-yk4k t:meta.view.tableauthor v:id=vni2-xngb v:screenName=pryorli v:displayName=pryorli
```

## Top Records

```ls
| :updated_at | commodity                                  | buyer        | title             | phone          | email                       | 
| =========== | ========================================== | ============ | ================= | ============== | =========================== | 
| 1473441830  | Property Management                        | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Office Spaces                              | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Temporary Personnel                        | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Contract Workers                           | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Administrative Temps                       | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Medical Temps                              | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Dental Temps                               | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Professional Temps                         | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Industrial Machinery                       | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
| 1473441830  | Boiler Equipment, Supplies and Maintenance | Amon Billups | Lead Senior Buyer | (206) 263-9306 | amon.billups@kingcounty.gov | 
```