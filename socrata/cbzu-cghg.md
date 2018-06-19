# City of Somerville Assessors Valuations FY15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-somerville-assessors-valuations-fy15) |
| Metadata | [Link](https://data.somervillema.gov/api/views/cbzu-cghg) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/cbzu-cghg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/cbzu-cghg/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | cbzu-cghg |
| Name | City of Somerville Assessors Valuations FY15 |
| Attribution | City of Somerville Assessing Department |
| Category | Finance |
| Tags | assessing, valuation, financial, assessor, property values |
| Created | 2015-11-19T14:24:11Z |
| Publication Date | 2015-11-19T15:35:30Z |

## Description

The State Department of Revenue (DOR) has approved assessed values for Fiscal Year (FY) 2015 for the Somerville Board of Assessors. The assessed values and data presented relects information available for the FY 2015 actual tax bill issued around January 1, 2015.  Assessments for FY 2015 have an effective market date of January 1, 2014.

Note that ownership information shows record owner as of January 1, 2014.  However, a second line of owneship, if applicable, showing "S/O" indicates a subsequent owner who purchased the property after January 1, 2014 but prior to January 1, 2015.  In this instance, title information including sale price, sale date, and book & page will not appear in the data base until next year or for the third quarter tax bill for FY 2016 issued around  January 1, 2015.  New ownership information is provided through about early October of 2014.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | mbl                 | MBL                 | text          | text          |
| Yes      | series tag     | unit                | UNIT                | text          | text          |
| Yes      | numeric metric | account             | ACCOUNT             | number        | number        |
| Yes      | series tag     | location            | LOCATION            | text          | text          |
| Yes      | series tag     | parcel_id           | PARCEL ID           | text          | text          |
| Yes      | numeric metric | pcc                 | PCC                 | number        | number        |
| Yes      | series tag     | pcc_descript        | PCC DESCRIPT        | text          | text          |
| Yes      | series tag     | commitment_owner    | COMMITMENT OWNER    | text          | text          |
| Yes      | series tag     | current_owner       | CURRENT OWNER       | text          | text          |
| Yes      | series tag     | current_co_owner    | CURRENT CO-OWNER    | text          | text          |
| No       |                | owner_add           | OWNER ADDRESS       | text          | text          |
| Yes      | series tag     | owner_city          | OWNER CITY          | text          | text          |
| Yes      | series tag     | owner_state         | OWNER STATE         | text          | text          |
| Yes      | series tag     | owner_zip           | OWNER ZIP           | text          | number        |
| Yes      | numeric metric | sale_price          | SALE PRICE          | number        | number        |
| Yes      | time           | sale_date           | SALE DATE           | calendar_date | calendar_date |
| Yes      | series tag     | book_page           | BOOK PAGE           | text          | text          |
| Yes      | series tag     | cert_no             | CERT NO             | text          | number        |
| Yes      | series tag     | boarder_flag        | BOARDER FLAG        | text          | text          |
| Yes      | series tag     | sale_valid          | SALE VALID          | text          | text          |
| Yes      | series tag     | ward                | WARD                | text          | number        |
| Yes      | series tag     | precinct            | PRECINCT            | text          | number        |
| Yes      | numeric metric | parcel_val          | PARCEL VAL          | number        | number        |
| Yes      | numeric metric | land_val            | LAND VAL            | number        | number        |
| Yes      | numeric metric | improve_val         | IMPROVE VAL         | number        | number        |
| Yes      | numeric metric | sqft                | SQFT                | number        | number        |
| Yes      | numeric metric | nhbd                | NHBD                | number        | number        |
| Yes      | numeric metric | site_index          | SITE INDEX          | number        | number        |
| Yes      | series tag     | bdld_no             | BDLD NO             | text          | number        |
| Yes      | numeric metric | occup               | OCCUP               | number        | number        |
| Yes      | series tag     | style_descrip       | STYLE DESCRIP       | text          | text          |
| Yes      | numeric metric | stories             | STORIES             | number        | number        |
| Yes      | series tag     | wall_type_1         | WALL TYPE 1         | text          | text          |
| Yes      | series tag     | wall_type_2         | WALL TYPE 2         | text          | text          |
| Yes      | series tag     | heat_type           | HEAT TYPE           | text          | text          |
| Yes      | series tag     | fuel_type           | FUEL TYPE           | text          | text          |
| Yes      | series tag     | ac_type             | AC TYPE             | text          | text          |
| Yes      | numeric metric | gross_area          | GROSS AREA          | number        | number        |
| Yes      | numeric metric | living_area         | LIVING AREA         | number        | number        |
| Yes      | numeric metric | rooms               | ROOMS               | number        | number        |
| Yes      | numeric metric | bedroom             | BEDROOM             | number        | number        |
| Yes      | numeric metric | bath                | BATH                | number        | number        |
| Yes      | series tag     | bath_descrip        | BATH DESCRIP        | text          | text          |
| Yes      | series tag     | kitchen_descrip     | KITCHEN DESCRIP     | text          | text          |
| Yes      | numeric metric | percent_good        | PERCENT GOOD        | number        | number        |
| Yes      | series tag     | grade_descrip       | GRADE DESCRIP       | text          | text          |
| Yes      | numeric metric | year                | YEAR                | number        | number        |
| Yes      | series tag     | resx_flag           | RESX FLAG           | text          | text          |
| Yes      | series tag     | local_historical    | LOCAL HISTORICAL    | text          | text          |
| Yes      | series tag     | national_historical | NATIONAL HISTORICAL | text          | text          |
| Yes      | series tag     | zone                | ZONE                | text          | text          |
| Yes      | series tag     | zone_desp           | ZONE DESP           | text          | text          |
| Yes      | numeric metric | exempt_amt          | EXEMPT AMT          | number        | number        |
| Yes      | numeric metric | tax_value           | TAX VALUE           | number        | number        |
```

## Time Field

```ls
Value = sale_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = owner_add
```

## Data Commands

```ls
series e:cbzu-cghg d:1989-11-10T00:00:00.000Z t:style_descrip=Conventional t:bdld_no=1 t:parcel_id=013A0025A000000 t:current_owner="DAVIS  L. WHITNEY" t:kitchen_descrip=Semi-Modern t:location="26 MEAD ST" t:owner_zip=2144 t:local_historical=N t:ac_type=None t:commitment_owner="DAVIS  L. WHITNEY" t:national_historical=N t:pcc_descript="SING FAMLY" t:owner_city=SOMERVILLE t:precinct=1 t:grade_descrip=Average t:heat_type="Forced Air-Duc" t:mbl="13/ A/ 25A" t:book_page="20177/ 588" t:fuel_type=Gas t:wall_type_1=Clapboard t:ward=7 t:zone_desp=RESIDENCE t:owner_state=MA t:boarder_flag=N t:resx_flag=Y t:zone=RB t:sale_valid=Q m:nhbd=1001 m:parcel_val=642400 m:sale_price=169000 m:living_area=848 m:land_val=463800 m:pcc=1010 m:gross_area=1526 m:improve_val=178600 m:sqft=3729 m:bedroom=1 m:exempt_amt=150674 m:stories=2 m:tax_value=2579.23 m:bath=2 m:occup=1 m:account=1720 m:percent_good=99 m:year=1985 m:site_index=4 m:rooms=5

series e:cbzu-cghg d:2015-11-19T06:24:27.000Z t:bdld_no=1 t:parcel_id=024G00001000000 t:current_owner="CITY OF SOMERVILLE" t:location="0 HIGHLAND AVE" t:owner_zip=2143 t:local_historical=N t:commitment_owner="CITY OF SOMERVILLE" t:national_historical=N t:current_co_owner="DAVIS SQ PARKING LOT" t:owner_city=SOMERVILLE t:pcc_descript="CITY VACANT" t:mbl="24/ G/ 1" t:owner_state=MA t:resx_flag=N t:sale_valid=U m:exempt_amt=0 m:parcel_val=1219900 m:nhbd=4009 m:sale_price=0 m:land_val=1192900 m:pcc=9300 m:tax_value=0 m:account=4120 m:year=0 m:improve_val=27000 m:sqft=9100

series e:cbzu-cghg d:2015-11-19T06:24:27.000Z t:bdld_no=1 t:parcel_id=027B00003000000 t:current_owner="FOSTER HERBERT F & HERBERT F JR." t:location="0 BROADWAY" t:owner_zip=2145 t:local_historical=N t:commitment_owner="FOSTER HERBERT F & HERBERT F JR." t:national_historical=N t:owner_city=SOMERVILLE t:pcc_descript="UNDEV LAND" t:precinct=2 t:mbl="27/ B/ 3" t:ward=5 t:owner_state=MA t:boarder_flag=M t:resx_flag=N t:sale_valid=U m:exempt_amt=0 m:parcel_val=49200 m:nhbd=4003 m:sale_price=0 m:land_val=49200 m:pcc=3920 m:tax_value=531.35 m:account=4414 m:year=0 m:improve_val=0 m:sqft=830
```

## Meta Commands

```ls
metric m:account p:integer l:ACCOUNT t:dataTypeName=number

metric m:pcc p:integer l:PCC t:dataTypeName=number

metric m:sale_price p:integer l:"SALE PRICE" t:dataTypeName=number

metric m:parcel_val p:integer l:"PARCEL VAL" t:dataTypeName=number

metric m:land_val p:integer l:"LAND VAL" t:dataTypeName=number

metric m:improve_val p:integer l:"IMPROVE VAL" t:dataTypeName=number

metric m:sqft p:integer l:SQFT t:dataTypeName=number

metric m:nhbd p:integer l:NHBD t:dataTypeName=number

metric m:site_index p:integer l:"SITE INDEX" t:dataTypeName=number

metric m:occup p:integer l:OCCUP t:dataTypeName=number

metric m:stories p:double l:STORIES t:dataTypeName=number

metric m:gross_area p:integer l:"GROSS AREA" t:dataTypeName=number

metric m:living_area p:integer l:"LIVING AREA" t:dataTypeName=number

metric m:rooms p:integer l:ROOMS t:dataTypeName=number

metric m:bedroom p:integer l:BEDROOM t:dataTypeName=number

metric m:bath p:integer l:BATH t:dataTypeName=number

metric m:percent_good p:integer l:"PERCENT GOOD" t:dataTypeName=number

metric m:year p:integer l:YEAR t:dataTypeName=number

metric m:exempt_amt p:integer l:"EXEMPT AMT" t:dataTypeName=number

metric m:tax_value p:float l:"TAX VALUE" t:dataTypeName=number

entity e:cbzu-cghg l:"City of Somerville Assessors Valuations FY15" t:attribution="City of Somerville Assessing Department" t:url=https://data.somervillema.gov/api/views/cbzu-cghg

property e:cbzu-cghg t:meta.view v:id=cbzu-cghg v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance/assessing v:averageRating=0 v:name="City of Somerville Assessors Valuations FY15" v:attribution="City of Somerville Assessing Department"

property e:cbzu-cghg t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:cbzu-cghg t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:cbzu-cghg t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| mbl        | unit | account | location          | parcel_id       | pcc  | pcc_descript | commitment_owner                 | current_owner                    | current_co_owner                 | owner_add                      | owner_city | owner_state | owner_zip | sale_price | sale_date           | book_page  | cert_no | boarder_flag | sale_valid | ward | precinct | parcel_val | land_val | improve_val | sqft | nhbd | site_index | bdld_no | occup | style_descrip  | stories | wall_type_1  | wall_type_2   | heat_type      | fuel_type | ac_type | gross_area | living_area | rooms | bedroom | bath | bath_descrip | kitchen_descrip | percent_good | grade_descrip | year | resx_flag | local_historical | national_historical | zone | zone_desp  | exempt_amt | tax_value | 
| ========== | ==== | ======= | ================= | =============== | ==== | ============ | ================================ | ================================ | ================================ | ============================== | ========== | =========== | ========= | ========== | =================== | ========== | ======= | ============ | ========== | ==== | ======== | ========== | ======== | =========== | ==== | ==== | ========== | ======= | ===== | ============== | ======= | ============ | ============= | ============== | ========= | ======= | ========== | =========== | ===== | ======= | ==== | ============ | =============== | ============ | ============= | ==== | ========= | ================ | =================== | ==== | ========== | ========== | ========= | 
| 13/ A/ 25A |      | 1720    | 26 MEAD ST        | 013A0025A000000 | 1010 | SING FAMLY   | DAVIS L. WHITNEY                 | DAVIS L. WHITNEY                 |                                  | 26 MEAD ST                     | SOMERVILLE | MA          | 2144      | 169000     | 1989-11-10T00:00:00 | 20177/ 588 |         | N            | Q          | 7    | 1        | 642400     | 463800   | 178600      | 3729 | 1001 | 4          | 1       | 1     | Conventional   | 2       | Clapboard    |               | Forced Air-Duc | Gas       | None    | 1526       | 848         | 5     | 1       | 2    |              | Semi-Modern     | 99           | Average       | 1985 | Y         | N                | N                   | RB   | RESIDENCE  | 150674     | 2579.23   | 
| 24/ G/ 1   |      | 4120    | 0 HIGHLAND AVE    | 024G00001000000 | 9300 | CITY VACANT  | CITY OF SOMERVILLE               | CITY OF SOMERVILLE               | DAVIS SQ PARKING LOT             | 93 HIGHLAND AVE                | SOMERVILLE | MA          | 2143      | 0          |                     |            |         |              | U          |      |          | 1219900    | 1192900  | 27000       | 9100 | 4009 |            | 1       |       |                |         |              |               |                |           |         |            |             |       |         |      |              |                 |              |               | 0    | N         | N                | N                   |      |            | 0          | 0         | 
| 27/ B/ 3   |      | 4414    | 0 BROADWAY        | 027B00003000000 | 3920 | UNDEV LAND   | FOSTER HERBERT F & HERBERT F JR. | FOSTER HERBERT F & HERBERT F JR. |                                  | 78 PUTNAM RD                   | SOMERVILLE | MA          | 2145      | 0          |                     |            |         | M            | U          | 5    | 2        | 49200      | 49200    | 0           | 830  | 4003 |            | 1       |       |                |         |              |               |                |           |         |            |             |       |         |      |              |                 |              |               | 0    | N         | N                | N                   |      |            | 0          | 531.35    | 
| 34/ D/ 21  |      | 5508    | 126 ALBION ST     | 034D00021000000 | 1050 | THREE FAM    | SIGGENS JR ROBERT F              | SIGGENS JR ROBERT F              |                                  | 45 HEMLOCK ST                  | ARLINGTON  | MA          | 2474      | 0          | 2008-03-21T00:00:00 | 50915/ 204 |         | N            | U          | 5    | 2        | 815600     | 379300   | 436300      | 4630 | 8001 | 3          | 1       | 3     | 3-Decker       | 3       | Vinyl Siding |               | Hot Water      | Oil       | None    | 5583       | 3839        | 17    | 7       | 3    |              | Modern          | 83           | Average       | 1910 | N         | N                | N                   | RB   | RESIDENCE  | 0          | 4743.74   | 
| 37/ B/ 1   |      | 5704    | 0 SOMERVILLE AVE  | 037B00001000000 |      | MBTA VACANT  | MBTA                             | MBTA                             | C/O BRENNAN MICHAEL R E DIRECTOR | 10 PARK PLAZA SUITE 5750       | BOSTON     | MA          | 2116      | 0          |                     |            |         |              | U          |      |          | 218200     | 205400   | 12800       | 2500 | 4009 |            | 1       |       |                |         |              |               |                |           |         |            |             |       |         |      |              |                 |              |               | 0    | N         | N                | N                   |      |            | 0          | 0         | 
| 37/ F/ 6   |      | 5900    | 0 OXFORD ST       | 037F00006000000 | 9300 | CITY VACANT  | CITY OF SOMERVILLE               | CITY OF SOMERVILLE               | OXFORD/BEACON LOT                | 93 HIGHLAND AVE                | SOMERVILLE | MA          | 2143      | 0          | 1973-03-01T00:00:00 | 12394/ 584 |         |              | U          |      |          | 1600       | 1600     | 0           | 40   | 2009 |            | 1       |       |                |         |              |               |                |           |         |            |             |       |         |      |              |                 |              |               | 0    | N         | N                | N                   |      |            | 0          | 0         | 
| 38/ A/ 14  |      | 6014    | 11 PORTER ST      | 038A00014000000 | 1050 | THREE FAM    | MAHER PATRICK TRSTEE             | MAHER PATRICK TRSTEE             | THE MALDEN TRUST                 | 966 BROADWAY                   | SOMERVILLE | MA          | 2144      | 1          | 2007-02-13T00:00:00 | 48983/ 061 |         | N            | U          | 3    | 3        | 652100     | 291800   | 360300      | 2145 | 8001 | 3          | 1       | 3     | 3-Decker       | 3       | Wood Shingle |               | Steam          | Oil       | None    | 4872       | 3231        | 15    | 6       | 3    |              | Old Style       | 79           | Average       | 1900 | N         | N                | N                   | RB   | RESIDENCE  | 0          | 3790.8    | 
| 39/ D/ 13  |      | 6933    | 4 BECKWITH CIRCLE | 039D00013000000 | 1050 | THREE FAM    | PRESIDENT & FELLOWS OF HARVARD   | PRESIDENT & FELLOWS OF HARVARD   | C/O HARVARD REAL ESTATE INC      | 46 BLACKSTONE ST - SO BUILDING | CAMBRIDGE  | MA          | 2139      | 1          |                     | 12554/ 029 |         | N            | U          | 2    | 3        | 751800     | 319800   | 432000      | 1686 | 2001 | 3          | 1       | 3     | 3-Decker       | 3       | Clapboard    |               | Hot Water      | Gas       | None    | 4958       | 3708        | 15    | 9       | 3    |              | Modern          | 84           | Average       | 1900 | N         | N                | N                   | RC   | RESIDENCE  | 0          | 4272.21   | 
| 40/ I/ 1   |      | 7304    | 531 MEDFORD ST    | 040I00001000000 | 3220 | STORE/SHOP   | MAGOUN SQUARE REALTY LLC         | MAGOUN SQUARE REALTY LLC         |                                  | PO BOX 45354                   | SOMERVILLE | MA          | 2145      | 470000     | 2002-07-10T00:00:00 |            | 1218250 | N            | Q          | 5    | 1        | 660400     | 226500   | 433900      | 3220 | 7003 |            | 1       | 10    | Retail/Offices | 2       | MASONRY      | Brick/Masonry | Steam          | Oil       | None    | 9947       | 6606        |       |         |      |              |                 | 58           | Average       | 1920 | N         | N                | N                   | NB   | NEIGHBORHO | 0          | 7255.35   | 
| 40/ I/ 3   |      | 7402    | 482 BROADWAY      | 040I00003000000 |      | OFFICE BLD   | BLUMSACK A P & KAUFMAN P S TRSTS | BLUMSACK A P & KAUFMAN P S TRSTS | BK REALTY TRUST                  | 482 BROADWAY                   | SOMERVILLE | MA          | 2145      | 200000     | 1998-05-07T00:00:00 | 28547/ 607 |         | N            | Q          | 5    | 1        | 533300     | 220500   | 312800      | 3043 | 7002 |            | 1       | 2     | Conventional   | 2       | Clapboard    | Wood Shingle  | Hot Water      | Gas       | None    | 4904       | 2655        | 10    | 2       | 2    |              | Modern          | 69           | Average       | 1900 | N         | N                | N                   | NB   | NEIGHBORHO | 0          | 4462.76   | 
```