# Austin Water - Water Service Connection Count By Zip Code

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-water-service-connection-count-by-zip-code) |
| Metadata | [Link](https://data.austintexas.gov/api/views/uizf-mcbc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/uizf-mcbc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/uizf-mcbc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | uizf-mcbc |
| Name | Austin Water - Water Service Connection Count By Zip Code |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, services, count |
| Created | 2015-08-31T21:38:10Z |
| Publication Date | 2016-11-21T15:35:47Z |

## Description

This data set will include total services connections count for water services by customer class and zip code.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | postal_code         | Postal Code         | text      | text        |
| Yes      | series tag     | customer_class      | Customer Class      | text      | text        |
| Yes      | numeric metric | service_connections | Service Connections | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uizf-mcbc d:2016-11-21T15:35:38.000Z t:customer_class="Austin Water Utility" t:postal_code=78613 m:service_connections=1

series e:uizf-mcbc d:2016-11-21T15:35:38.000Z t:customer_class=Commercial t:postal_code=78613 m:service_connections=80

series e:uizf-mcbc d:2016-11-21T15:35:38.000Z t:customer_class="Irrigation - Commercial" t:postal_code=78613 m:service_connections=29
```

## Meta Commands

```ls
metric m:service_connections p:integer l:"Service Connections" t:dataTypeName=number

entity e:uizf-mcbc l:"Austin Water - Water Service Connection Count By Zip Code" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/uizf-mcbc

property e:uizf-mcbc t:meta.view v:id=uizf-mcbc v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Water Service Connection Count By Zip Code" v:attribution="Austin Water"

property e:uizf-mcbc t:meta.view.license v:name="Public Domain"

property e:uizf-mcbc t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:uizf-mcbc t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | postal_code | customer_class              | service_connections | 
| =========== | =========== | =========================== | =================== | 
| 1479742538  | 78613       | Austin Water Utility        | 1                   | 
| 1479742538  | 78613       | Commercial                  | 80                  | 
| 1479742538  | 78613       | Irrigation - Commercial     | 29                  | 
| 1479742538  | 78613       | Irrigation - Multi-Family   | 7                   | 
| 1479742538  | 78613       | Multi-Family                | 7                   | 
| 1479742538  | 78617       | Austin Water Utility        | 2                   | 
| 1479742538  | 78617       | City of Austin              | 4                   | 
| 1479742538  | 78617       | Commercial                  | 80                  | 
| 1479742538  | 78617       | Irrigation - City of Austin | 1                   | 
| 1479742538  | 78617       | Irrigation - Commercial     | 29                  | 
```