# Department of Recreation and Parks' Facility and Park Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-recreation-and-parks-facility-and-park-information-e7cff) |
| Metadata | [Link](https://data.lacity.org/api/views/ax8j-dhzm) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ax8j-dhzm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ax8j-dhzm/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ax8j-dhzm |
| Name | Department of Recreation and Parks' Facility and Park Information |
| Attribution | Department of Recreation and Parks |
| Category | A Livable and Sustainable City |
| Tags | department of recreation and parks, facility, park, beaches, camps, dog parks, equestrian centers, gardens, golf courses, lakes, museums, public computer centers, recreation centers, rental facili... |
| Created | 2013-12-03T17:19:45Z |
| Publication Date | 2014-05-22T21:08:38Z |

## Description

The Department of Recreation and Parks' Facility and Park Information dataset provide information such as facilities and parks' addresses, contact phone numbers, websites, and mapping info by categories: beaches, camps, dog parks, equestrian centers, gardens, golf courses, lakes, museums, public computer centers, recreation centers, rental facilities, senior centers, skate parks, swimming pools, tennis courts, and theatres; and amenities: baseball/softball fields, basketball courts, hiking trails, outdoor fitness equipment, swimming pools with diving boards and universally accessible playgrounds.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | locationtype           | LocationType           | text      | text        |
| Yes      | series tag     | location_name          | Location Name          | text      | text        |
| Yes      | series tag     | stnumber               | StNumber               | text      | number      |
| Yes      | series tag     | stnumberfraction       | StNumberFraction       | text      | text        |
| Yes      | series tag     | stdirection            | StDirection            | text      | text        |
| Yes      | series tag     | stname                 | StName                 | text      | text        |
| Yes      | series tag     | stsuffix               | StSuffix               | text      | text        |
| Yes      | series tag     | stsuffixdirection      | StSuffixDirection      | text      | text        |
| No       |                | addresstype            | AddressType            | text      | text        |
| No       |                | addresstypevalue       | AddressTypeValue       | number    | text        |
| Yes      | series tag     | crossstdirection       | CrossStDirection       | text      | text        |
| Yes      | series tag     | crossstname            | CrossStName            | text      | text        |
| Yes      | series tag     | crossstsuffix          | CrossStSuffix          | text      | text        |
| Yes      | series tag     | crossstsuffixdirection | CrossStSuffixDirection | text      | text        |
| Yes      | series tag     | state                  | State                  | text      | text        |
| Yes      | series tag     | zip                    | Zip                    | text      | number      |
| Yes      | series tag     | website                | Website                | text      | text        |
| Yes      | series tag     | phone                  | Phone                  | text      | text        |
| Yes      | series tag     | councildistrict        | CouncilDistrict        | text      | number      |
| Yes      | numeric metric | geolat                 | GeoLat                 | number    | number      |
| Yes      | numeric metric | geolong                | GeoLong                | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = addresstype,addresstypevalue
```

## Data Commands

```ls
series e:ax8j-dhzm d:2015-06-18T10:49:28.000Z t:zip=91605 t:phone="(818) 506-7456" t:location_name="Bellaire Avenue Park" t:stdirection=N t:councildistrict=2 t:state=CA t:locationtype=Parks t:stname=Bellaire t:stsuffix=Ave t:stnumber=7960 m:geolong=-118.412666 m:geolat=34.21561

series e:ax8j-dhzm d:2015-06-18T10:49:28.000Z t:zip=90027 t:location_name="Sunnynook River Park" t:councildistrict=4 t:state=CA t:locationtype=Parks t:stname=Riverside t:stsuffix=Dr t:stnumber=3201 m:geolong=-118.268482 m:geolat=34.113439

series e:ax8j-dhzm d:2015-06-18T10:49:28.000Z t:zip=90024 t:phone="(310) 276-1604" t:location_name="Holmby Park" t:website=http://www.golf.lacity.org/cdp_holmby.htm t:councildistrict=5 t:state=CA t:locationtype=Parks t:stname="Club View" t:stsuffix=Dr t:stnumber=601 m:geolong=-118.4293956 m:geolat=34.07294331
```

## Meta Commands

```ls
metric m:geolat p:double l:GeoLat t:dataTypeName=number

metric m:geolong p:double l:GeoLong t:dataTypeName=number

entity e:ax8j-dhzm l:"Department of Recreation and Parks' Facility and Park Information" t:attribution="Department of Recreation and Parks" t:url=https://data.lacity.org/api/views/ax8j-dhzm

property e:ax8j-dhzm t:meta.view v:id=ax8j-dhzm v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Department of Recreation and Parks' Facility and Park Information" v:attribution="Department of Recreation and Parks"

property e:ax8j-dhzm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ax8j-dhzm t:meta.view.owner v:id=8dpa-rsea v:profileImageUrlMedium=/api/users/8dpa-rsea/profile_images/THUMB v:profileImageUrlLarge=/api/users/8dpa-rsea/profile_images/LARGE v:screenName="Recreation and Parks OpenData" v:profileImageUrlSmall=/api/users/8dpa-rsea/profile_images/TINY v:displayName="Recreation and Parks OpenData"

property e:ax8j-dhzm t:meta.view.tableauthor v:id=8dpa-rsea v:profileImageUrlMedium=/api/users/8dpa-rsea/profile_images/THUMB v:profileImageUrlLarge=/api/users/8dpa-rsea/profile_images/LARGE v:screenName="Recreation and Parks OpenData" v:profileImageUrlSmall=/api/users/8dpa-rsea/profile_images/TINY v:roleName=publisher v:displayName="Recreation and Parks OpenData"
```

## Top Records

```ls
| :updated_at | locationtype            | location_name                                     | stnumber | stnumberfraction | stdirection | stname      | stsuffix | stsuffixdirection | addresstype | addresstypevalue | crossstdirection | crossstname | crossstsuffix | crossstsuffixdirection | state | zip   | website                                                            | phone          | councildistrict | geolat      | geolong      | 
| =========== | ======================= | ================================================= | ======== | ================ | =========== | =========== | ======== | ================= | =========== | ================ | ================ | =========== | ============= | ====================== | ===== | ===== | ================================================================== | ============== | =============== | =========== | ============ | 
| 1434624568  | Parks                   | Bellaire Avenue Park                              | 7960     |                  | N           | Bellaire    | Ave      |                   |             |                  |                  |             |               |                        | CA    | 91605 |                                                                    | (818) 506-7456 | 2               | 34.21561    | -118.412666  | 
| 1434624568  | Parks                   | Sunnynook River Park                              | 3201     |                  |             | Riverside   | Dr       |                   |             |                  |                  |             |               |                        | CA    | 90027 |                                                                    |                | 4               | 34.113439   | -118.268482  | 
| 1434624568  | Parks                   | Holmby Park                                       | 601      |                  |             | Club View   | Dr       |                   |             |                  |                  |             |               |                        | CA    | 90024 | http://www.golf.lacity.org/cdp_holmby.htm                          | (310) 276-1604 | 5               | 34.07294331 | -118.4293956 | 
| 1434624568  | Parks                   | South Victoria Ave Park                           | 6537     |                  | S           | Victoria    | Ave      |                   |             |                  |                  |             |               |                        | CA    | 90043 |                                                                    | (310) 548-7675 | 8               | 33.979427   | -118.332474  | 
| 1434624567  | Parks                   | Barry A. Sanders Sports Field                     | 6300     |                  |             | Balboa      | Blvd     |                   |             |                  |                  |             |               |                        | CA    | 91316 | http://www.laparks.org/dos/parks/facility/lakeBalboaPk.htm         | (818) 756-8060 | 6               | 34.186672   | -118.50107   | 
| 1434624567  | Dog Parks               | Hermon / Arroyo Seco Dog Park                     | 5566     |                  |             | Via Marisol |          |                   |             |                  |                  |             |               |                        | CA    | 90042 | http://laparks.org/dos/parks/facility/dogparks/HermonDogPk.htm     | (213) 485-5054 | 14              | 34.107407   | -118.185319  | 
| 1434624567  | Parks                   | Imperial Courts Park                              | 2250     |                  | E           | 114th       | St       |                   |             |                  |                  |             |               |                        | CA    | 90059 | http://www.laparks.org/dos/reccenter/facility/imperialcourtsRC.htm | (323) 564-1834 | 15              | 33.93125654 | -118.2324199 | 
| 1434624567  | Public Computer Centers | Wabash Recreation Center - Public Computer Center | 2765     |                  |             | Wabash      | Ave      |                   |             |                  |                  |             |               |                        | CA    | 90033 | http://www.laparks.org/btop/lynda.htm                              | (323) 262-6534 | 14              | 34.05070789 | -118.1981928 | 
| 1434624567  | Tennis Courts           | Griffith Park - Vermont Canyon Tennis Courts      | 2715     |                  |             | Vermont     | Cyn      |                   |             |                  |                  |             |               |                        | CA    | 90027 | http://www.laparks.org/dos/sports/tennis/facility/vermontcynTC.htm | (323) 664-3521 | 4               | 34.121019   | -118.293574  | 
| 1434624567  | Recreation Centers      | James Slauson Recreation Center                   | 5306     |                  | S           | Compton     | Ave      |                   |             |                  |                  |             |               |                        | CA    | 90011 | http://www.laparks.org/dos/reccenter/facility/slausonMC.htm        | (323) 233-1174 | 9               | 33.994156   | -118.247682  | 
```