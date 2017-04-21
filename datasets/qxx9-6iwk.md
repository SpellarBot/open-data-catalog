# R2R 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/r2r-2013) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qxx9-6iwk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qxx9-6iwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qxx9-6iwk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qxx9-6iwk |
| Name | R2R 2013 |
| Attribution | Austin Police Department |
| Category | Government |
| Tags | police, r2r, response to resistance |
| Created | 2016-09-20T20:09:31Z |
| Publication Date | 2016-09-20T20:11:03Z |

## Description

Response to Resistance dataset for 2013.  
AUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided are for informational use only and may differ from official APD crime data.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | numeric metric | rin                       | RIN                       | number        | number        |
| Yes      | numeric metric | primary_key               | Primary Key               | number        | number        |
| Yes      | time           | date_occurred             | Date Occurred             | calendar_date | calendar_date |
| No       |                | time_occurred             | Time Occurred             | text          | text          |
| Yes      | series tag     | location                  | Location                  | text          | text          |
| Yes      | series tag     | area_command              | Area Command              | text          | text          |
| Yes      | series tag     | nature_of_contact         | Nature of Contact         | text          | text          |
| Yes      | series tag     | reason_desc               | Reason Desc               | text          | text          |
| Yes      | numeric metric | r2r_level                 | R2R Level                 | number        | number        |
| Yes      | series tag     | master_subject_id         | Master Subject ID         | text          | text          |
| Yes      | series tag     | subject_sex               | Subject Sex               | text          | text          |
| Yes      | series tag     | subject_race              | Subject Race              | text          | text          |
| Yes      | series tag     | subject_ethnicity         | Subject Ethnicity         | text          | text          |
| Yes      | series tag     | subject_conduct_desc      | Subject Conduct Desc      | text          | text          |
| Yes      | series tag     | subject_resistance        | Subject Resistance        | text          | text          |
| Yes      | series tag     | weapon_used_1             | Weapon Used 1             | text          | text          |
| Yes      | series tag     | weapon_used_2             | Weapon Used 2             | text          | text          |
| Yes      | series tag     | weapon_used_3             | Weapon Used 3             | text          | text          |
| Yes      | series tag     | weapon_used_4             | Weapon Used 4             | text          | text          |
| Yes      | series tag     | weapon_used_5             | Weapon Used 5             | text          | text          |
| Yes      | numeric metric | number_shots              | Number Shots              | number        | number        |
| Yes      | series tag     | subject_effects           | Subject Effects           | text          | text          |
| Yes      | series tag     | effect_on_officer         | Effect on Officer         | text          | text          |
| Yes      | series tag     | officer_organization_desc | Officer Organization Desc | text          | text          |
| No       |                | officer_commission_date   | Officer Commission Date   | calendar_date | calendar_date |
| Yes      | numeric metric | officer_yrs_of_service    | Officer Yrs of Service    | number        | number        |
| No       |                | x_coordinate              | X-Coordinate              | number        | number        |
| No       |                | y_coordinate              | Y-Coordinate              | number        | number        |
| Yes      | series tag     | councildistrict           | CouncilDistrict           | text          | number        |
```

## Time Field

```ls
Value = date_occurred
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = time_occurred,officer_commission_date,x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:qxx9-6iwk d:2013-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="DISPATCHED CALL" t:location="1706 RIVERVIEW ST" t:councildistrict=3 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 200 REG I PATROL" t:master_subject_id="72352188: 201311360" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=H t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201311360 m:officer_yrs_of_service=5 m:rin=116123

series e:qxx9-6iwk d:2013-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="DISPATCHED CALL" t:location="1706 RIVERVIEW ST" t:councildistrict=3 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 200 REG I PATROL" t:master_subject_id="72352188: 201311360" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=H t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201311360 m:officer_yrs_of_service=13 m:rin=116124

series e:qxx9-6iwk d:2013-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=FR t:subject_resistance="PASSIVE RESISTANCE; EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="DISPATCHED CALL" t:location="1909 BITTER CREEK DR" t:councildistrict=2 t:reason_desc="IN CUSTODY, MAINTAINING CONTROL" t:officer_organization_desc="FRANK 700 REG IV PATROL" t:master_subject_id="33108704: 201312275" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=F t:subject_ethnicity=N t:subject_conduct_desc="EDP/MENTALLY UNSTABLE; SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201312275 m:officer_yrs_of_service=1 m:rin=116164
```

## Meta Commands

```ls
metric m:rin p:integer l:RIN t:dataTypeName=number

metric m:primary_key p:long l:"Primary Key" t:dataTypeName=number

metric m:r2r_level p:integer l:"R2R Level" t:dataTypeName=number

metric m:number_shots p:integer l:"Number Shots" t:dataTypeName=number

metric m:officer_yrs_of_service p:integer l:"Officer Yrs of Service" t:dataTypeName=number

entity e:qxx9-6iwk l:"R2R 2013" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/qxx9-6iwk

property e:qxx9-6iwk t:meta.view v:id=qxx9-6iwk v:category=Government v:averageRating=0 v:name="R2R 2013" v:attribution="Austin Police Department"

property e:qxx9-6iwk t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:qxx9-6iwk t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| rin    | primary_key | date_occurred       | time_occurred | location              | area_command | nature_of_contact | reason_desc                            | r2r_level | master_subject_id    | subject_sex | subject_race | subject_ethnicity | subject_conduct_desc                                              | subject_resistance                                            | weapon_used_1                           | weapon_used_2 | weapon_used_3 | weapon_used_4 | weapon_used_5 | number_shots | subject_effects             | effect_on_officer           | officer_organization_desc  | officer_commission_date | officer_yrs_of_service | x_coordinate | y_coordinate | councildistrict | 
| ====== | =========== | =================== | ============= | ===================== | ============ | ================= | ====================================== | ========= | ==================== | =========== | ============ | ================= | ================================================================= | ============================================================= | ======================================= | ============= | ============= | ============= | ============= | ============ | =========================== | =========================== | ========================== | ======================= | ====================== | ============ | ============ | =============== | 
| 116123 | 201311360   | 2013-01-01T00:00:00 |               | 1706 RIVERVIEW ST     | GE           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 72352188: 201311360  | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 200 REG I PATROL    | 2008-01-04T00:00:00     | 5                      | 3119003      | 10065187     | 3               | 
| 116124 | 201311360   | 2013-01-01T00:00:00 | 1000          | 1706 RIVERVIEW ST     | GE           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 72352188: 201311360  | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 200 REG I PATROL    | 1999-07-09T00:00:00     | 13                     | 3119003      | 10065187     | 3               | 
| 116164 | 201312275   | 2013-01-01T00:00:00 |               | 1909 BITTER CREEK DR  | FR           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 33108704: 201312275  | F           | W            | N                 | EDP/MENTALLY UNSTABLE; SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | PASSIVE RESISTANCE; EMPTY HAND DEFENSIVE RESISTANCE           | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | FRANK 700 REG IV PATROL    | 2011-10-07T00:00:00     | 1                      | 3107685      | 10040480     | 2               | 
| 116165 | 201312275   | 2013-01-01T00:00:00 | 2253          | 1909 BITTER CREEK DR  | FR           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 33108704: 201312275  | F           | W            | N                 | EDP/MENTALLY UNSTABLE                                             | PASSIVE RESISTANCE; EMPTY HAND DEFENSIVE RESISTANCE           | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | FRANK 700 REG IV PATROL    | 2011-10-07T00:00:00     | 1                      | 3107685      | 10040480     | 2               | 
| 116208 | 201310137   | 2013-01-01T00:00:00 | 0244          | 1420 E ANDERSON LN WB | ID           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 187108126: 201310137 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | PASSIVE RESISTANCE                                            | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | EDWARD 500 REG II PATROL   | 2010-04-23T00:00:00     | 3                      | 3131509      | 10094942     | 4               | 
| 116223 | 201311360   | 2013-01-01T00:00:00 |               | 1706 RIVERVIEW ST     | GE           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 72352188: 201311360  | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                               | CED - DRIVE STUN-ENTER # SHOTS          |               |               |               |               | 2            | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 200 REG I PATROL    | 2002-05-10T00:00:00     | 11                     | 3119003      | 10065187     | 3               | 
| 116263 | 201310136   | 2013-01-01T00:00:00 | 0023          | 314 E 6TH ST          | GE           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 170134309: 201310136 | M           | B            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND ACTIVE AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 400 REG I PATROL    | 2010-04-23T00:00:00     | 3                      | 3115292      | 10070580     | 9               | 
| 116403 | 201310496   | 2013-01-01T00:00:00 |               | 1100 BLOCK ELEANOR ST | CH           | DISPATCHED CALL   | NECESSARY TO DEFEND ANOTHER            | 3         | 32179026: 201310496  | M           | B            | N                 |                                                                   | EMPTY HAND ACTIVE AGGRESSION                                  | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | CHARLIE 600 REG III PATROL | 2011-10-07T00:00:00     | 1                      | 3133913      | 10072113     | 1               | 
| 116483 | 201310136   | 2013-01-01T00:00:00 | 0023          | 314 E 6TH ST          | GE           | OTHER             | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 5040419: 201310136   | F           | W            | N                 |                                                                   | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 400 REG I PATROL    | 2010-04-23T00:00:00     | 3                      | 3115292      | 10070580     | 9               | 
| 116824 | 201310136   | 2013-01-01T00:00:00 | 0147          | 314 E 6TH ST          | GE           | OTHER             | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 170134309: 201310136 | M           | B            | N                 |                                                                   | EMPTY HAND ACTIVE AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 400 REG I PATROL    | 2010-04-23T00:00:00     | 3                      | 3115292      | 10070580     | 9               | 
```