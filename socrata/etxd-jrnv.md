# Diagnostic Workup File ( Code Group 6032)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/diagnostic-workup-file-code-group-6032) |
| Metadata | [Link](https://data.oregon.gov/api/views/etxd-jrnv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/etxd-jrnv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/etxd-jrnv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | etxd-jrnv |
| Name | Diagnostic Workup File ( Code Group 6032) |
| Attribution | Oregon Health Authority |
| Category | Health & Human Services |
| Created | 2016-12-05T22:22:48Z |
| Publication Date | 2016-12-05T23:27:59Z |

## Description

Codes in this group do not appear on the Prioritized List; however, they are covered by OHP's FFS program when billed with a procedure code from OHP's Diagnostic Procedures code group (Code Group 1119).

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
series e:etxd-jrnv d:2015-10-01T00:00:00.000Z t:code=D490 m:row_number.etxd-jrnv=1

series e:etxd-jrnv d:2015-10-01T00:00:00.000Z t:code=D491 m:row_number.etxd-jrnv=2

series e:etxd-jrnv d:2015-10-01T00:00:00.000Z t:code=D492 m:row_number.etxd-jrnv=3
```

## Meta Commands

```ls
metric m:row_number.etxd-jrnv p:long l:"Row Number"

entity e:etxd-jrnv l:"Diagnostic Workup File ( Code Group 6032)" t:attribution="Oregon Health Authority" t:url=https://data.oregon.gov/api/views/etxd-jrnv

property e:etxd-jrnv t:meta.view v:id=etxd-jrnv v:category="Health & Human Services" v:attributionLink=http://www.oregon.gov/OHA/healthplan v:averageRating=0 v:name="Diagnostic Workup File ( Code Group 6032)" v:attribution="Oregon Health Authority"

property e:etxd-jrnv t:meta.view.owner v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:displayName="Kim Witbeck"

property e:etxd-jrnv t:meta.view.tableauthor v:id=mx6a-id83 v:profileImageUrlMedium=/api/users/mx6a-id83/profile_images/THUMB v:profileImageUrlLarge=/api/users/mx6a-id83/profile_images/LARGE v:screenName="Kim Witbeck" v:profileImageUrlSmall=/api/users/mx6a-id83/profile_images/TINY v:roleName=editor v:displayName="Kim Witbeck"
```

## Top Records

```ls
| code  | effective_date      | end_date            | file_date           | 
| ===== | =================== | =================== | =================== | 
| D490  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D491  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D492  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D493  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D494  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D495  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D496  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D497  | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D4981 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
| D4989 | 2015-10-01T00:00:00 | 2299-12-31T00:00:00 | 2016-03-31T00:00:00 | 
```