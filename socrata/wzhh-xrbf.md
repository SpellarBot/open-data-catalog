# Sales Tax Collections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sales-tax-collections) |
| Metadata | [Link](https://data.brla.gov/api/views/wzhh-xrbf) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/wzhh-xrbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/wzhh-xrbf/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | wzhh-xrbf |
| Name | Sales Tax Collections |
| Attribution | Finance - Revenue |
| Category | Business and Financial |
| Tags | finance, sales tax, collections |
| Created | 2016-05-19T14:20:18Z |
| Publication Date | 2017-03-29T18:57:44Z |

## Description

Monthly sales tax collections by tax period for 2% City of Baton Rouge sales tax, 2% Unincorporated EBR Parish sales tax, and the combined 2% City-Parish sales tax.  Figures are presented as ?regular? collections (collected by City-Parish Revenue Division), vehicle tax only collections (collected by the State Department of Public Safety) and the total collections including vehicle tax.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                                             | Data Type | Render Type |
| ======== | ============== | ==================== | ================================================ | ========= | =========== |
| Yes      | time           | year                 | YEAR                                             | number    | text        |
| Yes      | series tag     | month                | MONTH                                            | text      | text        |
| Yes      | numeric metric | city_less_vehicle    | CITY TAX COLLECTIONS (NON-VEHICLE SALES)         | number    | number      |
| Yes      | numeric metric | city_vehicle         | CITY VEHICLE SALES TAX COLLECTIONS               | number    | number      |
| Yes      | numeric metric | city_total           | CITY TOTAL TAX COLLECTIONS                       | number    | number      |
| Yes      | numeric metric | parish_less_vehicle  | PARISH TAX COLLECTIONS (NON-VEHICLE SALES TAXES) | number    | number      |
| Yes      | numeric metric | parish_vehicle       | PARISH VEHICLE TAX COLLECTIONS                   | number    | number      |
| Yes      | numeric metric | parish_total         | PARISH TOTAL TAX COLLECTIONS                     | number    | number      |
| Yes      | numeric metric | monthly_less_vehicle | CITY-PARISH TOTAL (NON-VEHICLE SALES TAXES)      | number    | number      |
| Yes      | numeric metric | monthly_vehicle      | CITY-PARISH VEHICLE SALES TAX COLLECTIONS        | number    | number      |
| Yes      | numeric metric | monthly_total        | CITY-PARISH TOTAL TAX COLLECTIONS                | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wzhh-xrbf d:2017-01-01T00:00:00.000Z t:month=01-January m:city_less_vehicle=8542132 m:parish_total=7116597 m:parish_less_vehicle=6176761 m:city_vehicle=807622 m:monthly_total=16466351 m:monthly_less_vehicle=14718893 m:city_total=9349754 m:parish_vehicle=939836 m:monthly_vehicle=1747458

series e:wzhh-xrbf d:2016-01-01T00:00:00.000Z t:month=01-January m:city_less_vehicle=7276341 m:parish_total=6366605 m:parish_less_vehicle=5671850 m:city_vehicle=579746 m:monthly_total=14222692 m:monthly_less_vehicle=12948191 m:city_total=7856087 m:parish_vehicle=694755 m:monthly_vehicle=1274501

series e:wzhh-xrbf d:2016-01-01T00:00:00.000Z t:month=02-February m:city_less_vehicle=7458395 m:parish_total=6459946 m:parish_less_vehicle=5872754 m:city_vehicle=602694 m:monthly_total=14521035 m:monthly_less_vehicle=13331149 m:city_total=8061089 m:parish_vehicle=587192 m:monthly_vehicle=1189886
```

## Meta Commands

```ls
metric m:city_less_vehicle p:integer l:"CITY TAX COLLECTIONS (NON-VEHICLE SALES)" d:"Monthly sales tax collections (2%) in the City of Baton Rouge limits ? does not include parish or vehicle sales tax collections" t:dataTypeName=number

metric m:city_vehicle p:integer l:"CITY VEHICLE SALES TAX COLLECTIONS" d:"Monthly sales tax collections (2%) collected on monthly vehicle sales in the City of Baton Rouge limits only ? does not include city or parish non-vehicle sales tax collections" t:dataTypeName=number

metric m:city_total p:integer l:"CITY TOTAL TAX COLLECTIONS" d:"Combined monthly City of Baton Rouge sales and vehicle taxes ? does not include parish sales tax collections" t:dataTypeName=number

metric m:parish_less_vehicle p:integer l:"PARISH TAX COLLECTIONS (NON-VEHICLE SALES TAXES)" d:"Monthly sales tax collections (2%) for the unincorporated areas of East Baton Rouge Parish only ? does not include city or vehicle sales tax collections" t:dataTypeName=number

metric m:parish_vehicle p:integer l:"PARISH VEHICLE TAX COLLECTIONS" d:"Monthly sales tax collections (2%) collected on monthly vehicle sales in the unincorporated areas of East Baton Rouge Parish only ? does not include city or parish non-vehicle sales tax collections" t:dataTypeName=number

metric m:parish_total p:integer l:"PARISH TOTAL TAX COLLECTIONS" d:"Combined monthly sales and vehicle taxes collected in the unincorporated areas of East Baton Rouge Parish only ? does not include city sales tax collections" t:dataTypeName=number

metric m:monthly_less_vehicle p:integer l:"CITY-PARISH TOTAL (NON-VEHICLE SALES TAXES)" d:"Combined monthly non-vehicle sales tax collections from both the City of Baton Rouge limits and the unincorporated areas of East Baton Rouge Parish ? does not include vehicle sales tax collections" t:dataTypeName=number

metric m:monthly_vehicle p:integer l:"CITY-PARISH VEHICLE SALES TAX COLLECTIONS" d:"Combined monthly vehicle sales tax collections from vehicles sold in both the City of Baton Rouge limits and the unincorporated areas of East Baton Rouge Parish ? does not include city or parish non-vehicle sales tax collections" t:dataTypeName=number

metric m:monthly_total p:integer l:"CITY-PARISH TOTAL TAX COLLECTIONS" d:"Combined monthly vehicle and sales tax collections in both the City of Baton Rouge limits and the unincorporated areas of East Baton Rouge parish" t:dataTypeName=number

entity e:wzhh-xrbf l:"Sales Tax Collections" t:attribution="Finance - Revenue" t:url=https://data.brla.gov/api/views/wzhh-xrbf

property e:wzhh-xrbf t:meta.view v:id=wzhh-xrbf v:category="Business and Financial" v:attributionLink=https://brgov.com/dept/finance/Salestaxrates.htm v:averageRating=0 v:name="Sales Tax Collections" v:attribution="Finance - Revenue"

property e:wzhh-xrbf t:meta.view.license v:name="Public Domain"

property e:wzhh-xrbf t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:wzhh-xrbf t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| year | month        | city_less_vehicle | city_vehicle | city_total | parish_less_vehicle | parish_vehicle | parish_total | monthly_less_vehicle | monthly_vehicle | monthly_total | 
| ==== | ============ | ================= | ============ | ========== | =================== | ============== | ============ | ==================== | =============== | ============= | 
| 2017 | 01-January   | 8542132           | 807622       | 9349754    | 6176761             | 939836         | 7116597      | 14718893             | 1747458         | 16466351      | 
| 2016 | 01-January   | 7276341           | 579746       | 7856087    | 5671850             | 694755         | 6366605      | 12948191             | 1274501         | 14222692      | 
| 2016 | 02-February  | 7458395           | 602694       | 8061089    | 5872754             | 587192         | 6459946      | 13331149             | 1189886         | 14521035      | 
| 2016 | 03-March     | 8522406           | 695320       | 9217726    | 6567225             | 729349         | 7296574      | 15089631             | 1424669         | 16514300      | 
| 2016 | 04-April     | 7850191           | 661494       | 8511685    | 5989784             | 680611         | 6670395      | 13839975             | 1342105         | 15182080      | 
| 2016 | 05-May       | 7693124           | 603885       | 8297009    | 5914779             | 659369         | 6574148      | 13607903             | 1263254         | 14871157      | 
| 2016 | 06-June      | 7927529           | 655368       | 8582897    | 6290263             | 763118         | 7053381      | 14217792             | 1418486         | 15636278      | 
| 2016 | 07-July      | 7190158           | 531102       | 7721260    | 5686452             | 669958         | 6356410      | 12876610             | 1201060         | 14077670      | 
| 2016 | 08-August    | 7862089           | 530943       | 8393032    | 5911237             | 665177         | 6576414      | 13773326             | 1196120         | 14969446      | 
| 2016 | 09-September | 9316548           | 925396       | 10241944   | 6956708             | 1291971        | 8248679      | 16273256             | 2217367         | 18490623      | 
```