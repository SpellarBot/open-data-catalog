# Court-Approved Transcriptionists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/court-approved-transcriptionists-3bce6) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/bdjj-5xue) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/bdjj-5xue/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/bdjj-5xue/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | bdjj-5xue |
| Name | Court-Approved Transcriptionists |
| Attribution | King County Superior Court |
| Category | Legal |
| Tags | transcribe, transcription, transcriptionist, records, court, clerk |
| Created | 2013-06-22T21:37:09Z |
| Publication Date | 2015-03-16T18:31:15Z |

## Description

Per King County Local Civil Rule (LCR) 80.(d)(4): Verbatim Report of Proceedings. Preparation of an official transcript of electronically recorded proceedings conducted in Superior Court (including video tape, audiotape and digital recordings) shall be completed by a court-approved transcriber in accordance with procedures developed by the Office of the Administrator for the Courts and the King County Superior Court Clerk.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | business_name | Business name | html      | html        |
| Yes      | series tag  | note          | Note          | text      | text        |
| No       |             | address1      | Address1      | text      | text        |
| No       |             | address2      | Address2      | text      | text        |
| Yes      | series tag  | city          | City          | text      | text        |
| Yes      | series tag  | state         | State         | text      | text        |
| Yes      | series tag  | zip           | Zip           | text      | text        |
| Yes      | series tag  | phone1        | Phone1        | phone     | phone       |
| Yes      | series tag  | phone2        | Phone2        | phone     | phone       |
| Yes      | series tag  | fax           | Fax           | phone     | phone       |
| Yes      | series tag  | contact       | Contact       | text      | text        |
| Yes      | series tag  | email         | Email         | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:bdjj-5xue d:2014-11-25T15:22:12.000Z t:business_name="<p><strong>Janna Gross</strong></p>" t:zip=98296 t:phone_number=206-714-7537 t:email=jannagross@gmail.com t:state=WA t:city=Snohomish m:row_number.bdjj-5xue=1

series e:bdjj-5xue d:2014-11-25T15:22:12.000Z t:business_name="<p><strong>Northwest Transcribers</strong></p>" t:zip=98082 t:phone_number=425-497-9760 t:email=nwtranscribers@comcast.net t:state=WA t:contact="Barbara Lane, CET" t:city="Mill Creek" m:row_number.bdjj-5xue=2

series e:bdjj-5xue d:2014-11-25T15:22:12.000Z t:business_name="<p><strong>Reed, Jackson and Watkins</strong></p>" t:zip=98101 t:phone_number=206-624-3005 t:email=reed@rjwtranscripts.com t:state=WA t:contact="Bonnie Reed or Marjie Jackson" t:city=Seattle m:row_number.bdjj-5xue=3
```

## Meta Commands

```ls
metric m:row_number.bdjj-5xue p:long l:"Row Number"

entity e:bdjj-5xue l:"Court-Approved Transcriptionists" t:attribution="King County Superior Court" t:url=https://data.kingcounty.gov/api/views/bdjj-5xue

property e:bdjj-5xue t:meta.view v:id=bdjj-5xue v:category=Legal v:attributionLink=http://www.kingcounty.gov/courts/clerk v:averageRating=0 v:name="Court-Approved Transcriptionists" v:attribution="King County Superior Court"

property e:bdjj-5xue t:meta.view.license v:name="Public Domain"

property e:bdjj-5xue t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:bdjj-5xue t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | business_name                                      | note | address1                    | address2  | city             | state | zip        | phone1               | phone2       | fax                  | contact                       | email                             | 
| =========== | ================================================== | ==== | =========================== | ========= | ================ | ===== | ========== | ==================== | ============ | ==================== | ============================= | ================================= | 
| 1416928932  | Janna Gross                                        |      | 8224 E Lowell Larimer Rd.   |           | Snohomish        | WA    | 98296      | [206-714-7537, null] | [null, null] | [null, null]         |                               | jannagross@gmail.com              | 
| 1416928932  | Northwest Transcribers                             |      | P.O. Box 12192              |           | Mill Creek       | WA    | 98082      | [425-497-9760, null] | [null, null] | [null, null]         | Barbara Lane, CET             | nwtranscribers@comcast.net        | 
| 1416928932  | Reed, Jackson and Watkins                          |      | 1402 Third Avenue           | Suite 210 | Seattle          | WA    | 98101      | [206-624-3005, null] | [null, null] | [null, null]         | Bonnie Reed or Marjie Jackson | reed@rjwtranscripts.com           | 
| 1416928932  | Wilson Transcription Services                      |      | 5309 Village Park Drive SE. | #1622     | Bellevue         | WA    | 98006      | [425-391-4218, null] | [null, null] | [null, null]         | Rosie Wilson                  | Rosievwilson@yahoo.com            | 
| 1416928932  | Linda A Owen, CSR                                  |      | 9306 138th Court NE         |           | Redmond          | WA    | 98052      | [425-466-8543, null] | [null, null] | [null, null]         |                               | Lindaowen@pioneernet.net          | 
| 1416928932  | Jackson Street Associates                          |      | 108 S. Jackson Street       | Suite 302 | Seattle          | WA    | 98104      | [206-941-9142, null] | [null, null] | [206-548-0572, null] | Mary Ryan                     | jacksonstreetassociates@gmail.com | 
| 1416928932  | TypeWrite Word Processing Service                  |      | 211 N Milton Road           |           | Saratoga Springs | NY    | 12866      | [518-581-8973, null] | [null, null] | [null, null]         | Shari Riemer                  | transcripts@typewp.com            | 
| 1416928932  | For The Record                                     |      | 9801 116th ST NE            |           | Arlington        | WA    | 98223-6223 | [206-714-4578, null] | [null, null] | [null, null]         | Thomas Marshman               | fortherecordtranscripts@gmail.com | 
| 1416928932  | Rough & Associates                                 |      | 3515 SW Alaska              | 2nd Flr   | Seattle          | WA    | 98126      | [206-682-1427, null] | [null, null] | [null, null]         | Linda J. Rough                | roughandassoc@aol.com             | 
| 1416928932  | Catherine Vernon & Associates Court Reporters, LLC |      | 3641 N. Pearl Street        |           | Tacoma           | WA    | 98407      | [253-627-2062, null] | [null, null] | [253-779-4333, null] |                               | info@vernoncourtreporters.com     | 
```