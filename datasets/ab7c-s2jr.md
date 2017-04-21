# Bike Rack Locations By Area

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-rack-locations-by-area-4ce78) |
| Metadata | [Link](https://data.honolulu.gov/api/views/ab7c-s2jr) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/ab7c-s2jr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/ab7c-s2jr/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | ab7c-s2jr |
| Name | Bike Rack Locations By Area |
| Attribution | Dept of Transportation |
| Category | Transportation |
| Tags | bike, bicycles, racks |
| Created | 2012-11-22T06:43:23Z |
| Publication Date | 2012-11-22T06:46:09Z |

## Description

Bike Rack Data

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | location    | LOCATION   | text      | text        |
| Yes      | series tag  | area        | AREA       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ab7c-s2jr d:2012-11-21T22:43:25.000Z t:area=WAIKIKI t:location="Ala Moana Blvd., mauka side, in front of Doubletree Alana Waikiki Hotel" m:row_number.ab7c-s2jr=1

series e:ab7c-s2jr d:2012-11-21T22:43:25.000Z t:area=WAIKIKI t:location="Ala Moana Blvd., mauka side, in front of Dynasty Restaurant" m:row_number.ab7c-s2jr=2

series e:ab7c-s2jr d:2012-11-21T22:43:25.000Z t:area=WAIKIKI t:location="Ala Moana Blvd., mauka side, in front of Hawaiian Colony" m:row_number.ab7c-s2jr=3
```

## Meta Commands

```ls
metric m:row_number.ab7c-s2jr p:long l:"Row Number"

entity e:ab7c-s2jr l:"Bike Rack Locations By Area" t:attribution="Dept of Transportation" t:url=https://data.honolulu.gov/api/views/ab7c-s2jr

property e:ab7c-s2jr t:meta.view v:id=ab7c-s2jr v:category=Transportation v:averageRating=0 v:name="Bike Rack Locations By Area" v:attribution="Dept of Transportation"

property e:ab7c-s2jr t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:ab7c-s2jr t:meta.view.owner v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"

property e:ab7c-s2jr t:meta.view.tableauthor v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"
```

## Top Records

```ls
| :updated_at | location                                                                | area    | 
| =========== | ======================================================================= | ======= | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Doubletree Alana Waikiki Hotel | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Dynasty Restaurant             | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Hawaiian Colony                | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Inn On The Park                | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Parkside Hotel                 | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Todau Restaurant               | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, in front of Wailana Coffee Shop            | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, near Hobron, in front of ABC store         | WAIKIKI | 
| 1353537805  | Ala Moana Blvd., mauka side, near Kalakaua                              | WAIKIKI | 
| 1353537805  | Ena Rd., DH side, in front of Chiba-Ken Restaurant                      | WAIKIKI | 
```