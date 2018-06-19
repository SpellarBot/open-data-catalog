# Oregon Agencies, Boards and Commissions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-agencies-boards-and-commissions-d3971) |
| Metadata | [Link](https://data.oregon.gov/api/views/wu8n-jqum) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wu8n-jqum/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wu8n-jqum/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wu8n-jqum |
| Name | Oregon Agencies, Boards and Commissions |
| Attribution | Department of Administrative Services. Data assembled from the Oregon Blue Book, State Agency Directory, Oregon Accounting Manual and Agency A-Z list on Oregon.gov. |
| Category | Administrative |
| Tags | agency, agencies, board, boards, commissions, public meeting notice |
| Created | 2011-04-11T23:38:17Z |
| Publication Date | 2017-04-03T22:34:44Z |

## Description

A listing of Oregon agencies boards and commissions. The primary intention of this dataset is to be used as a lookup field when inputting data into the the Public Meeting Notices dataset.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | organization_name | Organization Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wu8n-jqum d:2011-04-14T09:34:44.000Z t:organization_name="Accountancy State Board" m:row_number.wu8n-jqum=1

series e:wu8n-jqum d:2011-04-14T09:34:44.000Z t:organization_name="Acquired Infections Committee" m:row_number.wu8n-jqum=2

series e:wu8n-jqum d:2011-04-14T09:34:44.000Z t:organization_name="Administrative Hearings, Office of" m:row_number.wu8n-jqum=3
```

## Meta Commands

```ls
metric m:row_number.wu8n-jqum p:long l:"Row Number"

entity e:wu8n-jqum l:"Oregon Agencies, Boards and Commissions" t:attribution="Department of Administrative Services. Data assembled from the Oregon Blue Book, State Agency Directory, Oregon Accounting Manual and Agency A-Z list on Oregon.gov." t:url=https://data.oregon.gov/api/views/wu8n-jqum

property e:wu8n-jqum t:meta.view v:id=wu8n-jqum v:category=Administrative v:averageRating=0 v:name="Oregon Agencies, Boards and Commissions" v:attribution="Department of Administrative Services. Data assembled from the Oregon Blue Book, State Agency Directory, Oregon Accounting Manual and Agency A-Z list on Oregon.gov."

property e:wu8n-jqum t:meta.view.license v:name="Public Domain"

property e:wu8n-jqum t:meta.view.owner v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:displayName="Wally Rogers"

property e:wu8n-jqum t:meta.view.tableauthor v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:roleName=administrator v:displayName="Wally Rogers"
```

## Top Records

```ls
| :updated_at | organization_name                   | 
| =========== | =================================== | 
| 1302773684  | Accountancy State Board             | 
| 1302773684  | Acquired Infections Committee       | 
| 1302773684  | Administrative Hearings, Office of  | 
| 1302773684  | Administrative Services Department  | 
| 1302773684  | Advocacy Commissions Office, Oregon | 
| 1302773684  | Agriculture Board                   | 
| 1302773684  | Agriculture Department              | 
| 1302773684  | Albacore Commission, Oregon         | 
| 1302773684  | Alcohol and Drug Policy Commission  | 
| 1302773684  | Alfalfa Seed Commission, Oregon     | 
```