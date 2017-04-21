# Food Enterprises Under 5000 Sq Ft

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-enterprises-under-5000-sq-ft) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bdr6-gbfn) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bdr6-gbfn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bdr6-gbfn/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bdr6-gbfn |
| Name | Food Enterprises Under 5000 Sq Ft |
| Tags | uro, arr, food permit |
| Created | 2016-10-20T12:16:07Z |
| Publication Date | 2016-10-20T12:27:30Z |

## Description

This is the list of food-service permitted businesses provided by Austin Travis County Health and Human Services Department. Please note that the square footage is self-reported, and some businesses may have left that information blank on the food-service permit. 
Food-service permitted businesses that are within the City of Austin?s jurisdiction, but are not yet affected by the Universal Recycling Ordinance (URO) Organics Diversion requirements can qualify for the zero waste business rebate.
Businesses registered as vendors with the City of Austin can be searched on the following webpage: https://www.ci.austin.tx.us/financeonline/vendor_connection/search/allsearch.cfm
For additional questions, contact Austin Resource Recovery?s Business Outreach Team at commercialrecycling@austintexas.gov or call 512-974-9727.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | permit_number_fp      | PERMIT NUMBER (FP)    | text      | text        |
| Yes      | series tag     | property_id_t_wcad    | PROPERTY ID (T/WCAD)  | text      | text        |
| Yes      | numeric metric | sq_ft_permit          | SQ FT (PERMIT)        | number    | number      |
| Yes      | series tag     | business_name         | BUSINESS NAME         | text      | text        |
| Yes      | series tag     | street_number         | STREET NUMBER         | text      | number      |
| Yes      | series tag     | street_direction      | STREET DIRECTION      | text      | text        |
| Yes      | series tag     | street_suffix         | STREET SUFFIX         | text      | text        |
| Yes      | series tag     | suite                 | SUITE                 | text      | text        |
| Yes      | series tag     | permit_subtype        | PERMIT SUBTYPE        | text      | text        |
| Yes      | series tag     | owner_name            | OWNER NAME            | text      | text        |
| No       |                | owner_mailing_address | OWNER MAILING ADDRESS | text      | text        |
| Yes      | series tag     | owner_mailing_city    | OWNER MAILING CITY    | text      | text        |
| Yes      | series tag     | owner_mailing_state   | OWNER MAILING STATE   | text      | text        |
| Yes      | series tag     | owner_mailing_zip     | OWNER MAILING ZIP     | text      | text        |
| Yes      | series tag     | fixed_food_type       | FIXED FOOD TYPE       | text      | text        |
| Yes      | series tag     | service_type          | SERVICE TYPE          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = owner_mailing_address
```

## Data Commands

```ls
series e:bdr6-gbfn d:2016-10-20T12:16:11.000Z t:business_name="Hyde Park Bar & Grill Commissary" t:fixed_food_type=Other t:permit_number_fp="2005000327 FP" t:owner_name="BICK BROWN" t:owner_mailing_state=TX t:street_suffix=#VALUE! t:permit_subtype="Food Products" t:owner_mailing_zip=78756 t:owner_mailing_city=AUSTIN m:sq_ft_permit=0

series e:bdr6-gbfn d:2016-10-20T12:16:11.000Z t:business_name="Bill Miller BBQ" t:fixed_food_type="General Food Service" t:permit_number_fp="2006007357 FP" t:property_id_t_wcad=476907 t:owner_name="ANGELA RIHN" t:service_type=Seated t:owner_mailing_state=TX t:street_suffix=WB t:permit_subtype="Food Service" t:street_direction=E t:owner_mailing_zip=78283 t:street_number=8700 t:owner_mailing_city="SAN ANTONIO" m:sq_ft_permit=0

series e:bdr6-gbfn d:2016-10-20T12:16:11.000Z t:business_name="Comfort Suites" t:fixed_food_type=Restaurant t:permit_number_fp="2006006233 FP" t:property_id_t_wcad=R379572 t:owner_name="ANAND & ALISHA, L.P." t:service_type=Seated t:owner_mailing_state=TX t:street_suffix=HWY t:permit_subtype="Food Service" t:street_direction=N t:owner_mailing_zip=78750 t:street_number=13681 t:owner_mailing_city=AUSTIN m:sq_ft_permit=0
```

## Meta Commands

```ls
metric m:sq_ft_permit p:integer l:"SQ FT (PERMIT)" t:dataTypeName=number

entity e:bdr6-gbfn l:"Food Enterprises Under 5000 Sq Ft" t:url=https://data.austintexas.gov/api/views/bdr6-gbfn

property e:bdr6-gbfn t:meta.view v:id=bdr6-gbfn v:averageRating=0 v:name="Food Enterprises Under 5000 Sq Ft"

property e:bdr6-gbfn t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:bdr6-gbfn t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| :updated_at | permit_number_fp | property_id_t_wcad                          | sq_ft_permit | business_name                            | street_number | street_direction | street_suffix | suite     | permit_subtype | owner_name                               | owner_mailing_address         | owner_mailing_city | owner_mailing_state | owner_mailing_zip | fixed_food_type      | service_type | 
| =========== | ================ | =========================================== | ============ | ======================================== | ============= | ================ | ============= | ========= | ============== | ======================================== | ============================= | ================== | =================== | ================= | ==================== | ============ | 
| 1476965771  | 2005000327 FP    |                                             | 0            | Hyde Park Bar & Grill Commissary         |               |                  | #VALUE!       |           | Food Products  | BICK BROWN                               | 4208 SHOALWOOD AVE.           | AUSTIN             | TX                  | 78756             | Other                |              | 
| 1476965771  | 2006007357 FP    | 476907                                      | 0            | Bill Miller BBQ                          | 8700          | E                | WB            |           | Food Service   | ANGELA RIHN                              | PO BOX 839925                 | SAN ANTONIO        | TX                  | 78283             | General Food Service | Seated       | 
| 1476965771  | 2006006233 FP    | R379572                                     | 0            | Comfort Suites                           | 13681         | N                | HWY           |           | Food Service   | ANAND & ALISHA, L.P.                     | 13681 N. US HWY 183           | AUSTIN             | TX                  | 78750             | Restaurant           | Seated       | 
| 1476965771  | 2014005876 FP    | R431840, R511407                            | 0            | Ashley's Playhouse                       | 13343         | N                | HWY           | Unit 200  | Food Service   | ASHLEY'S PLAYHOUSE,LLC                   | 13343 N. US HWY 183 STE #200  | AUSTIN             | TEXAS               | 78750             | Child Care           | Seated       | 
| 1476965771  | 2006005720 FP    | R055146, R330363, R330364, R330365, R363985 | 0            | China Cafe                               | 13729         | N                | NB            | Unit 695  | Food Service   | BING YU                                  | 13729 RESEARCH BLVD STE #695  | AUSTIN             | TX                  | 78750             | Restaurant           | Seated       | 
| 1476965771  | 2013026045 FP    | R381846                                     | 0            | Marble Slab Creamery                     | 14010         | N                | SVRD          | Unit 510  | Food Service   | CENTRAL TEXAS TREATS,INC                 | 14403 TERISU LN.              | AUSTIN             | TX                  | 78728             | General Food Service |              | 
| 1476965771  | 2011081987 FP    | 513049                                      | 0            | Reel Popcorn                             | 8708          | S                | AVE           | Bunit 550 | Food Service   | SHARON EASLEY                            | 8708 S CONGRESS AVE., STE 550 | AUSTIN             | TEXAS               | 78745             | General Food Service |              | 
| 1476965771  | 2006007019 FP    | 509427                                      | 0            | Sam's Club/Meat & Produce #4720          | 4970          | W                | WB            |           | Food Service   | WAL-MART STORES TEXAS, LLC/ATTN: AMY IGO | 3345 BEE CAVE RD STE# 105     | AUSTIN             | TX                  | 78746             | Other                | Carryout     | 
| 1476965771  | 2014054918 FP    | 119444                                      | 0            | Patricia's Table                         | 1510          | W                | CTOF          |           | Food Service   | PATRICIA TAMMINGA                        | 1510 WEST 35TH ST CUTOFF      | AUSTIN             | TEXAS               | 78731             | Other                |              | 
| 1476965771  | 2007109162 FP    | 745446                                      | 0            | Spec's Wines, Spirits & Finer Foods, #62 | 10515         | N                | NB            | Bldg K    | Retail Food    | SPEC'S FAMILY PARTNERS, LTD.             | 2410 SMITH ST.                | HOUSTON            | TEXAS               | 77006             | Other                |              | 
```