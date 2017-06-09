# Conditions Not Covered ( Diagnosis Code Group 6031)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/conditions-not-covered-diagnosis-code-group-6031) |
| Metadata | [Link](https://data.oregon.gov/api/views/btwj-27et) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/btwj-27et/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/btwj-27et/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | btwj-27et |
| Name | Conditions Not Covered ( Diagnosis Code Group 6031) |
| Attribution | Oregon Health Authority |
| Category | Health & Human Services |
| Created | 2016-12-05T22:17:31Z |
| Publication Date | 2017-05-02T18:19:18Z |

## Description

Codes in this group are not on the Prioritized List.  They are conditions that are not covered for reimbursement by OHP's FFS program. For specific coverage information please contact the Provider Services Unit at  1-800-336-6016.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | code           | Code           | text          | text          |
| Yes      | time        | effective_date | Effective Date | calendar_date | calendar_date |
| No       |             | end_date       | End Date       | calendar_date | calendar_date |
| No       |             | file_date      | File Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,file_date
```

## Data Commands

```ls
series e:btwj-27et d:2015-10-01T00:00:00.000Z t:code=K0856 m:row_number.btwj-27et=1

series e:btwj-27et d:2015-10-01T00:00:00.000Z t:code=N4601 m:row_number.btwj-27et=2

series e:btwj-27et d:2015-10-01T00:00:00.000Z t:code=N46021 m:row_number.btwj-27et=3
```

## Meta Commands

```ls
metric m:row_number.btwj-27et p:long l:"Row Number"

entity e:btwj-27et l:"Conditions Not Covered ( Diagnosis Code Group 6031)" t:attribution="Oregon Health Authority" t:url=https://data.oregon.gov/api/views/btwj-27et

property e:btwj-27et t:meta.view d:2017-06-09T13:54:57.864Z v:id=btwj-27et v:category="Health & Human Services" v:attributionLink=http://www.oregon.gov/OHA/healthplan v:averageRating=0 v:name="Conditions Not Covered ( Diagnosis Code Group 6031)" v:attribution="Oregon Health Authority"

property e:btwj-27et t:meta.view.owner d:2017-06-09T13:54:57.864Z v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:lastNotificationSeenAt=1493074868 v:displayName="Kim Witbeck"

property e:btwj-27et t:meta.view.tableauthor d:2017-06-09T13:54:57.864Z v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1493074868 v:displayName="Kim Witbeck"
```

## Top Records

```ls
| code   | effective_date      | end_date            | file_date           | 
| ====== | =================== | =================== | =================== | 
| K0856  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N4601  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46021 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46022 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46023 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46024 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46025 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46029 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N4611  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| N46121 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
```