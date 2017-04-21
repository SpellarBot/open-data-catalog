# City of Frederick Issued Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-frederick-issued-permits-08c1f) |
| Metadata | [Link](https://data.maryland.gov/api/views/xrz3-9xhj) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xrz3-9xhj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xrz3-9xhj/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xrz3-9xhj |
| Name | City of Frederick Issued Permits |
| Attribution | City of Frederick |
| Category | Administrative |
| Tags | building permits |
| Created | 2014-06-05T14:01:28Z |
| Publication Date | 2014-06-06T15:11:30Z |

## Description

This dataset includes all issued permits by the City of Frederick from 1/1/12 to 6/6/14

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | permit_no      | Permit No      | text          | text          |
| Yes      | series tag     | classification | Classification | text          | text          |
| Yes      | time           | issue_date     | Issue Date     | calendar_date | calendar_date |
| Yes      | series tag     | parcel         | Parcel         | text          | text          |
| Yes      | series tag     | owner          | Owner          | text          | text          |
| Yes      | series tag     | contractor     | Contractor     | text          | text          |
| Yes      | numeric metric | valuation      | Valuation      | money         | money         |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:valuation p:double l:Valuation t:dataTypeName=money

entity e:xrz3-9xhj l:"City of Frederick Issued Permits" t:attribution="City of Frederick" t:url=https://data.maryland.gov/api/views/xrz3-9xhj

property e:xrz3-9xhj t:meta.view v:id=xrz3-9xhj v:category=Administrative v:averageRating=0 v:name="City of Frederick Issued Permits" v:attribution="City of Frederick"

property e:xrz3-9xhj t:meta.view.owner v:id=qfp5-ru6q v:screenName=spiresgis v:displayName=spiresgis

property e:xrz3-9xhj t:meta.view.tableauthor v:id=qfp5-ru6q v:screenName=spiresgis v:roleName=editor v:displayName=spiresgis
```

## Top Records

```ls
| permit_no      | classification                  | issue_date          | parcel       | owner                      | contractor         | valuation | 
| ============== | =============================== | =================== | ============ | ========================== | ================== | ========= | 
| BP-09-00182-03 | ELECTRICAL COMMERCIAL           | 2012-03-15T00:00:00 | 1102046164-- | FREDERICK COUNTY BOCC      | Pastor, Richard J. |           | 
| BP-09-00213-01 | P004 PLUMBING RESIDENTIAL       | 2012-02-29T00:00:00 | 1102122529-- | COVERED ASSETS, LLC        | Yonetz, James      |           | 
| BP-09-00213-02 | ELECTRICAL RESIDENTIAL          | 2012-03-08T00:00:00 | 1102122529-- | COVERED ASSETS, LLC        | ALLAN KEYSER       |           | 
| BP-09-00236-01 | P004 PLUMBING RESIDENTIAL       | 2012-05-04T00:00:00 | 1102098733-- | CASSIDY, ROBERT J & RUTH B | Klipp, David       |           | 
| BP-09-00236-02 | ELECTRICAL RESIDENTIAL          | 2012-05-14T00:00:00 | 1102098733-- | CASSIDY, ROBERT J & RUTH B |                    |           | 
| BP-09-00492-01 | UTILITY PERMIT                  | 2013-01-03T00:00:00 | 1102218577-- | 111 EAST SOUTH ST LLC      | DONNIE POOLE JR    |           | 
| BP-09-00492-02 | ELECTRICAL COMMERCIAL           | 2013-01-16T00:00:00 | 1102218577-- | 111 EAST SOUTH ST LLC      | Beveridge, Carl H. |           | 
| BP-09-00492-03 | FPS04 FIRE ALARM /DETECT SYSTEM | 2013-03-01T00:00:00 | 1102218577-- | 111 EAST SOUTH ST LLC      | Beveridge, Carl H. |           | 
| BP-09-00492-04 | P001 PLUMBING COMMERCIAL        | 2013-03-01T00:00:00 | 1102218577-- | 111 EAST SOUTH ST LLC      | Waltz, Robert F.   |           | 
| BP-09-00492-05 | GAS COMMERCIAL                  | 2013-03-01T00:00:00 | 1102218577-- | 111 EAST SOUTH ST LLC      | Waltz, Robert F.   |           | 
```