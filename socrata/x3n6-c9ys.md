# North East BK"F" Arrest Log (Jan 2014 - April 19, 2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/north-east-bkf-arrest-log-jan-2014-january-24-2015) |
| Metadata | [Link](https://data.maryland.gov/api/views/x3n6-c9ys) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/x3n6-c9ys/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/x3n6-c9ys/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | x3n6-c9ys |
| Name | North East BK"F" Arrest Log (Jan 2014 - April 19, 2015) |
| Attribution | Maryland State Police |
| Category | Public Safety |
| Tags | arrest, state police, north east, crime |
| Created | 2014-10-18T01:23:30Z |
| Publication Date | 2015-04-19T17:13:27Z |

## Description

Maryland State Police North East Barrack "F" arrest log. Displayed are individuals who have been arrested and charged with a criminal violation of Maryland Statute. Names may multiple times for a single date because of multiple charges associated with an incident.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | arrest_date_time | ARREST_DATE_TIME | calendar_date | calendar_date |
| Yes      | series tag     | lname            | LNAME            | text          | text          |
| Yes      | series tag     | fname            | FNAME            | text          | text          |
| Yes      | numeric metric | age              | AGE              | number        | number        |
| Yes      | series tag     | race             | RACE             | text          | text          |
| Yes      | series tag     | sex              | SEX              | text          | text          |
| Yes      | series tag     | charge_desc      | CHARGE_DESC      | text          | text          |
```

## Time Field

```ls
Value = arrest_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:x3n6-c9ys d:2015-04-15T22:26:00.000Z t:sex=Male t:lname=Seidle t:race=White t:charge_desc="(DRIVING, ATTEMPTING TO DRIVE) VEH. WHILE IMPAIRED BY ALCOHOL : 902 b1 : 14583 :" t:fname=John m:age=35

series e:x3n6-c9ys d:2015-04-15T22:26:00.000Z t:sex=Male t:lname=Seidle t:race=White t:charge_desc="(DRIVING, ATTEMPTING TO DRIVE) VEHICLE WHILE UNDERTHE INFLUENCE OF ALCOHOL PER SE : 902 a2 : 16357 :" t:fname=John m:age=35

series e:x3n6-c9ys d:2015-04-15T22:26:00.000Z t:sex=Male t:lname=Seidle t:race=White t:charge_desc="(DRIVING, ATTEMPTING TO DRIVE) VEHICLE WHILE UNDERTHE INFLUENCE OF ALCOHOL : 902 a1 : 16356 :" t:fname=John m:age=35
```

## Meta Commands

```ls
metric m:age p:integer l:AGE t:dataTypeName=number

entity e:x3n6-c9ys l:"North East BK""F"" Arrest Log (Jan 2014 - April 19, 2015)" t:attribution="Maryland State Police" t:url=https://data.maryland.gov/api/views/x3n6-c9ys

property e:x3n6-c9ys t:meta.view v:id=x3n6-c9ys v:category="Public Safety" v:averageRating=0 v:name="North East BK""F"" Arrest Log (Jan 2014 - April 19, 2015)" v:attribution="Maryland State Police"

property e:x3n6-c9ys t:meta.view.owner v:id=u26b-uzyh v:screenName="North East Barrack ""F""" v:displayName="North East Barrack ""F"""

property e:x3n6-c9ys t:meta.view.tableauthor v:id=u26b-uzyh v:screenName="North East Barrack ""F""" v:roleName=editor v:displayName="North East Barrack ""F"""
```

## Top Records

```ls
| arrest_date_time    | lname     | fname   | age | race                      | sex  | charge_desc                                                                                                              | 
| =================== | ========= | ======= | === | ========================= | ==== | ======================================================================================================================== | 
| 2015-04-15T22:26:00 | Seidle    | John    | 35  | White                     | Male | (DRIVING, ATTEMPTING TO DRIVE) VEH. WHILE IMPAIRED BY ALCOHOL : 902 b1 : 14583 :                                         | 
| 2015-04-15T22:26:00 | Seidle    | John    | 35  | White                     | Male | (DRIVING, ATTEMPTING TO DRIVE) VEHICLE WHILE UNDERTHE INFLUENCE OF ALCOHOL PER SE : 902 a2 : 16357 :                     | 
| 2015-04-15T22:26:00 | Seidle    | John    | 35  | White                     | Male | (DRIVING, ATTEMPTING TO DRIVE) VEHICLE WHILE UNDERTHE INFLUENCE OF ALCOHOL : 902 a1 : 16356 :                            | 
| 2015-04-15T21:05:00 | Patterson | Charles | 54  | White                     | Male | CR, 3-202 : ASSAULT-FIRST DEGREE                                                                                         | 
| 2015-04-13T23:41:00 | Gill      | Robert  | 20  | White                     | Male | NO CHARGES                                                                                                               | 
| 2015-04-13T23:41:00 | Ellinger  | Cory    | 19  | White                     | Male | NO CHARGES                                                                                                               | 
| 2015-04-13T23:41:00 | Harris    | Kenneth | 20  | Black or African American | Male | NO CHARGES                                                                                                               | 
| 2015-04-13T21:53:00 | Lang      | Corey   | 26  | White                     | Male | CR, 7-104 : THEFT: LESS $1,000 VALUE- From Building                                                                      | 
| 2015-04-13T17:00:00 | Barnett   | Gerald  | 50  | Black or African American | Male | CR, 3-210 : Assault Second Degree / DOC Employee, etc. Aggravated Assault???Hands, Fists, Feet, Etc.???Aggravated Injury | 
| 2015-04-13T17:00:00 | Barnett   | Gerald  | 49  | Black or African American | Male | CR, 3-210 : Assault Second Degree / DOC Employee, etc. Aggravated Assault???Hands, Fists, Feet, Etc.???Aggravated Injury | 
```