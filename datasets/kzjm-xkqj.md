# Seattle Real Time Fire 911 Calls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-real-time-fire-911-calls-6cdf3) |
| Metadata | [Link](https://data.seattle.gov/api/views/kzjm-xkqj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kzjm-xkqj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kzjm-xkqj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kzjm-xkqj |
| Name | Seattle Real Time Fire 911 Calls |
| Attribution | City of Seattle Fire Department MIS |
| Category | Public Safety |
| Tags | seattle, 911, fire, dispatch e911, sfd mobile |
| Created | 2010-01-08T21:48:17Z |
| Publication Date | 2011-11-10T18:10:17Z |

## Description

Provides Seattle Fire Department 911 dispatches. Updated every 5 minutes.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       |             | address         | Address         | text      | text        |
| Yes      | series tag  | type            | Type            | text      | text        |
| Yes      | time        | datetime        | Datetime        | date      | date        |
| No       |             | latitude        | Latitude        | number    | number      |
| No       |             | longitude       | Longitude       | number    | number      |
| Yes      | series tag  | incident_number | Incident Number | text      | text        |
```

## Time Field

```ls
Value = datetime
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:kzjm-xkqj d:2011-11-10T10:07:43.000Z t:type=--T::00 m:row_number.kzjm-xkqj=1

series e:kzjm-xkqj d:2011-11-09T23:33:00.000Z t:incident_number=F110104166 t:type="Medic Response" m:row_number.kzjm-xkqj=2

series e:kzjm-xkqj d:2011-11-09T23:32:00.000Z t:incident_number=F110104164 t:type="Aid Response" m:row_number.kzjm-xkqj=3
```

## Meta Commands

```ls
metric m:row_number.kzjm-xkqj p:long l:"Row Number"

entity e:kzjm-xkqj l:"Seattle Real Time Fire 911 Calls" t:attribution="City of Seattle Fire Department MIS" t:url=https://data.seattle.gov/api/views/kzjm-xkqj

property e:kzjm-xkqj t:meta.view v:id=kzjm-xkqj v:category="Public Safety" v:attributionLink=http://web5.seattle.gov/MNM/incidentresponse.aspx v:averageRating=0 v:name="Seattle Real Time Fire 911 Calls" v:attribution="City of Seattle Fire Department MIS"

property e:kzjm-xkqj t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kzjm-xkqj t:meta.view.owner v:id=5rii-9ghs v:profileImageUrlMedium=/api/users/5rii-9ghs/profile_images/THUMB v:profileImageUrlLarge=/api/users/5rii-9ghs/profile_images/LARGE v:screenName="Seattle Fire Department" v:profileImageUrlSmall=/api/users/5rii-9ghs/profile_images/TINY v:displayName="Seattle Fire Department"

property e:kzjm-xkqj t:meta.view.tableauthor v:id=5rii-9ghs v:profileImageUrlMedium=/api/users/5rii-9ghs/profile_images/THUMB v:profileImageUrlLarge=/api/users/5rii-9ghs/profile_images/LARGE v:screenName="Seattle Fire Department" v:profileImageUrlSmall=/api/users/5rii-9ghs/profile_images/TINY v:displayName="Seattle Fire Department"
```

## Top Records

```ls
| address                 | type                       | datetime   | latitude  | longitude   | incident_number | 
| ======================= | ========================== | ========== | ========= | =========== | =============== | 
|                         | --T::00                    |            |           |             |                 | 
| 6900 37th Av S          | Medic Response             | 1320881580 | 47.540683 | -122.286131 | F110104166      | 
| N 50th St / Stone Way N | Aid Response               | 1320881520 | 47.665034 | -122.340207 | F110104164      | 
| E John St / E Olive Way | Aid Response               | 1320881520 | 47.619575 | -122.324257 | F110104165      | 
| 611 12th Av S           | Aid Response               | 1320881340 | 47.597406 | -122.317228 | F110104162      | 
| 4545 42nd Av Sw         | Automatic Medical Alarm    | 1320881100 | 47.562472 | -122.385455 | F110104161      | 
| 2124 3rd Av             | Investigate Out Of Service | 1320880620 | 47.613347 | -122.342498 | F110104160      | 
| 7605 Rainier Av S       | Aid Response               | 1320880020 | 47.534478 | -122.269989 | F110104159      | 
| 2615 Sw Barton St       | Medic Response             | 1320879900 | 47.521023 | -122.366095 | F110104158      | 
| 2028 Ne 65th St         | Aid Response               | 1320879780 | 47.675778 | -122.305907 | F110104156      | 
```