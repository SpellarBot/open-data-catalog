# HCIDLA Affordable Housing Projects Catalog And Listing (2003 To Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hcidla-affordable-housing-projects-catalog-and-listing-2003-to-present-34f2f) |
| Metadata | [Link](https://data.lacity.org/api/views/u4mj-cwbz) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/u4mj-cwbz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/u4mj-cwbz/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | u4mj-cwbz |
| Name | HCIDLA Affordable Housing Projects Catalog And Listing (2003 To Present) |
| Attribution | LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT |
| Category | A Livable and Sustainable City |
| Tags | hcidla, hcidla ahtf projects, hcidla affordable housing |
| Created | 2014-05-28T17:13:30Z |
| Publication Date | 2014-05-29T16:40:03Z |

## Description

HCIDLA projects developed with money from the Affordable Housing Trust Fund beginning in 2003 to present.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | numeric metric | apn                     | APN                     | number    | number      |
| Yes      | series tag     | project_number          | PROJECT NUMBER          | text      | text        |
| Yes      | series tag     | name                    | NAME                    | text      | text        |
| No       |                | ahtf_pa                 | ADDRESS                 | text      | text        |
| Yes      | numeric metric | site_cd                 | SITE_CD                 | number    | number      |
| Yes      | series tag     | community               | COMMUNITY               | text      | text        |
| Yes      | series tag     | council_district        | COUNCIL DISTRICT        | text      | number      |
| Yes      | series tag     | development_stage       | DEVELOPMENT STAGE       | text      | text        |
| Yes      | series tag     | construction_type       | CONSTRUCTION TYPE       | text      | text        |
| Yes      | numeric metric | units                   | UNITS                   | number    | number      |
| Yes      | series tag     | status_in_hims          | STATUS IN HIMS          | text      | text        |
| Yes      | numeric metric | of_funds_used           | (%) OF FUNDS USED       | percent   | percent     |
| Yes      | series tag     | housing_type            | HOUSING TYPE            | text      | text        |
| Yes      | numeric metric | hcidla_funded           | HCIDLA FUNDED           | money     | money       |
| Yes      | numeric metric | leverage                | LEVERAGE                | money     | money       |
| Yes      | numeric metric | tax_exempt_conduit_bond | TAX EXEMPT CONDUIT BOND | money     | money       |
| Yes      | numeric metric | tdc                     | TDC                     | money     | money       |
| Yes      | series tag     | photo                   | PHOTO                   | url       | url         |
| Yes      | numeric metric | jobs                    | JOBS                    | number    | number      |
| Yes      | series tag     | developer               | DEVELOPER               | text      | text        |
| Yes      | numeric metric | finish_date_year        | FINISH DATE(YEAR)       | number    | number      |
| Yes      | series tag     | management_company      | MANAGEMENT COMPANY      | text      | text        |
| Yes      | series tag     | contact_phone           | CONTACT PHONE           | text      | text        |
| No       |                | date_stamp              | DATE_STAMP              | text      | text        |
| No       |                | xcoord                  | LONGITUDE               | number    | number      |
| No       |                | ycoord                  | LATITUDE                | number    | number      |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = ahtf_pa,date_stamp,xcoord,ycoord
```

## Data Commands

```ls
series e:u4mj-cwbz d:2003-01-01T00:00:00.000Z t:development_stage=COMPLETED t:developer="NEIGHBORHOOD EFFORT," t:management_company="THE EBERLY COMPANY" t:name="HISTORIC BARBIZON HOTEL APTS." t:construction_type=REHAB t:contact_phone="(323) 937-6468" t:community=WESTLAKE t:project_number=000111 t:council_district=1 t:status_in_hims=COMPLETED t:photo=http://hcidapp.lacity.org/mpphotos/000111/Photo/Website/CD_1_-_Barbizon_Hotel.png t:housing_type=FAMILY m:hcidla_funded=5009394 m:of_funds_used=100 m:jobs=47 m:site_cd=1 m:tax_exempt_conduit_bond=0 m:tdc=18945208 m:leverage=13935814 m:apn=5154026023 m:finish_date_year=2008 m:units=51

series e:u4mj-cwbz d:2003-01-01T00:00:00.000Z t:development_stage=COMPLETED t:developer="HERMANDAD LA ECONOMICS AND COMMUNITY DEV CORP," t:management_company="SOLARI ENTERPRISES, INC." t:name="COLONIA CORONA APTS. (CSP I)" t:construction_type="NEW CONSTRUCTION" t:contact_phone="(714) 282-2520" t:community="VALLEY GLEN" t:project_number=000115 t:council_district=2 t:status_in_hims=COMPLETED t:photo=http://hcidapp.lacity.org/mpphotos/000115/Photo/Website/CD%202%20-%20Colonia%20Corona.JPG t:housing_type=FAMILY m:hcidla_funded=10527004 m:of_funds_used=100 m:jobs=146 m:site_cd=1 m:tax_exempt_conduit_bond=2918726 m:tdc=19280817 m:leverage=5835087 m:apn=2327017034 m:finish_date_year=2005 m:units=100

series e:u4mj-cwbz d:2003-01-01T00:00:00.000Z t:development_stage=COMPLETED t:developer="NEW ECONOMICS FOR WOMEN," t:management_company="NEW CAPITAL LLC" t:name="TIERRA DEL SOL" t:construction_type="NEW CONSTRUCTION" t:contact_phone="(818) 887-6920" t:community="CANOGA PARK" t:project_number=000124 t:council_district=3 t:status_in_hims=COMPLETED t:photo=http://hcidapp.lacity.org/mpphotos/000124/Photo/Website/CD%203%20-%20Tierra%20Del%20Sol%20-%20000124.jpg t:housing_type="LARGE FAMILY / WAIVER REQUIRED" m:hcidla_funded=8125000 m:of_funds_used=100 m:jobs=169 m:site_cd=1 m:tax_exempt_conduit_bond=2103714 m:tdc=25386893 m:leverage=15158179 m:apn=2111005034 m:finish_date_year=2003 m:units=119
```

## Meta Commands

```ls
metric m:apn p:long l:APN t:dataTypeName=number

metric m:site_cd p:integer l:SITE_CD t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:of_funds_used p:integer l:"(%) OF FUNDS USED" t:dataTypeName=percent

metric m:hcidla_funded p:integer l:"HCIDLA FUNDED" t:dataTypeName=money

metric m:leverage p:integer l:LEVERAGE t:dataTypeName=money

metric m:tax_exempt_conduit_bond p:integer l:"TAX EXEMPT CONDUIT BOND" t:dataTypeName=money

metric m:tdc p:integer l:TDC t:dataTypeName=money

metric m:jobs p:integer l:JOBS t:dataTypeName=number

metric m:finish_date_year p:integer l:"FINISH DATE(YEAR)" t:dataTypeName=number

entity e:u4mj-cwbz l:"HCIDLA Affordable Housing Projects Catalog And Listing (2003 To Present)" t:attribution="LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT" t:url=https://data.lacity.org/api/views/u4mj-cwbz

property e:u4mj-cwbz t:meta.view v:id=u4mj-cwbz v:category="A Livable and Sustainable City" v:attributionLink=http://www.hcidla.org v:averageRating=0 v:name="HCIDLA Affordable Housing Projects Catalog And Listing (2003 To Present)" v:attribution="LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT"

property e:u4mj-cwbz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:u4mj-cwbz t:meta.view.owner v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"

property e:u4mj-cwbz t:meta.view.tableauthor v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"
```

## Top Records

```ls
| apn        | project_number | name                                            | ahtf_pa                           | site_cd | community          | council_district | development_stage | construction_type | units | status_in_hims | of_funds_used | housing_type                                  | hcidla_funded | leverage | tax_exempt_conduit_bond | tdc      | photo                                                                                                                                | jobs | developer                                      | finish_date_year | management_company                      | contact_phone       | date_stamp         | xcoord         | ycoord       | 
| ========== | ============== | =============================================== | ================================= | ======= | ================== | ================ | ================= | ================= | ===== | ============== | ============= | ============================================= | ============= | ======== | ======================= | ======== | ==================================================================================================================================== | ==== | ============================================== | ================ | ======================================= | =================== | ================== | ============== | ============ | 
| 5154026023 | 000111         | HISTORIC BARBIZON HOTEL APTS.                   | 1927 W 6TH ST 1-51 CA 90057       | 1       | WESTLAKE           | 1                | COMPLETED         | REHAB             | 51    | COMPLETED      | 100           | FAMILY                                        | 5009394       | 13935814 | 0                       | 18945208 | [http://hcidapp.lacity.org/mpphotos/000111/Photo/Website/CD_1_-_Barbizon_Hotel.png, null]                                            | 47   | NEIGHBORHOOD EFFORT,                           | 2008             | THE EBERLY COMPANY                      | (323) 937-6468      | Nov 30 2015 5:25AM | -118.273227219 | 34.058957806 | 
| 2327017034 | 000115         | COLONIA CORONA APTS. (CSP I)                    | 13044 W SHERMAN WAY CA 91605      | 1       | VALLEY GLEN        | 2                | COMPLETED         | NEW CONSTRUCTION  | 100   | COMPLETED      | 100           | FAMILY                                        | 10527004      | 5835087  | 2918726                 | 19280817 | [http://hcidapp.lacity.org/mpphotos/000115/Photo/Website/CD%202%20-%20Colonia%20Corona.JPG, null]                                    | 146  | HERMANDAD LA ECONOMICS AND COMMUNITY DEV CORP, | 2005             | SOLARI ENTERPRISES, INC.                | (714) 282-2520      | Nov 30 2015 5:25AM | -118.417627842 | 34.201029003 | 
| 2111005034 | 000124         | TIERRA DEL SOL                                  | 7500 N ALABAMA AVE 1-119 CA 91303 | 1       | CANOGA PARK        | 3                | COMPLETED         | NEW CONSTRUCTION  | 119   | COMPLETED      | 100           | LARGE FAMILY / WAIVER REQUIRED                | 8125000       | 15158179 | 2103714                 | 25386893 | [http://hcidapp.lacity.org/mpphotos/000124/Photo/Website/CD%203%20-%20Tierra%20Del%20Sol%20-%20000124.jpg, null]                     | 169  | NEW ECONOMICS FOR WOMEN,                       | 2003             | NEW CAPITAL LLC                         | (818) 887-6920      | Nov 30 2015 5:25AM | -118.598286345 | 34.208140908 | 
| 5422020031 | 000156         | ALLESANDRO STREET APTS.                         | 1934 N ALLESANDRO ST CA 90039     | 1       | ECHO PARK          | 13               | COMPLETED         | NEW CONSTRUCTION  | 18    | COMPLETED      | 100           | SPECIAL NEEDS / HIV/AIDS INDIVIDUALS/FAMILIES | 620900        | 3037101  | 0                       | 3658001  | [http://hcidapp.lacity.org/mpphotos/000156/Photo/Website/CD%2013%20-%20Allesandro%20St.%20Apts..jpg, null]                           | 29   | HOLLYWOOD COMMUNITY HOUSING CORP.,             | 2005             | BARKER MANAGEMENT INCORPORATED          | (714) 533-3450      | Nov 30 2015 5:25AM | -118.257500077 | 34.091310368 | 
| 5110027025 | 010113         | BROADWAY VILLAGE II                             | 5101 S BROADWAY 1-50 CA 90037     | 1       | SOUTH PARK         | 9                | COMPLETED         | NEW CONSTRUCTION  | 50    | COMPLETED      | 100           | FAMILY                                        | 1987378       | 10017311 | 0                       | 12004689 | [http://hcidapp.lacity.org/mpphotos/010113/Photo/Website/CD_9_-_Broadway_Village_II_-_010113[1].png, null]                           | 53   | BEYOND SHELTER HOUSING,                        | 2006             | WNC & ASSOCIATES, INC.                  | (213) 251-2111      | Nov 30 2015 5:25AM | -118.278625635 | 33.996336098 | 
| 2654010001 | 010139         | COLUMBUS TRANSITIONAL HSG & PENNY LANE          | 15256 W ACRE ST CA 91343          | 1       | NORTH HILLS        | 6                | COMPLETED         | REHAB             | 4     | COMPLETED      | 100           | SPECIAL NEEDS                                 | 532500        | 666519   | 0                       | 1199019  | [http://hcidapp.lacity.org/mpphotos/010139/Photo/Website/CD%207%20-%20Columbus%20Transitional%2015257%20acre%20-%20010139.JPG, null] | 7    | NATIONAL FOUNDATION FOR ... (AKA PENNY LANE),  | 2003             | PENNY LANE TRANSITIONAL HOUSING PROGRAM | (818) 892-3423      | Nov 30 2015 5:25AM | -118.465337052 | 34.229852396 | 
| 2654009012 | 010139         | COLUMBUS TRANSITIONAL HSG & PENNY LANE (SITE 2) | 15259 W GRESHAM ST CA 91343       | 2       | NORTH HILLS        | 6                | COMPLETED         | REHAB             | 4     | COMPLETED      | 100           | SPECIAL NEEDS                                 | 532500        | 666519   | 0                       | 1199019  | [http://hcidapp.lacity.org/mpphotos/010139/Photo/Website%20Site2/Columbust%20Transition%20Site%202.png, null]                        | 7    | NATIONAL FOUNDATION FOR ... (AKA PENNY LANE),  | 2003             | PENNY LANE TRANSITIONAL HOUSING PROGRAM | (818) 892-3423      | Nov 30 2015 5:25AM | -118.465325782 | 34.231033956 | 
| 5148025025 | 010315         | YANKEE HOTEL                                    | 501 E 7TH ST CA 90014             | 1       | WHOLESALE DISTRICT | 14               | COMPLETED         | REHAB             | 80    | COMPLETED      | 100           | SPECIAL NEEDS                                 | 2019320       | 8432786  | 0                       | 10452106 | [http://hcidapp.lacity.org/mpphotos/010315/Photo/Website/CD%209%20-%20The%20Yankee%20Hotel.jpg, null]                                | 75   | SRO HOUSING CORPORTATION,                      | 2005             | SRO HOUSING CORPORATION                 | (213) 229-9641      | Nov 30 2015 5:25AM | -118.2471476   | 34.041155985 | 
| 5156018011 | 020093         | ST. ANNE'S TRANSITIONAL HOUSING                 | 155 N OCCIDENTAL BLVD CA 90026    | 1       | TEMPLE-BEAUDRY     | 13               | COMPLETED         | NEW CONSTRUCTION  | 40    | COMPLETED      | 100           | SPECIAL NEEDS / FOSTER YOUTH                  | 2000000       | 8758249  | 0                       | 10758249 | [http://hcidapp.lacity.org/mpphotos/020093/Photo/Website/CD_13_-_St._Anne's_Transitional%202.png, null]                              | 65   | ST. ANNE'S TRANSITIONAL HOUSING,               | 2005             | ST. ANNE'S TRANSITIONAL HOUSING         | (213) 381-2931      | Nov 30 2015 5:25AM | -118.27894062  | 34.071697454 | 
| 2210027012 | 020206         | SATICOY GARDENS                                 | 14649 W SATICOY ST CA 91405       | 1       | VAN NUYS           | 6                | COMPLETED         | NEW CONSTRUCTION  | 30    | COMPLETED      | 100           | LARGE FAMILY / WAIVER REQUIRED                | 2003000       | 4126190  | 1100000                 | 7229190  | [http://hcidapp.lacity.org/mpphotos/020206/Photo/Website/CD%206%20-%20Saticoy%20Gardens%20Apts..jpg, null]                           | 45   | LA FAMILY HOUSING CORP.,                       | 2006             | THE JOHN STEWART COMPANY                | (213) 833-1860 x203 | Nov 30 2015 5:25AM | -118.452638942 | 34.209240247 | 
```