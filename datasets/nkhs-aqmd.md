# Proposals and actions considered by the Boundary Review Board

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposals-and-actions-considered-by-the-boundary-review-board-6b22e) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/nkhs-aqmd) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/nkhs-aqmd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/nkhs-aqmd/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | nkhs-aqmd |
| Name | Proposals and actions considered by the Boundary Review Board |
| Attribution | King County Boundary Review Board |
| Category | Property |
| Tags | boundary review board, boundary review, annexations, annex |
| Created | 2014-01-14T00:50:08Z |
| Publication Date | 2017-04-10T23:39:27Z |

## Description

The current actions section details proposals to and actions considered by the Boundary Review Board in the form of File Summaries. The File Summaries include the actual file numbers of cases currently up for consideration.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | file_no            | File No.           | url           | url           |
| Yes      | series tag  | thomas_guide_map   | Thomas Guide Map   | text          | text          |
| Yes      | time        | date_received      | Date Received      | calendar_date | calendar_date |
| No       |             | date_distributed   | Date Distributed   | calendar_date | calendar_date |
| No       |             | expiration_45_days | Expiration 45 days | calendar_date | calendar_date |
| No       |             | board_meeting      | Board Meeting      | calendar_date | calendar_date |
| Yes      | series tag  | entity             | Entity             | text          | text          |
| Yes      | series tag  | action             | Action             | text          | text          |
| Yes      | series tag  | title              | Title              | text          | text          |
| Yes      | series tag  | view_map_image     | View map image     | url           | url           |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_distributed,expiration_45_days,board_meeting
```

## Data Commands

```ls
series e:nkhs-aqmd d:2013-01-14T00:00:00.000Z t:title="Jones Area Annexation" t:file_no=http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2345.ashx t:entity="City of Redmond" t:action="Resolution for Petition for Land Annexation" t:thomas_guide_map=507 t:view_map_image=http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2345map.ashx m:row_number.nkhs-aqmd=1

series e:nkhs-aqmd d:2013-04-18T00:00:00.000Z t:title="Hawkesbury Annexation" t:file_no=http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2346.ashx t:entity="King County Water District No. 111" t:action="Petition for Annexation to Permit Extension of Water Service Area" t:thomas_guide_map="716, 717" t:view_map_image=http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2346map.ashx m:row_number.nkhs-aqmd=2

series e:nkhs-aqmd d:2013-07-26T00:00:00.000Z t:title="Klahanie Area Annexation (Klahanie, Brookshire Estates. Brookshire Crest, Brookshire East, BrooKshire Ridge, Autumn Glen. Hunter's Lane, Hunter's Place, Hunter's Ridge, Livingston, Pine Classics. Rainbow Lake Ranch, Summer Meadows, Summer Pond, Glenwood, and Eastridge Church)" t:file_no=http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2347.ashx t:entity="City of Issaquah" t:action="Resolution for Land Annexation" t:thomas_guide_map="598, 628" t:view_map_image=http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2347map.ashx m:row_number.nkhs-aqmd=3
```

## Meta Commands

```ls
metric m:row_number.nkhs-aqmd p:long l:"Row Number"

entity e:nkhs-aqmd l:"Proposals and actions considered by the Boundary Review Board" t:attribution="King County Boundary Review Board" t:url=https://data.kingcounty.gov/api/views/nkhs-aqmd

property e:nkhs-aqmd t:meta.view v:id=nkhs-aqmd v:category=Property v:attributionLink=http://www.kingcounty.gov/property/annexations v:averageRating=0 v:name="Proposals and actions considered by the Boundary Review Board" v:attribution="King County Boundary Review Board"

property e:nkhs-aqmd t:meta.view.license v:name="Public Domain"

property e:nkhs-aqmd t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:nkhs-aqmd t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| file_no                                                                                            | thomas_guide_map | date_received       | date_distributed    | expiration_45_days  | board_meeting       | entity                             | action                                                            | title                                                                                                                                                                                                                                                                                | view_map_image                                                                                                | 
| ================================================================================================== | ================ | =================== | =================== | =================== | =================== | ================================== | ================================================================= | ==================================================================================================================================================================================================================================================================================== | ============================================================================================================= | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2345.ashx, 2345 (100KB PDF)]  | 507              | 2013-01-14T00:00:00 | 2013-01-16T00:00:00 | 2013-02-28T00:00:00 | 2013-01-17T00:00:00 | City of Redmond                    | Resolution for Petition for Land Annexation                       | Jones Area Annexation                                                                                                                                                                                                                                                                | [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2345map.ashx, 2345 map (84KB PDF)]  | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2346.ashx, 2346 (98KB PDF)]   | 716, 717         | 2013-04-18T00:00:00 | 2013-04-22T00:00:00 | 2013-06-02T00:00:00 | 2013-05-09T00:00:00 | King County Water District No. 111 | Petition for Annexation to Permit Extension of Water Service Area | Hawkesbury Annexation                                                                                                                                                                                                                                                                | [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2346map.ashx, 2346 map (118KB PDF)] | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2347.ashx, 2347 (587KB PDF)]  | 598, 628         | 2013-07-26T00:00:00 | 2013-07-30T00:00:00 | 2013-09-08T00:00:00 | 2013-08-08T00:00:00 | City of Issaquah                   | Resolution for Land Annexation                                    | Klahanie Area Annexation (Klahanie, Brookshire Estates. Brookshire Crest, Brookshire East, BrooKshire Ridge, Autumn Glen. Hunter's Lane, Hunter's Place, Hunter's Ridge, Livingston, Pine Classics. Rainbow Lake Ranch, Summer Meadows, Summer Pond, Glenwood, and Eastridge Church) | [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2347map.ashx, 2347 map (52KB PDF)]  | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2348.ashx, 2348 (417KB PDF)]  | 653              | 2013-08-16T00:00:00 | 2013-08-20T00:00:00 | 2013-09-30T00:00:00 | 2013-09-12T00:00:00 | King County Water District No. 1   | Petition for Annexation to Permit Extension of Water Service Area | Kiesecker Annexation                                                                                                                                                                                                                                                                 | [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2348map.ashx, 2348 map (79KB PDF)]  | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2349.ashx, 2349 (2.25MB PDF)] | 476              | 2013-09-24T00:00:00 | 2013-09-25T00:00:00 | 2013-11-08T00:00:00 | 2013-10-10T00:00:00 | City of Bothell                    | Interlocal Agreement for Land Annexation                          | Bothell East Area (aka North Bloomberg Hill)                                                                                                                                                                                                                                         | [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2349map.ashx, 2349 map (617KB PDF)] | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/2350.ashx, 2350 (421KB PDF)]  | 628              | 2013-10-21T00:00:00 | 2013-10-23T00:00:00 | 2013-12-01T00:00:00 | 2013-11-06T00:00:00 | City of Issaquah                   | Petition for Land Annexation                                      | City of Issaquah: Issaquah Middle School Annexation (Clark Elementary School & Tiger Mountain Academy)                                                                                                                                                                               | [http://www.kingcounty.gov/~/media/property/annexations/actions/2013/maps/2350map.ashx, 2350 map (114KB PDF)] | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/2352.ashx, 2352 (95KB PDF)]   | 684              | 2014-01-28T00:00:00 | 2014-01-30T00:00:00 | 2014-03-14T00:00:00 | 2014-02-13T00:00:00 | Midway Sewer District              | Annexation by Resolution                                          | Westwood Sewer BLA                                                                                                                                                                                                                                                                   | [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/maps/2352map.ashx, 2352 map (106KB PDF)] | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/2351.ashx, 2351 (111KB PDF)]  | 626              | 2014-01-13T00:00:00 | 2014-01-15T00:00:00 | 2014-02-17T00:00:00 | 2014-02-13T00:00:00 | City of Renton                     | Resolution for Petition for Land Annexation                       | Maertins Area Annexation                                                                                                                                                                                                                                                             | [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/maps/2351map.ashx, 2351 map (199KB PDF)] | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/2353.ashx, 2353 (100KB PDF)]  | 657              | 2014-02-21T00:00:00 | 2014-02-24T00:00:00 | 2014-04-06T00:00:00 | 2014-03-13T00:00:00 | City of Renton                     | Petition for Land Annexation                                      | Alpine Nursery Area Annexation                                                                                                                                                                                                                                                       | [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/maps/2353map.ashx, 2353 map (208KB PDF)] | 
| [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/2355.ashx, 2355 (107KB PDF)]  | 717, 718         | 2014-04-24T00:00:00 | 2014-04-28T00:00:00 | 2014-06-08T00:00:00 | 2014-05-08T00:00:00 | City of Maple Valley               | Interlocal Agreement for Land Annexation                          | Summit Place Area                                                                                                                                                                                                                                                                    | [http://www.kingcounty.gov/~/media/property/annexations/actions/2014/maps/2355map.ashx, 2355 map (243KB PDF)] | 
```