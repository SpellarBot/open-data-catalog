# BPD Employee File As Of 06/09/2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bpd-employee-file-as-of-06-09-2016) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/84yu-nmcy) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/84yu-nmcy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/84yu-nmcy/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 84yu-nmcy |
| Name | BPD Employee File As Of 06/09/2016 |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | bpd, employee |
| Created | 2016-06-09T19:14:58Z |
| Publication Date | 2016-06-09T19:21:59Z |

## Description

The dataset represents active employees of the Baltimore Police Department.  The demographics include rank, assignment, race, gender, age and years of service among other attributes.  The data is obtained from the agency's Records Management System (RMS) Master Employee Module.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | title            | TITLE            | text      | text        |
| Yes      | series tag     | assignment       | ASSIGNMENT       | text      | text        |
| Yes      | series tag     | race_ethnicity   | RACE/ETHNICITY   | text      | text        |
| Yes      | series tag     | gender           | GENDER           | text      | text        |
| Yes      | numeric metric | age              | AGE              | number    | number      |
| Yes      | numeric metric | years_in_service | YEARS_IN_SERVICE | number    | number      |
| Yes      | series tag     | degree           | DEGREE           | text      | text        |
| Yes      | series tag     | city_resident    | CITY_RESIDENT?   | text      | text        |
| Yes      | series tag     | agency           | AGENCY           | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:84yu-nmcy d:2016-01-01T00:00:00.000Z t:assignment="ADULT/JUVENILE BOOKING" t:title=CAPTAIN t:degree="B.A. OR B.S. COMPLETED & RECEIVED" t:city_resident=NO t:agency=BPD t:gender=MALE t:race_ethnicity=WHITE m:years_in_service=17 m:age=45

series e:84yu-nmcy d:2016-01-01T00:00:00.000Z t:assignment="ADULT/JUVENILE BOOKING" t:title="POLICE LIEUTENANT" t:degree="B.A. OR B.S. COMPLETED & RECEIVED" t:city_resident=YES t:agency=BPD t:gender=MALE t:race_ethnicity="AFRICAN AMERICAN" m:years_in_service=28 m:age=46

series e:84yu-nmcy d:2016-01-01T00:00:00.000Z t:assignment="ADULT/JUVENILE BOOKING" t:title="POLICE OFFICER" t:degree="HGH SCHOOL GRADUATE" t:city_resident=NO t:agency=BPD t:gender=MALE t:race_ethnicity="AFRICAN AMERICAN" m:years_in_service=14 m:age=33
```

## Meta Commands

```ls
metric m:age p:float l:AGE t:dataTypeName=number

metric m:years_in_service p:float l:YEARS_IN_SERVICE t:dataTypeName=number

entity e:84yu-nmcy l:"BPD Employee File As Of  06/09/2016" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/84yu-nmcy

property e:84yu-nmcy t:meta.view v:id=84yu-nmcy v:category="Public Safety" v:averageRating=0 v:name="BPD Employee File As Of  06/09/2016" v:attribution="Baltimore Police Department"

property e:84yu-nmcy t:meta.view.owner v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:displayName="Jeffrey Cooper"

property e:84yu-nmcy t:meta.view.tableauthor v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:roleName=publisher v:displayName="Jeffrey Cooper"
```

## Top Records

```ls
| title             | assignment             | race_ethnicity   | gender | age  | years_in_service | degree                            | city_resident | agency | 
| ================= | ====================== | ================ | ====== | ==== | ================ | ================================= | ============= | ====== | 
| CAPTAIN           | ADULT/JUVENILE BOOKING | WHITE            | MALE   | 45.0 | 17.0             | B.A. OR B.S. COMPLETED & RECEIVED | NO            | BPD    | 
| POLICE LIEUTENANT | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | MALE   | 46.0 | 28.0             | B.A. OR B.S. COMPLETED & RECEIVED | YES           | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | MALE   | 33.0 | 14.0             | HGH SCHOOL GRADUATE               | NO            | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | MALE   | 46.0 | 21.0             | 2 YEARS COLLEGE; NO A. A.         | YES           | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | OTHER HISPANIC   | MALE   | 38.0 | 5.0              | B.A. OR B.S. COMPLETED & RECEIVED | YES           | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | WHITE            | MALE   | 31.0 | 8.0              | A.A. COMPLETED & RECEIVED         | NO            | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | FEMALE | 42.0 | 7.0              | HGH SCHOOL GRADUATE               | YES           | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | FEMALE |      |                  | 1 YEAR COLLEGE OR LESS            | NO            | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | FEMALE | 51.0 | 15.0             | B.A. OR B.S. COMPLETED & RECEIVED | NO            | BPD    | 
| POLICE OFFICER    | ADULT/JUVENILE BOOKING | AFRICAN AMERICAN | MALE   | 39.0 | 15.0             | HIGH SCHOOL GED / EQUIVALENCY     | NO            | BPD    | 
```