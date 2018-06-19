# Condom Distribution Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/condom-distribution-sites-863a9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/azpf-uc4s) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/azpf-uc4s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/azpf-uc4s/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | azpf-uc4s |
| Name | Condom Distribution Sites |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | condoms |
| Created | 2011-11-23T23:43:07Z |
| Publication Date | 2013-11-25T22:36:31Z |

## Description

The Chicago Department of Public Health is distributing condoms at several locations across the City.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | venue_type  | Venue Type | text      | text        |
| Yes      | series tag  | name        | Name       | text      | text        |
| No       |             | address     | Address    | text      | text        |
| Yes      | series tag  | city_       | City       | text      | text        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | zip_code    | ZIP Code   | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:azpf-uc4s d:2013-11-25T14:34:44.000Z t:venue_type=Clinic t:zip_code=60636 t:name="Friend Family Health Center" t:state=IL t:city_=Chicago m:row_number.azpf-uc4s=1

series e:azpf-uc4s d:2013-11-25T14:34:44.000Z t:venue_type="Record Store" t:zip_code=60644 t:name="Mac's Record" t:state=IL t:city_=Chicago m:row_number.azpf-uc4s=2

series e:azpf-uc4s d:2013-11-25T14:34:44.000Z t:venue_type=CBO t:zip_code=60628 t:name="Chicago Family Health Center Roseland" t:state=IL t:city_=Chicago m:row_number.azpf-uc4s=3
```

## Meta Commands

```ls
metric m:row_number.azpf-uc4s p:long l:"Row Number"

entity e:azpf-uc4s l:"Condom Distribution Sites" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/azpf-uc4s

property e:azpf-uc4s t:meta.view v:id=azpf-uc4s v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Condom Distribution Sites" v:attribution="City of Chicago"

property e:azpf-uc4s t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:azpf-uc4s t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | venue_type       | name                                    | address             | city_   | state | zip_code | 
| =========== | ================ | ======================================= | =================== | ======= | ===== | ======== | 
| 1385390084  | Clinic           | Friend Family Health Center             | 5843 S. Western     | Chicago | IL    | 60636    | 
| 1385390084  | Record Store     | Mac's Record                            | 5425 W Madison      | Chicago | IL    | 60644    | 
| 1385390084  | CBO              | Chicago Family Health Center Roseland   | 120 W. 111th        | Chicago | IL    | 60628    | 
| 1385390084  | CBO              | Community Outreach Intervention Project | 1606 W. 63rd        | Chicago | IL    | 60636    | 
| 1385390084  | Bar/Club         | Lil' Jims                               | 3501 N. Halsted     | Chicago | IL    | 60657    | 
| 1385390084  | CBO              | Access Southwest                        | 4839 S. 47th St.    | Chicago | IL    | 60638    | 
| 1385390084  | Lingerie Company | Thin N That Lingerie                    | 7506 S. Saginaw     | Chicago | IL    | 60649    | 
| 1385390084  | CBO              | Access Cabrini                          | 3450 S. Archer Ave. | Chicago | IL    | 60608    | 
| 1385390084  | CBO              | Core Center                             | 2020 W. Harrison    | Chicago | IL    | 60612    | 
| 1385390084  | Clinic           | RoselandPlanned Parenthood of Illinois  | 11250 S Halsted     | Chicagi | IL    | 60628    | 
```