# Water Quality Sampling Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-quality-sampling-locations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/t9gx-rxwg) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/t9gx-rxwg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/t9gx-rxwg/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | t9gx-rxwg |
| Name | Water Quality Sampling Locations |
| Attribution | City of Austin, Watershed Protection |
| Category | Environmental |
| Tags | water quality, eii, ali, barton springs, lady bird lake, lake austin, salamanders, barton creek, bull creek, bacteria, coli |
| Created | 2013-12-11T16:13:18Z |
| Publication Date | 2015-08-14T23:41:07Z |

## Description

These are the discrete sampling locations brought out of the Water Quality Sampling Data dataset [https://data.austintexas.gov/Environmental/Water-Quality-Sampling-Data/5tye-7ray] for ease of mapping.  SampleSiteNo in this table maps to SAMPLE_SITE_NO in the larger dataset. Note that not all samples in the larger dataset have a match in this table ... this table only contains sampling locations with valid latitude/longitude values.  Reasons for samples not having a valid physical location: the data represents a non-spatial object like a product or a lab standard or blank; the data was collected at a protected karst feature; the data was collected prior to GIS or GPS and the information never existed or was lost.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | sample_site_no         | SampleSiteNo           | text          | number        |
| Yes      | series tag     | site_name              | SiteName               | text          | text          |
| Yes      | series tag     | watershed              | Watershed              | text          | text          |
| Yes      | series tag     | site_type              | SiteType               | text          | text          |
| Yes      | numeric metric | number_of_visits       | Number of Visits       | number        | number        |
| Yes      | numeric metric | number_of_data_points  | Number of Data Points  | number        | number        |
| Yes      | time           | first_sampledate       | First SampleDate       | calendar_date | calendar_date |
| No       |                | most_recent_sampledate | Most Recent SampleDate | calendar_date | calendar_date |
| Yes      | series tag     | eii_site               | EII Site               | text          | text          |
| Yes      | series tag     | ali_site               | ALI Site               | text          | text          |
```

## Time Field

```ls
Value = first_sampledate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = most_recent_sampledate
```

## Data Commands

```ls
series e:t9gx-rxwg d:1991-12-30T00:00:00.000Z t:ali_site=F t:watershed="Lady Bird Lake" t:site_type=Lake t:sample_site_no=10 t:eii_site=F t:site_name="Lady Bird Lake @ Deep Eddy" m:number_of_visits=10 m:number_of_data_points=169

series e:t9gx-rxwg d:1994-01-06T00:00:00.000Z t:ali_site=F t:watershed="Barton Creek" t:site_type=Stream t:sample_site_no=100 t:eii_site=F t:site_name="Hebbingston Hollow Trib @ Barton Creek (HHT)" m:number_of_visits=11 m:number_of_data_points=138

series e:t9gx-rxwg d:1997-07-08T00:00:00.000Z t:ali_site=F t:watershed="Buttercup Creek" t:site_type=Stream t:sample_site_no=1000 t:eii_site=F t:site_name="Buttercup Branch Creek Upstream of Springdale" m:number_of_visits=1 m:number_of_data_points=98
```

## Meta Commands

```ls
metric m:number_of_visits p:integer l:"Number of Visits" d:"The number of dates that this site was visited for a given project by a specific workgroup." t:dataTypeName=number

metric m:number_of_data_points p:integer l:"Number of Data Points" d:"Number of rows of data collected at this sample site." t:dataTypeName=number

entity e:t9gx-rxwg l:"Water Quality Sampling Locations" t:attribution="City of Austin, Watershed Protection" t:url=https://data.austintexas.gov/api/views/t9gx-rxwg

property e:t9gx-rxwg t:meta.view v:id=t9gx-rxwg v:category=Environmental v:attributionLink=http://www.austintexas.gov/department/watershed-protection v:averageRating=0 v:name="Water Quality Sampling Locations" v:attribution="City of Austin, Watershed Protection"

property e:t9gx-rxwg t:meta.view.license v:name="Public Domain"

property e:t9gx-rxwg t:meta.view.owner v:id=buxt-jupg v:profileImageUrlMedium=/api/users/buxt-jupg/profile_images/THUMB v:profileImageUrlLarge=/api/users/buxt-jupg/profile_images/LARGE v:screenName=Rob v:profileImageUrlSmall=/api/users/buxt-jupg/profile_images/TINY v:displayName=Rob

property e:t9gx-rxwg t:meta.view.tableauthor v:id=buxt-jupg v:profileImageUrlMedium=/api/users/buxt-jupg/profile_images/THUMB v:profileImageUrlLarge=/api/users/buxt-jupg/profile_images/LARGE v:screenName=Rob v:profileImageUrlSmall=/api/users/buxt-jupg/profile_images/TINY v:roleName=publisher v:displayName=Rob
```

## Top Records

```ls
| sample_site_no | site_name                                     | watershed       | site_type        | number_of_visits | number_of_data_points | first_sampledate    | most_recent_sampledate | eii_site | ali_site | 
| ============== | ============================================= | =============== | ================ | ================ | ===================== | =================== | ====================== | ======== | ======== | 
| 10             | Lady Bird Lake @ Deep Eddy                    | Lady Bird Lake  | Lake             | 10               | 169                   | 1991-12-30T00:00:00 | 2010-03-25T00:00:00    | F        | F        | 
| 100            | Hebbingston Hollow Trib @ Barton Creek (HHT)  | Barton Creek    | Stream           | 11               | 138                   | 1994-01-06T00:00:00 | 2001-05-01T00:00:00    | F        | F        | 
| 1000           | Buttercup Branch Creek Upstream of Springdale | Buttercup Creek | Stream           | 1                | 98                    | 1997-07-08T00:00:00 | 1997-07-08T00:00:00    | F        | F        | 
| 10000          | ISMP Walter E. Long 353                       | Decker Creek    | Vegetation Patch | 1                | 48                    | 2013-07-25T00:00:00 | 2013-07-25T00:00:00    | F        | F        | 
| 10002          | ISMP Walter E. Long 355                       | Decker Creek    | Vegetation Patch | 1                | 48                    | 2013-07-26T00:00:00 | 2013-07-26T00:00:00    | F        | F        | 
| 10004          | ISMP Walter E. Long 357                       | Decker Creek    | Vegetation Patch | 1                | 48                    | 2013-07-26T00:00:00 | 2013-07-26T00:00:00    | F        | F        | 
| 10006          | ISMP Walter E. Long 359                       | Decker Creek    | Vegetation Patch | 2                | 96                    | 2013-08-14T00:00:00 | 2013-08-29T00:00:00    | F        | F        | 
| 10008          | ISMP Walter E. Long 361                       | Decker Creek    | Vegetation Patch | 1                | 48                    | 2013-07-24T00:00:00 | 2013-07-24T00:00:00    | F        | F        | 
| 1001           | Unnamed Tributary @ Cedarcliffe Dr.           | Bull Creek      | Stream           | 1                | 75                    | 1997-06-27T00:00:00 | 1997-06-27T00:00:00    | F        | F        | 
| 10011          | ISMP Walter E. Long 364                       | Decker Creek    | Vegetation Patch | 1                | 48                    | 2013-07-20T00:00:00 | 2013-07-20T00:00:00    | F        | F        | 
```