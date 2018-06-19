# West Seattle ridership monthly, by year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/west-seattle-ridership-monthly-by-year-a0e6d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fchw-7nhb) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fchw-7nhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fchw-7nhb/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fchw-7nhb |
| Name | West Seattle ridership monthly, by year |
| Attribution | King County Ferry District |
| Category | Transportation |
| Tags | west seattle water taxi, ridership, king county ferry district, passenger, ferry |
| Created | 2012-05-21T19:41:32Z |
| Publication Date | 2014-02-14T21:41:41Z |

## Description

King County Ferry District, West Seattle ridership monthly, by year

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| No       | time           | :updated_at                       | updated_at                        | meta_data | meta_data   |
| No       |                | _1                                | Month                             | text      | text        |
| Yes      | numeric metric | passengers_1                      | 2011                              | number    | number      |
| Yes      | numeric metric | passengers_2                      | 2012                              | number    | number      |
| Yes      | numeric metric | 2013                              | 2013                              | number    | number      |
| Yes      | numeric metric | percent_change_from_previous_year | Percent change from previous year | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1
```

## Data Commands

```ls
series e:fchw-7nhb d:2013-11-14T16:55:03.000Z m:passengers_2=6304 m:passengers_1=8714

series e:fchw-7nhb d:2013-11-14T16:55:58.000Z m:2013=8067 m:percent_change_from_previous_year=0 m:passengers_2=8037 m:passengers_1=2733

series e:fchw-7nhb d:2013-11-14T16:56:03.000Z m:2013=7188 m:percent_change_from_previous_year=-18.7 m:passengers_2=8837 m:passengers_1=2569
```

## Meta Commands

```ls
metric m:passengers_1 p:integer l:2011 t:dataTypeName=number

metric m:passengers_2 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:percent_change_from_previous_year p:float l:"Percent change from previous year" t:dataTypeName=percent

entity e:fchw-7nhb l:"West Seattle ridership monthly, by year" t:attribution="King County Ferry District" t:url=https://data.kingcounty.gov/api/views/fchw-7nhb

property e:fchw-7nhb t:meta.view v:id=fchw-7nhb v:category=Transportation v:attributionLink=http://www.kingcounty.gov/transportation/kcdot/WaterTaxi.aspx v:averageRating=0 v:name="West Seattle ridership monthly, by year" v:attribution="King County Ferry District"

property e:fchw-7nhb t:meta.view.license v:name="Public Domain"

property e:fchw-7nhb t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:fchw-7nhb t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | _1    | passengers_1 | passengers_2 | 2013  | percent_change_from_previous_year | 
| =========== | ===== | ============ | ============ | ===== | ================================= | 
| 1384448103  | Dec.  | 8714         | 6304         |       |                                   | 
| 1384448158  | Jan.  | 2733         | 8037         | 8067  | 0                                 | 
| 1384448163  | Feb.  | 2569         | 8837         | 7188  | -18.7                             | 
| 1384448169  | March | 2745         | 9371         | 8666  | -7.5                              | 
| 1384448181  | April | 10335        | 18468        | 15894 | -13.9                             | 
| 1384448185  | May   | 17367        | 25564        | 26129 | 2.2                               | 
| 1384448188  | June  | 28202        | 26633        | 36076 | 35.5                              | 
| 1384448192  | July  | 38417        | 41716        | 47588 | 14.1                              | 
| 1384448196  | Aug.  | 41157        | 44225        | 45336 | 2.5                               | 
| 1392385244  | Sep.  | 28912        | 31775        | 26984 | -15.1                             | 
```