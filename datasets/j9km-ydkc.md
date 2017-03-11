# Seattle Parks and Recreation Parks With Features

## Dataset

* [Dataset URL](https://data.seattle.gov/api/views/j9km-ydkc/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/seattle-parks-and-recreation-parks-with-features)
* [Metadata URL](https://data.seattle.gov/api/views/j9km-ydkc)
* Id = j9km-ydkc
* Name = Seattle Parks and Recreation Parks With Features
* Attribution = Seattle Parks and Recreation
* [Attribution Link](http://www.seattle.gov/parks/)
* Category = Parks and Recreation
* Tags = [parks, features]
* Created = 2016-03-19T22:28:07Z
* Publication Date = 2016-03-19T22:58:21Z
* Rows Updated = 2016-03-19T22:57:29Z

## Description

Listing all parks that have at least one of a particular kind of feature.  EX:  if a park has one or more tennis court it is included.

PMAID is the Property Management Area ID. It is used by the City of Seattle to reference a group of adjoined land parcels into a larger area such as a park. This coding works well for Parks because most parks consist of multiple parcels. This number is assigned by the city. Other cities likely use a similar identifier, but not the same method as Seattle.

## Columns

```ls
| Name         | Field Name   | Data Type | Render Type | Schema Type    | Included | 
| ============ | ============ | ========= | =========== | ============== | ======== | 
| updated_at   | :updated_at  | meta_data | meta_data   | time           | No       | 
| pmaid        | pmaid        | text      | number      | series tag     | Yes      | 
| name         | name         | text      | text        | series tag     | Yes      | 
| feature_desc | feature_desc | text      | text        | series tag     | Yes      | 
| hours        | hours        | text      | text        | series tag     | Yes      | 
| xpos         | xpos         | number    | number      | numeric metric | Yes      | 
| ypos         | ypos         | number    | number      | numeric metric | Yes      | 
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
series e:j9km-ydkc d:2016-03-19T15:28:11.000Z t:pmaid=307 t:feature_desc=Golf t:hours="24 Hours" t:name="Green Lake Park" m:xpos=-122.33039 m:ypos=47.67894

series e:j9km-ydkc d:2016-03-19T15:28:11.000Z t:pmaid=456 t:feature_desc="Restrooms (ADA Compliant)" t:hours="4 a.m. - 11:30 p.m." t:name="Hiawatha Playfield" m:xpos=-122.38496 m:ypos=47.57827

series e:j9km-ydkc d:2016-03-19T15:28:11.000Z t:pmaid=310 t:feature_desc="Basketball (Full)" t:hours="Park Hours: Daily 4 a.m. - 11:30 p.m.
```

## Meta Commands

```ls
metric m:xpos l:xpos t:dataTypeName=number

metric m:ypos l:ypos t:dataTypeName=number

entity e:j9km-ydkc l:"Seattle Parks and Recreation Parks With Features" t:attribution="Seattle Parks and Recreation" t:url=https://data.seattle.gov/api/views/j9km-ydkc

property e:j9km-ydkc t:meta.view d:2017-03-07T18:12:28.058Z v:id=j9km-ydkc v:category="Parks and Recreation" v:attributionLink=http://www.seattle.gov/parks/ v:averageRating=0 v:name="Seattle Parks and Recreation Parks With Features" v:attribution="Seattle Parks and Recreation"

property e:j9km-ydkc t:meta.view.owner d:2017-03-07T18:12:28.058Z v:id=fs78-6jsr v:screenName="Blood, Bruce" v:displayName="Blood, Bruce"

property e:j9km-ydkc t:meta.view.tableauthor d:2017-03-07T18:12:28.058Z v:id=fs78-6jsr v:screenName="Blood, Bruce" v:displayName="Blood, Bruce"
```