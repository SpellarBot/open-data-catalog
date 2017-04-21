# NYC DOE 2015-2016 Final Class Size Report Middle & High School

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-doe-2015-2016-final-class-size-report-middle-high-school) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/icps-nwdu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/icps-nwdu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/icps-nwdu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | icps-nwdu |
| Name | NYC DOE 2015-2016 Final Class Size Report Middle & High School |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Created | 2016-03-11T20:34:33Z |
| Publication Date | 2016-03-11T20:44:31Z |

## Description

New York City Department of Education
2015-16 Final Class Size Report
School Middle School and High School Core Average Class Size
General Education (Gen Ed), Integrated Co-Teaching (ICT), Accelerated (Acc), Self-Contained (SC)

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | dbn                | DBN                | text      | text        |
| Yes      | series tag     | school_name        | School Name        | text      | text        |
| Yes      | series tag     | grade_level        | Grade Level        | text      | text        |
| Yes      | series tag     | program_type       | Program Type       | text      | text        |
| Yes      | series tag     | department         | Department         | text      | text        |
| Yes      | series tag     | subject            | Subject            | text      | text        |
| Yes      | numeric metric | number_of_students | Number of Students | number    | number      |
| Yes      | numeric metric | number_of_classes  | Number of Classes  | number    | number      |
| Yes      | numeric metric | average_class_size | Average Class Size | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:icps-nwdu d:2015-01-01T00:00:00.000Z t:program_type="Gen Ed" t:school_name="P.S. 034 FRANKLIN D. ROOSEVELT" t:dbn=01M034 t:subject="MS English Core" t:department=English t:grade_level="MS Core" m:number_of_students=85 m:average_class_size=28.3 m:number_of_classes=3

series e:icps-nwdu d:2015-01-01T00:00:00.000Z t:program_type="Gen Ed" t:school_name="P.S. 034 FRANKLIN D. ROOSEVELT" t:dbn=01M034 t:subject="MS Math Core" t:department=Math t:grade_level="MS Core" m:number_of_students=85 m:average_class_size=28.3 m:number_of_classes=3

series e:icps-nwdu d:2015-01-01T00:00:00.000Z t:program_type="Gen Ed" t:school_name="P.S. 034 FRANKLIN D. ROOSEVELT" t:dbn=01M034 t:subject="MS Science Core" t:department=Science t:grade_level="MS Core" m:number_of_students=85 m:average_class_size=28.3 m:number_of_classes=3
```

## Meta Commands

```ls
metric m:number_of_students p:integer l:"Number of Students" t:dataTypeName=number

metric m:number_of_classes p:integer l:"Number of Classes" t:dataTypeName=number

metric m:average_class_size p:double l:"Average Class Size" t:dataTypeName=number

entity e:icps-nwdu l:"NYC DOE 2015-2016 Final Class Size Report Middle & High School" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/icps-nwdu

property e:icps-nwdu t:meta.view v:id=icps-nwdu v:category=Education v:averageRating=0 v:name="NYC DOE 2015-2016 Final Class Size Report Middle & High School" v:attribution="Department of Education (DOE)"

property e:icps-nwdu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:icps-nwdu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | school_name                    | grade_level | program_type | department     | subject                | number_of_students | number_of_classes | average_class_size | 
| ====== | ============================== | =========== | ============ | ============== | ====================== | ================== | ================= | ================== | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | Gen Ed       | English        | MS English Core        | 85                 | 3                 | 28.3               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | Gen Ed       | Math           | MS Math Core           | 85                 | 3                 | 28.3               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | Gen Ed       | Science        | MS Science Core        | 85                 | 3                 | 28.3               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | Gen Ed       | Social Studies | MS Social Studies Core | 85                 | 3                 | 28.3               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | ICT          | English        | MS English Core        | 86                 | 3                 | 28.7               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | ICT          | Math           | MS Math Core           | 86                 | 3                 | 28.7               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | ICT          | Science        | MS Science Core        | 86                 | 3                 | 28.7               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | ICT          | Social Studies | MS Social Studies Core | 86                 | 3                 | 28.7               | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | SC           | English        | MS English Core        | 6                  | 1                 | 6                  | 
| 01M034 | P.S. 034 FRANKLIN D. ROOSEVELT | MS Core     | SC           | Math           | MS Math Core           | 6                  | 1                 | 6                  | 
```