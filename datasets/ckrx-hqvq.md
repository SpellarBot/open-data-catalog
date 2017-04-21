# IDPH Swimming Facilities Pre-Qualification Training Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-swimming-facilities-pre-qualification-training-schedule-0d3a1) |
| Metadata | [Link](https://data.illinois.gov/api/views/ckrx-hqvq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ckrx-hqvq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ckrx-hqvq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ckrx-hqvq |
| Name | IDPH Swimming Facilities Pre-Qualification Training Schedule |
| Attribution | Illinois Department of Public Health |
| Category | Public Health |
| Tags | pre-qualification training for swimming facility designers and contractors |
| Created | 2014-01-24T19:05:26Z |
| Publication Date | 2016-10-13T12:47:57Z |

## Description

This contains the scheduled dates that Swimming Facility Contractors, Architects and Engineers may attend the IDPH conducted webinar. Registration is required. Last Updated: October 2016

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| No       | time        | :updated_at              | updated_at               | meta_data     | meta_data     |
| No       |             | course_date              | Course Date              | calendar_date | calendar_date |
| No       |             | course_begin_time        | Course Begin Time        | text          | text          |
| No       |             | course_end_time          | Course End time          | text          | text          |
| Yes      | series tag  | registration_information | Registration Information | text          | text          |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = course_date,course_begin_time,course_end_time
```

## Data Commands

```ls
series e:ckrx-hqvq d:2016-10-13T12:47:27.000Z t:registration_information="To register, contact the Swimming Facility Program at 217-782-5830.  Once an application has been received, prequalification applicants will be provided information for joining the webinar." m:row_number.ckrx-hqvq=1

series e:ckrx-hqvq d:2016-10-13T12:47:27.000Z t:registration_information="To register, contact the Swimming Facility Program at 217-782-5830.  Once an application has been received, prequalification applicants will be provided information for joining the webinar." m:row_number.ckrx-hqvq=2

series e:ckrx-hqvq d:2016-10-13T12:47:27.000Z t:registration_information="To register, contact the Swimming Facility Program at 217-782-5830.  Once an application has been received, prequalification applicants will be provided information for joining the webinar." m:row_number.ckrx-hqvq=3
```

## Meta Commands

```ls
metric m:row_number.ckrx-hqvq p:long l:"Row Number"

entity e:ckrx-hqvq l:"IDPH Swimming Facilities Pre-Qualification Training Schedule" t:attribution="Illinois Department of Public Health" t:url=https://data.illinois.gov/api/views/ckrx-hqvq

property e:ckrx-hqvq t:meta.view v:id=ckrx-hqvq v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/swimming-facilities v:averageRating=0 v:name="IDPH Swimming Facilities Pre-Qualification Training Schedule" v:attribution="Illinois Department of Public Health"

property e:ckrx-hqvq t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:ckrx-hqvq t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| :updated_at | course_date | course_begin_time | course_end_time | registration_information                                                                                                                                                                     | 
| =========== | =========== | ================= | =============== | ============================================================================================================================================================================================ | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
| 1476362847  |             | 1:00 PM           | 4:00 PM         | To register, contact the Swimming Facility Program at 217-782-5830. Once an application has been received, prequalification applicants will be provided information for joining the webinar. | 
```