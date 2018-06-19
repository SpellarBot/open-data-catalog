# 2011-2012 NYC Family Guides

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-2012-nyc-family-guides-38af0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fuvx-wqd7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fuvx-wqd7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fuvx-wqd7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fuvx-wqd7 |
| Name | 2011-2012 NYC Family Guides |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | doe, famil guide, program, language, url, info, education, school, lifelong learning |
| Created | 2011-10-11T04:34:52Z |
| Publication Date | 2011-10-11T04:36:07Z |

## Description

2011-2012 NYC Family Guides Update schedule: As required

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | numeric metric | grade             | Grade             | number    | number      |
| Yes      | series tag     | family_guide_name | Family Guide Name | text      | text        |
| Yes      | series tag     | link              | Link              | text      | text        |
| Yes      | series tag     | language          | Language          | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fuvx-wqd7 d:2011-01-01T00:00:00.000Z t:link=http://schools.nyc.gov/NR/rdonlyres/EBD4D416-8FB3-4B7D-9151-B891E50B2EEA/0/Grade1Arabic_LowResFinals.pdf t:language=Arabic t:family_guide_name="2011-2012 NYC Family Guide for First Grade" m:grade=1

series e:fuvx-wqd7 d:2011-01-01T00:00:00.000Z t:link=http://schools.nyc.gov/NR/rdonlyres/7B33BB6B-D4F0-415F-BF21-602E2745D22E/0/Grade2Arabic_LowResFinals.pdf t:language=Arabic t:family_guide_name="2011-2012 NYC Family Guide for Second Grade" m:grade=2

series e:fuvx-wqd7 d:2011-01-01T00:00:00.000Z t:link=http://schools.nyc.gov/NR/rdonlyres/FD539338-9E7A-49D8-BD35-886AFF7243A8/0/Grade3Arabic_LowResFinals.pdf t:language=Arabic t:family_guide_name="2011-2012 NYC Family Guide for Third Grade" m:grade=3
```

## Meta Commands

```ls
metric m:grade p:integer l:Grade t:dataTypeName=number

entity e:fuvx-wqd7 l:"2011-2012 NYC Family Guides" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/fuvx-wqd7

property e:fuvx-wqd7 t:meta.view v:id=fuvx-wqd7 v:category=Education v:averageRating=100 v:name="2011-2012 NYC Family Guides" v:attribution="Department of Education (DOE)"

property e:fuvx-wqd7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fuvx-wqd7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| grade | family_guide_name                               | link                                                                                                                                                                 | language | 
| ===== | =============================================== | ==================================================================================================================================================================== | ======== | 
|       | 2011-2012 NYC Family Guide for Pre-Kindergarten | http://schools.nyc.gov/NR/rdonlyres/F3D5490B-7D8B-4D5E-B7ED-A0C45E51A8E7/0/GradePreKArabic_LowResFinals.pdf                                                          | Arabic   | 
|       | 2011-2012 NYC Family Guide for Kindergarten     | http://schools.nyc.gov/NR/rdonlyres/ECB713CA-DAF6-4E88-AE39-762ACB30B21B/0/GradeKArabic_LowResFinals.pdf-DAF6-4E88-AE39-762ACB30B21B/0/GradeKArabic_LowResFinals.pdf | Arabic   | 
| 1     | 2011-2012 NYC Family Guide for First Grade      | http://schools.nyc.gov/NR/rdonlyres/EBD4D416-8FB3-4B7D-9151-B891E50B2EEA/0/Grade1Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 2     | 2011-2012 NYC Family Guide for Second Grade     | http://schools.nyc.gov/NR/rdonlyres/7B33BB6B-D4F0-415F-BF21-602E2745D22E/0/Grade2Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 3     | 2011-2012 NYC Family Guide for Third Grade      | http://schools.nyc.gov/NR/rdonlyres/FD539338-9E7A-49D8-BD35-886AFF7243A8/0/Grade3Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 4     | 2011-2012 NYC Family Guide for Fourth Grade     | http://schools.nyc.gov/NR/rdonlyres/2F814DE7-BCD3-4AD8-A872-65B8E3F4CDD8/0/Grade4Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 5     | 2011-2012 NYC Family Guide for Fifth Grade      | http://schools.nyc.gov/NR/rdonlyres/C8F83CF0-72C1-4E7F-B0B7-3C8ACF713FB6/0/Grade5Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 6     | 2011-2012 NYC Family Guide for Sixth Grade      | http://schools.nyc.gov/NR/rdonlyres/CDB70BFF-C18E-46FB-9E39-24AAF1EBDCD2/0/Grade6Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 7     | 2011-2012 NYC Family Guide for Seventh Grade    | http://schools.nyc.gov/NR/rdonlyres/5A6474DF-8A17-4404-8671-4C092C98FA7F/0/Grade7Arabic_LowResFinals.pdf                                                             | Arabic   | 
| 8     | 2011-2012 NYC Family Guide for Eighth Grade     | http://schools.nyc.gov/NR/rdonlyres/222E92BC-B0CB-4DBE-889E-4B145E436531/0/Grade8Arabic_LowResFinals.pdf                                                             | Arabic   | 
```