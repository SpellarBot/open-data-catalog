# Zoning Board of Appeals Public Hearings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/zoning-board-of-appeals-public-hearings) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/gsgc-7puf) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/gsgc-7puf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/gsgc-7puf/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | gsgc-7puf |
| Name | Zoning Board of Appeals Public Hearings |
| Attribution | Cook County Zoning Board of Appeals |
| Category | Property & Taxation |
| Created | 2016-06-23T02:58:18Z |
| Publication Date | 2017-01-17T15:16:30Z |

## Description

Archive of Public Hearing Notices for the Cook County Zoning Board of Appeals

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | time        | date        | Date        | calendar_date | calendar_date |
| Yes      | series tag  | link        | Link        | url           | url           |
| Yes      | series tag  | time        | Time        | text          | text          |
| Yes      | series tag  | location    | Location    | text          | text          |
| Yes      | series tag  | description | Description | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gsgc-7puf d:2016-06-08T00:00:00.000Z t:time="1:00:00 PM" t:location="17th Floor Conference Room, 69 W. Washington, Suite 2840, Chicago, Illinois 60602" t:description="Zoning Board Agenda" t:link=http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/June-8-2016-Variation-Schedule.pdf m:row_number.gsgc-7puf=1

series e:gsgc-7puf d:2016-06-08T00:00:00.000Z t:time="1:00:00 PM" t:location="17th Floor Conference Room, 69 W. Washington, Suite 2840, Chicago, Illinois 60602" t:description="Zoning Board Agenda" t:link=http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/June-8-2016-MA-16-01-SU-16-03-Schedule.pdf m:row_number.gsgc-7puf=2

series e:gsgc-7puf d:2016-06-01T00:00:00.000Z t:time="1:00:00 PM" t:location="69 W. Washington, Suite 2840, Chicago, Illinois 60602" t:description="Zoning Board Agenda" t:link=http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/June-1-2016-SU-16-02-Schedule.pdf m:row_number.gsgc-7puf=3
```

## Meta Commands

```ls
metric m:row_number.gsgc-7puf p:long l:"Row Number"

entity e:gsgc-7puf l:"Zoning Board of Appeals Public Hearings" t:attribution="Cook County Zoning Board of Appeals" t:url=https://datacatalog.cookcountyil.gov/api/views/gsgc-7puf

property e:gsgc-7puf t:meta.view v:id=gsgc-7puf v:category="Property & Taxation" v:averageRating=0 v:name="Zoning Board of Appeals Public Hearings" v:attribution="Cook County Zoning Board of Appeals"

property e:gsgc-7puf t:meta.view.license v:name="Public Domain"

property e:gsgc-7puf t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:gsgc-7puf t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| date                | link                                                                                                                | time       | location                                                                          | description         | 
| =================== | =================================================================================================================== | ========== | ================================================================================= | =================== | 
| 2016-06-08T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/June-8-2016-Variation-Schedule.pdf, Agenda]         | 1:00:00 PM | 17th Floor Conference Room, 69 W. Washington, Suite 2840, Chicago, Illinois 60602 | Zoning Board Agenda | 
| 2016-06-08T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/June-8-2016-MA-16-01-SU-16-03-Schedule.pdf, Agenda] | 1:00:00 PM | 17th Floor Conference Room, 69 W. Washington, Suite 2840, Chicago, Illinois 60602 | Zoning Board Agenda | 
| 2016-06-01T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/June-1-2016-SU-16-02-Schedule.pdf, Agenda]          | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-05-18T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/5-18-2016_decision_schedule.pdf, Agenda]            | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-05-18T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/5-18-2016_variation_schedule.pdf, Agenda]           | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-05-04T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/May-4-2016-Decision-Schedule.pdf, Agenda]           | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-05-04T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/May-4-2016-Variation-Schedule.pdf, Agenda]          | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-04-06T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/April-6-2016-Decision-Schedule.pdf, Agenda]         | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-04-06T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/April-6-2016-MA-16-01-Schedule.pdf, Agenda]         | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
| 2016-04-06T00:00:00 | [http://opendocs.cookcountyil.gov/zoning-board-appeals/hearings/April-6-2016-Variation-Schedule.pdf, Agenda]        | 1:00:00 PM | 69 W. Washington, Suite 2840, Chicago, Illinois 60602                             | Zoning Board Agenda | 
```