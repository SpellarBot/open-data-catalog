# Addresses in the City of Los Angeles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/addresses-in-the-city-of-los-angeles) |
| Metadata | [Link](https://data.lacity.org/api/views/4ca8-mxuh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/4ca8-mxuh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/4ca8-mxuh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 4ca8-mxuh |
| Name | Addresses in the City of Los Angeles |
| Attribution | Bureau of Engineering |
| Category | A Well Run City |
| Tags | addresses, address, house number, street name |
| Created | 2014-05-13T23:08:31Z |
| Publication Date | 2016-01-14T01:05:01Z |

## Description

Official addresses assigned in the City of Los Angeles created and maintained by the Bureau of Engineering.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | hse_id         | HSE_ID         | text      | number      |
| Yes      | series tag     | pin            | PIN            | text      | text        |
| Yes      | series tag     | pind           | PIND           | text      | text        |
| Yes      | numeric metric | hse_nbr        | HSE_NBR        | number    | number      |
| Yes      | series tag     | hse_frac_nbr   | HSE_FRAC_NBR   | text      | text        |
| Yes      | series tag     | hse_dir_cd     | HSE_DIR_CD     | text      | text        |
| Yes      | series tag     | str_nm         | STR_NM         | text      | text        |
| Yes      | series tag     | str_sfx_cd     | STR_SFX_CD     | text      | text        |
| Yes      | series tag     | str_sfx_dir_cd | STR_SFX_DIR_CD | text      | text        |
| Yes      | series tag     | unit_range     | UNIT_RANGE     | text      | text        |
| Yes      | series tag     | zip_cd         | ZIP_CD         | text      | number      |
| No       |                | lat            | LAT            | number    | number      |
| Yes      | numeric metric | lon            | LON            | number    | number      |
| Yes      | numeric metric | x_coord_nbr    | X_COORD_NBR    | number    | number      |
| Yes      | numeric metric | y_coord_nbr    | Y_COORD_NBR    | number    | number      |
| Yes      | series tag     | asgn_stts_ind  | ASGN_STTS_IND  | text      | text        |
| Yes      | series tag     | eng_dist       | ENG_DIST       | text      | text        |
| Yes      | numeric metric | cncl_dist      | CNCL_DIST      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lat
```

## Data Commands

```ls
series e:4ca8-mxuh d:2014-05-13T16:08:51.000Z t:str_sfx_cd=AVE t:str_nm=IVAR t:pind=150A187-366 t:pin="150A187   366" t:eng_dist=C t:asgn_stts_ind=U t:hse_dir_cd=N t:zip_cd=90028 t:hse_id=772643 m:lon=-118.32831 m:cncl_dist=13 m:hse_nbr=1769 m:y_coord_nbr=1860278.2747 m:x_coord_nbr=6462277.7237

series e:4ca8-mxuh d:2014-05-13T16:08:52.000Z t:str_sfx_cd=AVE t:str_nm=6TH t:pind=111B141-217 t:pin="111B141   217" t:eng_dist=W t:asgn_stts_ind=A t:hse_dir_cd=S t:zip_cd=90291 t:hse_id=1044886 m:lon=-118.47219 m:cncl_dist=11 m:hse_nbr=260 m:y_coord_nbr=1822514.5122 m:x_coord_nbr=6418544.8207

series e:4ca8-mxuh d:2014-05-13T16:08:52.000Z t:str_sfx_cd=AVE t:str_nm=BELFORD t:pind=096B169-869 t:pin="096B169   869" t:eng_dist=W t:asgn_stts_ind=A t:hse_dir_cd=S t:zip_cd=90045 t:hse_id=1042028 m:lon=-118.38381 m:cncl_dist=11 m:hse_nbr=8802 m:y_coord_nbr=1806865.5433 m:x_coord_nbr=6445274.1173
```

## Meta Commands

```ls
metric m:hse_nbr p:integer l:HSE_NBR d:"House Number" t:dataTypeName=number

metric m:lon p:float l:LON d:Longitude t:dataTypeName=number

metric m:x_coord_nbr p:decimal l:X_COORD_NBR d:"X coordinate in State Plane Coordinate System NAD83 California Zone V SRID: 2229" t:dataTypeName=number

metric m:y_coord_nbr p:double l:Y_COORD_NBR d:"Y coordinate in State Plane Coordinate System NAD83 California Zone V SRID: 2229" t:dataTypeName=number

metric m:cncl_dist p:integer l:CNCL_DIST d:"Council District" t:dataTypeName=number

entity e:4ca8-mxuh l:"Addresses in the City of Los Angeles" t:attribution="Bureau of Engineering" t:url=https://data.lacity.org/api/views/4ca8-mxuh

property e:4ca8-mxuh t:meta.view v:id=4ca8-mxuh v:category="A Well Run City" v:averageRating=0 v:name="Addresses in the City of Los Angeles" v:attribution="Bureau of Engineering"

property e:4ca8-mxuh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4ca8-mxuh t:meta.view.owner v:id=d7t2-dvpb v:profileImageUrlMedium=/api/users/d7t2-dvpb/profile_images/THUMB v:profileImageUrlLarge=/api/users/d7t2-dvpb/profile_images/LARGE v:screenName="Public Works: Engineering OpenData" v:profileImageUrlSmall=/api/users/d7t2-dvpb/profile_images/TINY v:displayName="Public Works: Engineering OpenData"

property e:4ca8-mxuh t:meta.view.tableauthor v:id=d7t2-dvpb v:profileImageUrlMedium=/api/users/d7t2-dvpb/profile_images/THUMB v:profileImageUrlLarge=/api/users/d7t2-dvpb/profile_images/LARGE v:screenName="Public Works: Engineering OpenData" v:profileImageUrlSmall=/api/users/d7t2-dvpb/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Engineering OpenData"
```

## Top Records

```ls
| :updated_at | hse_id  | pin           | pind          | hse_nbr | hse_frac_nbr | hse_dir_cd | str_nm    | str_sfx_cd | str_sfx_dir_cd | unit_range | zip_cd | lat      | lon        | x_coord_nbr   | y_coord_nbr   | asgn_stts_ind | eng_dist | cncl_dist | 
| =========== | ======= | ============= | ============= | ======= | ============ | ========== | ========= | ========== | ============== | ========== | ====== | ======== | ========== | ============= | ============= | ============= | ======== | ========= | 
| 1399997331  | 772643  | 150A187 366   | 150A187-366   | 1769    |              | N          | IVAR      | AVE        |                |            | 90028  | 34.10369 | -118.32831 | 6462277.7237  | 1860278.2747  | U             | C        | 13        | 
| 1399997332  | 1044886 | 111B141 217   | 111B141-217   | 260     |              | S          | 6TH       | AVE        |                |            | 90291  | 33.99944 | -118.47219 | 6418544.8207  | 1822514.5122  | A             | W        | 11        | 
| 1399997332  | 1042028 | 096B169 869   | 096B169-869   | 8802    |              | S          | BELFORD   | AVE        |                |            | 90045  | 33.95675 | -118.38381 | 6445274.1173  | 1806865.5433  | A             | W        | 11        | 
| 1399997332  | 1040000 | 147B197 608   | 147B197-608   | 4610    |              | W          | MAUBERT   | AVE        |                |            | 90027  | 34.0989  | -118.29008 | 6473861.67148 | 1858509.22961 | A             | C        | 13        | 
| 1399997332  | 1042029 | 096B169 869   | 096B169-869   | 8802    | 1/2          | S          | BELFORD   | AVE        |                |            | 90045  | 33.95675 | -118.38381 | 6445274.1173  | 1806865.5433  | A             | W        | 11        | 
| 1399997332  | 1039775 | 192B101 758   | 192B101-758   | 8320    |              | N          | CHELSEA   | LANE       |                |            | 91304  | 34.22081 | -118.60988 | 6377299.8421  | 1903297.173   | A             | V        | 12        | 
| 1399997332  | 1045065 | 151-5A189 353 | 151-5A189-353 | 2031    |              | N          | CHEREMOYA | AVE        |                |            | 90068  | 34.10839 | -118.32073 | 6464578.7407  | 1861980.8861  | L             | C        | 4         | 
| 1399997332  | 1066012 | 129B169 1343  | 129B169-1343  | 9039    |              | W          | CRESTA    | DR         |                |            | 90035  | 34.04616 | -118.38767 | 6444227.19264 | 1839407.2285  | A             | W        | 5         | 
| 1399997332  | 1040871 | 108B213 259   | 108B213-259   | 5500    |              | S          | FORTUNA   | ST         |                |            | 90011  | 33.99288 | -118.24543 | 6487269.89475 | 1819882.09675 | A             | C        | 9         | 
| 1399997333  | 1040385 | 174B121 796   | 174B121-796   | 5821    |              | N          | YOLANDA   | AVE        |                |            | 91356  | 34.17615 | -118.54091 | 6398061.5307  | 1886925.6432  | A             | V        | 3         | 
```