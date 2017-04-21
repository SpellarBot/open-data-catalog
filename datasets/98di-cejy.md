# Maryland OEDs 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-oeds-2013-a8c7d) |
| Metadata | [Link](https://data.maryland.gov/api/views/98di-cejy) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/98di-cejy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/98di-cejy/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 98di-cejy |
| Name | Maryland OEDs 2013 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2014-09-30T18:28:43Z |
| Publication Date | 2014-09-30T18:30:40Z |

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Preliminary Data. In 2008 EPA set the ozone standard to 75 ppb. High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects. You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/. This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded. More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type     | Render Type   |
| ======== | ============== | ====================== | ======================== | ============= | ============= |
| Yes      | time           | date                   | Date                     | calendar_date | calendar_date |
| Yes      | numeric metric | aldino                 | Aldino                   | number        | number        |
| Yes      | numeric metric | beltsville_castnet     | Beltsville (CASTNET)     | number        | number        |
| Yes      | numeric metric | blackwater_nwr_castnet | Blackwater NWR (CASTNET) | number        | number        |
| Yes      | numeric metric | calvert                | Calvert                  | number        | number        |
| Yes      | numeric metric | davidsonville          | Davidsonville            | number        | number        |
| Yes      | numeric metric | edgewood               | Edgewood                 | number        | number        |
| Yes      | numeric metric | essex                  | Essex                    | number        | number        |
| Yes      | numeric metric | fair_hill              | Fair Hill                | number        | number        |
| Yes      | numeric metric | frederick_airport      | Frederick Airport        | number        | number        |
| Yes      | numeric metric | furley                 | Furley                   | number        | number        |
| Yes      | numeric metric | hagerstown             | Hagerstown               | number        | number        |
| Yes      | numeric metric | horn_point             | Horn Point               | number        | number        |
| Yes      | numeric metric | hu_beltsville          | HU-Beltsville            | number        | number        |
| Yes      | numeric metric | millington             | Millington               | number        | number        |
| Yes      | numeric metric | padonia                | Padonia                  | number        | number        |
| Yes      | numeric metric | pg_equestrian_center   | PG Equestrian Center     | number        | number        |
| Yes      | numeric metric | piney_run              | Piney Run                | number        | number        |
| Yes      | numeric metric | rockville              | Rockville                | number        | number        |
| Yes      | numeric metric | south_carroll          | South Carroll            | number        | number        |
| Yes      | numeric metric | southern_maryland      | Southern Maryland        | number        | number        |
| Yes      | numeric metric | state_wide_max         | State-wide Max           | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:98di-cejy d:2013-05-15T00:00:00.000Z m:piney_run=77 m:state_wide_max=77

series e:98di-cejy d:2013-05-29T00:00:00.000Z m:fair_hill=80 m:state_wide_max=80

series e:98di-cejy d:2013-05-31T00:00:00.000Z m:padonia=76 m:state_wide_max=76
```

## Meta Commands

```ls
metric m:aldino p:long l:Aldino t:dataTypeName=number

metric m:beltsville_castnet p:integer l:"Beltsville (CASTNET)" t:dataTypeName=number

metric m:blackwater_nwr_castnet p:long l:"Blackwater NWR (CASTNET)" t:dataTypeName=number

metric m:calvert p:long l:Calvert t:dataTypeName=number

metric m:davidsonville p:integer l:Davidsonville t:dataTypeName=number

metric m:edgewood p:integer l:Edgewood t:dataTypeName=number

metric m:essex p:long l:Essex t:dataTypeName=number

metric m:fair_hill p:integer l:"Fair Hill" t:dataTypeName=number

metric m:frederick_airport p:integer l:"Frederick Airport" t:dataTypeName=number

metric m:furley p:long l:Furley t:dataTypeName=number

metric m:hagerstown p:long l:Hagerstown t:dataTypeName=number

metric m:horn_point p:long l:"Horn Point" t:dataTypeName=number

metric m:hu_beltsville p:long l:HU-Beltsville t:dataTypeName=number

metric m:millington p:integer l:Millington t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:pg_equestrian_center p:long l:"PG Equestrian Center" t:dataTypeName=number

metric m:piney_run p:integer l:"Piney Run" t:dataTypeName=number

metric m:rockville p:long l:Rockville t:dataTypeName=number

metric m:south_carroll p:long l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:long l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:98di-cejy l:"Maryland OEDs 2013" t:url=https://data.maryland.gov/api/views/98di-cejy

property e:98di-cejy t:meta.view v:id=98di-cejy v:category="Energy and Environment" v:averageRating=0 v:name="Maryland OEDs 2013"

property e:98di-cejy t:meta.view.license v:name="Public Domain"

property e:98di-cejy t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:98di-cejy t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | aldino | beltsville_castnet | blackwater_nwr_castnet | calvert | davidsonville | edgewood | essex | fair_hill | frederick_airport | furley | hagerstown | horn_point | hu_beltsville | millington | padonia | pg_equestrian_center | piney_run | rockville | south_carroll | southern_maryland | state_wide_max | 
| =================== | ====== | ================== | ====================== | ======= | ============= | ======== | ===== | ========= | ================= | ====== | ========== | ========== | ============= | ========== | ======= | ==================== | ========= | ========= | ============= | ================= | ============== | 
| 2013-05-15T00:00:00 |        |                    |                        |         |               |          |       |           |                   |        |            |            |               |            |         |                      | 77        |           |               |                   | 77             | 
| 2013-05-29T00:00:00 |        |                    |                        |         |               |          |       | 80        |                   |        |            |            |               |            |         |                      |           |           |               |                   | 80             | 
| 2013-05-31T00:00:00 |        |                    |                        |         |               |          |       |           |                   |        |            |            |               |            | 76      |                      |           |           |               |                   | 76             | 
| 2013-06-05T00:00:00 |        |                    |                        |         |               |          |       |           | 76                |        |            |            |               |            |         |                      |           |           |               |                   | 76             | 
| 2013-06-25T00:00:00 |        |                    |                        |         |               |          |       |           |                   |        |            |            |               | 78         |         |                      |           |           |               |                   | 78             | 
| 2013-06-26T00:00:00 |        |                    |                        |         |               |          |       | 76        |                   |        |            |            |               |            |         |                      |           |           |               |                   | 76             | 
| 2013-07-17T00:00:00 |        |                    |                        |         | 76            |          |       |           |                   |        |            |            |               |            |         |                      |           |           |               |                   | 76             | 
| 2013-07-18T00:00:00 |        | 77                 |                        |         |               | 80       |       |           |                   |        |            |            |               |            |         |                      |           |           |               |                   | 80             | 
| 2013-07-19T00:00:00 |        | 77                 |                        |         |               | 78       |       |           |                   |        |            |            |               |            |         |                      |           |           |               |                   | 78             | 
```