# Boating Access Sites in Oregon

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boating-access-sites-in-oregon-f80d0) |
| Metadata | [Link](https://data.oregon.gov/api/views/spxe-q5vj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/spxe-q5vj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/spxe-q5vj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | spxe-q5vj |
| Name | Boating Access Sites in Oregon |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | boating access, boat launches, boat ramps, boating in oregon, marine board, kayaking, canoeing, cruising, waterskiing, lakes, reservoirs, rivers, bays, pacific ocean, waterway access, recreational... |
| Created | 2011-09-25T22:44:09Z |
| Publication Date | 2016-01-26T22:22:40Z |

## Description

Find a boat ramp in a location near you! Hundreds of boating access points, amenities, and launch information is available from this map. New coordinates are being added and other information to make your boating excursion fast and easy.

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | boating_facility_name        | Boating Facility Name        | text      | text        |
| Yes      | series tag  | waterbody                    | Waterbody                    | text      | text        |
| Yes      | series tag  | managed_by                   | Managed By                   | text      | text        |
| Yes      | series tag  | waterbody_aka_               | Waterbody (AKA)              | text      | text        |
| Yes      | series tag  | telephone                    | Telephone                    | phone     | phone       |
| Yes      | series tag  | additional_local_information | Details                      | url       | url         |
| Yes      | series tag  | county                       | County                       | text      | text        |
| Yes      | series tag  | launch_fee                   | Use Fee                      | text      | text        |
| Yes      | series tag  | restroom                     | Restroom                     | text      | text        |
| Yes      | series tag  | supplies                     | Supplies                     | text      | text        |
| Yes      | series tag  | gas_on_the_water             | Gas on the Water             | text      | text        |
| Yes      | series tag  | diesel_on_the_water          | Diesel on the Water          | text      | text        |
| Yes      | series tag  | ramp_type_lanes              | Ramp Type/ Number of Lanes   | text      | text        |
| Yes      | series tag  | fish_cleaning_station        | Fish Cleaning Station        | text      | text        |
| Yes      | series tag  | pumpout                      | Pumpout                      | text      | text        |
| Yes      | series tag  | dump_station                 | Dump Station                 | text      | text        |
| Yes      | series tag  | moorage                      | Moorage                      | text      | text        |
| Yes      | series tag  | transient_dock_footage       | Transient Dock Footage       | text      | text        |
| Yes      | series tag  | construction                 | Construction                 | text      | text        |
| Yes      | series tag  | boater_services              | Boater Services              | photo     | photo       |
| Yes      | series tag  | code                         | Code                         | text      | text        |
| Yes      | series tag  | trailer_parking              | Number of Trailer Spaces     | text      | text        |
| No       |             | latitude                     | Latitude                     | number    | number      |
| No       |             | longitude                    | Longitude                    | number    | number      |
| Yes      | series tag  | website                      | Website URL                  | url       | url         |
| Yes      | series tag  | boat_wash_station            | Boat Wash Station            | text      | text        |
| No       |             | pump_dump_location           | Pump/Dump Location           | text      | text        |
| Yes      | series tag  | use                          | Use                          | text      | text        |
| Yes      | series tag  | facility_also_known_as_aka_  | Facility Also Known As (AKA) | text      | text        |
| Yes      | series tag  | comments                     | Comments                     | text      | text        |
| Yes      | series tag  | photo                        | Photo                        | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,pump_dump_location
```

## Data Commands

```ls
series e:spxe-q5vj d:2012-01-06T14:07:10.000Z t:ramp_type_lanes="Hand Launch" t:phone_number=541-271-6000 t:managed_by="Oregon Dunes National Recreation Area" t:waterbody="Dune Lake" t:fish_cleaning_station="Not Available" t:launch_fee=None t:restroom="Vault Toilet Available" t:code=HlPr t:moorage="Not Available" t:pumpout=No t:trailer_parking="Not Available" t:transient_dock_footage="Not Available" t:diesel_on_the_water="Not Available" t:county=Coos t:boating_facility_name="Alder Dune Campground" t:dump_station=No t:construction="None at this time" t:gas_on_the_water="Not Available" t:supplies="Not Available" m:row_number.spxe-q5vj=1

series e:spxe-q5vj d:2012-01-06T14:07:10.000Z t:ramp_type_lanes="Hand Launch" t:phone_number=541-917-7777 t:managed_by="City of Albany" t:waterbody="Waverly Lake" t:fish_cleaning_station="Not Available" t:launch_fee=None t:restroom="Flush Restroom Available" t:code=HlPr t:moorage="Not Available" t:pumpout=No t:trailer_parking="Not Available" t:transient_dock_footage="Not Available" t:diesel_on_the_water="Not Available" t:county=Linn t:boating_facility_name="Waverly Park" t:dump_station=No t:construction="None at this time" t:gas_on_the_water="Not Available" t:supplies="Not Available" m:row_number.spxe-q5vj=2

series e:spxe-q5vj d:2012-01-09T08:32:04.000Z t:ramp_type_lanes="Gravel Ramp, No Defined Lanes" t:phone_number=503-897-2302 t:managed_by="City of Mill City" t:waterbody="Santiam River, North Fork" t:fish_cleaning_station="Not Available" t:launch_fee=None t:restroom="Not Available" t:code=La t:moorage="Not Available" t:pumpout=No t:boater_services=-0tvcjFKsEuGumH-lMooCQ3g7YOx8yc5i9MC9hUU2vk t:trailer_parking=Yes t:transient_dock_footage="Not Available" t:diesel_on_the_water="Not Available" t:county=Linn t:boating_facility_name="7th Street" t:dump_station=No t:construction="None at this time" t:facility_also_known_as_aka_="Kimmel Park" t:gas_on_the_water="Not Available" t:supplies="Not Available" m:row_number.spxe-q5vj=3
```

## Meta Commands

```ls
metric m:row_number.spxe-q5vj p:long l:"Row Number"

entity e:spxe-q5vj l:"Boating Access Sites in Oregon" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/spxe-q5vj

property e:spxe-q5vj t:meta.view v:id=spxe-q5vj v:category=Recreation v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="Boating Access Sites in Oregon" v:attribution="Oregon State Marine Board"

property e:spxe-q5vj t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:spxe-q5vj t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | boating_facility_name   | waterbody                 | managed_by                             | waterbody_aka_ | telephone            | additional_local_information                                                                                                       | county    | launch_fee | restroom                 | supplies      | gas_on_the_water | diesel_on_the_water | ramp_type_lanes               | fish_cleaning_station | pumpout | dump_station | moorage       | transient_dock_footage | construction      | boater_services                             | code | trailer_parking | latitude | longitude | website      | boat_wash_station | pump_dump_location | use | facility_also_known_as_aka_ | comments | photo                                       | 
| =========== | ======================= | ========================= | ====================================== | ============== | ==================== | ================================================================================================================================== | ========= | ========== | ======================== | ============= | ================ | =================== | ============================= | ===================== | ======= | ============ | ============= | ====================== | ================= | =========================================== | ==== | =============== | ======== | ========= | ============ | ================= | ================== | === | =========================== | ======== | =========================================== | 
| 1325858830  | Alder Dune Campground   | Dune Lake                 | Oregon Dunes National Recreation Area  |                | [541-271-6000, null] | [null, null]                                                                                                                       | Coos      | None       | Vault Toilet Available   | Not Available | Not Available    | Not Available       | Hand Launch                   | Not Available         | No      | No           | Not Available | Not Available          | None at this time |                                             | HlPr | Not Available   |          |           | [null, null] |                   |                    |     |                             |          |                                             | 
| 1325858830  | Waverly Park            | Waverly Lake              | City of Albany                         |                | [541-917-7777, null] | [null, null]                                                                                                                       | Linn      | None       | Flush Restroom Available | Not Available | Not Available    | Not Available       | Hand Launch                   | Not Available         | No      | No           | Not Available | Not Available          | None at this time |                                             | HlPr | Not Available   |          |           | [null, null] |                   |                    |     |                             |          |                                             | 
| 1326097924  | 7th Street              | Santiam River, North Fork | City of Mill City                      |                | [503-897-2302, null] | [null, null]                                                                                                                       | Linn      | None       | Not Available            | Not Available | Not Available    | Not Available       | Gravel Ramp, No Defined Lanes | Not Available         | No      | No           | Not Available | Not Available          | None at this time | -0tvcjFKsEuGumH-lMooCQ3g7YOx8yc5i9MC9hUU2vk | La   | Yes             |          |           | [null, null] |                   |                    |     | Kimmel Park                 |          |                                             | 
| 1326105545  | Barnes Valley           | Gerber Reservoir          | Bureau of Land Management              |                | [541-883-6916, null] | [null, null]                                                                                                                       | Klamath   | None       | Yes                      | Not Available | Not Available    | Not Available       | Asphalt Ramp with 1 Lane      | Not Available         | No      | No           | Not Available | Not Available          | None at this time | IGEgDRYavagR2r0vJZqqT0BgGEQTnJtQvo83pHiB39Q | LaPr | Yes             |          |           | [null, null] |                   |                    |     |                             |          |                                             | 
| 1326105177  | Art Moss                | Smith River               | Oregon Department of Fish and Wildlife |                | [800-720-6339, null] | [null, null]                                                                                                                       | Douglas   | None       | Not Available            | Not Available | Not Available    | Not Available       | Gravel Ramp, No Defined Lanes | Not Available         | No      | No           | Not Available | Not Available          | None at this time | -0tvcjFKsEuGumH-lMooCQ3g7YOx8yc5i9MC9hUU2vk | La   | Yes             |          |           | [null, null] |                   |                    |     |                             |          |                                             | 
| 1333442200  | Antelope Flat Reservoir | Antelope Flat Reservoir   | U.S. Forest Service                    |                | [541-416-6500, null] | [null, null]                                                                                                                       | Crook     | None       | Vault Toilet Available   | Not Available | Not Available    | Not Available       | Asphalt Ramp with 1 Lane      | Not Available         | No      | No           | Not Available | Not Available          | None at this time | IGEgDRYavagR2r0vJZqqT0BgGEQTnJtQvo83pHiB39Q | LaPr | 6-30 Stalls     |          |           | [null, null] |                   |                    |     |                             |          | A98o7fqqhE9mDAh_2E_cE41fGlaC-psw0tiCWnBFcws | 
| 1326105431  | Badger Lake             | Badger Lake               | U.S. Forest Service                    |                | [541-467-2291, null] | [null, null]                                                                                                                       | Wasco     | None       | Vault Toilet Available   | Not Available | Not Available    | Not Available       | Unimproved Ramp               | Not Available         | No      | No           | Not Available | Not Available          | None at this time | IGEgDRYavagR2r0vJZqqT0BgGEQTnJtQvo83pHiB39Q | LaPr | 6-30 Stalls     |          |           | [null, null] |                   |                    |     |                             |          |                                             | 
| 1326105497  | Baker Pond              | Baker Creek               | Oregon Department of Fish and Wildlife |                | [800-720-6339, null] | [null, null]                                                                                                                       | Coos      | None       | Not Available            | Not Available | Not Available    | Not Available       | Gravel Ramp, No Defined Lanes | Not Available         | No      | No           | Not Available | Not Available          | None at this time | -0tvcjFKsEuGumH-lMooCQ3g7YOx8yc5i9MC9hUU2vk | La   | Yes             |          |           | [null, null] |                   |                    |     | Baker Creek?                |          |                                             | 
| 1337591323  | Besson Day Use          | Deschutes River           | U.S. Forest Service                    |                | [541-383-4000, null] | [http://www.oregon.gov/OSMB/Pages/access/accesspages/DeschutesCounty/DeschutesRiverDeschutesCo.aspx, Additional Local Information] | Deschutes | None       | Vault Toilet Available   | Not Available | Not Available    | Not Available       | Gravel Ramp, No Defined Lanes | Not Available         | No      | No           | Not Available | Not Available          | None at this time | IGEgDRYavagR2r0vJZqqT0BgGEQTnJtQvo83pHiB39Q | LaPr | Yes             |          |           | [null, null] |                   |                    |     |                             |          |                                             | 
| 1333442724  | Beatty Access           | Sprague River             | Oregon Department of Fish and Wildlife |                | [800-720-6339, null] | [null, null]                                                                                                                       | Klamath   | None       | Not Available            | Not Available | Not Available    | Not Available       | Gravel Ramp, No Defined Lanes | Not Available         | No      | No           | Not Available | Not Available          | None at this time | -0tvcjFKsEuGumH-lMooCQ3g7YOx8yc5i9MC9hUU2vk | La   | Not Available   |          |           | [null, null] |                   |                    |     |                             |          | KSnJmosXAik7erYk863Ou3ozGLywFD13zw6CKbzaNb8 | 
```