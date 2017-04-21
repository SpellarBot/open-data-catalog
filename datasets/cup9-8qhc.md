# Illinois Plumbing Code Ordinance Approvals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-plumbing-code-ordinance-approvals) |
| Metadata | [Link](https://data.illinois.gov/api/views/cup9-8qhc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cup9-8qhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cup9-8qhc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cup9-8qhc |
| Name | Illinois Plumbing Code Ordinance Approvals |
| Attribution | Division of Environmental Health |
| Category | Public Health |
| Tags | plumbing, plumbing code, ordinance |
| Created | 2015-05-26T16:35:29Z |
| Publication Date | 2016-08-18T18:00:24Z |

## Description

Dataset of IDPH approved plumbing ordinances organized by effective amendment date. Attached to dataset is document containing copies of IDPH issued Certificates of Approval bearing adoption and local amendment language. 

*Note: NA = not applicable , TA = tentatively approved

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                          | Data Type     | Render Type   |
| ======== | =========== | ========================== | ============================= | ============= | ============= |
| Yes      | series tag  | unit_of_local_government   | Unit of Local Government      | text          | text          |
| Yes      | time        | effective_date             | Effective Date                | calendar_date | calendar_date |
| No       |             | expiration_date            | Expiration Date               | calendar_date | calendar_date |
| Yes      | series tag  | adoption_s                 | Adoption #(s)                 | text          | text          |
| Yes      | series tag  | local_amendment_approval_s | Local Amendment Approval #(s) | text          | text          |
| Yes      | series tag  | certificates               | Certificates                  | document      | document      |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:cup9-8qhc d:2015-10-15T00:00:00.000Z t:unit_of_local_government=Berwyn t:certificates.file_id=28d73fe8-f945-4585-9fab-c687c42848f5 t:certificates.filename="ApprovalDocs.Berwyn 2-17-16 (SECURED).pdf" t:certificates.size=159831 t:adoption_s=1015-000-034 t:certificates.content_type="application/pdf; charset=binary" t:local_amendment_approval_s=1015-708-0020 m:row_number.cup9-8qhc=1

series e:cup9-8qhc d:2015-09-30T00:00:00.000Z t:unit_of_local_government=Carpentersville t:certificates.file_id=404e107e-79e8-4c08-b529-ce169b2ddfe0 t:certificates.filename="ApprovalDocs.Burr Ridge 1-26-16 (SECURED).pdf" t:certificates.size=169239 t:adoption_s=0915-000-027 t:certificates.content_type="application/pdf; charset=binary" t:local_amendment_approval_s="0915-847-0024, 0915-847-0025, 0915-847-0026, 0915-847-0027, 0915-847-0028, 0915-847-0029, 0915-847-0030, 0915-847-0031, 0915-847-0032, 0915-847-0033, 0915-847-0034, 0915-847-0035, 0915-847-0036, 0915-847-0037, 0915-847-0038, 0915-847-0039, 0915-847-0040" m:row_number.cup9-8qhc=2

series e:cup9-8qhc d:2015-12-28T00:00:00.000Z t:unit_of_local_government="North Riverside" t:certificates.file_id=993d996c-d6fa-46fd-9564-1797cdd7fc1a t:certificates.filename="ApprovalDocs. North Riverside 1-4-16.pdf" t:certificates.size=159954 t:adoption_s=1215-000-042 t:certificates.content_type="application/pdf; charset=binary" t:local_amendment_approval_s=1215-708-0021 m:row_number.cup9-8qhc=3
```

## Meta Commands

```ls
metric m:row_number.cup9-8qhc p:long l:"Row Number"

entity e:cup9-8qhc l:"Illinois Plumbing Code Ordinance Approvals" t:attribution="Division of Environmental Health" t:url=https://data.illinois.gov/api/views/cup9-8qhc

property e:cup9-8qhc t:meta.view v:id=cup9-8qhc v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/plumbing v:averageRating=0 v:name="Illinois Plumbing Code Ordinance Approvals" v:attribution="Division of Environmental Health"

property e:cup9-8qhc t:meta.view.license v:name="Public Domain"

property e:cup9-8qhc t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:cup9-8qhc t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| unit_of_local_government | effective_date      | expiration_date     | adoption_s    | local_amendment_approval_s                                                                                                                                                                                                                                    | certificates                                                                                                                        | 
| ======================== | =================== | =================== | ============= | ============================================================================================================================================================================================================================================================= | =================================================================================================================================== | 
| Berwyn                   | 2015-10-15T00:00:00 | 2018-10-15T00:00:00 | 1015-000-034  | 1015-708-0020                                                                                                                                                                                                                                                 | [application/pdf; charset=binary, 28d73fe8-f945-4585-9fab-c687c42848f5, ApprovalDocs.Berwyn 2-17-16 (SECURED).pdf, 159831]          | 
| Carpentersville          | 2015-09-30T00:00:00 | 2018-09-30T00:00:00 | 0915-000-027  | 0915-847-0024, 0915-847-0025, 0915-847-0026, 0915-847-0027, 0915-847-0028, 0915-847-0029, 0915-847-0030, 0915-847-0031, 0915-847-0032, 0915-847-0033, 0915-847-0034, 0915-847-0035, 0915-847-0036, 0915-847-0037, 0915-847-0038, 0915-847-0039, 0915-847-0040 | [application/pdf; charset=binary, 404e107e-79e8-4c08-b529-ce169b2ddfe0, ApprovalDocs.Burr Ridge 1-26-16 (SECURED).pdf, 169239]      | 
| North Riverside          | 2015-12-28T00:00:00 | 2018-12-28T00:00:00 | 1215-000-042  | 1215-708-0021                                                                                                                                                                                                                                                 | [application/pdf; charset=binary, 993d996c-d6fa-46fd-9564-1797cdd7fc1a, ApprovalDocs. North Riverside 1-4-16.pdf, 159954]           | 
| Oakbrook Terrace         | 2015-10-05T00:00:00 | 2018-10-05T00:00:00 | 1015-000-0030 | 1015-630-0021                                                                                                                                                                                                                                                 | [application/pdf; charset=binary, 81729a2c-0155-4403-ab72-5f4d3c24893c, ApprovalDocs.OakbrookTerrace (SECURED) 2-17-16.pdf, 442959] | 
| Stickney                 | 2015-02-19T00:00:00 |                     | 0215-000-005  |                                                                                                                                                                                                                                                               | [application/pdf; charset=binary, fd02eb4f-e271-4db4-96cc-ffa303eaf5fd, ApprovalDocs.Stickeny 2-17-16 (SECURED).pdf, 148549]        | 
| Westchester              | 2015-12-08T00:00:00 | 2018-12-08T00:00:00 | 1215-000-039  | 1215-847-0046                                                                                                                                                                                                                                                 | [application/pdf; charset=binary, 84848f0b-51c7-4c79-ab3c-9f2b9477da48, Westchester.ApprovalDocs 12-23-15 (SECURED).pdf, 154486]    | 
| Wheeling                 | 2015-08-25T00:00:00 | 2018-08-25T00:00:00 | 0815-000-017  | 0815-847-0003                                                                                                                                                                                                                                                 | [application/pdf; charset=binary, fac78e8c-e0b1-4485-aa97-f3a87fd2d64d, ApprovalDocs.Wheeling (SECURED) 2-17-16.pdf, 158973]        | 
| Addison                  | 2016-01-06T00:00:00 | 2019-01-06T00:00:00 | 0116-000-046  | 0116-630-0027, 0116-630-0028, 0116-630-0029, 0116-630-0030, 0116-630-0031, 0116-630-0032, 0116-630-0033, 0116-630-0034, 0116-630-0035, 0116-630-0036, 0116-630-0037, 0116-630-0038                                                                            | [application/pdf; charset=binary, 1477f9ae-d6eb-43b9-a1a9-0156d1c81270, Addison.ApprovalDocs 1-12-16 (SECURED).pdf, 287817]         | 
| Burbank                  | 2016-01-13T00:00:00 | 2019-01-13T00:00:00 | 0116-000-048  | 0116-708-0022, 0116-708-0023, 0116-708-0024                                                                                                                                                                                                                   | [application/pdf; charset=binary, 3f315644-ba6c-4a5f-9c98-70842c711117, ApprovalDocs.Burbank (SECURED) 2-17-16.pdf, 255888]         | 
| Cicero                   | 2015-09-24T00:00:00 | 2018-09-24T00:00:00 | 0915-000-028  | 0915-708-0018                                                                                                                                                                                                                                                 | [application/pdf; charset=binary, 3dc6f06d-951f-4fb9-953e-4ec94e8d48c9, ApprovalDocs.Cicero (SECURED) 2-17-16.pdf, 159816]          | 
```