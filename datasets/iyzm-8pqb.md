# Maryland Ozone Exceedance Days in 2007

## Dataset

* [Dataset URL](https://data.maryland.gov/api/views/iyzm-8pqb/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2007-3ce55)
* [Metadata URL](https://data.maryland.gov/api/views/iyzm-8pqb)
* Id = iyzm-8pqb
* Name = Maryland Ozone Exceedance Days in 2007
* Category = Energy and Environment
* Tags = [air quality, ozone, mde]
* Created = 2012-10-26T17:50:33Z
* Publication Date = 2012-10-26T17:52:16Z
* Rows Updated = 2012-10-26T17:50:38Z

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Finalized Data.  In 2008 EPA set the ozone standard to 75 ppb.  High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects.  You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/.  This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded.  More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Name                          | Field Name                   | Data Type     | Render Type   | Schema Type    | Included | 
| ============================= | ============================ | ============= | ============= | ============== | ======== | 
| Date                          | date                         | calendar_date | calendar_date | time           | Yes      | 
| Aldino                        | aldino                       | number        | number        | numeric metric | Yes      | 
| Calvert Co / Barstow          | calvert_co_barstow           | number        | number        | numeric metric | Yes      | 
| Davidsonville                 | davidsonville                | number        | number        | numeric metric | Yes      | 
| Edgewood                      | edgewood                     | number        | number        | numeric metric | Yes      | 
| Essex                         | essex                        | number        | number        | numeric metric | Yes      | 
| Fairhill                      | fairhill                     | number        | number        | numeric metric | Yes      | 
| Frederick Airport             | frederick_airport            | number        | number        | numeric metric | Yes      | 
| Furley E.S. Recreation Center | furley_e_s_recreation_center | number        | text          | numeric metric | Yes      | 
| Hagerstown                    | hagerstown                   | number        | number        | numeric metric | Yes      | 
| HU-Beltsville                 | hu_beltsville                | number        | number        | numeric metric | Yes      | 
| Millington                    | millington                   | number        | number        | numeric metric | Yes      | 
| Padonia                       | padonia                      | number        | text          | numeric metric | Yes      | 
| PG Equestrian Center          | pg_equestrian_center         | number        | number        | numeric metric | Yes      | 
| Piney Run                     | piney_run                    | number        | text          | numeric metric | Yes      | 
| Rockville                     | rockville                    | number        | number        | numeric metric | Yes      | 
| South Carroll                 | south_carroll                | number        | number        | numeric metric | Yes      | 
| Southern Maryland             | southern_maryland            | number        | number        | numeric metric | Yes      | 
| State-wide Max                | state_wide_max               | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:iyzm-8pqb t:meta.view d:2017-03-08T01:03:42.021Z v:id=iyzm-8pqb v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2007"

property e:iyzm-8pqb t:meta.view.license d:2017-03-08T01:03:42.021Z v:name="Public Domain"

property e:iyzm-8pqb t:meta.view.owner d:2017-03-08T01:03:42.021Z v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:displayName="Andrew Gosden"

property e:iyzm-8pqb t:meta.view.tableauthor d:2017-03-08T01:03:42.021Z v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:displayName="Andrew Gosden"
```