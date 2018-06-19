# ODF Recreational Opportunities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odf-recreational-opportunities) |
| Metadata | [Link](https://data.oregon.gov/api/views/ufw2-6prx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ufw2-6prx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ufw2-6prx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ufw2-6prx |
| Name | ODF Recreational Opportunities |
| Attribution | Oregon Department of Forestry |
| Category | Recreation |
| Tags | odf, forestry, state forests, hiking, biking, horseback riding, paddling, boating |
| Created | 2015-05-04T21:17:22Z |
| Publication Date | 2017-04-10T21:15:19Z |

## Description

Recreation Opportunities on Oregon Department of Forestry State Forestland.

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                                | Data Type | Render Type |
| ======== | =========== | ================================= | =================================== | ========= | =========== |
| No       | time        | :updated_at                       | updated_at                          | meta_data | meta_data   |
| Yes      | series tag  | name                              | Name                                | text      | text        |
| Yes      | series tag  | district                          | District                            | text      | text        |
| Yes      | series tag  | state_forest                      | State Forest                        | text      | text        |
| Yes      | series tag  | contact_number                    | Contact Number                      | text      | text        |
| Yes      | series tag  | information                       | State Forest Brochure               | document  | document    |
| Yes      | series tag  | site_map                          | Campground Map                      | document  | document    |
| Yes      | series tag  | activity_brochure                 | Activity Guide                      | document  | document    |
| Yes      | series tag  | additional_activity_information   | Additional Activity Information     | document  | document    |
| Yes      | series tag  | recreation_opportunities_services | Recreation Opportunities & Services | photo     | photo       |
| Yes      | series tag  | season                            | Season                              | text      | text        |
| Yes      | series tag  | number_of_sites                   | Number of Sites                     | text      | text        |
| Yes      | series tag  | amentities                        | Amentities                          | text      | text        |
| Yes      | series tag  | overnight_fee                     | Overnight Fee                       | text      | text        |
| Yes      | series tag  | closures                          | Notes/Closures                      | text      | text        |
| Yes      | series tag  | icon                              | Icon                                | photo     | photo       |
| Yes      | series tag  | type                              | Type                                | text      | text        |
| Yes      | series tag  | description                       | Description                         | text      | text        |
| Yes      | series tag  | hike                              | Hike                                | photo     | photo       |
| Yes      | series tag  | ohv                               | OHV                                 | photo     | photo       |
| Yes      | series tag  | day_use                           | Day Use                             | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ufw2-6prx d:2015-05-18T11:12:46.000Z t:icon=tvCWoZx1NbjMAuxfieD01yVyqYjSHNubswoq7d02t5U t:information.file_id=PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0 t:type="Day Use" t:information.content_type="application/pdf; charset=binary" t:contact_number=503-325-5451 t:information.filename="Clatsop State Forest Recreation Guide.pdf" t:season="All year" t:overnight_fee=N/A t:description="Picnic Site" t:number_of_sites=N/A t:name="Bradley Wayside" t:recreation_opportunities_services=C8Z6WGqVVBrv6p7jh22FD-dYsxLWKk4hBUFFgK_23jY t:state_forest=Clatsop t:amentities="picnic tables" t:information.size=14815094 t:district=Astoria m:row_number.ufw2-6prx=1

series e:ufw2-6prx d:2015-05-21T14:18:30.000Z t:icon=boa-7ZddTK43kX9KRKvBWSV9krPbPXH8JkCM5DZzjfg t:activity_brochure.file_id=bw_QCdd-x37gu1_eRJKRSC0mUH0pGyn8jHPY7WB2oQM t:activity_brochure.content_type="application/pdf; charset=binary" t:activity_brochure.size=3005896 t:information.file_id=PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0 t:type=Camp t:information.content_type="application/pdf; charset=binary" t:contact_number=503-325-5451 t:information.filename="Clatsop State Forest Recreation Guide.pdf" t:activity_brochure.filename="Nicolai Mountain OHV Brochure.pdf" t:season="All year" t:overnight_fee=free t:description=Camping t:number_of_sites="2 vehicle sites" t:name="Plympton Ridge Road Campsite" t:recreation_opportunities_services=jj486q-r0tiRLs1Nwd6Z08Ui-_DePGx6W6VQ3VWVZS4 t:state_forest=Clatsop t:information.size=14815094 t:amentities="picnic tables; fire rings" t:district=Astoria m:row_number.ufw2-6prx=2

series e:ufw2-6prx d:2015-05-21T14:17:40.000Z t:icon=boa-7ZddTK43kX9KRKvBWSV9krPbPXH8JkCM5DZzjfg t:activity_brochure.file_id=bw_QCdd-x37gu1_eRJKRSC0mUH0pGyn8jHPY7WB2oQM t:activity_brochure.content_type="application/pdf; charset=binary" t:activity_brochure.size=3005896 t:information.file_id=PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0 t:type=Camp t:information.content_type="application/pdf; charset=binary" t:contact_number=503-325-5451 t:information.filename="Clatsop State Forest Recreation Guide.pdf" t:activity_brochure.filename="Nicolai Mountain OHV Brochure.pdf" t:season="All year" t:overnight_fee=free t:description=Camping t:number_of_sites="2 vehicle sites" t:name="Kerry Road Campsite" t:recreation_opportunities_services=jj486q-r0tiRLs1Nwd6Z08Ui-_DePGx6W6VQ3VWVZS4 t:state_forest=Clatsop t:information.size=14815094 t:amentities="picnic tables; fire rings" t:district=Astoria m:row_number.ufw2-6prx=3
```

## Meta Commands

```ls
metric m:row_number.ufw2-6prx p:long l:"Row Number"

entity e:ufw2-6prx l:"ODF Recreational Opportunities" t:attribution="Oregon Department of Forestry" t:url=https://data.oregon.gov/api/views/ufw2-6prx

property e:ufw2-6prx t:meta.view v:id=ufw2-6prx v:category=Recreation v:attributionLink=http://oregon.gov/ODF v:averageRating=0 v:name="ODF Recreational Opportunities" v:attribution="Oregon Department of Forestry"

property e:ufw2-6prx t:meta.view.license v:name="Public Domain"

property e:ufw2-6prx t:meta.view.owner v:id=d6zp-7ggp v:screenName=JeriChase v:displayName=JeriChase

property e:ufw2-6prx t:meta.view.tableauthor v:id=d6zp-7ggp v:screenName=JeriChase v:roleName=editor v:displayName=JeriChase
```

## Top Records

```ls
| :updated_at | name                         | district     | state_forest | contact_number | information                                                                                                                         | site_map                 | activity_brochure                                                                                                                           | additional_activity_information | recreation_opportunities_services           | season         | number_of_sites | amentities                | overnight_fee | closures | icon                                        | type              | description      | hike                                        | ohv                                         | day_use | 
| =========== | ============================ | ============ | ============ | ============== | =================================================================================================================================== | ======================== | =========================================================================================================================================== | =============================== | =========================================== | ============== | =============== | ========================= | ============= | ======== | =========================================== | ================= | ================ | =========================================== | =========================================== | ======= | 
| 1431947566  | Bradley Wayside              | Astoria      | Clatsop      | 503-325-5451   | [application/pdf; charset=binary, PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0, Clatsop State Forest Recreation Guide.pdf, 14815094] | [null, null, null, null] | [null, null, null, null]                                                                                                                    | [null, null, null, null]        | C8Z6WGqVVBrv6p7jh22FD-dYsxLWKk4hBUFFgK_23jY | All year       | N/A             | picnic tables             | N/A           |          | tvCWoZx1NbjMAuxfieD01yVyqYjSHNubswoq7d02t5U | Day Use           | Picnic Site      |                                             |                                             |         | 
| 1432217910  | Plympton Ridge Road Campsite | Astoria      | Clatsop      | 503-325-5451   | [application/pdf; charset=binary, PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0, Clatsop State Forest Recreation Guide.pdf, 14815094] | [null, null, null, null] | [application/pdf; charset=binary, bw_QCdd-x37gu1_eRJKRSC0mUH0pGyn8jHPY7WB2oQM, Nicolai Mountain OHV Brochure.pdf, 3005896]                  | [null, null, null, null]        | jj486q-r0tiRLs1Nwd6Z08Ui-_DePGx6W6VQ3VWVZS4 | All year       | 2 vehicle sites | picnic tables; fire rings | free          |          | boa-7ZddTK43kX9KRKvBWSV9krPbPXH8JkCM5DZzjfg | Camp              | Camping          |                                             |                                             |         | 
| 1432217860  | Kerry Road Campsite          | Astoria      | Clatsop      | 503-325-5451   | [application/pdf; charset=binary, PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0, Clatsop State Forest Recreation Guide.pdf, 14815094] | [null, null, null, null] | [application/pdf; charset=binary, bw_QCdd-x37gu1_eRJKRSC0mUH0pGyn8jHPY7WB2oQM, Nicolai Mountain OHV Brochure.pdf, 3005896]                  | [null, null, null, null]        | jj486q-r0tiRLs1Nwd6Z08Ui-_DePGx6W6VQ3VWVZS4 | All year       | 2 vehicle sites | picnic tables; fire rings | free          |          | boa-7ZddTK43kX9KRKvBWSV9krPbPXH8JkCM5DZzjfg | Camp              | Camping          |                                             |                                             |         | 
| 1432217954  | Nicolai Mountain OHV Area    | Astoria      | Clatsop      | 503-325-5451   | [application/pdf; charset=binary, PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0, Clatsop State Forest Recreation Guide.pdf, 14815094] | [null, null, null, null] | [application/pdf; charset=binary, bw_QCdd-x37gu1_eRJKRSC0mUH0pGyn8jHPY7WB2oQM, Nicolai Mountain OHV Brochure.pdf, 3005896]                  | [null, null, null, null]        | ZBMrSvtzZqHyOmVMkOoOXz-nNH4FrX2czoMW1NOEBC4 | All year       | N/A             | restrooms; picnic tables  | N/A           |          | uLH8egwO-EIYwbRhrbLRzCtnx14sbUrwNAtIxJPNX5I | OHV               | OHV Staging Area |                                             | uLH8egwO-EIYwbRhrbLRzCtnx14sbUrwNAtIxJPNX5I |         | 
| 1437573532  | Big Tree Trail               | Astoria      | Clatsop      | 503-325-5451   | [application/pdf; charset=binary, PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0, Clatsop State Forest Recreation Guide.pdf, 14815094] | [null, null, null, null] | [application/pdf; charset=binary, 45fkA9fdcNLa5K8M01YX9m6Z6WwpvoikRLEAeswIPGM, Northrup Creek Horse Camp & Trail Guide.pdf, 3093517]        | [null, null, null, null]        | 9HtNtxt2R87a0obNdqgihLGfc1sYg94OQTWVoR_RqEg | May - November | N/A             |                           | N/A           |          | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w | Hike              | Trailhead        | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w |                                             |         | 
| 1464708829  | University Falls             | Forest Grove | Tillamook    | 503-357-2191   | [application/pdf; charset=binary, a9e09aef-1067-4b81-aaa2-ef29aef59e72, Tillamook State Forest Recreation Guide.pdf, 11042302]      | [null, null, null, null] | [application/pdf; charset=binary, KttF8V7MplZsBTK-0971RNJUYnqQ9-Yb-J-H68i2SLI, Historic Hiking Loop Guide.pdf, 1831900]                     | [null, null, null, null]        | -77Wl2J-mn88fTtUhF5e8r1IYUYoVXGKuIpSk_9BG3U | All year       | N/A             |                           | N/A           |          | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w | Hike, Bike        | Trailhead        | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w |                                             |         | 
| 1464709003  | Deyoe Creek                  | Forest Grove | Tillamook    | 503-357-2191   | [application/pdf; charset=binary, de905cc7-e8b0-4fd6-8301-5f9742099f25, Tillamook State Forest Recreation Guide.pdf, 11042302]      | [null, null, null, null] | [application/pdf; charset=binary, KttF8V7MplZsBTK-0971RNJUYnqQ9-Yb-J-H68i2SLI, Historic Hiking Loop Guide.pdf, 1831900]                     | [null, null, null, null]        | -77Wl2J-mn88fTtUhF5e8r1IYUYoVXGKuIpSk_9BG3U | All year       | N/A             |                           | N/A           |          | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w | Hike, Bike        | Trailhead        | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w |                                             |         | 
| 1464709071  | Four County Point            | Forest Grove | Tillamook    | 503-357-2191   | [application/pdf; charset=binary, 40e29eb3-2829-4bb7-b3b0-c8a4afdf7a75, Tillamook State Forest Recreation Guide.pdf, 11042302]      | [null, null, null, null] | [application/pdf; charset=binary, rd253NwrARlLgm9LWAIik3UphIcIt3u5FO8dmhqloY0, Four County Point and Steam Donkey Trail Guide.pdf, 1667049] | [null, null, null, null]        | 9HtNtxt2R87a0obNdqgihLGfc1sYg94OQTWVoR_RqEg | All year       | N/A             |                           | N/A           |          | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w | Hike              | Trailhead        | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w |                                             |         | 
| 1464710081  | Bell Camp                    | Forest Grove | Tillamook    | 503-357-2191   | [application/pdf; charset=binary, de2687b7-8322-4094-907e-cdbdf3a384ea, Tillamook State Forest Recreation Guide.pdf, 11042302]      | [null, null, null, null] | [null, null, null, null]                                                                                                                    | [null, null, null, null]        | qjECpIhO-zWtrzmyckQYBWld2IgAv4IGAFBEGtBgoLk | All year       | N/A             |                           | N/A           |          | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w | Hike, Bike, Horse | Trailhead        | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w |                                             |         | 
| 1445249355  | Soapstone Lake               | Astoria      | Clatsop      | 503-325-5451   | [application/pdf; charset=binary, PZD-ian2zVH_xs-6i1y9WkPIGrN8m80dLY28bIvO7H0, Clatsop State Forest Recreation Guide.pdf, 14815094] | [null, null, null, null] | [application/pdf; charset=binary, ZyFTd4PEZm1Svv9mX2ijLwClaj0VrTcu1uRbaWdML4Y, Soapstone Lake Trail Guide.pdf, 2364779]                     | [null, null, null, null]        | 9HtNtxt2R87a0obNdqgihLGfc1sYg94OQTWVoR_RqEg | All year       | N/A             |                           | N/A           |          | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w | Hike, Day Use     | Trailhead        | XqyfTeppAWv4bx3PJcS9XG68sOKTPwEGIq8aq5i9u_w |                                             |         | 
```