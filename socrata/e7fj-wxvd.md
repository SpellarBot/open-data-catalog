# Power Supply Adjustment/Fuel Charge

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/power-supply-adjustment-fuel-charge) |
| Metadata | [Link](https://data.austintexas.gov/api/views/e7fj-wxvd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/e7fj-wxvd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/e7fj-wxvd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | e7fj-wxvd |
| Name | Power Supply Adjustment/Fuel Charge |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | psa, power supply adjustment, fuel charge, austin energy, energy |
| Created | 2015-08-20T14:47:04Z |
| Publication Date | 2016-05-16T21:49:00Z |

## Description

Austin Energy?s Power Supply Adjustment (PSA) and fuel charge are reviewed annually. Generally, changes to the fuel rate are effective on Jan. 1 for the calendar year. Effective FY 2013, the power supply adjustment is set as part of the annual budget process. Fuel Charge rates are established based on the type of electric service required by a customer and fall into one of three levels: secondary, primary or transmission.

Primary Level Customers - This rate is applicable to electric service required by any customer who receives service at 12,500 volts (nominal) to 69,000 volts and whose demand for power does not meet or exceed 3,000 kilowatts at any interval during the most recent June through September billing months as determined by the City of Austin. 

Secondary Level Customers - This rate is applicable to electric service required by residential customers in single-family dwellings, mobile homes, townhouses, or individually metered apartment units. It is also applicable to any business that does not receive power at a primary or transmission level. Currently, some 30,000 businesses receive the secondary Fuel Charge rate.

Transmission Level Customers - This rate is applicable to electric service required by any customer who receives service at 69,000 volts (nominal) or higher. This rate shall be applied for a minimum of one year. 

Primary and transmission voltage level customers (about 90 industrial customers) essentially receive power directly from a substation. This results in reduced line losses between the point of generation and delivery to the customer. These customers also install and maintain their own equipment at their site needed to step down the voltage before the power enters their facility. As a result, primary and transmission customers pay a slightly lower Fuel Charge.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                     | Data Type | Render Type |
| ======== | ============== | ============= | ======================== | ========= | =========== |
| No       |                | calendar_year | Calendar Year            | number    | number      |
| No       |                | month         | Month                    | text      | text        |
| Yes      | numeric metric | system        | System (Cents/kWh)       | number    | number      |
| Yes      | numeric metric | secondary     | Secondary (Cents/kWh)    | number    | number      |
| Yes      | numeric metric | primary       | Primary (Cents/kWh)      | number    | number      |
| Yes      | numeric metric | transmission  | Transmission (Cents/kWh) | number    | number      |
```

## Time Field

```ls
Value = calendar_year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = calendar_year,month
```

## Data Commands

```ls
series e:e7fj-wxvd d:2013-11-01T00:00:00.000Z m:system=3.691 m:primary=3.625 m:secondary=3.709 m:transmission=3.579

series e:e7fj-wxvd d:2012-10-01T00:00:00.000Z m:system=3.356 m:primary=3.296 m:secondary=3.372 m:transmission=3.254

series e:e7fj-wxvd d:2012-01-01T00:00:00.000Z m:system=3.598 m:primary=3.508 m:secondary=3.615 m:transmission=3.471
```

## Meta Commands

```ls
metric m:system p:float l:"System (Cents/kWh)" t:dataTypeName=number

metric m:secondary p:float l:"Secondary (Cents/kWh)" t:dataTypeName=number

metric m:primary p:float l:"Primary (Cents/kWh)" t:dataTypeName=number

metric m:transmission p:float l:"Transmission (Cents/kWh)" t:dataTypeName=number

entity e:e7fj-wxvd l:"Power Supply Adjustment/Fuel Charge" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/e7fj-wxvd

property e:e7fj-wxvd t:meta.view v:id=e7fj-wxvd v:category=Utility v:averageRating=0 v:name="Power Supply Adjustment/Fuel Charge" v:attribution="Austin Energy"

property e:e7fj-wxvd t:meta.view.license v:name="Public Domain"

property e:e7fj-wxvd t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:e7fj-wxvd t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| calendar_year | month    | system | secondary | primary | transmission | 
| ============= | ======== | ====== | ========= | ======= | ============ | 
| 2013          | November | 3.691  | 3.709     | 3.625   | 3.579        | 
| 2012          | October  | 3.356  | 3.372     | 3.296   | 3.254        | 
| 2012          | January  | 3.598  | 3.615     | 3.508   | 3.471        | 
| 2011          | January  | 3.09   | 3.105     | 3.012   | 2.981        | 
| 2010          | January  | 3.635  | 3.653     | 3.544   | 3.507        | 
| 2009          | January  | 3.635  | 3.653     | 3.544   | 3.507        | 
| 2008          | January  | 3.635  | 3.653     | 3.544   | 3.507        | 
| 2007          | June     | 3.029  | 3.044     | 2.953   | 2.922        | 
| 2007          | January  | 3.327  | 3.343     | 3.244   | 3.21         | 
| 2006          | January  | 3.617  | 3.634     | 3.526   | 3.489        | 
```