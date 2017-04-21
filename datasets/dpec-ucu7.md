# New Driver Application Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-driver-application-status) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dpec-ucu7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dpec-ucu7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dpec-ucu7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dpec-ucu7 |
| Name | New Driver Application Status |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | new application, fhv, medallion, green, shl, street hail livery, for-hire, exam, results, limousine, status, driver, exam fee, fingerprint, hack number, fru, drug test, wav, wheelchair accessible ... |
| Created | 2016-05-17T18:43:43Z |
| Publication Date | 2016-05-18T19:45:33Z |

## Description

THIS DATASET IS UPDATED SEVERAL TIMES PER DAY.  TLC Driver application status check for applicants who had applied for a new TLC driver?s license. For questions, please email newdriverapp@tlc.nyc.gov and visit www.nyc.gov/newdriver for more detailed information. 

For historical/archived data of past application statuses, please see- https://data.cityofnewyork.us/Transportation/Historical-Driver-Application-Status/p32s-yqxq

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
| No       |             | lastupdate              | Last Updated            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = app_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lastupdate
```

## Data Commands

```ls
series e:dpec-ucu7 d:2017-01-08T00:00:00.000Z t:driver_exam=Needed t:app_no=5756796 t:wav_course=Needed t:status=Denied t:fru_interview_scheduled="Not Applicable" t:medical_clearance_form=Complete t:other_requirements="Copy of DMV license needed" t:defensive_driving=Needed t:type=HDR t:drug_test=Complete m:row_number.dpec-ucu7=1

series e:dpec-ucu7 d:2017-01-30T00:00:00.000Z t:driver_exam=Needed t:app_no=5762241 t:wav_course=Needed t:status=Incomplete t:fru_interview_scheduled="Not Applicable" t:medical_clearance_form=Needed t:other_requirements="Fingerprints needed; Copy of DMV license needed" t:defensive_driving=Complete t:type=HDR t:drug_test=Needed m:row_number.dpec-ucu7=2

series e:dpec-ucu7 d:2017-03-26T00:00:00.000Z t:driver_exam=Complete t:app_no=5776872 t:wav_course=Complete t:status="Approved - License Issued" t:fru_interview_scheduled="Not Applicable" t:medical_clearance_form=Complete t:other_requirements="Not Applicable" t:defensive_driving=Complete t:type=HDR t:drug_test=Complete m:row_number.dpec-ucu7=3
```

## Meta Commands

```ls
metric m:row_number.dpec-ucu7 p:long l:"Row Number"

entity e:dpec-ucu7 l:"New Driver Application Status" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/dpec-ucu7

property e:dpec-ucu7 t:meta.view v:id=dpec-ucu7 v:category=Transportation v:averageRating=0 v:name="New Driver Application Status" v:attribution="Taxi and Limousine Commission (TLC)"

property e:dpec-ucu7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dpec-ucu7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| app_no  | type | app_date            | status                    | fru_interview_scheduled | drug_test | wav_course | defensive_driving | driver_exam | medical_clearance_form | other_requirements                              | lastupdate          | 
| ======= | ==== | =================== | ========================= | ======================= | ========= | ========== | ================= | =========== | ====================== | =============================================== | =================== | 
| 5756796 | HDR  | 2017-01-08T00:00:00 | Denied                    | Not Applicable          | Complete  | Needed     | Needed            | Needed      | Complete               | Copy of DMV license needed                      | 2017-04-21T00:00:12 | 
| 5762241 | HDR  | 2017-01-30T00:00:00 | Incomplete                | Not Applicable          | Needed    | Needed     | Complete          | Needed      | Needed                 | Fingerprints needed; Copy of DMV license needed | 2017-04-21T00:00:12 | 
| 5776872 | HDR  | 2017-03-26T00:00:00 | Approved - License Issued | Not Applicable          | Complete  | Complete   | Complete          | Complete    | Complete               | Not Applicable                                  | 2017-04-21T00:00:12 | 
| 5762061 | HDR  | 2017-01-28T00:00:00 | Incomplete                | Not Applicable          | Complete  | Complete   | Complete          | Needed      | Complete               | Not Applicable                                  | 2017-04-21T00:00:12 | 
| 5770274 | HDR  | 2017-03-02T00:00:00 | Incomplete                | Not Applicable          | Complete  | Needed     | Complete          | Needed      | Needed                 | Copy of DMV license needed                      | 2017-04-21T00:00:12 | 
| 5779215 | HDR  | 2017-04-04T00:00:00 | Incomplete                | Not Applicable          | Needed    | Complete   | Complete          | Needed      | Needed                 | Fingerprints needed; Copy of DMV license needed | 2017-04-21T00:00:12 | 
| 5774693 | HDR  | 2017-03-17T00:00:00 | Incomplete                | Not Applicable          | Complete  | Needed     | Complete          | Needed      | Needed                 | Copy of DMV license needed                      | 2017-04-21T00:00:12 | 
| 5780883 | HDR  | 2017-04-10T00:00:00 | Incomplete                | Not Applicable          | Complete  | Complete   | Complete          | Needed      | Complete               | Fingerprints needed                             | 2017-04-21T00:00:12 | 
| 5780382 | HDR  | 2017-04-07T00:00:00 | Incomplete                | Not Applicable          | Complete  | Needed     | Needed            | Needed      | Needed                 | Copy of DMV license needed                      | 2017-04-21T00:00:12 | 
| 5762205 | HDR  | 2017-01-29T00:00:00 | Incomplete                | Not Applicable          | Complete  | Complete   | Complete          | Needed      | Needed                 | Copy of DMV license needed                      | 2017-04-21T00:00:12 | 
```