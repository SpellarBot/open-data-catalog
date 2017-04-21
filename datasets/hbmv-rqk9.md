# County Clerk License Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-clerk-license-information-2ccd5) |
| Metadata | [Link](https://data.mo.gov/api/views/hbmv-rqk9) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/hbmv-rqk9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/hbmv-rqk9/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | hbmv-rqk9 |
| Name | County Clerk License Information |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | alcohol, license, liquor, county, clerk, missouri, weekly |
| Created | 2012-06-26T15:27:31Z |
| Publication Date | 2017-04-20T12:34:52Z |

## Description

Alcohol Licensing information by County compiled weekly storing 3 weeks at a time

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | license_number    | License Number    | text          | number        |
| Yes      | series tag  | licensee_name     | Licensee Name     | text          | text          |
| Yes      | series tag  | dba_name          | DBA Name          | text          | text          |
| Yes      | series tag  | license_type      | License Type      | text          | text          |
| Yes      | series tag  | current_status    | Current Status    | text          | text          |
| Yes      | time        | effective_date    | Effective Date    | calendar_date | calendar_date |
| No       |             | fee_date          | Fee Date          | calendar_date | calendar_date |
| Yes      | series tag  | fee_type          | Fee Type          | text          | text          |
| No       |             | expiration_date   | Expiration Date   | calendar_date | calendar_date |
| Yes      | series tag  | business_phone    | Business Phone    | phone         | phone         |
| Yes      | series tag  | manager_phone     | Manager Phone     | phone         | phone         |
| Yes      | series tag  | first_name        | First Name        | text          | text          |
| Yes      | series tag  | last_name         | Last Name         | text          | text          |
| Yes      | series tag  | district          | District          | text          | text          |
| Yes      | series tag  | subdistrict       | SubDistrict       | text          | text          |
| Yes      | series tag  | county            | County            | text          | text          |
| Yes      | series tag  | street_number     | Street Number     | text          | text          |
| Yes      | series tag  | street            | Street            | text          | text          |
| Yes      | series tag  | city              | City              | text          | text          |
| Yes      | series tag  | state             | State             | text          | text          |
| Yes      | series tag  | zip_code          | Zip Code          | text          | text          |
| No       |             | mailing_address_1 | Mailing Address 1 | text          | text          |
| No       |             | mailing_address_2 | Mailing Address 2 | text          | text          |
| No       |             | mailing_address_3 | Mailing Address 3 | text          | text          |
| No       |             | mailing_address_4 | Mailing Address 4 | text          | text          |
| Yes      | series tag  | legal_1           | Legal 1           | text          | text          |
| Yes      | series tag  | legal_2           | Legal 2           | text          | text          |
| Yes      | series tag  | legal_3           | Legal 3           | text          | text          |
| Yes      | series tag  | legal_4           | Legal 4           | text          | text          |
| Yes      | series tag  | legal_5           | Legal 5           | text          | text          |
| Yes      | series tag  | legal_6           | Legal 6           | text          | text          |
| Yes      | series tag  | legal_7           | Legal 7           | text          | text          |
| Yes      | series tag  | legal_8           | Legal 8           | text          | text          |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fee_date,expiration_date,mailing_address_1,mailing_address_2,mailing_address_3,mailing_address_4
```

## Data Commands

```ls
series e:hbmv-rqk9 d:2017-07-01T00:00:00.000Z t:license_type=RBD t:phone_number=6602160553 t:zip_code=63501 t:license_number=7 t:street="S BALTIMORE" t:state=MO t:fee_type=REN t:current_status=ACT t:city=KIRKSVILLE t:first_name=FRANK t:licensee_name="EL KADIR SHRINE ASSN. INC." t:legal_2="2401 SOUTH BALTIMORE, KIRKSVILLE, MO." t:legal_1="ALL OF A ONE STORY BRICK BUILDING, ON EAST SIDE OF HIGHWAY 63 SOUTH," t:county=ADAIR t:last_name=WAYMAN t:street_number=2401 t:district=2 t:subdistrict=00 m:row_number.hbmv-rqk9=1

series e:hbmv-rqk9 d:2017-07-01T00:00:00.000Z t:phone_number=5735810028 t:license_type=COL t:zip_code=65265 t:license_number=135 t:street="HWY 15 NORTH" t:state=MO t:fee_type=REN t:dba_name="JOHN J. DILLON KC CLUB" t:current_status=ACT t:city=MEXICO t:first_name=DENNIS t:licensee_name="KNIGHTS OF COLUMBUS" t:legal_2="OF MEXICO, MO." t:legal_1="ONE STORY BRICK AND METAL BUILDING, ON HIGHWAY 15, ONE MILE NORTH" t:county=AUDRAIN t:last_name=BECKER t:district=2 t:subdistrict=00 m:row_number.hbmv-rqk9=2

series e:hbmv-rqk9 d:2017-07-01T00:00:00.000Z t:license_type=OPL t:phone_number=4174762756 t:zip_code=657081852 t:license_number=219 t:street="E CLEVELAND AVE" t:state=MO t:fee_type=REN t:dba_name="STELL'S PACKAGE STORE" t:current_status=ACT t:city=MONETT t:first_name=JOYCE t:licensee_name="CANA INC." t:legal_2="STREET, HIGHWAY 60, CITY ROUTE, MONETT, MO." t:legal_1="ONE STORY CONCRETE BLOCK BUILDING AT THE INTERSECTION OF CLEVELAND" t:county=BARRY t:last_name=REISER t:street_number=1305 t:district=5 t:subdistrict=00 m:row_number.hbmv-rqk9=3
```

## Meta Commands

```ls
metric m:row_number.hbmv-rqk9 p:long l:"Row Number"

entity e:hbmv-rqk9 l:"County Clerk License Information" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/hbmv-rqk9

property e:hbmv-rqk9 t:meta.view v:id=hbmv-rqk9 v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="County Clerk License Information" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:hbmv-rqk9 t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:hbmv-rqk9 t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| license_number | licensee_name                | dba_name                        | license_type | current_status | effective_date      | fee_date            | fee_type | expiration_date     | business_phone     | manager_phone      | first_name | last_name | district | subdistrict | county   | street_number | street          | city       | state | zip_code  | mailing_address_1           | mailing_address_2      | mailing_address_3        | mailing_address_4       | legal_1                                                               | legal_2                                                 | legal_3       | legal_4 | legal_5 | legal_6 | legal_7 | legal_8 | 
| ============== | ============================ | =============================== | ============ | ============== | =================== | =================== | ======== | =================== | ================== | ================== | ========== | ========= | ======== | =========== | ======== | ============= | =============== | ========== | ===== | ========= | =========================== | ====================== | ======================== | ======================= | ===================================================================== | ======================================================= | ============= | ======= | ======= | ======= | ======= | ======= | 
| 7              | EL KADIR SHRINE ASSN. INC.   |                                 | RBD          | ACT            | 2017-07-01T00:00:00 | 2017-04-12T00:00:00 | REN      | 2018-06-30T00:00:00 | [6606653312, null] | [6602160553, null] | FRANK      | WAYMAN    | 2        | 00          | ADAIR    | 2401          | S BALTIMORE     | KIRKSVILLE | MO    | 63501     | EL KADIR SHRINE ASSN. INC.  | PO BOX 921             | KIRKSVILLE MO 63501-0921 |                         | ALL OF A ONE STORY BRICK BUILDING, ON EAST SIDE OF HIGHWAY 63 SOUTH,  | 2401 SOUTH BALTIMORE, KIRKSVILLE, MO.                   |               |         |         |         |         |         | 
| 135            | KNIGHTS OF COLUMBUS          | JOHN J. DILLON KC CLUB          | COL          | ACT            | 2017-07-01T00:00:00 | 2017-04-05T00:00:00 | REN      | 2018-06-30T00:00:00 | [5735811550, null] | [5735810028, null] | DENNIS     | BECKER    | 2        | 00          | AUDRAIN  |               | HWY 15 NORTH    | MEXICO     | MO    | 65265     | KNIGHTS OF COLUMBUS         | JOHN J. DILLON KC CLUB | PO BOX 425               | MEXICO MO 65265         | ONE STORY BRICK AND METAL BUILDING, ON HIGHWAY 15, ONE MILE NORTH     | OF MEXICO, MO.                                          |               |         |         |         |         |         | 
| 219            | CANA INC.                    | STELL'S PACKAGE STORE           | OPL          | ACT            | 2017-07-01T00:00:00 | 2017-04-14T00:00:00 | REN      | 2018-06-30T00:00:00 | [4172357949, null] | [4174762756, null] | JOYCE      | REISER    | 5        | 00          | BARRY    | 1305          | E CLEVELAND AVE | MONETT     | MO    | 657081852 |                             |                        |                          |                         | ONE STORY CONCRETE BLOCK BUILDING AT THE INTERSECTION OF CLEVELAND    | STREET, HIGHWAY 60, CITY ROUTE, MONETT, MO.             |               |         |         |         |         |         | 
| 294            | BOWERS, EMERY L. JR.         | BOWERS TOBACCO STORE            | OPL          | ACT            | 2017-07-01T00:00:00 | 2017-04-13T00:00:00 | REN      | 2018-06-30T00:00:00 | [6609253333, null] | [null, null]       |            |           | 5        | 00          | BATES    |               | MAIN STREET     | AMORET     | MO    | 64722     | BOWERS, EMERY L. JR.        | BOWERS TOBACCO STORE   | PO BOX 156               | AMORET MO 64722-0156    | ALL OF A ONE STORY METAL BUILDING, ON NORTH SIDE OF MAIN STREET,      | AMORET, MO.                                             |               |         |         |         |         |         | 
| 463            | COUNTRY CLUB OF MISSOURI     |                                 | RBD          | ACT            | 2017-07-01T00:00:00 | 2017-04-05T00:00:00 | REN      | 2018-06-30T00:00:00 | [5734497201, null] | [5732392563, null] | RODNEY     | NAGEL     | 2        | 00          | BOONE    | 1300          | WOODRAIL AVE    | COLUMBIA   | MO    | 652030920 |                             |                        |                          |                         | ALL OF A ONE STORY BRICK BUILDING, APPROXIMATELY 60X250 FEET,         | INCLUDING AN 18 HOLE GOLF COURSE, 1300 WOODRAIL AVENUE, | COLUMBIA, MO. |         |         |         |         |         | 
| 519            | COUNTRY CLUB OF MISSOURI     |                                 | SBD          | ACT            | 2017-07-01T00:00:00 | 2017-04-05T00:00:00 | REN      | 2018-06-30T00:00:00 | [5734497201, null] | [5732392563, null] | RODNEY     | NAGEL     | 2        | 00          | BOONE    | 1300          | WOODRAIL AVE    | COLUMBIA   | MO    | 652030920 |                             |                        |                          |                         |                                                                       |                                                         |               |         |         |         |         |         | 
| 546            | DILLON STORES DIVISION INC.  | GERBES SUPER MARKET #125        | OPL          | ACT            | 2017-04-12T00:00:00 |                     | MGR      | 2017-06-30T00:00:00 | [4178953000, null] | [5738199958, null] | CONNIE     | MAULLER   | 2        | 00          | BOONE    | 2900          | N PARIS ROAD    | COLUMBIA   | MO    | 65201     | DILLON STORES DIVISION INC. | DILLON STORE #125      | PO BOX 305103            | NASHVILLE TN 37230-5103 | ALL OF A ONE STORY ROCK BUILDING, KNOWN AS GERBES SUPER MARKET,       | 2900 NORTH PARIS ROAD, COLUMBIA, MO.                    |               |         |         |         |         |         | 
| 704            | FRATERNAL ORDER OF EAGLES 49 | AERIE 49                        | RBD          | ACT            | 2017-07-01T00:00:00 | 2017-04-05T00:00:00 | REN      | 2018-06-30T00:00:00 | [8162793014, null] | [8163514034, null] | VINCENT    | LEWIS     | 1        | 00          | BUCHANAN | 2004          | N BELT HWY      | ST JOSEPH  | MO    | 645062202 |                             |                        |                          |                         | ONE STORY CONCRETE BUILDING, 2004 NORTH BELT HIGHWAY, ST. JOSEPH, MO. |                                                         |               |         |         |         |         |         | 
| 817            | D & R FOODS INC.             | RAY'S GREEN HILLS #2            | OPL          | ACT            | 2017-07-01T00:00:00 | 2017-04-05T00:00:00 | REN      | 2018-06-30T00:00:00 | [8162335572, null] | [8162792398, null] | RAYMOND    | HEITMAN   | 1        | 00          | BUCHANAN | 3225          | BELT HWY NORTH  | ST JOSEPH  | MO    | 645061598 |                             |                        |                          |                         | ALL OF A CONCRETE BRICK BUILDING AND BASEMENT,                        | 3225 NORTH BELT HIGHWAY, ST. JOSEPH, MO.                |               |         |         |         |         |         | 
| 841            | R-J FOODS INC.               | ROGER'S GREEN HILLS SUPERMARKET | OPL          | ACT            | 2017-07-01T00:00:00 | 2017-04-12T00:00:00 | REN      | 2018-06-30T00:00:00 | [8162332885, null] | [8163907545, null] | JANIS      | ALLEN     | 1        | 00          | BUCHANAN | 1004          | 5TH AVENUE      | ST JOSEPH  | MO    | 645052111 |                             |                        |                          |                         | ALL OF A ONE STORY CONCRETE BUILDING, WITH NO BASEMENT, LOCATED AT    | 1004 FIFTH AVENUE, ST. JOSEPH, MO.                      |               |         |         |         |         |         | 
```