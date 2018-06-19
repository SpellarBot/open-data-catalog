# OpenNY Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/openny-reports) |
| Metadata | [Link](https://data.ny.gov/api/views/jabi-xxkk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jabi-xxkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jabi-xxkk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jabi-xxkk |
| Name | OpenNY Reports |
| Created | 2014-07-01T14:33:03Z |
| Publication Date | 2017-04-10T18:08:02Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name                  | Data Type     | Render Type   |
| ======== | =========== | ============ | ===================== | ============= | ============= |
| Yes      | time        | report_year  | Report Published Date | calendar_date | calendar_date |
| Yes      | series tag  | report_title | Report Title          | text          | text          |
| Yes      | series tag  | report_link  | Report Link           | url           | url           |
| Yes      | series tag  | report_type  | Report Type           | text          | text          |
```

## Time Field

```ls
Value = report_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jabi-xxkk d:2014-07-01T00:00:00.000Z t:report_link=https://data.ny.gov/download/aif5-3peb/application/pdf t:report_type="Quarterly Report" t:report_title="OpenNY Quarterly Report" m:row_number.jabi-xxkk=1

series e:jabi-xxkk d:2014-10-01T00:00:00.000Z t:report_link=https://data.ny.gov/download/xvqc-w2ea/application/pdf t:report_type="Quarterly Report" t:report_title="OpenNY Quarterly Report" m:row_number.jabi-xxkk=2

series e:jabi-xxkk d:2015-01-01T00:00:00.000Z t:report_link=https://data.ny.gov/download/qmwf-qn3t/application/pdf t:report_type="Quarterly Report" t:report_title="OpenNY Quarterly Report" m:row_number.jabi-xxkk=3
```

## Meta Commands

```ls
metric m:row_number.jabi-xxkk p:long l:"Row Number"

entity e:jabi-xxkk l:"OpenNY Reports" t:url=https://data.ny.gov/api/views/jabi-xxkk

property e:jabi-xxkk t:meta.view v:id=jabi-xxkk v:averageRating=0 v:name="OpenNY Reports"

property e:jabi-xxkk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jabi-xxkk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jabi-xxkk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| report_year         | report_title                       | report_link                                                    | report_type                 | 
| =================== | ================================== | ============================================================== | =========================== | 
| 2014-07-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/aif5-3peb/application/pdf, null] | Quarterly Report            | 
| 2014-10-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/xvqc-w2ea/application/pdf, null] | Quarterly Report            | 
| 2015-01-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/qmwf-qn3t/application/pdf, null] | Quarterly Report            | 
| 2014-03-01T00:00:00 | OpenNY One-year Anniversary Report | [https://data.ny.gov/download/smp8-sauy/application/pdf, null] | One-year Anniversary Report | 
| 2015-04-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/fki5-gc4g/application/pdf, null] | Quarterly Report            | 
| 2015-07-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/csj5-36ce/application/pdf, null] | Quarterly Report            | 
| 2015-10-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/8p6k-aqvm/application/pdf, null] | Quarterly Report            | 
| 2016-01-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/r8cg-6b9z/application/pdf, null] | Quarterly Report            | 
| 2016-04-01T00:00:00 | OpenNY Quarterly Report            | [https://data.ny.gov/download/37tu-akvr/application/pdf, null] | Quarterly Report            | 
| 2015-05-01T00:00:00 | OpenNY 2015 Annual Report          | [https://www.ny.gov/open-ny/2015-open-ny-annual-report, null]  | Annual Report               | 
```