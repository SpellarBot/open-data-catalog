# Maryland Ozone Exceedance Days in 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2004-d9a10) |
| Metadata | [Link](https://data.maryland.gov/api/views/32zj-iiju) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/32zj-iiju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/32zj-iiju/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 32zj-iiju |
| Name | Maryland Ozone Exceedance Days in 2004 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2012-10-09T21:23:03Z |
| Publication Date | 2012-10-26T17:44:07Z |

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
| Yes      | numeric metric | hagerstown           | Hagerstown           | number        | text          |
| Yes      | numeric metric | millington           | Millington           | number        | number        |
| Yes      | numeric metric | padonia              | Padonia              | number        | number        |
| Yes      | numeric metric | pg_equestrian_center | PG Equestrian Center | number        | number        |
| Yes      | numeric metric | piney_run            | Piney Run            | number        | text          |
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
series e:32zj-iiju d:2004-04-17T00:00:00.000Z m:davidsonville=76 m:state_wide_max=77 m:pg_equestrian_center=77

series e:32zj-iiju d:2004-04-18T00:00:00.000Z m:edgewood=81 m:southern_maryland=76 m:davidsonville=84 m:millington=77 m:aldino=80 m:state_wide_max=84 m:ft_meade=82 m:pg_equestrian_center=80

series e:32zj-iiju d:2004-04-19T00:00:00.000Z m:edgewood=79 m:davidsonville=76 m:aldino=76 m:state_wide_max=79 m:pg_equestrian_center=78
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

metric m:hagerstown p:integer l:Hagerstown t:dataTypeName=number

metric m:millington p:integer l:Millington t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:pg_equestrian_center p:integer l:"PG Equestrian Center" t:dataTypeName=number

metric m:piney_run p:integer l:"Piney Run" t:dataTypeName=number

metric m:rockville p:integer l:Rockville t:dataTypeName=number

metric m:south_carroll p:integer l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:integer l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:32zj-iiju l:"Maryland Ozone Exceedance Days in 2004" t:url=https://data.maryland.gov/api/views/32zj-iiju

property e:32zj-iiju t:meta.view v:id=32zj-iiju v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2004"

property e:32zj-iiju t:meta.view.license v:name="Public Domain"

property e:32zj-iiju t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:32zj-iiju t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | aldino | davidsonville | edgewood | essex | fairhill | frederick_airport | ft_meade | hagerstown | millington | padonia | pg_equestrian_center | piney_run | rockville | south_carroll | southern_maryland | state_wide_max | 
| =================== | ====== | ============= | ======== | ===== | ======== | ================= | ======== | ========== | ========== | ======= | ==================== | ========= | ========= | ============= | ================= | ============== | 
| 2004-04-17T00:00:00 |        | 76            |          |       |          |                   |          |            |            |         | 77                   |           |           |               |                   | 77             | 
| 2004-04-18T00:00:00 | 80     | 84            | 81       |       |          |                   | 82       |            | 77         |         | 80                   |           |           |               | 76                | 84             | 
| 2004-04-19T00:00:00 | 76     | 76            | 79       |       |          |                   |          |            |            |         | 78                   |           |           |               |                   | 79             | 
| 2004-05-10T00:00:00 | 82     |               | 79       |       |          |                   | 79       |            |            |         |                      |           | 80        |               |                   | 82             | 
| 2004-05-11T00:00:00 | 92     | 91            | 97       | 77    | 87       |                   | 90       |            | 84         | 76      | 85                   |           | 78        |               | 97                | 97             | 
| 2004-05-12T00:00:00 | 80     |               | 84       |       | 85       | 77                | 76       |            |            | 85      |                      |           | 77        |               |                   | 85             | 
| 2004-05-15T00:00:00 | 76     |               | 78       |       | 83       |                   |          |            |            |         |                      |           |           |               |                   | 83             | 
| 2004-05-22T00:00:00 |        |               | 81       |       | 78       |                   |          |            | 77         |         |                      |           |           |               |                   | 81             | 
| 2004-05-23T00:00:00 |        |               |          |       |          |                   |          |            | 76         |         |                      |           |           |               |                   | 76             | 
| 2004-05-25T00:00:00 | 80     | 76            | 87       |       |          |                   | 80       |            | 82         |         | 78                   |           |           |               |                   | 87             | 
```