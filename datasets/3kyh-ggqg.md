# Solar On City Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solar-on-city-facilities) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3kyh-ggqg) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3kyh-ggqg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3kyh-ggqg/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3kyh-ggqg |
| Name | Solar On City Facilities |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | solar, energy, electric |
| Created | 2016-10-10T17:04:58Z |
| Publication Date | 2016-11-14T21:39:08Z |

## Description

Austin Energy has installed solar projects on municipal facilities such as City Hall, libraries, and recreation centers to increase public awareness about solar power and demonstrate the effectiveness of this technology. View the location name, address, year installed, and system size in kW. Go to austinenergy.com/go/solar to learn more about solar solutions from Austin Energy.

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type     | Render Type   |
| ======== | ============== | ========== | ===== | ============= | ============= |
| Yes      | numeric metric | kw_ac      | kW AC | number        | number        |
| Yes      | series tag     | name       | Name  | text          | text          |
| Yes      | time           | year       | Year  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3kyh-ggqg d:2006-01-01T00:00:00.000Z t:name="Southeast Austin Community Branch Library" m:kw_ac=3.08

series e:3kyh-ggqg d:2008-01-01T00:00:00.000Z t:name="Far North Health Center" m:kw_ac=4.62

series e:3kyh-ggqg d:2010-01-01T00:00:00.000Z t:name="51st Street Water Tower / Fire Vehicle Maintenance Shop" m:kw_ac=6.47
```

## Meta Commands

```ls
metric m:kw_ac p:float l:"kW AC" t:dataTypeName=number

entity e:3kyh-ggqg l:"Solar On City Facilities" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/3kyh-ggqg

property e:3kyh-ggqg t:meta.view v:id=3kyh-ggqg v:category=Utility v:averageRating=0 v:name="Solar On City Facilities" v:attribution="Austin Energy"

property e:3kyh-ggqg t:meta.view.license v:name="Public Domain"

property e:3kyh-ggqg t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:3kyh-ggqg t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| kw_ac | name                                                    | year                | 
| ===== | ======================================================= | =================== | 
| 3.08  | Southeast Austin Community Branch Library               | 2006-01-01T00:00:00 | 
| 4.62  | Far North Health Center                                 | 2008-01-01T00:00:00 | 
| 6.47  | 51st Street Water Tower / Fire Vehicle Maintenance Shop | 2010-01-01T00:00:00 | 
| 77    | Austin Bergstrom International Airport                  | 1998-01-01T00:00:00 | 
| 3.08  | Dove Springs Recreation Center                          | 2006-01-01T00:00:00 | 
| 3.08  | Lorraine "Grandma" Camacho Activity Center              | 2006-01-01T00:00:00 | 
| 2.31  | Fire Station # 27                                       | 2008-01-01T00:00:00 | 
| 27.72 | Austin Convention Center #2                             | 2001-01-01T00:00:00 | 
| 8.32  | Howson Branch Library                                   | 2000-01-01T00:00:00 | 
| 24.64 | Taxi Staging Area Solar Shade                           | 2000-01-01T00:00:00 | 
```