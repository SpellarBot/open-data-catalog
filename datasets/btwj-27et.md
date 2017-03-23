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
| Publication Date | 2016-12-05T23:31:32Z |
| Rows Updated | 2016-12-05T23:29:36Z |

## Description

Codes in this group are not on the Prioritized List.  They are conditions that are not covered for reimbursement by OHP's FFS program. For specific coverage information please contact the Provider Services Unit at  1-800-336-6016.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type   |
| ======== | =========== | ============== | ============== | ========= | ============= |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data     |
| Yes      | series tag  | code           | Code           | text      | text          |
| No       |             | effective_date | Effective Date | text      | calendar_date |
| No       |             | end_date       | End Date       | text      | calendar_date |
| No       |             | file_date      | File Date      | text      | calendar_date |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_date,end_date,file_date
```

## Data Commands

```ls
series e:btwj-27et d:2016-12-05T22:17:34.000Z t:code=K0856 m:row_number.btwj-27et=1

series e:btwj-27et d:2016-12-05T22:17:34.000Z t:code=N4601 m:row_number.btwj-27et=2

series e:btwj-27et d:2016-12-05T22:17:34.000Z t:code=N46021 m:row_number.btwj-27et=3
```

## Meta Commands

```ls
metric m:row_number.btwj-27et p:long l:"Row Number"

entity e:btwj-27et l:"Conditions Not Covered ( Diagnosis Code Group 6031)" t:attribution="Oregon Health Authority" t:url=https://data.oregon.gov/api/views/btwj-27et

property e:btwj-27et t:meta.view v:id=btwj-27et v:category="Health & Human Services" v:attributionLink=http://www.oregon.gov/OHA/healthplan v:averageRating=0 v:name="Conditions Not Covered ( Diagnosis Code Group 6031)" v:attribution="Oregon Health Authority"

property e:btwj-27et t:meta.view.owner v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:displayName="Kim Witbeck"

property e:btwj-27et t:meta.view.tableauthor v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:roleName=editor v:displayName="Kim Witbeck"
```