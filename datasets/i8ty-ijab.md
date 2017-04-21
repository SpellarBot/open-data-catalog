# Purchase Power Agreements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/renewable-resources) |
| Metadata | [Link](https://data.austintexas.gov/api/views/i8ty-ijab) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/i8ty-ijab/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/i8ty-ijab/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | i8ty-ijab |
| Name | Purchase Power Agreements |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | power, renewable resources, austin energy, energy |
| Created | 2016-08-02T16:02:25Z |
| Publication Date | 2017-04-19T15:39:13Z |

## Description

View the unit names, fuel types, and more starting in 1995. Go to http://austinenergy.com/go/renewablepower to learn more.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| Yes      | series tag     | unit_name             | Unit Name               | text      | text        |
| Yes      | series tag     | fuel_type             | Fuel Type               | text      | text        |
| Yes      | numeric metric | installed_capacity_mw | Installed Capacity (MW) | number    | number      |
| Yes      | time           | year_installed        | Year Installed          | number    | number      |
| No       |                | expiration_date       | Expiration Date         | text      | number      |
| Yes      | series tag     | location              | Location                | text      | text        |
```

## Time Field

```ls
Value = year_installed
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:i8ty-ijab d:2005-01-01T00:00:00.000Z t:fuel_type=Wind t:location="Nolan, TX" t:unit_name="Sweetwater 3" m:installed_capacity_mw=34.5

series e:i8ty-ijab d:2007-01-01T00:00:00.000Z t:fuel_type=Wind t:location="Floyd, TX" t:unit_name=Whirlwind m:installed_capacity_mw=59.8

series e:i8ty-ijab d:2008-01-01T00:00:00.000Z t:fuel_type=Wind t:location="Shackelford, TX" t:unit_name=Hackberry m:installed_capacity_mw=165.6
```

## Meta Commands

```ls
metric m:installed_capacity_mw p:float l:"Installed Capacity (MW)" t:dataTypeName=number

entity e:i8ty-ijab l:"Purchase Power Agreements" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/i8ty-ijab

property e:i8ty-ijab t:meta.view v:id=i8ty-ijab v:category=Utility v:averageRating=0 v:name="Purchase Power Agreements" v:attribution="Austin Energy"

property e:i8ty-ijab t:meta.view.license v:name="Public Domain"

property e:i8ty-ijab t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:i8ty-ijab t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| unit_name         | fuel_type | installed_capacity_mw | year_installed | expiration_date | location                           | 
| ================= | ========= | ===================== | ============== | =============== | ================================== | 
| Sweetwater 3      | Wind      | 34.5                  | 2005           | 2017            | Nolan, TX                          | 
| Whirlwind         | Wind      | 59.8                  | 2007           | 2027            | Floyd, TX                          | 
| Hackberry         | Wind      | 165.6                 | 2008           | 2023            | Shackelford, TX                    | 
| Whitetail         | Wind      | 92.3                  | 2012           | 2037            | Webb, TX                           | 
| Los Vientos 2     | Wind      | 201.6                 | 2012           | 2037            | Willacy, TX                        | 
| Los Vientos 3     | Wind      | 200                   | 2015           | 2040            | Starr County, TX                   | 
| Jumbo Road        | Wind      | 299.7                 | 2015           | 2033            | Castro and Deaf Smith Counties, TX | 
| Los Vientos 4     | Wind      | 200                   | 2016           | 2041            | Starr County, TX                   | 
| Webberbille Solar | Solar     | 30                    | 2011           | 2036            | Travis, TX                         | 
| Roserock          | Solar     | 157.5                 | 2016           | 2036            | Pecos, TX                          | 
```