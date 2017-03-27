# Maryland Ozone Exceedance Days in 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2007-3ce55) |
| Metadata | [Link](https://data.maryland.gov/api/views/iyzm-8pqb) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iyzm-8pqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iyzm-8pqb/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iyzm-8pqb |
| Name | Maryland Ozone Exceedance Days in 2007 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2012-10-26T17:50:33Z |
| Publication Date | 2012-10-26T17:52:16Z |

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
| Yes      | numeric metric | frederick_airport            | Frederick Airport             | number        | number        |
| Yes      | numeric metric | furley_e_s_recreation_center | Furley E.S. Recreation Center | number        | text          |
| Yes      | numeric metric | hagerstown                   | Hagerstown                    | number        | number        |
| Yes      | numeric metric | hu_beltsville                | HU-Beltsville                 | number        | number        |
| Yes      | numeric metric | millington                   | Millington                    | number        | number        |
| Yes      | numeric metric | padonia                      | Padonia                       | number        | text          |
| Yes      | numeric metric | pg_equestrian_center         | PG Equestrian Center          | number        | number        |
| Yes      | numeric metric | piney_run                    | Piney Run                     | number        | text          |
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
series e:iyzm-8pqb d:2007-04-22T00:00:00.000Z m:fairhill=77 m:state_wide_max=77

series e:iyzm-8pqb d:2007-05-15T00:00:00.000Z m:piney_run=77 m:fairhill=79 m:state_wide_max=79

series e:iyzm-8pqb d:2007-05-22T00:00:00.000Z m:frederick_airport=78 m:hagerstown=78 m:state_wide_max=78
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

metric m:piney_run p:integer l:"Piney Run" t:dataTypeName=number

metric m:rockville p:integer l:Rockville t:dataTypeName=number

metric m:south_carroll p:integer l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:integer l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:iyzm-8pqb l:"Maryland Ozone Exceedance Days in 2007" t:url=https://data.maryland.gov/api/views/iyzm-8pqb

property e:iyzm-8pqb t:meta.view v:id=iyzm-8pqb v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2007"

property e:iyzm-8pqb t:meta.view.license v:name="Public Domain"

property e:iyzm-8pqb t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:displayName="Andrew Gosden"

property e:iyzm-8pqb t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:displayName="Andrew Gosden"
```