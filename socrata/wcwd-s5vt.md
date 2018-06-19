# Agricultural Fairs in New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-fairs-in-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/wcwd-s5vt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wcwd-s5vt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wcwd-s5vt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wcwd-s5vt |
| Name | Agricultural Fairs in New York State |
| Attribution | New York State Department of Agriculture and Markets |
| Category | Recreation |
| Tags | agriculture, horticulture, exhibits, fairs |
| Created | 2014-06-17T17:04:24Z |
| Publication Date | 2016-04-25T13:48:22Z |

## Description

Directory of New York State agricultural fairs for the current year, provided by the NYS Department of Agriculture and Markets.  The dataset includes the address and county of the fair, the fair?s begin and end dates and the website address for each fair.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | fair_name      | Fair Name      | text          | text          |
| Yes      | series tag  | street_address | Street Address | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | state          | State          | text          | text          |
| Yes      | series tag  | zip            | Zip            | text          | number        |
| Yes      | time        | start_date     | Start Date     | calendar_date | calendar_date |
| No       |             | end_date       | End Date       | calendar_date | calendar_date |
| Yes      | series tag  | fair_location  | Fair Location  | text          | text          |
| Yes      | series tag  | county         | County         | text          | text          |
| Yes      | series tag  | web_site       | Web Site       | url           | url           |
| Yes      | series tag  | type_of_fair   | Type of Fair   | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:wcwd-s5vt d:2016-07-26T00:00:00.000Z t:type_of_fair=county t:zip=13862 t:fair_location="Whitney Point" t:fair_name="Broome County Fair" t:county=Broome t:state=NY t:street_address="2939 Rt 11" t:web_site=http://www.broomecountyfairny.com t:city="Whitney Point" m:row_number.wcwd-s5vt=1

series e:wcwd-s5vt d:2016-07-05T00:00:00.000Z t:type_of_fair=youth t:zip=13045 t:fair_location=Cortland t:fair_name="Cortland County Junior Fair" t:county=Cortland t:state=NY t:street_address="Fairgrounds Blvd" t:web_site=http://www.cortlandfair.org t:city=Cortland m:row_number.wcwd-s5vt=2

series e:wcwd-s5vt d:2016-08-15T00:00:00.000Z t:type_of_fair=county t:zip=13856 t:fair_location=Walton t:fair_name="Delaware County Fair" t:county=Delaware t:state=NY t:street_address="Fair Street" t:web_site=http://www.delawarecountyfair.org t:city=Walton m:row_number.wcwd-s5vt=3
```

## Meta Commands

```ls
metric m:row_number.wcwd-s5vt p:long l:"Row Number"

entity e:wcwd-s5vt l:"Agricultural Fairs in New York State" t:attribution="New York State Department of Agriculture and Markets" t:url=https://data.ny.gov/api/views/wcwd-s5vt

property e:wcwd-s5vt t:meta.view v:id=wcwd-s5vt v:category=Recreation v:attributionLink=http://www.agriculture.ny.gov/AD/Agricultural-Fair-List.pdf v:averageRating=0 v:name="Agricultural Fairs in New York State" v:attribution="New York State Department of Agriculture and Markets"

property e:wcwd-s5vt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wcwd-s5vt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:wcwd-s5vt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fair_name                      | street_address                       | city          | state | zip   | start_date          | end_date            | fair_location | county    | web_site                                         | type_of_fair | 
| ============================== | ==================================== | ============= | ===== | ===== | =================== | =================== | ============= | ========= | ================================================ | ============ | 
| Broome County Fair             | 2939 Rt 11                           | Whitney Point | NY    | 13862 | 2016-07-26T00:00:00 | 2016-07-31T00:00:00 | Whitney Point | Broome    | [http://www.broomecountyfairny.com, null]        | county       | 
| Cortland County Junior Fair    | Fairgrounds Blvd                     | Cortland      | NY    | 13045 | 2016-07-05T00:00:00 | 2016-07-09T00:00:00 | Cortland      | Cortland  | [http://www.cortlandfair.org, null]              | youth        | 
| Delaware County Fair           | Fair Street                          | Walton        | NY    | 13856 | 2016-08-15T00:00:00 | 2016-08-20T00:00:00 | Walton        | Delaware  | [http://www.delawarecountyfair.org, null]        | county       | 
| Dutchess County Fair           | 6550 Springbrook Ave Rt 9            | Rhinebeck     | NY    | 12572 | 2016-08-23T00:00:00 | 2016-08-28T00:00:00 | Rhinebeck     | Dutchess  | [http://www.dutchessfair.com, null]              | county       | 
| Greene County Youth Fair       | Angelo Canna Town Park; Mountain Ave | Cairo         | NY    | 12413 | 2016-07-28T00:00:00 | 2016-07-31T00:00:00 | Cairo         | Greene    | [http://www.thegreenecountyyouthfair.com/, null] | youth        | 
| Madison County Fair            | 1968 Fairgrounds Road                | Brookfield    | NY    | 13314 | 2016-07-07T00:00:00 | 2016-07-10T00:00:00 | Brookfield    | Madison   | [http://www.madisoncountyfairny.com, null]       | county       | 
| Monroe County Fair             | Northhampton Park; Hubbell Rd        | Spencerport   | NY    | 14559 | 2016-08-04T00:00:00 | 2016-08-07T00:00:00 | Spencerport   | Monroe    | [http://www.mcfair.com/, null]                   | county       | 
| Schoharie County Sunshine Fair | 113 Sunshine Drive                   | Cobleskill    | NY    | 12043 | 2016-07-30T00:00:00 | 2016-08-06T00:00:00 | Cobleskill    | Schoharie | [http://www.sunshinefair.org, null]              | county       | 
| Tioga County Fair              | West Main Street                     | Owego         | NY    | 13827 | 2016-07-05T00:00:00 | 2016-07-09T00:00:00 | Owego         | Tioga     | [http://tiogacountyfair.com, null]               | county       | 
| Warren County Youth Fair       | Schroon River Road                   | Warrensburg   | NY    | 12885 | 2016-10-13T00:00:00 | 2016-10-13T00:00:00 | Warrensburg   | Warren    | [http://www.warren.cce.cornell.edu, null]        | youth        | 
```