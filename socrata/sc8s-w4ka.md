# R2 R 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/r2-r-2009) |
| Metadata | [Link](https://data.austintexas.gov/api/views/sc8s-w4ka) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/sc8s-w4ka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/sc8s-w4ka/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | sc8s-w4ka |
| Name | R2 R 2009 |
| Attribution | Austin Police Department |
| Category | Government |
| Tags | police, r2r, response to resistance |
| Created | 2016-09-20T19:54:38Z |
| Publication Date | 2016-09-20T19:59:52Z |

## Description

Response to Resistance dataset for 2009.  
AUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided are for informational use only and may differ from official APD crime data.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

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
series e:sc8s-w4ka d:2009-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="VIEWED OFFENSE" t:location="200 W 4TH ST" t:councildistrict=9 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 400 REG I PATROL" t:master_subject_id="305859998: 200910720" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=H t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=200910720 m:officer_yrs_of_service=16 m:rin=19654

series e:sc8s-w4ka d:2009-01-01T00:00:00.000Z t:subject_effects="MINOR INJURY" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=ID t:subject_resistance="EMPTY HAND ACTIVE AGGRESSION" t:nature_of_contact="DISPATCHED CALL" t:location="6309 BURNS ST" t:councildistrict=4 t:reason_desc="NECESSARY TO DEFEND REPORTING OFFICER" t:officer_organization_desc="BAKER 700 REG I PATROL" t:master_subject_id="66128268: 200910883" t:subject_race=W t:weapon_used_1="CED - PRONGS-ENTER # SHOTS" t:subject_sex=M t:subject_ethnicity=H t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=2 m:number_shots=1 m:primary_key=200910883 m:officer_yrs_of_service=2 m:rin=19656

series e:sc8s-w4ka d:2009-01-01T00:00:00.000Z t:subject_effects="MINOR INJURY" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=ID t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="DISPATCHED CALL" t:location="6309 BURNS ST" t:councildistrict=4 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="BAKER 700 REG I PATROL" t:master_subject_id="66128268: 200910883" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=H t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=1 m:number_shots=0 m:primary_key=200910883 m:officer_yrs_of_service=1 m:rin=19734
```

## Meta Commands

```ls
metric m:rin p:integer l:RIN t:dataTypeName=number

metric m:primary_key p:long l:"Primary Key" t:dataTypeName=number

metric m:r2r_level p:integer l:"R2R Level" t:dataTypeName=number

metric m:number_shots p:integer l:"Number Shots" t:dataTypeName=number

metric m:officer_yrs_of_service p:integer l:"Officer Yrs of Service" t:dataTypeName=number

entity e:sc8s-w4ka l:"R2 R 2009" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/sc8s-w4ka

property e:sc8s-w4ka t:meta.view v:id=sc8s-w4ka v:category=Government v:averageRating=0 v:name="R2 R 2009" v:attribution="Austin Police Department"

property e:sc8s-w4ka t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:sc8s-w4ka t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| rin   | primary_key | date_occurred       | time_occurred | location           | area_command | nature_of_contact | reason_desc                            | r2r_level | master_subject_id    | subject_sex | subject_race | subject_ethnicity | subject_conduct_desc                                              | subject_resistance                                            | weapon_used_1                           | weapon_used_2 | weapon_used_3 | weapon_used_4 | weapon_used_5 | number_shots | subject_effects             | effect_on_officer           | officer_organization_desc | officer_commission_date | officer_yrs_of_service | x_coordinate | y_coordinate | councildistrict | 
| ===== | =========== | =================== | ============= | ================== | ============ | ================= | ====================================== | ========= | ==================== | =========== | ============ | ================= | ================================================================= | ============================================================= | ======================================= | ============= | ============= | ============= | ============= | ============ | =========================== | =========================== | ========================= | ======================= | ====================== | ============ | ============ | =============== | 
| 19654 | 200910720   | 2009-01-01T00:00:00 |               | 200 W 4TH ST       | GE           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 305859998: 200910720 | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 400 REG I PATROL   | 1993-01-08T00:00:00     | 16                     | 3113640      | 10070272     | 9               | 
| 19656 | 200910883   | 2009-01-01T00:00:00 | 0330          | 6309 BURNS ST      | ID           | DISPATCHED CALL   | NECESSARY TO DEFEND REPORTING OFFICER  | 2         | 66128268: 200910883  | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND ACTIVE AGGRESSION                                  | CED - PRONGS-ENTER # SHOTS              |               |               |               |               | 1            | MINOR INJURY                | NO COMPLAINT OF INJURY/PAIN | BAKER 700 REG I PATROL    | 2007-04-27T00:00:00     | 2                      | 3120652      | 10093724     | 4               | 
| 19734 | 200910883   | 2009-01-01T00:00:00 |               | 6309 BURNS ST      | ID           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 1         | 66128268: 200910883  | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               | 0            | MINOR INJURY                | NO COMPLAINT OF INJURY/PAIN | BAKER 700 REG I PATROL    | 2008-06-20T00:00:00     | 1                      | 3120652      | 10093724     | 4               | 
| 19735 | 200911936   | 2009-01-01T00:00:00 | 1640          | 6710 ARROYO SECO   | ID           | DISPATCHED CALL   | OTHER (DOCUMENT IN SUPPLEMENT)         | 3         | 219233449: 200911936 | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | PASSIVE RESISTANCE                                            | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | BAKER 300 REG I PATROL    | 2004-06-18T00:00:00     | 5                      | 3117560      | 10097233     | 7               | 
| 19736 | 200911936   | 2009-01-01T00:00:00 | 1635          | 6710 ARROYO SECO   | ID           | DISPATCHED CALL   | OTHER (DOCUMENT IN SUPPLEMENT)         | 3         | 314316133: 200911936 | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | PASSIVE RESISTANCE                                            | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | BAKER 300 REG I PATROL    | 2008-01-04T00:00:00     | 1                      | 3117560      | 10097233     | 7               | 
| 19738 | 200910463   | 2009-01-01T00:00:00 | 0200          | 400 E 30TH ST      | BA           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 218433454: 200910463 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | BAKER 500 REG I PATROL    | 2003-06-27T00:00:00     | 6                      | 3116579      | 10079774     | 9               | 
| 19739 | 200910463   | 2009-01-01T00:00:00 |               | 400 E 30TH ST      | BA           | DISPATCHED CALL   | TO RESTRAIN FOR SUBJECTS SAFETY        | 3         | 218433454: 200910463 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | BAKER 500 REG I PATROL    | 2008-06-20T00:00:00     | 1                      | 3116579      | 10079774     | 9               | 
| 19916 | 200911936   | 2009-01-01T00:00:00 | 1612          | 6710 ARROYO SECO   | ID           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 314316133: 200911936 | M           | W            | H                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | PASSIVE RESISTANCE                                            | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | BAKER 300 REG I PATROL    | 2007-04-27T00:00:00     | 2                      | 3117560      | 10097233     | 7               | 
| 20066 | 200911717   | 2009-01-01T00:00:00 |               | 110 W SLAUGHTER LN | FR           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 52822386: 200911717  | F           | W            | H                 | EDP/MENTALLY UNSTABLE; SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | FRANK 200 REG IV PATROL   | 2002-09-06T00:00:00     | 6                      | 3100912      | 10033835     | 2               | 
| 20535 | 200910873   | 2009-01-01T00:00:00 |               | 3401 RED RIVER ST  | BA           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 183566801: 200910873 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND ACTIVE AGGRESSION    | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               | 0            | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | BAKER 700 REG I PATROL    | 2007-04-27T00:00:00     | 2                      | 3119664      | 10079872     | 9               | 
```