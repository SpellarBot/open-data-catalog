# Partners in Preparedness

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oem-partners-in-preparedness-c3f0e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h4jn-x3ty) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h4jn-x3ty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h4jn-x3ty/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h4jn-x3ty |
| Name | Partners in Preparedness |
| Attribution | Office of Emergency Management (OEM) |
| Category | Social Services |
| Tags | oem, emergency, management, services, preparedness |
| Created | 2013-02-26T19:48:20Z |
| Publication Date | 2016-08-01T17:00:02Z |

## Description

List of orgarnizations who have completed the necessary Emergency Preparedness tasks

## Columns

```ls
| Included | Schema Type | Field Name  | Name                     | Data Type | Render Type |
| ======== | =========== | =========== | ======================== | ========= | =========== |
| No       | time        | :updated_at | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | partner     | Partners in Preparedness | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h4jn-x3ty d:2016-08-01T09:59:07.000Z t:partner=AIG m:row_number.h4jn-x3ty=1

series e:h4jn-x3ty d:2016-08-01T09:59:07.000Z t:partner="Alliance for Downtown New York Inc." m:row_number.h4jn-x3ty=2

series e:h4jn-x3ty d:2016-08-01T09:59:07.000Z t:partner="Amber Court of Brooklyn" m:row_number.h4jn-x3ty=3
```

## Meta Commands

```ls
metric m:row_number.h4jn-x3ty p:long l:"Row Number"

entity e:h4jn-x3ty l:"Partners in Preparedness" t:attribution="Office of Emergency Management (OEM)" t:url=https://data.cityofnewyork.us/api/views/h4jn-x3ty

property e:h4jn-x3ty t:meta.view v:id=h4jn-x3ty v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/oem/html/get_prepared/prepared_partnersinprep_list.shtml v:averageRating=0 v:name="Partners in Preparedness" v:attribution="Office of Emergency Management (OEM)"

property e:h4jn-x3ty t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h4jn-x3ty t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | partner                                                    | 
| =========== | ========================================================== | 
| 1470045547  | AIG                                                        | 
| 1470045547  | Alliance for Downtown New York Inc.                        | 
| 1470045547  | Amber Court of Brooklyn                                    | 
| 1470045547  | American Eagle Force - SERT                                | 
| 1470045547  | APG Asset Management Us Inc.                               | 
| 1470045547  | Association of Black Social Workers Senior Citizens Center | 
| 1470045547  | Association to Benefit Children                            | 
| 1470045547  | Bank of America                                            | 
| 1470045547  | Baruch College                                             | 
| 1470045547  | Black Shield Armed Guard Corporation                       | 
```