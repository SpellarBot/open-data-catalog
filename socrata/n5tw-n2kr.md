# Water Well and Closed Loop Well Examination Dates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-well-and-closed-loop-well-examination-dates-e5e6a) |
| Metadata | [Link](https://data.illinois.gov/api/views/n5tw-n2kr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/n5tw-n2kr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/n5tw-n2kr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | n5tw-n2kr |
| Name | Water Well and Closed Loop Well Examination Dates |
| Attribution | Illinois Department of Public Health - Division of Environmental Health |
| Category | Public Health |
| Tags | closed loop, water, well, exam |
| Created | 2014-10-10T20:02:26Z |
| Publication Date | 2014-10-29T14:57:43Z |

## Description

New Water Well Installation and Pump Installation Contractors are required to take an examination in order to receive a license to install water wells or water well pumps in Illinois.  Closed Well Contractors may be required to take an examination as well.  The examination dates are presented here.  Last Updated October 2014

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | examination_type     | EXAMINATION TYPE     | text          | text          |
| Yes      | time        | examination_date     | EXAMINATION DATE     | calendar_date | calendar_date |
| Yes      | series tag  | requirements         | REQUIREMENTS         | text          | text          |
| Yes      | series tag  | examination_location | EXAMINATION LOCATION | text          | text          |
| No       |             | examination_address  | EXAMINATION ADDRESS  | text          | text          |
| Yes      | series tag  | examination_city     | EXAMINATION CITY     | text          | text          |
| Yes      | series tag  | examination_state    | EXAMINATION STATE    | text          | text          |
| Yes      | series tag  | examination_zipcode  | EXAMINATION ZIPCODE  | text          | number        |
| Yes      | series tag  | examination_times    | EXAMINATION TIMES    | text          | text          |
| Yes      | series tag  | phone                | Phone                | text          | text          |
```

## Time Field

```ls
Value = examination_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = examination_address
```

## Data Commands

```ls
series e:n5tw-n2kr d:2015-04-17T00:00:00.000Z t:phone=217-782-5830 t:examination_type="Water Well and/or Pump Installation Contractor Examination" t:examination_city=Springfield t:examination_location="Illinois Department of Natural Resources" t:examination_state=IL t:examination_times="Letter of Admission will be sent electronically after examination applications have been approved.  It will specify examination time." t:requirements="Applications must be in Springfield at least 45 days before date of examination.  Incomplete applications will be returned." t:examination_zipcode=62702 m:row_number.n5tw-n2kr=1

series e:n5tw-n2kr d:2015-10-16T00:00:00.000Z t:phone=217-782-5830 t:examination_type="Water Well and/or Pump Installation Contractor Examination" t:examination_city=Springfield t:examination_location="Illinois Department of Natural Resources" t:examination_state=IL t:examination_times="Letter of Admission will be sent electronically after examination applications have been approved.  It will specify examination time." t:requirements="Applications must be in Springfield at least 45 days before date of examination.  Incomplete applications will be returned." t:examination_zipcode=62702 m:row_number.n5tw-n2kr=2

series e:n5tw-n2kr d:2015-04-17T00:00:00.000Z t:phone=217-782-5830 t:examination_type="Closed Loop Contractor Certification" t:examination_city=Springfield t:examination_location="Illinois Department of Natural Resources" t:examination_state=IL t:examination_times="Letter of Admission will be sent electronically after examination applications have been approved.  It will specify examination time." t:requirements="Applications must be in Springfield at least 45 days before date of examination.  Incomplete applications will be returned." t:examination_zipcode=62702 m:row_number.n5tw-n2kr=3
```

## Meta Commands

```ls
metric m:row_number.n5tw-n2kr p:long l:"Row Number"

entity e:n5tw-n2kr l:"Water Well and Closed Loop Well Examination Dates" t:attribution="Illinois Department of Public Health - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/n5tw-n2kr

property e:n5tw-n2kr t:meta.view v:id=n5tw-n2kr v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/private-water v:averageRating=0 v:name="Water Well and Closed Loop Well Examination Dates" v:attribution="Illinois Department of Public Health - Division of Environmental Health"

property e:n5tw-n2kr t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:n5tw-n2kr t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| examination_type                                           | examination_date    | requirements                                                                                                               | examination_location                     | examination_address       | examination_city | examination_state | examination_zipcode | examination_times                                                                                                                    | phone        | 
| ========================================================== | =================== | ========================================================================================================================== | ======================================== | ========================= | ================ | ================= | =================== | ==================================================================================================================================== | ============ | 
| Water Well and/or Pump Installation Contractor Examination | 2015-04-17T00:00:00 | Applications must be in Springfield at least 45 days before date of examination. Incomplete applications will be returned. | Illinois Department of Natural Resources | One Natural Resources Way | Springfield      | IL                | 62702               | Letter of Admission will be sent electronically after examination applications have been approved. It will specify examination time. | 217-782-5830 | 
| Water Well and/or Pump Installation Contractor Examination | 2015-10-16T00:00:00 | Applications must be in Springfield at least 45 days before date of examination. Incomplete applications will be returned. | Illinois Department of Natural Resources | One Natural Resources Way | Springfield      | IL                | 62702               | Letter of Admission will be sent electronically after examination applications have been approved. It will specify examination time. | 217-782-5830 | 
| Closed Loop Contractor Certification                       | 2015-04-17T00:00:00 | Applications must be in Springfield at least 45 days before date of examination. Incomplete applications will be returned. | Illinois Department of Natural Resources | One Natural Resources Way | Springfield      | IL                | 62702               | Letter of Admission will be sent electronically after examination applications have been approved. It will specify examination time. | 217-782-5830 | 
| Closed Loop Contractor Certification                       | 2015-10-16T00:00:00 | Applications must be in Springfield at least 45 days before date of examination. Incomplete applications will be returned. | Illinois Department of Natural Resources | One Natural Resources Way | Springfield      | IL                | 62702               | Letter of Admission will be sent electronically after examination applications have been approved. It will specify examination time. | 217-782-5830 | 
```