# L&I Public Notes For Affidavit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-public-notes-for-affidavit) |
| Metadata | [Link](https://data.wa.gov/api/views/gs3k-hp7i) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gs3k-hp7i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gs3k-hp7i/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gs3k-hp7i |
| Name | L&I Public Notes For Affidavit |
| Attribution | L & I |
| Category | Labor |
| Tags | contractor, affidavit, notes |
| Created | 2015-10-30T20:39:23Z |
| Publication Date | 2015-12-07T20:08:05Z |

## Description

Public Notes For Affidavit

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| No       |             | id             | ID             | text          | number        |
| Yes      | series tag  | notes          | Notes          | text          | text          |
| Yes      | time        | notesenteredon | NotesEnteredOn | calendar_date | calendar_date |
```

## Time Field

```ls
Value = notesenteredon
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:gs3k-hp7i d:2015-11-30T00:00:00.000Z t:notes="-- On 10/20/2015:--
1. Clean up bio hazard. 2. Apartment 3. 3 stories 4. no retail or commercial use. Permanent residence only. No rehabilitation, no transitional housing, no treatment services, no dormitories, no counseling. Each unit is rented separately. Each unit contains its own bathroom &amp; kitchen. No parts of the structure are used by members of the public." m:row_number.gs3k-hp7i=1

series e:gs3k-hp7i d:2015-12-09T00:00:00.000Z t:notes="Nordic Project # 15869 WO #01 Harbor Island Safety Fencing" m:row_number.gs3k-hp7i=2

series e:gs3k-hp7i d:2015-10-27T00:00:00.000Z t:notes="-- On 7/10/2015:--
GARY REEDS EXCAVATING & TRUCKING IS - A DUMP TRUCKING COMPANY" m:row_number.gs3k-hp7i=3
```

## Meta Commands

```ls
metric m:row_number.gs3k-hp7i p:long l:"Row Number"

entity e:gs3k-hp7i l:"L&I Public Notes For Affidavit" t:attribution="L & I" t:url=https://data.wa.gov/api/views/gs3k-hp7i

property e:gs3k-hp7i t:meta.view v:id=gs3k-hp7i v:category=Labor v:averageRating=0 v:name="L&I Public Notes For Affidavit" v:attribution="L & I"

property e:gs3k-hp7i t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:gs3k-hp7i t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```