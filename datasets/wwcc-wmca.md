# Plant Nurseries 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plant-nurseries-2013-61ed1) |
| Metadata | [Link](https://data.maryland.gov/api/views/wwcc-wmca) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/wwcc-wmca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/wwcc-wmca/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | wwcc-wmca |
| Name | Plant Nurseries 2013 |
| Attribution | MD Department of Agriculture |
| Category | Agriculture |
| Tags | plants, flowers, nurseries, landscaping |
| Created | 2013-10-01T13:22:45Z |
| Publication Date | 2013-10-25T19:16:30Z |

## Description

Plant nurseries in Maryland

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | series tag  | company         | COMPANY         | text      | text        |
| Yes      | series tag  | county          | COUNTY          | text      | text        |
| Yes      | series tag  | phone1          | PHONE1          | phone     | phone       |
| Yes      | series tag  | phone2          | PHONE2          | phone     | phone       |
| Yes      | series tag  | business_type   | BUSINESS TYPE   | text      | text        |
| Yes      | series tag  | product_code    | PRODUCT CODE    | text      | text        |
| Yes      | series tag  | sales_structure | SALES STRUCTURE | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wwcc-wmca d:2013-01-01T00:00:00.000Z t:phone_number=3018545620 t:county=HOWARD t:product_code=7 t:company="CAPITOL CITY CONTRACTORS" t:business_type=A,D t:sales_structure=I m:row_number.wwcc-wmca=1

series e:wwcc-wmca d:2013-01-01T00:00:00.000Z t:phone_number=4107556331 t:county=CECIL t:product_code=7,8, t:company="HOPEWELL NURSERY, INC." t:business_type=A t:sales_structure=I m:row_number.wwcc-wmca=2

series e:wwcc-wmca d:2013-01-01T00:00:00.000Z t:phone_number=3018881890 t:county=CHARLES t:product_code=9 t:company="CELESTIAL GARDENS & NURSERIES, INC." t:business_type=E t:sales_structure=IV m:row_number.wwcc-wmca=3
```

## Meta Commands

```ls
metric m:row_number.wwcc-wmca p:long l:"Row Number"

entity e:wwcc-wmca l:"Plant Nurseries 2013" t:attribution="MD Department of Agriculture" t:url=https://data.maryland.gov/api/views/wwcc-wmca

property e:wwcc-wmca t:meta.view v:id=wwcc-wmca v:category=Agriculture v:attributionLink=http://www.mda.maryland.gov v:averageRating=0 v:name="Plant Nurseries 2013" v:attribution="MD Department of Agriculture"

property e:wwcc-wmca t:meta.view.owner v:id=tpc4-inqc v:screenName="Lisa Stollof" v:displayName="Lisa Stollof"

property e:wwcc-wmca t:meta.view.tableauthor v:id=tpc4-inqc v:screenName="Lisa Stollof" v:roleName=editor v:displayName="Lisa Stollof"
```

## Top Records

```ls
| company                                | county       | phone1             | phone2             | business_type | product_code | sales_structure | 
| ====================================== | ============ | ================== | ================== | ============= | ============ | =============== | 
| CAPITOL CITY CONTRACTORS               | HOWARD       | [3018545620, null] | [null, null]       | A,D           | 7            | I               | 
| HOPEWELL NURSERY, INC.                 | CECIL        | [4107556330, null] | [4107556331, null] | A             | 7,8,         | I               | 
| CELESTIAL GARDENS & NURSERIES, INC.    | CHARLES      | [3018881890, null] | [null, null]       | E             | 9            | IV              | 
| RANDY G. CHANGURIS                     | WASHINGTON   | [3014326347, null] | [null, null]       | B             | 1            | III             | 
| WESTMINSTER WHOLESALE NURSERIES, LLC   | CARROLL      | [null, null]       | [null, null]       | A             | 7            | I               | 
| MURPHY JOHN'S, INC.                    | QUEEN ANNE'S | [4109283029, null] | [null, null]       | E             | 1            | I               | 
| TREE CENTER, INC.                      | HOWARD       | [4104421041, null] | [4104421223, null] | A             | 7            | I               | 
| OLNEY GARDENS WHOLESALE, LLC           | MONTGOMERY   | [3012601024, null] | [3012601025, null] | A,B,C         | 7            | II              | 
| SIGNATURE HORTICULTURAL SERVICES, INC. | BALTIMORE    | [4103296633, null] | [null, null]       | A,B,C,F       | 8,10         | I               | 
| EMORY KNOLL FARMS                      | HARFORD      | [4104525880, null] | [4104525319, null] | A,B           | 8            | I               | 
```