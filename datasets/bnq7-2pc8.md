# Transit Communities Funding Toolkit

## Dataset

* [Dataset URL](https://data.seattle.gov/api/views/bnq7-2pc8/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/transit-communities-funding-toolkit-a7336)
* [Metadata URL](https://data.seattle.gov/api/views/bnq7-2pc8)
* Id = bnq7-2pc8
* Name = Transit Communities Funding Toolkit
* Attribution = City of Seattle, Seattle Planning Commission
* Category = Community
* Tags = [funding, levies, community development, economic development]
* Created = 2011-02-14T19:47:12Z
* Publication Date = 2011-04-17T00:03:09Z
* Rows Updated = 2011-08-21T02:48:35Z

## Description

The funding toolkit identifies funding sources for three broad categories of livability elements: infrastructure investments, which may include right-of-way improvements, sidewalks, Green Streets, or bike lanes/facilities; community development, such as affordable housing, public services, schools, historic preservation; and parks and open space, which includes parks, playfields, plazas, and p-patches.

## Columns

```ls
| Name                  | Field Name            | Data Type | Render Type | Schema Type | Included | 
| ===================== | ===================== | ========= | =========== | =========== | ======== | 
| updated_at            | :updated_at           | meta_data | meta_data   | time        | No       | 
| administrator         | administrator         | text      | text        | series tag  | Yes      | 
| program               | program               | text      | text        | series tag  | Yes      | 
| infrastructure        | infrastructure        | checkbox  | checkbox    | series tag  | Yes      | 
| community development | community_development | checkbox  | checkbox    | series tag  | Yes      | 
| open space            | open_space            | checkbox  | checkbox    | series tag  | Yes      | 
| funding amount        | funding_amount        | text      | text        | series tag  | Yes      | 
| funding type          | funding_type          | text      | text        | series tag  | Yes      | 
| description           | description           | text      | text        | series tag  | Yes      | 
| opportunities         | opportunities         | text      | text        | series tag  | Yes      | 
| challenges            | challenges            | text      | text        | series tag  | Yes      | 
| website               | website               | url       | url         | series tag  | Yes      | 
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
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:bnq7-2pc8 l:"Transit Communities Funding Toolkit" t:attribution="City of Seattle, Seattle Planning Commission" t:url=https://data.seattle.gov/api/views/bnq7-2pc8

property e:bnq7-2pc8 t:meta.view d:2017-03-07T22:41:04.983Z v:id=bnq7-2pc8 v:category=Community v:averageRating=0 v:name="Transit Communities Funding Toolkit" v:attribution="City of Seattle, Seattle Planning Commission"

property e:bnq7-2pc8 t:meta.view.license d:2017-03-07T22:41:04.983Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bnq7-2pc8 t:meta.view.owner d:2017-03-07T22:41:04.983Z v:id=9vuc-jwdr v:profileImageUrlMedium=/api/users/9vuc-jwdr/profile_images/THUMB v:profileImageUrlLarge=/api/users/9vuc-jwdr/profile_images/LARGE v:screenName="Sheehy, Katie" v:profileImageUrlSmall=/api/users/9vuc-jwdr/profile_images/TINY v:displayName="Sheehy, Katie"

property e:bnq7-2pc8 t:meta.view.tableauthor d:2017-03-07T22:41:04.983Z v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```