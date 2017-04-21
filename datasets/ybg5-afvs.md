# City University of New York (CUNY) University Degrees Granted per Degree Type: Beginning 1966

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-university-of-new-york-cuny-university-degrees-granted-per-degree-type-beginning-1966) |
| Metadata | [Link](https://data.ny.gov/api/views/ybg5-afvs) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ybg5-afvs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ybg5-afvs/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ybg5-afvs |
| Name | City University of New York (CUNY) University Degrees Granted per Degree Type: Beginning 1966 |
| Attribution | City University of New York |
| Category | Education |
| Tags | higher education, degrees, associate, baccalaureate, bachelor's, master's, doctorate, professional |
| Created | 2014-01-17T16:46:33Z |
| Publication Date | 2015-12-23T17:44:42Z |

## Description

Trends in degrees granted at CUNY by degree type:1.Certificate 2. Associate 3. Baccalaureate 4. Master's 5. Advance Certificate 6. J.D. 7. Master of Philosophy 8. PhD

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | academic_year | Academic Year | text      | text        |
| Yes      | series tag     | degree_type   | Degree Type   | text      | text        |
| Yes      | series tag     | record_type   | Record Type   | text      | text        |
| Yes      | numeric metric | count         | Count         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ybg5-afvs d:2014-01-17T08:46:37.000Z t:academic_year=1966-1967 t:record_type=Degrees t:degree_type=Certificate m:count=0

series e:ybg5-afvs d:2014-01-17T08:46:37.000Z t:academic_year=1966-1967 t:record_type=Degrees t:degree_type=Associate m:count=4048

series e:ybg5-afvs d:2014-01-17T08:46:37.000Z t:academic_year=1966-1967 t:record_type=Degrees t:degree_type=Baccalaureate m:count=10549
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:ybg5-afvs l:"City University of New York (CUNY) University Degrees Granted per Degree Type: Beginning 1966" t:attribution="City University of New York" t:url=https://data.ny.gov/api/views/ybg5-afvs

property e:ybg5-afvs t:meta.view v:id=ybg5-afvs v:category=Education v:averageRating=0 v:name="City University of New York (CUNY) University Degrees Granted per Degree Type: Beginning 1966" v:attribution="City University of New York"

property e:ybg5-afvs t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ybg5-afvs t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ybg5-afvs t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | academic_year | degree_type          | record_type | count | 
| =========== | ============= | ==================== | =========== | ===== | 
| 1389948397  | 1966-1967     | Certificate          | Degrees     | 0     | 
| 1389948397  | 1966-1967     | Associate            | Degrees     | 4048  | 
| 1389948397  | 1966-1967     | Baccalaureate        | Degrees     | 10549 | 
| 1389948397  | 1966-1967     | Master's             | Degrees     | 2722  | 
| 1389948397  | 1966-1967     | Advance Certificate  | Degrees     | 161   | 
| 1389948397  | 1966-1967     | J.D.                 | Degrees     | 0     | 
| 1389948397  | 1966-1967     | Master of Philosophy | Degrees     | 0     | 
| 1389948397  | 1966-1967     | PhD                  | Degrees     | 26    | 
| 1389948397  | 1966-1967     | Total                | Degrees     | 17506 | 
| 1389948397  | 1967-1968     | Certificate          | Degrees     | 0     | 
```