# R2R 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/r2r-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/iydp-s2cf) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/iydp-s2cf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/iydp-s2cf/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | iydp-s2cf |
| Name | R2R 2015 |
| Attribution | Austin Police Department |
| Tags | police, r2r, response to resistance |
| Created | 2016-09-20T20:14:14Z |
| Publication Date | 2016-09-20T20:16:18Z |

## Description

Response to Resistance dataset for 2015.
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
series e:iydp-s2cf d:2015-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="VIEWED OFFENSE" t:location="E 6TH ST / TRINITY ST" t:councildistrict=9 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 600 REG I PATROL" t:master_subject_id="459228703: 201510652" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=N t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201510652 m:officer_yrs_of_service=2 m:rin=154619

series e:iydp-s2cf d:2015-01-01T00:00:00.000Z t:subject_effects="MINOR INJURY" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND ACTIVE AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="VIEWED OFFENSE" t:location="E 6TH ST / TRINITY ST" t:councildistrict=9 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 700 REG I PATROL" t:master_subject_id="459228703: 201510652" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=N t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201510652 m:officer_yrs_of_service=13 m:rin=154620

series e:iydp-s2cf d:2015-01-01T00:00:00.000Z t:subject_effects="NO COMPLAINT OF INJURY/PAIN" t:effect_on_officer="NO COMPLAINT OF INJURY/PAIN" t:area_command=GE t:subject_resistance="EMPTY HAND DEFENSIVE RESISTANCE" t:nature_of_contact="VIEWED OFFENSE" t:location="E 6TH ST / TRINITY ST" t:councildistrict=9 t:reason_desc="NECESSARY TO EFFECT ARREST / DETENTION" t:officer_organization_desc="GEORGE 300 REG I PATROL" t:master_subject_id="459228703: 201510652" t:subject_race=W t:weapon_used_1="WEAPONLESS (PRESSURE POINTS/KICKS/HAND)" t:subject_sex=M t:subject_ethnicity=N t:subject_conduct_desc="SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS" m:r2r_level=3 m:primary_key=201510652 m:officer_yrs_of_service=2 m:rin=155009
```

## Meta Commands

```ls
metric m:rin p:integer l:RIN t:dataTypeName=number

metric m:primary_key p:long l:"Primary Key" t:dataTypeName=number

metric m:r2r_level p:integer l:"R2R Level" t:dataTypeName=number

metric m:number_shots p:integer l:"Number Shots" t:dataTypeName=number

metric m:officer_yrs_of_service p:integer l:"Officer Yrs of Service" t:dataTypeName=number

entity e:iydp-s2cf l:"R2R 2015" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/iydp-s2cf

property e:iydp-s2cf t:meta.view v:id=iydp-s2cf v:averageRating=0 v:name="R2R 2015" v:attribution="Austin Police Department"

property e:iydp-s2cf t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:iydp-s2cf t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| rin    | primary_key | date_occurred       | time_occurred | location              | area_command | nature_of_contact | reason_desc                            | r2r_level | master_subject_id    | subject_sex | subject_race | subject_ethnicity | subject_conduct_desc                                              | subject_resistance                                                                          | weapon_used_1                           | weapon_used_2 | weapon_used_3 | weapon_used_4 | weapon_used_5 | number_shots | subject_effects             | effect_on_officer           | officer_organization_desc | officer_commission_date | officer_yrs_of_service | x_coordinate | y_coordinate | councildistrict | 
| ====== | =========== | =================== | ============= | ===================== | ============ | ================= | ====================================== | ========= | ==================== | =========== | ============ | ================= | ================================================================= | =========================================================================================== | ======================================= | ============= | ============= | ============= | ============= | ============ | =========================== | =========================== | ========================= | ======================= | ====================== | ============ | ============ | =============== | 
| 154619 | 201510652   | 2015-01-01T00:00:00 | 0220          | E 6TH ST / TRINITY ST | GE           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459228703: 201510652 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                                                             | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 600 REG I PATROL   | 2013-05-17T00:00:00     | 2                      | 3115416      | 10070416     | 9               | 
| 154620 | 201510652   | 2015-01-01T00:00:00 | 0225          | E 6TH ST / TRINITY ST | GE           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459228703: 201510652 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND ACTIVE AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | MINOR INJURY                | NO COMPLAINT OF INJURY/PAIN | GEORGE 700 REG I PATROL   | 2002-05-10T00:00:00     | 13                     | 3115416      | 10070416     | 9               | 
| 155009 | 201510652   | 2015-01-01T00:00:00 |               | E 6TH ST / TRINITY ST | GE           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459228703: 201510652 | M           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                                                             | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 300 REG I PATROL   | 2012-11-30T00:00:00     | 2                      | 3115416      | 10070416     | 9               | 
| 154764 | 201520457   | 2015-01-02T00:00:00 | 0943          | 1900 FARO DR          | HE           | DISPATCHED CALL   | TO RESTRAIN FOR SUBJECTS SAFETY        | 3         | 356649076: 201520457 | F           | W            | N                 | EDP/MENTALLY UNSTABLE; SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND ACTIVE AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | COMPLAINT OF INJURY/PAIN    | COMPLAINT OF INJURY/PAIN    | HENRY 100 REG III PATROL  | 2008-06-20T00:00:00     | 7                      | 3124262      | 10057181     | 3               | 
| 154859 | 201520457   | 2015-01-02T00:00:00 | 0943          | 1900 FARO DR          | HE           | DISPATCHED CALL   | IN CUSTODY, MAINTAINING CONTROL        | 3         | 356649076: 201520457 | F           | W            | N                 | EDP/MENTALLY UNSTABLE; SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS | VERBAL RESISTANCE/AGGRESSION; EMPTY HAND DEFENSIVE RESISTANCE                               | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | COMPLAINT OF INJURY/PAIN    | NO COMPLAINT OF INJURY/PAIN | HENRY 100 REG III PATROL  | 2009-01-02T00:00:00     | 6                      | 3124262      | 10057181     | 3               | 
| 170044 | 201621470   | 2015-01-02T00:00:00 |               | 2520 ELMONT DR        | HE           | DISPATCHED CALL   | NECESSARY TO DEFEND REPORTING OFFICER  | 3         | 458762643: 201621470 | F           | W            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND ACTIVE AGGRESSION                                                                | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | MINOR INJURY                | HENRY 700 REG III PATROL  | 2013-05-17T00:00:00     | 2                      | 3121683      | 10060584     | 3               | 
| 154662 | 201530043   | 2015-01-03T00:00:00 | 0050          | 209 E 6TH ST          | GE           | OTHER             | IN CUSTODY, MAINTAINING CONTROL        | 3         | 458807987: 201530043 | M           | W            |                   | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | EMPTY HAND DEFENSIVE RESISTANCE                                                             | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               | 0            | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | GEORGE 400 REG I PATROL   | 2013-03-22T00:00:00     | 2                      | 3114846      | 10070494     | 9               | 
| 154699 | 201530572   | 2015-01-03T00:00:00 | 0947          | 700 W BRAKER LN       | ED           | VIEWED OFFENSE    | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459166364: 201530572 | M           | B            | N                 | SUSPECTED UNDER INFLUENCE OF ALCOHOL/DRUGS                        | PASSIVE RESISTANCE                                                                          | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | EDWARD 100 REG II PATROL  | 2012-03-23T00:00:00     | 3                      | 3131508      | 10112358     | 7               | 
| 154723 | 201530126   | 2015-01-03T00:00:00 | 0138          | 4417 FRANKLIN PARK DR | FR           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459131092: 201530126 | M           | B            | N                 |                                                                   | EMPTY HAND DEFENSIVE RESISTANCE                                                             | CED - DRIVE STUN-ENTER # SHOTS          |               |               |               |               | 1            | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | FRANK 400 REG IV PATROL   | 2013-03-22T00:00:00     | 2                      | 3114441      | 10045558     | 2               | 
| 154739 | 201530126   | 2015-01-03T00:00:00 | 0304          | 4417 FRANKLIN PARK DR | FR           | DISPATCHED CALL   | NECESSARY TO EFFECT ARREST / DETENTION | 3         | 459131092: 201530126 | M           | B            | N                 |                                                                   | EMPTY HAND DEFENSIVE RESISTANCE                                                             | WEAPONLESS (PRESSURE POINTS/KICKS/HAND) |               |               |               |               |              | NO COMPLAINT OF INJURY/PAIN | NO COMPLAINT OF INJURY/PAIN | FRANK 400 REG IV PATROL   | 2012-11-30T00:00:00     | 2                      | 3114441      | 10045558     | 2               | 
```