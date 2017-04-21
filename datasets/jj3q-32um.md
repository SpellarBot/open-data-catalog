# IDPH STD Illinois By County Rank

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-std-illinois-by-county-rank) |
| Metadata | [Link](https://data.illinois.gov/api/views/jj3q-32um) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jj3q-32um/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jj3q-32um/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jj3q-32um |
| Name | IDPH STD Illinois By County Rank |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, chlamydia, gonorrhea, early syphilis, syphilis, county, count, rate, rank |
| Created | 2013-11-01T17:45:07Z |
| Publication Date | 2016-08-15T15:52:16Z |

## Description

Illinois 2000-2015 STD counts and rates (per 100,000 population) ranked by county. See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | numeric metric | sort                       | Sort                       | number    | number      |
| Yes      | time           | year                       | Year                       | number    | text        |
| Yes      | series tag     | county                     | COUNTY                     | text      | text        |
| Yes      | series tag     | countyfips                 | CountyFIPS                 | text      | text        |
| Yes      | numeric metric | chlamydia_count            | Chlamydia_Count            | number    | number      |
| Yes      | numeric metric | chlamydia_rate             | Chlamydia_Rate             | number    | number      |
| Yes      | numeric metric | chlamydia_rankbycount      | Chlamydia_RankByCount      | number    | number      |
| Yes      | numeric metric | chlamydia_rankbyrate       | Chlamydia_RankByRate       | number    | number      |
| Yes      | numeric metric | gonorrhea_count            | Gonorrhea_Count            | number    | number      |
| Yes      | numeric metric | gonorrhea_rate             | Gonorrhea_Rate             | number    | number      |
| Yes      | numeric metric | gonorrhea_rankbycount      | Gonorrhea_RankByCount      | number    | number      |
| Yes      | numeric metric | gonorrhea_rankbyrate       | Gonorrhea_RankByRate       | number    | number      |
| Yes      | numeric metric | early_syphilis_count       | Early_Syphilis_Count       | number    | number      |
| Yes      | numeric metric | early_syphilis_rate        | Early_Syphilis_Rate        | number    | number      |
| Yes      | numeric metric | early_syphilis_rankbycount | Early_Syphilis_RankByCount | number    | number      |
| Yes      | numeric metric | early_syphilis_rankbyrate  | Early_Syphilis_RankByRate  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jj3q-32um d:2000-01-01T00:00:00.000Z t:countyfips=17001 t:county=ADAMS m:gonorrhea_rankbycount=27 m:early_syphilis_count=2 m:sort=1 m:early_syphilis_rankbycount=10 m:early_syphilis_rankbyrate=15 m:gonorrhea_rate=45.4 m:chlamydia_rankbycount=28 m:early_syphilis_rate=2.9 m:gonorrhea_rankbyrate=32 m:chlamydia_count=74 m:chlamydia_rate=108.4 m:gonorrhea_count=31 m:chlamydia_rankbyrate=52

series e:jj3q-32um d:2000-01-01T00:00:00.000Z t:countyfips=17003 t:county=ALEXANDER m:gonorrhea_rankbycount=24 m:early_syphilis_count=0 m:sort=2 m:early_syphilis_rankbycount=12 m:early_syphilis_rankbyrate=27 m:gonorrhea_rate=396.2 m:chlamydia_rankbycount=30 m:early_syphilis_rate=0 m:gonorrhea_rankbyrate=1 m:chlamydia_count=70 m:chlamydia_rate=729.9 m:gonorrhea_count=38 m:chlamydia_rankbyrate=1

series e:jj3q-32um d:2000-01-01T00:00:00.000Z t:countyfips=17005 t:county=BOND m:gonorrhea_rankbycount=45 m:early_syphilis_count=0 m:sort=3 m:early_syphilis_rankbycount=12 m:early_syphilis_rankbyrate=27 m:gonorrhea_rate=11.3 m:chlamydia_rankbycount=57 m:early_syphilis_rate=0 m:gonorrhea_rankbyrate=71 m:chlamydia_count=16 m:chlamydia_rate=90.7 m:gonorrhea_count=2 m:chlamydia_rankbyrate=61
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

metric m:early_syphilis_count p:integer l:Early_Syphilis_Count t:dataTypeName=number

metric m:early_syphilis_rate p:float l:Early_Syphilis_Rate t:dataTypeName=number

metric m:early_syphilis_rankbycount p:integer l:Early_Syphilis_RankByCount t:dataTypeName=number

metric m:early_syphilis_rankbyrate p:integer l:Early_Syphilis_RankByRate t:dataTypeName=number

entity e:jj3q-32um l:"IDPH STD Illinois By County Rank" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/jj3q-32um

property e:jj3q-32um t:meta.view v:id=jj3q-32um v:category="Public Health" v:averageRating=0 v:name="IDPH STD Illinois By County Rank" v:attribution="Illinois Department of Public Health STD Program"

property e:jj3q-32um t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:jj3q-32um t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | county    | countyfips | chlamydia_count | chlamydia_rate | chlamydia_rankbycount | chlamydia_rankbyrate | gonorrhea_count | gonorrhea_rate | gonorrhea_rankbycount | gonorrhea_rankbyrate | early_syphilis_count | early_syphilis_rate | early_syphilis_rankbycount | early_syphilis_rankbyrate | 
| ==== | ==== | ========= | ========== | =============== | ============== | ===================== | ==================== | =============== | ============== | ===================== | ==================== | ==================== | =================== | ========================== | ========================= | 
| 1    | 2000 | ADAMS     | 17001      | 74              | 108.4          | 28                    | 52                   | 31              | 45.4           | 27                    | 32                   | 2                    | 2.9                 | 10                         | 15                        | 
| 2    | 2000 | ALEXANDER | 17003      | 70              | 729.9          | 30                    | 1                    | 38              | 396.2          | 24                    | 1                    | 0                    | 0.0                 | 12                         | 27                        | 
| 3    | 2000 | BOND      | 17005      | 16              | 90.7           | 57                    | 61                   | 2               | 11.3           | 45                    | 71                   | 0                    | 0.0                 | 12                         | 27                        | 
| 4    | 2000 | BOONE     | 17007      | 52              | 124.4          | 34                    | 45                   | 15              | 35.9           | 33                    | 38                   | 1                    | 2.4                 | 11                         | 18                        | 
| 5    | 2000 | BROWN     | 17009      | 10              | 143.9          | 63                    | 35                   | 0               | 0.0            | 47                    | 83                   | 0                    | 0.0                 | 12                         | 27                        | 
| 6    | 2000 | BUREAU    | 17011      | 31              | 87.3           | 44                    | 65                   | 3               | 8.4            | 44                    | 74                   | 0                    | 0.0                 | 12                         | 27                        | 
| 7    | 2000 | CALHOUN   | 17013      | 6               | 118.0          | 65                    | 47                   | 0               | 0.0            | 47                    | 83                   | 0                    | 0.0                 | 12                         | 27                        | 
| 8    | 2000 | CARROLL   | 17015      | 11              | 66.0           | 62                    | 82                   | 2               | 12.0           | 45                    | 69                   | 0                    | 0.0                 | 12                         | 27                        | 
| 9    | 2000 | CASS      | 17017      | 18              | 131.4          | 55                    | 38                   | 1               | 7.3            | 46                    | 76                   | 0                    | 0.0                 | 12                         | 27                        | 
| 10   | 2000 | CHAMPAIGN | 17019      | 900             | 500.9          | 6                     | 4                    | 518             | 288.3          | 7                     | 9                    | 3                    | 1.7                 | 9                          | 20                        | 
```