# SSMMA Intermodal Terminals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-intermodal-terminals-f806c) |
| Metadata | [Link](https://data.illinois.gov/api/views/wbks-tkq9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wbks-tkq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wbks-tkq9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wbks-tkq9 |
| Name | SSMMA Intermodal Terminals |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Created | 2012-11-27T19:06:13Z |
| Publication Date | 2012-11-27T19:07:28Z |

## Description

This dataset details Intermodal terminals in the Chicago Southland region.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | series tag     | municipali  | MUNICIPALI | text      | text        |
| Yes      | series tag     | county      | COUNTY     | text      | text        |
| Yes      | series tag     | phone       | PHONE      | text      | text        |
| Yes      | series tag     | mainfax     | MAINFAX    | text      | text        |
| Yes      | series tag     | dispatchfa  | DISPATCHFA | text      | text        |
| Yes      | series tag     | website     | WEBSITE    | text      | text        |
| Yes      | series tag     | contactnum  | CONTACTNUM | text      | text        |
| Yes      | series tag     | descriptio  | DESCRIPTIO | text      | text        |
| Yes      | series tag     | railroad    | RAILROAD   | text      | text        |
| Yes      | numeric metric | editor      | EDITOR     | number    | number      |
| Yes      | series tag     | propreitar  | PROPREITAR | text      | text        |
| Yes      | series tag     | universali  | UNIVERSALI | text      | text        |
| Yes      | series tag     | location_1  | Location 1 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wbks-tkq9 d:2012-11-27T11:06:15.000Z t:phone=(888)-428-2673 t:mainfax=(817)-352-7222 t:website="http://www.loadmatch.com/link_thru.cfm?cID=5954&r=company_detail.cfm&url=http://domino.bnsf.com/website/facility.nsf/PrinterFriendly?open&location=" t:railroad=MJR t:universali=UR t:contactnum=(708)-482-5101 t:county=Cook t:name="BNSF-Willow Springs" t:objectid=1 t:propreitar=UR1 t:location_1="7600 Santa Fe Drive" t:municipali=Hodgkins t:dispatchfa=(708)-482-5189 m:editor=1

series e:wbks-tkq9 d:2012-11-27T11:06:15.000Z t:phone=(708)-957-6590 t:mainfax=(708)-957-6545 t:county=Cook t:website="http://www.loadmatch.com/link_thru.cfm?cID=5984&r=company_detail.cfm&url=http://www.cn.ca/en/shipping-how-intermodal-terminals.htm" t:railroad=MJR t:name=CN-Gateway t:location_1="15840 West Avenue" t:objectid=2 t:universali=UR2 t:municipali=Harvey t:contactnum=(800)-822-6440 m:editor=2

series e:wbks-tkq9 d:2012-11-27T11:06:15.000Z t:phone=(708)-563-1900 t:mainfax=(708)-563-3923 t:county=Cook t:website="http://www.loadmatch.com/link_thru.cfm?cID=6024&r=company_detail.cfm&url=http://www.csxi.com/?fuseaction=customers.terminals" t:railroad=MJR t:name="CSX-Bedford Park" t:location_1="7000 W. 71st Street" t:propreitar=3 t:objectid=3 t:universali=UR3 t:municipali="Bedford Park" m:editor=3
```

## Meta Commands

```ls
metric m:editor p:integer l:EDITOR t:dataTypeName=number

entity e:wbks-tkq9 l:"SSMMA Intermodal Terminals" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/wbks-tkq9

property e:wbks-tkq9 t:meta.view v:id=wbks-tkq9 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Intermodal Terminals" v:attribution="South Suburban Mayors and Managers Association"

property e:wbks-tkq9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:wbks-tkq9 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:wbks-tkq9 t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | objectid | name                     | municipali   | county | phone          | mainfax        | dispatchfa     | website                                                                                                                                             | contactnum     | descriptio | railroad | editor | propreitar | universali | location_1             | 
| =========== | ======== | ======================== | ============ | ====== | ============== | ============== | ============== | =================================================================================================================================================== | ============== | ========== | ======== | ====== | ========== | ========== | ====================== | 
| 1354014375  | 1        | BNSF-Willow Springs      | Hodgkins     | Cook   | (888)-428-2673 | (817)-352-7222 | (708)-482-5189 | http://www.loadmatch.com/link_thru.cfm?cID=5954&r=company_detail.cfm&url=http://domino.bnsf.com/website/facility.nsf/PrinterFriendly?open&location= | (708)-482-5101 |            | MJR      | 1      | UR1        | UR         | 7600 Santa Fe Drive    | 
| 1354014375  | 2        | CN-Gateway               | Harvey       | Cook   | (708)-957-6590 | (708)-957-6545 |                | http://www.loadmatch.com/link_thru.cfm?cID=5984&r=company_detail.cfm&url=http://www.cn.ca/en/shipping-how-intermodal-terminals.htm                  | (800)-822-6440 |            | MJR      | 2      |            | UR2        | 15840 West Avenue      | 
| 1354014375  | 3        | CSX-Bedford Park         | Bedford Park | Cook   | (708)-563-1900 | (708)-563-3923 |                | http://www.loadmatch.com/link_thru.cfm?cID=6024&r=company_detail.cfm&url=http://www.csxi.com/?fuseaction=customers.terminals                        |                |            | MJR      | 3      | 3          | UR3        | 7000 W. 71st Street    | 
| 1354014375  | 4        | IAIS-Blue Island         | Blue Island  | Cook   | (708)-597-0250 | (708)-371-0981 |                | http://www.loadmatch.com/link_thru.cfm?cID=6067&r=company_detail.cfm&url=http://www.iaisrr.com                                                      |                |            | MJR      | 4      |            | UR4        | 2100 Prairie Street    | 
| 1354014375  | 5        | Norfolk Southern-Landers | Chicago      | Cook   | (773)-933-5695 | (773)-933-5611 | (773)-933-5694 | www.nscorp.com/nscintermodal/Intermodal/                                                                                                            |                |            | MJR      | 5      |            | UR5        | 2543 W. Columbus Drive | 
| 1354014375  | 6        | UP-Yard Center           | Dolton       | Cook   | (800)-877-5123 | (708)-201-2253 |                | www.uprr.com/customers/intermodal/intmap                                                                                                            | (708)-201-2330 |            | MJR      | 6      | 6          | UR6        | 147th and Indiana      | 
| 1354014375  | 7        | UP-JIT                   |              | Will   |                |                |                | www.uprr.com/customers/intermodal/intmap                                                                                                            |                |            | MJR      | 7      | 7          | UR7        | 3000 Centerpoint Way   | 
| 1354014375  | 8        | BNSF-Logistics Park      |              | Will   | (888)-428-2673 | (817)-352-7222 | (815)-454-2266 | domino.bnsf.com/website/facility.nsf/PrinterFriendly?open&location=                                                                                 | (815)-454-2225 |            | MJR      | 8      | 8          | UR8        | 26664 Baseline Rd      | 
```