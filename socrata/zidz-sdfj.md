# Landmark Districts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/landmark-districts-c4c61) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zidz-sdfj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zidz-sdfj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zidz-sdfj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zidz-sdfj |
| Name | Landmark Districts |
| Attribution | City of Chicago |
| Category | Historic Preservation |
| Tags | landmarks, tourism, gis |
| Created | 2010-04-28T22:44:13Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

This dataset is a list of Chicago Landmark Districts designated by City Council upon recommendation of the Commission on Chicago Landmarks. It contains the name of each Chicago Landmark District along with the date of its designation. Additional information about each Chicago Landmark District, including district maps, is available on the Chicago Landmarks home page at http://j.mp/lRJVnh. Districts which have been proposed for landmark designation by the Commission on Chicago Landmarks and remain under consideration are not included. This information is for illustrative purposes only; the legal boundaries are as identified by the respective landmark designation ordinances. A data set containing Individual Chicago Landmarks is available separately. Go to http://j.mp/m7t5nB to access the related GIS layer files. You will need compression software and special software, such as ESRI ArcGIS, to use the GIS files.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | district_name    | DISTRICT NAME    | text      | text        |
| Yes      | time        | designation_date | DESIGNATION DATE | date      | date        |
```

## Time Field

```ls
Value = designation_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:zidz-sdfj d:1977-09-28T07:00:00.000Z t:district_name="Old Town Triangle" m:row_number.zidz-sdfj=1

series e:zidz-sdfj d:2008-04-09T07:00:00.000Z t:district_name="Milwaukee Avenue" m:row_number.zidz-sdfj=2

series e:zidz-sdfj d:1975-12-19T08:00:00.000Z t:district_name="Astor Street" m:row_number.zidz-sdfj=3
```

## Meta Commands

```ls
metric m:row_number.zidz-sdfj p:long l:"Row Number"

entity e:zidz-sdfj l:"Landmark Districts" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/zidz-sdfj

property e:zidz-sdfj t:meta.view v:id=zidz-sdfj v:category="Historic Preservation" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Landmark Districts" v:attribution="City of Chicago"

property e:zidz-sdfj t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:zidz-sdfj t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| district_name                         | designation_date | 
| ===================================== | ================ | 
| Old Town Triangle                     | 244278000        | 
| Milwaukee Avenue                      | 1207724400       | 
| Astor Street                          | 188208000        | 
| Beverly/Morgan Park Railroad Stations | 797929200        | 
| Black Metropolis-Bronzeville          | 905324400        | 
| Surf-Pine Grove                       | 1184828400       | 
| Five Houses on Avers Avenue           | 762595200        | 
| Hawthorne Place                       | 827827200        | 
| Historic Michigan Boulevard           | 1014796800       | 
| Hutchinson Street                     | 241858800        | 
```