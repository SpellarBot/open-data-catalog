# Public Health Clinics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-clinics-308e0) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/dnjy-kgwg) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/dnjy-kgwg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/dnjy-kgwg/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | dnjy-kgwg |
| Name | Public Health Clinics |
| Attribution | Seattle-King County Public Health |
| Category | Health |
| Tags | location, map, office, clinic, health |
| Created | 2014-01-30T02:33:17Z |
| Publication Date | 2014-01-30T03:47:38Z |

## Description

Clinic locations for Seattle/King County Public Health

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | clinic_name    | Clinic name    | text      | text        |
| Yes      | series tag  | region         | Region         | text      | text        |
| Yes      | series tag  | street_address | Street address | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | zip            | Zip            | text      | text        |
| Yes      | series tag  | url            | URL            | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dnjy-kgwg d:2014-01-29T19:26:31.000Z t:zip=98002 t:clinic_name="Auburn Public Health Center" t:street_address="901 Auburn Way N, Suite A" t:url=http://www.kingcounty.gov/healthservices/health/locations/auburn.aspx t:city=Auburn m:row_number.dnjy-kgwg=1

series e:dnjy-kgwg d:2014-01-29T19:27:56.000Z t:region="South Seattle" t:zip=98118 t:clinic_name="Columbia Public Health Center" t:street_address="4400 37th Ave S." t:url=http://www.kingcounty.gov/healthservices/health/locations/columbia.aspx t:city=Seattle m:row_number.dnjy-kgwg=2

series e:dnjy-kgwg d:2014-01-29T19:38:13.000Z t:region=Kent t:zip=98030 t:clinic_name="Kent Public Health Center at Birch Creek" t:street_address="13111 SE 274th St." t:url=http://www.kingcounty.gov/healthservices/health/locations/birchcreek.aspx t:city=Kent m:row_number.dnjy-kgwg=3
```

## Meta Commands

```ls
metric m:row_number.dnjy-kgwg p:long l:"Row Number"

entity e:dnjy-kgwg l:"Public Health Clinics" t:attribution="Seattle-King County Public Health" t:url=https://data.kingcounty.gov/api/views/dnjy-kgwg

property e:dnjy-kgwg t:meta.view v:id=dnjy-kgwg v:category=Health v:attributionLink=http://www.kingcounty.gov/healthservices/health/ v:averageRating=0 v:name="Public Health Clinics" v:attribution="Seattle-King County Public Health"

property e:dnjy-kgwg t:meta.view.license v:name="Public Domain"

property e:dnjy-kgwg t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:dnjy-kgwg t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | clinic_name                              | region            | street_address            | city        | zip   | url                                                                                                                                                    | 
| =========== | ======================================== | ================= | ========================= | =========== | ===== | ====================================================================================================================================================== | 
| 1391023591  | Auburn Public Health Center              |                   | 901 Auburn Way N, Suite A | Auburn      | 98002 | [http://www.kingcounty.gov/healthservices/health/locations/auburn.aspx, http://www.kingcounty.gov/healthservices/health/locations/auburn.aspx]         | 
| 1391023676  | Columbia Public Health Center            | South Seattle     | 4400 37th Ave S.          | Seattle     | 98118 | [http://www.kingcounty.gov/healthservices/health/locations/columbia.aspx, http://www.kingcounty.gov/healthservices/health/locations/columbia.aspx]     | 
| 1391024293  | Kent Public Health Center at Birch Creek | Kent              | 13111 SE 274th St.        | Kent        | 98030 | [http://www.kingcounty.gov/healthservices/health/locations/birchcreek.aspx, http://www.kingcounty.gov/healthservices/health/locations/birchcreek.aspx] | 
| 1391024314  | Downtown Public Health Center            | Seattle           | 2124 - 4th Ave.           | Seattle     | 98121 | [http://www.kingcounty.gov/healthservices/health/locations/downtown.aspx, http://www.kingcounty.gov/healthservices/health/locations/downtown.aspx]     | 
| 1391024476  | Eastgate Public Health Center            | Eastgate/Factoria | 14350 SE Eastgate Way     | Bellevue    | 98007 | [http://www.kingcounty.gov/healthservices/health/locations/eastgate.aspx, http://www.kingcounty.gov/healthservices/health/locations/eastgate.aspx]     | 
| 1391024756  | Kent Public Health Center at East Hill   |                   | 13210 SE 240th St         | Kent        | 98004 | [http://www.kingcounty.gov/healthservices/health/locations/easthill.aspx, http://www.kingcounty.gov/healthservices/health/locations/easthill.aspx]     | 
| 1391024780  | Federal Way Public Health Center         |                   | 33431 13th Place S.       | Federal Way | 98003 | [http://www.kingcounty.gov/healthservices/health/locations/federalway.aspx, http://www.kingcounty.gov/healthservices/health/locations/federalway.aspx] | 
| 1391024804  | North Public Health Center               | North Seattle     | 10501 Meridian Ave N.     | Seattle     | 98133 | [http://www.kingcounty.gov/healthservices/health/locations/north.aspx, http://www.kingcounty.gov/healthservices/health/locations/north.aspx]           | 
| 1391024822  | Northshore Public Health Center          | Bothell           | 10808 NE 145th St.        | Bothell     | 98011 | [http://www.kingcounty.gov/healthservices/health/locations/northshore.aspx, http://www.kingcounty.gov/healthservices/health/locations/northshore.aspx] | 
| 1391024839  | Renton Public Health Center              |                   | 3001 NE 4th St.           | Renton      | 98056 | [http://www.kingcounty.gov/healthservices/health/locations/renton.aspx, http://www.kingcounty.gov/healthservices/health/locations/renton.aspx]         | 
```