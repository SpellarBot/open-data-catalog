# New York State ZIP Codes-County FIPS Cross-Reference

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-zip-codes-county-fips-cross-reference) |
| Metadata | [Link](https://data.ny.gov/api/views/juva-r6g2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/juva-r6g2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/juva-r6g2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | juva-r6g2 |
| Name | New York State ZIP Codes-County FIPS Cross-Reference |
| Attribution | New York State Office of Information Technology Services |
| Category | Government & Finance |
| Tags | fips, zip, county |
| Created | 2015-04-24T16:46:41Z |
| Publication Date | 2015-05-11T15:12:52Z |

## Description

A listing of NYS counties with accompanying Federal Information Processing System (FIPS) and US Postal Service ZIP codes sourced from the NYS GIS Clearinghouse.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | county      | County Name | text          | text          |
| Yes      | series tag  | state_fips  | State FIPS  | text          | text          |
| Yes      | series tag  | county_code | County Code | text          | text          |
| Yes      | series tag  | county_fips | County FIPS | text          | text          |
| Yes      | series tag  | zip_code    | ZIP Code    | text          | text          |
| Yes      | time        | file_date   | File Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = file_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:juva-r6g2 d:2007-07-25T00:00:00.000Z t:zip_code=12046 t:county_fips=36001 t:county=Albany t:state_fips=36 t:county_code=001 m:row_number.juva-r6g2=1

series e:juva-r6g2 d:2007-07-25T00:00:00.000Z t:zip_code=12083 t:county_fips=36001 t:county=Albany t:state_fips=36 t:county_code=001 m:row_number.juva-r6g2=2

series e:juva-r6g2 d:2007-07-25T00:00:00.000Z t:zip_code=12085 t:county_fips=36001 t:county=Albany t:state_fips=36 t:county_code=001 m:row_number.juva-r6g2=3
```

## Meta Commands

```ls
metric m:row_number.juva-r6g2 p:long l:"Row Number"

entity e:juva-r6g2 l:"New York State ZIP Codes-County FIPS Cross-Reference" t:attribution="New York State Office of Information Technology Services" t:url=https://data.ny.gov/api/views/juva-r6g2

property e:juva-r6g2 t:meta.view v:id=juva-r6g2 v:category="Government & Finance" v:averageRating=0 v:name="New York State ZIP Codes-County FIPS Cross-Reference" v:attribution="New York State Office of Information Technology Services"

property e:juva-r6g2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:juva-r6g2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:juva-r6g2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county | state_fips | county_code | county_fips | zip_code | file_date           | 
| ====== | ========== | =========== | =========== | ======== | =================== | 
| Albany | 36         | 001         | 36001       | 12046    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12083    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12085    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12201    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12203    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12055    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12204    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12023    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12087    | 2007-07-25T00:00:00 | 
| Albany | 36         | 001         | 36001       | 12205    | 2007-07-25T00:00:00 | 
```