# Calls for Service 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calls-for-service-2013) |
| Metadata | [Link](https://data.nola.gov/api/views/5fn8-vtui) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/5fn8-vtui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/5fn8-vtui/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 5fn8-vtui |
| Name | Calls for Service 2013 |
| Attribution | Orleans Parish Communications District |
| Category | Public Safety and Preparedness |
| Tags | crime, police, nopd |
| Created | 2013-02-04T22:04:42Z |
| Publication Date | 2016-02-11T22:53:26Z |

## Description

This dataset reflects incidents that have been reported to the New Orleans Police Department in 2013. Data is provided by Orleans Parish Communication District (OPCD), the administrative office of 9-1-1 for the City of New Orleans. In the OPCD system, NOPD may reclassify or change the signal type for up to 36 hours after the incident is marked up. For information about an incident after this time period, citizens may request police reports from the NOPD Public Records Division.  In order to protect the privacy of victims, addresses are shown at the block level and the call types cruelty to juveniles, juvenile attachment and missing juvenile have been removed in accordance with the Louisiana Public Records Act, L.R.S. 44:1.  Map coordinates (X,Y) have been removed for the following call types: Aggravated Rape, Aggravated Rape - MA, Crime Against Nature, Mental Patient, Oral Sexual Battery, Prostitution, Sexual Battery, Simple Rape, Simple Rape - Male V, and Soliciting for Prost.Disclaimer: These incidents may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | nopd_item       | NOPD_Item       | text          | text          |
| Yes      | series tag  | type_           | Type_           | text          | text          |
| Yes      | series tag  | typetext        | TypeText        | text          | text          |
| Yes      | series tag  | priority        | Priority        | text          | text          |
| No       |             | mapx            | MapX            | number        | text          |
| No       |             | mapy            | MapY            | number        | text          |
| Yes      | time        | timecreate      | TimeCreate      | calendar_date | calendar_date |
| No       |             | timedispatch    | TimeDispatch    | calendar_date | calendar_date |
| No       |             | timearrive      | TimeArrive      | calendar_date | calendar_date |
| No       |             | timeclosed      | TimeClosed      | calendar_date | calendar_date |
| Yes      | series tag  | disposition     | Disposition     | text          | text          |
| Yes      | series tag  | dispositiontext | DispositionText | text          | text          |
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
series e:5fn8-vtui d:2012-12-31T23:59:34.000Z t:zip=70117 t:type_=94 t:nopd_item=A0000113 t:priority=2B t:dispositiontext=UNFOUNDED t:policedistrict=5 t:typetext="DISCHARGING FIREARM" t:disposition=UNF m:row_number.5fn8-vtui=1

series e:5fn8-vtui d:2012-12-31T23:59:49.000Z t:zip=70131 t:type_=94 t:nopd_item=A0000213 t:priority=2B t:dispositiontext=UNFOUNDED t:policedistrict=4 t:typetext="DISCHARGING FIREARM" t:disposition=UNF m:row_number.5fn8-vtui=2

series e:5fn8-vtui d:2013-01-01T00:00:22.000Z t:zip=70130 t:type_=67S t:nopd_item=A0000313 t:priority=1C t:dispositiontext=DUPLICATE t:policedistrict=8 t:typetext=SHOPLIFTING t:disposition=DUP m:row_number.5fn8-vtui=3
```

## Meta Commands

```ls
metric m:row_number.5fn8-vtui p:long l:"Row Number"

entity e:5fn8-vtui l:"Calls for Service 2013" t:attribution="Orleans Parish Communications District" t:url=https://data.nola.gov/api/views/5fn8-vtui

property e:5fn8-vtui t:meta.view v:id=5fn8-vtui v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Calls for Service 2013" v:attribution="Orleans Parish Communications District"

property e:5fn8-vtui t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5fn8-vtui t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:5fn8-vtui t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:5fn8-vtui t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| nopd_item | type_ | typetext             | priority | mapx             | mapy            | timecreate          | timedispatch        | timearrive          | timeclosed          | disposition | dispositiontext        | block_address              | zip   | policedistrict | 
| ========= | ===== | ==================== | ======== | ================ | =============== | =================== | =================== | =================== | =================== | =========== | ====================== | ========================== | ===== | ============== | 
| A0000113  | 94    | DISCHARGING FIREARM  | 2B       | 3696313.00000000 | 533332.00000000 | 2012-12-31T23:59:34 | 2013-01-01T00:03:10 | 2013-01-01T00:23:57 | 2013-01-01T00:24:10 | UNF         | UNFOUNDED              | 052XX Burgundy St          | 70117 | 5              | 
| A0000213  | 94    | DISCHARGING FIREARM  | 2B       | 3710263.00000000 | 518976.00000000 | 2012-12-31T23:59:49 | 2013-01-01T00:05:43 | 2013-01-01T00:14:35 | 2013-01-01T00:21:29 | UNF         | UNFOUNDED              | 029XX Bacchus Dr           | 70131 | 4              | 
| A0000313  | 67S   | SHOPLIFTING          | 1C       | 3683068.00000000 | 531830.00000000 | 2013-01-01T00:00:22 |                     |                     | 2013-01-01T00:33:26 | DUP         | DUPLICATE              | 006XX Decatur St           | 70130 | 8              | 
| A0000413  | 21    | COMPLAINT OTHER      | 1H       | 3673396.00000000 | 533473.00000000 | 2013-01-01T00:00:29 | 2013-01-01T00:00:30 | 2013-01-01T00:00:33 | 2013-01-01T00:13:58 | NAT         | NECESSARY ACTION TAKEN | 007XX S White St           | 70119 | 1              | 
| A0000513  | 62A   | BURGLAR ALARM, SILEN | 2C       | 3665197.00000000 | 544507.00000000 | 2013-01-01T00:00:22 | 2013-01-01T00:36:13 |                     | 2013-01-01T00:36:32 | VOI         | VOID                   | 055XX Cherlyn Dr           | 70124 | 3              | 
| A0000613  | 94F   | FIREWORKS            | 1H       | 3668342.00000000 | 518606.00000000 | 2012-12-31T23:59:56 | 2013-01-01T00:27:00 | 2013-01-01T00:36:38 | 2013-01-01T00:57:01 | UNF         | UNFOUNDED              | Magazine St & Soniat St    | 70115 | 2              | 
| A0000713  | 21    | COMPLAINT OTHER      | 1H       | 3679448.00000000 | 540791.00000000 | 2013-01-01T00:01:04 | 2013-01-01T00:01:05 | 2013-01-01T00:03:21 | 2013-01-01T00:07:26 | UNF         | UNFOUNDED              | 026XX D'Abadie St          | 70119 | 1              | 
| A0000813  | 94    | DISCHARGING FIREARM  | 2B       | 3688421.00000000 | 527933.00000000 | 2013-01-01T00:00:51 | 2013-01-01T00:04:29 | 2013-01-01T00:07:09 | 2013-01-01T00:11:27 | UNF         | UNFOUNDED              | Newton St & Pacific Ave    | 70114 | 4              | 
| A0000913  | 94    | DISCHARGING FIREARM  | 2B       | 3678701.00000000 | 537294.00000000 | 2013-01-01T00:01:55 | 2013-01-01T00:01:55 |                     | 2013-01-01T00:03:37 | UNF         | UNFOUNDED              | N Tonti St & Ursulines Ave | 70119 | 1              | 
| A0001013  | 94    | DISCHARGING FIREARM  | 2B       | 3677890.00000000 | 525169.00000000 | 2013-01-01T00:01:54 | 2013-01-01T00:02:55 | 2013-01-01T00:05:00 | 2013-01-01T00:07:23 | UNF         | UNFOUNDED              | Baronne St & Felicity St   | 70113 | 6              | 
```