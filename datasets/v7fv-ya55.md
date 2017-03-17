# Maryland Ozone Exceedance Days in 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2010-1c221) |
| Metadata | [Link](https://data.maryland.gov/api/views/v7fv-ya55) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/v7fv-ya55/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/v7fv-ya55/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | v7fv-ya55 |
| Name | Maryland Ozone Exceedance Days in 2010 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2012-10-26T18:08:17Z |
| Publication Date | 2012-10-26T18:10:04Z |
| Rows Updated | 2012-10-26T18:08:27Z |

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Finalized Data.  In 2008 EPA set the ozone standard to 75 ppb.  High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects.  You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/.  This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded.  More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================= | ============= | ============= |
| Yes      | time           | date                         | Date                          | calendar_date | calendar_date |
| Yes      | numeric metric | aldino                       | Aldino                        | number        | number        |
| Yes      | numeric metric | essex                        | Essex                         | number        | number        |
| Yes      | numeric metric | calvert_co_barstow           | Calvert Co / Barstow          | number        | number        |
| Yes      | numeric metric | davidsonville                | Davidsonville                 | number        | number        |
| Yes      | numeric metric | edgewood                     | Edgewood                      | number        | number        |
| Yes      | numeric metric | fairhill                     | Fairhill                      | number        | number        |
| Yes      | numeric metric | frederick_airport            | Frederick Airport             | number        | number        |
| Yes      | series tag     | furley_e_s_recreation_center | Furley E.S. Recreation Center | text          | text          |
| Yes      | numeric metric | hagerstown                   | Hagerstown                    | number        | number        |
| Yes      | numeric metric | hu_beltsville                | HU-Beltsville                 | number        | number        |
| Yes      | numeric metric | millington                   | Millington                    | number        | text          |
| Yes      | numeric metric | padonia                      | Padonia                       | number        | number        |
| Yes      | series tag     | pg_equestrian_center         | PG Equestrian Center          | text          | number        |
| Yes      | numeric metric | piney_run                    | Piney Run                     | number        | number        |
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
series e:v7fv-ya55 d:2010-04-02T00:00:00.000Z m:piney_run=76 m:state_wide_max=76

series e:v7fv-ya55 d:2010-04-11T00:00:00.000Z m:piney_run=78 m:state_wide_max=78

series e:v7fv-ya55 d:2010-04-15T00:00:00.000Z m:piney_run=83 m:state_wide_max=83
```

## Meta Commands

```ls
metric m:aldino p:integer l:Aldino t:dataTypeName=number

metric m:essex p:integer l:Essex t:dataTypeName=number

metric m:calvert_co_barstow p:integer l:"Calvert Co / Barstow" t:dataTypeName=number

metric m:davidsonville p:integer l:Davidsonville t:dataTypeName=number

metric m:edgewood p:integer l:Edgewood t:dataTypeName=number

metric m:fairhill p:integer l:Fairhill t:dataTypeName=number

metric m:frederick_airport p:integer l:"Frederick Airport" t:dataTypeName=number

metric m:hagerstown p:integer l:Hagerstown t:dataTypeName=number

metric m:hu_beltsville p:integer l:HU-Beltsville t:dataTypeName=number

metric m:millington p:integer l:Millington t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:piney_run p:integer l:"Piney Run" t:dataTypeName=number

metric m:rockville p:integer l:Rockville t:dataTypeName=number

metric m:south_carroll p:integer l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:integer l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:v7fv-ya55 l:"Maryland Ozone Exceedance Days in 2010" t:url=https://data.maryland.gov/api/views/v7fv-ya55

property e:v7fv-ya55 t:meta.view v:id=v7fv-ya55 v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2010"

property e:v7fv-ya55 t:meta.view.license v:name="Public Domain"

property e:v7fv-ya55 t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:displayName="Andrew Gosden"

property e:v7fv-ya55 t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:displayName="Andrew Gosden"
```