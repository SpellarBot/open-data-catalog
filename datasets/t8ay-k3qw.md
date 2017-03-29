# Blue Zone (Accessible) Parking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/blue-zone-accessible-parking) |
| Metadata | [Link](https://data.sfgov.org/api/views/t8ay-k3qw) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/t8ay-k3qw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/t8ay-k3qw/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | t8ay-k3qw |
| Name | Blue Zone (Accessible) Parking |
| Category | Transportation |
| Tags | accessible parking, blue curb, curb color, parking |
| Created | 2016-02-27T01:33:06Z |
| Publication Date | 2016-05-07T23:34:07Z |

## Description

Identifes location of blue zones. Was created through SFpark surveys and data creation, 2008-2011.This is not updated regularly. Please note: Drivers with disabled placards can park at any metered space for free and with no time limits; they are not limited to blue zones.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| No       |                | address          | Address          | text      | text        |
| Yes      | series tag     | cross_street     | Cross Street     | text      | text        |
| Yes      | series tag     | site_detail      | Site Detail      | text      | text        |
| Yes      | numeric metric | space_length     | Space Length     | number    | number      |
| Yes      | series tag     | street_side      | Street Side      | text      | text        |
| Yes      | series tag     | curb_quality     | Curb Quality     | text      | text        |
| Yes      | series tag     | meter_post_id    | Meter Post ID    | text      | text        |
| Yes      | time           | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:t8ay-k3qw d:1996-04-18T00:00:00.000Z t:street_side=E t:site_detail="5' to 23' north of Ellis" t:cross_street=Ellis t:object_id=1 t:curb_quality=good m:space_length=18

series e:t8ay-k3qw d:1994-06-27T00:00:00.000Z t:street_side=W t:site_detail="5' to 27' south of 24th St" t:cross_street="24th St" t:object_id=2 t:curb_quality=good m:space_length=22

series e:t8ay-k3qw d:2017-03-25T16:30:18.000Z t:street_side=E t:site_detail="2' to 27' south of the north property line" t:cross_street="17th St" t:object_id=3 m:space_length=25
```

## Meta Commands

```ls
metric m:space_length p:integer l:"Space Length" t:dataTypeName=number

entity e:t8ay-k3qw l:"Blue Zone (Accessible) Parking" t:url=https://data.sfgov.org/api/views/t8ay-k3qw

property e:t8ay-k3qw t:meta.view v:id=t8ay-k3qw v:category=Transportation v:averageRating=0 v:name="Blue Zone (Accessible) Parking"

property e:t8ay-k3qw t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:t8ay-k3qw t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:t8ay-k3qw t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | address          | cross_street | site_detail                                | space_length | street_side | curb_quality | meter_post_id | last_edited_date | 
| ========= | ================ | ============ | ========================================== | ============ | =========== | ============ | ============= | ================ | 
| 1         | 1400 Fillmore St | Ellis        | 5' to 23' north of Ellis                   | 18           | E           | good         |               | 829785600        | 
| 2         | 1200 Florida St  | 24th St      | 5' to 27' south of 24th St                 | 22           | W           | good         |               | 772675200        | 
| 3         | 2075 Folsom St   | 17th St      | 2' to 27' south of the north property line | 25           | E           |              |               |                  | 
| 4         | 200 Folsom St    | Main         | 96' to 116' west of Main                   | 20           | N           |              |               |                  | 
| 5         | 50 California St | Davis        | 37' to 66' east of Davis                   | 29           | N           | good         |               | 871603200        | 
| 6         | 1199 Clement St  | Funston      | 0' to 19' east of Funston                  | 19           | S           | good         |               | 839462400        | 
| 7         | 560 Davis St     | Jackson      | 6' to 28' north of Jackson                 | 22           | E           | good         |               | 863049600        | 
| 8         | 2800 Folsom St   | 24th St      | 8' to 30' south of 24th St                 | 22           | W           | poor         |               | 772675200        | 
| 9         | 633 Folsom St    | Hawthorne    | 6' to 28' east of Hawthorne                | 22           | S           | good         |               | 804470400        | 
| 10        | 700 Font Blvd    | Tapia        | 5' to 71' west of Tapia                    | 66           | N           | good         |               |                  | 
```