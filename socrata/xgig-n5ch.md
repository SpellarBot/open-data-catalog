# County Mental Health Profiles: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-mental-health-profiles-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/xgig-n5ch) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xgig-n5ch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xgig-n5ch/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xgig-n5ch |
| Name | County Mental Health Profiles: Beginning 2006 |
| Attribution | New York State Office of Mental Health |
| Category | Human Services |
| Tags | community services, medicaid utilization |
| Created | 2014-07-11T21:16:37Z |
| Publication Date | 2017-08-02T22:02:23Z |

## Description

These reports provide summary information about mental health service utilization funded through Medicaid for Local Fiscal Years, beginning in service year 2006 and updated yearly thereafter. Totals are based on date of service and data are refreshed on a monthly basis so values in the same report may change over time. Prepaid Mental Health Plan (PMHP) data are included in these reports as Recovery Services (RS); however, Medicaid Managed Care data are not included. Expenditures include Comprehensive Outpatient Program Services (COPS) and Community Support Program (CSP) add-on payments, where applicable.

## Columns

```ls
| Included | Schema Type    | Field Name                                        | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ================================================= | ================================================= | ============= | ============= |
| Yes      | time           | row_created_date_time                             | Row Created Date Time                             | calendar_date | calendar_date |
| No       |                | service_year                                      | Service Year                                      | number        | number        |
| Yes      | series tag     | omh_region_code                                   | OMH Region Code                                   | text          | number        |
| Yes      | series tag     | omh_region_label                                  | OMH Region Label                                  | text          | text          |
| Yes      | series tag     | county_label                                      | County Label                                      | text          | text          |
| Yes      | series tag     | age_group                                         | Age Group                                         | text          | text          |
| Yes      | series tag     | rate_code_group                                   | Rate Code Group                                   | text          | text          |
| Yes      | numeric metric | recipient_count_by_county                         | Recipient Count By County                         | number        | number        |
| Yes      | numeric metric | count_of_recipients_by_rate_code_group_and_county | Count Of Recipients By Rate Code Group And County | number        | number        |
| Yes      | numeric metric | units_total                                       | Units Total                                       | number        | number        |
| Yes      | numeric metric | paid_claim_total                                  | Paid Claim Total                                  | number        | number        |
```

## Time Field

```ls
Value = row_created_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = service_year
```

## Data Commands

```ls
series e:xgig-n5ch d:2017-07-19T09:44:43.000Z t:rate_code_group="Day Treatment" t:omh_region_code=3 t:county_label=Ulster t:age_group=CHILD t:omh_region_label="Hudson River" m:paid_claim_total=313495 m:recipient_count_by_county=714 m:units_total=953 m:count_of_recipients_by_rate_code_group_and_county=39

series e:xgig-n5ch d:2017-07-19T09:44:43.000Z t:rate_code_group="Family Based Treatment/Teaching Family Home" t:omh_region_code=3 t:county_label=Ulster t:age_group=CHILD t:omh_region_label="Hudson River" m:paid_claim_total=293742 m:recipient_count_by_county=714 m:units_total=40 m:count_of_recipients_by_rate_code_group_and_county=10

series e:xgig-n5ch d:2017-07-19T09:44:43.000Z t:rate_code_group="Psychiatric Inpatient" t:omh_region_code=3 t:county_label=Ulster t:age_group=CHILD t:omh_region_label="Hudson River" m:paid_claim_total=2873 m:recipient_count_by_county=714 m:units_total=3 m:count_of_recipients_by_rate_code_group_and_county=1
```

## Meta Commands

```ls
metric m:recipient_count_by_county p:integer l:"Recipient Count By County" d:"Count of distinct Client Identification Numbers by county." t:dataTypeName=number

metric m:count_of_recipients_by_rate_code_group_and_county p:integer l:"Count Of Recipients By Rate Code Group And County" d:"Count of distinct Client Identification Numbers by rate code group and county." t:dataTypeName=number

metric m:units_total p:float l:"Units Total" d:"Sum of mental health service Units provided. Service Units may be measured in Days or Months depending on service category and provider specialty. (see also: “Notes” link at “http://bi.omh.ny.gov/cmhp/mh-services”)" t:dataTypeName=number

metric m:paid_claim_total p:double l:"Paid Claim Total" d:"Sum of total payment or reimbursement amount for a claim or claim line." t:dataTypeName=number

entity e:xgig-n5ch l:"County Mental Health Profiles: Beginning 2006" t:attribution="New York State Office of Mental Health" t:url=https://data.ny.gov/api/views/xgig-n5ch

property e:xgig-n5ch t:meta.view d:2017-09-25T07:30:20.230Z v:averageRating=0 v:name="County Mental Health Profiles: Beginning 2006" v:attribution="New York State Office of Mental Health" v:attributionLink=http://bi.omh.ny.gov/cmhp/mh-services v:id=xgig-n5ch v:category="Human Services"

property e:xgig-n5ch t:meta.view.owner d:2017-09-25T07:30:20.230Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:xgig-n5ch t:meta.view.tableauthor d:2017-09-25T07:30:20.230Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:xgig-n5ch t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:30:20.230Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| row_created_date_time | service_year | omh_region_code | omh_region_label | county_label | age_group | rate_code_group                             | recipient_count_by_county | count_of_recipients_by_rate_code_group_and_county | units_total | paid_claim_total | 
| ===================== | ============ | =============== | ================ | ============ | ========= | =========================================== | ========================= | ================================================= | =========== | ================ | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Ulster       | CHILD     | Day Treatment                               | 714                       | 39                                                | 953.000     | 313495.00        | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Ulster       | CHILD     | Family Based Treatment/Teaching Family Home | 714                       | 10                                                | 40.000      | 293742.00        | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Ulster       | CHILD     | Psychiatric Inpatient                       | 714                       | 1                                                 | 3.000       | 2873.00          | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Ulster       | CHILD     | Partial Hospitalization                     | 714                       | 32                                                | 416.000     | 51516.00         | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Ulster       | CHILD     | Targeted Case Management (ICM, BCM, SCM)    | 714                       | 40                                                | 191.000     | 105932.00        | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Warren       | ADULT     | Continuing Day Treatment                    | 950                       | 52                                                | 5059.000    | 244036.00        | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Warren       | ADULT     | Clinic Treatment                            | 950                       | 706                                               | 8239.000    | 677531.00        | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Warren       | ADULT     | Community Residence                         | 950                       | 14                                                | 83.000      | 182253.00        | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Warren       | ADULT     | Psychiatric Inpatient                       | 950                       | 273                                               | 2417.000    | 1749725.00       | 
| 2017-07-19T09:44:43   | 2011         | 3               | Hudson River     | Warren       | ADULT     | Targeted Case Management (ICM, BCM, SCM)    | 950                       | 55                                                | 393.000     | 261659.00        | 
```