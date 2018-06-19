# DBEDT Hawaii Nominal Gross Domestic Product 2000-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-nominal-gross-domestic-product-2000-2010-59862) |
| Metadata | [Link](https://data.hawaii.gov/api/views/s3qd-f86n) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/s3qd-f86n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/s3qd-f86n/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | s3qd-f86n |
| Name | DBEDT Hawaii Nominal Gross Domestic Product 2000-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | product |
| Created | 2012-08-28T19:49:41Z |
| Publication Date | 2012-08-29T01:30:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | numeric metric | x_values               | X Values               | number    | number      |
| Yes      | numeric metric | growth                 | % Growth               | percent   | percent     |
| Yes      | numeric metric | gross_domestic_product | Gross Domestic Product | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s3qd-f86n d:2000-01-01T00:00:00.000Z m:gross_domestic_product=41372 m:x_values=2000 m:growth=5.5

series e:s3qd-f86n d:2000-01-01T00:00:00.000Z m:gross_domestic_product=42401 m:x_values=2001 m:growth=2.5

series e:s3qd-f86n d:2000-01-01T00:00:00.000Z m:gross_domestic_product=44716 m:x_values=2002 m:growth=5.5
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:growth p:float l:"% Growth" t:dataTypeName=percent

metric m:gross_domestic_product p:integer l:"Gross Domestic Product" t:dataTypeName=number

entity e:s3qd-f86n l:"DBEDT Hawaii Nominal Gross Domestic Product 2000-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/s3qd-f86n

property e:s3qd-f86n t:meta.view v:id=s3qd-f86n v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Nominal Gross Domestic Product 2000-2010" v:attribution="Department of Economic Development and Tourism"

property e:s3qd-f86n t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:s3qd-f86n t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:s3qd-f86n t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | growth | gross_domestic_product | 
| ======== | ====== | ====================== | 
| 2000     | 5.5    | 41372                  | 
| 2001     | 2.5    | 42401                  | 
| 2002     | 5.5    | 44716                  | 
| 2003     | 7.1    | 47908                  | 
| 2004     | 8.9    | 52185                  | 
| 2005     | 9.0    | 56869                  | 
| 2006     | 7.6    | 61194                  | 
| 2007     | 4.9    | 64212                  | 
| 2008     | 3.0    | 66119                  | 
| 2009     | -1.0   | 65428                  | 
```