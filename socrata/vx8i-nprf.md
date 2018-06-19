# Civil Service List (Active)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/civil-service-list-active) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vx8i-nprf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vx8i-nprf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vx8i-nprf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vx8i-nprf |
| Name | Civil Service List (Active) |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Created | 2016-06-14T21:12:15Z |
| Publication Date | 2017-04-20T13:37:29Z |

## Description

A Civil Service List consists of all candidates who passed an exam, ranked in score order. An established list is considered active for no less than one year and no more than four years from the date of establishment. For more information visit DCAS? ?Work for the City? webpage at: http://www.nyc.gov/html/dcas/html/work/work.shtml

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
Excluded Fields = mi,established_date,anniversary_date,extension_date
```

## Data Commands

```ls
series e:vx8i-nprf d:2015-07-29T00:00:00.000Z t:first_name=SABINA t:list_no=1.000 t:exam_no=3004 t:list_title_code=10020 t:group_no=000 t:list_agency_code=000 t:last_name=BLASKOVIC t:list_title_desc="ADMINISTRATIVE INVESTIGATOR" t:list_agency_desc="OPEN COMPETITIVE" m:adj_fa=97

series e:vx8i-nprf d:2015-07-29T00:00:00.000Z t:first_name=MITCHELL t:list_no=2.000 t:exam_no=3004 t:list_title_code=10020 t:group_no=000 t:list_agency_code=000 t:last_name=STURMAN t:list_title_desc="ADMINISTRATIVE INVESTIGATOR" t:list_agency_desc="OPEN COMPETITIVE" m:adj_fa=97

series e:vx8i-nprf d:2015-07-29T00:00:00.000Z t:first_name=CHRISTOPHER t:list_no=3.000 t:exam_no=3004 t:list_title_code=10020 t:group_no=000 t:list_agency_code=000 t:last_name=ROOS t:list_title_desc="ADMINISTRATIVE INVESTIGATOR" t:list_agency_desc="OPEN COMPETITIVE" m:adj_fa=94
```

## Meta Commands

```ls
metric m:adj_fa p:long l:"Adj. FA" d:"The Adjusted Final Average (?Adj. FA? or ?AFA?) is an eligible candidate?s test score in addition to any additional credits granted." t:dataTypeName=number

entity e:vx8i-nprf l:"Civil Service List (Active)" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/vx8i-nprf

property e:vx8i-nprf t:meta.view v:id=vx8i-nprf v:category="City Government" v:averageRating=0 v:name="Civil Service List (Active)" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:vx8i-nprf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vx8i-nprf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| exam_no | list_no | first_name  | mi | last_name | adj_fa | list_title_code | list_title_desc             | group_no | list_agency_code | list_agency_desc | list_div_code | published_date      | established_date    | anniversary_date    | extension_date | veteran_credit | parent_lgy_credit | sibling_lgy_credit | residency_credit | 
| ======= | ======= | =========== | == | ========= | ====== | =============== | =========================== | ======== | ================ | ================ | ============= | =================== | =================== | =================== | ============== | ============== | ================= | ================== | ================ | 
| 3004    | 1.000   | SABINA      |    | BLASKOVIC | 97.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 2.000   | MITCHELL    |    | STURMAN   | 97.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 3.000   | CHRISTOPHER | J  | ROOS      | 94.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 4.000   | ALISON      | M  | BONFOEY   | 94.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 5.000   | RUSSELL     | C  | GALLO     | 94.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 6.000   | GERMAIN     | M  | DIFO      | 93.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 7.000   | MAUREEN     | R  | KOKEAS    | 93.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 8.000   | BRIAN       | J  | KRIST     | 93.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 9.000   | RANJIT      |    | PARMAR    | 93.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
| 3004    | 10.000  | RACINE      | D  | BENTON    | 93.00  | 10020           | ADMINISTRATIVE INVESTIGATOR | 000      | 000              | OPEN COMPETITIVE |               | 2015-07-29T00:00:00 | 2015-09-30T00:00:00 | 2019-09-30T00:00:00 |                |                |                   |                    |                  | 
```