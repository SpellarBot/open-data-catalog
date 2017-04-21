# Boats For Hire Near NYS Canal System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boats-for-hire-near-nys-canal-system) |
| Metadata | [Link](https://data.ny.gov/api/views/ibtm-q4dj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ibtm-q4dj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ibtm-q4dj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ibtm-q4dj |
| Name | Boats For Hire Near NYS Canal System |
| Attribution | NYS Canal Corporation |
| Category | Transportation |
| Tags | transportation, nys canal system, nys thruway, boat rental, boat cruises, marina, vacation, travel |
| Created | 2014-04-22T16:14:58Z |
| Publication Date | 2015-11-19T21:12:40Z |

## Description

A listing of boats for hire (rentals and cruises) that are near the NYS Canal System

## Columns

```ls
| Included | Schema Type | Field Name     | Name                | Data Type | Render Type |
| ======== | =========== | ============== | =================== | ========= | =========== |
| No       | time        | :updated_at    | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | type           | Type                | text      | text        |
| Yes      | series tag  | company        | Company             | text      | text        |
| No       |             | street_address | Address             | text      | text        |
| Yes      | series tag  | company_url    | Company URL         | url       | url         |
| Yes      | series tag  | city           | City                | text      | text        |
| Yes      | series tag  | state          | State               | text      | text        |
| Yes      | series tag  | zip            | ZIP                 | text      | text        |
| Yes      | series tag  | phone_number   | Phone number        | text      | html        |
| Yes      | series tag  | vessel_types   | Vessel Types, Names | text      | text        |
| Yes      | series tag  | cruise_type    | Cruise Type         | text      | text        |
| Yes      | series tag  | home_port      | Home Port           | text      | text        |
| Yes      | series tag  | waterways      | Waterways           | text      | text        |
| No       |             | latitude       | Latitude            | number    | number      |
| No       |             | longitude      | Longitude           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = street_address,latitude,longitude
```

## Data Commands

```ls
series e:ibtm-q4dj d:2015-11-19T13:11:29.000Z t:zip=14228 t:home_port=Amherst t:phone_number="(716) 691-6707" t:company="Amherst Marine Center" t:state=NY t:waterways=All t:type=rentals t:vessel_types="24' Pontoon-camper" t:company_url=http://www.amherstmarinecenter.com/ t:city=Amherst m:row_number.ibtm-q4dj=1

series e:ibtm-q4dj d:2015-11-19T13:11:29.000Z t:zip=13042 t:home_port=Cleveland t:phone_number="(315) 820-2628" t:company="Angler's Bay" t:state=NY t:waterways="Oneida Lake, Erie Canal (eastern)" t:type=rentals t:vessel_types="Sport, fishing, and pontoon boats" t:company_url=http://boatoneida.com/ t:city=Cleveland m:row_number.ibtm-q4dj=2

series e:ibtm-q4dj d:2015-11-19T13:11:29.000Z t:zip=14202 t:home_port=Buffalo t:phone_number="(716) 228-9153" t:company="BFLO Harbor Kayak" t:state=NY t:waterways="Buffalo Inner Harbor" t:type=rentals t:vessel_types="Kayaks, paddle boards" t:company_url=http://bfloharborkayak.com/ t:city=Buffalo m:row_number.ibtm-q4dj=3
```

## Meta Commands

```ls
metric m:row_number.ibtm-q4dj p:long l:"Row Number"

entity e:ibtm-q4dj l:"Boats For Hire Near NYS Canal System" t:attribution="NYS Canal Corporation" t:url=https://data.ny.gov/api/views/ibtm-q4dj

property e:ibtm-q4dj t:meta.view v:id=ibtm-q4dj v:category=Transportation v:attributionLink=http://www.canals.ny.gov/boating/boatsforhire.cgi v:averageRating=0 v:name="Boats For Hire Near NYS Canal System" v:attribution="NYS Canal Corporation"

property e:ibtm-q4dj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ibtm-q4dj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ibtm-q4dj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | type    | company                       | street_address                  | company_url                                            | city          | state | zip   | phone_number   | vessel_types                                                | cruise_type | home_port     | waterways                                              | latitude           | longitude           | 
| =========== | ======= | ============================= | =============================== | ====================================================== | ============= | ===== | ===== | ============== | =========================================================== | =========== | ============= | ====================================================== | ================== | =================== | 
| 1447938689  | rentals | Amherst Marine Center         | 1900 Campbell Boulevard         | [http://www.amherstmarinecenter.com/, null]            | Amherst       | NY    | 14228 | (716) 691-6707 | 24' Pontoon-camper                                          |             | Amherst       | All                                                    | 43.067810999999999 | -78.773047000000005 | 
| 1447938689  | rentals | Angler's Bay                  | 103 Drive 17                    | [http://boatoneida.com/, null]                         | Cleveland     | NY    | 13042 | (315) 820-2628 | Sport, fishing, and pontoon boats                           |             | Cleveland     | Oneida Lake, Erie Canal (eastern)                      | 43.224485999999999 | -75.833256000000006 | 
| 1447938689  | rentals | BFLO Harbor Kayak             | 1 Navel Park Cove               | [http://bfloharborkayak.com/, null]                    | Buffalo       | NY    | 14202 | (716) 228-9153 | Kayaks, paddle boards                                       |             | Buffalo       | Buffalo Inner Harbor                                   | 42.876953          | -78.879801999999998 | 
| 1447938689  | rentals | The Boat House                | 2855 Aqueduct Road              | [http://www.boathousecanoeskayaks.com/, null]          | Schenectady   | NY    | 12309 | (518) 393-5711 | Canoes & kayaks                                             |             | Niskayuna     | Erie Canal (eastern)                                   | 42.849040000000002 | -73.889588000000003 | 
| 1447938689  | rentals | Buffalo River Canoe & Kayak   | 900 Harlem Road                 | [http://alli-50.wix.com/buffaloriver, null]            | West Seneca   | NY    | 14224 | (716) 771-2995 | Canoes & kayaks                                             |             | Buffalo       | Buffalo River                                          | 42.869520999999999 | -78.786711999999994 | 
| 1447938689  | rentals | Canal Princess Charters       | 5176 Tonawanda Creek Road-North | [http://www.porchesofpendleton.com/cruise.shtml, null] | N. Tonawanda  | NY    | 14120 | (716) 308-3961 | 34' Houseboats                                              |             | Pendleton     | Erie Canal (western)                                   | 43.070141          | -78.754748000000006 | 
| 1447938689  | rentals | Canalside Experiences         | 706 Waterloo-Geneva Road        | [http://www.canalside.net/, null]                      | Waterloo      | NY    | 13165 | (315) 651-4443 | Canoes & kayaks, fishing boats & rowboats, 24' Pontoon boat |             | Waterloo      | Cayuga-Seneca Canal                                    | 42.891620000000003 | -76.916673000000003 | 
| 1447938689  | rentals | Champlain Houseboat Charters  | P.O. Box 62                     | [http://www.champlainhouseboatcharters.com/, null]     | Orwell        | VT    | 5760  | (802) 948-2288 | Houseboats, pontoon boats                                   |             | Orwell, VT    | Champlain Canal, Lake Champlain                        | 43.799988999999997 | -73.375732999999997 | 
| 1447938689  | rentals | Cruise - USA                  | 406 Mc Namee Ave                | [http://www.cruise-usa.com/, null]                     | Ocean Springs | MS    | 39564 | (228) 424-3768 | 24' Trawlers                                                |             | Union Springs | Cayuga Lake, Cayuga-Seneca Canal, Erie Canal (western) | 42.857511000000002 | -76.707217999999997 | 
| 1447938689  | rentals | Erie Canal Boat Company, Inc. | 7 Liftbridge Lane West          | [http://www.eriecanalboatcompany.com/, null]           | Fairport      | NY    | 14450 | (585) 748-2628 | Canoes, kayaks, paddleboats & pontoon boats                 |             | Fairport      | Erie Canal (western)                                   | 43.102710999999999 | -77.443280000000001 | 
```