# Historical Driver Application Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-driver-application-status) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/p32s-yqxq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/p32s-yqxq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/p32s-yqxq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | p32s-yqxq |
| Name | Historical Driver Application Status |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Created | 2016-06-16T18:07:19Z |
| Publication Date | 2016-08-09T14:56:41Z |

## Description

Historical licensee status data. Data dictionary available here: https://data.cityofnewyork.us/api/views/p32s-yqxq/files/20bca1de-74f0-462e-8574-f25ca66b8346?download=true&filename=NewDriverAppStatusLookupLegend.pdf

For questions, please email newdriverapp@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | app_no                  | App No                  | text          | number        |
| Yes      | series tag  | type                    | Type                    | text          | text          |
| Yes      | time        | app_date                | App Date                | calendar_date | calendar_date |
| Yes      | series tag  | status                  | Status                  | text          | text          |
| Yes      | series tag  | fru_interview_scheduled | FRU Interview Scheduled | text          | text          |
| Yes      | series tag  | drug_test               | Drug Test               | text          | text          |
| Yes      | series tag  | wav_course              | WAV Course              | text          | text          |
| Yes      | series tag  | defensive_driving       | Defensive Driving       | text          | text          |
| Yes      | series tag  | driver_exam             | Driver Exam             | text          | text          |
| Yes      | series tag  | medical_clearance_form  | Medical Clearance Form  | text          | text          |
| Yes      | series tag  | other_requirements      | Other Requirements      | text          | text          |
| No       |             | last_updated            | Last Updated            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = app_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_updated
```

## Data Commands

```ls
series e:p32s-yqxq d:2016-01-21T00:00:00.000Z t:driver_exam=Complete t:app_no=5675820 t:wav_course=Complete t:status=Denied t:fru_interview_scheduled=06/01/2016 t:medical_clearance_form=Complete t:other_requirements="Not Applicable" t:defensive_driving=Complete t:type=CDR t:drug_test=Complete m:row_number.p32s-yqxq=1

series e:p32s-yqxq d:2016-01-26T00:00:00.000Z t:driver_exam=Complete t:app_no=5676756 t:wav_course=Complete t:status="Approved - License Issued" t:fru_interview_scheduled="Not Applicable" t:medical_clearance_form=Complete t:other_requirements="Not Applicable" t:defensive_driving=Complete t:type=CDR t:drug_test=Complete m:row_number.p32s-yqxq=2

series e:p32s-yqxq d:2016-02-22T00:00:00.000Z t:driver_exam=Complete t:app_no=5681259 t:wav_course=Complete t:status=Denied t:fru_interview_scheduled=06/14/2016 t:medical_clearance_form=Complete t:other_requirements="Not Applicable" t:defensive_driving=Complete t:type=HDR t:drug_test=Complete m:row_number.p32s-yqxq=3
```

## Meta Commands

```ls
metric m:row_number.p32s-yqxq p:long l:"Row Number"

entity e:p32s-yqxq l:"Historical Driver Application Status" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/p32s-yqxq

property e:p32s-yqxq t:meta.view v:id=p32s-yqxq v:category=Transportation v:averageRating=0 v:name="Historical Driver Application Status" v:attribution="Taxi and Limousine Commission (TLC)"

property e:p32s-yqxq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:p32s-yqxq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| app_no  | type | app_date            | status                    | fru_interview_scheduled | drug_test | wav_course | defensive_driving | driver_exam | medical_clearance_form | other_requirements | last_updated        | 
| ======= | ==== | =================== | ========================= | ======================= | ========= | ========== | ================= | =========== | ====================== | ================== | =================== | 
| 5675820 | CDR  | 2016-01-21T00:00:00 | Denied                    | 06/01/2016              | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5676756 | CDR  | 2016-01-26T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5681259 | HDR  | 2016-02-22T00:00:00 | Denied                    | 06/14/2016              | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5681326 | CDR  | 2016-02-22T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5681690 | CDR  | 2016-02-23T00:00:00 | Denied                    | 04/29/2016              | Complete  | Complete   | Complete          | Complete    | Needed                 | Not Applicable     | 2016-07-06T18:11:29 | 
| 5682613 | CDR  | 2016-02-28T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5682927 | CDR  | 2016-03-01T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5683071 | CDR  | 2016-03-01T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5683211 | CDR  | 2016-03-02T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
| 5684390 | CDR  | 2016-03-07T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable     | 2016-07-06T18:11:29 | 
```