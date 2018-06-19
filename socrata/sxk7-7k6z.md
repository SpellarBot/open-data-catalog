# Austin Water - Residential Water Consumption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-residential-water-consumption) |
| Metadata | [Link](https://data.austintexas.gov/api/views/sxk7-7k6z) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/sxk7-7k6z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/sxk7-7k6z/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | sxk7-7k6z |
| Name | Austin Water - Residential Water Consumption |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, consumption, residential |
| Created | 2015-08-31T18:23:56Z |
| Publication Date | 2016-11-18T14:17:45Z |

## Description

Monthly residential water consumption grouped by zip code and customer class.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | numeric metric | year_month     | Year Month     | number    | text        |
| Yes      | series tag     | postal_code    | Postal Code    | text      | text        |
| Yes      | series tag     | customer_class | Customer Class | text      | text        |
| Yes      | numeric metric | total_gallons  | Total Gallons  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sxk7-7k6z d:2016-11-18T14:17:30.000Z t:customer_class=Multi-Family t:postal_code=78613 m:year_month=201201 m:total_gallons=23000

series e:sxk7-7k6z d:2016-11-18T14:17:30.000Z t:customer_class="Irrigation - Multi-Family" t:postal_code=78613 m:year_month=201201 m:total_gallons=11000

series e:sxk7-7k6z d:2016-11-18T14:17:30.000Z t:customer_class=Multi-Family t:postal_code=78617 m:year_month=201201 m:total_gallons=2477000
```

## Meta Commands

```ls
metric m:year_month p:integer l:"Year Month" t:dataTypeName=number

metric m:total_gallons p:double l:"Total Gallons" t:dataTypeName=number

entity e:sxk7-7k6z l:"Austin Water - Residential Water Consumption" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/sxk7-7k6z

property e:sxk7-7k6z t:meta.view v:id=sxk7-7k6z v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Residential Water Consumption" v:attribution="Austin Water"

property e:sxk7-7k6z t:meta.view.license v:name="Public Domain"

property e:sxk7-7k6z t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:sxk7-7k6z t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | year_month | postal_code | customer_class            | total_gallons   | 
| =========== | ========== | =========== | ========================= | =============== | 
| 1479478650  | 201201     | 78613       | Multi-Family              | 23000.000000    | 
| 1479478650  | 201201     | 78613       | Irrigation - Multi-Family | 11000.000000    | 
| 1479478650  | 201201     | 78617       | Multi-Family              | 2477000.000000  | 
| 1479478650  | 201201     | 78617       | Residential               | 19955700.000000 | 
| 1479478650  | 201201     | 78652       | Irrigation - Residential  | 38500.000000    | 
| 1479478650  | 201201     | 78652       | Residential               | 632300.000000   | 
| 1479478650  | 201201     | 78652       | Multi-Family              | 116900.000000   | 
| 1479478650  | 201201     | 78653       | Multi-Family              | 194500.000000   | 
| 1479478650  | 201201     | 78653       | Residential               | 3836200.000000  | 
| 1479478650  | 201201     | 78660       | Residential               | 7226400.000000  | 
```