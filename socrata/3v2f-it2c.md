# Vashon ridership monthly

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vashon-ridership-monthly-6e7d7) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/3v2f-it2c) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/3v2f-it2c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/3v2f-it2c/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 3v2f-it2c |
| Name | Vashon ridership monthly |
| Attribution | King County Ferry District |
| Category | Transportation |
| Tags | ferry, vashon, passengers |
| Created | 2012-05-21T18:17:46Z |
| Publication Date | 2014-02-14T21:38:31Z |

## Description

King County Ferry District, monthly ridership on Vashon Island ferry

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                         | Data Type | Render Type |
| ======== | ============== | ============== | ============================ | ========= | =========== |
| No       | time           | :updated_at    | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | month          | Month                        | text      | text        |
| No       |                | _1             | 2011                         | number    | number      |
| No       |                | _2             | 2012                         | number    | number      |
| Yes      | numeric metric | 2013           | 2013                         | number    | number      |
| Yes      | numeric metric | percent_change | Percent change for this year | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2
```

## Data Commands

```ls
series e:3v2f-it2c d:2013-11-14T16:52:20.000Z t:month=Jan. m:2013=16397 m:percent_change=27.9

series e:3v2f-it2c d:2013-11-14T16:52:24.000Z t:month=Feb. m:2013=16397 m:percent_change=0.9

series e:3v2f-it2c d:2013-11-14T16:52:28.000Z t:month=March m:2013=15654 m:percent_change=2.1
```

## Meta Commands

```ls
metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:percent_change p:float l:"Percent change for this year" d:"Difference between this year and last" t:dataTypeName=percent

entity e:3v2f-it2c l:"Vashon ridership monthly" t:attribution="King County Ferry District" t:url=https://data.kingcounty.gov/api/views/3v2f-it2c

property e:3v2f-it2c t:meta.view v:id=3v2f-it2c v:category=Transportation v:attributionLink=http://www.kingcounty.gov/transportation/kcdot/WaterTaxi.aspx v:averageRating=0 v:name="Vashon ridership monthly" v:attribution="King County Ferry District"

property e:3v2f-it2c t:meta.view.license v:name="Public Domain"

property e:3v2f-it2c t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:3v2f-it2c t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | month | _1    | _2    | 2013  | percent_change | 
| =========== | ===== | ===== | ===== | ===== | ============== | 
| 1384447846  | Dec.  | 12405 | 12514 |       |                | 
| 1384447940  | Jan.  | 13810 | 12820 | 16397 | 27.9           | 
| 1384447944  | Feb.  | 11996 | 14130 | 16397 | 0.9            | 
| 1384447948  | March | 15083 | 15330 | 15654 | 2.1            | 
| 1384447951  | April | 13414 | 14835 | 16526 | 11.4           | 
| 1384447957  | May   | 14087 | 15604 | 16735 | 7.2            | 
| 1384447961  | June  | 14487 | 14989 | 15199 | 1.4            | 
| 1384447965  | July  | 13887 | 15150 | 17547 | 15.8           | 
| 1392385052  | Aug.  | 15681 | 16392 | 16880 | 3              | 
| 1392385078  | Sep.  | 14082 | 13994 | 15197 | 8.6            | 
```