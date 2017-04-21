# APD Incident Extract 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/apd-incident-extract-2011) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gr59-ids7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gr59-ids7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gr59-ids7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gr59-ids7 |
| Name | APD Incident Extract 2011 |
| Attribution | City of Austin |
| Category | Public Safety |
| Created | 2012-04-30T14:43:59Z |
| Publication Date | 2016-08-19T13:48:07Z |

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
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | incident_report_number | Incident Report Number | text          | number        |
| Yes      | series tag     | crime_type             | Crime Type             | text          | text          |
| Yes      | time           | date                   | Date                   | calendar_date | calendar_date |
| Yes      | numeric metric | time                   | Time                   | number        | number        |
| Yes      | series tag     | location_type          | LOCATION_TYPE          | text          | text          |
| No       |                | address                | ADDRESS                | text          | text          |
| No       |                | longitude              | LONGITUDE              | number        | number        |
| No       |                | latitude               | LATITUDE               | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:gr59-ids7 d:2011-03-30T00:00:00.000Z t:crime_type="THEFT OF BICYCLE" t:incident_report_number=20115016237 m:time=800

series e:gr59-ids7 d:2011-03-16T00:00:00.000Z t:crime_type="TEMP EX PARTE  ORDER" t:incident_report_number=20115013617 m:time=2333

series e:gr59-ids7 d:2011-09-30T00:00:00.000Z t:crime_type="DISTURBANCE - OTHER" t:incident_report_number=20112731103 m:time=1350
```

## Meta Commands

```ls
metric m:time p:integer l:Time t:dataTypeName=number

entity e:gr59-ids7 l:"APD Incident Extract 2011" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/gr59-ids7

property e:gr59-ids7 t:meta.view v:id=gr59-ids7 v:category="Public Safety" v:averageRating=0 v:name="APD Incident Extract 2011" v:attribution="City of Austin"

property e:gr59-ids7 t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:gr59-ids7 t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| incident_report_number | crime_type                  | date                | time | location_type | address                         | longitude    | latitude    | 
| ====================== | =========================== | =================== | ==== | ============= | =============================== | ============ | =========== | 
| 20115016237            | THEFT OF BICYCLE            | 2011-03-30T00:00:00 | 800  |               | 2300 BLOCK WICKERSHAM LN        |              |             | 
| 20115013617            | TEMP EX PARTE ORDER         | 2011-03-16T00:00:00 | 2333 |               | 2300 BLOCK BERKELEY AVE         |              |             | 
| 20112731103            | DISTURBANCE - OTHER         | 2011-09-30T00:00:00 | 1350 |               | 3100 BLOCK STARDUST DR          |              |             | 
| 20112760367            | CUSTODY ARREST TRAFFIC WARR | 2011-10-03T00:00:00 | 814  |               | LOS CIELOS BLVD / SKY HARBOR DR | -97.62526349 | 30.16727189 | 
| 20115059974            | THEFT                       | 2011-11-23T00:00:00 | 1800 |               | 7300 BLOCK FM 2222 RD           |              |             | 
| 2011221121             | BURGLARY OF RESIDENCE       | 2011-01-22T00:00:00 | 1132 |               | 2400 BLOCK LOYOLA LN            |              |             | 
| 20115059727            | THEFT                       | 2011-12-17T00:00:00 | 0    |               | 2700 BLOCK E 7TH ST             |              |             | 
| 20115013368            | THEFT                       | 2011-03-15T00:00:00 | 1245 |               | 3000 BLOCK NORTHLAND DR         |              |             | 
| 20112410564            | FAILURE TO IDENTIFY         | 2011-08-29T00:00:00 | 850  |               | 2100 BLOCK W PARMER LN          |              |             | 
| 20112400155            | PUBLIC INTOXICATION         | 2011-08-28T00:00:00 | 108  |               | 1900 BLOCK E CESAR CHAVEZ ST    |              |             | 
```