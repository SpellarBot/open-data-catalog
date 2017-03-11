# Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/p7e4-ipty/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/port-authority-trans-hudson-corporation-path-average-weekday-and-weekend-ridership-beginni)
* Id = p7e4-ipty
* Name = Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996
* Attribution = Port Authority NY & NJ
* Category = Transportation
* Tags = [port authority of ny & nj, rail, path, transit]
* Created = 2013-05-10T17:35:02Z
* Publication Date = 2016-10-28T19:01:47Z
* Rows Updated = 2016-10-28T19:01:32Z

## Description

PATH System average weekday and weekend linked passenger trips, by month beginning 1996 through current year period.  Trips are based on station turnstile entry counts for weekdays and weekends operating under normal weekday schedule (excludes holidays).

## Columns

```ls
| Name                   | Field Name             | Data Type | Render Type | Schema Type    | Included | 
| ====================== | ====================== | ========= | =========== | ============== | ======== | 
| Year                   | year                   | number    | number      | time           | Yes      | 
| Month                  | month                  | number    | text        | numeric metric | Yes      | 
| Average Weekday Trips  | average_weekday_trips  | number    | number      | numeric metric | Yes      | 
| Average Saturday Trips | average_saturday_trips | number    | number      | numeric metric | Yes      | 
| Average Sunday Trips   | average_sunday_trips   | number    | number      | numeric metric | Yes      | 
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
series e:p7e4-ipty d:2015-01-01T00:00:00.000Z m:average_weekday_trips=227560 m:average_saturday_trips=88875 m:month=1 m:average_sunday_trips=65718

series e:p7e4-ipty d:2015-01-01T00:00:00.000Z m:average_weekday_trips=245222 m:average_saturday_trips=94726 m:month=2 m:average_sunday_trips=69433

series e:p7e4-ipty d:2015-01-01T00:00:00.000Z m:average_weekday_trips=250436 m:average_saturday_trips=107723 m:month=3 m:average_sunday_trips=80341
```

## Meta Commands

```ls
metric m:month p:integer l:Month d:"Calendar month (1 = January, 12 = December)" t:dataTypeName=number

metric m:average_weekday_trips p:integer l:"Average Weekday Trips" d:"Identifies passenger trip volumes on weekdays" t:dataTypeName=number

metric m:average_saturday_trips p:integer l:"Average Saturday Trips" d:"Identifies passenger trip volumes on Saturdays" t:dataTypeName=number

metric m:average_sunday_trips p:integer l:"Average Sunday Trips" d:"Identifies passenger trip volumes on Sundays" t:dataTypeName=number

entity e:p7e4-ipty l:"Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996" t:attribution="Port Authority NY & NJ" t:url=https://data.ny.gov/api/views/p7e4-ipty

property e:p7e4-ipty t:meta.view d:2017-03-03T14:22:48.510Z v:id=p7e4-ipty v:category=Transportation v:averageRating=0 v:name="Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996" v:attribution="Port Authority NY & NJ"

property e:p7e4-ipty t:meta.view.owner d:2017-03-03T14:22:48.510Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:p7e4-ipty t:meta.view.tableauthor d:2017-03-03T14:22:48.510Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:p7e4-ipty t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:22:48.510Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```