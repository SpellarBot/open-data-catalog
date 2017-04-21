# Calls for Service 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calls-for-service-2016) |
| Metadata | [Link](https://data.nola.gov/api/views/wgrp-d3ma) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/wgrp-d3ma/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/wgrp-d3ma/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | wgrp-d3ma |
| Name | Calls for Service 2016 |
| Attribution | Orleans Parish Communications District |
| Category | Public Safety and Preparedness |
| Tags | crime, police, nopd |
| Created | 2016-01-03T08:19:14Z |
| Publication Date | 2017-04-05T16:18:44Z |

## Description

This dataset reflects incidents that have been reported to the New Orleans Police Department in 2016. Data is provided by Orleans Parish Communication District (OPCD), the administrative office of 9-1-1 for the City of New Orleans. In the OPCD system, NOPD may reclassify or change the signal type for up to 36 hours after the incident is marked up. For information about an incident after this time period, citizens may request police reports from the NOPD Public Records Division.  In order to protect the privacy of victims, addresses are shown at the block level and the call types cruelty to juveniles, juvenile attachment and missing juvenile have been removed in accordance with the Louisiana Public Records Act, L.R.S. 44:1.  Map coordinates (X,Y) have been removed for the following call types: Aggravated Rape, Aggravated Rape - MA, Crime Against Nature, Mental Patient, Oral Sexual Battery, Prostitution, Sexual Battery, Simple Rape, Simple Rape - Male V, and Soliciting for Prost.Disclaimer: These incidents may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

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
series e:wgrp-d3ma d:2016-01-01T05:33:23.000Z t:zip=70112 t:type_=67A t:beat=8J02 t:initialtype=67A t:nopd_item=A0045116 t:selfinitiated=N t:initialpriority=1B t:priority=1B t:initialtypetext="AUTO THEFT" t:dispositiontext=VOID t:policedistrict=8 t:typetext="AUTO THEFT" t:disposition=VOI m:row_number.wgrp-d3ma=1

series e:wgrp-d3ma d:2016-01-01T00:01:02.000Z t:zip=70118 t:type_=94F t:beat=2K04 t:initialtype=94 t:nopd_item=A0000116 t:selfinitiated=N t:initialpriority=2B t:priority=2H t:initialtypetext="DISCHARGING FIREARM" t:dispositiontext="Necessary Action Taken" t:policedistrict=2 t:typetext=FIREWORKS t:disposition=NAT m:row_number.wgrp-d3ma=2

series e:wgrp-d3ma d:2016-01-01T00:01:11.000Z t:zip=70115 t:type_=94F t:beat=2B03 t:initialtype=94F t:nopd_item=A0000216 t:selfinitiated=N t:initialpriority=1A t:priority=1A t:initialtypetext=FIREWORKS t:dispositiontext=DUPLICATE t:policedistrict=2 t:typetext=FIREWORKS t:disposition=DUP m:row_number.wgrp-d3ma=3
```

## Meta Commands

```ls
metric m:row_number.wgrp-d3ma p:long l:"Row Number"

entity e:wgrp-d3ma l:"Calls for Service 2016" t:attribution="Orleans Parish Communications District" t:url=https://data.nola.gov/api/views/wgrp-d3ma

property e:wgrp-d3ma t:meta.view v:id=wgrp-d3ma v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Calls for Service 2016" v:attribution="Orleans Parish Communications District"

property e:wgrp-d3ma t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:wgrp-d3ma t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:wgrp-d3ma t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:wgrp-d3ma t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| nopd_item | type_ | typetext            | priority | initialtype | initialtypetext     | initialpriority | mapx     | mapy    | timecreate          | timedispatch        | timearrive          | timeclosed          | disposition | dispositiontext        | selfinitiated | beat | block_address                    | zip   | policedistrict | 
| ========= | ===== | =================== | ======== | =========== | =================== | =============== | ======== | ======= | =================== | =================== | =================== | =================== | =========== | ====================== | ============= | ==== | ================================ | ===== | ============== | 
| A0045116  | 67A   | AUTO THEFT          | 1B       | 67A         | AUTO THEFT          | 1B              | 3678737  | 531385  | 2016-01-01T05:33:23 |                     |                     | 2016-01-01T10:10:34 | VOI         | VOID                   | N             | 8J02 | 014XX Tulane Ave                 | 70112 | 8              | 
| A0000116  | 94F   | FIREWORKS           | 2H       | 94          | DISCHARGING FIREARM | 2B              | 3661003  | 532567  | 2016-01-01T00:01:02 | 2016-01-01T00:46:39 |                     | 2016-01-01T00:54:27 | NAT         | Necessary Action Taken | N             | 2K04 | Cohn St & Hamilton St            | 70118 | 2              | 
| A0000216  | 94F   | FIREWORKS           | 1A       | 94F         | FIREWORKS           | 1A              | 3666320  | 517836  | 2016-01-01T00:01:11 |                     |                     | 2016-01-01T00:48:51 | DUP         | DUPLICATE              | N             | 2B03 | 054XX Laurel St                  | 70115 | 2              | 
| A0000316  | 94    | DISCHARGING FIREARM | 2B       | 94          | DISCHARGING FIREARM | 2B              | 3720728  | 574341  | 2016-01-01T00:01:30 | 2016-01-01T00:02:12 | 2016-01-01T00:12:20 | 2016-01-01T00:19:09 | GOA         | GONE ON ARRIVAL        | N             | 7K04 | 078XX Star St                    | 70128 | 7              | 
| A0000416  | 18    | TRAFFIC INCIDENT    | 1H       | 18          | TRAFFIC INCIDENT    | 1H              | 3704220  | 522170  | 2016-01-01T00:01:46 |                     | 2016-01-01T00:01:46 | 2016-01-01T00:15:41 | NAT         | Necessary Action Taken | Y             | 4D04 | General Meyer Ave & Eton St      | 70131 | 4              | 
| A0000516  | 94    | DISCHARGING FIREARM | 2B       | 94          | DISCHARGING FIREARM | 2B              | 3681555  | 541217  | 2016-01-01T00:02:13 | 2016-01-01T00:19:34 |                     | 2016-01-01T00:19:41 | NAT         | Necessary Action Taken | N             | 5K04 | A P Tureaud Ave & N Dorgenois St | 70119 | 5              | 
| A0000616  | 94    | DISCHARGING FIREARM | 1A       | 94          | DISCHARGING FIREARM | 2B              | 3680933  | 537334  | 2016-01-01T00:02:59 | 2016-01-01T00:03:42 | 2016-01-01T00:12:38 | 2016-01-01T00:17:19 | GOA         | GONE ON ARRIVAL        | N             | 1B01 | Kerlerec St & N Roman St         | 70116 | 1              | 
| A0000716  | 94F   | FIREWORKS           | 1A       | 94F         | FIREWORKS           | 2H              | 3723844  | 560452  | 2016-01-01T00:03:05 | 2016-01-01T00:37:40 |                     | 2016-01-01T00:47:11 | GOA         | GONE ON ARRIVAL        | N             | 7L01 | 130XX Calais St                  | 70129 | 7              | 
| A0000816  | 24    | MEDICAL             | 2B       | 24          | MEDICAL             | 2B              | 37369000 | 3513814 | 2016-01-01T00:03:31 |                     | 2016-01-01T00:03:31 | 2016-01-01T00:16:44 | NAT         | Necessary Action Taken | Y             | 8G02 | Canal St & S Peters St           | 70130 | 8              | 
| A0000916  | 94    | DISCHARGING FIREARM | 2B       | 94          | DISCHARGING FIREARM | 2B              | 3690662  | 552814  | 2016-01-01T00:03:33 |                     |                     | 2016-01-01T00:30:51 | GOA         | GONE ON ARRIVAL        | N             | 3U03 | 051XX Louisa Dr                  | 70126 | 3              | 
```