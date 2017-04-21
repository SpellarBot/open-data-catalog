# Maryland Real Property Assessments: Fields Reference

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-real-property-assessments-fields-reference) |
| Metadata | [Link](https://data.maryland.gov/api/views/w8th-47fz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/w8th-47fz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/w8th-47fz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | w8th-47fz |
| Name | Maryland Real Property Assessments: Fields Reference |
| Attribution | Department of Information Technology |
| Category | Business and Economy |
| Tags | property, properties, real property, sdat, state department of assessments and taxation, mdp, maryland department of planning, tax, assessments, value, housing, house, business, property tax, econ... |
| Created | 2015-11-24T22:21:11Z |
| Publication Date | 2015-12-11T18:40:14Z |

## Description

This dataset is a supplement to the statewide dataset of Real Property Assessments, at https://data.maryland.gov/view/sjn4-j6z3, which shows all properties in the state and assessment data from SDAT and MDP.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | numeric metric | field_order       | Field Order       | number    | number      |
| Yes      | series tag     | field_name        | Field Name        | text      | text        |
| Yes      | series tag     | data_type         | Data Type         | text      | text        |
| Yes      | series tag     | mdp_field_name    | MDP Field Name    | text      | text        |
| Yes      | series tag     | sdat_field_number | SDAT Field Number | text      | number      |
| Yes      | series tag     | api_field_name    | API Field Name    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w8th-47fz d:2015-11-24T14:21:24.000Z t:api_field_name=jurisdiction_code_mdp_field_jurscode t:field_name="Jurisdiction Code (MDP Field: JURSCODE)" t:mdp_field_name=JURSCODE t:data_type=text m:field_order=1

series e:w8th-47fz d:2015-11-24T14:21:24.000Z t:api_field_name=county_name_mdp_field_cntyname t:field_name="County Name (MDP Field: CNTYNAME)" t:mdp_field_name=CNTYNAME t:data_type=text m:field_order=2

series e:w8th-47fz d:2015-11-24T14:21:24.000Z t:api_field_name=account_id_mdp_field_acctid t:field_name="Account ID (MDP Field: ACCTID)" t:mdp_field_name=ACCTID t:data_type=text m:field_order=3
```

## Meta Commands

```ls
metric m:field_order p:integer l:"Field Order" d:"This is the order in which fields (columns) are shown in the Real Property dataset." t:dataTypeName=number

entity e:w8th-47fz l:"Maryland Real Property Assessments: Fields Reference" t:attribution="Department of Information Technology" t:url=https://data.maryland.gov/api/views/w8th-47fz

property e:w8th-47fz t:meta.view v:id=w8th-47fz v:category="Business and Economy" v:attributionLink=https://data.maryland.gov/Business-and-Economy/Maryland-Real-Property-Assessments-Hidden-Property/ed4q-f8tm v:averageRating=0 v:name="Maryland Real Property Assessments: Fields Reference" v:attribution="Department of Information Technology"

property e:w8th-47fz t:meta.view.license v:name="Public Domain"

property e:w8th-47fz t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:w8th-47fz t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | field_order | field_name                                             | data_type | mdp_field_name | sdat_field_number | api_field_name                                      | 
| =========== | =========== | ====================================================== | ========= | ============== | ================= | =================================================== | 
| 1448374884  | 1           | Jurisdiction Code (MDP Field: JURSCODE)                | text      | JURSCODE       |                   | jurisdiction_code_mdp_field_jurscode                | 
| 1448374884  | 2           | County Name (MDP Field: CNTYNAME)                      | text      | CNTYNAME       |                   | county_name_mdp_field_cntyname                      | 
| 1448374884  | 3           | Account ID (MDP Field: ACCTID)                         | text      | ACCTID         |                   | account_id_mdp_field_acctid                         | 
| 1448374884  | 4           | Real Property Search Link                              | url       |                |                   | real_property_search_link                           | 
| 1448374884  | 5           | FINDER Online Link                                     | url       |                |                   | finder_online_link                                  | 
| 1448374884  | 6           | Search Google Maps for this Location                   | url       |                |                   | search_google_maps_for_this_location                | 
| 1448374884  | 7           | MDP Longitude (MDP Field: DIGXCORD converted to WGS84) | number    | DIGXCORD       |                   | mdp_longitude_mdp_field_digxcord_converted_to_wgs84 | 
| 1448374884  | 8           | MDP Latitude (MDP Field: DIGYCORD converted to WGS84)  | number    | DIGYCORD       |                   | mdp_latitude_mdp_field_digycord_converted_to_wgs84  | 
| 1448374884  | 9           | Mappable Latitude and Longitude                        | location  |                |                   | mappable_latitude_and_longitude                     | 
| 1448374884  | 10          | RECORD KEY: County Code (SDAT Field #1)                | text      |                | 1                 | record_key_county_code_sdat_field_1                 | 
```