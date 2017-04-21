# SoQL Testing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/soql-testing) |
| Metadata | [Link](https://data.nola.gov/api/views/gz4p-phzs) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/gz4p-phzs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/gz4p-phzs/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | gz4p-phzs |
| Name | SoQL Testing |
| Created | 2015-12-22T17:02:24Z |
| Publication Date | 2015-12-22T17:11:39Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | nopd_item       | NOPD_Item       | text          | text          |
| Yes      | series tag  | type_           | Type_           | text          | text          |
| Yes      | series tag  | typetext        | TypeText        | text          | text          |
| Yes      | series tag  | priority        | Priority        | text          | text          |
| No       |             | mapx            | MapX            | number        | number        |
| No       |             | mapy            | MapY            | number        | number        |
| Yes      | time        | timecreate      | TimeCreate      | calendar_date | calendar_date |
| No       |             | timedispatch    | TimeDispatch    | calendar_date | calendar_date |
| No       |             | timearrive      | TimeArrive      | calendar_date | calendar_date |
| No       |             | timeclosed      | TimeClosed      | calendar_date | calendar_date |
| Yes      | series tag  | disposition     | Disposition     | text          | text          |
| Yes      | series tag  | dispositiontext | DispositionText | text          | text          |
| No       |             | block_address   | BLOCK_ADDRESS   | text          | text          |
| Yes      | series tag  | zip             | Zip             | text          | number        |
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
series e:gz4p-phzs d:2015-10-01T00:00:50.000Z t:zip=70118 t:type_=21 t:nopd_item=J0000115 t:priority=1H t:dispositiontext="Necessary Action Taken" t:policedistrict=2 t:typetext="COMPLAINT OTHER" t:disposition=NAT m:row_number.gz4p-phzs=1

series e:gz4p-phzs d:2015-10-01T00:00:51.000Z t:zip=70117 t:type_=103 t:nopd_item=J0000215 t:priority=1A t:dispositiontext=UNFOUNDED t:policedistrict=5 t:typetext="DISTURBANCE (OTHER)" t:disposition=UNF m:row_number.gz4p-phzs=2

series e:gz4p-phzs d:2015-10-01T00:02:23.000Z t:zip=70115 t:type_=18 t:nopd_item=J0000315 t:priority=1H t:dispositiontext="Necessary Action Taken" t:policedistrict=2 t:typetext="TRAFFIC INCIDENT" t:disposition=NAT m:row_number.gz4p-phzs=3
```

## Meta Commands

```ls
metric m:row_number.gz4p-phzs p:long l:"Row Number"

entity e:gz4p-phzs l:"SoQL Testing" t:url=https://data.nola.gov/api/views/gz4p-phzs

property e:gz4p-phzs t:meta.view v:id=gz4p-phzs v:averageRating=0 v:name="SoQL Testing"

property e:gz4p-phzs t:meta.view.owner v:id=7kk9-bewq v:screenName="J.B. Raasch" v:displayName="J.B. Raasch"

property e:gz4p-phzs t:meta.view.tableauthor v:id=7kk9-bewq v:screenName="J.B. Raasch" v:roleName=administrator v:displayName="J.B. Raasch"

property e:gz4p-phzs t:meta.view.metadata.custom_fields.common_core v:Contact_Email=jbraasch@nola.gov
```

## Top Records

```ls
| nopd_item | type_ | typetext            | priority | mapx    | mapy   | timecreate          | timedispatch        | timearrive          | timeclosed          | disposition | dispositiontext        | block_address                 | zip   | policedistrict | 
| ========= | ===== | =================== | ======== | ======= | ====== | =================== | =================== | =================== | =================== | =========== | ====================== | ============================= | ===== | ============== | 
| J0000115  | 21    | COMPLAINT OTHER     | 1H       | 3661552 | 532096 | 2015-10-01T00:00:50 | 2015-10-01T00:02:50 | 2015-10-01T00:10:34 | 2015-10-01T00:23:24 | NAT         | Necessary Action Taken | 019XX General Ogden St        | 70118 | 2              | 
| J0000215  | 103   | DISTURBANCE (OTHER) | 1A       | 3684990 | 538273 | 2015-10-01T00:00:51 | 2015-10-01T00:40:04 | 2015-10-01T00:43:41 | 2015-10-01T00:53:29 | UNF         | UNFOUNDED              | 016XX Elysian Fields Ave      | 70117 | 5              | 
| J0000315  | 18    | TRAFFIC INCIDENT    | 1H       | 3668599 | 517215 | 2015-10-01T00:02:23 |                     | 2015-10-01T00:02:23 | 2015-10-01T00:04:21 | NAT         | Necessary Action Taken | Robert St & Tchoupitoulas St  | 70115 | 2              | 
| J0000515  | 21    | COMPLAINT OTHER     | 1H       | 3691350 | 527943 | 2015-10-01T00:06:36 | 2015-10-01T00:07:32 | 2015-10-01T00:06:36 | 2015-10-01T01:59:37 | NAT         | Necessary Action Taken | 019XX Newton St               | 70114 | 4              | 
| J0000615  | 21    | COMPLAINT OTHER     | 1H       | 3671394 | 518823 | 2015-10-01T00:07:01 |                     | 2015-10-01T00:07:01 | 2015-10-01T00:38:27 | NAT         | Necessary Action Taken | 043XX Magazine St             | 70115 | 6              | 
| J0000715  | 18    | TRAFFIC INCIDENT    | 1H       | 3697619 | 520025 | 2015-10-01T00:07:25 |                     | 2015-10-01T00:07:25 | 2015-10-01T00:56:07 | NAT         | Necessary Action Taken | 037XX General De Gaulle Dr    | 70114 | 4              | 
| J0000815  | 21    | COMPLAINT OTHER     | 2A       | 3701681 | 559170 | 2015-10-01T00:07:48 |                     | 2015-10-01T00:08:12 | 2015-10-01T02:37:16 | NAT         | Necessary Action Taken | 071XX Neptune Ct              | 70126 | 7              | 
| J0000915  | 18    | TRAFFIC INCIDENT    | 1H       | 3684104 | 546998 | 2015-10-01T00:08:24 |                     | 2015-10-01T00:08:24 | 2015-10-01T00:26:13 | NAT         | Necessary Action Taken | 039XX Elysian Fields Ave      | 70122 | 3              | 
| J0001015  | 18    | TRAFFIC INCIDENT    | 1H       | 3677642 | 538157 | 2015-10-01T00:08:57 |                     | 2015-10-01T00:08:57 | 2015-10-01T00:19:23 | NAT         | Necessary Action Taken | N Broad St & Ursulines Ave    | 70119 | 1              | 
| J0001115  | 18    | TRAFFIC INCIDENT    | 1H       | 3672231 | 554831 | 2015-10-01T00:09:23 |                     | 2015-10-01T00:09:23 | 2015-10-01T00:28:20 | NAT         | Necessary Action Taken | Thrush St & Marconi Dr (3K01) | 70124 | 3              | 
```