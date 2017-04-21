# Open Data Planning Compliance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-planning-compliance) |
| Metadata | [Link](https://data.wa.gov/api/views/9f5q-vk4q) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9f5q-vk4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9f5q-vk4q/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9f5q-vk4q |
| Name | Open Data Planning Compliance |
| Attribution | OCIO |
| Tags | governance, compliance |
| Created | 2016-08-11T15:32:57Z |
| Publication Date | 2017-03-14T17:39:36Z |

## Description

OCIO policy 187 requires agencies to adopt open data plans annually. This table identifies the plans received by OCIO.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | entity_id            | Entity ID            | text          | text          |
| Yes      | series tag     | looked_up_name       | Looked-up Name       | dataset_link  | dataset_link  |
| Yes      | series tag     | entity_name          | Filing Name          | text          | text          |
| Yes      | time           | date_of_report       | Date of Report       | calendar_date | calendar_date |
| Yes      | numeric metric | reporting_period     | Reporting Period     | number        | number        |
| Yes      | numeric metric | reporting_sub_period | Reporting Sub-period | number        | number        |
| Yes      | numeric metric | commitment_a         | Plan                 | number        | number        |
| Yes      | numeric metric | commitment_b         | Do                   | number        | number        |
| Yes      | numeric metric | commitment_c         | Check                | number        | number        |
| Yes      | numeric metric | commitment_d         | Adjust               | number        | number        |
| Yes      | numeric metric | commitment_e         | Consult              | number        | number        |
| Yes      | numeric metric | score_aggregate      | Score                | number        | number        |
| Yes      | series tag     | reference_or_link    | Reference or Link    | url           | url           |
| Yes      | series tag     | attachment           | Attachment           | document      | document      |
```

## Time Field

```ls
Value = date_of_report
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9f5q-vk4q d:2016-04-08T00:00:00.000Z t:attachment.size=39411 t:attachment.filename="Open Data Plan - ARTS fina.docx" t:attachment.file_id=5170efd8-8330-4672-8434-0fd4a9fdfd97 t:entity_id=ART t:attachment.content_type="application/vnd.openxmlformats-officedocument.wordprocessingml.document; charset=binary" t:looked_up_name=ART m:commitment_b=1 m:commitment_e=1 m:score_aggregate=3 m:commitment_a=2 m:reporting_period=2016 m:reporting_sub_period=1

series e:9f5q-vk4q d:2016-04-12T00:00:00.000Z t:entity_id=OMWBE t:looked_up_name=WBE m:commitment_e=1 m:score_aggregate=1 m:reporting_period=2016 m:reporting_sub_period=2

series e:9f5q-vk4q d:2016-10-28T00:00:00.000Z t:attachment.size=373819 t:attachment.filename="ECY Open Data Plan Final.pdf" t:attachment.file_id=41e0cffc-7a0c-463d-89c0-fa990847bb60 t:entity_id=ECY t:reference_or_link=http://www.ecy.wa.gov/databases/OpenDataPlan2016.html t:attachment.content_type="application/pdf; charset=binary" t:looked_up_name=ECY m:commitment_b=2 m:commitment_e=1 m:score_aggregate=3 m:commitment_a=2 m:reporting_period=2016 m:reporting_sub_period=4
```

## Meta Commands

```ls
metric m:reporting_period p:integer l:"Reporting Period" d:"The period for which the entity is required to comply. Usually a calendar year" t:dataTypeName=number

metric m:reporting_sub_period p:integer l:"Reporting Sub-period" d:"Sub-unit of the reporting period, for example, the quarter of the calendar year" t:dataTypeName=number

metric m:commitment_a p:integer l:Plan d:"Does the agency have an open data plan? Max = 2" t:dataTypeName=number

metric m:commitment_b p:integer l:Do d:"Is the agency executing its commitments under the plan? Max = 3" t:dataTypeName=number

metric m:commitment_c p:integer l:Check d:"Has the agency checked with stakeholders to see whether its open data plan is working? Max = 2" t:dataTypeName=number

metric m:commitment_d p:long l:Adjust d:"Has the agency adjusted its open data plan based on feedback or past years' experience? Max = 2" t:dataTypeName=number

metric m:commitment_e p:integer l:Consult d:"Extra credit: has the OCIO consulted with the agency to help develop or adjust the open data plan? Max = 1" t:dataTypeName=number

metric m:score_aggregate p:integer l:Score d:"Overall score for this entity in this period." t:dataTypeName=number

entity e:9f5q-vk4q l:"Open Data Planning Compliance" t:attribution=OCIO t:url=https://data.wa.gov/api/views/9f5q-vk4q

property e:9f5q-vk4q t:meta.view v:id=9f5q-vk4q v:averageRating=0 v:name="Open Data Planning Compliance" v:attribution=OCIO

property e:9f5q-vk4q t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:9f5q-vk4q t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| entity_id | looked_up_name | entity_name           | date_of_report      | reporting_period | reporting_sub_period | commitment_a | commitment_b | commitment_c | commitment_d | commitment_e | score_aggregate | reference_or_link                                                    | attachment                                                                                                                                                                        | 
| ========= | ============== | ===================== | =================== | ================ | ==================== | ============ | ============ | ============ | ============ | ============ | =============== | ==================================================================== | ================================================================================================================================================================================= | 
| ART       | ART            |                       | 2016-04-08T00:00:00 | 2016             | 1                    | 2            | 1            |              |              | 1            | 3               | [null, null]                                                         | [application/vnd.openxmlformats-officedocument.wordprocessingml.document; charset=binary, 5170efd8-8330-4672-8434-0fd4a9fdfd97, Open Data Plan - ARTS fina.docx, 39411]           | 
| OMWBE     | WBE            |                       | 2016-04-12T00:00:00 | 2016             | 2                    |              |              |              |              | 1            | 1               | [null, null]                                                         | [null, null, null, null]                                                                                                                                                          | 
| ECY       | ECY            |                       | 2016-10-28T00:00:00 | 2016             | 4                    | 2            | 2            |              |              | 1            | 3               | [http://www.ecy.wa.gov/databases/OpenDataPlan2016.html, ECY Website] | [application/pdf; charset=binary, 41e0cffc-7a0c-463d-89c0-fa990847bb60, ECY Open Data Plan Final.pdf, 373819]                                                                     | 
| OEO       |                | Education Ombuds      | 2016-04-11T00:00:00 | 2016             |                      |              |              |              |              | 1            | 1               | [null, null]                                                         | [null, null, null, null]                                                                                                                                                          | 
| DVA       | DVA            |                       | 2016-08-05T00:00:00 | 2016             | 3                    | 2            |              |              |              | 1            | 3               | [http://www.dva.wa.gov/node/259, DVA website]                        | [application/vnd.openxmlformats-officedocument.wordprocessingml.document; charset=binary, 7e585de2-de8e-4122-b189-a651c4995080, WDVA Open Data Plan.docx, 16111]                  | 
| OAH       | OAH            |                       | 2016-05-18T00:00:00 | 2016             | 2                    | 2            |              |              |              | 1            | 3               | [null, null]                                                         | [application/msword; charset=binary, e50fa4df-09a5-46af-ab7b-4c81872ce3a6, OAH - Open Data Program.docx, 55665]                                                                   | 
| HCA       |                | Health Care Authority | 2016-09-29T00:00:00 | 2016             | 3                    | 2            | 2            |              |              | 1            | 4               | [http://hca.wa.gov/assets/program/open-data-plan.pdf, HCA website]   | [application/msword; charset=binary, dbdbf349-cca2-47a2-9031-2f733c1a7a3e, HCA Open Data Plan as of- 9-29-2016-final.doc, 653824]                                                 | 
| DEL       | DEL            |                       | 2016-08-08T00:00:00 | 2016             | 3                    | 2            |              |              |              | 1            | 3               | [null, null]                                                         | [application/msword; charset=binary, 33f6da33-3d42-4e91-b122-ffb9608a7f0b, DEL-Open Data Plan 01Aug2016.docx, 79806]                                                              | 
| WaTech    | CTS            | WaTech                | 2016-08-29T00:00:00 | 2016             | 3                    |              |              |              |              | 1            | 1               | [null, null]                                                         | [null, null, null, null]                                                                                                                                                          | 
| DFI       | DFI            |                       | 2016-09-29T00:00:00 | 2016             | 3                    | 2            |              |              |              | 1            | 3               | [null, null]                                                         | [application/vnd.openxmlformats-officedocument.wordprocessingml.document; charset=binary, cee2df15-0131-4aa5-8fd9-53d036eafeaf, DFI Open Data Sharing Plan 9 21 2016.docx, 47803] | 
```