# Affordable Rental Housing Developments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/affordable-rental-housing-developments-ef5c2) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/s6ha-ppgi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/s6ha-ppgi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/s6ha-ppgi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | s6ha-ppgi |
| Name | Affordable Rental Housing Developments |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | housing |
| Created | 2013-03-14T21:05:29Z |
| Publication Date | 2016-11-08T16:09:59Z |

## Description

The affordable rental housing developments listed below are supported by the City of Chicago to maintain affordability standards. For information on rents, income requirements and availability, contact each property directly. For information on other affordable rental properties in Chicago and Illinois, call (877) 428-8844, or visit www.ILHousingSearch.org.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | community_area        | Community Area Name   | text      | text        |
| Yes      | series tag     | community_area_number | Community Area Number | text      | number      |
| Yes      | series tag     | property_type         | Property Type         | text      | text        |
| Yes      | series tag     | property_name         | Property Name         | text      | text        |
| No       |                | address               | Address               | text      | text        |
| Yes      | series tag     | zip_code              | Zip Code              | text      | text        |
| Yes      | series tag     | phone_number          | Phone Number          | text      | text        |
| Yes      | series tag     | management_company    | Management Company    | text      | text        |
| Yes      | numeric metric | units                 | Units                 | number    | number      |
| No       |                | x_coordinate          | X Coordinate          | number    | number      |
| No       |                | y_coordinate          | Y Coordinate          | number    | number      |
| No       |                | latitude              | Latitude              | number    | number      |
| No       |                | longitude             | Longitude             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:s6ha-ppgi d:2016-05-11T11:34:23.000Z t:property_type=Senior t:phone_number=773-205-7862 t:zip_code=60630 t:property_name="Mayfair Commons" t:management_company="Metroplex, Inc." t:community_area="Albany Park" t:community_area_number=14 m:units=97

series e:s6ha-ppgi d:2016-05-11T11:34:23.000Z t:property_type=Senior t:phone_number=773-509-9333 t:zip_code=60618 t:property_name="Senior Suites of Ravenswood Manor" t:management_company="Senior Lifestyle Corp." t:community_area="Albany Park" t:community_area_number=14 m:units=80

series e:s6ha-ppgi d:2016-05-11T11:34:23.000Z t:property_type=Senior t:phone_number=773-463-3004 t:zip_code=60625 t:property_name="Darul Amaan Senior Living" t:management_company="East Lake Management & Development Corp." t:community_area="Albany Park" t:community_area_number=14 m:units=56
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

entity e:s6ha-ppgi l:"Affordable Rental Housing Developments" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/s6ha-ppgi

property e:s6ha-ppgi t:meta.view v:id=s6ha-ppgi v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Affordable Rental Housing Developments" v:attribution="City of Chicago"

property e:s6ha-ppgi t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:s6ha-ppgi t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | community_area | community_area_number | property_type  | property_name                              | address                | zip_code | phone_number | management_company                       | units | x_coordinate       | y_coordinate       | latitude      | longitude      | 
| =========== | ============== | ===================== | ============== | ========================================== | ====================== | ======== | ============ | ======================================== | ===== | ================== | ================== | ============= | ============== | 
| 1462966463  | Albany Park    | 14                    | Senior         | Mayfair Commons                            | 4444 W. Lawrence Ave.  | 60630    | 773-205-7862 | Metroplex, Inc.                          | 97    | 1145674.7538177613 | 1931569.979044555  | 41.9682242321 | -87.7397474866 | 
| 1462966463  | Albany Park    | 14                    | Senior         | Senior Suites of Ravenswood Manor          | 2800 W. Montrose Ave.  | 60618    | 773-509-9333 | Senior Lifestyle Corp.                   | 80    | 1156898.5139453819 | 1929148.4609726223 | 41.9613586525 | -87.6985441744 | 
| 1462966463  | Albany Park    | 14                    | Senior         | Darul Amaan Senior Living                  | 4814-58 N. Kedzie Ave. | 60625    | 773-463-3004 | East Lake Management & Development Corp. | 56    | 1154133.1245140075 | 1931889.1596844296 | 41.9689350644 | -87.7086378257 | 
| 1462966463  | Ashburn        | 70                    | Senior         | Wrightwood Senior Apartments               | 2815 W. 79th St.       | 60652    | 773-471-7777 | Ludwig and Company                       | 85    | 1158906.9337661215 | 1852040.9542699235 | 41.7497264566 | -87.6932733372 | 
| 1462966463  | Auburn Gresham | 71                    | Multifamily    | Stone Terrace                              | 8440 S. Parnell Ave.   | 60620    | 773-651-9234 | East Lake Management & Development Corp. | 56    | 1174067.0161528846 | 1848682.073813996  | 41.740186358  | -87.6378199128 | 
| 1462966463  | Auburn Gresham | 71                    | Senior HUD 202 | St. Sabina Elder Village Apartments        | 1222 W. 79th St.       | 60620    | 773-994-7850 | Catholic Charities Housing Devp.         | 80    | 1169422.9298314867 | 1852437.4683081156 | 41.7505934139 | -87.6547267546 | 
| 1462966463  | Auburn Gresham | 71                    | Senior         | Senior Suites of Auburn-Gresham            | 1050 W. 79th St.       | 60620    | 773-723-0333 | Senior Lifestyle Corp.                   | 85    | 1170460.9005370243 | 1852465.7954619504 | 41.7506486193 | -87.6509223206 | 
| 1462966463  | Auburn Gresham | 71                    | Senior HUD 202 | Naomi & Sylvester Smith Senior Living Ctr. | 8019-55 S. Halsted St. | 60620    | 773-651-6400 | HSR Property Services, LLC               | 59    | 1172404.4659361218 | 1851597.1338227245 | 41.7482223777 | -87.6438256988 | 
| 1462966463  | Auburn Gresham | 71                    | Senior         | Auburn Commons                             | 1626 W. 87th St.       | 60620    | 773-238-0850 | Urban Property Advisors, LLC             | 72    | 1166895.2399723816 | 1847057.795509487  | 41.7358851523 | -87.6641427166 | 
| 1462966463  | Austin         | 25                    | Multifamily    | Pine Central                               | 557 N. Pine Ave.       | 60644    | 773-568-1020 | NHS Redevelopment Corp.                  | 78    | 1139471.8964290908 | 1903210.8349472568 | 41.8905193977 | -87.7632486365 | 
```