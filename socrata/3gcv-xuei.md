# Sales ? kWh by Customer Class

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sales-kwh-by-customer-class) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3gcv-xuei) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3gcv-xuei/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3gcv-xuei/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3gcv-xuei |
| Name | Sales ? kWh by Customer Class |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | utility sales, utility data, austin energy |
| Created | 2015-08-18T17:43:29Z |
| Publication Date | 2016-06-03T14:21:07Z |

## Description

This table groups Austin Energy customers into five classes: residential, commercial, industrial, public street and highway, and government. View sales in dollars and kWh.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year           | Fiscal Year             | number    | text        |
| Yes      | numeric metric | residential           | Residential             | number    | number      |
| Yes      | numeric metric | commerical            | Commerical              | number    | number      |
| Yes      | numeric metric | industrial            | Industrial              | number    | number      |
| Yes      | numeric metric | public_street_highway | Public Street & Highway | number    | number      |
| Yes      | numeric metric | government_entities   | Government Entities     | number    | number      |
| Yes      | numeric metric | total_billed_kwh      | Total Billed kWh        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3gcv-xuei d:2013-01-01T00:00:00.000Z m:commerical=4644247105 m:industrial=2735011717 m:residential=4162387287 m:government_entities=690249126 m:public_street_highway=38838425 m:total_billed_kwh=12270733660

series e:3gcv-xuei d:2012-01-01T00:00:00.000Z m:commerical=4633556863 m:industrial=2648486622 m:residential=4381193546 m:government_entities=1005960507 m:public_street_highway=46948693 m:total_billed_kwh=12716146231

series e:3gcv-xuei d:2011-01-01T00:00:00.000Z m:commerical=4675615088 m:industrial=2342538382 m:residential=4561857688 m:government_entities=1094964902 m:public_street_highway=48327221 m:total_billed_kwh=12723303281
```

## Meta Commands

```ls
metric m:residential p:long l:Residential d:"Residential customers live in single-family dwellings, mobile homes, townhouses, or individually metered apartment units." t:dataTypeName=number

metric m:commerical p:long l:Commerical d:"The majority of commercial customers are small to large businesses that fall under Austin Energy?s secondary level of service. This means Austin Energy owns, operates, and maintains the equipment (wires, transformers, etc.) supplying power to those facilities." t:dataTypeName=number

metric m:industrial p:long l:Industrial d:"Industrial (Primary) customers take service at high voltage (12,500 volts or higher) and own, operate and maintain their own equipment. Consequently, Austin Energy experiences lower overall system losses and it costs less to serve these customers. Large commercial and industrial customers such as semiconductors, high-tech facilities, and data centers typically fall under the primary level of service. These customers have very high usage and load factors because they tend to operate 24/7." t:dataTypeName=number

metric m:public_street_highway p:integer l:"Public Street & Highway" t:dataTypeName=number

metric m:government_entities p:integer l:"Government Entities" d:"Government Entities include the city, state, county and schools in the Austin Energy service territory." t:dataTypeName=number

metric m:total_billed_kwh p:long l:"Total Billed kWh" t:dataTypeName=number

entity e:3gcv-xuei l:"Sales ? kWh by Customer Class" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/3gcv-xuei

property e:3gcv-xuei t:meta.view v:id=3gcv-xuei v:category=Utility v:averageRating=0 v:name="Sales ? kWh by Customer Class" v:attribution="Austin Energy"

property e:3gcv-xuei t:meta.view.license v:name="Public Domain"

property e:3gcv-xuei t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:3gcv-xuei t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | residential | commerical | industrial | public_street_highway | government_entities | total_billed_kwh | 
| =========== | =========== | ========== | ========== | ===================== | =================== | ================ | 
| 2013        | 4162387287  | 4644247105 | 2735011717 | 38838425              | 690249126           | 12270733660      | 
| 2012        | 4381193546  | 4633556863 | 2648486622 | 46948693              | 1005960507          | 12716146231      | 
| 2011        | 4561857688  | 4675615088 | 2342538382 | 48327221              | 1094964902          | 12723303281      | 
| 2010        | 4238690401  | 4553866402 | 2038706310 | 48077910              | 1096985412          | 11976326435      | 
| 2009        | 4218600234  | 4480902380 | 2218314628 | 47830865              | 1137492172          | 12103140282      | 
| 2008        | 4220597712  | 4534963675 | 2233505323 | 47689860              | 1147483264          | 12184239834      | 
| 2007        | 3908317955  | 4350911526 | 1930288560 | 47230496              | 1088319666          | 11325068203      | 
| 2006        | 4079909225  | 4287175580 | 1779332604 | 46872901              | 1103588987          | 11296879297      | 
| 2005        | 3879940471  | 4195211630 | 1662457519 | 46366406              | 1081420132          | 10865396158      | 
| 2004        | 3605110769  | 4013463458 | 1536813178 | 48176968              | 1058566697          | 10262130070      | 
```