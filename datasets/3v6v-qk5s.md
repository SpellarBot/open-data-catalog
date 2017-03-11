# State Drug Utilization Data 2016

## Dataset

* [Dataset URL](https://data.medicaid.gov/api/views/3v6v-qk5s/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/state-drug-utilization-data-2016)
* Id = 3v6v-qk5s
* Name = State Drug Utilization Data 2016
* Attribution = Centers for Medicare and Medicaid
* Attribution Link = https://medicaid.gov
* Category = State Drug Utilization
* Tags = [drug utilization, medicaid reimbursements, pharmacy]
* Created = 2016-08-01T19:24:51Z
* Publication Date = 2016-11-01T15:23:45Z
* Rows Updated = 2017-02-03T08:51:25Z

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Name                           | Field Name                     | Data Type     | Render Type   | Schema Type    | Included | 
| ============================== | ============================== | ============= | ============= | ============== | ======== | 
| Utilization Type               | utilization_type               | text          | text          | series tag     | Yes      | 
| State                          | state_code                     | text          | text          | series tag     | Yes      | 
| Labeler Code                   | labeler_code                   | text          | text          | series tag     | Yes      | 
| Product Code                   | product_code                   | text          | text          | series tag     | Yes      | 
| Package Size                   | package_size                   | number        | text          | numeric metric | Yes      | 
| Year                           | period_covered                 | number        | text          | numeric metric | Yes      | 
| Quarter                        | quarter                        | number        | text          | numeric metric | Yes      | 
| Product Name                   | product_fda_list_name          | text          | text          | series tag     | Yes      | 
| Suppression Used               | suppression_used               | checkbox      | checkbox      | series tag     | Yes      | 
| Units Reimbursed               | units_reimbursed               | number        | number        | numeric metric | Yes      | 
| Number of Prescriptions        | number_of_prescriptions        | number        | number        | numeric metric | Yes      | 
| Total Amount Reimbursed        | total_amount_reimbursed        | number        | number        | numeric metric | Yes      | 
| Medicaid Amount Reimbursed     | medicaid_amount_reimbursed     | number        | number        | numeric metric | Yes      | 
| Non Medicaid Amount Reimbursed | non_medicaid_amount_reimbursed | number        | number        | numeric metric | Yes      | 
| Quarter begin                  | _quarter_begin                 | text          | text          | series tag     | Yes      | 
| Quarter Begin Date             | _quarter_begin_date            | calendar_date | calendar_date | time           | Yes      | 
| _latitude                      | _latitude                      | number        | number        | numeric metric | Yes      | 
| _longitude                     | _longitude                     | number        | number        | numeric metric | Yes      | 
| NDC                            | ndc                            | number        | text          | numeric metric | Yes      | 
```

## Time Field

```ls
Value = _quarter_begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:_quarter_begin=1/1 t:utilization_type=FFSU t:suppression_used=true m:_latitude=61.385 m:package_size=1 m:ndc=2445301 m:_longitude=-152.2683 m:period_covered=2016 m:quarter=1

series e:3v6v-qk5s d:2016-04-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:_quarter_begin=4/1 t:utilization_type=FFSU t:suppression_used=true m:_latitude=61.385 m:package_size=1 m:ndc=2445301 m:_longitude=-152.2683 m:period_covered=2016 m:quarter=2

series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:_quarter_begin=1/1 t:utilization_type=FFSU t:suppression_used=true m:_latitude=61.385 m:package_size=85 m:ndc=2445385 m:_longitude=-152.2683 m:period_covered=2016 m:quarter=1
```

## Meta Commands

```ls
metric m:package_size p:integer l:"Package Size" t:dataTypeName=number

metric m:period_covered p:integer l:Year t:dataTypeName=number

metric m:quarter p:integer l:Quarter t:dataTypeName=number

metric m:units_reimbursed l:"Units Reimbursed" t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" t:dataTypeName=number

metric m:total_amount_reimbursed l:"Total Amount Reimbursed" t:dataTypeName=number

metric m:medicaid_amount_reimbursed l:"Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed l:"Non Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:_latitude l:_latitude t:dataTypeName=number

metric m:_longitude l:_longitude t:dataTypeName=number

metric m:ndc p:long l:NDC t:dataTypeName=number

entity e:3v6v-qk5s l:"State Drug Utilization Data 2016" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/3v6v-qk5s

property e:3v6v-qk5s t:meta.view d:2017-03-03T14:26:28.326Z v:id=3v6v-qk5s v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2016" v:attribution="Centers for Medicare and Medicaid"

property e:3v6v-qk5s t:meta.view.license d:2017-03-03T14:26:28.326Z v:name="Public Domain"

property e:3v6v-qk5s t:meta.view.owner d:2017-03-03T14:26:28.326Z v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:displayName="Jeff Chamblee"

property e:3v6v-qk5s t:meta.view.tableauthor d:2017-03-03T14:26:28.326Z v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:displayName="Jeff Chamblee"

property e:3v6v-qk5s t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:26:28.326Z v:Bureau_Code=009:00 v:Program_Code=009:076
```