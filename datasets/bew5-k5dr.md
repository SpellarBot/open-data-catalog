# Crash Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crash-data) |
| Metadata | [Link](https://data.iowa.gov/api/views/bew5-k5dr) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/bew5-k5dr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/bew5-k5dr/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | bew5-k5dr |
| Name | Crash Data |
| Attribution | Iowa Department of Transportation - Office of Traffic & Safety |
| Category | Transportation & Utilities |
| Tags | crash, accident, safety, iowa dot, iowa department of transportation |
| Created | 2016-07-12T18:12:21Z |
| Publication Date | 2016-07-12T18:17:27Z |

## Description

Point features depicting last 10 years of crash data and data that is related to general crash information. Contains crash-wide data for each crash such as date, time, weather conditions, severity and other information. 

Data compiled in this format for the Traffic Safety Data and Analysis website (www.iowadot.gov/tsda)

Data is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | numeric metric | crash_key     | CRASH_KEY     | number    | number      |
| Yes      | series tag     | casenumber    | CASENUMBER    | text      | number      |
| Yes      | series tag     | lecasenum     | LECASENUM     | text      | text        |
| Yes      | time           | crash_date    | CRASH_DATE    | date      | date        |
| Yes      | numeric metric | crash_month   | CRASH_MONTH   | number    | number      |
| Yes      | numeric metric | crash_day     | CRASH_DAY     | number    | number      |
| Yes      | series tag     | timestr       | TIMESTR       | text      | text        |
| Yes      | series tag     | district      | DISTRICT      | text      | number      |
| Yes      | series tag     | county_number | COUNTY_NUMBER | text      | number      |
| Yes      | numeric metric | cityname      | CITYNAME      | number    | number      |
| Yes      | series tag     | systemstr     | SYSTEMSTR     | text      | text        |
| Yes      | series tag     | literal       | LITERAL       | text      | text        |
| Yes      | numeric metric | frstharm      | FRSTHARM      | number    | number      |
| Yes      | numeric metric | locfsthrm     | LOCFSTHRM     | number    | number      |
| Yes      | numeric metric | crcomnnr      | CRCOMNNR      | number    | number      |
| Yes      | numeric metric | majcse        | MAJCSE        | number    | number      |
| Yes      | numeric metric | drugalc       | DRUGALC       | number    | number      |
| Yes      | numeric metric | ecntcrc       | ECNTCRC       | number    | number      |
| Yes      | numeric metric | light         | LIGHT         | number    | number      |
| Yes      | numeric metric | csrfcnd       | CSRFCND       | number    | number      |
| Yes      | numeric metric | weather       | WEATHER       | number    | number      |
| Yes      | numeric metric | rcntcrc       | RCNTCRC       | number    | number      |
| Yes      | numeric metric | rdtyp         | RDTYP         | number    | number      |
| Yes      | numeric metric | paved         | PAVED         | number    | number      |
| Yes      | numeric metric | wzrelated     | WZRELATED     | number    | number      |
| Yes      | numeric metric | csev          | CSEV          | number    | number      |
| Yes      | numeric metric | fatalities    | FATALITIES    | number    | number      |
| Yes      | numeric metric | injuries      | INJURIES      | number    | number      |
| Yes      | numeric metric | majinjury     | MAJINJURY     | number    | number      |
| Yes      | numeric metric | mininjury     | MININJURY     | number    | number      |
| Yes      | numeric metric | possinjury    | POSSINJURY    | number    | number      |
| Yes      | numeric metric | unkinjury     | UNKINJURY     | number    | number      |
| Yes      | numeric metric | propdmg       | PROPDMG       | number    | number      |
| Yes      | numeric metric | vehicles      | VEHICLES      | number    | number      |
| Yes      | numeric metric | toccupants    | TOCCUPANTS    | number    | number      |
| Yes      | numeric metric | report        | REPORT        | number    | number      |
| No       |                | xcoord        | XCOORD        | number    | number      |
| No       |                | ycoord        | YCOORD        | number    | number      |
| Yes      | series tag     | objectid      | OBJECTID      | text      | number      |
```

## Time Field

```ls
Value = crash_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = xcoord,ycoord
```

## Data Commands

```ls
series e:bew5-k5dr d:2016-01-02T00:00:00.000Z t:casenumber=2016899114 t:county_number=77 t:lecasenum=20160000119 t:timestr=08:40 t:objectid=1 t:district=1 t:literal="INDIANOLA AVE" m:frstharm=33 m:majinjury=0 m:csev=4 m:drugalc=8 m:csrfcnd=3 m:locfsthrm=1 m:fatalities=0 m:report=7 m:weather=1 m:vehicles=2 m:crash_key=2016899114 m:light=1 m:majcse=20 m:rcntcrc=1 m:paved=1 m:possinjury=1 m:crash_month=1 m:propdmg=6000 m:ecntcrc=1 m:crash_day=7 m:injuries=1 m:mininjury=0 m:rdtyp=1 m:cityname=1945 m:crcomnnr=3 m:unkinjury=0 m:toccupants=2

series e:bew5-k5dr d:2016-01-02T00:00:00.000Z t:casenumber=2016899118 t:county_number=57 t:lecasenum=201600088 t:timestr=16:37 t:objectid=2 t:district=6 t:literal="A AVE NE & 7TH ST NE" m:frstharm=33 m:majinjury=0 m:csev=4 m:drugalc=8 m:csrfcnd=1 m:locfsthrm=1 m:fatalities=0 m:report=7 m:weather=1 m:vehicles=3 m:crash_key=2016899118 m:light=1 m:majcse=2 m:rcntcrc=1 m:paved=1 m:possinjury=1 m:crash_month=1 m:propdmg=22000 m:ecntcrc=1 m:crash_day=7 m:injuries=1 m:mininjury=0 m:rdtyp=12 m:cityname=1187 m:crcomnnr=5 m:unkinjury=0 m:toccupants=5

series e:bew5-k5dr d:2016-01-02T00:00:00.000Z t:casenumber=2016899126 t:county_number=77 t:lecasenum=16-0024 t:timestr=16:35 t:objectid=3 t:district=1 t:literal="31ST ST" m:frstharm=33 m:majinjury=0 m:csev=5 m:drugalc=8 m:csrfcnd=1 m:locfsthrm=1 m:fatalities=0 m:report=7 m:weather=1 m:vehicles=4 m:crash_key=2016899126 m:light=1 m:majcse=24 m:rcntcrc=1 m:paved=1 m:possinjury=0 m:crash_month=1 m:propdmg=9000 m:ecntcrc=1 m:crash_day=7 m:injuries=0 m:mininjury=0 m:rdtyp=1 m:cityname=8260 m:crcomnnr=3 m:unkinjury=0 m:toccupants=7
```

## Meta Commands

```ls
metric m:crash_key p:integer l:CRASH_KEY d:"Crash Key" t:dataTypeName=number

metric m:crash_month p:integer l:CRASH_MONTH d:"Month of Crash" t:dataTypeName=number

metric m:crash_day p:integer l:CRASH_DAY d:"Day of Week" t:dataTypeName=number

metric m:cityname p:integer l:CITYNAME d:City t:dataTypeName=number

metric m:frstharm p:integer l:FRSTHARM d:"First Harmful Event" t:dataTypeName=number

metric m:locfsthrm p:integer l:LOCFSTHRM d:"Location of First Harmful Event" t:dataTypeName=number

metric m:crcomnnr p:integer l:CRCOMNNR d:"Manner of Crash/Collision" t:dataTypeName=number

metric m:majcse p:integer l:MAJCSE d:"Major Cause" t:dataTypeName=number

metric m:drugalc p:integer l:DRUGALC d:"Drug or Alcohol Related" t:dataTypeName=number

metric m:ecntcrc p:long l:ECNTCRC d:"Contributing Circumstances - Environment" t:dataTypeName=number

metric m:light p:integer l:LIGHT d:"Light Conditions" t:dataTypeName=number

metric m:csrfcnd p:integer l:CSRFCND d:"Surface Conditions" t:dataTypeName=number

metric m:weather p:integer l:WEATHER d:"Weather Conditions" t:dataTypeName=number

metric m:rcntcrc p:integer l:RCNTCRC d:"Contributing Circumstances - Roadway" t:dataTypeName=number

metric m:rdtyp p:integer l:RDTYP d:"Type of Roadway Junction / Feature" t:dataTypeName=number

metric m:paved p:integer l:PAVED d:"Paved or Not" t:dataTypeName=number

metric m:wzrelated p:integer l:WZRELATED d:"Work Zone Related?" t:dataTypeName=number

metric m:csev p:integer l:CSEV d:"Crash Severity" t:dataTypeName=number

metric m:fatalities p:integer l:FATALITIES d:"Number of Fatalities" t:dataTypeName=number

metric m:injuries p:integer l:INJURIES d:"Number of Injuries" t:dataTypeName=number

metric m:majinjury p:integer l:MAJINJURY d:"Number of Major Injuries" t:dataTypeName=number

metric m:mininjury p:integer l:MININJURY d:"Number of Minor Injuries" t:dataTypeName=number

metric m:possinjury p:integer l:POSSINJURY d:"Number of Possible Injuries" t:dataTypeName=number

metric m:unkinjury p:integer l:UNKINJURY d:"Number of Unknown Injuries" t:dataTypeName=number

metric m:propdmg p:integer l:PROPDMG d:"Amount of Property Damage ($)" t:dataTypeName=number

metric m:vehicles p:integer l:VEHICLES d:"Number of Vehicles Involved" t:dataTypeName=number

metric m:toccupants p:integer l:TOCCUPANTS d:"Total Number of Occupants" t:dataTypeName=number

metric m:report p:integer l:REPORT d:"Report Type" t:dataTypeName=number

entity e:bew5-k5dr l:"Crash Data" t:attribution="Iowa Department of Transportation - Office of Traffic & Safety" t:url=https://data.iowa.gov/api/views/bew5-k5dr

property e:bew5-k5dr t:meta.view v:id=bew5-k5dr v:category="Transportation & Utilities" v:averageRating=0 v:name="Crash Data" v:attribution="Iowa Department of Transportation - Office of Traffic & Safety"

property e:bew5-k5dr t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:bew5-k5dr t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| crash_key  | casenumber | lecasenum   | crash_date | crash_month | crash_day | timestr | district | county_number | cityname | systemstr | literal                               | frstharm | locfsthrm | crcomnnr | majcse | drugalc | ecntcrc | light | csrfcnd | weather | rcntcrc | rdtyp | paved | wzrelated | csev | fatalities | injuries | majinjury | mininjury | possinjury | unkinjury | propdmg | vehicles | toccupants | report | xcoord | ycoord  | objectid | 
| ========== | ========== | =========== | ========== | =========== | ========= | ======= | ======== | ============= | ======== | ========= | ===================================== | ======== | ========= | ======== | ====== | ======= | ======= | ===== | ======= | ======= | ======= | ===== | ===== | ========= | ==== | ========== | ======== | ========= | ========= | ========== | ========= | ======= | ======== | ========== | ====== | ====== | ======= | ======== | 
| 2016899114 | 2016899114 | 20160000119 | 1451692800 | 1           | 7         | 08:40   | 1        | 77            | 1945     |           | INDIANOLA AVE                         | 33       | 1         | 3        | 20     | 8       | 1       | 1     | 3       | 1       | 1       | 1     | 1     |           | 4    | 0          | 1        | 0         | 0         | 1          | 0         | 6000    | 2        | 2          | 7      | 449393 | 4601206 | 1        | 
| 2016899118 | 2016899118 | 201600088   | 1451692800 | 1           | 7         | 16:37   | 6        | 57            | 1187     |           | A AVE NE & 7TH ST NE                  | 33       | 1         | 5        | 2      | 8       | 1       | 1     | 1       | 1       | 1       | 12    | 1     |           | 4    | 0          | 1        | 0         | 0         | 1          | 0         | 22000   | 3        | 5          | 7      | 610668 | 4648720 | 2        | 
| 2016899126 | 2016899126 | 16-0024     | 1451692800 | 1           | 7         | 16:35   | 1        | 77            | 8260     |           | 31ST ST                               | 33       | 1         | 3        | 24     | 8       | 1       | 1     | 1       | 1       | 1       | 1     | 1     |           | 5    | 0          | 0        | 0         | 0         | 0          | 0         | 9000    | 4        | 7          | 7      | 437737 | 4605578 | 3        | 
| 2016899130 | 2016899130 | 20160000142 | 1451692800 | 1           | 7         | 15:20   | 1        | 77            | 1945     |           | E PAYTON AVE                          | 35       | 1         | 3        | 71     | 8       | 99      | 1     | 3       | 1       | 99      | 1     | 1     |           | 5    | 0          | 0        | 0         | 0         | 0          | 0         | 1500    | 2        | 1          | 7      | 449059 | 4597779 | 4        | 
| 2016899131 | 2016899131 | 20160000148 | 1451692800 | 1           | 7         | 16:08   | 1        | 77            | 1945     |           | SE 5TH ST & E MCKINLEY AVE            | 33       | 1         | 4        | 44     | 8       | 1       | 1     | 1       | 1       | 1       | 12    | 1     |           | 4    | 0          | 1        | 0         | 0         | 1          | 0         | 4000    | 2        | 7          | 7      | 449410 | 4598982 | 5        | 
| 2016899133 | 2016899133 | 20160000157 | 1451692800 | 1           | 7         | 18:15   | 1        | 77            | 1945     |           | E GRAND AVE & HUBBELL AVE & E 18TH ST | 33       | 1         | 2        | 9      | 8       | 1       | 4     | 1       | 1       | 1       | 12    | 1     |           | 5    | 0          | 0        | 0         | 0         | 0          | 0         | 3000    | 2        | 3          | 7      | 451068 | 4605049 | 6        | 
| 2016899138 | 2016899138 | 16-0018     | 1451692800 | 1           | 7         | 18:15   | 1        | 94            | 2690     |           | 1ST AVE N & N 12TH ST                 | 33       | 1         | 4        | 9      | 6       | 1       | 4     | 1       | 2       | 1       | 13    | 1     |           | 5    | 0          | 0        | 0         | 0         | 0          | 0         | 10000   | 3        | 4          | 7      | 402827 | 4706718 | 7        | 
| 2016899143 | 2016899143 | 16-00074    | 1451692800 | 1           | 7         | 14:07   | 6        | 82            | 0        | I-80      | I-80                                  | 33       | 1         | 6        | 99     | 8       | 1       | 1     | 1       | 1       | 1       | 1     | 1     |           | 5    | 0          | 0        | 0         | 0         | 0          | 0         | 1501    | 2        | 2          | 7      | 679902 | 4611284 | 8        | 
| 2016899152 | 2016899152 | 20160000186 | 1451779200 | 1           | 1         | 01:59   | 1        | 77            | 1945     |           | SW 2ND ST                             | 32       | 1         | 1        | 70     | 3       | 1       | 4     | 1       | 1       | 1       | 1     | 1     |           | 4    | 0          | 1        | 0         | 0         | 1          | 0         | 1000    | 1        | 1          | 7      | 448452 | 4603715 | 9        | 
| 2016899163 | 2016899163 | S16-000013  | 1451692800 | 1           | 7         | 01:08   | 4        | 78            | 0        | I-80      | I-80                                  | 55       | 2         | 1        | 42     | 3       | 1       | 5     | 1       | 1       | 1       | 20    | 1     |           | 5    | 0          | 0        | 0         | 0         | 0          | 0         | 10000   | 1        | 4          | 7      | 319022 | 4596319 | 10       | 
```