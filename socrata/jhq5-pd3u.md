# Table 14: Toxic Release Inventory (TRI) (in pounds)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-14-toxic-release-inventory-tri-in-pounds-7518f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jhq5-pd3u) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jhq5-pd3u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jhq5-pd3u/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jhq5-pd3u |
| Name | Table 14: Toxic Release Inventory (TRI) (in pounds) |
| Attribution | DOH |
| Category | Health |
| Tags | toxic, release, inventory |
| Created | 2012-08-01T00:09:48Z |
| Publication Date | 2012-08-01T00:10:39Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       |                | _                     | #                     | number    | number      |
| Yes      | time           | calendar_year         | Calendar Year         | number    | text        |
| Yes      | numeric metric | air_emissions         | Air Emissions         | number    | number      |
| Yes      | numeric metric | off_site_transfers    | Off-Site Transfers    | number    | number      |
| Yes      | numeric metric | on_site_land          | On-site Land          | number    | number      |
| Yes      | numeric metric | water                 | Water                 | number    | number      |
| Yes      | numeric metric | underground_injection | Underground Injection | number    | number      |
| Yes      | numeric metric | total                 | Total                 | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:jhq5-pd3u d:2005-01-01T00:00:00.000Z m:water=522217 m:total=3102730 m:air_emissions=2311635 m:underground_injection=2736 m:on_site_land=89734 m:off_site_transfers=176408

series e:jhq5-pd3u d:2006-01-01T00:00:00.000Z m:water=358266 m:total=3022392 m:air_emissions=2254027 m:underground_injection=4743 m:on_site_land=174678 m:off_site_transfers=230678

series e:jhq5-pd3u d:2007-01-01T00:00:00.000Z m:water=446948 m:total=3015602 m:air_emissions=2266925 m:underground_injection=2670 m:on_site_land=143011 m:off_site_transfers=156048
```

## Meta Commands

```ls
metric m:air_emissions p:integer l:"Air Emissions" t:dataTypeName=number

metric m:off_site_transfers p:integer l:"Off-Site Transfers" t:dataTypeName=number

metric m:on_site_land p:integer l:"On-site Land" t:dataTypeName=number

metric m:water p:integer l:Water t:dataTypeName=number

metric m:underground_injection p:integer l:"Underground Injection" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:jhq5-pd3u l:"Table 14: Toxic Release Inventory (TRI) (in pounds)" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/jhq5-pd3u

property e:jhq5-pd3u t:meta.view v:id=jhq5-pd3u v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 14: Toxic Release Inventory (TRI) (in pounds)" v:attribution=DOH

property e:jhq5-pd3u t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jhq5-pd3u t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:jhq5-pd3u t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | air_emissions | off_site_transfers | on_site_land | water  | underground_injection | total   | 
| = | ============= | ============= | ================== | ============ | ====== | ===================== | ======= | 
| 1 | 2005          | 2311635       | 176408             | 89734        | 522217 | 2736                  | 3102730 | 
| 2 | 2006          | 2254027       | 230678             | 174678       | 358266 | 4743                  | 3022392 | 
| 3 | 2007          | 2266925       | 156048             | 143011       | 446948 | 2670                  | 3015602 | 
| 4 | 2008          | 2277988       | 245556             | 169076       | 549838 | 3471                  | 3245929 | 
| 5 | 2009          | 2228566       | 343925             | 147530       | 222963 | 4477                  | 2947461 | 
```