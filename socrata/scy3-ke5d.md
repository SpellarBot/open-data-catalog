# Austin Energy Rates - Cents per kilowatt hour by customer class

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-rates-cents-per-kilowatt-hour-by-customer-class) |
| Metadata | [Link](https://data.austintexas.gov/api/views/scy3-ke5d) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/scy3-ke5d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/scy3-ke5d/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | scy3-ke5d |
| Name | Austin Energy Rates - Cents per kilowatt hour by customer class |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | utility rates, utility data, austin energy, rates |
| Created | 2016-06-24T19:26:36Z |
| Publication Date | 2016-12-27T14:06:08Z |

## Description

Austin Energy?s rates, revenue and megawatt hour information is listed by customer class. View more information about Austin Energy?s rates here: http://austinenergy.com/wps/portal/ae/rates
Unlike many utilities, the community?s elected officials set Austin Energy?s rates in a public, transparent manner. In 2016, Austin City Council reviewed base electric rates through an in-depth cost of service study and an independent public rate review process. Learn more about the 2016 rate review: http://austinenergy.com/wps/portal/ae/rates/2016-rate-review/2016-rate-review

Austin Energy has four main customer classes: residential, commercial, industrial, and lighting. 

Residential customers live in single-family dwellings, mobile homes, townhouses, or individually metered apartment units. 

The majority of commercial customers are small to large businesses that fall under Austin Energy?s secondary level of service. This means Austin Energy owns, operates, and maintains the equipment (wires, transformers, etc.) supplying power to those facilities. 

Industrial customers such as semiconductor and other high-tech facilities and data centers typically fall under the primary level of service, which take service at high voltage and own, operate and maintain their own transformation equipment. These customers typically have very high usage and load factors because they tend to operate 24/7. 

?Public Street and Highway Lighting? refers to street lighting, traffic signals and highway signs. ?Other lighting? refers to lighting other community areas like ballparks. These accounts will typically have minimal load during the summer peak time periods.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | time           | fiscal_year        | Fiscal Year          | calendar_date | calendar_date |
| Yes      | series tag     | customer_class     | Customer Class       | text          | text          |
| Yes      | numeric metric | rate_cents_per_kwh | Rate (Cents per KWh) | number        | number        |
| Yes      | numeric metric | revenue            | Revenue              | money         | money         |
| Yes      | numeric metric | megawatt_hour      | Megawatt Hour        | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:scy3-ke5d d:2006-01-01T00:00:00.000Z t:customer_class=Residential m:megawatt_hour=4079909 m:rate_cents_per_kwh=9.498741271 m:revenue=387540000

series e:scy3-ke5d d:2006-01-01T00:00:00.000Z t:customer_class=Commercial m:megawatt_hour=4287176 m:rate_cents_per_kwh=8.560810193 m:revenue=367017000

series e:scy3-ke5d d:2006-01-01T00:00:00.000Z t:customer_class=Industrial m:megawatt_hour=1779333 m:rate_cents_per_kwh=6.097284769 m:revenue=108491000
```

## Meta Commands

```ls
metric m:rate_cents_per_kwh p:double l:"Rate (Cents per KWh)" t:dataTypeName=number

metric m:revenue p:integer l:Revenue t:dataTypeName=money

metric m:megawatt_hour p:double l:"Megawatt Hour" t:dataTypeName=number

entity e:scy3-ke5d l:"Austin Energy Rates - Cents per kilowatt hour by customer class" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/scy3-ke5d

property e:scy3-ke5d t:meta.view v:id=scy3-ke5d v:category=Utility v:averageRating=0 v:name="Austin Energy Rates - Cents per kilowatt hour by customer class" v:attribution="Austin Energy"

property e:scy3-ke5d t:meta.view.license v:name="Public Domain"

property e:scy3-ke5d t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:scy3-ke5d t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year         | customer_class                   | rate_cents_per_kwh | revenue   | megawatt_hour | 
| =================== | ================================ | ================== | ========= | ============= | 
| 2006-01-01T00:00:00 | Residential                      | 9.498741271        | 387540000 | 4079909       | 
| 2006-01-01T00:00:00 | Commercial                       | 8.560810193        | 367017000 | 4287176       | 
| 2006-01-01T00:00:00 | Industrial                       | 6.097284769        | 108491000 | 1779333       | 
| 2006-01-01T00:00:00 | Public Street & Highway Lighting | 17.34047319        | 8128000   | 46873         | 
| 2006-01-01T00:00:00 | Other Lighting                   | 7.279340407        | 80334000  | 1103589       | 
| 2006-01-01T00:00:00 | Total                            | 8.422768056        | 951510000 | 11296880      | 
| 2007-01-01T00:00:00 | Residential                      | 9.112436603        | 356143000 | 3908318       | 
| 2007-01-01T00:00:00 | Commercial                       | 8.411822625        | 365991000 | 4350912       | 
| 2007-01-01T00:00:00 | Industrial                       | 5.866893507        | 113248000 | 1930289       | 
| 2007-01-01T00:00:00 | Public Street & Highway Lighting | 17.16282024        | 8106000   | 47230         | 
```