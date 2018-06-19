# Commercial and Non Commercial Flights per Month, Port Authority of NY NJ: Beginning 1977

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commercial-and-non-commercial-flights-per-month-port-authority-of-ny-nj-beginning-1977) |
| Metadata | [Link](https://data.ny.gov/api/views/gy9h-ebus) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gy9h-ebus/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gy9h-ebus/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gy9h-ebus |
| Name | Commercial and Non Commercial Flights per Month, Port Authority of NY NJ: Beginning 1977 |
| Attribution | The Port Authority of New York and New Jersey |
| Category | Transportation |
| Tags | international flights, domestic flights |
| Created | 2013-05-09T17:28:02Z |
| Publication Date | 2016-06-30T19:26:37Z |

## Description

The dataset presented in this forum is monthly data. The Port Authority collects monthly data for domestic and international cargo, flights, passengers and aircraft equipment type from each carrier at PANYNJ-operated airports. The data is aggregated and forms the basis for estimating flight fees, parking, concession, and PFC revenues at the Port Authority Airports.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                  | Data Type | Render Type |
| ======== | ============== | ============= | ===================== | ========= | =========== |
| Yes      | series tag     | airport       | Airport Code          | text      | text        |
| No       |                | year          | Year                  | number    | number      |
| No       |                | month         | Month                 | text      | text        |
| Yes      | numeric metric | domestic      | Domestic Flights      | number    | number      |
| Yes      | numeric metric | international | International Flights | number    | number      |
| Yes      | numeric metric | total         | Total Flights         | number    | number      |
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
series e:gy9h-ebus d:2015-01-01T00:00:00.000Z t:airport=ACY m:total=832 m:international=1 m:domestic=831

series e:gy9h-ebus d:2015-02-01T00:00:00.000Z t:airport=ACY m:total=786 m:international=1 m:domestic=785

series e:gy9h-ebus d:2015-03-01T00:00:00.000Z t:airport=ACY m:total=910 m:international=3 m:domestic=907
```

## Meta Commands

```ls
metric m:domestic p:integer l:"Domestic Flights" d:"Number of arriving plus departing flights between Port Authority airports and other United States Airports. It includes connecting traffic" t:dataTypeName=number

metric m:international p:integer l:"International Flights" d:"Number of arriving plus departing flights between Port Authority airports and other international Airports. It includes connecting traffic" t:dataTypeName=number

metric m:total p:integer l:"Total Flights" d:"Number of domestic plus international flights" t:dataTypeName=number

entity e:gy9h-ebus l:"Commercial and Non Commercial Flights per Month, Port Authority of NY NJ: Beginning 1977" t:attribution="The Port Authority of New York and New Jersey" t:url=https://data.ny.gov/api/views/gy9h-ebus

property e:gy9h-ebus t:meta.view v:id=gy9h-ebus v:category=Transportation v:averageRating=0 v:name="Commercial and Non Commercial Flights per Month, Port Authority of NY NJ: Beginning 1977" v:attribution="The Port Authority of New York and New Jersey"

property e:gy9h-ebus t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gy9h-ebus t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:gy9h-ebus t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport | year | month | domestic | international | total | 
| ======= | ==== | ===== | ======== | ============= | ===== | 
| ACY     | 2015 | Jan   | 831      | 1             | 832   | 
| ACY     | 2015 | Feb   | 785      | 1             | 786   | 
| ACY     | 2015 | Mar   | 907      | 3             | 910   | 
| ACY     | 2015 | Apr   | 901      | 3             | 904   | 
| ACY     | 2015 | May   | 964      | 16            | 980   | 
| ACY     | 2015 | Jun   | 927      | 36            | 963   | 
| ACY     | 2015 | Jul   | 992      | 39            | 1031  | 
| ACY     | 2015 | Aug   | 922      | 41            | 963   | 
| ACY     | 2015 | Sep   | 725      | 8             | 733   | 
| ACY     | 2015 | Oct   | 694      | 4             | 698   | 
```