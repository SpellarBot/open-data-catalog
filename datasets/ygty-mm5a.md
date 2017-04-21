# Payment - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/payment-national) |
| Metadata | [Link](https://data.medicare.gov/api/views/ygty-mm5a) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/ygty-mm5a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/ygty-mm5a/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | ygty-mm5a |
| Name | Payment - National |
| Category | Hospital Compare |
| Tags | hospital compare, medicare payment |
| Created | 2014-11-21T02:03:12Z |
| Publication Date | 2016-12-19T17:07:41Z |

## Description

Payment measures ? national data. This data set includes national-level data for the payment measures associated with a 30-day episode of care for heart attack, heart failure, and pneumonia patients.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ======================================= | ==================================== | ============= | ============= |
| Yes      | series tag     | measure_name                            | Measure name                         | text          | text          |
| Yes      | series tag     | measure_id                              | Measure ID                           | text          | text          |
| Yes      | numeric metric | national_payment                        | National payment                     | money         | money         |
| Yes      | numeric metric | number_less_than_national_payment       | Number less than national payment    | number        | text          |
| Yes      | numeric metric | number_of_same_as_national_payment      | Number same as national payment      | number        | text          |
| Yes      | numeric metric | number_of_greater_than_national_payment | Number greater than national payment | number        | text          |
| Yes      | numeric metric | number_of_hospitals_too_few             | Number of hospitals too few          | number        | text          |
| No       |                | footnote                                | Footnote                             | text          | text          |
| Yes      | time           | measure_start_date                      | Measure start date                   | calendar_date | calendar_date |
| No       |                | measure_end_date                        | Measure end date                     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = footnote,measure_end_date
```

## Data Commands

```ls
series e:ygty-mm5a d:2012-07-01T00:00:00.000Z t:measure_id=PAYM_30_AMI t:measure_name="Payment for heart attack patients" m:national_payment=22760 m:number_less_than_national_payment=182 m:number_of_hospitals_too_few=1912 m:number_of_same_as_national_payment=1971 m:number_of_greater_than_national_payment=255

series e:ygty-mm5a d:2012-07-01T00:00:00.000Z t:measure_id=PAYM_30_HF t:measure_name="Payment for heart failure patients" m:national_payment=15959 m:number_less_than_national_payment=377 m:number_of_hospitals_too_few=939 m:number_of_same_as_national_payment=2702 m:number_of_greater_than_national_payment=617

series e:ygty-mm5a d:2012-07-01T00:00:00.000Z t:measure_id=PAYM_30_PN t:measure_name="Payment for pneumonia patients" m:national_payment=14817 m:number_less_than_national_payment=673 m:number_of_hospitals_too_few=498 m:number_of_same_as_national_payment=2968 m:number_of_greater_than_national_payment=541
```

## Meta Commands

```ls
metric m:national_payment p:integer l:"National payment" t:dataTypeName=money

metric m:number_less_than_national_payment p:integer l:"Number less than national payment" t:dataTypeName=number

metric m:number_of_same_as_national_payment p:integer l:"Number same as national payment" t:dataTypeName=number

metric m:number_of_greater_than_national_payment p:integer l:"Number greater than national payment" t:dataTypeName=number

metric m:number_of_hospitals_too_few p:integer l:"Number of hospitals too few" t:dataTypeName=number

entity e:ygty-mm5a l:"Payment - National" t:url=https://data.medicare.gov/api/views/ygty-mm5a

property e:ygty-mm5a t:meta.view v:id=ygty-mm5a v:category="Hospital Compare" v:averageRating=0 v:name="Payment - National"

property e:ygty-mm5a t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:ygty-mm5a t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:ygty-mm5a t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| measure_name                       | measure_id  | national_payment | number_less_than_national_payment | number_of_same_as_national_payment | number_of_greater_than_national_payment | number_of_hospitals_too_few | footnote | measure_start_date  | measure_end_date    | 
| ================================== | =========== | ================ | ================================= | ================================== | ======================================= | =========================== | ======== | =================== | =================== | 
| Payment for heart attack patients  | PAYM_30_AMI | 22760            | 182                               | 1971                               | 255                                     | 1912                        |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Payment for heart failure patients | PAYM_30_HF  | 15959            | 377                               | 2702                               | 617                                     | 939                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Payment for pneumonia patients     | PAYM_30_PN  | 14817            | 673                               | 2968                               | 541                                     | 498                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
```