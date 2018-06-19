# Police Department Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfpd-incidents-from-1-january-2014) |
| Metadata | [Link](https://data.sfgov.org/api/views/tmnf-yvry) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tmnf-yvry/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tmnf-yvry/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tmnf-yvry |
| Name | Police Department Incidents |
| Attribution | City and County of San Francisco |
| Category | Public Safety |
| Tags | sfpd, crime, police department |
| Created | 2012-02-24T20:55:13Z |
| Publication Date | 2017-03-14T00:39:57Z |

## Description

***As of July 19, 2015, the PD District boundaries have been updated through a redistricting process. These new boundaries are not reflected in the dataset yet so you cannot compare data from July 19, 2015 onward to official reports from PD with the Police District column. We are working on an update to the dataset to reflect the updated boundaries starting with data entered July 19 onward.***

Incidents derived from SFPD Crime Incident Reporting system  Updated daily, showing data from 1/1/2003 up until two weeks ago from current date. Please note: San Francisco police have implemented a new system for tracking crime. The dataset included here is still coming from the old system, which is in the process of being retired (a multi-year process).  Data included here is no longer the official SFPD data. We will migrate to the new system for DataSF in the upcoming months.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | series tag  | incidntnum | IncidntNum | text          | text          |
| Yes      | series tag  | category   | Category   | text          | text          |
| Yes      | series tag  | descript   | Descript   | text          | text          |
| No       |             | dayofweek  | DayOfWeek  | text          | text          |
| Yes      | time        | date       | Date       | calendar_date | calendar_date |
| Yes      | series tag  | time       | Time       | text          | text          |
| Yes      | series tag  | pddistrict | PdDistrict | text          | text          |
| Yes      | series tag  | resolution | Resolution | text          | text          |
| No       |             | address    | Address    | text          | text          |
| No       |             | x          | X          | number        | number        |
| No       |             | y          | Y          | number        | number        |
| Yes      | series tag  | pdid       | PdId       | text          | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dayofweek,address,x,y
```

## Data Commands

```ls
series e:tmnf-yvry d:2015-01-19T00:00:00.000Z t:category=NON-CRIMINAL t:time=14:00 t:pddistrict=MISSION t:pdid=15006027571000 t:descript="LOST PROPERTY" t:resolution=NONE t:incidntnum=150060275 m:row_number.tmnf-yvry=1

series e:tmnf-yvry d:2015-02-01T00:00:00.000Z t:category=ROBBERY t:time=15:45 t:pddistrict=TENDERLOIN t:pdid=15009821003074 t:descript="ROBBERY, BODILY FORCE" t:resolution=NONE t:incidntnum=150098210 m:row_number.tmnf-yvry=2

series e:tmnf-yvry d:2015-02-01T00:00:00.000Z t:category=ASSAULT t:time=15:45 t:pddistrict=TENDERLOIN t:pdid=15009821004014 t:descript="AGGRAVATED ASSAULT WITH BODILY FORCE" t:resolution=NONE t:incidntnum=150098210 m:row_number.tmnf-yvry=3
```

## Meta Commands

```ls
metric m:row_number.tmnf-yvry p:long l:"Row Number"

entity e:tmnf-yvry l:"Police Department Incidents" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/tmnf-yvry

property e:tmnf-yvry t:meta.view v:id=tmnf-yvry v:category="Public Safety" v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Police Department Incidents" v:attribution="City and County of San Francisco"

property e:tmnf-yvry t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tmnf-yvry t:meta.view.owner v:id=3i4b-bknh v:profileImageUrlMedium=/api/users/3i4b-bknh/profile_images/THUMB v:profileImageUrlLarge=/api/users/3i4b-bknh/profile_images/LARGE v:screenName="Jeff Johnson" v:profileImageUrlSmall=/api/users/3i4b-bknh/profile_images/TINY v:displayName="Jeff Johnson"

property e:tmnf-yvry t:meta.view.tableauthor v:id=3i4b-bknh v:profileImageUrlMedium=/api/users/3i4b-bknh/profile_images/THUMB v:profileImageUrlLarge=/api/users/3i4b-bknh/profile_images/LARGE v:screenName="Jeff Johnson" v:profileImageUrlSmall=/api/users/3i4b-bknh/profile_images/TINY v:roleName=administrator v:displayName="Jeff Johnson"
```

## Top Records

```ls
| incidntnum | category        | descript                                  | dayofweek | date                | time  | pddistrict | resolution | address                     | x                 | y                | pdid           | 
| ========== | =============== | ========================================= | ========= | =================== | ===== | ========== | ========== | =========================== | ================= | ================ | ============== | 
| 150060275  | NON-CRIMINAL    | LOST PROPERTY                             | Monday    | 2015-01-19T00:00:00 | 14:00 | MISSION    | NONE       | 18TH ST / VALENCIA ST       | -122.42158168137  | 37.7617007179518 | 15006027571000 | 
| 150098210  | ROBBERY         | ROBBERY, BODILY FORCE                     | Sunday    | 2015-02-01T00:00:00 | 15:45 | TENDERLOIN | NONE       | 300 Block of LEAVENWORTH ST | -122.414406029855 | 37.7841907151119 | 15009821003074 | 
| 150098210  | ASSAULT         | AGGRAVATED ASSAULT WITH BODILY FORCE      | Sunday    | 2015-02-01T00:00:00 | 15:45 | TENDERLOIN | NONE       | 300 Block of LEAVENWORTH ST | -122.414406029855 | 37.7841907151119 | 15009821004014 | 
| 150098210  | SECONDARY CODES | DOMESTIC VIOLENCE                         | Sunday    | 2015-02-01T00:00:00 | 15:45 | TENDERLOIN | NONE       | 300 Block of LEAVENWORTH ST | -122.414406029855 | 37.7841907151119 | 15009821015200 | 
| 150098226  | VANDALISM       | MALICIOUS MISCHIEF, VANDALISM OF VEHICLES | Tuesday   | 2015-01-27T00:00:00 | 19:00 | NORTHERN   | NONE       | LOMBARD ST / LAGUNA ST      | -122.431118543788 | 37.8004687042875 | 15009822628160 | 
| 150098232  | NON-CRIMINAL    | AIDED CASE -PROPERTY FOR DESTRUCTION      | Sunday    | 2015-02-01T00:00:00 | 16:21 | RICHMOND   | NONE       | 400 Block of LOCUST ST      | -122.451781767894 | 37.7870853907529 | 15009823251041 | 
| 150098248  | SECONDARY CODES | DOMESTIC VIOLENCE                         | Saturday  | 2015-01-31T00:00:00 | 21:00 | BAYVIEW    | NONE       | 700 Block of KIRKWOOD AV    | -122.374019331833 | 37.729203356539  | 15009824815200 | 
| 150098248  | VANDALISM       | MALICIOUS MISCHIEF, VANDALISM             | Saturday  | 2015-01-31T00:00:00 | 21:00 | BAYVIEW    | NONE       | 700 Block of KIRKWOOD AV    | -122.374019331833 | 37.729203356539  | 15009824828150 | 
| 150098254  | BURGLARY        | BURGLARY OF STORE, UNLAWFUL ENTRY         | Saturday  | 2015-01-31T00:00:00 | 16:09 | CENTRAL    | NONE       | 200 Block of STOCKTON ST    | -122.40656817787  | 37.7878092959561 | 15009825405053 | 
| 150098260  | LARCENY/THEFT   | PETTY THEFT SHOPLIFTING                   | Saturday  | 2015-01-31T00:00:00 | 17:00 | CENTRAL    | NONE       | 800 Block of GEARY ST       | -122.417295322526 | 37.7862578545865 | 15009826006362 | 
```