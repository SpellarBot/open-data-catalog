# Public Meeting Task Force on School Safety

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-meeting-task-force-on-school-safety-acbb3) |
| Metadata | [Link](https://data.oregon.gov/api/views/5tb6-7zmc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5tb6-7zmc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5tb6-7zmc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5tb6-7zmc |
| Name | Public Meeting Task Force on School Safety |
| Category | Public Safety |
| Tags | task force, school, safety, state, police, education, governors |
| Created | 2014-08-07T17:56:55Z |
| Publication Date | 2017-02-09T19:04:00Z |

## Description

This is the public meeting calendar for the Task Force on School Safety

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | time        | date         | Start Date   | calendar_date | calendar_date |
| No       |             | end_date     | End Date     | calendar_date | calendar_date |
| Yes      | series tag  | meeting_name | Meeting Name | text          | text          |
| Yes      | series tag  | location_2   | Location     | text          | text          |
| Yes      | series tag  | weblink      | Weblink      | url           | url           |
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
series e:5tb6-7zmc d:2014-08-04T00:00:00.000Z t:location_2="Department of Public Safety Standards and Training" t:weblink=http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx t:meeting_name="Task Force on School Safety Public Meeting" m:row_number.5tb6-7zmc=1

series e:5tb6-7zmc d:2014-08-28T00:00:00.000Z t:location_2="Department of Public Safety Standards and Training" t:weblink=http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx t:meeting_name="Task Force on School Safety Public Meeting" m:row_number.5tb6-7zmc=2

series e:5tb6-7zmc d:2014-09-29T00:00:00.000Z t:location_2="Department of Public Safety Standards and Training" t:weblink=http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx t:meeting_name="Task Force on School Safety" m:row_number.5tb6-7zmc=3
```

## Meta Commands

```ls
metric m:row_number.5tb6-7zmc p:long l:"Row Number"

entity e:5tb6-7zmc l:"Public Meeting Task Force on School Safety" t:url=https://data.oregon.gov/api/views/5tb6-7zmc

property e:5tb6-7zmc t:meta.view v:id=5tb6-7zmc v:category="Public Safety" v:attributionLink=http://www.oregon.gov/OSP v:averageRating=0 v:name="Public Meeting Task Force on School Safety"

property e:5tb6-7zmc t:meta.view.owner v:id=ftmj-mvwe v:screenName="Mindy McCartt" v:displayName="Mindy McCartt"

property e:5tb6-7zmc t:meta.view.tableauthor v:id=ftmj-mvwe v:screenName="Mindy McCartt" v:roleName=editor v:displayName="Mindy McCartt"
```

## Top Records

```ls
| date                | end_date            | meeting_name                               | location_2                                         | weblink                                                                  | 
| =================== | =================== | ========================================== | ================================================== | ======================================================================== | 
| 2014-08-04T00:00:00 | 2014-08-04T00:00:00 | Task Force on School Safety Public Meeting | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2014-08-28T00:00:00 | 2014-08-28T00:00:00 | Task Force on School Safety Public Meeting | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2014-09-29T00:00:00 | 2014-09-29T00:00:00 | Task Force on School Safety                | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2014-10-27T00:00:00 | 2014-10-27T00:00:00 | Task Force on School Safety                | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2014-11-17T00:00:00 | 2014-11-17T00:00:00 | Task Force on School Safety                | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2015-02-05T00:00:00 | 2015-02-05T00:00:00 | Task Force on School Safety                | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2015-04-28T00:00:00 | 2015-04-28T00:00:00 | Task Force on School Safety                | Clackamas County Sheriff's Office                  | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2015-05-26T00:00:00 | 2015-05-26T00:00:00 | Task Force on School Safety                | Willamette Education Service District              | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2015-03-18T00:00:00 | 2015-03-18T00:00:00 | Task Force on School Safety                | Willamette Education Service District              | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
| 2015-08-27T00:00:00 | 2015-08-27T00:00:00 | Task Force on School Safety                | Department of Public Safety Standards and Training | [http://www.oregon.gov/osp/Pages/Task-Force-on-School-Safety.aspx, null] | 
```