# Environmental Conservation Staff Office Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/environmental-conservation-staff-office-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/ph8g-y9wj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ph8g-y9wj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ph8g-y9wj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ph8g-y9wj |
| Name | Environmental Conservation Staff Office Locations |
| Attribution | Department of Environmental Conservation (DEC) |
| Category | Energy & Environment |
| Tags | dec staff |
| Created | 2015-04-17T19:24:41Z |
| Publication Date | 2015-06-22T16:54:55Z |

## Description

This dataset provides a listing, including location and site informtion for all New York State offices with Department of Environmental Conservation (DEC) staff.

## Columns

```ls
| Included | Schema Type | Field Name     | Name            | Data Type | Render Type |
| ======== | =========== | ============== | =============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | region         | Region          | text      | text        |
| Yes      | series tag  | location       | Office Location | text      | text        |
| Yes      | series tag  | site           | Site            | text      | text        |
| Yes      | series tag  | facility       | Facility        | text      | text        |
| Yes      | series tag  | street_address | Street Address  | text      | text        |
| Yes      | series tag  | city           | City            | text      | text        |
| Yes      | series tag  | state          | State           | text      | text        |
| Yes      | series tag  | zip            | Zip             | text      | number      |
| No       |             | latitude       | Latitude        | number    | number      |
| No       |             | longititude    | Longititude     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longititude
```

## Data Commands

```ls
series e:ph8g-y9wj d:2015-06-05T07:49:45.000Z t:site="Potsdam Sub-Office" t:region=6 t:zip=13676 t:facility="regional sub-office" t:location=Potsdam t:state=NY t:street_address="6739 US Highway 11" t:city=Potsdam m:row_number.ph8g-y9wj=1

series e:ph8g-y9wj d:2015-06-05T07:49:45.000Z t:site="Ridge Maintenance Center" t:region=1 t:zip=11961 t:facility="maintenance center" t:location=Ridge t:state=NY t:street_address="484 Randall Road" t:city=Ridge m:row_number.ph8g-y9wj=2

series e:ph8g-y9wj d:2015-06-05T07:49:45.000Z t:site="Marine Resources Headquarters" t:region=1 t:zip=11733 t:facility="marine headquarters" t:location="East Setauket" t:state=NY t:street_address="205 Belle Meade Road" t:city="East Setauket" m:row_number.ph8g-y9wj=3
```

## Meta Commands

```ls
metric m:row_number.ph8g-y9wj p:long l:"Row Number"

entity e:ph8g-y9wj l:"Environmental Conservation Staff Office Locations" t:attribution="Department of Environmental Conservation (DEC)" t:url=https://data.ny.gov/api/views/ph8g-y9wj

property e:ph8g-y9wj t:meta.view v:id=ph8g-y9wj v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov v:averageRating=0 v:name="Environmental Conservation Staff Office Locations" v:attribution="Department of Environmental Conservation (DEC)"

property e:ph8g-y9wj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ph8g-y9wj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ph8g-y9wj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | region | location           | site                                   | facility              | street_address                           | city             | state | zip   | latitude  | longititude | 
| =========== | ====== | ================== | ====================================== | ===================== | ======================================== | ================ | ===== | ===== | ========= | =========== | 
| 1433490585  | 6      | Potsdam            | Potsdam Sub-Office                     | regional sub-office   | 6739 US Highway 11                       | Potsdam          | NY    | 13676 | 44.63212  | -75.084756  | 
| 1433490585  | 1      | Ridge              | Ridge Maintenance Center               | maintenance center    | 484 Randall Road                         | Ridge            | NY    | 11961 | 40.897689 | -72.893457  | 
| 1433490585  | 1      | East Setauket      | Marine Resources Headquarters          | marine headquarters   | 205 Belle Meade Road                     | East Setauket    | NY    | 11733 | 40.898445 | -73.088322  | 
| 1433490585  | 1      | Stony Brook Campus | Stony Brook Regional Headquarters      | regional headquarters | SUNY Campus; 50 Circle Road              | Stony Brook      | NY    | 11790 | 40.921887 | -73.119969  | 
| 1433490585  | 2      | Long Island City   | Long Island City Regional Headquarters | regional headquarters | 1 Hunters Point Plaza; 47-40 21st Street | Long Island City | NY    | 11101 | 40.744273 | -73.948911  | 
| 1433490585  | 3      | Catskill Park      | Beaverkill Campground                  | campground            | 792 Berrybrook Road                      | Roscoe           | NY    | 12776 | 41.978274 | -74.840606  | 
| 1433490585  | 3      | Catskill Park      | Kenneth L. Wilson Campground           | campground            | 859 Wittenberg Road                      | Mt. Tremper      | NY    | 12457 | 42.026819 | -74.225316  | 
| 1433490585  | 3      | Catskill Park      | Mongaup Pond Campground                | campground            | 231 Mongaup Road                         | Livingston Manor | NY    | 12758 | 41.957321 | -74.691193  | 
| 1433490585  | 3      | Catskill Park      | Woodland Valley Campground             | campground            | 1319 Woodland Valley Road                | Phoenicia        | NY    | 12464 | 42.035724 | -74.360854  | 
| 1433490585  | 3      | Livingston Manor   | DeBruce Environmental Education Camp   | education camp        | 307 Mongaup Pond Road                    | Livingston Manor | NY    | 12758 | 41.932596 | -74.71251   | 
```