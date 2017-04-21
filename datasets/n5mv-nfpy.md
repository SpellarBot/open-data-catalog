# IPIS (Integrated Property Information System)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ipis-integrated-property-information-system-a5b7f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/n5mv-nfpy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/n5mv-nfpy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/n5mv-nfpy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | n5mv-nfpy |
| Name | IPIS (Integrated Property Information System) |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | Housing & Development |
| Tags | property, finance, lease, agency, city-owned, private, consumer affairs, dcas, administrative services, ipis (integrated property information system), ipis |
| Created | 2011-07-26T16:26:28Z |
| Publication Date | 2013-06-21T20:49:18Z |

## Description

Database of City-owned properties and private properties that the City leases for City agency use.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | numeric metric | boro                     | BORO                     | number    | number      |
| Yes      | series tag     | block                    | BLOCK                    | text      | number      |
| Yes      | series tag     | lot                      | LOT                      | text      | number      |
| Yes      | series tag     | parcel_name              | PARCEL_NAME              | text      | text        |
| No       |                | parcel_address           | PARCEL_ADDRESS           | text      | text        |
| Yes      | series tag     | juris                    | JURIS                    | text      | text        |
| Yes      | series tag     | jurisdiction_description | Jurisdiction Description | text      | text        |
| Yes      | series tag     | rpad                     | RPAD                     | text      | text        |
| Yes      | series tag     | rpad_description         | RPAD_DESCRIPTION         | text      | text        |
| Yes      | numeric metric | prop_front               | PROP_FRONT               | number    | number      |
| Yes      | numeric metric | prop_depth               | PROP_DEPTH               | number    | number      |
| Yes      | numeric metric | prop_sqft                | PROP_SQFT                | number    | number      |
| Yes      | series tag     | irreg                    | IRREG                    | text      | text        |
| Yes      | numeric metric | bld_front                | BLD_FRONT                | number    | number      |
| Yes      | numeric metric | bld_depth                | BLD_DEPTH                | number    | number      |
| Yes      | numeric metric | bld_sqft                 | BLD_SQFT                 | number    | number      |
| Yes      | numeric metric | num_bld                  | NUM_BLD                  | number    | number      |
| Yes      | numeric metric | floors                   | FLOORS                   | number    | number      |
| No       |                | cd                       | CD                       | number    | number      |
| Yes      | series tag     | council_district         | COUNCIL_DISTRICT         | text      | number      |
| Yes      | series tag     | councilmember_name       | COUNCILMEMBER_NAME       | text      | text        |
| Yes      | series tag     | pr_zone                  | PR_ZONE                  | text      | text        |
| Yes      | series tag     | ov_zone                  | OV_ZONE                  | text      | text        |
| Yes      | series tag     | sd_zone                  | SD_ZONE                  | text      | text        |
| Yes      | numeric metric | bbl                      | BBL                      | number    | number      |
| Yes      | series tag     | waterfront               | WATERFRONT               | text      | text        |
| Yes      | series tag     | urban_renewal_site       | URBAN RENEWAL SITE       | text      | text        |
| Yes      | series tag     | agency                   | Agency                   | text      | text        |
| Yes      | series tag     | owned_leased             | Owned/Leased             | text      | text        |
| Yes      | series tag     | primary_use_text         | Primary Use Text         | text      | text        |
| Yes      | series tag     | final_commitment_text    | Final Commitment Text    | text      | text        |
| Yes      | series tag     | agreement_lease_out_     | Agreement (Lease-Out)    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = parcel_address,cd
```

## Data Commands

```ls
series e:n5mv-nfpy d:2012-09-05T13:18:27.000Z t:parcel_name="BATTERY MARITIME BLDG / FERRY" t:rpad=O9 t:jurisdiction_description="JOINT JURIS AMONG CITY AGENCIES" t:councilmember_name="MARGARET CHIN" t:sd_zone=LM t:primary_use_text="NO USE" t:juris=JOINT t:block=2 t:agency=DSBS t:council_district=1 t:irreg=I t:pr_zone=C4-6 t:owned_leased=O t:rpad_description="OFFICE BLDGS/MISC" t:lot=1 t:waterfront=Y m:prop_sqft=445250 m:bbl=1000020001 m:bld_sqft=445250 m:prop_depth=564 m:boro=1 m:prop_front=709 m:floors=3 m:num_bld=3 m:bld_depth=564 m:bld_front=709

series e:n5mv-nfpy d:2012-09-05T13:18:27.000Z t:parcel_name="BATTERY MARITIME BLDG / FERRY" t:rpad=O9 t:jurisdiction_description="JOINT JURIS AMONG CITY AGENCIES" t:councilmember_name="MARGARET CHIN" t:sd_zone=LM t:primary_use_text="FERRY TERMINAL" t:juris=JOINT t:block=2 t:agency=DOT t:council_district=1 t:irreg=I t:pr_zone=C4-6 t:owned_leased=O t:rpad_description="OFFICE BLDGS/MISC" t:lot=1 t:waterfront=Y m:prop_sqft=445250 m:bbl=1000020001 m:bld_sqft=445250 m:prop_depth=564 m:boro=1 m:prop_front=709 m:floors=3 m:num_bld=3 m:bld_depth=564 m:bld_front=709

series e:n5mv-nfpy d:2012-09-05T13:18:27.000Z t:parcel_name="PIER 6" t:rpad=T2 t:jurisdiction_description="DEPT OF SMALL BUSINESS SERVICES" t:councilmember_name="MARGARET CHIN" t:sd_zone=LM t:primary_use_text="IN USE-TENANTED" t:juris=DSBS t:block=2 t:agency=EDC t:council_district=1 t:irreg=I t:agreement_lease_out_="LONG-TERM AGREEMENT" t:urban_renewal_site=Y t:pr_zone=C4-6 t:owned_leased=O t:rpad_description="PIERS, DOCKS, BULKHEADS" t:lot=23 t:waterfront=Y m:prop_sqft=510025 m:bbl=1000020023 m:bld_sqft=24346 m:prop_depth=551 m:boro=1 m:prop_front=793 m:floors=2 m:num_bld=1 m:bld_depth=551 m:bld_front=85
```

## Meta Commands

```ls
metric m:boro p:integer l:BORO t:dataTypeName=number

metric m:prop_front p:integer l:PROP_FRONT t:dataTypeName=number

metric m:prop_depth p:integer l:PROP_DEPTH t:dataTypeName=number

metric m:prop_sqft p:integer l:PROP_SQFT t:dataTypeName=number

metric m:bld_front p:integer l:BLD_FRONT t:dataTypeName=number

metric m:bld_depth p:integer l:BLD_DEPTH t:dataTypeName=number

metric m:bld_sqft p:integer l:BLD_SQFT t:dataTypeName=number

metric m:num_bld p:integer l:NUM_BLD t:dataTypeName=number

metric m:floors p:integer l:FLOORS t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:n5mv-nfpy l:"IPIS (Integrated Property Information System)" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/n5mv-nfpy

property e:n5mv-nfpy t:meta.view v:id=n5mv-nfpy v:category="Housing & Development" v:averageRating=0 v:name="IPIS (Integrated Property Information System)" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:n5mv-nfpy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:n5mv-nfpy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | boro | block | lot | parcel_name                   | parcel_address     | juris | jurisdiction_description        | rpad | rpad_description          | prop_front | prop_depth | prop_sqft | irreg | bld_front | bld_depth | bld_sqft | num_bld | floors | cd | council_district | councilmember_name | pr_zone | ov_zone | sd_zone | bbl        | waterfront | urban_renewal_site | agency | owned_leased | primary_use_text | final_commitment_text | agreement_lease_out_ | 
| =========== | ==== | ===== | === | ============================= | ================== | ===== | =============================== | ==== | ========================= | ========== | ========== | ========= | ===== | ========= | ========= | ======== | ======= | ====== | == | ================ | ================== | ======= | ======= | ======= | ========== | ========== | ================== | ====== | ============ | ================ | ===================== | ==================== | 
| 1346851107  | 1    | 2     | 1   | BATTERY MARITIME BLDG / FERRY | 10 SOUTH STREET    | JOINT | JOINT JURIS AMONG CITY AGENCIES | O9   | OFFICE BLDGS/MISC         | 709        | 564        | 445250    | I     | 709       | 564       | 445250   | 3       | 3      | 1  | 1                | MARGARET CHIN      | C4-6    |         | LM      | 1000020001 | Y          |                    | DSBS   | O            | NO USE           |                       |                      | 
| 1346851107  | 1    | 2     | 1   | BATTERY MARITIME BLDG / FERRY | 10 SOUTH STREET    | JOINT | JOINT JURIS AMONG CITY AGENCIES | O9   | OFFICE BLDGS/MISC         | 709        | 564        | 445250    | I     | 709       | 564       | 445250   | 3       | 3      | 1  | 1                | MARGARET CHIN      | C4-6    |         | LM      | 1000020001 | Y          |                    | DOT    | O            | FERRY TERMINAL   |                       |                      | 
| 1346851107  | 1    | 2     | 23  | PIER 6                        | SOUTH STREET       | DSBS  | DEPT OF SMALL BUSINESS SERVICES | T2   | PIERS, DOCKS, BULKHEADS   | 793        | 551        | 510025    | I     | 85        | 551       | 24346    | 1       | 2      | 1  | 1                | MARGARET CHIN      | C4-6    |         | LM      | 1000020023 | Y          | Y                  | EDC    | O            | IN USE-TENANTED  |                       | LONG-TERM AGREEMENT  | 
| 1346851107  | 1    | 2     | 23  | PIER 6                        | SOUTH STREET       | DSBS  | DEPT OF SMALL BUSINESS SERVICES | T2   | PIERS, DOCKS, BULKHEADS   | 793        | 551        | 510025    | I     | 85        | 551       | 24346    | 1       | 2      | 1  | 1                | MARGARET CHIN      | C4-6    |         | LM      | 1000020023 | Y          | Y                  | DSBS   | O            | NO USE           | FINAL COMMITMNT-DISP  |                      | 
| 1346851107  | 1    | 3     | 1   | BATTERY PARK                  | BATTERY PLACE      | PARKS | DEPT OF PARKS & RECREATION      | Q1   | PARKS                     | 323        | 1260       | 945425    | I     | 89        | 57        | 945425   | 5       | 1      | 1  | 1                | MARGARET CHIN      | PARK    |         |         | 1000030001 | Y          |                    | PARKS  | O            | PARK             |                       |                      | 
| 1346851107  | 1    | 3     | 2   | PETER MINUIT PLAZA/BATTERY PK | PETER MINUIT PLAZA | PARKS | DEPT OF PARKS & RECREATION      | Q1   | PARKS                     | 496        | 76         | 39900     | I     |           |           |          |         |        | 1  | 1                | MARGARET CHIN      | PARK    |         |         | 1000030002 |            |                    | PARKS  | O            | PARK             |                       |                      | 
| 1346851107  | 1    | 3     | 3   | PETER MINUIT PLAZA/BATTERY PK | WHITEHALL STREET   | PARKS | DEPT OF PARKS & RECREATION      | Q1   | PARKS                     | 180        | 370        | 33600     | I     | 16        | 19        |          | 1       | 1      | 1  | 1                | MARGARET CHIN      | PARK    |         |         | 1000030003 |            |                    | PARKS  | O            | PARK             |                       |                      | 
| 1346851107  | 1    | 6     | 1   | VIETNAM VETERANS PLAZA        | SOUTH ST           | PARKS | DEPT OF PARKS & RECREATION      | Q1   | PARKS                     | 234        | 349        | 35166     | I     |           |           |          |         |        | 1  | 1                | MARGARET CHIN      | PARK    |         |         | 1000060001 |            |                    | PARKS  | O            | PARK             |                       |                      | 
| 1346851107  | 1    | 12    | 28  | BOWLING GREEN PARK            | 0 BROADWAY         | PARKS | DEPT OF PARKS & RECREATION      | Q1   | PARKS                     | 200        | 140        | 22500     | I     |           |           |          |         |        | 1  | 1                | MARGARET CHIN      | PARK    |         |         | 1000120028 |            |                    | PARKS  | O            | PARK             |                       |                      | 
| 1346851107  | 1    | 16    | 1   | PIER A / MARINE UNIT #1       | PIER A             | DSBS  | DEPT OF SMALL BUSINESS SERVICES | Y7   | DEPT OF MARINE & AVIATION | 77         | 293        | 83100     | I     | 43        | 293       | 32000    | 1       | 3      | 1  | 1                | MARGARET CHIN      | C6-4    |         | LM      | 1000160001 | Y          |                    | DOT    | O            | FERRY TERMINAL   |                       |                      | 
```