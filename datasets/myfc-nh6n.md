# EBRP Tax Roll

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ebrp-tax-roll) |
| Metadata | [Link](https://data.brla.gov/api/views/myfc-nh6n) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/myfc-nh6n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/myfc-nh6n/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | myfc-nh6n |
| Name | EBRP Tax Roll |
| Attribution | East Baton Rouge Parish Assessor's Office |
| Category | Housing and Development |
| Tags | tax; parcel; tax roll; assessment; property; ebrp |
| Created | 2015-12-21T21:57:40Z |
| Publication Date | 2017-01-23T14:05:38Z |

## Description

This dataset is a full listing of tax parcels in East Baton Rouge Parish including the cities of Baton Rouge, Baker, Central and Zachary.  The records contained herein include information about taxpayers, homestead exemptions, adjudications, property details, and many other topics.  The Assessor's Office provides this information for public use in an effort to better serve the taxpayers and property owners of East Baton Rouge Parish, Louisiana.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                      | Data Type     | Render Type   |
| ======== | ============== | ====================== | ========================= | ============= | ============= |
| No       |                | tax_year               | TAX YEAR                  | number        | number        |
| Yes      | series tag     | assessment_no          | PROPERTY NUMBER           | text          | text          |
| Yes      | series tag     | assessment_type        | ASSESSMENT TYPE           | text          | text          |
| Yes      | series tag     | assessment_status      | ASSESSMENT STATUS         | text          | text          |
| Yes      | series tag     | taxpayer_name          | TAXPAYER NAME             | text          | text          |
| No       |                | taxpayer_addr_1        | TAXPAYER ADDRESS          | text          | text          |
| No       |                | taxpayer_addr_2        | TAXPAYER SUBADDRESS       | text          | text          |
| Yes      | series tag     | taxpayer_addr_3        | TAXPAYER CITY STATE ZIP   | text          | text          |
| Yes      | series tag     | ward_no                | WARD                      | text          | number        |
| Yes      | series tag     | subdivision_name       | SUBDIVISION NAME          | text          | text          |
| Yes      | series tag     | block_no               | BLOCK/SQUARE NO           | text          | number        |
| Yes      | series tag     | lot_no                 | LOT NO                    | text          | text          |
| No       |                | parcel_address         | PHYSICAL ADDRESS          | text          | text          |
| Yes      | series tag     | structure_use          | STRUCTURE USE             | text          | text          |
| Yes      | series tag     | unit_type              | UNIT TYPE                 | text          | text          |
| Yes      | numeric metric | units                  | NO UNITS                  | number        | number        |
| Yes      | series tag     | vacant_lot_yn          | VACANT                    | text          | text          |
| Yes      | series tag     | instrument_type        | TRANSFER TYPE             | text          | text          |
| Yes      | time           | transfer_date          | TRANSFER DATE             | calendar_date | calendar_date |
| Yes      | series tag     | conveyance_page_no     | ORIGINAL                  | text          | number        |
| Yes      | series tag     | conveyance_book_no     | BUNDLE                    | text          | number        |
| Yes      | series tag     | legal_description      | LEGAL DESCRIPTION         | text          | text          |
| Yes      | series tag     | restora_tax_abatements | RESTORATION TAX ABATEMENT | text          | text          |
| Yes      | series tag     | homestead_exempt_type  | HOMESTEAD EXEMPTION       | text          | text          |
| Yes      | numeric metric | fair_market_val        | FAIR MARKET VALUE         | money         | money         |
| Yes      | numeric metric | total_value            | TOTAL ASSESSED VALUE      | number        | number        |
| Yes      | numeric metric | homestead_exemption    | HOMESTEAD EXEMPTION VALUE | number        | number        |
| Yes      | numeric metric | taxpayer_val           | TAXABLE PARISH            | number        | number        |
```

## Time Field

```ls
Value = transfer_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = taxpayer_addr_1,taxpayer_addr_2,parcel_address,tax_year
```

## Data Commands

```ls
series e:myfc-nh6n d:1972-01-01T00:00:00.000Z t:homestead_exempt_type=NO t:instrument_type="Sale with Mortgage" t:conveyance_page_no=2 t:taxpayer_name="BAILEY, MARY ESTHER" t:lot_no=251 t:structure_use=RESIDENTIAL t:ward_no=1 t:assessment_type="REAL PROPERTY" t:vacant_lot_yn=NO t:assessment_no=000-0475-8 t:taxpayer_addr_3="BATON ROUGE LA  70814" t:legal_description="Ward 1-1 #300, Lot: 251, Subdiv: BELFORT." t:assessment_status=ACTUAL t:unit_type=LOT t:subdivision_name=BELFORT t:conveyance_book_no=8164 t:restora_tax_abatements=NO m:fair_market_val=3000 m:homestead_exemption=0 m:units=2 m:taxpayer_val=300 m:total_value=300

series e:myfc-nh6n d:1990-07-10T00:00:00.000Z t:homestead_exempt_type=NO t:instrument_type="Sale with Assumption" t:conveyance_page_no=709 t:taxpayer_name="MILLS EARNEST & YVONNE J. MILLS" t:lot_no=53 t:structure_use=RESIDENTIAL t:ward_no=1 t:assessment_type="REAL PROPERTY" t:vacant_lot_yn=NO t:assessment_no=000-6528-5 t:taxpayer_addr_3="BAKER LA  70714" t:legal_description="Ward 1-1 #5249, Lot: 53, Subdiv: PRESCOTT PLACE." t:assessment_status=ACTUAL t:unit_type=LOT t:subdivision_name="PRESCOTT PLACE" t:conveyance_book_no=1016 t:restora_tax_abatements=NO m:fair_market_val=2500 m:homestead_exemption=0 m:units=2 m:taxpayer_val=250 m:total_value=250

series e:myfc-nh6n d:1969-01-01T00:00:00.000Z t:homestead_exempt_type=YES t:instrument_type="Tax Deed" t:conveyance_page_no=6 t:taxpayer_name="HAYES, LILLIE MAE FRANKLIN" t:lot_no=79 t:structure_use=RESIDENTIAL t:ward_no=1 t:assessment_type="REAL PROPERTY" t:vacant_lot_yn=NO t:assessment_no=000-8480-8 t:taxpayer_addr_3="BATON ROUGE LA  70802" t:legal_description="Ward 1-1 #3332, Lot: 79, Subdiv: BELFAIR HOMES." t:assessment_status=ACTUAL t:unit_type=LOT t:subdivision_name="BELFAIR HOMES" t:conveyance_book_no=7203 t:restora_tax_abatements=NO m:fair_market_val=3000 m:homestead_exemption=300 m:units=2 m:taxpayer_val=0 m:total_value=300
```

## Meta Commands

```ls
metric m:units p:double l:"NO UNITS" d:"Total number of structures attached to the tax parcel" t:dataTypeName=number

metric m:fair_market_val p:double l:"FAIR MARKET VALUE" d:"Fair market value of the tax parcel" t:dataTypeName=money

metric m:total_value p:double l:"TOTAL ASSESSED VALUE" d:"A percentage of the fair market value determined by the use of the property (commercial or residential)" t:dataTypeName=number

metric m:homestead_exemption p:double l:"HOMESTEAD EXEMPTION VALUE" d:"Homestead exemption amount for the tax parcel" t:dataTypeName=number

metric m:taxpayer_val p:double l:"TAXABLE PARISH" d:"The taxable amount for determining Parish taxes derived from the sum of land/acreage value and any improvement value minus any applicable homestead exemption" t:dataTypeName=number

entity e:myfc-nh6n l:"EBRP Tax Roll" t:attribution="East Baton Rouge Parish Assessor's Office" t:url=https://data.brla.gov/api/views/myfc-nh6n

property e:myfc-nh6n t:meta.view v:id=myfc-nh6n v:category="Housing and Development" v:attributionLink=http://ebrpa.org/ v:averageRating=0 v:name="EBRP Tax Roll" v:attribution="East Baton Rouge Parish Assessor's Office"

property e:myfc-nh6n t:meta.view.license v:name="Public Domain"

property e:myfc-nh6n t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:myfc-nh6n t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| tax_year | assessment_no | assessment_type | assessment_status | taxpayer_name                   | taxpayer_addr_1       | taxpayer_addr_2 | taxpayer_addr_3      | ward_no | subdivision_name | block_no | lot_no | parcel_address      | structure_use  | unit_type | units | vacant_lot_yn | instrument_type      | transfer_date       | conveyance_page_no | conveyance_book_no | legal_description                                 | restora_tax_abatements | homestead_exempt_type | fair_market_val | total_value | homestead_exemption | taxpayer_val | 
| ======== | ============= | =============== | ================= | =============================== | ===================== | =============== | ==================== | ======= | ================ | ======== | ====== | =================== | ============== | ========= | ===== | ============= | ==================== | =================== | ================== | ================== | ================================================= | ====================== | ===================== | =============== | =========== | =================== | ============ | 
| 2015     | 000-0475-8    | REAL PROPERTY   | ACTUAL            | BAILEY, MARY ESTHER             | 4126 HILLMONT DR.     |                 | BATON ROUGE LA 70814 | 1       | BELFORT          |          | 251    | 2306 N 38TH ST.     | RESIDENTIAL    | LOT       | 2     | NO            | Sale with Mortgage   | 1972-01-01T00:00:00 | 2                  | 8164               | Ward 1-1 #300, Lot: 251, Subdiv: BELFORT.         | NO                     | NO                    | 3000            | 300         | 0                   | 300          | 
| 2015     | 000-6528-5    | REAL PROPERTY   | ACTUAL            | MILLS EARNEST & YVONNE J. MILLS | 17616 WISDOM AVE.     |                 | BAKER LA 70714       | 1       | PRESCOTT PLACE   |          | 53     |                     | RESIDENTIAL    | LOT       | 2     | NO            | Sale with Assumption | 1990-07-10T00:00:00 | 709                | 1016               | Ward 1-1 #5249, Lot: 53, Subdiv: PRESCOTT PLACE.  | NO                     | NO                    | 2500            | 250         | 0                   | 250          | 
| 2015     | 000-8480-8    | REAL PROPERTY   | ACTUAL            | HAYES, LILLIE MAE FRANKLIN      | 2145 BATEMAN CIRCLE   |                 | BATON ROUGE LA 70802 | 1       | BELFAIR HOMES    |          | 79     | 2145 BATEMAN CIRCLE | RESIDENTIAL    | LOT       | 2     | NO            | Tax Deed             | 1969-01-01T00:00:00 | 6                  | 7203               | Ward 1-1 #3332, Lot: 79, Subdiv: BELFAIR HOMES.   | NO                     | YES                   | 3000            | 300         | 300                 | 0            | 
| 2015     | 001-2526-1    | REAL PROPERTY   | ACTUAL            | MILES, ELEANOR S.               | 1620 OLEANDER ST.     |                 | BATON ROUGE LA 70802 | 1       | CLARK            |          | 10     | 1620 OLEANDER ST.   | RESIDENTIAL    | LOT       | 2     | NO            | DONATION             | 2047-01-01T00:00:00 |                    |                    | Ward 1-1 #5204, Lot: 10, Subdiv: CLARK.           | NO                     | YES                   | 4000            | 400         | 400                 | 0            | 
| 2015     | 001-3165-2    | REAL PROPERTY   | ACTUAL            | MING, ANNIECE EMERY             | 4216 BAWELL ST.       |                 | BATON ROUGE LA 70808 | 1       | HART             | 2        | 22     | 811 SOUTH 12TH ST.  | RESIDENTIAL    | LOT       | 1     | YES           |                      | 1958-01-01T00:00:00 |                    |                    | Ward 1-1 #5277, Lot: 22, Square: 2, Subdiv: HART. | NO                     | NO                    | 3000            | 300         | 0                   | 300          | 
| 2015     | 001-5327-3    | REAL PROPERTY   | ACTUAL            | BANKS, NELDA KAY                | 2061 RICE DR.         |                 | BATON ROUGE LA 70802 | 1       | BELFAIR HOMES    |          | 188    | 2061 RICE DR.       | RESIDENTIAL    | LOT       | 2     | NO            | Cash Sale            | 1995-04-26T00:00:00 | 539                | 1059               | Ward 1-1 #353, Lot: 188, Subdiv: BELFAIR HOMES.   | NO                     | YES                   | 3000            | 300         | 300                 | 0            | 
| 2015     | 002-0258-4    | REAL PROPERTY   | ACTUAL            | EXPRESS FOOD MART, INC.         | 3322 NORTH FOSTER DR. |                 | BATON ROUGE LA 70805 | 1       | FAIRWOODS        |          | 235    |                     | NOT DETERMINED | LOT       | 1     | YES           | Cash Sale            | 1996-12-17T00:00:00 | 797                | 1075               | Ward 1-2 #5643, Lot: 235, Subdiv: FAIRWOODS.      | NO                     | NO                    | 2000            | 200         | 0                   | 200          | 
| 2015     | 002-2998-9    | REAL PROPERTY   | ACTUAL            | BELONA, IVY & DELORES WILLIAMS  | 3984 ST. ANDREW DR.   |                 | BATON ROUGE LA 70805 | 1       | LYNN PLACE       |          | 13     | 3984 ST. ANDREW DR. | RESIDENTIAL    | LOT       | 2     | NO            | Cash Sale            | 1994-05-16T00:00:00 | 116                | 1050               | Ward 1-2 #1431, Lot: 13, Subdiv: LYNN PLACE.      | NO                     | YES                   | 4500            | 450         | 450                 | 0            | 
| 2015     | 002-3161-4    | REAL PROPERTY   | ACTUAL            | CAGE, CAROLA ROBINS             | 3067 BLACKWELL DR.    |                 | BATON ROUGE LA 70805 | 1       | FIELDCREST       |          | 27     | 3067 BLACKWELL DR.  | RESIDENTIAL    | LOT       | 2     | NO            | Cash Sale            | 1997-09-26T00:00:00 | 672                | 1082               | Ward 1-2 #2741, Lot: 27, Subdiv: FIELDCREST.      | NO                     | YES                   | 2000            | 200         | 200                 | 0            | 
| 2015     | 002-3710-8    | REAL PROPERTY   | ACTUAL            | BURTON, CLARENCE                | 6349 KINCAID AVE.     |                 | BATON ROUGE LA 70805 | 1       | BIRD STATION     |          | 369    | 6349 KINCAID AVE.   | RESIDENTIAL    | LOT       | 2     | NO            | Sheriff Sale         | 1959-01-01T00:00:00 |                    |                    | Ward 1-2 #2524, Lot: 369, Subdiv: BIRD STATION.   | NO                     | YES                   | 1500            | 150         | 150                 | 0            | 
```