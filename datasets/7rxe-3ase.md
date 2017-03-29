# City Of Somerville Assessors Valuations FY16

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-somerville-assessors-valuations-fy16) |
| Metadata | [Link](https://data.somervillema.gov/api/views/7rxe-3ase) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/7rxe-3ase/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/7rxe-3ase/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | 7rxe-3ase |
| Name | City Of Somerville Assessors Valuations FY16 |
| Attribution | City of Somerville Assessing Department |
| Category | Finance |
| Tags | assessing, valuation, financial, assessor, property values |
| Created | 2015-11-10T19:36:33Z |
| Publication Date | 2015-11-12T21:10:38Z |

## Description

The State Department of Revenue (DOR) has approved assessed values for Fiscal Year (FY) 2016 for the Somerville Board of Assessors. The assessed values and data presented relects information available for the FY 2016 actual tax bill issued around January 1, 2016.  Assessments for FY 2016 have an effective market date of January 1, 2015.

Note that ownership information shows record owner as of January 1, 2015.  However, a second line of owneship, if applicable, showing "S/O" indicates a subsequent owner who purchased the property after January 1, 2015 but prior to January 1, 2016.  In this instance, title information including sale price, sale date, and book & page will not appear in the data base until next year or for the third quarter tax bill for FY 2017 issued around  January 1, 2016.  New ownership information is provided through about early October of 2015.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | mbl                         | MBL                         | text      | text        |
| Yes      | series tag     | account_number              | Account Number              | text      | number      |
| Yes      | numeric metric | res_nbhd                    | Res NBHD                    | number    | number      |
| Yes      | series tag     | location                    | Location                    | text      | text        |
| Yes      | series tag     | building_type               | Building Type               | text      | text        |
| Yes      | series tag     | gis_id                      | GIS ID                      | text      | text        |
| Yes      | series tag     | bldg_no                     | Bldg No                     | text      | number      |
| Yes      | series tag     | cls                         | Cls                         | text      | text        |
| Yes      | series tag     | use_code                    | Use Code                    | text      | text        |
| Yes      | numeric metric | land_area_in_acres          | Land Area in Acres          | number    | number      |
| Yes      | numeric metric | living_area                 | Living Area                 | number    | number      |
| Yes      | numeric metric | ayb                         | AYB                         | number    | number      |
| Yes      | series tag     | eyb_code                    | EYB Code                    | text      | text        |
| Yes      | series tag     | style_desc                  | Style Desc                  | text      | text        |
| Yes      | numeric metric | grd                         | GRD                         | number    | number      |
| Yes      | series tag     | siding                      | SIDING                      | text      | text        |
| Yes      | numeric metric | num_bedrms                  | Num Bedrms                  | number    | number      |
| Yes      | numeric metric | full_baths                  | Full Baths                  | number    | number      |
| Yes      | numeric metric | half_baths                  | Half Baths                  | number    | number      |
| Yes      | numeric metric | total_assessed_land_value   | Total Assessed Land Value   | number    | number      |
| Yes      | numeric metric | total_assessed_parcel_value | Total Assessed Parcel Value | number    | number      |
| Yes      | series tag     | grantee                     | Grantee                     | text      | text        |
| Yes      | series tag     | co_grantee_s_name           | Co_grantee's Name           | text      | text        |
| No       |                | mailing_address             | Mailing Address             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:7rxe-3ase d:2015-11-10T17:20:08.000Z t:mbl="39/ C/ 23/ 4C/" t:bldg_no=1 t:use_code=1020 t:cls=R t:account_number=870151 t:eyb_code=A+5 t:location="255 BEACON ST" t:style_desc="Low rise" t:gis_id=39-C-23 t:building_type=Condominium t:grantee="ZHU ZHIYING" m:living_area=794 m:land_area_in_acres=0 m:num_bedrms=2 m:ayb=1986 m:res_nbhd=2001 m:total_assessed_parcel_value=342300 m:half_baths=0 m:total_assessed_land_value=0 m:full_baths=2

series e:7rxe-3ase d:2015-11-10T17:18:21.000Z t:mbl="73/ A/ 48/ 1/" t:bldg_no=1 t:use_code=1020 t:cls=R t:account_number=20052620 t:eyb_code=VG t:location="7 VINAL AVE" t:style_desc="Three decker" t:gis_id=73-A-48 t:building_type=Condominium t:grantee="ASHER RUTH SARAH" m:living_area=1044 m:land_area_in_acres=0 m:num_bedrms=2 m:ayb=1900 m:res_nbhd=8001 m:total_assessed_parcel_value=429100 m:half_baths=0 m:total_assessed_land_value=0 m:full_baths=1

series e:7rxe-3ase d:2015-11-10T17:19:10.000Z t:mbl="70/ C/ 23/ 1/" t:bldg_no=1 t:use_code=1020 t:cls=R t:account_number=20092730 t:eyb_code=VG t:location="25 WHEATLAND ST #1" t:style_desc="Two Family" t:gis_id=70-C-23 t:building_type=Condominium t:grantee="DIAMOND LESLIE" m:living_area=1058 m:land_area_in_acres=0 m:num_bedrms=2 m:ayb=1885 m:res_nbhd=5001 m:total_assessed_parcel_value=340000 m:total_assessed_land_value=0 m:full_baths=1
```

## Meta Commands

```ls
metric m:res_nbhd p:integer l:"Res NBHD" t:dataTypeName=number

metric m:land_area_in_acres p:decimal l:"Land Area in Acres" t:dataTypeName=number

metric m:living_area p:integer l:"Living Area" t:dataTypeName=number

metric m:ayb p:integer l:AYB t:dataTypeName=number

metric m:grd p:integer l:GRD t:dataTypeName=number

metric m:num_bedrms p:integer l:"Num Bedrms" t:dataTypeName=number

metric m:full_baths p:integer l:"Full Baths" t:dataTypeName=number

metric m:half_baths p:integer l:"Half Baths" t:dataTypeName=number

metric m:total_assessed_land_value p:integer l:"Total Assessed Land Value" t:dataTypeName=number

metric m:total_assessed_parcel_value p:integer l:"Total Assessed Parcel Value" t:dataTypeName=number

entity e:7rxe-3ase l:"City Of Somerville Assessors Valuations FY16" t:attribution="City of Somerville Assessing Department" t:url=https://data.somervillema.gov/api/views/7rxe-3ase

property e:7rxe-3ase t:meta.view v:id=7rxe-3ase v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance/assessing v:averageRating=0 v:name="City Of Somerville Assessors Valuations FY16" v:attribution="City of Somerville Assessing Department"

property e:7rxe-3ase t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:7rxe-3ase t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| :updated_at | mbl             | account_number | res_nbhd | location            | building_type | gis_id  | bldg_no | cls | use_code | land_area_in_acres | living_area | ayb  | eyb_code | style_desc   | grd | siding | num_bedrms | full_baths | half_baths | total_assessed_land_value | total_assessed_parcel_value | grantee          | co_grantee_s_name | mailing_address     | 
| =========== | =============== | ============== | ======== | =================== | ============= | ======= | ======= | === | ======== | ================== | =========== | ==== | ======== | ============ | === | ====== | ========== | ========== | ========== | ========================= | =========================== | ================ | ================= | =================== | 
| 1447176008  | 39/ C/ 23/ 4C/  | 870151         | 2001     | 255 BEACON ST       | Condominium   | 39-C-23 | 1       | R   | 1020     | 0                  | 794         | 1986 | A+5      | Low rise     |     |        | 2          | 2          | 0          | 0                         | 342300                      | ZHU ZHIYING      |                   | 50 MAIN ST          | 
| 1447175901  | 73/ A/ 48/ 1/   | 20052620       | 8001     | 7 VINAL AVE         | Condominium   | 73-A-48 | 1       | R   | 1020     | 0                  | 1044        | 1900 | VG       | Three decker |     |        | 2          | 1          | 0          | 0                         | 429100                      | ASHER RUTH SARAH |                   | 7 VINAL AVE #1      | 
| 1447175950  | 70/ C/ 23/ 1/   | 20092730       | 5001     | 25 WHEATLAND ST #1  | Condominium   | 70-C-23 | 1       | R   | 1020     | 0                  | 1058        | 1885 | VG       | Two Family   |     |        | 2          | 1          |            | 0                         | 340000                      | DIAMOND LESLIE   |                   | 25 WHEATLAND ST #1  | 
| 1447175951  | 68/ A/ 15/ 33/  | 20101640       | 6001     | 33 PUTNAM RD        | Condominium   | 68-A-15 | 1       | R   | 1020     | 0                  | 1818        | 1900 | G        | Two decker   |     |        | 4          | 2          |            | 0                         | 413600                      | MORROW RENE      |                   | 33 PUTNAM RD        | 
| 1447175939  | 66/ E/ 13/ 1/   | 20091350       | 2001     | 36 LINE ST          | Condominium   | 66-E-13 | 1       | R   | 1020     | 0                  | 1023        | 1900 | E        | Three decker |     |        | 2          | 1          |            | 0                         | 512800                      | GOOD RICHARD K   |                   | 36 LINE ST #1       | 
| 1447175957  | 62/ B/ 8/ 21-2/ | 20064400       | 8001     | 21 PRESCOTT ST #2   | Condominium   | 62-B-8  | 1       | R   | 1020     | 0                  | 570         | 1900 | G+5      | Row End      |     |        | 1          | 1          |            | 0                         | 255800                      | KEEGAN HETTY M   |                   | 21 PRESCOTT ST #2   | 
| 1447175907  | 47/ C/ 22/ 1/   | 20110670       | 5001     | 127 HEATH ST #1     | Condominium   | 47-C-22 | 1       | R   | 1020     | 0                  | 829         | 1910 | VG       | Duplex       |     |        | 2          | 2          |            | 0                         | 354600                      | NETO JAQUER D    |                   | 96 POND ST          | 
| 1447175966  | 47/ B/ 7/ 2/    | 20151180       | 5001     | 36 MORELAND ST #2   | Condominium   | 47-B-7  | 1       | R   | 1020     | 0                  | 993         | 1915 | E        | Two Family   |     |        | 2          | 2          |            | 0                         | 367700                      | SAULNIER DENIS   |                   | 36 MORELAND ST #2   | 
| 1447175900  | 43/ D/ 6/ 1/    | 20141230       | 8001     | 162 HIGHLAND AVE #1 | Condominium   | 43-D-6  | 1       | R   | 1020     | 0                  | 1365        | 1900 | VG       | Victorian    |     |        | 3          | 3          |            | 0                         | 564900                      | SOBENKO STEPHEN  |                   | 162 HIGHLAND AVE #1 | 
| 1447175888  | 41/ A/ 28/ 12/  | 20064920       | 7001     | 12 TRULL ST         | Condominium   | 41-A-28 | 1       | R   | 1020     | 0                  | 976         | 1920 | G+5      | Two Family   |     |        | 2          | 2          |            | 0                         | 384500                      | TASCI YUNUS E    |                   | 12 TRULL ST         | 
```