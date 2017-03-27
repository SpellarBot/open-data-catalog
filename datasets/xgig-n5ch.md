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
| Publication Date | 2017-02-08T23:03:41Z |

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
series e:xgig-n5ch d:2017-01-18T12:08:00.000Z t:rate_code_group="Clinic Treatment" t:county_label=Allegany t:age_group=ADULT t:omh_region_label="Western NY" t:omh_region_code=1 m:recipient_count_by_county=443 m:paid_claim_total=273141 m:units_total=2674 m:count_of_recipients_by_rate_code_group_and_county=345

series e:xgig-n5ch d:2017-01-18T12:08:00.000Z t:rate_code_group="Community Residence" t:county_label=Allegany t:age_group=ADULT t:omh_region_label="Western NY" t:omh_region_code=1 m:recipient_count_by_county=443 m:paid_claim_total=289091 m:units_total=128 m:count_of_recipients_by_rate_code_group_and_county=20

series e:xgig-n5ch d:2017-01-18T12:08:00.000Z t:rate_code_group="Health Home" t:county_label=Allegany t:age_group=ADULT t:omh_region_label="Western NY" t:omh_region_code=1 m:recipient_count_by_county=443 m:paid_claim_total=109393 m:units_total=237 m:count_of_recipients_by_rate_code_group_and_county=33
```

## Meta Commands

```ls
metric m:recipient_count_by_county p:integer l:"Recipient Count By County" d:"Count of distinct Client Identification Numbers by county." t:dataTypeName=number

metric m:count_of_recipients_by_rate_code_group_and_county p:integer l:"Count Of Recipients By Rate Code Group And County" d:"Count of distinct Client Identification Numbers by rate code group and county." t:dataTypeName=number

metric m:units_total p:integer l:"Units Total" d:"Sum of mental health service Units provided. Service Units may be measured in Days or Months depending on service category and provider specialty. (see also: “Notes” link at “http://bi.omh.ny.gov/cmhp/mh-services”)" t:dataTypeName=number

metric m:paid_claim_total p:integer l:"Paid Claim Total" d:"Sum of total payment or reimbursement amount for a claim or claim line." t:dataTypeName=number

entity e:xgig-n5ch l:"County Mental Health Profiles: Beginning 2006" t:attribution="New York State Office of Mental Health" t:url=https://data.ny.gov/api/views/xgig-n5ch

property e:xgig-n5ch t:meta.view v:id=xgig-n5ch v:category="Human Services" v:attributionLink=http://bi.omh.ny.gov/cmhp/mh-services v:averageRating=0 v:name="County Mental Health Profiles: Beginning 2006" v:attribution="New York State Office of Mental Health"

property e:xgig-n5ch t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xgig-n5ch t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:xgig-n5ch t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```