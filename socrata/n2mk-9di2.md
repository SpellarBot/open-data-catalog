# Capacity For All Parcels 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capacity-for-all-parcel-2015) |
| Metadata | [Link](https://data.seattle.gov/api/views/n2mk-9di2) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/n2mk-9di2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/n2mk-9di2/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | n2mk-9di2 |
| Name | Capacity For All Parcels 2015 |
| Category | Land Base |
| Created | 2015-06-16T21:12:07Z |
| Publication Date | 2015-07-01T22:23:08Z |

## Description

Read the Development Capacity Report for the Seattle 2035 Comprehensive Plan here:
http://www.seattle.gov/dpd/cs/groups/pan/@pan/documents/web_informational/p2182731.pdf

Learn more about zone development capacity here: http://www.seattle.gov/DPD/cityplanning/populationdemographics/zoneddevcapacity/default.htm

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | pin                  | PIN                  | text      | text        |
| Yes      | series tag     | prop_name            | PROP_NAME            | text      | text        |
| Yes      | numeric metric | land_sqft            | LAND_SQFT            | number    | number      |
| Yes      | numeric metric | land_no_shore_sqft   | LAND_NO_SHORE_SQFT   | number    | number      |
| Yes      | numeric metric | parcel_dev_sqft      | PARCEL_DEV_SQFT      | number    | number      |
| Yes      | series tag     | land_use_code        | LAND_USE_CODE        | text      | number      |
| Yes      | series tag     | land_use_desc        | LAND_USE_DESC        | text      | text        |
| Yes      | series tag     | land_use_desc_10     | LAND_USE_DESC_10     | text      | text        |
| Yes      | series tag     | zoning               | ZONING               | text      | text        |
| Yes      | series tag     | zonelut              | ZONELUT              | text      | text        |
| Yes      | series tag     | mio_base_zone        | MIO_BASE_ZONE        | text      | text        |
| Yes      | series tag     | class                | CLASS                | text      | text        |
| Yes      | series tag     | zone_geo             | ZONE_GEO             | text      | text        |
| Yes      | numeric metric | villnumb             | VILLNUMB             | number    | number      |
| Yes      | numeric metric | trbl10               | TRBL10               | number    | number      |
| Yes      | series tag     | rescat               | RESCAT               | text      | text        |
| Yes      | series tag     | empcat               | EMPCAT               | text      | text        |
| Yes      | series tag     | pub_own_type         | PUB_OWN_TYPE         | text      | text        |
| Yes      | series tag     | tax_status           | TAX_STATUS           | text      | text        |
| Yes      | numeric metric | sf_units             | SF_UNITS             | number    | number      |
| Yes      | numeric metric | mf_units             | MF_UNITS             | number    | number      |
| Yes      | numeric metric | exist_units          | EXIST_UNITS          | number    | number      |
| Yes      | numeric metric | yr_built             | YR_BUILT             | number    | number      |
| Yes      | numeric metric | maxrdens             | MAXRDENS             | number    | number      |
| Yes      | numeric metric | obs_rdens_units      | OBS_RDENS_UNITS      | number    | number      |
| Yes      | numeric metric | res_far              | RES_FAR              | number    | number      |
| Yes      | numeric metric | obs_far_units        | OBS_FAR_UNITS        | number    | number      |
| Yes      | numeric metric | res_max_far          | RES_MAX_FAR          | number    | number      |
| Yes      | numeric metric | max_far_units        | MAX_FAR_UNITS        | number    | number      |
| Yes      | numeric metric | max_res_fl_area      | MAX_RES_FL_AREA      | number    | number      |
| Yes      | numeric metric | bldg_grss_sqft       | BLDG_GRSS_SQFT       | number    | number      |
| Yes      | numeric metric | bldg_res_grssqf      | BLDG_RES_GRSSQF      | number    | number      |
| Yes      | numeric metric | bldg_com_grssqf      | BLDG_COM_GRSSQF      | number    | number      |
| Yes      | numeric metric | comm_far             | COMM_FAR             | number    | number      |
| Yes      | numeric metric | obs_comm_fl_area     | OBS_COMM_FL_AREA     | number    | number      |
| Yes      | numeric metric | comm_max_far         | COMM_MAX_FAR         | number    | number      |
| Yes      | numeric metric | max_comm_fl_area     | MAX_COMM_FL_AREA     | number    | number      |
| Yes      | numeric metric | redev_fl_area        | REDEV_FL_AREA        | number    | number      |
| Yes      | numeric metric | bldg_av              | BLDG_AV              | number    | number      |
| Yes      | numeric metric | land_av              | LAND_AV              | number    | number      |
| Yes      | series tag     | landmark             | LANDMARK             | text      | text        |
| Yes      | series tag     | stat_type            | STAT_TYPE            | text      | text        |
| Yes      | numeric metric | ratio                | RATIO                | number    | number      |
| Yes      | numeric metric | ilr                  | ILR                  | number    | number      |
| No       |                | dr                   | DR                   | number    | number      |
| Yes      | series tag     | resstat              | RESSTAT              | text      | text        |
| Yes      | series tag     | comstat              | COMSTAT              | text      | text        |
| Yes      | numeric metric | splitres             | SPLITRES             | number    | number      |
| Yes      | numeric metric | splitcom             | SPLITCOM             | number    | number      |
| Yes      | numeric metric | empl                 | EMPL                 | number    | number      |
| Yes      | numeric metric | adjrcap_maxrdens_sfl | ADJRCAP_MAXRDENS_SFL | number    | number      |
| Yes      | numeric metric | adjrcap_obs_far      | ADJRCAP_OBS_FAR      | number    | number      |
| Yes      | numeric metric | adjrcap_max_far      | ADJRCAP_MAX_FAR      | number    | number      |
| Yes      | numeric metric | adjrcap_fl_area_max  | ADJRCAP_FL_AREA_MAX  | number    | number      |
| Yes      | numeric metric | adjccap              | ADJCCAP              | number    | number      |
| Yes      | numeric metric | adjccap_max          | ADJCCAP_MAX          | number    | number      |
| Yes      | numeric metric | exist_empl           | EXIST_EMPL           | number    | number      |
| Yes      | numeric metric | empcap               | EMPCAP               | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = dr
```

## Data Commands

```ls
series e:n2mk-9di2 d:2015-01-01T00:00:00.000Z t:stat_type=DR:UNITS t:empcat=n/a t:land_use_desc_10="Single Family" t:tax_status=T t:zonelut="SF 5000" t:class=SF t:rescat=SF t:pub_own_type=PRIVATE t:land_use_desc="Single Family(Res Use/Zone)" t:pin=269000641 t:resstat=DEVELOPED t:comstat=UNAVAIL t:land_use_code=2 t:zone_geo=NONE t:zoning="SF 5000" m:max_res_fl_area=5898 m:adjrcap_maxrdens_sfl=0 m:villnumb=0 m:redev_fl_area=5898 m:splitres=1 m:comm_max_far=0 m:trbl10=5802.3013 m:land_av=334000 m:bldg_grss_sqft=3030 m:res_far=1 m:mf_units=0 m:comm_far=0 m:sf_units=1 m:bldg_res_grssqf=3030 m:res_max_far=1 m:exist_units=1 m:empl=0 m:empcap=0 m:adjrcap_max_far=0 m:parcel_dev_sqft=5898 m:ilr=1.5 m:max_far_units=1 m:obs_rdens_units=1 m:adjrcap_fl_area_max=2868 m:obs_far_units=1 m:adjccap=0 m:maxrdens=5000 m:adjccap_max=0 m:exist_empl=0 m:yr_built=1946 m:land_no_shore_sqft=5898 m:splitcom=0 m:land_sqft=5898 m:bldg_av=501000 m:adjrcap_obs_far=0 m:ratio=1 m:max_comm_fl_area=0 m:obs_comm_fl_area=0 m:bldg_com_grssqf=0

series e:n2mk-9di2 d:2015-01-01T00:00:00.000Z t:stat_type=DR:UNITS t:empcat=n/a t:land_use_desc_10="Single Family" t:tax_status=T t:zonelut="SF 5000" t:class=SF t:rescat=SF t:pub_own_type=PRIVATE t:land_use_desc="Single Family(Res Use/Zone)" t:pin=269000634 t:resstat=DEVELOPED t:comstat=UNAVAIL t:land_use_code=2 t:zone_geo=NONE t:zoning="SF 5000" m:max_res_fl_area=5898 m:adjrcap_maxrdens_sfl=0 m:villnumb=0 m:redev_fl_area=5898 m:splitres=1 m:comm_max_far=0 m:trbl10=5802.3013 m:land_av=334000 m:bldg_grss_sqft=1920 m:res_far=1 m:mf_units=0 m:comm_far=0 m:sf_units=1 m:bldg_res_grssqf=1920 m:res_max_far=1 m:exist_units=1 m:empl=0 m:empcap=0 m:adjrcap_max_far=0 m:parcel_dev_sqft=5898 m:ilr=0.299 m:max_far_units=1 m:obs_rdens_units=1 m:adjrcap_fl_area_max=3978 m:obs_far_units=1 m:adjccap=0 m:maxrdens=5000 m:adjccap_max=0 m:exist_empl=0 m:yr_built=1946 m:land_no_shore_sqft=5898 m:splitcom=0 m:land_sqft=5898 m:bldg_av=100000 m:adjrcap_obs_far=0 m:ratio=1 m:max_comm_fl_area=0 m:obs_comm_fl_area=0 m:bldg_com_grssqf=0

series e:n2mk-9di2 d:2015-01-01T00:00:00.000Z t:stat_type=DR:UNITS t:empcat=n/a t:land_use_desc_10="Single Family" t:tax_status=T t:zonelut="SF 5000" t:class=SF t:rescat=SF t:pub_own_type=PRIVATE t:land_use_desc="Single Family(Res Use/Zone)" t:pin=269000629 t:resstat=DEVELOPED t:comstat=UNAVAIL t:land_use_code=2 t:zone_geo=NONE t:zoning="SF 5000" m:max_res_fl_area=6255 m:adjrcap_maxrdens_sfl=0 m:villnumb=0 m:redev_fl_area=6255 m:splitres=1 m:comm_max_far=0 m:trbl10=5802.3013 m:land_av=353000 m:bldg_grss_sqft=2000 m:res_far=1 m:mf_units=0 m:comm_far=0 m:sf_units=1 m:bldg_res_grssqf=2000 m:res_max_far=1 m:exist_units=1 m:empl=0 m:empcap=0 m:adjrcap_max_far=0 m:parcel_dev_sqft=6255 m:ilr=0.309 m:max_far_units=1 m:obs_rdens_units=1 m:adjrcap_fl_area_max=4255 m:obs_far_units=1 m:adjccap=0 m:maxrdens=5000 m:adjccap_max=0 m:exist_empl=0 m:yr_built=1946 m:land_no_shore_sqft=6255 m:splitcom=0 m:land_sqft=6255 m:bldg_av=109000 m:adjrcap_obs_far=0 m:ratio=1 m:max_comm_fl_area=0 m:obs_comm_fl_area=0 m:bldg_com_grssqf=0
```

## Meta Commands

```ls
metric m:land_sqft p:integer l:LAND_SQFT t:dataTypeName=number

metric m:land_no_shore_sqft p:integer l:LAND_NO_SHORE_SQFT t:dataTypeName=number

metric m:parcel_dev_sqft p:integer l:PARCEL_DEV_SQFT t:dataTypeName=number

metric m:villnumb p:double l:VILLNUMB t:dataTypeName=number

metric m:trbl10 p:double l:TRBL10 t:dataTypeName=number

metric m:sf_units p:integer l:SF_UNITS t:dataTypeName=number

metric m:mf_units p:integer l:MF_UNITS t:dataTypeName=number

metric m:exist_units p:integer l:EXIST_UNITS t:dataTypeName=number

metric m:yr_built p:integer l:YR_BUILT t:dataTypeName=number

metric m:maxrdens p:integer l:MAXRDENS t:dataTypeName=number

metric m:obs_rdens_units p:integer l:OBS_RDENS_UNITS t:dataTypeName=number

metric m:res_far p:float l:RES_FAR t:dataTypeName=number

metric m:obs_far_units p:integer l:OBS_FAR_UNITS t:dataTypeName=number

metric m:res_max_far p:float l:RES_MAX_FAR t:dataTypeName=number

metric m:max_far_units p:integer l:MAX_FAR_UNITS t:dataTypeName=number

metric m:max_res_fl_area p:integer l:MAX_RES_FL_AREA t:dataTypeName=number

metric m:bldg_grss_sqft p:integer l:BLDG_GRSS_SQFT t:dataTypeName=number

metric m:bldg_res_grssqf p:integer l:BLDG_RES_GRSSQF t:dataTypeName=number

metric m:bldg_com_grssqf p:integer l:BLDG_COM_GRSSQF t:dataTypeName=number

metric m:comm_far p:double l:COMM_FAR t:dataTypeName=number

metric m:obs_comm_fl_area p:integer l:OBS_COMM_FL_AREA t:dataTypeName=number

metric m:comm_max_far p:double l:COMM_MAX_FAR t:dataTypeName=number

metric m:max_comm_fl_area p:integer l:MAX_COMM_FL_AREA t:dataTypeName=number

metric m:redev_fl_area p:integer l:REDEV_FL_AREA t:dataTypeName=number

metric m:bldg_av p:integer l:BLDG_AV t:dataTypeName=number

metric m:land_av p:integer l:LAND_AV t:dataTypeName=number

metric m:ratio p:double l:RATIO t:dataTypeName=number

metric m:ilr p:float l:ILR t:dataTypeName=number

metric m:splitres p:double l:SPLITRES t:dataTypeName=number

metric m:splitcom p:double l:SPLITCOM t:dataTypeName=number

metric m:empl p:integer l:EMPL t:dataTypeName=number

metric m:adjrcap_maxrdens_sfl p:integer l:ADJRCAP_MAXRDENS_SFL t:dataTypeName=number

metric m:adjrcap_obs_far p:integer l:ADJRCAP_OBS_FAR t:dataTypeName=number

metric m:adjrcap_max_far p:integer l:ADJRCAP_MAX_FAR t:dataTypeName=number

metric m:adjrcap_fl_area_max p:integer l:ADJRCAP_FL_AREA_MAX t:dataTypeName=number

metric m:adjccap p:integer l:ADJCCAP t:dataTypeName=number

metric m:adjccap_max p:integer l:ADJCCAP_MAX t:dataTypeName=number

metric m:exist_empl p:integer l:EXIST_EMPL t:dataTypeName=number

metric m:empcap p:integer l:EMPCAP t:dataTypeName=number

entity e:n2mk-9di2 l:"Capacity For All Parcels 2015" t:url=https://data.seattle.gov/api/views/n2mk-9di2

property e:n2mk-9di2 t:meta.view v:id=n2mk-9di2 v:category="Land Base" v:averageRating=0 v:name="Capacity For All Parcels 2015"

property e:n2mk-9di2 t:meta.view.license v:name="Public Domain"

property e:n2mk-9di2 t:meta.view.owner v:id=5wys-t5s3 v:screenName="Seattle DPD" v:displayName="Seattle DPD"

property e:n2mk-9di2 t:meta.view.tableauthor v:id=5wys-t5s3 v:screenName="Seattle DPD" v:roleName=publisher v:displayName="Seattle DPD"
```

## Top Records

```ls
| pin       | prop_name | land_sqft | land_no_shore_sqft | parcel_dev_sqft | land_use_code | land_use_desc               | land_use_desc_10 | zoning  | zonelut | mio_base_zone | class | zone_geo | villnumb | trbl10    | rescat | empcat | pub_own_type | tax_status | sf_units | mf_units | exist_units | yr_built | maxrdens | obs_rdens_units | res_far | obs_far_units | res_max_far | max_far_units | max_res_fl_area | bldg_grss_sqft | bldg_res_grssqf | bldg_com_grssqf | comm_far | obs_comm_fl_area | comm_max_far | max_comm_fl_area | redev_fl_area | bldg_av | land_av | landmark | stat_type | ratio | ilr                  | dr | resstat   | comstat | splitres | splitcom | empl | adjrcap_maxrdens_sfl | adjrcap_obs_far | adjrcap_max_far | adjrcap_fl_area_max | adjccap | adjccap_max | exist_empl | empcap | 
| ========= | ========= | ========= | ================== | =============== | ============= | =========================== | ================ | ======= | ======= | ============= | ===== | ======== | ======== | ========= | ====== | ====== | ============ | ========== | ======== | ======== | =========== | ======== | ======== | =============== | ======= | ============= | =========== | ============= | =============== | ============== | =============== | =============== | ======== | ================ | ============ | ================ | ============= | ======= | ======= | ======== | ========= | ===== | ==================== | == | ========= | ======= | ======== | ======== | ==== | ==================== | =============== | =============== | =================== | ======= | =========== | ========== | ====== | 
| 269000641 |           | 5898      | 5898               | 5898            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1946     | 5000     | 1               | 1       | 1             | 1           | 1             | 5898            | 3030           | 3030            | 0               | 0        | 0                | 0            | 0                | 5898          | 501000  | 334000  |          | DR:UNITS  | 1     | 1.5                  | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 2868                | 0       | 0           | 0          | 0      | 
| 269000634 |           | 5898      | 5898               | 5898            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1946     | 5000     | 1               | 1       | 1             | 1           | 1             | 5898            | 1920           | 1920            | 0               | 0        | 0                | 0            | 0                | 5898          | 100000  | 334000  |          | DR:UNITS  | 1     | 0.29899999999999999  | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 3978                | 0       | 0           | 0          | 0      | 
| 269000629 |           | 6255      | 6255               | 6255            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1946     | 5000     | 1               | 1       | 1             | 1           | 1             | 6255            | 2000           | 2000            | 0               | 0        | 0                | 0            | 0                | 6255          | 109000  | 353000  |          | DR:UNITS  | 1     | 0.309                | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 4255                | 0       | 0           | 0          | 0      | 
| 269000623 |           | 5899      | 5899               | 5899            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1947     | 5000     | 1               | 1       | 1             | 1           | 1             | 5899            | 2150           | 2150            | 0               | 0        | 0                | 0            | 0                | 5899          | 171000  | 390000  |          | DR:UNITS  | 1     | 0.438                | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 3749                | 0       | 0           | 0          | 0      | 
| 269000619 |           | 5902      | 5902               | 5902            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1947     | 5000     | 1               | 1       | 1             | 1           | 1             | 5902            | 2030           | 2030            | 0               | 0        | 0                | 0            | 0                | 5902          | 107000  | 423000  |          | DR:UNITS  | 1     | 0.253                | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 3872                | 0       | 0           | 0          | 0      | 
| 269000615 |           | 6595      | 6595               | 6595            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1947     | 5000     | 1               | 1       | 1             | 1           | 1             | 6595            | 2440           | 2440            | 0               | 0        | 0                | 0            | 0                | 6595          | 191000  | 473000  |          | DR:UNITS  | 1     | 0.40400000000000003  | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 4155                | 0       | 0           | 0          | 0      | 
| 269000680 |           | 7674      | 7674               | 7674            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3014 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 2006     | 5000     | 1               | 1       | 1             | 1           | 1             | 7674            | 4210           | 4210            | 0               | 0        | 0                | 0            | 0                | 7674          | 872000  | 548000  |          | DR:UNITS  | 1     | 1.591                | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 3464                | 0       | 0           | 0          | 0      | 
| 269000611 |           | 6015      | 6015               | 6015            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1946     | 5000     | 1               | 1       | 1             | 1           | 1             | 6015            | 2080           | 2080            | 0               | 0        | 0                | 0            | 0                | 6015          | 23000   | 472000  |          | DR:UNITS  | 1     | 0.049000000000000002 | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 3935                | 0       | 0           | 0          | 0      | 
| 269000685 |           | 7675      | 7675               | 7675            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3014 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1949     | 5000     | 1               | 1       | 1             | 1           | 1             | 7675            | 2770           | 2770            | 0               | 0        | 0                | 0            | 0                | 7675          | 297000  | 616000  |          | DR:UNITS  | 1     | 0.48199999999999998  | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 4905                | 0       | 0           | 0          | 0      | 
| 269000598 |           | 5425      | 5425               | 5425            | 2             | Single Family(Res Use/Zone) | Single Family    | SF 5000 | SF 5000 |               | SF    | NONE     | 0        | 5802.3013 | SF     | n/a    | PRIVATE      | T          | 1        | 0        | 1           | 1947     | 5000     | 1               | 1       | 1             | 1           | 1             | 5425            | 1960           | 1960            | 0               | 0        | 0                | 0            | 0                | 5425          | 210000  | 446000  |          | DR:UNITS  | 1     | 0.47099999999999997  | 1  | DEVELOPED | UNAVAIL | 1        | 0        | 0    | 0                    | 0               | 0               | 3465                | 0       | 0           | 0          | 0      | 
```