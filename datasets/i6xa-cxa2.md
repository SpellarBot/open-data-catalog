# Deer Kill Locations 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deer-kill-locations-2009) |
| Metadata | [Link](https://data.iowa.gov/api/views/i6xa-cxa2) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/i6xa-cxa2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/i6xa-cxa2/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | i6xa-cxa2 |
| Name | Deer Kill Locations 2009 |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, deer, deer kill, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-09T05:59:41Z |
| Publication Date | 2016-06-09T06:01:15Z |

## Description

This database is a yearly snapshot of deer kill sites as entered by Maintenance field crews. This does not necessarily correlate to crash data related to deer impacts; this is strictly deer downed within the right of way that are documented and moved by Maintenance staff. The data in this layer is for Fiscal Year 2009 only.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | costcenter            | COSTCENTER            | text      | text        |
| No       |                | calyear               | CALYEAR               | number    | number      |
| No       |                | fiscal_year           | FISCAL_YEAR           | number    | number      |
| No       |                | fy_quarter            | FY_QUARTER            | number    | number      |
| Yes      | time           | dk_date               | DK_DATE               | date      | date        |
| Yes      | series tag     | rms_county            | RMS_COUNTY            | text      | number      |
| Yes      | series tag     | route_name            | ROUTE_NAME            | text      | text        |
| Yes      | numeric metric | rms_milepost          | RMS_MILEPOST          | number    | number      |
| Yes      | series tag     | sex                   | SEX                   | text      | text        |
| Yes      | series tag     | comments              | COMMENTS              | text      | text        |
| No       |                | latitude              | LATITUDE              | number    | number      |
| No       |                | longitude             | LONGITUDE             | number    | number      |
| Yes      | series tag     | burial_description    | BURIAL_DESCRIPTION    | text      | text        |
| Yes      | numeric metric | burial                | BURIAL                | number    | number      |
| Yes      | numeric metric | response_to_complaint | RESPONSE_TO_COMPLAINT | number    | number      |
| Yes      | series tag     | district              | DISTRICT              | text      | number      |
| Yes      | series tag     | objectid              | OBJECTID              | text      | number      |
```

## Time Field

```ls
Value = dk_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fiscal_year,latitude,longitude,calyear,fy_quarter
```

## Data Commands

```ls
series e:i6xa-cxa2 d:2008-07-11T00:00:00.000Z t:rms_county=40 t:sex=Female t:route_name="US 20 E" t:costcenter=551609 t:objectid=29498 t:district=1 m:rms_milepost=150 m:burial=1

series e:i6xa-cxa2 d:2008-07-11T00:00:00.000Z t:rms_county=38 t:sex=Female t:route_name="US 20 E" t:costcenter=551607 t:objectid=29499 t:district=1 m:rms_milepost=184.3 m:burial=1

series e:i6xa-cxa2 d:2008-07-11T00:00:00.000Z t:rms_county=22 t:sex=Female t:route_name="US 52 N" t:costcenter=552822 t:objectid=29500 t:district=2 m:rms_milepost=91.3 m:burial=1
```

## Meta Commands

```ls
metric m:rms_milepost p:double l:RMS_MILEPOST d:"RMS Milepost" t:dataTypeName=number

metric m:burial p:integer l:BURIAL d:Burial t:dataTypeName=number

metric m:response_to_complaint p:long l:RESPONSE_TO_COMPLAINT d:"Response to Complaint?" t:dataTypeName=number

entity e:i6xa-cxa2 l:"Deer Kill Locations 2009" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/i6xa-cxa2

property e:i6xa-cxa2 t:meta.view v:id=i6xa-cxa2 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Historic_Deer_Kill_Locations/MapServer/6 v:averageRating=0 v:name="Deer Kill Locations 2009" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:i6xa-cxa2 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:i6xa-cxa2 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```