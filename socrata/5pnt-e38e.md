# Response To Resistance 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/response-to-resistance-2014) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5pnt-e38e) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5pnt-e38e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5pnt-e38e/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5pnt-e38e |
| Name | Response To Resistance 2014 |
| Created | 2015-10-26T14:16:57Z |
| Publication Date | 2015-10-29T14:44:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | numeric metric | rin                       | RIN                       | number        | number        |
| Yes      | numeric metric | primary_key               | Primary Key               | number        | number        |
| Yes      | time           | date_occurred             | Date Occurred             | calendar_date | calendar_date |
| No       |                | time_occurred             | Time Occurred             | number        | number        |
| Yes      | series tag     | location                  | Location                  | text          | text          |
| Yes      | series tag     | area_command              | Area Command              | text          | text          |
| Yes      | series tag     | nature_of_contact         | Nature of Contact         | text          | text          |
| Yes      | series tag     | reason_desc               | Reason Desc               | text          | text          |
| Yes      | numeric metric | r2r_level                 | R2R Level                 | number        | number        |
| Yes      | series tag     | master_subject_id         | Master Subject ID         | text          | text          |
| Yes      | series tag     | subject_sex               | Subject Sex               | text          | text          |
| Yes      | series tag     | subject_race              | Subject Race              | text          | text          |
| Yes      | series tag     | subject_ethnicity         | Subject Ethnicity         | text          | text          |
| Yes      | series tag     | subject_role              | Subject Role              | text          | text          |
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
series e:5pnt-e38e d:2014-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=CH t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="DISPATCHED CALL" t:location="E MARTIN LUTHER KING JR BLVD / CHICON ST" t:reason_desc="TO RESTRAIN FOR SUBJECTS SAFETY" t:officer_organization_desc="CHARLIE 300 REG III PATROL" t:master_subject_id="308019604: 201411884" t:subject_race=B t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_role=COMPLAINANT t:subject_ethnicity=N t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:number_shots=0 m:primary_key=201411884 m:officer_yrs_of_service=1 m:rin=142193

series e:5pnt-e38e d:2014-01-04T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=CH t:subject_resistance=OTHER t:nature_of_contact="TRAFFIC STOP" t:location="900 BLOCK BRASS ST" t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="CHARLIE 500 REG III PATROL" t:master_subject_id="32245649: 201441484" t:subject_race=W t:weapon_used_1="CED - PRONGS MISSED-ENTER # SHOTS" t:subject_sex=M t:subject_role=ARRESTED t:subject_ethnicity=N m:r2r_level=3 m:number_shots=1 m:primary_key=201441484 m:officer_yrs_of_service=2 m:rin=142151

series e:5pnt-e38e d:2014-01-04T00:00:00.000Z t:subject_effects="COMPLAINT OF INJURY/PAIN" t:effect_on_officer="COMPLAINT OF INJURY/PAIN" t:area_command=CH t:subject_resistance=OTHER t:nature_of_contact="TRAFFIC STOP" t:location="900 BLOCK BRASS ST" t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="CHARLIE 500 REG III PATROL" t:master_subject_id="32245649: 201441484" t:subject_race=W t:weapon_used_1="CED - PRONGS MISSED-ENTER # SHOTS" t:subject_sex=M t:subject_role=ARRESTED t:subject_ethnicity=N m:r2r_level=3 m:number_shots=1 m:primary_key=201441484 m:officer_yrs_of_service=2 m:rin=142152
```

## Meta Commands

```ls
metric m:rin p:integer l:RIN t:dataTypeName=number

metric m:primary_key p:long l:"Primary Key" t:dataTypeName=number

metric m:r2r_level p:integer l:"R2R Level" t:dataTypeName=number

metric m:number_shots p:integer l:"Number Shots" t:dataTypeName=number

metric m:officer_yrs_of_service p:integer l:"Officer Yrs of Service" t:dataTypeName=number

entity e:5pnt-e38e l:"Response To Resistance 2014" t:url=https://data.austintexas.gov/api/views/5pnt-e38e

property e:5pnt-e38e t:meta.view v:id=5pnt-e38e v:averageRating=0 v:name="Response To Resistance 2014"

property e:5pnt-e38e t:meta.view.owner v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"

property e:5pnt-e38e t:meta.view.tableauthor v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"
```

## Top Records

```ls
| rin    | primary_key | date_occurred       | time_occurred | location                                 | area_command | nature_of_contact | reason_desc                            | r2r_level | master_subject_id    | subject_sex | subject_race | subject_ethnicity | subject_role | subject_conduct_desc                       | subject_resistance                                                             | weapon_used_1                           | weapon_used_2                  | weapon_used_3              | weapon_used_4 | weapon_used_5 | number_shots | subject_effects                        | effect_on_officer           | officer_organization_desc  | officer_commission_date | officer_yrs_of_service | x_coordinate | y_coordinate | 
| ====== | =========== | =================== | ============= | ======================================== | ============ | ================= | ====================================== | ========= | ==================== | =========== | ============ | ================= | ============ | ========================================== | ============================================================================== | ======================================= | ============================== | ========================== | ============= | ============= | ============ | ====================================== | =========================== | ========================== | ======================= | ====================== | ============ | ============ | 
| 142193 | 201411884   | 2014-01-01T00:00:00 | 1808          | E MARTIN LUTHER KING JR BLVD / CHICON ST | CH           | DISPATCHED CALL   | TO RESTRAIN FOR SUBJECTS SAFETY        | 3         | 308019604: 201411884 | M           | B            | N                 | COMPLAINANT  | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | EMPTY HAND DEFENSIVE RESISTANCE                                                | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                |                            |               |               | 0            | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | CHARLIE 300 REG III PATROL | 2012-07-13T00:00:00     | 1                      | 3121019      | 10075181     | 
| 142151 | 201441484   | 2014-01-04T00:00:00 | 2106          | 900 BLOCK BRASS ST                       | CH           | TRAFFIC STOP      | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 32245649: 201441484  | M           | W            | N                 | ARRESTED     |                                            | OTHER                                                                          | CED - PRONGS MISSED-ENTER # SHOTS       |                                |                            |               |               | 1            | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | CHARLIE 500 REG III PATROL | 2012-03-23T00:00:00     | 2                      | 3126469      | 10069562     | 
| 142152 | 201441484   | 2014-01-04T00:00:00 | 2015          | 900 BLOCK BRASS ST                       | CH           | TRAFFIC STOP      | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 32245649: 201441484  | M           | W            | N                 | ARRESTED     |                                            | OTHER                                                                          | CED - PRONGS MISSED-ENTER # SHOTS       |                                |                            |               |               | 1            | COMPLAINT OF INJURY/PAIN               | COMPLAINT OF INJURY/PAIN    | CHARLIE 500 REG III PATROL | 2011-10-07T00:00:00     | 2                      | 3126469      | 10069562     | 
| 142169 | 201450163   | 2014-01-05T00:00:00 | 141           | SAHARA AVE / EMERALD FOREST DR           | FR           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 219239625: 201450163 | M           | W            | H                 | ARRESTED     |                                            | EMPTY HAND DEFENSIVE RESISTANCE                                                | CED - PRONGS MISSED-ENTER # SHOTS       | CED - DRIVE STUN-ENTER # SHOTS | CED - PRONGS-ENTER # SHOTS |               |               | 3            | MINOR INJURY; COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | FRANK 700 REG IV PATROL    | 2003-06-27T00:00:00     | 11                     | 3100019      | 10048050     | 
| 142153 | 201450163   | 2014-01-05T00:00:00 |               | SAHARA AVE / EMERALD FOREST DR           | FR           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459110463: 201450163 | M           | B            | N                 | ARRESTED     |                                            | EMPTY HAND DEFENSIVE RESISTANCE                                                | CED - PRONGS MISSED-ENTER # SHOTS       |                                |                            |               |               | 1            | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | FRANK 700 REG IV PATROL    | 2012-11-30T00:00:00     | 1                      | 3100019      | 10048050     | 
| 142130 | 201441870   | 2014-01-04T00:00:00 | 2312          | 500 BLOCK BRAZOS ST                      | GE           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459115090: 201441870 | M           | W            | N                 | ARRESTED     | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | OTHER                                                                          | CED - PRONGS-ENTER # SHOTS              |                                |                            |               |               | 1            | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | GEORGE 300 REG I PATROL    | 2007-04-27T00:00:00     | 7                      | 3114590      | 10070379     | 
| 142155 | 201451523   | 2014-01-05T00:00:00 |               | 2100 BLOCK ELMONT DR                     | HE           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 160629604: 201451523 | M           | W            | H                 | ARRESTED     | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | OTHER                                                                          | CED - PRONGS-ENTER # SHOTS              |                                |                            |               |               | 1            | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | HENRY 400 REG III PATROL   | 2012-07-13T00:00:00     | 1                      | 3120033      | 10061229     | 
| 142190 | 201461448   | 2014-01-06T00:00:00 | 2200          | 8900 N IH 35 SVRD SB                     | ED           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 366155572: 201461448 | F           | W            | H                 | JUV-ARRESTE  | EDP/MENTALLY UNSTABLE                      | VERBAL RESISTANCE/AGGRESSION; PASSIVE RESISTANCE; EMPTY HAND ACTIVE AGGRESSION | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                |                            |               |               |              | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | EDWARD 300 REG II PATROL   | 2013-12-13T00:00:00     | 0                      | 3129388      | 10102200     | 
| 142208 | 201461448   | 2014-01-06T00:00:00 | 2328          | 8900 N IH 35 SVRD SB                     | ED           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 366155572: 201461448 | F           | W            | H                 | JUV-ARRESTE  | EDP/MENTALLY UNSTABLE                      | EMPTY HAND DEFENSIVE RESISTANCE                                                | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                |                            |               |               |              | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | EDWARD 300 REG II PATROL   | 2013-03-22T00:00:00     | 1                      | 3129388      | 10102200     | 
| 142209 | 201461448   | 2014-01-06T00:00:00 | 2115          | 8900 N IH 35 SVRD SB                     | ED           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 366155572: 201461448 | F           | W            | H                 | JUV-ARRESTE  | EDP/MENTALLY UNSTABLE                      | EMPTY HAND ACTIVE AGGRESSION                                                   | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |                                |                            |               |               |              | NO COMPLAINT OF INJURY/PAIN            | NO COMPLAINT OF INJURY/PAIN | EDWARD 400 REG II PATROL   | 2012-03-23T00:00:00     | 2                      | 3129388      | 10102200     | 
```