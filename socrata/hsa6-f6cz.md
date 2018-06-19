# IDPH STD Illinois By County By Sex

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-std-illinois-by-county-by-sex-d8a64) |
| Metadata | [Link](https://data.illinois.gov/api/views/hsa6-f6cz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hsa6-f6cz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hsa6-f6cz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hsa6-f6cz |
| Name | IDPH STD Illinois By County By Sex |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, chlamydia, gonorrhea, early syphilis, syphilis, county, count, sex |
| Created | 2013-11-01T17:28:54Z |
| Publication Date | 2016-06-10T18:51:08Z |

## Description

Illinois 2000-2015 STD counts by county by sex (where sex is known). See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Cases reported with unknown sex have been excluded.  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | numeric metric | sort                        | Sort                        | number    | number      |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | series tag     | county_jurisdiction         | County/Jurisdiction         | text      | text        |
| Yes      | series tag     | countyfips                  | CountyFIPS                  | text      | text        |
| Yes      | numeric metric | chlamydia_male_count        | Chlamydia_Male_Count        | number    | number      |
| Yes      | numeric metric | chlamydia_female_count      | Chlamydia_Female_Count      | number    | number      |
| Yes      | numeric metric | gonorrhea_male_count        | Gonorrhea_Male_Count        | number    | number      |
| Yes      | numeric metric | gonorrhea_female_count      | Gonorrhea_Female_Count      | number    | number      |
| Yes      | numeric metric | early_syphilis_male_count   | Early_Syphilis_Male_Count   | number    | number      |
| Yes      | numeric metric | early_syphilis_female_count | Early_Syphilis_Female_Count | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hsa6-f6cz d:2000-01-01T00:00:00.000Z t:county_jurisdiction=ADAMS t:countyfips=17001 m:gonorrhea_male_count=12 m:early_syphilis_female_count=1 m:chlamydia_female_count=61 m:sort=1 m:gonorrhea_female_count=19 m:chlamydia_male_count=13 m:early_syphilis_male_count=1

series e:hsa6-f6cz d:2000-01-01T00:00:00.000Z t:county_jurisdiction=ALEXANDER t:countyfips=17003 m:gonorrhea_male_count=21 m:early_syphilis_female_count=0 m:chlamydia_female_count=53 m:sort=2 m:gonorrhea_female_count=17 m:chlamydia_male_count=17 m:early_syphilis_male_count=0

series e:hsa6-f6cz d:2000-01-01T00:00:00.000Z t:county_jurisdiction=BOND t:countyfips=17005 m:gonorrhea_male_count=1 m:early_syphilis_female_count=0 m:chlamydia_female_count=12 m:sort=3 m:gonorrhea_female_count=1 m:chlamydia_male_count=4 m:early_syphilis_male_count=0
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:chlamydia_male_count p:integer l:Chlamydia_Male_Count t:dataTypeName=number

metric m:chlamydia_female_count p:integer l:Chlamydia_Female_Count t:dataTypeName=number

metric m:gonorrhea_male_count p:integer l:Gonorrhea_Male_Count t:dataTypeName=number

metric m:gonorrhea_female_count p:integer l:Gonorrhea_Female_Count t:dataTypeName=number

metric m:early_syphilis_male_count p:integer l:Early_Syphilis_Male_Count t:dataTypeName=number

metric m:early_syphilis_female_count p:integer l:Early_Syphilis_Female_Count t:dataTypeName=number

entity e:hsa6-f6cz l:"IDPH STD Illinois By County By Sex" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/hsa6-f6cz

property e:hsa6-f6cz t:meta.view v:id=hsa6-f6cz v:category="Public Health" v:averageRating=0 v:name="IDPH STD Illinois By County By Sex" v:attribution="Illinois Department of Public Health STD Program"

property e:hsa6-f6cz t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:hsa6-f6cz t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | county_jurisdiction | countyfips | chlamydia_male_count | chlamydia_female_count | gonorrhea_male_count | gonorrhea_female_count | early_syphilis_male_count | early_syphilis_female_count | 
| ==== | ==== | =================== | ========== | ==================== | ====================== | ==================== | ====================== | ========================= | =========================== | 
| 1    | 2000 | ADAMS               | 17001      | 13                   | 61                     | 12                   | 19                     | 1                         | 1                           | 
| 2    | 2000 | ALEXANDER           | 17003      | 17                   | 53                     | 21                   | 17                     | 0                         | 0                           | 
| 3    | 2000 | BOND                | 17005      | 4                    | 12                     | 1                    | 1                      | 0                         | 0                           | 
| 4    | 2000 | BOONE               | 17007      | 12                   | 40                     | 6                    | 9                      | 1                         | 0                           | 
| 5    | 2000 | BROWN               | 17009      | 6                    | 4                      | 0                    | 0                      | 0                         | 0                           | 
| 6    | 2000 | BUREAU              | 17011      | 4                    | 27                     | 1                    | 2                      | 0                         | 0                           | 
| 7    | 2000 | CALHOUN             | 17013      | 1                    | 5                      | 0                    | 0                      | 0                         | 0                           | 
| 8    | 2000 | CARROLL             | 17015      | 1                    | 10                     | 0                    | 2                      | 0                         | 0                           | 
| 9    | 2000 | CASS                | 17017      | 2                    | 16                     | 0                    | 1                      | 0                         | 0                           | 
| 10   | 2000 | CHAMPAIGN           | 17019      | 195                  | 705                    | 199                  | 319                    | 1                         | 2                           | 
```