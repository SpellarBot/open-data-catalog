# Seattle Police Department Police Report Incident

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-police-department-police-report-incident-7430a) |
| Metadata | [Link](https://data.seattle.gov/api/views/7ais-f98f) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/7ais-f98f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/7ais-f98f/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 7ais-f98f |
| Name | Seattle Police Department Police Report Incident |
| Attribution | City of Seattle, Department of Information Technology, Seattle Police Department |
| Category | Public Safety |
| Tags | crime, police, police report, census911incidents |
| Created | 2010-07-28T16:55:15Z |
| Publication Date | 2016-05-31T18:15:21Z |

## Description

These incidents are based on initial police reports taken by officers when responding to incidents around the city. The information enters our Records Management System (RMS) and is then transmitted out to data.seattle.gov. This information is published within 6 to 12 hours after the report is filed into the system.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | rms_cdw_id                        | RMS CDW ID                        | text          | text          |
| Yes      | series tag     | general_offense_number            | General Offense Number            | text          | text          |
| Yes      | series tag     | offense_code                      | Offense Code                      | text          | text          |
| Yes      | numeric metric | offense_code_extension            | Offense Code Extension            | number        | text          |
| Yes      | series tag     | offense_type                      | Offense Type                      | text          | text          |
| Yes      | series tag     | summary_offense_code              | Summary Offense Code              | text          | text          |
| Yes      | series tag     | summarized_offense_description    | Summarized Offense Description    | text          | text          |
| Yes      | time           | date_reported                     | Date Reported                     | calendar_date | calendar_date |
| No       |                | occurred_date_or_date_range_start | Occurred Date or Date Range Start | calendar_date | calendar_date |
| No       |                | occurred_date_range_end           | Occurred Date Range End           | calendar_date | calendar_date |
| Yes      | series tag     | hundred_block_location            | Hundred Block Location            | text          | text          |
| Yes      | series tag     | district_sector                   | District/Sector                   | text          | text          |
| Yes      | series tag     | zone_beat                         | Zone/Beat                         | text          | text          |
| Yes      | series tag     | census_tract_2000                 | Census Tract 2000                 | text          | text          |
| No       |                | longitude                         | Longitude                         | number        | number        |
| No       |                | latitude                          | Latitude                          | number        | number        |
| No       |                | month                             | Month                             | number        | number        |
| No       |                | year                              | Year                              | number        | number        |
```

## Time Field

```ls
Value = date_reported
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = occurred_date_or_date_range_start,occurred_date_range_end,longitude,latitude,year,month
```

## Data Commands

```ls
series e:7ais-f98f d:2012-01-24T10:07:00.000Z t:offense_code=2305 t:offense_type=THEFT-CARPROWL t:census_tract_2000=8600.3013 t:hundred_block_location="1XX BLOCK OF BROADWAY" t:summarized_offense_description="CAR PROWL" t:zone_beat=G1 t:general_offense_number=201222240 t:summary_offense_code=2300 t:district_sector=G t:rms_cdw_id=1032235 m:offense_code_extension=0

series e:7ais-f98f d:2012-05-26T20:20:00.000Z t:offense_code=2303 t:offense_type=THEFT-SHOPLIFT t:census_tract_2000=7000.3021 t:hundred_block_location="1XX BLOCK OF MERCER ST" t:summarized_offense_description=SHOPLIFTING t:zone_beat=Q3 t:general_offense_number=2012163025 t:summary_offense_code=2300 t:district_sector=Q t:rms_cdw_id=1032236 m:offense_code_extension=0

series e:7ais-f98f d:2012-06-24T17:29:00.000Z t:offense_code=2399 t:offense_type=THEFT-OTH t:census_tract_2000=7100.2001 t:hundred_block_location="3XX BLOCK OF HARRISON ST" t:summarized_offense_description="OTHER PROPERTY" t:zone_beat=Q3 t:general_offense_number=2012198841 t:summary_offense_code=2300 t:district_sector=Q t:rms_cdw_id=1032237 m:offense_code_extension=3
```

## Meta Commands

```ls
metric m:offense_code_extension p:integer l:"Offense Code Extension" d:Offense_Code_Extension t:dataTypeName=number

entity e:7ais-f98f l:"Seattle Police Department Police Report Incident" t:attribution="City of Seattle, Department of Information Technology, Seattle Police Department" t:url=https://data.seattle.gov/api/views/7ais-f98f

property e:7ais-f98f t:meta.view v:id=7ais-f98f v:category="Public Safety" v:averageRating=0 v:name="Seattle Police Department Police Report Incident" v:attribution="City of Seattle, Department of Information Technology, Seattle Police Department"

property e:7ais-f98f t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7ais-f98f t:meta.view.owner v:id=avyg-ej9j v:screenName=spd2internetData v:displayName=spd2internetData

property e:7ais-f98f t:meta.view.tableauthor v:id=6bay-fiph v:screenName="6506 Baden, Toby" v:roleName=publisher v:displayName="6506 Baden, Toby"
```

## Top Records

```ls
| rms_cdw_id | general_offense_number | offense_code | offense_code_extension | offense_type               | summary_offense_code | summarized_offense_description | date_reported       | occurred_date_or_date_range_start | occurred_date_range_end | hundred_block_location    | district_sector | zone_beat | census_tract_2000 | longitude      | latitude     | month | year | 
| ========== | ====================== | ============ | ====================== | ========================== | ==================== | ============================== | =================== | ================================= | ======================= | ========================= | =============== | ========= | ================= | ============== | ============ | ===== | ==== | 
| 1032235    | 201222240              | 2305         | 0                      | THEFT-CARPROWL             | 2300                 | CAR PROWL                      | 2012-01-24T10:07:00 | 2012-01-23T23:30:00               | 2012-01-24T08:42:00     | 1XX BLOCK OF BROADWAY     | G               | G1        | 8600.3013         | -122.320739746 | 47.602195740 | 1     | 2012 | 
| 1032236    | 2012163025             | 2303         | 0                      | THEFT-SHOPLIFT             | 2300                 | SHOPLIFTING                    | 2012-05-26T20:20:00 | 2012-05-26T20:20:00               |                         | 1XX BLOCK OF MERCER ST    | Q               | Q3        | 7000.3021         | -122.354751587 | 47.624576569 | 5     | 2012 | 
| 1032237    | 2012198841             | 2399         | 3                      | THEFT-OTH                  | 2300                 | OTHER PROPERTY                 | 2012-06-24T17:29:00 | 2012-06-24T15:30:00               |                         | 3XX BLOCK OF HARRISON ST  | Q               | Q3        | 7100.2001         | -122.350852966 | 47.622085571 | 6     | 2012 | 
| 1032238    | 201472111              | 2404         | 8                      | VEH-THEFT-TRUCK            | 2400                 | VEHICLE THEFT                  | 2014-03-08T06:57:00 | 2014-03-07T22:00:00               | 2014-03-08T06:30:00     | CHERRY ST / 2 AV          | K               | K1        | 8100.2036         | -122.333175659 | 47.603015900 | 3     | 2014 | 
| 1032239    | 2014107311             | 2202         | 0                      | BURGLARY-FORCE-RES         | 2200                 | BURGLARY                       | 2014-04-08T15:59:00 | 2014-04-08T10:30:00               | 2014-04-08T15:59:00     | 130XX BLOCK OF 25 AV NE   | L               | L1        | 200.2001          | -122.301887512 | 47.723846436 | 4     | 2014 | 
| 1032240    | 201468254              | 2308         | 0                      | THEFT-BUILDING             | 2300                 | OTHER PROPERTY                 | 2014-03-05T01:31:00 | 2014-03-05T00:20:00               | 2014-03-05T00:44:00     | 22XX BLOCK OF 1 AV        | D               | D1        | 8002.2005         | -122.345863342 | 47.612991333 | 3     | 2014 | 
| 1032241    | 2014123990             | 2404         | 1                      | VEH-THEFT-AUTO             | 2400                 | VEHICLE THEFT                  | 2014-04-23T08:29:00 | 2014-04-22T18:15:00               | 2014-04-23T08:25:00     | 22XX BLOCK OF NW 64 ST    | B               | B1        | 3300.4006         | -122.386161804 | 47.675289154 | 4     | 2014 | 
| 1032242    | 2014125050             | 2404         | 1                      | VEH-THEFT-AUTO             | 2400                 | VEHICLE THEFT                  | 2014-04-24T06:30:00 | 2014-04-24T05:30:00               | 2014-04-24T06:30:00     | 73XX BLOCK OF 16 AV NW    | J               | J2        | 3000.4011         | -122.377853394 | 47.682281494 | 4     | 2014 | 
| 1032243    | 2014120550             | 1203         | 3                      | ROBBERY-BUSINESS-BODYFORCE | 1200                 | ROBBERY                        | 2014-04-19T23:37:00 | 2014-04-19T23:30:00               | 2014-04-19T23:37:00     | 20XX BLOCK OF FAIRVIEW AV | D               | D3        | 7300.2005         | -122.334251404 | 47.618183136 | 4     | 2014 | 
| 1032244    | 2014122739             | 2404         | 1                      | VEH-THEFT-AUTO             | 2400                 | VEHICLE THEFT                  | 2014-04-22T06:12:00 | 2014-04-21T22:30:00               | 2014-04-22T05:45:00     | 22XX BLOCK OF N 106 ST    | N               | N3        | 1200.5011         | -122.331932068 | 47.705928802 | 4     | 2014 | 
```