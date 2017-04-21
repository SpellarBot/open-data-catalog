# IDPH STD Illinois By Sex

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-std-illinois-by-sex) |
| Metadata | [Link](https://data.illinois.gov/api/views/cb2a-8e6s) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cb2a-8e6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cb2a-8e6s/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cb2a-8e6s |
| Name | IDPH STD Illinois By Sex |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, chlamydia, gonorrhea, early syphilis, syphilis, count, rate, sex |
| Created | 2013-11-01T18:01:24Z |
| Publication Date | 2016-06-10T16:54:08Z |

## Description

Illinois 2000-2015 STD counts and rates (per 100,000 population) by sex. See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| Yes      | numeric metric | sort                 | Sort                  | number    | number      |
| Yes      | time           | year                 | Year                  | number    | text        |
| Yes      | series tag     | sex                  | Sex                   | text      | text        |
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
series e:cb2a-8e6s d:2000-01-01T00:00:00.000Z t:sex=Female m:early_syphilis_count=375 m:early_syphilis_rate=5.9 m:sort=1 m:chlamydia_count=31771 m:chlamydia_rate=501.2 m:gonorrhea_count=11829 m:gonorrhea_rate=186.6

series e:cb2a-8e6s d:2000-01-01T00:00:00.000Z t:sex=Male m:early_syphilis_count=419 m:early_syphilis_rate=6.9 m:sort=2 m:chlamydia_count=8578 m:chlamydia_rate=141.1 m:gonorrhea_count=12981 m:gonorrhea_rate=213.5

series e:cb2a-8e6s d:2000-01-01T00:00:00.000Z t:sex=Unknown m:early_syphilis_count=0 m:sort=3 m:chlamydia_count=1 m:gonorrhea_count=2
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

entity e:cb2a-8e6s l:"IDPH STD Illinois By Sex" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/cb2a-8e6s

property e:cb2a-8e6s t:meta.view v:id=cb2a-8e6s v:category="Public Health" v:averageRating=0 v:name="IDPH STD Illinois By Sex" v:attribution="Illinois Department of Public Health STD Program"

property e:cb2a-8e6s t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:cb2a-8e6s t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | sex     | chlamydia_count | chlamydia_rate | gonorrhea_count | gonorrhea_rate | early_syphilis_count | early_syphilis_rate | 
| ==== | ==== | ======= | =============== | ============== | =============== | ============== | ==================== | =================== | 
| 1    | 2000 | Female  | 31771           | 501.2          | 11829           | 186.6          | 375                  | 5.9                 | 
| 2    | 2000 | Male    | 8578            | 141.1          | 12981           | 213.5          | 419                  | 6.9                 | 
| 3    | 2000 | Unknown | 1               |                | 2               |                | 0                    |                     | 
| 4    | 2000 | Total   | 40350           | 324.9          | 24812           | 199.8          | 794                  | 6.4                 | 
| 1    | 2001 | Female  | 33124           | 522.5          | 12178           | 192.1          | 252                  | 4.0                 | 
| 2    | 2001 | Male    | 10588           | 174.1          | 11845           | 194.8          | 543                  | 8.9                 | 
| 3    | 2001 | Unknown | 4               |                | 2               |                | 0                    |                     | 
| 4    | 2001 | Total   | 43716           | 352.0          | 24025           | 193.4          | 795                  | 6.4                 | 
| 1    | 2002 | Female  | 34154           | 538.8          | 12273           | 193.6          | 227                  | 3.6                 | 
| 2    | 2002 | Male    | 13942           | 229.3          | 11750           | 193.2          | 779                  | 12.8                | 
```