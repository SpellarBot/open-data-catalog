# Grocery Stores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grocery-stores-80b33) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/uuwk-975y) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/uuwk-975y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/uuwk-975y/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | uuwk-975y |
| Name | Grocery Stores |
| Attribution | Baltimore City Planning Department |
| Category | Health |
| Tags | food, grocery |
| Created | 2011-12-14T17:45:30Z |
| Publication Date | 2014-04-03T23:27:00Z |

## Description

This data lists the locations of grocery stores in the City. This may not be a complete list.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | type            | type            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uuwk-975y d:2011-12-14T09:46:02.000Z t:councildistrict=11 t:zipcode=21217 t:name=SAVE-A-LOT t:neighborhood="Bolton Hill" t:policedistrict=CENTRAL t:type="Limited Supermarket" m:row_number.uuwk-975y=1

series e:uuwk-975y d:2011-12-14T09:46:02.000Z t:councildistrict=6 t:zipcode=21215 t:name=ALDI t:neighborhood=Ashburton t:policedistrict=NORTHWESTERN t:type="Limited Supermarket" m:row_number.uuwk-975y=2

series e:uuwk-975y d:2011-12-14T09:46:02.000Z t:councildistrict=10 t:zipcode=21230 t:name="ALDI     (A.K.A. 3000 ATCO AVENUE)" t:neighborhood="Morrell Park" t:policedistrict=SOUTHWESTERN t:type="Limited Supermarket" m:row_number.uuwk-975y=3
```

## Meta Commands

```ls
metric m:row_number.uuwk-975y p:long l:"Row Number"

entity e:uuwk-975y l:"Grocery Stores" t:attribution="Baltimore City Planning Department" t:url=https://data.baltimorecity.gov/api/views/uuwk-975y

property e:uuwk-975y t:meta.view v:id=uuwk-975y v:category=Health v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Planning.aspx v:averageRating=0 v:name="Grocery Stores" v:attribution="Baltimore City Planning Department"

property e:uuwk-975y t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:uuwk-975y t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:uuwk-975y t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                            | type                | zipcode | neighborhood            | councildistrict | policedistrict | 
| =========== | =============================== | =================== | ======= | ======================= | =============== | ============== | 
| 1323855962  | SAVE-A-LOT                      | Limited Supermarket | 21217   | Bolton Hill             | 11              | CENTRAL        | 
| 1323855962  | ALDI                            | Limited Supermarket | 21215   | Ashburton               | 6               | NORTHWESTERN   | 
| 1323855962  | ALDI (A.K.A. 3000 ATCO AVENUE)  | Limited Supermarket | 21230   | Morrell Park            | 10              | SOUTHWESTERN   | 
| 1323855962  | SAVE A LOT OF FELLS POINT       | Limited Supermarket | 21231   | Fells Point             | 1               | SOUTHEASTERN   | 
| 1323855962  | SAFEWAY, INC.                   | Full Supermarket    | 21218   | Charles Village         | 12              | NORTHERN       | 
| 1323855962  | SANTONI'S, INC.                 | Small Supermarket   | 21224   | Baltimore Highlands     | 2               | SOUTHEASTERN   | 
| 1323855962  | SHOPPERS FOOD & PHARMACY # 7567 | Full Supermarket    | 21224   | Pulaski Industrial Area | 2               | SOUTHEASTERN   | 
| 1323855962  | SAVE-ON-FOOD SUPERMARKET        | Limited Supermarket | 21225   | Brooklyn                | 10              | SOUTHERN       | 
| 1323855962  | GIANT FOOD STORE # 317          | Full Supermarket    | 21229   | Hunting Ridge           | 8               | SOUTHWESTERN   | 
| 1323855962  | STOP, SHOP & SAVE               | Limited Supermarket | 21217   | Bridgeview/Greenlawn    | 7               | WESTERN        | 
```