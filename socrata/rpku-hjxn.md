# START-UP NY Tax-Free Area Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/start-up-ny-tax-free-area-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/rpku-hjxn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rpku-hjxn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rpku-hjxn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rpku-hjxn |
| Name | START-UP NY Tax-Free Area Locations |
| Attribution | NYS Empire State Development (ESD) |
| Category | Economic Development |
| Tags | start-upny, tfa, tax-free area |
| Created | 2015-06-15T16:40:26Z |
| Publication Date | 2016-11-04T21:23:34Z |

## Description

Empire State Development (ESD) produces an annual report with a cumulative list of College and University Sponsors approved in the START-UP NY Program.  The dataset displays the name of the Sponsor, the street address, city and county of the tax-free areas (TFA) designated by that college or university, square footage of each building space and acreage of each parcel of vacant land, the name of buildings designated and the START-UPNY website of the college.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name           | Data Type | Render Type |
| ======== | ============== | ============= | ============== | ========= | =========== |
| No       | time           | :updated_at   | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | sponsor       | Sponsor        | text      | text        |
| Yes      | series tag     | streetaddress | Street Address | text      | text        |
| Yes      | series tag     | city          | City           | text      | text        |
| Yes      | series tag     | county        | County         | text      | text        |
| Yes      | numeric metric | acres         | Acres          | number    | number      |
| Yes      | series tag     | building      | Building       | text      | text        |
| Yes      | numeric metric | sqft          | Square Footage | number    | number      |
| Yes      | series tag     | website       | Website        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rpku-hjxn d:2016-11-04T21:23:01.000Z t:streetaddress="640 Bay Road" t:website=http://startup.ny.gov/map-school/adirondack-community-college t:county=Warren t:sponsor="Adirondack Community College" t:city=Queensbury m:acres=16.5

series e:rpku-hjxn d:2016-11-04T21:23:01.000Z t:streetaddress="640 Bay Road" t:website=http://startup.ny.gov/map-school/adirondack-community-college t:county=Warren t:sponsor="Adirondack Community College" t:city=Queensbury m:acres=16.8

series e:rpku-hjxn d:2016-11-04T21:23:01.000Z t:streetaddress="640 Bay Road" t:website=http://startup.ny.gov/map-school/adirondack-community-college t:county=Warren t:sponsor="Adirondack Community College" t:city=Queensbury m:acres=12.38
```

## Meta Commands

```ls
metric m:acres p:float l:Acres d:"Amount of acres of land designated as a tax-free area." t:dataTypeName=number

metric m:sqft p:integer l:"Square Footage" d:"Square footage of the designated building space in the tax-free area. Blank if tax-free area is acreage." t:dataTypeName=number

entity e:rpku-hjxn l:"START-UP NY Tax-Free Area Locations" t:attribution="NYS Empire State Development (ESD)" t:url=https://data.ny.gov/api/views/rpku-hjxn

property e:rpku-hjxn t:meta.view v:id=rpku-hjxn v:category="Economic Development" v:attributionLink=http://esd.ny.gov/index.html v:averageRating=0 v:name="START-UP NY Tax-Free Area Locations" v:attribution="NYS Empire State Development (ESD)"

property e:rpku-hjxn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rpku-hjxn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rpku-hjxn t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | sponsor                      | streetaddress         | city       | county   | acres | building    | sqft   | website                                                               | 
| =========== | ============================ | ===================== | ========== | ======== | ===== | =========== | ====== | ===================================================================== | 
| 1478294581  | Adirondack Community College | 640 Bay Road          | Queensbury | Warren   | 16.5  |             |        | [http://startup.ny.gov/map-school/adirondack-community-college, null] | 
| 1478294581  | Adirondack Community College | 640 Bay Road          | Queensbury | Warren   | 16.8  |             |        | [http://startup.ny.gov/map-school/adirondack-community-college, null] | 
| 1478294581  | Adirondack Community College | 640 Bay Road          | Queensbury | Warren   | 12.38 |             |        | [http://startup.ny.gov/map-school/adirondack-community-college, null] | 
| 1478294581  | Albany Medical College       | 43 New Scotand Ave    | Albany     | Albany   |       | ME Building | 950    | [http://startup.ny.gov/map-school/albany-medical-college, null]       | 
| 1478294581  | Albany Medical College       | 43 New Scotand Ave    | Albany     | Albany   |       | ME Building | 1050   | [http://startup.ny.gov/map-school/albany-medical-college, null]       | 
| 1478294581  | Albany Medical College       | 43 New Scotand Ave    | Albany     | Albany   |       | S Building  | 7859   | [http://startup.ny.gov/map-school/albany-medical-college, null]       | 
| 1478294581  | Alfred State                 | 1 Horton St           | Hornell    | Steuben  |       |             | 133000 | [http://startup.ny.gov/map-school/alfred-state-college, null]         | 
| 1478294581  | Alfred State                 | 2530 River Road       | Wellsville | Allegany | 7.86  |             |        | [http://startup.ny.gov/map-school/alfred-state-college, null]         | 
| 1478294581  | Alfred State                 | 6150 Sugar Hill Drive | Alfred     | Allegany |       |             | 6000   | [http://startup.ny.gov/map-school/alfred-state-college, null]         | 
| 1478294581  | Alfred State                 | 18 N Main St          | Hornell    | Steuben  |       |             | 34396  | [http://startup.ny.gov/map-school/alfred-state-college, null]         | 
```