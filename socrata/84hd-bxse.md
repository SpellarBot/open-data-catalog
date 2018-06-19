# IDPH STD Illinois By Age Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-std-illinois-by-age-group) |
| Metadata | [Link](https://data.illinois.gov/api/views/84hd-bxse) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/84hd-bxse/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/84hd-bxse/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 84hd-bxse |
| Name | IDPH STD Illinois By Age Group |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, chlamydia, gonorrhea, early syphilis, syphilis, count, rate, age group |
| Created | 2013-11-01T16:29:53Z |
| Publication Date | 2016-06-10T19:26:39Z |

## Description

Illinois 2000-2015 STD counts and rates (per 100,000 population) by five year age groups. See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| Yes      | numeric metric | sort                 | Sort                  | number    | number      |
| Yes      | time           | year                 | Year                  | number    | text        |
| Yes      | series tag     | age_group            | Age Group             | text      | text        |
| Yes      | numeric metric | chlamydia_count      | Chlamydia_Count       | number    | number      |
| Yes      | numeric metric | chlamydia_rate       | Chlamydia_Rate        | number    | number      |
| Yes      | numeric metric | gonorrhea_count      | Gonorrhea_Count       | number    | number      |
| Yes      | numeric metric | gonorrhea_rate       | Gonorrhea_Rate        | number    | number      |
| Yes      | numeric metric | early_syphilis_count | Early_ Syphilis_Count | number    | number      |
| Yes      | numeric metric | early_syphilis_rate  | Early_Syphilis_Rate   | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:84hd-bxse d:2000-01-01T00:00:00.000Z t:age_group=00-04 m:early_syphilis_count=0 m:early_syphilis_rate=0 m:sort=1 m:chlamydia_count=94 m:chlamydia_rate=10.7 m:gonorrhea_count=46 m:gonorrhea_rate=5.2

series e:84hd-bxse d:2000-01-01T00:00:00.000Z t:age_group=05-09 m:early_syphilis_count=0 m:early_syphilis_rate=0 m:sort=2 m:chlamydia_count=15 m:chlamydia_rate=1.6 m:gonorrhea_count=20 m:gonorrhea_rate=2.2

series e:84hd-bxse d:2000-01-01T00:00:00.000Z t:age_group=10-14 m:early_syphilis_count=2 m:early_syphilis_rate=0.2 m:sort=3 m:chlamydia_count=441 m:chlamydia_rate=48.7 m:gonorrhea_count=207 m:gonorrhea_rate=22.9
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:chlamydia_count p:integer l:Chlamydia_Count t:dataTypeName=number

metric m:chlamydia_rate p:float l:Chlamydia_Rate t:dataTypeName=number

metric m:gonorrhea_count p:integer l:Gonorrhea_Count t:dataTypeName=number

metric m:gonorrhea_rate p:float l:Gonorrhea_Rate t:dataTypeName=number

metric m:early_syphilis_count p:integer l:"Early_ Syphilis_Count" t:dataTypeName=number

metric m:early_syphilis_rate p:float l:Early_Syphilis_Rate t:dataTypeName=number

entity e:84hd-bxse l:"IDPH STD Illinois By Age Group" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/84hd-bxse

property e:84hd-bxse t:meta.view v:id=84hd-bxse v:category="Public Health" v:averageRating=0 v:name="IDPH STD Illinois By Age Group" v:attribution="Illinois Department of Public Health STD Program"

property e:84hd-bxse t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:84hd-bxse t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | age_group | chlamydia_count | chlamydia_rate | gonorrhea_count | gonorrhea_rate | early_syphilis_count | early_syphilis_rate | 
| ==== | ==== | ========= | =============== | ============== | =============== | ============== | ==================== | =================== | 
| 1    | 2000 | 00-04     | 94              | 10.7           | 46              | 5.2            | 0                    | 0.0                 | 
| 2    | 2000 | 05-09     | 15              | 1.6            | 20              | 2.2            | 0                    | 0.0                 | 
| 3    | 2000 | 10-14     | 441             | 48.7           | 207             | 22.9           | 2                    | 0.2                 | 
| 4    | 2000 | 15-19     | 13391           | 1497.9         | 5963            | 667.0          | 58                   | 6.5                 | 
| 5    | 2000 | 20-24     | 15313           | 1799.7         | 8492            | 998.1          | 125                  | 14.7                | 
| 6    | 2000 | 25-29     | 6217            | 697.2          | 4092            | 458.9          | 113                  | 12.7                | 
| 7    | 2000 | 30-34     | 2524            | 274.4          | 2277            | 247.5          | 144                  | 15.7                | 
| 8    | 2000 | 35-39     | 1206            | 121.0          | 1556            | 156.1          | 132                  | 13.2                | 
| 9    | 2000 | 40-44     | 554             | 56.1           | 1089            | 110.3          | 91                   | 9.2                 | 
| 10   | 2000 | 45-49     | 229             | 26.2           | 512             | 58.6           | 63                   | 7.2                 | 
```