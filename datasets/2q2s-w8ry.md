# Oregon State Owned/Leased Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-state-owned-leased-buildings-7d155) |
| Metadata | [Link](https://data.oregon.gov/api/views/2q2s-w8ry) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2q2s-w8ry/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2q2s-w8ry/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2q2s-w8ry |
| Name | Oregon State Owned/Leased Buildings |
| Attribution | State of Oregon Dept. of Administrative Services |
| Tags | assets, buildings, leased, owned, oregon |
| Created | 2010-10-25T18:43:46Z |
| Publication Date | 2011-04-17T00:03:09Z |
| Rows Updated | 2011-09-03T20:59:15Z |

## Description

Locations of buildings owned and leased by the State of Oregon.

[Note: This dataset does not contain a complete list of state owned and leased buildings, a updated dataset will be uploaded shortly.]

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | Name       | text      | text        |
| No       |                | address     | Address    | text      | text        |
| Yes      | series tag     | city        | City       | text      | text        |
| Yes      | series tag     | zipcode     | ZipCode    | text      | text        |
| Yes      | series tag     | type        | Type       | text      | text        |
| Yes      | series tag     | webpage     | webpage    | url       | url         |
| Yes      | numeric metric | sqft        | SqFt       | number    | number      |
| Yes      | series tag     | expdate     | EXPdate    | text      | text        |
| Yes      | series tag     | directions  | Directions | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:2q2s-w8ry d:2011-09-03T13:55:59.000Z t:directions="http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=635+CAPITOL+ST+NE+Salem+97301" t:webpage=http://sustainability.oregon.gov/DAS/FAC/Building_Info/agriculture.shtml t:name="Agriculture Building" t:type=Owned t:city=Salem m:sqft=76817

series e:2q2s-w8ry d:2011-09-03T13:55:59.000Z t:directions="http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=811+SW+Sixth+Avenue+Portland+97204" t:webpage=http://sustainability.oregon.gov/DAS/FAC/Building_Info t:name="Consumer & Bus Services" t:expdate=10/31/2009 t:type=Leased t:city=Portland m:sqft=90

series e:2q2s-w8ry d:2011-09-03T13:55:59.000Z t:directions="http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=2757+22nd+Street+SE+Salem+97302" t:webpage=http://sustainability.oregon.gov/DAS/FAC/Building_Info t:name="Corrections, Dept" t:expdate=1/31/2012 t:type=Leased t:city=Salem m:sqft=12000
```

## Meta Commands

```ls
metric m:sqft p:integer l:SqFt t:dataTypeName=number

entity e:2q2s-w8ry l:"Oregon State Owned/Leased Buildings" t:attribution="State of Oregon Dept. of Administrative Services" t:url=https://data.oregon.gov/api/views/2q2s-w8ry

property e:2q2s-w8ry t:meta.view v:id=2q2s-w8ry v:averageRating=0 v:name="Oregon State Owned/Leased Buildings" v:attribution="State of Oregon Dept. of Administrative Services"

property e:2q2s-w8ry t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:2q2s-w8ry t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```