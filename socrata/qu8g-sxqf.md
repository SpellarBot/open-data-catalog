# Civil Service List (Terminated)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/civil-service-list-terminated) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qu8g-sxqf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qu8g-sxqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qu8g-sxqf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qu8g-sxqf |
| Name | Civil Service List (Terminated) |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Tags | civil, service, exam, dcas |
| Created | 2016-06-14T21:26:18Z |
| Publication Date | 2017-04-01T13:30:42Z |

## Description

A Civil Service List is considered terminated usually four years after the list has been established, unless it is extended at the Commissioner?s discretion. For more information visit DCAS? ?Work for the City? webpage at: http://www.nyc.gov/html/dcas/html/work/work.shtml.

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
| No       |                | published_date     | Published Date     | calendar_date | calendar_date |
| Yes      | time           | established_date   | Established Date   | calendar_date | calendar_date |
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
Value = established_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mi,published_date,anniversary_date,extension_date,termination_date
```

## Data Commands

```ls
series e:qu8g-sxqf d:2014-02-12T00:00:00.000Z t:first_name=MICHAEL t:list_no=1.000 t:exam_no=3511 t:list_title_code=31662 t:group_no=000 t:list_agency_code=057 t:last_name=BEROLATTI t:list_title_desc="ASSOCIATE FIRE PROTECTION INSPECTOR" t:list_agency_desc="FIRE DEPARTMENT" m:adj_fa=87.6

series e:qu8g-sxqf d:2014-02-12T00:00:00.000Z t:first_name=AMJAD t:list_no=2.000 t:exam_no=3511 t:list_title_code=31662 t:group_no=000 t:list_agency_code=057 t:last_name=HOSSAIN t:list_title_desc="ASSOCIATE FIRE PROTECTION INSPECTOR" t:list_agency_desc="FIRE DEPARTMENT" m:adj_fa=87.2

series e:qu8g-sxqf d:2014-02-12T00:00:00.000Z t:first_name=ANDREW t:list_no=3.000 t:exam_no=3511 t:list_title_code=31662 t:group_no=000 t:list_agency_code=057 t:last_name=DEHEER t:list_title_desc="ASSOCIATE FIRE PROTECTION INSPECTOR" t:list_agency_desc="FIRE DEPARTMENT" m:adj_fa=86.88
```

## Meta Commands

```ls
metric m:adj_fa p:float l:"Adj. FA" d:"The Adjusted Final Average (?Adj. FA? or ?AFA?) is an eligible candidate?s test score in addition to any additional credits granted." t:dataTypeName=number

entity e:qu8g-sxqf l:"Civil Service List (Terminated)" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/qu8g-sxqf

property e:qu8g-sxqf t:meta.view v:id=qu8g-sxqf v:category="City Government" v:averageRating=0 v:name="Civil Service List (Terminated)" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:qu8g-sxqf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qu8g-sxqf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| exam_no | list_no | first_name | mi | last_name  | adj_fa | list_title_code | list_title_desc                     | group_no | list_agency_code | list_agency_desc | list_div_code | published_date      | established_date    | anniversary_date    | extension_date | termination_date    | veteran_credit | parent_lgy_credit | sibling_lgy_credit | residency_credit | 
| ======= | ======= | ========== | == | ========== | ====== | =============== | =================================== | ======== | ================ | ================ | ============= | =================== | =================== | =================== | ============== | =================== | ============== | ================= | ================== | ================ | 
| 3511    | 1.000   | MICHAEL    | J  | BEROLATTI  | 87.60  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 2.000   | AMJAD      |    | HOSSAIN    | 87.20  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 3.000   | ANDREW     | N  | DEHEER     | 86.88  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 4.000   | SUJIT      | K  | ROY        | 86.75  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 5.000   | ERVIN      |    | SANTIAGO   | 85.90  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 6.000   | ADEKUNLE   | A  | BANJOKO    | 85.17  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 7.000   | TANVIR     |    | AHMED      | 84.20  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 8.000   | FESTUS     | A  | AKINRODOYE | 84.15  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 9.000   | JOSEPH     |    | EDEM       | 84.12  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
| 3511    | 10.000  | WINFIELD   | A  | GORDON     | 84.08  | 31662           | ASSOCIATE FIRE PROTECTION INSPECTOR | 000      | 057              | FIRE DEPARTMENT  |               | 2013-08-07T00:00:00 | 2014-02-12T00:00:00 | 2018-02-12T00:00:00 |                | 2016-06-22T00:00:00 |                |                   |                    |                  | 
```