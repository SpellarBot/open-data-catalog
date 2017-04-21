# Bank-Owned ATM Locations in New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bank-owned-atm-locations-in-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/ndex-ad5r) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ndex-ad5r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ndex-ad5r/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ndex-ad5r |
| Name | Bank-Owned ATM Locations in New York State |
| Attribution | Department of Financial Services |
| Category | Government & Finance |
| Tags | financial, banking, atm |
| Created | 2014-06-13T18:05:24Z |
| Publication Date | 2016-11-04T22:14:32Z |

## Description

A list of all bank owned or in-bank ATMs located in New York State.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | name_of_institution | Name of Institution | text      | text        |
| Yes      | series tag  | street_address      | Street Address      | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | zip_code            | ZIP Code            | text      | number      |
| Yes      | series tag  | county              | County              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ndex-ad5r d:2016-11-04T22:14:19.000Z t:name_of_institution="Abacus Federal Savings Bank" t:zip_code=11220 t:county=Kings t:street_address="5518 8th Avenue" t:city=Brooklyn m:row_number.ndex-ad5r=1

series e:ndex-ad5r d:2016-11-04T22:14:19.000Z t:name_of_institution="Abacus Federal Savings Bank" t:zip_code=11354 t:county=Queens t:street_address="36-30 Main Street" t:city=Flushing m:row_number.ndex-ad5r=2

series e:ndex-ad5r d:2016-11-04T22:14:19.000Z t:name_of_institution="Abacus Federal Savings Bank" t:zip_code=10013 t:county="New York" t:street_address="6-8 Bowery" t:city="New York" m:row_number.ndex-ad5r=3
```

## Meta Commands

```ls
metric m:row_number.ndex-ad5r p:long l:"Row Number"

entity e:ndex-ad5r l:"Bank-Owned ATM Locations in New York State" t:attribution="Department of Financial Services" t:url=https://data.ny.gov/api/views/ndex-ad5r

property e:ndex-ad5r t:meta.view v:id=ndex-ad5r v:category="Government & Finance" v:attributionLink=http://www.dfs.ny.gov v:averageRating=0 v:name="Bank-Owned ATM Locations in New York State" v:attribution="Department of Financial Services"

property e:ndex-ad5r t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ndex-ad5r t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ndex-ad5r t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name_of_institution         | street_address         | city         | zip_code | county   | 
| =========== | =========================== | ====================== | ============ | ======== | ======== | 
| 1478297659  | Abacus Federal Savings Bank | 5518 8th Avenue        | Brooklyn     | 11220    | Kings    | 
| 1478297659  | Abacus Federal Savings Bank | 36-30 Main Street      | Flushing     | 11354    | Queens   | 
| 1478297659  | Abacus Federal Savings Bank | 6-8 Bowery             | New York     | 10013    | New York | 
| 1478297659  | Access Federal Credit Union | 230 South James Street | Rome         | 13440    | Oneida   | 
| 1478297659  | Access Federal Credit Union | 74-76 Main Street      | Camden       | 13316    | Oneida   | 
| 1478297659  | Access Federal Credit Union | 390 West Seneca Street | Sherrill     | 13461    | Oneida   | 
| 1478297659  | Access Federal Credit Union | 2094 Glenwood Plaza    | Oneida       | 13421    | Madison  | 
| 1478297659  | Access Federal Credit Union | 6 Franklin             | Clinton      | 13323    | Oneida   | 
| 1478297659  | Adirondack Bank             | 108 Codling Street     | Old Forge    | 13420    | Herkimer | 
| 1478297659  | Adirondack Bank             | 4697 Commercial Drive  | New Hartford | 13413    | Oneida   | 
```