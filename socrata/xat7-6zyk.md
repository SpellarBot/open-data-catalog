# Fire Response Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-response-data) |
| Metadata | [Link](https://data.srcity.org/api/views/xat7-6zyk) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/xat7-6zyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/xat7-6zyk/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | xat7-6zyk |
| Name | Fire Response Data |
| Category | Fire |
| Created | 2016-02-18T22:59:12Z |
| Publication Date | 2016-02-18T23:30:02Z |

## Description

Fire Department Responses since 1-1-2014

## Columns

```ls
| Included | Schema Type | Field Name       | Name              | Data Type     | Render Type   |
| ======== | =========== | ================ | ================= | ============= | ============= |
| Yes      | time        | alarmdate        | Date of Response  | calendar_date | calendar_date |
| Yes      | series tag  | incidentcategory | Type of Response  | text          | text          |
| Yes      | series tag  | district         | Response District | text          | number        |
| Yes      | series tag  | shift            | shift             | text          | text          |
```

## Time Field

```ls
Value = alarmdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xat7-6zyk d:2014-01-01T00:31:00.000Z t:incidentcategory=Medical t:district=7108 t:shift=C m:row_number.xat7-6zyk=1

series e:xat7-6zyk d:2014-01-01T00:51:00.000Z t:incidentcategory=Medical t:district=7102 t:shift=C m:row_number.xat7-6zyk=2

series e:xat7-6zyk d:2014-01-01T01:05:00.000Z t:incidentcategory=Medical t:district=7101 t:shift=C m:row_number.xat7-6zyk=3
```

## Meta Commands

```ls
metric m:row_number.xat7-6zyk p:long l:"Row Number"

entity e:xat7-6zyk l:"Fire Response Data" t:url=https://data.srcity.org/api/views/xat7-6zyk

property e:xat7-6zyk t:meta.view v:id=xat7-6zyk v:category=Fire v:averageRating=0 v:name="Fire Response Data"

property e:xat7-6zyk t:meta.view.owner v:id=jizs-3xc2 v:screenName="Reese, Jackie" v:displayName="Reese, Jackie"

property e:xat7-6zyk t:meta.view.tableauthor v:id=jizs-3xc2 v:screenName="Reese, Jackie" v:roleName=publisher v:displayName="Reese, Jackie"
```

## Top Records

```ls
| alarmdate           | incidentcategory | district | shift | 
| =================== | ================ | ======== | ===== | 
| 2014-01-01T00:31:00 | Medical          | 7108     | C     | 
| 2014-01-01T00:51:00 | Medical          | 7102     | C     | 
| 2014-01-01T01:05:00 | Medical          | 7101     | C     | 
| 2014-01-01T06:45:00 | Medical          | 7105     | C     | 
| 2014-01-01T07:51:00 | Medical          | 7101     | C     | 
| 2014-01-01T11:02:00 | Medical          | 7103     | C     | 
| 2014-01-01T11:17:00 | Medical          | 7102     | C     | 
| 2014-01-01T13:58:00 | Medical          | 7104     | C     | 
| 2014-01-01T14:11:00 | Medical          | 7102     | C     | 
| 2014-01-01T15:36:00 | Medical          | 7104     | C     | 
```