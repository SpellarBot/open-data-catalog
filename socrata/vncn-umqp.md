# City of Seattle Bicycle Racks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-bicycle-racks-a12fa) |
| Metadata | [Link](https://data.seattle.gov/api/views/vncn-umqp) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vncn-umqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vncn-umqp/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vncn-umqp |
| Name | City of Seattle Bicycle Racks |
| Attribution | City of Seattle, Department of Transportation, Traffic Management, Bicycle Program |
| Category | Transportation |
| Tags | city of seattle, seattle, government, sdot, transportation, bike rack, bicycle, bicycle racks |
| Created | 2010-09-24T20:17:39Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Bicycle racks owned and maintained by SDOT. Location of bicycle racks owned and maintained by SDOT in the GIS for cartographic, analysis, and tracking purposes.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | numeric metric | compkey    | COMPKEY    | number        | number        |
| Yes      | series tag     | comptype   | COMPTYPE   | text          | number        |
| Yes      | numeric metric | segkey     | SEGKEY     | number        | number        |
| Yes      | numeric metric | distance   | DISTANCE   | number        | number        |
| Yes      | numeric metric | width      | WIDTH      | number        | number        |
| Yes      | series tag     | unitid     | UNITID     | text          | text          |
| Yes      | series tag     | unittype   | UNITTYPE   | text          | text          |
| Yes      | series tag     | unitdesc   | UNITDESC   | text          | text          |
| Yes      | series tag     | bike_facil | BIKE_FACIL | text          | text          |
| Yes      | numeric metric | rack_capac | RACK_CAPAC | number        | number        |
| Yes      | series tag     | delineator | DELINEATOR | checkbox      | checkbox      |
| Yes      | series tag     | finish_typ | FINISH_TYP | text          | text          |
| Yes      | series tag     | surface_ty | SURFACE_TY | text          | text          |
| No       |                | install_da | INSTALL_DA | calendar_date | calendar_date |
| Yes      | series tag     | mount_type | MOUNT_TYPE | text          | text          |
| Yes      | series tag     | color      | COLOR      | text          | text          |
| Yes      | series tag     | manufactur | MANUFACTUR | text          | text          |
| Yes      | series tag     | model_type | MODEL_TYPE | text          | text          |
| Yes      | series tag     | condition  | CONDITION  | text          | text          |
| Yes      | series tag     | asset_cond | ASSET_COND | text          | text          |
| Yes      | time           | condition_ | CONDITION_ | calendar_date | calendar_date |
| No       |                | latitude   | LATITUDE   | number        | number        |
| No       |                | longitude  | LONGITUDE  | number        | number        |
```

## Time Field

```ls
Value = condition_
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = install_da,latitude,longitude
```

## Data Commands

```ls
series e:vncn-umqp d:2010-09-24T13:17:44.000Z t:finish_typ=GALV t:condition=GOOD t:delineator=false t:manufactur=BKR-CRMTL t:comptype=16 t:asset_cond=GOOD t:unitdesc="STEWART ST 0010 BLOCK SE SIDE (  78) 78 FT NE/O 1ST AVE" t:unitid=BKR-1291 t:color=NONE t:bike_facil=SGL t:surface_ty=PCC t:model_type=BKR-RLRCK t:objectid=517753 t:unittype=BKR t:mount_type=SUFMT m:segkey=12897 m:distance=99 m:width=-27 m:rack_capac=2 m:compkey=517753

series e:vncn-umqp d:2009-09-25T00:00:00.000Z t:finish_typ=GALV t:unitdesc="E LAKE WASHINGTON BLVD 0220 BLOCK N SIDE (  35) 35 FT E/O MONTLAKE BLVD E" t:unitid=BKR-2784 t:color=GRN t:delineator=false t:manufactur=OTHER t:surface_ty=PCC t:bike_facil=SGL t:comptype=16 t:model_type=BKR-NCONF t:objectid=517876 t:unittype=BKR t:mount_type=SUFMT m:segkey=14276 m:distance=65 m:width=34 m:rack_capac=1 m:compkey=517876

series e:vncn-umqp d:2009-07-15T00:00:00.000Z t:finish_typ=GALV t:condition=GOOD t:delineator=false t:manufactur=BKR-CRMTL t:comptype=16 t:asset_cond=GOOD t:unitdesc="7TH AVE 0220 BLOCK SW SIDE ( 341) 44 FT SE/O BELL ST" t:unitid=BKR-1889 t:color=NONE t:bike_facil=SGL t:surface_ty=PCC t:model_type=BKR-RLRCK t:objectid=518838 t:unittype=BKR t:mount_type=SUFMT m:segkey=8165 m:distance=363 m:width=44 m:rack_capac=2 m:compkey=518838
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE t:dataTypeName=number

metric m:width p:integer l:WIDTH t:dataTypeName=number

metric m:rack_capac p:integer l:RACK_CAPAC t:dataTypeName=number

entity e:vncn-umqp l:"City of Seattle Bicycle Racks" t:attribution="City of Seattle, Department of Transportation, Traffic Management, Bicycle Program" t:url=https://data.seattle.gov/api/views/vncn-umqp

property e:vncn-umqp t:meta.view v:id=vncn-umqp v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/bikeprogram.htm v:averageRating=0 v:name="City of Seattle Bicycle Racks" v:attribution="City of Seattle, Department of Transportation, Traffic Management, Bicycle Program"

property e:vncn-umqp t:meta.view.license v:name="Public Domain"

property e:vncn-umqp t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vncn-umqp t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | compkey | comptype | segkey | distance | width | unitid   | unittype | unitdesc                                                                 | bike_facil | rack_capac | delineator | finish_typ | surface_ty | install_da          | mount_type | color | manufactur | model_type | condition | asset_cond | condition_          | latitude | longitude | 
| ======== | ======= | ======== | ====== | ======== | ===== | ======== | ======== | ======================================================================== | ========== | ========== | ========== | ========== | ========== | =================== | ========== | ===== | ========== | ========== | ========= | ========== | =================== | ======== | ========= | 
| 517753   | 517753  | 16       | 12897  | 99       | -27   | BKR-1291 | BKR      | STEWART ST 0010 BLOCK SE SIDE ( 78) 78 FT NE/O 1ST AVE                   | SGL        | 2          | false      | GALV       | PCC        |                     | SUFMT      | NONE  | BKR-CRMTL  | BKR-RLRCK  | GOOD      | GOOD       |                     | 47.6104  | -122.341  | 
| 517876   | 517876  | 16       | 14276  | 65       | 34    | BKR-2784 | BKR      | E LAKE WASHINGTON BLVD 0220 BLOCK N SIDE ( 35) 35 FT E/O MONTLAKE BLVD E | SGL        | 1          | false      | GALV       | PCC        |                     | SUFMT      | GRN   | OTHER      | BKR-NCONF  |           |            | 2009-09-25T00:00:00 | 47.6441  | -122.3039 | 
| 518838   | 518838  | 16       | 8165   | 363      | 44    | BKR-1889 | BKR      | 7TH AVE 0220 BLOCK SW SIDE ( 341) 44 FT SE/O BELL ST                     | SGL        | 2          | false      | GALV       | PCC        |                     | SUFMT      | NONE  | BKR-CRMTL  | BKR-RLRCK  | GOOD      | GOOD       | 2009-07-15T00:00:00 | 47.6172  | -122.3413 | 
| 507180   | 507180  | 16       | 2658   | 172      | -34   | BKR-1    | BKR      | 19TH AVE E 0050 BLOCK E SIDE ( 142) 142 FT N/O E REPUBLICAN ST           | SGL        | 2          | false      | GALV       | PCC        |                     | SUFMT      |       | BKR-CRMTL  | BKR-INVRU  | GOOD      | GOOD       |                     | 47.6237  | -122.3072 | 
| 508041   | 508041  | 16       | 14243  | 113      | 29    | BKR-2    | BKR      | E JOHN ST 0090 BLOCK N SIDE ( 86) 86 FT E/O BROADWAY E                   | SGL        | 2          | false      | GALV       | PCC        | 2009-08-31T00:00:00 | SUFMT      | NONE  | BKR-CRMTL  | BKR-INVRU  |           |            | 2009-08-31T00:00:00 | 47.62    | -122.3204 | 
| 508042   | 508042  | 16       | 12867  | 127      | 30    | BKR-3    | BKR      | SPRING ST 0080 BLOCK NW SIDE ( 113) 113 FT NE/O 8TH AVE                  | SGL        | 2          | false      | GALV       | PCC        |                     | STBS       | NONE  | BKR-CRMTL  | BKR-CRRKB  |           |            |                     | 47.6089  | -122.3288 | 
| 508047   | 508047  | 16       | 14481  | 235      | 17    | BKR-4    | BKR      | E MERCER ST 0105 BLOCK N SIDE ( 222) 11 FT W/O 11TH AVE E                | SGL        | 2          | false      | GALV       | OTHER      |                     | SUFMT      | NONE  | BKR-CRMTL  | BKR-CRRKW  |           |            |                     | 47.6243  | -122.3179 | 
| 508050   | 508050  | 16       | 9223   | 134      | 26    | BKR-5    | BKR      | BELLEVUE AVE E 0060 BLOCK W SIDE ( 129) 115 FT S/O E ROY ST              | SGL        | 2          | false      | GALV       | PCC        |                     | SUFMT      | NONE  | BKR-CRMTL  | BKR-CRRKW  |           |            |                     | 47.6247  | -122.3267 | 
| 508051   | 508051  | 16       | 2556   | 473      | -17   | BKR-6    | BKR      | 18TH AVE E 0120 BLOCK E SIDE ( 460) 124 FT S/O E GALER ST                | SGL        | 2          | false      | GALV       | OTHER      |                     | SUFMT      | NONE  | BKR-CRMTL  | BKR-CRRKW  |           |            |                     | 47.6319  | -122.3085 | 
| 508052   | 508052  | 16       | 13106  | 98       | -24   | BKR-7    | BKR      | TERRY AVE 0080 BLOCK NE SIDE ( 85) 85 FT NW/O COLUMBIA ST                | SGL        | 2          | false      | GALV       | PCC        |                     | SUFMT      | NONE  | BKR-CRMTL  | BKR-CRRKW  |           |            |                     | 47.6077  | -122.3251 | 
```