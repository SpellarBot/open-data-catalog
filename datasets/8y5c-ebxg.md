# Oil and Gas Summary Production Data: 1967-1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oil-and-gas-summary-production-data-1967-1999) |
| Metadata | [Link](https://data.ny.gov/api/views/8y5c-ebxg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/8y5c-ebxg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/8y5c-ebxg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 8y5c-ebxg |
| Name | Oil and Gas Summary Production Data: 1967-1999 |
| Attribution | New York State Dept. of Environmental Conservation |
| Category | Energy & Environment |
| Tags | oil, gas, wells, production, geology, mineral resources |
| Created | 2016-08-12T16:45:33Z |
| Publication Date | 2016-09-28T15:00:17Z |

## Description

This dataset contains production information from oil and gas wells in New York State from 1967 to 1999. Each record represents a sum by operator for each county, town, field, and formation grouping.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| No       |                | production_year         | Production Year         | number        | number        |
| Yes      | time           | production_date_entered | Production Date Entered | calendar_date | calendar_date |
| Yes      | series tag     | operator                | Operator                | text          | text          |
| Yes      | series tag     | county                  | County                  | text          | text          |
| Yes      | series tag     | town                    | Town                    | text          | text          |
| Yes      | series tag     | field                   | Field                   | text          | text          |
| Yes      | series tag     | producing_formation     | Producing Formation     | text          | text          |
| Yes      | numeric metric | active_oil_wells        | Active Oil Wells        | number        | number        |
| Yes      | numeric metric | inactive_oil_wells      | Inactive Oil Wells      | number        | number        |
| Yes      | numeric metric | active_gas_wells        | Active Gas Wells        | number        | number        |
| Yes      | numeric metric | inactive_gas_wells      | Inactive Gas Wells      | number        | number        |
| Yes      | numeric metric | injection_wells         | Injection Wells         | number        | number        |
| Yes      | numeric metric | disposal_wells          | Disposal Wells          | number        | number        |
| Yes      | series tag     | self_use_well           | Self-use Well           | text          | text          |
| Yes      | numeric metric | oil_produced_bbl        | Oil Produced, bbl       | number        | number        |
| Yes      | numeric metric | gas_produced_mcf        | Gas Produced, Mcf       | number        | number        |
| Yes      | numeric metric | water_produced_bbl      | Water produced, bbl     | number        | number        |
| Yes      | numeric metric | taxable_gas_mcf         | Taxable Gas, Mcf        | number        | number        |
| Yes      | series tag     | purchaser_codes         | Purchaser Codes         | text          | text          |
```

## Time Field

```ls
Value = production_date_entered
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = production_year
```

## Data Commands

```ls
series e:8y5c-ebxg d:1996-12-03T00:00:00.000Z t:field=BUFFALO t:producing_formation=MEDINA t:county=Erie t:self_use_well=YES t:town=BUFFALO t:operator="Buffalo China, Inc." m:disposal_wells=0 m:gas_produced_mcf=106 m:injection_wells=0 m:active_gas_wells=1 m:oil_produced_bbl=0 m:taxable_gas_mcf=0 m:water_produced_bbl=0 m:active_oil_wells=0 m:inactive_oil_wells=0 m:inactive_gas_wells=0

series e:8y5c-ebxg d:1996-03-29T00:00:00.000Z t:field="BEECH HILL-INDEPENDENCE" t:producing_formation="FULMER VALLEY" t:county=Steuben t:self_use_well=NO t:town="WEST UNION" t:purchaser_codes=OA t:operator="Copper Ridge Oil, Inc." m:disposal_wells=0 m:gas_produced_mcf=0 m:injection_wells=7 m:active_gas_wells=0 m:oil_produced_bbl=1229 m:taxable_gas_mcf=0 m:water_produced_bbl=180 m:active_oil_wells=28 m:inactive_oil_wells=0 m:inactive_gas_wells=0

series e:8y5c-ebxg d:1995-02-14T00:00:00.000Z t:field=BRADFORD t:producing_formation=BRADFORD t:county=Cattaraugus t:self_use_well=NO t:town=CARROLLTON t:purchaser_codes=OA t:operator="White, Walter W. & Christina L." m:disposal_wells=0 m:gas_produced_mcf=0 m:injection_wells=0 m:active_gas_wells=0 m:oil_produced_bbl=462 m:taxable_gas_mcf=0 m:water_produced_bbl=0 m:active_oil_wells=3 m:inactive_oil_wells=0 m:inactive_gas_wells=0
```

## Meta Commands

```ls
metric m:active_oil_wells p:integer l:"Active Oil Wells" d:"Number of active oil wells for the production year in the county, town, field, and formation grouping" t:dataTypeName=number

metric m:inactive_oil_wells p:integer l:"Inactive Oil Wells" d:"Number of inactive oil wells for the production year in the county, town, field, and formation grouping" t:dataTypeName=number

metric m:active_gas_wells p:integer l:"Active Gas Wells" d:"Number of active gas wells for the production year in the county, town, field, and formation grouping" t:dataTypeName=number

metric m:inactive_gas_wells p:integer l:"Inactive Gas Wells" d:"Number of inactive gas wells for the production year in the county, town, field, and formation grouping" t:dataTypeName=number

metric m:injection_wells p:integer l:"Injection Wells" d:"Number of injection wells in the county, town, field, and formation grouping" t:dataTypeName=number

metric m:disposal_wells p:integer l:"Disposal Wells" d:"Number of disposal wells in the county, town, field, and formation grouping" t:dataTypeName=number

metric m:oil_produced_bbl p:integer l:"Oil Produced, bbl" d:"Oil volume produced (bbl)" t:dataTypeName=number

metric m:gas_produced_mcf p:integer l:"Gas Produced, Mcf" d:"Gas volume produced (Mcf)" t:dataTypeName=number

metric m:water_produced_bbl p:integer l:"Water produced, bbl" d:"Water volume produced (bbl)" t:dataTypeName=number

metric m:taxable_gas_mcf p:integer l:"Taxable Gas, Mcf" d:"Taxable gas (Mcf)" t:dataTypeName=number

entity e:8y5c-ebxg l:"Oil and Gas Summary Production Data: 1967-1999" t:attribution="New York State Dept. of Environmental Conservation" t:url=https://data.ny.gov/api/views/8y5c-ebxg

property e:8y5c-ebxg t:meta.view v:id=8y5c-ebxg v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/energy/205.html v:averageRating=0 v:name="Oil and Gas Summary Production Data: 1967-1999" v:attribution="New York State Dept. of Environmental Conservation"

property e:8y5c-ebxg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:8y5c-ebxg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| production_year | production_date_entered | operator                           | county      | town        | field                   | producing_formation  | active_oil_wells | inactive_oil_wells | active_gas_wells | inactive_gas_wells | injection_wells | disposal_wells | self_use_well | oil_produced_bbl | gas_produced_mcf | water_produced_bbl | taxable_gas_mcf | purchaser_codes | 
| =============== | ======================= | ================================== | =========== | =========== | ======================= | ==================== | ================ | ================== | ================ | ================== | =============== | ============== | ============= | ================ | ================ | ================== | =============== | =============== | 
| 1995            | 1996-12-03T00:00:00     | Buffalo China, Inc.                | Erie        | BUFFALO     | BUFFALO                 | MEDINA               | 0                | 0                  | 1                | 0                  | 0               | 0              | YES           | 0                | 106              | 0                  | 0               |                 | 
| 1995            | 1996-03-29T00:00:00     | Copper Ridge Oil, Inc.             | Steuben     | WEST UNION  | BEECH HILL-INDEPENDENCE | FULMER VALLEY        | 28               | 0                  | 0                | 0                  | 7               | 0              | NO            | 1229             | 0                | 180                | 0               | OA              | 
| 1994            | 1995-02-14T00:00:00     | White, Walter W. & Christina L.    | Cattaraugus | CARROLLTON  | BRADFORD                | BRADFORD             | 3                | 0                  | 0                | 0                  | 0               | 0              | NO            | 462              | 0                | 0                  | 0               | OA              | 
| 1994            | 1995-01-19T00:00:00     | Stiegler, Richard M                | Erie        | CHEEKTOWAGA | BUFFALO                 | MEDINA               | 0                | 0                  | 1                | 0                  | 0               | 0              | YES           | 0                | 530              | 0                  | 0               |                 | 
| 1995            | 1996-02-12T00:00:00     | Bucher, Charles J                  | Cattaraugus | ALLEGANY    | FIVE MILE               | BRADFORD             | 10               | 0                  | 0                | 0                  | 0               | 0              | NO            | 45               | 0                | 80                 | 0               | OA              | 
| 1995            | 1996-04-02T00:00:00     | Cotton Well Drilling Company, Inc. | Chautauqua  | SHERIDAN    | LAKESHORE               | MEDINA               | 0                | 0                  | 13               | 2                  | 0               | 0              | NO            | 0                | 27742            | 377                | 24177           | GK              | 
| 1994            | 1995-04-05T00:00:00     | Oil, Gas & Land Services, Inc.     | Chautauqua  | ELLERY      | ELLERY                  | ONONDAGA-BASS ISLAND | 1                | 3                  | 1                | 0                  | 0               | 0              | NO            | 96               | 1582             | 730                | 1439            | GX,OA           | 
| 1994            | 1995-03-15T00:00:00     | Traxler, Joyce                     | Genesee     | LE ROY      | UHLEY CORNERS-CALEDONIA | MEDINA               | 0                | 0                  | 1                | 0                  | 0               | 0              | YES           | 0                | 500              | 0                  | 0               |                 | 
| 1995            | 1996-09-12T00:00:00     | Cunningham Natural Gas Corp.       | Allegany    | WILLING     | STATE LINE              | ORISKANY             | 0                | 0                  | 1                | 3                  | 0               | 0              | NO            | 0                | 484927           | 0                  | 484927          | GX              | 
| 1995            | 1996-10-18T00:00:00     | Crowell, Walter R.                 | Chautauqua  | VILLENOVA   | LAKESHORE               | MEDINA               | 0                | 0                  | 1                | 0                  | 0               | 0              | YES           | 0                | 100              | 0                  | 0               |                 | 
```