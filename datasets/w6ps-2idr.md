# Licensed Horse Stables Statewide

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-horse-stables-statewide-16fd6) |
| Metadata | [Link](https://data.maryland.gov/api/views/w6ps-2idr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/w6ps-2idr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/w6ps-2idr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | w6ps-2idr |
| Name | Licensed Horse Stables Statewide |
| Attribution | MD Department of Agriculture |
| Category | Agriculture |
| Tags | horses, stables, riding |
| Created | 2012-10-26T15:16:53Z |
| Publication Date | 2012-10-26T16:20:25Z |

## Description

This dataset shows all horse stables in Maryland which are licensed by the Maryland Department of Agriculture.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | time        | license_date    | LICENSE DATE    | calendar_date | calendar_date |
| Yes      | series tag  | license_number  | LICENSE NUMBER  | text          | number        |
| No       |             | expiration_year | EXPIRATION YEAR | number        | number        |
| Yes      | series tag  | stable_contact  | STABLE CONTACT  | text          | text          |
| Yes      | series tag  | stable_name     | STABLE NAME     | text          | text          |
| Yes      | series tag  | county          | COUNTY          | text          | text          |
| No       |             | mailing_address | MAILING ADDRESS | text          | text          |
| Yes      | series tag  | stable_phone    | STABLE PHONE    | text          | text          |
| Yes      | series tag  | day_phone       | DAY PHONE       | text          | text          |
| Yes      | series tag  | evening_phone   | EVENING PHONE   | text          | text          |
| Yes      | series tag  | boarding        | BOARDING        | text          | text          |
| Yes      | series tag  | sales           | SALES           | text          | text          |
| Yes      | series tag  | rental          | RENTAL          | text          | text          |
| Yes      | series tag  | instruction     | INSTRUCTION     | text          | text          |
| Yes      | series tag  | rescue          | RESCUE          | text          | text          |
| Yes      | series tag  | nutri_mang      | NUTRI_MANG      | text          | text          |
| Yes      | series tag  | website         | WEBSITE         | text          | text          |
| Yes      | series tag  | email           | EMAIL           | text          | text          |
| Yes      | series tag  | manager         | MANAGER         | text          | text          |
| Yes      | series tag  | manager_phone   | MANAGER PHONE   | text          | text          |
| Yes      | series tag  | summer_camps    | SUMMER CAMPS    | text          | text          |
| Yes      | series tag  | therapeutic     | THERAPEUTIC     | text          | text          |
| Yes      | series tag  | multi_purpose   | MULTI PURPOSE   | text          | text          |
| Yes      | series tag  | beginners       | BEGINNERS       | text          | text          |
| Yes      | series tag  | horse_share     | HORSE_SHARE     | text          | text          |
| Yes      | series tag  | western         | WESTERN         | text          | text          |
```

## Time Field

```ls
Value = license_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mailing_address,expiration_year
```

## Data Commands

```ls
series e:w6ps-2idr d:2012-07-26T00:00:00.000Z t:nutri_mang=Y t:county=CE t:email=reneeluther@netzero.com t:website=rollinghillsranch.org t:stable_name="ROLLING HILLS RANCH, LLC." t:stable_contact="RENEE S. LUTHER" t:license_number=475 t:boarding=Y t:instruction=Y t:stable_phone=410-378-3817 t:day_phone=410-378-3817 m:row_number.w6ps-2idr=1

series e:w6ps-2idr d:2012-05-01T00:00:00.000Z t:website=WWW.ROLLACRESSHOWSTABLES.COM t:license_number=37 t:stable_contact="JANICE P. NICHOLSON" t:stable_name="ROLLING ACRES FARM, INC." t:boarding=Y t:rental=Y t:stable_phone=301-774-4604 t:nutri_mang=Y t:county=MG t:email=pamsaul@verizon.net t:sales=Y t:instruction=Y t:day_phone=301-774-9269 m:row_number.w6ps-2idr=2

series e:w6ps-2idr d:2010-07-30T00:00:00.000Z t:nutri_mang=Y t:county=FR t:stable_name="PLEASANT FIELDS FARM" t:stable_contact="JOAN & CHIP RIDGELY" t:license_number=183 t:boarding=Y t:stable_phone=301-748-7330 t:day_phone=301-748-7330 m:row_number.w6ps-2idr=3
```

## Meta Commands

```ls
metric m:row_number.w6ps-2idr p:long l:"Row Number"

entity e:w6ps-2idr l:"Licensed Horse Stables Statewide" t:attribution="MD Department of Agriculture" t:url=https://data.maryland.gov/api/views/w6ps-2idr

property e:w6ps-2idr t:meta.view v:id=w6ps-2idr v:category=Agriculture v:attributionLink=http://www.mda.maryland.gov v:averageRating=0 v:name="Licensed Horse Stables Statewide" v:attribution="MD Department of Agriculture"

property e:w6ps-2idr t:meta.view.license v:name="Public Domain"

property e:w6ps-2idr t:meta.view.owner v:id=tpc4-inqc v:screenName="Lisa Stollof" v:displayName="Lisa Stollof"

property e:w6ps-2idr t:meta.view.tableauthor v:id=tpc4-inqc v:screenName="Lisa Stollof" v:roleName=editor v:displayName="Lisa Stollof"
```

## Top Records

```ls
| license_date        | license_number | expiration_year | stable_contact      | stable_name               | county | mailing_address                                 | stable_phone | day_phone    | evening_phone | boarding | sales | rental | instruction | rescue | nutri_mang | website                      | email                     | manager | manager_phone | summer_camps | therapeutic | multi_purpose | beginners | horse_share | western | 
| =================== | ============== | =============== | =================== | ========================= | ====== | =============================================== | ============ | ============ | ============= | ======== | ===== | ====== | =========== | ====== | ========== | ============================ | ========================= | ======= | ============= | ============ | =========== | ============= | ========= | =========== | ======= | 
| 2012-07-26T00:00:00 | 475            | 2013            | RENEE S. LUTHER     | ROLLING HILLS RANCH, LLC. | CE     |                                                 | 410-378-3817 | 410-378-3817 |               | Y        |       |        | Y           |        | Y          | rollinghillsranch.org        | reneeluther@netzero.com   |         |               |              |             |               |           |             |         | 
| 2012-05-01T00:00:00 | 37             | 2013            | JANICE P. NICHOLSON | ROLLING ACRES FARM, INC.  | MG     | MD                                              | 301-774-4604 | 301-774-9269 |               | Y        | Y     | Y      | Y           |        | Y          | WWW.ROLLACRESSHOWSTABLES.COM | pamsaul@verizon.net       |         |               |              |             |               |           |             |         | 
| 2010-07-30T00:00:00 | 183            | 2011            | JOAN & CHIP RIDGELY | PLEASANT FIELDS FARM      | FR     | MD                                              | 301-748-7330 | 301-748-7330 |               | Y        |       |        |             |        | Y          |                              |                           |         |               |              |             |               |           |             |         | 
| 2012-07-26T00:00:00 | 427            | 2013            | LISA BAILEY         | MILE AROUND FARM, INC.    | MG     | 3 VICTORIA CROSSING COURT GAITHERSBURG MD 20877 |              | 240-676-1377 | 240-676-1377  | Y        |       |        |             |        | Y          |                              |                           |         |               |              |             |               |           |             |         | 
| 2009-06-09T00:00:00 | 122            | 2010            | DIANNE POWERS       | BRENTWOOD STABLE          | FR     | PO BOX 4187 FREDERICK MD 21705                  | 301-473-7067 | 301-663-4000 | 301-473-8153  | Y        | Y     |        | N           |        | Y          |                              |                           |         |               |              |             |               |           |             |         | 
| 2009-01-14T00:00:00 | 542            | 2009            | ROBERT KARN         | SWEET CREEK FARM          | MG     | MD                                              |              | 301-972-0882 |               | Y        |       |        |             |        |            |                              |                           |         |               |              |             |               |           |             |         | 
| 2011-08-09T00:00:00 | 503            | 2012            | ASTRID DALLEY       | OATLAND STABLES, INC.     | MG     | 5120 BROOKEVILLE RD. GAITHERSBURG MD 20882      | 301-977-5558 | 301-977-5558 | 301-580-5055  | Y        | Y     |        | Y           |        | Y          |                              |                           |         |               |              |             |               |           |             |         | 
| 2009-06-18T00:00:00 | 285            | 2010            | SHERIE CASE         | FIVE O'CLOCK FARM, LLC    | MG     | MD                                              | 301-717-6471 |              | 301-482-1557  | Y        |       |        |             |        |            |                              |                           |         |               |              |             |               |           |             |         | 
| 2012-05-17T00:00:00 | 212            | 2013            | BECKY MATICIC       | DIAMOND'S BLUFF FARM      | CR     | MD                                              | 443-864-0940 | 443-864-0940 |               | Y        | Y     |        | Y           |        | Y          | www.diamondsbluff.com        | DIAMONDSBLUFF@VERIZON.NET |         |               |              |             |               |           |             |         | 
| 2012-05-17T00:00:00 | 139            | 2013            | MELINDA COHEN       | DREAM CATCHER FARM        | FR     |                                                 | 301-607-4238 |              |               | Y        | Y     |        | Y           |        | Y          | dreamcatcherfarm.net         | dcfarm@verizon.net        |         |               |              |             |               |           |             |         | 
```