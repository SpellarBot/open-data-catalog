# Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/39r6-cbzf/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/coach-bus-passengers-per-month-at-port-authority-of-ny-nj-airports-beginning-2002)
* Id = 39r6-cbzf
* Name = Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002
* Attribution = The Port Authority of New York & New Jersey
* Attribution Link = http://www.panynj.gov/airports/ewr-public-transportation.html
* Category = Transportation
* Tags = [the port authority of new york & new jersey, airport, coach bus, bus passengers, ground transportation]
* Created = 2014-02-10T20:00:53Z
* Publication Date = 2016-11-10T20:05:22Z
* Rows Updated = 2016-11-10T20:05:10Z

## Description

The Port Authority of New York & New Jersey quarterly produces a data file and provides information on monthly in-bound, out-bound, and connecting Coach Bus passengers between John F. Kennedy International Airport, LaGuardia Airport, and Newark Liberty International Airport; and between aforementioned airports and NYC bus stations beginning in 2002. The dataset represents aggregate numbers of single destination (e.g. A -> B) Coach Bus ticket sale by the Coach Bus companies.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| Airport          | airport          | text      | text        | series tag     | Yes      | 
| Year             | year             | number    | number      | time           | Yes      | 
| Month            | month            | number    | number      | numeric metric | Yes      | 
| Coach Passengers | coach_passengers | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=30338 m:month=1

series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=26409 m:month=2

series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=36206 m:month=3
```

## Meta Commands

```ls
metric m:month p:integer l:Month t:dataTypeName=number

metric m:coach_passengers p:integer l:"Coach Passengers" t:dataTypeName=number

entity e:39r6-cbzf l:"Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002" t:attribution="The Port Authority of New York & New Jersey" t:url=https://data.ny.gov/api/views/39r6-cbzf

property e:39r6-cbzf t:meta.view d:2017-03-03T14:07:06.277Z v:id=39r6-cbzf v:category=Transportation v:attributionLink=http://www.panynj.gov/airports/ewr-public-transportation.html v:averageRating=0 v:name="Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002" v:attribution="The Port Authority of New York & New Jersey"

property e:39r6-cbzf t:meta.view.owner d:2017-03-03T14:07:06.277Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:39r6-cbzf t:meta.view.tableauthor d:2017-03-03T14:07:06.277Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:39r6-cbzf t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:07:06.277Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```