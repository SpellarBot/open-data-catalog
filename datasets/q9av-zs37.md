# Industrial Timber Harvest Production and Consumption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/industrial-timber-harvest-production-and-consumption) |
| Metadata | [Link](https://data.ny.gov/api/views/q9av-zs37) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q9av-zs37/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q9av-zs37/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q9av-zs37 |
| Name | Industrial Timber Harvest Production and Consumption |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | timber harvest, logging, forest products |
| Created | 2015-11-17T23:22:54Z |
| Publication Date | 2016-04-27T17:09:23Z |

## Description

Reports estimated industrial timber harvest production level from New York?s forests, the consumption level of New York?s primary wood processors, and the flow of harvested timber products to/from New York.  Data is available for the pilot year, 1999, and from 2001 to the most currently available data year.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                | Data Type | Render Type |
| ======== | ============== | ========== | =================== | ========= | =========== |
| Yes      | series tag     | use        | Use                 | text      | text        |
| Yes      | time           | year       | Year                | number    | number      |
| Yes      | numeric metric | quantity   | Quantity (millions) | number    | number      |
| Yes      | series tag     | unit       | Unit                | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q9av-zs37 d:2013-01-01T00:00:00.000Z t:unit="Board feet (International 1/4"" Rule) of logs" t:use="Export to Canada" m:quantity=93

series e:q9av-zs37 d:2013-01-01T00:00:00.000Z t:unit="Board feet (International 1/4"" Rule) of logs" t:use="NY Harvest Production" m:quantity=526

series e:q9av-zs37 d:2013-01-01T00:00:00.000Z t:unit="Board feet (International 1/4"" Rule) of logs" t:use="NY Mill Consumption" m:quantity=438
```

## Meta Commands

```ls
metric m:quantity p:integer l:"Quantity (millions)" d:"The numeric quantity for the harvested timber for the specified use. Note: All measurements are in millions of units, e.g. a quantity of ?12? represents 12,000,000 units." t:dataTypeName=number

entity e:q9av-zs37 l:"Industrial Timber Harvest Production and Consumption" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/q9av-zs37

property e:q9av-zs37 t:meta.view v:id=q9av-zs37 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/lands/4963.html v:averageRating=0 v:name="Industrial Timber Harvest Production and Consumption" v:attribution="Department of Environmental Conservation"

property e:q9av-zs37 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q9av-zs37 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| use                   | year | quantity | unit                                         | 
| ===================== | ==== | ======== | ============================================ | 
| Export to Canada      | 2013 | 93       | Board feet (International 1/4" Rule) of logs | 
| NY Harvest Production | 2013 | 526      | Board feet (International 1/4" Rule) of logs | 
| NY Mill Consumption   | 2013 | 438      | Board feet (International 1/4" Rule) of logs | 
| Export to Canada      | 2012 | 92       | Board feet (International 1/4" Rule) of logs | 
| NY Harvest Production | 2012 | 508      | Board feet (International 1/4" Rule) of logs | 
| NY Mill Consumption   | 2012 | 413      | Board feet (International 1/4" Rule) of logs | 
| Export to Canada      | 2011 | 95       | Board feet (International 1/4" Rule) of logs | 
| NY Harvest Production | 2011 | 480      | Board feet (International 1/4" Rule) of logs | 
| NY Mill Consumption   | 2011 | 401      | Board feet (International 1/4" Rule) of logs | 
| Export to Canada      | 2010 | 118      | Board feet (International 1/4" Rule) of logs | 
```