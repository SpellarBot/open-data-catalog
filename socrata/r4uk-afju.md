# Listing of All Businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/listing-of-all-businesses) |
| Metadata | [Link](https://data.lacity.org/api/views/r4uk-afju) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/r4uk-afju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/r4uk-afju/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | r4uk-afju |
| Name | Listing of All Businesses |
| Attribution | Office of Finance |
| Category | A Prosperous City |
| Created | 2016-01-11T21:53:56Z |
| Publication Date | 2016-01-12T21:22:45Z |

## Description

Listing of all (active and inactive) businesses registered with the Office of Finance. An "active" business is defined as a registered business whose owner has not notified the Office of Finance of a cease of business operations. Update Interval: Monthly.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | location_account          | LOCATION ACCOUNT #        | text          | text          |
| Yes      | series tag     | business_name             | BUSINESS NAME             | text          | text          |
| Yes      | series tag     | dba_name                  | DBA NAME                  | text          | text          |
| Yes      | series tag     | street_address            | STREET ADDRESS            | text          | text          |
| Yes      | series tag     | city                      | CITY                      | text          | text          |
| Yes      | series tag     | zip_code                  | ZIP CODE                  | text          | text          |
| Yes      | series tag     | location_description      | LOCATION DESCRIPTION      | text          | text          |
| No       |                | mailing_address           | MAILING ADDRESS           | text          | text          |
| Yes      | series tag     | mailing_city              | MAILING CITY              | text          | text          |
| Yes      | series tag     | mailing_zip_code          | MAILING ZIP CODE          | text          | text          |
| Yes      | numeric metric | naics                     | NAICS                     | number        | number        |
| Yes      | series tag     | primary_naics_description | PRIMARY NAICS DESCRIPTION | text          | text          |
| Yes      | series tag     | council_district          | COUNCIL DISTRICT          | text          | number        |
| Yes      | time           | location_start_date       | LOCATION START DATE       | calendar_date | calendar_date |
| No       |                | location_end_date         | LOCATION END DATE         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = location_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mailing_address,location_end_date
```

## Data Commands

```ls
series e:r4uk-afju d:1991-05-15T00:00:00.000Z t:business_name="PALACE OF VENICE GUEST HOME /C" t:primary_naics_description="Rooming & boarding houses" t:zip_code=90019-6037 t:council_district=10 t:location_account=0000000108-0001-3 t:location_description="1727 CRENSHAW 90019-6037" t:street_address="1727 CRENSHAW BLVD" t:city="LOS ANGELES" m:naics=721310

series e:r4uk-afju d:1990-01-01T00:00:00.000Z t:business_name="VINCENZO LABELLA" t:primary_naics_description="Travel arrangement & reservation services" t:zip_code=90272-4350 t:council_district=11 t:mailing_city="PACIFIC PALISADES" t:location_account=0000000115-0001-3 t:location_description="521 SWARTHMORE 90272-4350" t:street_address="521 SWARTHMORE AVENUE" t:mailing_zip_code=90272-4350 t:city="PACIFIC PALISADES" m:naics=561500

series e:r4uk-afju d:1999-01-01T00:00:00.000Z t:business_name="WILCARE ECONOMIC DEVELOPMENT CORPORATION" t:primary_naics_description="Rooming & boarding houses" t:zip_code=90003-4805 t:council_district=8 t:mailing_city="LOS ANGELES" t:location_account=0000000121-0001-9 t:location_description="9911 AVALON 90003-4805" t:street_address="9911 AVALON BLVD" t:mailing_zip_code=90003-4804 t:city="LOS ANGELES" m:naics=721310
```

## Meta Commands

```ls
metric m:naics p:integer l:NAICS d:"The self-reported North American Industry Classification System (NAICS) code, which is used in classifying business establishments." t:dataTypeName=number

entity e:r4uk-afju l:"Listing of All Businesses" t:attribution="Office of Finance" t:url=https://data.lacity.org/api/views/r4uk-afju

property e:r4uk-afju t:meta.view v:id=r4uk-afju v:category="A Prosperous City" v:averageRating=0 v:name="Listing of All Businesses" v:attribution="Office of Finance"

property e:r4uk-afju t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:r4uk-afju t:meta.view.owner v:id=c255-4shb v:profileImageUrlMedium=/api/users/c255-4shb/profile_images/THUMB v:profileImageUrlLarge=/api/users/c255-4shb/profile_images/LARGE v:screenName="Office of Finance OpenData" v:profileImageUrlSmall=/api/users/c255-4shb/profile_images/TINY v:displayName="Office of Finance OpenData"

property e:r4uk-afju t:meta.view.tableauthor v:id=c255-4shb v:profileImageUrlMedium=/api/users/c255-4shb/profile_images/THUMB v:profileImageUrlLarge=/api/users/c255-4shb/profile_images/LARGE v:screenName="Office of Finance OpenData" v:profileImageUrlSmall=/api/users/c255-4shb/profile_images/TINY v:roleName=publisher v:displayName="Office of Finance OpenData"
```

## Top Records

```ls
| location_account  | business_name                                                  | dba_name | street_address                         | city              | zip_code   | location_description      | mailing_address       | mailing_city      | mailing_zip_code | naics  | primary_naics_description                 | council_district | location_start_date | location_end_date   | 
| ================= | ============================================================== | ======== | ====================================== | ================= | ========== | ========================= | ===================== | ================= | ================ | ====== | ========================================= | ================ | =================== | =================== | 
| 0000000101-0001-1 | ETON PARTNERS                                                  |          | 7238 ETON AVENUE                       | CANOGA PARK       | 91303-1505 | 7238 ETON 91303-1505      |                       |                   |                  |        |                                           | 3                | 2002-08-05T00:00:00 | 2004-08-01T00:00:00 | 
| 0000000103-0001-1 | MANJEET KAUR                                                   |          | 7555 CLAIRE AVENUE                     | RESEDA            | 91335-2543 | 7555 CLAIRE 91335-2543    |                       |                   |                  |        |                                           | 3                | 2001-04-15T00:00:00 | 2004-12-31T00:00:00 | 
| 0000000104-0001-5 | THR CHRYSALIS PROJECT/C                                        |          | 617 S MESA STREET                      | SAN PEDRO         | 90731-2633 | 617 MESA 90731-2633       |                       |                   |                  |        |                                           | 15               | 2000-05-01T00:00:00 | 2008-12-31T00:00:00 | 
| 0000000108-0001-3 | PALACE OF VENICE GUEST HOME /C                                 |          | 1727 CRENSHAW BLVD                     | LOS ANGELES       | 90019-6037 | 1727 CRENSHAW 90019-6037  |                       |                   |                  | 721310 | Rooming & boarding houses                 | 10               | 1991-05-15T00:00:00 |                     | 
| 0000000115-0001-3 | VINCENZO LABELLA                                               |          | 521 SWARTHMORE AVENUE                  | PACIFIC PALISADES | 90272-4350 | 521 SWARTHMORE 90272-4350 | 521 SWARTHMORE AVENUE | PACIFIC PALISADES | 90272-4350       | 561500 | Travel arrangement & reservation services | 11               | 1990-01-01T00:00:00 |                     | 
| 0000000121-0001-9 | WILCARE ECONOMIC DEVELOPMENT CORPORATION                       |          | 9911 AVALON BLVD                       | LOS ANGELES       | 90003-4805 | 9911 AVALON 90003-4805    | 448 E 99TH STREET     | LOS ANGELES       | 90003-4804       | 721310 | Rooming & boarding houses                 | 8                | 1999-01-01T00:00:00 |                     | 
| 0000000123-0001-8 | ANDREI GUBOVICI                                                |          | 23244 SYLVAN STREET                    | WOODLAND HILLS    | 91367-1523 | 23244 SYLVAN 91367-1523   |                       |                   |                  |        |                                           | 3                | 1998-11-10T00:00:00 | 2003-11-30T00:00:00 | 
| 0000000124-0001-2 | DOUGLAS GREER CARROLL                                          |          | 6520 PLATT AVENUE POST OFFICE BOX #667 | WEST HILLS        | 91307-3218 | 6520 PLATT 91307-3218     |                       |                   |                  |        |                                           | 12               | 2003-02-17T00:00:00 | 2006-12-31T00:00:00 | 
| 0000000126-0001-1 | PAULA PLATOFF                                                  |          | 3314 BERRY DRIVE                       | STUDIO CITY       | 91604-4150 | 3314 BERRY 91604-4150     |                       |                   |                  |        |                                           | 2                | 1974-01-01T00:00:00 | 2005-01-01T00:00:00 | 
| 0000000128-0001-1 | KASIDIT SUWANTAMEY/SUPITRA SUPAPANASINKAS EM/CHALIN LEET RAKUL |          | 12643 SHERMAN WAY #D                   | N HOLLYWOOD       | 91605-5271 | 12643 SHERMAN 91605-5271  |                       |                   |                  |        |                                           | 2                | 1992-02-01T00:00:00 | 2010-01-15T00:00:00 | 
```