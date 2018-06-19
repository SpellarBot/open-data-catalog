# Micro-Market Recovery Program - Addresses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/micro-market-recovery-program-addresses-0e20b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cf2f-mmzv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cf2f-mmzv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cf2f-mmzv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cf2f-mmzv |
| Name | Micro-Market Recovery Program - Addresses |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | buildings, inspections |
| Created | 2013-06-21T18:03:55Z |
| Publication Date | 2013-11-15T20:37:20Z |

## Description

The City of Chicago launched the Micro-Market Recovery Program (MMRP), a coordinated effort among the City, not-for-profit intermediaries, and non-profit and for-profit capital sources to improve conditions, strengthen property values, and create environments supportive of private investment in targeted markets throughout the city. The goal of MMRP is to improve conditions, strengthen property values, and create environments supportive of private investment in targeted areas by strategically deploying public and private capital and other tools and resources in well-defined micro-markets. This address dataset contains additional geographies, such as Fire and Police Districts, Census Tract and TIF Zones, that can be linked to MMRP Permit, Case and Violation data using the ADDRKEY or ADDRGRPKEY.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | mmrp_zone                 | MMRP Zone                 | text      | text        |
| Yes      | series tag     | street_number             | Street Number             | text      | number      |
| Yes      | series tag     | pre_direction             | Pre-Direction             | text      | text        |
| Yes      | series tag     | street_name               | Street Name               | text      | text        |
| Yes      | series tag     | suffix                    | Suffix                    | text      | text        |
| Yes      | series tag     | post_direction            | Post Direction            | text      | text        |
| Yes      | series tag     | zip_code                  | Zip Code                  | text      | number      |
| Yes      | series tag     | community_area            | Community Area            | text      | number      |
| Yes      | series tag     | ward                      | Ward                      | text      | number      |
| Yes      | series tag     | fire_district             | Fire District             | text      | text        |
| Yes      | series tag     | police_district           | Police District           | text      | number      |
| Yes      | numeric metric | census_tract              | Census Tract              | number    | number      |
| Yes      | series tag     | tif_zone                  | TIF Zone                  | text      | text        |
| Yes      | numeric metric | x_coord                   | X Coord                   | number    | number      |
| Yes      | numeric metric | y_coord                   | Y Coord                   | number    | number      |
| No       |                | latitude                  | Latitude                  | number    | number      |
| No       |                | longitude                 | Longitude                 | number    | number      |
| Yes      | series tag     | central_business_district | Central Business District | text      | text        |
| No       |                | address_key               | Address Key               | number    | number      |
| No       |                | address_grouping_key      | Address Grouping Key      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,address_key,address_grouping_key
```

## Data Commands

```ls
series e:cf2f-mmzv d:2014-11-28T22:00:51.000Z t:ward=17 t:zip_code=60620 t:fire_district=DDC5 t:police_district=6 t:street_name=MORGAN t:central_business_district=N t:street_number=7720 t:community_area=71 t:pre_direction=S t:suffix=ST t:mmrp_zone="Auburn Gresham" m:y_coord=1853527.6787065247 m:x_coord=1170944.9031244244 m:census_tract=710200

series e:cf2f-mmzv d:2015-01-14T22:00:51.000Z t:ward=31 t:zip_code=60639 t:fire_district=DDC2 t:police_district=25 t:street_name=PARKER t:central_business_district=N t:street_number=5202 t:community_area=19 t:pre_direction=W t:suffix=AVE t:mmrp_zone="North Belmont Cragin" m:y_coord=1917828.7163831242 m:x_coord=1141187.3073681635 m:census_tract=190701

series e:cf2f-mmzv d:2015-01-20T22:00:56.000Z t:ward=17 t:zip_code=60620 t:fire_district=DDC5 t:police_district=6 t:street_name=76TH t:central_business_district=N t:street_number=859 t:community_area=71 t:pre_direction=W t:suffix=ST t:mmrp_zone="Auburn Gresham" m:y_coord=1854410.1146667472 m:x_coord=1171640.1001754126 m:census_tract=710200
```

## Meta Commands

```ls
metric m:census_tract p:integer l:"Census Tract" d:"Geography - Census Tract" t:dataTypeName=number

metric m:x_coord p:double l:"X Coord" d:"X Coord - State Plane Eastern IL 1983" t:dataTypeName=number

metric m:y_coord p:double l:"Y Coord" d:"Y Coord - State Plane Eastern IL 1983" t:dataTypeName=number

entity e:cf2f-mmzv l:"Micro-Market Recovery Program - Addresses" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/cf2f-mmzv

property e:cf2f-mmzv t:meta.view v:id=cf2f-mmzv v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Micro-Market Recovery Program - Addresses" v:attribution="City of Chicago"

property e:cf2f-mmzv t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:cf2f-mmzv t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | mmrp_zone            | street_number | pre_direction | street_name | suffix | post_direction | zip_code | community_area | ward | fire_district | police_district | census_tract | tif_zone             | x_coord            | y_coord            | latitude          | longitude          | central_business_district | address_key | address_grouping_key | 
| =========== | ==================== | ============= | ============= | =========== | ====== | ============== | ======== | ============== | ==== | ============= | =============== | ============ | ==================== | ================== | ================== | ================= | ================== | ========================= | =========== | ==================== | 
| 1417212051  | Auburn Gresham       | 7720          | S             | MORGAN      | ST     |                | 60620    | 71             | 17   | DDC5          | 6               | 710200       |                      | 1170944.9031244244 | 1853527.6787065247 | 41.75355201836382 | -87.64911776261444 | N                         | 1514073     | 662786               | 
| 1421272851  | North Belmont Cragin | 5202          | W             | PARKER      | AVE    |                | 60639    | 19             | 31   | DDC2          | 25              | 190701       |                      | 1141187.3073681635 | 1917828.7163831242 | 41.93060105433462 | -87.75658775972838 | N                         | 1517345     | 7857                 | 
| 1421791256  | Auburn Gresham       | 859           | W             | 76TH        | ST     |                | 60620    | 71             | 17   | DDC5          | 6               | 710200       |                      | 1171640.1001754126 | 1854410.1146667472 | 41.7559583360956  | -87.64654430557658 | N                         | 1517756     | 423419               | 
| 1421791256  | Auburn Gresham       | 7605          | S             | PEORIA      | ST     |                | 60620    | 71             | 17   | DDC5          | 6               | 710200       |                      | 1171664.7273119113 | 1854376.4727240792 | 41.75586547877622 | -87.64645503716304 | N                         | 1517755     | 423419               | 
| 1421791256  | Auburn Gresham       | 7603          | S             | PEORIA      | ST     |                | 60620    | 71             | 17   | DDC5          | 6               | 710200       |                      | 1171664.0927513372 | 1854397.0766903008 | 41.75592203259488 | -87.64645675981151 | N                         | 1517754     | 423419               | 
| 1440626453  | Auburn Gresham       | 1307          | W             | 78TH        | ST     |                | 60620    | 71             | 17   | DDC5          | 6               | 710700       |                      | 1169152.3444251125 | 1853013.6614610741 | 41.75218041792687 | -87.65570167746172 | N                         | 1538152     | 25117                | 
| 1440799243  | Chatham              | 979           | E             | 80TH        | ST     |                | 60619    | 44             | 8    | DDC5          | 6               | 440101       |                      | 1184266.2553939687 | 1852124.5924792942 | 41.74940071856707 | -87.60034404924242 | N                         | 1538353     | 665146               | 
| 1441058441  | North Belmont Cragin | 2518          | N             | CICERO      | AVE    |                | 60639    | 19             | 31   | DDC2          | 25              | 190800       | Belmont/Cicero       | 1143930.1909635097 | 1916436.7569176324 | 41.92673030805081 | -87.74654315815138 | N                         | 1538552     | 665174               | 
| 1441922480  | Belmont Cragin       | 4817          | W             | MEDILL      | AVE    |                | 60639    | 19             | 36   | DDC2          | 25              | 191100       |                      | 1143813.5236522094 | 1915152.8242177959 | 41.92320925798993 | -87.74700412363097 |                           | 138096      | 94122                | 
| 1441922480  | Auburn Gresham       | 7912          | S             | RACINE      | AVE    |                | 60620    | 71             | 21   | DDC5          | 6               | 710700       | 79th Street Corridor | 1169657.3407706926 | 1852246.8462916424 | 41.75006524479848 | -87.65387327908266 |                           | 506915      | 438495               | 
```