# Open.ny.gov API Catalog

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-ny-gov-api-catalog) |
| Metadata | [Link](https://data.ny.gov/api/views/vfrh-bvhu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vfrh-bvhu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vfrh-bvhu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vfrh-bvhu |
| Name | Open.ny.gov API Catalog |
| Created | 2013-03-11T02:54:40Z |
| Publication Date | 2013-07-11T02:04:43Z |

## Description

List of public APIs created using API Foundry that access Open.ny.gov datasets

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | name        | Name        | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
| Yes      | series tag  | category    | Category    | text      | text        |
| Yes      | series tag  | keywords    | Keywords    | text      | text        |
| Yes      | series tag  | alias       | Alias       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vfrh-bvhu d:2013-03-10T20:46:28.000Z t:category="Economic Development" t:keywords="community farmers markets" t:alias=farmersmarkets t:description="In the past decade the number of farmers markets in New York State has grown at a rapid rate. The dataset published on the website contains information detailing the time and location of community farmers markets as well as the name and phone number of the market manager." t:name="Farmers Markets in New York State API" m:row_number.vfrh-bvhu=1

series e:vfrh-bvhu d:2013-03-10T20:46:28.000Z t:category=Recreation t:keywords="river, stream, fish, angler" t:alias=fishinglocations t:description="This data displays the access  locations of rivers and streams for fishing in New York State, as determined by fisheries biologists working for the New York State Department of Environmental Conservation. Although every effort has been made to ensure the accuracy of information, errors may be reflected in the data supplied. The user must be aware of data conditions and bear responsibility for the appropriate use of the information with respect to possible errors, original map scale, collection methodology, currency of data, and other conditions." t:name="Recommended Fishing Rivers And Streams API" m:row_number.vfrh-bvhu=2

series e:vfrh-bvhu d:2013-03-10T20:46:28.000Z t:category="Human Services" t:keywords="child care, day care, childcare" t:alias=childcareprograms t:description="Included in the data set are data elements that will help the public learn about the licensed and registered child care programs in New York State to assist families with choosing child care and to help the media and/or academic institutions with research." t:name="Child Care Regulated Programs API" m:row_number.vfrh-bvhu=3
```

## Meta Commands

```ls
metric m:row_number.vfrh-bvhu p:long l:"Row Number"

entity e:vfrh-bvhu l:"Open.ny.gov API Catalog" t:url=https://data.ny.gov/api/views/vfrh-bvhu

property e:vfrh-bvhu t:meta.view v:id=vfrh-bvhu v:averageRating=0 v:name="Open.ny.gov API Catalog"

property e:vfrh-bvhu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vfrh-bvhu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vfrh-bvhu t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name                                                                                                 | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | category             | keywords                                                                                                                      | alias                             | 
| =========== | ==================================================================================================== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ==================== | ============================================================================================================================= | ================================= | 
| 1362948388  | Farmers Markets in New York State API                                                                | In the past decade the number of farmers markets in New York State has grown at a rapid rate. The dataset published on the website contains information detailing the time and location of community farmers markets as well as the name and phone number of the market manager.                                                                                                                                                                                                                                                                                           | Economic Development | community farmers markets                                                                                                     | farmersmarkets                    | 
| 1362948388  | Recommended Fishing Rivers And Streams API                                                           | This data displays the access locations of rivers and streams for fishing in New York State, as determined by fisheries biologists working for the New York State Department of Environmental Conservation. Although every effort has been made to ensure the accuracy of information, errors may be reflected in the data supplied. The user must be aware of data conditions and bear responsibility for the appropriate use of the information with respect to possible errors, original map scale, collection methodology, currency of data, and other conditions.     | Recreation           | river, stream, fish, angler                                                                                                   | fishinglocations                  | 
| 1362948388  | Child Care Regulated Programs API                                                                    | Included in the data set are data elements that will help the public learn about the licensed and registered child care programs in New York State to assist families with choosing child care and to help the media and/or academic institutions with research.                                                                                                                                                                                                                                                                                                           | Human Services       | child care, day care, childcare                                                                                               | childcareprograms                 | 
| 1370862924  | Liquor Authority Quarterly List of Active Licenses API                                               | The State Liquor Authority (SLA) regulates the manufacture and sale of alcoholic beverages. The SLA maintains offices in New York City, Albany (which serves as the agency headquarters), and Buffalo. The SLA?s Licensing Bureau is responsible for the statewide processing of licenses, license renewals, permits and brand label registrations. All must be consistent with the Alcoholic Beverage Control Law.                                                                                                                                                        | Economic Development | licenses, farm, wholesale, mapping, brewer, cidery, distiller, beer, wine, liquor, restaurant, bar, club, grocery, drug store | liquorauthorityactivelicenses     | 
| 1373482829  | Fare Card History for Metropolitan Transportation Authority (MTA): Beginning 2010 API                | These raw dataset shows the number of MetroCard swipes made each week by customers entering each station of the New York City Subway, PATH, AirTrain JFK and the Roosevelt Island Tram, broken out to show the relative popularity of the various types of MetroCards. MTA New York City Transit posts the latest data every Saturday by 1 a.m., and the dates listed in the links reference the date the data is posted. The data in the files covers seven-day periods beginning on the Saturday two weeks prior to the posting date and ending on the following Friday. | Transportation       | metrocard, mta, fare                                                                                                          | mtafarecardhistory                | 
| 1373483038  | NYC Transit Subway Entrance And Exit Data API                                                        | This data file provides a variety of information on subway station entrances and exits which includes but is not limited to: Division, Line, Station Name, Longitude and Latitude coordinates of entrances/exits.                                                                                                                                                                                                                                                                                                                                                          | Transportation       | subway, stations, routes, line                                                                                                | nyctransitsubwayentrance-and-exit | 
| 1373483081  | Daily Traffic on Metropolitan Transportation Authority (MTA) Bridges and Tunnels: Beginning 2010 API | This data file provides data showing the number of vehicles (including cars, buses, trucks and motorcycles) that pass through each of the nine bridges and tunnels operated by the MTA each day. The data is updated weekly.                                                                                                                                                                                                                                                                                                                                               | Transportation       | bridges and tunnels, daily traffic                                                                                            | mtadailytrafficbridges-tunnels    | 
```