# Calls for Service 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calls-for-service-2012) |
| Metadata | [Link](https://data.nola.gov/api/views/rv3g-ypg7) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/rv3g-ypg7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/rv3g-ypg7/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | rv3g-ypg7 |
| Name | Calls for Service 2012 |
| Attribution | Orleans Parish Communications District |
| Category | Public Safety and Preparedness |
| Tags | crime, police, nopd |
| Created | 2013-01-03T23:49:27Z |
| Publication Date | 2016-02-11T22:53:00Z |

## Description

This dataset reflects incidents that have been reported to the New Orleans Police Department in 2012. Data is provided by Orleans Parish Communication District (OPCD), the administrative office of 9-1-1 for the City of New Orleans. In the OPCD system, NOPD may reclassify or change the signal type for up to 36 hours after the incident is marked up. For information about an incident after this time period, citizens may request police reports from the NOPD Public Records Division.  In order to protect the privacy of victims, addresses are shown at the block level and the call types cruelty to juveniles, juvenile attachment and missing juvenile have been removed in accordance with the Louisiana Public Records Act, L.R.S. 44:1.  Map coordinates (X,Y) have been removed for the following call types: Aggravated Rape, Aggravated Rape - MA, Crime Against Nature, Mental Patient, Oral Sexual Battery, Prostitution, Sexual Battery, Simple Rape, Simple Rape - Male V, and Soliciting for Prost.Disclaimer: These incidents may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | nopd_item       | NOPD_Item       | text          | text          |
| Yes      | series tag  | type            | Type_           | text          | text          |
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
series e:rv3g-ypg7 d:2012-01-01T00:00:11.000Z t:zip=70116 t:nopd_item=A0000112 t:priority=2C t:dispositiontext="NECESSARY ACTION TAKEN" t:policedistrict=8 t:typetext="BURGLAR ALARM, SILEN" t:type=62A t:disposition=NAT m:row_number.rv3g-ypg7=1

series e:rv3g-ypg7 d:2012-01-01T00:00:36.000Z t:zip=70129 t:nopd_item=A0000412 t:priority=2B t:dispositiontext=UNFOUNDED t:policedistrict=7 t:typetext="DISCHARGING FIREARMS" t:type=94 t:disposition=UNF m:row_number.rv3g-ypg7=2

series e:rv3g-ypg7 d:2012-01-01T00:01:13.000Z t:zip=70122 t:nopd_item=A0000212 t:priority=1C t:dispositiontext="NECESSARY ACTION TAKEN" t:policedistrict=3 t:typetext="DISTURBANCE (OTHER)" t:type=103 t:disposition=NAT m:row_number.rv3g-ypg7=3
```

## Meta Commands

```ls
metric m:row_number.rv3g-ypg7 p:long l:"Row Number"

entity e:rv3g-ypg7 l:"Calls for Service 2012" t:attribution="Orleans Parish Communications District" t:url=https://data.nola.gov/api/views/rv3g-ypg7

property e:rv3g-ypg7 t:meta.view v:id=rv3g-ypg7 v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Calls for Service 2012" v:attribution="Orleans Parish Communications District"

property e:rv3g-ypg7 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rv3g-ypg7 t:meta.view.owner v:id=etmh-sfwk v:screenName="Greg Hymel" v:displayName="Greg Hymel"

property e:rv3g-ypg7 t:meta.view.tableauthor v:id=etmh-sfwk v:screenName="Greg Hymel" v:roleName=publisher v:displayName="Greg Hymel"

property e:rv3g-ypg7 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| nopd_item | type | typetext             | priority | mapx             | mapy            | timecreate          | timedispatch        | timearrive          | timeclosed          | disposition | dispositiontext        | block_address                | zip   | policedistrict | 
| ========= | ==== | ==================== | ======== | ================ | =============== | =================== | =================== | =================== | =================== | =========== | ====================== | ============================ | ===== | ============== | 
| A0000112  | 62A  | BURGLAR ALARM, SILEN | 2C       | 3683627.00000000 | 532625.00000000 | 2012-01-01T00:00:11 | 2012-01-01T00:02:46 |                     | 2012-01-01T00:33:32 | NAT         | NECESSARY ACTION TAKEN | 009XX Decatur St             | 70116 | 8              | 
| A0000412  | 94   | DISCHARGING FIREARMS | 2B       | 3732996.00000000 | 562418.00000000 | 2012-01-01T00:00:36 | 2012-01-01T00:03:22 | 2012-01-01T00:16:59 | 2012-01-01T00:30:09 | UNF         | UNFOUNDED              | 147XX Chef Menteur Hwy       | 70129 | 7              | 
| A0000212  | 103  | DISTURBANCE (OTHER)  | 1C       | 3687688.00000000 | 548824.00000000 | 2012-01-01T00:01:13 | 2012-01-01T00:01:19 | 2012-01-01T00:01:44 | 2012-01-01T00:19:52 | NAT         | NECESSARY ACTION TAKEN | 038XX Gentilly Blvd          | 70122 | 3              | 
| A0000712  | 21   | COMPLAINT OTHER      | 1H       | 3670776.00000000 | 521242.00000000 | 2012-01-01T00:01:18 | 2012-01-01T00:13:35 |                     | 2012-01-01T00:20:13 | NAT         | NECESSARY ACTION TAKEN | Carondelet St & Napoleon Ave | 70115 | 2              | 
| A0000512  | 62A  | BURGLAR ALARM, SILEN | 2C       | 3665739.00000000 | 549621.00000000 | 2012-01-01T00:01:20 | 2012-01-01T00:02:52 | 2012-01-01T00:09:11 | 2012-01-01T01:55:13 | NAT         | NECESSARY ACTION TAKEN | 002XX W Harrison Ave         | 70124 | 3              | 
| A0000912  | 94   | DISCHARGING FIREARMS | 2B       | 3665391.00000000 | 536341.00000000 | 2012-01-01T00:01:48 | 2012-01-01T00:04:56 | 2012-01-01T00:10:07 | 2012-01-01T00:11:51 | NAT         | NECESSARY ACTION TAKEN | Edinburgh St & Gen Ogden St  | 70118 | 2              | 
| A0000612  | 94F  | FIREWORKS            | 1H       | 3675716.00000000 | 524537.00000000 | 2012-01-01T00:01:53 | 2012-01-01T00:13:59 |                     | 2012-01-01T00:14:35 | NAT         | NECESSARY ACTION TAKEN | 2nd St & S Saratoga St       | 70113 | 6              | 
| A0000812  | 94   | DISCHARGING FIREARMS | 2B       | 3669605.00000000 | 530044.00000000 | 2012-01-01T00:01:57 | 2012-01-01T00:04:22 | 2012-01-01T00:07:00 | 2012-01-01T00:08:06 | NAT         | NECESSARY ACTION TAKEN | 044XX Walmsley Ave           | 70125 | 2              | 
| A0001012  | 94F  | FIREWORKS            | 1H       | 3698138.00000000 | 552955.00000000 | 2012-01-01T00:02:30 | 2012-01-01T00:18:28 | 2012-01-01T00:30:35 | 2012-01-01T00:39:17 | NAT         | NECESSARY ACTION TAKEN | 045XX Lynhuber Dr            | 70126 | 7              | 
| A0001212  | 107  | SUSPICIOUS PERSON    | 2B       | 3705859.00000000 | 561144.00000000 | 2012-01-01T00:02:44 | 2012-01-01T00:35:42 |                     | 2012-01-01T00:41:18 | GOA         | GONE ON ARRIVAL        | 072XX Yorktown Dr            | 70127 | 7              | 
```