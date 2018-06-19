# R2R 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/r2r-2010) |
| Metadata | [Link](https://data.austintexas.gov/api/views/q5ym-htjz) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/q5ym-htjz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/q5ym-htjz/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | q5ym-htjz |
| Name | R2R 2010 |
| Attribution | Austin Police Department |
| Category | Government |
| Tags | police, r2r, response to resistance |
| Created | 2016-09-20T20:00:37Z |
| Publication Date | 2016-09-20T20:04:20Z |

## Description

ResponsAUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided are for informational use only and may differ from official APD crime data.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.
e to Resistance dataset for 2010

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | numeric metric | rin                       | RIN                       | number        | text          |
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
series e:q5ym-htjz d:2010-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="DISPATCHED CALL" t:location="611 E 7TH ST" t:councildistrict=9 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 500 REG I PATROL" t:master_subject_id="51317081: 201010440" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=N t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201010440 m:officer_yrs_of_service=6 m:rin=34938

series e:q5ym-htjz d:2010-01-01T00:00:00.000Z t:subject_effects="COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND ACTIVE AGGRESSION" t:nature_of_contact="VIEWED OFFENSE" t:location="400 BLOCK E 6TH ST" t:councildistrict=9 t:reason_desc="NECESSARY TO DEFEND ANOTHER" t:officer_organization_desc="GEORGE 500 REG I PATROL" t:master_subject_id="383517875: 201010408" t:subject_race=W t:weapon_used_1="CHEMICAL AGENT - O C SPRAY" t:subject_sex=M t:subject_ethnicity=H t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201010408 m:officer_yrs_of_service=3 m:rin=34958

series e:q5ym-htjz d:2010-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance=OTHER t:nature_of_contact="VIEWED OFFENSE" t:location="400 BLOCK E 6TH ST" t:councildistrict=9 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 500 REG I PATROL" t:master_subject_id="186784999: 201010408" t:subject_race=B t:weapon_used_1="CHEMICAL AGENT - O C SPRAY" t:subject_sex=M t:subject_ethnicity=N t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201010408 m:officer_yrs_of_service=3 m:rin=34959
```

## Meta Commands

```ls
metric m:rin p:integer l:RIN t:dataTypeName=number

metric m:primary_key p:long l:"Primary Key" t:dataTypeName=number

metric m:r2r_level p:integer l:"R2R Level" t:dataTypeName=number

metric m:number_shots p:integer l:"Number Shots" t:dataTypeName=number

metric m:officer_yrs_of_service p:integer l:"Officer Yrs of Service" t:dataTypeName=number

entity e:q5ym-htjz l:"R2R 2010" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/q5ym-htjz

property e:q5ym-htjz t:meta.view v:id=q5ym-htjz v:category=Government v:averageRating=0 v:name="R2R 2010" v:attribution="Austin Police Department"

property e:q5ym-htjz t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:q5ym-htjz t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| rin   | primary_key | date_occurred       | time_occurred | location                         | area_command | nature_of_contact  | reason_desc                            | r2r_level | master_subject_id      | subject_sex | subject_race | subject_ethnicity | subject_conduct_desc                       | subject_resistance                                            | weapon_used_1                           | weapon_used_2                           | weapon_used_3 | weapon_used_4 | weapon_used_5 | number_shots | subject_effects             | effect_on_officer                         | officer_organization_desc            | officer_commission_date | officer_yrs_of_service | x_coordinate | y_coordinate | councildistrict | 
| ===== | =========== | =================== | ============= | ================================ | ============ | ================== | ====================================== | ========= | ====================== | =========== | ============ | ================= | ========================================== | ============================================================= | ======================================= | ======================================= | ============= | ============= | ============= | ============ | =========================== | ========================================= | ==================================== | ======================= | ====================== | ============ | ============ | =============== | 
| 34938 | 201010440   | 2010-01-01T00:00:00 | 0128          | 611 E 7TH ST                     | GE           | DISPATCHED CALL    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 51317081: 201010440    | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                         |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | GEORGE 500 REG I PATROL              | 2004-06-18T00:00:00     | 6                      | 3116365      | 10070461     | 9               | 
| 34958 | 201010408   | 2010-01-01T00:00:00 |               | 400 BLOCK E 6TH ST               | GE           | VIEWED OFFENSE     | NECESSARY TO DEFEND ANOTHER            | 3         | 383517875: 201010408   | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | EMPTY HAND ACTIVE AGGRESSION                                  | CHEMICAL AGENT - O C SPRAY              |                                         |               |               |               |              | COMPLAINT OF INJURY/PAIN    | NO COMPLAINT OF INJURY/PAIN               | GEORGE 500 REG I PATROL              | 2007-04-27T00:00:00     | 3                      | 3115491      | 10070521     | 9               | 
| 34959 | 201010408   | 2010-01-01T00:00:00 |               | 400 BLOCK E 6TH ST               | GE           | VIEWED OFFENSE     | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 186784999: 201010408   | M           | B            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | OTHER                                                         | CHEMICAL AGENT - O C SPRAY              |                                         |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | GEORGE 500 REG I PATROL              | 2007-04-27T00:00:00     | 3                      | 3115491      | 10070521     | 9               | 
| 34979 | 20106900003 | 2010-01-01T00:00:00 |               | 1650 RUTLAND DR                  | ED           | TACTICAL OPERATION | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 154599692: 20106900003 | M           | B            | N                 |                                            | PASSIVE RESISTANCE                                            | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                         |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | CHARLIE DISTRICT REPS REG III PATROL | 2004-06-18T00:00:00     | 6                      | 3123341      | 10109252     | 4               | 
| 34980 | 201011525   | 2010-01-01T00:00:00 | 1206          | 1200 BLOCK RADCLIFF DR           | ID           | VIEWED OFFENSE     | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 255001933: 201011525   | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | EMPTY HAND DEFENSIVE RESISTANCE                               | CED - PRONGS-ENTER # SHOTS              | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               | 1            | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | EDWARD 200 REG II PATROL             | 2008-01-04T00:00:00     | 2                      | 3129597      | 10092895     | 4               | 
| 35098 | 201011525   | 2010-01-01T00:00:00 |               | 1200 BLOCK RADCLIFF DR           | ID           | VIEWED OFFENSE     | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 255001933: 201011525   | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                         |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | EDWARD 200 REG II PATROL             | 1997-07-25T00:00:00     | 12                     | 3129597      | 10092895     | 4               | 
| 35138 | 201012896   | 2010-01-01T00:00:00 |               | 2013 COVERED WAGON PASS          | FR           | DISPATCHED CALL    | NECESSARY TO EFFECT ARREST / DETENTION | 2         | 222691594: 201012896   | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | OTHER                                                         | CED - PRONGS-ENTER # SHOTS              |                                         |               |               |               | 2            | COMPLAINT OF INJURY/PAIN    | NO COMPLAINT OF INJURY/PAIN               | FRANK 700 REG IV PATROL              | 2008-01-04T00:00:00     | 2                      | 3109677      | 10043582     | 2               | 
| 35180 | 201010390   | 2010-01-01T00:00:00 |               | N MOPAC EXPY SVRD NB / STECK AVE | BA           | TRAFFIC STOP       | NECESSARY TO EFFECT ARREST / DETENTION | 2         | 153167853: 201010390   | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | EMPTY HAND DEFENSIVE RESISTANCE                               | CED - PRONGS-ENTER # SHOTS              |                                         |               |               |               | 1            | NO COMPLAINT OF INJURY/PAIN | MINOR INJURY; NO COMPLAINT OF INJURY/PAIN | BAKER 700 REG I PATROL               | 1999-07-09T00:00:00     | 10                     | 3113746      | 10107070     | 10              | 
| 35305 | 20106900003 | 2010-01-01T00:00:00 | 2222          | 1650 RUTLAND DR                  | ED           | TACTICAL OPERATION | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 154599692: 20106900003 | M           | B            | N                 |                                            | PASSIVE RESISTANCE                                            | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                         |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | CHARLIE DISTRICT REPS REG III PATROL | 2005-07-08T00:00:00     | 4                      | 3123341      | 10109252     | 4               | 
| 36108 | 201012766   | 2010-01-01T00:00:00 |               | 31 BLOCK N IH 35 SVRD NB         | GE           | DISPATCHED CALL    | TO RESTRAIN FOR SUBJECTS SAFETY        | 3         | 17433733: 201012766    | M           | B            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                         |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN               | CHARLIE 400 REG III PATROL           | 2008-01-04T00:00:00     | 2                      | 3116537      | 10065712     | 3               | 
```