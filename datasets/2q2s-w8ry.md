# Oregon State Owned/Leased Buildings

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/2q2s-w8ry/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/oregon-state-owned-leased-buildings-7d155)
* Id = 2q2s-w8ry
* Name = Oregon State Owned/Leased Buildings
* Attribution = State of Oregon Dept. of Administrative Services
* Tags = [assets, buildings, leased, owned, oregon]
* Created = 2010-10-25T18:43:46Z
* Publication Date = 2011-04-17T00:03:09Z
* Rows Updated = 2011-09-03T20:59:15Z

## Description

Locations of buildings owned and leased by the State of Oregon.

[Note: This dataset does not contain a complete list of state owned and leased buildings, a updated dataset will be uploaded shortly.]

## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| ========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time           | Yes      | 
| Name       | name        | text      | text        | series tag     | Yes      | 
| Address    | address     | text      | text        |                | No       | 
| City       | city        | text      | text        | series tag     | Yes      | 
| ZipCode    | zipcode     | text      | text        | series tag     | Yes      | 
| Type       | type        | text      | text        | series tag     | Yes      | 
| webpage    | webpage     | url       | url         | series tag     | Yes      | 
| SqFt       | sqft        | number    | number      | numeric metric | Yes      | 
| EXPdate    | expdate     | text      | text        | series tag     | Yes      | 
| Directions | directions  | url       | url         | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = address
Annotation Fields = 
```

## Data Commands

```ls
series e:2q2s-w8ry d:2011-09-03T13:55:59.000Z t:name="Agriculture Building" t:type=Owned t:city=Salem m:sqft=76817

series e:2q2s-w8ry d:2011-09-03T13:55:59.000Z t:name="Consumer & Bus Services" t:expdate=10/31/2009 t:type=Leased t:city=Portland m:sqft=90

series e:2q2s-w8ry d:2011-09-03T13:55:59.000Z t:name="Corrections, Dept" t:expdate=1/31/2012 t:type=Leased t:city=Salem m:sqft=12000
```

## Meta Commands

```ls
metric m:sqft p:integer l:SqFt t:dataTypeName=number

entity e:2q2s-w8ry l:"Oregon State Owned/Leased Buildings" t:attribution="State of Oregon Dept. of Administrative Services" t:url=https://data.oregon.gov/api/views/2q2s-w8ry

property e:2q2s-w8ry t:meta.view d:2017-03-03T14:07:37.968Z v:id=2q2s-w8ry v:averageRating=0 v:name="Oregon State Owned/Leased Buildings" v:attribution="State of Oregon Dept. of Administrative Services"

property e:2q2s-w8ry t:meta.view.owner d:2017-03-03T14:07:37.968Z v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:2q2s-w8ry t:meta.view.tableauthor d:2017-03-03T14:07:37.968Z v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```