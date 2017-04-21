# Mobile Vendors Active

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mobile-vendors-active) |
| Metadata | [Link](https://data.hartford.gov/api/views/gab7-hi8g) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/gab7-hi8g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/gab7-hi8g/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | gab7-hi8g |
| Name | Mobile Vendors Active |
| Attribution | City of Hartford |
| Category | Public Health |
| Tags | mobile, vendor, food, health, hartford, ct |
| Created | 2015-05-12T18:08:43Z |
| Publication Date | 2015-05-20T18:27:51Z |

## Description

This dataset is a listing of the current mobile food vendors that have licenses in the City. Updated nightly

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | blms_id             | blms_id             | text      | text        |
| Yes      | series tag  | dba                 | DBA                 | text      | text        |
| Yes      | series tag  | vendor_food_class   | Vendor Food Class   | text      | text        |
| Yes      | time        | license_issue_date  | License Issue Date  | date      | date        |
| No       |             | license_expire_date | License Expire Date | date      | date        |
| No       |             | last_license_date   | Last License Date   | date      | date        |
| No       |             | first_license_date  | First License Date  | date      | date        |
| Yes      | series tag  | owner_name          | Owner Name          | text      | text        |
| No       |             | address1            | Address1            | text      | text        |
| No       |             | address2            | Address2            | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | zip                 | Zip                 | text      | text        |
```

## Time Field

```ls
Value = license_issue_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = license_expire_date,last_license_date,first_license_date,address1,address2
```

## Data Commands

```ls
series e:gab7-hi8g d:2014-07-01T00:00:00.000Z t:zip=06066 t:owner_name="BASSETT DOUG & DONNA" t:blms_id=16757 t:dba="BEYOND BURGERS" t:state=CT t:vendor_food_class="MOBILE FOOD VENDOR CLASS 4" t:city="VERNON ROCKVILLE" m:row_number.gab7-hi8g=1

series e:gab7-hi8g d:2014-07-01T00:00:00.000Z t:zip=06112 t:owner_name="GONZALEZ JESUS" t:blms_id=16242 t:dba="HAPPY LUNCH CART" t:state=CT t:vendor_food_class="MOBILE FOOD VENDOR CLASS 4" t:city=HARTFORD m:row_number.gab7-hi8g=2

series e:gab7-hi8g d:2014-07-01T00:00:00.000Z t:zip=06114 t:owner_name="FLORES JUAN C" t:blms_id=16324 t:dba="MUNCHIES HOT DOG" t:state=CT t:vendor_food_class="MOBILE FOOD VENDOR CLASS 2" t:city=HARTFORD m:row_number.gab7-hi8g=3
```

## Meta Commands

```ls
metric m:row_number.gab7-hi8g p:long l:"Row Number"

entity e:gab7-hi8g l:"Mobile Vendors Active" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/gab7-hi8g

property e:gab7-hi8g t:meta.view v:id=gab7-hi8g v:category="Public Health" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Mobile Vendors Active" v:attribution="City of Hartford"

property e:gab7-hi8g t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gab7-hi8g t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:gab7-hi8g t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| blms_id | dba                         | vendor_food_class          | license_issue_date | license_expire_date | last_license_date | first_license_date | owner_name           | address1                  | address2 | city             | state | zip        | 
| ======= | =========================== | ========================== | ================== | =================== | ================= | ================== | ==================== | ========================= | ======== | ================ | ===== | ========== | 
| 16757   | BEYOND BURGERS              | MOBILE FOOD VENDOR CLASS 4 | 1404172800         | 1435622400          | 1435708800        | 1426032000         | BASSETT DOUG & DONNA | 53 HAYES DR               |          | VERNON ROCKVILLE | CT    | 06066      | 
| 16242   | HAPPY LUNCH CART            | MOBILE FOOD VENDOR CLASS 4 | 1404172800         | 1435622400          | 1435708800        | 1397174400         | GONZALEZ JESUS       | 20 ROCKVILLE ST APT 16B   |          | HARTFORD         | CT    | 06112      | 
| 16324   | MUNCHIES HOT DOG            | MOBILE FOOD VENDOR CLASS 2 | 1404172800         | 1435622400          | 1404172800        | 1399852800         | FLORES JUAN C        | 29 ANNAWAN ST APT F-2     |          | HARTFORD         | CT    | 06114      | 
| 14824   | A TASTE OF K. J.            | MOBILE FOOD VENDOR CLASS 3 | 1404172800         | 1435622400          | 1435708800        | 1313452800         | FOSTER, SR. KERRY B  | 52 CLARK ST               |          | HARTFORD         | CT    | 06120      | 
| 14898   | DI DI'S DOGS                | MOBILE FOOD VENDOR CLASS 3 | 1404172800         | 1435622400          | 1435708800        | 1316563200         | AUGER DIANE S        | 89 BOULANGER AV           |          | W HARTFORD       | CT    | 06110-1104 | 
| 15217   | FRANK ON WHEELS             | MOBILE FOOD VENDOR CLASS 4 | 1404172800         | 1435622400          | 1435708800        | 1338422400         | POLANCO FRANK        | 118 HUNGERFORD ST         |          | HARTFORD         | CT    | 06106      | 
| 15486   | JOHNNY'S PLACE              | MOBILE FOOD VENDOR CLASS 4 | 1404172800         | 1435622400          | 1435708800        | 1351728000         | SEPULVEDA JOHNNY     | 214 CAMPFIELD AV          |          | HARTFORD         | CT    | 06114      | 
| 15374   | CARIBBEAN FOOD CONCEPTS LLC | MOBILE FOOD VENDOR CLASS 3 | 1404172800         | 1435622400          | 1435708800        | 1344988800         | MYLES ADRIAN O       | 1028 BOULEVARD, SUITE 332 |          | WEST HARTFORD    | CT    | 06119      | 
| 15391   | TROPICAL GRILL AND CATERING | MOBILE FOOD VENDOR CLASS 3 | 1404172800         | 1435622400          | 1435708800        | 1346112000         | SAMUELS NOREEN       | 422 W WOLCOTT AV          |          | WINDSOR          | CT    | 06095      | 
| 16359   | FAT FREDDIES HOT DOGS       | MOBILE FOOD VENDOR CLASS 4 | 1404172800         | 1435622400          | 1435708800        | 1401235200         | SANTIAGO WILFREDO    | 34 CAMPFIELD AV           |          | HARTFORD         | CT    | 06114      | 
```