# IDPH Free Standing Emergency Center Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-free-standing-emergency-center-directory-3b1bc) |
| Metadata | [Link](https://data.illinois.gov/api/views/f5p7-mh8n) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/f5p7-mh8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/f5p7-mh8n/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | f5p7-mh8n |
| Name | IDPH Free Standing Emergency Center Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | free standing, emergency center |
| Created | 2012-01-30T19:37:10Z |
| Publication Date | 2017-01-06T18:08:38Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | freestanding_emergency_center | Freestanding Emergency Center | text      | text        |
| No       |             | address                       | Address                       | text      | text        |
| Yes      | series tag  | city                          | City                          | text      | text        |
| Yes      | series tag  | zip                           | Zip                           | text      | text        |
| Yes      | series tag  | county                        | County                        | text      | text        |
| Yes      | series tag  | phone                         | Phone                         | phone     | phone       |
| Yes      | series tag  | license_                      | License #                     | text      | text        |
| Yes      | series tag  | license_expiration_date       | License Expiration Date       | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:f5p7-mh8n d:2017-01-06T18:07:20.000Z t:license_=22005 t:zip=60560 t:license_expiration_date=03/16/17 t:phone_number="(630) 466-8200" t:county=Kendall t:freestanding_emergency_center="Copley Memorial Hospital-Freestanding Emergency Center" t:city=Yorkville m:row_number.f5p7-mh8n=1

series e:f5p7-mh8n d:2017-01-06T18:07:20.000Z t:license_=22003 t:zip=60585 t:license_expiration_date=09/10/17 t:phone_number="(815) 731-3000" t:county=Will t:freestanding_emergency_center="Edward Plainfield Emergency Center" t:city=Plainfield m:row_number.f5p7-mh8n=2

series e:f5p7-mh8n d:2017-01-06T18:07:21.000Z t:license_=22002 t:zip=60030 t:license_expiration_date=09/23/17 t:phone_number="(847) 535-8950" t:county=Lake t:freestanding_emergency_center="Lake Forest Hospital Freestanding Emergency Center" t:city=Grayslake m:row_number.f5p7-mh8n=3
```

## Meta Commands

```ls
metric m:row_number.f5p7-mh8n p:long l:"Row Number"

entity e:f5p7-mh8n l:"IDPH Free Standing Emergency Center Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/f5p7-mh8n

property e:f5p7-mh8n t:meta.view v:id=f5p7-mh8n v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Free Standing Emergency Center Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:f5p7-mh8n t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:f5p7-mh8n t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | freestanding_emergency_center                             | address                           | city        | zip   | county   | phone                  | license_ | license_expiration_date | 
| =========== | ========================================================= | ================================= | =========== | ===== | ======== | ====================== | ======== | ======================= | 
| 1483726040  | Copley Memorial Hospital-Freestanding Emergency Center    | 1122 W. Veterans Parkway          | Yorkville   | 60560 | Kendall  | [(630) 466-8200, null] | 22005    | 03/16/17                | 
| 1483726040  | Edward Plainfield Emergency Center                        | 24600 W. 127th Street             | Plainfield  | 60585 | Will     | [(815) 731-3000, null] | 22003    | 09/10/17                | 
| 1483726041  | Lake Forest Hospital Freestanding Emergency Center        | 1475 E. Belvidere Road, Suite 211 | Grayslake   | 60030 | Lake     | [(847) 535-8950, null] | 22002    | 09/23/17                | 
| 1483726041  | Lindenhurst Freestanding Emergency Center                 | 1050 Red Oak Lane                 | Lindenhurst | 60046 | Lake     | [(847) 356-4705, null] | 22004    | 07/14/17                | 
| 1483726041  | OSF Saint Elizabeth Med Ctr Freestanding Emergency Center | 111 Spring Street                 | Streator    | 61364 | La Salle | [(815) 431-5456, null] | 22006    | 08/08/17                | 
| 1483726041  | Silver Cross Emergicare Center                            | 12701 West 143rd Street           | Homer Glen  | 60491 | Will     | [(708) 364-6337, null] | 22001    | 07/15/17                | 
```