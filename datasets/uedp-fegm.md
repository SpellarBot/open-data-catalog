# Natural Gas Consumption by ZIP Code - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/natural-gas-consumption-by-zip-code-2010-0329b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uedp-fegm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uedp-fegm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uedp-fegm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uedp-fegm |
| Name | Natural Gas Consumption by ZIP Code - 2010 |
| Attribution | Mayor's Office of Long-Term Planning and Sustainability (OLTPS) |
| Category | Environment |
| Tags | energy, gas, power, environment, utilities, planning |
| Created | 2011-09-28T22:01:04Z |
| Publication Date | 2013-06-21T19:42:08Z |

## Description

2010 Natural Gas consumption in therms and GJ, by ZIP code, building type, and utility company.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | building_type_service_class | Building type (service class | text      | text        |
| Yes      | numeric metric | consumption_therms_         | Consumption (therms)         | number    | number      |
| Yes      | numeric metric | consumption_gj_             | Consumption (GJ)             | number    | number      |
| Yes      | series tag     | utility_data_source         | Utility/Data Source          | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uedp-fegm d:2010-01-01T00:00:00.000Z t:utility_data_source="National Grid" t:building_type_service_class=Commercial m:consumption_gj_=50 m:consumption_therms_=470

series e:uedp-fegm d:2010-01-01T00:00:00.000Z t:utility_data_source="National Grid" t:building_type_service_class=Commercial m:consumption_gj_=68 m:consumption_therms_=647

series e:uedp-fegm d:2010-01-01T00:00:00.000Z t:utility_data_source="National Grid" t:building_type_service_class="Large residential" m:consumption_gj_=3562 m:consumption_therms_=33762
```

## Meta Commands

```ls
metric m:consumption_therms_ p:integer l:"Consumption (therms)" t:dataTypeName=number

metric m:consumption_gj_ p:integer l:"Consumption (GJ)" t:dataTypeName=number

entity e:uedp-fegm l:"Natural Gas Consumption by ZIP Code - 2010" t:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)" t:url=https://data.cityofnewyork.us/api/views/uedp-fegm

property e:uedp-fegm t:meta.view v:id=uedp-fegm v:category=Environment v:averageRating=0 v:name="Natural Gas Consumption by ZIP Code - 2010" v:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)"

property e:uedp-fegm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uedp-fegm t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| building_type_service_class | consumption_therms_ | consumption_gj_ | utility_data_source | 
| =========================== | =================== | =============== | =================== | 
| Commercial                  | 470                 | 50              | National Grid       | 
| Commercial                  | 647                 | 68              | National Grid       | 
| Large residential           | 33762               | 3562            | National Grid       | 
| Commercial                  | 32125               | 3389            | National Grid       | 
| Institutional               | 3605                | 380             | National Grid       | 
| Small residential           | 3960                | 418             | National Grid       | 
| Small residential           | 1896                | 200             | National Grid       | 
| Commercial                  | 8364                | 882             | National Grid       | 
| Commercial                  | 2579                | 272             | National Grid       | 
| Large residential           | 301                 | 32              | National Grid       | 
```