# APD Incident Extract 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/apd-incident-extract-2009) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ei2n-fehk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ei2n-fehk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ei2n-fehk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ei2n-fehk |
| Name | APD Incident Extract 2009 |
| Attribution | City of Austin |
| Category | Public Safety |
| Created | 2011-12-16T21:09:19Z |
| Publication Date | 2016-08-19T13:55:52Z |

## Description

Please read and understand the following information. 
 
Understanding the following conditions will allow you to get the most out of the data provided.
???	Due to the methodological differences in data collection, different data sources may produce different results. 
???	Our on-line database is continuously being updated. The data provided here represents a particular point in time. 
Searches may be accomplished using several geographic boundaries: Police area commands or districts, zip codes and census tracts. Additionally, a known case number may be entered. Updates to the police report database occur daily. Information is available from today???s date back 18 months. 
Due to several factors (once-a-day updates, offense reclassification, reported versus occurred dates, etc.) comparisons should not be made between numbers generated with this database to any other official police reports. Data provided represents only calls for police service where a report was written.
Totals in the database may vary considerably from official totals following investigation and final categorization. Therefore, the data should not be used for comparisons with Uniform Crime Report statistics.
The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | incident_report_number | Incident Report Number | text      | text        |
| Yes      | series tag     | crime_type             | Crime Type             | text      | text        |
| Yes      | time           | date                   | Date                   | date      | date        |
| Yes      | numeric metric | time                   | Time                   | number    | number      |
| Yes      | series tag     | location_type          | LOCATION_TYPE          | text      | text        |
| No       |                | address                | ADDRESS                | text      | text        |
| No       |                | longitude              | LONGITUDE              | number    | number      |
| No       |                | latitude               | LATITUDE               | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:ei2n-fehk d:2009-12-12T08:00:00.000Z t:crime_type="CRASH/LEAVING THE SCENE" t:incident_report_number=20093460525 m:time=538

series e:ei2n-fehk d:2009-12-22T08:00:00.000Z t:crime_type="DISTURBANCE - OTHER" t:incident_report_number=20093560107 m:time=104

series e:ei2n-fehk d:2009-08-31T07:00:00.000Z t:crime_type="DEATH DUE TO NATURAL CAUSES" t:incident_report_number=20092430975 m:time=1114
```

## Meta Commands

```ls
metric m:time p:integer l:Time t:dataTypeName=number

entity e:ei2n-fehk l:"APD Incident Extract 2009" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/ei2n-fehk

property e:ei2n-fehk t:meta.view v:id=ei2n-fehk v:category="Public Safety" v:averageRating=0 v:name="APD Incident Extract 2009" v:attribution="City of Austin"

property e:ei2n-fehk t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:ei2n-fehk t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| incident_report_number | crime_type                     | date       | time | location_type | address                         | longitude | latitude | 
| ====================== | ============================== | ========== | ==== | ============= | =============================== | ========= | ======== | 
| 20093460525            | CRASH/LEAVING THE SCENE        | 1260604800 | 538  |               | 1100 BLOCK N PLEASANT VALLEY RD |           |          | 
| 20093560107            | DISTURBANCE - OTHER            | 1261468800 | 104  |               | 5200 BLOCK TAHOE TRL            |           |          | 
| 20092430975            | DEATH DUE TO NATURAL CAUSES    | 1251702000 | 1114 |               | 4600 BLOCK MONTEREY OAKS BLVD   |           |          | 
| 20095049309            | APPLICATION FOR PERMIT OR LIC  | 1251702000 | 1359 |               | 400 BLOCK E 6TH ST              |           |          | 
| 2009622496             | DRIVING WHILE INTOX / FELONY   | 1236067200 | 2348 |               | 100 BLOCK S 1ST ST              |           |          | 
| 20092811661            | CRIMINAL TRESPASS              | 1254985200 | 1738 |               | 800 BLOCK GUADALUPE ST          |           |          | 
| 20093190594            | POSS MARIJUANA                 | 1258272000 | 440  |               | 300 BLOCK E 4TH ST              |           |          | 
| 20093190396            | ASSAULT W/INJURY-FAM/DATE VIOL | 1258272000 | 241  |               | 1800 BLOCK FORT VIEW RD         |           |          | 
| 20093140166            | DWI                            | 1257840000 | 240  |               | 8900 BLOCK BRIARDALE DR         |           |          | 
| 20095056596            | FORGERY AND PASSING            | 1252393200 | 1741 |               | 1200 BLOCK ARMADILLO RD         |           |          | 
```