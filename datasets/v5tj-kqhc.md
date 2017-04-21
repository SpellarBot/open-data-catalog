# Seattle Parks And Recreation Park Addresses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-parks-and-recreation-park-addresses-635d4) |
| Metadata | [Link](https://data.seattle.gov/api/views/v5tj-kqhc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/v5tj-kqhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/v5tj-kqhc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | v5tj-kqhc |
| Name | Seattle Parks And Recreation Park Addresses |
| Attribution | Seattle Parks and Recreation |
| Category | Parks and Recreation |
| Tags | seattle, parks, recreation, address, addresses |
| Created | 2016-03-11T17:51:33Z |
| Publication Date | 2016-03-17T23:44:35Z |

## Description

Seattle Parks and Recreation Park Addresses with X and Y coordinates

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | pmaid       | PMAID      | text      | number      |
| Yes      | series tag     | locid       | LocID      | text      | number      |
| Yes      | series tag     | name        | Name       | text      | text        |
| No       |                | address     | Address    | text      | text        |
| Yes      | series tag     | zip_code    | ZIP Code   | text      | text        |
| Yes      | numeric metric | x_coord     | X Coord    | number    | number      |
| Yes      | numeric metric | y_coord     | Y Coord    | number    | number      |
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
series e:v5tj-kqhc d:2016-03-11T09:51:36.000Z t:pmaid=281 t:zip_code=98119 t:locid=2545 t:name="12th and Howe Play Park" m:y_coord=47.636097 m:x_coord=-122.372985

series e:v5tj-kqhc d:2016-03-11T09:51:36.000Z t:pmaid=4159 t:zip_code=98144 t:locid=2387 t:name="12th Ave S Viewpoint" m:y_coord=47.577953 m:x_coord=-122.317765

series e:v5tj-kqhc d:2016-03-11T09:51:36.000Z t:pmaid=4467 t:zip_code=98122 t:locid=2382 t:name="12th Ave Square Park" m:y_coord=47.607427 m:x_coord=-122.316455
```

## Meta Commands

```ls
metric m:x_coord p:double l:"X Coord" t:dataTypeName=number

metric m:y_coord p:double l:"Y Coord" t:dataTypeName=number

entity e:v5tj-kqhc l:"Seattle Parks And Recreation Park Addresses" t:attribution="Seattle Parks and Recreation" t:url=https://data.seattle.gov/api/views/v5tj-kqhc

property e:v5tj-kqhc t:meta.view v:id=v5tj-kqhc v:category="Parks and Recreation" v:attributionLink=http://www.seattle.gov/parks v:averageRating=0 v:name="Seattle Parks And Recreation Park Addresses" v:attribution="Seattle Parks and Recreation"

property e:v5tj-kqhc t:meta.view.license v:name="Public Domain"

property e:v5tj-kqhc t:meta.view.owner v:id=3asm-yice v:profileImageUrlMedium=/api/users/3asm-yice/profile_images/THUMB v:profileImageUrlLarge=/api/users/3asm-yice/profile_images/LARGE v:screenName="Smith, Christopher" v:profileImageUrlSmall=/api/users/3asm-yice/profile_images/TINY v:displayName="Smith, Christopher"

property e:v5tj-kqhc t:meta.view.tableauthor v:id=3asm-yice v:profileImageUrlMedium=/api/users/3asm-yice/profile_images/THUMB v:profileImageUrlLarge=/api/users/3asm-yice/profile_images/LARGE v:screenName="Smith, Christopher" v:profileImageUrlSmall=/api/users/3asm-yice/profile_images/TINY v:roleName=publisher v:displayName="Smith, Christopher"
```

## Top Records

```ls
| :updated_at | pmaid   | locid | name                    | address                             | zip_code | x_coord     | y_coord   | 
| =========== | ======= | ===== | ======================= | =================================== | ======== | =========== | ========= | 
| 1457689896  | 281     | 2545  | 12th and Howe Play Park | 1200 W Howe St                      | 98119    | -122.372985 | 47.636097 | 
| 1457689896  | 4159    | 2387  | 12th Ave S Viewpoint    | 2821 12TH Ave S                     | 98144    | -122.317765 | 47.577953 | 
| 1457689896  | 4467    | 2382  | 12th Ave Square Park    | 564 12th Ave                        | 98122    | -122.316455 | 47.607427 | 
| 1457689896  | 4010    | 2546  | 14th Ave NW Boat Ramp   | 4400 14th Ave NW                    | 98107    | -122.373536 | 47.660775 | 
| 1457689896  | 296     | 296   | 3001 E Madison          | 3001 E Madison St                   | 98112    | -122.293173 | 47.625169 | 
| 1457689896  | 1000001 | 0     | 32nd Ave W Boat Launch  | 32nd Ave W                          | 98199    | -122.398685 | 47.632345 | 
| 1457689896  | 3158    | 2378  | 6th Ave NW Pocket Park  | 606 NW 76th St                      | 98117    | -122.363566 | 47.684202 | 
| 1457689896  | 4404    | 2533  | A. B. Ernst Park        | 723 N 35th St                       | 98103    | -122.348826 | 47.650087 | 
| 1457689896  | 1000002 | 0     | Adams Street Boat Ramp  | Lake Washington Blvd S & S Adams St | 98118    | -122.267178 | 47.565219 | 
| 1457689896  | 244     | 1886  | Albert Davis Park       | 12526 27th Ave NE                   | 98125    | -122.298752 | 47.72016  | 
```