# State University Construction Fund (SUCF) Request for Qualifications (RFQs) Distributed: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-request-for-qualifications-rfqs-distributed-beginn) |
| Metadata | [Link](https://data.ny.gov/api/views/inze-5yed) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/inze-5yed/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/inze-5yed/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | inze-5yed |
| Name | State University Construction Fund (SUCF) Request for Qualifications (RFQs) Distributed: Beginning 2000 |
| Attribution | State University Construction Fund |
| Category | Education |
| Tags | state university construction fund, sucf, construction, contract, education, capital, suny |
| Created | 2014-01-24T16:46:16Z |
| Publication Date | 2017-04-01T10:22:35Z |

## Description

Listing of firms requesting information on design procurements

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | project                 | Project                 | text          | text          |
| Yes      | series tag  | campus_name             | Campus name             | text          | text          |
| Yes      | series tag  | project_title           | Project Title           | text          | text          |
| Yes      | time        | contract_advertise_date | Contract Advertise Date | calendar_date | calendar_date |
| Yes      | series tag  | company_name            | Company Name            | text          | text          |
```

## Time Field

```ls
Value = contract_advertise_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:inze-5yed d:2015-09-11T00:00:00.000Z t:project=011006-00 t:project_title="Upgrade Central Plant - SUCF" t:company_name="Accu-Cost Construction Consultants, Inc. - WBE" t:campus_name="State University of New York at Albany" m:row_number.inze-5yed=1

series e:inze-5yed d:2015-09-11T00:00:00.000Z t:project=011006-00 t:project_title="Upgrade Central Plant - SUCF" t:company_name="AG Consulting Engineering PC" t:campus_name="State University of New York at Albany" m:row_number.inze-5yed=2

series e:inze-5yed d:2015-09-11T00:00:00.000Z t:project=011006-00 t:project_title="Upgrade Central Plant - SUCF" t:company_name="Amoia Cody Architecture D.P.C." t:campus_name="State University of New York at Albany" m:row_number.inze-5yed=3
```

## Meta Commands

```ls
metric m:row_number.inze-5yed p:long l:"Row Number"

entity e:inze-5yed l:"State University Construction Fund (SUCF) Request for Qualifications (RFQs) Distributed: Beginning 2000" t:attribution="State University Construction Fund" t:url=https://data.ny.gov/api/views/inze-5yed

property e:inze-5yed t:meta.view v:id=inze-5yed v:category=Education v:attributionLink=http://sucf.suny.edu v:averageRating=0 v:name="State University Construction Fund (SUCF) Request for Qualifications (RFQs) Distributed: Beginning 2000" v:attribution="State University Construction Fund"

property e:inze-5yed t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:inze-5yed t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:inze-5yed t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project   | campus_name                            | project_title                | contract_advertise_date | company_name                                       | 
| ========= | ====================================== | ============================ | ======================= | ================================================== | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | Accu-Cost Construction Consultants, Inc. - WBE     | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | AG Consulting Engineering PC                       | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | Amoia Cody Architecture D.P.C.                     | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | architecture+                                      | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | Atlantic Testing Laboratories                      | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | Aubertine and Currier Architects, Engineers and LS | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | Bergmann Associates                                | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | C&S Companies                                      | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | C.T. Male Associates                               | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF | 2015-09-11T00:00:00     | Cameron Engineering & Associates, LLP              | 
```