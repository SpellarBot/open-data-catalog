# Bridge and Ferry Terminal Washing Draft General Permit Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bridge-and-ferry-terminal-washing-draft-general-permit-comments) |
| Metadata | [Link](https://data.wa.gov/api/views/asne-y2hi) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/asne-y2hi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/asne-y2hi/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | asne-y2hi |
| Name | Bridge and Ferry Terminal Washing Draft General Permit Comments |
| Category | Natural Resources & Environment |
| Tags | ecology, bridge and ferry terminal washing, general permit |
| Created | 2016-12-09T17:35:37Z |
| Publication Date | 2016-12-09T18:28:04Z |

## Description

Public comments received on the draft general permit for Bridge and Ferry Terminal Washing

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | organization | Organization | text      | text        |
| Yes      | series tag  | comments     | Comments     | html      | html        |
| Yes      | series tag  | attachment   | Attachment   | document  | document    |
| Yes      | series tag  | attachment_2 | Attachment 2 | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:asne-y2hi d:2016-12-09T18:03:58.000Z t:attachment.size=171548 t:organization="Resources for Sustainable Communities" t:attachment.filename="NPDES bridge and ferry.pdf" t:attachment.file_id=68ed6b81-00c3-4e2d-9c8f-321bdb35f1c7 t:name="Lee First" t:attachment.content_type="application/pdf; charset=binary" m:row_number.asne-y2hi=1

series e:asne-y2hi d:2016-12-09T18:05:59.000Z t:attachment.size=338490 t:organization="Puget Soundkeeper Alliance" t:attachment.filename="Puget Soundkeeper Comments on Draft Bridge & Ferry Terminal Washing General NPDES Permit 12-2-16.pdf" t:attachment.file_id=b9d7cc35-b4e6-4c90-90b2-7871c7ee28a8 t:name="Alyssa L. Englebrecht" t:attachment.content_type="application/pdf; charset=binary" m:row_number.asne-y2hi=2

series e:asne-y2hi d:2016-12-09T18:20:20.000Z t:attachment.size=197891 t:organization="City of Tacoma" t:attachment.filename="Bridge Washing Permit Comments.pdf" t:attachment.file_id=2d085068-33ff-4e6a-885f-73b304ba8d28 t:name="Mieke Hoppin" t:attachment.content_type="application/pdf; charset=binary" m:row_number.asne-y2hi=3
```

## Meta Commands

```ls
metric m:row_number.asne-y2hi p:long l:"Row Number"

entity e:asne-y2hi l:"Bridge and Ferry Terminal Washing Draft General Permit Comments" t:url=https://data.wa.gov/api/views/asne-y2hi

property e:asne-y2hi t:meta.view v:id=asne-y2hi v:category="Natural Resources & Environment" v:averageRating=0 v:name="Bridge and Ferry Terminal Washing Draft General Permit Comments"

property e:asne-y2hi t:meta.view.owner v:id=us76-w9xc v:screenName="Tim Lewis" v:displayName="Tim Lewis"

property e:asne-y2hi t:meta.view.tableauthor v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"
```

## Top Records

```ls
| :updated_at | name                  | organization                                      | comments | attachment                                                                                                                                                                            | attachment_2             | 
| =========== | ===================== | ================================================= | ======== | ===================================================================================================================================================================================== | ======================== | 
| 1481306638  | Lee First             | Resources for Sustainable Communities             |          | [application/pdf; charset=binary, 68ed6b81-00c3-4e2d-9c8f-321bdb35f1c7, NPDES bridge and ferry.pdf, 171548]                                                                           | [null, null, null, null] | 
| 1481306759  | Alyssa L. Englebrecht | Puget Soundkeeper Alliance                        |          | [application/pdf; charset=binary, b9d7cc35-b4e6-4c90-90b2-7871c7ee28a8, Puget Soundkeeper Comments on Draft Bridge & Ferry Terminal Washing General NPDES Permit 12-2-16.pdf, 338490] | [null, null, null, null] | 
| 1481307620  | Mieke Hoppin          | City of Tacoma                                    |          | [application/pdf; charset=binary, 2d085068-33ff-4e6a-885f-73b304ba8d28, Bridge Washing Permit Comments.pdf, 197891]                                                                   | [null, null, null, null] | 
| 1481307674  | Denise M. Healy       | City of Seattle, Department of Transportation     |          | [application/pdf; charset=binary, 18bf85c4-31a6-481b-ac64-3edf0ee37d4b, SDOT_BRIDGE_WASH_PER_COMMRNTS.pdf, 168385]                                                                    | [null, null, null, null] | 
| 1481307739  | Michal Rechner        | Washington Department of Natural Resources        |          | [application/pdf; charset=binary, c058870a-6ae0-4287-85ff-33913893cf23, BridgeFerryCleaningNPDES_CommentFINAL.PDF, 49062]                                                             | [null, null, null, null] | 
| 1481307802  | Angela Dillon         | Snoqualmie Indian Tribe                           |          | [application/pdf; charset=binary, 23773a14-d48c-4e0e-965b-dc9c3100d0d5, RE_ Announcing a Draft Bridge and Ferry Terminal Washing General Permit.pdf, 90229]                           | [null, null, null, null] | 
| 1481307889  | Matthew Sterner       | Department of Archaeology & Historic Preservation |          | [application/pdf; charset=binary, abee87dd-270d-444e-aefe-0c4fd23f434b, Draft Bridge and Ferry Terminal Washing General Permit--Comments.pdf, 43245]                                  | [null, null, null, null] | 
```