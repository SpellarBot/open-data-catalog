# Maryland Ozone Exceedance Days in 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2008-93a0f) |
| Metadata | [Link](https://data.maryland.gov/api/views/qgct-y4xa) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qgct-y4xa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qgct-y4xa/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qgct-y4xa |
| Name | Maryland Ozone Exceedance Days in 2008 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2012-10-26T17:54:16Z |
| Publication Date | 2012-10-26T18:00:59Z |

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Finalized Data.  In 2008 EPA set the ozone standard to 75 ppb.  High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects.  You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/.  This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded.  More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================= | ============= | ============= |
| Yes      | time           | date                         | Date                          | calendar_date | calendar_date |
| Yes      | numeric metric | aldino                       | Aldino                        | number        | number        |
| Yes      | numeric metric | calvert_co_barstow           | Calvert Co / Barstow          | number        | number        |
| Yes      | numeric metric | davidsonville                | Davidsonville                 | number        | number        |
| Yes      | numeric metric | edgewood                     | Edgewood                      | number        | number        |
| Yes      | numeric metric | essex                        | Essex                         | number        | number        |
| Yes      | numeric metric | fairhill                     | Fairhill                      | number        | number        |
| Yes      | numeric metric | frederick_airport            | Frederick Airport             | number        | text          |
| Yes      | numeric metric | furley_e_s_recreation_center | Furley E.S. Recreation Center | number        | text          |
| Yes      | numeric metric | hagerstown                   | Hagerstown                    | number        | text          |
| Yes      | numeric metric | hu_beltsville                | HU-Beltsville                 | number        | number        |
| Yes      | numeric metric | millington                   | Millington                    | number        | number        |
| Yes      | numeric metric | padonia                      | Padonia                       | number        | number        |
| Yes      | numeric metric | pg_equestrian_center         | PG Equestrian Center          | number        | number        |
| Yes      | numeric metric | rockville                    | Rockville                     | number        | number        |
| Yes      | numeric metric | south_carroll                | South Carroll                 | number        | number        |
| Yes      | numeric metric | southern_maryland            | Southern Maryland             | number        | number        |
| Yes      | numeric metric | state_wide_max               | State-wide Max                | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qgct-y4xa d:2008-04-18T00:00:00.000Z m:edgewood=86 m:southern_maryland=83 m:davidsonville=87 m:fairhill=82 m:essex=79 m:millington=79 m:calvert_co_barstow=79 m:aldino=85 m:state_wide_max=87 m:pg_equestrian_center=79 m:hu_beltsville=77

series e:qgct-y4xa d:2008-04-19T00:00:00.000Z m:edgewood=82 m:davidsonville=81 m:fairhill=85 m:essex=77 m:millington=81 m:south_carroll=77 m:calvert_co_barstow=76 m:aldino=82 m:state_wide_max=85 m:pg_equestrian_center=76 m:hu_beltsville=77

series e:qgct-y4xa d:2008-05-07T00:00:00.000Z m:rockville=76 m:state_wide_max=76
```

## Meta Commands

```ls
metric m:aldino p:integer l:Aldino t:dataTypeName=number

metric m:calvert_co_barstow p:integer l:"Calvert Co / Barstow" t:dataTypeName=number

metric m:davidsonville p:integer l:Davidsonville t:dataTypeName=number

metric m:edgewood p:integer l:Edgewood t:dataTypeName=number

metric m:essex p:integer l:Essex t:dataTypeName=number

metric m:fairhill p:integer l:Fairhill t:dataTypeName=number

metric m:frederick_airport p:integer l:"Frederick Airport" t:dataTypeName=number

metric m:furley_e_s_recreation_center p:integer l:"Furley E.S. Recreation Center" t:dataTypeName=number

metric m:hagerstown p:integer l:Hagerstown t:dataTypeName=number

metric m:hu_beltsville p:integer l:HU-Beltsville t:dataTypeName=number

metric m:millington p:integer l:Millington t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:pg_equestrian_center p:integer l:"PG Equestrian Center" t:dataTypeName=number

metric m:rockville p:integer l:Rockville t:dataTypeName=number

metric m:south_carroll p:integer l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:integer l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:qgct-y4xa l:"Maryland Ozone Exceedance Days in 2008" t:url=https://data.maryland.gov/api/views/qgct-y4xa

property e:qgct-y4xa t:meta.view v:id=qgct-y4xa v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2008"

property e:qgct-y4xa t:meta.view.license v:name="Public Domain"

property e:qgct-y4xa t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:qgct-y4xa t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | aldino | calvert_co_barstow | davidsonville | edgewood | essex | fairhill | frederick_airport | furley_e_s_recreation_center | hagerstown | hu_beltsville | millington | padonia | pg_equestrian_center | rockville | south_carroll | southern_maryland | state_wide_max | 
| =================== | ====== | ================== | ============= | ======== | ===== | ======== | ================= | ============================ | ========== | ============= | ========== | ======= | ==================== | ========= | ============= | ================= | ============== | 
| 2008-04-18T00:00:00 | 85     | 79                 | 87            | 86       | 79    | 82       |                   |                              |            | 77            | 79         |         | 79                   |           |               | 83                | 87             | 
| 2008-04-19T00:00:00 | 82     | 76                 | 81            | 82       | 77    | 85       |                   |                              |            | 77            | 81         |         | 76                   |           | 77            |                   | 85             | 
| 2008-05-07T00:00:00 |        |                    |               |          |       |          |                   |                              |            |               |            |         |                      | 76        |               |                   | 76             | 
| 2008-05-30T00:00:00 |        |                    |               |          |       |          |                   |                              |            |               |            |         |                      |           | 76            |                   | 76             | 
| 2008-06-07T00:00:00 | 92     |                    | 77            | 88       |       | 88       |                   |                              |            |               |            |         | 81                   |           |               |                   | 92             | 
| 2008-06-09T00:00:00 |        |                    |               |          |       |          |                   |                              |            |               | 83         |         |                      |           |               |                   | 83             | 
| 2008-06-10T00:00:00 | 80     |                    |               |          |       |          |                   |                              |            | 85            |            | 99      |                      | 85        | 79            |                   | 99             | 
| 2008-06-12T00:00:00 |        |                    | 76            | 79       | 78    |          |                   |                              |            |               | 88         |         | 80                   |           |               | 78                | 88             | 
| 2008-06-13T00:00:00 | 83     |                    | 78            | 85       | 81    |          | 85                |                              |            | 85            | 85         | 97      | 77                   | 94        | 96            | 76                | 97             | 
| 2008-06-14T00:00:00 | 89     |                    |               | 93       | 81    | 80       |                   |                              |            |               | 99         |         |                      |           |               |                   | 99             | 
```