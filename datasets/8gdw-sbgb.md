# DNR-WPP-Boil Order Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dnr-wpp-boil-order-report) |
| Metadata | [Link](https://data.mo.gov/api/views/8gdw-sbgb) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/8gdw-sbgb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/8gdw-sbgb/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 8gdw-sbgb |
| Name | DNR-WPP-Boil Order Report |
| Attribution | Department of Natural Resources |
| Category | Regulatory |
| Created | 2015-12-18T20:25:43Z |
| Publication Date | 2017-04-20T21:10:01Z |

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | time        | issue_date             | Issue Date             | calendar_date | calendar_date |
| Yes      | series tag  | pws_id                 | PWS ID#                | text          | text          |
| Yes      | series tag  | system_name            | System Name            | text          | text          |
| Yes      | series tag  | location               | Location               | text          | text          |
| Yes      | series tag  | county                 | County                 | text          | text          |
| Yes      | series tag  | contaminant_of_concern | Contaminant of Concern | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8gdw-sbgb d:2015-07-03T00:00:00.000Z t:county=Jefferson t:location="Hwy 61/67, Barnhart - N of Festus" t:system_name="Wolff's Softball Haven" t:contaminant_of_concern="Fecal Coliform/E.Coli" t:pws_id=MO6203139 m:row_number.8gdw-sbgb=1

series e:8gdw-sbgb d:2016-06-17T00:00:00.000Z t:county=Pulaski t:location="Laney Road/Lynwood Road, St. Robert - N of St. Robert" t:system_name="Ridge Creek Water Company LLC" t:contaminant_of_concern="History of E.Coli/No Treatment" t:pws_id=MO4031631 m:row_number.8gdw-sbgb=2

series e:8gdw-sbgb d:2016-09-02T00:00:00.000Z t:county=Benton t:location="Panorama Road, Warsaw - NW of Warsaw" t:system_name="Winegars Teal Bend Subdivision" t:contaminant_of_concern="Low Pressure" t:pws_id=MO3036121 m:row_number.8gdw-sbgb=3
```

## Meta Commands

```ls
metric m:row_number.8gdw-sbgb p:long l:"Row Number"

entity e:8gdw-sbgb l:"DNR-WPP-Boil Order Report" t:attribution="Department of Natural Resources" t:url=https://data.mo.gov/api/views/8gdw-sbgb

property e:8gdw-sbgb t:meta.view v:id=8gdw-sbgb v:category=Regulatory v:attributionLink=http://dnr.mo.gov/env/wpp/boil/ v:averageRating=0 v:name="DNR-WPP-Boil Order Report" v:attribution="Department of Natural Resources"

property e:8gdw-sbgb t:meta.view.owner v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:displayName="Renee Wright"

property e:8gdw-sbgb t:meta.view.tableauthor v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:roleName=editor v:displayName="Renee Wright"
```

## Top Records

```ls
| issue_date          | pws_id    | system_name                    | location                                              | county    | contaminant_of_concern         | 
| =================== | ========= | ============================== | ===================================================== | ========= | ============================== | 
| 2015-07-03T00:00:00 | MO6203139 | Wolff's Softball Haven         | Hwy 61/67, Barnhart - N of Festus                     | Jefferson | Fecal Coliform/E.Coli          | 
| 2016-06-17T00:00:00 | MO4031631 | Ridge Creek Water Company LLC  | Laney Road/Lynwood Road, St. Robert - N of St. Robert | Pulaski   | History of E.Coli/No Treatment | 
| 2016-09-02T00:00:00 | MO3036121 | Winegars Teal Bend Subdivision | Panorama Road, Warsaw - NW of Warsaw                  | Benton    | Low Pressure                   | 
| 2017-01-18T00:00:00 | MO3048127 | Woodcrest MHP                  | Woodcrest Circle, Rolla - N of Rolla                  | Phelps    | Low Pressure                   | 
| 2017-04-20T00:00:00 | MO6048200 | A & H Country Estates Inc      | 6118 Jo Drive, House Springs - SW of St. Louis        | Jefferson | Inadequate Operation           | 
```