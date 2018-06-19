# Austin Energy Plant Assets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-energy-plant-assets) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kidc-knry) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kidc-knry/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kidc-knry/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kidc-knry |
| Name | Austin Energy Plant Assets |
| Attribution | City of Austin |
| Category | Financial |
| Created | 2011-12-16T13:52:39Z |
| Publication Date | 2016-05-12T19:38:49Z |

## Description

Plant assets include all of Austin Energy's system equipment and includes everything from office buildings and computers to generation. This includes Austin Energy's power plants (Fayette Power Project, South Texas Project, Decker Creek Power Station, and Sand Hill Energy Center), distribution and transmission lines, poles, and transformers.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | fiscal_year        | Fiscal Year        | number    | number      |
| Yes      | numeric metric | total_plant_assets | Total Plant Assets | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kidc-knry d:2010-01-01T00:00:00.000Z m:total_plant_assets=2579518000

series e:kidc-knry d:2009-01-01T00:00:00.000Z m:total_plant_assets=2504398000

series e:kidc-knry d:2008-01-01T00:00:00.000Z m:total_plant_assets=2379041000
```

## Meta Commands

```ls
metric m:total_plant_assets p:long l:"Total Plant Assets" t:dataTypeName=money

entity e:kidc-knry l:"Austin Energy Plant Assets" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/kidc-knry

property e:kidc-knry t:meta.view v:id=kidc-knry v:category=Financial v:averageRating=0 v:name="Austin Energy Plant Assets" v:attribution="City of Austin"

property e:kidc-knry t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:kidc-knry t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | total_plant_assets | 
| =========== | ================== | 
| 2010        | 2579518000         | 
| 2009        | 2504398000         | 
| 2008        | 2379041000         | 
| 2007        | 2229418000         | 
| 2006        | 2176440000         | 
| 2011        | 2589577000         | 
| 2012        | 2591616000         | 
| 2013        | 2586774000         | 
| 2014        | 2587457000         | 
| 2015        | 2603768000         | 
```