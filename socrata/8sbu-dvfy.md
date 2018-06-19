# Cultural & Special Events at El Pueblo Historical Monument

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cultural-special-events-at-el-pueblo-historical-monument) |
| Metadata | [Link](https://data.lacity.org/api/views/8sbu-dvfy) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/8sbu-dvfy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/8sbu-dvfy/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 8sbu-dvfy |
| Name | Cultural & Special Events at El Pueblo Historical Monument |
| Attribution | El Pueblo Historical Monument |
| Category | A Livable and Sustainable City |
| Tags | events, culture |
| Created | 2014-05-30T00:42:21Z |
| Publication Date | 2017-03-20T22:44:13Z |

## Description

Number and type of events at El Pueblo

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | time           | date_of_event                 | Date of Event                 | calendar_date | calendar_date |
| Yes      | series tag     | event_name                    | Event Name                    | text          | text          |
| Yes      | numeric metric | estimated_number_of_attendees | Estimated Number of Attendees | number        | number        |
| Yes      | numeric metric | production_days               | Production Days               | number        | number        |
```

## Time Field

```ls
Value = date_of_event
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8sbu-dvfy d:2014-02-02T00:00:00.000Z t:event_name="La Candelaria" m:estimated_number_of_attendees=300 m:production_days=1

series e:8sbu-dvfy d:2014-02-19T00:00:00.000Z t:event_name="Chinese American Museum" m:estimated_number_of_attendees=50 m:production_days=1

series e:8sbu-dvfy d:2014-03-04T00:00:00.000Z t:event_name="Children's Mardi Gras" m:estimated_number_of_attendees=150 m:production_days=1
```

## Meta Commands

```ls
metric m:estimated_number_of_attendees p:integer l:"Estimated Number of Attendees" t:dataTypeName=number

metric m:production_days p:integer l:"Production Days" t:dataTypeName=number

entity e:8sbu-dvfy l:"Cultural & Special Events at El Pueblo Historical Monument" t:attribution="El Pueblo Historical Monument" t:url=https://data.lacity.org/api/views/8sbu-dvfy

property e:8sbu-dvfy t:meta.view v:id=8sbu-dvfy v:category="A Livable and Sustainable City" v:attributionLink=http://elpueblo.lacity.org/index.htm v:averageRating=0 v:name="Cultural & Special Events at El Pueblo Historical Monument" v:attribution="El Pueblo Historical Monument"

property e:8sbu-dvfy t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8sbu-dvfy t:meta.view.owner v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:displayName="El Pueblo OpenData"

property e:8sbu-dvfy t:meta.view.tableauthor v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:roleName=publisher v:displayName="El Pueblo OpenData"
```

## Top Records

```ls
| date_of_event       | event_name                                     | estimated_number_of_attendees | production_days | 
| =================== | ============================================== | ============================= | =============== | 
| 2014-02-02T00:00:00 | La Candelaria                                  | 300                           | 1               | 
| 2014-02-19T00:00:00 | Chinese American Museum                        | 50                            | 1               | 
| 2014-03-04T00:00:00 | Children's Mardi Gras                          | 150                           | 1               | 
| 2014-02-16T00:00:00 | Cuauhtemoc Celebration                         | 300                           | 1               | 
| 2014-02-16T00:00:00 | Mexican Cultural Institute - Danzon            | 100                           | 1               | 
| 2014-02-20T00:00:00 | Western National Parks Assoc. Reception        | 70                            | 1               | 
| 2014-02-21T00:00:00 | Assemblyman Gomez - Business Leaders Breakfast | 30                            | 1               | 
| 2014-02-23T00:00:00 | Cuauhtemoc Celebration                         | 350                           | 1               | 
| 2014-03-09T00:00:00 | Mexican Cultural Institute - Danzon            | 175                           | 1               | 
| 2014-03-13T00:00:00 | Covered California                             | 150                           | 1               | 
```