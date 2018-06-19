# Calls for Service 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calls-for-service-2017) |
| Metadata | [Link](https://data.nola.gov/api/views/bqmt-f3jk) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/bqmt-f3jk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/bqmt-f3jk/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | bqmt-f3jk |
| Name | Calls for Service 2017 |
| Attribution | Orleans Parish Communications District |
| Category | Public Safety and Preparedness |
| Tags | crime, police |
| Created | 2017-01-01T09:00:36Z |
| Publication Date | 2017-04-05T16:25:07Z |

## Description

This dataset reflects incidents that have been reported to the New Orleans Police Department in 2017. Data is provided by Orleans Parish Communication District (OPCD), the administrative office of 9-1-1 for the City of New Orleans. In the OPCD system, NOPD may reclassify or change the signal type for up to 36 hours after the incident is marked up. For information about an incident after this time period, citizens may request police reports from the NOPD Public Records Division.  In order to protect the privacy of victims, addresses are shown at the block level and the call types cruelty to juveniles, juvenile attachment and missing juvenile have been removed in accordance with the Louisiana Public Records Act, L.R.S. 44:1.  Map coordinates (X,Y) have been removed for the following call types: Aggravated Rape, Aggravated Rape - MA, Crime Against Nature, Mental Patient, Oral Sexual Battery, Prostitution, Sexual Battery, Simple Rape, Simple Rape - Male V, and Soliciting for Prost.

Disclaimer: These incidents may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

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
series e:bqmt-f3jk d:2017-01-01T00:00:14.000Z t:zip=70119 t:type_=62A t:beat=1L04 t:initialtype=62A t:nopd_item=A0000117 t:selfinitiated=N t:initialpriority=2C t:priority=2C t:initialtypetext="BURGLAR ALARM, SILENT" t:dispositiontext="Necessary Action Taken" t:policedistrict=1 t:typetext="BURGLAR ALARM, SILENT" t:disposition=NAT m:row_number.bqmt-f3jk=1

series e:bqmt-f3jk d:2017-01-01T00:01:13.000Z t:zip=70125 t:type_=103 t:beat=2U04 t:initialtype=103 t:nopd_item=A0000217 t:selfinitiated=Y t:initialpriority=1A t:priority=1A t:initialtypetext="DISTURBANCE (OTHER)" t:dispositiontext="Necessary Action Taken" t:policedistrict=2 t:typetext="DISTURBANCE (OTHER)" t:disposition=NAT m:row_number.bqmt-f3jk=2

series e:bqmt-f3jk d:2017-01-01T00:02:03.000Z t:zip=70125 t:type_=94F t:beat=2P02 t:initialtype=95 t:nopd_item=A0000317 t:selfinitiated=N t:initialpriority=2B t:priority=1A t:initialtypetext="ILLEGAL CARRYING OF WEAPON" t:dispositiontext="Necessary Action Taken" t:policedistrict=2 t:typetext=FIREWORKS t:disposition=NAT m:row_number.bqmt-f3jk=3
```

## Meta Commands

```ls
metric m:row_number.bqmt-f3jk p:long l:"Row Number"

entity e:bqmt-f3jk l:"Calls for Service 2017" t:attribution="Orleans Parish Communications District" t:url=https://data.nola.gov/api/views/bqmt-f3jk

property e:bqmt-f3jk t:meta.view v:id=bqmt-f3jk v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Calls for Service 2017" v:attribution="Orleans Parish Communications District"

property e:bqmt-f3jk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bqmt-f3jk t:meta.view.owner v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:displayName="Socrata Service Account"

property e:bqmt-f3jk t:meta.view.tableauthor v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:roleName=editor v:displayName="Socrata Service Account"

property e:bqmt-f3jk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| nopd_item | type_ | typetext              | priority | initialtype | initialtypetext            | initialpriority | mapx    | mapy   | timecreate          | timedispatch        | timearrive          | timeclosed          | disposition | dispositiontext        | selfinitiated | beat | block_address                    | zip   | policedistrict | 
| ========= | ===== | ===================== | ======== | =========== | ========================== | =============== | ======= | ====== | =================== | =================== | =================== | =================== | =========== | ====================== | ============= | ==== | ================================ | ===== | ============== | 
| A0000117  | 62A   | BURGLAR ALARM, SILENT | 2C       | 62A         | BURGLAR ALARM, SILENT      | 2C              | 3671806 | 537333 | 2017-01-01T00:00:14 | 2017-01-01T00:13:32 | 2017-01-01T00:17:30 | 2017-01-01T00:24:51 | NAT         | Necessary Action Taken | N             | 1L04 | 001XX S Cortez St                | 70119 | 1              | 
| A0000217  | 103   | DISTURBANCE (OTHER)   | 1A       | 103         | DISTURBANCE (OTHER)        | 1A              | 3667431 | 534105 | 2017-01-01T00:01:13 |                     | 2017-01-01T00:01:13 | 2017-01-01T00:34:09 | NAT         | Necessary Action Taken | Y             | 2U04 | 034XX S Carrollton Ave           | 70125 | 2              | 
| A0000317  | 94F   | FIREWORKS             | 1A       | 95          | ILLEGAL CARRYING OF WEAPON | 2B              | 3666742 | 530866 | 2017-01-01T00:02:03 | 2017-01-01T00:18:21 |                     | 2017-01-01T00:20:54 | NAT         | Necessary Action Taken | N             | 2P02 | Pine St & Fontainebleau Dr       | 70125 | 2              | 
| A0000417  | 103F  | FIGHT                 | 2B       | 21          | COMPLAINT OTHER            | 1H              | 3681754 | 532071 | 2017-01-01T00:02:43 | 2017-01-01T00:02:52 |                     | 2017-01-01T01:39:11 | NAT         | Necessary Action Taken | N             | 8D05 | 004XX Bourbon St                 | 70112 | 8              | 
| A0000517  | 94F   | FIREWORKS             | 1A       | 21          | COMPLAINT OTHER            | 1H              | 3675501 | 521216 | 2017-01-01T00:03:43 | 2017-01-01T00:05:13 |                     | 2017-01-01T00:05:33 | NAT         | Necessary Action Taken | N             | 6D02 | 014XX 8th St                     | 70115 | 6              | 
| A0000617  | 94    | DISCHARGING FIREARM   | 2B       | 94          | DISCHARGING FIREARM        | 2B              | 3704499 | 559296 | 2017-01-01T00:04:37 | 2017-01-01T00:05:48 | 2017-01-01T00:05:30 | 2017-01-01T00:14:23 | GOA         | GONE ON ARRIVAL        | N             | 7O04 | N I-10 Service Rd & Crowder Blvd | 70127 | 7              | 
| A0000717  | 34    | AGGRAVATED BATTERY    | 2B       | 34          | AGGRAVATED BATTERY         | 2B              | 3674258 | 534731 | 2017-01-01T00:04:48 | 2017-01-01T00:09:38 |                     | 2017-01-01T00:13:09 | GOA         | GONE ON ARRIVAL        | N             | 1L01 | 003XX S White St                 | 70119 | 1              | 
| A0000817  | 94    | DISCHARGING FIREARM   | 1A       | 94          | DISCHARGING FIREARM        | 2B              | 3695193 | 525938 | 2017-01-01T00:05:00 | 2017-01-01T00:55:03 | 2017-01-01T00:56:05 | 2017-01-01T00:59:30 | GOA         | GONE ON ARRIVAL        | N             | 4I03 | 014XX Southlawn Blvd             | 70114 | 4              | 
| A0000917  | 21    | COMPLAINT OTHER       | 1A       | 21          | COMPLAINT OTHER            | 2A              | 3663885 | 527492 | 2017-01-01T00:05:20 | 2017-01-01T00:23:43 | 2017-01-01T01:18:14 | 2017-01-01T01:20:56 | NAT         | Necessary Action Taken | N             | 2L03 | 075XX Willow St                  | 70118 | 2              | 
| A0001017  | 94F   | FIREWORKS             | 2H       | 94          | DISCHARGING FIREARM        | 2B              | 3680014 | 547994 | 2017-01-01T00:05:44 | 2017-01-01T00:35:26 | 2017-01-01T00:43:50 | 2017-01-01T00:45:55 | NAT         | Necessary Action Taken | N             | 3P02 | 043XX Van Ave                    | 70122 | 3              | 
```