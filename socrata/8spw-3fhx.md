# Building and Safety Temporary Special Event (TSE) Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-safety-temporary-special-event-tse-permits-887b1) |
| Metadata | [Link](https://data.lacity.org/api/views/8spw-3fhx) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/8spw-3fhx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/8spw-3fhx/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 8spw-3fhx |
| Name | Building and Safety Temporary Special Event (TSE) Permits |
| Attribution | LADBS |
| Category | A Prosperous City |
| Tags | ladbs, department of building and safety, building and safety, building, safety, construction services, permit, permit number, permit type, temporary special event permit, temporary special event,... |
| Created | 2014-04-18T21:10:45Z |
| Publication Date | 2017-01-04T01:18:39Z |

## Description

Temporary Special Events being held within the City of Los Angeles are required to be inspected and approved by the Department of Building and Safety. A Temporary Special Event permit application is filed with the Department of Building and Safety as a prerequisite for inspection.

## Columns

```ls
| Included | Schema Type | Field Name       | Name                   | Data Type     | Render Type   |
| ======== | =========== | ================ | ====================== | ============= | ============= |
| Yes      | series tag  | permitno         | PCIS Permit #          | text          | text          |
| Yes      | series tag  | per_type         | Permit Type            | text          | text          |
| Yes      | series tag  | per_sub_type     | Permit Sub-Type        | text          | text          |
| No       |             | address_start    | Address Start          | number        | number        |
| No       |             | addr_frac_start  | Address Fraction Start | text          | text          |
| No       |             | address_end      | Address End            | number        | number        |
| No       |             | addr_frac_end    | Address Fraction End   | text          | text          |
| Yes      | series tag  | addr_dir         | Street Direction       | text          | text          |
| Yes      | series tag  | addr_name        | Street Name            | text          | text          |
| Yes      | series tag  | addr_suff        | Street Suffix          | text          | text          |
| Yes      | series tag  | addr_suff_dir    | Suffix Direction       | text          | text          |
| Yes      | series tag  | addr_unit_start  | Unit Range Start       | text          | text          |
| Yes      | series tag  | addr_unit_end    | Unit Range End         | text          | text          |
| Yes      | series tag  | zip_code         | Zip Code               | text          | number        |
| Yes      | series tag  | work_desc        | Work Description       | text          | text          |
| Yes      | series tag  | location         | Event Location         | text          | text          |
| Yes      | series tag  | event_name       | Event Name             | text          | text          |
| Yes      | time        | event_start_date | Event Start Date       | calendar_date | calendar_date |
| No       |             | event_end_date   | Event End Date         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = event_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_start,addr_frac_start,address_end,addr_frac_end,event_end_date
```

## Data Commands

```ls
series e:8spw-3fhx d:2013-04-27T00:00:00.000Z t:per_sub_type=Commercial t:per_type="Temporary Special Event" t:zip_code=90012 t:permitno=13410-10000-00654 t:location="ANGEL CITY BREWERY" t:addr_dir=S t:addr_name=ALAMEDA t:addr_suff=ST t:event_name="OPEN HOUSE BREWERY TOURS" t:work_desc="EVENT APRIL 27, 2012 OPEN HOUSE BREWERY TOURS." m:row_number.8spw-3fhx=1

series e:8spw-3fhx d:2013-05-31T00:00:00.000Z t:per_sub_type=Commercial t:per_type="Temporary Special Event" t:zip_code=90016 t:permitno=13410-10000-00657 t:location="ST AGATHA CATHOLIC CHURCH" t:addr_dir=S t:addr_name=MANSFIELD t:addr_suff=AVE t:event_name="CARNIVAL @ ST AGATHA" t:work_desc="FIESTA AT ST AGATHA WITH MECHANICAL RIDES ON MAY 31-JUNE 2, 2013." m:row_number.8spw-3fhx=2

series e:8spw-3fhx d:2013-05-04T00:00:00.000Z t:per_sub_type=Commercial t:per_type="Temporary Special Event" t:permitno=13410-10000-00692 t:location="2025 AVENUE OF THE STARS" t:event_name="L'ANZA HAIR SHOW" t:work_desc="AEINAL RIG FOR PERFORMANCE, 18 FEET HIGH TRIPOD STRUCTURE WITH CABLES" m:row_number.8spw-3fhx=3
```

## Meta Commands

```ls
metric m:row_number.8spw-3fhx p:long l:"Row Number"

entity e:8spw-3fhx l:"Building and Safety Temporary Special Event (TSE) Permits" t:attribution=LADBS t:url=https://data.lacity.org/api/views/8spw-3fhx

property e:8spw-3fhx t:meta.view v:id=8spw-3fhx v:category="A Prosperous City" v:averageRating=0 v:name="Building and Safety Temporary Special Event (TSE) Permits" v:attribution=LADBS

property e:8spw-3fhx t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8spw-3fhx t:meta.view.owner v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:displayName="Building and Safety OpenData"

property e:8spw-3fhx t:meta.view.tableauthor v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:roleName=publisher v:displayName="Building and Safety OpenData"
```

## Top Records

```ls
| permitno          | per_type                | per_sub_type | address_start | addr_frac_start | address_end | addr_frac_end | addr_dir | addr_name           | addr_suff | addr_suff_dir | addr_unit_start | addr_unit_end | zip_code | work_desc                                                              | location                                    | event_name                               | event_start_date    | event_end_date      | 
| ================= | ======================= | ============ | ============= | =============== | =========== | ============= | ======== | =================== | ========= | ============= | =============== | ============= | ======== | ====================================================================== | =========================================== | ======================================== | =================== | =================== | 
| 13410-10000-00654 | Temporary Special Event | Commercial   | 216           |                 | 216         |               | S        | ALAMEDA             | ST        |               |                 |               | 90012    | EVENT APRIL 27, 2012 OPEN HOUSE BREWERY TOURS.                         | ANGEL CITY BREWERY                          | OPEN HOUSE BREWERY TOURS                 | 2013-04-27T00:00:00 | 2013-04-27T00:00:00 | 
| 13410-10000-00657 | Temporary Special Event | Commercial   | 2646          |                 | 2646        |               | S        | MANSFIELD           | AVE       |               |                 |               | 90016    | FIESTA AT ST AGATHA WITH MECHANICAL RIDES ON MAY 31-JUNE 2, 2013.      | ST AGATHA CATHOLIC CHURCH                   | CARNIVAL @ ST AGATHA                     | 2013-05-31T00:00:00 | 2013-06-02T00:00:00 | 
| 13410-10000-00692 | Temporary Special Event | Commercial   |               |                 |             |               |          |                     |           |               |                 |               |          | AEINAL RIG FOR PERFORMANCE, 18 FEET HIGH TRIPOD STRUCTURE WITH CABLES  | 2025 AVENUE OF THE STARS                    | L'ANZA HAIR SHOW                         | 2013-05-04T00:00:00 | 2013-05-05T00:00:00 | 
| 13410-10000-00721 | Temporary Special Event | Vacant Land  |               |                 |             |               |          |                     |           |               |                 |               |          | SET UP CIRCUS TENT. EVENT MAY 30-JUNE 3, 2013 AMERICAN CROWN CIRCUS-CA | WATERFRONT BERTH 48-49, SAN PEDRO, CA 90731 | AMERICAN CROWN CIRCUS                    | 2013-05-30T00:00:00 | 2013-06-03T00:00:00 | 
| 13410-10000-00722 | Temporary Special Event | Commercial   | 3939          |                 | 3939        |               | S        | FIGUEROA            | ST        |               |                 |               | 90037    | N/A                                                                    | EXPOSITION PARK LOT #6                      | FIGUEROA SWAPMEET                        | 2013-05-05T00:00:00 | 2013-05-05T00:00:00 | 
| 13410-10000-00727 | Temporary Special Event | Commercial   | 2025          |                 | 2025        |               | S        | AVENUE OF THE STARS |           |               |                 |               | 90067    | TRUSS STRUCTURE OPEN 40' X 22' TRUSS STRUCTURE OPEN 12' X 20' TRUSS ST | CENTURY PLAZA HOTEL                         | AVOOS BRIDAL SHOW                        | 2013-05-05T00:00:00 | 2013-05-05T00:00:00 | 
| 13410-10000-00742 | Temporary Special Event | Commercial   | 19812         |                 | 19812       |               | W        | CANTLAY             | ST        |               |                 |               | 91306    | CARNIVAL WITH RIDES AND GAMES JUNE 21-23                               | ST. JOSEPH THE WORKER PARISH PARKING LOT    | SJW 2013 FESTIVAL                        | 2013-06-21T00:00:00 | 2013-06-23T00:00:00 | 
| 13410-10000-00744 | Temporary Special Event | Commercial   | 1150          |                 | 1150        |               | S        | BEVERLY             | DR        |               |                 |               | 90035    | BUYING ROADSHOW, BUYING ANTIQUES PRECIOUS METAL FROM PUBLIC NOT SELLIN | THE CROWN PLAZA BEVERLY HILLS HOTEL         | TYRE,BAILEY,ROBERTS & ASSOC ESTATE BUYER | 2013-06-02T00:00:00 | 2013-06-02T00:00:00 | 
| 13410-10000-00751 | Temporary Special Event | Commercial   | 2650          |                 | 2650        |               | E        | OLYMPIC             | BLVD      |               |                 |               | 90023    | A CIRCUS FAMILY TENT SHOW WITH A GRAND STAND AT THE SEARS PARKING LOT. |                                             | CIRCO HERMANOS CABALLERO                 | 2013-05-10T00:00:00 | 2013-05-14T00:00:00 | 
| 13410-10000-00782 | Temporary Special Event | Commercial   | 800           |                 | 800         |               | W        | OLYMPIC             | BLVD      |               |                 |               | 90015    | 6 leg self climber truss, 2 x 20' w truss arches 48" H stage 20' d x 3 | Nokia Plaza LA Live                         | CHOICE WELCOME SHOW                      | 2013-05-13T00:00:00 | 2013-05-13T00:00:00 | 
```