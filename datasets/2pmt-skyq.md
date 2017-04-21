# Steam Consumption by ZIP Code - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/steam-consumption-by-zip-code-2010-5b8ed) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2pmt-skyq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2pmt-skyq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2pmt-skyq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2pmt-skyq |
| Name | Steam Consumption by ZIP Code - 2010 |
| Attribution | Mayor's Office of Long-Term Planning and Sustainability (OLTPS) |
| Category | Environment |
| Tags | energy, environment, planning, power, utilities |
| Created | 2011-09-28T22:16:19Z |
| Publication Date | 2013-06-21T19:42:31Z |

## Description

2010 steam consumption in mlbs and Mg, by ZIP code and building type.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                          | Data Type | Render Type |
| ======== | ============== | ============================ | ============================= | ========= | =========== |
| Yes      | series tag     | building_type_service_class_ | Building type (service class) | text      | text        |
| Yes      | numeric metric | consumption_mlbs_            | Consumption (mlbs)            | number    | number      |
| Yes      | numeric metric | consumption_mg_              | Consumption (Mg)              | number    | number      |
| Yes      | series tag     | utility_data_source          | Utility/Data Source           | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2pmt-skyq d:2010-01-01T00:00:00.000Z t:utility_data_source=ConEd t:building_type_service_class_=Commercial m:consumption_mg_=32712 m:consumption_mlbs_=72117

series e:2pmt-skyq d:2010-01-01T00:00:00.000Z t:utility_data_source=ConEd t:building_type_service_class_=Commercial m:consumption_mg_=5946 m:consumption_mlbs_=13108

series e:2pmt-skyq d:2010-01-01T00:00:00.000Z t:utility_data_source=ConEd t:building_type_service_class_=Commercial m:consumption_mg_=3519 m:consumption_mlbs_=7757
```

## Meta Commands

```ls
metric m:consumption_mlbs_ p:integer l:"Consumption (mlbs)" t:dataTypeName=number

metric m:consumption_mg_ p:integer l:"Consumption (Mg)" t:dataTypeName=number

entity e:2pmt-skyq l:"Steam Consumption by ZIP Code - 2010" t:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)" t:url=https://data.cityofnewyork.us/api/views/2pmt-skyq

property e:2pmt-skyq t:meta.view v:id=2pmt-skyq v:category=Environment v:averageRating=0 v:name="Steam Consumption by ZIP Code - 2010" v:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)"

property e:2pmt-skyq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2pmt-skyq t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| building_type_service_class_ | consumption_mlbs_ | consumption_mg_ | utility_data_source | 
| ============================ | ================= | =============== | =================== | 
| Commercial                   | 72117             | 32712           | ConEd               | 
| Commercial                   | 13108             | 5946            | ConEd               | 
| Commercial                   | 7757              | 3519            | ConEd               | 
| Large Residential            | 154049            | 69876           | ConEd               | 
| Large Residential            | 101042            | 45832           | ConEd               | 
| Commercial                   | 177244            | 80397           | ConEd               | 
| Commercial                   | 104967            | 47612           | ConEd               | 
| Commercial                   | 32974             | 14957           | ConEd               | 
| Commercial                   | 13951             | 6328            | ConEd               | 
| Commercial                   | 10168             | 4612            | ConEd               | 
```