# State Drug Utilization Data 2005

## Dataset

* [Dataset URL](https://data.medicaid.gov/api/views/ezjn-vqh8/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/state-drug-utilization-data-2005)
* Id = ezjn-vqh8
* Name = State Drug Utilization Data 2005
* Attribution = Centers for Medicare and Medicaid
* Attribution Link = https://medicaid.gov
* Category = State Drug Utilization
* Tags = [drug utilization, medicaid reimbursements, pharmacy]
* Created = 2015-06-11T13:23:15Z
* Publication Date = 2016-08-29T22:58:27Z
* Rows Updated = 2017-02-03T02:30:37Z

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Name                           | Field Name                     | Data Type     | Render Type   | Schema Type    | Included | 
| ============================== | ============================== | ============= | ============= | ============== | ======== | 
| Utilization Type               | record_id                      | text          | text          | series tag     | Yes      | 
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
| Quarter Begin                  | _quarter_begin                 | text          | text          | series tag     | Yes      | 
| Quarter Begin Date             | _quarter_begin_date            | calendar_date | calendar_date | time           | Yes      | 
| Latitude                       | _latitude                      | number        | number        | numeric metric | Yes      | 
| Longitude                      | _longitude                     | number        | number        | numeric metric | Yes      | 
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
series e:ezjn-vqh8 d:2005-04-01T00:00:00.000Z t:product_fda_list_name=INTAL t:state_code=MO t:labeler_code=60793 t:product_code=0011 t:_quarter_begin=4/1 t:suppression_used=false t:record_id=FFSU m:_latitude=38.4623 m:package_size=8 m:ndc=60793001108 m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2953.32 m:number_of_prescriptions=38 m:_longitude=-92.302 m:units_reimbursed=364.5 m:period_covered=2005 m:non_medicaid_amount_reimbursed=0 m:quarter=2

series e:ezjn-vqh8 d:2005-01-01T00:00:00.000Z t:product_fda_list_name=LACTULOSE t:state_code=VA t:labeler_code=50383 t:product_code=0795 t:_quarter_begin=1/1 t:suppression_used=false t:record_id=FFSU m:_latitude=37.768 m:package_size=16 m:ndc=50383079516 m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=6713.48 m:number_of_prescriptions=432 m:_longitude=-78.2057 m:units_reimbursed=255853 m:period_covered=2005 m:non_medicaid_amount_reimbursed=0 m:quarter=1

series e:ezjn-vqh8 d:2005-01-01T00:00:00.000Z t:product_fda_list_name="ESTRING VA" t:state_code=NE t:labeler_code=00013 t:product_code=2150 t:_quarter_begin=1/1 t:suppression_used=true t:record_id=FFSU m:_latitude=41.1289 m:package_size=36 m:ndc=13215036 m:_longitude=-98.2883 m:period_covered=2005 m:quarter=1
```

## Meta Commands

```ls
metric m:package_size p:integer l:"Package Size" d:"Third segment of National Drug Code (NDC3) identifies package forms and sizes." t:dataTypeName=number

metric m:period_covered p:integer l:Year d:"Calendar year" t:dataTypeName=number

metric m:quarter p:integer l:Quarter d:"Quarter of year (1-4) 1 = January 1 ? March 31, 2 = April 1 ? June 30, 3 = July 1 ? September 30, 4 = October 1 ? December 31" t:dataTypeName=number

metric m:units_reimbursed l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

metric m:_latitude l:Latitude d:"Location within state. Derived from state code provides ability to create maps and geographic comparisons." t:dataTypeName=number

metric m:_longitude l:Longitude d:"Location within state. Derived from state code provides ability to create maps and geographic comparisons." t:dataTypeName=number

metric m:ndc p:long l:NDC t:dataTypeName=number

entity e:ezjn-vqh8 l:"State Drug Utilization Data 2005" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ezjn-vqh8

property e:ezjn-vqh8 t:meta.view d:2017-03-03T14:24:53.846Z v:id=ezjn-vqh8 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2005" v:attribution="Centers for Medicare and Medicaid"

property e:ezjn-vqh8 t:meta.view.license d:2017-03-03T14:24:53.846Z v:name="Public Domain"

property e:ezjn-vqh8 t:meta.view.owner d:2017-03-03T14:24:53.846Z v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ezjn-vqh8 t:meta.view.tableauthor d:2017-03-03T14:24:53.846Z v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ezjn-vqh8 t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:24:53.846Z v:Bureau_Code=009:00 v:Program_Code=009:076
```