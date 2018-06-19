# Health Care Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-care-expenditures-ce9e6) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/impj-6vgn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/impj-6vgn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/impj-6vgn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | impj-6vgn |
| Name | Health Care Expenditures |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, healthcare, budget2013 |
| Created | 2012-09-06T22:23:58Z |
| Publication Date | 2012-09-06T23:29:30Z |

## Description

King County budget healthcare expenditures since 2000. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name | Name         | Data Type | Render Type |
| ======== | ============== | ========== | ============ | ========= | =========== |
| Yes      | time           | year       | Year         | number    | number      |
| Yes      | numeric metric | exp_mill   | Exp. ($mill) | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:impj-6vgn d:2000-01-01T00:00:00.000Z m:exp_mill=86

series e:impj-6vgn d:2001-01-01T00:00:00.000Z m:exp_mill=95

series e:impj-6vgn d:2002-01-01T00:00:00.000Z m:exp_mill=113
```

## Meta Commands

```ls
metric m:exp_mill p:integer l:"Exp. ($mill)" t:dataTypeName=money

entity e:impj-6vgn l:"Health Care Expenditures" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/impj-6vgn

property e:impj-6vgn t:meta.view v:id=impj-6vgn v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget/ v:averageRating=0 v:name="Health Care Expenditures" v:attribution="King County Executive"

property e:impj-6vgn t:meta.view.license v:name="Public Domain"

property e:impj-6vgn t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:impj-6vgn t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| year | exp_mill | 
| ==== | ======== | 
| 2000 | 86       | 
| 2001 | 95       | 
| 2002 | 113      | 
| 2003 | 115      | 
| 2004 | 133      | 
| 2005 | 139      | 
| 2006 | 152      | 
| 2007 | 159      | 
| 2008 | 177      | 
| 2009 | 192      | 
```