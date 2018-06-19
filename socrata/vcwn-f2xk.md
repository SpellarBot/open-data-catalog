# Regression data for Inclusionary Housing Simulation Model

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regression-data-for-inclusionary-housing-simulation-model) |
| Metadata | [Link](https://data.sfgov.org/api/views/vcwn-f2xk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/vcwn-f2xk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/vcwn-f2xk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | vcwn-f2xk |
| Name | Regression data for Inclusionary Housing Simulation Model |
| Category | Economy and Community |
| Tags | inclusionary housing, regression model, statistics, probability |
| Created | 2016-11-23T18:16:01Z |
| Publication Date | 2016-11-29T02:43:58Z |

## Description

In order to understand how higher inclusionary housing requirements affects the feasibility of new market-rate housing development, the Controller's Office contracted with Blue Sky Consulting Group to statistically model the factors that affect the probability of housing development in San Francisco. This data underlies the model reported in our preliminary report. An overview of the statistical analysis is provided in main section of the report, with more details provided in the Appendix.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | year              | year              | number    | number      |
| Yes      | numeric metric | dev_year          | Dev_Year          | number    | number      |
| Yes      | series tag     | mapblklot_master  | MapBlkLot_Master  | text      | text        |
| Yes      | series tag     | mapblklot_year    | MapBlkLot_Year    | text      | text        |
| Yes      | numeric metric | res_dummy         | Res_Dummy         | number    | number      |
| Yes      | numeric metric | price_oea         | Price_OEA         | number    | number      |
| Yes      | numeric metric | inc_costsqft      | Inc_CostSqFt      | number    | number      |
| Yes      | numeric metric | inc_unitfee1000   | Inc_UnitFee1000   | number    | number      |
| Yes      | numeric metric | price_zillow      | Price_Zillow      | number    | number      |
| Yes      | numeric metric | rentcomm_yrend    | RentComm_YrEnd    | number    | number      |
| Yes      | numeric metric | rentcomm_avg      | RentComm_Avg      | number    | number      |
| Yes      | numeric metric | constr_index      | Constr_Index      | number    | number      |
| Yes      | numeric metric | bldg_index        | Bldg_Index        | number    | number      |
| Yes      | numeric metric | permits_msa_tot   | Permits_MSA_Tot   | number    | number      |
| Yes      | numeric metric | permits_msa_5plus | Permits_MSA_5Plus | number    | number      |
| Yes      | numeric metric | sfcity_unemprate  | SFCity_UnempRate  | number    | number      |
| Yes      | numeric metric | sfcity_emp        | SFCity_Emp        | number    | number      |
| Yes      | numeric metric | sfmsa_unemprate   | SFMSA_UnempRate   | number    | number      |
| Yes      | numeric metric | sfmsa_emp         | SFMSA_Emp         | number    | number      |
| Yes      | numeric metric | dj_tsm            | DJ_TSM            | number    | number      |
| Yes      | numeric metric | sp500             | SP500             | number    | number      |
| Yes      | numeric metric | nasdaq            | NASDAQ            | number    | number      |
| Yes      | numeric metric | conf_cb           | Conf_CB           | number    | number      |
| Yes      | numeric metric | conf_um           | Conf_UM           | number    | number      |
| Yes      | numeric metric | intrate_10yr      | IntRate_10yr      | number    | number      |
| Yes      | numeric metric | intrate_mortg     | IntRate_Mortg     | number    | number      |
| Yes      | series tag     | landuse_asgiven   | LandUse_AsGiven   | text      | text        |
| Yes      | numeric metric | lu_yr_missing     | lu_yr_Missing     | number    | number      |
| Yes      | numeric metric | lu_yr_cie         | lu_yr_CIE         | number    | number      |
| Yes      | numeric metric | lu_yr_ind         | lu_yr_IND         | number    | number      |
| Yes      | numeric metric | lu_yr_med         | lu_yr_MED         | number    | number      |
| Yes      | numeric metric | lu_yr_mips        | lu_yr_MIPS        | number    | number      |
| Yes      | numeric metric | lu_yr_mixed       | lu_yr_Mixed       | number    | number      |
| Yes      | numeric metric | lu_yr_openspace   | lu_yr_OpenSpace   | number    | number      |
| Yes      | numeric metric | lu_yr_paperlot    | lu_yr_Paperlot    | number    | number      |
| Yes      | numeric metric | lu_yr_public      | lu_yr_Public      | number    | number      |
| Yes      | numeric metric | lu_yr_resid       | lu_yr_Resid       | number    | number      |
| Yes      | numeric metric | lu_yr_retail      | lu_yr_RETAIL      | number    | number      |
| Yes      | numeric metric | lu_yr_row         | lu_yr_ROW         | number    | number      |
| Yes      | numeric metric | lu_yr_vacant      | lu_yr_VACANT      | number    | number      |
| Yes      | numeric metric | lu_yr_visitor     | lu_yr_VISITOR     | number    | number      |
| Yes      | series tag     | zoning_asgiven    | Zoning_AsGiven    | text      | text        |
| Yes      | numeric metric | z_commercial      | z_Commercial      | number    | number      |
| Yes      | numeric metric | z_dtr             | z_DTR             | number    | number      |
| Yes      | numeric metric | z_missing         | z_Missing         | number    | number      |
| Yes      | numeric metric | z_mixeduse        | z_MixedUse        | number    | number      |
| Yes      | numeric metric | z_open            | z_Open            | number    | number      |
| Yes      | numeric metric | z_pdr             | z_PDR             | number    | number      |
| Yes      | numeric metric | z_public          | z_Public          | number    | number      |
| Yes      | numeric metric | z_rc3             | z_RC3             | number    | number      |
| Yes      | numeric metric | z_rc4             | z_RC4             | number    | number      |
| Yes      | numeric metric | z_redev           | z_Redev           | number    | number      |
| Yes      | numeric metric | z_res_low         | z_Res_Low         | number    | number      |
| Yes      | numeric metric | z_rm1             | z_RM1             | number    | number      |
| Yes      | numeric metric | z_rm2             | z_RM2             | number    | number      |
| Yes      | numeric metric | z_rm3             | z_RM3             | number    | number      |
| Yes      | numeric metric | z_rm4             | z_RM4             | number    | number      |
| Yes      | numeric metric | z_rsd             | z_RSD             | number    | number      |
| Yes      | numeric metric | z_rto             | z_RTO             | number    | number      |
| Yes      | numeric metric | z_sli             | z_SLI             | number    | number      |
| Yes      | numeric metric | z_slr             | z_SLR             | number    | number      |
| Yes      | numeric metric | z_sso             | z_SSO             | number    | number      |
| Yes      | numeric metric | parkingminreq     | ParkingMinReq     | number    | number      |
| Yes      | numeric metric | area              | Area              | number    | number      |
| Yes      | numeric metric | bldg_sqft_use     | Bldg_SqFt_Use     | number    | number      |
| Yes      | numeric metric | env_1000_dens     | Env_1000_Dens     | number    | number      |
| Yes      | numeric metric | shistoric1        | SHistoric1        | number    | number      |
| Yes      | numeric metric | devpotential_dens | DevPotential_Dens | number    | number      |
| Yes      | numeric metric | n_bayview         | n_Bayview         | number    | number      |
| Yes      | numeric metric | n_bernal          | n_Bernal          | number    | number      |
| Yes      | numeric metric | n_castro          | n_Castro          | number    | number      |
| Yes      | numeric metric | n_china           | n_China           | number    | number      |
| Yes      | numeric metric | n_crocker         | n_Crocker         | number    | number      |
| Yes      | numeric metric | n_diamond         | n_Diamond         | number    | number      |
| Yes      | numeric metric | n_downtown        | n_Downtown        | number    | number      |
| Yes      | numeric metric | n_excel           | n_Excel           | number    | number      |
| Yes      | numeric metric | n_finan           | n_Finan           | number    | number      |
| Yes      | numeric metric | n_ggpark          | n_GGPark          | number    | number      |
| Yes      | numeric metric | n_haight          | n_Haight          | number    | number      |
| Yes      | numeric metric | n_inrich          | n_InRich          | number    | number      |
| Yes      | numeric metric | n_insun           | n_InSun           | number    | number      |
| Yes      | numeric metric | n_lakeshore       | n_Lakeshore       | number    | number      |
| Yes      | numeric metric | n_marina          | n_Marina          | number    | number      |
| Yes      | numeric metric | n_mission         | n_Mission         | number    | number      |
| Yes      | numeric metric | n_missbay         | n_MissBay         | number    | number      |
| Yes      | numeric metric | n_nob             | n_Nob             | number    | number      |
| Yes      | numeric metric | n_noe             | n_Noe             | number    | number      |
| Yes      | numeric metric | n_northb          | n_NorthB          | number    | number      |
| Yes      | numeric metric | n_oceanv          | n_OceanV          | number    | number      |
| Yes      | numeric metric | n_outmiss         | n_OutMiss         | number    | number      |
| Yes      | numeric metric | n_outrich         | n_OutRich         | number    | number      |
| Yes      | numeric metric | n_outsun          | n_OutSun          | number    | number      |
| Yes      | numeric metric | n_pachts          | n_PacHts          | number    | number      |
| Yes      | numeric metric | n_parkside        | n_Parkside        | number    | number      |
| Yes      | numeric metric | n_potrero         | n_Potrero         | number    | number      |
| Yes      | numeric metric | n_presid          | n_Presid          | number    | number      |
| Yes      | numeric metric | n_presidht        | n_PresidHt        | number    | number      |
| Yes      | numeric metric | n_russian         | n_Russian         | number    | number      |
| Yes      | numeric metric | n_seacliff        | n_Seacliff        | number    | number      |
| Yes      | numeric metric | n_soma            | n_SOMA            | number    | number      |
| Yes      | numeric metric | n_tiybi           | n_TIYBI           | number    | number      |
| Yes      | numeric metric | n_twin            | n_Twin            | number    | number      |
| Yes      | numeric metric | n_visit           | n_Visit           | number    | number      |
| Yes      | numeric metric | n_westtp          | n_WestTP          | number    | number      |
| Yes      | numeric metric | n_westadd         | n_WestAdd         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vcwn-f2xk d:2001-01-01T00:00:00.000Z t:mapblklot_master=0001001 t:zoning_asgiven=P t:mapblklot_year=0001001 t:landuse_asgiven="PAPER LOT" m:n_northb=0 m:n_inrich=0 m:rentcomm_yrend=93.5556 m:price_zillow=49.021000468 m:sfmsa_emp=2186081 m:n_pachts=0 m:inc_unitfee1000=0 m:lu_yr_missing=0 m:n_westadd=0 m:n_outsun=0 m:n_missbay=0 m:n_crocker=0 m:n_marina=0 m:n_soma=0 m:n_excel=0 m:n_castro=0 m:res_dummy=0 m:bldg_sqft_use=21248.865016 m:n_noe=0 m:z_sso=0 m:sfcity_emp=445193 m:sp500=1148.079956 m:n_nob=0 m:n_westtp=0 m:conf_um=88.8 m:intrate_mortg=7.07 m:z_rsd=0 m:z_public=1 m:inc_costsqft=0 m:z_missing=0 m:lu_yr_retail=0 m:lu_yr_mixed=0 m:z_slr=0 m:nasdaq=1950.400024 m:lu_yr_vacant=0 m:n_bernal=0 m:shistoric1=0 m:z_dtr=0 m:permits_msa_tot=17323 m:lu_yr_mips=0 m:z_open=0 m:n_visit=0 m:intrate_10yr=5.09 m:lu_yr_cie=0 m:price_oea=50.561216064 m:z_redev=0 m:n_bayview=0 m:n_downtown=0 m:z_pdr=0 m:lu_yr_row=0 m:permits_msa_5plus=7955 m:lu_yr_paperlot=1 m:n_ggpark=0 m:z_sli=0 m:n_finan=0 m:n_presidht=0 m:dj_tsm=35.4339349 m:z_commercial=0 m:n_potrero=0 m:n_oceanv=0 m:n_outmiss=0 m:env_1000_dens=42.497730032 m:conf_cb=94.6 m:sfmsa_unemprate=4.4 m:bldg_index=4025.65 m:n_parkside=0 m:constr_index=7399.07 m:devpotential_dens=2 m:z_rto=0 m:area=28331.820021 m:z_rc3=0 m:n_tiybi=0 m:z_rc4=0 m:n_insun=0 m:sfcity_unemprate=5.1 m:dev_year=0 m:lu_yr_resid=0 m:n_twin=0 m:n_seacliff=0 m:lu_yr_visitor=0 m:n_china=0 m:n_outrich=0 m:lu_yr_openspace=0 m:n_presid=0 m:lu_yr_med=0 m:lu_yr_ind=0 m:z_mixeduse=0 m:n_lakeshore=0 m:n_russian=1 m:n_mission=0 m:n_haight=0 m:rentcomm_avg=98.6214825 m:z_res_low=0 m:z_rm1=0 m:z_rm2=0 m:z_rm3=0 m:z_rm4=0 m:lu_yr_public=0 m:n_diamond=0

series e:vcwn-f2xk d:2002-01-01T00:00:00.000Z t:mapblklot_master=0001001 t:zoning_asgiven=P t:mapblklot_year=0001001 t:landuse_asgiven=PDR m:n_northb=0 m:n_inrich=0 m:rentcomm_yrend=97.52959 m:price_zillow=52.208196801 m:sfmsa_emp=2103900 m:n_pachts=0 m:inc_unitfee1000=29.23575 m:lu_yr_missing=0 m:n_westadd=0 m:n_outsun=0 m:n_missbay=0 m:n_crocker=0 m:n_marina=0 m:n_soma=0 m:n_excel=0 m:n_castro=0 m:res_dummy=0 m:bldg_sqft_use=21248.865016 m:n_noe=0 m:z_sso=0 m:sfcity_emp=417259 m:sp500=879.820007 m:n_nob=0 m:n_westtp=0 m:conf_um=86.7 m:intrate_mortg=6.05 m:z_rsd=0 m:z_public=1 m:inc_costsqft=28.046393194 m:z_missing=0 m:lu_yr_retail=0 m:lu_yr_mixed=0 m:z_slr=0 m:nasdaq=1335.51001 m:lu_yr_vacant=0 m:n_bernal=0 m:shistoric1=0 m:z_dtr=0 m:permits_msa_tot=16914 m:lu_yr_mips=0 m:z_open=0 m:n_visit=0 m:intrate_10yr=4.03 m:lu_yr_cie=0 m:price_oea=53.644685261 m:z_redev=0 m:n_bayview=0 m:n_downtown=0 m:z_pdr=0 m:lu_yr_row=0 m:permits_msa_5plus=5703 m:lu_yr_paperlot=0 m:n_ggpark=0 m:z_sli=0 m:n_finan=0 m:n_presidht=0 m:dj_tsm=28.0425057 m:z_commercial=0 m:n_potrero=0 m:n_oceanv=0 m:n_outmiss=0 m:env_1000_dens=42.497730032 m:conf_cb=80.7 m:sfmsa_unemprate=6.2 m:bldg_index=4093.21 m:n_parkside=0 m:constr_index=7644.46 m:devpotential_dens=2 m:z_rto=0 m:area=28331.820021 m:z_rc3=0 m:n_tiybi=0 m:z_rc4=0 m:n_insun=0 m:sfcity_unemprate=6.9 m:dev_year=0 m:lu_yr_resid=0 m:n_twin=0 m:n_seacliff=0 m:lu_yr_visitor=0 m:n_china=0 m:n_outrich=0 m:lu_yr_openspace=0 m:n_presid=0 m:lu_yr_med=0 m:lu_yr_ind=0 m:z_mixeduse=0 m:n_lakeshore=0 m:n_russian=1 m:n_mission=0 m:n_haight=0 m:rentcomm_avg=96.96121 m:z_res_low=0 m:z_rm1=0 m:z_rm2=0 m:z_rm3=0 m:z_rm4=0 m:lu_yr_public=0 m:n_diamond=0

series e:vcwn-f2xk d:2003-01-01T00:00:00.000Z t:mapblklot_master=0001001 t:zoning_asgiven=P t:mapblklot_year=0001001 t:landuse_asgiven=PDR m:n_northb=0 m:n_inrich=0 m:rentcomm_yrend=85.5927 m:price_zillow=55.933721812 m:sfmsa_emp=2051117 m:n_pachts=0 m:inc_unitfee1000=29.23575 m:lu_yr_missing=0 m:n_westadd=0 m:n_outsun=0 m:n_missbay=0 m:n_crocker=0 m:n_marina=0 m:n_soma=0 m:n_excel=0 m:n_castro=0 m:res_dummy=0 m:bldg_sqft_use=21248.865016 m:n_noe=0 m:z_sso=0 m:sfcity_emp=400587 m:sp500=1111.920044 m:n_nob=0 m:n_westtp=0 m:conf_um=92.6 m:intrate_mortg=5.88 m:z_rsd=0 m:z_public=1 m:inc_costsqft=26.674753692 m:z_missing=0 m:lu_yr_retail=0 m:lu_yr_mixed=0 m:z_slr=0 m:nasdaq=2003.369995 m:lu_yr_vacant=0 m:n_bernal=0 m:shistoric1=0 m:z_dtr=0 m:permits_msa_tot=21931 m:lu_yr_mips=0 m:z_open=0 m:n_visit=0 m:intrate_10yr=4.27 m:lu_yr_cie=0 m:price_oea=54.746212228 m:z_redev=0 m:n_bayview=0 m:n_downtown=0 m:z_pdr=0 m:lu_yr_row=0 m:permits_msa_5plus=10129 m:lu_yr_paperlot=0 m:n_ggpark=0 m:z_sli=0 m:n_finan=0 m:n_presidht=0 m:dj_tsm=36.9153462 m:z_commercial=0 m:n_potrero=0 m:n_oceanv=0 m:n_outmiss=0 m:env_1000_dens=42.497730032 m:conf_cb=91.7 m:sfmsa_unemprate=6.3 m:bldg_index=4113.11 m:n_parkside=0 m:constr_index=7788.8 m:devpotential_dens=2 m:z_rto=0 m:area=28331.820021 m:z_rc3=0 m:n_tiybi=0 m:z_rc4=0 m:n_insun=0 m:sfcity_unemprate=6.7 m:dev_year=0 m:lu_yr_resid=0 m:n_twin=0 m:n_seacliff=0 m:lu_yr_visitor=0 m:n_china=0 m:n_outrich=0 m:lu_yr_openspace=0 m:n_presid=0 m:lu_yr_med=0 m:lu_yr_ind=0 m:z_mixeduse=0 m:n_lakeshore=0 m:n_russian=1 m:n_mission=0 m:n_haight=0 m:rentcomm_avg=89.0437 m:z_res_low=0 m:z_rm1=0 m:z_rm2=0 m:z_rm3=0 m:z_rm4=0 m:lu_yr_public=0 m:n_diamond=0
```

## Meta Commands

```ls
metric m:dev_year p:integer l:Dev_Year t:dataTypeName=number

metric m:res_dummy p:integer l:Res_Dummy t:dataTypeName=number

metric m:price_oea p:double l:Price_OEA t:dataTypeName=number

metric m:inc_costsqft p:double l:Inc_CostSqFt t:dataTypeName=number

metric m:inc_unitfee1000 p:float l:Inc_UnitFee1000 t:dataTypeName=number

metric m:price_zillow p:double l:Price_Zillow t:dataTypeName=number

metric m:rentcomm_yrend p:float l:RentComm_YrEnd t:dataTypeName=number

metric m:rentcomm_avg p:float l:RentComm_Avg t:dataTypeName=number

metric m:constr_index p:float l:Constr_Index t:dataTypeName=number

metric m:bldg_index p:float l:Bldg_Index t:dataTypeName=number

metric m:permits_msa_tot p:integer l:Permits_MSA_Tot t:dataTypeName=number

metric m:permits_msa_5plus p:integer l:Permits_MSA_5Plus t:dataTypeName=number

metric m:sfcity_unemprate p:float l:SFCity_UnempRate t:dataTypeName=number

metric m:sfcity_emp p:integer l:SFCity_Emp t:dataTypeName=number

metric m:sfmsa_unemprate p:float l:SFMSA_UnempRate t:dataTypeName=number

metric m:sfmsa_emp p:integer l:SFMSA_Emp t:dataTypeName=number

metric m:dj_tsm p:double l:DJ_TSM t:dataTypeName=number

metric m:sp500 p:double l:SP500 t:dataTypeName=number

metric m:nasdaq p:double l:NASDAQ t:dataTypeName=number

metric m:conf_cb p:double l:Conf_CB t:dataTypeName=number

metric m:conf_um p:float l:Conf_UM t:dataTypeName=number

metric m:intrate_10yr p:float l:IntRate_10yr t:dataTypeName=number

metric m:intrate_mortg p:float l:IntRate_Mortg t:dataTypeName=number

metric m:lu_yr_missing p:integer l:lu_yr_Missing t:dataTypeName=number

metric m:lu_yr_cie p:integer l:lu_yr_CIE t:dataTypeName=number

metric m:lu_yr_ind p:integer l:lu_yr_IND t:dataTypeName=number

metric m:lu_yr_med p:integer l:lu_yr_MED t:dataTypeName=number

metric m:lu_yr_mips p:integer l:lu_yr_MIPS t:dataTypeName=number

metric m:lu_yr_mixed p:integer l:lu_yr_Mixed t:dataTypeName=number

metric m:lu_yr_openspace p:integer l:lu_yr_OpenSpace t:dataTypeName=number

metric m:lu_yr_paperlot p:integer l:lu_yr_Paperlot t:dataTypeName=number

metric m:lu_yr_public p:integer l:lu_yr_Public t:dataTypeName=number

metric m:lu_yr_resid p:integer l:lu_yr_Resid t:dataTypeName=number

metric m:lu_yr_retail p:integer l:lu_yr_RETAIL t:dataTypeName=number

metric m:lu_yr_row p:integer l:lu_yr_ROW t:dataTypeName=number

metric m:lu_yr_vacant p:integer l:lu_yr_VACANT t:dataTypeName=number

metric m:lu_yr_visitor p:integer l:lu_yr_VISITOR t:dataTypeName=number

metric m:z_commercial p:integer l:z_Commercial t:dataTypeName=number

metric m:z_dtr p:integer l:z_DTR t:dataTypeName=number

metric m:z_missing p:integer l:z_Missing t:dataTypeName=number

metric m:z_mixeduse p:integer l:z_MixedUse t:dataTypeName=number

metric m:z_open p:integer l:z_Open t:dataTypeName=number

metric m:z_pdr p:integer l:z_PDR t:dataTypeName=number

metric m:z_public p:integer l:z_Public t:dataTypeName=number

metric m:z_rc3 p:integer l:z_RC3 t:dataTypeName=number

metric m:z_rc4 p:integer l:z_RC4 t:dataTypeName=number

metric m:z_redev p:integer l:z_Redev t:dataTypeName=number

metric m:z_res_low p:integer l:z_Res_Low t:dataTypeName=number

metric m:z_rm1 p:integer l:z_RM1 t:dataTypeName=number

metric m:z_rm2 p:integer l:z_RM2 t:dataTypeName=number

metric m:z_rm3 p:integer l:z_RM3 t:dataTypeName=number

metric m:z_rm4 p:integer l:z_RM4 t:dataTypeName=number

metric m:z_rsd p:integer l:z_RSD t:dataTypeName=number

metric m:z_rto p:integer l:z_RTO t:dataTypeName=number

metric m:z_sli p:integer l:z_SLI t:dataTypeName=number

metric m:z_slr p:integer l:z_SLR t:dataTypeName=number

metric m:z_sso p:integer l:z_SSO t:dataTypeName=number

metric m:parkingminreq p:integer l:ParkingMinReq t:dataTypeName=number

metric m:area p:double l:Area t:dataTypeName=number

metric m:bldg_sqft_use p:double l:Bldg_SqFt_Use t:dataTypeName=number

metric m:env_1000_dens p:double l:Env_1000_Dens t:dataTypeName=number

metric m:shistoric1 p:integer l:SHistoric1 t:dataTypeName=number

metric m:devpotential_dens p:double l:DevPotential_Dens t:dataTypeName=number

metric m:n_bayview p:integer l:n_Bayview t:dataTypeName=number

metric m:n_bernal p:integer l:n_Bernal t:dataTypeName=number

metric m:n_castro p:integer l:n_Castro t:dataTypeName=number

metric m:n_china p:integer l:n_China t:dataTypeName=number

metric m:n_crocker p:integer l:n_Crocker t:dataTypeName=number

metric m:n_diamond p:integer l:n_Diamond t:dataTypeName=number

metric m:n_downtown p:integer l:n_Downtown t:dataTypeName=number

metric m:n_excel p:integer l:n_Excel t:dataTypeName=number

metric m:n_finan p:integer l:n_Finan t:dataTypeName=number

metric m:n_ggpark p:integer l:n_GGPark t:dataTypeName=number

metric m:n_haight p:integer l:n_Haight t:dataTypeName=number

metric m:n_inrich p:integer l:n_InRich t:dataTypeName=number

metric m:n_insun p:integer l:n_InSun t:dataTypeName=number

metric m:n_lakeshore p:integer l:n_Lakeshore t:dataTypeName=number

metric m:n_marina p:integer l:n_Marina t:dataTypeName=number

metric m:n_mission p:integer l:n_Mission t:dataTypeName=number

metric m:n_missbay p:integer l:n_MissBay t:dataTypeName=number

metric m:n_nob p:integer l:n_Nob t:dataTypeName=number

metric m:n_noe p:integer l:n_Noe t:dataTypeName=number

metric m:n_northb p:integer l:n_NorthB t:dataTypeName=number

metric m:n_oceanv p:integer l:n_OceanV t:dataTypeName=number

metric m:n_outmiss p:integer l:n_OutMiss t:dataTypeName=number

metric m:n_outrich p:integer l:n_OutRich t:dataTypeName=number

metric m:n_outsun p:integer l:n_OutSun t:dataTypeName=number

metric m:n_pachts p:integer l:n_PacHts t:dataTypeName=number

metric m:n_parkside p:integer l:n_Parkside t:dataTypeName=number

metric m:n_potrero p:integer l:n_Potrero t:dataTypeName=number

metric m:n_presid p:integer l:n_Presid t:dataTypeName=number

metric m:n_presidht p:integer l:n_PresidHt t:dataTypeName=number

metric m:n_russian p:integer l:n_Russian t:dataTypeName=number

metric m:n_seacliff p:integer l:n_Seacliff t:dataTypeName=number

metric m:n_soma p:integer l:n_SOMA t:dataTypeName=number

metric m:n_tiybi p:integer l:n_TIYBI t:dataTypeName=number

metric m:n_twin p:integer l:n_Twin t:dataTypeName=number

metric m:n_visit p:integer l:n_Visit t:dataTypeName=number

metric m:n_westtp p:integer l:n_WestTP t:dataTypeName=number

metric m:n_westadd p:integer l:n_WestAdd t:dataTypeName=number

entity e:vcwn-f2xk l:"Regression data for Inclusionary Housing Simulation Model" t:url=https://data.sfgov.org/api/views/vcwn-f2xk

property e:vcwn-f2xk t:meta.view v:id=vcwn-f2xk v:category="Economy and Community" v:averageRating=0 v:name="Regression data for Inclusionary Housing Simulation Model"

property e:vcwn-f2xk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:vcwn-f2xk t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:vcwn-f2xk t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| year | dev_year | mapblklot_master | mapblklot_year | res_dummy | price_oea    | inc_costsqft | inc_unitfee1000 | price_zillow | rentcomm_yrend | rentcomm_avg | constr_index | bldg_index   | permits_msa_tot | permits_msa_5plus | sfcity_unemprate | sfcity_emp | sfmsa_unemprate | sfmsa_emp | dj_tsm     | sp500       | nasdaq      | conf_cb | conf_um | intrate_10yr | intrate_mortg | landuse_asgiven | lu_yr_missing | lu_yr_cie | lu_yr_ind | lu_yr_med | lu_yr_mips | lu_yr_mixed | lu_yr_openspace | lu_yr_paperlot | lu_yr_public | lu_yr_resid | lu_yr_retail | lu_yr_row | lu_yr_vacant | lu_yr_visitor | zoning_asgiven | z_commercial | z_dtr | z_missing | z_mixeduse | z_open | z_pdr | z_public | z_rc3 | z_rc4 | z_redev | z_res_low | z_rm1 | z_rm2 | z_rm3 | z_rm4 | z_rsd | z_rto | z_sli | z_slr | z_sso | parkingminreq | area         | bldg_sqft_use | env_1000_dens | shistoric1 | devpotential_dens | n_bayview | n_bernal | n_castro | n_china | n_crocker | n_diamond | n_downtown | n_excel | n_finan | n_ggpark | n_haight | n_inrich | n_insun | n_lakeshore | n_marina | n_mission | n_missbay | n_nob | n_noe | n_northb | n_oceanv | n_outmiss | n_outrich | n_outsun | n_pachts | n_parkside | n_potrero | n_presid | n_presidht | n_russian | n_seacliff | n_soma | n_tiybi | n_twin | n_visit | n_westtp | n_westadd | 
| ==== | ======== | ================ | ============== | ========= | ============ | ============ | =============== | ============ | ============== | ============ | ============ | ============ | =============== | ================= | ================ | ========== | =============== | ========= | ========== | =========== | =========== | ======= | ======= | ============ | ============= | =============== | ============= | ========= | ========= | ========= | ========== | =========== | =============== | ============== | ============ | =========== | ============ | ========= | ============ | ============= | ============== | ============ | ===== | ========= | ========== | ====== | ===== | ======== | ===== | ===== | ======= | ========= | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ============= | ============ | ============= | ============= | ========== | ================= | ========= | ======== | ======== | ======= | ========= | ========= | ========== | ======= | ======= | ======== | ======== | ======== | ======= | =========== | ======== | ========= | ========= | ===== | ===== | ======== | ======== | ========= | ========= | ======== | ======== | ========== | ========= | ======== | ========== | ========= | ========== | ====== | ======= | ====== | ======= | ======== | ========= | 
| 2001 | 0        | 0001001          | 0001001        | 0         | 50.561216064 | 0            | 0               | 49.021000468 | 93.5556        | 98.6214825   | 7399.07      | 4025.65      | 17323           | 7955              | 5.1              | 445193     | 4.4             | 2186081   | 35.4339349 | 1148.079956 | 1950.400024 | 94.6    | 88.8    | 5.09         | 7.07          | PAPER LOT       | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 1              | 0            | 0           | 0            | 0         | 0            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2002 | 0        | 0001001          | 0001001        | 0         | 53.644685261 | 28.046393194 | 29.23575        | 52.208196801 | 97.52959       | 96.96121     | 7644.46      | 4093.21      | 16914           | 5703              | 6.9              | 417259     | 6.2             | 2103900   | 28.0425057 | 879.820007  | 1335.51001  | 80.7    | 86.7    | 4.03         | 6.05          | PDR             | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 0            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2003 | 0        | 0001001          | 0001001        | 0         | 54.746212228 | 26.674753692 | 29.23575        | 55.933721812 | 85.5927        | 89.0437      | 7788.8       | 4113.11      | 21931           | 10129             | 6.7              | 400587     | 6.3             | 2051117   | 36.9153462 | 1111.920044 | 2003.369995 | 91.7    | 92.6    | 4.27         | 5.88          | PDR             | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 0            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2004 | 0        | 0001001          | 0001001        | 0         | 60.970784125 | 25.900682051 | 29.23575        | 64.821391099 | 105.0989       | 97.618865    | 8228.39      | 4521.51      | 20731           | 9292              | 5.8              | 394397     | 5.5             | 2040353   | 41.57553   | 1211.920044 | 2175.439941 | 102.7   | 97.1    | 4.23         | 5.75          | PDR             | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 0            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2005 | 0        | 0001001          | 0001001        | 0         | 70.412461675 | 32.254785864 | 29.23575        | 74.219140934 | 119.2056       | 113.8927     | 8308.5883333 | 4620.2233333 | 20619           | 9499              | 5                | 392747     | 4.8             | 2043849   | 44.204103  | 1248.290039 | 2205.320068 | 103.8   | 91.5    | 4.47         | 6.27          | PAPERLOT        | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 1              | 0            | 0           | 0            | 0         | 0            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2006 | 0        | 0001001          | 0001001        | 0         | 72.87180959  | 42.041452481 | 50.1826         | 75.060935255 | 127.2001       | 121.758725   | 8618.0266667 | 4858.7075    | 20633           | 12112             | 4.2              | 398293     | 4.2             | 2064760   | 51.221926  | 1418.300049 | 2415.290039 | 110     | 91.7    | 4.56         | 6.14          | PAPERLOT        | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 1              | 0            | 0           | 0            | 0         | 0            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2007 | 0        | 0001001          | 0001001        | 0         | 73.648330662 | 70.421321025 | 68.6512         | 77.78405514  | 169.0764       | 154.379075   | 9095.5975    | 5047.6108333 | 14754           | 7354              | 4.2              | 414199     | 4.4             | 2097061   | 54.159184  | 1468.359985 | 2652.280029 | 90.6    | 75.5    | 4.1          | 6.1           | VACANT          | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 1            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2008 | 0        | 0001001          | 0001001        | 0         | 67.959258565 | 71.251364718 | 66.8956         | 74.124711466 | 138.1511       | 155.066275   | 9363.0683333 | 5319.1758333 | 11045           | 4483              | 5.3              | 432981     | 5.7             | 2113687   | 33.938118  | 903.25      | 1577.030029 | 38.6    | 60.1    | 2.42         | 5.33          | VACANT          | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 1            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2009 | 0        | 0001001          | 0001001        | 0         | 58.880187818 | 56.846630164 | 66.8956         | 67.70512179  | 94.36742       | 105.3436575  | 9737.8783333 | 5479.2683333 | 4644            | 1547              | 8.7              | 419546     | 9.4             | 2040528   | 43.9211329 | 1115.099976 | 2269.149902 | 53.6    | 72.5    | 3.59         | 4.93          | VACANT          | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 1            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
| 2010 | 0        | 0001001          | 0001001        | 0         | 60.272261274 | 54.899718004 | 66.8956         | 67.572759116 | 106.2536       | 100.546145   | 9896.3141667 | 5617.51      | 8800            | 5637              | 8.9              | 442695     | 9.9             | 2090453   | 51.7701492 | 1257.640015 | 2652.870117 | 63.4    | 74.5    | 3.29         | 4.71          | VACANT          | 0             | 0         | 0         | 0         | 0          | 0           | 0               | 0              | 0            | 0           | 0            | 0         | 1            | 0             | P              | 0            | 0     | 0         | 0          | 0      | 0     | 1        | 0     | 0     | 0       | 0         | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |               | 28331.820021 | 21248.865016  | 42.497730032  | 0          | 2                 | 0         | 0        | 0        | 0       | 0         | 0         | 0          | 0       | 0       | 0        | 0        | 0        | 0       | 0           | 0        | 0         | 0         | 0     | 0     | 0        | 0        | 0         | 0         | 0        | 0        | 0          | 0         | 0        | 0          | 1         | 0          | 0      | 0       | 0      | 0       | 0        | 0         | 
```