# Austin Energy Customer Data by Customer Class 2006 - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-customer-data-by-customer-class) |
| Metadata | [Link](https://data.austintexas.gov/api/views/9xdm-yhmb) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/9xdm-yhmb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/9xdm-yhmb/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 9xdm-yhmb |
| Name | Austin Energy Customer Data by Customer Class 2006 - 2014 |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | residential, industrial, commercial, "percentage of revenue", kwh, "cents per kwh", "percentage of mwh", mwh, "number of customers" |
| Created | 2015-08-18T18:33:48Z |
| Publication Date | 2016-09-22T14:25:34Z |

## Description

Austin Energy has four main customer classes: residential, commercial, industrial, and other. 

Residential customers live in single-family dwellings, mobile homes, townhouses, or individually metered apartment units. 

The majority of commercial customers are small to large businesses that fall under Austin Energy’s secondary level of service. This means Austin Energy owns, operates, and maintains the equipment (wires, transformers, etc.) supplying power to those facilities. 

Industrial (Primary) customers take service at high voltage (12,500 volts or higher) and own, operate and maintain their own equipment. Consequently, Austin Energy experiences lower overall system losses and it costs less to serve these customers. Large commercial and industrial customers such as semiconductors, high-tech facilities, and data centers typically fall under the primary level of service. These customers have very high usage and load factors because they tend to operate 24/7. 

The final class, other, typically refers to street lighting and facilities such as ballparks.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | customer_class        | Customer Class        | text      | text        |
| Yes      | time           | fiscal_year           | Fiscal Year           | number    | number      |
| Yes      | numeric metric | number_of_customers   | Number of Customers   | number    | number      |
| Yes      | numeric metric | revenue               | Revenue               | money     | money       |
| Yes      | numeric metric | percentage_of_revenue | Percentage of Revenue | percent   | percent     |
| Yes      | numeric metric | cents_per_kwh         | Cents per kWh         | number    | number      |
| Yes      | numeric metric | percentage_of_mwh     | Percentage of MWh     | percent   | percent     |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9xdm-yhmb d:2006-01-01T00:00:00.000Z t:customer_class=Residential m:cents_per_kwh=9.499 m:percentage_of_mwh=36 m:percentage_of_revenue=41 m:number_of_customers=338184 m:revenue=387540000

series e:9xdm-yhmb d:2007-01-01T00:00:00.000Z t:customer_class=Residential m:cents_per_kwh=9.112 m:percentage_of_mwh=35 m:percentage_of_revenue=39 m:number_of_customers=345197 m:revenue=356143000

series e:9xdm-yhmb d:2008-01-01T00:00:00.000Z t:customer_class=Residential m:cents_per_kwh=9.863 m:percentage_of_mwh=35 m:percentage_of_revenue=39 m:number_of_customers=352574 m:revenue=416809000
```

## Meta Commands

```ls
metric m:number_of_customers p:integer l:"Number of Customers" t:dataTypeName=number

metric m:revenue p:double l:Revenue t:dataTypeName=money

metric m:percentage_of_revenue p:float l:"Percentage of Revenue" t:dataTypeName=percent

metric m:cents_per_kwh p:float l:"Cents per kWh" t:dataTypeName=number

metric m:percentage_of_mwh p:float l:"Percentage of MWh" t:dataTypeName=percent

entity e:9xdm-yhmb l:"Austin Energy Customer Data by Customer Class 2006 - 2014" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/9xdm-yhmb

property e:9xdm-yhmb t:meta.view v:id=9xdm-yhmb v:category=Utility v:averageRating=0 v:name="Austin Energy Customer Data by Customer Class 2006 - 2014" v:attribution="Austin Energy"

property e:9xdm-yhmb t:meta.view.license v:name="Public Domain"

property e:9xdm-yhmb t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:9xdm-yhmb t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| customer_class | fiscal_year | number_of_customers | revenue      | percentage_of_revenue | cents_per_kwh      | percentage_of_mwh | 
| ============== | =========== | =================== | ============ | ===================== | ================== | ================= | 
| Residential    | 2006        | 338184              | 387540000.00 | 41.00                 | 9.4990000000000006 | 36.00             | 
| Residential    | 2007        | 345197              | 356143000.00 | 39.00                 | 9.1120000000000001 | 35.00             | 
| Residential    | 2008        | 352574              | 416809000.00 | 39.00                 | 9.8629999999999995 | 35.00             | 
| Residential    | 2009        | 363217              | 406393000.00 | 39.00                 | 9.6329999999999991 | 35.00             | 
| Residential    | 2010        | 368700              | 407074000.00 | 39.00                 | 9.6039999999999992 | 35.00             | 
| Residential    | 2011        | 372329              | 457262000.00 | 40.00                 | 10.023999999999999 | 36.00             | 
| Residential    | 2012        | 376614              | 422195183.00 | 39.00                 | 9.6370000000000005 | 34.00             | 
| Residential    | 2013        | 383257              | 458657021.00 | 39.00                 | 11.019             | 34.00             | 
| Residential    | 2014        | 391410              | 487165010.00 | 38.91                 | 11.334             | 30.76             | 
| Commercial     | 2006        | 40934               | 367017000.00 | 39.00                 | 8.5609999999999999 | 38.00             | 
```