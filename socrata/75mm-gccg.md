# DCA Grant Awards by Grant Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dca-grant-awards-by-grant-type-14379) |
| Metadata | [Link](https://data.lacity.org/api/views/75mm-gccg) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/75mm-gccg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/75mm-gccg/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 75mm-gccg |
| Name | DCA Grant Awards by Grant Type |
| Attribution | City of Los Angeles, Department of Cultural Affairs |
| Category | A Livable and Sustainable City |
| Tags | dca, grants, grant-type, non-profit, organizations, individual artists |
| Created | 2014-10-02T03:11:57Z |
| Publication Date | 2014-10-02T03:25:49Z |

## Description

Providing grant support to LA’s rich and diverse arts and cultural organizations and individual artists is the core service provided by the Department of Cultural Affairs. The budget of the Grant Program has fluctuated between $2.1 and $3.3 million dollars per year, approx. 10% of the department's annual budget. The categories of grants include: Artists-In Residence (AIR), Cultural Engagement International (CEI), City of Los Angeles Fellowships (COLA) Individual Artist Fellowships, Community Advancement, and Organizational/Festival grants.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                              | Data Type | Render Type |
| ======== | ============== | ======================================= | ================================= | ========= | =========== |
| No       | time           | :updated_at                             | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | number_of_grantees_by_type              | Total Number of Grantees (FY2013) | text      | number      |
| Yes      | numeric metric | total_number_of_grantees_by_type_fy2014 | Total Number of Grantees (FY2014) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:75mm-gccg d:2014-10-01T20:22:19.000Z t:number_of_grantees_by_type=273 m:total_number_of_grantees_by_type_fy2014=257
```

## Meta Commands

```ls
metric m:total_number_of_grantees_by_type_fy2014 p:integer l:"Total Number of Grantees (FY2014)" d:"Providing grant support to LA’s rich and diverse arts and cultural organizations and individual artists is the core service provided by the Department of Cultural Affairs. The budget of the Grant Program has fluctuated between $2.1 and $3.3 million dollars per year, approx. 10% of the department's annual budget. The categories of grants include: Artists-In Residence (AIR), Cultural Engagement International (CEI), City of Los Angeles Fellowships (COLA) Individual Artist Fellowships, Community Advancement, and Organizational/Festival grants." t:dataTypeName=number

entity e:75mm-gccg l:"DCA Grant Awards by Grant Type" t:attribution="City of Los Angeles, Department of Cultural Affairs" t:url=https://data.lacity.org/api/views/75mm-gccg

property e:75mm-gccg t:meta.view d:2017-09-25T07:28:46.189Z v:averageRating=0 v:name="DCA Grant Awards by Grant Type" v:attribution="City of Los Angeles, Department of Cultural Affairs" v:id=75mm-gccg v:category="A Livable and Sustainable City"

property e:75mm-gccg t:meta.view.license d:2017-09-25T07:28:46.189Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:75mm-gccg t:meta.view.owner d:2017-09-25T07:28:46.189Z v:displayName="Cultural Affairs OpenData" v:profileImageUrlLarge=/api/users/nze8-qr9f/profile_images/LARGE v:profileImageUrlSmall=/api/users/nze8-qr9f/profile_images/TINY v:id=nze8-qr9f v:screenName="Cultural Affairs OpenData" v:profileImageUrlMedium=/api/users/nze8-qr9f/profile_images/THUMB

property e:75mm-gccg t:meta.view.tableauthor d:2017-09-25T07:28:46.189Z v:displayName="Cultural Affairs OpenData" v:profileImageUrlLarge=/api/users/nze8-qr9f/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/nze8-qr9f/profile_images/TINY v:id=nze8-qr9f v:screenName="Cultural Affairs OpenData" v:profileImageUrlMedium=/api/users/nze8-qr9f/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | number_of_grantees_by_type | total_number_of_grantees_by_type_fy2014 | 
| =========== | ========================== | ======================================= | 
| 1412194939  | 273                        | 257                                     | 
```