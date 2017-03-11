# Community Board Appointments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-board-appointments-699cb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3gkd-ddzn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3gkd-ddzn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3gkd-ddzn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3gkd-ddzn |
| Name | Community Board Appointments |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | community board appointments, mbp, manhattan borough president (mbp) |
| Created | 2014-03-06T17:40:48Z |
| Publication Date | 2014-03-06T17:41:51Z |
| Rows Updated | 2014-03-06T17:40:58Z |

## Description

This list contains information on community board appointments.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | numeric metric | community_board_number        | Community Board Number        | number    | number      |
| Yes      | series tag     | chair                         | Chair                         | text      | text        |
| Yes      | series tag     | district_manager              | District Manager              | text      | text        |
| Yes      | series tag     | board_meeting_cabinet_meeting | Board Meeting/Cabinet Meeting | text      | text        |
| Yes      | series tag     | location_2                    | Location 2                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3gkd-ddzn d:2014-03-06T09:40:58.000Z t:chair="Georgette Morgan-Thomas" t:district_manager="Eutha R. Prince" t:board_meeting_cabinet_meeting="Third Thursday, 6:30 PM" m:community_board_number=9

series e:3gkd-ddzn d:2014-03-06T09:40:58.000Z t:chair="Mark N. Diller" t:district_manager="Penny Ryan" t:board_meeting_cabinet_meeting="First Tuesday, 6:30PM" m:community_board_number=7

series e:3gkd-ddzn d:2014-03-06T09:40:58.000Z t:chair="Henrietta Lyle" t:location_2="4th floor" t:district_manager="Christopher T. Wooley" t:board_meeting_cabinet_meeting="First Wednesday, 6PM" m:community_board_number=10
```

## Meta Commands

```ls
metric m:community_board_number p:integer l:"Community Board Number" t:dataTypeName=number

entity e:3gkd-ddzn l:"Community Board Appointments" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/3gkd-ddzn

property e:3gkd-ddzn t:meta.view d:2017-03-10T14:25:08.994Z v:id=3gkd-ddzn v:category="City Government" v:averageRating=0 v:name="Community Board Appointments" v:attribution="Manhattan Borough President (MBP)"

property e:3gkd-ddzn t:meta.view.owner d:2017-03-10T14:25:08.994Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:3gkd-ddzn t:meta.view.tableauthor d:2017-03-10T14:25:08.994Z v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```