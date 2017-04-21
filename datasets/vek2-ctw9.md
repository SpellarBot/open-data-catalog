# 2012 Special April - Election Results (final daily)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/apr17-special-election-results-db88b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vek2-ctw9) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vek2-ctw9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vek2-ctw9/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vek2-ctw9 |
| Name | 2012 Special April - Election Results (final daily) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 special, special, elections, results |
| Created | 2012-04-20T15:40:20Z |
| Publication Date | 2012-04-20T20:05:43Z |

## Description

April 2012 special election; final daily results report.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | jurisdiction | Jurisdiction | text      | text        |
| Yes      | series tag     | measure      | Measure      | text      | text        |
| Yes      | series tag     | option       | Option       | text      | text        |
| Yes      | numeric metric | ballots      | Ballots      | number    | number      |
| Yes      | numeric metric | percent      | Percent      | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vek2-ctw9 d:2012-01-01T00:00:00.000Z t:measure="Proposition No. 1 General, Obligation Bonds - $59,000,000" t:jurisdiction="Auburn Transportation Benefit District" t:option=Yes m:ballots=3918 m:percent=49.04

series e:vek2-ctw9 d:2012-01-01T00:00:00.000Z t:measure="Proposition No. 1 General, Obligation Bonds - $59,000,001" t:jurisdiction="Auburn Transportation Benefit District" t:option=No m:ballots=4072 m:percent=50.96

series e:vek2-ctw9 d:2012-01-01T00:00:00.000Z t:measure="Proposition No. 1" t:jurisdiction="City of Enumclaw" t:option=Yes m:ballots=1185 m:percent=50.53
```

## Meta Commands

```ls
metric m:ballots p:integer l:Ballots t:dataTypeName=number

metric m:percent p:double l:Percent t:dataTypeName=number

entity e:vek2-ctw9 l:"2012 Special April - Election Results (final daily)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/vek2-ctw9

property e:vek2-ctw9 t:meta.view v:id=vek2-ctw9 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2012 Special April - Election Results (final daily)" v:attribution="King County Elections"

property e:vek2-ctw9 t:meta.view.license v:name="Public Domain"

property e:vek2-ctw9 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:vek2-ctw9 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| jurisdiction                           | measure                                                                                               | option   | ballots | percent | 
| ====================================== | ===================================================================================================== | ======== | ======= | ======= | 
| Auburn Transportation Benefit District | Proposition No. 1 General, Obligation Bonds - $59,000,000                                             | Yes      | 3918    | 49.04   | 
| Auburn Transportation Benefit District | Proposition No. 1 General, Obligation Bonds - $59,000,001                                             | No       | 4072    | 50.96   | 
| City of Enumclaw                       | Proposition No. 1                                                                                     | Yes      | 1185    | 50.53   | 
| City of Enumclaw                       | Proposition No. 2                                                                                     | No       | 1160    | 49.47   | 
| Issaquah School District No. 411       | Proposition No. 1 General Obligation Bonds - $219,121,500                                             | Approved | 15566   | 70      | 
| Issaquah School District No. 411       | Proposition No. 1 General Obligation Bonds - $219,121,501                                             | Rejected | 6670    | 30      | 
| Mercer Island School District No. 400  | Proposition No. 1 General Obligation Bonds - $196,275,000                                             | Approved | 3874    | 40.5    | 
| Mercer Island School District No. 400  | Proposition No. 1 General Obligation Bonds - $196,275,001                                             | Rejected | 5691    | 59.5    | 
| Renton School District No. 403         | Proposition No. 1 Building for a Lifetime of Learning School Building Improvement Bonds - $97,000,000 | Approved | 10246   | 60.55   | 
| Renton School District No. 403         | Proposition No. 1 Building for a Lifetime of Learning School Building Improvement Bonds - $97,000,001 | Rejected | 6676    | 39.45   | 
```