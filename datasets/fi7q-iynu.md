# Appeals filed with the Civil Service Commission

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/appeals-filed-with-the-civil-service-commission) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fi7q-iynu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fi7q-iynu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fi7q-iynu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fi7q-iynu |
| Name | Appeals filed with the Civil Service Commission |
| Attribution | Civil Service Commission (CSC) |
| Category | City Government |
| Created | 2016-01-05T17:13:20Z |
| Publication Date | 2016-04-26T19:08:44Z |

## Description

Number of appeals filed within a pre-determined time.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | appeal_type      | Appeal Type      | text          | text          |
| Yes      | series tag  | disqualification | Disqualification | text          | text          |
| Yes      | series tag  | received         | Received         | text          | text          |
| No       |             | status_flag      | Status flag      | text          | text          |
| Yes      | series tag  | status           | Status           | text          | text          |
| Yes      | time        | date_filed       | Date Filed       | calendar_date | calendar_date |
| Yes      | series tag  | agency           | Agency           | text          | text          |
| No       |             | closed           | Closed           | calendar_date | calendar_date |
| Yes      | series tag  | exam_no          | Exam No.         | text          | number        |
| Yes      | series tag  | exam_title       | Exam Title       | text          | text          |
| No       |             | expiration       | Expiration       | calendar_date | calendar_date |
| Yes      | series tag  | acronym          | acronym          | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = status_flag,closed,expiration
```

## Data Commands

```ls
series e:fi7q-iynu d:2014-12-31T00:00:00.000Z t:exam_no=1305 t:acronym=NYCTA t:status=Active t:agency="Police Department - NYPD" t:appeal_type="Section 50" t:received="U.S. Mail" t:disqualification=Psych t:exam_title="Police Officer" m:row_number.fi7q-iynu=1

series e:fi7q-iynu d:2014-12-31T00:00:00.000Z t:exam_no=3056 t:acronym=FDNY t:status=Active t:agency="Department of Citywide Administrative Services - DCAS" t:appeal_type="Section 50" t:received="U.S. Mail" t:disqualification="Education and Experience" t:exam_title="Supervising Computer Service Technician" m:row_number.fi7q-iynu=2

series e:fi7q-iynu d:2015-01-02T00:00:00.000Z t:exam_no=4026 t:acronym=DCAS t:status=Active t:agency="Department of Citywide Administrative Services - DCAS" t:appeal_type="Section 50" t:received="By Hand" t:disqualification="Education and Experience" t:exam_title=Forester m:row_number.fi7q-iynu=3
```

## Meta Commands

```ls
metric m:row_number.fi7q-iynu p:long l:"Row Number"

entity e:fi7q-iynu l:"Appeals filed with the Civil Service Commission" t:attribution="Civil Service Commission (CSC)" t:url=https://data.cityofnewyork.us/api/views/fi7q-iynu

property e:fi7q-iynu t:meta.view v:id=fi7q-iynu v:category="City Government" v:averageRating=0 v:name="Appeals filed with the Civil Service Commission" v:attribution="Civil Service Commission (CSC)"

property e:fi7q-iynu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fi7q-iynu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| appeal_type | disqualification         | received  | status_flag | status | date_filed          | agency                                                | closed              | exam_no | exam_title                              | expiration          | acronym | 
| =========== | ======================== | ========= | =========== | ====== | =================== | ===================================================== | =================== | ======= | ======================================= | =================== | ======= | 
| Section 50  | Psych                    | U.S. Mail | Open        | Active | 2014-12-31T00:00:00 | Police Department - NYPD                              |                     | 1305    | Police Officer                          | 2016-07-03T00:00:00 | NYCTA   | 
| Section 50  | Education and Experience | U.S. Mail | Open        | Active | 2014-12-31T00:00:00 | Department of Citywide Administrative Services - DCAS |                     | 3056    | Supervising Computer Service Technician |                     | FDNY    | 
| Section 50  | Education and Experience | By Hand   | Open        | Active | 2015-01-02T00:00:00 | Department of Citywide Administrative Services - DCAS |                     | 4026    | Forester                                | 2019-04-22T00:00:00 | DCAS    | 
| Section 50  | Psych                    | U.S. Mail | Closed      | Closed | 2014-12-31T00:00:00 | Police Department - NYPD                              | 2015-12-30T00:00:00 | 2013    | Police Communications Technician        | 2016-10-31T00:00:00 | NYPD    | 
| Section 50  | Character                | U.S. Mail | Closed      | Closed | 2014-12-31T00:00:00 | Police Department - NYPD                              | 2015-03-09T00:00:00 | 8051    | POLICE OFFICER                          | 2015-12-14T00:00:00 | DCAS    | 
| Section 50  | Education and Experience | U.S. Mail | Open        | Active | 2015-01-02T00:00:00 | Department of Citywide Administrative Services - DCAS |                     | 4026    | Forester                                | 2019-04-22T00:00:00 | NYCTA   | 
| Section 50  | Education and Experience | U.S. Mail | Open        | Active | 2015-01-02T00:00:00 | Department of Citywide Administrative Services - DCAS |                     | 3056    | Supervising Computer Service Technician |                     | NYPD    | 
| Section 50  | Education and Experience | U.S. Mail | Open        | Active | 2015-01-02T00:00:00 | Department of Citywide Administrative Services - DCAS |                     | 3056    | Supervising Computer Service Technician |                     | FDNY    | 
| Section 50  | Psych                    | U.S. Mail | Open        | Active | 2015-01-02T00:00:00 | Police Department - NYPD                              |                     | 2311    | Police Officer                          | 2018-05-01T00:00:00 | DCAS    | 
| Section 50  | Medical                  | U.S. Mail | Closed      | Closed | 2015-01-02T00:00:00 | Department of Correction - DOC                        | 2015-10-23T00:00:00 | 1318    | Correction Officer                      | 2018-05-08T00:00:00 | NYPD    | 
```