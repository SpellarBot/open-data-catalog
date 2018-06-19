# Oregon Elections Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-elections-calendar) |
| Metadata | [Link](https://data.oregon.gov/api/views/i8qc-cakg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/i8qc-cakg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/i8qc-cakg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | i8qc-cakg |
| Name | Oregon Elections Calendar |
| Category | Administrative |
| Tags | election, elections, secretary of state, voting, vote |
| Created | 2015-10-07T18:31:56Z |
| Publication Date | 2017-01-30T22:02:07Z |

## Description

Calendar of important elections dates and deadlines provided by the Oregon Secretary of State.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | time        | date                 | Date                 | calendar_date | calendar_date |
| Yes      | series tag  | description_of_event | Description of Event | text          | text          |
| Yes      | series tag  | reference            | Reference            | text          | text          |
| No       |             | end_date             | End Date             | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:i8qc-cakg d:2016-01-01T00:00:00.000Z t:description_of_event="New Year's Day" t:reference="Secretary of State offices closed" m:row_number.i8qc-cakg=1

series e:i8qc-cakg d:2016-01-03T00:00:00.000Z t:description_of_event="Last day to mail district board member update form by certified mail to district elections authority." t:reference=255.06899999999899 m:row_number.i8qc-cakg=2

series e:i8qc-cakg d:2016-01-07T00:00:00.000Z t:description_of_event="Last day to inactivate voters for non-voting or failure to update." t:reference=247.01300000000001 m:row_number.i8qc-cakg=3
```

## Meta Commands

```ls
metric m:row_number.i8qc-cakg p:long l:"Row Number"

entity e:i8qc-cakg l:"Oregon Elections Calendar" t:url=https://data.oregon.gov/api/views/i8qc-cakg

property e:i8qc-cakg t:meta.view v:id=i8qc-cakg v:category=Administrative v:attributionLink=http://sos.oregon.gov/Pages/default.aspx v:averageRating=0 v:name="Oregon Elections Calendar"

property e:i8qc-cakg t:meta.view.owner v:id=ibb7-gbfs v:profileImageUrlMedium=/api/users/ibb7-gbfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/ibb7-gbfs/profile_images/LARGE v:screenName="Secretary of State Open Data Admin" v:profileImageUrlSmall=/api/users/ibb7-gbfs/profile_images/TINY v:displayName="Secretary of State Open Data Admin"

property e:i8qc-cakg t:meta.view.tableauthor v:id=ibb7-gbfs v:profileImageUrlMedium=/api/users/ibb7-gbfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/ibb7-gbfs/profile_images/LARGE v:screenName="Secretary of State Open Data Admin" v:profileImageUrlSmall=/api/users/ibb7-gbfs/profile_images/TINY v:roleName=editor v:displayName="Secretary of State Open Data Admin"
```

## Top Records

```ls
| date                | description_of_event                                                                                                            | reference                         | end_date            | 
| =================== | =============================================================================================================================== | ================================= | =================== | 
| 2016-01-01T00:00:00 | New Year's Day                                                                                                                  | Secretary of State offices closed | 2015-01-01T00:00:00 | 
| 2016-01-03T00:00:00 | Last day to mail district board member update form by certified mail to district elections authority.                           | 255.06899999999899                | 2015-01-03T00:00:00 | 
| 2016-01-07T00:00:00 | Last day to inactivate voters for non-voting or failure to update.                                                              | 247.01300000000001                | 2015-01-07T00:00:00 | 
| 2016-01-07T00:00:00 | Last day for city elections official, county governing body or district elections authority to file notice of measure election. | 254.095; 254.103; 255.085         | 2015-01-07T00:00:00 | 
| 2016-01-07T00:00:00 | Last day for governing body to file explanatory statement if county will publish voters' pamphlet.                              | OAR 165-022-0010                  | 2015-01-07T00:00:00 | 
| 2016-01-11T00:00:00 | Last day to file measure arguments for county voters' pamphlet.                                                                 | OAR 165-022-0010                  | 2015-01-11T00:00:00 | 
| 2016-01-11T00:00:00 | Last day to file candidate statements for county voters' pamphlet.                                                              | OAR 165-022-0010                  | 2015-01-11T00:00:00 | 
| 2016-01-13T00:00:00 | Last day for district elections authority to return board member updates.                                                       | 255.06899999999899                | 2015-01-13T00:00:00 | 
| 2016-01-15T00:00:00 | State initiative petition monthly submission.                                                                                   | 250.104999999999                  | 2015-01-15T00:00:00 | 
| 2016-01-15T00:00:00 | Material submitted for county voters' pamphlet available for public inspection.                                                 | 251.43                            | 2015-01-15T00:00:00 | 
```