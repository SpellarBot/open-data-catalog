# BRS Field Office Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brs-field-office-locations) |
| Metadata | [Link](https://data.ct.gov/api/views/7hah-zeuv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/7hah-zeuv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/7hah-zeuv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 7hah-zeuv |
| Name | BRS Field Office Locations |
| Attribution | Department of Rehabilitation Services |
| Category | Health and Human Services |
| Created | 2014-07-08T14:06:34Z |
| Publication Date | 2014-07-08T14:16:05Z |

## Description

Location and phone numbers for all Department of Rehabilitation Services - Bureau of Rehabilitation Services field offices

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | city        | City       | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7hah-zeuv d:2014-07-08T07:09:36.000Z t:phone="(203) 732-1667" t:zip_code=06401 t:city=Ansonia m:row_number.7hah-zeuv=1

series e:7hah-zeuv d:2014-07-08T07:09:42.000Z t:phone="(203) 551-5500" t:zip_code=06604 t:city=Bridgeport m:row_number.7hah-zeuv=2

series e:7hah-zeuv d:2014-07-08T07:09:47.000Z t:phone="(203) 207-8990" t:zip_code=06810 t:city=Danbury m:row_number.7hah-zeuv=3
```

## Meta Commands

```ls
metric m:row_number.7hah-zeuv p:long l:"Row Number"

entity e:7hah-zeuv l:"BRS Field Office Locations" t:attribution="Department of Rehabilitation Services" t:url=https://data.ct.gov/api/views/7hah-zeuv

property e:7hah-zeuv t:meta.view v:id=7hah-zeuv v:category="Health and Human Services" v:averageRating=0 v:name="BRS Field Office Locations" v:attribution="Department of Rehabilitation Services"

property e:7hah-zeuv t:meta.view.owner v:id=g7gd-t9kf v:screenName="Kathleen Sullivan" v:displayName="Kathleen Sullivan"

property e:7hah-zeuv t:meta.view.tableauthor v:id=g7gd-t9kf v:screenName="Kathleen Sullivan" v:roleName=editor v:displayName="Kathleen Sullivan"
```

## Top Records

```ls
| :updated_at | city        | zip_code | phone          | 
| =========== | =========== | ======== | ============== | 
| 1404803376  | Ansonia     | 06401    | (203) 732-1667 | 
| 1404803382  | Bridgeport  | 06604    | (203) 551-5500 | 
| 1404803387  | Danbury     | 06810    | (203) 207-8990 | 
| 1404803393  | Danielson   | 06239    | (860) 412-7070 | 
| 1404803398  | Enfield     | 06082    | (860) 899-3567 | 
| 1404803401  | Hartford    | 06120    | (860) 723-1400 | 
| 1404803404  | Manchester  | 06040    | (860) 647-5960 | 
| 1404803407  | Middletown  | 06457    | (860) 704-3070 | 
| 1404803426  | New Britain | 06051    | (860) 612-3569 | 
| 1404803438  | New Haven   | 06511    | (203) 974-3000 | 
```