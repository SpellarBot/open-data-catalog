# 2011 Visitor Plant Inventory Hawaii

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-visitor-plant-inventory-hawaii-7c148) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rjmg-cpq7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rjmg-cpq7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rjmg-cpq7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rjmg-cpq7 |
| Name | 2011 Visitor Plant Inventory Hawaii |
| Attribution | Hawaii Tourism Authority |
| Category | Economic Development |
| Tags | visitor, tourist, rooms, hotel, condo, timeshare, individual vacation units, bed & breakfast |
| Created | 2012-08-17T20:23:16Z |
| Publication Date | 2012-08-17T20:32:14Z |

## Description

The Visitor Plant Inventory presents the results of the Hawaii Tourism Authority's enumeration of visitor accommodations in Hawaii. Existing visitor accommodations as of May 1, 2011.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | island              | Island              | text      | text        |
| Yes      | series tag     | area                | Area                | text      | text        |
| Yes      | series tag     | propertyid          | PropertyID          | text      | number      |
| Yes      | series tag     | propertyname        | PropertyName        | text      | text        |
| Yes      | series tag     | zipcode             | Zipcode             | text      | number      |
| Yes      | series tag     | type                | Type                | text      | text        |
| Yes      | numeric metric | availableunits      | AvailableUnits      | number    | number      |
| Yes      | numeric metric | changefromprioryear | ChangeFromPriorYear | number    | number      |
| Yes      | time           | yearopened          | YearOpened          | number    | number      |
| Yes      | numeric metric | budget              | Budget              | number    | number      |
| Yes      | numeric metric | standard            | Standard            | number    | number      |
| Yes      | numeric metric | deluxe              | Deluxe              | number    | number      |
| Yes      | numeric metric | luxury              | Luxury              | number    | number      |
| Yes      | numeric metric | lastresponse        | LastResponse        | number    | number      |
| Yes      | series tag     | city                | City                | text      | text        |
```

## Time Field

```ls
Value = yearopened
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rjmg-cpq7 d:1973-01-01T00:00:00.000Z t:area=Hilo/Honoka?a t:zipcode=96720 t:propertyname="Country Club Hawaii Condo/Hotel" t:type="CONDOMINIUM HOTEL" t:propertyid=1958 t:city=Hilo t:island=HAWAI'I m:luxury=0 m:budget=70 m:availableunits=70 m:standard=0 m:deluxe=0 m:changefromprioryear=0 m:lastresponse=2010

series e:rjmg-cpq7 d:2003-01-01T00:00:00.000Z t:area=Hilo/Honoka?a t:zipcode=96720 t:propertyname="At The Beach With Friends B&B Inn" t:type="BED & BREAKFAST" t:propertyid=2278 t:city=Hilo t:island=HAWAI'I m:luxury=0 m:budget=0 m:availableunits=3 m:standard=3 m:deluxe=0 m:changefromprioryear=0 m:lastresponse=2010

series e:rjmg-cpq7 d:2001-01-01T00:00:00.000Z t:area=Hilo/Honoka?a t:zipcode=96720 t:propertyname="Emeraldview Guest House" t:type="BED & BREAKFAST" t:propertyid=2197 t:city=Hilo t:island=HAWAI'I m:luxury=0 m:budget=0 m:availableunits=2 m:standard=2 m:deluxe=0 m:changefromprioryear=0 m:lastresponse=2009
```

## Meta Commands

```ls
metric m:availableunits p:integer l:AvailableUnits t:dataTypeName=number

metric m:changefromprioryear p:integer l:ChangeFromPriorYear t:dataTypeName=number

metric m:budget p:integer l:Budget t:dataTypeName=number

metric m:standard p:integer l:Standard t:dataTypeName=number

metric m:deluxe p:integer l:Deluxe t:dataTypeName=number

metric m:luxury p:integer l:Luxury t:dataTypeName=number

metric m:lastresponse p:integer l:LastResponse t:dataTypeName=number

entity e:rjmg-cpq7 l:"2011 Visitor Plant Inventory Hawaii" t:attribution="Hawaii Tourism Authority" t:url=https://data.hawaii.gov/api/views/rjmg-cpq7

property e:rjmg-cpq7 t:meta.view v:id=rjmg-cpq7 v:category="Economic Development" v:attributionLink=http://www.hawaiitourismauthority.org/research/reports/visitor-plant-inventory/ v:averageRating=0 v:name="2011 Visitor Plant Inventory Hawaii" v:attribution="Hawaii Tourism Authority"

property e:rjmg-cpq7 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:rjmg-cpq7 t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:rjmg-cpq7 t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| island  | area          | propertyid | propertyname                      | zipcode | type                    | availableunits | changefromprioryear | yearopened | budget | standard | deluxe | luxury | lastresponse | city    | 
| ======= | ============= | ========== | ================================= | ======= | ======================= | ============== | =================== | ========== | ====== | ======== | ====== | ====== | ============ | ======= | 
| HAWAI'I | Hilo/Honoka?a | 1958       | Country Club Hawaii Condo/Hotel   | 96720   | CONDOMINIUM HOTEL       | 70             | 0                   | 1973       | 70     | 0        | 0      | 0      | 2010         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 2278       | At The Beach With Friends B&B Inn | 96720   | BED & BREAKFAST         | 3              | 0                   | 2003       | 0      | 3        | 0      | 0      | 2010         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 2197       | Emeraldview Guest House           | 96720   | BED & BREAKFAST         | 2              | 0                   | 2001       | 0      | 2        | 0      | 0      | 2009         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 3765       | Hale Ehu Kai                      | 96720   | IVU-HOUSE/VILLA/COTTAGE | 1              | 0                   |            | 0      | 1        | 0      | 0      | 2011         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 3719       | Bayshore Towers                   | 96720   | IVU-CONDO               | 1              | -1                  |            | 0      | 1        | 0      | 0      | 2011         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 2119       | Beaches House                     | 96720   | IVU-HOUSE/VILLA/COTTAGE | 1              | 0                   | 2002       | 0      | 0        | 1      | 0      | 2011         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 2212       | #1 Akiko's Buddhist B&B           | 96710   | BED & BREAKFAST         | 7              | 0                   | 1995       | 7      | 0        | 0      | 0      | 2011         | Hakalau | 
| HAWAI'I | Hilo/Honoka?a | 2246       | Dolphin Bay Hotel                 | 96720   | HOTEL                   | 18             | 0                   | 1968       | 0      | 18       | 0      | 0      | 2010         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 2616       | Castle Hilo Hawaiian Hotel        | 96720   | HOTEL                   | 286            | 0                   | 1975       | 0      | 268      | 18     | 0      | 2010         | Hilo    | 
| HAWAI'I | Hilo/Honoka?a | 3575       | Aaron's Cottage                   | 96720   | BED & BREAKFAST         | 3              | 0                   | 2000       | 3      | 0        | 0      | 0      | 2011         | Hilo    | 
```