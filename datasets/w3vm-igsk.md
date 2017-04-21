# Admissions to Juvenile Detention Related to a Status Offense By Status Offender Contempt Charge

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/admissions-to-juvenile-detention-related-to-a-status-offense-by-status-offender-contempt-c) |
| Metadata | [Link](https://data.wa.gov/api/views/w3vm-igsk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/w3vm-igsk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/w3vm-igsk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | w3vm-igsk |
| Name | Admissions to Juvenile Detention Related to a Status Offense By Status Offender Contempt Charge |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, detention, status offense, youth |
| Created | 2015-12-28T07:54:27Z |
| Publication Date | 2016-01-12T20:03:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                    | Data Type | Render Type |
| ======== | ============== | ==================================== | ======================================= | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                              | meta_data | meta_data   |
| Yes      | series tag     | facility                             | Facility                                | text      | text        |
| Yes      | numeric metric | dependency_contempt_2013             | Dependency Contempt (2013)              | number    | number      |
| Yes      | numeric metric | dependency_contempt_2012             | Dependency Contempt (2012)              | number    | number      |
| Yes      | numeric metric | dependency_contempt_2011             | Dependency Contempt (2011)              | number    | number      |
| Yes      | numeric metric | dependency_contempt_2010             | Dependency Contempt (2010)              | number    | number      |
| Yes      | series tag     | dependency_contempt_2010_2013_chg    | Dependency Contempt 2010-2013 % Chg.    | text      | text        |
| Yes      | numeric metric | truancy_contempt_2013                | Truancy Contempt (2013)                 | number    | number      |
| Yes      | numeric metric | truancy_contempt_2012                | Truancy Contempt (2012)                 | number    | number      |
| Yes      | numeric metric | truancy_contempt_2011                | Truancy Contempt (2011)                 | number    | number      |
| Yes      | numeric metric | truancy_contempt_2010                | Truancy Contempt (2010)                 | number    | number      |
| Yes      | series tag     | truancy_contempt_2010_2013_chg       | Truancy Contempt 2010-2013 % Chg.       | text      | text        |
| Yes      | numeric metric | at_risk_youth_contempt_2013          | At-Risk Youth Contempt (2013)           | number    | number      |
| Yes      | numeric metric | at_risk_youth_contempt_2012          | At-Risk Youth Contempt (2012)           | number    | number      |
| Yes      | numeric metric | at_risk_youth_contempt_2011          | At-Risk Youth Contempt (2011)           | number    | number      |
| Yes      | numeric metric | at_risk_youth_contempt_2010          | At-Risk Youth Contempt (2010)           | number    | number      |
| Yes      | series tag     | at_risk_youth_contempt_2010_2013_chg | At-Risk Youth Contempt 2010-2013 % Chg. | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w3vm-igsk d:2015-12-27T23:54:30.000Z t:at_risk_youth_contempt_2010_2013_chg=8% t:facility=Benton/Franklin t:dependency_contempt_2010_2013_chg=29% t:truancy_contempt_2010_2013_chg=51% m:at_risk_youth_contempt_2010=25 m:at_risk_youth_contempt_2011=35 m:truancy_contempt_2010=72 m:truancy_contempt_2011=74 m:dependency_contempt_2012=15 m:at_risk_youth_contempt_2013=27 m:truancy_contempt_2012=62 m:dependency_contempt_2013=18 m:at_risk_youth_contempt_2012=42 m:truancy_contempt_2013=109 m:dependency_contempt_2010=14 m:dependency_contempt_2011=20

series e:w3vm-igsk d:2015-12-27T23:54:30.000Z t:at_risk_youth_contempt_2010_2013_chg=40% t:facility=Chelan t:truancy_contempt_2010_2013_chg=-29% m:at_risk_youth_contempt_2010=20 m:at_risk_youth_contempt_2011=25 m:truancy_contempt_2010=42 m:truancy_contempt_2011=15 m:dependency_contempt_2012=3 m:at_risk_youth_contempt_2013=28 m:truancy_contempt_2012=21 m:dependency_contempt_2013=0 m:at_risk_youth_contempt_2012=28 m:truancy_contempt_2013=30 m:dependency_contempt_2010=0 m:dependency_contempt_2011=0

series e:w3vm-igsk d:2015-12-27T23:54:30.000Z t:at_risk_youth_contempt_2010_2013_chg=-29% t:facility=Clallam t:dependency_contempt_2010_2013_chg=143% t:truancy_contempt_2010_2013_chg=-32% m:at_risk_youth_contempt_2010=68 m:at_risk_youth_contempt_2011=46 m:truancy_contempt_2010=98 m:truancy_contempt_2011=90 m:dependency_contempt_2012=12 m:at_risk_youth_contempt_2013=48 m:truancy_contempt_2012=67 m:dependency_contempt_2013=17 m:at_risk_youth_contempt_2012=82 m:truancy_contempt_2013=67 m:dependency_contempt_2010=7 m:dependency_contempt_2011=8
```

## Meta Commands

```ls
metric m:dependency_contempt_2013 p:integer l:"Dependency Contempt (2013)" t:dataTypeName=number

metric m:dependency_contempt_2012 p:integer l:"Dependency Contempt (2012)" t:dataTypeName=number

metric m:dependency_contempt_2011 p:integer l:"Dependency Contempt (2011)" t:dataTypeName=number

metric m:dependency_contempt_2010 p:integer l:"Dependency Contempt (2010)" t:dataTypeName=number

metric m:truancy_contempt_2013 p:integer l:"Truancy Contempt (2013)" t:dataTypeName=number

metric m:truancy_contempt_2012 p:integer l:"Truancy Contempt (2012)" t:dataTypeName=number

metric m:truancy_contempt_2011 p:integer l:"Truancy Contempt (2011)" t:dataTypeName=number

metric m:truancy_contempt_2010 p:integer l:"Truancy Contempt (2010)" t:dataTypeName=number

metric m:at_risk_youth_contempt_2013 p:integer l:"At-Risk Youth Contempt (2013)" t:dataTypeName=number

metric m:at_risk_youth_contempt_2012 p:integer l:"At-Risk Youth Contempt (2012)" t:dataTypeName=number

metric m:at_risk_youth_contempt_2011 p:integer l:"At-Risk Youth Contempt (2011)" t:dataTypeName=number

metric m:at_risk_youth_contempt_2010 p:integer l:"At-Risk Youth Contempt (2010)" t:dataTypeName=number

entity e:w3vm-igsk l:"Admissions to Juvenile Detention Related to a Status Offense By Status Offender Contempt Charge" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/w3vm-igsk

property e:w3vm-igsk t:meta.view v:id=w3vm-igsk v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Admissions to Juvenile Detention Related to a Status Offense By Status Offender Contempt Charge" v:attribution="Office of Juvenile Justice"

property e:w3vm-igsk t:meta.view.license v:name="Public Domain"

property e:w3vm-igsk t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:w3vm-igsk t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| :updated_at | facility        | dependency_contempt_2013 | dependency_contempt_2012 | dependency_contempt_2011 | dependency_contempt_2010 | dependency_contempt_2010_2013_chg | truancy_contempt_2013 | truancy_contempt_2012 | truancy_contempt_2011 | truancy_contempt_2010 | truancy_contempt_2010_2013_chg | at_risk_youth_contempt_2013 | at_risk_youth_contempt_2012 | at_risk_youth_contempt_2011 | at_risk_youth_contempt_2010 | at_risk_youth_contempt_2010_2013_chg | 
| =========== | =============== | ======================== | ======================== | ======================== | ======================== | ================================= | ===================== | ===================== | ===================== | ===================== | ============================== | =========================== | =========================== | =========================== | =========================== | ==================================== | 
| 1451260470  | Benton/Franklin | 18                       | 15                       | 20                       | 14                       | 29%                               | 109                   | 62                    | 74                    | 72                    | 51%                            | 27                          | 42                          | 35                          | 25                          | 8%                                   | 
| 1451260470  | Chelan          | 0                        | 3                        | 0                        | 0                        |                                   | 30                    | 21                    | 15                    | 42                    | -29%                           | 28                          | 28                          | 25                          | 20                          | 40%                                  | 
| 1451260470  | Clallam         | 17                       | 12                       | 8                        | 7                        | 143%                              | 67                    | 67                    | 90                    | 98                    | -32%                           | 48                          | 82                          | 46                          | 68                          | -29%                                 | 
| 1451260470  | Clark           | 1                        | 5                        | 3                        | 4                        | -75%                              | 1                     | 2                     | 0                     | 1                     | 0%                             | 1                           | 2                           | 6                           | 3                           | -67%                                 | 
| 1451260470  | Cowlitz         | 11                       | 10                       | 1                        | 1                        | 1000%                             | 91                    | 65                    | 35                    | 25                    | 264%                           | 144                         | 150                         | 68                          | 24                          | 500%                                 | 
| 1451260470  | Grant           | 0                        | 0                        | 0                        | 1                        | -100%                             | 48                    | 52                    | 45                    | 91                    | -47%                           | 18                          | 5                           | 38                          | 39                          | -54%                                 | 
| 1451260470  | Grays Harbor    | 27                       | 27                       | 41                       | 46                       | -41%                              | 294                   | 322                   | 260                   | 300                   | -2%                            | 238                         | 218                         | 197                         | 174                         | 37%                                  | 
| 1451260470  | Island          | 0                        | 0                        | 0                        | 0                        |                                   | 25                    | 18                    | 12                    | 10                    | 150%                           | 12                          | 19                          | 15                          | 9                           | 33%                                  | 
| 1451260470  | King            | 77                       | 85                       | 67                       | 71                       | 8%                                | 23                    | 10                    | 16                    | 8                     | 188%                           | 93                          | 82                          | 119                         | 137                         | -32%                                 | 
| 1451260470  | Kitsap          | 2                        | 1                        | 3                        | 1                        | 100%                              | 8                     | 36                    | 32                    | 54                    | -85%                           | 20                          | 3                           | 9                           | 11                          | 82%                                  | 
```