# Undefined Diagnosis Codes (Diagnosis Code Group 6030)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/undefined-diagnosis-codes-diagnosis-code-group-6030) |
| Metadata | [Link](https://data.oregon.gov/api/views/wi4n-ban3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wi4n-ban3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wi4n-ban3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wi4n-ban3 |
| Name | Undefined Diagnosis Codes (Diagnosis Code Group 6030) |
| Attribution | Oregon Health Authority |
| Category | Health & Human Services |
| Created | 2016-12-05T22:05:05Z |
| Publication Date | 2016-12-05T23:34:35Z |

## Description

Codes in this group are not on the Prioritized List.  They are not specific enough for OHP to determine coverage.  As such they are not eligible for reimbursement by OHP's FFS program. Providers are directed to bill with a more definitive diagnosis code. This list does not guarantee coverage.  For specific coverage information please contact the Provider Services Unit at  1-800-336-6016.

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
series e:wi4n-ban3 d:2015-10-01T00:00:00.000Z t:code=A0220 m:row_number.wi4n-ban3=1

series e:wi4n-ban3 d:2015-10-01T00:00:00.000Z t:code=A399 m:row_number.wi4n-ban3=2

series e:wi4n-ban3 d:2015-10-01T00:00:00.000Z t:code=A488 m:row_number.wi4n-ban3=3
```

## Meta Commands

```ls
metric m:row_number.wi4n-ban3 p:long l:"Row Number"

entity e:wi4n-ban3 l:"Undefined Diagnosis Codes (Diagnosis Code Group 6030)" t:attribution="Oregon Health Authority" t:url=https://data.oregon.gov/api/views/wi4n-ban3

property e:wi4n-ban3 t:meta.view v:id=wi4n-ban3 v:category="Health & Human Services" v:attributionLink=http://www.oregon.gov/OHA/healthplan v:averageRating=0 v:name="Undefined Diagnosis Codes (Diagnosis Code Group 6030)" v:attribution="Oregon Health Authority"

property e:wi4n-ban3 t:meta.view.owner v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:displayName="Kim Witbeck"

property e:wi4n-ban3 t:meta.view.tableauthor v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:roleName=editor v:displayName="Kim Witbeck"
```

## Top Records

```ls
| code  | effective_date      | end_date            | file_date           | 
| ===== | =================== | =================== | =================== | 
| A0220 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A399  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A488  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A4901 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A4902 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A491  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A492  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A493  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A498  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| A499  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
```