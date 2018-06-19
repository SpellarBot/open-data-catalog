# IDPH STD Illinois By County By Race Ethnicity Gonorrhea

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-std-illinois-by-county-by-race-ethnicity-gonorrhea) |
| Metadata | [Link](https://data.illinois.gov/api/views/mypp-sb8d) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/mypp-sb8d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/mypp-sb8d/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | mypp-sb8d |
| Name | IDPH STD Illinois By County By Race Ethnicity Gonorrhea |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, gonorrhea, county, race, ethnicity, race/ethnicity, count |
| Created | 2013-11-01T16:52:54Z |
| Publication Date | 2016-09-13T16:28:45Z |

## Description

Illinois 2000-2015 STD gonorrhea counts by county by race/ethnicity. See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  {AIAN: American Indian, Alaskan Native, non-Hispanic; Asian: Asian, non-Hispanic; Black: Black or African American, non-Hispanic; Hisp: Hispanc (of any race); MultiRace: more than one race was reported, non-Hispanic (Chlamydia and gonorrhea use multiple races in reporting, syphilis cases use single race reporting (i.e., MultiRace values may be zero for syphilis cases)); NHPI: Native Hawaiian or Other Pacific Islander (Chlamydia and gonorrhea cases reports distinguishes NHPI from Asians, whereas syphilis cases group Asians, native Hawaiians and other Pacific Islanders as ?Asian? (i.e., NHPI cases in syphilis case reports may display zero cases; these cases would have been reported under Asian)); White: White or Caucasian, non-Hispanic; Other: Other race, non-Hispanic; Unk: Unknown race, ethnicity.}  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | numeric metric | sort                | Sort                | number    | number      |
| Yes      | time           | year                | Year                | number    | text        |
| Yes      | series tag     | county_jurisdiction | County/Jurisdiction | text      | text        |
| Yes      | series tag     | countyfips          | CountyFIPS          | text      | text        |
| Yes      | numeric metric | total_counts        | Total_Counts        | number    | number      |
| Yes      | numeric metric | aian_count          | AIAN_Count          | number    | number      |
| Yes      | numeric metric | asian_count         | Asian_Count         | number    | number      |
| Yes      | numeric metric | black_count         | Black_Count         | number    | number      |
| Yes      | numeric metric | hisp_count          | Hisp_Count          | number    | number      |
| Yes      | numeric metric | multirace_count     | MultiRace_Count     | number    | number      |
| Yes      | numeric metric | nhpi_count          | NHPI_Count          | number    | number      |
| Yes      | numeric metric | white_count         | White_Count         | number    | number      |
| Yes      | numeric metric | other_count         | Other_Count         | number    | number      |
| Yes      | numeric metric | unk_count           | Unk_Count           | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mypp-sb8d d:2000-01-01T00:00:00.000Z t:county_jurisdiction=ADAMS t:countyfips=17001 m:sort=1 m:total_counts=31

series e:mypp-sb8d d:2000-01-01T00:00:00.000Z t:county_jurisdiction=ALEXANDER t:countyfips=17003 m:sort=2 m:total_counts=38

series e:mypp-sb8d d:2000-01-01T00:00:00.000Z t:county_jurisdiction=BOND t:countyfips=17005 m:sort=3 m:total_counts=2
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:total_counts p:integer l:Total_Counts t:dataTypeName=number

metric m:aian_count p:integer l:AIAN_Count t:dataTypeName=number

metric m:asian_count p:integer l:Asian_Count t:dataTypeName=number

metric m:black_count p:integer l:Black_Count t:dataTypeName=number

metric m:hisp_count p:integer l:Hisp_Count t:dataTypeName=number

metric m:multirace_count p:integer l:MultiRace_Count t:dataTypeName=number

metric m:nhpi_count p:integer l:NHPI_Count t:dataTypeName=number

metric m:white_count p:integer l:White_Count t:dataTypeName=number

metric m:other_count p:integer l:Other_Count t:dataTypeName=number

metric m:unk_count p:integer l:Unk_Count t:dataTypeName=number

entity e:mypp-sb8d l:"IDPH STD Illinois By County By Race Ethnicity Gonorrhea" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/mypp-sb8d

property e:mypp-sb8d t:meta.view v:id=mypp-sb8d v:category="Public Health" v:averageRating=0 v:name="IDPH STD Illinois By County By Race Ethnicity Gonorrhea" v:attribution="Illinois Department of Public Health STD Program"

property e:mypp-sb8d t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:mypp-sb8d t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | county_jurisdiction | countyfips | total_counts | aian_count | asian_count | black_count | hisp_count | multirace_count | nhpi_count | white_count | other_count | unk_count | 
| ==== | ==== | =================== | ========== | ============ | ========== | =========== | =========== | ========== | =============== | ========== | =========== | =========== | ========= | 
| 1    | 2000 | ADAMS               | 17001      | 31           |            |             |             |            |                 |            |             |             |           | 
| 2    | 2000 | ALEXANDER           | 17003      | 38           |            |             |             |            |                 |            |             |             |           | 
| 3    | 2000 | BOND                | 17005      | 2            |            |             |             |            |                 |            |             |             |           | 
| 4    | 2000 | BOONE               | 17007      | 15           |            |             |             |            |                 |            |             |             |           | 
| 5    | 2000 | BROWN               | 17009      | 0            |            |             |             |            |                 |            |             |             |           | 
| 6    | 2000 | BUREAU              | 17011      | 3            |            |             |             |            |                 |            |             |             |           | 
| 7    | 2000 | CALHOUN             | 17013      | 0            |            |             |             |            |                 |            |             |             |           | 
| 8    | 2000 | CARROLL             | 17015      | 2            |            |             |             |            |                 |            |             |             |           | 
| 9    | 2000 | CASS                | 17017      | 1            |            |             |             |            |                 |            |             |             |           | 
| 10   | 2000 | CHAMPAIGN           | 17019      | 518          | 0          | 2           | 414         | 8          | 0               | 0          | 79          | 2           | 13        | 
```