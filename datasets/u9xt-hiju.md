# Parking Permit Zones

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-permit-zones-6d501) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/u9xt-hiju) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/u9xt-hiju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/u9xt-hiju/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | u9xt-hiju |
| Name | Parking Permit Zones |
| Attribution | City of Chicago |
| Category | Transportation |
| Created | 2014-10-07T22:16:43Z |
| Publication Date | 2015-05-18T17:54:42Z |

## Description

This dataset contains all those street segments (individually uniquely identified by Record ID) that have been designated as belonging to a ?Residential Parking Zone.?  Residential Parking Zones are established by passage of legislation through the Chicago City Council; this data set is updated daily, but major update installments typically occur shortly after City Council Meetings (where/when legislation affecting zones ? such as zone creation or zone modification ? occurs).   (See City Council Meeting schedule: https://chicago.legistar.com/Calendar.aspx.)  The collection of street segments for a single zone (collectively identified by Zone number) are not required to constitute a seamless polygon; however, they must be contiguous; in this sense, ?Zones? often closer resemble a collection of intersecting segments rather than an unbroken area. Segments are commonly categorized as being either ?Standard? or ?Buffer?: Standard means that signs exist on the street segment beginning at the low-point and ending at the high-point; Buffer means that physical signs do not exist for that zone on that physical street, but residents of addresses within that segment shall have the privilege to purchase zone products (daily permits and annual passes) for that zone, as if physical signs were installed.  (In this way, segments designated as ?Buffer? can in fact overlap with either other buffers and/or standard segments.)  Physical signs will display the zone number and the day/times when the zone restriction is in effect, e.g., ?All Times? / ?Anytime?; ?Monday through Friday?; ?6am ? 6pm All Days.?  During restricted days/times, any vehicle parked in the zone which does not display a valid unexpired zone product (either a daily permit or an annual pass printed on the City Vehicle Sticker) is subject to ticketing/enforcement.  Read more about Residential Zone Parking and eligibility to purchase zoned products: http://chicityclerk.com/city-stickers-parking/about-residential-parking.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | row_id                  | ROW ID                  | text      | number      |
| Yes      | series tag     | status                  | STATUS                  | text      | text        |
| Yes      | numeric metric | zone                    | ZONE                    | number    | text        |
| Yes      | series tag     | odd_even                | ODD_EVEN                | text      | text        |
| No       |                | address_range_low       | ADDRESS RANGE - LOW     | number    | number      |
| No       |                | address_range_high      | ADDRESS RANGE - HIGH    | number    | number      |
| Yes      | series tag     | street_direction        | STREET DIRECTION        | text      | text        |
| Yes      | series tag     | street_name             | STREET NAME             | text      | text        |
| Yes      | series tag     | street_type             | STREET TYPE             | text      | text        |
| Yes      | series tag     | second_street_direction | SECOND STREET DIRECTION | text      | text        |
| Yes      | series tag     | buffer                  | BUFFER                  | text      | text        |
| Yes      | numeric metric | ward_low                | WARD - LOW              | number    | number      |
| Yes      | numeric metric | ward_high               | WARD - HIGH             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_range_low,address_range_high
```

## Data Commands

```ls
series e:u9xt-hiju d:2014-10-28T22:33:56.000Z t:odd_even=E t:buffer=N t:row_id=7485 t:status=ACTIVE t:street_name=HARDING t:street_direction=N t:street_type=AVE m:zone=221

series e:u9xt-hiju d:2014-10-28T22:34:02.000Z t:odd_even=E t:buffer=N t:row_id=7461 t:status=ACTIVE t:street_name=KOMENSKY t:street_direction=S t:street_type=AVE m:zone=382

series e:u9xt-hiju d:2014-10-28T22:34:03.000Z t:odd_even=O t:buffer=N t:row_id=7484 t:status=ACTIVE t:street_name=HARDING t:street_direction=N t:street_type=AVE m:zone=221
```

## Meta Commands

```ls
metric m:zone p:integer l:ZONE d:"The zone number. In cases where signs are posted (i.e., range is not a buffer range), this is the number that is listed on the physical sign." t:dataTypeName=number

metric m:ward_low p:integer l:"WARD - LOW" d:"The ward in which the low end of the address range falls." t:dataTypeName=number

metric m:ward_high p:integer l:"WARD - HIGH" d:"The ward in which the high end of the address range falls." t:dataTypeName=number

entity e:u9xt-hiju l:"Parking Permit Zones" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/u9xt-hiju

property e:u9xt-hiju t:meta.view v:id=u9xt-hiju v:category=Transportation v:averageRating=0 v:name="Parking Permit Zones" v:attribution="City of Chicago"

property e:u9xt-hiju t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:u9xt-hiju t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | row_id | status | zone | odd_even | address_range_low | address_range_high | street_direction | street_name | street_type | second_street_direction | buffer | ward_low | ward_high | 
| =========== | ====== | ====== | ==== | ======== | ================= | ================== | ================ | =========== | =========== | ======================= | ====== | ======== | ========= | 
| 1414535636  | 7485   | ACTIVE | 221  | E        | 5900              | 5998               | N                | HARDING     | AVE         |                         | N      |          |           | 
| 1414535642  | 7461   | ACTIVE | 382  | E        | 4016              | 4046               | S                | KOMENSKY    | AVE         |                         | N      |          |           | 
| 1414535643  | 7484   | ACTIVE | 221  | O        | 5701              | 5799               | N                | HARDING     | AVE         |                         | N      |          |           | 
| 1414535643  | 7483   | ACTIVE | 221  | E        | 5700              | 5798               | N                | HARDING     | AVE         |                         | N      |          |           | 
| 1414535645  | 7481   | ACTIVE | 221  | E        | 5600              | 5698               | N                | HARDING     | AVE         |                         | N      |          |           | 
| 1418682834  | 7630   | ACTIVE | 19   | O        | 1201              | 1209               | S                | AUSTIN      | BLVD        |                         | N      |          |           | 
| 1418682834  | 4185   | ACTIVE | 990  | O        | 1307              | 1399               | S                | CALIFORNIA  | AVE         |                         | N      |          |           | 
| 1418740588  | 8119   | ACTIVE | 1268 | O        | 4601              | 4699               | N                | WINTHROP    | AVE         |                         | N      | 46       | 46        | 
| 1418740588  | 1776   | ACTIVE | 5    | E        | 1100              | 1198               | S                | MAY         | ST          |                         | N      | 25       | 25        | 
| 1418740589  | 3523   | ACTIVE | 1377 | E        | 8600              | 8698               | S                | MARYLAND    | AVE         |                         | N      | 8        | 8         | 
```