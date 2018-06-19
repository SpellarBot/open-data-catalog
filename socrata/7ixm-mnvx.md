# 311 Citizen Requests for Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-citizen-requests-for-service) |
| Metadata | [Link](https://data.brla.gov/api/views/7ixm-mnvx) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/7ixm-mnvx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/7ixm-mnvx/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 7ixm-mnvx |
| Name | 311 Citizen Requests for Service |
| Attribution | Public Works Business Office |
| Category | Government |
| Tags | request, service, 311, public works |
| Created | 2016-10-05T14:36:26Z |
| Publication Date | 2016-11-05T16:06:34Z |

## Description

This dataset includes all requests for service received from the City-Parish 311 Call Center, including requests for service submitted online and through the Red Stick 311 mobile application, dating back to January 1, 2016. Submitter names, phone numbers, and e-mail addresses are redacted for privacy purposes. Data is updated daily from the Public Works Business Office and 311 Call Center.

Phone numbers are redacted to protect the contact information and privacy of citizens by replacing raw digits with XXX-XXX-XXXX. For any questions about this process, please contact opendata@brgov.com.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                     | Data Type     | Render Type   |
| ======== | ============== | ============= | ======================== | ============= | ============= |
| No       |                | id            | SERVICE REQUEST ID       | text          | text          |
| Yes      | series tag     | statusdesc    | STATUS                   | text          | text          |
| Yes      | time           | createdate    | CREATE DATE              | calendar_date | calendar_date |
| No       |                | closeddate    | CLOSE DATE               | calendar_date | calendar_date |
| No       |                | lastaction    | LAST ACTION DATE         | calendar_date | calendar_date |
| Yes      | series tag     | parenttype    | PARENT TYPE              | text          | text          |
| Yes      | series tag     | typename      | TYPE                     | text          | text          |
| Yes      | series tag     | comments      | COMMENTS                 | text          | text          |
| Yes      | series tag     | streetnum     | STREET NUMBER            | text          | text          |
| Yes      | series tag     | streetname    | STREET NAME              | text          | text          |
| No       |                | streetaddress | FULL ADDRESS             | text          | text          |
| Yes      | series tag     | crossname     | CROSS STREET             | text          | text          |
| Yes      | series tag     | cityname      | CITY                     | text          | text          |
| Yes      | series tag     | department    | DEPARTMENT               | text          | text          |
| Yes      | series tag     | division      | DIVISION                 | text          | text          |
| No       |                | latitude      | LATITUDE                 | number        | number        |
| No       |                | longitude     | LONGITUDE                | number        | number        |
| Yes      | series tag     | typeid        | TYPEI D                  | text          | text          |
| Yes      | series tag     | parentid      | PARENT ID                | text          | text          |
| Yes      | series tag     | deptdivid     | DEPTDIV ID               | text          | text          |
| Yes      | series tag     | deptdiv       | DEPARTMENT-DIVISION NAME | text          | text          |
| Yes      | numeric metric | status        | STATUS ID                | number        | text          |
```

## Time Field

```ls
Value = createdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,closeddate,lastaction,streetaddress,latitude,longitude
```

## Data Commands

```ls
series e:7ixm-mnvx d:2016-01-05T11:15:00.000Z t:streetnum=3452 t:department="ENVIRONMENTAL SERVICES" t:parentid=172975 t:deptdivid=57 t:parenttype=GARBAGE t:division=SANITATION t:deptdiv="DES - SANITATION" t:typename="DAMAGED GARBAGE CART" t:typeid=173020 t:cityname="BATON ROUGE" t:statusdesc=CLOSED t:comments="REPLACE 96 GALLON CART LID" t:streetname="MAIN ST" m:status=1

series e:7ixm-mnvx d:2016-01-06T03:55:00.000Z t:streetnum=14846 t:department="ENVIRONMENTAL SERVICES" t:parentid=172975 t:deptdivid=57 t:parenttype=GARBAGE t:division=SANITATION t:deptdiv="DES - SANITATION" t:typename="MISSING GARBAGE CART" t:typeid=173028 t:cityname=CENTRAL t:statusdesc=CLOSED t:comments="CALLER 96 GAL CART WAS STOLEN FILE#16-01087" t:streetname="HOOPER RD" m:status=1

series e:7ixm-mnvx d:2016-01-12T07:33:00.000Z t:streetnum=2933 t:department=MAINTENANCE t:parentid=172975 t:deptdivid=63 t:parenttype=GARBAGE t:division="LANDSCAPE MAINTENANCE" t:deptdiv="DOM - LANDSCAPE MAINTENANCE" t:typename="REQUEST DEBRIS REMOVAL - PUBLIC PROPERTY" t:typeid=174362 t:cityname="BATON ROUGE" t:statusdesc=CLOSED t:comments="THERE IS A LARGE PILE OF TRASH NEXT TO THE STREET TO THE RIGHT OF 2939 MIDWAY AVE. I SUSPECT IT CAME FROM 2939 MIDWAY BECAUSE THEY ARE WORKING ON IT. IT IS AT LOT 25 SQUARE 1 MIDWAY PLACE." t:streetname="MIDWAY AVE" m:status=1
```

## Meta Commands

```ls
metric m:status p:integer l:"STATUS ID" d:"Status of service request 0 = Open, 1 = Closed, 3 = In Progress." t:dataTypeName=number

entity e:7ixm-mnvx l:"311 Citizen Requests for Service" t:attribution="Public Works Business Office" t:url=https://data.brla.gov/api/views/7ixm-mnvx

property e:7ixm-mnvx t:meta.view v:id=7ixm-mnvx v:category=Government v:attributionLink=http://311.brla.gov v:averageRating=0 v:name="311 Citizen Requests for Service" v:attribution="Public Works Business Office"

property e:7ixm-mnvx t:meta.view.license v:name="Public Domain"

property e:7ixm-mnvx t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:7ixm-mnvx t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| id     | statusdesc  | createdate          | closeddate          | lastaction          | parenttype              | typename                                   | comments                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | streetnum | streetname   | streetaddress     | crossname | cityname    | department             | division              | latitude  | longitude  | typeid | parentid | deptdivid | deptdiv                     | status | 
| ====== | =========== | =================== | =================== | =================== | ======================= | ========================================== | =================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========= | ============ | ================= | ========= | =========== | ====================== | ===================== | ========= | ========== | ====== | ======== | ========= | =========================== | ====== | 
| 207364 | CLOSED      | 2016-01-05T11:15:00 | 2016-01-12T04:53:00 | 2016-01-12T04:53:00 | GARBAGE                 | DAMAGED GARBAGE CART                       | REPLACE 96 GALLON CART LID                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 3452      | MAIN ST      | 3452 MAIN ST      |           | BATON ROUGE | ENVIRONMENTAL SERVICES | SANITATION            | 30.452316 | -91.154236 | 173020 | 172975   | 57        | DES - SANITATION            | 1      | 
| 207423 | CLOSED      | 2016-01-06T03:55:00 | 2016-01-12T04:23:00 | 2016-01-12T04:23:00 | GARBAGE                 | MISSING GARBAGE CART                       | CALLER 96 GAL CART WAS STOLEN FILE#16-01087                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 14846     | HOOPER RD    | 14846 HOOPER RD   |           | CENTRAL     | ENVIRONMENTAL SERVICES | SANITATION            | 30.559675 | -91.023949 | 173028 | 172975   | 57        | DES - SANITATION            | 1      | 
| 208375 | CLOSED      | 2016-01-12T07:33:00 | 2016-02-22T08:36:00 | 2016-02-22T08:36:00 | GARBAGE                 | REQUEST DEBRIS REMOVAL - PUBLIC PROPERTY   | THERE IS A LARGE PILE OF TRASH NEXT TO THE STREET TO THE RIGHT OF 2939 MIDWAY AVE. I SUSPECT IT CAME FROM 2939 MIDWAY BECAUSE THEY ARE WORKING ON IT. IT IS AT LOT 25 SQUARE 1 MIDWAY PLACE.                                                                                                                                                                                                                                                                                                        | 2933      | MIDWAY AVE   | 2933 MIDWAY AVE   |           | BATON ROUGE | MAINTENANCE            | LANDSCAPE MAINTENANCE | 30.477669 | -91.160149 | 174362 | 172975   | 63        | DOM - LANDSCAPE MAINTENANCE | 1      | 
| 208376 | CLOSED      | 2016-01-12T07:34:00 | 2016-01-19T03:20:00 | 2016-01-19T03:20:00 | GARBAGE                 | MISSING GARBAGE CART                       | 96 GALLON CART FELL INTO ALLIED TRUCK                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 10146     | ARDOON DR    | 10146 ARDOON DR   |           | BAKER       | ENVIRONMENTAL SERVICES | SANITATION            | 30.540127 | -91.090378 | 173028 | 172975   | 57        | DES - SANITATION            | 1      | 
| 208647 | CLOSED      | 2016-01-13T11:57:00 | 2016-01-19T05:07:00 | 2016-01-19T05:07:00 | RECYCLING               | MISSED RECYCLING SERVICE                   | MISSED RECYCLE P/U FOR FOUR WEEKS ON BLOUIN ROAD                                                                                                                                                                                                                                                                                                                                                                                                                                                    |           | BLOUIN RD    | BLOUIN RD         |           | BATON ROUGE | ENVIRONMENTAL SERVICES | RECYCLING             | 30.478697 | -90.99752  | 173063 | 172979   | 56        | DES - RECYCLING             | 1      | 
| 208713 | IN PROGRESS | 2016-01-14T05:49:00 |                     | 2016-01-20T03:49:00 | BLIGHTED PROPERTIES     | JUNK, TRASH, OR DEBRIS ON PRIVATE PROPERTY | JUNK AND DEBRIS ON VACANT LOT TO THE LEFT OF 2847 PLANK RD NEED TO BE REMOVED                                                                                                                                                                                                                                                                                                                                                                                                                       |           | PLANK RD     | PLANK RD          | OSAGE ST  | BATON ROUGE | DEVELOPMENT            | BLIGHT ENFORCEMENT    | 30.474285 | -91.162033 | 172985 | 172971   | 59        | DOD - BLIGHT ENFORCEMENT    | 3      | 
| 208716 | CLOSED      | 2016-01-14T05:58:00 | 2016-01-20T04:18:00 | 2016-01-20T04:18:00 | GARBAGE                 | DAMAGED GARBAGE CART                       | WHEEL REPLACEMENT FOR 96 GAL CART                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 3236      | HYACINTH AVE | 3236 HYACINTH AVE |           | BATON ROUGE | ENVIRONMENTAL SERVICES | SANITATION            | 30.416927 | -91.159317 | 173020 | 172975   | 57        | DES - SANITATION            | 1      | 
| 209280 | CLOSED      | 2016-01-19T08:14:00 | 2016-01-22T09:31:00 | 2016-01-22T09:31:00 | RECYCLING               | MISSED RECYCLING SERVICE                   | DISABLED CUSTOMER; RECYCLING MISSED ON FRIDAY                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 2638      | ADAMS AVE    | 2638 ADAMS AVE    |           | BATON ROUGE | ENVIRONMENTAL SERVICES | RECYCLING             | 30.468241 | -91.162239 | 173063 | 172979   | 56        | DES - RECYCLING             | 1      | 
| 209293 | CLOSED      | 2016-01-19T08:41:00 | 2016-02-05T04:44:00 | 2016-02-05T04:44:00 | RECYCLING               | STOLEN RECYCLING CART                      | NO LONGER HAVE A RECYCLE CART                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 5730      | N SHORE DR   | 5730 N SHORE DR   |           | BATON ROUGE | ENVIRONMENTAL SERVICES | RECYCLING             | 30.402842 | -90.982193 | 173068 | 172979   | 56        | DES - RECYCLING             | 1      | 
| 209450 | CLOSED      | 2016-01-20T04:37:00 | 2016-03-30T09:59:00 | 2016-03-30T09:59:00 | ROAD MAINTENANCE ISSUES | SHOULDER REPAIR NEEDED                     | THERE IS DAMAGE TO THE SHOULDER IN FRONT OF MY ESTABLISHMENT THAT IS CAPABLE OF DOING DAMAGE TO THE CARS OF MY CUSTOMERS ENTERING THE RESTAURANT. PLEASE SEND SOMEONE TO ASSESS AND CORRECT THE SITUATIONS. THERE ARE SIGNIFICANT TIRE RUTS FROM 18 WHEELERS THAT AT DUSK CANNOT BE SEEN BY THOSE PULLING INTO MY PARKING LOT, AND THERE IS A HOLE CAPABLE OF DOING MAJOR FRONT END DAMAGE TO A CAR THAT CAN RESULT IN BODILY INJURY AS IT CANNOT BE EASILY SEEN WHEN PULLING INTO THE PARKING LOT. | 8334      | AIRLINE HWY  | 8334 AIRLINE HWY  |           | BATON ROUGE | MAINTENANCE            | STREET MAINTENANCE    | 30.460089 | -91.101097 | 173076 | 172980   | 64        | DOM - STREET MAINTENANCE    | 1      | 
```