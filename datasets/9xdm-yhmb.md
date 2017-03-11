# Austin Energy Customer Data by Customer Class 2006 - 2014

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/9xdm-yhmb/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/austin-energy-customer-data-by-customer-class)
* Id = 9xdm-yhmb
* Name = Austin Energy Customer Data by Customer Class 2006 - 2014
* Attribution = Austin Energy
* Category = Utility
* Tags = [residential, industrial, commercial, "percentage of revenue", kwh, "cents per kwh", "percentage of mwh", mwh, "number of customers"]
* Created = 2015-08-18T18:33:48Z
* Publication Date = 2016-09-22T14:25:34Z
* Rows Updated = 2016-09-22T14:25:07Z

## Description

Austin Energy has four main customer classes: residential, commercial, industrial, and other. 

Residential customers live in single-family dwellings, mobile homes, townhouses, or individually metered apartment units. 

The majority of commercial customers are small to large businesses that fall under Austin Energy?s secondary level of service. This means Austin Energy owns, operates, and maintains the equipment (wires, transformers, etc.) supplying power to those facilities. 

Industrial (Primary) customers take service at high voltage (12,500 volts or higher) and own, operate and maintain their own equipment. Consequently, Austin Energy experiences lower overall system losses and it costs less to serve these customers. Large commercial and industrial customers such as semiconductors, high-tech facilities, and data centers typically fall under the primary level of service. These customers have very high usage and load factors because they tend to operate 24/7. 

The final class, other, typically refers to street lighting and facilities such as ballparks.

## Columns

```ls
| Name                  | Field Name            | Data Type | Render Type | Schema Type    | Included | 
| ===================== | ===================== | ========= | =========== | ============== | ======== | 
| Customer Class        | customer_class        | text      | text        | series tag     | Yes      | 
| Fiscal Year           | fiscal_year           | number    | number      | time           | Yes      | 
| Number of Customers   | number_of_customers   | number    | number      | numeric metric | Yes      | 
| Revenue               | revenue               | money     | money       | numeric metric | Yes      | 
| Percentage of Revenue | percentage_of_revenue | percent   | percent     | numeric metric | Yes      | 
| Cents per kWh         | cents_per_kwh         | number    | number      | numeric metric | Yes      | 
| Percentage of MWh     | percentage_of_mwh     | percent   | percent     | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

metric m:cents_per_kwh l:"Cents per kWh" t:dataTypeName=number

entity e:9xdm-yhmb l:"Austin Energy Customer Data by Customer Class 2006 - 2014" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/9xdm-yhmb

property e:9xdm-yhmb t:meta.view d:2017-03-03T14:12:41.663Z v:id=9xdm-yhmb v:category=Utility v:averageRating=0 v:name="Austin Energy Customer Data by Customer Class 2006 - 2014" v:attribution="Austin Energy"

property e:9xdm-yhmb t:meta.view.license d:2017-03-03T14:12:41.663Z v:name="Public Domain"

property e:9xdm-yhmb t:meta.view.owner d:2017-03-03T14:12:41.663Z v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"

property e:9xdm-yhmb t:meta.view.tableauthor d:2017-03-03T14:12:41.663Z v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```