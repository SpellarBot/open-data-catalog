# Choose Maryland: Compare Counties - Taxes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-counties-taxes) |
| Metadata | [Link](https://data.maryland.gov/api/views/9rx9-sduc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/9rx9-sduc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/9rx9-sduc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 9rx9-sduc |
| Name | Choose Maryland: Compare Counties - Taxes |
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | maryland, county, compare, taxes, income, property, exemption, enterprise zone, one maryland |
| Created | 2013-08-23T13:56:20Z |
| Publication Date | 2017-01-20T17:02:10Z |

## Description

Taxation - income tax, property tax, exemptions, enterprise zones.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================================ | ========= | =========== |
| No       | time           | :updated_at                                      | updated_at                                                       | meta_data | meta_data   |
| Yes      | series tag     | county                                           | County                                                           | text      | text        |
| Yes      | numeric metric | local_personal_income_tax                        | Local Personal Income Tax Rate (%)                               | percent   | percent     |
| Yes      | numeric metric | combined_state_and_county_real_property_tax_rate | Combined State and County Real Property Tax Rate ($ per hundred) | number    | number      |
| Yes      | numeric metric | county_business_personal_property_tax            | County Business Personal Property Tax Rate ($ per hundred)       | number    | number      |
| Yes      | numeric metric | manufacturing_rd_equipment_exemption             | Manufacturing/R&D Machinery and Equipment Exemption (%)          | percent   | percent     |
| Yes      | numeric metric | manufacturing_rd_inventory_exemption             | Manufacturing/R&D Inventory Exemption (%)                        | percent   | percent     |
| Yes      | numeric metric | commercial_inventory_exemption                   | Commercial Inventory Exemption (%)                               | percent   | percent     |
| Yes      | numeric metric | acreage_state_enterprise_zones                   | Acreage in State Enterprise Zones                                | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9rx9-sduc d:2017-01-20T17:01:24.000Z t:county="Allegany County" m:commercial_inventory_exemption=100 m:local_personal_income_tax=3.05 m:combined_state_and_county_real_property_tax_rate=1.089 m:county_business_personal_property_tax=2.4425 m:manufacturing_rd_inventory_exemption=100 m:manufacturing_rd_equipment_exemption=100 m:acreage_state_enterprise_zones=8509

series e:9rx9-sduc d:2017-01-20T17:01:24.000Z t:county="Anne Arundel County" m:commercial_inventory_exemption=100 m:local_personal_income_tax=2.5 m:combined_state_and_county_real_property_tax_rate=1.027 m:county_business_personal_property_tax=2.287 m:manufacturing_rd_inventory_exemption=100 m:manufacturing_rd_equipment_exemption=100 m:acreage_state_enterprise_zones=0

series e:9rx9-sduc d:2017-01-20T17:01:24.000Z t:county="Baltimore City" m:commercial_inventory_exemption=100 m:local_personal_income_tax=3.2 m:combined_state_and_county_real_property_tax_rate=2.36 m:county_business_personal_property_tax=5.62 m:manufacturing_rd_inventory_exemption=100 m:manufacturing_rd_equipment_exemption=100 m:acreage_state_enterprise_zones=13453
```

## Meta Commands

```ls
metric m:local_personal_income_tax p:float l:"Local Personal Income Tax Rate (%)" t:dataTypeName=percent

metric m:combined_state_and_county_real_property_tax_rate p:float l:"Combined State and County Real Property Tax Rate ($ per hundred)" t:dataTypeName=number

metric m:county_business_personal_property_tax p:float l:"County Business Personal Property Tax Rate ($ per hundred)" t:dataTypeName=number

metric m:manufacturing_rd_equipment_exemption p:integer l:"Manufacturing/R&D Machinery and Equipment Exemption (%)" t:dataTypeName=percent

metric m:manufacturing_rd_inventory_exemption p:integer l:"Manufacturing/R&D Inventory Exemption (%)" t:dataTypeName=percent

metric m:commercial_inventory_exemption p:integer l:"Commercial Inventory Exemption (%)" t:dataTypeName=percent

metric m:acreage_state_enterprise_zones p:integer l:"Acreage in State Enterprise Zones" t:dataTypeName=number

entity e:9rx9-sduc l:"Choose Maryland:  Compare Counties - Taxes" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/9rx9-sduc

property e:9rx9-sduc t:meta.view v:id=9rx9-sduc v:category="Business and Economy" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Counties - Taxes" v:attribution="Maryland Department of Commerce"

property e:9rx9-sduc t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:9rx9-sduc t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | county              | local_personal_income_tax | combined_state_and_county_real_property_tax_rate | county_business_personal_property_tax | manufacturing_rd_equipment_exemption | manufacturing_rd_inventory_exemption | commercial_inventory_exemption | acreage_state_enterprise_zones | 
| =========== | =================== | ========================= | ================================================ | ===================================== | ==================================== | ==================================== | ============================== | ============================== | 
| 1484931684  | Allegany County     | 3.05                      | 1.0890                                           | 2.4425                                | 100                                  | 100                                  | 100                            | 8509                           | 
| 1484931684  | Anne Arundel County | 2.50                      | 1.0270                                           | 2.2870                                | 100                                  | 100                                  | 100                            | 0                              | 
| 1484931684  | Baltimore City      | 3.20                      | 2.3600                                           | 5.6200                                | 100                                  | 100                                  | 100                            | 13453                          | 
| 1484931684  | Baltimore County    | 2.83                      | 1.2120                                           | 2.7500                                | 100                                  | 100                                  | 100                            | 8687                           | 
| 1484931684  | Calvert County      | 3.00                      | 1.0640                                           | 2.2300                                | 100                                  | 100                                  | 100                            | 0                              | 
| 1484931684  | Caroline County     | 2.73                      | 1.0920                                           | 0.0000                                | 100                                  | 100                                  | 100                            | 534                            | 
| 1484931684  | Carroll County      | 3.03                      | 1.1300                                           | 2.5150                                | 100                                  | 100                                  | 100                            | 0                              | 
| 1484931684  | Cecil County        | 2.80                      | 1.1034                                           | 2.4785                                | 100                                  | 100                                  | 100                            | 5968                           | 
| 1484931684  | Charles County      | 3.03                      | 1.3170                                           | 3.0125                                | 100                                  | 100                                  | 100                            | 0                              | 
| 1484931684  | Dorchester County   | 2.62                      | 1.0880                                           | 0.0000                                | 100                                  | 100                                  | 100                            | 2319                           | 
```