# Reported Sewer Overflows

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reported-sewer-overflows) |
| Metadata | [Link](https://data.maryland.gov/api/views/3rgd-zjxx) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/3rgd-zjxx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/3rgd-zjxx/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 3rgd-zjxx |
| Name | Reported Sewer Overflows |
| Attribution | Maryland Department of the Environment |
| Category | Energy and Environment |
| Tags | water, sewer overflow, sso, cso, water quality, mde |
| Created | 2012-10-04T20:41:37Z |
| Publication Date | 2017-03-08T19:07:36Z |

## Description

Reported sewer overflows from January 2005 through December 22, 2016.  Although MDE requires that all public sewer system owners or operators report overflows to us, there may be incidents that were not reported. Note that overflow amounts provided by the person reporting the overflow may be estimated using best professional judgment or they may be actual readings from flow measurement devices when available.  

Penalty information started during 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                            | Data Type     | Render Type   |
| ======== | ============== | ============================= | =============================== | ============= | ============= |
| Yes      | series tag     | overflow_type                 | Overflow Type                   | text          | text          |
| Yes      | series tag     | municipality_facility         | Municipality/Facility           | text          | text          |
| Yes      | series tag     | npdes                         | NPDES #                         | text          | text          |
| Yes      | time           | date_discovered               | Date Discovered                 | calendar_date | calendar_date |
| No       |                | time_discovered               | Time Discovered                 | text          | text          |
| Yes      | numeric metric | days                          | Duration - Days                 | number        | number        |
| Yes      | numeric metric | hours                         | Duration - Hours                | number        | number        |
| Yes      | numeric metric | minutes                       | Duration - Minutes              | number        | number        |
| Yes      | series tag     | location                      | Location                        | text          | text          |
| Yes      | series tag     | zip_code                      | Zip Code                        | text          | number        |
| Yes      | series tag     | collection_system             | Collection-System               | text          | text          |
| Yes      | numeric metric | quantity_in_gallons_estimated | Quantity in Gallons (Estimated) | number        | number        |
| Yes      | numeric metric | net_in_gallons_estimated      | Net in Gallons (Estimated)      | number        | number        |
| Yes      | series tag     | cause                         | Cause                           | text          | text          |
| Yes      | series tag     | watershed                     | Watershed                       | text          | text          |
| Yes      | series tag     | receiving_waters              | Receiving waters                | text          | text          |
| Yes      | series tag     | county                        | County                          | text          | text          |
| Yes      | series tag     | notes                         | Notes                           | text          | text          |
| Yes      | numeric metric | penalty_collected             | Penalty Collected               | money         | money         |
| Yes      | series tag     | penalty_comments              | Penalty Comments                | text          | text          |
| No       |                | latitude                      | Latitude                        | number        | number        |
| Yes      | numeric metric | longitude                     | Longitude                       | number        | number        |
```

## Time Field

```ls
Value = date_discovered
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = time_discovered,latitude
```

## Data Commands

```ls
series e:3rgd-zjxx d:2005-01-01T00:00:00.000Z t:cause=Undetermined t:receiving_waters=Unknown t:zip_code=20814 t:county=Montgomery t:location="7628 Old Georgetown Rd, MH/12025126M" t:overflow_type=SSO t:notes="Collection system not provided" t:municipality_facility=WSSC t:npdes=N/A m:minutes=52 m:quantity_in_gallons_estimated=100 m:days=0 m:hours=2 m:net_in_gallons_estimated=100

series e:3rgd-zjxx d:2005-01-01T00:00:00.000Z t:cause="Structural failure" t:receiving_waters="Tenthouse Creek" t:zip_code=20765 t:county="Anne Arundel" t:location="Benning & Woodfield Rds." t:overflow_type=SSO t:notes="Collection system not provided" t:municipality_facility="Anne Arundel County DPW" t:npdes=N/A m:minutes=0 m:quantity_in_gallons_estimated=2000 m:days=0 m:hours=4 m:net_in_gallons_estimated=2000

series e:3rgd-zjxx d:2005-01-01T00:00:00.000Z t:cause=Blockage t:receiving_waters="Jones Falls" t:zip_code=21209 t:county="City of Baltimore" t:location="5300 Falls Rd" t:collection_system="Patapsco WWTP" t:overflow_type=SSO t:notes=None t:municipality_facility="City of Baltimore" t:npdes=N/A m:minutes=0 m:quantity_in_gallons_estimated=600 m:days=0 m:hours=2 m:net_in_gallons_estimated=600
```

## Meta Commands

```ls
metric m:days p:integer l:"Duration - Days" d:"Days duration of the overflow. Total duration is Days, Hours, Minutes." t:dataTypeName=number

metric m:hours p:integer l:"Duration - Hours" d:"Overflow duration hours. Total duration is days, hours, minutes." t:dataTypeName=number

metric m:minutes p:integer l:"Duration - Minutes" d:"Overflow duration minutes. Total duration is days, hours, minutes." t:dataTypeName=number

metric m:quantity_in_gallons_estimated p:integer l:"Quantity in Gallons (Estimated)" d:"Estimated total amount of the overflow." t:dataTypeName=number

metric m:net_in_gallons_estimated p:integer l:"Net in Gallons (Estimated)" d:"Amount of the overflow that was not collected." t:dataTypeName=number

metric m:penalty_collected p:double l:"Penalty Collected" d:"Penalty collected for the overflow event. This data is only available beginning in 2013" t:dataTypeName=money

metric m:longitude p:decimal l:Longitude t:dataTypeName=number

entity e:3rgd-zjxx l:"Reported Sewer Overflows" t:attribution="Maryland Department of the Environment" t:url=https://data.maryland.gov/api/views/3rgd-zjxx

property e:3rgd-zjxx t:meta.view v:id=3rgd-zjxx v:category="Energy and Environment" v:averageRating=0 v:name="Reported Sewer Overflows" v:attribution="Maryland Department of the Environment"

property e:3rgd-zjxx t:meta.view.license v:name="Public Domain"

property e:3rgd-zjxx t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:3rgd-zjxx t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| overflow_type | municipality_facility          | npdes | date_discovered     | time_discovered | days | hours | minutes | location                             | zip_code | collection_system | quantity_in_gallons_estimated | net_in_gallons_estimated | cause              | watershed | receiving_waters | county            | notes                          | penalty_collected | penalty_comments | latitude | longitude | 
| ============= | ============================== | ===== | =================== | =============== | ==== | ===== | ======= | ==================================== | ======== | ================= | ============================= | ======================== | ================== | ========= | ================ | ================= | ============================== | ================= | ================ | ======== | ========= | 
| SSO           | WSSC                           | N/A   | 2005-01-01T00:00:00 | 10:00:00 AM     | 0    | 2     | 52      | 7628 Old Georgetown Rd, MH/12025126M | 20814    |                   | 100                           | 100                      | Undetermined       |           | Unknown          | Montgomery        | Collection system not provided |                   |                  |          |           | 
| SSO           | Anne Arundel County DPW        | N/A   | 2005-01-01T00:00:00 | 12:00:00 PM     | 0    | 4     | 0       | Benning & Woodfield Rds.             | 20765    |                   | 2000                          | 2000                     | Structural failure |           | Tenthouse Creek  | Anne Arundel      | Collection system not provided |                   |                  |          |           | 
| SSO           | City of Baltimore              | N/A   | 2005-01-01T00:00:00 | 8:16:00 PM      | 0    | 2     | 0       | 5300 Falls Rd                        | 21209    | Patapsco WWTP     | 600                           | 600                      | Blockage           |           | Jones Falls      | City of Baltimore | None                           |                   |                  |          |           | 
| SSO           | Anne Arundel County DPW        | N/A   | 2005-01-01T00:00:00 | 10:00:00 PM     | 0    | 12    | 0       | 101 Groh Ln                          | 21403    |                   | 5000                          | 5000                     | Structural failure |           | South River      | Anne Arundel      | Collection system not provided |                   |                  |          |           | 
| SSO           | City of Baltimore              | N/A   | 2005-01-02T00:00:00 | 12:03:00 PM     | 0    | 3     | 0       | 6200 Ship View Way                   | 21224    | Back River WWTP   | 891                           | 891                      | Blockage           |           | Inner Harbor     | City of Baltimore | None                           |                   |                  |          |           | 
| SSO           | Baltimore County DPW           | N/A   | 2005-01-02T00:00:00 | 12:30:00 PM     | 0    | 4     | 0       | 531 Kingston Rd @ Sunnythorn Rd      | 21229    | Patapsco WWTP     | 500                           | 500                      | Structural failure |           | Middle River     | Baltimore County  | None                           |                   |                  |          |           | 
| SSO           | Perryville, Town Commissioners | N/A   | 2005-01-02T00:00:00 | 2:30:00 PM      | 0    | 1     | 0       | 1400 Blk Frenchtown Rd               | 21903    | Perryville WWTP   | 500                           | 500                      | Grease             |           | Unknown          | Cecil             | Collection system not provided |                   |                  |          |           | 
| SSO           | City of Baltimore              | N/A   | 2005-01-02T00:00:00 | 10:00:00 PM     | 0    | 1     | 0       | 1800 Park Ave                        | 21217    | Patapsco WWTP     | 300                           | 300                      | Blockage           |           | Jones Falls      | City of Baltimore | None                           |                   |                  |          |           | 
| SSO           | Ridgely, Commissioners of      | N/A   | 2005-01-03T00:00:00 | 9:00:00 AM      | 0    | 0     | 20      | Between Liberty & Bell Sts           | 21660    |                   | 10                            | 10                       | Blockage           |           | Unknown          | Caroline          | Collection system not provided |                   |                  |          |           | 
| SSO           | City of Baltimore              | N/A   | 2005-01-03T00:00:00 | 10:30:00 AM     | 1    | 4     | 15      | 4601 Franklintown Rd                 | 21229    | Patapsco WWTP     | 24975                         | 24975                    | Blockage           |           | Gwynn's Falls    | City of Baltimore | None                           |                   |                  |          |           | 
```