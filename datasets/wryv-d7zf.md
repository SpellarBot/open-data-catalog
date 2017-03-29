# Nearby Cook County Grocery Store Chains

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nearby-cook-county-grocery-store-chains-cc102) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/wryv-d7zf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/wryv-d7zf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/wryv-d7zf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | wryv-d7zf |
| Name | Nearby Cook County Grocery Store Chains |
| Attribution | Danny Block, Chicago State University, and Frederick Blum Neighborhood Assistance Center |
| Category | Community & Economic Development |
| Tags | food, food desert |
| Created | 2013-08-26T19:36:23Z |
| Publication Date | 2013-08-26T20:27:32Z |

## Description

A list of grocery stores which are part of a multi-store chain and are located at or within 1 mile of Chicago's city limits. In addition, this dataset contains additional information about the size and type of food offered by the grocery store. This dataset was provided to the City of Chicago by Chicago State University.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | company     | COMPANY    | text      | text        |
| Yes      | series tag  | store_type  | STORE TYPE | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | zip_code    | ZIP CODE   | text      | number      |
| Yes      | series tag  | state       | STATE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:wryv-d7zf d:2013-08-26T12:36:45.000Z t:zip_code=60068 t:company="Trader Joe's" t:state=IL t:store_type=Specialty t:city="Park Ridge" m:row_number.wryv-d7zf=1

series e:wryv-d7zf d:2013-08-26T12:36:46.000Z t:zip_code=60202 t:company="Food 4 Less" t:state=IL t:store_type=FullService t:city=Evanston m:row_number.wryv-d7zf=2

series e:wryv-d7zf d:2013-08-26T12:36:46.000Z t:zip_code=60804 t:company=Aldi t:state=IL t:store_type=Discount t:city=Cicero m:row_number.wryv-d7zf=3
```

## Meta Commands

```ls
metric m:row_number.wryv-d7zf p:long l:"Row Number"

entity e:wryv-d7zf l:"Nearby Cook County Grocery Store Chains" t:attribution="Danny Block, Chicago State University, and Frederick Blum Neighborhood Assistance Center" t:url=https://data.cityofchicago.org/api/views/wryv-d7zf

property e:wryv-d7zf t:meta.view v:id=wryv-d7zf v:category="Community & Economic Development" v:attributionLink=http://www.csu.edu/nac/ v:averageRating=0 v:name="Nearby Cook County Grocery Store Chains" v:attribution="Danny Block, Chicago State University, and Frederick Blum Neighborhood Assistance Center"

property e:wryv-d7zf t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:displayName="Tom Schenk Jr"

property e:wryv-d7zf t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| :updated_at | company      | store_type  | address                  | city         | zip_code | state | 
| =========== | ============ | =========== | ======================== | ============ | ======== | ===== | 
| 1377520605  | Trader Joe's | Specialty   | 190 N. Northwest Highway | Park Ridge   | 60068    | IL    | 
| 1377520606  | Food 4 Less  | FullService | 2400 Main St             | Evanston     | 60202    | IL    | 
| 1377520606  | Aldi         | Discount    | 4630 Cermak Rd           | Cicero       | 60804    | IL    | 
| 1377520606  | Food 4 Less  | FullService | 3039 S Cicero            | Cicero       | 60804    | IL    | 
| 1377520606  | Dominick's   | FullService | 3141 Thatcher Ave        | River Grove  | 60171    | IL    | 
| 1377520606  | Target       | Supercenter | 4120 W 95th St           | Oak Lawn     | 60453    | IL    | 
| 1377520606  | Costco       | Wholesale   | 7311 North Melvina Ave   | Niles        | 60714    | IL    | 
| 1377520606  | Sams Club    | Wholesale   | 2601 S Cicero Ave        | Cicero       | 60804    | IL    | 
| 1377520606  | Jewel-Osco   | FullService | 5667 W Touhy Ave         | Niles        | 60714    | IL    | 
| 1377520606  | Dominick's   | FullService | 7501 North Ave           | River Forest | 60305    | IL    | 
```