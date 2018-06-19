# Work Order Management Module

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/work-order-management-module) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4fvw-nn9c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4fvw-nn9c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4fvw-nn9c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4fvw-nn9c |
| Name | Work Order Management Module |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Created | 2015-05-22T21:03:59Z |
| Publication Date | 2015-06-15T16:08:40Z |

## Description

Work orders associated with a CSR complaints

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | =========== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag  | svc_request_number             | SVC_REQUEST_NUMBER             | text          | number        |
| Yes      | series tag  | workorder_number               | WORKORDER_NUMBER               | text          | number        |
| Yes      | series tag  | workorder_activity_code        | WORKORDER_ACTIVITY_CODE        | text          | text          |
| Yes      | series tag  | workorder_activity_description | WORKORDER_ACTIVITY_DESCRIPTION | text          | text          |
| No       |             | workorder_started              | WORKORDER_STARTED              | calendar_date | calendar_date |
| No       |             | workorder_completed            | WORKORDER_COMPLETED            | calendar_date | calendar_date |
| Yes      | time        | workorder_added                | WORKORDER_ADDED                | calendar_date | calendar_date |
| No       |             | time_stamp                     | TIME_STAMP                     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = workorder_added
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = workorder_started,workorder_completed,time_stamp
```

## Data Commands

```ls
series e:4fvw-nn9c d:2004-07-16T10:00:04.000Z t:svc_request_number=860449 t:workorder_activity_description="REPAIR CONNECTION" t:workorder_activity_code=SA25 t:workorder_number=895401 m:row_number.4fvw-nn9c=1

series e:4fvw-nn9c d:2000-06-01T13:20:07.000Z t:svc_request_number=168089 t:workorder_activity_description="PERFORM OTHER MANHOLE WORK" t:workorder_activity_code=SA27 t:workorder_number=100322 m:row_number.4fvw-nn9c=2

series e:4fvw-nn9c d:2002-04-08T23:03:19.000Z t:svc_request_number=428803 t:workorder_activity_description="RESET/REPLACE VALVE BOX" t:workorder_activity_code=WA10 t:workorder_number=843089280 m:row_number.4fvw-nn9c=3
```

## Meta Commands

```ls
metric m:row_number.4fvw-nn9c p:long l:"Row Number"

entity e:4fvw-nn9c l:"Work Order Management Module" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/4fvw-nn9c

property e:4fvw-nn9c t:meta.view v:id=4fvw-nn9c v:category=Environment v:averageRating=0 v:name="Work Order Management Module" v:attribution="Department of Environmental Protection (DEP)"

property e:4fvw-nn9c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4fvw-nn9c t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| svc_request_number | workorder_number | workorder_activity_code | workorder_activity_description | workorder_started   | workorder_completed | workorder_added     | time_stamp          | 
| ================== | ================ | ======================= | ============================== | =================== | =================== | =================== | =================== | 
| 860449             | 895401           | SA25                    | REPAIR CONNECTION              |                     |                     | 2004-07-16T10:00:04 | 2015-07-07T00:45:01 | 
| 168089             | 100322           | SA27                    | PERFORM OTHER MANHOLE WORK     |                     |                     | 2000-06-01T13:20:07 | 2015-06-29T00:40:55 | 
| 428803             | 843089280        | WA10                    | RESET/REPLACE VALVE BOX        | 2015-06-10T08:20:00 | 2015-06-10T11:00:00 | 2002-04-08T23:03:19 | 2015-06-16T00:45:01 | 
| 185634611          | 842762063        | SA26                    | REPLACE MANHOLE CASTING        | 2016-02-25T00:45:00 | 2016-02-25T03:00:00 | 2013-09-03T09:13:14 | 2016-02-26T00:45:03 | 
| 895478             | 842882322        | SRL                     | LINE SEWER (CONTRACTOR)        | 2016-11-29T00:00:00 | 2016-12-13T00:00:00 | 2014-04-23T13:47:23 | 2017-01-10T00:45:01 | 
| 2011048            | 1780489          | WHF                     | FLUSH HYDRANTS IN AREA         | 2016-02-17T17:41:00 | 2016-02-17T17:41:00 | 2008-12-02T13:48:23 | 2016-02-18T00:45:01 | 
| 185673001          | 843073274        | SVAC                    | VACTOR SEWER                   | 2015-05-05T10:45:00 | 2015-05-05T11:45:00 | 2015-05-07T10:25:54 | 2015-05-08T00:45:09 | 
| 185645826          | 843047233        | SRB                     | REPAIR SEWER BREAK (CONTRACT.) | 2015-11-14T07:00:00 | 2015-11-17T15:00:00 | 2015-04-03T08:15:43 | 2015-11-24T00:45:08 | 
| 1011746            | 1006805          | SA25                    | REPAIR CONNECTION              |                     |                     | 2005-02-16T11:18:09 | 2015-07-07T00:45:01 | 
| 185537818          | 843454743        | SCC                     | CLEAN CATCH BASIN/INLET        | 2016-06-30T11:40:00 | 2016-06-30T12:45:00 | 2016-08-01T20:54:30 | 2016-08-02T00:45:02 | 
```