# Headcount Enrollment by Student Level and Student Load, State University of New York: Beginning 1948

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/headcount-enrollment-by-student-level-and-student-load-state-university-of-new-york-beginn) |
| Metadata | [Link](https://data.ny.gov/api/views/ben2-nyur) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ben2-nyur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ben2-nyur/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ben2-nyur |
| Name | Headcount Enrollment by Student Level and Student Load, State University of New York: Beginning 1948 |
| Attribution | SUNY System Administration, Office of Institutional Research |
| Category | Education |
| Tags | suny institutions, student enrollment |
| Created | 2013-03-05T22:33:30Z |
| Publication Date | 2016-09-09T21:07:16Z |

## Description

Number of home institution students attending a SUNY campus by level (Undergraduate/Graduate) and load status (full-time, part-time). SUNY System combined annual enrollment since 1948.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | year                    | Year                    | number    | text        |
| Yes      | numeric metric | all_students_total      | All Students Total      | number    | text        |
| Yes      | numeric metric | all_students_full_time  | All Students Full-Time  | number    | text        |
| Yes      | numeric metric | all_students_part_time  | All Students Part-Time  | number    | text        |
| Yes      | numeric metric | undergraduate_total     | Undergraduate Total     | number    | text        |
| Yes      | numeric metric | undergraduate_full_time | Undergraduate Full-Time | number    | text        |
| Yes      | numeric metric | undergraduate_part_time | Undergraduate Part-Time | number    | text        |
| Yes      | numeric metric | graduate_total          | Graduate Total          | number    | text        |
| Yes      | numeric metric | graduate_full_time      | Graduate Full-Time      | number    | text        |
| Yes      | numeric metric | graduate_part_time      | Graduate Part-Time      | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ben2-nyur d:2015-01-01T00:00:00.000Z m:all_students_full_time=306811 m:graduate_full_time=24308 m:all_students_part_time=136129 m:all_students_total=442940 m:graduate_total=40218 m:undergraduate_full_time=282503 m:undergraduate_part_time=120219 m:undergraduate_total=402722 m:graduate_part_time=15910

series e:ben2-nyur d:2014-01-01T00:00:00.000Z m:all_students_full_time=313699 m:graduate_full_time=24132 m:all_students_part_time=141140 m:all_students_total=454839 m:graduate_total=40535 m:undergraduate_full_time=289567 m:undergraduate_part_time=124737 m:undergraduate_total=414304 m:graduate_part_time=16403

series e:ben2-nyur d:2013-01-01T00:00:00.000Z m:all_students_full_time=319539 m:graduate_full_time=24518 m:all_students_part_time=140011 m:all_students_total=459550 m:graduate_total=40633 m:undergraduate_full_time=295021 m:undergraduate_part_time=123896 m:undergraduate_total=418917 m:graduate_part_time=16115
```

## Meta Commands

```ls
metric m:all_students_total p:long l:"All Students Total" d:"a Part-time data not available." t:dataTypeName=number

metric m:all_students_full_time p:long l:"All Students Full-Time" t:dataTypeName=number

metric m:all_students_part_time p:long l:"All Students Part-Time" d:"a Part-time data not available." t:dataTypeName=number

metric m:undergraduate_total p:long l:"Undergraduate Total" d:"a Part-time data not available." t:dataTypeName=number

metric m:undergraduate_full_time p:long l:"Undergraduate Full-Time" t:dataTypeName=number

metric m:undergraduate_part_time p:long l:"Undergraduate Part-Time" d:"a - Part-time data not available." t:dataTypeName=number

metric m:graduate_total p:long l:"Graduate Total" d:"a Part-time data not available." t:dataTypeName=number

metric m:graduate_full_time p:long l:"Graduate Full-Time" t:dataTypeName=number

metric m:graduate_part_time p:long l:"Graduate Part-Time" d:"a - Part-time data not available." t:dataTypeName=number

entity e:ben2-nyur l:"Headcount Enrollment by Student Level and Student Load, State University of New York: Beginning 1948" t:attribution="SUNY System Administration, Office of Institutional Research" t:url=https://data.ny.gov/api/views/ben2-nyur

property e:ben2-nyur t:meta.view v:id=ben2-nyur v:category=Education v:attributionLink=http://www.suny.edu/ v:averageRating=0 v:name="Headcount Enrollment by Student Level and Student Load, State University of New York: Beginning 1948" v:attribution="SUNY System Administration, Office of Institutional Research"

property e:ben2-nyur t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ben2-nyur t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ben2-nyur t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | all_students_total | all_students_full_time | all_students_part_time | undergraduate_total | undergraduate_full_time | undergraduate_part_time | graduate_total | graduate_full_time | graduate_part_time | 
| ==== | ================== | ====================== | ====================== | =================== | ======================= | ======================= | ============== | ================== | ================== | 
| 2015 | 442,940            | 306,811                | 136,129                | 402,722             | 282,503                 | 120,219                 | 40,218         | 24,308             | 15,910             | 
| 2014 | 454,839            | 313,699                | 141,140                | 414,304             | 289,567                 | 124,737                 | 40,535         | 24,132             | 16,403             | 
| 2013 | 459,550            | 319,539                | 140,011                | 418,917             | 295,021                 | 123,896                 | 40,633         | 24,518             | 16,115             | 
| 2012 | 461,816            | 319,797                | 142,019                | 421,716             | 296,187                 | 125,529                 | 40,100         | 23,610             | 16,490             | 
| 2011 | 468,006            | 323,903                | 144,103                | 427,402             | 300,602                 | 126,800                 | 40,604         | 23,301             | 17,303             | 
| 2010 | 471,105            | 332,479                | 138,626                | 429,020             | 308,634                 | 120,386                 | 42,085         | 23,845             | 18,240             | 
| 2009 | 461,447            | 326,428                | 135,019                | 419,886             | 303,180                 | 116,706                 | 41,561         | 23,248             | 18,313             | 
| 2008 | 439,523            | 306,517                | 133,006                | 398,617             | 283,557                 | 115,060                 | 40,906         | 22,960             | 17,946             | 
| 2007 | 427,398            | 298,040                | 129,358                | 386,818             | 275,058                 | 111,760                 | 40,580         | 22,982             | 17,598             | 
| 2006 | 417,575            | 290,691                | 126,884                | 377,283             | 268,068                 | 109,215                 | 40,292         | 22,623             | 17,669             | 
```