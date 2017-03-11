# Residential Average Monthly kWh and Bills

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/d9pb-3vh7/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/residential-average-monthly-kwh-and-bills)
* Id = d9pb-3vh7
* Name = Residential Average Monthly kWh and Bills
* Attribution = Austin Energy
* Category = Utility
* Tags = [austin energy, bill, residential bill, kwh, electric bill]
* Created = 2016-05-12T17:09:17Z
* Publication Date = 2016-10-13T21:58:12Z
* Rows Updated = 2016-10-13T21:56:37Z

## Description

Residential customers use an average of about 1,000 kWh of electricity per month, with usage higher during hot summer months and lower in the winter. View tables show monthly average usage in kWh by month for residential customers starting in 2000. Tables include monthly fuel charges and electric bill amounts.

## Columns

```ls
| Name                    | Field Name            | Data Type     | Render Type   | Schema Type    | Included | 
| ======================= | ===================== | ============= | ============= | ============== | ======== | 
| Date                    | year                  | calendar_date | calendar_date | time           | Yes      | 
| Average kWh             | average_kwh           | number        | number        | numeric metric | Yes      | 
| Fuel Charge (Cents/kWh) | fuel_charge_cents_kwh | number        | number        | numeric metric | Yes      | 
| Average Bill            | average_bill          | money         | money         | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
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
series e:d9pb-3vh7 d:2000-01-01T00:00:00.000Z m:average_bill=54.26 m:fuel_charge_cents_kwh=1.372 m:average_kwh=820

series e:d9pb-3vh7 d:2000-02-01T00:00:00.000Z m:average_bill=50.27 m:fuel_charge_cents_kwh=1.372 m:average_kwh=766

series e:d9pb-3vh7 d:2000-03-01T00:00:00.000Z m:average_bill=45.91 m:fuel_charge_cents_kwh=1.372 m:average_kwh=707
```

## Meta Commands

```ls
metric m:average_kwh p:integer l:"Average kWh" t:dataTypeName=number

metric m:fuel_charge_cents_kwh l:"Fuel Charge (Cents/kWh)" t:dataTypeName=number

entity e:d9pb-3vh7 l:"Residential Average Monthly kWh and Bills" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/d9pb-3vh7

property e:d9pb-3vh7 t:meta.view d:2017-03-03T14:06:58.137Z v:id=d9pb-3vh7 v:category=Utility v:averageRating=0 v:name="Residential Average Monthly kWh and Bills" v:attribution="Austin Energy"

property e:d9pb-3vh7 t:meta.view.license d:2017-03-03T14:06:58.137Z v:name="Public Domain"

property e:d9pb-3vh7 t:meta.view.owner d:2017-03-03T14:06:58.137Z v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"

property e:d9pb-3vh7 t:meta.view.tableauthor d:2017-03-03T14:06:58.137Z v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```