# Fire Building-Related Permits Since 2015-01-01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-building-related-permits-since-2015-01-01) |
| Metadata | [Link](https://data.srcity.org/api/views/h553-bxek) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/h553-bxek/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/h553-bxek/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | h553-bxek |
| Name | Fire Building-Related Permits Since 2015-01-01 |
| Category | Fire |
| Created | 2016-02-02T04:44:37Z |
| Publication Date | 2016-02-11T02:05:41Z |

## Description

Accela Automation Fire Permits Since January 1, 2015. These are one-time permits relating to building activity.

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
| Yes      | series tag     | proposeduse           | ProposedUse           | text          | text          |
| Yes      | numeric metric | estprojectcost        | EstProjectCost        | money         | money         |
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
series e:h553-bxek d:2016-11-01T14:40:10.000Z t:parcelnumber=043134042 t:originalcity="SANTA ROSA" t:permitclass="Fire Sprinkler" t:originalstate=CA t:originalzip=95407 t:description="Sprinkler TI - Wright Construction - 3020 Dutton Ave" t:statuscurrent=Finaled t:permittype="Fire Sprinkler Permit" t:permitnum=F16-0090 m:fee=488.84 m:estprojectcost=0

series e:h553-bxek d:2016-11-01T14:40:10.000Z t:parcelnumber=009371010 t:originalcity="SANTA ROSA" t:permitclass="Limited Term" t:originalstate=CA t:originalzip=95404 t:description="LIMITED PROPANE PERMIT:  1ST USE - THE EMERALD CUP, SONOMA COUNTY FAIRGROUNDS, 1350 BENNETT VALLEY RD ON 12/12 & 12/13, 2015 FROM 11AM TO 7PM." t:statuscurrent=Issued t:permittype="Limited Term Permit" t:permitnum=F15-0665 m:fee=60 m:estprojectcost=0

series e:h553-bxek d:2016-11-01T14:40:10.000Z t:originalcity="SANTA ROSA" t:permitclass="Limited Term" t:originalstate=CA t:description="SPECIAL EVENT PERMIT: RINCON VALLEY SCHOOLS MUSIC CONCERT: VETERAN?S MEMORIAL BUILDING 1351 MAPLE: DECEMBER 16 & 17 (WED & THUR), 2015 6PM ? 9PM: CONTACT ?ISAAC VANDOVEER 695-3611ON CALL: P LOWENTHAL" t:statuscurrent=Finaled t:permittype="Limited Term Permit" t:permitnum=F15-0638 m:fee=129 m:estprojectcost=0
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:contractorlicnum p:integer l:ContractorLicNum t:dataTypeName=number

metric m:estprojectcost p:integer l:EstProjectCost t:dataTypeName=money

metric m:fee p:double l:Fee t:dataTypeName=money

entity e:h553-bxek l:"Fire Building-Related Permits Since 2015-01-01" t:url=https://data.srcity.org/api/views/h553-bxek

property e:h553-bxek t:meta.view v:id=h553-bxek v:category=Fire v:averageRating=0 v:name="Fire Building-Related Permits Since 2015-01-01"

property e:h553-bxek t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:h553-bxek t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum  | description                                                                                                                                                                                             | applieddate | issueddate | completeddate | originaladdress1       | originalcity | originalstate | originalzip | permitclass              | statuscurrent | permittype                      | statusdate | units | parcelnumber | contractorcompanyname | contractortrade | contractorlicnum | contractorstatelic | contractorphone | contractoraddress1 | contractoraddress2 | contractorcity | contractorstate | contractorzip | contractoremail | proposeduse | estprojectcost | fee      | lastupdated         | 
| ========== | ======================================================================================================================================================================================================= | =========== | ========== | ============= | ====================== | ============ | ============= | =========== | ======================== | ============= | =============================== | ========== | ===== | ============ | ===================== | =============== | ================ | ================== | =============== | ================== | ================== | ============== | =============== | ============= | =============== | =========== | ============== | ======== | =================== | 
| F16-0090   | Sprinkler TI - Wright Construction - 3020 Dutton Ave                                                                                                                                                    | 2016-02-18  | 2016-03-07 |               | 3020 DUTTON AVE        | SANTA ROSA   | CA            | 95407       | Fire Sprinkler           | Finaled       | Fire Sprinkler Permit           | 2016-07-13 |       | 043134042    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 488.84   | 2016-11-01T14:40:10 | 
| F15-0665   | LIMITED PROPANE PERMIT: 1ST USE - THE EMERALD CUP, SONOMA COUNTY FAIRGROUNDS, 1350 BENNETT VALLEY RD ON 12/12 & 12/13, 2015 FROM 11AM TO 7PM.                                                           | 2015-12-08  | 2015-12-08 |               | 1350 BENNETT VALLEY RD | SANTA ROSA   | CA            | 95404       | Limited Term             | Issued        | Limited Term Permit             | 2015-12-08 |       | 009371010    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 60       | 2016-11-01T14:40:10 | 
| F15-0638   | SPECIAL EVENT PERMIT: RINCON VALLEY SCHOOLS MUSIC CONCERT: VETERAN?S MEMORIAL BUILDING 1351 MAPLE: DECEMBER 16 & 17 (WED & THUR), 2015 6PM ? 9PM: CONTACT ?ISAAC VANDOVEER 695-3611ON CALL: P LOWENTHAL | 2015-11-20  | 2015-11-20 |               |                        | SANTA ROSA   | CA            |             | Limited Term             | Finaled       | Limited Term Permit             | 2016-05-06 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 129      | 2016-11-01T14:40:10 | 
| F16-0406   | Phase I ESA - Pacifica Senior Living - 3731 Airway Drive                                                                                                                                                | 2016-07-27  | 2016-07-27 |               | 3731 AIRWAY DR         | SANTA ROSA   | CA            | 95403       | CUPA Hazardous Materials | Issued        | CUPA Hazardous Materials Permit | 2016-07-27 |       | 058011014    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 285.6    | 2016-11-01T14:40:10 | 
| F15-0267   | ROSELAND/PRMD REVIEW - 720 BRITTAIN LANE - NEW DETACHED GARAGE/SHOP WITH FULL BATH                                                                                                                      | 2015-05-04  | 2015-05-26 |               | 720 BRITTAIN LN        | SANTA ROSA   | CA            |             | Consultation             | Complete      | Fire Consultation               | 2015-05-26 | 0     | 035251025    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 264.44   | 2016-11-01T14:40:10 | 
| F15-0249   | LIMITED PROPANE PERMIT: CINCO DE MAYO STREET EVENT - SEBASTOPOL RD: PACHECO'S ROASTED CORN: MAY 5, 2015 TUESDAY (2PM - 9PM): CONTACT: JOSE PACHECO 540-1116: INSPECTOR ON CALL T REY                    | 2015-04-29  | 2015-04-29 |               |                        |              |               |             | Limited Term             | Finaled       | Limited Term Permit             | 2015-05-05 | 0     |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 59       | 2016-11-01T14:40:10 | 
| FR16-00013 | Wildland - Butte                                                                                                                                                                                        | 2016-02-29  |            | 2016-02-29    |                        |              |               |             | Miscellaneous            | Complete      | Fire Receipt                    | 2016-02-29 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 85903.61 | 2016-11-01T14:40:10 | 
| F16-0021   | New Fire Sprinkler Install - 1475 Pebble Creek Drive - Catalina Subdivision - Lot 49                                                                                                                    | 2016-01-15  | 2016-02-01 |               | 1475 PEBBLECREEK DR    | SANTA ROSA   | CA            | 95407       | Fire Sprinkler           | Finaled       | Fire Sprinkler Permit           | 2016-09-14 |       | 043370049    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 346.5    | 2016-11-01T14:40:10 | 
| FR16-00045 | FOR JOSEPH HUGHES                                                                                                                                                                                       | 2016-06-13  |            | 2016-06-13    |                        |              |               |             | Miscellaneous            | Complete      | Fire Receipt                    | 2016-06-13 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 275      | 2016-11-01T14:40:10 | 
| F16-0196   | Fire Sprinkler TI - AAA - 1501 Farmers Lane                                                                                                                                                             | 2016-04-18  | 2016-04-20 |               | 1501 FARMERS LN        | SANTA ROSA   | CA            | 95405       | Fire Sprinkler           | Finaled       | Fire Sprinkler Permit           | 2016-07-07 |       | 014561005    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 1408.08  | 2016-11-01T14:40:10 | 
```