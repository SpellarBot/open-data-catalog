# HPD Developer Selection Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-developer-selection-element-509c4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fged-sxa8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fged-sxa8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fged-sxa8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fged-sxa8 |
| Name | HPD Developer Selection Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, developer selection |
| Created | 2014-02-26T17:30:51Z |
| Publication Date | 2014-02-27T19:24:57Z |

## Description

Information on how the developer was selected for each project.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | developer_selection_dw_id  | Developer Selection DW ID  | text      | number      |
| Yes      | series tag  | project_id                 | Project ID                 | text      | number      |
| Yes      | series tag  | method                     | Method                     | text      | text        |
| Yes      | series tag  | rfp_name                   | RFP Name                   | text      | text        |
| Yes      | series tag  | rfq_name                   | RFQ Name                   | text      | text        |
| Yes      | series tag  | is_developer_prequalified_ | Is Developer Prequalified? | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fged-sxa8 d:2014-02-26T09:30:56.000Z t:developer_selection_dw_id=265 t:is_developer_prequalified_=No t:project_id=38989 t:method="Direct Negotiation" m:row_number.fged-sxa8=1

series e:fged-sxa8 d:2014-02-26T09:30:56.000Z t:developer_selection_dw_id=274 t:is_developer_prequalified_=No t:project_id=38990 t:method="Direct Negotiation" m:row_number.fged-sxa8=2

series e:fged-sxa8 d:2014-02-26T09:30:56.000Z t:developer_selection_dw_id=221 t:is_developer_prequalified_=No t:project_id=38991 t:method="Direct Negotiation" m:row_number.fged-sxa8=3
```

## Meta Commands

```ls
metric m:row_number.fged-sxa8 p:long l:"Row Number"

entity e:fged-sxa8 l:"HPD Developer Selection Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/fged-sxa8

property e:fged-sxa8 t:meta.view v:id=fged-sxa8 v:category="Housing & Development" v:averageRating=0 v:name="HPD Developer Selection Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:fged-sxa8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fged-sxa8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | developer_selection_dw_id | project_id | method                     | rfp_name | rfq_name        | is_developer_prequalified_ | 
| =========== | ========================= | ========== | ========================== | ======== | =============== | ========================== | 
| 1393407056  | 265                       | 38989      | Direct Negotiation         |          |                 | No                         | 
| 1393407056  | 274                       | 38990      | Direct Negotiation         |          |                 | No                         | 
| 1393407056  | 221                       | 38991      | Direct Negotiation         |          |                 | No                         | 
| 1393407056  | 284                       | 39155      | Application                |          |                 | No                         | 
| 1393407056  | 280                       | 39223      | Application                |          |                 | No                         | 
| 1393407056  | 520                       | 39227      | Request for Qualifications |          | TPT Round 6 RFQ | Yes                        | 
| 1393407056  | 195                       | 39256      | Application                |          |                 | No                         | 
| 1393407056  | 505                       | 39264      | Application                |          |                 | No                         | 
| 1393407056  | 519                       | 39326      | Request for Qualifications |          | TPT Round 5 RFQ | Yes                        | 
| 1393407056  | 507                       | 39343      | Request for Qualifications |          | TPT Round 7 RFQ | Yes                        | 
```