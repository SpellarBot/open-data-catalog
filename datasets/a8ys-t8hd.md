# Missouri River Water Trail Access Points

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-river-water-trail-access-points-e5bd8) |
| Metadata | [Link](https://data.mo.gov/api/views/a8ys-t8hd) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/a8ys-t8hd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/a8ys-t8hd/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | a8ys-t8hd |
| Name | Missouri River Water Trail Access Points |
| Attribution | Bryan Hopkins, Department of Natural Resources |
| Category | Natural Resources |
| Tags | missouri river water trail access points |
| Created | 2014-03-24T20:50:59Z |
| Publication Date | 2014-05-19T20:19:30Z |

## Description

Missouri River Water Trail Access Points

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | site_name   | SITE_NAME  | text      | text        |
| Yes      | series tag     | bank        | BANK       | text      | text        |
| Yes      | numeric metric | river_mile  | RIVER_MILE | number    | number      |
| Yes      | series tag     | owner_type  | OWNER_TYPE | text      | text        |
| Yes      | series tag     | owner       | OWNER      | text      | text        |
| Yes      | series tag     | camping     | CAMPING    | text      | text        |
| Yes      | series tag     | store       | STORE      | text      | text        |
| Yes      | series tag     | restrictns  | RESTRICTNS | text      | text        |
| Yes      | series tag     | web_site    | WEB_SITE   | text      | text        |
| Yes      | series tag     | phone_1     | PHONE_1    | text      | text        |
| Yes      | series tag     | phone_2     | PHONE_2    | text      | text        |
| Yes      | series tag     | map_url     | MAP_URL    | text      | text        |
| Yes      | series tag     | comments    | COMMENTS   | text      | text        |
| Yes      | series tag     | hcollcode   | HCOLLCODE  | text      | text        |
| Yes      | numeric metric | sourcescal  | SOURCESCAL | number    | number      |
| Yes      | series tag     | lodging     | LODGING    | text      | text        |
| Yes      | series tag     | boat_ramp   | BOAT_RAMP  | text      | text        |
| Yes      | series tag     | rvr_access  | RVR_ACCESS | text      | text        |
| Yes      | series tag     | short_name  | SHORT_NAME | text      | text        |
| Yes      | numeric metric | utmnorthng  | UTMNORTHNG | number    | number      |
| Yes      | numeric metric | utmeasting  | UTMEASTING | number    | number      |
| Yes      | series tag     | icon_url    | Icon-URL   | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a8ys-t8hd d:2014-04-03T09:44:42.000Z t:owner_type=Government t:rvr_access=Portage t:icon_url=http://dnr.mo.gov/images/paddling-icon.JPG t:hcollcode=I2 t:boat_ramp=No t:restrictns="No offical parking, rough bank access to river" t:site_name="Roadside Access below Lisbon Bottoms" t:short_name="County Road Access" t:camping=None t:owner="County Road" t:bank=RL t:lodging=No t:comments="Roadside access to river, very limited parking on side of county gravel road." m:utmeasting=508201.638 m:river_mile=212.8 m:utmnorthng=4326353 m:sourcescal=24000

series e:a8ys-t8hd d:2014-04-03T09:43:03.000Z t:owner_type=Government t:rvr_access=Portage t:icon_url=http://dnr.mo.gov/images/paddling-icon.JPG t:hcollcode=I2 t:boat_ramp=No t:restrictns="Day use only. Possible exclusion during bald eagle nesting season." t:site_name="Edward ""Ted"" and Pat Jones-Confluence Point State Park" t:short_name="Confluence State Park" t:map_url=http://www.mostateparks.com/confluence/map.htm t:phone_1="(636) 899-1135" t:camping=None t:owner="Missouri Department of Natural Resources State Parks" t:bank=RL t:web_site=http://www.mostateparks.com/confluence.htm t:lodging=No t:comments="River access involves a short paddle up the Mississippi River for 200 yards (west bank).  Need to cross the levy (west bank of Mississippi River) into the State Park parking area." m:utmeasting=750141.648 m:river_mile=0 m:utmnorthng=4300570.789 m:sourcescal=24000

series e:a8ys-t8hd d:2014-04-03T09:43:18.000Z t:owner_type=Government t:rvr_access="Boat Ramp" t:icon_url=http://dnr.mo.gov/images/paddling-icon.JPG t:hcollcode=I2 t:boat_ramp=Yes t:restrictns="Group camping by permit only. Contact county parks." t:site_name="Ramp at Sioux Passage Park" t:short_name="Sioux Passage Park" t:map_url=http://www.co.st-louis.mo.us/parks/locator/SiouxPassage.jpg t:phone_1="(314) 615-5000" t:camping=Improved t:owner="St. Louis County Parks" t:bank=RR t:web_site=http://www.co.st-louis.mo.us/parks/sioux.html t:lodging=No t:comments="Park extends on upstream bank of the chute behind Pelican Island; rampsite leased to MDC, as extension of  Pelican Island CA; road access at 17930 Old Jamestown Road 63034. Typical city park with pavillions, etc." m:utmeasting=736787 m:river_mile=10.5 m:utmnorthng=4304786 m:sourcescal=24000
```

## Meta Commands

```ls
metric m:river_mile p:float l:RIVER_MILE t:dataTypeName=number

metric m:sourcescal p:integer l:SOURCESCAL t:dataTypeName=number

metric m:utmnorthng p:double l:UTMNORTHNG t:dataTypeName=number

metric m:utmeasting p:double l:UTMEASTING t:dataTypeName=number

entity e:a8ys-t8hd l:"Missouri River Water Trail Access Points" t:attribution="Bryan Hopkins, Department of Natural Resources" t:url=https://data.mo.gov/api/views/a8ys-t8hd

property e:a8ys-t8hd t:meta.view v:id=a8ys-t8hd v:category="Natural Resources" v:averageRating=100 v:name="Missouri River Water Trail Access Points" v:attribution="Bryan Hopkins, Department of Natural Resources"

property e:a8ys-t8hd t:meta.view.owner v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:displayName="Renee Wright"

property e:a8ys-t8hd t:meta.view.tableauthor v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:roleName=editor v:displayName="Renee Wright"
```

## Top Records

```ls
| :updated_at | site_name                                              | bank | river_mile | owner_type | owner                                                | camping   | store       | restrictns                                                                                    | web_site                                                                                                                                                      | phone_1        | phone_2 | map_url                                                     | comments                                                                                                                                                                                                                          | hcollcode | sourcescal | lodging | boat_ramp | rvr_access             | short_name            | utmnorthng  | utmeasting | icon_url                                           | 
| =========== | ====================================================== | ==== | ========== | ========== | ==================================================== | ========= | =========== | ============================================================================================= | ============================================================================================================================================================= | ============== | ======= | =========================================================== | ================================================================================================================================================================================================================================= | ========= | ========== | ======= | ========= | ====================== | ===================== | =========== | ========== | ================================================== | 
| 1396518282  | Roadside Access below Lisbon Bottoms                   | RL   | 212.80000  | Government | County Road                                          | None      |             | No offical parking, rough bank access to river                                                |                                                                                                                                                               |                |         |                                                             | Roadside access to river, very limited parking on side of county gravel road.                                                                                                                                                     | I2        | 24000      | No      | No        | Portage                | County Road Access    | 4326353.000 | 508201.638 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518183  | Edward "Ted" and Pat Jones-Confluence Point State Park | RL   | 0.00000    | Government | Missouri Department of Natural Resources State Parks | None      |             | Day use only. Possible exclusion during bald eagle nesting season.                            | http://www.mostateparks.com/confluence.htm                                                                                                                    | (636) 899-1135 |         | http://www.mostateparks.com/confluence/map.htm              | River access involves a short paddle up the Mississippi River for 200 yards (west bank). Need to cross the levy (west bank of Mississippi River) into the State Park parking area.                                                | I2        | 24000      | No      | No        | Portage                | Confluence State Park | 4300570.789 | 750141.648 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518198  | Ramp at Sioux Passage Park                             | RR   | 10.50000   | Government | St. Louis County Parks                               | Improved  |             | Group camping by permit only. Contact county parks.                                           | http://www.co.st-louis.mo.us/parks/sioux.html                                                                                                                 | (314) 615-5000 |         | http://www.co.st-louis.mo.us/parks/locator/SiouxPassage.jpg | Park extends on upstream bank of the chute behind Pelican Island; rampsite leased to MDC, as extension of Pelican Island CA; road access at 17930 Old Jamestown Road 63034. Typical city park with pavillions, etc.               | I2        | 24000      | No      | Yes       | Boat Ramp              | Sioux Passage Park    | 4304786.000 | 736787.000 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518201  | Private Boat Ramp Across River From Pelican Island     | RL   | 12.50000   | Private    | Information Coming ???                               | None      |             | Private ramp, public access not resolved/defined at this point- drop box for fee to use ramp. |                                                                                                                                                               |                |         |                                                             | Private ramp, public access not resolved/defined at this point.                                                                                                                                                                   | I2        | 24000      | No      | Yes       | Boat Ramp              | Private Ramp          | 4307701.198 | 735190.723 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518222  | City of Washington Boat Ramp                           | RR   | 68.30000   | Government | City of Washington                                   | None      | Grocery     | No camping at river front park area.                                                          | http://www.washmo.org/VisitorInfo/index.html                                                                                                                  | (636) 289-7575 |         | http://www.washmo.org/VisitorInfo/maps.html                 | Short walk to town from ramp and riverside park. Historic river town with bed and breakfasts, hotels, restuarants, etc.                                                                                                           | I2        | 24000      | Yes     | Yes       | Boat Ramp              | Washington            | 4269991.268 | 673363.124 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518250  | Noren Access                                           | RL   | 144.00000  | Government | Missouri Department of Conservation                  | Primitive |             |                                                                                               | http://mdc4.mdc.mo.gov/applications/moatlas/AreaSummaryPage.aspx?txtAreaID=200003&txtAreaNm=noren%20access&txtCounty=&txtRegion=&txtUserID=guest&txtDivision= | (573) 884-6861 |         | http://mdc.mo.gov/documents/area_brochures/200003map.pdf    | The Department of Conservation and Jefferson City Parks and Recreation cooperate to provide Carl R. Noren Access on the Missouri River. The access has a ramp and a privy, both disabled-accessible.                              | I2        | 24000      | No      | Yes       | Boat Ramp              | Noren Access          | 4271497.000 | 571496.000 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518258  | Plowboy Bend Conservation Area                         | RR   | 169.00000  | Government | Missouri Department of Conservation                  | Primitive |             | River approached primitive camping.                                                           | http://mdc4.mdc.mo.gov/applications/moatlas/AreaSummaryPage.aspx?txtAreaID=9530&txtAreaNm=plowboy&txtCounty=&txtRegion=&txtUserID=guest&txtDivision=          | (573) 884-6861 |         |                                                             | Extensive conservation area, note some riverside private property, look for conservation area signs. River access camping possible.                                                                                               | I2        | 24000      | No      | No        | Bank access from river | Plowboy Bend CA       | 4294645.104 | 553679.733 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518261  | Coopers Landing                                        | RL   | 170.20000  | Private    | Mike Cooper                                          | Improved  | Convenience | Ramp use fee, pay to camp, restaurant and store open to the public                            | http://www.cooperslanding.net/                                                                                                                                | (573) 657-2554 |         |                                                             | Full service marina, store and local music hangout on the banks of the Missouri river. A local Icon.                                                                                                                              | I2        | 24000      | Yes     | Yes       | Boat Ramp              | Coopers Landing       | 4296546.738 | 553510.864 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518263  | Mouth of Perche Creek (Leading to Providence Access)   | RL   | 170.60000  | Government | Missouri Department of Conservation                  | Primitive |             |                                                                                               | http://mdc4.mdc.mo.gov/applications/moatlas/AreaSummaryPage.aspx?txtAreaID=6905&txtAreaNm=providence&txtCounty=&txtRegion=&txtUserID=guest&txtDivision=       | (573) 884-6861 |         | http://mdc.mo.gov/documents/area_brochures/6905map.pdf      | Possible to paddle 1.25 miles up Creek to Conservation Boat Ramp.                                                                                                                                                                 | I2        | 24000      | No      | Yes       | Boat Ramp              | Perche Creek          | 4297000.981 | 552931.330 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
| 1396518274  | Mouth of Moniteau Creek (Leading to Town of Rocheport) | RL   | 186.50000  | Government | City of Rocheport                                    | None      | Convenience | Both access points are "unofficial" contact 1-800-576-7322 for status pior to use.            | http://www.rocheport.com/ http://www.mighty-mo.com/                                                                                                           | (800) 576-7322 |         |                                                             | Local take out, small dock on south side of creek only 0.2 miles up creek. Short walk to town. Local kayak touring outfitter http://www.mighty-mo.com. Old run down boat ramp located up creek under Katy Trail bridge 0.8 miles. | I2        | 24000      | Yes     | No        | Portage                | Moniteau Creek        | 4313999.000 | 537584.000 | [http://dnr.mo.gov/images/paddling-icon.JPG, null] | 
```