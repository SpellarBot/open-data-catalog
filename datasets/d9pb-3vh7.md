# Residential Average Monthly kWh and Bills

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-average-monthly-kwh-and-bills) |
| Metadata | [Link](https://data.austintexas.gov/api/views/d9pb-3vh7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/d9pb-3vh7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/d9pb-3vh7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | d9pb-3vh7 |
| Name | Residential Average Monthly kWh and Bills |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, bill, residential bill, kwh, electric bill |
| Created | 2016-05-12T17:09:17Z |
| Publication Date | 2016-10-13T21:58:12Z |

## Description

Residential customers use an average of about 1,000 kWh of electricity per month, with usage higher during hot summer months and lower in the winter. View tables show monthly average usage in kWh by month for residential customers starting in 2000. Tables include monthly fuel charges and electric bill amounts.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type     | Render Type   |
| ======== | ============== | ===================== | ======================= | ============= | ============= |
| Yes      | time           | year                  | Date                    | calendar_date | calendar_date |
| Yes      | numeric metric | average_kwh           | Average kWh             | number        | number        |
| Yes      | numeric metric | fuel_charge_cents_kwh | Fuel Charge (Cents/kWh) | number        | number        |
| Yes      | numeric metric | average_bill          | Average Bill            | money         | money         |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
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

metric m:fuel_charge_cents_kwh p:float l:"Fuel Charge (Cents/kWh)" t:dataTypeName=number

metric m:average_bill p:double l:"Average Bill" t:dataTypeName=money

entity e:d9pb-3vh7 l:"Residential Average Monthly kWh and Bills" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/d9pb-3vh7

property e:d9pb-3vh7 t:meta.view d:2017-06-09T13:54:37.979Z v:id=d9pb-3vh7 v:category=Utility v:averageRating=0 v:name="Residential Average Monthly kWh and Bills" v:attribution="Austin Energy"

property e:d9pb-3vh7 t:meta.view.license d:2017-06-09T13:54:37.979Z v:name="Public Domain"

property e:d9pb-3vh7 t:meta.view.owner d:2017-06-09T13:54:37.979Z v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:d9pb-3vh7 t:meta.view.tableauthor d:2017-06-09T13:54:37.979Z v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| year                | average_kwh | fuel_charge_cents_kwh | average_bill | 
| =================== | =========== | ===================== | ============ | 
| 2000-01-01T00:00:00 | 820         | 1.372                 | 54.26        | 
| 2000-02-01T00:00:00 | 766         | 1.372                 | 50.27        | 
| 2000-03-01T00:00:00 | 707         | 1.372                 | 45.91        | 
| 2000-04-01T00:00:00 | 715         | 1.372                 | 46.50        | 
| 2000-05-01T00:00:00 | 838         | 1.372                 | 61.68        | 
| 2000-06-01T00:00:00 | 1221        | 1.372                 | 96.88        | 
| 2000-07-01T00:00:00 | 1442        | 1.372                 | 117.20       | 
| 2000-08-01T00:00:00 | 1493        | 1.635                 | 125.81       | 
| 2000-09-01T00:00:00 | 1368        | 1.635                 | 113.99       | 
| 2000-10-01T00:00:00 | 1029        | 1.635                 | 81.94        | 
```