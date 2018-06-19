# New York State Fallen Firefighters Memorial Roll of Honor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-fallen-firefighters-memorial-roll-of-honor) |
| Metadata | [Link](https://data.ny.gov/api/views/i77z-w4nh) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/i77z-w4nh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/i77z-w4nh/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | i77z-w4nh |
| Name | New York State Fallen Firefighters Memorial Roll of Honor |
| Attribution | Division of Homeland Security and Emergency Services |
| Category | Public Safety |
| Tags | fallen, firefighter, memorial |
| Created | 2016-09-23T20:01:18Z |
| Publication Date | 2016-12-27T20:49:53Z |

## Description

This dataset lists the Name, Rank, Fire Department, Date of Death, Current Location on Memorial Wall of each Firefighter whose name has been engraved on the wall.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | name                 | Name                 | text          | text          |
| Yes      | series tag  | rank                 | Rank                 | text          | text          |
| Yes      | series tag  | fire_department      | Fire Department      | text          | text          |
| Yes      | time        | date_of_death        | Date of Death        | calendar_date | calendar_date |
| Yes      | series tag  | location_on_memorial | Location on Memorial | text          | text          |
```

## Time Field

```ls
Value = date_of_death
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:i77z-w4nh d:1976-08-26T00:00:00.000Z t:rank=Foreman t:name="A. David Feluren" t:fire_department="Scotia Fire Department" t:location_on_memorial="8 Top" m:row_number.i77z-w4nh=1

series e:i77z-w4nh d:1906-01-08T00:00:00.000Z t:rank=Firefighter t:name="Abe Dias" t:fire_department="Haverstraw Fire Department" t:location_on_memorial="20 Bottom" m:row_number.i77z-w4nh=2

series e:i77z-w4nh d:1924-04-26T00:00:00.000Z t:rank=Captain t:name="Abraham Price" t:fire_department="Rochester Fire Department" t:location_on_memorial="5 Top" m:row_number.i77z-w4nh=3
```

## Meta Commands

```ls
metric m:row_number.i77z-w4nh p:long l:"Row Number"

entity e:i77z-w4nh l:"New York State Fallen Firefighters Memorial Roll of Honor" t:attribution="Division of Homeland Security and Emergency Services" t:url=https://data.ny.gov/api/views/i77z-w4nh

property e:i77z-w4nh t:meta.view v:id=i77z-w4nh v:category="Public Safety" v:attributionLink=http://www.dhses.ny.gov/ofpc/memorial v:averageRating=0 v:name="New York State Fallen Firefighters Memorial Roll of Honor" v:attribution="Division of Homeland Security and Emergency Services"

property e:i77z-w4nh t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:i77z-w4nh t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| name                  | rank        | fire_department               | date_of_death       | location_on_memorial | 
| ===================== | =========== | ============================= | =================== | ==================== | 
| A. David Feluren      | Foreman     | Scotia Fire Department        | 1976-08-26T00:00:00 | 8 Top                | 
| Abe Dias              | Firefighter | Haverstraw Fire Department    | 1906-01-08T00:00:00 | 20 Bottom            | 
| Abraham Price         | Captain     | Rochester Fire Department     | 1924-04-26T00:00:00 | 5 Top                | 
| Adam D. Rand          | Firefighter | New York City Fire Department | 2001-09-11T00:00:00 | 16 Top               | 
| Adam Damm             | Firefighter | New York City Fire Department | 1907-02-27T00:00:00 | 6 Bottom             | 
| Adam Fisher           | Captain     | Buffalo Fire Department       | 1891-01-23T00:00:00 | 14 Bottom            | 
| Adolph A. D? Ambrosio | Firefighter | New York City Fire Department | 1975-07-04T00:00:00 | 8 Top                | 
| Adolph L. Wiemer      | Hoseman     | Rochester Fire Department     | 1939-05-20T00:00:00 | 17 Top               | 
| Adrian B. Curnan      | Firefighter | New York City Fire Department | 1922-06-19T00:00:00 | 6 Top                | 
| Adrian C. Snyder      | Firefighter | Caton Fire Department         | 1976-08-26T00:00:00 | 8 Top                | 
```