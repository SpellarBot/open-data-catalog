# Managing for Results - Maryland State Department of Education (MSDE) - Supplemental Dataset for Objective 1.1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/managing-for-results-maryland-state-department-of-education-msde-supplemental-dataset-for-) |
| Metadata | [Link](https://data.maryland.gov/api/views/iadb-36pt) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iadb-36pt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iadb-36pt/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iadb-36pt |
| Name | Managing for Results - Maryland State Department of Education (MSDE) - Supplemental Dataset for Objective 1.1 |
| Attribution | Department of Budget and Management (DBM) |
| Category | Education |
| Tags | managing for results, mfr, department of budget and management, dbm, state department of assessments and taxation, sdat, taxation, assessments, tax, property, properties, real estate, income tax, ... |
| Created | 2016-05-16T17:48:41Z |
| Publication Date | 2016-05-16T18:04:02Z |

## Description

This dataset contains data from the Department of Budget and Management as part of the Managing for Results (MFR) program. DBM collects these data for each state agency. The MFR data are published to the Open Data Portal by the Department of Information Technology (DoIT). This dataset contains only the data for the Maryland State Department of Education's Objective 1.1: 'By 2016-2017, the percentage of non-proficient students in English/language arts and mathematics on State Assessments will be reduced from baseline data which will be established following the 2014-15 administration of the new PARCC assessments.' This objective falls under MSDE's Goal 1: 'Achievement will improve for each student.' For the rest of MSDE's Managing for Results data, please see this dataset: https://data.maryland.gov/Education/Managing-for-Results-Maryland-State-Department-of-/hqge-qgw8

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | fiscal_year | Fiscal Year | number    | text        |
| Yes      | numeric metric | g101        | G101        | percent   | percent     |
| Yes      | numeric metric | g102        | G102        | percent   | percent     |
| Yes      | numeric metric | g103        | G103        | percent   | percent     |
| Yes      | numeric metric | g104        | G104        | percent   | percent     |
| Yes      | numeric metric | g105        | G105        | percent   | percent     |
| Yes      | numeric metric | g106        | G106        | percent   | percent     |
| Yes      | numeric metric | g107        | G107        | percent   | percent     |
| Yes      | numeric metric | g108        | G108        | percent   | percent     |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iadb-36pt d:2003-01-01T00:00:00.000Z m:g106=55 m:g107=39.6 m:g101=58.1 m:g105=65.1 m:g103=59.9 m:g102=65.6

series e:iadb-36pt d:2004-01-01T00:00:00.000Z m:g106=63.1 m:g107=45.7 m:g101=71 m:g105=72.2 m:g103=63.9 m:g102=68.4

series e:iadb-36pt d:2005-01-01T00:00:00.000Z m:g106=69.2 m:g107=51.7 m:g101=75.9 m:g105=76.8 m:g103=66.4 m:g102=74.3
```

## Meta Commands

```ls
metric m:g101 p:float l:G101 t:dataTypeName=percent

metric m:g102 p:float l:G102 t:dataTypeName=percent

metric m:g103 p:float l:G103 t:dataTypeName=percent

metric m:g104 p:float l:G104 t:dataTypeName=percent

metric m:g105 p:float l:G105 t:dataTypeName=percent

metric m:g106 p:float l:G106 t:dataTypeName=percent

metric m:g107 p:float l:G107 t:dataTypeName=percent

metric m:g108 p:float l:G108 t:dataTypeName=percent

entity e:iadb-36pt l:"Managing for Results - Maryland State Department of Education (MSDE) - Supplemental Dataset for Objective 1.1" t:attribution="Department of Budget and Management (DBM)" t:url=https://data.maryland.gov/api/views/iadb-36pt

property e:iadb-36pt t:meta.view v:id=iadb-36pt v:category=Education v:attributionLink=http://dbm.maryland.gov/pages/default.aspx v:averageRating=0 v:name="Managing for Results - Maryland State Department of Education (MSDE) - Supplemental Dataset for Objective 1.1" v:attribution="Department of Budget and Management (DBM)"

property e:iadb-36pt t:meta.view.license v:name="Public Domain"

property e:iadb-36pt t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:iadb-36pt t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| fiscal_year | g101 | g102 | g103 | g104 | g105 | g106 | g107 | g108 | 
| =========== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| 2003        | 58.1 | 65.6 | 59.9 |      | 65.1 | 55   | 39.6 |      | 
| 2004        | 71   | 68.4 | 63.9 |      | 72.2 | 63.1 | 45.7 |      | 
| 2005        | 75.9 | 74.3 | 66.4 |      | 76.8 | 69.2 | 51.7 |      | 
| 2006        | 78.3 | 76.6 | 67   |      | 79.1 | 73.4 | 55.1 |      | 
| 2007        | 80.5 | 76.7 | 68.3 |      | 78.6 | 78.3 | 56.7 |      | 
| 2008        | 83   | 86.7 | 72.8 |      | 82.6 | 80.5 | 61.9 |      | 
| 2009        | 84.9 | 89.5 | 80.2 | 86.6 | 84.3 | 81.2 | 65.8 | 88.8 | 
| 2010        | 84   | 89.4 | 80.4 | 83.7 | 86   | 83.1 | 65.4 | 87.9 | 
| 2011        | 85.1 | 90.2 | 82.7 | 85.2 | 86.3 | 82.3 | 66.1 | 87.9 | 
| 2012        | 85   | 89.9 | 80.8 | 86.4 | 87.8 | 85.3 | 69.3 | 87.9 | 
```