# PMMR Raw Data - FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pmmr-raw-data-fy-2013-ad9e5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4fnu-iufz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4fnu-iufz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4fnu-iufz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4fnu-iufz |
| Name | PMMR Raw Data - FY 2013 |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | City Government |
| Tags | ops, mayor's office of operations, pmmr raw data |
| Created | 2013-02-12T09:14:32Z |
| Publication Date | 2013-06-26T17:18:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | agency                | Agency                | text      | text        |
| Yes      | series tag     | indicator_id          | Indicator ID          | text      | text        |
| Yes      | series tag     | indicator_name        | Indicator Name        | text      | text        |
| Yes      | numeric metric | indicator_sequence    | Indicator Sequence    | number    | number      |
| Yes      | series tag     | sub_indicator         | Sub-Indicator         | text      | text        |
| Yes      | numeric metric | subindicator_sequence | Subindicator Sequence | number    | number      |
| Yes      | series tag     | record_type           | Record Type           | text      | text        |
| Yes      | series tag     | desired_direction     | Desired Direction     | text      | text        |
| Yes      | series tag     | critical_flag         | Critical Flag         | text      | text        |
| Yes      | series tag     | geography             | Geography             | text      | text        |
| Yes      | series tag     | measure_type          | Measure Type          | text      | text        |
| Yes      | time           | fiscal_year           | Fiscal Year           | number    | number      |
| Yes      | series tag     | conditional_format    | Conditional Format    | text      | text        |
| Yes      | numeric metric | raw_value             | Raw Value             | number    | number      |
| Yes      | series tag     | format_type           | Format Type           | text      | text        |
| Yes      | numeric metric | value_percent         | Value Percent         | percent   | percent     |
| Yes      | series tag     | value_number          | Value Number          | text      | number      |
| Yes      | numeric metric | value_currency        | Value Currency        | money     | money       |
| No       |                | value_time            | Value Time            | text      | text        |
| Yes      | series tag     | value_ratio           | Value Ratio           | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = value_time
```

## Data Commands

```ls
series e:4fnu-iufz d:2012-01-01T00:00:00.000Z t:value_number=5.74 t:geography=NA t:indicator_name="Medicaid - Existing Applicant or Enrollee" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:format_type=N t:indicator_id=1-E6YH t:agency=HRA m:subindicator_sequence=0 m:raw_value=5.741239686452903 m:indicator_sequence=0

series e:4fnu-iufz d:2013-01-01T00:00:00.000Z t:value_number=12.32 t:geography=NA t:indicator_name="Food Stamp Assistance" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:format_type=N t:indicator_id=1-E6VP t:agency=HRA m:subindicator_sequence=0 m:raw_value=12.322972227331249 m:indicator_sequence=0

series e:4fnu-iufz d:2012-01-01T00:00:00.000Z t:value_number=11.53 t:geography=NA t:indicator_name="Food Stamp Assistance" t:measure_type="% of Inquiries" t:critical_flag=NA t:record_type=INQ t:desired_direction=NA t:format_type=N t:indicator_id=1-E6VP t:agency=HRA m:subindicator_sequence=0 m:raw_value=11.532091255333278 m:indicator_sequence=0
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" t:dataTypeName=number

metric m:subindicator_sequence p:integer l:"Subindicator Sequence" t:dataTypeName=number

metric m:raw_value p:double l:"Raw Value" t:dataTypeName=number

metric m:value_percent p:float l:"Value Percent" t:dataTypeName=percent

metric m:value_currency p:double l:"Value Currency" t:dataTypeName=money

entity e:4fnu-iufz l:"PMMR Raw Data - FY 2013" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/4fnu-iufz

property e:4fnu-iufz t:meta.view v:id=4fnu-iufz v:category="City Government" v:averageRating=0 v:name="PMMR Raw Data - FY 2013" v:attribution="Mayor's Office of Operations (OPS)"

property e:4fnu-iufz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4fnu-iufz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | indicator_id | indicator_name                                          | indicator_sequence | sub_indicator | subindicator_sequence | record_type | desired_direction | critical_flag | geography | measure_type   | fiscal_year | conditional_format | raw_value          | format_type | value_percent | value_number | value_currency | value_time | value_ratio | 
| ====== | ============ | ======================================================= | ================== | ============= | ===================== | =========== | ================= | ============= | ========= | ============== | =========== | ================== | ================== | =========== | ============= | ============ | ============== | ========== | =========== | 
| HRA    | 1-E6YH       | Medicaid - Existing Applicant or Enrollee               | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 5.741239686452903  | N           |               | 5.74         |                |            |             | 
| HRA    | 1-E6VP       | Food Stamp Assistance                                   | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 12.322972227331249 | N           |               | 12.32        |                |            |             | 
| HRA    | 1-E6VP       | Food Stamp Assistance                                   | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 11.532091255333278 | N           |               | 11.53        |                |            |             | 
| HRA    | 1-1-068N1E9  | One Shot Deal - Short Term Emergency Assistance         | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 7.096875903202922  | N           |               | 7.10         |                |            |             | 
| HRA    | 1-1-068N1E9  | One Shot Deal - Short Term Emergency Assistance         | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 5.822145217796164  | N           |               | 5.82         |                |            |             | 
| HRA    | 1-1-00BHDK4  | Food Stamp Center                                       | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 12.541930511398968 | N           |               | 12.54        |                |            |             | 
| HRA    | 1-1-00BHDK4  | Food Stamp Center                                       | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 13.551676499996185 | N           |               | 13.55        |                |            |             | 
| HPD    | 1-6SAH       | Heat Complaint - Residential Building - Inadequate Heat | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 11.039965652782199 | N           |               | 11.04        |                |            |             | 
| HPD    | 1-6SAH       | Heat Complaint - Residential Building - Inadequate Heat | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2012        |                    | 12.991542365062278 | N           |               | 12.99        |                |            |             | 
| HPD    | 1-6S7P       | Landlord Complaint - Maintenance                        | 0                  |               | 0                     | INQ         | NA                | NA            | NA        | % of Inquiries | 2013        |                    | 39.26390359091279  | N           |               | 39.26        |                |            |             | 
```