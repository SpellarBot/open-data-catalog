# Water Permits Since 2015-01-01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-permits-since-2015-01-01) |
| Metadata | [Link](https://data.srcity.org/api/views/aerr-uvjy) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/aerr-uvjy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/aerr-uvjy/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | aerr-uvjy |
| Name | Water Permits Since 2015-01-01 |
| Category | Development |
| Created | 2016-02-11T05:25:52Z |
| Publication Date | 2016-02-11T05:37:37Z |

## Description

Accela Automation Water Permits Since January 1, 2015

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
| Yes      | numeric metric | contractorlicnum      | ContractorLicNum      | number        | text          |
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
series e:aerr-uvjy d:2017-04-21T00:40:03.000Z t:originalcity="SANTA ROSA" t:permitclass=Permit t:originalstate=CA t:description="NEW CONDOS, BUILDING 2, 10 MULITFAMILY UNITSSEE U16-0245 FOR IRRIGATION METER AND FIRE BYPASS METERS" t:statuscurrent=Approved t:permittype="Water Permit" t:permitnum=U16-0247 m:fee=0

series e:aerr-uvjy d:2017-04-21T00:40:03.000Z t:originalcity="SANTA ROSA" t:permitclass=Permit t:originalstate=CA t:originalzip=95404 t:description="INTERIOR IMPROVEMENTS - NEW HOTEL WITH 3 FLOORS OF HOTELS ROOMS (13 ROOMS PER FLOOR). 22,044 SF HOTEL (INCLUDES 256 SF BAR AREA - 113 SF BAR + 143 SF FOOD PREP). RENOVATION INCLUDES REMODEL OF 15,000 SF." t:statuscurrent=Applied t:permittype="Water Permit" t:permitnum=U17-0005 m:fee=0

series e:aerr-uvjy d:2017-04-21T00:40:03.000Z t:contractortrade=Contractor t:parcelnumber=012084010 t:originalcity="SANTA ROSA" t:permitclass=Permit t:originalstate=CA t:originalzip=95401 t:description="New 5,000 sq ft warehouse/office building. 1,250 sq ft office and 3,750 sq ft warehouse.Waiting for WELO capacity number to determine irrigation demand fees." t:statuscurrent=Approved t:permittype="Water Permit" t:contractorstatelic=CA t:permitnum=U15-0073 t:contractorcompanyname=OWNER-BUILDER m:fee=11421 m:contractorlicnum=0
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:contractorlicnum p:integer l:ContractorLicNum t:dataTypeName=number

metric m:fee p:integer l:Fee t:dataTypeName=money

entity e:aerr-uvjy l:"Water Permits Since 2015-01-01" t:url=https://data.srcity.org/api/views/aerr-uvjy

property e:aerr-uvjy t:meta.view v:id=aerr-uvjy v:category=Development v:averageRating=0 v:name="Water Permits Since 2015-01-01"

property e:aerr-uvjy t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:aerr-uvjy t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum | description                                                                                                                                                                                                                                   | applieddate | issueddate | completeddate | originaladdress1       | originalcity | originalstate | originalzip | permitclass | statuscurrent | permittype   | statusdate | units | parcelnumber | contractorcompanyname | contractortrade | contractorlicnum | contractorstatelic | contractorphone | contractoraddress1 | contractoraddress2 | contractorcity | contractorstate | contractorzip | contractoremail | fee    | lastupdated         | 
| ========= | ============================================================================================================================================================================================================================================= | =========== | ========== | ============= | ====================== | ============ | ============= | =========== | =========== | ============= | ============ | ========== | ===== | ============ | ===================== | =============== | ================ | ================== | =============== | ================== | ================== | ============== | =============== | ============= | =============== | ====== | =================== | 
| U16-0247  | NEW CONDOS, BUILDING 2, 10 MULITFAMILY UNITSSEE U16-0245 FOR IRRIGATION METER AND FIRE BYPASS METERS                                                                                                                                          | 2016-05-12  |            |               | 2605 MONTGOMERY DR     | SANTA ROSA   | CA            |             | Permit      | Approved      | Water Permit | 2016-05-19 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0      | 2017-04-21T00:40:03 | 
| U17-0005  | INTERIOR IMPROVEMENTS - NEW HOTEL WITH 3 FLOORS OF HOTELS ROOMS (13 ROOMS PER FLOOR). 22,044 SF HOTEL (INCLUDES 256 SF BAR AREA - 113 SF BAR + 143 SF FOOD PREP). RENOVATION INCLUDES REMODEL OF 15,000 SF.                                   | 2017-01-04  |            |               | 37 OLD COURTHOUSE SQ   | SANTA ROSA   | CA            | 95404       | Permit      | Applied       | Water Permit | 2017-01-04 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0      | 2017-04-21T00:40:03 | 
| U15-0073  | New 5,000 sq ft warehouse/office building. 1,250 sq ft office and 3,750 sq ft warehouse.Waiting for WELO capacity number to determine irrigation demand fees.                                                                                 | 2015-08-11  | 2016-07-28 |               | 125 FOLEY ST           | SANTA ROSA   | CA            | 95401       | Permit      | Approved      | Water Permit | 2017-04-12 |       | 012084010    | OWNER-BUILDER         | Contractor      | 0                | CA                 |                 |                    |                    |                |                 |               |                 | 11421  | 2017-04-21T00:40:03 | 
| U15-0033  | Meter fees were paid in 2004 for a 5/8" meter, but was never installed. This fee is to upsize to a 1" meter. Meter box and plumbing will need to be replaced/modified for the larger meter. An Encroachment Permit is required for this work. | 2015-05-21  |            |               | 41 RANDALL LN          | SANTA ROSA   | CA            |             | Permit      | Approved      | Water Permit | 2015-05-21 | 0     | 182490026    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 50     | 2017-04-21T00:40:03 | 
| U16-0325  | Add new water meter for SFD which was previously served by the church AT 697 Benecia Drive.                                                                                                                                                   | 2016-08-25  | 2016-09-13 |               | 2222 FREMONT DR        | SANTA ROSA   | CA            |             | Permit      | Finaled       | Water Permit | 2016-09-13 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 820    | 2017-04-21T00:40:03 | 
| U16-0138  | NEW 3-STORY SFD                                                                                                                                                                                                                               | 2016-05-10  |            |               | 51 BRIAR BUSH WAY      | SANTA ROSA   | CA            |             | Permit      | Approved      | Water Permit | 2016-05-10 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0      | 2017-04-21T00:40:03 | 
| U15-0075  | addition of 1850 square feet of warehouse/storage area to existing building                                                                                                                                                                   | 2015-08-12  |            |               | 3965 OCCIDENTAL RD     | SANTA ROSA   | CA            | 95401       | Permit      | Applied       | Water Permit | 2015-08-12 |       | 035062003    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 1587   | 2017-04-21T00:40:03 | 
| U17-0030  | PLAN 2 ELEVATION C: NEW 2-SOTRY 2183 SF SFD WITH 431 SF GARAGE, 62 SF COVERED PORCH, 3 BEDROOMS PLUS LOFT AND DEN. OPTIONS: CONVERT LOFT TO 4TH BEDROOM. CONVERT DEN TO 5TH BEDROOM.                                                          | 2017-01-18  |            |               | 2654 PETERSON CREEK LN | SANTA ROSA   | CA            | 95404       | Permit      | Approved      | Water Permit | 2017-01-18 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0      | 2017-04-21T00:40:03 | 
| U16-0056  | CIP 1673(UIP 3517) CONNECT MOBILE HOME PARK TO CITY WATER ON SOUTHPARK SEWER PROVIDED IRRG METER BOX FOR FUTURE USE. IRRG NOT A PART OF THIS DEMAND FEES TO BE PAID BY STATE GRANT AT END OF PROJECT                                          | 2016-01-13  | 2016-08-31 |               | 3455 SANTA ROSA AVE    | SANTA ROSA   | CA            | 95407       | Permit      | Finaled       | Water Permit | 2016-08-31 |       | 134123016    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 192740 | 2017-04-21T00:40:03 | 
| U16-0165  | NEW 2-STORY SFD                                                                                                                                                                                                                               | 2016-05-10  |            |               | 56 BRIAR BUSH WAY      | SANTA ROSA   | CA            |             | Permit      | Approved      | Water Permit | 2016-05-10 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0      | 2017-04-21T00:40:03 | 
```