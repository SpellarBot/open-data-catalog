# Special Protection Area Review Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/special-protection-area-review-data) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/p4x2-jhaf) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/p4x2-jhaf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/p4x2-jhaf/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | p4x2-jhaf |
| Name | Special Protection Area Review Data |
| Category | Licenses/Permits |
| Tags | permit, water, sensitive water resources, environmental features, proposed land development, water quality, protection measures, spa |
| Created | 2015-03-25T00:05:37Z |
| Publication Date | 2015-03-25T13:29:43Z |

## Description

A Special Protection Area (SPA) is a geographic area designated by the County Council which has high quality or unusually sensitive water resources and environmental features that would be threatened by proposed land development if special water quality protection measures were not applied.  This dataset tracks reviews for development in all SPAs. Update Frequency : Daily.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | applicationtype         | Application Type        | text          | text          |
| Yes      | series tag     | application_no          | Application Number      | text          | text          |
| Yes      | time           | process_date            | Processed Date          | calendar_date | calendar_date |
| No       |                | approveddate            | Approved Date           | calendar_date | calendar_date |
| Yes      | series tag     | projname                | Project Name            | text          | text          |
| Yes      | series tag     | description             | Description             | text          | text          |
| Yes      | series tag     | stno                    | Street Number           | text          | text          |
| Yes      | series tag     | predir                  | Pre-direction           | text          | text          |
| Yes      | series tag     | stname                  | Street Name             | text          | text          |
| Yes      | series tag     | suffix                  | Street Suffix           | text          | text          |
| Yes      | series tag     | postdir                 | Post-direction          | text          | text          |
| Yes      | series tag     | city                    | City                    | text          | text          |
| Yes      | series tag     | state                   | State                   | text          | text          |
| Yes      | series tag     | zip                     | ZIP code                | text          | number        |
| Yes      | series tag     | location                | Work Location           | text          | text          |
| Yes      | series tag     | wssc_grid               | WSSC Grid               | text          | text          |
| Yes      | series tag     | tax_map                 | Tax Map                 | text          | text          |
| Yes      | numeric metric | site_area               | Site Area               | number        | number        |
| Yes      | numeric metric | proposed_disturbed_area | Proposed Disturbed Area | number        | number        |
| Yes      | series tag     | current_zoning          | Current Zoning          | text          | text          |
| Yes      | series tag     | proposed_zoing          | Proposed Zoning         | text          | text          |
| Yes      | series tag     | current_land_use        | Current Land use        | text          | text          |
| Yes      | series tag     | proposed_land_use       | Proposed Land Use       | text          | text          |
| Yes      | series tag     | watershed               | Watershed               | text          | text          |
| Yes      | series tag     | tributary               | Tributary               | text          | text          |
| Yes      | series tag     | protection_area         | Protection Area         | text          | text          |
| Yes      | series tag     | state_water_use         | State Water Use         | text          | text          |
```

## Time Field

```ls
Value = process_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = approveddate
```

## Data Commands

```ls
series e:p4x2-jhaf d:2008-06-30T00:00:00.000Z t:stno=1234 t:zip=20905 t:proposed_zoing=RE-1 t:current_land_use=RES t:state=MD t:protection_area=SPA-UPB t:current_zoning=RE-1 t:stname="BRIGGS CHANEY" t:projname="ECO ESTATES" t:tax_map=JS561 t:suffix=RD t:wssc_grid=220NE01 t:city="SILVER SPRING" t:watershed=PBR t:application_no=233949 t:applicationtype="SPECIAL PROTECTION AREA" t:proposed_land_use=RES t:state_water_use=III t:tributary="LEFT FORK" m:site_area=13 m:proposed_disturbed_area=6.1

series e:p4x2-jhaf d:2009-09-25T00:00:00.000Z t:watershed=LSC t:proposed_zoing=MXPD t:application_no=236690 t:applicationtype="SPECIAL PROTECTION AREA" t:proposed_land_use=AGRICULT t:location="WEST OLD BALTIMORE, I-270 AND CLARKSBURG" t:current_land_use=AGRICULT t:current_zoning=MXPD t:projname="CABIN BRANCH-WINCHESTER PHAS" t:tax_map=FU562 t:wssc_grid=231NW13 m:site_area=9.2 m:proposed_disturbed_area=9.2

series e:p4x2-jhaf d:2011-04-11T00:00:00.000Z t:proposed_zoing=MXPD t:location="SOUTHWEST QUADRANT, INTERSECTION OF I-270 & CLARKSBURG ROAD" t:current_land_use=VACANT t:protection_area=SPA-CB t:current_zoning=MXPD t:tax_map=EV23 t:projname="CABIN BRANCH-WINCHESTER 2" t:wssc_grid=230NW13 t:watershed=LSC t:application_no=239941 t:applicationtype="SPECIAL PROTECTION AREA" t:proposed_land_use=SFD t:state_water_use=IV m:site_area=38.2 m:proposed_disturbed_area=0
```

## Meta Commands

```ls
metric m:site_area p:float l:"Site Area" d:"The number of acres for the proposed Special Protection Area ." t:dataTypeName=number

metric m:proposed_disturbed_area p:float l:"Proposed Disturbed Area" d:"The number of acres disturbed for the proposed Special Protection Area ." t:dataTypeName=number

entity e:p4x2-jhaf l:"Special Protection Area Review Data" t:url=https://data.montgomerycountymd.gov/api/views/p4x2-jhaf

property e:p4x2-jhaf t:meta.view v:id=p4x2-jhaf v:category=Licenses/Permits v:averageRating=0 v:name="Special Protection Area Review Data"

property e:p4x2-jhaf t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:p4x2-jhaf t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| applicationtype         | application_no | process_date        | approveddate        | projname                          | description | stno | predir | stname        | suffix | postdir | city          | state | zip   | location                                                    | wssc_grid | tax_map | site_area | proposed_disturbed_area | current_zoning | proposed_zoing | current_land_use | proposed_land_use | watershed | tributary | protection_area | state_water_use | 
| ======================= | ============== | =================== | =================== | ================================= | =========== | ==== | ====== | ============= | ====== | ======= | ============= | ===== | ===== | =========================================================== | ========= | ======= | ========= | ======================= | ============== | ============== | ================ | ================= | ========= | ========= | =============== | =============== | 
| SPECIAL PROTECTION AREA | 233949         | 2008-06-30T00:00:00 |                     | ECO ESTATES                       |             | 1234 |        | BRIGGS CHANEY | RD     |         | SILVER SPRING | MD    | 20905 |                                                             | 220NE01   | JS561   | 13        | 6.1                     | RE-1           | RE-1           | RES              | RES               | PBR       | LEFT FORK | SPA-UPB         | III             | 
| SPECIAL PROTECTION AREA | 236690         | 2009-09-25T00:00:00 |                     | CABIN BRANCH-WINCHESTER PHAS      |             |      |        |               |        |         |               |       |       | WEST OLD BALTIMORE, I-270 AND CLARKSBURG                    | 231NW13   | FU562   | 9.2       | 9.2                     | MXPD           | MXPD           | AGRICULT         | AGRICULT          | LSC       |           |                 |                 | 
| SPECIAL PROTECTION AREA | 239941         | 2011-04-11T00:00:00 | 2013-05-02T00:00:00 | CABIN BRANCH-WINCHESTER 2         |             |      |        |               |        |         |               |       |       | SOUTHWEST QUADRANT, INTERSECTION OF I-270 & CLARKSBURG ROAD | 230NW13   | EV23    | 38.2      | 0                       | MXPD           | MXPD           | VACANT           | SFD               | LSC       |           | SPA-CB          | IV              | 
| SPECIAL PROTECTION AREA | 241081         | 2011-09-20T00:00:00 |                     | GARNKIRK FARMS                    |             |      |        |               |        |         |               |       |       | SHAWNEE LANE CLARKSBURG MD                                  | 13NW231   |         | 37        | 31                      |                |                |                  |                   | LSC       |           |                 |                 | 
| SPECIAL PROTECTION AREA | 242263         | 2012-03-07T00:00:00 |                     | CLARKSBURG ELEMENTARY SCHOOL#1    |             |      |        |               |        |         |               |       |       | 12520 BLUE SKY DRIVE, CLARKSBURG                            | 232NW12   | EW51    | 9.3       | 10.4                    | R-200          | R-200          | VACANT           | SCHOOL            | LSC       |           | SPA-CB          |                 | 
| SPECIAL PROTECTION AREA | 249531         | 2013-01-11T00:00:00 |                     | CLARKSBURG/DAMASCUS MIDDLE SCHOOL |             |      |        |               |        |         |               |       |       | LITTLE SENECA PARKWAY, CLARKSBURG, MD 20871                 | 232NW11   | FW11    | 22.4      | 22.4                    | PD-4           | PD-4           | VACANT           | SCHOOL            | LSC       |           | SPA-CB          |                 | 
| SPECIAL PROTECTION AREA | 270835         | 2014-12-18T00:00:00 |                     | Dowden's Station                  |             |      |        |               |        |         |               |       |       | Dowden's Station Frederick Road / Clarksburg, MD 20841      | 232NW13   | EW31    | 24.4      | 13.6                    | R-200          | PD-5           |                  |                   | LSC       | UNNAMED   | SPA-CB          | IV              | 
| SPECIAL PROTECTION AREA | 222055         | 2005-11-21T00:00:00 |                     | CABIN BRANCH-GOSNELL 1 E & W      |             |      |        |               |        |         |               |       |       | WEST OLD BALTIMORE ROAD, I-270, CLARKSBURG ROAD             | 230NW13   | EV562   | 10.6      | 10                      |                |                |                  |                   | LSC       |           | SPA-CB          |                 | 
| SPECIAL PROTECTION AREA | 237572         | 2010-04-02T00:00:00 |                     | RAINBOW DRIVE                     |             |      |        |               |        |         |               |       |       | RAINBOW DRIVE (FROM SNIDER LANE TO BRIGGS CHANEY ROAD)      | 220NE02   | KS121   | 1.9       | 1.9                     |                |                | ROW              | ROW               | PBR       |           |                 |                 | 
| SPECIAL PROTECTION AREA | 261857         | 2014-02-26T00:00:00 |                     | Bowie Mill Estates                |             |      |        |               |        |         |               |       |       | 17815 & 17827 Bowie Mill Road, Rockville, Maryland 20855    | 224NW05   | HT122   | 18.1      | 0                       | RE-2           | RE-2           | SFResident       | SFResident        | URC       | NORTH BR  | III             | III             | 
```