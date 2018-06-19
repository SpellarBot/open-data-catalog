# Maryland Ozone Exceedance Days in 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2009-a9308) |
| Metadata | [Link](https://data.maryland.gov/api/views/vbtk-pt3t) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/vbtk-pt3t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/vbtk-pt3t/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | vbtk-pt3t |
| Name | Maryland Ozone Exceedance Days in 2009 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2012-10-26T18:03:50Z |
| Publication Date | 2012-10-26T18:05:50Z |

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Finalized Data.  In 2008 EPA set the ozone standard to 75 ppb.  High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects.  You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/.  This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded.  More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | time           | date               | Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | aldino             | Aldino               | number        | text          |
| Yes      | numeric metric | calvert_co_barstow | Calvert Co / Barstow | number        | text          |
| Yes      | numeric metric | edgewood           | Edgewood             | number        | number        |
| Yes      | numeric metric | essex              | Essex                | number        | text          |
| Yes      | numeric metric | fairhill           | Fairhill             | number        | text          |
| Yes      | numeric metric | hu_beltsville      | HU-Beltsville        | number        | text          |
| Yes      | numeric metric | padonia            | Padonia              | number        | text          |
| Yes      | numeric metric | state_wide_max     | State-wide Max       | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vbtk-pt3t d:2009-04-25T00:00:00.000Z m:fairhill=76 m:state_wide_max=76

series e:vbtk-pt3t d:2009-04-26T00:00:00.000Z m:edgewood=78 m:state_wide_max=78

series e:vbtk-pt3t d:2009-06-08T00:00:00.000Z m:padonia=76 m:state_wide_max=76 m:hu_beltsville=76
```

## Meta Commands

```ls
metric m:aldino p:integer l:Aldino t:dataTypeName=number

metric m:calvert_co_barstow p:integer l:"Calvert Co / Barstow" t:dataTypeName=number

metric m:edgewood p:integer l:Edgewood t:dataTypeName=number

metric m:essex p:integer l:Essex t:dataTypeName=number

metric m:fairhill p:integer l:Fairhill t:dataTypeName=number

metric m:hu_beltsville p:integer l:HU-Beltsville t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:vbtk-pt3t l:"Maryland Ozone Exceedance Days in 2009" t:url=https://data.maryland.gov/api/views/vbtk-pt3t

property e:vbtk-pt3t t:meta.view v:id=vbtk-pt3t v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2009"

property e:vbtk-pt3t t:meta.view.license v:name="Public Domain"

property e:vbtk-pt3t t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:vbtk-pt3t t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | aldino | calvert_co_barstow | edgewood | essex | fairhill | hu_beltsville | padonia | state_wide_max | 
| =================== | ====== | ================== | ======== | ===== | ======== | ============= | ======= | ============== | 
| 2009-04-25T00:00:00 |        |                    |          |       | 76       |               |         | 76             | 
| 2009-04-26T00:00:00 |        |                    | 78       |       |          |               |         | 78             | 
| 2009-06-08T00:00:00 |        |                    |          |       |          | 76            | 76      | 76             | 
| 2009-06-25T00:00:00 | 79     | 76                 | 109      | 86    |          |               |         | 109            | 
| 2009-06-26T00:00:00 | 81     |                    | 91       |       | 83       |               |         | 91             | 
| 2009-07-13T00:00:00 |        |                    | 77       |       |          |               |         | 77             | 
| 2009-07-15T00:00:00 |        |                    | 82       |       |          |               |         | 82             | 
| 2009-07-16T00:00:00 |        |                    | 81       |       | 77       |               |         | 81             | 
| 2009-08-16T00:00:00 |        |                    | 85       |       |          |               |         | 85             | 
| 2009-08-18T00:00:00 |        |                    | 83       |       |          |               |         | 83             | 
```