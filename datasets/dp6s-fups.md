# Taxis Dispatched at Port Authority of NY NJ Airports: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/taxis-dispatched-at-port-authority-of-ny-nj-airports-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/dp6s-fups) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dp6s-fups/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dp6s-fups/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dp6s-fups |
| Name | Taxis Dispatched at Port Authority of NY NJ Airports: Beginning 2002 |
| Attribution | The Port Authority of New York & New Jersey |
| Category | Transportation |
| Tags | the port authority of new york & new jersey, airport, taxi dispatch, ground transportation |
| Created | 2014-02-10T19:27:11Z |
| Publication Date | 2015-07-29T13:25:43Z |

## Description

The Port Authority of New York & New Jersey quarterly produces a data file and provides information on monthly  passengers Taxi Dispatch counts at John F. Kennedy International Airport, LaGuardia Airport, and Newark Liberty International Airport beginning in 2002. Taxi dispatch counts include only medallion taxis  that transport passengers from these airports to a destination.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | airport         | Airport         | text      | text        |
| No       |                | year            | Year            | number    | number      |
| No       |                | month           | Month           | number    | number      |
| Yes      | numeric metric | taxi_dispatched | Taxi Dispatched | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:dp6s-fups d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:taxi_dispatched=154245

series e:dp6s-fups d:2002-02-01T00:00:00.000Z t:airport="Kennedy International Airport" m:taxi_dispatched=132553

series e:dp6s-fups d:2002-03-01T00:00:00.000Z t:airport="Kennedy International Airport" m:taxi_dispatched=170990
```

## Meta Commands

```ls
metric m:taxi_dispatched p:integer l:"Taxi Dispatched" t:dataTypeName=number

entity e:dp6s-fups l:"Taxis Dispatched at Port Authority of NY NJ Airports: Beginning 2002" t:attribution="The Port Authority of New York & New Jersey" t:url=https://data.ny.gov/api/views/dp6s-fups

property e:dp6s-fups t:meta.view v:id=dp6s-fups v:category=Transportation v:attributionLink=http://www.panynj.gov/airports/ewr-taxi-car-van-service.html v:averageRating=0 v:name="Taxis Dispatched at Port Authority of NY NJ Airports: Beginning 2002" v:attribution="The Port Authority of New York & New Jersey"

property e:dp6s-fups t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dp6s-fups t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dp6s-fups t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport                       | year | month | taxi_dispatched | 
| ============================= | ==== | ===== | =============== | 
| Kennedy International Airport | 2002 | 1     | 154245          | 
| Kennedy International Airport | 2002 | 2     | 132553          | 
| Kennedy International Airport | 2002 | 3     | 170990          | 
| Kennedy International Airport | 2002 | 4     | 170926          | 
| Kennedy International Airport | 2002 | 5     | 174781          | 
| Kennedy International Airport | 2002 | 6     | 173452          | 
| Kennedy International Airport | 2002 | 7     | 177482          | 
| Kennedy International Airport | 2002 | 8     | 191258          | 
| Kennedy International Airport | 2002 | 9     | 176218          | 
| Kennedy International Airport | 2002 | 10    | 188771          | 
```