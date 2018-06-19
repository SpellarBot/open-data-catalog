# Planning Projects Since 2015-01-01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/planning-projects-since-2015-01-01) |
| Metadata | [Link](https://data.srcity.org/api/views/chwp-zf3z) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/chwp-zf3z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/chwp-zf3z/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | chwp-zf3z |
| Name | Planning Projects Since 2015-01-01 |
| Category | Development |
| Created | 2016-02-11T05:20:51Z |
| Publication Date | 2016-02-11T05:49:26Z |

## Description

Accela Automation Planning Projects Since January 1, 2015

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | permitnum             | PermitNum             | text          | text          |
| Yes      | series tag     | description           | Description           | text          | text          |
| No       |                | applieddate           | AppliedDate           | text          | text          |
| No       |                | completeddate         | CompletedDate         | text          | text          |
| No       |                | originaladdress1      | OriginalAddress1      | text          | text          |
| Yes      | series tag     | originalcity          | OriginalCity          | text          | text          |
| Yes      | series tag     | originalstate         | OriginalState         | text          | text          |
| Yes      | series tag     | originalzip           | OriginalZip           | text          | text          |
| Yes      | series tag     | permitclass           | PermitClass           | text          | text          |
| Yes      | series tag     | statuscurrent         | StatusCurrent         | text          | text          |
| Yes      | series tag     | permittype            | PermitType            | text          | text          |
| No       |                | statusdate            | StatusDate            | text          | text          |
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
Excluded Fields = applieddate,completeddate,originaladdress1,statusdate,contractoraddress1,contractoraddress2
```

## Data Commands

```ls
series e:chwp-zf3z d:2016-08-23T09:40:03.000Z t:parcelnumber=013012055 t:originalcity="SANTA ROSA" t:permitclass=Entitlements t:originalstate=CA t:description="PSYCOTHERAPY OFFICE" t:statuscurrent=Approved t:permittype="Zoning Clearance" t:permitnum=ZC15-0086 m:fee=0

series e:chwp-zf3z d:2016-08-23T09:40:03.000Z t:parcelnumber=148070020 t:originalcity="SANTA ROSA" t:permitclass=Entitlements t:originalstate=CA t:originalzip=95403 t:description="Renovation of 136-room Sandman Inn.  Plans include adding a 6' fence between the Sandman Inn and neighboring Carrow's parking lot; upgrade landscaping including adding drought-resistant plant life; upgrade pool building to turn into a pool bar with a beer and wine license; reconfigure lobby space including ceiling height; small improvements to existing gym." t:statuscurrent=Closed t:permittype="Neighborhood Meeting" t:permitnum=PRAP16-015 m:fee=0

series e:chwp-zf3z d:2016-08-23T09:40:03.000Z t:parcelnumber=010012020 t:originalcity="SANTA ROSA" t:permitclass=Entitlements t:originalstate=CA t:description="Vinyl window replacement with single hung wood and new wood trim." t:statuscurrent=Referred t:permittype="Landmark Alteration" t:permitnum=LMA15-002 m:fee=1187
```

## Meta Commands

```ls
metric m:contractorlicnum p:integer l:ContractorLicNum t:dataTypeName=number

metric m:fee p:integer l:Fee t:dataTypeName=money

entity e:chwp-zf3z l:"Planning Projects Since 2015-01-01" t:url=https://data.srcity.org/api/views/chwp-zf3z

property e:chwp-zf3z t:meta.view v:id=chwp-zf3z v:category=Development v:averageRating=0 v:name="Planning Projects Since 2015-01-01"

property e:chwp-zf3z t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:chwp-zf3z t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum  | description                                                                                                                                                                                                                                                                                                                                                            | applieddate | completeddate | originaladdress1     | originalcity | originalstate | originalzip | permitclass  | statuscurrent | permittype           | statusdate | parcelnumber | contractorcompanyname     | contractortrade | contractorlicnum | contractorstatelic | contractorphone | contractoraddress1 | contractoraddress2 | contractorcity | contractorstate | contractorzip | contractoremail | fee  | lastupdated         | 
| ========== | ====================================================================================================================================================================================================================================================================================================================================================================== | =========== | ============= | ==================== | ============ | ============= | =========== | ============ | ============= | ==================== | ========== | ============ | ========================= | =============== | ================ | ================== | =============== | ================== | ================== | ============== | =============== | ============= | =============== | ==== | =================== | 
| ZC15-0086  | PSYCOTHERAPY OFFICE                                                                                                                                                                                                                                                                                                                                                    | 2015-02-25  |               | 4357 MONTGOMERY DR D | SANTA ROSA   | CA            |             | Entitlements | Approved      | Zoning Clearance     | 2015-02-25 | 013012055    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0    | 2016-08-23T09:40:03 | 
| PRAP16-015 | Renovation of 136-room Sandman Inn. Plans include adding a 6' fence between the Sandman Inn and neighboring Carrow's parking lot; upgrade landscaping including adding drought-resistant plant life; upgrade pool building to turn into a pool bar with a beer and wine license; reconfigure lobby space including ceiling height; small improvements to existing gym. | 2016-03-24  | 2016-04-05    | 3421 CLEVELAND AVE   | SANTA ROSA   | CA            | 95403       | Entitlements | Closed        | Neighborhood Meeting | 2016-06-13 | 148070020    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0    | 2016-08-23T09:40:03 | 
| LMA15-002  | Vinyl window replacement with single hung wood and new wood trim.                                                                                                                                                                                                                                                                                                      | 2015-02-12  |               | 637 B ST             | SANTA ROSA   | CA            |             | Entitlements | Referred      | Landmark Alteration  | 2015-12-09 | 010012020    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 1187 | 2016-08-23T09:40:03 | 
| ZC15-0478  | No HDP required for pool (accessory structure). Lot was previously developed. Pool will affect area that was altered already for construction. Per J. Oswald.                                                                                                                                                                                                          | 2015-12-09  |               | 3788 SKYFARM DR      | SANTA ROSA   | CA            | 95403       | Entitlements | Approved      | Zoning Clearance     | 2015-12-09 | 173750021    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0    | 2016-08-23T09:40:03 | 
| SI15-039   | TWO SETS OF INTERIOR ILLUMINATED INDIVIDUAL LETTERS (PERSONA) WITH FLAT CUTOUT SUBTEXT (WOOD FIRED PIZZERIA)                                                                                                                                                                                                                                                           | 2015-05-26  | 2015-05-26    | 701 4TH ST           | SANTA ROSA   | CA            |             | Entitlements | Approved      | Sign Permit          | 2015-10-23 | 009012002    | JOHNSTON SIGN COMPANY INC | Contractor      | 609593           | CA                 | (707) 829-7332  | 3595 HWY 116 SO    |                    | SEBASTOPOL     | CA              | 95472         |                 | 213  | 2016-08-23T09:40:03 | 
| TR15-082   | Redwood tree.                                                                                                                                                                                                                                                                                                                                                          | 2015-09-16  |               | 1503 GLENSIDE ST     | SANTA ROSA   | CA            | 95403       | Entitlements | Approved      | Tree Removal         | 2015-10-13 | 034131030    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 194  | 2016-08-23T09:40:03 | 
| ZC16-0118  | Wine production - Atelier Copain LLC dba Punchdown Cellars (Host Winery) custom crush facility.                                                                                                                                                                                                                                                                        | 2016-04-21  |               | 1160 HOPPER AVE      | SANTA ROSA   | CA            | 95403       | Entitlements | Approved      | Zoning Clearance     | 2016-04-21 | 015360059    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 0    | 2016-08-23T09:40:03 | 
| TR15-063   | Remove Oak tree - 6' 10".                                                                                                                                                                                                                                                                                                                                              | 2015-07-27  |               | 496 HENDLEY ST       | SANTA ROSA   | CA            | 95404       | Entitlements | Submitted     | Tree Removal         | 2015-07-27 | 009274037    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 194  | 2016-08-23T09:40:03 | 
| TR15-058   | Remove three redwood trees that are causing damage.                                                                                                                                                                                                                                                                                                                    | 2015-07-07  |               | 2391 CIRCADIAN WAY   | SANTA ROSA   | CA            | 95407       | Entitlements | Submitted     | Tree Removal         | 2015-07-07 | 035133024    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 582  | 2016-08-23T09:40:03 | 
| DR16-043   | Installation of automatic gate.                                                                                                                                                                                                                                                                                                                                        | 2016-07-12  |               | 777 ASTON AVE        | SANTA ROSA   | CA            | 95404       | Entitlements | Referred      | Design Review Minor  | 2016-07-19 | 038171021    |                           |                 |                  |                    |                 |                    |                    |                |                 |               |                 | 1623 | 2016-08-23T09:40:03 | 
```