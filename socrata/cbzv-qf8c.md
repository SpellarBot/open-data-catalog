# City of Hartford Birth Information 2002 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-hartford-birth-information-2002-2012) |
| Metadata | [Link](https://data.hartford.gov/api/views/cbzv-qf8c) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/cbzv-qf8c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/cbzv-qf8c/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | cbzv-qf8c |
| Name | City of Hartford Birth Information 2002 - 2012 |
| Attribution | City of Hartford |
| Category | Public Health |
| Tags | birth, children, education, youth, family, health, hartford, ct |
| Created | 2014-09-02T20:36:06Z |
| Publication Date | 2014-09-02T20:42:47Z |

## Description

Birth information for 2002-2012 by Neighborhood/High School District provided by the Health & Human Services Department. Updated as available.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | time        | birth_year           | Birth_Year           | number    | number      |
| Yes      | series tag  | gender               | Gender               | text      | text        |
| Yes      | series tag  | ethnicity            | Ethnicity            | text      | text        |
| Yes      | series tag  | race                 | Race                 | text      | text        |
| Yes      | series tag  | neighborhood         | Neighborhood         | text      | text        |
| Yes      | series tag  | high_school_district | High_School_District | text      | text        |
```

## Time Field

```ls
Value = birth_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:cbzv-qf8c l:"City of Hartford Birth Information 2002 - 2012" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/cbzv-qf8c

property e:cbzv-qf8c t:meta.view v:id=cbzv-qf8c v:category="Public Health" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="City of Hartford Birth Information 2002 - 2012" v:attribution="City of Hartford"

property e:cbzv-qf8c t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cbzv-qf8c t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:cbzv-qf8c t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| birth_year | gender | ethnicity                           | race        | neighborhood | high_school_district | 
| ========== | ====== | =================================== | =========== | ============ | ==================== | 
| 2002       | Male   | PUERTO RICAN                        | WHITE       | SOUTH WEST   | Zone 3               | 
| 2002       | Female | NON_HISPANIC                        | WHITE       | SOUTH WEST   | Zone 3               | 
| 2002       | Male   | NON_HISPANIC                        | BLACK       | SOUTH WEST   | Zone 3               | 
| 2002       | Male   | HISPANIC ORIGIN IDENTITY NOT STATED | OTHER ASIAN | SOUTH WEST   | Zone 3               | 
| 2002       | Male   | HISPANIC ORIGIN IDENTITY NOT STATED | WHITE       | SOUTH WEST   | Zone 3               | 
| 2002       | Female | NON_HISPANIC                        | WHITE       | SOUTH WEST   | Zone 3               | 
| 2002       | Female | PUERTO RICAN                        | WHITE       | SOUTH WEST   | Zone 3               | 
| 2002       | Female | PUERTO RICAN                        | WHITE       | SOUTH WEST   | Zone 3               | 
| 2002       | Male   | NON_HISPANIC                        | BLACK       | SOUTH WEST   | Zone 3               | 
| 2002       | Male   | NON_HISPANIC                        | BLACK       | SOUTH WEST   | Zone 3               | 
```