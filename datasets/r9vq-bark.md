# DCAS TERMINATED Civil Svc List (DEV - Beta)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcas-terminated-civil-svc-list-dev-beta) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/r9vq-bark) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/r9vq-bark/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/r9vq-bark/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | r9vq-bark |
| Name | DCAS TERMINATED Civil Svc List (DEV - Beta) |
| Created | 2016-06-14T19:23:39Z |
| Publication Date | 2016-08-24T21:45:01Z |

## Description

DCAS Terminated Civil Service List

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | exam_no            | Exam No            | text          | text          |
| Yes      | series tag     | list_no            | List No            | text          | number        |
| Yes      | series tag     | first_name         | First Name         | text          | text          |
| No       |                | mi                 | MI                 | text          | text          |
| Yes      | series tag     | last_name          | Last Name          | text          | text          |
| Yes      | numeric metric | adj_fa             | Adj. FA            | number        | number        |
| Yes      | series tag     | list_title_code    | List Title Code    | text          | text          |
| Yes      | series tag     | list_title_desc    | List Title Desc    | text          | text          |
| Yes      | series tag     | group_no           | Group No           | text          | text          |
| Yes      | series tag     | list_agency_code   | List Agency Code   | text          | text          |
| Yes      | series tag     | list_agency_desc   | List Agency Desc   | text          | text          |
| Yes      | series tag     | list_div_code      | List Div Code      | text          | text          |
| Yes      | time           | published_date     | Published Date     | calendar_date | calendar_date |
| No       |                | established_date   | Established Date   | calendar_date | calendar_date |
| No       |                | anniversary_date   | Anniversary Date   | calendar_date | calendar_date |
| No       |                | extension_date     | Extension Date     | calendar_date | calendar_date |
| No       |                | termination_date   | Termination Date   | calendar_date | calendar_date |
| Yes      | series tag     | veteran_credit     | Veteran Credit     | text          | text          |
| Yes      | series tag     | parent_lgy_credit  | Parent Lgy Credit  | text          | text          |
| Yes      | series tag     | sibling_lgy_credit | Sibling Lgy Credit | text          | text          |
| Yes      | series tag     | residency_credit   | Residency Credit   | text          | text          |
```

## Time Field

```ls
Value = published_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mi,established_date,anniversary_date,extension_date,termination_date
```

## Data Commands

```ls
series e:r9vq-bark d:2008-08-13T00:00:00.000Z t:first_name=JOSEPH t:list_no=1.000 t:exam_no=7531 t:list_title_code=90904 t:group_no=000 t:list_agency_code=841 t:last_name=VRANA t:list_title_desc="SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS" t:list_agency_desc="DEPARTMENT OF TRANSPORTATION" m:adj_fa=90.23

series e:r9vq-bark d:2008-08-13T00:00:00.000Z t:first_name=NATALIE t:list_no=55.000 t:exam_no=7531 t:list_title_code=90904 t:group_no=000 t:list_agency_code=841 t:last_name=GRANT t:list_title_desc="SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS" t:list_agency_desc="DEPARTMENT OF TRANSPORTATION" m:adj_fa=70.08

series e:r9vq-bark d:2008-08-13T00:00:00.000Z t:first_name=JOSEPH t:list_no=3.000 t:exam_no=7531 t:list_title_code=90904 t:group_no=000 t:list_agency_code=841 t:last_name=CARL t:list_title_desc="SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS" t:list_agency_desc="DEPARTMENT OF TRANSPORTATION" m:adj_fa=88.42
```

## Meta Commands

```ls
metric m:adj_fa p:float l:"Adj. FA" t:dataTypeName=number

entity e:r9vq-bark l:"DCAS TERMINATED Civil Svc List (DEV - Beta)" t:url=https://data.cityofnewyork.us/api/views/r9vq-bark

property e:r9vq-bark t:meta.view v:id=r9vq-bark v:averageRating=0 v:name="DCAS TERMINATED Civil Svc List (DEV - Beta)"

property e:r9vq-bark t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:r9vq-bark t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| exam_no | list_no | first_name | mi | last_name | adj_fa | list_title_code | list_title_desc                          | group_no | list_agency_code | list_agency_desc             | list_div_code | published_date      | established_date    | anniversary_date    | extension_date | termination_date    | veteran_credit | parent_lgy_credit | sibling_lgy_credit | residency_credit | 
| ======= | ======= | ========== | == | ========= | ====== | =============== | ======================================== | ======== | ================ | ============================ | ============= | =================== | =================== | =================== | ============== | =================== | ============== | ================= | ================== | ================ | 
| 7531    | 1.000   | JOSEPH     | P  | VRANA     | 90.23  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 55.000  | NATALIE    | J  | GRANT     | 70.08  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 3.000   | JOSEPH     | W  | CARL      | 88.42  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 4.000   | DAVID      | G  | YEPEZ     | 88.42  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 5.000   | FRED       |    | SCHRAFT   | 87.29  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 6.000   | JOSEPH     |    | ASCANIO   | 87.25  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 7.000   | ANTHONY    |    | GINEX     | 87.04  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 8.000   | JOHN       | H  | COFFEY JR | 86.96  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 9.000   | GEORGE     | C  | TOMPKINS  | 86.01  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
| 7531    | 10.000  | STEPHEN    | W  | MEADE     | 85.16  | 90904           | SUPERVISOR OF TRAFFIC DEVICE MAINTAINERS | 000      | 841              | DEPARTMENT OF TRANSPORTATION |               | 2008-08-13T00:00:00 | 2012-06-02T00:00:00 | 2012-06-02T00:00:00 |                | 2016-06-02T00:00:00 |                |                   |                    |                  | 
```