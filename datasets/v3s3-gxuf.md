# 2009 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-aug-2009-primary-b21e4) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/v3s3-gxuf) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/v3s3-gxuf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/v3s3-gxuf/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | v3s3-gxuf |
| Name | 2009 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2009, 2009 primary, primary, elections, results, precinct, ecanvass |
| Created | 2010-08-24T05:11:47Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

August 2009 primary election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | race                    | Race                    | text      | text        |
| Yes      | series tag     | precinct                | Precinct                | text      | text        |
| Yes      | series tag     | county_council_district | County Council District | text      | number      |
| Yes      | series tag     | legislative_district    | Legislative District    | text      | number      |
| Yes      | series tag     | congressional_district  | Congressional District  | text      | number      |
| Yes      | series tag     | candidate               | Candidate               | text      | text        |
| Yes      | numeric metric | count                   | Count                   | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v3s3-gxuf d:2009-01-01T00:00:00.000Z t:precinct="AUB 30-1066" t:legislative_district=30 t:county_council_district=7 t:candidate="Registered Voters" t:congressional_district=9 t:race="City of Auburn Mayor" m:count=381

series e:v3s3-gxuf d:2009-01-01T00:00:00.000Z t:precinct="AUB 30-1066" t:legislative_district=30 t:county_council_district=7 t:candidate=Write-in t:congressional_district=9 t:race="City of Auburn Mayor" m:count=1

series e:v3s3-gxuf d:2009-01-01T00:00:00.000Z t:precinct="AUB 30-1066" t:legislative_district=30 t:county_council_district=7 t:candidate="Virginia Haugen" t:congressional_district=9 t:race="City of Auburn Mayor" m:count=51
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:v3s3-gxuf l:"2009 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/v3s3-gxuf

property e:v3s3-gxuf t:meta.view v:id=v3s3-gxuf v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections/results.aspx v:averageRating=50 v:name="2009 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:v3s3-gxuf t:meta.view.license v:name="Public Domain"

property e:v3s3-gxuf t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:v3s3-gxuf t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| race                 | precinct    | county_council_district | legislative_district | congressional_district | candidate         | count | 
| ==================== | =========== | ======================= | ==================== | ====================== | ================= | ===== | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Registered Voters | 381   | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Write-in          | 1     | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Virginia Haugen   | 51    | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Pete Lewis        | 50    | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Frank Lonergan    | 16    | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Shelley Erickson  | 14    | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Times Over Voted  | 0     | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Times Blank Voted | 0     | 
| City of Auburn Mayor | AUB 30-1066 | 7                       | 30                   | 9                      | Times Counted     | 132   | 
| City of Auburn Mayor | AUB 30-2573 | 7                       | 30                   | 9                      | Registered Voters | 637   | 
```