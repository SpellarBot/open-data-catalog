# Building Code Scofflaw List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-code-scofflaw-list-cfe18) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/crg5-4zyp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/crg5-4zyp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/crg5-4zyp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | crg5-4zyp |
| Name | Building Code Scofflaw List |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | scofflaw, buildings, violations |
| Created | 2015-01-26T05:31:31Z |
| Publication Date | 2017-01-13T23:32:51Z |

## Description

The Chicago Building Scofflaw Ordinance (Section 2-92-416 of the Municipal Code of Chicago) is designed to prevent landlords that refuse or refrain from correcting ongoing building code violations from receiving city contracts, including those that subsidize housing. Building owners must have a least three residential buildings with uncorrected violations and have had three or more properties referred to Circuit Court within the applicable 12 month period to be eligible for the list. The building code scofflaw list is updated once a year on the first business day of December, and building owners may appeal being named on the list. Building owners with controlling interest in at least three residential properties that have habitual, extensive or serioues building code violations are now ineligible for any new city contracts in 2015. The following individuals or entities have been placed on the Building Code Scofflaw list for the entire calendar year.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | respondent                | RESPONDENT                | text          | text          |
| No       |                | address                   | ADDRESS                   | text          | text          |
| No       |                | secondary_address         | SECONDARY ADDRESS         | text          | text          |
| No       |                | tertiary_address          | TERTIARY ADDRESS          | text          | text          |
| Yes      | series tag     | circuit_court_case_number | CIRCUIT COURT CASE NUMBER | text          | text          |
| Yes      | series tag     | violation                 | VIOLATION                 | text          | text          |
| Yes      | series tag     | community_area            | COMMUNITY AREA            | text          | text          |
| Yes      | series tag     | community_area_number     | COMMUNITY AREA NUMBER     | text          | text          |
| Yes      | series tag     | ward                      | WARD                      | text          | text          |
| Yes      | numeric metric | census_tracts             | CENSUS TRACTS             | number        | text          |
| Yes      | numeric metric | census_blocks             | CENSUS BLOCKS             | number        | text          |
| Yes      | series tag     | street_block_id           | STREET BLOCK ID           | text          | text          |
| Yes      | time           | placed_on_list            | PLACED ON LIST            | calendar_date | calendar_date |
| No       |                | x_coordinate              | X_COORDINATE              | number        | number        |
| Yes      | numeric metric | y_coordindate             | Y_COORDINDATE             | number        | number        |
| No       |                | longitude                 | LONGITUDE                 | number        | number        |
| No       |                | latitude                  | LATITUDE                  | number        | number        |
```

## Time Field

```ls
Value = placed_on_list
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,secondary_address,tertiary_address,x_coordinate,longitude,latitude
```

## Data Commands

```ls
series e:crg5-4zyp d:2016-01-19T00:00:00.000Z t:respondent="TONY BAHARY" t:street_block_id=49614 t:ward=26 t:violation=Conservation t:community_area="HUMBOLDT PARK" t:community_area_number=23 t:circuit_court_case_number=10-M1-400964 m:y_coordindate=1910431.5831366694 m:census_tracts=17031230400 m:census_blocks=170312304001010

series e:crg5-4zyp d:2016-01-19T00:00:00.000Z t:respondent="TONY BAHARY" t:street_block_id=30144 t:ward=26 t:violation=Conservation t:community_area="HUMBOLDT PARK" t:community_area_number=23 t:circuit_court_case_number=12-M1-400183 m:y_coordindate=1910447.8405029539 m:census_tracts=17031230300 m:census_blocks=170312303001003

series e:crg5-4zyp d:2016-01-19T00:00:00.000Z t:respondent="TONY BAHARY" t:street_block_id=49614 t:ward=26 t:violation=Conservation t:community_area="HUMBOLDT PARK" t:community_area_number=23 t:circuit_court_case_number=12-M1-403249 m:y_coordindate=1910432.5109357357 m:census_tracts=17031230400 m:census_blocks=170312304001010
```

## Meta Commands

```ls
metric m:census_tracts p:long l:"CENSUS TRACTS" d:"Census tract number based on the 2010 census tracts. For more information, see https://www.census.gov/geo/reference/gtc/gtc_ct.html" t:dataTypeName=number

metric m:census_blocks p:long l:"CENSUS BLOCKS" d:"Census blocks based on the 2010 census blocks. For more information, see: https://www.census.gov/geo/maps-data/maps/block/2010/" t:dataTypeName=number

metric m:y_coordindate p:double l:Y_COORDINDATE d:"The north-south coordinate defined in feet, based on NAD 83 - State Plane Eastern IL" t:dataTypeName=number

entity e:crg5-4zyp l:"Building Code Scofflaw List" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/crg5-4zyp

property e:crg5-4zyp t:meta.view v:id=crg5-4zyp v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Building Code Scofflaw List" v:attribution="City of Chicago"

property e:crg5-4zyp t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:crg5-4zyp t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| respondent                                   | address                    | secondary_address           | tertiary_address | circuit_court_case_number | violation        | community_area         | community_area_number | ward | census_tracts | census_blocks   | street_block_id | placed_on_list      | x_coordinate       | y_coordindate      | longitude         | latitude         | 
| ============================================ | ========================== | =========================== | ================ | ========================= | ================ | ====================== | ===================== | ==== | ============= | =============== | =============== | =================== | ================== | ================== | ================= | ================ | 
| TONY BAHARY                                  | 3614 W NORTH AVE           |                             |                  | 10-M1-400964              | Conservation     | HUMBOLDT PARK          | 23                    | 26   | 17031230400   | 170312304001010 | 49614           | 2016-01-19T00:00:00 | 1151949.4858656211 | 1910431.5831366694 | -87.7172341156365 | 41.9100972059707 | 
| TONY BAHARY                                  | 3506 W NORTH AVE           |                             |                  | 12-M1-400183              | Conservation     | HUMBOLDT PARK          | 23                    | 26   | 17031230300   | 170312303001003 | 30144           | 2016-01-19T00:00:00 | 1152670.6735713684 | 1910447.8405029539 | -87.7145843134168 | 41.9101275721719 | 
| TONY BAHARY                                  | 3610 W NORTH AVE           |                             |                  | 12-M1-403249              | Conservation     | HUMBOLDT PARK          | 23                    | 26   | 17031230400   | 170312304001010 | 49614           | 2016-01-19T00:00:00 | 1151986.6346202928 | 1910432.5109357357 | -87.7170976206011 | 41.9100990196375 | 
| MONSERRATE HERNANDEZ                         | 1937 N KARLOV AVE          |                             |                  | 12-M1-402395              | Conservation     | HERMOSA                | 20                    | 35   | 17031200500   | 170312005001001 | 35760           | 2016-01-19T00:00:00 | 1148776.6995573929 | 1912714.4491659529 | -87.7288306491313 | 41.9164235570712 | 
| MONSERRATE HERNANDEZ                         | 614 N CENTRAL PARK AVE     |                             |                  | 13-M1-400644              | Conservation     | HUMBOLDT PARK          | 23                    | 27   | 17031231500   | 170312315004004 | 1101            | 2016-01-19T00:00:00 | 1152231.8046309776 | 1903945.7250772647 | -87.7163683369213 | 41.8922938178799 | 
| MONSERRATE HERNANDEZ                         | 6203-6209 N RAVENSWOOD AVE |                             |                  | 13-M1-403198              | Conservation     | EDGEWATER              | 77                    | 40   | 17031030300   | 170310303001008 | 20232           | 2016-01-19T00:00:00 | 1163276.7291570748 | 1941264.9080662595 | -87.6747519153733 | 41.9944745827633 | 
| DORENDA SUMATRA AKA COMBINED REALTY SERVICES | 1509-1511 E 73RD PL        | 7333-7337 S BLACKSTONE AVE  |                  | 11-M1-401016              | Conservation     | SOUTH SHORE            | 43                    | 05   | 17031430400   | 170314304003015 | 9241            | 2016-01-19T00:00:00 | 1187583.4258497541 | 1856516.6629229924 | -87.5880493457    | 41.7613747797    | 
| DORENDA SUMATRA AKA COMBINED REALTY SERVICES | 6732 S WABASH AVE          |                             |                  | 11-M1-402770              | Conservation     | GREATER GRAND CROSSING | 69                    | 06   | 17031690400   | 170316904004002 | 24206           | 2016-01-19T00:00:00 | 1177848.806902742  | 1860240.4943240331 | -87.6236146118708 | 41.7718192791052 | 
| DORENDA SUMATRA AKA COMBINED REALTY SERVICES | 11324 S MICHIGAN AVE       |                             |                  | 13-M1-402241              | Conservation     | ROSELAND               | 49                    | 09   | 17031491400   | 170314914005001 | 41664           | 2016-01-19T00:00:00 | 1178774.463773602  | 1829746.2792636785 | -87.6211463640058 | 41.6881183269776 | 
| DORENDA SUMATRA AKA COMBINED REALTY SERVICES | 5740 S CARPENTER ST        |                             |                  | 13-M1-402656              | Vacant Buildings | ENGLEWOOD              | 68                    | 16   | 17031680500   | 170316805002000 | 42225           | 2016-01-19T00:00:00 | 1170258.6583572554 | 1866569.9494365896 | -87.6512535496345 | 41.7893565643303 | 
```