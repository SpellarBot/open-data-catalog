# Hearings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hearings) |
| Metadata | [Link](https://data.austintexas.gov/api/views/s7dz-xhcs) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/s7dz-xhcs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/s7dz-xhcs/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | s7dz-xhcs |
| Name | Hearings |
| Category | Utility |
| Tags | hearing, account reconciliation, water, electric, wastewater, waste |
| Created | 2016-09-06T17:41:43Z |
| Publication Date | 2016-10-17T18:02:01Z |

## Description

The City of Austin provides hearings for customers who would like the opportunity to dispute charges or are in need of any other type of account reconciliation. The hearings are conducted by an impartial Hearing Officer retained by the City of Austin.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | calendar_year_2    | Calendar Year      | calendar_date | calendar_date |
| Yes      | series tag     | category           | Category           | text          | text          |
| Yes      | numeric metric | number_of_hearings | Number of Hearings | number        | number        |
```

## Time Field

```ls
Value = calendar_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s7dz-xhcs d:2006-01-01T00:00:00.000Z t:category=Electric m:number_of_hearings=45

series e:s7dz-xhcs d:2007-01-01T00:00:00.000Z t:category=Electric m:number_of_hearings=64

series e:s7dz-xhcs d:2008-01-01T00:00:00.000Z t:category=Electric m:number_of_hearings=62
```

## Meta Commands

```ls
metric m:number_of_hearings p:integer l:"Number of Hearings" t:dataTypeName=number

entity e:s7dz-xhcs l:Hearings t:url=https://data.austintexas.gov/api/views/s7dz-xhcs

property e:s7dz-xhcs t:meta.view v:id=s7dz-xhcs v:category=Utility v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name=Hearings

property e:s7dz-xhcs t:meta.view.license v:name="Public Domain"

property e:s7dz-xhcs t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:s7dz-xhcs t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| calendar_year_2     | category          | number_of_hearings | 
| =================== | ================= | ================== | 
| 2006-01-01T00:00:00 | Electric          | 45                 | 
| 2007-01-01T00:00:00 | Electric          | 64                 | 
| 2008-01-01T00:00:00 | Electric          | 62                 | 
| 2009-01-01T00:00:00 | Electric          | 33                 | 
| 2010-01-01T00:00:00 | Electric          | 23                 | 
| 2011-01-01T00:00:00 | Electric          | 59                 | 
| 2012-01-01T00:00:00 | Electric          | 47                 | 
| 2006-01-01T00:00:00 | Water/ Wastewater | 20                 | 
| 2007-01-01T00:00:00 | Water/ Wastewater | 21                 | 
| 2008-01-01T00:00:00 | Water/ Wastewater | 16                 | 
```