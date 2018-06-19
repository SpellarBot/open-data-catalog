# HPD Fund Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-fund-element-61da0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hc6m-qm6w) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hc6m-qm6w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hc6m-qm6w/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hc6m-qm6w |
| Name | HPD Fund Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, fund element |
| Created | 2014-02-26T21:30:54Z |
| Publication Date | 2014-02-27T16:35:53Z |

## Description

Information on funding amounts, name and type for those funds that meet the definition of City Financial Assistance for each project.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | fund_dw_id  | Fund DW ID | text      | number      |
| Yes      | series tag     | project_id  | Project ID | text      | number      |
| Yes      | series tag     | fund_name   | Fund Name  | text      | text        |
| Yes      | series tag     | type        | Type       | text      | text        |
| Yes      | numeric metric | amount      | Amount     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hc6m-qm6w d:2014-02-26T13:30:59.000Z t:fund_name="City Capital" t:fund_dw_id=2496 t:project_id=39155 t:type=Loan m:amount=4243450

series e:hc6m-qm6w d:2014-02-26T13:30:59.000Z t:fund_name="City Capital" t:fund_dw_id=2500 t:project_id=39223 t:type=Loan m:amount=2132692

series e:hc6m-qm6w d:2014-02-26T13:30:59.000Z t:fund_name="City Capital" t:fund_dw_id=2289 t:project_id=39227 t:type=Loan m:amount=1244000
```

## Meta Commands

```ls
metric m:amount p:float l:Amount d:"Dollar amount at the start of project" t:dataTypeName=number

entity e:hc6m-qm6w l:"HPD Fund Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/hc6m-qm6w

property e:hc6m-qm6w t:meta.view v:id=hc6m-qm6w v:category="Housing & Development" v:averageRating=0 v:name="HPD Fund Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:hc6m-qm6w t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hc6m-qm6w t:meta.view.tableauthor v:id=uurm-7z6x v:screenName=Siddhartha v:displayName=Siddhartha
```

## Top Records

```ls
| :updated_at | fund_dw_id | project_id | fund_name    | type | amount     | 
| =========== | ========== | ========== | ============ | ==== | ========== | 
| 1393421459  | 2496       | 39155      | City Capital | Loan | 4243450.00 | 
| 1393421459  | 2500       | 39223      | City Capital | Loan | 2132692.00 | 
| 1393421459  | 2289       | 39227      | City Capital | Loan | 1244000.00 | 
| 1393421459  | 2963       | 39256      | Reso A       | Loan | 135000.00  | 
| 1393421459  | 1820       | 39256      | City Capital | Loan | 665000.00  | 
| 1393421459  | 1445       | 39264      | HOME         | Loan | 1327266.00 | 
| 1393421459  | 2290       | 39326      | City Capital | Loan | 618267.00  | 
| 1393421459  | 1433       | 39326      | HOME         | Loan | 527000.00  | 
| 1393421459  | 1351       | 39343      | City Capital | Loan | 3621482.00 | 
| 1393421459  | 2178       | 39349      | Reso A       | Loan | 500000.00  | 
```