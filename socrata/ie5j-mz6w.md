# Connecticut Resident Deaths, 1999-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-resident-deaths-1999-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/ie5j-mz6w) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ie5j-mz6w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ie5j-mz6w/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ie5j-mz6w |
| Name | Connecticut Resident Deaths, 1999-2013 |
| Attribution | Department of Public Health |
| Category | Health and Human Services |
| Tags | death, deaths |
| Created | 2016-02-29T19:38:20Z |
| Publication Date | 2016-02-29T19:41:32Z |

## Description

Connecticut resident deaths, 1999-2013, by Age, Sex, Race/Ethnicity for select Causes of Death; available at www.ct.gov/dph/RegistrationReport.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | source                     | SOURCE                     | text      | text        |
| Yes      | time           | death_year                 | Death Year                 | number    | text        |
| Yes      | series tag     | cause_of_death_category    | Cause of Death Category    | text      | text        |
| Yes      | series tag     | sex_of_decendent           | Sex of Decendent           | text      | text        |
| Yes      | series tag     | race_ethnicity_of_decedent | Race/Ethnicity of Decedent | text      | text        |
| Yes      | numeric metric | all_ages                   | All Ages                   | number    | number      |
| Yes      | numeric metric | less_than_5_years_old      | Less than 5 years old      | number    | number      |
| Yes      | numeric metric | 5_to_9_years_old           | 5 to 9 years old           | number    | number      |
| Yes      | numeric metric | 10_to_14_years_old         | 10 to 14 years old         | number    | number      |
| Yes      | numeric metric | 15_to_19_years_old         | 15 to 19 years old         | number    | number      |
| Yes      | numeric metric | 20_to_24_years_old         | 20 to 24 years old         | number    | number      |
| Yes      | numeric metric | 25_to_29_years_old         | 25 to 29 years old         | number    | number      |
| Yes      | numeric metric | 30_to_34_years_old         | 30 to 34 years old         | number    | number      |
| Yes      | numeric metric | 35_to_39_years_old         | 35 to 39 years old         | number    | number      |
| Yes      | numeric metric | 40_to_44_years_old         | 40 to 44 years old         | number    | number      |
| Yes      | numeric metric | 45_to_49_years_old         | 45 to 49 years old         | number    | number      |
| Yes      | numeric metric | 50_to_54_years_old         | 50 to 54 years old         | number    | number      |
| Yes      | numeric metric | 55_to_59_years_old         | 55 to 59 years old         | number    | number      |
| Yes      | numeric metric | 60_to_64_years_old         | 60 to 64 years old         | number    | number      |
| Yes      | numeric metric | 65_to_69_years_old         | 65 to 69 years old         | number    | number      |
| Yes      | numeric metric | 70_to_74_years_old         | 70 to 74 years old         | number    | number      |
| Yes      | numeric metric | 75_to_79_years_old         | 75 to 79 years old         | number    | number      |
| Yes      | numeric metric | 80_to_84_years_old         | 80 to 84 years old         | number    | number      |
| Yes      | numeric metric | 85_years_old               | 85+ years old              | number    | number      |
| Yes      | numeric metric | unknown_age                | Unknown Age                | number    | number      |
```

## Time Field

```ls
Value = death_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ie5j-mz6w d:1999-01-01T00:00:00.000Z t:cause_of_death_category="TOTAL, ALL CAUSES" t:sex_of_decendent="BOTH SEXES" t:source="Connecticut DPH Registration Reports" t:race_ethnicity_of_decedent="ALL RACES/ETHNICITIES" m:20_to_24_years_old=156 m:40_to_44_years_old=710 m:85_years_old=0 m:60_to_64_years_old=1911 m:less_than_5_years_old=30 m:unknown_age=29314 m:30_to_34_years_old=406 m:80_to_84_years_old=9202 m:50_to_54_years_old=1156 m:45_to_49_years_old=908 m:25_to_29_years_old=233 m:55_to_59_years_old=1382 m:70_to_74_years_old=4156 m:35_to_39_years_old=499 m:10_to_14_years_old=93 m:5_to_9_years_old=40 m:15_to_19_years_old=152 m:all_ages=300 m:75_to_79_years_old=4914 m:65_to_69_years_old=3066

series e:ie5j-mz6w d:1999-01-01T00:00:00.000Z t:cause_of_death_category="TOTAL, ALL CAUSES" t:sex_of_decendent=MALE t:source="Connecticut DPH Registration Reports" t:race_ethnicity_of_decedent="ALL RACES/ETHNICITIES" m:20_to_24_years_old=121 m:40_to_44_years_old=449 m:85_years_old=0 m:60_to_64_years_old=1094 m:less_than_5_years_old=14 m:unknown_age=13903 m:30_to_34_years_old=248 m:80_to_84_years_old=2988 m:50_to_54_years_old=710 m:45_to_49_years_old=556 m:25_to_29_years_old=154 m:55_to_59_years_old=828 m:70_to_74_years_old=2130 m:35_to_39_years_old=308 m:10_to_14_years_old=71 m:5_to_9_years_old=29 m:15_to_19_years_old=117 m:all_ages=173 m:75_to_79_years_old=2247 m:65_to_69_years_old=1666

series e:ie5j-mz6w d:1999-01-01T00:00:00.000Z t:cause_of_death_category="TOTAL, ALL CAUSES" t:sex_of_decendent=FEMALE t:source="Connecticut DPH Registration Reports" t:race_ethnicity_of_decedent="ALL RACES/ETHNICITIES" m:20_to_24_years_old=35 m:40_to_44_years_old=261 m:85_years_old=0 m:60_to_64_years_old=817 m:less_than_5_years_old=16 m:unknown_age=15411 m:30_to_34_years_old=158 m:80_to_84_years_old=6214 m:50_to_54_years_old=446 m:45_to_49_years_old=352 m:25_to_29_years_old=79 m:55_to_59_years_old=554 m:70_to_74_years_old=2026 m:35_to_39_years_old=191 m:10_to_14_years_old=22 m:5_to_9_years_old=11 m:15_to_19_years_old=35 m:all_ages=127 m:75_to_79_years_old=2667 m:65_to_69_years_old=1400
```

## Meta Commands

```ls
metric m:all_ages p:integer l:"All Ages" t:dataTypeName=number

metric m:less_than_5_years_old p:integer l:"Less than 5 years old" t:dataTypeName=number

metric m:5_to_9_years_old p:integer l:"5 to 9 years old" t:dataTypeName=number

metric m:10_to_14_years_old p:integer l:"10 to 14 years old" t:dataTypeName=number

metric m:15_to_19_years_old p:integer l:"15 to 19 years old" t:dataTypeName=number

metric m:20_to_24_years_old p:integer l:"20 to 24 years old" t:dataTypeName=number

metric m:25_to_29_years_old p:integer l:"25 to 29 years old" t:dataTypeName=number

metric m:30_to_34_years_old p:integer l:"30 to 34 years old" t:dataTypeName=number

metric m:35_to_39_years_old p:integer l:"35 to 39 years old" t:dataTypeName=number

metric m:40_to_44_years_old p:integer l:"40 to 44 years old" t:dataTypeName=number

metric m:45_to_49_years_old p:integer l:"45 to 49 years old" t:dataTypeName=number

metric m:50_to_54_years_old p:integer l:"50 to 54 years old" t:dataTypeName=number

metric m:55_to_59_years_old p:integer l:"55 to 59 years old" t:dataTypeName=number

metric m:60_to_64_years_old p:integer l:"60 to 64 years old" t:dataTypeName=number

metric m:65_to_69_years_old p:integer l:"65 to 69 years old" t:dataTypeName=number

metric m:70_to_74_years_old p:integer l:"70 to 74 years old" t:dataTypeName=number

metric m:75_to_79_years_old p:integer l:"75 to 79 years old" t:dataTypeName=number

metric m:80_to_84_years_old p:integer l:"80 to 84 years old" t:dataTypeName=number

metric m:85_years_old p:integer l:"85+ years old" t:dataTypeName=number

metric m:unknown_age p:integer l:"Unknown Age" t:dataTypeName=number

entity e:ie5j-mz6w l:"Connecticut Resident Deaths, 1999-2013" t:attribution="Department of Public Health" t:url=https://data.ct.gov/api/views/ie5j-mz6w

property e:ie5j-mz6w t:meta.view v:id=ie5j-mz6w v:category="Health and Human Services" v:attributionLink=http://www.ct.gov/dph/RegistrationReport v:averageRating=0 v:name="Connecticut Resident Deaths, 1999-2013" v:attribution="Department of Public Health"

property e:ie5j-mz6w t:meta.view.owner v:id=gskr-8ue9 v:screenName="Karyn Backus" v:displayName="Karyn Backus"

property e:ie5j-mz6w t:meta.view.tableauthor v:id=gskr-8ue9 v:screenName="Karyn Backus" v:roleName=editor v:displayName="Karyn Backus"
```

## Top Records

```ls
| source                               | death_year | cause_of_death_category | sex_of_decendent | race_ethnicity_of_decedent | all_ages | less_than_5_years_old | 5_to_9_years_old | 10_to_14_years_old | 15_to_19_years_old | 20_to_24_years_old | 25_to_29_years_old | 30_to_34_years_old | 35_to_39_years_old | 40_to_44_years_old | 45_to_49_years_old | 50_to_54_years_old | 55_to_59_years_old | 60_to_64_years_old | 65_to_69_years_old | 70_to_74_years_old | 75_to_79_years_old | 80_to_84_years_old | 85_years_old | unknown_age | 
| ==================================== | ========== | ======================= | ================ | ========================== | ======== | ===================== | ================ | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ============ | =========== | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | BOTH SEXES       | ALL RACES/ETHNICITIES      | 300      | 30                    | 40               | 93                 | 152                | 156                | 233                | 406                | 499                | 710                | 908                | 1156               | 1382               | 1911               | 3066               | 4156               | 4914               | 9202               | 0            | 29314       | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | MALE             | ALL RACES/ETHNICITIES      | 173      | 14                    | 29               | 71                 | 117                | 121                | 154                | 248                | 308                | 449                | 556                | 710                | 828                | 1094               | 1666               | 2130               | 2247               | 2988               | 0            | 13903       | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | FEMALE           | ALL RACES/ETHNICITIES      | 127      | 16                    | 11               | 22                 | 35                 | 35                 | 79                 | 158                | 191                | 261                | 352                | 446                | 554                | 817                | 1400               | 2026               | 2667               | 6214               | 0            | 15411       | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | BOTH SEXES       | WHITE, NON-HISPANIC        | 182      | 20                    | 22               | 66                 | 96                 | 86                 | 141                | 272                | 348                | 532                | 722                | 933                | 1153               | 1651               | 2779               | 3864               | 4667               | 8797               | 0            | 26331       | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | MALE             | WHITE, NON-HISPANIC        | 109      | 6                     | 16               | 50                 | 68                 | 66                 | 100                | 175                | 216                | 339                | 440                | 577                | 702                | 935                | 1511               | 1990               | 2142               | 2849               | 0            | 12291       | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | FEMALE           | WHITE, NON-HISPANIC        | 73       | 14                    | 6                | 16                 | 28                 | 20                 | 41                 | 97                 | 132                | 193                | 282                | 356                | 451                | 716                | 1268               | 1874               | 2525               | 5948               | 0            | 14040       | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | BOTH SEXES       | BLACK, NON-HISPANIC        | 55       | 4                     | 11               | 10                 | 27                 | 43                 | 49                 | 80                 | 94                 | 122                | 119                | 141                | 153                | 178                | 185                | 201                | 174                | 275                | 0            | 1921        | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | MALE             | BLACK, NON-HISPANIC        | 25       | 2                     | 7                | 9                  | 24                 | 32                 | 28                 | 37                 | 52                 | 78                 | 70                 | 88                 | 76                 | 117                | 91                 | 96                 | 66                 | 95                 | 0            | 993         | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | FEMALE           | BLACK, NON-HISPANIC        | 30       | 2                     | 4                | 1                  | 3                  | 11                 | 21                 | 43                 | 42                 | 44                 | 49                 | 53                 | 77                 | 61                 | 94                 | 105                | 108                | 180                | 0            | 928         | 
| Connecticut DPH Registration Reports | 1999       | TOTAL, ALL CAUSES       | BOTH SEXES       | OTHER, NON-HISPANIC        | 4        | 0                     | 0                | 0                  | 0                  | 5                  | 3                  | 4                  | 4                  | 8                  | 10                 | 7                  | 12                 | 23                 | 23                 | 19                 | 17                 | 16                 | 0            | 155         | 
```