# Air Passenger Traffic per Month, Port Authority of NY NJ: Beginning 1977

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-passenger-traffic-per-month-port-authority-of-ny-nj-beginning-1977) |
| Metadata | [Link](https://data.ny.gov/api/views/8pkr-4b7t) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/8pkr-4b7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/8pkr-4b7t/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 8pkr-4b7t |
| Name | Air Passenger Traffic per Month, Port Authority of NY NJ: Beginning 1977 |
| Attribution | The Port Authority of New York and New Jersey |
| Category | Transportation |
| Tags | domestic air passengers, international air passengers |
| Created | 2013-05-09T17:10:41Z |
| Publication Date | 2016-06-30T19:36:57Z |

## Description

The dataset presented in this forum is monthly data. The Port Authority  collects monthly data for domestic and international, cargo, flights, passengers and aircraft equipment type from each carrier at PANYNJ-operated airports. The data is aggregated and forms the basis for estimating flight fees, parking, concession, and PFC revenues at the Port Authority Airports.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                     | Data Type | Render Type |
| ======== | ============== | ============= | ======================== | ========= | =========== |
| Yes      | series tag     | airport_code  | Airport Code             | text      | text        |
| No       |                | year          | Year                     | number    | number      |
| No       |                | month         | Month                    | text      | text        |
| Yes      | numeric metric | domestic      | Domestic Passengers      | number    | number      |
| Yes      | numeric metric | international | International Passengers | number    | number      |
| Yes      | numeric metric | total         | Total Passengers         | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:8pkr-4b7t d:2015-01-01T00:00:00.000Z t:airport_code=ACY m:total=98267 m:international=90 m:domestic=98177

series e:8pkr-4b7t d:2015-02-01T00:00:00.000Z t:airport_code=ACY m:total=96496 m:international=65 m:domestic=96431

series e:8pkr-4b7t d:2015-03-01T00:00:00.000Z t:airport_code=ACY m:total=116690 m:international=197 m:domestic=116493
```

## Meta Commands

```ls
metric m:domestic p:integer l:"Domestic Passengers" d:"Number of arriving plus departing passengers between Port Authority airports and other United States Airports. It includes connecting traffic" t:dataTypeName=number

metric m:international p:integer l:"International Passengers" d:"Number of arriving plus departing passengers between Port Authority airports and other International Airports. It includes connecting traffic" t:dataTypeName=number

metric m:total p:integer l:"Total Passengers" d:"Number of domestic plus international passengers" t:dataTypeName=number

entity e:8pkr-4b7t l:"Air Passenger Traffic per Month, Port Authority of NY NJ: Beginning 1977" t:attribution="The Port Authority of New York and New Jersey" t:url=https://data.ny.gov/api/views/8pkr-4b7t

property e:8pkr-4b7t t:meta.view v:id=8pkr-4b7t v:category=Transportation v:averageRating=0 v:name="Air Passenger Traffic per Month, Port Authority of NY NJ: Beginning 1977" v:attribution="The Port Authority of New York and New Jersey"

property e:8pkr-4b7t t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:8pkr-4b7t t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:8pkr-4b7t t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport_code | year | month | domestic | international | total  | 
| ============ | ==== | ===== | ======== | ============= | ====== | 
| ACY          | 2015 | Jan   | 98177    | 90            | 98267  | 
| ACY          | 2015 | Feb   | 96431    | 65            | 96496  | 
| ACY          | 2015 | Mar   | 116493   | 197           | 116690 | 
| ACY          | 2015 | Apr   | 105539   | 161           | 105700 | 
| ACY          | 2015 | May   | 103668   | 425           | 104093 | 
| ACY          | 2015 | Jun   | 96259    | 1102          | 97361  | 
| ACY          | 2015 | Jul   | 109247   | 1894          | 111141 | 
| ACY          | 2015 | Aug   | 108700   | 1932          | 110632 | 
| ACY          | 2015 | Sep   | 82268    | 315           | 82583  | 
| ACY          | 2015 | Oct   | 80901    | 443           | 81344  | 
```