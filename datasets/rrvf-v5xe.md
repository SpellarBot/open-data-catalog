# Power Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/power-plants) |
| Metadata | [Link](https://data.austintexas.gov/api/views/rrvf-v5xe) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/rrvf-v5xe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/rrvf-v5xe/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | rrvf-v5xe |
| Name | Power Plants |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | power plants, power, energy |
| Created | 2016-09-30T13:19:21Z |
| Publication Date | 2016-10-27T16:53:07Z |

## Description

Austin Energy generates power through a diverse generation portfolio of natural gas, coal, nuclear, renewable resources and purchased power. Browse data about our power plants: percent owned; fuel type used; capacity in MW; and installation year. Go to http://austinenergy.com/go/info to learn more.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type | Render Type |
| ======== | ============== | ======================== | ========================== | ========= | =========== |
| Yes      | series tag     | power_plant              | Power Plant                | text      | text        |
| Yes      | series tag     | unit                     | Unit                       | text      | text        |
| Yes      | series tag     | fuel                     | Fuel                       | text      | text        |
| Yes      | numeric metric | summer_rated_capacity_mw | Summer Rated Capacity (MW) | number    | number      |
| Yes      | time           | year_installed           | Year Installed             | number    | number      |
```

## Time Field

```ls
Value = year_installed
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rrvf-v5xe d:1979-01-01T00:00:00.000Z t:unit="Unit 1" t:fuel=Coal t:power_plant="Fayette Power Project (50% Share)" m:summer_rated_capacity_mw=302

series e:rrvf-v5xe d:1980-01-01T00:00:00.000Z t:unit="Unit 2" t:fuel=Coal t:power_plant="Fayette Power Project (50% Share)" m:summer_rated_capacity_mw=300

series e:rrvf-v5xe d:1970-01-01T00:00:00.000Z t:unit="Unit 1" t:fuel=Gas t:power_plant="Decker Creek Power Station" m:summer_rated_capacity_mw=315
```

## Meta Commands

```ls
metric m:summer_rated_capacity_mw p:double l:"Summer Rated Capacity (MW)" t:dataTypeName=number

entity e:rrvf-v5xe l:"Power Plants" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/rrvf-v5xe

property e:rrvf-v5xe t:meta.view v:id=rrvf-v5xe v:category=Utility v:averageRating=0 v:name="Power Plants" v:attribution="Austin Energy"

property e:rrvf-v5xe t:meta.view.license v:name="Public Domain"

property e:rrvf-v5xe t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:rrvf-v5xe t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| power_plant                       | unit                     | fuel    | summer_rated_capacity_mw | year_installed | 
| ================================= | ======================== | ======= | ======================== | ============== | 
| Fayette Power Project (50% Share) | Unit 1                   | Coal    | 302                      | 1979           | 
| Fayette Power Project (50% Share) | Unit 2                   | Coal    | 300                      | 1980           | 
| Decker Creek Power Station        | Unit 1                   | Gas     | 315                      | 1970           | 
| Decker Creek Power Station        | Unit 2                   | Gas     | 420                      | 1977           | 
| Decker Creek Power Station        | Unit 1-4 (Gas Turbines)  | Gas     | 192                      | 1988           | 
| Sand Hill Energy Center           | Units 1-4 (Gas Turbines) | Gas     | 180                      | 2001           | 
| Sand Hill Energy Center           | Units 6-7 (Gas Turbines) | Gas     | 90                       | 2010           | 
| Sand Hill Energy Center           | Unit 5 (Combined Cycle)  | Gas     | 300                      | 2004           | 
| South Texas Project (16% Share)   | Unit 1                   | Nuclear | 218                      | 1988           | 
| South Texas Project (16% Share)   | Unit 2                   | Nuclear | 218                      | 1989           | 
```