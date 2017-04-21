# Public Right Of Way Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-right-of-way-permits-ebaed) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/2b9e-mbxk) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/2b9e-mbxk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/2b9e-mbxk/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 2b9e-mbxk |
| Name | Public Right Of Way Permits |
| Category | Licenses/Permits |
| Tags | permit, right of way, residential |
| Created | 2013-06-12T01:40:52Z |
| Publication Date | 2014-03-12T15:49:34Z |

## Description

Data for all Public Right of Way Permit applications, including status and work performed. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                    | Data Type     | Render Type   |
| ======== | ============== | =============== | ======================= | ============= | ============= |
| Yes      | series tag     | applicationtype | Application Type        | text          | text          |
| Yes      | series tag     | permitno        | Permit Number           | text          | text          |
| Yes      | series tag     | worktype        | Work Type               | text          | text          |
| Yes      | series tag     | usecode         | Use Code                | text          | text          |
| Yes      | time           | addeddate       | Added Date              | calendar_date | calendar_date |
| No       |                | issueddate      | Issue Date              | calendar_date | calendar_date |
| No       |                | finaleddate     | Final Date              | calendar_date | calendar_date |
| Yes      | series tag     | status          | Status                  | text          | text          |
| Yes      | series tag     | description     | Description of Location | text          | text          |
| Yes      | series tag     | stno            | Street Number           | text          | text          |
| Yes      | series tag     | predir          | Pre-direction           | text          | text          |
| Yes      | series tag     | stname          | Street Name             | text          | text          |
| Yes      | series tag     | suffix          | Street Suffix           | text          | text          |
| Yes      | series tag     | postdir         | Post-direction          | text          | text          |
| Yes      | series tag     | city            | City                    | text          | text          |
| Yes      | series tag     | state           | State                   | text          | text          |
| Yes      | series tag     | zip             | ZIP Code                | text          | number        |
| Yes      | series tag     | descoflocation  | Work Location           | text          | text          |
| Yes      | series tag     | allegheny       | ALLEGHENY               | text          | text          |
| Yes      | series tag     | bge             | BGE                     | text          | text          |
| Yes      | series tag     | comcast         | COMCAST                 | text          | text          |
| Yes      | series tag     | pepco           | PEPCO                   | text          | text          |
| Yes      | numeric metric | bus_shelter     | BUS_SHELTER             | number        | text          |
| Yes      | series tag     | verizon         | VERIZON                 | text          | text          |
| Yes      | series tag     | wgl             | WGL                     | text          | text          |
| Yes      | series tag     | wssc            | WSSC                    | text          | text          |
```

## Time Field

```ls
Value = addeddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issueddate,finaleddate
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:bus_shelter p:integer l:BUS_SHELTER d:"Project/plan number provided by the utility/agency that constructed bus shelters within the County on the Public Right-of-Way application for use in correlating the DPS permit to their project/plan." t:dataTypeName=number

entity e:2b9e-mbxk l:"Public Right Of Way Permits" t:url=https://data.montgomerycountymd.gov/api/views/2b9e-mbxk

property e:2b9e-mbxk t:meta.view v:id=2b9e-mbxk v:category=Licenses/Permits v:averageRating=0 v:name="Public Right Of Way Permits"

property e:2b9e-mbxk t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:2b9e-mbxk t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| applicationtype     | permitno | worktype                | usecode        | addeddate           | issueddate          | finaleddate         | status    | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | stno  | predir | stname      | suffix | postdir | city          | state | zip   | descoflocation                                                                      | allegheny | bge | comcast | pepco | bus_shelter | verizon | wgl | wssc | 
| =================== | ======== | ======================= | ============== | =================== | =================== | =================== | ========= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ===== | ====== | =========== | ====== | ======= | ============= | ===== | ===== | =================================================================================== | ========= | === | ======= | ===== | =========== | ======= | === | ==== | 
| PUBLIC RIGHT OF WAY | 202813   | CONSTRUCT               | DRIVEWAY       | 2000-01-14T01:01:57 | 2000-01-18T09:01:00 | 2000-04-05T03:04:59 | Completed | Construct the following type driveway in accordance with Montgomery County Standards and Specifications and the direction of the DPS Inspector. All future maintenance of this apron will be the responsibility of the property owner. MCDOT Standard: MC301.01 No pipe required.                                                                                                                                                                                                                                                                                                                                                                                                              | 9302  |        | CEDAR       | LN     |         | BETHESDA      | MD    | 20814 |                                                                                     |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 218818   | INSTALL                 | PUBLIC UTILITY | 2002-09-20T09:09:30 | 2002-10-04T09:10:00 | 2016-04-20T11:04:34 | Finaled   | >>> PRE-CONSTRUCTION MEETING REQUIRED >> PRE-CONSTRUCTION MEETING REQUIRED > PRE-CONSTRUCTION MEETING REQUIRED PRE-CONSTRUCTION MEETING REQUIRED <<< CONTACT MC.DPS INSPECTOR BOB BUCKLIN @ 301-370-3683 Build conduit to cut the roadway, install cable, replace overhead secondary wire and associated overhead and underground equipment. UTILITY REPRESENTATIVE: BOBBY DICKEY @ 301-931-2821                                                                                                                                                                                                                                                                                               |       |        |             |        |         |               |       |       | ROSEDALE AVENUE - BETHESDA                                                          |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 243354   | CONSTRUCT               | PAVING         | 2006-02-15T10:02:14 | 2006-04-28T03:04:00 |                     | Issued    | PAVING PERMIT: Construct concrete sidewalk, concrete curb and gutter, driveway aprons, sidewalk and street paving as per aproved Montgomery County Standards and Specifications and approved plans. Install street lights in accordance with plans to be approved by the Division of Traffic and Parking Services, Montgomery county Department of Public Works and Transportation. Plant street trees in accordance with Montgomery County Code Section 49-35(j)(i). Pleace permanent reference monuments and property line markers on all lots and parcels abutting the streets covered by this permit per Section 50-24(e) of the Montgomery county Code. All unpaved areas will be sodded. |       |        |             |        |         |               |       |       | PETWYN COURT: FROM STA.0+00 TO STA.2+55.65. NOTLEY ROAD: FROM STA.1+00 TO STA.6+50. |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 202832   | CONSTRUCT               | DRIVEWAY       | 2000-01-18T02:01:14 | 2000-01-20T09:01:00 | 2000-04-04T10:04:18 | Completed | Construct the following type driveway in accordance with Montgomery County Standards and Specifications and the direction of the DPS Inspector. All future maintenance of this apron will be the responsibility of the property owner. MCDOT Standard: MC301.01 Grade side slopes at a maximum 3:1 as directed.                                                                                                                                                                                                                                                                                                                                                                                | 12604 |        | DENLEY      | RD     |         | SILVER SPRING | MD    | 20906 |                                                                                     |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 202875   | CONSTRUCT               | DRIVEWAY       | 2000-01-20T11:01:05 | 2000-01-24T02:01:00 | 2000-02-23T10:02:21 | Completed | Construct the following type driveway in accordance with Montgomery County Standards and Specifications and the direction of the DPS Inspector. All future maintenance of this apron will be the responsibility of the property owner. MCDOT Standard: MC301.01                                                                                                                                                                                                                                                                                                                                                                                                                                | 10703 |        | MALONE      | ST     |         | SILVER SPRING | MD    | 20902 |                                                                                     |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 202911   | PLACE                   | DUMPSTER       | 2000-01-21T08:01:43 | 2000-01-21T10:01:00 | 2000-06-05T12:06:36 | Completed | Temporarily place a dumpster within the public right of way. The permittee agrees to hold Montgomery County harmless from any liability associated with the placement of the dumpster in the public right of way. Dumpster locations, barricades and/or lights are to be placed as directed by the DPS Inspector.                                                                                                                                                                                                                                                                                                                                                                              | 2717  |        | DANIEL      | RD     |         | CHEVY CHASE   | MD    | 20815 |                                                                                     |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 202933   | REMOVE                  | DRIVEWAY       | 2000-01-24T09:01:43 | 2000-01-24T10:01:00 | 2001-09-24T03:09:00 | Completed | Restore right of way. Complete repair (restoration of right of way) shall be made of any and all damages done to the existing improvements in the public right of way caused by construction operations on this site. Field Connection 15" RCP into existing structure. Plant 28 Street Trees. Remove existing Driveway restore area.                                                                                                                                                                                                                                                                                                                                                          | 12530 |        | PARKLAWN    | DR     |         | ROCKVILLE     | MD    | 20852 |                                                                                     |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 244232   | RESTORE AND / OR REPAIR | PUBLIC UTILITY | 2006-03-15T02:03:49 | 2006-03-15T03:03:00 | 2016-09-08T01:09:28 | Finaled   | SHELTER 5484/WB ROCK SPRING DRIVE/FS OLD GEORGETOWN ROAD/BETHESDA, MD 20814/CLEAR CHANNEL-RIDE ON BAY BUS SHELTER/RESTORATION-REPAIR:Complete repair (restoration of right of way) shall be made of any and all damages done to the existing improvements in the public right of way caused by construction on this site.NOTIFY MISS UTILITY PRIOR TO PRE CONSTRUCTION MEETINGPRE CONSTRUCTION MEETING REQUIREDCONTACT MCDPS INSPECTOR BOB BUCKLIN ON 301-370-3683 BEFORE AND AFTER INSTALLATION                                                                                                                                                                                               |       |        |             |        |         |               |       |       | WB ROCK SPRING DRIVE/FS OLD GEORGETOWN ROAD/BETHESDA, MD 20814                      |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 202936   | INSTALL                 | PUBLIC UTILITY | 2000-01-24T12:01:08 | 2000-01-27T09:01:00 | 2001-05-30T10:05:36 | Completed | Restore right of way. Complete repair (restoration of right of way) shall be made of any and all damages done to the existing improvements in the public right of way caused by construction operations on this site. Install 6" water and 4" sewer connections.                                                                                                                                                                                                                                                                                                                                                                                                                               | 12020 |        | CHERRY HILL | RD     |         | SILVER SPRING | MD    | 20904 |                                                                                     |           |     |         |       |             |         |     |      | 
| PUBLIC RIGHT OF WAY | 218693   | INSTALL                 | PUBLIC UTILITY | 2002-09-11T10:09:12 | 2002-09-12T10:09:00 | 2016-07-01T09:07:46 | Finaled   | Bore roadway, install, remove wire and OH, UG associated equipment, also perform a 1' x 1' cut to check for other utilities. Plan No. 5722297, contact person is Roberta Dickey at 301-931-2821.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |       |        |             |        |         |               |       |       | BALTIMORE AVENUE                                                                    |           |     |         |       |             |         |     |      | 
```