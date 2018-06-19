# DDS Individuals on a Medicaid Waiver as of 9/30/16

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dds-individuals-on-a-medicaid-waiver-as-of-9-30-16) |
| Metadata | [Link](https://data.ct.gov/api/views/9x9z-wwvd) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9x9z-wwvd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9x9z-wwvd/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9x9z-wwvd |
| Name | DDS Individuals on a Medicaid Waiver as of 9/30/16 |
| Category | Health and Human Services |
| Tags | dds, department of developmental service, medicaid waiver, residence type, region |
| Created | 2016-12-22T14:31:58Z |
| Publication Date | 2016-12-22T14:48:25Z |

## Description

This chart shows the number of DDS individuals on a Medicaid Waiver as of the last day of each quarter in a State Fiscal Year. This information is broken out by the region and type of placement in which they were residing on that day.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | time        | data_as_of           | Data_as_of           | calendar_date | calendar_date |
| Yes      | series tag  | region               | Region               | text          | text          |
| Yes      | series tag  | medicaid_waiver_type | Medicaid_Waiver_Type | text          | text          |
| Yes      | series tag  | residence_type       | Residence_Type       | text          | text          |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9x9z-wwvd d:2016-09-30T00:00:00.000Z t:region=NR t:medicaid_waiver_type="Comprehensive Waiver" t:residence_type=CCH m:row_number.9x9z-wwvd=1

series e:9x9z-wwvd d:2016-09-30T00:00:00.000Z t:region=NR t:medicaid_waiver_type="Comprehensive Waiver" t:residence_type=CCH m:row_number.9x9z-wwvd=2

series e:9x9z-wwvd d:2016-09-30T00:00:00.000Z t:region=NR t:medicaid_waiver_type="Comprehensive Waiver" t:residence_type=CCH m:row_number.9x9z-wwvd=3
```

## Meta Commands

```ls
metric m:row_number.9x9z-wwvd p:long l:"Row Number"

entity e:9x9z-wwvd l:"DDS Individuals on a Medicaid Waiver as of 9/30/16" t:url=https://data.ct.gov/api/views/9x9z-wwvd

property e:9x9z-wwvd t:meta.view v:id=9x9z-wwvd v:category="Health and Human Services" v:averageRating=0 v:name="DDS Individuals on a Medicaid Waiver as of 9/30/16"

property e:9x9z-wwvd t:meta.view.owner v:id=fwn7-mi4m v:screenName="Victoria Berman" v:displayName="Victoria Berman"

property e:9x9z-wwvd t:meta.view.tableauthor v:id=fwn7-mi4m v:screenName="Victoria Berman" v:roleName=editor v:displayName="Victoria Berman"
```

## Top Records

```ls
| data_as_of          | region | medicaid_waiver_type | residence_type | 
| =================== | ====== | ==================== | ============== | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
| 2016-09-30T00:00:00 | NR     | Comprehensive Waiver | CCH            | 
```