# Math And Reading Proficiency by School Year, Public School District and Grade Level

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-and-reading-proficiency-by-school-year-public-school-district-and-grade-level) |
| Metadata | [Link](https://data.iowa.gov/api/views/f3h8-mnxi) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/f3h8-mnxi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/f3h8-mnxi/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | f3h8-mnxi |
| Name | Math And Reading Proficiency by School Year, Public School District and Grade Level |
| Attribution | Iowa Department of Education, Adequate Yearly Progress |
| Category | Education |
| Tags | reading, math, mathematics, adequate yearly progress, ayp, academic progress, student performance |
| Created | 2014-11-26T15:34:35Z |
| Publication Date | 2016-08-08T21:09:30Z |

## Description

Dataset contains information on public school districts academic progress of their students in reading and math annually starting with school year ending in 2003.  All public schools and districts report annually to the Iowa Department of Education through Adequate Yearly Progress (AYP).  All AYP determinations are made annually using reading and math student assessment data.  Proficiency is based on a standard score scale.  More information can be found at: http://itp.education.uiowa.edu/ia/AYPInformation.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | numeric metric | school_year         | School Year         | number    | number      |
| Yes      | series tag     | topic               | Topic               | text      | text        |
| Yes      | numeric metric | grade               | Grade               | number    | number      |
| Yes      | series tag     | district            | District            | text      | text        |
| Yes      | series tag     | district_name       | District Name       | text      | text        |
| Yes      | numeric metric | proficient_1        | Proficient          | number    | number      |
| Yes      | numeric metric | total               | Total               | number    | number      |
| Yes      | numeric metric | proficient_2        | % Proficient        | number    | number      |
| Yes      | series tag     | proficient_category | Proficient Category | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:f3h8-mnxi d:2014-12-05T08:06:08.000Z t:topic=Reading t:district_name=Central t:district=1080 t:proficient_category="60.1 - 70%" m:total=59 m:proficient_2=67.8 m:grade=11 m:school_year=2003 m:proficient_1=40

series e:f3h8-mnxi d:2014-12-05T08:06:08.000Z t:topic=Reading t:district_name=Cardinal t:district=0977 t:proficient_category="70.1 - 80%" m:total=44 m:proficient_2=70.5 m:grade=11 m:school_year=2004 m:proficient_1=31

series e:f3h8-mnxi d:2014-12-05T08:06:08.000Z t:topic=Reading t:district_name=Jefferson-Scranton t:district=3195 t:proficient_category="80.1 - 90%" m:total=76 m:proficient_2=81.6 m:grade=7 m:school_year=2013 m:proficient_1=62
```

## Meta Commands

```ls
metric m:school_year p:integer l:"School Year" d:"School year, indicated by year ending, assessment information is associated with" t:dataTypeName=number

metric m:grade p:integer l:Grade d:"Indicates the grade level of students assessed." t:dataTypeName=number

metric m:proficient_1 p:integer l:Proficient d:"Number of students tested that were considered proficient - meeting standard score metric associated with the grade and content. A null value identified by SCS (small cell size) indicates data was redacted to ensure privacy standards where met." t:dataTypeName=number

metric m:total p:integer l:Total d:"Total displays the number of students tested who were enrolled in the school district for the full academic year. A null value identified by SCS (small cell size) indicates data was redacted to ensure privacy standards where met." t:dataTypeName=number

metric m:proficient_2 p:float l:"% Proficient" d:"Numerator is the number of proficient students tested and the denominator is the total number of students tested who were enrolled in the school district for the full academic year. A null value identified by SCS (small cell size) indicates data was redacted to ensure privacy standards where met." t:dataTypeName=number

entity e:f3h8-mnxi l:"Math And Reading Proficiency by School Year, Public School District and Grade Level" t:attribution="Iowa Department of Education, Adequate Yearly Progress" t:url=https://data.iowa.gov/api/views/f3h8-mnxi

property e:f3h8-mnxi t:meta.view v:id=f3h8-mnxi v:category=Education v:averageRating=0 v:name="Math And Reading Proficiency by School Year, Public School District and Grade Level" v:attribution="Iowa Department of Education, Adequate Yearly Progress"

property e:f3h8-mnxi t:meta.view.license v:name="Public Domain"

property e:f3h8-mnxi t:meta.view.owner v:id=2fjc-cwwr v:profileImageUrlMedium=/api/users/2fjc-cwwr/profile_images/THUMB v:profileImageUrlLarge=/api/users/2fjc-cwwr/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/2fjc-cwwr/profile_images/TINY v:displayName="Iowa Department of Education"

property e:f3h8-mnxi t:meta.view.tableauthor v:id=2fjc-cwwr v:profileImageUrlMedium=/api/users/2fjc-cwwr/profile_images/THUMB v:profileImageUrlLarge=/api/users/2fjc-cwwr/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/2fjc-cwwr/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| :updated_at | school_year | topic   | grade | district | district_name            | proficient_1 | total | proficient_2 | proficient_category | 
| =========== | =========== | ======= | ===== | ======== | ======================== | ============ | ===== | ============ | =================== | 
| 1417766768  | 2003        | Reading | 11    | 1080     | Central                  | 40           | 59    | 67.8         | 60.1 - 70%          | 
| 1417766768  | 2004        | Reading | 11    | 0977     | Cardinal                 | 31           | 44    | 70.5         | 70.1 - 80%          | 
| 1417766768  | 2013        | Reading | 7     | 3195     | Jefferson-Scranton       | 62           | 76    | 81.6         | 80.1 - 90%          | 
| 1417766768  | 2005        | Reading | 11    | 6462     | Tri-County               | 19           | 25    | 76.0         | 70.1 - 80%          | 
| 1417766768  | 2013        | Math    | 8     | 1917     | Boyer Valley             | 19           | 29    | 65.5         | 60.1 - 70%          | 
| 1417766768  | 2009        | Reading | 6     | 0270     | Anthon-Oto               | 33           | 53    | 62.3         | 60.1 - 70%          | 
| 1417766768  | 2006        | Reading | 8     | 4689     | New London               | 19           | 38    | 50.0         | 40.1 - 50%          | 
| 1417766768  | 2012        | Math    | 3     | 4023     | Manson Northwest Webster | 41           | 45    | 91.1         | 90.1 - 100%         | 
| 1417766768  | 2006        | Reading | 11    | 1989     | Edgewood-Colesburg       | 47           | 51    | 92.2         | 90.1 - 100%         | 
| 1417766768  | 2012        | Reading | 8     | 4599     | Nashua-Plainfield        | 33           | 42    | 78.6         | 70.1 - 80%          | 
```