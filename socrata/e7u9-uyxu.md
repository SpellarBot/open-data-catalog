# Adult Residential Care Home LISTING

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-residential-care-home-listing-90b36) |
| Metadata | [Link](https://data.hawaii.gov/api/views/e7u9-uyxu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/e7u9-uyxu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/e7u9-uyxu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | e7u9-uyxu |
| Name | Adult Residential Care Home LISTING |
| Attribution | DOH |
| Category | Health |
| Tags | arch, listing |
| Created | 2012-08-01T01:11:50Z |
| Publication Date | 2012-08-01T01:43:18Z |

## Description

DOH Adult Residential Care Home Facilities Listing

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | name                | NAME                | text      | text        |
| Yes      | series tag  | house_no            | HOUSE NO            | text      | text        |
| Yes      | series tag  | street              | STREET              | text      | text        |
| Yes      | series tag  | city_state_zip_code | CITY/STATE/ZIP CODE | text      | text        |
| Yes      | series tag  | island              | ISLAND              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e7u9-uyxu d:2012-07-31T18:11:51.000Z t:city_state_zip_code="Total Maui" t:island=10 m:row_number.e7u9-uyxu=1

series e:e7u9-uyxu d:2012-07-31T18:11:51.000Z t:city_state_zip_code="Total Molokai" t:island=3 m:row_number.e7u9-uyxu=2

series e:e7u9-uyxu d:2012-07-31T18:11:51.000Z t:city_state_zip_code="GRAND TOTAL" t:island=497 m:row_number.e7u9-uyxu=3
```

## Meta Commands

```ls
metric m:row_number.e7u9-uyxu p:long l:"Row Number"

entity e:e7u9-uyxu l:"Adult Residential Care Home LISTING" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/e7u9-uyxu

property e:e7u9-uyxu t:meta.view v:id=e7u9-uyxu v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Adult Residential Care Home LISTING" v:attribution=DOH

property e:e7u9-uyxu t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:e7u9-uyxu t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:e7u9-uyxu t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | name             | house_no | street        | city_state_zip_code | island | 
| =========== | ================ | ======== | ============= | =================== | ====== | 
| 1343758311  |                  |          |               | Total Maui          | 10     | 
| 1343758311  |                  |          |               | Total Molokai       | 3      | 
| 1343758311  |                  |          |               | GRAND TOTAL         | 497    | 
| 1343758312  |                  |          |               |                     |        | 
| 1343758311  |                  |          |               | Total Oahu          | 420    | 
| 1343758315  | DE VERA, LORETTA | 94-865   | Mokuahi St.   | Waipahu, HI 96797   | Oahu   | 
| 1343758315  | ANDAYA'S         | 94-029   | Poailani Cir. | Waipahu, HI 96797   | Oahu   | 
| 1343758315  | ISLAND LIVING    | 92-1269  | Umena St.     | Kapolei, HI 96707   | Oahu   | 
| 1343758315  | HALE KUPUNA      | 1783     | Piikea St.    | Honolulu, HI 96818  | Oahu   | 
| 1343758315  | ERLINDA'S        | 2020     | Uhu St.       | Honolulu, HI 96819  | Oahu   | 
```