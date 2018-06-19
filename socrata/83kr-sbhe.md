# CCRB: Command Rankings: Complaints per Uniformed Officer 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-command-rankings-complaints-per-uniformed-officer-2009-eebee) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/83kr-sbhe) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/83kr-sbhe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/83kr-sbhe/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 83kr-sbhe |
| Name | CCRB: Command Rankings: Complaints per Uniformed Officer 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, command, ranking, command ranking |
| Created | 2011-09-15T19:48:30Z |
| Publication Date | 2011-09-15T19:48:30Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009 Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | numeric metric | 2009_command_ranking                  | 2009 Command Ranking                  | number    | number      |
| Yes      | series tag     | precinct_command                      | Precinct/Command                      | text      | text        |
| Yes      | numeric metric | 2009_complaints                       | 2009 Complaints                       | number    | number      |
| Yes      | numeric metric | 2009_number_of_subject_officers       | 2009 Number of Subject Officers       | number    | number      |
| Yes      | numeric metric | 2009_complaints_per_uniformed_officer | 2009 Complaints per Uniformed Officer | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:83kr-sbhe d:2009-01-01T00:00:00.000Z t:precinct_command="Patrol Borough Bronx" m:2009_command_ranking=1 m:2009_complaints=735 m:2009_number_of_subject_officers=3095 m:2009_complaints_per_uniformed_officer=0.2375

series e:83kr-sbhe d:2009-01-01T00:00:00.000Z t:precinct_command="Patrol Borough Brooklyn North" m:2009_command_ranking=2 m:2009_complaints=556 m:2009_number_of_subject_officers=2891 m:2009_complaints_per_uniformed_officer=0.1923

series e:83kr-sbhe d:2009-01-01T00:00:00.000Z t:precinct_command="Patrol Borough Brooklyn South" m:2009_command_ranking=3 m:2009_complaints=401 m:2009_number_of_subject_officers=2501 m:2009_complaints_per_uniformed_officer=0.1603
```

## Meta Commands

```ls
metric m:2009_command_ranking p:integer l:"2009 Command Ranking" t:dataTypeName=number

metric m:2009_complaints p:integer l:"2009 Complaints" t:dataTypeName=number

metric m:2009_number_of_subject_officers p:integer l:"2009 Number of Subject Officers" t:dataTypeName=number

metric m:2009_complaints_per_uniformed_officer p:float l:"2009 Complaints per Uniformed Officer" t:dataTypeName=number

entity e:83kr-sbhe l:"CCRB: Command Rankings: Complaints per Uniformed Officer 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/83kr-sbhe

property e:83kr-sbhe t:meta.view v:id=83kr-sbhe v:category="Public Safety" v:averageRating=0 v:name="CCRB: Command Rankings: Complaints per Uniformed Officer 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:83kr-sbhe t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:83kr-sbhe t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| 2009_command_ranking | precinct_command               | 2009_complaints | 2009_number_of_subject_officers | 2009_complaints_per_uniformed_officer | 
| ==================== | ============================== | =============== | =============================== | ===================================== | 
| 1                    | Patrol Borough Bronx           | 735             | 3095                            | 0.2375                                | 
| 2                    | Patrol Borough Brooklyn North  | 556             | 2891                            | 0.1923                                | 
| 3                    | Patrol Borough Brooklyn South  | 401             | 2501                            | 0.1603                                | 
| 4                    | Organized Crime Control Bureau | 265             | 1794                            | 0.1477                                | 
| 5                    | Patrol Borough Queens South    | 249             | 1748                            | 0.1424                                | 
| 6                    | Housing Bureau                 | 277             | 2002                            | 0.1384                                | 
| 7                    | Patrol Borough Manhattan North | 357             | 2604                            | 0.1371                                | 
| 8                    | Patrol Borough Staten Island   | 110             | 941                             | 0.1169                                | 
| 9                    | Patrol Borough Manhattan South | 261             | 2315                            | 0.1127                                | 
| 10                   | Patrol Borough Queens North    | 170             | 1830                            | 0.0929                                | 
```