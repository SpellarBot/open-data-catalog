# Building Permits Since 2015-01-01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-permits-since-2015-01-01) |
| Metadata | [Link](https://data.srcity.org/api/views/fpj8-e7vu) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/fpj8-e7vu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/fpj8-e7vu/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | fpj8-e7vu |
| Name | Building Permits Since 2015-01-01 |
| Category | Development |
| Created | 2016-02-02T04:24:25Z |
| Publication Date | 2016-07-13T15:33:40Z |

## Description

Accela Automation Building Permits Since January 1, 2015

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
| Yes      | series tag     | proposeduse           | ProposedUse           | text          | text          |
| Yes      | numeric metric | estprojectcost        | EstProjectCost        | money         | money         |
| Yes      | numeric metric | fee                   | Fee                   | money         | money         |
| Yes      | series tag     | aca                   | ACA                   | text          | text          |
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
series e:fpj8-e7vu d:2017-04-21T01:40:09.000Z t:parcelnumber=016650023 t:originalcity="SANTA ROSA" t:permitclass=Residential t:originalstate=CA t:originalzip=95409 t:description="Install new electrical feed wire from meter main panel to sub panel and upgrade sub panel new GE 100 amp panel." t:statuscurrent=Finaled t:permittype="Residential Electrical" t:permitnum=B15-4507 t:aca=Y m:fee=104.7 m:estprojectcost=0

series e:fpj8-e7vu d:2017-04-21T01:40:09.000Z t:parcelnumber=015390048 t:contractorzip=95402 t:originalstate=CA t:contractorstatelic=CA t:permittype="Non-Residential Sign" t:contractorlicnum=308203 t:contractorcity="SANTA ROSA" t:contractorcompanyname="J & L SIGNS" t:contractortrade=Contractor t:originalcity="SANTA ROSA" t:permitclass=Non-Residential t:contractorstate=CA t:description="INSTALLATION OF NEW SIGN FRONTERA CHECK CASHING" t:statuscurrent=Finaled t:contractorphone="(707) 953-4874" t:permitnum=B15-1772 t:aca=N m:fee=166.09 m:estprojectcost=0 m:units=0

series e:fpj8-e7vu d:2017-04-21T01:40:09.000Z t:parcelnumber=036680060 t:originalcity="SANTA ROSA" t:permitclass=Residential t:originalstate=CA t:originalzip=95403 t:description="Installation of new Bryant furnace." t:statuscurrent=Finaled t:permittype="Residential Mechanical" t:permitnum=B16-0241 t:aca=Y m:fee=104.87 m:estprojectcost=0
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:estprojectcost p:double l:EstProjectCost t:dataTypeName=money

metric m:fee p:double l:Fee t:dataTypeName=money

entity e:fpj8-e7vu l:"Building Permits Since 2015-01-01" t:url=https://data.srcity.org/api/views/fpj8-e7vu

property e:fpj8-e7vu t:meta.view v:id=fpj8-e7vu v:category=Development v:averageRating=0 v:name="Building Permits Since 2015-01-01"

property e:fpj8-e7vu t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:fpj8-e7vu t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum | description                                                                                                                                                                                       | applieddate | issueddate | completeddate | originaladdress1            | originalcity | originalstate | originalzip | permitclass     | statuscurrent | permittype                          | statusdate | units | parcelnumber | contractorcompanyname    | contractortrade | contractorlicnum | contractorstatelic | contractorphone | contractoraddress1     | contractoraddress2 | contractorcity | contractorstate | contractorzip | contractoremail           | proposeduse | estprojectcost | fee     | aca | lastupdated         | 
| ========= | ================================================================================================================================================================================================= | =========== | ========== | ============= | =========================== | ============ | ============= | =========== | =============== | ============= | =================================== | ========== | ===== | ============ | ======================== | =============== | ================ | ================== | =============== | ====================== | ================== | ============== | =============== | ============= | ========================= | =========== | ============== | ======= | === | =================== | 
| B15-4507  | Install new electrical feed wire from meter main panel to sub panel and upgrade sub panel new GE 100 amp panel.                                                                                   | 2015-10-01  | 2015-10-01 |               | 504 OAK VISTA LN            | SANTA ROSA   | CA            | 95409       | Residential     | Finaled       | Residential Electrical              | 2016-03-14 |       | 016650023    |                          |                 |                  |                    |                 |                        |                    |                |                 |               |                           |             | 0              | 104.7   | Y   | 2017-04-21T01:40:09 | 
| B15-1772  | INSTALLATION OF NEW SIGN FRONTERA CHECK CASHING                                                                                                                                                   | 2015-04-28  | 2015-04-28 |               | 1772 PINER RD               | SANTA ROSA   | CA            |             | Non-Residential | Finaled       | Non-Residential Sign                | 2015-08-25 | 0     | 015390048    | J & L SIGNS              | Contractor      | 308203           | CA                 | (707) 953-4874  | PO BOX 5099            |                    | SANTA ROSA     | CA              | 95402         |                           |             | 0              | 166.09  | N   | 2017-04-21T01:40:09 | 
| B16-0241  | Installation of new Bryant furnace.                                                                                                                                                               | 2016-01-22  | 2016-01-22 |               | 2191 ZINFANDEL AVE          | SANTA ROSA   | CA            | 95403       | Residential     | Finaled       | Residential Mechanical              | 2016-02-22 |       | 036680060    |                          |                 |                  |                    |                 |                        |                    |                |                 |               |                           |             | 0              | 104.87  | Y   | 2017-04-21T01:40:09 | 
| B17-1139  | T/O 29 SQ of comp shingles; reroof w/Class A rated composition shingles: SFD.                                                                                                                     | 2017-03-28  | 2017-03-28 |               | 324 MIRAMONTE WAY           | SANTA ROSA   | CA            | 95409       | Residential     | Finaled       | Residential Addition-Alteration     | 2017-04-17 |       | 016750023    | CRANDALL ROOFING INC     | Contractor      | 452195           | CA                 | 7075862500      | P O BOX 394            |                    | SANTA ROSA     | CA              | 95402         | crandallroofing@aol.com   |             | 11770          | 234.3   | Y   | 2017-04-21T01:40:09 | 
| B16-2362  | Residential electrical 125 amp underground main panel upgrade.                                                                                                                                    | 2016-06-08  | 2016-06-08 |               | 254 LOS ALAMOS RD           | SANTA ROSA   | CA            | 95409       | Residential     | Finaled       | Residential Electrical              | 2016-06-21 |       | 031310001    | LADY B ELECTRIC INC      | Contractor      | 956510           | CA                 | 7075085398      | 741 SHERIDAN DRIVE     |                    | SANTA ROSA     | CA              | 95405         |                           |             | 0              | 157.4   | Y   | 2017-04-21T01:40:09 | 
| B15-2756  | REROOF OVER 1 LAYER, 3 TAB SHINGLES WITH GAF LIFETIME COMP ROOF SYSTEM. CLASS A RATING, 23 SQUARES                                                                                                | 2015-06-23  | 2015-06-23 |               | 2429 LEMUR ST               | SANTA ROSA   | CA            |             | Residential     | Finaled       | Residential Addition-Alteration     | 2015-07-07 | 0     | 035640012    | R C ROOFING              | Contractor      | 577823           | CA                 | (707) 824-8564  | 953 RAGLE RD           |                    | SEBASTOPOL     | CA              | 95472         |                           |             | 0              | 214.92  | N   | 2017-04-21T01:40:09 | 
| B17-0352  | Installation of 19 roof mounted solar panels, 5.605 kW.                                                                                                                                           | 2017-01-30  | 2017-01-31 |               | 916 ESTES DR                | SANTA ROSA   | CA            | 95409       | Residential     | Finaled       | Residential Addition-Alteration     | 2017-02-24 |       | 183070041    | SOLARCITY CORPORATION    | Contractor      | 888104           | CA                 | 6509635100      | 3055 CLEARVIEW         |                    | SAN MATEO      | CA              | 94402         |                           |             | 12300          | 170.99  | N   | 2017-04-21T01:40:09 | 
| B16-3649  | Tenant Improvement remodel of existing shell space to create vanilla shell for 2 future retail tenants in Suite F and Suite G. Tenants are not identified at this time. Permit not for occupancy. | 2016-08-30  | 2016-11-28 |               | 925 CORPORATE CENTER PKWY F | SANTA ROSA   | CA            | 95407       | Non-Residential | Issued        | Non-Residential Addition-Alteration | 2016-11-28 |       | 035111022    |                          |                 |                  |                    |                 |                        |                    |                |                 |               |                           |             | 150000         | 2217.3  | N   | 2017-04-21T01:40:09 | 
| B17-0001  | Replace old furnace with new Trane 80% furnace. Also replace ductwork with R-6 Wireflex, 10 runs.                                                                                                 | 2017-01-02  | 2017-01-02 |               | 1610 SAN RAMON WAY          | SANTA ROSA   | CA            | 95409       | Residential     | Finaled       | Residential Mechanical              | 2017-03-13 |       | 153123001    | ERNEST ONGARO & SONS INC | Contractor      | 215233           | CA                 | 7075793511      | 2995 DUTTON AVE        |                    | SANTA ROSA     | CA              | 95407         | INSTALL@ONGAROANDSONS.COM |             | 0              | 118.36  | Y   | 2017-04-21T01:40:09 | 
| B16-1261  | Single story addition, continuous concrete perimeter foundation, raiser wood floor, 896 SF.                                                                                                       | 2016-04-04  | 2016-06-21 |               | 2724 AZTEC ST               | SANTA ROSA   | CA            | 95403       | Residential     | Finaled       | Residential Addition-Alteration     | 2017-01-13 |       | 036021021    | ALTA VISTA CONSTRUCTION  | Contractor      | 756639           | CA                 | 7073343007      | 4444 ALTA VISTA AVENUE |                    | SANTA ROSA     | CA              | 95404         |                           |             | 94026          | 6465.03 | N   | 2017-04-21T01:40:09 | 
```