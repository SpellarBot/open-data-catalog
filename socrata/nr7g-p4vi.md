# Engineering Permits Since 2015-01-01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/engineering-permits-since-2015-01-01) |
| Metadata | [Link](https://data.srcity.org/api/views/nr7g-p4vi) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/nr7g-p4vi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/nr7g-p4vi/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | nr7g-p4vi |
| Name | Engineering Permits Since 2015-01-01 |
| Category | Development |
| Created | 2016-02-11T05:23:26Z |
| Publication Date | 2016-02-11T06:26:37Z |

## Description

Accela Automation Engineering Permits Since January 1, 2015

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | permitnum             | PermitNum             | text          | text          |
| Yes      | series tag     | description           | Description           | text          | text          |
| No       |                | applieddate           | AppliedDate           | text          | text          |
| No       |                | issueddate            | IssuedDate            | text          | text          |
| No       |                | completeddate         | CompletedDate         | text          | text          |
| No       |                | originaladdress1      | OriginalAddress1      | text          | text          |
| Yes      | series tag     | originalcity          | OriginalCity          | text          | text          |
| Yes      | series tag     | originalstate         | OriginalState         | text          | text          |
| Yes      | series tag     | originalzip           | OriginalZip           | text          | text          |
| Yes      | series tag     | permitclass           | PermitClass           | text          | text          |
| Yes      | series tag     | statuscurrent         | StatusCurrent         | text          | text          |
| Yes      | series tag     | permittype            | PermitType            | text          | text          |
| No       |                | statusdate            | StatusDate            | text          | text          |
| Yes      | numeric metric | units                 | Units                 | number        | text          |
| Yes      | series tag     | parcelnumber          | ParcelNumber          | text          | text          |
| Yes      | series tag     | contractorcompanyname | ContractorCompanyName | text          | text          |
| Yes      | series tag     | contractortrade       | ContractorTrade       | text          | text          |
| Yes      | series tag     | contractorlicnum      | ContractorLicNum      | text          | text          |
| Yes      | series tag     | contractorstatelic    | ContractorStateLic    | text          | text          |
| Yes      | series tag     | contractorphone       | ContractorPhone       | text          | text          |
| No       |                | contractoraddress1    | ContractorAddress1    | text          | text          |
| No       |                | contractoraddress2    | ContractorAddress2    | text          | text          |
| Yes      | series tag     | contractorcity        | ContractorCity        | text          | text          |
| Yes      | series tag     | contractorstate       | ContractorState       | text          | text          |
| Yes      | series tag     | contractorzip         | ContractorZip         | text          | text          |
| Yes      | series tag     | contractoremail       | ContractorEmail       | text          | text          |
| Yes      | numeric metric | fee                   | Fee                   | money         | money         |
| Yes      | time           | lastupdated           | LastUpdated           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = lastupdated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applieddate,issueddate,completeddate,originaladdress1,statusdate,contractoraddress1,contractoraddress2
```

## Data Commands

```ls
series e:nr7g-p4vi d:2016-05-12T09:40:03.000Z t:parcelnumber=009061051 t:contractorzip=98072 t:originalstate=CA t:originalzip=95404 t:contractorstatelic=CA t:permittype="Encroachment Permit" t:contractoremail=stephen.richardson@cablecomllc.net t:contractorlicnum=826295 t:contractorcity=WOODINVILLE t:contractorcompanyname="CABLECOM LLC" t:contractortrade=Contractor t:originalcity="SANTA ROSA" t:permitclass=Encroachment t:contractorstate=WA t:description="NEW TRENCH ROUTE TO SERVICE NEW CUSTOMERS.PUBLIC INFRASTRUCTURE RESTORATION WORK SHALL BE COMPLETED IN ACCORDANCE WITH CITY STANDARDS WITHIN 30 CALANDER DAYSREMOVE AND REPLACE SIDEWALK PER CITY STDS. 235 AND 237.CONTACT INSPECTOR 48 HOURS PRIOR TO START OF WORK.PROVIDE PEDESTRIAN TRAFFIC CONTROL PER MUTCD TA28 ANDCITY OF SANTA ROSA STANDARDS.A PEDESTRIAN ESCORT SHALL BE PROVIDED AND AVAILABLE TO ASSIST PEDESTRIANS THROUGH THE WORK ZONE AT ALL TIMES WHEN THE SIDEWALK IS CLOSED." t:statuscurrent=Issued t:contractorphone=3606681300 t:permitnum=EP15-0402 m:fee=254

series e:nr7g-p4vi d:2016-05-12T09:40:03.000Z t:parcelnumber=134042011 t:originalcity="SANTA ROSA" t:permitclass=Variance t:originalstate=CA t:originalzip=95407 t:description="Grove Village Subdivision variance request to install public water main in private alley." t:statuscurrent="In Plan Review" t:permittype=Variance t:permitnum=ENGV16-002 m:fee=0

series e:nr7g-p4vi d:2016-05-12T09:40:03.000Z t:parcelnumber=009012002 t:contractorzip=94952 t:originalstate=CA t:contractorstatelic=CA t:permittype="Encroachment Permit" t:contractorlicnum=628194 t:contractorcity=PETALUMA t:contractorcompanyname="PACIFIC COAST CUTTERS INC" t:contractortrade=Contractor t:originalcity="SANTA ROSA" t:permitclass=Encroachment t:contractorstate=CA t:description="CONTACT INSPECTOR 48 HOURS PRIOR TO START OF WORK.PROVIDE PEDESTRIAN TRAFFIC CONTROL PER MUTCD TA28 ANDCITY OF SANTA ROSA STANDARDS.A PEDESTRIAN ESCORT SHALL BE PROVIDED AND AVAILABLE TO ASSIST PEDESTRIANS THROUGH THE WORK ZONE AT ALL TIMES WHEN THE SIDEWALK IS CLOSED.WORK HOURS ARE BE 8:30 P.M. TO 5:30 A.M. ONLY" t:statuscurrent=Finaled t:contractorphone=(707)765-0661 t:permitnum=EP15-0248 m:fee=80 m:units=0
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:fee p:double l:Fee t:dataTypeName=money

entity e:nr7g-p4vi l:"Engineering Permits Since 2015-01-01" t:url=https://data.srcity.org/api/views/nr7g-p4vi

property e:nr7g-p4vi t:meta.view v:id=nr7g-p4vi v:category=Development v:averageRating=0 v:name="Engineering Permits Since 2015-01-01"

property e:nr7g-p4vi t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:nr7g-p4vi t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum  | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | applieddate | issueddate | completeddate | originaladdress1    | originalcity | originalstate | originalzip | permitclass    | statuscurrent  | permittype            | statusdate | units | parcelnumber | contractorcompanyname     | contractortrade | contractorlicnum | contractorstatelic | contractorphone | contractoraddress1            | contractoraddress2 | contractorcity | contractorstate | contractorzip | contractoremail                    | fee | lastupdated         | 
| ========== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | =========== | ========== | ============= | =================== | ============ | ============= | =========== | ============== | ============== | ===================== | ========== | ===== | ============ | ========================= | =============== | ================ | ================== | =============== | ============================= | ================== | ============== | =============== | ============= | ================================== | === | =================== | 
| EP15-0402  | NEW TRENCH ROUTE TO SERVICE NEW CUSTOMERS.PUBLIC INFRASTRUCTURE RESTORATION WORK SHALL BE COMPLETED IN ACCORDANCE WITH CITY STANDARDS WITHIN 30 CALANDER DAYSREMOVE AND REPLACE SIDEWALK PER CITY STDS. 235 AND 237.CONTACT INSPECTOR 48 HOURS PRIOR TO START OF WORK.PROVIDE PEDESTRIAN TRAFFIC CONTROL PER MUTCD TA28 ANDCITY OF SANTA ROSA STANDARDS.A PEDESTRIAN ESCORT SHALL BE PROVIDED AND AVAILABLE TO ASSIST PEDESTRIANS THROUGH THE WORK ZONE AT ALL TIMES WHEN THE SIDEWALK IS CLOSED. | 2015-07-22  | 2015-07-22 |               | 71 BROOKWOOD AVE    | SANTA ROSA   | CA            | 95404       | Encroachment   | Issued         | Encroachment Permit   | 2015-07-22 |       | 009061051    | CABLECOM LLC              | Contractor      | 826295           | CA                 | 3606681300      | 8602 MALTBY ROAD              |                    | WOODINVILLE    | WA              | 98072         | stephen.richardson@cablecomllc.net | 254 | 2016-05-12T09:40:03 | 
| ENGV16-002 | Grove Village Subdivision variance request to install public water main in private alley.                                                                                                                                                                                                                                                                                                                                                                                                         | 2016-02-23  |            |               | 2872 STONY POINT RD | SANTA ROSA   | CA            | 95407       | Variance       | In Plan Review | Variance              | 2016-02-23 |       | 134042011    |                           |                 |                  |                    |                 |                               |                    |                |                 |               |                                    | 0   | 2016-05-12T09:40:03 | 
| EP15-0248  | CONTACT INSPECTOR 48 HOURS PRIOR TO START OF WORK.PROVIDE PEDESTRIAN TRAFFIC CONTROL PER MUTCD TA28 ANDCITY OF SANTA ROSA STANDARDS.A PEDESTRIAN ESCORT SHALL BE PROVIDED AND AVAILABLE TO ASSIST PEDESTRIANS THROUGH THE WORK ZONE AT ALL TIMES WHEN THE SIDEWALK IS CLOSED.WORK HOURS ARE BE 8:30 P.M. TO 5:30 A.M. ONLY                                                                                                                                                                        | 2015-05-12  | 2015-05-12 |               | 701 4TH ST          | SANTA ROSA   | CA            |             | Encroachment   | Finaled        | Encroachment Permit   | 2016-02-03 | 0     | 009012002    | PACIFIC COAST CUTTERS INC | Contractor      | 628194           | CA                 | (707)765-0661   | 450 LAKEVILLE STREET STE B    |                    | PETALUMA       | CA              | 94952         |                                    | 80  | 2016-05-12T09:40:03 | 
| EP16-0230  | Job# 42679658PG&E to dig 5 x 5 bell hole in roadway shoulder to repair service                                                                                                                                                                                                                                                                                                                                                                                                                    | 2016-05-02  |            |               | 222 BENTON ST       | SANTA ROSA   | CA            | 95401       | Encroachment   | Pending        | Encroachment Permit   | 2016-05-02 |       | 180740043    | PG&E                      | Contractor      | NL3965           | CA                 |                 | 3965 Occidental Rd            |                    | Santa Rosa     | CA              | 95401         |                                    | 0   | 2016-05-12T09:40:03 | 
| 302028     | Single Transportation Permit #302028                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2015-05-28  | 2015-05-28 |               |                     |              |               |             | Transportation | Issued         | Transportation Permit | 2015-05-28 | 0     |              |                           |                 |                  |                    |                 |                               |                    |                |                 |               |                                    | 16  | 2016-05-12T09:40:03 | 
| EP15-0031  | REMOVE AND REPLACE SIDEWALK, CURB AND GUTTER TO REPAIR WATER SERVICE.CONTACT INSPECTOR 48 HOURS PRIOR TO START OF WORK.REMOVE AND REPLACE CURB AND GUTTER PER CITY STANDARDS 235 AND 241.REMOVE AND REPLACE SIDEWALK PER CITY STANDARDS 235 AND 237.PEDESTRIANS SHALL BE SAFELY ESCORTED THROUGH THE WORKZONE OR DIVERTED AROUND THE WORKZONE IN ACCORDANCE WITH MUTCD TA-28.                                                                                                                     | 2015-01-21  | 2015-01-21 |               | 1316 MILLER DR      | SANTA ROSA   | CA            |             | Encroachment   | Finaled        | Encroachment Permit   | 2015-03-30 | 0     | 148180041    | ONGARO & SONS (DBA)       | Contractor      | 215233           | CA                 | (707) 579-3511  | 2995 DUTTON AVE               |                    | SANTA ROSA     | CA              | 95407         |                                    | 200 | 2016-05-12T09:40:03 | 
| EP16-0163  | remove and replace sidewalk to repair water leak.                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 2016-03-29  | 2016-03-29 |               | 3415 SANTIAGO DR    | SANTA ROSA   | CA            | 95403       | Encroachment   | Issued         | Encroachment Permit   | 2016-03-29 |       | 034260030    | RAPIDFLO INC              | Contractor      | 821844           | CA                 | 4153821215      | 354 BEL MARIN KEYS BLVD STE L |                    | NOVATO         | CA              | 94949         |                                    | 188 | 2016-05-12T09:40:03 | 
| EP15-0531  | Repair gas leak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2015-09-16  | 2015-10-06 |               | 1709 BURGUNDY PL    | SANTA ROSA   | CA            | 95403       | Encroachment   | Issued         | Encroachment Permit   | 2015-10-06 |       | 036290045    | PG&E                      | Contractor      | NL3965           | CA                 | 7075796318      | 3965 Occidental Road          |                    | Santa Rosa     | CA              | 95401         |                                    | 140 | 2016-05-12T09:40:03 | 
| 301218     | SINGLE TRANS. PERMIT - KLH TRANSPORT #301218                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 2015-01-21  | 2015-01-21 |               |                     |              |               |             | Transportation | Issued         | Transportation Permit | 2015-01-21 | 0     |              |                           |                 |                  |                    |                 |                               |                    |                |                 |               |                                    | 16  | 2016-05-12T09:40:03 | 
| 301297     | SINGLE TRANS PERMIT - BRAGG CRANE #301297                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 2015-04-30  | 2015-04-30 |               |                     |              |               |             | Transportation | Issued         | Transportation Permit | 2015-04-30 | 0     |              |                           |                 |                  |                    |                 |                               |                    |                |                 |               |                                    | 16  | 2016-05-12T09:40:03 | 
```