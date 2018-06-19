# Retail Food Stores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/retail-food-stores) |
| Metadata | [Link](https://data.ny.gov/api/views/9a8c-vfzj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9a8c-vfzj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9a8c-vfzj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9a8c-vfzj |
| Name | Retail Food Stores |
| Attribution | New York State Department of Agriculture and Markets |
| Category | Economic Development |
| Tags | retail food store, food safety, license |
| Created | 2013-02-26T14:49:59Z |
| Publication Date | 2016-10-24T16:18:01Z |

## Description

A listing of all retail food stores which are licensed by the Department of Agriculture and Markets.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name               | Data Type | Render Type |
| ======== | ============== | ============== | ================== | ========= | =========== |
| No       | time           | :updated_at    | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | county         | County             | text      | text        |
| Yes      | series tag     | license_number | License Number     | text      | text        |
| Yes      | series tag     | operation_type | Operation Type     | text      | text        |
| Yes      | series tag     | estab_type     | Establishment Type | text      | text        |
| Yes      | series tag     | entity_name    | Entity Name        | text      | text        |
| Yes      | series tag     | dba_name       | DBA Name           | text      | text        |
| Yes      | series tag     | street_number  | Street Number      | text      | text        |
| Yes      | series tag     | street_name    | Street Name        | text      | text        |
| No       |                | address_line_2 | Address Line 2     | text      | text        |
| No       |                | address_line_3 | Address Line 3     | text      | text        |
| Yes      | series tag     | city           | City               | text      | text        |
| Yes      | series tag     | state          | State              | text      | text        |
| Yes      | series tag     | zip_code       | Zip Code           | text      | text        |
| Yes      | numeric metric | square_footage | Square Footage     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_2,address_line_3
```

## Data Commands

```ls
series e:9a8c-vfzj d:2016-10-21T01:45:19.000Z t:estab_type=A t:entity_name="DOLLAR FLOW INC" t:zip_code=11215 t:county=Kings t:license_number=617635 t:street_name="PROSPECT PARK W" t:state=NY t:street_number=260 t:operation_type=Store t:dba_name="99 CENT RUSH" t:city=BROOKLYN m:square_footage=3000

series e:9a8c-vfzj d:2016-10-21T01:45:19.000Z t:estab_type=JAC t:entity_name="SLOPE FOODS INC" t:zip_code=11217 t:county=Kings t:license_number=619122 t:street_name="5TH AVE" t:state=NY t:street_number=61 t:operation_type=Store t:dba_name="SLOPE FOODS" t:city=BROOKLYN m:square_footage=1200

series e:9a8c-vfzj d:2016-10-21T01:45:19.000Z t:estab_type=JAC t:entity_name="WIESNERS FOOD CENTER INC" t:zip_code=11204 t:county=Kings t:license_number=619765 t:street_name="18TH AVE" t:state=NY t:street_number=5918 t:operation_type=Store t:dba_name="WIESNERS SUPERMARKET" t:city=BROOKLYN m:square_footage=2000
```

## Meta Commands

```ls
metric m:square_footage p:integer l:"Square Footage" d:"The square footage of the entire physical location of the licensed entity" t:dataTypeName=number

entity e:9a8c-vfzj l:"Retail Food Stores" t:attribution="New York State Department of Agriculture and Markets" t:url=https://data.ny.gov/api/views/9a8c-vfzj

property e:9a8c-vfzj t:meta.view v:id=9a8c-vfzj v:category="Economic Development" v:attributionLink=http://www.agriculture.ny.gov/FS/FSHome.html v:averageRating=0 v:name="Retail Food Stores" v:attribution="New York State Department of Agriculture and Markets"

property e:9a8c-vfzj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9a8c-vfzj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:9a8c-vfzj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | county | license_number | operation_type | estab_type | entity_name              | dba_name                | street_number | street_name        | address_line_2 | address_line_3 | city     | state | zip_code | square_footage | 
| =========== | ====== | ============== | ============== | ========== | ======================== | ======================= | ============= | ================== | ============== | ============== | ======== | ===== | ======== | ============== | 
| 1477014319  | Kings  | 617635         | Store          | A          | DOLLAR FLOW INC          | 99 CENT RUSH            | 260           | PROSPECT PARK W    |                |                | BROOKLYN | NY    | 11215    | 3000           | 
| 1477014319  | Kings  | 619122         | Store          | JAC        | SLOPE FOODS INC          | SLOPE FOODS             | 61            | 5TH AVE            |                |                | BROOKLYN | NY    | 11217    | 1200           | 
| 1477014319  | Kings  | 619765         | Store          | JAC        | WIESNERS FOOD CENTER INC | WIESNERS SUPERMARKET    | 5918          | 18TH AVE           |                |                | BROOKLYN | NY    | 11204    | 2000           | 
| 1477014319  | Kings  | 617316         | Store          | JAC        | GOBWA EXOTIC IMPORTS INC | GOBWA EXOTIC IMPORTS    | 1127          | NOSTRAND AVE       |                |                | BROOKLYN | NY    | 11225    | 2000           | 
| 1477014319  | Kings  | 612560         | Store          | JAC        | SURIEL JOSE R            | LAST STOP GROCERY STORE | 5316          | 3RD AVE            |                |                | BROOKLYN | NY    | 11220    | 1500           | 
| 1477014319  | Kings  | 619158         | Store          | JABC       | BRIGHTON BAZAAR INC      | BRIGHTON BAZAAR         | 1007          | BRIGHTON BEACH AVE |                |                | BROOKLYN | NY    | 11235    | 4500           | 
| 1477014319  | Kings  | 614255         | Store          | A          | MIAH MOHAMMAD S          | 99 CENTS DISCOUNT STORE | 1596-98       | NOSTRAND AVE       |                |                | BROOKLYN | NY    | 11226    | 1800           | 
| 1477014319  | Kings  | 611328         | Store          | JAC        | YI KYE MYONG             | LEE SUPERMARKET         | 9004          | AVE A              |                |                | BROOKLYN | NY    | 11236    | 1500           | 
| 1477014319  | Kings  | 618521         | Store          | JAC        | CHURCH AVE FOOD CORP     | CHURCH AVE FOOD         | 111           | CHURCH AVE         |                |                | BROOKLYN | NY    | 11218    | 1500           | 
| 1477014319  | Kings  | 611112         | Store          | JACH       | F&R GOLDFISH CORP        | F&R GOLDFISH            | 2749          | OCEAN AVE          |                |                | BROOKLYN | NY    | 11229    | 2000           | 
```