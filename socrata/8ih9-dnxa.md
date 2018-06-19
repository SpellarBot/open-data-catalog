# Austin Water - Dillo Dirt Vendors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-dillo-dirt-vendors) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8ih9-dnxa) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8ih9-dnxa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8ih9-dnxa/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8ih9-dnxa |
| Name | Austin Water - Dillo Dirt Vendors |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, wastewater, dillo dirt |
| Created | 2015-08-14T20:37:17Z |
| Publication Date | 2015-08-14T20:40:02Z |

## Description

List of companies that have registered with Austin Water to purchase wholesale Dillo Dirt from the utility and offer retail sales of Dillo Dirt to the public.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | NAME       | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
| Yes      | series tag  | location    | LOCATION   | text      | text        |
| Yes      | series tag  | location_1  | Location 1 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8ih9-dnxa d:2015-08-14T13:37:20.000Z t:phone="(512) 378-3645" t:location="C AUSTIN" t:name="ABC ENVIRONMENTAL" m:row_number.8ih9-dnxa=1

series e:8ih9-dnxa d:2015-08-14T13:37:20.000Z t:phone="(512) 927-7091" t:location="E AUSTIN" t:name="ADVANCED ORGANIC MATERIALS" m:row_number.8ih9-dnxa=2

series e:8ih9-dnxa d:2015-08-14T13:37:20.000Z t:phone="(512) 845-9765" t:location="C AUSTIN" t:name="AGGREGATE & GRASS PRODUCTS" m:row_number.8ih9-dnxa=3
```

## Meta Commands

```ls
metric m:row_number.8ih9-dnxa p:long l:"Row Number"

entity e:8ih9-dnxa l:"Austin Water - Dillo Dirt Vendors" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/8ih9-dnxa

property e:8ih9-dnxa t:meta.view v:id=8ih9-dnxa v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Dillo Dirt Vendors" v:attribution="Austin Water"

property e:8ih9-dnxa t:meta.view.license v:name="Public Domain"

property e:8ih9-dnxa t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:8ih9-dnxa t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | name                         | phone          | location   | location_1 | 
| =========== | ============================ | ============== | ========== | ========== | 
| 1439559440  | ABC ENVIRONMENTAL            | (512) 378-3645 | C AUSTIN   |            | 
| 1439559440  | ADVANCED ORGANIC MATERIALS   | (512) 927-7091 | E AUSTIN   |            | 
| 1439559440  | AGGREGATE & GRASS PRODUCTS   | (512) 845-9765 | C AUSTIN   |            | 
| 1439559440  | AMAZING SCAPES               | (512) 231-9695 | SW AUSTIN  |            | 
| 1439559440  | AUSTIN ENGINEERING CO., INC. | (512) 327-1464 | C AUSTIN   |            | 
| 1439559440  | AUSTIN GRASS AND SOILS       |                | NW AUSTIN  |            | 
| 1439559440  | AUSTIN LANDSCAPE SUPPLIES    | (512) 930-2311 | GEORGETOWN |            | 
| 1439559440  | AUSTIN OUTERSCAPES *         | (512) 244-1222 | C AUSTIN   |            | 
| 1439559440  | AUSTIN RECLAIMED MATERIALS   | (512) 928-4852 | C AUSTIN   |            | 
| 1439559440  | AUSTIN WOOD RECYCLING        | (512) 259-7430 | CEDAR PARK |            | 
```