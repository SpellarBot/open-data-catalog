# Maintenance Yards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maintenance-yards) |
| Metadata | [Link](https://data.lacity.org/api/views/gsdn-8z5h) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/gsdn-8z5h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/gsdn-8z5h/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | gsdn-8z5h |
| Name | Maintenance Yards |
| Category | A Well Run City |
| Created | 2014-12-23T23:24:41Z |
| Publication Date | 2014-12-23T23:26:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | department        | Department        | text      | text        |
| Yes      | series tag     | name              | Name              | text      | text        |
| Yes      | series tag     | zip_code          | Zip Code          | text      | number      |
| Yes      | series tag     | department_number | Department Number | text      | number      |
| Yes      | series tag     | building_number   | Building Number   | text      | number      |
| Yes      | numeric metric | square_footage    | Square Footage    | number    | number      |
| Yes      | series tag     | facility          | Facility          | text      | text        |
| Yes      | series tag     | council_district  | Council District  | text      | number      |
| Yes      | series tag     | dept_name         | dept_name         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gsdn-8z5h d:2014-12-23T15:24:45.000Z t:facility="7TH ST CONSOLIDATED FACIL- Sanitation" t:zip_code=90023 t:department=BOS-SR t:department_number=1 t:name="South Central Refuse Collection Yard" t:council_district=14 t:building_number=37 t:dept_name=DGS m:square_footage=8100

series e:gsdn-8z5h d:2014-12-23T15:24:45.000Z t:facility="GAFFEY STREET YARD" t:zip_code=90731 t:department=BOS-SR t:department_number=21 t:name="Harbor District Collection Yard" t:council_district=15 t:building_number=32 t:dept_name=SAN m:square_footage=0

series e:gsdn-8z5h d:2014-12-23T15:24:45.000Z t:zip_code=90025 t:department=BOS-SR t:department_number=20 t:name="Western District Refuse Collection Yard" t:council_district=11 t:building_number=3 m:square_footage=116775
```

## Meta Commands

```ls
metric m:square_footage p:float l:"Square Footage" t:dataTypeName=number

entity e:gsdn-8z5h l:"Maintenance Yards" t:url=https://data.lacity.org/api/views/gsdn-8z5h

property e:gsdn-8z5h t:meta.view v:id=gsdn-8z5h v:category="A Well Run City" v:averageRating=0 v:name="Maintenance Yards"

property e:gsdn-8z5h t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gsdn-8z5h t:meta.view.owner v:id=7t2j-pb28 v:profileImageUrlMedium=/api/users/7t2j-pb28/profile_images/THUMB v:profileImageUrlLarge=/api/users/7t2j-pb28/profile_images/LARGE v:screenName="Abhi Nemani" v:profileImageUrlSmall=/api/users/7t2j-pb28/profile_images/TINY v:displayName="Abhi Nemani"

property e:gsdn-8z5h t:meta.view.tableauthor v:id=7t2j-pb28 v:profileImageUrlMedium=/api/users/7t2j-pb28/profile_images/THUMB v:profileImageUrlLarge=/api/users/7t2j-pb28/profile_images/LARGE v:screenName="Abhi Nemani" v:profileImageUrlSmall=/api/users/7t2j-pb28/profile_images/TINY v:displayName="Abhi Nemani"
```

## Top Records

```ls
| :updated_at | department | name                                             | zip_code | department_number | building_number | square_footage | facility                              | council_district | dept_name | 
| =========== | ========== | ================================================ | ======== | ================= | =============== | ============== | ===================================== | ================ | ========= | 
| 1419348285  | BOS-SR     | North Central District Yard - San Fernando Road  | 90031    | 21                | 36              |                | SAN FERNANDO ROAD FACILITY            | 1                | SAN       | 
| 1419348285  | BOS-SR     | South Central Refuse Collection Yard             | 90023    | 1                 | 37              | 8100.00        | 7TH ST CONSOLIDATED FACIL- Sanitation | 14               | DGS       | 
| 1419348285  | BOS-SR     | Harbor District Collection Yard                  | 90731    | 21                | 32              | 0.00           | GAFFEY STREET YARD                    | 15               | SAN       | 
| 1419348285  | BOS-SR     | Western District Refuse Collection Yard          | 90025    | 20                | 3               | 116775.00      |                                       | 11               |           | 
| 1419348285  | BOS-SR     | Central Los Angeles Recycle And Transfer Station | 90021    | 20                | 9               |                |                                       | 10               |           | 
| 1419348285  | BOS-SR     | Refuse Collection Center                         | 90058    | 20                | 1               | 0.00           | REFUSE COLLECTION CENTER              | 14               | SAN       | 
| 1419348285  | BOS-SR     | South Central                                    | 90021    | 20                | 2               | 0.00           | SOUTH-CENTRAL                         | 14               | SAN       | 
| 1419348285  | BOS-SR     | Lancer Project                                   | 90039    | 20                | 20              | 0.00           | LANCER PROJECT                        | 9                | SAN       | 
| 1419348285  | BOS-SR     | Toyon Canyon Park Reclamation Project            | 90035    | 20                | 13              | 2000.00        | TOYON CANYON PARK RECLAMATION PROJECT | 4                | SAN       | 
| 1419348285  | BOS-SR     | Sheldon-Arleta Landfill                          | 91352    | 20                | 17              | 3650.00        | SHELDON-ARLETA LANDFILL               | 6                | SAN       | 
```