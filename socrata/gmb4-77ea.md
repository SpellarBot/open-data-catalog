# Diagnostic Procedure Codes ( Procedure Group 1119)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/diagnostic-procedure-codes-procedure-group-1119) |
| Metadata | [Link](https://data.oregon.gov/api/views/gmb4-77ea) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/gmb4-77ea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/gmb4-77ea/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | gmb4-77ea |
| Name | Diagnostic Procedure Codes ( Procedure Group 1119) |
| Attribution | Oregon Health Authority |
| Category | Health & Human Services |
| Created | 2016-12-05T21:52:19Z |
| Publication Date | 2016-12-05T23:44:42Z |

## Description

Most codes in this group do not appear on the Prioritized List of Health Services; however, they are covered when billed with a diagnosis code from OHP's Diagnostic Workup File (Code Group 6032).  This list does not guarantee coverage. For specific coverage information, call the Provider Services Unit at 1-800-336-6016.

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
series e:gmb4-77ea d:2002-01-01T00:00:00.000Z t:code=10021 m:row_number.gmb4-77ea=1

series e:gmb4-77ea d:2002-01-01T00:00:00.000Z t:code=10022 m:row_number.gmb4-77ea=2

series e:gmb4-77ea d:2015-01-01T00:00:00.000Z t:code=10035 m:row_number.gmb4-77ea=3
```

## Meta Commands

```ls
metric m:row_number.gmb4-77ea p:long l:"Row Number"

entity e:gmb4-77ea l:"Diagnostic Procedure Codes ( Procedure Group 1119)" t:attribution="Oregon Health Authority" t:url=https://data.oregon.gov/api/views/gmb4-77ea

property e:gmb4-77ea t:meta.view v:id=gmb4-77ea v:category="Health & Human Services" v:attributionLink=http://www.oregon.gov/OHA/healthplan v:averageRating=0 v:name="Diagnostic Procedure Codes ( Procedure Group 1119)" v:attribution="Oregon Health Authority"

property e:gmb4-77ea t:meta.view.owner v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:displayName="Kim Witbeck"

property e:gmb4-77ea t:meta.view.tableauthor v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:roleName=editor v:displayName="Kim Witbeck"
```

## Top Records

```ls
| code  | effective_date      | end_date            | file_date           | 
| ===== | =================== | =================== | =================== | 
| 10021 | 2002-01-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 10022 | 2002-01-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 10035 | 2015-01-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 10036 | 2015-01-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 11100 | 1994-02-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 11101 | 1994-02-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 15860 | 2001-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 19030 | 1996-12-15T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 19081 | 2014-01-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| 19082 | 2014-01-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
```