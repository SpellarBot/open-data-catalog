# Towed Cars for the Past 30 Days

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/towed-cars-for-the-past-30-days) |
| Metadata | [Link](https://data.hartford.gov/api/views/hefc-wgp8) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/hefc-wgp8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/hefc-wgp8/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | hefc-wgp8 |
| Name | Towed Cars for the Past 30 Days |
| Attribution | City of Hartford |
| Category | Public Safety |
| Tags | tow, vehicle, car, public safety, hartford, ct |
| Created | 2015-02-14T01:41:08Z |
| Publication Date | 2015-04-27T14:31:38Z |

## Description

This is a listing of the vehicles that were towed in the past 30 days and it is updated hourly. It shows vehicle information, license plate number, and where the vehicle was towed along with other information. When there is a large volume of towing in will take a while for the information to be updated. This data set does not include vehicles coded in the database as evidence, operator arrested, suspected stolen, or all holds.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | numeric metric | townum           | TowNum           | number    | number      |
| Yes      | series tag     | tow_firm         | Tow_Firm         | text      | text        |
| No       |                | tow_firm_address | Tow_Firm_Address | text      | text        |
| Yes      | series tag     | tow_firm_phone   | Tow_Firm_Phone   | text      | text        |
| Yes      | series tag     | vehicle_state    | Vehicle_State    | text      | text        |
| Yes      | series tag     | vehicle_plate    | Vehicle_Plate    | text      | text        |
| Yes      | series tag     | vehicle_year     | Vehicle_Year     | text      | text        |
| Yes      | series tag     | make             | Make             | text      | text        |
| Yes      | series tag     | model            | Model            | text      | text        |
| Yes      | series tag     | color            | Color            | text      | text        |
| No       |                | tow_from_address | Tow_From_Address | text      | text        |
| No       |                | date             | Date             | text      | text        |
| Yes      | series tag     | time             | Time             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = tow_firm_address,tow_from_address,date
```

## Data Commands

```ls
series e:hefc-wgp8 d:2017-03-24T14:28:57.000Z t:time=0253 t:model=BONNEVILE t:tow_firm_phone=860-296-8588 t:color=SILVER t:vehicle_year=2002 t:vehicle_state=CT t:make=PONTIAC t:vehicle_plate=746ZSW m:townum=334031

series e:hefc-wgp8 d:2017-03-24T14:28:57.000Z t:time=0027 t:model=IMPALA t:tow_firm_phone=860-296-5382 t:color=GRY t:vehicle_year=2011 t:vehicle_state=CT t:tow_firm="CORONA'S AUTO PARTS,INC." t:make=CHEV t:vehicle_plate=928ZKP m:townum=334026

series e:hefc-wgp8 d:2017-03-24T14:28:57.000Z t:time=1922 t:model=DEVILLE t:tow_firm_phone=860-293-2442 t:color=BLACK t:vehicle_year=2003 t:vehicle_state=CT t:tow_firm="CAPITOL TOWING" t:make=CADILLAC t:vehicle_plate=AH92797 m:townum=333976
```

## Meta Commands

```ls
metric m:townum p:integer l:TowNum t:dataTypeName=number

entity e:hefc-wgp8 l:"Towed Cars for the Past 30 Days" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/hefc-wgp8

property e:hefc-wgp8 t:meta.view v:id=hefc-wgp8 v:category="Public Safety" v:attributionLink=http://ww.hartford.gov v:averageRating=0 v:name="Towed Cars for the Past 30 Days" v:attribution="City of Hartford"

property e:hefc-wgp8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:hefc-wgp8 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:hefc-wgp8 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| :updated_at | townum | tow_firm                    | tow_firm_address                        | tow_firm_phone | vehicle_state | vehicle_plate | vehicle_year | make     | model     | color  | tow_from_address | date     | time | 
| =========== | ====== | =========================== | ======================================= | ============== | ============= | ============= | ============ | ======== | ========= | ====== | ================ | ======== | ==== | 
| 1490365737  | 334031 |                             |                                         | 860-296-8588   | CT            | 746ZSW        | 2002         | PONTIAC  | BONNEVILE | SILVER |                  | 03242017 | 0253 | 
| 1490365737  | 334026 | CORONA'S AUTO PARTS,INC.    | 608 WETHERSFIELD AV. HARTFORD CT. 06114 | 860-296-5382   | CT            | 928ZKP        | 2011         | CHEV     | IMPALA    | GRY    |                  | 03242017 | 0027 | 
| 1490365737  | 333976 | CAPITOL TOWING              | 181-211 WALNUT ST. HARTFORD, CT. 06120  | 860-293-2442   | CT            | AH92797       | 2003         | CADILLAC | DEVILLE   | BLACK  |                  | 03222017 | 1922 | 
| 1490365737  | 334000 | A & N AUTO                  | 1516,PARK ST,HARTFORD,CT,06106          | 860-233-7079   | CT            | 529XSG        | 2007         | TOYOTA   | SIENNA    | GRAY   |                  | 03232017 | 1429 | 
| 1490365737  | 334006 | CORONA'S AUTO PARTS,INC.    | 608 WETHERSFIELD AV. HARTFORD CT. 06114 | 860-296-5382   | CT            | 271HXE        | 2001         | VW       | PASSAT    | BLUE   |                  | 03232017 | 1620 | 
| 1490365737  | 334029 |                             |                                         | 860-296-8588   | CT            | 2AVTD4        | 2003         | AUDI     | A6        | SILVER |                  | 03242017 | 0137 | 
| 1490365737  | 334025 | CENTRAL GARAGE              | 36 BOND ST. HARTFORD,CT 06114           | 860-296-1426   | CT            | AG35737       | 2001         | FORD     | TAURUS    | RED    |                  | 03232017 | 2357 | 
| 1490365737  | 333968 | FRIENDLY AUTO BODY & TOWING | 99 MEADOW ST. HARTFORD, CT. 06114       | 860-296-8588   |               |               | 1996         | HONDA    | ACCORD    | GREEN  |                  | 03222017 | 1501 | 
| 1490365737  | 334011 | RENO'S AUTO BODY            | 525 FRANKLIN AV. HARTFORD, CT 06114     | 860-296-1518   | CT            | AH45192       | 2005         | HYUNDIA  | ELANTRA   | SILVER |                  | 03232017 | 1846 | 
| 1490365737  | 333969 | METRO AUTOBODY & TOWING INC | 722 WETHERSFIELD AV HARTFORD CT 06114   | 860-947-3062   | CT            | 3AFEJ4        | 2010         | NISSAN   | ALTIMA    | BLK    |                  | 03222017 | 1542 | 
```