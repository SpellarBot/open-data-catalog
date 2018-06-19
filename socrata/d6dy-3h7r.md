# Retail Food Store Inspections ? Current Critical Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/retail-food-store-inspections-current-critical-violations) |
| Metadata | [Link](https://data.ny.gov/api/views/d6dy-3h7r) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/d6dy-3h7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/d6dy-3h7r/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | d6dy-3h7r |
| Name | Retail Food Store Inspections ? Current Critical Violations |
| Attribution | Department of Agriculture and Markets |
| Category | Economic Development |
| Tags | food safety, inspection, retail food store |
| Created | 2014-01-23T17:41:34Z |
| Publication Date | 2017-01-25T04:12:02Z |

## Description

Dataset includes most recent inspections of retail food stores where critical deficiencies were found during the inspection.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | county                 | County                 | text          | text          |
| Yes      | time        | inspection_date        | Inspection Date        | calendar_date | calendar_date |
| Yes      | series tag  | owner_name             | Owner Name             | text          | text          |
| Yes      | series tag  | trade_name             | Trade Name             | text          | text          |
| Yes      | series tag  | street                 | Street                 | text          | text          |
| Yes      | series tag  | city                   | City                   | text          | text          |
| Yes      | series tag  | statecode              | State Code             | text          | text          |
| Yes      | series tag  | zipcode                | Zip Code               | text          | text          |
| Yes      | series tag  | deficiency_number      | Deficiency Number      | text          | text          |
| Yes      | series tag  | deficiency_description | Deficiency Description | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:d6dy-3h7r d:2016-11-08T00:00:00.000Z t:statecode=NY t:owner_name="SAVI&PAUL INC" t:county=Orange t:zipcode=12549 t:street="2079 ST RT 208" t:trade_name="MOBIL MART" t:deficiency_description="Employee handwashing facilities inadequate for establishments handling exposed foods" t:deficiency_number=03D t:city=MONTGOMERY m:row_number.d6dy-3h7r=1

series e:d6dy-3h7r d:2016-11-08T00:00:00.000Z t:statecode=NY t:owner_name="SAVI&PAUL INC" t:county=Orange t:zipcode=12549 t:street="2079 ST RT 208" t:trade_name="MOBIL MART" t:deficiency_description="Handwashing facilities improperly installed or maintained" t:deficiency_number=09A t:city=MONTGOMERY m:row_number.d6dy-3h7r=2

series e:d6dy-3h7r d:2016-11-08T00:00:00.000Z t:statecode=NY t:owner_name="SAVI&PAUL INC" t:county=Orange t:zipcode=12549 t:street="2079 ST RT 208" t:trade_name="MOBIL MART" t:deficiency_description="Cleaning or sanitizing equipment, materials or agents are not available, suitable or properly stored" t:deficiency_number=09F t:city=MONTGOMERY m:row_number.d6dy-3h7r=3
```

## Meta Commands

```ls
metric m:row_number.d6dy-3h7r p:long l:"Row Number"

entity e:d6dy-3h7r l:"Retail Food Store Inspections ? Current Critical Violations" t:attribution="Department of Agriculture and Markets" t:url=https://data.ny.gov/api/views/d6dy-3h7r

property e:d6dy-3h7r t:meta.view v:id=d6dy-3h7r v:category="Economic Development" v:averageRating=0 v:name="Retail Food Store Inspections ? Current Critical Violations" v:attribution="Department of Agriculture and Markets"

property e:d6dy-3h7r t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:d6dy-3h7r t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| county | inspection_date     | owner_name                     | trade_name        | street                  | city       | statecode | zipcode | deficiency_number | deficiency_description                                                                                          | 
| ====== | =================== | ============================== | ================= | ======================= | ========== | ========= | ======= | ================= | =============================================================================================================== | 
| Orange | 2016-11-08T00:00:00 | SAVI&PAUL INC                  | MOBIL MART        | 2079 ST RT 208          | MONTGOMERY | NY        | 12549   | 03D               | Employee handwashing facilities inadequate for establishments handling exposed foods                            | 
| Orange | 2016-11-08T00:00:00 | SAVI&PAUL INC                  | MOBIL MART        | 2079 ST RT 208          | MONTGOMERY | NY        | 12549   | 09A               | Handwashing facilities improperly installed or maintained                                                       | 
| Orange | 2016-11-08T00:00:00 | SAVI&PAUL INC                  | MOBIL MART        | 2079 ST RT 208          | MONTGOMERY | NY        | 12549   | 09F               | Cleaning or sanitizing equipment, materials or agents are not available, suitable or properly stored            | 
| Orange | 2016-11-08T00:00:00 | SAVI&PAUL INC                  | MOBIL MART        | 2079 ST RT 208          | MONTGOMERY | NY        | 12549   | 14B               | Insect, birds or other vermin observed within the establishment (not likely to result in product contamination) | 
| Orange | 2016-11-08T00:00:00 | SAVI&PAUL INC                  | MOBIL MART        | 2079 ST RT 208          | MONTGOMERY | NY        | 12549   | 15C               | Food equipment improperly designed, constructed or maintained                                                   | 
| Orange | 2016-11-08T00:00:00 | SAVI&PAUL INC                  | MOBIL MART        | 2079 ST RT 208          | MONTGOMERY | NY        | 12549   | 15E               | Unused equipment or materials improperly stored or in an unclean condition                                      | 
| Albany | 2016-12-23T00:00:00 | PRICE CHOPPER OPERATING CO INC | PRICE CHOPPER 196 | 329 TOWN SQUARE PLAZA # | GLENMONT   | NY        | 12077   | 06B               | Potentially hazardous foods are not stored at safe temperatures                                                 | 
| Albany | 2016-12-23T00:00:00 | PRICE CHOPPER OPERATING CO INC | PRICE CHOPPER 196 | 329 TOWN SQUARE PLAZA # | GLENMONT   | NY        | 12077   | 09C               | Toilet facilities improperly installed, equipped or maintained                                                  | 
| Albany | 2016-12-23T00:00:00 | PRICE CHOPPER OPERATING CO INC | PRICE CHOPPER 196 | 329 TOWN SQUARE PLAZA # | GLENMONT   | NY        | 12077   | 09D               | Plumbing or sinks not properly sized, installed or maintained: equipment or floors not properly drained         | 
| Albany | 2016-12-23T00:00:00 | PRICE CHOPPER OPERATING CO INC | PRICE CHOPPER 196 | 329 TOWN SQUARE PLAZA # | GLENMONT   | NY        | 12077   | 09F               | Cleaning or sanitizing equipment, materials or agents are not available, suitable or properly stored            | 
```