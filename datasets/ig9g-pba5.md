# Taxable Property Values By Tax District and Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/taxable-property-values-by-tax-district-and-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/ig9g-pba5) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ig9g-pba5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ig9g-pba5/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ig9g-pba5 |
| Name | Taxable Property Values By Tax District and Year |
| Attribution | Iowa Department of Management, Property Valuation System |
| Category | Government |
| Tags | property values, tax district, residential, agricultural, commercial, industrial, railroads, utilities, property taxes |
| Created | 2014-11-12T20:59:33Z |
| Publication Date | 2015-09-21T15:54:55Z |

## Description

This dataset contains taxable property values for classes of real property by tax district. Taxable values are based on assessed valuations after application of the statutory assessment limitation (i.e. rollback), and is the value to which tax rates are applied (e.g. 2012 net taxable valuations are used for the FY 2014 property tax levies).  Real property is mostly land, buildings, structures, and other improvements that are constructed on or in the land, attached to the land, or placed upon a foundation. Typical improvements include a building, house or mobile home, fences, and paving. Classes of real property include the following: Residential, Agricultural Land, Agricultural Buildings, Commercial, Industrial, Utilities and Railroads.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | tday_id                     | TDAY ID                     | text      | text        |
| Yes      | time           | assessment_year             | Assessment Year             | number    | number      |
| Yes      | series tag     | tax_district_code           | Tax District Code           | text      | text        |
| Yes      | series tag     | district_name               | District Name               | text      | text        |
| Yes      | series tag     | county_fip                  | County FIP                  | text      | text        |
| Yes      | series tag     | county_name                 | County Name                 | text      | text        |
| Yes      | series tag     | city_fip                    | City FIP                    | text      | text        |
| Yes      | series tag     | city_name                   | City Name                   | text      | text        |
| Yes      | series tag     | co_subdivision_fip          | Co Subdivision FIP          | text      | text        |
| Yes      | series tag     | township_name               | Township Name               | text      | text        |
| Yes      | series tag     | school_district_name        | School District Name        | text      | text        |
| Yes      | series tag     | property_type               | Property Type               | text      | text        |
| Yes      | numeric metric | residential                 | Residential                 | money     | money       |
| Yes      | numeric metric | ag_land                     | Ag Land                     | money     | money       |
| Yes      | numeric metric | ag_building                 | Ag Building                 | money     | money       |
| Yes      | numeric metric | commercial                  | Commercial                  | money     | money       |
| Yes      | numeric metric | industrial                  | Industrial                  | money     | money       |
| Yes      | numeric metric | reimb_ind_m_e_computers     | Reimb Ind M&E/Computers     | money     | money       |
| Yes      | numeric metric | non_reimb_ind_m_e_computers | Non-Reimb Ind M&E/Computers | money     | money       |
| Yes      | numeric metric | rail                        | Rail                        | money     | money       |
| Yes      | numeric metric | utilities_w_o_g_e           | Utilities w/o G&E           | money     | money       |
| Yes      | numeric metric | other                       | Other                       | money     | money       |
| Yes      | numeric metric | gross_w_o_g_e               | Gross w/o G&E               | money     | money       |
| Yes      | numeric metric | military_exempt             | Military Exempt             | money     | money       |
| Yes      | numeric metric | net_w_o_g_e                 | Net w/o G&E                 | money     | money       |
| Yes      | numeric metric | gas_electric                | Gas & Electric              | money     | money       |
| Yes      | numeric metric | open_spaces                 | Open Spaces                 | money     | money       |
| No       |                | prim_lat_dec                | PRIM_LAT_DEC                | number    | number      |
| No       |                | prim_long_dec               | PRIM_LONG_DEC               | number    | number      |
```

## Time Field

```ls
Value = assessment_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = prim_lat_dec,prim_long_dec
```

## Data Commands

```ls
series e:ig9g-pba5 d:2000-01-01T00:00:00.000Z t:co_subdivision_fip=1900194161 t:property_type=R t:school_district_name=ORIENT-MACKSBURG t:tax_district_code=1001 t:county_fip=19001 t:district_name="UNION TWP/ORIENT MACKSBURG SCH" t:tday_id=20001001 t:township_name=UNION t:county_name=ADAIR m:net_w_o_g_e=16865984 m:other=0 m:reimb_ind_m_e_computers=0 m:residential=3066280 m:utilities_w_o_g_e=2216994 m:non_reimb_ind_m_e_computers=0 m:ag_building=877535 m:open_spaces=0 m:industrial=0 m:rail=0 m:gross_w_o_g_e=16886356 m:gas_electric=2382021 m:commercial=49922 m:military_exempt=20372 m:ag_land=10675625

series e:ig9g-pba5 d:2000-01-01T00:00:00.000Z t:co_subdivision_fip=1900193198 t:property_type=R t:school_district_name=ORIENT-MACKSBURG t:tax_district_code=1002 t:county_fip=19001 t:district_name="ORIENT TWP/ORIENT MACKSBURG SCH" t:tday_id=20001002 t:township_name=ORIENT t:county_name=ADAIR m:net_w_o_g_e=19033183 m:other=0 m:reimb_ind_m_e_computers=0 m:residential=3522063 m:utilities_w_o_g_e=2403654 m:non_reimb_ind_m_e_computers=0 m:ag_building=992366 m:open_spaces=0 m:industrial=0 m:rail=0 m:gross_w_o_g_e=19059111 m:gas_electric=3149120 m:commercial=0 m:military_exempt=25928 m:ag_land=12141028

series e:ig9g-pba5 d:2000-01-01T00:00:00.000Z t:co_subdivision_fip=1900193570 t:property_type=R t:school_district_name=ORIENT-MACKSBURG t:tax_district_code=1003 t:county_fip=19001 t:district_name="RICHLAND TWP/ORIENT MACKSBURG SCH/GREENFIELD" t:tday_id=20001003 t:township_name=RICHLAND t:county_name=ADAIR m:net_w_o_g_e=1876372 m:other=0 m:reimb_ind_m_e_computers=0 m:residential=428351 m:utilities_w_o_g_e=142483 m:non_reimb_ind_m_e_computers=0 m:ag_building=333455 m:open_spaces=0 m:industrial=0 m:rail=0 m:gross_w_o_g_e=1880076 m:gas_electric=671426 m:commercial=0 m:military_exempt=3704 m:ag_land=975787
```

## Meta Commands

```ls
metric m:residential p:long l:Residential d:"Taxable value of property classified as residential" t:dataTypeName=money

metric m:ag_land p:integer l:"Ag Land" d:"Taxable value of property classified as agricultural land" t:dataTypeName=money

metric m:ag_building p:integer l:"Ag Building" d:"Taxable value of buildings used for agricultural purposes" t:dataTypeName=money

metric m:commercial p:integer l:Commercial d:"Taxable value of property classified as commercial" t:dataTypeName=money

metric m:industrial p:integer l:Industrial d:"Taxable value of property classified as industrial" t:dataTypeName=money

metric m:reimb_ind_m_e_computers p:integer l:"Reimb Ind M&E/Computers" d:"Taxable value of property classified as machinery and equipment that was exempted and phased out" t:dataTypeName=money

metric m:non_reimb_ind_m_e_computers p:integer l:"Non-Reimb Ind M&E/Computers" d:"Any taxable machinery and equipment valuation with Community College Jobs Training TIF" t:dataTypeName=money

metric m:rail p:integer l:Rail d:"Taxable value of property classified as railroad property" t:dataTypeName=money

metric m:utilities_w_o_g_e p:integer l:"Utilities w/o G&E" d:"Taxable value of all utilities subject to local property tax, excluding gas and electric utilities" t:dataTypeName=money

metric m:other p:integer l:Other d:"Taxable valuations of property subject to taxation that does not fit under another classification, may include mineral rights, certain bridges and toll bridges" t:dataTypeName=money

metric m:gross_w_o_g_e p:long l:"Gross w/o G&E" d:"Sum of taxable property values within tax district, excluding gas & electric" t:dataTypeName=money

metric m:military_exempt p:integer l:"Military Exempt" d:"Amount of taxable property valuations reduced due to military exemptions" t:dataTypeName=money

metric m:net_w_o_g_e p:long l:"Net w/o G&E" d:"Gross less the military exemption" t:dataTypeName=money

metric m:gas_electric p:integer l:"Gas & Electric" d:"Taxable value of gas and electric utilities as certified by Department of Revenue" t:dataTypeName=money

metric m:open_spaces p:integer l:"Open Spaces" d:"Taxable value of property classified as open space" t:dataTypeName=money

entity e:ig9g-pba5 l:"Taxable Property Values By Tax District and Year" t:attribution="Iowa Department of Management, Property Valuation System" t:url=https://data.iowa.gov/api/views/ig9g-pba5

property e:ig9g-pba5 t:meta.view v:id=ig9g-pba5 v:category=Government v:attributionLink="https://www.iowaonline.state.ia.us/dompvs/default.aspx?cmd=SelReport" v:averageRating=0 v:name="Taxable Property Values By Tax District and Year" v:attribution="Iowa Department of Management, Property Valuation System"

property e:ig9g-pba5 t:meta.view.license v:name="Public Domain"

property e:ig9g-pba5 t:meta.view.owner v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:displayName="IDOM, Local Budget & Finance"

property e:ig9g-pba5 t:meta.view.tableauthor v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```

## Top Records

```ls
| tday_id  | assessment_year | tax_district_code | district_name                                | county_fip | county_name | city_fip | city_name | co_subdivision_fip | township_name | school_district_name | property_type | residential | ag_land  | ag_building | commercial | industrial | reimb_ind_m_e_computers | non_reimb_ind_m_e_computers | rail | utilities_w_o_g_e | other | gross_w_o_g_e | military_exempt | net_w_o_g_e | gas_electric | open_spaces | prim_lat_dec | prim_long_dec | 
| ======== | =============== | ================= | ============================================ | ========== | =========== | ======== | ========= | ================== | ============= | ==================== | ============= | =========== | ======== | =========== | ========== | ========== | ======================= | =========================== | ==== | ================= | ===== | ============= | =============== | =========== | ============ | =========== | ============ | ============= | 
| 20001001 | 2000            | 1001              | UNION TWP/ORIENT MACKSBURG SCH               | 19001      | ADAIR       |          |           | 1900194161         | UNION         | ORIENT-MACKSBURG     | R             | 3066280     | 10675625 | 877535      | 49922      | 0          | 0                       | 0                           | 0    | 2216994           | 0     | 16886356      | 20372           | 16865984    | 2382021      | 0           | 41.200508    | -94.2992281   | 
| 20001002 | 2000            | 1002              | ORIENT TWP/ORIENT MACKSBURG SCH              | 19001      | ADAIR       |          |           | 1900193198         | ORIENT        | ORIENT-MACKSBURG     | R             | 3522063     | 12141028 | 992366      | 0          | 0          | 0                       | 0                           | 0    | 2403654           | 0     | 19059111      | 25928           | 19033183    | 3149120      | 0           | 41.2007028   | -94.4137139   | 
| 20001003 | 2000            | 1003              | RICHLAND TWP/ORIENT MACKSBURG SCH/GREENFIELD | 19001      | ADAIR       |          |           | 1900193570         | RICHLAND      | ORIENT-MACKSBURG     | R             | 428351      | 975787   | 333455      | 0          | 0          | 0                       | 0                           | 0    | 142483            | 0     | 1880076       | 3704            | 1876372     | 671426       | 0           | 41.2008879   | -94.5278663   | 
| 20001004 | 2000            | 1004              | LEE TWP/ORIENT MACKSBURG SCH                 | 19001      | ADAIR       |          |           | 1900192397         | LEE           | ORIENT-MACKSBURG     | R             | 229212      | 660244   | 53338       | 0          | 0          | 0                       | 0                           | 0    | 119731            | 0     | 1062525       | 3704            | 1058821     | 8748         | 0           | 41.2859955   | -94.4063302   | 
| 20001005 | 2000            | 1005              | ORIENT CITY/ORIENT MACKSBURG SCH             | 19001      | ADAIR       | 1959565  | ORIENT    |                    |               | ORIENT-MACKSBURG     | U             | 5683239     | 0        | 0           | 652589     | 0          | 1306                    | 0                           | 0    | 37595             | 0     | 6374729       | 61116           | 6313613     | 46740        | 0           | 41.203044    | -94.4146845   | 
| 20001006 | 2000            | 1006              | WASHINGTON TWP/BRIDGEWATER FONTANELLE SCH    | 19001      | ADAIR       |          |           | 1900194443         | WASHINGTON    | NODAWAY VALLEY       | R             | 2047133     | 10793391 | 684998      | 393875     | 0          | 0                       | 0                           | 0    | 225586            | 0     | 14144983      | 22224           | 14122759    | 1112280      | 0           | 41.2010145   | -94.6428532   | 
| 20001007 | 2000            | 1007              | JACKSON TWP/BRIDGEWATER FONTANELLE SCH       | 19001      | ADAIR       |          |           | 1900192088         | JACKSON       | NODAWAY VALLEY       | R             | 2798318     | 10709703 | 952410      | 136853     | 0          | 252                     | 0                           | 0    | 1347790           | 0     | 15945326      | 22224           | 15923102    | 210407       | 0           | 41.2875059   | -94.6427732   | 
| 20001008 | 2000            | 1008              | SUMMERSET TWP/BRIDGEWATER FONTANELLE SCH     | 19001      | ADAIR       |          |           | 1900194032         | SUMMERSET     | NODAWAY VALLEY       | R             | 2316024     | 6397386  | 675551      | 129145     | 0          | 0                       | 0                           | 0    | 858954            | 0     | 10377060      | 22224           | 10354836    | 90524        | 0           | 41.2874884   | -94.5278678   | 
| 20001009 | 2000            | 1009              | PRUSSIA TWP/BRIDGEWATER FONTANELLE SCH       | 19001      | ADAIR       |          |           | 1900193519         | PRUSSIA       | NODAWAY VALLEY       | R             | 1591283     | 5691353  | 434622      | 138542     | 0          | 620                     | 0                           | 0    | 226154            | 0     | 8082574       | 14816           | 8067758     | 360158       | 0           | 41.3741603   | -94.5282085   | 
| 20001010 | 2000            | 1010              | EUREKA TWP/BRIDGEWATER FONTANELLE SCH        | 19001      | ADAIR       |          |           | 1900191248         | EUREKA        | NODAWAY VALLEY       | R             | 888402      | 5485764  | 353108      | 0          | 0          | 0                       | 0                           | 0    | 110232            | 0     | 6837506       | 9260            | 6828246     | 492558       | 0           | 41.3742176   | -94.6429302   | 
```