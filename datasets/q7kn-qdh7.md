# Ballot Tracker visits Oct-Nov 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ballot-tracker-visits-oct-nov-2012-f1317) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/q7kn-qdh7) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/q7kn-qdh7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/q7kn-qdh7/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | q7kn-qdh7 |
| Name | Ballot Tracker visits Oct-Nov 2012 |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | election, 201211 |
| Created | 2013-01-18T00:56:13Z |
| Publication Date | 2013-01-18T01:09:38Z |

## Description

Ballot tracker page visits for the November 2012 general election

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | time           | date        | Date        | calendar_date | calendar_date |
| Yes      | numeric metric | page_visits | Page visits | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:q7kn-qdh7 d:2012-10-01T00:00:00.000Z m:page_visits=222

series e:q7kn-qdh7 d:2012-10-02T00:00:00.000Z m:page_visits=432

series e:q7kn-qdh7 d:2012-10-03T00:00:00.000Z m:page_visits=237
```

## Meta Commands

```ls
metric m:page_visits p:integer l:"Page visits" t:dataTypeName=number

entity e:q7kn-qdh7 l:"Ballot Tracker visits Oct-Nov 2012" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/q7kn-qdh7

property e:q7kn-qdh7 t:meta.view v:id=q7kn-qdh7 v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="Ballot Tracker visits Oct-Nov 2012" v:attribution="King County Elections"

property e:q7kn-qdh7 t:meta.view.license v:name="Public Domain"

property e:q7kn-qdh7 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:q7kn-qdh7 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| date                | page_visits | 
| =================== | =========== | 
| 2012-10-01T00:00:00 | 222         | 
| 2012-10-02T00:00:00 | 432         | 
| 2012-10-03T00:00:00 | 237         | 
| 2012-10-04T00:00:00 | 115         | 
| 2012-10-05T00:00:00 | 579         | 
| 2012-10-06T00:00:00 | 580         | 
| 2012-10-07T00:00:00 | 116         | 
| 2012-10-08T00:00:00 | 201         | 
| 2012-10-09T00:00:00 | 202         | 
| 2012-10-10T00:00:00 | 181         | 
```