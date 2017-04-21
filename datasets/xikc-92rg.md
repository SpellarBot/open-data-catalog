# Downtown Development

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/downtown-development) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/xikc-92rg) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/xikc-92rg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/xikc-92rg/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | xikc-92rg |
| Name | Downtown Development |
| Attribution | Downtown Jackson Partners |
| Category | Economic Development |
| Tags | downtown, development, economic, vibrant |
| Created | 2016-08-16T14:01:49Z |
| Publication Date | 2016-12-02T01:17:51Z |

## Description

Downtown has experienced $700 million in development since 2005, and there is more than $160 million of projects currently underway or on the drawing board. Below is a list of current projects exceeding $1 million. Check out this list of projects dating back from 2001 to the present day.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | development_listings | Development Listings | text          | text          |
| Yes      | series tag     | description          | Description          | text          | text          |
| Yes      | numeric metric | cost                 | Cost                 | money         | money         |
| Yes      | series tag     | status               | Status               | text          | text          |
| Yes      | time           | year                 | Year                 | calendar_date | calendar_date |
| Yes      | series tag     | photo                | Photo                | photo         | photo         |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xikc-92rg d:2016-08-01T00:00:00.000Z t:development_listings="Capitol Art Lofts" t:status=Planning t:description="Mixed-Use, 31 Apartments" t:photo=8aaf2542-d825-45fc-9b43-026fd229dc52 m:cost=10400000

series e:xikc-92rg d:2016-08-01T00:00:00.000Z t:development_listings="Capitol and West" t:status=Planning t:description="Conversion of Former Federal Courthouse to 50 Residential Units and Commercial Space, 115,000 sf" t:photo=8e00a376-0f80-41da-b0ca-16f05398954e m:cost=20000000

series e:xikc-92rg d:2016-08-01T00:00:00.000Z t:development_listings="Westin Hotel" t:status="Under Construction" t:description="9-Story, Full-Service Hotel, 205 Rooms" t:photo=43032a0a-ad8c-4c40-a116-d83399f5367c m:cost=60000000
```

## Meta Commands

```ls
metric m:cost p:integer l:Cost d:"Cost or estimated cost of the development project" t:dataTypeName=money

entity e:xikc-92rg l:"Downtown Development" t:attribution="Downtown Jackson Partners" t:url=https://data.jacksonms.gov/api/views/xikc-92rg

property e:xikc-92rg t:meta.view v:id=xikc-92rg v:category="Economic Development" v:attributionLink=http://downtown-jackson.com/working-and-investing/development-projects v:averageRating=0 v:name="Downtown Development" v:attribution="Downtown Jackson Partners"

property e:xikc-92rg t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:xikc-92rg t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| development_listings                                              | description                                                                                      | cost     | status             | year                | photo                                | 
| ================================================================= | ================================================================================================ | ======== | ================== | =================== | ==================================== | 
| Capitol Art Lofts                                                 | Mixed-Use, 31 Apartments                                                                         | 10400000 | Planning           | 2016-08-01T00:00:00 | 8aaf2542-d825-45fc-9b43-026fd229dc52 | 
| Capitol and West                                                  | Conversion of Former Federal Courthouse to 50 Residential Units and Commercial Space, 115,000 sf | 20000000 | Planning           | 2016-08-01T00:00:00 | 8e00a376-0f80-41da-b0ca-16f05398954e | 
| Westin Hotel                                                      | 9-Story, Full-Service Hotel, 205 Rooms                                                           | 60000000 | Under Construction | 2016-08-01T00:00:00 | 43032a0a-ad8c-4c40-a116-d83399f5367c | 
| Landmark Center                                                   | Mixed-Use, 180 Apartments, Office & Retail                                                       |          | Planning           | 2016-08-01T00:00:00 | 515e2971-6cab-448e-875e-47ff6c3cedfa | 
| Regions Bank Building                                             | Mixed-Use, 140 Apartments                                                                        |          | Planning           | 2016-08-01T00:00:00 | 4fe11100-79e7-4b24-a5a7-dcbdcf255a33 | 
| Mississippi Civil Rights Museum and Museum of Mississippi History | Two Museums                                                                                      | 74000000 | Under Construction | 2016-08-01T00:00:00 | 1d461c56-c363-4168-8c99-5466f7ba6024 | 
| 101 West Capitol                                                  | 52,000 sf Renovation for Jackson State University Satellite Campus                               | 2000000  | Complete           | 2015-08-01T00:00:00 | 0c9a75fb-e9c0-44f1-afc2-0f03deea5851 | 
| Capitol Street Renaissance                                        | Revert Capitol Street back to 2-Way Traffic, Rebuild and New Landscaping between Mill and Lamar  | 9220000  | Complete           | 2015-08-01T00:00:00 | 27d7792f-dad9-4d20-a003-44305678146f | 
| Thalia Mara Hall                                                  | Phase I: Interior renovations of City auditorium                                                 | 5500000  | Complete           | 2014-08-01T00:00:00 | 96ff91a1-fad2-4c33-9808-fc170ddb84f8 | 
| Electric 308                                                      | Mixed-Use, 115,000 sf, Restaurant, Office, Residential                                           | 16000000 | Complete           | 2005-08-01T00:00:00 | a3028f61-c4a2-402e-9bc9-25a0bab1b709 | 
```