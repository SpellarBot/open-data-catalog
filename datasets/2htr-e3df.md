# SSMMA Available Bank- Owned Residential

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-available-bank-owned-residential-926bd) |
| Metadata | [Link](https://data.illinois.gov/api/views/2htr-e3df) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2htr-e3df/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2htr-e3df/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2htr-e3df |
| Name | SSMMA Available Bank- Owned Residential |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | housing, banks, planning |
| Created | 2012-11-27T17:33:40Z |
| Publication Date | 2012-11-27T19:16:45Z |

## Description

This dataset details bank-owned homes that are on the market. This is an aggregate of public listings from banks.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                       | Data Type | Render Type |
| ======== | ============== | ========================= | ========================== | ========= | =========== |
| Yes      | series tag     | propertyid                | PropertyID                 | text      | text        |
| Yes      | series tag     | county                    | County                     | text      | text        |
| Yes      | numeric metric | year_built                | Year Built                 | number    | number      |
| Yes      | series tag     | lot_size                  | Lot Size                   | text      | text        |
| Yes      | numeric metric | living_area               | Living Area                | number    | number      |
| Yes      | series tag     | property_type             | Property Type              | text      | text        |
| Yes      | numeric metric | bed                       | Bed                        | number    | number      |
| Yes      | numeric metric | bath                      | Bath                       | number    | number      |
| Yes      | numeric metric | half_bath                 | Half Bath                  | number    | number      |
| Yes      | series tag     | status                    | Status                     | text      | text        |
| Yes      | series tag     | price                     | Price                      | text      | text        |
| Yes      | series tag     | contact                   | Contact                    | text      | text        |
| Yes      | series tag     | company_name              | Company Name               | text      | text        |
| Yes      | series tag     | home_mortgage_contact_hmc | Home Mortgage Contact(HMC) | text      | text        |
| Yes      | series tag     | bank                      | BANK                       | text      | text        |
| Yes      | time           | yearbuilt                 | YearBuilt                  | number    | number      |
| No       |                | location_1                | Location 1                 | text      | text        |
```

## Time Field

```ls
Value = yearbuilt
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = location_1
```

## Data Commands

```ls
series e:2htr-e3df d:2012-01-01T00:00:00.000Z t:home_mortgage_contact_hmc="Joseph Cuellar" t:property_type="Single Family" t:price="$99 900" t:lot_size="7150 SQ.FT." t:company_name="Southland Chicago Real Estate Corp" t:county=Cook t:status=Available t:bank="Wells Fargo" t:propertyid=REO380391 t:contact="Henry Jones" m:half_bath=1 m:year_built=1965 m:living_area=1378 m:bed=3 m:bath=2

series e:2htr-e3df d:2012-01-01T00:00:00.000Z t:home_mortgage_contact_hmc="Nancy Johnson" t:property_type="Single Family" t:price="$74 500" t:lot_size="10173 SQ.FT." t:company_name="Re/Max Synergy" t:county=Cook t:status="Sale Pending" t:bank="Wells Fargo" t:propertyid=PAS374473 t:contact="Bob OHara" m:half_bath=0 m:year_built=1988 m:living_area=1693 m:bed=3 m:bath=2

series e:2htr-e3df d:2012-01-01T00:00:00.000Z t:property_type="Single Family" t:price=TBD t:lot_size="6400 SQ.FT." t:company_name="DR Real Estate Consultin" t:county=Cook t:status="Sale Pending" t:bank="Wells Fargo" t:propertyid=REO380665 t:contact="Daryl Russell" m:half_bath=0 m:year_built=1914 m:living_area=1236 m:bed=3 m:bath=1
```

## Meta Commands

```ls
metric m:year_built p:integer l:"Year Built" t:dataTypeName=number

metric m:living_area p:integer l:"Living Area" t:dataTypeName=number

metric m:bed p:integer l:Bed t:dataTypeName=number

metric m:bath p:double l:Bath t:dataTypeName=number

metric m:half_bath p:double l:"Half Bath" t:dataTypeName=number

entity e:2htr-e3df l:"SSMMA Available Bank- Owned Residential" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/2htr-e3df

property e:2htr-e3df t:meta.view v:id=2htr-e3df v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Available Bank- Owned Residential" v:attribution="South Suburban Mayors and Managers Association"

property e:2htr-e3df t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:2htr-e3df t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:2htr-e3df t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| propertyid | county  | year_built | lot_size     | living_area | property_type | bed | bath | half_bath | status       | price    | contact          | company_name                                 | home_mortgage_contact_hmc | bank        | yearbuilt | location_1                                                                           | 
| ========== | ======= | ========== | ============ | =========== | ============= | === | ==== | ========= | ============ | ======== | ================ | ============================================ | ========================= | =========== | ========= | ==================================================================================== | 
| REO380391  | Cook    | 1965       | 7150 SQ.FT.  | 1378        | Single Family | 3   | 2    | 1         | Available    | $99 900  | Henry Jones      | Southland Chicago Real Estate Corp           | Joseph Cuellar            | Wells Fargo |           | 17506 Butternut Road Hazel Crest, IL 60429 (41.57098347102601, -87.68076568504864)   | 
| PAS374473  | Cook    | 1988       | 10173 SQ.FT. | 1693        | Single Family | 3   | 2    | 0         | Sale Pending | $74 500  | Bob OHara        | Re/Max Synergy                               | Nancy Johnson             | Wells Fargo |           | 4015 Cypress Ct Country Club Hills, IL 60478 (41.54112597965326, -87.71537159673613) | 
| REO380665  | Cook    | 1914       | 6400 SQ.FT.  | 1236        | Single Family | 3   | 1    | 0         | Sale Pending | TBD      | Daryl Russell    | DR Real Estate Consultin                     |                           | Wells Fargo |           | 440 Hirsch Ave Calumet City, IL 60409 (41.62399839471209, -87.53849433341355)        | 
| REO343817  | Cook    | 1954       | 41040 SQ.FT. | 1715        | Single Family | 4   | 2    | 1         | Sale Pending | TBD      | Steve Malik      | Youbetcha Inc. - RE/MAX Professionals Select | Ken Crowder               | Wells Fargo |           | 7425 Arbor Avenue Burr Ridge, IL 60527 (41.75434623958, -87.9052904228837)           | 
| REO389654  | Cook    | 1991       | 0.15 Acres   | 1560        | Single Family | 3   | 1    | 0         | Coming Soon  | TBD      | Tammy DeYoung    | Realty Executives                            | TESSIE KRYGIER            | Wells Fargo |           | 20125 Lake Park Dr Lynwood, IL 60411 (41.53019921699723, -87.54610120438127)         | 
| REO379373  | Cook Il | 2007       | 0.31 Acres   | 5649        | Single Family | 5   | 5    | 2         | Sale Pending | $585 000 | Carl Letcher     | Re/Max Professionals                         | Eric Hamilton             | Wells Fargo |           | 61 Deer Ln Lemont, IL 60439 (41.64955723672597, -88.01195001555868)                  | 
| REO383635  | Cook Il | 1925       | 8446 SQ.FT.  | 2639        | Single Family | 4   | 2    | 1         | Available    | $409 900 | Joanne Brill     | Coldwell Banker Residential Brokerage Inc    | James Jefferson           | Wells Fargo |           | 292 Blackhawk Rd Riverside, IL 60546 (41.82466422905094, -87.8081366640584)          | 
| REO364470  | Cook Il | 2006       | 1.0 Acres    | 2900        | Single Family | 5   | 3    | 1         | Available    | $359 900 | Louise OConnor   | Baird & Warner                               | TESSIE KRYGIER            | Wells Fargo |           | 10050 W 127th St Palos Park, IL 60464 (41.65943179260768, -87.86636776545555)        | 
| PAS372161  | Cook Il | 1989       | 9180 SQ.FT.  | 3086        | Single Family | 5   | 2    | 1         | Sale Pending | $309 900 | Jim Kennedy      | JPK Capital LTD.                             | Noel Leyden               | Wells Fargo |           | 17460 Highwood Dr Orland Park, IL 60467 (41.57245835915404, -87.89725947716204)      | 
| REO382821  | Cook Il | 1948       | 16700 SQ.FT. | 2850        | Single Family | 5   | 2    | 1         | Available    | $274 900 | Becky Eichstaedt | Coldwell Banker Residential Brokerage        | James Jefferson           | Wells Fargo |           | 5617 Willow Springs Rd Countryside, IL 60525 (41.78759417500322, -87.88799646026024) | 
```