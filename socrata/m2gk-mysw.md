# Seattle Police Department Police Report Offense

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-police-department-police-report-offense-d2ec7) |
| Metadata | [Link](https://data.seattle.gov/api/views/m2gk-mysw) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/m2gk-mysw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/m2gk-mysw/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | m2gk-mysw |
| Name | Seattle Police Department Police Report Offense |
| Attribution | City of Seattle, Department of Information Technology, Seattle Police Department |
| Category | Public Safety |
| Tags | crime, police, police report |
| Created | 2010-07-28T18:11:17Z |
| Publication Date | 2016-03-04T17:10:36Z |

## Description

These offenses correspond to the Police Report Incidents http://data.seattle.gov/dataset/Seattle-Police-Department-Police-Report-Incident/7ais-f98f

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | cdw_offense_id         | CDW Offense ID         | text      | text        |
| Yes      | series tag  | cdw_incident_id        | CDW Incident ID        | text      | text        |
| Yes      | series tag  | offense_code           | Offense Code           | text      | text        |
| Yes      | series tag  | offense_code_extension | Offense Code Extension | text      | text        |
| Yes      | series tag  | crime_type             | Crime Type             | text      | text        |
| Yes      | series tag  | summary_offense_code   | Summary Offense Code   | text      | text        |
| Yes      | series tag  | summary_crime_type     | Summary Crime Type     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m2gk-mysw d:2016-08-28T20:58:25.000Z t:offense_code=5499 t:crime_type=TRAFFIC t:cdw_offense_id=70 t:summary_crime_type=TRAFFIC t:summary_offense_code=5400 t:offense_code_extension=0 t:cdw_incident_id=55 m:row_number.m2gk-mysw=1

series e:m2gk-mysw d:2016-08-28T20:58:25.000Z t:offense_code=1313 t:crime_type=ASSLT-NONAGG t:cdw_offense_id=71 t:summary_crime_type=ASSAULT t:summary_offense_code=1300 t:offense_code_extension=0 t:cdw_incident_id=56 m:row_number.m2gk-mysw=2

series e:m2gk-mysw d:2016-08-28T20:58:25.000Z t:offense_code=2305 t:crime_type=THEFT-CARPROWL t:cdw_offense_id=72 t:summary_crime_type="CAR PROWL" t:summary_offense_code=2300 t:offense_code_extension=0 t:cdw_incident_id=57 m:row_number.m2gk-mysw=3
```

## Meta Commands

```ls
metric m:row_number.m2gk-mysw p:long l:"Row Number"

entity e:m2gk-mysw l:"Seattle Police Department Police Report Offense" t:attribution="City of Seattle, Department of Information Technology, Seattle Police Department" t:url=https://data.seattle.gov/api/views/m2gk-mysw

property e:m2gk-mysw t:meta.view v:id=m2gk-mysw v:category="Public Safety" v:averageRating=0 v:name="Seattle Police Department Police Report Offense" v:attribution="City of Seattle, Department of Information Technology, Seattle Police Department"

property e:m2gk-mysw t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:m2gk-mysw t:meta.view.owner v:id=avyg-ej9j v:screenName=spd2internetData v:displayName=spd2internetData

property e:m2gk-mysw t:meta.view.tableauthor v:id=avyg-ej9j v:screenName=spd2internetData v:roleName=publisher v:displayName=spd2internetData
```

## Top Records

```ls
| :updated_at | cdw_offense_id | cdw_incident_id | offense_code | offense_code_extension | crime_type                     | summary_offense_code | summary_crime_type | 
| =========== | ============== | =============== | ============ | ====================== | ============================== | ==================== | ================== | 
| 1472417905  | 70             | 55              | 5499         | 0                      | TRAFFIC                        | 5400                 | TRAFFIC            | 
| 1472417905  | 71             | 56              | 1313         | 0                      | ASSLT-NONAGG                   | 1300                 | ASSAULT            | 
| 1472417905  | 72             | 57              | 2305         | 0                      | THEFT-CARPROWL                 | 2300                 | CAR PROWL          | 
| 1472417905  | 73             | 58              | 2902         | 0                      | PROPERTY DAMAGE-RESIDENTIAL    | 2900                 | PROPERTY DAMAGE    | 
| 1472417905  | 74             | 59              | X            | 65                     | NARC-FOUND-COCAINE             | X                    | NARCOTICS          | 
| 1472417907  | 212            | 188             | X            | 94                     | ENDANGER                       | X                    | ASSAULT            | 
| 1464720772  | 99613          | 91961           | 2399         | 3                      | THEFT-OTH                      | 2300                 | OTHER PROPERTY     | 
| 1472417924  | 1010           | 929             | X            | 48                     | PROPERTY LOST                  | X                    | LOST PROPERTY      | 
| 1472417924  | 1011           | 930             | 2305         | 0                      | THEFT-CARPROWL                 | 2300                 | CAR PROWL          | 
| 1472417924  | 1012           | 931             | 2299         | 1                      | BURGLARY-SECURE PARKING-NONRES | 2200                 | BURGLARY           | 
```