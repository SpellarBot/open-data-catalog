# Parking Garage Space Availability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-garage-space-availability-73662) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qahs-fevu) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qahs-fevu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qahs-fevu/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qahs-fevu |
| Name | Parking Garage Space Availability |
| Category | Transportation |
| Tags | parking, garage, space available, cehicle counting, public facility |
| Created | 2013-08-07T13:47:10Z |
| Publication Date | 2013-11-13T18:35:23Z |

## Description

This dataset includes parking spaces availability for Montgomery County Public Parking Facilities. This dataset only includes facilities that are equipped with vehicle counting systems.

Update frequency:  Every few minutes

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type     | Render Type   |
| ======== | ============== | ============== | =============== | ============= | ============= |
| Yes      | series tag     | facilitynumber | Facility Number | text          | text          |
| Yes      | numeric metric | space_count    | Space Count     | number        | number        |
| Yes      | numeric metric | total_spaces   | Total Spaces    | number        | number        |
| Yes      | time           | asofdatetime   | Last Update     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = asofdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qahs-fevu d:2017-04-21T04:32:58.000Z t:facilitynumber="GAR 31" m:total_spaces=955 m:space_count=702

series e:qahs-fevu d:2017-04-21T04:32:58.000Z t:facilitynumber="GAR 61" m:total_spaces=1251 m:space_count=1028

series e:qahs-fevu d:2017-04-21T04:32:58.000Z t:facilitynumber="GAR 57" m:total_spaces=926 m:space_count=909
```

## Meta Commands

```ls
metric m:space_count p:integer l:"Space Count" d:"The total number of parking spaces available within the facility." t:dataTypeName=number

metric m:total_spaces p:integer l:"Total Spaces" d:"The total number of vehicle parking spaces within the facility" t:dataTypeName=number

entity e:qahs-fevu l:"Parking Garage Space Availability" t:url=https://data.montgomerycountymd.gov/api/views/qahs-fevu

property e:qahs-fevu t:meta.view v:id=qahs-fevu v:category=Transportation v:averageRating=0 v:name="Parking Garage Space Availability"

property e:qahs-fevu t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:qahs-fevu t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| facilitynumber | space_count | total_spaces | asofdatetime        | 
| ============== | =========== | ============ | =================== | 
| GAR 31         | 702         | 955          | 2017-04-21T04:32:58 | 
| GAR 61         | 1028        | 1251         | 2017-04-21T04:32:58 | 
| GAR 57         | 909         | 926          | 2017-04-21T04:32:58 | 
| GAR 60         | 1380        | 1648         | 2017-04-21T04:32:58 | 
```