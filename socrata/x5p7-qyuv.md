# Affordable Housing Inventory (AHI)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/affordable-housing-inventory-ahi) |
| Metadata | [Link](https://data.austintexas.gov/api/views/x5p7-qyuv) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/x5p7-qyuv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/x5p7-qyuv/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | x5p7-qyuv |
| Name | Affordable Housing Inventory (AHI) |
| Attribution | Neighborhood Housing and Community Development Office |
| Category | Neighborhood |
| Tags | affordable, housing, affordable housing, rhda, a&d, density bonus, s.m.a.r.t. housing, ahfc, mfi, nhcd |
| Created | 2017-01-12T17:56:48Z |
| Publication Date | 2017-01-12T18:59:33Z |

## Description

This dataset is an inventory of income-restricted affordable housing funded and/or incentivized by the City of Austin and/or the Austin Housing Finance Corporation (AHFC).
No warranty is made by the City of Austin regarding the specific accuracy or completeness of this dataset.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | project_name                   | Project Name                   | text          | text          |
| Yes      | series tag     | owner                          | Owner                          | text          | text          |
| Yes      | series tag     | developer                      | Developer                      | text          | text          |
| No       |                | address                        | Address                        | text          | text          |
| Yes      | series tag     | zip_code                       | Zip Code                       | text          | number        |
| Yes      | series tag     | council_district               | Council District               | text          | number        |
| Yes      | series tag     | kirwan_opportunity_index       | Kirwan Opportunity Index       | text          | text          |
| Yes      | series tag     | distance_to_bus_stop           | Distance to Bus Stop           | text          | text          |
| Yes      | numeric metric | total_units                    | Total Units                    | number        | number        |
| Yes      | numeric metric | total_affordable_units         | Total Affordable Units         | number        | number        |
| Yes      | series tag     | unit_type                      | Unit Type                      | text          | text          |
| Yes      | series tag     | program                        | Program                        | text          | text          |
| Yes      | series tag     | housing_type                   | Housing Type                   | text          | text          |
| Yes      | series tag     | status                         | Status                         | text          | text          |
| No       |                | affordability_start_date       | Affordability Start Date       | calendar_date | calendar_date |
| Yes      | numeric metric | affordability_period           | Affordability Period           | number        | number        |
| Yes      | time           | affordability_expiration_date  | Affordability Expiration Date  | calendar_date | calendar_date |
| No       |                | certification_date             | Certification Date             | calendar_date | calendar_date |
| No       |                | c_of_o_date                    | C. of O. Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | required_amount_of_fee_in_lieu | Required Amount of Fee in Lieu | money         | money         |
| No       |                | date_fee_in_lieu_received      | Date Fee in Lieu Received      | calendar_date | calendar_date |
| Yes      | numeric metric | units_30_mfi                   | Units <= 30% MFI               | number        | number        |
| Yes      | numeric metric | units_40_mfi                   | Units <= 40% MFI               | number        | number        |
| Yes      | numeric metric | units_50_mfi                   | Units <= 50% MFI               | number        | number        |
| Yes      | numeric metric | units_60_mfi                   | Units <= 60% MFI               | number        | number        |
| Yes      | numeric metric | units_65_mfi                   | Units <= 65% MFI               | number        | number        |
| Yes      | numeric metric | units_80_mfi                   | Units <= 80% MFI               | number        | number        |
| Yes      | numeric metric | units_100_mfi                  | Units <= 100% MFI              | number        | number        |
| Yes      | numeric metric | market_rate_units              | Market Rate Units              | number        | number        |
| Yes      | numeric metric | city_funded_amount             | City Funded Amount             | money         | money         |
| Yes      | numeric metric | of_funds_leveraged             | % of Funds Leveraged           | percent       | percent       |
| Yes      | series tag     | clt                            | CLT                            | text          | text          |
| Yes      | series tag     | ddb                            | DDB                            | text          | text          |
| Yes      | series tag     | rny                            | RNY                            | text          | text          |
| Yes      | series tag     | mda                            | MDA                            | text          | text          |
| Yes      | series tag     | nbg                            | NBG                            | text          | text          |
| Yes      | series tag     | pudda                          | PUDDA                          | text          | text          |
| Yes      | series tag     | smart                          | SMART                          | text          | text          |
| Yes      | series tag     | tod                            | TOD                            | text          | text          |
| Yes      | series tag     | uno                            | UNO                            | text          | text          |
| Yes      | series tag     | vmu                            | VMU                            | text          | text          |
```

## Time Field

```ls
Value = affordability_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,affordability_start_date,certification_date,c_of_o_date,date_fee_in_lieu_received
```

## Data Commands

```ls
series e:x5p7-qyuv d:2008-11-16T00:00:00.000Z t:mda=No t:ddb=No t:tod=Yes t:distance_to_bus_stop="1/4 Mile" t:clt=No t:project_name="M Station" t:zip_code=78722 t:status="Project Complete / Final C.of O. Received" t:nbg=No t:council_district=1 t:uno=No t:rny=No t:pudda=No t:program=RHDA t:developer="Foundation Communities, Inc." t:kirwan_opportunity_index="Very High" t:owner="Foundation Communities, Inc." t:unit_type=Multifamily t:vmu=No t:smart=Yes t:housing_type=Rental m:market_rate_units=10 m:total_affordable_units=140 m:city_funded_amount=2000000 m:units_80_mfi=8 m:units_30_mfi=28 m:units_65_mfi=0 m:units_60_mfi=36 m:units_50_mfi=68 m:affordability_period=99 m:of_funds_leveraged=868.83 m:units_40_mfi=0 m:units_100_mfi=0 m:total_units=150

series e:x5p7-qyuv d:2037-10-08T00:00:00.000Z t:mda=No t:ddb=No t:tod=No t:distance_to_bus_stop="1/4 Mile" t:clt=No t:project_name="Garden Terrace Expansion (aka Garden Terrace, Phase II)" t:zip_code=78745 t:status="Project Complete / Final C.of O. Received" t:nbg=No t:council_district=2 t:uno=No t:rny=No t:pudda=No t:program=RHDA t:developer="Foundation Communities, Inc." t:kirwan_opportunity_index=Low t:owner="Garden Terrace Housing Corporation" t:unit_type=Multifamily t:vmu=No t:smart=Yes t:housing_type=Rental m:market_rate_units=0 m:total_affordable_units=15 m:city_funded_amount=500000 m:units_80_mfi=0 m:units_30_mfi=0 m:units_65_mfi=0 m:units_60_mfi=0 m:units_50_mfi=15 m:affordability_period=30 m:of_funds_leveraged=160 m:units_40_mfi=0 m:units_100_mfi=0 m:total_units=15

series e:x5p7-qyuv d:2026-05-04T00:00:00.000Z t:mda=No t:ddb=No t:tod=No t:distance_to_bus_stop=Neither t:clt=No t:project_name="LifeWorks Transitional Living Project" t:zip_code=78704 t:status="Project Complete / Final C.of O. Received" t:nbg=No t:council_district=3 t:uno=No t:rny=No t:pudda=No t:program=RHDA t:developer=Lifeworks t:kirwan_opportunity_index="Very Low" t:owner=Lifeworks t:unit_type=Multifamily t:vmu=No t:smart=Yes t:housing_type=Rental m:market_rate_units=0 m:total_affordable_units=12 m:city_funded_amount=300000 m:units_80_mfi=0 m:units_30_mfi=0 m:units_65_mfi=0 m:units_60_mfi=0 m:units_50_mfi=12 m:affordability_period=20 m:of_funds_leveraged=101.22 m:units_40_mfi=0 m:units_100_mfi=0 m:total_units=12
```

## Meta Commands

```ls
metric m:total_units p:integer l:"Total Units" t:dataTypeName=number

metric m:total_affordable_units p:integer l:"Total Affordable Units" t:dataTypeName=number

metric m:affordability_period p:integer l:"Affordability Period" t:dataTypeName=number

metric m:required_amount_of_fee_in_lieu p:integer l:"Required Amount of Fee in Lieu" d:"Fee in Lieu represents funds paid by the developer in exchange for not building onsite affordable housing. These funds will be utilized to develop affordable housing in other locations." t:dataTypeName=money

metric m:units_30_mfi p:integer l:"Units <= 30% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:units_40_mfi p:integer l:"Units <= 40% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:units_50_mfi p:integer l:"Units <= 50% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:units_60_mfi p:integer l:"Units <= 60% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:units_65_mfi p:integer l:"Units <= 65% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:units_80_mfi p:integer l:"Units <= 80% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:units_100_mfi p:integer l:"Units <= 100% MFI" d:"Number of income restricted affordable housing units at each property reserved for households making a certain percentage of the Austin-Round Rock metropolitan statistical area (MSA) median family income (MFI) (see http://www.austintexas.gov/page/income-limits for current MFI)." t:dataTypeName=number

metric m:market_rate_units p:integer l:"Market Rate Units" d:"Non Income Restricted Units" t:dataTypeName=number

metric m:city_funded_amount p:double l:"City Funded Amount" t:dataTypeName=money

metric m:of_funds_leveraged p:float l:"% of Funds Leveraged" d:"Amount of external funding secured for development as a percentage of City or AHFC investment." t:dataTypeName=percent

entity e:x5p7-qyuv l:"Affordable Housing Inventory (AHI)" t:attribution="Neighborhood Housing and Community Development Office" t:url=https://data.austintexas.gov/api/views/x5p7-qyuv

property e:x5p7-qyuv t:meta.view v:id=x5p7-qyuv v:category=Neighborhood v:attributionLink=http://www.austintexas.gov/department/housing v:averageRating=0 v:name="Affordable Housing Inventory (AHI)" v:attribution="Neighborhood Housing and Community Development Office"

property e:x5p7-qyuv t:meta.view.license v:name="Public Domain"

property e:x5p7-qyuv t:meta.view.owner v:id=nkm5-uj2r v:profileImageUrlMedium=/api/users/nkm5-uj2r/profile_images/THUMB v:profileImageUrlLarge=/api/users/nkm5-uj2r/profile_images/LARGE v:screenName="Jonathan Tomko" v:profileImageUrlSmall=/api/users/nkm5-uj2r/profile_images/TINY v:displayName="Jonathan Tomko"

property e:x5p7-qyuv t:meta.view.tableauthor v:id=nkm5-uj2r v:profileImageUrlMedium=/api/users/nkm5-uj2r/profile_images/THUMB v:profileImageUrlLarge=/api/users/nkm5-uj2r/profile_images/LARGE v:screenName="Jonathan Tomko" v:profileImageUrlSmall=/api/users/nkm5-uj2r/profile_images/TINY v:roleName=editor_stories v:displayName="Jonathan Tomko"
```

## Top Records

```ls
| project_name                                            | owner                                          | developer                                      | address                                | zip_code | council_district | kirwan_opportunity_index | distance_to_bus_stop | total_units | total_affordable_units | unit_type     | program | housing_type | status                                    | affordability_start_date | affordability_period | affordability_expiration_date | certification_date  | c_of_o_date         | required_amount_of_fee_in_lieu | date_fee_in_lieu_received | units_30_mfi | units_40_mfi | units_50_mfi | units_60_mfi | units_65_mfi | units_80_mfi | units_100_mfi | market_rate_units | city_funded_amount | of_funds_leveraged | clt | ddb | rny | mda | nbg | pudda | smart | tod | uno | vmu | 
| ======================================================= | ============================================== | ============================================== | ====================================== | ======== | ================ | ======================== | ==================== | =========== | ====================== | ============= | ======= | ============ | ========================================= | ======================== | ==================== | ============================= | =================== | =================== | ============================== | ========================= | ============ | ============ | ============ | ============ | ============ | ============ | ============= | ================= | ================== | ================== | === | === | === | === | === | ===== | ===== | === | === | === | 
| M Station                                               | Foundation Communities, Inc.                   | Foundation Communities, Inc.                   | 2906 E Martin Luther King Jr Boulevard | 78722    | 1                | Very High                | 1/4 Mile             | 150         | 140                    | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2009-11-16T00:00:00      | 99                   | 2008-11-16T00:00:00           | 2009-01-21T00:00:00 | 2011-09-02T00:00:00 |                                |                           | 28           | 0            | 68           | 36           | 0            | 8            | 0             | 10                | 2000000.00         | 868.83             | No  | No  | No  | No  | No  | No    | Yes   | Yes | No  | No  | 
| Garden Terrace Expansion (aka Garden Terrace, Phase II) | Garden Terrace Housing Corporation             | Foundation Communities, Inc.                   | 1015 W William Cannon Drive            | 78745    | 2                | Low                      | 1/4 Mile             | 15          | 15                     | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2007-10-08T00:00:00      | 30                   | 2037-10-08T00:00:00           |                     |                     |                                |                           | 0            | 0            | 15           | 0            | 0            | 0            | 0             | 0                 | 500000.00          | 160.00             | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| LifeWorks Transitional Living Project                   | Lifeworks                                      | Lifeworks                                      | 3710 S 2nd Street                      | 78704    | 3                | Very Low                 | Neither              | 12          | 12                     | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2006-05-04T00:00:00      | 20                   | 2026-05-04T00:00:00           |                     |                     |                                |                           | 0            | 0            | 12           | 0            | 0            | 0            | 0             | 0                 | 300000.00          | 101.22             | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| Cornerstone                                             | Mary Lee Community                             | Mary Lee Foundation                            | 1322 Lamar Square Drive                | 78704    | 5                | Very Low                 | 1/4 Mile             | 30          | 30                     | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2002-11-21T00:00:00      | 20                   | 2022-11-21T00:00:00           |                     |                     |                                |                           | 0            | 0            | 30           | 0            | 0            | 0            | 0             | 0                 | 1009502.00         | 0.00               | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| The Willows                                             | Mary Lee Community                             | Mary Lee Foundation                            | 1330 Lamar Square Drive                | 78704    | 5                | Moderate                 | 1/4 Mile             | 64          | 64                     | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2010-08-31T00:00:00      | 40                   | 1950-08-31T00:00:00           | 2006-09-08T00:00:00 |                     |                                |                           | 32           | 0            | 28           | 0            | 0            | 4            | 0             | 0                 | 2475000.00         | 90.37              | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| Arbor Terrace                                           | FC Austin One Housing Corporation              | Foundation Communities, Inc.                   | 2501 S IH-35                           | 78741    | 3                | Low                      | 1/2 Mile             | 120         | 120                    | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2011-06-24T00:00:00      | 99                   | 2010-06-24T00:00:00           | 2010-09-30T00:00:00 | 2012-06-29T00:00:00 |                                |                           | 0            | 0            | 120          | 0            | 0            | 0            | 0             | 0                 | 2898934.00         | 224.05             | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| Sierra Vista                                            | Foundation Communities                         | Foundation Communities, Inc.                   | 4320 S Congress Avenue                 | 78745    | 3                | Low                      | Neither              | 233         | 233                    | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2010-02-04T00:00:00      | 99                   | 2009-02-04T00:00:00           | 2009-06-10T00:00:00 | 2011-09-12T00:00:00 |                                |                           | 0            | 0            | 0            | 143          | 0            | 90           | 0             | 0                 | 3000000.00         | 329.13             | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| Crossroads Apartments                                   | Crossroads Mutual Housing Corporation          | Foundation Communities, Inc.                   | 8801 McCann Drive                      | 78757    | 7                | Very Low                 | Neither              | 14          | 14                     | Multifamily   | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2009-06-17T00:00:00      | 99                   | 2008-06-17T00:00:00           |                     |                     |                                |                           | 14           | 0            | 0            | 0            | 0            | 0            | 0             | 0                 | 900000.00          | 33.33              | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| 904 Lydia                                               | Guadalupe Neighborhood Development Corporation | Guadalupe Neighborhood Development Corporation | 904 Lydia Street                       | 78702    | 1                | Very Low                 | 1/4 Mile             | 1           | 1                      | Single Family | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2009-04-03T00:00:00      | 40                   | 2049-04-03T00:00:00           |                     |                     |                                |                           | 1            | 0            | 0            | 0            | 0            | 0            | 0             | 0                 | 60000.00           | 143.33             | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
| 1220 Paul Theresa Saldana Street                        | Guadalupe Neighborhood Development Corporation | Guadalupe Neighborhood Development Corporation | 1220 Paul Theresa Saldana Street       | 78702    | 3                | Very Low                 | 1/4 Mile             | 2           | 2                      | Duplex        | RHDA    | Rental       | Project Complete / Final C.of O. Received | 2013-01-25T00:00:00      | 99                   | 2012-01-25T00:00:00           | 2013-10-25T00:00:00 |                     |                                |                           | 0            | 0            | 2            | 0            | 0            | 0            | 0             | 0                 | 150000.00          | 215.33             | No  | No  | No  | No  | No  | No    | Yes   | No  | No  | No  | 
```