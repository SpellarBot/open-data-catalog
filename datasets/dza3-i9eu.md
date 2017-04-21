# Recreation and Park Department's Facility Conditions Assessment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comet-conditions-assessment) |
| Metadata | [Link](https://data.sfgov.org/api/views/dza3-i9eu) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/dza3-i9eu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/dza3-i9eu/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | dza3-i9eu |
| Name | Recreation and Park Department's Facility Conditions Assessment |
| Attribution | San Francisco Recreation & Parks Department |
| Category | Culture and Recreation |
| Tags | comet, capital assets, capital program |
| Created | 2016-04-05T00:20:47Z |
| Publication Date | 2016-04-05T00:28:33Z |

## Description

A 2007 conditions assessment of the Recreation & Parks Department's capital assets. This data is collected and published from COMET.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | tma_supervisoral_district | TMA_SUPERVISORAL_DISTRICT | text      | number      |
| Yes      | series tag     | psa_id                    | PSA_ID                    | text      | number      |
| Yes      | series tag     | psa_title                 | PSA_TITLE                 | text      | text        |
| Yes      | numeric metric | psa_fci                   | PSA_FCI                   | percent   | percent     |
| Yes      | series tag     | site_id                   | SITE_ID                   | text      | number      |
| Yes      | series tag     | site_name                 | SITE_NAME                 | text      | text        |
| Yes      | numeric metric | site_sq_ft                | SITE_SQ_FT                | number    | number      |
| Yes      | numeric metric | site_fci                  | SITE_FCI                  | percent   | percent     |
| Yes      | series tag     | tma_facility_type         | TMA_FACILITY_TYPE         | text      | text        |
| Yes      | series tag     | path_name                 | PATH_NAME                 | text      | text        |
| Yes      | numeric metric | fci                       | FCI                       | percent   | percent     |
| Yes      | series tag     | path_type                 | PATH_TYPE                 | text      | text        |
| Yes      | series tag     | assembly                  | ASSEMBLY                  | text      | text        |
| Yes      | series tag     | assembly_id               | ASSEMBLY_ID               | text      | number      |
| Yes      | series tag     | assm_desc                 | ASSM_DESC                 | text      | text        |
| Yes      | series tag     | uom                       | UOM                       | text      | text        |
| Yes      | numeric metric | qty                       | QTY                       | number    | number      |
| Yes      | numeric metric | unit_price                | UNIT_PRICE                | money     | money       |
| Yes      | numeric metric | ext_unit_price            | EXT_UNIT_PRICE            | money     | money       |
| Yes      | numeric metric | replacement_amt           | REPLACEMENT_AMT           | money     | money       |
| Yes      | numeric metric | renewal_pct               | RENEWAL_PCT               | percent   | percent     |
| Yes      | numeric metric | renewal_amt               | RENEWAL_AMT               | money     | money       |
| Yes      | numeric metric | life                      | LIFE                      | percent   | percent     |
| Yes      | time           | year_installed            | YEAR_INSTALLED            | number    | number      |
| Yes      | numeric metric | priority                  | PRIORITY                  | number    | number      |
| Yes      | series tag     | priority_description      | PRIORITY_DESCRIPTION      | text      | text        |
| Yes      | series tag     | category                  | CATEGORY                  | text      | text        |
| Yes      | series tag     | distress                  | DISTRESS                  | text      | text        |
| Yes      | series tag     | material                  | MATERIAL                  | text      | text        |
```

## Time Field

```ls
Value = year_installed
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dza3-i9eu d:1936-01-01T00:00:00.000Z t:path_name="Maintenance Shed" t:uom=S.F. t:assembly=A1030 t:site_id=59 t:psa_title="PSA 1" t:path_type=Building t:assembly_id=81 t:site_name="Lafayette Park" t:tma_supervisoral_district=2 t:psa_id=2 t:tma_facility_type="Neighborhood Park or Playground" t:assm_desc="Slab on Grade" m:life=100 m:renewal_pct=100 m:site_fci=65.34 m:fci=19.74 m:ext_unit_price=32.15 m:qty=360 m:site_sq_ft=500504.4 m:unit_price=15.82 m:replacement_amt=11573.73 m:renewal_amt=9245 m:psa_fci=40.39

series e:dza3-i9eu d:1936-01-01T00:00:00.000Z t:path_name="Maintenance Shed" t:uom=S.F. t:assembly=B1020 t:site_id=59 t:psa_title="PSA 1" t:path_type=Building t:assembly_id=85 t:site_name="Lafayette Park" t:tma_supervisoral_district=2 t:psa_id=2 t:tma_facility_type="Neighborhood Park or Playground" t:assm_desc="Roof Construction" m:life=100 m:renewal_pct=100 m:site_fci=65.34 m:fci=19.74 m:ext_unit_price=52.21 m:qty=360 m:site_sq_ft=500504.4 m:unit_price=25.69 m:replacement_amt=18794.52 m:renewal_amt=14217 m:psa_fci=40.39

series e:dza3-i9eu d:1936-01-01T00:00:00.000Z t:priority_description="Necessary- 2-5 Yrs" t:assembly=B2010 t:site_id=59 t:tma_supervisoral_district=2 t:site_name="Lafayette Park" t:assm_desc="Painted Concrete Exterior Walls" t:tma_facility_type="Neighborhood Park or Playground" t:material=System t:path_name="Maintenance Shed" t:category="Deferred Maintenance" t:uom=S.F. t:psa_title="PSA 1" t:path_type=Building t:assembly_id=87 t:psa_id=2 t:distress="Beyond Useful Life" m:life=10 m:renewal_pct=100 m:site_fci=65.34 m:priority=3 m:fci=19.74 m:ext_unit_price=1.06 m:qty=360 m:site_sq_ft=500504.4 m:unit_price=0.52 m:replacement_amt=380.43 m:renewal_amt=304 m:psa_fci=40.39
```

## Meta Commands

```ls
metric m:psa_fci p:float l:PSA_FCI t:dataTypeName=percent

metric m:site_sq_ft p:decimal l:SITE_SQ_FT t:dataTypeName=number

metric m:site_fci p:float l:SITE_FCI t:dataTypeName=percent

metric m:fci p:float l:FCI t:dataTypeName=percent

metric m:qty p:integer l:QTY t:dataTypeName=number

metric m:unit_price p:double l:UNIT_PRICE t:dataTypeName=money

metric m:ext_unit_price p:double l:EXT_UNIT_PRICE t:dataTypeName=money

metric m:replacement_amt p:double l:REPLACEMENT_AMT t:dataTypeName=money

metric m:renewal_pct p:double l:RENEWAL_PCT t:dataTypeName=percent

metric m:renewal_amt p:double l:RENEWAL_AMT t:dataTypeName=money

metric m:life p:integer l:LIFE t:dataTypeName=percent

metric m:priority p:integer l:PRIORITY t:dataTypeName=number

entity e:dza3-i9eu l:"Recreation and Park Department's Facility Conditions Assessment" t:attribution="San Francisco Recreation & Parks Department" t:url=https://data.sfgov.org/api/views/dza3-i9eu

property e:dza3-i9eu t:meta.view v:id=dza3-i9eu v:category="Culture and Recreation" v:averageRating=0 v:name="Recreation and Park Department's Facility Conditions Assessment" v:attribution="San Francisco Recreation & Parks Department"

property e:dza3-i9eu t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:dza3-i9eu t:meta.view.owner v:id=qivp-g7uh v:screenName="Eric Pawlowsky" v:displayName="Eric Pawlowsky"

property e:dza3-i9eu t:meta.view.tableauthor v:id=qivp-g7uh v:screenName="Eric Pawlowsky" v:roleName=editor v:displayName="Eric Pawlowsky"
```

## Top Records

```ls
| tma_supervisoral_district | psa_id | psa_title | psa_fci | site_id | site_name      | site_sq_ft | site_fci | tma_facility_type               | path_name        | fci   | path_type | assembly | assembly_id | assm_desc                       | uom  | qty | unit_price | ext_unit_price | replacement_amt | renewal_pct | renewal_amt | life | year_installed | priority | priority_description | category             | distress           | material | 
| ========================= | ====== | ========= | ======= | ======= | ============== | ========== | ======== | =============================== | ================ | ===== | ========= | ======== | =========== | =============================== | ==== | === | ========== | ============== | =============== | =========== | =========== | ==== | ============== | ======== | ==================== | ==================== | ================== | ======== | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | A1030    | 81          | Slab on Grade                   | S.F. | 360 | 15.82      | 32.15          | 11573.73        | 100         | 9245.00     | 100  | 1936           |          |                      |                      |                    |          | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | B1020    | 85          | Roof Construction               | S.F. | 360 | 25.69      | 52.21          | 18794.52        | 100         | 14217.00    | 100  | 1936           |          |                      |                      |                    |          | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | B2010    | 87          | Painted Concrete Exterior Walls | S.F. | 360 | 0.52       | 1.06           | 380.43          | 100         | 304.00      | 10   | 1936           | 3        | Necessary- 2-5 Yrs   | Deferred Maintenance | Beyond Useful Life | System   | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | B2020    | 88          | Exterior Windows                | S.F. | 360 | 4.72       | 9.59           | 3453.10         | 100         | 2758.00     | 50   | 1936           | 3        | Necessary- 2-5 Yrs   | Deferred Maintenance | Beyond Useful Life | System   | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | B2030    | 89          | Metal Exterior Doors            | S.F. | 360 | 6.59       | 13.39          | 4821.17         | 100         | 3851.00     | 40   | 1936           | 3        | Necessary- 2-5 Yrs   | Deferred Maintenance | Beyond Useful Life | System   | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | B3010    | 91          | Composition Roof                | S.F. | 360 | 4.50       | 9.14           | 3292.15         | 100         | 2630.00     | 20   | 1996           |          |                      |                      |                    |          | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | D2010    | 102         | Plumbing Fixtures               | S.F. | 360 | 3.60       | 7.32           | 2633.72         | 100         | 2104.00     | 30   | 1936           | 3        | Necessary- 2-5 Yrs   | Deferred Maintenance | Beyond Useful Life | System   | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | D2020    | 103         | Domestic Water Distribution     | S.F. | 360 | 3.75       | 7.62           | 2743.46         | 100         | 2191.00     | 30   | 1936           | 3        | Necessary- 2-5 Yrs   | Deferred Maintenance | Beyond Useful Life | System   | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Maintenance Shed | 19.74 | Building  | D2030    | 104         | Sanitary Waste                  | S.F. | 360 | 3.45       | 7.01           | 2523.98         | 100         | 2016.00     | 30   | 1936           | 3        | Necessary- 2-5 Yrs   | Deferred Maintenance | Beyond Useful Life | System   | 
| 2                         | 2      | PSA 1     | 40.39   | 59      | Lafayette Park | 500504.4   | 65.34    | Neighborhood Park or Playground | Restroom         | 62.79 | Building  | A1030    | 115         | Slab on Grade                   | S.F. | 575 | 15.82      | 32.15          | 18485.83        | 100         | 18556.00    | 100  | 1936           |          |                      |                      |                    |          | 
```