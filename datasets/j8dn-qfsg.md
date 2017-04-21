# Closure Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/closure-data) |
| Metadata | [Link](https://data.oregon.gov/api/views/j8dn-qfsg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/j8dn-qfsg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/j8dn-qfsg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | j8dn-qfsg |
| Name | Closure Data |
| Category | Administrative |
| Tags | secretary of state, office closure |
| Created | 2015-10-28T16:24:20Z |
| Publication Date | 2016-11-16T19:31:37Z |

## Description

Secretary of State offices closed

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | time        | date        | Date        | calendar_date | calendar_date |
| Yes      | series tag  | description | Description | text          | text          |
| Yes      | series tag  | details     | Details     | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:j8dn-qfsg d:2015-01-01T00:00:00.000Z t:details="State offices closed" t:description="New Year's Day" m:row_number.j8dn-qfsg=1

series e:j8dn-qfsg d:2015-02-16T00:00:00.000Z t:details="State offices closed" t:description="Presidents Day" m:row_number.j8dn-qfsg=2

series e:j8dn-qfsg d:2015-05-25T00:00:00.000Z t:details="State offices closed" t:description="Memorial Day" m:row_number.j8dn-qfsg=3
```

## Meta Commands

```ls
metric m:row_number.j8dn-qfsg p:long l:"Row Number"

entity e:j8dn-qfsg l:"Closure Data" t:url=https://data.oregon.gov/api/views/j8dn-qfsg

property e:j8dn-qfsg t:meta.view v:id=j8dn-qfsg v:category=Administrative v:averageRating=0 v:name="Closure Data"

property e:j8dn-qfsg t:meta.view.owner v:id=ibb7-gbfs v:profileImageUrlMedium=/api/users/ibb7-gbfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/ibb7-gbfs/profile_images/LARGE v:screenName="Secretary of State Open Data Admin" v:profileImageUrlSmall=/api/users/ibb7-gbfs/profile_images/TINY v:displayName="Secretary of State Open Data Admin"

property e:j8dn-qfsg t:meta.view.tableauthor v:id=ibb7-gbfs v:profileImageUrlMedium=/api/users/ibb7-gbfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/ibb7-gbfs/profile_images/LARGE v:screenName="Secretary of State Open Data Admin" v:profileImageUrlSmall=/api/users/ibb7-gbfs/profile_images/TINY v:roleName=editor v:displayName="Secretary of State Open Data Admin"
```

## Top Records

```ls
| date                | description                | details              | 
| =================== | ========================== | ==================== | 
| 2015-01-01T00:00:00 | New Year's Day             | State offices closed | 
| 2015-02-16T00:00:00 | Presidents Day             | State offices closed | 
| 2015-05-25T00:00:00 | Memorial Day               | State offices closed | 
| 2015-07-03T00:00:00 | Independence Day observed  | State offices closed | 
| 2015-09-07T00:00:00 | Labor Day                  | State offices closed | 
| 2015-11-11T00:00:00 | Veterans Day               | State offices closed | 
| 2015-11-26T00:00:00 | Thanksgiving Day           | State offices closed | 
| 2015-11-27T00:00:00 | The day after Thanksgiving | State offices closed | 
| 2015-12-25T00:00:00 | Christmas Day              | State offices closed | 
| 2016-01-01T00:00:00 | New Year's Day             | State offices closed | 
```