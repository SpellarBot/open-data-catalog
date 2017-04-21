# Chesapeake Bay Pollution Reduction Activities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chesapeake-bay-pollution-reduction-activities-cdb97) |
| Metadata | [Link](https://data.maryland.gov/api/views/2rth-fybg) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2rth-fybg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2rth-fybg/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2rth-fybg |
| Name | Chesapeake Bay Pollution Reduction Activities |
| Attribution | MDA |
| Category | Energy and Environment |
| Tags | chesapeake bay, cover crops, nitrogen, wastewater treatment, governor's office of performance improvement, bay, baystat, pollution |
| Created | 2012-08-21T19:38:15Z |
| Publication Date | 2014-11-30T23:04:47Z |

## Description

The Governor's Office of Performance Improvement tracks the overall health of the bay in addition to specific restoration actions undertaken by Maryland's state agencies.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                            | Name                                                                                      | Data Type | Render Type |
| ======== | ============== | ===================================================================================== | ========================================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                                           | updated_at                                                                                | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                                                                           | Fiscal Year                                                                               | text      | text        |
| Yes      | numeric metric | certified_cover_crops_acres_planted                                                   | Certified Cover Crops Acres Planted in Chesapeake Bay Watershed (Annually)                | number    | number      |
| Yes      | numeric metric | stormwater_retrofits_acres_retrofitted                                                | Stormwater Retrofits: Pounds of Nitrogen Removed                                          | number    | number      |
| Yes      | numeric metric | stormwater_retrofits_new_acres_retrofitted                                            | Stormwater Retrofits: New Pounds of Nitrogen Removed                                      | number    | number      |
| Yes      | numeric metric | stormwater_retrofits_existing_acres_retrofitted                                       | Stormwater Retrofits: Existing Pounds of Nitrogen Removed                                 | number    | number      |
| Yes      | numeric metric | wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal                 | Wastewater Treatment Plants Retrofitted for Enhanced Nutrient Removal: Total Retrofits    | number    | number      |
| Yes      | numeric metric | wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal_new_plants      | Wastewater Treatment Plants Retrofitted for Enhanced Nutrient Removal: New Retrofits      | number    | number      |
| Yes      | numeric metric | wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal_existing_plants | Wastewater Treatment Plants Retrofitted for Enhanced Nutrient Removal: Existing Retrofits | number    | number      |
| Yes      | numeric metric | natural_filters_on_private_lands                                                      | Natural Filters on Private Lands: Total Acres                                             | number    | number      |
| Yes      | numeric metric | natural_filters_on_private_lands_new_acres                                            | Natural Filters on Private Lands: New Acres                                               | number    | number      |
| Yes      | numeric metric | natural_filters_on_private_lands_existing_acres                                       | Natural Filters on Private Lands: Existing Acres                                          | number    | number      |
| Yes      | numeric metric | agricultural_stream_protection_acres                                                  | Agricultural Stream Protection (Acres)                                                    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2rth-fybg d:2013-09-04T09:27:26.000Z t:fiscal_year=FY2000 m:agricultural_stream_protection_acres=26941 m:natural_filters_on_private_lands_existing_acres=0 m:natural_filters_on_private_lands=13618 m:certified_cover_crops_acres_planted=159773 m:natural_filters_on_private_lands_new_acres=13618

series e:2rth-fybg d:2013-09-04T09:27:26.000Z t:fiscal_year=FY2001 m:agricultural_stream_protection_acres=27426 m:natural_filters_on_private_lands_existing_acres=13618 m:natural_filters_on_private_lands=28005 m:certified_cover_crops_acres_planted=70920 m:natural_filters_on_private_lands_new_acres=14387

series e:2rth-fybg d:2013-09-04T09:27:26.000Z t:fiscal_year=FY2002 m:agricultural_stream_protection_acres=27662 m:natural_filters_on_private_lands_existing_acres=28005 m:natural_filters_on_private_lands=45487 m:certified_cover_crops_acres_planted=97755 m:natural_filters_on_private_lands_new_acres=17482
```

## Meta Commands

```ls
metric m:certified_cover_crops_acres_planted p:integer l:"Certified Cover Crops Acres Planted in Chesapeake Bay Watershed (Annually)" t:dataTypeName=number

metric m:stormwater_retrofits_acres_retrofitted p:integer l:"Stormwater Retrofits: Pounds of Nitrogen Removed" t:dataTypeName=number

metric m:stormwater_retrofits_new_acres_retrofitted p:integer l:"Stormwater Retrofits: New Pounds of Nitrogen Removed" t:dataTypeName=number

metric m:stormwater_retrofits_existing_acres_retrofitted p:integer l:"Stormwater Retrofits: Existing Pounds of Nitrogen Removed" t:dataTypeName=number

metric m:wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal p:integer l:"Wastewater Treatment Plants Retrofitted for Enhanced Nutrient Removal: Total Retrofits" t:dataTypeName=number

metric m:wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal_new_plants p:integer l:"Wastewater Treatment Plants Retrofitted for Enhanced Nutrient Removal: New Retrofits" t:dataTypeName=number

metric m:wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal_existing_plants p:integer l:"Wastewater Treatment Plants Retrofitted for Enhanced Nutrient Removal: Existing Retrofits" t:dataTypeName=number

metric m:natural_filters_on_private_lands p:integer l:"Natural Filters on Private Lands: Total Acres" d:"Cumulative acres of buffers along streams and waterways" t:dataTypeName=number

metric m:natural_filters_on_private_lands_new_acres p:integer l:"Natural Filters on Private Lands: New Acres" t:dataTypeName=number

metric m:natural_filters_on_private_lands_existing_acres p:integer l:"Natural Filters on Private Lands: Existing Acres" t:dataTypeName=number

metric m:agricultural_stream_protection_acres p:integer l:"Agricultural Stream Protection (Acres)" t:dataTypeName=number

entity e:2rth-fybg l:"Chesapeake Bay Pollution Reduction Activities" t:attribution=MDA t:url=https://data.maryland.gov/api/views/2rth-fybg

property e:2rth-fybg t:meta.view v:id=2rth-fybg v:category="Energy and Environment" v:attributionLink=http://mda.maryland.gov/Pages/homepage.aspx v:averageRating=0 v:name="Chesapeake Bay Pollution Reduction Activities" v:attribution=MDA

property e:2rth-fybg t:meta.view.license v:name="Public Domain"

property e:2rth-fybg t:meta.view.owner v:id=n5xi-8ray v:screenName=Laura.Bruner v:displayName=Laura.Bruner

property e:2rth-fybg t:meta.view.tableauthor v:id=n5xi-8ray v:screenName=Laura.Bruner v:roleName=administrator v:displayName=Laura.Bruner
```

## Top Records

```ls
| :updated_at | fiscal_year | certified_cover_crops_acres_planted | stormwater_retrofits_acres_retrofitted | stormwater_retrofits_new_acres_retrofitted | stormwater_retrofits_existing_acres_retrofitted | wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal | wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal_new_plants | wastewater_treatment_plants_retrofitted_for_enhanced_nutrient_removal_existing_plants | natural_filters_on_private_lands | natural_filters_on_private_lands_new_acres | natural_filters_on_private_lands_existing_acres | agricultural_stream_protection_acres | 
| =========== | =========== | =================================== | ====================================== | ========================================== | =============================================== | ===================================================================== | ================================================================================ | ===================================================================================== | ================================ | ========================================== | =============================================== | ==================================== | 
| 1378286846  | FY2000      | 159773                              |                                        |                                            |                                                 |                                                                       |                                                                                  |                                                                                       | 13618                            | 13618                                      | 0                                               | 26941                                | 
| 1378286846  | FY2001      | 70920                               |                                        |                                            |                                                 |                                                                       |                                                                                  |                                                                                       | 28005                            | 14387                                      | 13618                                           | 27426                                | 
| 1378286846  | FY2002      | 97755                               |                                        |                                            |                                                 |                                                                       |                                                                                  |                                                                                       | 45487                            | 17482                                      | 28005                                           | 27662                                | 
| 1378286846  | FY2003      | 113628                              | 26101                                  | 26101                                      | 0                                               |                                                                       |                                                                                  |                                                                                       | 61123                            | 15636                                      | 45487                                           | 27899                                | 
| 1378286846  | FY2004      | 31335                               | 42391                                  | 16290                                      | 26101                                           |                                                                       |                                                                                  |                                                                                       | 69973                            | 8850                                       | 61123                                           | 28681                                | 
| 1378286846  | FY2005      | 52302                               | 58347                                  | 15956                                      | 42391                                           |                                                                       |                                                                                  |                                                                                       | 76725                            | 6752                                       | 69973                                           | 30057                                | 
| 1378286846  | FY2006      | 124800                              | 74706                                  | 16359                                      | 58347                                           | 2                                                                     | 2                                                                                | 0                                                                                     | 79519                            | 2794                                       | 76725                                           | 31266                                | 
| 1378286846  | FY2007      | 232985                              | 90689                                  | 15983                                      | 74706                                           | 5                                                                     | 3                                                                                | 2                                                                                     | 81512                            | 1993                                       | 79519                                           | 33767                                | 
| 1378286846  | FY2008      | 179366                              | 106761                                 | 16072                                      | 90689                                           | 8                                                                     | 3                                                                                | 5                                                                                     | 83395                            | 1883                                       | 81512                                           | 36038                                | 
| 1378286846  | FY2009      | 179366                              | 132453                                 | 25692                                      | 106761                                          | 11                                                                    | 3                                                                                | 8                                                                                     | 86559                            | 3164                                       | 83395                                           | 36792                                | 
```