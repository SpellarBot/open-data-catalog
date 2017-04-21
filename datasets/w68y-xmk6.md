# Calls for Service 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calls-for-service-2015) |
| Metadata | [Link](https://data.nola.gov/api/views/w68y-xmk6) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/w68y-xmk6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/w68y-xmk6/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | w68y-xmk6 |
| Name | Calls for Service 2015 |
| Attribution | Orleans Parish Communications District |
| Category | Public Safety and Preparedness |
| Tags | crime, police, nopd |
| Created | 2015-01-03T09:15:06Z |
| Publication Date | 2016-07-28T21:23:22Z |

## Description

This dataset reflects incidents that have been reported to the New Orleans Police Department in 2015. Data is provided by Orleans Parish Communication District (OPCD), the administrative office of 9-1-1 for the City of New Orleans. In the OPCD system, NOPD may reclassify or change the signal type for up to 36 hours after the incident is marked up. For information about an incident after this time period, citizens may request police reports from the NOPD Public Records Division.  In order to protect the privacy of victims, addresses are shown at the block level and the call types cruelty to juveniles, juvenile attachment and missing juvenile have been removed in accordance with the Louisiana Public Records Act, L.R.S. 44:1.  Map coordinates (X,Y) have been removed for the following call types: Aggravated Rape, Aggravated Rape - MA, Crime Against Nature, Mental Patient, Oral Sexual Battery, Prostitution, Sexual Battery, Simple Rape, Simple Rape - Male V, and Soliciting for Prost.Disclaimer: These incidents may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | nopd_item       | NOPD_Item       | text          | text          |
| Yes      | series tag  | type_           | Type_           | text          | text          |
| Yes      | series tag  | typetext        | TypeText        | text          | text          |
| Yes      | series tag  | priority        | Priority        | text          | text          |
| Yes      | series tag  | initialtype     | InitialType     | text          | text          |
| Yes      | series tag  | initialtypetext | InitialTypeText | text          | text          |
| Yes      | series tag  | initialpriority | InitialPriority | text          | text          |
| No       |             | mapx            | MapX            | number        | text          |
| No       |             | mapy            | MapY            | number        | text          |
| Yes      | time        | timecreate      | TimeCreate      | calendar_date | calendar_date |
| No       |             | timedispatch    | TimeDispatch    | calendar_date | calendar_date |
| No       |             | timearrive      | TimeArrive      | calendar_date | calendar_date |
| No       |             | timeclosed      | TimeClosed      | calendar_date | calendar_date |
| Yes      | series tag  | disposition     | Disposition     | text          | text          |
| Yes      | series tag  | dispositiontext | DispositionText | text          | text          |
| Yes      | series tag  | selfinitiated   | SelfInitiated   | text          | text          |
| Yes      | series tag  | beat            | Beat            | text          | text          |
| No       |             | block_address   | BLOCK_ADDRESS   | text          | text          |
| Yes      | series tag  | zip             | Zip             | text          | text          |
| Yes      | series tag  | policedistrict  | PoliceDistrict  | text          | number        |
```

## Time Field

```ls
Value = timecreate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mapx,mapy,timedispatch,timearrive,timeclosed,block_address
```

## Data Commands

```ls
series e:w68y-xmk6 d:2015-01-01T00:00:34.000Z t:zip=70116 t:type_=56 t:beat=8D06 t:initialtype=94F t:nopd_item=A0000115 t:selfinitiated=N t:initialpriority=1A t:priority=1D t:initialtypetext=FIREWORKS t:dispositiontext=UNFOUNDED t:policedistrict=8 t:typetext="SIMPLE CRIMINAL DAMAGE" t:disposition=UNF m:row_number.w68y-xmk6=1

series e:w68y-xmk6 d:2015-01-01T00:00:36.000Z t:zip=70116 t:type_=21 t:beat=8E01 t:initialtype=21 t:nopd_item=A0000215 t:selfinitiated=Y t:initialpriority=1H t:priority=1H t:initialtypetext="COMPLAINT OTHER" t:dispositiontext="Necessary Action Taken" t:policedistrict=8 t:typetext="COMPLAINT OTHER" t:disposition=NAT m:row_number.w68y-xmk6=2

series e:w68y-xmk6 d:2015-01-01T00:01:47.000Z t:zip=70122 t:type_=94 t:beat=3Y03 t:initialtype=94 t:nopd_item=A0000415 t:selfinitiated=N t:initialpriority=2B t:priority=1A t:initialtypetext="DISCHARGING FIREARM" t:dispositiontext=UNFOUNDED t:policedistrict=3 t:typetext="DISCHARGING FIREARM" t:disposition=UNF m:row_number.w68y-xmk6=3
```

## Meta Commands

```ls
metric m:row_number.w68y-xmk6 p:long l:"Row Number"

entity e:w68y-xmk6 l:"Calls for Service 2015" t:attribution="Orleans Parish Communications District" t:url=https://data.nola.gov/api/views/w68y-xmk6

property e:w68y-xmk6 t:meta.view v:id=w68y-xmk6 v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Calls for Service 2015" v:attribution="Orleans Parish Communications District"

property e:w68y-xmk6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:w68y-xmk6 t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:w68y-xmk6 t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:w68y-xmk6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| nopd_item | type_ | typetext               | priority | initialtype | initialtypetext     | initialpriority | mapx    | mapy   | timecreate          | timedispatch        | timearrive          | timeclosed          | disposition | dispositiontext        | selfinitiated | beat | block_address             | zip   | policedistrict | 
| ========= | ===== | ====================== | ======== | =========== | =================== | =============== | ======= | ====== | =================== | =================== | =================== | =================== | =========== | ====================== | ============= | ==== | ========================= | ===== | ============== | 
| A0000115  | 56    | SIMPLE CRIMINAL DAMAGE | 1D       | 94F         | FIREWORKS           | 1A              | 3682553 | 532626 | 2015-01-01T00:00:34 | 2015-01-01T01:24:47 | 2015-01-01T01:41:20 | 2015-01-01T01:41:30 | UNF         | UNFOUNDED              | N             | 8D06 | 007XX Orleans Ave         | 70116 | 8              | 
| A0000215  | 21    | COMPLAINT OTHER        | 1H       | 21          | COMPLAINT OTHER     | 1H              | 3682368 | 532820 | 2015-01-01T00:00:36 |                     | 2015-01-01T00:00:36 | 2015-01-01T01:31:54 | NAT         | Necessary Action Taken | Y             | 8E01 | Bourbon St & Orleans Ave  | 70116 | 8              | 
| A0000415  | 94    | DISCHARGING FIREARM    | 1A       | 94          | DISCHARGING FIREARM | 2B              | 3686245 | 546280 | 2015-01-01T00:01:47 | 2015-01-01T01:20:19 |                     | 2015-01-01T01:32:38 | UNF         | UNFOUNDED              | N             | 3Y03 | Clematis St & Acacia St   | 70122 | 3              | 
| A0000515  | 107   | SUSPICIOUS PERSON      | 2A       | 107         | SUSPICIOUS PERSON   | 2A              | 3687521 | 537825 | 2015-01-01T00:02:22 | 2015-01-01T00:08:17 | 2015-01-01T00:13:19 | 2015-01-01T00:24:40 | GOA         | GONE ON ARRIVAL        | N             | 5C03 | 026XX N Robertson St      | 70117 | 5              | 
| A0000615  | 21    | COMPLAINT OTHER        | 1H       | 21          | COMPLAINT OTHER     | 1H              | 3682082 | 529645 | 2015-01-01T00:02:44 |                     |                     | 2015-01-01T01:22:17 | VOI         | VOID                   | N             | 8G02 | 003XX Canal St            | 70130 | 8              | 
| A0000715  | 94F   | FIREWORKS              | 1A       | 94F         | FIREWORKS           | 1A              | 3704519 | 561636 | 2015-01-01T00:02:46 | 2015-01-01T00:06:21 |                     | 2015-01-01T00:06:32 | NAT         | Necessary Action Taken | N             | 7P01 | 074XX Kenyon Rd           | 70127 | 7              | 
| A0000815  | 94F   | FIREWORKS              | 1A       | 94F         | FIREWORKS           | 2H              | 3679489 | 546712 | 2015-01-01T00:03:09 |                     |                     | 2015-01-01T00:06:53 | NAT         | Necessary Action Taken | N             | 3M02 | 039XX Paris Ave           | 70122 | 3              | 
| A0000915  | 63    | PROWLER                | 2C       | 63          | PROWLER             | 2C              | 3691999 | 525715 | 2015-01-01T00:03:26 | 2015-01-01T00:06:15 | 2015-01-01T00:13:46 | 2015-01-01T00:29:15 | GOA         | GONE ON ARRIVAL        | N             | 4I01 | 014XX Casa Calvo St       | 70114 | 4              | 
| A0001015  | 94    | DISCHARGING FIREARM    | 2B       | 94          | DISCHARGING FIREARM | 2B              | 3668626 | 532154 | 2015-01-01T00:03:43 | 2015-01-01T00:07:12 | 2015-01-01T00:09:18 | 2015-01-01T00:15:09 | UNF         | UNFOUNDED              | N             | 2U03 | College Ct & Earhart Blvd | 70125 | 2              | 
| A0001115  | 94    | DISCHARGING FIREARM    | 1A       | 94          | DISCHARGING FIREARM | 2B              | 3668441 | 538345 | 2015-01-01T00:03:59 | 2015-01-01T03:28:00 |                     | 2015-01-01T03:30:05 | UNF         | UNFOUNDED              | N             | 3D02 | Baudin St & S Olympia St  | 70119 | 3              | 
```