# City Of Seattle Neighborhood Matching Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-neighborhood-matching-funds) |
| Metadata | [Link](https://data.seattle.gov/api/views/pr2n-4pn6) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/pr2n-4pn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/pr2n-4pn6/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | pr2n-4pn6 |
| Name | City Of Seattle Neighborhood Matching Funds |
| Attribution | Department of Neighborhood |
| Category | Community |
| Tags | grants, matching funds, neighborhood, neighborhoods, maag, nre, nmf |
| Created | 2015-02-18T20:32:20Z |
| Publication Date | 2017-01-04T22:45:26Z |

## Description

Seattle Department Of Neighborhoods - All awarded Neighborhood Matching Funds from 1989 to present. DON

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       |                | id                         | ID                         | text      | text        |
| Yes      | series tag     | contract_number            | Contract Number            | text      | text        |
| Yes      | series tag     | program_area               | Program Area               | text      | text        |
| Yes      | time           | award_year                 | Award Year                 | number    | number      |
| Yes      | series tag     | project_title              | Project Title              | text      | text        |
| Yes      | series tag     | organization_name          | Organization Name          | text      | text        |
| Yes      | series tag     | project_description        | Project Description        | text      | text        |
| Yes      | numeric metric | awarded_amount             | Awarded Amount             | number    | number      |
| Yes      | numeric metric | pledged_match_amount       | Pledged Match Amount       | number    | number      |
| Yes      | series tag     | seattle_electoral_district | Seattle Electoral District | text      | text        |
| Yes      | series tag     | neighborhood_district      | Neighborhood District      | text      | text        |
```

## Time Field

```ls
Value = award_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:pr2n-4pn6 d:1997-01-01T00:00:00.000Z t:project_title="Orca Garden Project" t:program_area="School Beautification" t:neighborhood_district=Unknown t:contract_number=EBF9717 t:organization_name="Orca at Columbia Elementary PTSA" m:pledged_match_amount=0 m:awarded_amount=840

series e:pr2n-4pn6 d:1997-01-01T00:00:00.000Z t:project_title="Wing Luke Garden Project" t:program_area="School Beautification" t:neighborhood_district=Southwest t:contract_number=EBF9719 t:organization_name="Wing Luke Elementary PTSA" m:pledged_match_amount=0 m:awarded_amount=1000

series e:pr2n-4pn6 d:1991-01-01T00:00:00.000Z t:project_title="Traffic Circle 22nd & E Lynn" t:program_area="Small and Simple Projects Fund" t:neighborhood_district=Northeast t:contract_number=S90079 t:project_description="Constructed new traffic circle." t:organization_name="Montlake Community Club" m:pledged_match_amount=3292 m:awarded_amount=3461
```

## Meta Commands

```ls
metric m:awarded_amount p:integer l:"Awarded Amount" t:dataTypeName=number

metric m:pledged_match_amount p:integer l:"Pledged Match Amount" t:dataTypeName=number

entity e:pr2n-4pn6 l:"City Of Seattle Neighborhood Matching Funds" t:attribution="Department of Neighborhood" t:url=https://data.seattle.gov/api/views/pr2n-4pn6

property e:pr2n-4pn6 t:meta.view v:id=pr2n-4pn6 v:category=Community v:attributionLink=http://www.seattle.gov/neighborhoods/ v:averageRating=0 v:name="City Of Seattle Neighborhood Matching Funds" v:attribution="Department of Neighborhood"

property e:pr2n-4pn6 t:meta.view.license v:name="Public Domain"

property e:pr2n-4pn6 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:pr2n-4pn6 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| id   | contract_number | program_area                   | award_year | project_title                | organization_name                 | project_description                                                                                  | awarded_amount | pledged_match_amount | seattle_electoral_district | neighborhood_district | 
| ==== | =============== | ============================== | ========== | ============================ | ================================= | ==================================================================================================== | ============== | ==================== | ========================== | ===================== | 
| 957  | EBF9717         | School Beautification          | 1997       | Orca Garden Project          | Orca at Columbia Elementary PTSA  |                                                                                                      | 840            | 0                    |                            | Unknown               | 
| 959  | EBF9719         | School Beautification          | 1997       | Wing Luke Garden Project     | Wing Luke Elementary PTSA         |                                                                                                      | 1000           | 0                    |                            | Southwest             | 
| 1392 | S90079          | Small and Simple Projects Fund | 1991       | Traffic Circle 22nd & E Lynn | Montlake Community Club           | Constructed new traffic circle.                                                                      | 3461           | 3292                 |                            | Northeast             | 
| 952  | EBF9712         | School Beautification          | 1997       | Garden and Art Project       | Washington Middle School PTSA     |                                                                                                      | 1000           | 0                    |                            | Unknown               | 
| 961  | EBF9721         | School Beautification          | 1997       | Lawton Garden Project        | Lawton Elementary PTSA            |                                                                                                      | 1000           | 0                    |                            | Unknown               | 
| 519  | B9546           | Large Projects Fund            | 1994       | Webster Playground Project   | Groundswell Northwest             | To restore and improve a community playground on the grounds of the old Webster School.              | 49872          | 53579                |                            | Ballard               | 
| 1977 | S97011          | Small and Simple Projects Fund | 1997       | Urban Naturescaping Project  | Cascade Neighborhood Council      |                                                                                                      | 4837           | 4957                 |                            | Lake Union            | 
| 958  | EBF9718         | School Beautification          | 1997       | Planter Boxes                | Whitworth Elementary PTSA         |                                                                                                      | 618            | 0                    |                            | Southeast             | 
| 2063 | S98007          | Small and Simple Projects Fund | 1998       | Immaculate P-Patch           | Cherry Hill Community Association | Establish a P-Patch on the NE corner of 18th Ave. & E. Columbia Street.                              | 4911           | 8570                 |                            | Central               | 
| 900  | EBF9608         | School Beautification          | 1996       | Butterfly Garden             | Whittier Elementary PTSA          | Creation of a butterfly garden and development of a butterfly corridor between school and Baker Park | 500            | 1421                 |                            | Ballard               | 
```