# Abandoned Wells

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/abandoned-wells) |
| Metadata | [Link](https://data.ny.gov/api/views/vgue-bamz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vgue-bamz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vgue-bamz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vgue-bamz |
| Name | Abandoned Wells |
| Attribution | New York State Department of Environmental Conservation, Division of Mineral Resources |
| Category | Energy & Environment |
| Tags | oil, gas, brine, wells, geology, mineral resources, abandoned, plugging, plugged |
| Created | 2016-02-03T21:34:08Z |
| Publication Date | 2016-02-10T19:47:04Z |

## Description

List of wells that are regulated under the Oil, Gas and Solution Mining Law (ECL Article 23) in New York State that are abandoned and not plugged.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | company_name      | COMPANY NAME      | text      | text        |
| Yes      | series tag  | county            | COUNTY            | text      | text        |
| Yes      | series tag  | town              | TOWN              | text      | text        |
| Yes      | series tag  | api_well_number   | API WELL NUMBER   | text      | number      |
| Yes      | series tag  | well_name         | WELL NAME         | text      | text        |
| Yes      | series tag  | well_status       | WELL STATUS CODE  | text      | text        |
| Yes      | series tag  | well_status_name  | WELL STATUS NAME  | text      | text        |
| Yes      | series tag  | well_type         | WELL TYPE         | text      | text        |
| Yes      | series tag  | well_type_name    | WELL TYPE NAME    | text      | text        |
| No       |             | surface_longitude | SURFACE LONGITUDE | number    | number      |
| No       |             | surface_latitude  | SURFACE LATITUDE  | number    | number      |
| Yes      | series tag  | region            | REGION            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = surface_longitude,surface_latitude
```

## Data Commands

```ls
series e:vgue-bamz d:2016-02-03T14:28:29.000Z t:region=9 t:well_name="Lacy James 1" t:well_type_name="Gas Development" t:company_name="Alden Batavia Natural Gas Co." t:county=Statewide t:well_type=GD t:well_status_name=Unknown t:town=UNK t:api_well_number=31121022790000 t:well_status=UN m:row_number.vgue-bamz=1

series e:vgue-bamz d:2016-02-03T14:28:29.000Z t:region=9 t:well_name="Mooney William" t:well_type_name="Gas Development" t:company_name="Alden Batavia Natural Gas Co." t:county=Wyoming t:well_type=GD t:well_status_name=Unknown t:town=Middlebury t:api_well_number=31121031590000 t:well_status=UN m:row_number.vgue-bamz=2

series e:vgue-bamz d:2016-02-03T14:28:29.000Z t:region=9 t:well_name="Brennan 1" t:well_type_name="Not Listed" t:company_name="Becker,  Howard Russell" t:county=Cattaraugus t:well_type=NL t:well_status_name=Unknown t:town=Ellicottville t:api_well_number=31009051730000 t:well_status=UN m:row_number.vgue-bamz=3
```

## Meta Commands

```ls
metric m:row_number.vgue-bamz p:long l:"Row Number"

entity e:vgue-bamz l:"Abandoned Wells" t:attribution="New York State Department of Environmental Conservation, Division of Mineral Resources" t:url=https://data.ny.gov/api/views/vgue-bamz

property e:vgue-bamz t:meta.view v:id=vgue-bamz v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/energy/205.html v:averageRating=0 v:name="Abandoned Wells" v:attribution="New York State Department of Environmental Conservation, Division of Mineral Resources"

property e:vgue-bamz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vgue-bamz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | company_name                  | county      | town          | api_well_number | well_name      | well_status | well_status_name    | well_type | well_type_name  | surface_longitude | surface_latitude | region | 
| =========== | ============================= | =========== | ============= | =============== | ============== | =========== | =================== | ========= | =============== | ================= | ================ | ====== | 
| 1454509709  | Alden Batavia Natural Gas Co. | Statewide   | UNK           | 31121022790000  | Lacy James 1   | UN          | Unknown             | GD        | Gas Development |                   |                  | 9      | 
| 1454509709  | Alden Batavia Natural Gas Co. | Wyoming     | Middlebury    | 31121031590000  | Mooney William | UN          | Unknown             | GD        | Gas Development |                   |                  | 9      | 
| 1454509709  | Becker, Howard Russell        | Cattaraugus | Ellicottville | 31009051730000  | Brennan 1      | UN          | Unknown             | NL        | Not Listed      |                   |                  | 9      | 
| 1454509709  | Bradley Producing Corp.       | Allegany    | Alma          | 31003050250000  | Lot 91 29-91   | NR          | Not Reported on AWR | OD        | Oil Development |                   |                  | 9      | 
| 1454509709  | Bradley Salt Co.              | Wyoming     | Warsaw        | 31121033020000  | Salt Well      | UN          | Unknown             | BR        | Brine           |                   |                  | 9      | 
| 1454509709  | Corning Fuel & Heating        | Steuben     | Corning       | 31101009630000  | Unnamed        | UM          | Unknown Not Found   | DW        | Dry Wildcat     |                   |                  | 8      | 
| 1454509709  | Farmers Oil & Gas, Inc.       | Cattaraugus | Cold Spring   | 31009048450000  | Monroe 35      | NR          | Not Reported on AWR | GD        | Gas Development |                   |                  | 9      | 
| 1454509709  | Glen Salt Company             | Schuyler    | Dix           | 31097007340000  | None           | UM          | Unknown Not Found   | BR        | Brine           |                   |                  | 8      | 
| 1454509709  | Hadley & Rogers               | Cayuga      | Cato          | 31011018780000  | Huffman        | UN          | Unknown             | NL        | Not Listed      |                   |                  | 7      | 
| 1454509709  | Home Gas Company              | Steuben     | Wayne         | 31101005870000  | Conklin        | UM          | Unknown Not Found   | GD        | Gas Development |                   |                  | 8      | 
```