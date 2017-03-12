# Energy Sales - kilowatt hours by Customer Class

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-sales-kilowatt-hours-by-customer-class) |
| Metadata | [Link](https://data.austintexas.gov/api/views/t4zw-f3yr) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/t4zw-f3yr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/t4zw-f3yr/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | t4zw-f3yr |
| Name | Energy Sales - kilowatt hours by Customer Class |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, utility data, energy sales |
| Created | 2016-06-24T19:14:38Z |
| Publication Date | 2016-06-24T19:25:13Z |
| Rows Updated | 2016-06-24T19:24:43Z |

## Description

This table groups Austin Energy customers into five classes: residential, commercial, industrial, public street and highway, and government. View sales in dollars and kWh along with annual percent change for each customer class.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year           | Fiscal Year             | number    | number      |
| Yes      | numeric metric | residential           | Residential             | number    | number      |
| Yes      | numeric metric | commerical            | Commerical              | number    | number      |
| Yes      | numeric metric | industrial            | Industrial              | number    | number      |
| Yes      | series tag     | public_street_highway | Public Street & Highway | text      | number      |
| Yes      | numeric metric | government_entities   | Government Entities*    | number    | number      |
| Yes      | numeric metric | total_billed_kwh      | Total Billed kWh        | number    | number      |
| Yes      | numeric metric | inc_dec               | % Inc/Dec               | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t4zw-f3yr d:2012-01-01T00:00:00.000Z t:public_street_highway=46948693 m:inc_dec=-0.0006 m:commerical=4633556863 m:industrial=2648486622 m:residential=4381193546 m:government_entities=1005960507 m:total_billed_kwh=12716146231

series e:t4zw-f3yr d:2011-01-01T00:00:00.000Z t:public_street_highway=48327221 m:inc_dec=0.0624 m:commerical=4675615088 m:industrial=2342538382 m:residential=4561857688 m:government_entities=1094964902 m:total_billed_kwh=12723303281

series e:t4zw-f3yr d:2010-01-01T00:00:00.000Z t:public_street_highway=48077910 m:inc_dec=-0.01048 m:commerical=4553866402 m:industrial=2038706310 m:residential=4238690401 m:government_entities=1096985412 m:total_billed_kwh=11976326435
```

## Meta Commands

```ls
metric m:residential p:long l:Residential t:dataTypeName=number

metric m:commerical p:long l:Commerical t:dataTypeName=number

metric m:industrial p:long l:Industrial t:dataTypeName=number

metric m:government_entities p:integer l:"Government Entities*" d:"*Government entities include the city, state, county and schools in the Austin Energy service territory." t:dataTypeName=number

metric m:total_billed_kwh p:long l:"Total Billed kWh" t:dataTypeName=number

metric m:inc_dec l:"% Inc/Dec" t:dataTypeName=number

entity e:t4zw-f3yr l:"Energy Sales - kilowatt hours by Customer Class" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/t4zw-f3yr

property e:t4zw-f3yr t:meta.view v:id=t4zw-f3yr v:category=Utility v:averageRating=0 v:name="Energy Sales - kilowatt hours by Customer Class" v:attribution="Austin Energy"

property e:t4zw-f3yr t:meta.view.license v:name="Public Domain"

property e:t4zw-f3yr t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"

property e:t4zw-f3yr t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```