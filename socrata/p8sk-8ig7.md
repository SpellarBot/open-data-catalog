# Assessed Property Values By Tax District and Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assessed-property-values-by-tax-district-and-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/p8sk-8ig7) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/p8sk-8ig7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/p8sk-8ig7/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | p8sk-8ig7 |
| Name | Assessed Property Values By Tax District and Year |
| Attribution | Iowa Department of Management, Property Valuation System |
| Category | Communities & People |
| Tags | property values, tax district, residential, agricultural, commercial, industrial, railroads, utilities |
| Created | 2014-11-12T19:24:43Z |
| Publication Date | 2014-11-20T19:59:10Z |

## Description

This dataset contains 100% assessed property values for classes of real property. Real property is mostly land, buildings, structures, and other improvements that are constructed on or in the land, attached to the land, or placed upon a foundation. Typical improvements include a building, house or mobile home, fences, and paving. Classes of real property include the following: Residential, Agricultural Land, Agricultural Buildings, Commercial, Industrial, Utilities, and Railroads.

The assessed property values help determine the net taxable valuations for property tax levies (e.g. 2012 assessment property values help determine the net taxable valuations for FY 2014 property tax levies).

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
series e:p8sk-8ig7 d:2011-01-01T00:00:00.000Z t:co_subdivision_fip=1900194161 t:property_type=R t:school_district_name=ORIENT-MACKSBURG t:tax_district_code=01001 t:county_fip=19001 t:district_name="UNION TWP/ORIENT MACKSBURG SCH" t:tday_id=201101001 t:township_name=UNION t:county_name=ADAIR m:net_w_o_g_e=34962603 m:other=0 m:reimb_ind_m_e_computers=0 m:residential=5314109 m:utilities_w_o_g_e=2878009 m:non_reimb_ind_m_e_computers=0 m:ag_building=294586 m:open_spaces=0 m:industrial=0 m:rail=0 m:gross_w_o_g_e=34977419 m:gas_electric=4521138 m:commercial=58629 m:military_exempt=14816 m:ag_land=26432086

series e:p8sk-8ig7 d:2011-01-01T00:00:00.000Z t:co_subdivision_fip=1900193198 t:property_type=R t:school_district_name=ORIENT-MACKSBURG t:tax_district_code=01002 t:county_fip=19001 t:district_name="ORIENT TWP/ORIENT MACKSBURG SCH" t:tday_id=201101002 t:township_name=ORIENT t:county_name=ADAIR m:net_w_o_g_e=39169565 m:other=0 m:reimb_ind_m_e_computers=0 m:residential=5734665 m:utilities_w_o_g_e=2984260 m:non_reimb_ind_m_e_computers=0 m:ag_building=295373 m:open_spaces=0 m:industrial=0 m:rail=0 m:gross_w_o_g_e=39191789 m:gas_electric=5650387 m:commercial=129671 m:military_exempt=22224 m:ag_land=30047820

series e:p8sk-8ig7 d:2011-01-01T00:00:00.000Z t:co_subdivision_fip=1900193570 t:property_type=R t:school_district_name=ORIENT-MACKSBURG t:tax_district_code=01003 t:county_fip=19001 t:district_name="RICHLAND TWP/ORIENT MACKSBURG SCH/GREENFIELD" t:tday_id=201101003 t:township_name=RICHLAND t:county_name=ADAIR m:net_w_o_g_e=3466570 m:other=0 m:reimb_ind_m_e_computers=0 m:residential=811808 m:utilities_w_o_g_e=181553 m:non_reimb_ind_m_e_computers=0 m:ag_building=55589 m:open_spaces=0 m:industrial=0 m:rail=0 m:gross_w_o_g_e=3470274 m:gas_electric=1314694 m:commercial=0 m:military_exempt=3704 m:ag_land=2421324
```

## Meta Commands

```ls
metric m:residential p:long l:Residential d:"Assessed value of property classified as residential" t:dataTypeName=money

metric m:ag_land p:integer l:"Ag Land" d:"Assessed value of property classified as agricultural land" t:dataTypeName=money

metric m:ag_building p:integer l:"Ag Building" d:"Assessed value of buildings used for agricultural purposes" t:dataTypeName=money

metric m:commercial p:integer l:Commercial d:"Assessed value of property classified as commercial" t:dataTypeName=money

metric m:industrial p:integer l:Industrial d:"Assessed value of property classified as industrial" t:dataTypeName=money

metric m:reimb_ind_m_e_computers p:integer l:"Reimb Ind M&E/Computers" d:"Property classified as machinery and equipment that was exempted and phased out" t:dataTypeName=money

metric m:non_reimb_ind_m_e_computers p:integer l:"Non-Reimb Ind M&E/Computers" d:"Any taxable machinery and equipment valuation with Community College Jobs Training TIF" t:dataTypeName=money

metric m:rail p:integer l:Rail d:"Assessed value of property classified as railroad property" t:dataTypeName=money

metric m:utilities_w_o_g_e p:integer l:"Utilities w/o G&E" d:"Assessed value of all utilities subject to local property tax, excluding gas and electric utilities" t:dataTypeName=money

metric m:other p:integer l:Other d:"Property subject to taxtation that does not fit under another classification, may include mineral rights, certain bridges and toll bridges" t:dataTypeName=money

metric m:gross_w_o_g_e p:long l:"Gross w/o G&E" d:"Sum of assessed property with tax district, excluding gas & electric" t:dataTypeName=money

metric m:military_exempt p:integer l:"Military Exempt" d:"Amount of assessed property valuations reduced due to military exemptions" t:dataTypeName=money

metric m:net_w_o_g_e p:long l:"Net w/o G&E" d:"Gross less the military exemption" t:dataTypeName=money

metric m:gas_electric p:integer l:"Gas & Electric" d:"Assessed value of gas and electric utilities as certified by Department of Revenue" t:dataTypeName=money

metric m:open_spaces p:integer l:"Open Spaces" d:"Assessed value of property classified as open space" t:dataTypeName=money

entity e:p8sk-8ig7 l:"Assessed Property Values By Tax District and Year" t:attribution="Iowa Department of Management, Property Valuation System" t:url=https://data.iowa.gov/api/views/p8sk-8ig7

property e:p8sk-8ig7 t:meta.view v:id=p8sk-8ig7 v:category="Communities & People" v:attributionLink="https://www.iowaonline.state.ia.us/dompvs/default.aspx?cmd=SelReport" v:averageRating=0 v:name="Assessed Property Values By Tax District and Year" v:attribution="Iowa Department of Management, Property Valuation System"

property e:p8sk-8ig7 t:meta.view.license v:name="Public Domain"

property e:p8sk-8ig7 t:meta.view.owner v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:displayName="IDOM, Local Budget & Finance"

property e:p8sk-8ig7 t:meta.view.tableauthor v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```

## Top Records

```ls
| tday_id   | assessment_year | tax_district_code | district_name                                | county_fip | county_name | city_fip | city_name | co_subdivision_fip | township_name | school_district_name | property_type | residential | ag_land  | ag_building | commercial | industrial | reimb_ind_m_e_computers | non_reimb_ind_m_e_computers | rail | utilities_w_o_g_e | other | gross_w_o_g_e | military_exempt | net_w_o_g_e | gas_electric | open_spaces | prim_lat_dec | prim_long_dec | 
| ========= | =============== | ================= | ============================================ | ========== | =========== | ======== | ========= | ================== | ============= | ==================== | ============= | =========== | ======== | =========== | ========== | ========== | ======================= | =========================== | ==== | ================= | ===== | ============= | =============== | =========== | ============ | =========== | ============ | ============= | 
| 201101001 | 2011            | 01001             | UNION TWP/ORIENT MACKSBURG SCH               | 19001      | ADAIR       |          |           | 1900194161         | UNION         | ORIENT-MACKSBURG     | R             | 5314109     | 26432086 | 294586      | 58629      | 0          | 0                       | 0                           | 0    | 2878009           | 0     | 34977419      | 14816           | 34962603    | 4521138      | 0           | 41.200508    | -94.2992281   | 
| 201101002 | 2011            | 01002             | ORIENT TWP/ORIENT MACKSBURG SCH              | 19001      | ADAIR       |          |           | 1900193198         | ORIENT        | ORIENT-MACKSBURG     | R             | 5734665     | 30047820 | 295373      | 129671     | 0          | 0                       | 0                           | 0    | 2984260           | 0     | 39191789      | 22224           | 39169565    | 5650387      | 0           | 41.2007028   | -94.4137139   | 
| 201101003 | 2011            | 01003             | RICHLAND TWP/ORIENT MACKSBURG SCH/GREENFIELD | 19001      | ADAIR       |          |           | 1900193570         | RICHLAND      | ORIENT-MACKSBURG     | R             | 811808      | 2421324  | 55589       | 0          | 0          | 0                       | 0                           | 0    | 181553            | 0     | 3470274       | 3704            | 3466570     | 1314694      | 0           | 41.2008879   | -94.5278663   | 
| 201101004 | 2011            | 01004             | LEE TWP/ORIENT MACKSBURG SCH                 | 19001      | ADAIR       |          |           | 1900192397         | LEE           | ORIENT-MACKSBURG     | R             | 318152      | 1638477  | 15512       | 0          | 0          | 0                       | 0                           | 0    | 10844             | 0     | 1982985       | 1852            | 1981133     | 19007        | 0           | 41.2859955   | -94.4063302   | 
| 201101005 | 2011            | 01005             | ORIENT CITY/ORIENT MACKSBURG SCH             | 19001      | ADAIR       | 1959565  | ORIENT    |                    |               | ORIENT-MACKSBURG     | U             | 144334      | 0        | 0           | 0          | 0          | 0                       | 0                           | 0    | 41242             | 0     | 185576        | 1852            | 183724      | 79075        | 0           | 41.203044    | -94.4146845   | 
| 201101006 | 2011            | 01006             | WASHINGTON TWP/BRIDGEWATER FONTANELLE SCH    | 19001      | ADAIR       |          |           | 1900194443         | WASHINGTON    | NODAWAY VALLEY       | R             | 3322881     | 26642046 | 302940      | 294118     | 0          | 0                       | 0                           | 0    | 260862            | 0     | 30822847      | 24076           | 30798771    | 2080685      | 0           | 41.2010145   | -94.6428532   | 
| 201101007 | 2011            | 01007             | JACKSON TWP/BRIDGEWATER FONTANELLE SCH       | 19001      | ADAIR       |          |           | 1900192088         | JACKSON       | NODAWAY VALLEY       | R             | 4611541     | 26563113 | 258519      | 76592      | 55372      | 0                       | 0                           | 0    | 1024957           | 0     | 32590094      | 14816           | 32575278    | 423089       | 0           | 41.2875059   | -94.6427732   | 
| 201101008 | 2011            | 01008             | SUMMERSET TWP/BRIDGEWATER FONTANELLE SCH     | 19001      | ADAIR       |          |           | 1900194032         | SUMMERSET     | NODAWAY VALLEY       | R             | 4373891     | 15848285 | 212716      | 263266     | 0          | 0                       | 0                           | 0    | 681777            | 0     | 21379935      | 16668           | 21363267    | 169096       | 0           | 41.2874884   | -94.5278678   | 
| 201101009 | 2011            | 01009             | PRUSSIA TWP/BRIDGEWATER FONTANELLE SCH       | 19001      | ADAIR       |          |           | 1900193519         | PRUSSIA       | NODAWAY VALLEY       | R             | 2639261     | 14117686 | 167150      | 191504     | 0          | 0                       | 0                           | 0    | 190240            | 0     | 17305841      | 11112           | 17294729    | 697760       | 0           | 41.3741603   | -94.5282085   | 
| 201101010 | 2011            | 01010             | EUREKA TWP/BRIDGEWATER FONTANELLE SCH        | 19001      | ADAIR       |          |           | 1900191248         | EUREKA        | NODAWAY VALLEY       | R             | 1147028     | 13612460 | 343102      | 0          | 0          | 0                       | 0                           | 0    | 124727            | 0     | 15227317      | 5556            | 15221761    | 942748       | 0           | 41.3742176   | -94.6429302   | 
```