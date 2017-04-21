# L&I Contractor License Data - Bond

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-contractor-license-data-bond) |
| Metadata | [Link](https://data.wa.gov/api/views/bzff-4fmt) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/bzff-4fmt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/bzff-4fmt/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | bzff-4fmt |
| Name | L&I Contractor License Data - Bond |
| Attribution | Labor & Industries |
| Category | Labor |
| Tags | l&i, lni, labor & industries, contractor, license, insurance |
| Created | 2016-12-02T18:42:24Z |
| Publication Date | 2016-12-08T21:22:34Z |

## Description

State of Washington, Labor & Industries contractor license and bond data.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | businessname                  | BusinessName                  | text          | text          |
| Yes      | series tag     | contractorlicensenumber       | ContractorLicenseNumber       | text          | text          |
| Yes      | series tag     | contractorlicensetypecode     | ContractorLicenseTypeCode     | text          | text          |
| Yes      | series tag     | contractorlicensetypecodedesc | ContractorLicenseTypeCodeDesc | text          | text          |
| Yes      | series tag     | licensestatus                 | LicenseStatus                 | text          | text          |
| Yes      | series tag     | licensestatusdesc             | LicenseStatusDesc             | text          | text          |
| Yes      | numeric metric | ubi                           | UBI                           | number        | number        |
| Yes      | series tag     | bondfirmname                  | BondFirmName                  | text          | text          |
| Yes      | series tag     | bondaccountid                 | BondAccountID                 | text          | text          |
| Yes      | numeric metric | bondamt                       | BondAmt                       | number        | number        |
| No       |                | receivedbyl_i                 | ReceivedByL&I                 | calendar_date | calendar_date |
| Yes      | time           | bondeffectivedate             | BondEffectiveDate             | calendar_date | calendar_date |
| No       |                | bondexpirationdate            | BondExpirationDate            | text          | text          |
| No       |                | bondcanceldate                | BondCancelDate                | calendar_date | calendar_date |
| Yes      | series tag     | bondimpaired                  | BondImpaired                  | text          | text          |
| No       |                | bondimpaireddate              | BondImpairedDate              | calendar_date | calendar_date |
```

## Time Field

```ls
Value = bondeffectivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = receivedbyl_i,bondexpirationdate,bondcanceldate,bondimpaireddate
```

## Data Commands

```ls
series e:bzff-4fmt d:2010-05-17T00:00:00.000Z t:businessname="3Kam Construction LLC" t:contractorlicensetypecode=CC t:contractorlicensenumber=3KAMCCL903KP t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:bondaccountid=6711301 t:licensestatus=R t:bondfirmname="AMERICAN STATES INS CO" t:licensestatusdesc=RE-LICENSED m:ubi=602959266 m:bondamt=12000

series e:bzff-4fmt d:2012-08-17T00:00:00.000Z t:businessname="3RD GENERATION FLOORING" t:contractorlicensetypecode=CC t:contractorlicensenumber=3RDGEGF940NN t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:bondaccountid=9813739 t:licensestatus=R t:bondfirmname="Lexon Ins Co" t:licensestatusdesc=RE-LICENSED m:ubi=602640556 m:bondamt=6000

series e:bzff-4fmt d:2006-08-17T00:00:00.000Z t:businessname="3RD GENERATION FLOORING" t:contractorlicensetypecode=CC t:contractorlicensenumber=3RDGEGF940NN t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:bondaccountid=743297C t:licensestatus=R t:bondfirmname="DEVELOPERS SURETY & INDEM CO" t:licensestatusdesc=RE-LICENSED m:ubi=602640556 m:bondamt=6000
```

## Meta Commands

```ls
metric m:ubi p:integer l:UBI t:dataTypeName=number

metric m:bondamt p:double l:BondAmt t:dataTypeName=number

entity e:bzff-4fmt l:"L&I Contractor License Data - Bond" t:attribution="Labor & Industries" t:url=https://data.wa.gov/api/views/bzff-4fmt

property e:bzff-4fmt t:meta.view v:id=bzff-4fmt v:category=Labor v:attributionLink=http://www.lni.wa.gov/TradesLicensing/Contractors/HireCon/Verify v:averageRating=0 v:name="L&I Contractor License Data - Bond" v:attribution="Labor & Industries"

property e:bzff-4fmt t:meta.view.owner v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:displayName=Estz235LI

property e:bzff-4fmt t:meta.view.tableauthor v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:roleName=editor v:displayName=Estz235LI
```

## Top Records

```ls
| businessname                  | contractorlicensenumber | contractorlicensetypecode | contractorlicensetypecodedesc | licensestatus | licensestatusdesc | ubi       | bondfirmname                       | bondaccountid | bondamt    | receivedbyl_i       | bondeffectivedate   | bondexpirationdate | bondcanceldate      | bondimpaired | bondimpaireddate | 
| ============================= | ======================= | ========================= | ============================= | ============= | ================= | ========= | ================================== | ============= | ========== | =================== | =================== | ================== | =================== | ============ | ================ | 
| 3Kam Construction LLC         | 3KAMCCL903KP            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 602959266 | AMERICAN STATES INS CO             | 6711301       | 12000.0000 | 2010-05-17T00:00:00 | 2010-05-17T00:00:00 |                    | 2011-11-10T00:00:00 |              |                  | 
| 3RD GENERATION FLOORING       | 3RDGEGF940NN            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 602640556 | Lexon Ins Co                       | 9813739       | 6000.0000  | 2012-08-14T00:00:00 | 2012-08-17T00:00:00 |                    | 2013-08-19T00:00:00 |              |                  | 
| 3RD GENERATION FLOORING       | 3RDGEGF940NN            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 602640556 | DEVELOPERS SURETY & INDEM CO       | 743297C       | 6000.0000  | 2006-08-17T00:00:00 | 2006-08-17T00:00:00 |                    | 2012-09-03T00:00:00 |              |                  | 
| 3 Tree Contracting            | 3TREETC870M6            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 602615892 | American Contractors Indem CO      | 100227666     | 12000.0000 | 2013-07-26T00:00:00 | 2013-07-24T00:00:00 |                    | 2013-10-31T00:00:00 |              |                  | 
| 411 PLUMBER                   | 411PLP*896CC            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 601709311 | PLATTE RIVER INS CO                | 41218157      | 12000.0000 | 2011-02-03T00:00:00 | 2011-01-18T00:00:00 |                    | 2012-02-07T00:00:00 |              |                  | 
| 5 Star Chimney & Masonry NW   | 5STARSC870CR            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 603242248 | Wesco Insurance Co                 | 46wb008242    | 6000.0000  | 2013-02-19T00:00:00 | 2013-02-19T00:00:00 | Until Canceled     |                     |              |                  | 
| 5 STAR PAINTING               | 5STARSP904R3            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 603072191 | Contractors Bonding & Insurance Co | SI8192        | 12000.0000 | 2012-11-13T00:00:00 | 2011-12-21T00:00:00 |                    | 2015-01-14T00:00:00 |              |                  | 
| 5 STAR PAINTING               | 5STARSP904R3            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 603072191 | Contractors Bonding & Insurance Co | SI8192        | 6000.0000  | 2010-12-23T00:00:00 | 2010-12-21T00:00:00 | 12/21/2011         |                     |              |                  | 
| 6 FRAME                       | 6FRAMF*883QN            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 603136566 | Platte River Ins Co                | CLB2713607    | 12000.0000 | 2012-11-15T00:00:00 | 2012-11-13T00:00:00 |                    | 2013-11-19T00:00:00 |              |                  | 
| 911 CONSTRUCTION PLUMBING LLC | 911COCP916LJ            | CC                        | CONSTRUCTION CONTRACTOR       | R             | RE-LICENSED       | 602798874 | AMERICAN STATES INS CO             | 6692369       | 12000.0000 | 2010-01-29T00:00:00 | 2010-01-28T00:00:00 |                    | 2013-02-12T00:00:00 |              |                  | 
```