# APD Incident Extract 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/apd-incident-extract-2010) |
| Metadata | [Link](https://data.austintexas.gov/api/views/4c6h-tv2y) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/4c6h-tv2y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/4c6h-tv2y/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 4c6h-tv2y |
| Name | APD Incident Extract 2010 |
| Attribution | City of Austin |
| Category | Public Safety |
| Created | 2011-12-16T16:33:20Z |
| Publication Date | 2016-08-19T13:59:39Z |

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
series e:4c6h-tv2y d:2010-12-18T08:00:00.000Z t:crime_type="CRASH/LEAVING THE SCENE" t:incident_report_number=20105067300 m:time=1100

series e:4c6h-tv2y d:2010-12-20T08:00:00.000Z t:crime_type="CRIMINAL MISCHIEF" t:incident_report_number=20105067330 m:time=1200

series e:4c6h-tv2y d:2010-12-21T08:00:00.000Z t:crime_type=COUNTERFEITING t:incident_report_number=20105067629 m:time=1650
```

## Meta Commands

```ls
metric m:time p:integer l:Time t:dataTypeName=number

entity e:4c6h-tv2y l:"APD Incident Extract 2010" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/4c6h-tv2y

property e:4c6h-tv2y t:meta.view v:id=4c6h-tv2y v:category="Public Safety" v:averageRating=0 v:name="APD Incident Extract 2010" v:attribution="City of Austin"

property e:4c6h-tv2y t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:4c6h-tv2y t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| incident_report_number | crime_type                  | date       | time | location_type | address                      | longitude    | latitude    | 
| ====================== | =========================== | ========== | ==== | ============= | ============================ | ============ | =========== | 
| 20105067300            | CRASH/LEAVING THE SCENE     | 1292659200 | 1100 |               | 11200 BLOCK LAKELINE MALL DR |              |             | 
| 20105067330            | CRIMINAL MISCHIEF           | 1292832000 | 1200 |               | WEST LYNN ST / W 6TH ST      | -97.76264215 | 30.27482564 | 
| 20105067629            | COUNTERFEITING              | 1292918400 | 1650 |               | 2700 BLOCK GONZALES ST       |              |             | 
| 20101020316            | CRIMINAL MISCHIEF           | 1271055600 | 559  |               | 6200 BLOCK MANOR RD          |              |             | 
| 20105019108            | BURGLARY OF VEHICLE         | 1271314800 | 1200 |               | 4600 BLOCK ELMONT DR         |              |             | 
| 20105068834            | THEFT                       | 1293436800 | 1300 |               | 500 BLOCK S LAMAR BLVD       |              |             | 
| 20102070151            | CUSTODY ARREST TRAFFIC WARR | 1280127600 | 134  |               | 13000 BLOCK POND SPRINGS RD  |              |             | 
| 20101283130            | ASSIST EMS                  | 1273302000 | 2023 |               | 1600 BLOCK WICKERSHAM LN     |              |             | 
| 20102120875            | THEFT OF VEHICLE/OTHER      | 1280559600 | 924  |               | 1700 BLOCK NELMS DR          |              |             | 
| 2010331353             | FAMILY DISTURBANCE          | 1265097600 | 1738 |               | 1700 BLOCK E OLTORF ST       |              |             | 
```