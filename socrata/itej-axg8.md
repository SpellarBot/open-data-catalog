# Cook County Cooling Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-cooling-centers) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/itej-axg8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/itej-axg8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/itej-axg8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | itej-axg8 |
| Name | Cook County Cooling Centers |
| Attribution | Cook County Department of Homeland Security and Emergency Management |
| Created | 2016-07-19T18:06:19Z |
| Publication Date | 2016-07-19T19:13:18Z |

## Description

Residents who do not have access to air conditioning are encouraged to take advantage of cooling centers throughout Cook County.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | township_village   | Township/Village   | text      | text        |
| Yes      | series tag  | hours_of_operation | Hours of Operation | text      | text        |
| No       |             | address            | Address            | text      | text        |
| Yes      | series tag  | city               | City               | text      | text        |
| Yes      | series tag  | transportation     | Transportation     | text      | text        |
| Yes      | series tag  | office_number      | Office Number      | text      | text        |
| Yes      | series tag  | after_hours_number | After Hours Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:itej-axg8 d:2016-07-19T12:10:35.000Z t:office_number=708-788-2660 t:after_hours_number=708-795-5600 t:hours_of_operation="9am-9pm M-F, 9am-6pm Sat, 9am-5pm sun" t:township_village="Berwyn Township" t:transportation=No t:city=Berwyn m:row_number.itej-axg8=1

series e:itej-axg8 d:2016-07-19T12:10:35.000Z t:office_number=708-795-2150 t:after_hours_number=708-795-5600 t:hours_of_operation=24/7 t:township_village="Berwyn Township" t:transportation=No t:city=Berwyn m:row_number.itej-axg8=2

series e:itej-axg8 d:2016-07-19T12:10:35.000Z t:office_number=708-754-9400 t:after_hours_number=708-756-6400 t:hours_of_operation="8:30am-4:30 pm M-F" t:township_village="Bloom Township" t:transportation=No t:city="Chicago Heights" m:row_number.itej-axg8=3
```

## Meta Commands

```ls
metric m:row_number.itej-axg8 p:long l:"Row Number"

entity e:itej-axg8 l:"Cook County Cooling Centers" t:attribution="Cook County Department of Homeland Security and Emergency Management" t:url=https://datacatalog.cookcountyil.gov/api/views/itej-axg8

property e:itej-axg8 t:meta.view v:id=itej-axg8 v:averageRating=0 v:name="Cook County Cooling Centers" v:attribution="Cook County Department of Homeland Security and Emergency Management"

property e:itej-axg8 t:meta.view.license v:name="Public Domain"

property e:itej-axg8 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:itej-axg8 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | township_village | hours_of_operation                    | address                                        | city            | transportation                                                 | office_number | after_hours_number | 
| =========== | ================ | ===================================== | ============================================== | =============== | ============================================================== | ============= | ================== | 
| 1468930235  | Berwyn Township  | 9am-9pm M-F, 9am-6pm Sat, 9am-5pm sun | 2701 S Harlem (Library)                        | Berwyn          | No                                                             | 708-788-2660  | 708-795-5600       | 
| 1468930235  | Berwyn Township  | 24/7                                  | 6401 W 31st St (Police Department)             | Berwyn          | No                                                             | 708-795-2150  | 708-795-5600       | 
| 1468930235  | Bloom Township   | 8:30am-4:30 pm M-F                    | 425 S Halsted (Village Building)               | Chicago Heights | No                                                             | 708-754-9400  | 708-756-6400       | 
| 1468930235  | Bremen Township  | 9am-3pm M-F                           | 15350 S Oak Park (Community Center)            | Oak Forest      | No                                                             | 708-333-9530  | 708-687-1376       | 
| 1468930235  | Bremen Township  | 9am-5pm M-F                           | 16361 S Kedzie Parkway (Administrative Office) | Markham         | No                                                             | 708-333-9530  | 708-687-1376       | 
| 1468930235  | Calumet Township | 8am-4pm M-F                           | 12633 Ashland (Community Center)               | Calumet Park    | Yes- call 708-388-6606 and contact transit (8:30am-3:30pm M-F) | 708-388-6606  | 708-385-0264       | 
| 1468930235  | Cicero Township  | 8am-8pm M-F                           | 4949 W Cermak (Village Building)               | Cicero          |                                                                | 708-656-3600  | 708-652-2130       | 
| 1468930235  | Cicero Township  | 8pm-8am M-F, 24/7 Sa-Sun              | 4901 W Cermak (Police Office)                  | Cicero          |                                                                | 708-656-3600  | 708-652-2130       | 
| 1468930235  | Cicero Township  | 8am-8pm M-F                           | 5410 W 34th St (Public Safety Building)        | Cicero          |                                                                | 708-656-3600  | 708-652-2130       | 
| 1468930235  | Cicero Township  | 8am-8pm M-F                           | 2250 S 49th Ave (Community Center)             | Cicero          |                                                                | 708-656-3600  | 708-652-2130       | 
```