# Blue Zone (Accessible) Parking

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/t8ay-k3qw/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/blue-zone-accessible-parking)
* Id = t8ay-k3qw
* Name = Blue Zone (Accessible) Parking
* Category = Transportation
* Tags = [accessible parking, blue curb, curb color, parking]
* Created = 2016-02-27T01:33:06Z
* Publication Date = 2016-05-07T23:34:07Z
* Rows Updated = 2017-02-25T17:30:26Z

## Description

Identifes location of blue zones. Was created through SFpark surveys and data creation, 2008-2011.This is not updated regularly. Please note: Drivers with disabled placards can park at any metered space for free and with no time limits; they are not limited to blue zones.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| Object ID        | object_id        | text      | number      | series tag     | Yes      | 
| Address          | address          | text      | text        |                | No       | 
| Cross Street     | cross_street     | text      | text        | series tag     | Yes      | 
| Site Detail      | site_detail      | text      | text        | series tag     | Yes      | 
| Space Length     | space_length     | number    | number      | numeric metric | Yes      | 
| Street Side      | street_side      | text      | text        | series tag     | Yes      | 
| Curb Quality     | curb_quality     | text      | text        | series tag     | Yes      | 
| Meter Post ID    | meter_post_id    | text      | text        | series tag     | Yes      | 
| Last Edited Date | last_edited_date | date      | date        | time           | Yes      | 
```

## Time Field

```ls
Value = last_edited_date
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
series e:t8ay-k3qw d:1996-04-18T00:00:00.000Z t:street_side=E t:site_detail="5' to 23' north of Ellis" t:cross_street=Ellis t:object_id=1 t:curb_quality=good m:space_length=18

series e:t8ay-k3qw d:1994-06-27T00:00:00.000Z t:street_side=W t:site_detail="5' to 27' south of 24th St" t:cross_street="24th St" t:object_id=2 t:curb_quality=good m:space_length=22

series e:t8ay-k3qw d:2017-03-03T13:55:42.339Z t:street_side=E t:site_detail="2' to 27' south of the north property line" t:cross_street="17th St" t:object_id=3 m:space_length=25
```

## Meta Commands

```ls
metric m:space_length p:integer l:"Space Length" t:dataTypeName=number

entity e:t8ay-k3qw l:"Blue Zone (Accessible) Parking" t:url=https://data.sfgov.org/api/views/t8ay-k3qw

property e:t8ay-k3qw t:meta.view d:2017-03-03T13:55:42.339Z v:id=t8ay-k3qw v:category=Transportation v:averageRating=0 v:name="Blue Zone (Accessible) Parking"

property e:t8ay-k3qw t:meta.view.license d:2017-03-03T13:55:42.339Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:t8ay-k3qw t:meta.view.owner d:2017-03-03T13:55:42.339Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:t8ay-k3qw t:meta.view.tableauthor d:2017-03-03T13:55:42.339Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```