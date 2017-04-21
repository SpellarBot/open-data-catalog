# Properties Affected by Organics Diversion Requirements of Universal Recycling Ordinance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/properties-affected-by-organics-diversion-requirements-of-universal-recycling-ordinance) |
| Metadata | [Link](https://data.austintexas.gov/api/views/a3pf-9u7n) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/a3pf-9u7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/a3pf-9u7n/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | a3pf-9u7n |
| Name | Properties Affected by Organics Diversion Requirements of Universal Recycling Ordinance |
| Category | Environmental |
| Tags | organics, food, permit, business, property, recycle, universal recycling ordinance, austin resource recovery, arr |
| Created | 2016-08-29T18:51:12Z |
| Publication Date | 2017-01-04T21:08:51Z |

## Description

Dataset of all properties newly affected by the Organics section of the Universal Recycling Ordinance beginning October 1, 2016. The URO supports Austin's Zero Waste goal by requiring affected property owners to ensure that tenants and employees have access to convenient recycling.  Starting Oct. 1, 2016, the largest businesses with food service permits will be required to establish organics diversion programs.
For more on the Universal Recycling Ordinance visit www.austintexas.gov/uro.
Austin Resource Recovery staff is also available to answer questions ? call 512-974-9727 or email commercialrecycling@austintexas.gov.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | property_id                     | Property ID                       | text      | number      |
| Yes      | numeric metric | food_permit                     | Food Permit #                     | number    | number      |
| Yes      | series tag     | food_permit_rsn                 | Food Permit RSN                   | text      | text        |
| Yes      | numeric metric | reported_food_permit_area_sq_ft | Reported Food Permit Area (sq ft) | number    | number      |
| Yes      | time           | year_affected                   | Year Affected                     | number    | number      |
| Yes      | series tag     | property_name                   | Property Name                     | text      | text        |
| Yes      | series tag     | physical_zip                    | Physical Zip                      | text      | text        |
| Yes      | series tag     | owner_name                      | Owner Name                        | text      | text        |
| No       |                | owner_address_line_1            | Owner Address Line 1              | text      | text        |
| Yes      | series tag     | owner_city                      | Owner City                        | text      | text        |
| Yes      | series tag     | owner_state                     | Owner State                       | text      | text        |
| Yes      | series tag     | owner_zip                       | Owner Zip                         | text      | text        |
```

## Time Field

```ls
Value = year_affected
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = owner_address_line_1
```

## Data Commands

```ls
series e:a3pf-9u7n d:2016-01-01T00:00:00.000Z t:property_id=312676 t:food_permit_rsn="2014128235 FP" t:owner_name="A-TX LICENSING SERVICE" t:owner_zip=78680 t:owner_state=TX t:property_name="Poco Loco Supermercado" t:physical_zip=78745 t:owner_city="ROUND ROCK" m:reported_food_permit_area_sq_ft=15945

series e:a3pf-9u7n d:2016-01-01T00:00:00.000Z t:food_permit_rsn="2007159323 FP, 2007159330 FP" t:owner_name="HEB/ ATTN: LICENSING DEPT." t:owner_zip=78283-3986 t:owner_state=TX t:property_name="HEB #031" t:physical_zip=78750 t:owner_city="SAN ANTONIO" m:reported_food_permit_area_sq_ft=52400

series e:a3pf-9u7n d:2016-01-01T00:00:00.000Z t:property_id=230780 t:food_permit_rsn="2013107701 FP" t:owner_name="DDEMP & DBUCK LLC / ATTN: DAVID C. BUCHANAN" t:owner_zip=85306 t:owner_state=AZ t:property_name="Sleep Inn & Suites" t:physical_zip=78754 t:owner_city=GLENDALE m:reported_food_permit_area_sq_ft=45976 m:food_permit=11031713
```

## Meta Commands

```ls
metric m:food_permit p:integer l:"Food Permit #" t:dataTypeName=number

metric m:reported_food_permit_area_sq_ft p:integer l:"Reported Food Permit Area (sq ft)" t:dataTypeName=number

entity e:a3pf-9u7n l:"Properties Affected by Organics Diversion Requirements of Universal Recycling Ordinance" t:url=https://data.austintexas.gov/api/views/a3pf-9u7n

property e:a3pf-9u7n t:meta.view v:id=a3pf-9u7n v:category=Environmental v:averageRating=0 v:name="Properties Affected by Organics Diversion Requirements of Universal Recycling Ordinance"

property e:a3pf-9u7n t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:a3pf-9u7n t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| property_id | food_permit | food_permit_rsn              | reported_food_permit_area_sq_ft | year_affected | property_name                       | physical_zip | owner_name                                  | owner_address_line_1              | owner_city  | owner_state | owner_zip  | 
| =========== | =========== | ============================ | =============================== | ============= | =================================== | ============ | =========================================== | ================================= | =========== | =========== | ========== | 
| 312676      |             | 2014128235 FP                | 15945                           | 2016          | Poco Loco Supermercado              | 78745        | A-TX LICENSING SERVICE                      | PO BOX 337                        | ROUND ROCK  | TX          | 78680      | 
|             |             | 2007159323 FP, 2007159330 FP | 52400                           | 2016          | HEB #031                            | 78750        | HEB/ ATTN: LICENSING DEPT.                  | P. O. BOX 839986                  | SAN ANTONIO | TX          | 78283-3986 | 
| 230780      | 11031713    | 2013107701 FP                | 45976                           | 2016          | Sleep Inn & Suites                  | 78754        | DDEMP & DBUCK LLC / ATTN: DAVID C. BUCHANAN | 6677 W. THUNDERBIRD ROAD STE J176 | GLENDALE    | AZ          | 85306      | 
|             | 10978489    | 2013070414 FP                | 36000                           | 2016          | Alamo Drafthouse Cinema             | 78613        | MISSY REYNOLDS                              | 612 E 6TH STREET, UNIT A          | AUSTIN      | TX          | 78701      | 
| 144833      | 2801652     | 2006006108 FP                | 24113                           | 2016          | Children's Courtyard                | 78731        | THE CHILDREN'S COURTYARD, INC.              | 4213 SPICEWOOD SPRING RD          | AUSTIN      | TX          | 78731      | 
|             | 2804049     | 2006002013 FP                | 15500                           | 2016          | CVS/Pharmacy #8322                  | 78750        | CVS PHARMACY INC. LICENSING DEPT            | ONE CVS DR. MAIL DROP 23062 A     | WOONSOCKET  | RI          | 02895      | 
| 291452      | 11378674    | 2015079191 FP                | 15520                           | 2016          | Dance Across TX                     | 78744        | DANCE ACROSS TX, INC                        | P. O. BOX 17845                   | AUSTIN      | TX          | 78760      | 
| 246256      | 10398249    | 2010010611 FP                | 24000                           | 2016          | El Rancho 18                        | 78757        | MEXICO FOODS,LLC/ ATTN: NELY                | P.O. BOX 472586                   | GARLAND     | TX          | 75041      | 
|             | 10796050    | 2012070040 FP                | 38000                           | 2016          | Gold's Gym - Anderson Arbor         | 78729        | GOLD'S TX HOLDINGS GROUP, INC.              | 4001 MAPLE AVE. #200              | DALLAS      | TX          | 75219      | 
|             | 10655854    | 2011086181 FP                | 60000                           | 2016          | Harmony School of Political Science | 78729        | COSMOS FOUNDATION, INC.                     | 13415 N FM 620 RD                 | AUSTIN      | TX          | 78717      | 
```