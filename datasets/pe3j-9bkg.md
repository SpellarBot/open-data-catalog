# Canal System Lift Bridges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/canal-system-lift-bridges) |
| Metadata | [Link](https://data.ny.gov/api/views/pe3j-9bkg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pe3j-9bkg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pe3j-9bkg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pe3j-9bkg |
| Name | Canal System Lift Bridges |
| Attribution | New York State Canal Corporation |
| Category | Recreation |
| Tags | canal, waterway, lift bridges, erie canal, champlain canal, oswego canal, cayuga-seneca canal |
| Created | 2013-02-26T23:14:15Z |
| Publication Date | 2013-02-28T19:02:54Z |

## Description

The New York State Canal System is a 524 mile inland waterway that includes 16 lift bridges, which are operationally left in the down position to allow vehicular road traffic to pass over the canal, but then are lifted on demand to allow vessels to pass beneath. Information provided in this dataset includes the name of each lift bridge, its phone number, and specific location by mileage along the canal and geographic coordinates.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | canal_name    | Canal Name    | text      | text        |
| Yes      | numeric metric | mile          | Mile          | number    | number      |
| Yes      | series tag     | name_location | Name/Location | text      | text        |
| Yes      | series tag     | phone         | Phone         | text      | text        |
| Yes      | series tag     | notes         | Notes         | text      | text        |
| No       |                | latitude      | Latitude      | number    | number      |
| No       |                | longitude     | Longitude     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:pe3j-9bkg d:2013-02-26T15:14:16.000Z t:name_location="Main Street, Fairport*" t:phone="(585) 223-9412" t:canal_name="Erie Canal" t:notes="*Fairport has a 7' overhead clearance unlifted (toward south side of channel)" m:mile=246.67

series e:pe3j-9bkg d:2013-02-26T15:14:16.000Z t:name_location="Union Street, Spencerport" t:phone="(585) 352-5451" t:canal_name="Erie Canal" m:mile=271.28

series e:pe3j-9bkg d:2013-02-26T15:14:16.000Z t:name_location="Washington Street, Adams Basin" t:phone="(585) 352-3548" t:canal_name="Erie Canal" m:mile=274.21
```

## Meta Commands

```ls
metric m:mile p:float l:Mile d:"Mileage along the waterway (in 1/100ths of a mile)" t:dataTypeName=number

entity e:pe3j-9bkg l:"Canal System Lift Bridges" t:attribution="New York State Canal Corporation" t:url=https://data.ny.gov/api/views/pe3j-9bkg

property e:pe3j-9bkg t:meta.view v:id=pe3j-9bkg v:category=Recreation v:attributionLink=http://www.canals.ny.gov/boating/liftbridges.cgi v:averageRating=0 v:name="Canal System Lift Bridges" v:attribution="New York State Canal Corporation"

property e:pe3j-9bkg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pe3j-9bkg t:meta.view.tableauthor v:id=6kas-u9kj v:profileImageUrlMedium=/api/users/6kas-u9kj/profile_images/THUMB v:profileImageUrlLarge=/api/users/6kas-u9kj/profile_images/LARGE v:screenName="Jenson Jacob" v:profileImageUrlSmall=/api/users/6kas-u9kj/profile_images/TINY v:roleName=administrator v:displayName="Jenson Jacob"

property e:pe3j-9bkg t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | canal_name | mile   | name_location                   | phone          | notes                                                                         | latitude | longitude | 
| =========== | ========== | ====== | =============================== | ============== | ============================================================================= | ======== | ========= | 
| 1361891656  | Erie Canal | 246.67 | Main Street, Fairport*          | (585) 223-9412 | *Fairport has a 7' overhead clearance unlifted (toward south side of channel) | 43.10160 | -77.44192 | 
| 1361891656  | Erie Canal | 271.28 | Union Street, Spencerport       | (585) 352-5451 |                                                                               | 43.19335 | -77.80038 | 
| 1361891656  | Erie Canal | 274.21 | Washington Street, Adams Basin  | (585) 352-3548 |                                                                               | 43.19578 | -77.85384 | 
| 1361891656  | Erie Canal | 278.76 | Park Avenue, Brockport          | (585) 637-0460 |                                                                               | 43.21536 | -77.93537 | 
| 1361891656  | Erie Canal | 278.93 | North Main Street, Brockport    | (585) 637-4530 |                                                                               | 43.21669 | -77.93815 | 
| 1361891656  | Erie Canal | 283.48 | East Avenue, Holley             | (585) 638-6456 |                                                                               | 43.22860 | -78.02166 | 
| 1361891656  | Erie Canal | 286.58 | Hulberton Road, Hulberton       | (585) 638-8183 |                                                                               | 43.25438 | -78.06624 | 
| 1361891656  | Erie Canal | 292.98 | Ingersoll Street, Albion        | (585) 589-4107 |                                                                               | 43.24853 | -78.19042 | 
| 1361891656  | Erie Canal | 293.15 | North Main Street, Albion       | (585) 589-6255 |                                                                               | 43.24907 | -78.19367 | 
| 1361891656  | Erie Canal | 296.41 | Eagle Harbor Road, Eagle Harbor | (585) 589-0628 |                                                                               | 43.25186 | -78.25314 | 
```