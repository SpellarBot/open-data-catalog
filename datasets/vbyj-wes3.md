# SDOT Parking Day Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-parking-day-locations) |
| Metadata | [Link](https://data.seattle.gov/api/views/vbyj-wes3) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vbyj-wes3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vbyj-wes3/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vbyj-wes3 |
| Name | SDOT Parking Day Locations |
| Category | Transportation |
| Created | 2016-04-21T16:07:30Z |
| Publication Date | 2016-04-22T15:13:45Z |

## Description

Displays parking day locations in the City of Seattle for the previous year.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID   | text      | number      |
| No       |                | address    | ADDRESS    | text      | text        |
| Yes      | series tag     | host       | HOST       | text      | text        |
| Yes      | series tag     | theme      | THEME      | text      | text        |
| Yes      | series tag     | descriptio | DESCRIPTIO | text      | text        |
| Yes      | numeric metric | number_of  | NUMBER_OF  | number    | number      |
| Yes      | time           | year       | YEAR       | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:vbyj-wes3 d:2014-01-01T00:00:00.000Z t:host="ZGF Architects" t:descriptio="Installation Art Piece" t:theme="Installation Art Piece" t:objectid=1 m:number_of=2

series e:vbyj-wes3 d:2014-01-01T00:00:00.000Z t:host=PSRC t:descriptio="Lawn games and community fun!" t:theme="Western Pocket Park" t:objectid=2 m:number_of=2

series e:vbyj-wes3 d:2014-01-01T00:00:00.000Z t:host=Pronto t:descriptio="Come learn about Pronto Cycle Share, check out a bike and enjoy coffee." t:theme="Cycle Share" t:objectid=3 m:number_of=2
```

## Meta Commands

```ls
metric m:number_of p:integer l:NUMBER_OF d:Number_of t:dataTypeName=number

entity e:vbyj-wes3 l:"SDOT Parking Day Locations" t:url=https://data.seattle.gov/api/views/vbyj-wes3

property e:vbyj-wes3 t:meta.view v:id=vbyj-wes3 v:category=Transportation v:averageRating=0 v:name="SDOT Parking Day Locations"

property e:vbyj-wes3 t:meta.view.license v:name="Public Domain"

property e:vbyj-wes3 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:vbyj-wes3 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | address                                           | host                        | theme                        | descriptio                                                                                                                             | number_of | year | 
| ======== | ================================================= | =========================== | ============================ | ====================================================================================================================================== | ========= | ==== | 
| 1        | 1001 4th Ave, Seattle, Washington, 98104          | ZGF Architects              | Installation Art Piece       | Installation Art Piece                                                                                                                 | 2         | 2014 | 
| 2        | 1001 Western Ave, Seattle, Washington 98104       | PSRC                        | Western Pocket Park          | Lawn games and community fun!                                                                                                          | 2         | 2014 | 
| 3        | 1005 E Pike Street, Seattle, Washington, 98122    | Pronto                      | Cycle Share                  | Come learn about Pronto Cycle Share, check out a bike and enjoy coffee.                                                                | 2         | 2014 | 
| 4        | 1103 Madison St, Seattle, Washington 98104        | Madison BRT                 | Madison BRT Corridor Study   | Come learn more about the Madison Corridor Bus Rapid Transit project! Learn how to put your bike on the bus, and sit in our bus seats! | 2         | 2014 | 
| 5        | 1111 E Pike St, Seattle, WA 98122                 | Capitol Hill Housing        | Community Conversations      | Come listen and share with community members at our interactive art display and                                                        | 2         | 2014 | 
| 6        | 112 9th Ave N, Seattle, Washington 98109          | Cascade Bicycle Club        | 9th Ave Protected Bike Lanes | A two block protected bike lane from Denny to Thomas.                                                                                  | 0         | 2014 | 
| 7        | 1122 Alaskan Way, Seattle, Washington 98101       | MITHUN + Social Scale Media | WORK + PLAN | ALASKAN WAY    | Life along Alaskan way, a place to relax and enjoy.                                                                                    | 2         | 2014 | 
| 8        | 118 S Washington St, Seattle, Washington 98104    | Freiheit & Ho Architects    | Freiheit & Ho Architects     | Life sized Jenga, and custom astroturf seating make this park a can't miss.                                                            | 2         | 2014 | 
| 9        | 125 University Street, Seattle, Washington 98101  | The Watershed Company       | The 'Shed                    | Bring your coffee and chill with Hammering Man and environmental arts at The ?Shed.                                                    | 2         | 2014 | 
| 10       | 12513 Lake City Way NE, Seattle, Washington 98125 | Kaffeeklatsch               | Kaffeeklatsch                | Benches and a place to relax!                                                                                                          | 2         | 2014 | 
```