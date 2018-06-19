# Real Property Tax - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-tax-2016) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/uvy4-94zr) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/uvy4-94zr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/uvy4-94zr/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | uvy4-94zr |
| Name | Real Property Tax - 2016 |
| Category | Finance/Tax/Property |
| Tags | tax, taxes, property, resident, treasury, bill, credits, house |
| Created | 2016-02-11T20:43:42Z |
| Publication Date | 2016-07-08T13:39:49Z |

## Description

This data represents all of the County?s residential real estate properties and all of the associated tax charges and credits with that property processed at the annual billing in July of each year, excluding any subsequent billing additions and/or revisions throughout the year.  This dataset excludes the names of the property owners.  The addresses in this database represent the address of the property.  For more information about the individual taxes and credits, please go to http://www.montgomerycountymd.gov/finance/taxes/faqs.html#credit. 

Update Frequency:  Updated Annually in July

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| Yes      | series tag     | parcel_code                    | PARCEL CODE                      | text      | text        |
| Yes      | series tag     | residence                      | RESIDENCE                        | text      | text        |
| No       |                | property_address               | PROPERTY ADDRESS                 | text      | text        |
| Yes      | series tag     | zip_code                       | ZIP CODE                         | text      | number      |
| Yes      | numeric metric | bill_total                     | BILL TOTAL                       | money     | money       |
| Yes      | numeric metric | state_property_tax             | STATE PROPERTY TAX               | money     | money       |
| Yes      | numeric metric | county_property_tax            | COUNTY PROPERTY TAX              | money     | money       |
| Yes      | numeric metric | barnesville_property_tax       | BARNESVILLE PROPERTY TAX         | money     | money       |
| Yes      | numeric metric | battery_park_property_tax      | BATTERY PARK PROPERTY TAX        | money     | money       |
| Yes      | numeric metric | brookeville_property_tax       | BROOKEVILLE PROPERTY TAX         | money     | money       |
| Yes      | numeric metric | ch_ch_section_3_property_tax   | CH CH SECTION 3 PROPERTY TAX     | money     | money       |
| Yes      | numeric metric | ch_ch_section_5_property_tax   | CH CH SECTION 5 PROPERTY TAX     | money     | money       |
| Yes      | numeric metric | ch_ch_town_property_tax        | CH CH TOWN PROPERTY TAX          | money     | money       |
| Yes      | numeric metric | ch_ch_view_property_tax        | CH CH VIEW PROPERTY TAX          | money     | money       |
| Yes      | numeric metric | ch_ch_village_property_tax     | CH CH VILLAGE PROPERTY TAX       | money     | money       |
| Yes      | numeric metric | drummond_property_tax          | DRUMMOND PROPERTY TAX            | money     | money       |
| Yes      | numeric metric | friendship_hts_property_tax    | FRIENDSHIP HTS PROPERTY TAX      | money     | money       |
| Yes      | numeric metric | gaithersburg_property_tax      | GAITHERSBURG PROPERTY TAX        | money     | money       |
| Yes      | numeric metric | garrett_park_property_tax      | GARRETT PARK PROPERTY TAX        | money     | money       |
| Yes      | numeric metric | glen_echo_property_tax         | GLEN ECHO PROPERTY TAX           | money     | money       |
| Yes      | numeric metric | kensington_property_tax        | KENSINGTON PROPERTY TAX          | money     | money       |
| Yes      | numeric metric | laytonsville_property_tax      | LAYTONSVILLE PROPERTY TAX        | money     | money       |
| Yes      | numeric metric | martins_addition_property_tax  | MARTINS ADDITION PROPERTY TAX    | money     | money       |
| Yes      | numeric metric | north_ch_ch_property_tax       | NORTH CH CH PROPERTY TAX         | money     | money       |
| Yes      | numeric metric | oakmont_property_tax           | OAKMONT PROPERTY TAX             | money     | money       |
| Yes      | numeric metric | poolesville_property_tax       | POOLESVILLE PROPERTY TAX         | money     | money       |
| Yes      | numeric metric | rockville_property_tax         | ROCKVILLE PROPERTY TAX           | money     | money       |
| Yes      | numeric metric | somerset_property_tax          | SOMERSET PROPERTY TAX            | money     | money       |
| Yes      | numeric metric | takoma_park_property_tax       | TAKOMA PARK PROPERTY TAX         | money     | money       |
| Yes      | numeric metric | washington_grove_property_tax  | WASHINGTON GROVE PROPERTY TAX    | money     | money       |
| Yes      | numeric metric | bay_restoration_fund           | BAY RESTORATION FUND             | money     | money       |
| Yes      | numeric metric | ch_ch_section_3_charge_rh      | CH CH SECTION 3 CHARGE-RH        | money     | money       |
| Yes      | numeric metric | ch_ch_section_5_charge_rj      | CH CH SECTION 5 CHARGE-RJ        | money     | money       |
| Yes      | numeric metric | ch_ch_town_charge_ri           | CH CH TOWN CHARGE-RI             | money     | money       |
| Yes      | numeric metric | ch_ch_village_charge_rg        | CH CH VILLAGE CHARGE-RG          | money     | money       |
| Yes      | numeric metric | dbu_road                       | DBU ROAD                         | money     | money       |
| Yes      | numeric metric | dev_dist_special_assessment_kv | DEV DIST SPECIAL ASSESSMENT - KV | money     | money       |
| Yes      | numeric metric | dev_dist_special_assessment_wg | DEV DIST SPECIAL ASSESSMENT-WG   | money     | money       |
| Yes      | numeric metric | dev_dist_special_tax_kv        | DEV DIST SPECIAL TAX - KV        | money     | money       |
| Yes      | numeric metric | dev_dist_special_tax_wg        | DEV DIST SPECIAL TAX -WG         | money     | money       |
| Yes      | numeric metric | gaithersburg_charge_rm         | GAITHERSBURG CHARGE-RM           | money     | money       |
| Yes      | numeric metric | gaithersburg_stormwater_fee    | GAITHERSBURG STORMWATER FEE      | money     | money       |
| Yes      | numeric metric | garrett_park_charge_rl         | GARRETT PARK CHARGE-RL           | money     | money       |
| Yes      | numeric metric | martins_addition_charge_rk     | MARTINS ADDITION CHARGE-RK       | money     | money       |
| Yes      | numeric metric | rockville_front_foot_chg       | ROCKVILLE FRONT FOOT CHG         | money     | money       |
| Yes      | numeric metric | rockville_stormwater_mgmt_fee  | ROCKVILLE STORMWATER MGMT FEE    | money     | money       |
| Yes      | numeric metric | solid_waste_charge             | SOLID WASTE CHARGE               | money     | money       |
| Yes      | numeric metric | takoma_park_special            | TAKOMA PARK SPECIAL              | money     | money       |
| Yes      | numeric metric | washington_grove_rn            | WASHINGTON GROVE -RN             | money     | money       |
| Yes      | numeric metric | washington_grove_serv_chg      | WASHINGTON GROVE SERV.CHG        | money     | money       |
| Yes      | numeric metric | white_flint_sp_tax             | WHITE FLINT SP TAX               | money     | money       |
| Yes      | numeric metric | water_qual_protect_chg_mfr     | WATER QUAL PROTECT CHG (MFR)     | money     | money       |
| Yes      | numeric metric | water_qual_protect_chg_nr      | WATER QUAL PROTECT CHG (NR)      | money     | money       |
| Yes      | numeric metric | water_qual_protect_chg_rsfa    | WATER QUAL PROTECT CHG (RSFA)    | money     | money       |
| Yes      | numeric metric | water_qual_protect_chg_rsfd    | WATER QUAL PROTECT CHG (RSFD)    | money     | money       |
| Yes      | numeric metric | water_quality_protect_chg_ag   | WATER QUALITY PROTECT CHG (AG)   | money     | money       |
| Yes      | numeric metric | water_quality_protect_chg_ex   | WATER QUALITY PROTECT CHG (EX)   | money     | money       |
| Yes      | numeric metric | water_quality_protect_chg_gov  | WATER QUALITY PROTECT CHG (GOV)  | money     | money       |
| Yes      | numeric metric | water_quality_protect_chg_sfr  | WATER QUALITY PROTECT CHG (SFR)  | money     | money       |
| Yes      | numeric metric | water_quality_protect_chg_np   | WATER QUALITY PROTECT CHG (NP)   | money     | money       |
| Yes      | numeric metric | wssc_connection_fee_chg        | WSSC CONNECTION FEE CHG          | money     | money       |
| Yes      | numeric metric | wssc_front_foot_benefit_chg    | WSSC FRONT FOOT BENEFIT CHG      | money     | money       |
| Yes      | numeric metric | clean_lien_demolition          | CLEAN & LIEN/DEMOLITION          | money     | money       |
| Yes      | numeric metric | total                          | TOTAL                            | money     | money       |
| Yes      | numeric metric | state_homestead_credit         | STATE HOMESTEAD CREDIT           | money     | money       |
| Yes      | numeric metric | county_homestead_credit        | COUNTY HOMESTEAD CREDIT          | money     | money       |
| Yes      | numeric metric | state_homeowner_s_credit       | STATE HOMEOWNER'S CREDIT         | money     | money       |
| Yes      | numeric metric | county_homeowner_s_credit      | COUNTY HOMEOWNER'S CREDIT        | money     | money       |
| Yes      | numeric metric | county_property_tax_credit     | COUNTY PROPERTY TAX CREDIT       | money     | money       |
| Yes      | numeric metric | municipal_homeowners_credit    | MUNICIPAL HOMEOWNERS' CREDIT     | money     | money       |
| Yes      | numeric metric | municipal_homestead_credit     | MUNICIPAL HOMESTEAD CREDIT       | money     | money       |
| Yes      | numeric metric | rockville_property_tax_credit  | ROCKVILLE PROPERTY TAX CREDIT    | money     | money       |
| Yes      | numeric metric | full_parking_lot_credit        | FULL PARKING LOT CREDIT          | money     | money       |
| Yes      | numeric metric | partial_parking_lot_credit     | PARTIAL PARKING LOT CREDIT       | money     | money       |
| Yes      | numeric metric | art_s_entertainment_credit     | ART'S & ENTERTAINMENT CREDIT     | money     | money       |
| Yes      | numeric metric | brownfield_s_county_tax_credit | BROWNFIELD'S COUNTY TAX CREDIT   | money     | money       |
| Yes      | numeric metric | brownfields_state_tax_credit   | BROWNFIELDS STATE TAX CREDIT     | money     | money       |
| Yes      | numeric metric | business_incubator_tax_credit  | BUSINESS INCUBATOR TAX CREDIT    | money     | money       |
| Yes      | numeric metric | conservation_energy_credit     | CONSERVATION ENERGY CREDIT       | money     | money       |
| Yes      | numeric metric | conservation_land_tax_credit   | CONSERVATION LAND TAX CREDIT     | money     | money       |
| Yes      | numeric metric | day_car_tax_credit             | DAY CAR TAX CREDIT               | money     | money       |
| Yes      | numeric metric | design_for_life_tax_credit     | DESIGN FOR LIFE TAX CREDIT       | money     | money       |
| Yes      | numeric metric | enterprise_zone_municipal      | ENTERPRISE ZONE MUNICIPAL        | money     | money       |
| Yes      | numeric metric | enterprise_zone_tax_credit     | ENTERPRISE ZONE TAX CREDIT       | money     | money       |
| Yes      | numeric metric | excess_homeowner_credit        | EXCESS HOMEOWNER CREDIT          | money     | money       |
| Yes      | numeric metric | fallen_officer_rescue_credit   | FALLEN OFFICER/RESCUE CREDIT     | money     | money       |
| Yes      | numeric metric | fire_sprinkler_tax_credit      | FIRE SPRINKLER TAX CREDIT        | money     | money       |
| Yes      | numeric metric | green_building_tax_credit      | GREEN BUILDING TAX CREDIT        | money     | money       |
| Yes      | numeric metric | historic_preservation_credit   | HISTORIC PRESERVATION CREDIT     | money     | money       |
| Yes      | numeric metric | municipal_swimclub             | MUNICIPAL SWIMCLUB               | money     | money       |
| Yes      | numeric metric | new_jobs_tax_credit            | NEW JOBS TAX CREDIT              | money     | money       |
| Yes      | numeric metric | religious_organizations_credit | RELIGIOUS ORGANIZATIONS CREDIT   | money     | money       |
| Yes      | numeric metric | renewable_energy_credit        | RENEWABLE ENERGY CREDIT          | money     | money       |
| Yes      | numeric metric | special_area_homestead_credit  | SPECIAL AREA HOMESTEAD CREDIT    | money     | money       |
| Yes      | numeric metric | swimclub                       | SWIMCLUB                         | money     | money       |
| Yes      | numeric metric | total_credits                  | TOTAL CREDITS                    | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = property_address
```

## Data Commands

```ls
series e:uvy4-94zr d:2016-01-01T00:00:00.000Z t:residence="NOT A PRINCIPAL RESIDENCE" t:zip_code=20912 t:parcel_code=1407612 m:total=8746.66 m:municipal_homeowners_credit=0 m:glen_echo_property_tax=0 m:water_quality_protect_chg_ex=0 m:garrett_park_charge_rl=0 m:washington_grove_serv_chg=0 m:state_homeowner_s_credit=0 m:water_quality_protect_chg_ag=0 m:water_quality_protect_chg_np=0 m:art_s_entertainment_credit=0 m:gaithersburg_charge_rm=0 m:water_qual_protect_chg_mfr=0 m:ch_ch_town_property_tax=0 m:municipal_homestead_credit=0 m:municipal_swimclub=0 m:county_property_tax=6334.04 m:kensington_property_tax=0 m:drummond_property_tax=0 m:conservation_energy_credit=0 m:somerset_property_tax=0 m:laytonsville_property_tax=0 m:barnesville_property_tax=0 m:total_credits=0 m:washington_grove_property_tax=0 m:battery_park_property_tax=0 m:ch_ch_view_property_tax=0 m:gaithersburg_stormwater_fee=0 m:state_homestead_credit=0 m:ch_ch_village_charge_rg=0 m:poolesville_property_tax=0 m:dev_dist_special_tax_wg=0 m:new_jobs_tax_credit=0 m:gaithersburg_property_tax=0 m:oakmont_property_tax=0 m:wssc_connection_fee_chg=0 m:conservation_land_tax_credit=0 m:renewable_energy_credit=0 m:bill_total=8746.66 m:county_property_tax_credit=0 m:fire_sprinkler_tax_credit=0 m:design_for_life_tax_credit=0 m:rockville_front_foot_chg=0 m:washington_grove_rn=0 m:state_property_tax=683.31 m:water_qual_protect_chg_nr=55.49 m:ch_ch_village_property_tax=0 m:rockville_property_tax_credit=0 m:takoma_park_property_tax=0 m:county_homestead_credit=0 m:rockville_stormwater_mgmt_fee=0 m:water_qual_protect_chg_rsfa=0 m:partial_parking_lot_credit=0 m:dbu_road=0 m:water_qual_protect_chg_rsfd=0 m:dev_dist_special_assessment_kv=0 m:north_ch_ch_property_tax=0 m:brownfield_s_county_tax_credit=0 m:green_building_tax_credit=0 m:water_quality_protect_chg_gov=0 m:martins_addition_charge_rk=0 m:bay_restoration_fund=0 m:friendship_hts_property_tax=0 m:clean_lien_demolition=0 m:brookeville_property_tax=0 m:day_car_tax_credit=0 m:full_parking_lot_credit=0 m:business_incubator_tax_credit=0 m:takoma_park_special=0 m:wssc_front_foot_benefit_chg=0 m:dev_dist_special_assessment_wg=0 m:martins_addition_property_tax=0 m:county_homeowner_s_credit=0 m:brownfields_state_tax_credit=0 m:ch_ch_section_3_charge_rh=0 m:white_flint_sp_tax=0 m:fallen_officer_rescue_credit=0 m:excess_homeowner_credit=0 m:religious_organizations_credit=0 m:water_quality_protect_chg_sfr=0 m:historic_preservation_credit=0 m:rockville_property_tax=0 m:enterprise_zone_tax_credit=0 m:ch_ch_town_charge_ri=0 m:ch_ch_section_5_property_tax=0 m:ch_ch_section_3_property_tax=0 m:solid_waste_charge=1673.82 m:dev_dist_special_tax_kv=0 m:garrett_park_property_tax=0 m:special_area_homestead_credit=0 m:swimclub=0 m:ch_ch_section_5_charge_rj=0 m:enterprise_zone_municipal=0

series e:uvy4-94zr d:2016-01-01T00:00:00.000Z t:residence="PRINCIPAL RESIDENCE" t:zip_code=20910 t:parcel_code=1410346 m:total=5417.41 m:municipal_homeowners_credit=0 m:glen_echo_property_tax=0 m:water_quality_protect_chg_ex=0 m:garrett_park_charge_rl=0 m:washington_grove_serv_chg=0 m:state_homeowner_s_credit=0 m:water_quality_protect_chg_ag=0 m:water_quality_protect_chg_np=0 m:art_s_entertainment_credit=0 m:gaithersburg_charge_rm=0 m:water_qual_protect_chg_mfr=0 m:ch_ch_town_property_tax=0 m:municipal_homestead_credit=0 m:municipal_swimclub=0 m:county_property_tax=4467.37 m:kensington_property_tax=0 m:drummond_property_tax=0 m:conservation_energy_credit=0 m:somerset_property_tax=0 m:laytonsville_property_tax=0 m:barnesville_property_tax=0 m:total_credits=-692 m:washington_grove_property_tax=0 m:battery_park_property_tax=0 m:ch_ch_view_property_tax=0 m:gaithersburg_stormwater_fee=0 m:state_homestead_credit=0 m:ch_ch_village_charge_rg=0 m:poolesville_property_tax=0 m:dev_dist_special_tax_wg=0 m:new_jobs_tax_credit=0 m:gaithersburg_property_tax=0 m:oakmont_property_tax=0 m:wssc_connection_fee_chg=0 m:conservation_land_tax_credit=0 m:renewable_energy_credit=0 m:bill_total=4725.41 m:county_property_tax_credit=-692 m:fire_sprinkler_tax_credit=0 m:design_for_life_tax_credit=0 m:rockville_front_foot_chg=0 m:washington_grove_rn=0 m:state_property_tax=481.94 m:water_qual_protect_chg_nr=0 m:ch_ch_village_property_tax=0 m:rockville_property_tax_credit=0 m:takoma_park_property_tax=0 m:county_homestead_credit=0 m:rockville_stormwater_mgmt_fee=0 m:water_qual_protect_chg_rsfa=0 m:partial_parking_lot_credit=0 m:dbu_road=0 m:water_qual_protect_chg_rsfd=0 m:dev_dist_special_assessment_kv=0 m:north_ch_ch_property_tax=0 m:brownfield_s_county_tax_credit=0 m:green_building_tax_credit=0 m:water_quality_protect_chg_gov=0 m:martins_addition_charge_rk=0 m:bay_restoration_fund=0 m:friendship_hts_property_tax=0 m:clean_lien_demolition=0 m:brookeville_property_tax=0 m:day_car_tax_credit=0 m:full_parking_lot_credit=0 m:business_incubator_tax_credit=0 m:takoma_park_special=0 m:wssc_front_foot_benefit_chg=0 m:dev_dist_special_assessment_wg=0 m:martins_addition_property_tax=0 m:county_homeowner_s_credit=0 m:brownfields_state_tax_credit=0 m:ch_ch_section_3_charge_rh=0 m:white_flint_sp_tax=0 m:fallen_officer_rescue_credit=0 m:excess_homeowner_credit=0 m:religious_organizations_credit=0 m:water_quality_protect_chg_sfr=95 m:historic_preservation_credit=0 m:rockville_property_tax=0 m:enterprise_zone_tax_credit=0 m:ch_ch_town_charge_ri=0 m:ch_ch_section_5_property_tax=0 m:ch_ch_section_3_property_tax=0 m:solid_waste_charge=373.1 m:dev_dist_special_tax_kv=0 m:garrett_park_property_tax=0 m:special_area_homestead_credit=0 m:swimclub=0 m:ch_ch_section_5_charge_rj=0 m:enterprise_zone_municipal=0

series e:uvy4-94zr d:2016-01-01T00:00:00.000Z t:residence="PRINCIPAL RESIDENCE" t:zip_code=20853 t:parcel_code=1411170 m:total=3609.29 m:municipal_homeowners_credit=0 m:glen_echo_property_tax=0 m:water_quality_protect_chg_ex=0 m:garrett_park_charge_rl=0 m:washington_grove_serv_chg=0 m:state_homeowner_s_credit=0 m:water_quality_protect_chg_ag=0 m:water_quality_protect_chg_np=0 m:art_s_entertainment_credit=0 m:gaithersburg_charge_rm=0 m:water_qual_protect_chg_mfr=0 m:ch_ch_town_property_tax=0 m:municipal_homestead_credit=0 m:municipal_swimclub=0 m:county_property_tax=2835.32 m:kensington_property_tax=0 m:drummond_property_tax=0 m:conservation_energy_credit=0 m:somerset_property_tax=0 m:laytonsville_property_tax=0 m:barnesville_property_tax=0 m:total_credits=-692 m:washington_grove_property_tax=0 m:battery_park_property_tax=0 m:ch_ch_view_property_tax=0 m:gaithersburg_stormwater_fee=0 m:state_homestead_credit=0 m:ch_ch_village_charge_rg=0 m:poolesville_property_tax=0 m:dev_dist_special_tax_wg=0 m:new_jobs_tax_credit=0 m:gaithersburg_property_tax=0 m:oakmont_property_tax=0 m:wssc_connection_fee_chg=0 m:conservation_land_tax_credit=0 m:renewable_energy_credit=0 m:bill_total=2917.29 m:county_property_tax_credit=-692 m:fire_sprinkler_tax_credit=0 m:design_for_life_tax_credit=0 m:rockville_front_foot_chg=0 m:washington_grove_rn=0 m:state_property_tax=305.87 m:water_qual_protect_chg_nr=0 m:ch_ch_village_property_tax=0 m:rockville_property_tax_credit=0 m:takoma_park_property_tax=0 m:county_homestead_credit=0 m:rockville_stormwater_mgmt_fee=0 m:water_qual_protect_chg_rsfa=0 m:partial_parking_lot_credit=0 m:dbu_road=0 m:water_qual_protect_chg_rsfd=0 m:dev_dist_special_assessment_kv=0 m:north_ch_ch_property_tax=0 m:brownfield_s_county_tax_credit=0 m:green_building_tax_credit=0 m:water_quality_protect_chg_gov=0 m:martins_addition_charge_rk=0 m:bay_restoration_fund=0 m:friendship_hts_property_tax=0 m:clean_lien_demolition=0 m:brookeville_property_tax=0 m:day_car_tax_credit=0 m:full_parking_lot_credit=0 m:business_incubator_tax_credit=0 m:takoma_park_special=0 m:wssc_front_foot_benefit_chg=0 m:dev_dist_special_assessment_wg=0 m:martins_addition_property_tax=0 m:county_homeowner_s_credit=0 m:brownfields_state_tax_credit=0 m:ch_ch_section_3_charge_rh=0 m:white_flint_sp_tax=0 m:fallen_officer_rescue_credit=0 m:excess_homeowner_credit=0 m:religious_organizations_credit=0 m:water_quality_protect_chg_sfr=95 m:historic_preservation_credit=0 m:rockville_property_tax=0 m:enterprise_zone_tax_credit=0 m:ch_ch_town_charge_ri=0 m:ch_ch_section_5_property_tax=0 m:ch_ch_section_3_property_tax=0 m:solid_waste_charge=373.1 m:dev_dist_special_tax_kv=0 m:garrett_park_property_tax=0 m:special_area_homestead_credit=0 m:swimclub=0 m:ch_ch_section_5_charge_rj=0 m:enterprise_zone_municipal=0
```

## Meta Commands

```ls
metric m:bill_total p:double l:"BILL TOTAL" t:dataTypeName=money

metric m:state_property_tax p:double l:"STATE PROPERTY TAX" t:dataTypeName=money

metric m:county_property_tax p:double l:"COUNTY PROPERTY TAX" t:dataTypeName=money

metric m:barnesville_property_tax p:double l:"BARNESVILLE PROPERTY TAX" t:dataTypeName=money

metric m:battery_park_property_tax p:double l:"BATTERY PARK PROPERTY TAX" t:dataTypeName=money

metric m:brookeville_property_tax p:double l:"BROOKEVILLE PROPERTY TAX" t:dataTypeName=money

metric m:ch_ch_section_3_property_tax p:double l:"CH CH SECTION 3 PROPERTY TAX" t:dataTypeName=money

metric m:ch_ch_section_5_property_tax p:double l:"CH CH SECTION 5 PROPERTY TAX" t:dataTypeName=money

metric m:ch_ch_town_property_tax p:double l:"CH CH TOWN PROPERTY TAX" t:dataTypeName=money

metric m:ch_ch_view_property_tax p:double l:"CH CH VIEW PROPERTY TAX" t:dataTypeName=money

metric m:ch_ch_village_property_tax p:double l:"CH CH VILLAGE PROPERTY TAX" t:dataTypeName=money

metric m:drummond_property_tax p:double l:"DRUMMOND PROPERTY TAX" t:dataTypeName=money

metric m:friendship_hts_property_tax p:double l:"FRIENDSHIP HTS PROPERTY TAX" t:dataTypeName=money

metric m:gaithersburg_property_tax p:double l:"GAITHERSBURG PROPERTY TAX" t:dataTypeName=money

metric m:garrett_park_property_tax p:double l:"GARRETT PARK PROPERTY TAX" t:dataTypeName=money

metric m:glen_echo_property_tax p:double l:"GLEN ECHO PROPERTY TAX" t:dataTypeName=money

metric m:kensington_property_tax p:double l:"KENSINGTON PROPERTY TAX" t:dataTypeName=money

metric m:laytonsville_property_tax p:double l:"LAYTONSVILLE PROPERTY TAX" t:dataTypeName=money

metric m:martins_addition_property_tax p:double l:"MARTINS ADDITION PROPERTY TAX" t:dataTypeName=money

metric m:north_ch_ch_property_tax p:double l:"NORTH CH CH PROPERTY TAX" t:dataTypeName=money

metric m:oakmont_property_tax p:double l:"OAKMONT PROPERTY TAX" t:dataTypeName=money

metric m:poolesville_property_tax p:double l:"POOLESVILLE PROPERTY TAX" t:dataTypeName=money

metric m:rockville_property_tax p:double l:"ROCKVILLE PROPERTY TAX" t:dataTypeName=money

metric m:somerset_property_tax p:double l:"SOMERSET PROPERTY TAX" t:dataTypeName=money

metric m:takoma_park_property_tax p:double l:"TAKOMA PARK PROPERTY TAX" t:dataTypeName=money

metric m:washington_grove_property_tax p:double l:"WASHINGTON GROVE PROPERTY TAX" t:dataTypeName=money

metric m:bay_restoration_fund p:double l:"BAY RESTORATION FUND" t:dataTypeName=money

metric m:ch_ch_section_3_charge_rh p:double l:"CH CH SECTION 3 CHARGE-RH" t:dataTypeName=money

metric m:ch_ch_section_5_charge_rj p:double l:"CH CH SECTION 5 CHARGE-RJ" t:dataTypeName=money

metric m:ch_ch_town_charge_ri p:double l:"CH CH TOWN CHARGE-RI" t:dataTypeName=money

metric m:ch_ch_village_charge_rg p:double l:"CH CH VILLAGE CHARGE-RG" t:dataTypeName=money

metric m:dbu_road p:double l:"DBU ROAD" t:dataTypeName=money

metric m:dev_dist_special_assessment_kv p:double l:"DEV DIST SPECIAL ASSESSMENT - KV" t:dataTypeName=money

metric m:dev_dist_special_assessment_wg p:double l:"DEV DIST SPECIAL ASSESSMENT-WG" t:dataTypeName=money

metric m:dev_dist_special_tax_kv p:double l:"DEV DIST SPECIAL TAX - KV" t:dataTypeName=money

metric m:dev_dist_special_tax_wg p:double l:"DEV DIST SPECIAL TAX -WG" t:dataTypeName=money

metric m:gaithersburg_charge_rm p:double l:"GAITHERSBURG CHARGE-RM" t:dataTypeName=money

metric m:gaithersburg_stormwater_fee p:double l:"GAITHERSBURG STORMWATER FEE" t:dataTypeName=money

metric m:garrett_park_charge_rl p:double l:"GARRETT PARK CHARGE-RL" t:dataTypeName=money

metric m:martins_addition_charge_rk p:double l:"MARTINS ADDITION CHARGE-RK" t:dataTypeName=money

metric m:rockville_front_foot_chg p:double l:"ROCKVILLE FRONT FOOT CHG" t:dataTypeName=money

metric m:rockville_stormwater_mgmt_fee p:double l:"ROCKVILLE STORMWATER MGMT FEE" t:dataTypeName=money

metric m:solid_waste_charge p:double l:"SOLID WASTE CHARGE" t:dataTypeName=money

metric m:takoma_park_special p:double l:"TAKOMA PARK SPECIAL" t:dataTypeName=money

metric m:washington_grove_rn p:double l:"WASHINGTON GROVE -RN" t:dataTypeName=money

metric m:washington_grove_serv_chg p:double l:"WASHINGTON GROVE SERV.CHG" t:dataTypeName=money

metric m:white_flint_sp_tax p:double l:"WHITE FLINT SP TAX" t:dataTypeName=money

metric m:water_qual_protect_chg_mfr p:double l:"WATER QUAL PROTECT CHG (MFR)" t:dataTypeName=money

metric m:water_qual_protect_chg_nr p:double l:"WATER QUAL PROTECT CHG (NR)" t:dataTypeName=money

metric m:water_qual_protect_chg_rsfa p:double l:"WATER QUAL PROTECT CHG (RSFA)" t:dataTypeName=money

metric m:water_qual_protect_chg_rsfd p:double l:"WATER QUAL PROTECT CHG (RSFD)" t:dataTypeName=money

metric m:water_quality_protect_chg_ag p:double l:"WATER QUALITY PROTECT CHG (AG)" t:dataTypeName=money

metric m:water_quality_protect_chg_ex p:double l:"WATER QUALITY PROTECT CHG (EX)" t:dataTypeName=money

metric m:water_quality_protect_chg_gov p:double l:"WATER QUALITY PROTECT CHG (GOV)" t:dataTypeName=money

metric m:water_quality_protect_chg_sfr p:double l:"WATER QUALITY PROTECT CHG (SFR)" t:dataTypeName=money

metric m:water_quality_protect_chg_np p:double l:"WATER QUALITY PROTECT CHG (NP)" t:dataTypeName=money

metric m:wssc_connection_fee_chg p:double l:"WSSC CONNECTION FEE CHG" t:dataTypeName=money

metric m:wssc_front_foot_benefit_chg p:double l:"WSSC FRONT FOOT BENEFIT CHG" t:dataTypeName=money

metric m:clean_lien_demolition p:double l:"CLEAN & LIEN/DEMOLITION" t:dataTypeName=money

metric m:total p:double l:TOTAL t:dataTypeName=money

metric m:state_homestead_credit p:double l:"STATE HOMESTEAD CREDIT" t:dataTypeName=money

metric m:county_homestead_credit p:double l:"COUNTY HOMESTEAD CREDIT" t:dataTypeName=money

metric m:state_homeowner_s_credit p:double l:"STATE HOMEOWNER'S CREDIT" t:dataTypeName=money

metric m:county_homeowner_s_credit p:double l:"COUNTY HOMEOWNER'S CREDIT" t:dataTypeName=money

metric m:county_property_tax_credit p:double l:"COUNTY PROPERTY TAX CREDIT" t:dataTypeName=money

metric m:municipal_homeowners_credit p:double l:"MUNICIPAL HOMEOWNERS' CREDIT" t:dataTypeName=money

metric m:municipal_homestead_credit p:double l:"MUNICIPAL HOMESTEAD CREDIT" t:dataTypeName=money

metric m:rockville_property_tax_credit p:double l:"ROCKVILLE PROPERTY TAX CREDIT" t:dataTypeName=money

metric m:full_parking_lot_credit p:double l:"FULL PARKING LOT CREDIT" t:dataTypeName=money

metric m:partial_parking_lot_credit p:double l:"PARTIAL PARKING LOT CREDIT" t:dataTypeName=money

metric m:art_s_entertainment_credit p:double l:"ART'S & ENTERTAINMENT CREDIT" t:dataTypeName=money

metric m:brownfield_s_county_tax_credit p:double l:"BROWNFIELD'S COUNTY TAX CREDIT" t:dataTypeName=money

metric m:brownfields_state_tax_credit p:double l:"BROWNFIELDS STATE TAX CREDIT" t:dataTypeName=money

metric m:business_incubator_tax_credit p:double l:"BUSINESS INCUBATOR TAX CREDIT" t:dataTypeName=money

metric m:conservation_energy_credit p:double l:"CONSERVATION ENERGY CREDIT" t:dataTypeName=money

metric m:conservation_land_tax_credit p:double l:"CONSERVATION LAND TAX CREDIT" t:dataTypeName=money

metric m:day_car_tax_credit p:double l:"DAY CAR TAX CREDIT" t:dataTypeName=money

metric m:design_for_life_tax_credit p:double l:"DESIGN FOR LIFE TAX CREDIT" t:dataTypeName=money

metric m:enterprise_zone_municipal p:double l:"ENTERPRISE ZONE MUNICIPAL" t:dataTypeName=money

metric m:enterprise_zone_tax_credit p:double l:"ENTERPRISE ZONE TAX CREDIT" t:dataTypeName=money

metric m:excess_homeowner_credit p:double l:"EXCESS HOMEOWNER CREDIT" t:dataTypeName=money

metric m:fallen_officer_rescue_credit p:double l:"FALLEN OFFICER/RESCUE CREDIT" t:dataTypeName=money

metric m:fire_sprinkler_tax_credit p:double l:"FIRE SPRINKLER TAX CREDIT" t:dataTypeName=money

metric m:green_building_tax_credit p:double l:"GREEN BUILDING TAX CREDIT" t:dataTypeName=money

metric m:historic_preservation_credit p:double l:"HISTORIC PRESERVATION CREDIT" t:dataTypeName=money

metric m:municipal_swimclub p:double l:"MUNICIPAL SWIMCLUB" t:dataTypeName=money

metric m:new_jobs_tax_credit p:double l:"NEW JOBS TAX CREDIT" t:dataTypeName=money

metric m:religious_organizations_credit p:double l:"RELIGIOUS ORGANIZATIONS CREDIT" t:dataTypeName=money

metric m:renewable_energy_credit p:double l:"RENEWABLE ENERGY CREDIT" t:dataTypeName=money

metric m:special_area_homestead_credit p:double l:"SPECIAL AREA HOMESTEAD CREDIT" t:dataTypeName=money

metric m:swimclub p:double l:SWIMCLUB t:dataTypeName=money

metric m:total_credits p:double l:"TOTAL CREDITS" t:dataTypeName=money

entity e:uvy4-94zr l:"Real Property Tax - 2016" t:url=https://data.montgomerycountymd.gov/api/views/uvy4-94zr

property e:uvy4-94zr t:meta.view v:id=uvy4-94zr v:category=Finance/Tax/Property v:averageRating=0 v:name="Real Property Tax - 2016"

property e:uvy4-94zr t:meta.view.owner v:id=fnci-gphj v:screenName="MC Open Data" v:displayName="MC Open Data"

property e:uvy4-94zr t:meta.view.tableauthor v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"
```

## Top Records

```ls
| parcel_code | residence                 | property_address      | zip_code | bill_total | state_property_tax | county_property_tax | barnesville_property_tax | battery_park_property_tax | brookeville_property_tax | ch_ch_section_3_property_tax | ch_ch_section_5_property_tax | ch_ch_town_property_tax | ch_ch_view_property_tax | ch_ch_village_property_tax | drummond_property_tax | friendship_hts_property_tax | gaithersburg_property_tax | garrett_park_property_tax | glen_echo_property_tax | kensington_property_tax | laytonsville_property_tax | martins_addition_property_tax | north_ch_ch_property_tax | oakmont_property_tax | poolesville_property_tax | rockville_property_tax | somerset_property_tax | takoma_park_property_tax | washington_grove_property_tax | bay_restoration_fund | ch_ch_section_3_charge_rh | ch_ch_section_5_charge_rj | ch_ch_town_charge_ri | ch_ch_village_charge_rg | dbu_road | dev_dist_special_assessment_kv | dev_dist_special_assessment_wg | dev_dist_special_tax_kv | dev_dist_special_tax_wg | gaithersburg_charge_rm | gaithersburg_stormwater_fee | garrett_park_charge_rl | martins_addition_charge_rk | rockville_front_foot_chg | rockville_stormwater_mgmt_fee | solid_waste_charge | takoma_park_special | washington_grove_rn | washington_grove_serv_chg | white_flint_sp_tax | water_qual_protect_chg_mfr | water_qual_protect_chg_nr | water_qual_protect_chg_rsfa | water_qual_protect_chg_rsfd | water_quality_protect_chg_ag | water_quality_protect_chg_ex | water_quality_protect_chg_gov | water_quality_protect_chg_sfr | water_quality_protect_chg_np | wssc_connection_fee_chg | wssc_front_foot_benefit_chg | clean_lien_demolition | total   | state_homestead_credit | county_homestead_credit | state_homeowner_s_credit | county_homeowner_s_credit | county_property_tax_credit | municipal_homeowners_credit | municipal_homestead_credit | rockville_property_tax_credit | full_parking_lot_credit | partial_parking_lot_credit | art_s_entertainment_credit | brownfield_s_county_tax_credit | brownfields_state_tax_credit | business_incubator_tax_credit | conservation_energy_credit | conservation_land_tax_credit | day_car_tax_credit | design_for_life_tax_credit | enterprise_zone_municipal | enterprise_zone_tax_credit | excess_homeowner_credit | fallen_officer_rescue_credit | fire_sprinkler_tax_credit | green_building_tax_credit | historic_preservation_credit | municipal_swimclub | new_jobs_tax_credit | religious_organizations_credit | renewable_energy_credit | special_area_homestead_credit | swimclub | total_credits | 
| =========== | ========================= | ===================== | ======== | ========== | ================== | =================== | ======================== | ========================= | ======================== | ============================ | ============================ | ======================= | ======================= | ========================== | ===================== | =========================== | ========================= | ========================= | ====================== | ======================= | ========================= | ============================= | ======================== | ==================== | ======================== | ====================== | ===================== | ======================== | ============================= | ==================== | ========================= | ========================= | ==================== | ======================= | ======== | ============================== | ============================== | ======================= | ======================= | ====================== | =========================== | ====================== | ========================== | ======================== | ============================= | ================== | =================== | =================== | ========================= | ================== | ========================== | ========================= | =========================== | =========================== | ============================ | ============================ | ============================= | ============================= | ============================ | ======================= | =========================== | ===================== | ======= | ====================== | ======================= | ======================== | ========================= | ========================== | =========================== | ========================== | ============================= | ======================= | ========================== | ========================== | ============================== | ============================ | ============================= | ========================== | ============================ | ================== | ========================== | ========================= | ========================== | ======================= | ============================ | ========================= | ========================= | ============================ | ================== | =================== | ============================== | ======================= | ============================= | ======== | ============= | 
| 1407612     | NOT A PRINCIPAL RESIDENCE | 310 DOMER AVE         | 20912    | 8746.66    | 683.31             | 6334.04             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 1673.82            | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 55.49                     | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 0.00                          | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 8746.66 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | 0.00                       | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | 0.00          | 
| 1410346     | PRINCIPAL RESIDENCE       | 8809 LEONARD DR       | 20910    | 4725.41    | 481.94             | 4467.37             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 5417.41 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1411170     | PRINCIPAL RESIDENCE       | 4709 FALCON ST        | 20853    | 2917.29    | 305.87             | 2835.32             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 3609.29 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1408866     | PRINCIPAL RESIDENCE       | 2306 KANSAS AVE       | 20910    | 5175.40    | 476.90             | 4420.66             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 501.74                  | 0.00                        | 0.00                  | 5867.40 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1407133     | PRINCIPAL RESIDENCE       | 3207 PAUL DR          | 20902    | 2680.38    | 282.80             | 2621.48             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 3372.38 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1408946     | PRINCIPAL RESIDENCE       | 8915 PENNSYLVANIA AVE | 20910    | 4243.48    | 435.01             | 4032.37             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 4935.48 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1404904     | PRINCIPAL RESIDENCE       | 11000 CONTI PL        | 20902    | 3577.53    | 370.16             | 3431.27             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 4269.53 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1409757     | PRINCIPAL RESIDENCE       | 8904 TALBOT AVE       | 20910    | 5072.79    | 515.76             | 4780.93             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 5764.79 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1402404     | PRINCIPAL RESIDENCE       | 830 GREGORIO DR       | 20901    | 3221.73    | 335.52             | 3110.11             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 95.00                         | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 3913.73 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
| 1408252     | PRINCIPAL RESIDENCE       | 8323 HADDON DR        | 20912    | 5829.91    | 580.24             | 5378.57             | 0.00                     | 0.00                      | 0.00                     | 0.00                         | 0.00                         | 0.00                    | 0.00                    | 0.00                       | 0.00                  | 0.00                        | 0.00                      | 0.00                      | 0.00                   | 0.00                    | 0.00                      | 0.00                          | 0.00                     | 0.00                 | 0.00                     | 0.00                   | 0.00                  | 0.00                     | 0.00                          | 0.00                 | 0.00                      | 0.00                      | 0.00                 | 0.00                    | 0.00     | 0.00                           | 0.00                           | 0.00                    | 0.00                    | 0.00                   | 0.00                        | 0.00                   | 0.00                       | 0.00                     | 0.00                          | 373.10             | 0.00                | 0.00                | 0.00                      | 0.00               | 0.00                       | 0.00                      | 0.00                        | 0.00                        | 0.00                         | 0.00                         | 0.00                          | 190.00                        | 0.00                         | 0.00                    | 0.00                        | 0.00                  | 6521.91 | 0.00                   | 0.00                    | 0.00                     | 0.00                      | -692.00                    | 0.00                        | 0.00                       | 0.00                          | 0.00                    | 0.00                       | 0.00                       | 0.00                           | 0.00                         | 0.00                          | 0.00                       | 0.00                         | 0.00               | 0.00                       | 0.00                      | 0.00                       | 0.00                    | 0.00                         | 0.00                      | 0.00                      | 0.00                         | 0.00               | 0.00                | 0.00                           | 0.00                    | 0.00                          | 0.00     | -692.00       | 
```