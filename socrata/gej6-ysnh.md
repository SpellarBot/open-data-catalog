# Draft Boatyard General Permit Public Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-boatyard-general-permit-public-comments) |
| Metadata | [Link](https://data.wa.gov/api/views/gej6-ysnh) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gej6-ysnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gej6-ysnh/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gej6-ysnh |
| Name | Draft Boatyard General Permit Public Comments |
| Category | Natural Resources & Environment |
| Tags | ecology, boatyard |
| Created | 2016-05-02T20:37:53Z |
| Publication Date | 2016-05-02T20:45:26Z |

## Description

Public comments received for the draft Boatyard General Permit

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | attachment  | Attachment | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gej6-ysnh d:2016-05-02T13:39:47.000Z t:attachment.size=182763 t:attachment.filename=Comments-BYGPDraft1-DNR-20160429.pdf t:attachment.file_id=6cf00931-e0b6-44d5-81b1-861b0372d072 t:name="Washington State Department of Natural Resources (DNR)" t:attachment.content_type="application/pdf; charset=binary" m:row_number.gej6-ysnh=1

series e:gej6-ysnh d:2016-05-02T13:40:07.000Z t:attachment.size=179085 t:attachment.filename=Comments-BYGPDraft1-KarenGale-20160428.pdf t:attachment.file_id=54250514-b4a8-43eb-8a4b-a262ba0ef01c t:name="Karen Gale" t:attachment.content_type="application/pdf; charset=binary" m:row_number.gej6-ysnh=2

series e:gej6-ysnh d:2016-05-02T13:41:42.000Z t:attachment.size=132517 t:attachment.filename=Comments-BYGPDraft1-PtOfEdmonds-20160428.pdf t:attachment.file_id=6ab135ce-2cc1-4a99-a7f3-f93e251a8fd5 t:name="Port of Edmonds" t:attachment.content_type="application/pdf; charset=binary" m:row_number.gej6-ysnh=3
```

## Meta Commands

```ls
metric m:row_number.gej6-ysnh p:long l:"Row Number"

entity e:gej6-ysnh l:"Draft Boatyard General Permit Public Comments" t:url=https://data.wa.gov/api/views/gej6-ysnh

property e:gej6-ysnh t:meta.view v:id=gej6-ysnh v:category="Natural Resources & Environment" v:averageRating=0 v:name="Draft Boatyard General Permit Public Comments"

property e:gej6-ysnh t:meta.view.owner v:id=us76-w9xc v:screenName="Tim Lewis" v:displayName="Tim Lewis"

property e:gej6-ysnh t:meta.view.tableauthor v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"
```

## Top Records

```ls
| :updated_at | name                                                   | attachment                                                                                                                         | 
| =========== | ====================================================== | ================================================================================================================================== | 
| 1462196387  | Washington State Department of Natural Resources (DNR) | [application/pdf; charset=binary, 6cf00931-e0b6-44d5-81b1-861b0372d072, Comments-BYGPDraft1-DNR-20160429.pdf, 182763]              | 
| 1462196407  | Karen Gale                                             | [application/pdf; charset=binary, 54250514-b4a8-43eb-8a4b-a262ba0ef01c, Comments-BYGPDraft1-KarenGale-20160428.pdf, 179085]        | 
| 1462196502  | Port of Edmonds                                        | [application/pdf; charset=binary, 6ab135ce-2cc1-4a99-a7f3-f93e251a8fd5, Comments-BYGPDraft1-PtOfEdmonds-20160428.pdf, 132517]      | 
| 1462196521  | Port of Port Townsend                                  | [application/pdf; charset=binary, 1387956b-2a20-40bd-9383-05455685f85a, Comments-BYGPDraft1-PtOfPortTownsend-20160429.pdf, 515803] | 
| 1462196534  | Port of Seattle                                        | [application/pdf; charset=binary, 95014a10-665b-4067-a71b-25db20714769, Comments-BYGPDraft1-PtOfSeattle-20160428.pdf, 589994]      | 
| 1462196643  | Ecology Public Hearing April 19, 2016                  | [audio/mpeg; charset=binary, 01fbece2-9076-4add-a61c-d0e0ce013d38, Recording-PublicHearing-BYGP-20160419.MP3, 12250092]            | 
| 1462196674  | Ecology Public Hearing April 20, 2016                  | [audio/mpeg; charset=binary, 0e15bd6c-5fd9-4227-ad5a-826db3b2b34a, Recording-PublicHearing-BYGP-20160420.MP3, 31596168]            | 
| 1462196702  | Washington Public Ports Association (WPPA)             | [application/pdf; charset=binary, f83b1a53-df65-49fc-847e-2638fe97dd92, Comments-BYGPDraft1-WPPA-20160428.pdf, 280053]             | 
| 1462196708  | Puget Soundkeeper Alliance (PSA)                       | [application/pdf; charset=binary, 71ca44cf-eebd-4109-be5b-49725d1a6cb3, Comments-BYGPDraft1-PSA-20160429.pdf, 812459]              | 
| 1462196716  | Northwest Marine Trade Association (NMTA)              | [application/pdf; charset=binary, 5a1ecb60-59c5-49a2-b6cd-3e16a8becdcf, Comments-BYGPDraft1-NMTA-20160429.pdf, 798598]             | 
```