# Listing of Active Businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/listing-of-active-businesses) |
| Metadata | [Link](https://data.lacity.org/api/views/6rrh-rzua) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/6rrh-rzua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/6rrh-rzua/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 6rrh-rzua |
| Name | Listing of Active Businesses |
| Attribution | Office of Finance |
| Category | A Prosperous City |
| Created | 2014-05-21T17:21:35Z |
| Publication Date | 2016-01-11T18:44:17Z |

## Description

Listing of all active businesses currently registered with the Office of Finance. An "active" business is defined as a registered business whose owner has not notified the Office of Finance of a cease of business operations. Update Interval: Monthly.

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
| Yes      | numeric metric | naics                     | NAICS                     | number        | text          |
| Yes      | series tag     | primary_naics_description | PRIMARY NAICS DESCRIPTION | text          | text          |
| Yes      | series tag     | council_district          | COUNCIL DISTRICT          | text          | number        |
| Yes      | time           | location_start_date       | LOCATION START DATE       | calendar_date | calendar_date |
| No       |                | location_end_date         | LOCATION END DATE         | text          | text          |
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
series e:6rrh-rzua d:1990-01-01T00:00:00.000Z t:business_name="VINCENZO LABELLA" t:primary_naics_description="Travel arrangement & reservation services" t:zip_code=90272-4350 t:council_district=11 t:mailing_city="PACIFIC PALISADES" t:location_account=0000000115-0001-3 t:location_description="521 SWARTHMORE 90272-4350" t:street_address="521 SWARTHMORE AVENUE" t:mailing_zip_code=90272-4350 t:city="PACIFIC PALISADES" m:naics=561500

series e:6rrh-rzua d:1991-01-01T00:00:00.000Z t:business_name="A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C" t:primary_naics_description="Educational services (including schools, colleges, & universities)" t:zip_code=90026-4913 t:council_district=13 t:mailing_city="LOS ANGELES" t:location_account=0000000150-0001-5 t:location_description="2015 TEMPLE 90026-4913" t:street_address="2015 W TEMPLE STREET" t:mailing_zip_code=90007-2129 t:city="LOS ANGELES" m:naics=611000

series e:6rrh-rzua d:1999-02-01T00:00:00.000Z t:business_name="SPRINGBOARD NON-PROFIT CONSUMER CREDIT MANAGEMENT" t:primary_naics_description="Other financial investment activities (including investment advice)" t:zip_code=90015-3828 t:council_district=1 t:location_account=0000000156-0001-2 t:location_description="1605 OLYMPIC 90015-3828" t:street_address="1605 W OLYMPIC BLVD #9023" t:dba_name="MONEY MANAGEMENT INTERNATIONAL" t:city="LOS ANGELES" m:naics=523900
```

## Meta Commands

```ls
metric m:naics p:integer l:NAICS d:"The self-reported North American Industry Classification System (NAICS) code, which is used in classifying business establishments." t:dataTypeName=number

entity e:6rrh-rzua l:"Listing of Active Businesses" t:attribution="Office of Finance" t:url=https://data.lacity.org/api/views/6rrh-rzua

property e:6rrh-rzua t:meta.view v:id=6rrh-rzua v:category="A Prosperous City" v:averageRating=0 v:name="Listing of Active Businesses" v:attribution="Office of Finance"

property e:6rrh-rzua t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:6rrh-rzua t:meta.view.owner v:id=c255-4shb v:profileImageUrlMedium=/api/users/c255-4shb/profile_images/THUMB v:profileImageUrlLarge=/api/users/c255-4shb/profile_images/LARGE v:screenName="Office of Finance OpenData" v:profileImageUrlSmall=/api/users/c255-4shb/profile_images/TINY v:displayName="Office of Finance OpenData"

property e:6rrh-rzua t:meta.view.tableauthor v:id=c255-4shb v:profileImageUrlMedium=/api/users/c255-4shb/profile_images/THUMB v:profileImageUrlLarge=/api/users/c255-4shb/profile_images/LARGE v:screenName="Office of Finance OpenData" v:profileImageUrlSmall=/api/users/c255-4shb/profile_images/TINY v:roleName=publisher v:displayName="Office of Finance OpenData"
```

## Top Records

```ls
| location_account  | business_name                                            | dba_name                       | street_address            | city              | zip_code   | location_description      | mailing_address       | mailing_city      | mailing_zip_code | naics  | primary_naics_description                                           | council_district | location_start_date | location_end_date | 
| ================= | ======================================================== | ============================== | ========================= | ================= | ========== | ========================= | ===================== | ================= | ================ | ====== | =================================================================== | ================ | =================== | ================= | 
| 0000000115-0001-3 | VINCENZO LABELLA                                         |                                | 521 SWARTHMORE AVENUE     | PACIFIC PALISADES | 90272-4350 | 521 SWARTHMORE 90272-4350 | 521 SWARTHMORE AVENUE | PACIFIC PALISADES | 90272-4350       | 561500 | Travel arrangement & reservation services                           | 11               | 1990-01-01T00:00:00 |                   | 
| 0000000150-0001-5 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 2015 W TEMPLE STREET      | LOS ANGELES       | 90026-4913 | 2015 TEMPLE 90026-4913    | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 13               | 1991-01-01T00:00:00 |                   | 
| 0000000156-0001-2 | SPRINGBOARD NON-PROFIT CONSUMER CREDIT MANAGEMENT        | MONEY MANAGEMENT INTERNATIONAL | 1605 W OLYMPIC BLVD #9023 | LOS ANGELES       | 90015-3828 | 1605 OLYMPIC 90015-3828   |                       |                   |                  | 523900 | Other financial investment activities (including investment advice) | 1                | 1999-02-01T00:00:00 |                   | 
| 0000000225-0001-5 | STRATEGIC CONCEPTS IN ORGANIZING AND POLICY EDUCATION /C |                                | 1715 W FLORENCE AVENUE    | LOS ANGELES       | 90047-2220 | 1715 FLORENCE 90047-2220  |                       |                   |                  | 611000 | Educational services (including schools, colleges, & universities)  | 8                | 1997-06-03T00:00:00 |                   | 
| 0000000247-0001-1 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 3806 W PICO BLVD          | LOS ANGELES       | 90019-4304 | 3806 PICO 90019-4304      | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 10               | 1991-01-01T00:00:00 |                   | 
| 0000000265-0001-0 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 260 S UNION AVENUE #1     | LOS ANGELES       | 90026-5452 | 260 UNION 90026           | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 13               | 1991-01-01T00:00:00 |                   | 
| 0000000267-0001-9 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 3115 VENICE BLVD          | LOS ANGELES       | 90019-6238 | 3115 VENICE 90019-6238    | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 10               | 1991-01-01T00:00:00 |                   | 
| 0000000282-0001-3 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 2601 W PICO BLVD #2       | LOS ANGELES       | 90006-3901 | 2601 PICO 90006-3901      | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 1                | 1991-01-01T00:00:00 |                   | 
| 0000000327-0001-2 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 4151 BEVERLY BLVD         | LOS ANGELES       | 90004-4461 | 4151 BEVERLY 90004-4461   | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 13               | 1991-01-01T00:00:00 |                   | 
| 0000000328-0001-7 | A A OFICINA CENTRAL HISPANA DE LOS ANGELES /C            |                                | 3049 W 8TH STREET #763    | LOS ANGELES       | 90005-1873 | 3049 8TH 90005-1873       | 2607 VAN BUREN PLACE  | LOS ANGELES       | 90007-2129       | 611000 | Educational services (including schools, colleges, & universities)  | 10               | 1991-01-01T00:00:00 |                   | 
```