# Real Property Tax Rates - Levy Year 2014 and Beyond

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/levy-year-2014-real-property-tax-rates-449c7) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/mdtv-drkr) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/mdtv-drkr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/mdtv-drkr/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | mdtv-drkr |
| Name | Real Property Tax Rates - Levy Year 2014 and Beyond |
| Category | Finance/Tax/Property |
| Tags | property, tax rates |
| Created | 2014-08-29T17:53:47Z |
| Publication Date | 2015-10-07T16:12:14Z |

## Description

The real property tax rate dataset reflects all the rates per $100 set each year by the County Council. These rates are applied to the assessed value of the real property to derive the applicable ad valorem tax. The fully phased-in assessed value equals the full cash value of the property. The real property tax is levied annually on all taxable land and improvements. The tax rate schedule is updated annually. A detailed tax rate schedule for all tax classes is available by clicking on ?Tax Rates? under the link for ?County Taxes? when visiting the County website at www.montgomerycountymd.gov/finance or by calling 311 (240-777-0311). Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | time           | levy_year                                | LEVY YEAR                                | number    | text        |
| Yes      | numeric metric | tax_class                                | TAX CLASS *                              | number    | number      |
| Yes      | numeric metric | general_county_tax                       | GENERAL COUNTY TAX                       | number    | number      |
| Yes      | numeric metric | state_tax                                | STATE TAX                                | number    | number      |
| Yes      | series tag     | municipal_district_tax                   | MUNICIPAL DISTRICT TAX                   | text      | number      |
| Yes      | series tag     | municipal_district                       | MUNICIPAL DISTRICT                       | text      | text        |
| Yes      | numeric metric | ssa_transit_tax                          | SSA TRANSIT TAX                          | number    | number      |
| Yes      | series tag     | ssa_fire_district_tax                    | SSA FIRE DISTRICT TAX                    | text      | number      |
| Yes      | numeric metric | ssa_mncppc_advanced_land_acquisition_tax | SSA/MNCPPC ADVANCED LAND ACQUISITION TAX | number    | number      |
| Yes      | numeric metric | ssa_mncppc_metro_politan_tax             | SSA/MNCPPC METRO-POLITAN TAX             | number    | number      |
| Yes      | numeric metric | ssa_mncppc_regional_tax                  | SSA/MNCPPC REGIONAL TAX                  | number    | text        |
| Yes      | numeric metric | ssa_recreation_tax                       | SSA RECREATION TAX                       | number    | text        |
| Yes      | numeric metric | ssa_storm_drainage_tax                   | SSA STORM DRAINAGE TAX                   | number    | text        |
| Yes      | series tag     | ssa_parking_lot_district_tax             | SSA PARKING LOT DISTRICT TAX             | text      | number      |
| Yes      | series tag     | ssa_parking_lot_district                 | SSA PARKING LOT DISTRICT                 | text      | text        |
| Yes      | series tag     | ssa_urban_district_tax                   | SSA URBAN DISTRICT TAX                   | text      | number      |
| Yes      | series tag     | ssa_urban_district                       | SSA URBAN DISTRICT                       | text      | text        |
| Yes      | series tag     | ssa_noise_abatement_district_tax         | SSA NOISE ABATEMENT DISTRICT TAX         | text      | number      |
| Yes      | series tag     | ssa_noise_abatement_district             | SSA NOISE ABATEMENT DISTRICT             | text      | text        |
| Yes      | series tag     | ssa_development_district_tax             | SSA DEVELOPMENT DISTRICT TAX             | text      | number      |
| Yes      | series tag     | ssa_development_district                 | SSA DEVELOPMENT DISTRICT                 | text      | text        |
| Yes      | numeric metric | total_special_service_area_tax           | TOTAL SPECIAL SERVICE AREA TAX           | number    | number      |
| Yes      | numeric metric | total_tax_rate                           | TOTAL TAX RATE                           | number    | number      |
```

## Time Field

```ls
Value = levy_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mdtv-drkr d:2014-01-01T00:00:00.000Z t:ssa_fire_district_tax=0.1360 t:municipal_district="City of Rockville" t:municipal_district_tax=0.6220 m:total_special_service_area_tax=0.177 m:total_tax_rate=1.643 m:ssa_mncppc_advanced_land_acquisition_tax=0.001 m:tax_class=1 m:state_tax=0.112 m:ssa_transit_tax=0.04 m:general_county_tax=0.732

series e:mdtv-drkr d:2014-01-01T00:00:00.000Z t:ssa_fire_district_tax=0.1360 t:ssa_noise_abatement_district="Cabin John" t:ssa_noise_abatement_district_tax=0.0000 m:total_special_service_area_tax=0.276 m:total_tax_rate=1.12 m:ssa_mncppc_advanced_land_acquisition_tax=0.001 m:tax_class=2 m:ssa_mncppc_regional_tax=0.017 m:ssa_mncppc_metro_politan_tax=0.056 m:state_tax=0.112 m:ssa_transit_tax=0.04 m:ssa_recreation_tax=0.023 m:general_county_tax=0.732 m:ssa_storm_drainage_tax=0.003

series e:mdtv-drkr d:2014-01-01T00:00:00.000Z t:ssa_fire_district_tax=0.1360 t:municipal_district="City of Rockville" t:municipal_district_tax=0.0430 m:total_special_service_area_tax=0.177 m:total_tax_rate=1.064 m:ssa_mncppc_advanced_land_acquisition_tax=0.001 m:tax_class=4 m:state_tax=0.112 m:ssa_transit_tax=0.04 m:general_county_tax=0.732
```

## Meta Commands

```ls
metric m:tax_class p:integer l:"TAX CLASS *" d:"Tax class category the property address is located within." t:dataTypeName=number

metric m:general_county_tax p:float l:"GENERAL COUNTY TAX" d:"The General County tax is levied on all property in the County and funds, in part, such basic services as police protection, elementary and secondary education, the community college, transportation, health and social services, and libraries." t:dataTypeName=number

metric m:state_tax p:float l:"STATE TAX" d:"This tax is levied by the State of Maryland for the payment of principal and interest on State bonds." t:dataTypeName=number

metric m:ssa_transit_tax p:float l:"SSA TRANSIT TAX" d:"Transit Tax is levied Countywide and funds public transportation services including the Ride On bus system." t:dataTypeName=number

metric m:ssa_mncppc_advanced_land_acquisition_tax p:float l:"SSA/MNCPPC ADVANCED LAND ACQUISITION TAX" d:"Advance Land Acquisition Tax is levied Countywide and funds land acquisitions by the Maryland-National Capital Park and Planning Commission (M-NCPPC)." t:dataTypeName=number

metric m:ssa_mncppc_metro_politan_tax p:float l:"SSA/MNCPPC METRO-POLITAN TAX" d:"Metropolitan Tax funds M-NCPPC local park facilities and parks programs. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:ssa_mncppc_regional_tax p:float l:"SSA/MNCPPC REGIONAL TAX" d:"Regional Tax funds M-NCPPC planning and administrative programs. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:ssa_recreation_tax p:float l:"SSA RECREATION TAX" d:"Recreation tax funds recreation facilities and programs. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:ssa_storm_drainage_tax p:float l:"SSA STORM DRAINAGE TAX" d:"Storm Drainage Tax funds storm drainage improvements. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:total_special_service_area_tax p:float l:"TOTAL SPECIAL SERVICE AREA TAX" d:"The Special Service Area Tax includes Transit, Fire District, Advanced Land Acquisition, Metropolitan, Regional, Recreation, Storm Drainage, Parking Lot District, Urban District, Noise Abatement District, and Development District taxes." t:dataTypeName=number

metric m:total_tax_rate p:float l:"TOTAL TAX RATE" d:"Total tax rate." t:dataTypeName=number

entity e:mdtv-drkr l:"Real Property Tax Rates - Levy Year 2014 and Beyond" t:url=https://data.montgomerycountymd.gov/api/views/mdtv-drkr

property e:mdtv-drkr t:meta.view v:id=mdtv-drkr v:category=Finance/Tax/Property v:averageRating=0 v:name="Real Property Tax Rates - Levy Year 2014 and Beyond"

property e:mdtv-drkr t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:mdtv-drkr t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| levy_year | tax_class | general_county_tax | state_tax | municipal_district_tax | municipal_district   | ssa_transit_tax | ssa_fire_district_tax | ssa_mncppc_advanced_land_acquisition_tax | ssa_mncppc_metro_politan_tax | ssa_mncppc_regional_tax | ssa_recreation_tax | ssa_storm_drainage_tax | ssa_parking_lot_district_tax | ssa_parking_lot_district | ssa_urban_district_tax | ssa_urban_district | ssa_noise_abatement_district_tax | ssa_noise_abatement_district | ssa_development_district_tax | ssa_development_district | total_special_service_area_tax | total_tax_rate | 
| ========= | ========= | ================== | ========= | ====================== | ==================== | =============== | ===================== | ======================================== | ============================ | ======================= | ================== | ====================== | ============================ | ======================== | ====================== | ================== | ================================ | ============================ | ============================ | ======================== | ============================== | ============== | 
| 2014      | 1         | 0.7320             | 0.1120    | 0.6220                 | City of Rockville    | 0.0400          | 0.1360                | 0.0010                                   |                              |                         |                    |                        |                              |                          |                        |                    |                                  |                              |                              |                          | 0.1770                         | 1.6430         | 
| 2014      | 2         | 0.7320             | 0.1120    |                        |                      | 0.0400          | 0.1360                | 0.0010                                   | 0.0560                       | 0.0170                  | 0.0230             | 0.0030                 |                              |                          |                        |                    | 0.0000                           | Cabin John                   |                              |                          | 0.2760                         | 1.1200         | 
| 2014      | 4         | 0.7320             | 0.1120    | 0.0430                 | City of Rockville    | 0.0400          | 0.1360                | 0.0010                                   |                              |                         |                    |                        |                              |                          |                        |                    |                                  |                              |                              |                          | 0.1770                         | 1.0640         | 
| 2014      | 5         | 0.7320             | 0.1120    | 0.2920                 | City of Rockville    | 0.0400          | 0.1360                | 0.0010                                   |                              |                         |                    |                        |                              |                          |                        |                    |                                  |                              |                              |                          | 0.1770                         | 1.3130         | 
| 2014      | 9         | 0.7320             | 0.1120    | 0.0800                 | Town of Somerset     | 0.0400          | 0.1360                | 0.0010                                   | 0.0560                       | 0.0170                  | 0.0230             | 0.0030                 |                              |                          |                        |                    |                                  |                              |                              |                          | 0.2760                         | 1.2000         | 
| 2014      | 14        | 0.7320             | 0.1120    | 0.0400                 | Friendship Heights   | 0.0400          | 0.1360                | 0.0010                                   | 0.0560                       | 0.0170                  | 0.0230             |                        |                              |                          |                        |                    |                                  |                              |                              |                          | 0.2730                         | 1.1570         | 
| 2014      | 15        | 0.7320             | 0.1120    | 0.0480                 | Drummond             | 0.0400          | 0.1360                | 0.0010                                   | 0.0560                       | 0.0170                  | 0.0230             | 0.0030                 |                              |                          |                        |                    |                                  |                              |                              |                          | 0.2760                         | 1.1680         | 
| 2014      | 16        | 0.7320             | 0.1120    | 0.2620                 | City of Gaithersburg | 0.0400          | 0.1360                | 0.0010                                   |                              |                         |                    |                        |                              |                          |                        |                    |                                  |                              |                              |                          | 0.1770                         | 1.2830         | 
| 2014      | 17        | 0.7320             | 0.1120    | 0.0400                 | Oakmont              | 0.0400          | 0.1360                | 0.0010                                   | 0.0560                       | 0.0170                  | 0.0230             | 0.0030                 |                              |                          |                        |                    |                                  |                              |                              |                          | 0.2760                         | 1.1600         | 
| 2014      | 19        | 0.7320             | 0.1120    | 0.0850                 | Chevy Chase Village  | 0.0400          | 0.1360                | 0.0010                                   | 0.0560                       | 0.0170                  | 0.0230             | 0.0030                 |                              |                          |                        |                    |                                  |                              |                              |                          | 0.2760                         | 1.2050         | 
```