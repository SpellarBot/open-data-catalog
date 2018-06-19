# New&Notable

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/newnotable) |
| Metadata | [Link](https://data.wa.gov/api/views/pws9-gkz8) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/pws9-gkz8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/pws9-gkz8/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | pws9-gkz8 |
| Name | New&Notable |
| Tags | administration, curation |
| Created | 2016-05-06T16:09:57Z |
| Publication Date | 2017-02-17T00:18:31Z |

## Description

Curated list of new and notable datasets, visualizations etc.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type      | Render Type    |
| ======== | =========== | ============= | ============= | ============== | ============== |
| Yes      | series tag  | name          | ItemName      | html           | html           |
| Yes      | series tag  | highlights    | Highlights    | html           | html           |
| Yes      | series tag  | type          | Type          | drop_down_list | drop_down_list |
| Yes      | time        | lastlook      | DateAvailable | calendar_date  | calendar_date  |
| Yes      | series tag  | image         | Image         | photo          | photo          |
| Yes      | series tag  | creator       | Creator       | text           | text           |
| Yes      | series tag  | originator    | Originator    | text           | text           |
| Yes      | series tag  | link          | Link          | url            | url            |
| Yes      | series tag  | contact_email | Contact email | email          | email          |
| Yes      | series tag  | fanname       | FanName       | email          | email          |
| Yes      | series tag  | coolness      | Coolness      | stars          | stars          |
| Yes      | series tag  | show          | Show          | checkbox       | checkbox       |
```

## Time Field

```ls
Value = lastlook
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pws9-gkz8 d:2016-05-16T17:00:00.000Z t:fanname=will.saunders@watech.wa.gov t:name="<p>Medicare recipient demographics in WA</p>" t:link=https://data.wa.gov/Health/Medicare-Beneficiary-Enrollment-and-Demographics-W/9bjy-hi93 t:show=true t:type=n6sz-cyas t:originator=OFM t:creator="Wei Yen" m:coolness=3 m:row_number.pws9-gkz8=1

series e:pws9-gkz8 d:2016-05-20T00:00:00.000Z t:fanname=Will.saunders@watech.wa.gov t:name="<p>Public Lands Inventory</p>" t:link=http://publiclandsinventory.wa.gov/#Map t:image=3a0be552-d2f9-488a-a4cb-750f576629d7 t:show=true t:type=2wur-mgw8 t:originator=RCO t:highlights="<p>Great web-based interactive map of all lands owned by the state.</p>" m:coolness=4 m:row_number.pws9-gkz8=2

series e:pws9-gkz8 d:2016-05-20T00:00:00.000Z t:fanname=will.saunders@watech.wa.gov t:name="<p>Facilities Inventory</p>" t:link="http://wa-ofm.maps.arcgis.com/home/group.html?id=b0b23a7d8523438da752f6d6a9671e4b" t:image=c5804484-03d6-43c2-aa6e-30fa37ff908f t:show=true t:type=2wur-mgw8 t:originator=OFM t:highlights="<p>State facilities maps by county, agency, etc.</p>" m:coolness=3 m:row_number.pws9-gkz8=3
```

## Meta Commands

```ls
metric m:row_number.pws9-gkz8 p:long l:"Row Number"

entity e:pws9-gkz8 l:New&Notable t:url=https://data.wa.gov/api/views/pws9-gkz8

property e:pws9-gkz8 t:meta.view v:id=pws9-gkz8 v:averageRating=0 v:name=New&Notable

property e:pws9-gkz8 t:meta.view.license v:name="Public Domain"

property e:pws9-gkz8 t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:pws9-gkz8 t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| name                                        | highlights                                                                                                                                                                                                                                                                                                                                                                                                                      | type      | lastlook            | image                                | creator           | originator        | link                                                                                                                            | contact_email | fanname                     | coolness | show | 
| =========================================== | =============================================================================================================================================================================================================================================================================================================================================================================================================================== | ========= | =================== | ==================================== | ================= | ================= | =============================================================================================================================== | ============= | =========================== | ======== | ==== | 
| Medicare recipient demographics in WA       |                                                                                                                                                                                                                                                                                                                                                                                                                                 | n6sz-cyas | 2016-05-16T17:00:00 |                                      | Wei Yen           | OFM               | [https://data.wa.gov/Health/Medicare-Beneficiary-Enrollment-and-Demographics-W/9bjy-hi93, null]                                 |               | will.saunders@watech.wa.gov | 3        | true | 
| Public Lands Inventory                      | Great web-based interactive map of all lands owned by the state.                                                                                                                                                                                                                                                                                                                                                                | 2wur-mgw8 | 2016-05-20T00:00:00 | 3a0be552-d2f9-488a-a4cb-750f576629d7 |                   | RCO               | [http://publiclandsinventory.wa.gov/#Map, null]                                                                                 |               | Will.saunders@watech.wa.gov | 4        | true | 
| Facilities Inventory                        | State facilities maps by county, agency, etc.                                                                                                                                                                                                                                                                                                                                                                                   | 2wur-mgw8 | 2016-05-20T00:00:00 | c5804484-03d6-43c2-aa6e-30fa37ff908f |                   | OFM               | [http://wa-ofm.maps.arcgis.com/home/group.html?id=b0b23a7d8523438da752f6d6a9671e4b, null]                                       |               | will.saunders@watech.wa.gov | 3        | true | 
| I-405 traffic data sample                   | WSDOT published a cool assortment of travel time data for I-405 a while back; not a ton of promotion of the dataset, but it's out there for folks to explore (here's a link). Now it looks like that posting has inspired one of the community of Tableau Public users to do just that -- explore the data with a different visual (embedded below).  Cool example of how even a dense set of data can attract public interest. | n6sz-cyas | 2016-01-13T00:00:00 | 2bb0ecad-a085-402a-a603-b7b75aa95760 |                   | WSDOT             | [https://public.tableau.com/views/WSDOTI-405ETLTravelTimes/Sheet1?:embed=y&:loadOrderID=0&:display_count=yes&:showTabs=y, null] |               | Will.saunders@watech.wa.gov |          |      | 
| Crash Data Portal from WSDOT                | DOT has a new portal for reporting crash data from around the state - by type of road, by year and so on.                                                                                                                                                                                                                                                                                                                       | fnga-mes7 | 2016-07-07T00:00:00 | 7a351190-6164-4161-9854-00d32be1985d | Ida van Schalkwyk | WSDOT             | [https://remoteapps.wsdot.wa.gov/HighwaySafety/Collision/Data/Portal/Public/, null]                                             |               | will.saunders@watech.wa.gov | 3        | true | 
| Consumer complaints to the Attorney General |                                                                                                                                                                                                                                                                                                                                                                                                                                 | n6sz-cyas | 2016-05-06T00:00:00 |                                      |                   | ATG               | [https://data.wa.gov/dataset/Attorney-General-Consumer-Complaints/gpri-47xz, null]                                              |               | will.saunders@watech.wa.gov |          |      | 
| White House Salary data                     | Federal salaries                                                                                                                                                                                                                                                                                                                                                                                                                | n6sz-cyas | 2017-02-16T00:00:00 |                                      |                   | National Archives | [https://open.obamawhitehouse.archives.gov/search/type/dataset, null]                                                           |               | will.saunders@watech.wa.gov | 2        | true | 
```