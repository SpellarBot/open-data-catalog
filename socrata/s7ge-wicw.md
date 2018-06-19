# L&I Contractor Authorized Signer Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-contractor-authorized-signer-data) |
| Metadata | [Link](https://data.wa.gov/api/views/s7ge-wicw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/s7ge-wicw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/s7ge-wicw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | s7ge-wicw |
| Name | L&I Contractor Authorized Signer Data |
| Attribution | Labor & Industries |
| Category | Labor |
| Tags | l&i, labor & industries, labor and industries, contractor, license |
| Created | 2015-10-15T16:45:55Z |
| Publication Date | 2015-10-30T17:01:08Z |

## Description

Addendum to Labor & Industries Contractor License and Registration data. Authorized signers are those identified on the license as authorized signers for permits or affidavits.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | businessname                  | BusinessName                  | text      | text        |
| Yes      | series tag  | contractorlicensenumber       | ContractorLicenseNumber       | text      | text        |
| Yes      | series tag  | contractorlicensetypecode     | ContractorLicenseTypeCode     | text      | text        |
| Yes      | series tag  | contractorlicensetypecodedesc | ContractorLicenseTypeCodeDesc | text      | text        |
| Yes      | series tag  | businesstypecode              | BusinessTypeCode              | text      | text        |
| Yes      | series tag  | businesstypecodedesc          | BusinessTypeCodeDesc          | text      | text        |
| Yes      | series tag  | ubi                           | UBI                           | text      | text        |
| Yes      | series tag  | authorizedsigner              | AuthorizedSigner              | text      | text        |
| Yes      | series tag  | signerrole                    | SignerRole                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s7ge-wicw d:2015-10-15T09:45:58.000Z t:ubi=113004420 t:contractorlicensetypecode=EC t:businessname="DEPENDABLE APPLIANCE CO" t:businesstypecode=C t:contractorlicensenumber=DEPENAC904PD t:contractorlicensetypecodedesc="ELECTRICAL CONTRACTOR" t:businesstypecodedesc=Corporation m:row_number.s7ge-wicw=1

series e:s7ge-wicw d:2015-10-15T09:45:58.000Z t:ubi=141005104 t:contractorlicensetypecode=EC t:businessname="GRAYS HARBOR EQUIPMENT CO INC" t:businesstypecode=C t:contractorlicensenumber=GRAYSHE935C4 t:contractorlicensetypecodedesc="ELECTRICAL CONTRACTOR" t:businesstypecodedesc=Corporation m:row_number.s7ge-wicw=2

series e:s7ge-wicw d:2015-10-15T09:45:58.000Z t:ubi=151000406 t:contractorlicensetypecode=EC t:businessname="CENTRAL ELEC OF COUPEVILLE INC" t:businesstypecode=C t:contractorlicensenumber=CENTREC389MJ t:contractorlicensetypecodedesc="ELECTRICAL CONTRACTOR" t:businesstypecodedesc=Corporation m:row_number.s7ge-wicw=3
```

## Meta Commands

```ls
metric m:row_number.s7ge-wicw p:long l:"Row Number"

entity e:s7ge-wicw l:"L&I Contractor Authorized Signer Data" t:attribution="Labor & Industries" t:url=https://data.wa.gov/api/views/s7ge-wicw

property e:s7ge-wicw t:meta.view v:id=s7ge-wicw v:category=Labor v:attributionLink=http://www.Lni.wa.gov/TradesLicensing/Contractors/HireCon/Verify/ v:averageRating=0 v:name="L&I Contractor Authorized Signer Data" v:attribution="Labor & Industries"

property e:s7ge-wicw t:meta.view.license v:name="Public Domain"

property e:s7ge-wicw t:meta.view.owner v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:displayName=Estz235LI

property e:s7ge-wicw t:meta.view.tableauthor v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:roleName=editor v:displayName=Estz235LI
```

## Top Records

```ls
| :updated_at | businessname                   | contractorlicensenumber | contractorlicensetypecode | contractorlicensetypecodedesc | businesstypecode | businesstypecodedesc | ubi       | authorizedsigner | signerrole | 
| =========== | ============================== | ======================= | ========================= | ============================= | ================ | ==================== | ========= | ================ | ========== | 
| 1444902358  | DEPENDABLE APPLIANCE CO        | DEPENAC904PD            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 113004420 |                  |            | 
| 1444902358  | GRAYS HARBOR EQUIPMENT CO INC  | GRAYSHE935C4            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 141005104 |                  |            | 
| 1444902358  | CENTRAL ELEC OF COUPEVILLE INC | CENTREC389MJ            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 151000406 |                  |            | 
| 1444902358  | EASTSIDE ICE COMPANY           | EASTSIC007O8            | EC                        | ELECTRICAL CONTRACTOR         | I                | Individual           | 174004156 |                  |            | 
| 1444902358  | HOLMES ELECTRIC CO             | HOLMEEC549BH            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 177003752 |                  |            | 
| 1444902358  | SECURITY SAFE & LOCK INC       | SECURSL981JJ            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 179019607 |                  |            | 
| 1444902358  | MIDSTATE CO-OP                 | MIDSTC*8821B            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 192001263 |                  |            | 
| 1444902358  | R & R CABLE COMPANY            | RRCABC*066RR            | EC                        | ELECTRICAL CONTRACTOR         | C                | Corporation          | 195000292 |                  |            | 
| 1444902358  | LOUIS STOFFER/SON SHEET METAL  | LOUISSS000C4            | EC                        | ELECTRICAL CONTRACTOR         | I                | Individual           | 211001774 |                  |            | 
| 1444902362  | Elevations Ltd                 | ELEVAL*901NT            | LC                        | ELEVATOR CONTRACTOR           |                  |                      | 603037955 |                  |            | 
```