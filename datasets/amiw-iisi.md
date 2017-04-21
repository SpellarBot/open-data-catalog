# Street Segment and Intersection (CNN) Change Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cnn-changes-d3254) |
| Metadata | [Link](https://data.sfgov.org/api/views/amiw-iisi) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/amiw-iisi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/amiw-iisi/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | amiw-iisi |
| Name | Street Segment and Intersection (CNN) Change Log |
| Attribution | San Francisco Department of Public Works |
| Category | Geographic Locations and Boundaries |
| Tags | cnn, base, map, basemap, street, segment |
| Created | 2014-01-23T06:44:27Z |
| Publication Date | 2015-07-17T15:03:05Z |

## Description

A list of Street Segment and Intersection (CNN) changes including new, dropped, realigned, divided and split records.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | changeid     | CHANGEID     | text          | text          |
| Yes      | numeric metric | oldcnn       | OldCNN       | number        | number        |
| Yes      | numeric metric | newcnn       | NewCNN       | number        | number        |
| Yes      | time           | dateofupdate | DateOfUpdate | calendar_date | calendar_date |
| Yes      | series tag     | changetype   | ChangeType   | text          | text          |
```

## Time Field

```ls
Value = dateofupdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:amiw-iisi d:2008-10-09T00:00:00.000Z t:changeid=2008-013 t:changetype=Add m:newcnn=15145000 m:oldcnn=0

series e:amiw-iisi d:2008-10-09T00:00:00.000Z t:changeid=2008-013 t:changetype=Add m:newcnn=54223000 m:oldcnn=0

series e:amiw-iisi d:2008-11-05T00:00:00.000Z t:changeid=2008-015 t:changetype=Break/Flip m:newcnn=11305001 m:oldcnn=11305000
```

## Meta Commands

```ls
metric m:oldcnn p:integer l:OldCNN t:dataTypeName=number

metric m:newcnn p:integer l:NewCNN t:dataTypeName=number

entity e:amiw-iisi l:"Street Segment and Intersection (CNN) Change Log" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/amiw-iisi

property e:amiw-iisi t:meta.view v:id=amiw-iisi v:category="Geographic Locations and Boundaries" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Street Segment and Intersection (CNN) Change Log" v:attribution="San Francisco Department of Public Works"

property e:amiw-iisi t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:amiw-iisi t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:amiw-iisi t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| changeid | oldcnn   | newcnn   | dateofupdate        | changetype   | 
| ======== | ======== | ======== | =================== | ============ | 
| 2008-013 | 0        | 15145000 | 2008-10-09T00:00:00 | Add          | 
| 2008-013 | 0        | 54223000 | 2008-10-09T00:00:00 | Add          | 
| 2008-015 | 11305000 | 11305001 | 2008-11-05T00:00:00 | Break/Flip   | 
| 2008-015 | 11305000 | 11305002 | 2008-11-05T00:00:00 | Break/Flip   | 
| 2008-015 | 0        | 54224000 | 2008-11-05T00:00:00 | Break/Flip   | 
| 2010-004 | 0        | 35015000 | 2010-06-24T00:00:00 | Add          | 
| 2010-004 | 0        | 13798000 | 2010-06-24T00:00:00 | Add          | 
| 2010-005 | 13576000 | 13576001 | 2010-10-04T00:00:00 | Drop/Shorten | 
| 2010-005 | 0        | 54225000 | 2010-10-04T00:00:00 | Drop/Shorten | 
| 2010-005 | 5389000  | 0        | 2010-10-04T00:00:00 | Drop/Shorten | 
```