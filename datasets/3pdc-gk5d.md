# IDPH: STDs Nationally Ranked By State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-stds-nationally-ranked-by-state) |
| Metadata | [Link](https://data.illinois.gov/api/views/3pdc-gk5d) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3pdc-gk5d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3pdc-gk5d/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3pdc-gk5d |
| Name | IDPH: STDs Nationally Ranked By State |
| Attribution | Centers for Disease Control and Prevention |
| Category | Public Health |
| Tags | std, nationally, ranked, nationally ranked, state, chlamydia, gonrorhea, primary syphilis, secondary syphilis, primary and secondary syphilis, p&s, count, rate |
| Created | 2015-04-27T15:48:19Z |
| Publication Date | 2016-10-20T13:08:45Z |

## Description

U.S. states ranked by cases of Chlamydia, gonorrhea, and primary and secondary syphilis reported.  Data Source: Centers for Disease Control and Prevention Surveillance Reports 2000-2015 (http://www.cdc.gov/std/stats11/default.htm)

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | numeric metric | sort                                   | Sort                                   | number    | number      |
| Yes      | time           | year                                   | Year                                   | number    | text        |
| Yes      | series tag     | state                                  | State                                  | text      | text        |
| Yes      | numeric metric | chlamydia_count                        | Chlamydia_Count                        | number    | number      |
| Yes      | numeric metric | chlamydia_rate                         | Chlamydia_Rate                         | number    | number      |
| Yes      | numeric metric | chlamydia_rankbycount                  | Chlamydia_RankByCount                  | number    | number      |
| Yes      | numeric metric | chlamydia_rankbyrate                   | Chlamydia_RankByRate                   | number    | number      |
| Yes      | numeric metric | gonorrhea_count                        | Gonorrhea_Count                        | number    | number      |
| Yes      | numeric metric | gonorrhea_rate                         | Gonorrhea_Rate                         | number    | number      |
| Yes      | numeric metric | gonorrhea_rankbycount                  | Gonorrhea_RankByCount                  | number    | number      |
| Yes      | numeric metric | gonorrhea_rankbyrate                   | Gonorrhea_RankByRate                   | number    | number      |
| Yes      | numeric metric | primary_secondary_syphilis_count       | Primary_Secondary_Syphilis_Count       | number    | number      |
| Yes      | numeric metric | primary_secondary_syphilis_rate        | Primary_Secondary_Syphilis_Rate        | number    | number      |
| Yes      | numeric metric | primary_secondary_syphilis_rankbycount | Primary_Secondary_Syphilis_RankByCount | number    | number      |
| Yes      | numeric metric | primary_secondary_syphilis_rankbyrate  | Primary_Secondary_Syphilis_RankByRate  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3pdc-gk5d d:2000-01-01T00:00:00.000Z t:state=Alabama m:gonorrhea_rankbycount=12 m:chlamydia_rankbycount=14 m:sort=1 m:gonorrhea_rankbyrate=3 m:chlamydia_count=15323 m:primary_secondary_syphilis_rankbycount=17 m:primary_secondary_syphilis_count=123 m:primary_secondary_syphilis_rate=2.8 m:chlamydia_rate=344.2 m:gonorrhea_count=12063 m:chlamydia_rankbyrate=6 m:primary_secondary_syphilis_rankbyrate=13 m:gonorrhea_rate=271

series e:3pdc-gk5d d:2000-01-01T00:00:00.000Z t:state=Alaska m:gonorrhea_rankbycount=41 m:chlamydia_rankbycount=40 m:sort=2 m:gonorrhea_rankbyrate=35 m:chlamydia_count=2569 m:primary_secondary_syphilis_rankbycount=39 m:primary_secondary_syphilis_count=0 m:primary_secondary_syphilis_rate=0 m:chlamydia_rate=409.3 m:gonorrhea_count=361 m:chlamydia_rankbyrate=2 m:gonorrhea_rate=57.5

series e:3pdc-gk5d d:2000-01-01T00:00:00.000Z t:state=Arizona m:gonorrhea_rankbycount=23 m:chlamydia_rankbycount=21 m:sort=3 m:gonorrhea_rankbyrate=28 m:chlamydia_count=12591 m:primary_secondary_syphilis_rankbycount=13 m:primary_secondary_syphilis_count=189 m:primary_secondary_syphilis_rate=3.7 m:chlamydia_rate=243.7 m:gonorrhea_count=4130 m:chlamydia_rankbyrate=22 m:primary_secondary_syphilis_rankbyrate=10 m:gonorrhea_rate=79.9
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:chlamydia_count p:integer l:Chlamydia_Count t:dataTypeName=number

metric m:chlamydia_rate p:float l:Chlamydia_Rate t:dataTypeName=number

metric m:chlamydia_rankbycount p:integer l:Chlamydia_RankByCount t:dataTypeName=number

metric m:chlamydia_rankbyrate p:integer l:Chlamydia_RankByRate t:dataTypeName=number

metric m:gonorrhea_count p:integer l:Gonorrhea_Count t:dataTypeName=number

metric m:gonorrhea_rate p:float l:Gonorrhea_Rate t:dataTypeName=number

metric m:gonorrhea_rankbycount p:integer l:Gonorrhea_RankByCount t:dataTypeName=number

metric m:gonorrhea_rankbyrate p:integer l:Gonorrhea_RankByRate t:dataTypeName=number

metric m:primary_secondary_syphilis_count p:integer l:Primary_Secondary_Syphilis_Count t:dataTypeName=number

metric m:primary_secondary_syphilis_rate p:float l:Primary_Secondary_Syphilis_Rate t:dataTypeName=number

metric m:primary_secondary_syphilis_rankbycount p:integer l:Primary_Secondary_Syphilis_RankByCount t:dataTypeName=number

metric m:primary_secondary_syphilis_rankbyrate p:integer l:Primary_Secondary_Syphilis_RankByRate t:dataTypeName=number

entity e:3pdc-gk5d l:"IDPH: STDs Nationally Ranked By State" t:attribution="Centers for Disease Control and Prevention" t:url=https://data.illinois.gov/api/views/3pdc-gk5d

property e:3pdc-gk5d t:meta.view v:id=3pdc-gk5d v:category="Public Health" v:attributionLink=http://www.cdc.gov/STD/publications/default.htm v:averageRating=0 v:name="IDPH: STDs Nationally Ranked By State" v:attribution="Centers for Disease Control and Prevention"

property e:3pdc-gk5d t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:3pdc-gk5d t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | state       | chlamydia_count | chlamydia_rate | chlamydia_rankbycount | chlamydia_rankbyrate | gonorrhea_count | gonorrhea_rate | gonorrhea_rankbycount | gonorrhea_rankbyrate | primary_secondary_syphilis_count | primary_secondary_syphilis_rate | primary_secondary_syphilis_rankbycount | primary_secondary_syphilis_rankbyrate | 
| ==== | ==== | =========== | =============== | ============== | ===================== | ==================== | =============== | ============== | ===================== | ==================== | ================================ | =============================== | ====================================== | ===================================== | 
| 1    | 2000 | Alabama     | 15323           | 344.2          | 14                    | 6                    | 12063           | 271.0          | 12                    | 3                    | 123                              | 2.8                             | 17                                     | 13                                    | 
| 2    | 2000 | Alaska      | 2569            | 409.3          | 40                    | 2                    | 361             | 57.5           | 41                    | 35                   | 0                                | 0.0                             | 39                                     |                                       | 
| 3    | 2000 | Arizona     | 12591           | 243.7          | 21                    | 22                   | 4130            | 79.9           | 23                    | 28                   | 189                              | 3.7                             | 13                                     | 10                                    | 
| 4    | 2000 | Arkansas    | 6219            | 232.2          | 31                    | 25                   | 3642            | 136.0          | 24                    | 17                   | 104                              | 3.9                             | 19                                     | 9                                     | 
| 5    | 2000 | California  | 95392           | 280.5          | 1                     | 12                   | 21619           | 63.6           | 4                     | 32                   | 325                              | 1.0                             | 9                                      | 19                                    | 
| 6    | 2000 | Colorado    | 12000           | 277.3          | 22                    | 13                   | 3112            | 71.9           | 27                    | 30                   | 11                               | 0.3                             | 31                                     | 26                                    | 
| 7    | 2000 | Connecticut | 7604            | 222.9          | 29                    | 28                   | 2912            | 85.3           | 29                    | 27                   | 16                               | 0.5                             | 28                                     | 24                                    | 
| 8    | 2000 | Delaware    | 2856            | 363.1          | 38                    | 4                    | 1735            | 220.6          | 32                    | 5                    | 9                                | 1.1                             | 32                                     | 18                                    | 
| 9    | 2000 | Florida     | 33390           | 208.0          | 4                     | 33                   | 22781           | 141.9          | 3                     | 16                   | 413                              | 2.6                             | 3                                      | 14                                    | 
| 10   | 2000 | Georgia     | 29359           | 356.5          | 7                     | 5                    | 20265           | 246.1          | 5                     | 4                    | 402                              | 4.9                             | 5                                      | 6                                     | 
```