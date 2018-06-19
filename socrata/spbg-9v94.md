# Annual Crime Dataset 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-crime-dataset-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/spbg-9v94) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/spbg-9v94/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/spbg-9v94/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | spbg-9v94 |
| Name | Annual Crime Dataset 2015 |
| Attribution | Austin Police Department |
| Category | Public Safety |
| Tags | police, crime |
| Created | 2016-07-05T16:51:45Z |
| Publication Date | 2016-11-28T13:06:58Z |

## Description

This dataset encompasses all of the Part 1 crimes in Austin, Texas from January 1 2015 - December 31 2015.  

AUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided are for informational use only and may differ from official APD crime data.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | numeric metric | go_primary_key                        | GO Primary Key                        | number    | number      |
| Yes      | series tag     | council_district                      | Council District                      | text      | number      |
| Yes      | series tag     | go_highest_offense_desc               | GO Highest Offense Desc               | text      | text        |
| Yes      | series tag     | highest_nibrs_ucr_offense_description | Highest NIBRS/UCR Offense Description | text      | text        |
| No       |                | go_report_date                        | GO Report Date                        | text      | text        |
| Yes      | series tag     | go_location                           | GO Location                           | text      | text        |
| Yes      | series tag     | clearance_status                      | Clearance Status                      | text      | text        |
| No       |                | clearance_date                        | Clearance Date                        | text      | text        |
| Yes      | series tag     | go_district                           | GO District                           | text      | text        |
| Yes      | series tag     | go_location_zip                       | GO Location Zip                       | text      | text        |
| Yes      | numeric metric | go_census_tract                       | GO Census Tract                       | number    | number      |
| Yes      | numeric metric | go_x_coordinate                       | GO X Coordinate                       | number    | number      |
| Yes      | numeric metric | go_y_coordinate                       | GO Y Coordinate                       | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = go_report_date,clearance_date
```

## Data Commands

```ls
series e:spbg-9v94 d:2015-01-01T00:00:00.000Z t:go_location_zip=78753 t:go_highest_offense_desc="AGG ROBBERY/DEADLY WEAPON" t:go_location="9001 N IH 35 SVRD NB" t:council_district=4 t:highest_nibrs_ucr_offense_description=Robbery t:clearance_status=N t:go_district=E m:go_primary_key=201510782 m:go_y_coordinate=10102366 m:go_x_coordinate=3130483 m:go_census_tract=18.13

series e:spbg-9v94 d:2015-01-01T00:00:00.000Z t:go_location_zip=78751 t:go_highest_offense_desc="ROBBERY BY ASSAULT" t:go_location="919 E KOENIG LN SVRD EB" t:council_district=4 t:highest_nibrs_ucr_offense_description=Robbery t:clearance_status=N t:go_district=I m:go_primary_key=201511231 m:go_y_coordinate=10090296 m:go_x_coordinate=3124730 m:go_census_tract=21.05

series e:spbg-9v94 d:2015-01-01T00:00:00.000Z t:go_location_zip=78753 t:go_highest_offense_desc="BURGLARY OF RESIDENCE" t:go_location="12151 N IH 35 SVRD NB" t:council_district=1 t:highest_nibrs_ucr_offense_description=Burglary t:clearance_status=N t:go_district=E m:go_primary_key=201511736 m:go_y_coordinate=10117220 m:go_x_coordinate=3135985 m:go_census_tract=18.35
```

## Meta Commands

```ls
metric m:go_primary_key p:long l:"GO Primary Key" d:"Incident Number" t:dataTypeName=number

metric m:go_census_tract p:double l:"GO Census Tract" t:dataTypeName=number

metric m:go_x_coordinate p:integer l:"GO X Coordinate" d:"Incident location using projection NAD 1983 State Plane Texas Central FIPS 4203 (US Feet)" t:dataTypeName=number

metric m:go_y_coordinate p:integer l:"GO Y Coordinate" d:"Incident location using projection NAD 1983 State Plane Texas Central FIPS 4203 (US Feet)" t:dataTypeName=number

entity e:spbg-9v94 l:"Annual Crime Dataset 2015" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/spbg-9v94

property e:spbg-9v94 t:meta.view v:id=spbg-9v94 v:category="Public Safety" v:averageRating=0 v:name="Annual Crime Dataset 2015" v:attribution="Austin Police Department"

property e:spbg-9v94 t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:spbg-9v94 t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| go_primary_key | council_district | go_highest_offense_desc   | highest_nibrs_ucr_offense_description | go_report_date | go_location              | clearance_status | clearance_date | go_district | go_location_zip | go_census_tract    | go_x_coordinate | go_y_coordinate | 
| ============== | ================ | ========================= | ===================================== | ============== | ======================== | ================ | ============== | =========== | =============== | ================== | =============== | =============== | 
| 201510782      | 4                | AGG ROBBERY/DEADLY WEAPON | Robbery                               | 1-Jan-15       | 9001 N IH 35 SVRD NB     | N                | 28-Jan-15      | E           | 78753           | 18.13              | 3130483         | 10102366        | 
| 201511231      | 4                | ROBBERY BY ASSAULT        | Robbery                               | 1-Jan-15       | 919 E KOENIG LN SVRD EB  | N                | 13-Jan-15      | I           | 78751           | 21.05              | 3124730         | 10090296        | 
| 201511736      | 1                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 12151 N IH 35 SVRD NB    | N                | 13-Jan-15      | E           | 78753           | 18.350000000000001 | 3135985         | 10117220        | 
| 201511433      | 4                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 1044 NORWOOD PARK BLVD   | N                | 5-Jan-15       | I           | 78753           | 18.13              | 3129896         | 10096032        | 
| 201511936      | 2                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 2413 BITTER CREEK DR     | N                | 7-Jan-15       | F           | 78744           | 24.27              | 3110455         | 10039340        | 
| 201511398      | 3                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 4600 ELMONT DR           | N                | 7-Jan-15       | H           | 78741           | 23.17              | 3122853         | 10060648        | 
| 201511363      | 9                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 1500 E RIVERSIDE DR      | N                | 25-Feb-15      | H           | 78741           | 23.04              | 3117897         | 10063203        | 
| 201510756      | 7                | BURGLARY NON RESIDENCE    | Burglary                              | 1-Jan-15       | 2500 W PARMER LN         | N                | 16-Jan-15      | A           | 78727           | 18.48              | 3125825         | 10127011        | 
| 201510608      | 1                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 1400 MARCUS PL           | N                | 13-Jan-15      | C           | 78721           | 21.09              | 3131757         | 10075823        | 
| 201511584      | 2                | BURGLARY OF RESIDENCE     | Burglary                              | 1-Jan-15       | 4600 NUCKOLS CROSSING RD | N                | 7-Jan-15       | F           | 78744           | 24.13              | 3117292         | 10045926        | 
```