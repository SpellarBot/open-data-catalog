# Toxic Release Inventory Facility List 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/toxic-release-inventory-facility-list-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/fma9-k2kj) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fma9-k2kj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fma9-k2kj/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fma9-k2kj |
| Name | Toxic Release Inventory Facility List 2015 |
| Attribution | U.S. Environmental Protection Agency |
| Category | Environment and Natural Resources |
| Tags | toxic, release, tri |
| Created | 2017-02-02T14:50:44Z |
| Publication Date | 2017-02-02T15:11:39Z |

## Description

The Toxics Release Inventory (TRI) tracks the management of certain toxic chemicals that may pose a threat to human health and the environment. Certain industrial facilities in the U.S. must report annually how much of each chemical is recycled, combusted for energy recovery, treated for destruction, and disposed of or otherwise released on- and off-site. This information is collectively referred to as production-related waste managed.

2015 Dataset (released October 2016 and updated November 2016)
Descriptions of data terms and field names: https://www.epa.gov/toxics-release-inventory-tri-program/descriptions-tri-data-terms-text-version
Factors to consider when using this data: https://www.epa.gov/toxics-release-inventory-tri-program/factors-consider-when-using-toxics-release-inventory-data

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | time           | year                           | YEAR                           | number    | number      |
| Yes      | series tag     | tri_facility_id                | TRI_FACILITY_ID                | text      | text        |
| Yes      | series tag     | frs_id                         | FRS_ID                         | text      | number      |
| Yes      | series tag     | facility_name                  | FACILITY_NAME                  | text      | text        |
| Yes      | series tag     | street_address                 | STREET_ADDRESS                 | text      | text        |
| Yes      | series tag     | city                           | CITY                           | text      | text        |
| Yes      | series tag     | county                         | COUNTY                         | text      | text        |
| No       |                | st                             | ST                             | text      | text        |
| Yes      | series tag     | zip                            | ZIP                            | text      | number      |
| No       |                | latitude                       | LATITUDE                       | number    | number      |
| No       |                | longitude                      | LONGITUDE                      | number    | number      |
| Yes      | series tag     | bia_code                       | BIA_CODE                       | text      | text        |
| Yes      | series tag     | tribe                          | TRIBE                          | text      | text        |
| Yes      | series tag     | federal_facility               | FEDERAL_FACILITY               | text      | text        |
| Yes      | series tag     | industry_sector_code           | INDUSTRY_SECTOR_CODE           | text      | number      |
| Yes      | series tag     | industry_sector                | INDUSTRY_SECTOR                | text      | text        |
| Yes      | series tag     | primary_sic                    | PRIMARY_SIC                    | text      | text        |
| Yes      | series tag     | sic_2                          | SIC_2                          | text      | text        |
| Yes      | series tag     | sic_3                          | SIC_3                          | text      | text        |
| Yes      | series tag     | sic_4                          | SIC_4                          | text      | text        |
| Yes      | series tag     | sic_5                          | SIC_5                          | text      | text        |
| Yes      | series tag     | sic_6                          | SIC_6                          | text      | text        |
| Yes      | numeric metric | primary_naics                  | PRIMARY_NAICS                  | number    | number      |
| Yes      | numeric metric | naics_2                        | NAICS_2                        | number    | number      |
| Yes      | numeric metric | naics_3                        | NAICS_3                        | number    | number      |
| Yes      | numeric metric | naics_4                        | NAICS_4                        | number    | number      |
| Yes      | numeric metric | naics_5                        | NAICS_5                        | number    | number      |
| Yes      | numeric metric | naics_6                        | NAICS_6                        | number    | number      |
| Yes      | series tag     | doc_ctrl_num                   | DOC_CTRL_NUM                   | text      | number      |
| Yes      | series tag     | chemical                       | CHEMICAL                       | text      | text        |
| Yes      | series tag     | cas_compound_id                | CAS_#/COMPOUND_ID              | text      | text        |
| Yes      | series tag     | srs_id                         | SRS_ID                         | text      | number      |
| Yes      | series tag     | clear_air_act_chemical         | CLEAR_AIR_ACT_CHEMICAL         | text      | text        |
| Yes      | series tag     | classification                 | CLASSIFICATION                 | text      | text        |
| Yes      | series tag     | metal                          | METAL                          | text      | text        |
| Yes      | numeric metric | metal_category                 | METAL_CATEGORY                 | number    | number      |
| Yes      | series tag     | carcinogen                     | CARCINOGEN                     | text      | text        |
| Yes      | series tag     | form_type                      | FORM_TYPE                      | text      | text        |
| Yes      | series tag     | unit_of_measure                | UNIT_OF_MEASURE                | text      | text        |
| Yes      | numeric metric | 5_1_fugitive_air               | 5.1_FUGITIVE_AIR               | number    | number      |
| Yes      | numeric metric | 5_2_stack_air                  | 5.2_STACK_AIR                  | number    | number      |
| Yes      | numeric metric | 5_3_water                      | 5.3_WATER                      | number    | number      |
| Yes      | numeric metric | 5_4_underground                | 5.4_UNDERGROUND                | number    | number      |
| Yes      | numeric metric | 5_4_1_underground_class_i      | 5.4.1_UNDERGROUND_CLASS_I      | number    | number      |
| Yes      | numeric metric | 5_4_2_underground_class_ii_v   | 5.4.2_UNDERGROUND_CLASS_II-V   | number    | number      |
| Yes      | numeric metric | 5_5_1_landfills                | 5.5.1_LANDFILLS                | number    | number      |
| Yes      | numeric metric | 5_5_1a_rcra_c_landfills        | 5.5.1A_RCRA_C_LANDFILLS        | number    | number      |
| Yes      | numeric metric | 5_5_1b_other_landfills         | 5.5.1B_OTHER_LANDFILLS         | number    | number      |
| Yes      | numeric metric | 5_5_2_land_treatment           | 5.5.2_LAND_TREATMENT           | number    | number      |
| Yes      | numeric metric | 5_5_3_surface_impoundment      | 5.5.3_SURFACE_IMPOUNDMENT      | number    | number      |
| Yes      | numeric metric | 5_5_3a_rcra_c_surface_imp      | 5.5.3A_RCRA_C_SURFACE_IMP.     | number    | number      |
| Yes      | numeric metric | 5_5_3b_other_surface_imp       | 5.5.3B_Other_SURFACE_IMP.      | number    | number      |
| Yes      | numeric metric | 5_5_4_other_disposal           | 5.5.4_OTHER_DISPOSAL           | number    | number      |
| Yes      | numeric metric | on_site_release_total          | ON-SITE_RELEASE_TOTAL          | number    | number      |
| Yes      | numeric metric | 6_1_potw_transfers_for_release | 6.1_POTW-TRANSFERS_FOR_RELEASE | number    | number      |
| Yes      | numeric metric | 6_1_potw_transfers_for_treatm  | 6.1_POTW-TRANSFERS_FOR_TREATM. | number    | number      |
| Yes      | numeric metric | 6_1_potw_total_transfers       | 6.1_POTW-TOTAL_TRANSFERS       | number    | number      |
| Yes      | numeric metric | 6_2_m10                        | 6.2_M10                        | number    | number      |
| Yes      | numeric metric | 6_2_m41                        | 6.2_M41                        | number    | number      |
| Yes      | numeric metric | 6_2_m62                        | 6.2_M62                        | number    | number      |
| Yes      | numeric metric | 6_2_m71                        | 6.2_M71                        | number    | number      |
| Yes      | numeric metric | 6_2_m81                        | 6.2_M81                        | number    | number      |
| Yes      | numeric metric | 6_2_m82                        | 6.2_M82                        | number    | number      |
| Yes      | numeric metric | 6_2_m72                        | 6.2_M72                        | number    | number      |
| Yes      | numeric metric | 6_2_m63                        | 6.2_M63                        | number    | number      |
| Yes      | numeric metric | 6_2_m66                        | 6.2_M66                        | number    | number      |
| Yes      | numeric metric | 6_2_m67                        | 6.2_M67                        | number    | number      |
| Yes      | numeric metric | 6_2_m64                        | 6.2_M64                        | number    | number      |
| Yes      | numeric metric | 6_2_m65                        | 6.2_M65                        | number    | number      |
| Yes      | numeric metric | 6_2_m73                        | 6.2_M73                        | number    | number      |
| Yes      | numeric metric | 6_2_m79                        | 6.2_M79                        | number    | number      |
| Yes      | numeric metric | 6_2_m90                        | 6.2_M90                        | number    | number      |
| Yes      | numeric metric | 6_2_m94                        | 6.2_M94                        | number    | number      |
| Yes      | numeric metric | 6_2_m99                        | 6.2_M99                        | number    | number      |
| Yes      | numeric metric | off_site_release_total         | OFF-SITE_RELEASE_TOTAL         | number    | number      |
| Yes      | numeric metric | 6_2_m20                        | 6.2_M20                        | number    | number      |
| Yes      | numeric metric | 6_2_m24                        | 6.2_M24                        | number    | number      |
| Yes      | numeric metric | 6_2_m26                        | 6.2_M26                        | number    | number      |
| Yes      | numeric metric | 6_2_m28                        | 6.2_M28                        | number    | number      |
| Yes      | numeric metric | 6_2_m93                        | 6.2_M93                        | number    | number      |
| Yes      | numeric metric | off_site_recycled_total        | OFF-SITE_RECYCLED_TOTAL        | number    | number      |
| Yes      | numeric metric | 6_2_m56                        | 6.2_M56                        | number    | number      |
| Yes      | numeric metric | 6_2_m92                        | 6.2_M92                        | number    | number      |
| Yes      | numeric metric | off_site_recovery_total        | OFF-SITE_RECOVERY_TOTAL        | number    | number      |
| Yes      | numeric metric | 6_2_m40                        | 6.2_M40                        | number    | number      |
| Yes      | numeric metric | 6_2_m50                        | 6.2_M50                        | number    | number      |
| Yes      | numeric metric | 6_2_m54                        | 6.2_M54                        | number    | number      |
| Yes      | numeric metric | 6_2_m61                        | 6.2_M61                        | number    | number      |
| Yes      | numeric metric | 6_2_m69                        | 6.2_M69                        | number    | number      |
| Yes      | numeric metric | 6_2_m95                        | 6.2_M95                        | number    | number      |
| Yes      | numeric metric | off_site_treated_total         | OFF-SITE_TREATED_TOTAL         | number    | number      |
| Yes      | numeric metric | total_releases                 | TOTAL_RELEASES                 | number    | number      |
| Yes      | numeric metric | 8_1_releases                   | 8.1_RELEASES                   | number    | number      |
| Yes      | numeric metric | 8_1a_on_site_contained_rel     | 8.1A_ON-SITE_CONTAINED_REL.    | number    | number      |
| Yes      | numeric metric | 8_1b_on_site_other_releases    | 8.1B_ON-SITE_OTHER_RELEASES    | number    | number      |
| Yes      | numeric metric | 8_1c_off_site_contained_rel    | 8.1C_OFF-SITE_CONTAINED_REL.   | number    | number      |
| Yes      | numeric metric | 8_1d_off_site_other_releases   | 8.1D_OFF-SITE_OTHER_RELEASES   | number    | number      |
| Yes      | numeric metric | 8_2_energy_recovery_on_site    | 8.2_ENERGY_RECOVERY_ON-SITE    | number    | number      |
| Yes      | numeric metric | 8_3_energy_recovery_off_site   | 8.3_ENERGY_RECOVERY_OFF-SITE   | number    | number      |
| Yes      | numeric metric | 8_4_recycling_on_site          | 8.4_RECYCLING_ON-SITE          | number    | number      |
| Yes      | numeric metric | 8_5_recycling_off_site         | 8.5_RECYCLING_OFF-SITE         | number    | number      |
| Yes      | numeric metric | 8_6_treatment_on_site          | 8.6_TREATMENT_ON-SITE          | number    | number      |
| Yes      | numeric metric | 8_7_treatment_off_site         | 8.7_TREATMENT_OFF-SITE         | number    | number      |
| Yes      | numeric metric | prod_waste_8_1_thru_8_7        | PROD._WASTE_(8.1_THRU_8.7)     | number    | number      |
| Yes      | numeric metric | 8_8_one_time_release           | 8.8_ONE-TIME_RELEASE           | number    | number      |
| Yes      | series tag     | prod_ratio_or_activity         | PROD_RATIO_OR_ACTIVITY         | text      | text        |
| Yes      | numeric metric | 8_9_production_ratio           | 8.9_PRODUCTION_RATIO           | number    | number      |
| Yes      | series tag     | parent_company_name            | PARENT_COMPANY_NAME            | text      | text        |
| Yes      | series tag     | parent_company_db_number       | PARENT_COMPANY_DB_NUMBER       | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = st,latitude,longitude
```

## Data Commands

```ls
series e:fma9-k2kj d:2015-01-01T00:00:00.000Z t:zip=6492 t:parent_company_name=NA t:frs_id=110000316630 t:tri_facility_id=06492BYKCH524SO t:industry_sector=Chemicals t:srs_id=16261 t:prod_ratio_or_activity=PRODUCTION t:city=WALLINGFORD t:carcinogen=NO t:doc_ctrl_num=1315210000000 t:unit_of_measure=Pounds t:clear_air_act_chemical=NO t:facility_name="BYK USA INC" t:form_type=R t:metal=NO t:county="NEW HAVEN" t:chemical=1,2,4-TRIMETHYLBENZENE t:classification=TRI t:cas_compound_id=95636 t:street_address="524 S CHERRY ST" t:federal_facility=NO t:industry_sector_code=325 m:5_5_3_surface_impoundment=0 m:6_2_m24=0 m:5_4_underground=0 m:6_2_m26=0 m:6_2_m28=0 m:6_2_m20=0 m:6_2_m62=0 m:off_site_recycled_total=0 m:6_2_m61=0 m:5_5_2_land_treatment=0 m:6_2_m66=0 m:6_2_m65=0 m:6_2_m64=0 m:6_2_m63=0 m:6_2_m69=0 m:8_9_production_ratio=1.11 m:8_4_recycling_on_site=20680 m:6_2_m67=0 m:5_1_fugitive_air=42 m:5_5_1b_other_landfills=0 m:off_site_recovery_total=13694 m:8_1b_on_site_other_releases=83 m:8_2_energy_recovery_on_site=0 m:6_2_m71=0 m:6_2_m73=0 m:6_2_m72=0 m:6_2_m79=0 m:5_5_3b_other_surface_imp=0 m:off_site_treated_total=3772 m:5_2_stack_air=41 m:primary_naics=325510 m:8_1a_on_site_contained_rel=0 m:5_4_1_underground_class_i=0 m:off_site_release_total=0 m:6_1_potw_transfers_for_treatm=0 m:6_2_m41=0 m:5_5_1a_rcra_c_landfills=0 m:8_5_recycling_off_site=0 m:5_5_4_other_disposal=0 m:6_1_potw_total_transfers=0 m:6_2_m40=0 m:total_releases=83 m:6_2_m82=0 m:8_7_treatment_off_site=3772 m:6_2_m81=0 m:prod_waste_8_1_thru_8_7=38229 m:6_1_potw_transfers_for_release=0 m:6_2_m10=0 m:8_1c_off_site_contained_rel=0 m:5_3_water=0 m:5_5_1_landfills=0 m:6_2_m56=13694 m:on_site_release_total=83 m:8_3_energy_recovery_off_site=13694 m:5_5_3a_rcra_c_surface_imp=0 m:6_2_m54=0 m:6_2_m90=0 m:6_2_m50=3772 m:8_1d_off_site_other_releases=0 m:8_6_treatment_on_site=0 m:6_2_m99=0 m:8_1_releases=0 m:5_4_2_underground_class_ii_v=0 m:6_2_m93=0 m:6_2_m92=0 m:6_2_m95=0 m:metal_category=0 m:6_2_m94=0

series e:fma9-k2kj d:2015-01-01T00:00:00.000Z t:zip=6320 t:parent_company_name="US DEPARTMENT OF HOMELAND SECURITY" t:frs_id=110000786524 t:tri_facility_id=06320SCSTG15MOH t:industry_sector=Other t:srs_id=149583 t:parent_company_db_number=NA t:prod_ratio_or_activity=PRODUCTION t:city="NEW LONDON" t:carcinogen=YES t:doc_ctrl_num=1315210000000 t:unit_of_measure=Pounds t:clear_air_act_chemical=YES t:facility_name="US COAST GUARD ACADEMY" t:form_type=R t:metal=YES t:county="NEW LONDON" t:chemical=LEAD t:classification=PBT t:cas_compound_id=7439921 t:street_address="15 MOHEGAN AVE" t:federal_facility=YES t:industry_sector_code=999 m:5_5_3_surface_impoundment=0 m:6_2_m24=1945 m:5_4_underground=0 m:6_2_m26=0 m:6_2_m28=0 m:6_2_m20=0 m:6_2_m62=0 m:off_site_recycled_total=1945 m:6_2_m61=0 m:5_5_2_land_treatment=0 m:6_2_m66=0 m:6_2_m65=0 m:6_2_m64=0 m:6_2_m63=0 m:6_2_m69=0 m:8_9_production_ratio=1.53 m:8_4_recycling_on_site=0 m:6_2_m67=0 m:5_1_fugitive_air=0 m:5_5_1b_other_landfills=0 m:off_site_recovery_total=0 m:8_1b_on_site_other_releases=1.04 m:8_2_energy_recovery_on_site=0 m:6_2_m71=0 m:6_2_m73=0 m:6_2_m72=0 m:6_2_m79=0 m:5_5_3b_other_surface_imp=0 m:off_site_treated_total=0 m:5_2_stack_air=1.04 m:primary_naics=611310 m:8_1a_on_site_contained_rel=0 m:5_4_1_underground_class_i=0 m:off_site_release_total=2636 m:6_1_potw_transfers_for_treatm=0 m:6_2_m41=0 m:5_5_1a_rcra_c_landfills=0 m:8_5_recycling_off_site=1945 m:5_5_4_other_disposal=0 m:6_1_potw_total_transfers=0 m:6_2_m40=0 m:total_releases=2637.04 m:6_2_m82=0 m:8_7_treatment_off_site=0 m:6_2_m81=0 m:prod_waste_8_1_thru_8_7=4582.04 m:6_1_potw_transfers_for_release=0 m:6_2_m10=0 m:8_1c_off_site_contained_rel=0 m:5_3_water=0 m:5_5_1_landfills=0 m:6_2_m56=0 m:on_site_release_total=1.04 m:8_3_energy_recovery_off_site=0 m:5_5_3a_rcra_c_surface_imp=0 m:6_2_m54=0 m:6_2_m90=2636 m:6_2_m50=0 m:8_1d_off_site_other_releases=2636 m:8_6_treatment_on_site=0 m:6_2_m99=0 m:8_1_releases=0 m:5_4_2_underground_class_ii_v=0 m:6_2_m93=0 m:6_2_m92=0 m:6_2_m95=0 m:metal_category=1 m:6_2_m94=0

series e:fma9-k2kj d:2015-01-01T00:00:00.000Z t:zip=6787 t:parent_company_name="UNIMETAL SURFACE FINISHING LLC" t:frs_id=110000317434 t:tri_facility_id=06787QLTYR135SO t:industry_sector="Fabricated Metals" t:srs_id=649616 t:parent_company_db_number=NA t:prod_ratio_or_activity=PRODUCTION t:city=THOMASTON t:carcinogen=NO t:doc_ctrl_num=1315210000000 t:unit_of_measure=Pounds t:clear_air_act_chemical=NO t:facility_name="UNIMETAL SURFACE FINISHING LLC" t:form_type=R t:metal=NO t:county=LITCHFIELD t:chemical="NITRATE COMPOUNDS" t:classification=TRI t:cas_compound_id=N511 t:street_address="135 S MAIN ST" t:federal_facility=NO t:industry_sector_code=332 m:5_5_3_surface_impoundment=0 m:6_2_m24=0 m:5_4_underground=0 m:6_2_m26=0 m:6_2_m28=0 m:6_2_m20=0 m:6_2_m62=0 m:off_site_recycled_total=0 m:6_2_m61=0 m:5_5_2_land_treatment=0 m:6_2_m66=0 m:6_2_m65=0 m:6_2_m64=0 m:6_2_m63=0 m:6_2_m69=0 m:8_9_production_ratio=1.56 m:8_4_recycling_on_site=0 m:6_2_m67=0 m:5_1_fugitive_air=60330 m:5_5_1b_other_landfills=0 m:off_site_recovery_total=0 m:8_1b_on_site_other_releases=67636 m:8_2_energy_recovery_on_site=0 m:6_2_m71=0 m:6_2_m73=0 m:6_2_m72=0 m:6_2_m79=0 m:5_5_3b_other_surface_imp=0 m:off_site_treated_total=231.68 m:5_2_stack_air=0 m:primary_naics=332813 m:8_1a_on_site_contained_rel=0 m:5_4_1_underground_class_i=0 m:off_site_release_total=1902.6 m:6_1_potw_transfers_for_treatm=211.4 m:6_2_m41=0 m:5_5_1a_rcra_c_landfills=0 m:8_5_recycling_off_site=0 m:5_5_4_other_disposal=0 m:6_1_potw_total_transfers=2114 m:6_2_m40=20.28 m:total_releases=71441.2 m:6_2_m82=0 m:8_7_treatment_off_site=231.68 m:6_2_m81=0 m:prod_waste_8_1_thru_8_7=69770.28 m:6_1_potw_transfers_for_release=1902.6 m:6_2_m10=0 m:8_1c_off_site_contained_rel=0 m:5_3_water=7306 m:5_5_1_landfills=0 m:6_2_m56=0 m:on_site_release_total=67636 m:8_3_energy_recovery_off_site=0 m:5_5_3a_rcra_c_surface_imp=0 m:6_2_m54=0 m:6_2_m90=0 m:6_2_m50=0 m:8_1d_off_site_other_releases=1902.6 m:8_6_treatment_on_site=0 m:6_2_m99=0 m:8_1_releases=0 m:5_4_2_underground_class_ii_v=0 m:6_2_m93=0 m:6_2_m92=0 m:6_2_m95=0 m:metal_category=0 m:6_2_m94=0
```

## Meta Commands

```ls
metric m:primary_naics p:integer l:PRIMARY_NAICS t:dataTypeName=number

metric m:naics_2 p:integer l:NAICS_2 t:dataTypeName=number

metric m:naics_3 p:integer l:NAICS_3 t:dataTypeName=number

metric m:naics_4 p:integer l:NAICS_4 t:dataTypeName=number

metric m:naics_5 p:integer l:NAICS_5 t:dataTypeName=number

metric m:naics_6 p:integer l:NAICS_6 t:dataTypeName=number

metric m:metal_category p:integer l:METAL_CATEGORY t:dataTypeName=number

metric m:5_1_fugitive_air p:double l:5.1_FUGITIVE_AIR t:dataTypeName=number

metric m:5_2_stack_air p:float l:5.2_STACK_AIR t:dataTypeName=number

metric m:5_3_water p:double l:5.3_WATER t:dataTypeName=number

metric m:5_4_underground p:integer l:5.4_UNDERGROUND t:dataTypeName=number

metric m:5_4_1_underground_class_i p:integer l:5.4.1_UNDERGROUND_CLASS_I t:dataTypeName=number

metric m:5_4_2_underground_class_ii_v p:integer l:5.4.2_UNDERGROUND_CLASS_II-V t:dataTypeName=number

metric m:5_5_1_landfills p:integer l:5.5.1_LANDFILLS t:dataTypeName=number

metric m:5_5_1a_rcra_c_landfills p:integer l:5.5.1A_RCRA_C_LANDFILLS t:dataTypeName=number

metric m:5_5_1b_other_landfills p:float l:5.5.1B_OTHER_LANDFILLS t:dataTypeName=number

metric m:5_5_2_land_treatment p:integer l:5.5.2_LAND_TREATMENT t:dataTypeName=number

metric m:5_5_3_surface_impoundment p:integer l:5.5.3_SURFACE_IMPOUNDMENT t:dataTypeName=number

metric m:5_5_3a_rcra_c_surface_imp p:integer l:5.5.3A_RCRA_C_SURFACE_IMP. t:dataTypeName=number

metric m:5_5_3b_other_surface_imp p:integer l:5.5.3B_Other_SURFACE_IMP. t:dataTypeName=number

metric m:5_5_4_other_disposal p:float l:5.5.4_OTHER_DISPOSAL t:dataTypeName=number

metric m:on_site_release_total p:double l:ON-SITE_RELEASE_TOTAL t:dataTypeName=number

metric m:6_1_potw_transfers_for_release p:double l:6.1_POTW-TRANSFERS_FOR_RELEASE t:dataTypeName=number

metric m:6_1_potw_transfers_for_treatm p:float l:6.1_POTW-TRANSFERS_FOR_TREATM. t:dataTypeName=number

metric m:6_1_potw_total_transfers p:double l:6.1_POTW-TOTAL_TRANSFERS t:dataTypeName=number

metric m:6_2_m10 p:float l:6.2_M10 t:dataTypeName=number

metric m:6_2_m41 p:double l:6.2_M41 t:dataTypeName=number

metric m:6_2_m62 p:double l:6.2_M62 t:dataTypeName=number

metric m:6_2_m71 p:integer l:6.2_M71 t:dataTypeName=number

metric m:6_2_m81 p:integer l:6.2_M81 t:dataTypeName=number

metric m:6_2_m82 p:integer l:6.2_M82 t:dataTypeName=number

metric m:6_2_m72 p:integer l:6.2_M72 t:dataTypeName=number

metric m:6_2_m63 p:integer l:6.2_M63 t:dataTypeName=number

metric m:6_2_m66 p:integer l:6.2_M66 t:dataTypeName=number

metric m:6_2_m67 p:float l:6.2_M67 t:dataTypeName=number

metric m:6_2_m64 p:double l:6.2_M64 t:dataTypeName=number

metric m:6_2_m65 p:float l:6.2_M65 t:dataTypeName=number

metric m:6_2_m73 p:integer l:6.2_M73 t:dataTypeName=number

metric m:6_2_m79 p:integer l:6.2_M79 t:dataTypeName=number

metric m:6_2_m90 p:double l:6.2_M90 t:dataTypeName=number

metric m:6_2_m94 p:double l:6.2_M94 t:dataTypeName=number

metric m:6_2_m99 p:double l:6.2_M99 t:dataTypeName=number

metric m:off_site_release_total p:double l:OFF-SITE_RELEASE_TOTAL t:dataTypeName=number

metric m:6_2_m20 p:integer l:6.2_M20 t:dataTypeName=number

metric m:6_2_m24 p:integer l:6.2_M24 t:dataTypeName=number

metric m:6_2_m26 p:double l:6.2_M26 t:dataTypeName=number

metric m:6_2_m28 p:integer l:6.2_M28 t:dataTypeName=number

metric m:6_2_m93 p:double l:6.2_M93 t:dataTypeName=number

metric m:off_site_recycled_total p:double l:OFF-SITE_RECYCLED_TOTAL t:dataTypeName=number

metric m:6_2_m56 p:double l:6.2_M56 t:dataTypeName=number

metric m:6_2_m92 p:double l:6.2_M92 t:dataTypeName=number

metric m:off_site_recovery_total p:double l:OFF-SITE_RECOVERY_TOTAL t:dataTypeName=number

metric m:6_2_m40 p:double l:6.2_M40 t:dataTypeName=number

metric m:6_2_m50 p:double l:6.2_M50 t:dataTypeName=number

metric m:6_2_m54 p:double l:6.2_M54 t:dataTypeName=number

metric m:6_2_m61 p:double l:6.2_M61 t:dataTypeName=number

metric m:6_2_m69 p:double l:6.2_M69 t:dataTypeName=number

metric m:6_2_m95 p:double l:6.2_M95 t:dataTypeName=number

metric m:off_site_treated_total p:double l:OFF-SITE_TREATED_TOTAL t:dataTypeName=number

metric m:total_releases p:double l:TOTAL_RELEASES t:dataTypeName=number

metric m:8_1_releases p:integer l:8.1_RELEASES t:dataTypeName=number

metric m:8_1a_on_site_contained_rel p:float l:8.1A_ON-SITE_CONTAINED_REL. t:dataTypeName=number

metric m:8_1b_on_site_other_releases p:double l:8.1B_ON-SITE_OTHER_RELEASES t:dataTypeName=number

metric m:8_1c_off_site_contained_rel p:float l:8.1C_OFF-SITE_CONTAINED_REL. t:dataTypeName=number

metric m:8_1d_off_site_other_releases p:double l:8.1D_OFF-SITE_OTHER_RELEASES t:dataTypeName=number

metric m:8_2_energy_recovery_on_site p:integer l:8.2_ENERGY_RECOVERY_ON-SITE t:dataTypeName=number

metric m:8_3_energy_recovery_off_site p:double l:8.3_ENERGY_RECOVERY_OFF-SITE t:dataTypeName=number

metric m:8_4_recycling_on_site p:double l:8.4_RECYCLING_ON-SITE t:dataTypeName=number

metric m:8_5_recycling_off_site p:double l:8.5_RECYCLING_OFF-SITE t:dataTypeName=number

metric m:8_6_treatment_on_site p:double l:8.6_TREATMENT_ON-SITE t:dataTypeName=number

metric m:8_7_treatment_off_site p:double l:8.7_TREATMENT_OFF-SITE t:dataTypeName=number

metric m:prod_waste_8_1_thru_8_7 p:double l:PROD._WASTE_(8.1_THRU_8.7) t:dataTypeName=number

metric m:8_8_one_time_release p:double l:8.8_ONE-TIME_RELEASE t:dataTypeName=number

metric m:8_9_production_ratio p:float l:8.9_PRODUCTION_RATIO t:dataTypeName=number

entity e:fma9-k2kj l:"Toxic Release Inventory Facility List 2015" t:attribution="U.S. Environmental Protection Agency" t:url=https://data.ct.gov/api/views/fma9-k2kj

property e:fma9-k2kj t:meta.view v:id=fma9-k2kj v:category="Environment and Natural Resources" v:attributionLink="https://iaspub.epa.gov/triexplorer/tri_factsheet.factsheet_forstate?pstate=CT&pYear=2015&pParent=TRI&pDataSet=TRIQ1#pane-1" v:averageRating=0 v:name="Toxic Release Inventory Facility List 2015" v:attribution="U.S. Environmental Protection Agency"

property e:fma9-k2kj t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:fma9-k2kj t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:fma9-k2kj t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| year | tri_facility_id | frs_id       | facility_name                                      | street_address      | city          | county     | st | zip  | latitude  | longitude  | bia_code | tribe | federal_facility | industry_sector_code | industry_sector                   | primary_sic | sic_2 | sic_3 | sic_4 | sic_5 | sic_6 | primary_naics | naics_2 | naics_3 | naics_4 | naics_5 | naics_6 | doc_ctrl_num  | chemical                      | cas_compound_id | srs_id | clear_air_act_chemical | classification | metal | metal_category | carcinogen | form_type | unit_of_measure | 5_1_fugitive_air | 5_2_stack_air | 5_3_water | 5_4_underground | 5_4_1_underground_class_i | 5_4_2_underground_class_ii_v | 5_5_1_landfills | 5_5_1a_rcra_c_landfills | 5_5_1b_other_landfills | 5_5_2_land_treatment | 5_5_3_surface_impoundment | 5_5_3a_rcra_c_surface_imp | 5_5_3b_other_surface_imp | 5_5_4_other_disposal | on_site_release_total | 6_1_potw_transfers_for_release | 6_1_potw_transfers_for_treatm | 6_1_potw_total_transfers | 6_2_m10 | 6_2_m41 | 6_2_m62 | 6_2_m71 | 6_2_m81 | 6_2_m82 | 6_2_m72 | 6_2_m63 | 6_2_m66 | 6_2_m67 | 6_2_m64 | 6_2_m65 | 6_2_m73 | 6_2_m79 | 6_2_m90 | 6_2_m94 | 6_2_m99 | off_site_release_total | 6_2_m20 | 6_2_m24   | 6_2_m26 | 6_2_m28 | 6_2_m93 | off_site_recycled_total | 6_2_m56 | 6_2_m92 | off_site_recovery_total | 6_2_m40 | 6_2_m50 | 6_2_m54 | 6_2_m61 | 6_2_m69 | 6_2_m95 | off_site_treated_total | total_releases | 8_1_releases | 8_1a_on_site_contained_rel | 8_1b_on_site_other_releases | 8_1c_off_site_contained_rel | 8_1d_off_site_other_releases | 8_2_energy_recovery_on_site | 8_3_energy_recovery_off_site | 8_4_recycling_on_site | 8_5_recycling_off_site | 8_6_treatment_on_site | 8_7_treatment_off_site | prod_waste_8_1_thru_8_7 | 8_8_one_time_release | prod_ratio_or_activity | 8_9_production_ratio | parent_company_name                | parent_company_db_number | 
| ==== | =============== | ============ | ================================================== | =================== | ============= | ========== | == | ==== | ========= | ========== | ======== | ===== | ================ | ==================== | ================================= | =========== | ===== | ===== | ===== | ===== | ===== | ============= | ======= | ======= | ======= | ======= | ======= | ============= | ============================= | =============== | ====== | ====================== | ============== | ===== | ============== | ========== | ========= | =============== | ================ | ============= | ========= | =============== | ========================= | ============================ | =============== | ======================= | ====================== | ==================== | ========================= | ========================= | ======================== | ==================== | ===================== | ============================== | ============================= | ======================== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ====================== | ======= | ========= | ======= | ======= | ======= | ======================= | ======= | ======= | ======================= | ======= | ======= | ======= | ======= | ======= | ======= | ====================== | ============== | ============ | ========================== | =========================== | =========================== | ============================ | =========================== | ============================ | ===================== | ====================== | ===================== | ====================== | ======================= | ==================== | ====================== | ==================== | ================================== | ======================== | 
| 2015 | 06492BYKCH524SO | 110000316630 | BYK USA INC                                        | 524 S CHERRY ST     | WALLINGFORD   | NEW HAVEN  | CT | 6492 | 41.4425   | -72.83477  |          |       | NO               | 325                  | Chemicals                         |             |       |       |       |       |       | 325510        |         |         |         |         |         | 1315210000000 | 1,2,4-TRIMETHYLBENZENE        | 95636           | 16261  | NO                     | TRI            | NO    | 0              | NO         | R         | Pounds          | 42               | 41            | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 83                    | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0       | 0         | 0       | 0       | 0       | 0                       | 13694   | 0       | 13694                   | 0       | 3772    | 0       | 0       | 0       | 0       | 3772                   | 83             | 0            | 0                          | 83                          | 0                           | 0                            | 0                           | 13694                        | 20680                 | 0                      | 0                     | 3772                   | 38229                   |                      | PRODUCTION             | 1.11                 | NA                                 |                          | 
| 2015 | 06320SCSTG15MOH | 110000786524 | US COAST GUARD ACADEMY                             | 15 MOHEGAN AVE      | NEW LONDON    | NEW LONDON | CT | 6320 | 41.371504 | -72.09932  |          |       | YES              | 999                  | Other                             |             |       |       |       |       |       | 611310        |         |         |         |         |         | 1315210000000 | LEAD                          | 7439921         | 149583 | YES                    | PBT            | YES   | 1              | YES        | R         | Pounds          | 0                | 1.04          | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 1.04                  | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 2636    | 0       | 0       | 2636                   | 0       | 1945      | 0       | 0       | 0       | 1945                    | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 2637.04        | 0            | 0                          | 1.04                        | 0                           | 2636                         | 0                           | 0                            | 0                     | 1945                   | 0                     | 0                      | 4582.04                 |                      | PRODUCTION             | 1.53                 | US DEPARTMENT OF HOMELAND SECURITY | NA                       | 
| 2015 | 06787QLTYR135SO | 110000317434 | UNIMETAL SURFACE FINISHING LLC                     | 135 S MAIN ST       | THOMASTON     | LITCHFIELD | CT | 6787 | 41.66935  | -73.07774  |          |       | NO               | 332                  | Fabricated Metals                 |             |       |       |       |       |       | 332813        |         |         |         |         |         | 1315210000000 | NITRATE COMPOUNDS             | N511            | 649616 | NO                     | TRI            | NO    | 0              | NO         | R         | Pounds          | 60330            | 0             | 7306      | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 67636                 | 1902.6                         | 211.4                         | 2114                     | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1902.6                 | 0       | 0         | 0       | 0       | 0       | 0                       | 0       | 0       | 0                       | 20.28   | 0       | 0       | 0       | 0       | 0       | 231.68                 | 71441.2        | 0            | 0                          | 67636                       | 0                           | 1902.6                       | 0                           | 0                            | 0                     | 0                      | 0                     | 231.68                 | 69770.28                |                      | PRODUCTION             | 1.56                 | UNIMETAL SURFACE FINISHING LLC     | NA                       | 
| 2015 | 06512NRTHS481ES | 110000491977 | MOTIVA ENTERPRISES LLC NEW HAVEN TERMINAL          | 481 E SHORE PKWY    | NEW HAVEN     | NEW HAVEN  | CT | 6512 | 41.290439 | -72.900798 |          |       | NO               | 4247                 | Petroleum Bulk Terminals          |             |       |       |       |       |       | 424710        |         |         |         |         |         | 1315210000000 | ETHYLBENZENE                  | 100414          | 19406  | YES                    | TRI            | NO    | 0              | NO         | R         | Pounds          | 191              | 75            | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 266                   | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1       | 0       | 0       | 0       | 0       | 1       | 0       | 2                      | 0       | 0         | 0       | 0       | 0       | 0                       | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 268            | 0            | 0                          | 266                         | 1                           | 1                            | 0                           | 0                            | 0                     | 0                      | 75                    | 0                      | 343                     |                      | PRODUCTION             | 1.06                 | MOTIVA ENTERPRISES LLC             | 23838670                 | 
| 2015 | 0681WBLMRC33TUR | 110069308261 | BELIMO AIRCONTROLS                                 | 33 TURNER RD        | DANBURY       | FAIRFIELD  | CT | 6810 | 41.375526 | -73.536186 |          |       | NO               | 333                  | Machinery                         |             |       |       |       |       |       | 333415        |         |         |         |         |         | 1315210000000 | DIISOCYANATES                 | N120            | 649715 | YES                    | TRI            | NO    | 0              | NO         | R         | Pounds          | 0                | 0             | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 0                     | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0       | 0         | 0       | 0       | 0       | 0                       | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0              | 0            | 0                          | 0                           | 0                           | 0                            | 0                           | 0                            | 0                     | 0                      | 0                     | 0                      | 0                       |                      | PRODUCTION             | 1.2                  | NA                                 |                          | 
| 2015 | 06511HKRVT73WEL | 110000316774 | H KREVIT & CO INC                                  | 67 WELTON ST        | NEW HAVEN     | NEW HAVEN  | CT | 6511 | 41.326389 | -72.895556 |          |       | NO               | 325                  | Chemicals                         |             |       |       |       |       |       | 325180        |         |         |         |         |         | 1315210000000 | CHLORINE                      | 7782505         | 154328 | YES                    | TRI            | NO    | 0              | NO         | R         | Pounds          | 85               | 39            | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 124                   | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0       | 0         | 0       | 0       | 0       | 0                       | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 124            | 0            | 0                          | 124                         | 0                           | 0                            | 0                           | 0                            | 0                     | 0                      | 3800                  | 0                      | 3924                    |                      | PRODUCTION             | 0.84                 | NA                                 |                          | 
| 2015 | 06787YLTSF45OLD | 110000317452 | STEWART EFI CT LLC                                 | 45 OLD WATERBURY RD | THOMASTON     | LITCHFIELD | CT | 6787 | 41.65173  | -73.07802  |          |       | NO               | 332                  | Fabricated Metals                 |             |       |       |       |       |       | 332119        |         |         |         |         |         | 1315210000000 | COPPER                        | 7440508         | 150086 | NO                     | TRI            | YES   | 1              | NO         | R         | Pounds          | 0                | 0             | 0.0916    | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 0.0916                | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0       | 178443.37 | 0       | 0       | 0       | 178443.37               | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0.0916         | 0            | 0                          | 0.0916                      | 0                           | 0                            | 0                           | 0                            | 0                     | 178443.37              | 0                     | 0                      | 178443.4616             |                      | PRODUCTION             | 0.82                 | STEWART EFI LLC                    | NA                       | 
| 2015 | 06787YLTSF45OLD | 110000317452 | STEWART EFI CT LLC                                 | 45 OLD WATERBURY RD | THOMASTON     | LITCHFIELD | CT | 6787 | 41.65173  | -73.07802  |          |       | NO               | 332                  | Fabricated Metals                 |             |       |       |       |       |       | 332119        |         |         |         |         |         | 1315210000000 | NICKEL                        | 7440020         | 149674 | YES                    | TRI            | YES   | 1              | YES        | R         | Pounds          | 0                | 0             | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 0                     | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0       | 125364.03 | 0       | 0       | 0       | 125364.03               | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0              | 0            | 0                          | 0                           | 0                           | 0                            | 0                           | 0                            | 0                     | 125364.03              | 0                     | 0                      | 125364.03               |                      | PRODUCTION             | 0.98                 | STEWART EFI LLC                    | NA                       | 
| 2015 | 06075NRTHMUPPER | 110000315454 | TTM PRINTED CIRCUIT GROUP MULT ILAYER STAFFORD DIV | 228 UPPER RD        | STAFFORDVILLE | TOLLAND    | CT | 6077 | 41.993952 | -72.261569 |          |       | NO               | 334                  | Computers and Electronic Products |             |       |       |       |       |       | 334412        |         |         |         |         |         | 1315210000000 | COPPER COMPOUNDS              | N100            | 649491 | NO                     | TRI            | YES   | 1              | NO         | R         | Pounds          | 0                | 10            | 1.7       | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 11.7                  | 1.3                            | 0                             | 1.3                      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1.3                    | 0       | 178190    | 0       | 0       | 0       | 178190                  | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 14.3           | 0            | 0                          | 11.7                        | 0.936                       | 0.364                        | 0                           | 0                            | 0                     | 178190                 | 0                     | 0                      | 178203                  |                      | PRODUCTION             | 0.93                 | TTM TECHNOLOGIES INC               | NA                       | 
| 2015 | 06791GNDST255BG | 110002009157 | O&G INDUSTRIES INC                                 | 255 BOGUE RD        | HARWINTON     | LITCHFIELD | CT | 6791 | 41.777312 | -73.115213 |          |       | NO               | 324                  | Petroleum                         |             |       |       |       |       |       | 324121        | 327999  | 327320  |         |         |         | 1315210000000 | POLYCYCLIC AROMATIC COMPOUNDS | N590            | 649749 | YES                    | PBT            | NO    | 0              | YES        | R         | Pounds          | 0                | 0.42          | 0         | 0               | 0                         | 0                            | 0               | 0                       | 0                      | 0                    | 0                         | 0                         | 0                        | 0                    | 0.42                  | 0                              | 0                             | 0                        | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0       | 0         | 0       | 0       | 0       | 0                       | 0       | 0       | 0                       | 0       | 0       | 0       | 0       | 0       | 0       | 0                      | 0.42           | 0            | 0                          | 0.42                        | 0                           | 0                            | 0                           | 0                            | 0                     | 0                      | 0                     | 0                      | 0.42                    |                      | PRODUCTION             | 1.3                  | O & G INDUSTRIES INC               | 18838136                 | 
```