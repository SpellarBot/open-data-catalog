# Pest Control Exam Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pest-control-exam-schedule-f65f3) |
| Metadata | [Link](https://data.illinois.gov/api/views/hmag-wvgb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hmag-wvgb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hmag-wvgb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hmag-wvgb |
| Name | Pest Control Exam Schedule |
| Attribution | IDPH - Division of Environmental Health |
| Category | Public Health |
| Tags | pest control, exam |
| Created | 2014-11-21T21:53:34Z |
| Publication Date | 2017-04-18T16:28:58Z |

## Description

This contains the dates of the Pest Control Exam. Last Update January 2017

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | exam_date       | Exam Date       | calendar_date | calendar_date |
| Yes      | series tag     | exam_status     | Exam Status     | text          | text          |
| Yes      | numeric metric | seats_available | Seats Available | number        | number        |
| Yes      | series tag     | exam_begins_at  | Exam Begins at: | text          | text          |
| Yes      | series tag     | exam_location   | Exam Location   | text          | text          |
| No       |                | exam_address    | Exam Address    | text          | text          |
| Yes      | series tag     | city            | City            | text          | text          |
| Yes      | series tag     | state           | State           | text          | text          |
| Yes      | series tag     | zip_code        | ZIP Code        | text          | number        |
| Yes      | numeric metric | examinee_limits | Examinee Limits | number        | number        |
| Yes      | series tag     | exam_type       | Exam Type       | text          | text          |
```

## Time Field

```ls
Value = exam_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = exam_address
```

## Data Commands

```ls
series e:hmag-wvgb d:2017-09-19T00:00:00.000Z t:zip_code=60477 t:state=IL t:exam_status=OPEN t:exam_location="Holiday Inn Convention Center" t:exam_begins_at="1:00 PM" t:exam_type="General Standards Exam Only" t:city="Tinley Park" m:seats_available=30 m:examinee_limits=30

series e:hmag-wvgb d:2017-12-12T00:00:00.000Z t:zip_code=60016 t:state=IL t:exam_status=OPEN t:exam_location="Illinois Central Management Systems" t:exam_begins_at="9:00 AM" t:exam_type="General Standards Exam Only" t:city="Des Plaines" m:seats_available=80 m:examinee_limits=80

series e:hmag-wvgb d:2017-03-15T00:00:00.000Z t:zip_code=62095 t:state=IL t:exam_status=OPEN t:exam_location="Madison County Health Department" t:exam_begins_at="9:00 AM" t:city="Wood River" m:seats_available=50 m:examinee_limits=50
```

## Meta Commands

```ls
metric m:seats_available p:integer l:"Seats Available" t:dataTypeName=number

metric m:examinee_limits p:integer l:"Examinee Limits" t:dataTypeName=number

entity e:hmag-wvgb l:"Pest Control Exam Schedule" t:attribution="IDPH - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/hmag-wvgb

property e:hmag-wvgb t:meta.view v:id=hmag-wvgb v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/structural-pest-control v:averageRating=0 v:name="Pest Control Exam Schedule" v:attribution="IDPH - Division of Environmental Health"

property e:hmag-wvgb t:meta.view.license v:name="Public Domain"

property e:hmag-wvgb t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:hmag-wvgb t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| exam_date           | exam_status | seats_available | exam_begins_at | exam_location                       | exam_address                   | city        | state | zip_code | examinee_limits | exam_type                   | 
| =================== | =========== | =============== | ============== | =================================== | ============================== | =========== | ===== | ======== | =============== | =========================== | 
| 2017-09-19T00:00:00 | OPEN        | 30              | 1:00 PM        | Holiday Inn Convention Center       | 18451 Convention Center Dr     | Tinley Park | IL    | 60477    | 30              | General Standards Exam Only | 
| 2017-12-12T00:00:00 | OPEN        | 80              | 9:00 AM        | Illinois Central Management Systems | 9511 W Harrison St, Room LL-11 | Des Plaines | IL    | 60016    | 80              | General Standards Exam Only | 
| 2017-03-15T00:00:00 | OPEN        | 50              | 9:00 AM        | Madison County Health Department    | 101 E Edwardsville Rd          | Wood River  | IL    | 62095    | 50              |                             | 
| 2017-08-03T00:00:00 | OPEN        | 80              | 9:00 AM        | Illinois Central Management Systems | 9511 W Harrison St, Room LL-11 | Des Plaines | IL    | 60016    | 80              | General Standards Exam Only | 
| 2017-10-26T00:00:00 | OPEN        | 25              | 9:00 AM        | IDPH Rockford Region Office         | 4302 N Main St                 | Rockford    | IL    | 61103    | 25              |                             | 
| 2017-12-12T00:00:00 | OPEN        | 30              | 1:00 PM        | Illinois Central Management Systems | 9511 W Harrison St, Room LL-11 | Des Plaines | IL    | 60016    | 30              |                             | 
| 2017-09-19T00:00:00 | OPEN        | 80              | 9:00 AM        | Holiday Inn Convention Center       | 18451 Convention Center Dr     | Tinley Park | IL    | 60477    | 80              |                             | 
| 2017-09-06T00:00:00 | OPEN        | 20              | 9:00 AM        | IDPH Marion Region Office           | 2309 W Main St                 | Marion      | IL    | 62959    | 20              |                             | 
| 2017-08-03T00:00:00 | OPEN        | 30              | 1:00 PM        | Illinois Central Management Systems | 9511 W Harrison St, Room LL-11 | Des Plaines | IL    | 60016    | 30              |                             | 
| 2017-09-27T00:00:00 | OPEN        | 60              | 9:00 AM        | IPCA Fall Conference                | 701 E Adams St                 | Springfield | IL    | 62701    | 60              |                             | 
```