# Informational Diagnosis Codes ( Diagnosis Code Group 6033)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/informational-diagnosis-codes-diagnosis-code-group-6033) |
| Metadata | [Link](https://data.oregon.gov/api/views/fn3v-gen9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fn3v-gen9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fn3v-gen9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fn3v-gen9 |
| Name | Informational Diagnosis Codes ( Diagnosis Code Group 6033) |
| Attribution | Oregon Health Authority |
| Category | Health & Human Services |
| Created | 2016-12-05T22:29:14Z |
| Publication Date | 2016-12-06T00:11:42Z |

## Description

Codes in this group are not on the Prioritized List. They are considered informational only. They may be needed for reporting purposes but they are not eligible for reimbursement by OHP's FFS program. For specific coverage information please contact the Provider Services Unit at  1-800-336-6016.

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
series e:fn3v-gen9 d:2015-10-01T00:00:00.000Z t:code=B900 m:row_number.fn3v-gen9=1

series e:fn3v-gen9 d:2015-10-01T00:00:00.000Z t:code=B901 m:row_number.fn3v-gen9=2

series e:fn3v-gen9 d:2015-10-01T00:00:00.000Z t:code=B902 m:row_number.fn3v-gen9=3
```

## Meta Commands

```ls
metric m:row_number.fn3v-gen9 p:long l:"Row Number"

entity e:fn3v-gen9 l:"Informational Diagnosis Codes ( Diagnosis Code Group 6033)" t:attribution="Oregon Health Authority" t:url=https://data.oregon.gov/api/views/fn3v-gen9

property e:fn3v-gen9 t:meta.view v:id=fn3v-gen9 v:category="Health & Human Services" v:attributionLink=http://www.oregon.gov/OHA/healthplan v:averageRating=0 v:name="Informational Diagnosis Codes ( Diagnosis Code Group 6033)" v:attribution="Oregon Health Authority"

property e:fn3v-gen9 t:meta.view.owner v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:displayName="Kim Witbeck"

property e:fn3v-gen9 t:meta.view.tableauthor v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:roleName=editor v:displayName="Kim Witbeck"
```

## Top Records

```ls
| code | effective_date      | end_date            | file_date           | 
| ==== | =================== | =================== | =================== | 
| B900 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B901 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B902 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B908 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B909 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B91  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B92  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B940 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B941 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| B942 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
```