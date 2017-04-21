# My Neighborhood Map

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/my-neighborhood-map-74144) |
| Metadata | [Link](https://data.seattle.gov/api/views/82su-5fxf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/82su-5fxf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/82su-5fxf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 82su-5fxf |
| Name | My Neighborhood Map |
| Attribution | City of Seattle, My Neighborhood Map program |
| Category | Community |
| Created | 2009-12-10T21:44:40Z |
| Publication Date | 2014-07-11T22:59:34Z |

## Description

Data set from My Neighborhood Map program.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | city_feature | City Feature | text      | text        |
| Yes      | series tag  | common_name  | Common Name  | text      | text        |
| No       |             | address      | Address      | text      | text        |
| Yes      | series tag  | website      | Website      | url       | url         |
| No       |             | longitude    | Longitude    | number    | number      |
| No       |             | latitude     | Latitude     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:82su-5fxf d:2010-01-12T08:21:35.000Z t:city_feature="Fire Stations" t:common_name="Fire Station #25" m:row_number.82su-5fxf=1

series e:82su-5fxf d:2010-05-07T12:14:00.000Z t:city_feature="Computer/Media Center" t:common_name="611 12th AV S STE 300" m:row_number.82su-5fxf=2

series e:82su-5fxf d:2010-01-12T08:21:35.000Z t:website=http://www.seattle.gov/trafficcams/i5_pine.htm t:city_feature="Traffic Cameras" m:row_number.82su-5fxf=3
```

## Meta Commands

```ls
metric m:row_number.82su-5fxf p:long l:"Row Number"

entity e:82su-5fxf l:"My Neighborhood Map" t:attribution="City of Seattle, My Neighborhood Map program" t:url=https://data.seattle.gov/api/views/82su-5fxf

property e:82su-5fxf t:meta.view v:id=82su-5fxf v:category=Community v:attributionLink=http://www.seattle.gov/mnm v:averageRating=0 v:name="My Neighborhood Map" v:attribution="City of Seattle, My Neighborhood Map program"

property e:82su-5fxf t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:82su-5fxf t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | city_feature          | common_name           | address                      | website                                                        | longitude   | latitude  | 
| =========== | ===================== | ===================== | ============================ | ============================================================== | =========== | ========= | 
| 1263284495  | Fire Stations         | Fire Station #25      | 1300 E PINE ST               | [null, null]                                                   | -122.315096 | 47.615568 | 
| 1273234440  | Computer/Media Center | 611 12th AV S STE 300 | Seattle Indian Center        | [null, null]                                                   | -122.31838  | 47.59721  | 
| 1263284495  | Traffic Cameras       |                       | I-5 at Pine Street           | [http://www.seattle.gov/trafficcams/i5_pine.htm, null]         | -122.329823 | 47.614455 | 
| 1263284495  | Traffic Cameras       |                       | Northgate Way and 5th Ave NE | [http://www.seattle.gov/trafficcams/northgate_5thb.htm, null]  | -122.323277 | 47.708594 | 
| 1263284495  | Traffic Cameras       |                       | Northgate Way and 5th Ave NE | [http://www.seattle.gov/trafficcams/northgate_5thb.htm, null]  | -122.323074 | 47.708597 | 
| 1263284495  | Traffic Cameras       |                       | Aurora Ave and Mercer St     | [http://www.seattle.gov/trafficcams/aurora_mercer.htm, null]   | -122.343659 | 47.6245   | 
| 1263284495  | Traffic Cameras       |                       | Fairview and Mercer St       | [http://www.seattle.gov/trafficcams/fairview_mercer.htm, null] | -122.334291 | 47.624539 | 
| 1263284495  | Traffic Cameras       |                       | 4th Ave South at I-90 Ramps  | [http://www.seattle.gov/trafficcams/4thave_i90.htm, null]      | -122.329052 | 47.594286 | 
| 1263284495  | Traffic Cameras       |                       | 4th and Atlantic             | [http://www.seattle.gov/trafficcams/4th_atlantic.htm, null]    | -122.328841 | 47.590302 | 
| 1263284495  | Traffic Cameras       |                       | 6th Ave S at S Spokane St    | [http://www.seattle.gov/trafficcams/6th_Spokane.htm, null]     | -122.325985 | 47.571713 | 
```