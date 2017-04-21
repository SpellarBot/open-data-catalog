# Real Property Tax Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-tax-rates-f8580) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/es5m-4wf9) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/es5m-4wf9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/es5m-4wf9/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | es5m-4wf9 |
| Name | Real Property Tax Rates |
| Tags | real, property, tax, rates |
| Created | 2012-10-03T17:26:37Z |
| Publication Date | 2012-11-23T15:45:09Z |

## Description

The Levy Year 2012 real property tax rate dataset reflects all the rates per $100 set each year by the County Council.  These rates are applied to the assessed value of the real property to derive the applicable ad valorem tax.  The fully phased-in assessed value equals the full cash value of the property. The real property tax is levied annually on all taxable land and improvements.  The tax rate schedule is updated annually. A detailed tax rate schedule for all tax classes is available by clicking on ?Tax Rates? under the link for ?County Taxes? when visiting the County website at www.montgomerycountymd.gov/finance or by calling 311 (240-777-0311).

Update Frequency:  Annually

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | tax_class                      | TAX CLASS                      | text      | text        |
| Yes      | numeric metric | general_county_tax             | GENERAL COUNTY TAX             | number    | number      |
| Yes      | numeric metric | state_tax                      | STATE TAX                      | number    | number      |
| Yes      | series tag     | municipal_district_tax         | MUNICIPAL DISTRICT TAX         | text      | number      |
| Yes      | numeric metric | transit_tax                    | TRANSIT TAX                    | number    | number      |
| Yes      | series tag     | fire_district_tax              | FIRE DISTRICT TAX              | text      | number      |
| Yes      | numeric metric | advanced_land_acquisition_tax  | ADVANCED LAND ACQUISITION TAX  | number    | number      |
| Yes      | numeric metric | metro_politan_tax              | METRO-POLITAN TAX              | number    | number      |
| Yes      | numeric metric | regional_tax                   | REGIONAL TAX                   | number    | number      |
| Yes      | numeric metric | recreation_tax                 | RECREATION TAX                 | number    | number      |
| Yes      | numeric metric | storm_drainage_tax             | STORM DRAINAGE TAX             | number    | number      |
| Yes      | series tag     | parking_lot_district_tax       | PARKING LOT DISTRICT TAX       | text      | number      |
| Yes      | series tag     | urban_district_tax             | URBAN DISTRICT TAX             | text      | number      |
| Yes      | series tag     | noise_abatement_district_tax   | NOISE ABATEMENT DISTRICT TAX   | text      | text        |
| Yes      | series tag     | development_district_tax       | DEVELOPMENT DISTRICT TAX       | text      | text        |
| Yes      | numeric metric | total_special_service_area_tax | TOTAL SPECIAL SERVICE AREA TAX | number    | number      |
| Yes      | numeric metric | total_tax_rate                 | TOTAL TAX RATE                 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:es5m-4wf9 d:2012-11-21T09:53:14.000Z t:fire_district_tax=0.134 t:tax_class=R001 t:municipal_district_tax=0.6220 m:total_special_service_area_tax=0.183 m:transit_tax=0.048 m:total_tax_rate=1.641 m:advanced_land_acquisition_tax=0.001 m:state_tax=0.112 m:general_county_tax=0.724

series e:es5m-4wf9 d:2012-11-21T09:53:14.000Z t:fire_district_tax=0.134 t:tax_class=R002 t:noise_abatement_district_tax=0.010 m:storm_drainage_tax=0.003 m:total_special_service_area_tax=0.289 m:transit_tax=0.048 m:recreation_tax=0.021 m:total_tax_rate=1.125 m:regional_tax=0.018 m:metro_politan_tax=0.054 m:advanced_land_acquisition_tax=0.001 m:state_tax=0.112 m:general_county_tax=0.724

series e:es5m-4wf9 d:2012-11-21T09:53:14.000Z t:fire_district_tax=0.134 t:tax_class=R004 t:municipal_district_tax=0.0490 m:total_special_service_area_tax=0.183 m:transit_tax=0.048 m:total_tax_rate=1.068 m:advanced_land_acquisition_tax=0.001 m:state_tax=0.112 m:general_county_tax=0.724
```

## Meta Commands

```ls
metric m:general_county_tax p:float l:"GENERAL COUNTY TAX" d:"The General County tax is levied on all property in the County and funds, in part, such basic services as police protection, elementary and secondary education, the community college, transportation, health and social services, and libraries." t:dataTypeName=number

metric m:state_tax p:float l:"STATE TAX" d:"This tax is levied by the State of Maryland for the payment of principal and interest on State bonds." t:dataTypeName=number

metric m:transit_tax p:float l:"TRANSIT TAX" d:"Transit Tax is levied Countywide and funds public transportation services including the Ride On bus system." t:dataTypeName=number

metric m:advanced_land_acquisition_tax p:float l:"ADVANCED LAND ACQUISITION TAX" d:"Advance Land Acquisition Tax is levied Countywide and funds land acquisitions by the Maryland-National Capital Park and Planning Commission (M-NCPPC)." t:dataTypeName=number

metric m:metro_politan_tax p:float l:"METRO-POLITAN TAX" d:"Metropolitan Tax funds M-NCPPC local park facilities and parks programs. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:regional_tax p:float l:"REGIONAL TAX" d:"Regional Tax funds M-NCPPC planning and administrative programs. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:recreation_tax p:float l:"RECREATION TAX" d:"Recreation tax funds recreation facilities and programs. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:storm_drainage_tax p:float l:"STORM DRAINAGE TAX" d:"Storm Drainage Tax funds storm drainage improvements. Whether a taxpayer pays one of these special area taxes depends on where the property is located." t:dataTypeName=number

metric m:total_special_service_area_tax p:float l:"TOTAL SPECIAL SERVICE AREA TAX" d:"The Special Service Area Tax includes Transit, Fire District, Advanced Land Acquisition, Metropolitan, Regional, Recreation, Storm Drainage, Parking Lot District, Urban District, Noise Abatement District, and Development District taxes." t:dataTypeName=number

metric m:total_tax_rate p:float l:"TOTAL TAX RATE" t:dataTypeName=number

entity e:es5m-4wf9 l:"Real Property Tax Rates" t:url=https://data.montgomerycountymd.gov/api/views/es5m-4wf9

property e:es5m-4wf9 t:meta.view v:id=es5m-4wf9 v:averageRating=0 v:name="Real Property Tax Rates"

property e:es5m-4wf9 t:meta.view.owner v:id=fnci-gphj v:screenName="MC Open Data" v:displayName="MC Open Data"

property e:es5m-4wf9 t:meta.view.tableauthor v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"
```

## Top Records

```ls
| :updated_at | tax_class | general_county_tax | state_tax | municipal_district_tax | transit_tax | fire_district_tax | advanced_land_acquisition_tax | metro_politan_tax | regional_tax | recreation_tax | storm_drainage_tax | parking_lot_district_tax | urban_district_tax | noise_abatement_district_tax | development_district_tax | total_special_service_area_tax | total_tax_rate | 
| =========== | ========= | ================== | ========= | ====================== | =========== | ================= | ============================= | ================= | ============ | ============== | ================== | ======================== | ================== | ============================ | ======================== | ============================== | ============== | 
| 1353491594  | R001      | 0.724              | 0.112     | 0.6220                 | 0.048       | 0.134             | 0.001                         |                   |              |                |                    |                          |                    |                              |                          | 0.183                          | 1.6410         | 
| 1353491594  | R002      | 0.724              | 0.112     |                        | 0.048       | 0.134             | 0.001                         | 0.054             | 0.018        | 0.021          | 0.003              |                          |                    | 0.010                        |                          | 0.289                          | 1.1250         | 
| 1353491594  | R004      | 0.724              | 0.112     | 0.0490                 | 0.048       | 0.134             | 0.001                         |                   |              |                |                    |                          |                    |                              |                          | 0.183                          | 1.0680         | 
| 1353491594  | R005      | 0.724              | 0.112     | 0.2920                 | 0.048       | 0.134             | 0.001                         |                   |              |                |                    |                          |                    |                              |                          | 0.183                          | 1.3110         | 
| 1353491594  | R009      | 0.724              | 0.112     | 0.0800                 | 0.048       | 0.134             | 0.001                         | 0.054             | 0.018        | 0.021          | 0.003              |                          |                    |                              |                          | 0.279                          | 1.1950         | 
| 1353491594  | R014      | 0.724              | 0.112     | 0.0400                 | 0.048       | 0.134             | 0.001                         | 0.054             | 0.018        | 0.021          |                    |                          |                    |                              |                          | 0.276                          | 1.1520         | 
| 1353491594  | R015      | 0.724              | 0.112     | 0.0480                 | 0.048       | 0.134             | 0.001                         | 0.054             | 0.018        | 0.021          | 0.003              |                          |                    |                              |                          | 0.279                          | 1.1630         | 
| 1353491594  | R016      | 0.724              | 0.112     | 0.2620                 | 0.048       | 0.134             | 0.001                         |                   |              |                |                    |                          |                    |                              |                          | 0.183                          | 1.2810         | 
| 1353491594  | R017      | 0.724              | 0.112     | 0.0400                 | 0.048       | 0.134             | 0.001                         | 0.054             | 0.018        | 0.021          | 0.003              |                          |                    |                              |                          | 0.279                          | 1.1550         | 
| 1353491594  | R019      | 0.724              | 0.112     | 0.1005                 | 0.048       | 0.134             | 0.001                         | 0.054             | 0.018        | 0.021          | 0.003              |                          |                    |                              |                          | 0.279                          | 1.2155         | 
```