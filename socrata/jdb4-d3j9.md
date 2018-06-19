# Luxury Limousine Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/luxury-limousine-vehicles-51d0f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jdb4-d3j9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jdb4-d3j9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jdb4-d3j9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jdb4-d3j9 |
| Name | Luxury Limousine Vehicles |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, luxury |
| Created | 2011-08-29T17:51:46Z |
| Publication Date | 2013-06-26T17:20:16Z |

## Description

All TLC luxury limousine vehicles

## Columns

```ls
| Included | Schema Type | Field Name                                         | Name                                               | Data Type     | Render Type   |
| ======== | =========== | ================================================== | ================================================== | ============= | ============= |
| Yes      | series tag  | affiliated_base_license_number                     | Affiliated Base License Number                     | text          | text          |
| Yes      | series tag  | affiliated_base_name                               | Affiliated Base Name                               | text          | text          |
| Yes      | series tag  | license_number                                     | License Number                                     | text          | text          |
| Yes      | series tag  | name_of_licensee                                   | Name of Licensee                                   | text          | text          |
| Yes      | series tag  | license_type                                       | License Type                                       | text          | text          |
| Yes      | series tag  | dmv_license_plate                                  | DMV License Plate                                  | text          | text          |
| Yes      | series tag  | vin                                                | VIN                                                | text          | text          |
| No       |             | model_year                                         | Model Year                                         | number        | number        |
| Yes      | series tag  | hybrid_accessible_cng_or_stretch_limousine_vehicle | Hybrid_Accessible_CNG_OR_Stretch_Limousine_Vehicle | text          | text          |
| Yes      | time        | license_expiration_date                            | License Expiration Date                            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = model_year
```

## Data Commands

```ls
series e:jdb4-d3j9 d:2012-12-14T00:00:00.000Z t:affiliated_base_license_number=B00370 t:license_type=For-Hire-Vehicle t:license_number=5384207 t:vin=1G6KR5EY0AU132490 t:dmv_license_plate=OL1425H t:name_of_licensee="DAVEL NEW JERSEY INC" t:affiliated_base_name="DAV-EL SERVICES INC" m:row_number.jdb4-d3j9=1

series e:jdb4-d3j9 d:2013-05-16T00:00:00.000Z t:affiliated_base_license_number=B00837 t:license_type=For-Hire-Vehicle t:license_number=5399077 t:vin=4JGCB6FE9BA126671 t:dmv_license_plate=T610134C t:name_of_licensee="EZ TRIP INC" t:affiliated_base_name="CAREY LIMO N Y INC" m:row_number.jdb4-d3j9=2

series e:jdb4-d3j9 d:2013-04-28T00:00:00.000Z t:affiliated_base_license_number=B01644 t:license_type=For-Hire-Vehicle t:license_number=5398531 t:vin=2LNBL8EV5BX755390 t:dmv_license_plate=OL5921H t:name_of_licensee="MUSIC EXPRESS NY INC" t:affiliated_base_name="MUSIC EXPRESS/N.Y. INC" m:row_number.jdb4-d3j9=3
```

## Meta Commands

```ls
metric m:row_number.jdb4-d3j9 p:long l:"Row Number"

entity e:jdb4-d3j9 l:"Luxury Limousine Vehicles" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/jdb4-d3j9

property e:jdb4-d3j9 t:meta.view v:id=jdb4-d3j9 v:category=Transportation v:averageRating=0 v:name="Luxury Limousine Vehicles" v:attribution="Taxi and Limousine Commission (TLC)"

property e:jdb4-d3j9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jdb4-d3j9 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| affiliated_base_license_number | affiliated_base_name       | license_number | name_of_licensee                       | license_type     | dmv_license_plate | vin               | model_year | hybrid_accessible_cng_or_stretch_limousine_vehicle | license_expiration_date | 
| ============================== | ========================== | ============== | ====================================== | ================ | ================= | ================= | ========== | ================================================== | ======================= | 
| B00370                         | DAV-EL SERVICES INC        | 5384207        | DAVEL NEW JERSEY INC                   | For-Hire-Vehicle | OL1425H           | 1G6KR5EY0AU132490 | 2010       |                                                    | 2012-12-14T00:00:00     | 
| B00837                         | CAREY LIMO N Y INC         | 5399077        | EZ TRIP INC                            | For-Hire-Vehicle | T610134C          | 4JGCB6FE9BA126671 | 2011       |                                                    | 2013-05-16T00:00:00     | 
| B01644                         | MUSIC EXPRESS/N.Y. INC     | 5398531        | MUSIC EXPRESS NY INC                   | For-Hire-Vehicle | OL5921H           | 2LNBL8EV5BX755390 | 2011       |                                                    | 2013-04-28T00:00:00     | 
| B01818                         | TA-TA TRANSPORTATION, INC. | 5255612        | PRECISION LIMOUSINE INTERNATIONAL INC. | For-Hire-Vehicle | PLI22             | 2LNBL8EV3AX616843 | 2010       |                                                    | 2013-03-13T00:00:00     | 
| B00001                         | LONDON TOWNCARS INC        |                | LONDON TOWNCARS INC                    | For-Hire-Vehicle | LTC31             | 1GKFK66847J288022 | 2007       |                                                    | 2011-11-09T00:00:00     | 
| B00001                         | LONDON TOWNCARS INC        |                | LONDON TOWNCARS INC                    | For-Hire-Vehicle | LTC88             | 1GYUKGEF8AR123554 | 2010       |                                                    | 2013-06-30T00:00:00     | 
| B00001                         | LONDON TOWNCARS INC        |                | LONDON TOWNCARS INC                    | For-Hire-Vehicle | LTC57             | 1G6KR5E6XBU102610 | 2011       |                                                    | 2013-06-30T00:00:00     | 
| B00001                         | LONDON TOWNCARS INC        |                | LONDON TOWNCARS INC                    | For-Hire-Vehicle | LTC65             | 1G6KR5E67BU106775 | 2011       |                                                    | 2012-06-30T00:00:00     | 
| B00001                         | LONDON TOWNCARS INC        |                | LONDON TOWNCARS INC                    | For-Hire-Vehicle | LTC58             | 1G6KR5EY7AU105254 | 2010       |                                                    | 2013-06-30T00:00:00     | 
| B00001                         | LONDON TOWNCARS INC        |                | LONDON TOWNCARS INC                    | For-Hire-Vehicle | LTC91             | 1G6KD57Y69U101607 | 2009       |                                                    | 2013-06-30T00:00:00     | 
```