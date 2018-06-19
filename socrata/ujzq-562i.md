# HPD LIHTC Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-lihtc-element-d88be) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ujzq-562i) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ujzq-562i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ujzq-562i/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ujzq-562i |
| Name | HPD LIHTC Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, lihtc |
| Created | 2014-02-26T21:30:57Z |
| Publication Date | 2014-02-27T19:49:40Z |

## Description

Information on Low Income Housing Tax Credit (LIHTC) allocation amounts and type for those LIHTC allocations that meet the definition of City Financial Assistance for each project.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | lihtc_dw_id              | LIHTC DW ID              | text      | number      |
| Yes      | series tag     | project_id               | Project ID               | text      | number      |
| Yes      | series tag     | type                     | Type                     | text      | text        |
| Yes      | numeric metric | annual_allocation_amount | Annual Allocation Amount | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ujzq-562i d:2014-02-26T13:31:01.000Z t:lihtc_dw_id=4 t:project_id=48910 t:type="4% LIHTC" m:annual_allocation_amount=907426

series e:ujzq-562i d:2014-02-26T13:31:01.000Z t:lihtc_dw_id=5 t:project_id=49517 t:type="9% LIHTC" m:annual_allocation_amount=2195000

series e:ujzq-562i d:2014-02-26T13:31:01.000Z t:lihtc_dw_id=6 t:project_id=44865 t:type="9% LIHTC" m:annual_allocation_amount=1141200
```

## Meta Commands

```ls
metric m:annual_allocation_amount p:float l:"Annual Allocation Amount" d:"Annual amount of 4% or 9% of Low Income Housing Tax Credits (LIHTC) allocated. This is estimated at Project start and finalized at Project completion" t:dataTypeName=number

entity e:ujzq-562i l:"HPD LIHTC Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/ujzq-562i

property e:ujzq-562i t:meta.view v:id=ujzq-562i v:category="Housing & Development" v:averageRating=0 v:name="HPD LIHTC Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:ujzq-562i t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ujzq-562i t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | lihtc_dw_id | project_id | type     | annual_allocation_amount | 
| =========== | =========== | ========== | ======== | ======================== | 
| 1393421461  | 4           | 48910      | 4% LIHTC | 907426.00                | 
| 1393421461  | 5           | 49517      | 9% LIHTC | 2195000.00               | 
| 1393421461  | 6           | 44865      | 9% LIHTC | 1141200.00               | 
| 1393421461  | 7           | 49576      | 9% LIHTC | 808017.00                | 
| 1393421461  | 8           | 48766      | 4% LIHTC | 2246580.00               | 
| 1393421461  | 9           | 48625      | 9% LIHTC | 1219919.00               | 
| 1393421461  | 10          | 44350      | 9% LIHTC | 1342000.00               | 
| 1393421461  | 11          | 48726      | 4% LIHTC | 1689687.00               | 
| 1393421461  | 12          | 49143      | 4% LIHTC | 863885.00                | 
| 1393421461  | 13          | 46299      | 4% LIHTC | 972365.00                | 
```