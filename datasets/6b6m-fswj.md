# Maryland Ozone Exceedance Days in 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2003-88679) |
| Metadata | [Link](https://data.maryland.gov/api/views/6b6m-fswj) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6b6m-fswj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6b6m-fswj/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6b6m-fswj |
| Name | Maryland Ozone Exceedance Days in 2003 |
| Category | Energy and Environment |
| Tags | ozone, air quality, mde |
| Created | 2012-10-04T19:17:23Z |
| Publication Date | 2012-10-04T19:32:32Z |

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Finalized Data.  In 2008 EPA set the ozone standard to 75 ppb.  High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects.  You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/.  This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded.  More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | date                 | Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | aldino               | Aldino               | number        | number        |
| Yes      | numeric metric | davidsonville        | Davidsonville        | number        | number        |
| Yes      | numeric metric | edgewood             | Edgewood             | number        | number        |
| Yes      | numeric metric | essex                | Essex                | number        | number        |
| Yes      | numeric metric | fairhill             | Fairhill             | number        | number        |
| Yes      | numeric metric | frederick_airport    | Frederick Airport    | number        | number        |
| Yes      | numeric metric | ft_meade             | Ft Meade             | number        | number        |
| Yes      | numeric metric | greenbelt            | Greenbelt            | number        | number        |
| Yes      | numeric metric | hagerstown           | Hagerstown           | number        | number        |
| Yes      | numeric metric | millington           | Millington           | number        | number        |
| Yes      | numeric metric | padonia              | Padonia              | number        | number        |
| Yes      | numeric metric | pg_equestrian_center | PG Equestrian Center | number        | number        |
| Yes      | numeric metric | rockville            | Rockville            | number        | number        |
| Yes      | numeric metric | south_carroll        | South Carroll        | number        | number        |
| Yes      | numeric metric | southern_maryland    | Southern Maryland    | number        | number        |
| Yes      | numeric metric | state_wide_max       | State-wide Max       | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6b6m-fswj d:2003-04-15T00:00:00.000Z m:davidsonville=76 m:hagerstown=78 m:south_carroll=81 m:state_wide_max=81 m:pg_equestrian_center=76

series e:6b6m-fswj d:2003-04-16T00:00:00.000Z m:greenbelt=77 m:edgewood=78 m:southern_maryland=85 m:davidsonville=87 m:fairhill=77 m:frederick_airport=76 m:hagerstown=77 m:millington=80 m:south_carroll=83 m:aldino=81 m:state_wide_max=87 m:ft_meade=80 m:pg_equestrian_center=79

series e:6b6m-fswj d:2003-04-28T00:00:00.000Z m:rockville=76 m:state_wide_max=76
```

## Meta Commands

```ls
metric m:aldino p:integer l:Aldino t:dataTypeName=number

metric m:davidsonville p:integer l:Davidsonville t:dataTypeName=number

metric m:edgewood p:integer l:Edgewood t:dataTypeName=number

metric m:essex p:integer l:Essex t:dataTypeName=number

metric m:fairhill p:integer l:Fairhill t:dataTypeName=number

metric m:frederick_airport p:integer l:"Frederick Airport" t:dataTypeName=number

metric m:ft_meade p:integer l:"Ft Meade" t:dataTypeName=number

metric m:greenbelt p:integer l:Greenbelt t:dataTypeName=number

metric m:hagerstown p:integer l:Hagerstown t:dataTypeName=number

metric m:millington p:integer l:Millington t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:pg_equestrian_center p:integer l:"PG Equestrian Center" t:dataTypeName=number

metric m:rockville p:integer l:Rockville t:dataTypeName=number

metric m:south_carroll p:integer l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:integer l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" d:"Highest ozone reading that exceeded the standard in Maryland for the day" t:dataTypeName=number

entity e:6b6m-fswj l:"Maryland Ozone Exceedance Days in 2003" t:url=https://data.maryland.gov/api/views/6b6m-fswj

property e:6b6m-fswj t:meta.view v:id=6b6m-fswj v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2003"

property e:6b6m-fswj t:meta.view.license v:name="Public Domain"

property e:6b6m-fswj t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:6b6m-fswj t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | aldino | davidsonville | edgewood | essex | fairhill | frederick_airport | ft_meade | greenbelt | hagerstown | millington | padonia | pg_equestrian_center | rockville | south_carroll | southern_maryland | state_wide_max | 
| =================== | ====== | ============= | ======== | ===== | ======== | ================= | ======== | ========= | ========== | ========== | ======= | ==================== | ========= | ============= | ================= | ============== | 
| 2003-04-15T00:00:00 |        | 76            |          |       |          |                   |          |           | 78         |            |         | 76                   |           | 81            |                   | 81             | 
| 2003-04-16T00:00:00 | 81     | 87            | 78       |       | 77       | 76                | 80       | 77        | 77         | 80         |         | 79                   |           | 83            | 85                | 87             | 
| 2003-04-28T00:00:00 |        |               |          |       |          |                   |          |           |            |            |         |                      | 76        |               |                   | 76             | 
| 2003-06-11T00:00:00 |        |               | 85       |       | 88       |                   |          |           |            | 77         |         |                      |           |               |                   | 88             | 
| 2003-06-23T00:00:00 |        |               |          |       |          |                   |          |           |            |            |         |                      |           |               | 79                | 79             | 
| 2003-06-24T00:00:00 | 85     | 96            | 85       | 79    | 89       | 90                | 96       | 89        | 85         | 81         | 80      | 97                   | 94        | 77            | 106               | 106            | 
| 2003-06-25T00:00:00 | 105    | 122           | 113      | 103   | 108      | 110               | 115      | 112       | 101        | 108        | 104     | 124                  | 115       | 98            | 121               | 124            | 
| 2003-06-26T00:00:00 | 112    | 122           | 130      | 109   | 116      | 97                | 117      | 106       | 90         | 109        | 99      | 125                  | 100       | 89            | 108               | 130            | 
| 2003-06-28T00:00:00 |        |               |          |       |          |                   |          |           |            |            | 76      |                      |           |               |                   | 76             | 
| 2003-06-29T00:00:00 | 89     |               | 89       |       | 78       |                   | 79       |           |            |            |         |                      |           |               |                   | 89             | 
```