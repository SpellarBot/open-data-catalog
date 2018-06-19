# L&I Contractor License Data - General

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-contractor-license-data-general-2d270) |
| Metadata | [Link](https://data.wa.gov/api/views/m8qx-ubtq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/m8qx-ubtq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/m8qx-ubtq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | m8qx-ubtq |
| Name | L&I Contractor License Data - General |
| Attribution | Labor & Industries |
| Category | Labor |
| Tags | l&i, labor & industries, contractor, licenses |
| Created | 2015-10-13T21:34:35Z |
| Publication Date | 2015-10-30T16:56:34Z |

## Description

State of Washington, Labor & Industries contractor license and registration data

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | businessname                  | BusinessName                  | text          | text          |
| Yes      | series tag     | contractorlicensenumber       | ContractorLicenseNumber       | text          | text          |
| Yes      | series tag     | contractorlicensetypecode     | ContractorLicenseTypeCode     | text          | text          |
| Yes      | series tag     | contractorlicensetypecodedesc | ContractorLicenseTypeCodeDesc | text          | text          |
| No       |                | address1                      | Address1                      | text          | text          |
| No       |                | address2                      | Address2                      | text          | text          |
| Yes      | series tag     | city                          | City                          | text          | text          |
| Yes      | series tag     | state                         | State                         | text          | text          |
| Yes      | series tag     | zip                           | Zip                           | text          | text          |
| Yes      | series tag     | phonenumber                   | PhoneNumber                   | text          | number        |
| Yes      | time           | licenseeffectivedate          | LicenseEffectiveDate          | calendar_date | calendar_date |
| No       |                | licenseexpirationdate         | LicenseExpirationDate         | calendar_date | calendar_date |
| Yes      | series tag     | businesstypecode              | BusinessTypeCode              | text          | text          |
| Yes      | series tag     | businesstypecodedesc          | BusinessTypeCodeDesc          | text          | text          |
| Yes      | series tag     | specialtycode1                | SpecialtyCode1                | text          | text          |
| Yes      | series tag     | specialtycode1desc            | SpecialtyCode1Desc            | text          | text          |
| Yes      | series tag     | specialtycode2                | SpecialtyCode2                | text          | text          |
| Yes      | series tag     | specialtycode2desc            | SpecialtyCode2Desc            | text          | text          |
| Yes      | numeric metric | ubi                           | UBI                           | number        | number        |
| Yes      | series tag     | primaryprincipalname          | PrimaryPrincipalName          | text          | text          |
| Yes      | series tag     | statuscode                    | StatusCode                    | text          | text          |
| Yes      | series tag     | contractorlicensestatus       | ContractorLicenseStatus       | text          | text          |
| No       |                | contractorlicensesuspenddate  | ContractorLicenseSuspendDate  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = licenseeffectivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address1,address2,licenseexpirationdate,contractorlicensesuspenddate
```

## Data Commands

```ls
series e:m8qx-ubtq d:2016-05-09T00:00:00.000Z t:contractorlicensetypecode=CC t:businessname="ALL IN CONST/LANDSCAPING LLC" t:phonenumber=3608407990 t:zip=98273 t:contractorlicensenumber=ALLCOCL847KZ t:businesstypecode=L t:primaryprincipalname="CLEVENGER, JACK A JR" t:specialtycode1=01 t:state=WA t:city="MOUNT VERNON" t:businesstypecodedesc="Limited Liability Company" t:contractorlicensestatus=ACTIVE t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:specialtycode1desc=GENERAL t:statuscode=A m:ubi=603614697

series e:m8qx-ubtq d:1996-05-30T00:00:00.000Z t:contractorlicensetypecode=CC t:businessname="BEANBLOSSOM BACKHOE SERVICE" t:phonenumber=5094762480 t:zip=98844 t:contractorlicensenumber=BEANBBS044KT t:businesstypecode=I t:primaryprincipalname="BEANBLOSSOM, DONALD EARL" t:specialtycode1=01 t:state=WA t:city=OROVILLE t:businesstypecodedesc=Individual t:contractorlicensestatus=ACTIVE t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:specialtycode1desc=GENERAL t:statuscode=A m:ubi=244000959

series e:m8qx-ubtq d:1999-06-04T00:00:00.000Z t:contractorlicensetypecode=CC t:businessname="T WOOD CONSTRUCTION CO INC" t:phonenumber=3603765647 t:zip=982450321 t:contractorlicensenumber=TWOODCC011LD t:businesstypecode=C t:primaryprincipalname="WOOD, TERRY E" t:specialtycode1=01 t:state=WA t:city=EASTSOUND t:businesstypecodedesc=Corporation t:contractorlicensestatus=ACTIVE t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:specialtycode1desc=GENERAL t:statuscode=A m:ubi=602932295
```

## Meta Commands

```ls
metric m:ubi p:integer l:UBI t:dataTypeName=number

entity e:m8qx-ubtq l:"L&I Contractor License Data - General" t:attribution="Labor & Industries" t:url=https://data.wa.gov/api/views/m8qx-ubtq

property e:m8qx-ubtq t:meta.view v:id=m8qx-ubtq v:category=Labor v:attributionLink=http://www.lni.wa.gov/TradesLicensing/Contractors/HireCon/default.asp v:averageRating=20 v:name="L&I Contractor License Data - General" v:attribution="Labor & Industries"

property e:m8qx-ubtq t:meta.view.license v:name="Public Domain"

property e:m8qx-ubtq t:meta.view.owner v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:displayName=Estz235LI

property e:m8qx-ubtq t:meta.view.tableauthor v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:roleName=editor v:displayName=Estz235LI
```

## Top Records

```ls
| businessname                   | contractorlicensenumber | contractorlicensetypecode | contractorlicensetypecodedesc | address1           | address2 | city         | state | zip       | phonenumber | licenseeffectivedate | licenseexpirationdate | businesstypecode | businesstypecodedesc      | specialtycode1 | specialtycode1desc | specialtycode2 | specialtycode2desc | ubi       | primaryprincipalname      | statuscode | contractorlicensestatus | contractorlicensesuspenddate | 
| ============================== | ======================= | ========================= | ============================= | ================== | ======== | ============ | ===== | ========= | =========== | ==================== | ===================== | ================ | ========================= | ============== | ================== | ============== | ================== | ========= | ========================= | ========== | ======================= | ============================ | 
| ALL IN CONST/LANDSCAPING LLC   | ALLCOCL847KZ            | CC                        | CONSTRUCTION CONTRACTOR       | 1122 WARREN ST     |          | MOUNT VERNON | WA    | 98273     | 3608407990  | 2016-05-09T00:00:00  | 2018-05-09T00:00:00   | L                | Limited Liability Company | 01             | GENERAL            |                |                    | 603614697 | CLEVENGER, JACK A JR      | A          | ACTIVE                  |                              | 
| BEANBLOSSOM BACKHOE SERVICE    | BEANBBS044KT            | CC                        | CONSTRUCTION CONTRACTOR       | PO BOX 427         |          | OROVILLE     | WA    | 98844     | 5094762480  | 1996-05-30T00:00:00  | 2018-05-21T00:00:00   | I                | Individual                | 01             | GENERAL            |                |                    | 244000959 | BEANBLOSSOM, DONALD EARL  | A          | ACTIVE                  |                              | 
| T WOOD CONSTRUCTION CO INC     | TWOODCC011LD            | CC                        | CONSTRUCTION CONTRACTOR       | PO BOX 321         |          | EASTSOUND    | WA    | 982450321 | 3603765647  | 1999-06-04T00:00:00  | 2018-06-05T00:00:00   | C                | Corporation               | 01             | GENERAL            |                |                    | 602932295 | WOOD, TERRY E             | A          | ACTIVE                  |                              | 
| DDP ROOFING SERVICES INC       | DDPRORS861K8            | CC                        | CONSTRUCTION CONTRACTOR       | 20 CONCHESTER RD   |          | GLEN MILLS   | PA    | 19342     | 6103619337  | 2014-05-28T00:00:00  | 2018-05-28T00:00:00   | C                | Corporation               | CD             | ROOFING            |                |                    | 603396822 | BECKER, PAUL J            | A          | ACTIVE                  |                              | 
| SERVPRO OF GRESHAM             | SERVPG*892PL            | CC                        | CONSTRUCTION CONTRACTOR       | PO BOX 235         |          | GRESHAM      | OR    | 97030     | 5036657752  | 2011-10-20T00:00:00  | 2018-05-22T00:00:00   | C                | Corporation               | 01             | GENERAL            |                |                    | 603152131 | MESFORD, DENNIS RICHARD   | A          | ACTIVE                  |                              | 
| ROBERT EGGE CONSTRUCTION INC   | ROBEREC151DR            | CC                        | CONSTRUCTION CONTRACTOR       | 14328 157TH AVE NE |          | WOODINVILLE  | WA    | 98072     | 4258831897  | 1985-03-19T00:00:00  | 2018-05-09T00:00:00   | C                | Corporation               | 01             | GENERAL            |                |                    | 600583401 | EGGE, ROBERT C            | A          | ACTIVE                  |                              | 
| EGRESS SPECIALTIES             | EGRESS*911KR            | CC                        | CONSTRUCTION CONTRACTOR       | 14108 E CASEY LN   |          | ELK          | WA    | 99009     | 5099999750  | 2009-05-19T00:00:00  | 2017-05-28T00:00:00   | I                | Individual                | 01             | GENERAL            |                |                    | 602924924 | MARTIN, MICHAEL POWELL JR | A          | ACTIVE                  |                              | 
| NORTH BND PLMBNG/RDNT HTNG LLC | NORTHBP890JK            | CC                        | CONSTRUCTION CONTRACTOR       | PO BOX 1532        |          | NORTH BEND   | WA    | 98045     | 4256983321  | 2011-05-01T00:00:00  | 2017-05-01T00:00:00   | L                | Limited Liability Company | AD             | PLUMBING           |                |                    | 603096761 | FRIEDMAN, PHILLIP LEE     | A          | ACTIVE                  |                              | 
| CAMCAL INC                     | CAMCAI*972KK            | CC                        | CONSTRUCTION CONTRACTOR       | 1970 MILWAUKEE WAY |          | TACOMA       | WA    | 984212702 | 2538504950  | 2003-05-12T00:00:00  | 2018-05-09T00:00:00   | C                | Corporation               | 01             | GENERAL            |                |                    | 602282226 | OSTROWSKI, JOHN P         | A          | ACTIVE                  |                              | 
| ONE CALL OF TACOMA             | ONECACT880KQ            | CC                        | CONSTRUCTION CONTRACTOR       | 2928 58TH AVE NE   |          | TACOMA       | WA    | 98422     | 2065714777  | 2012-05-18T00:00:00  | 2018-05-30T00:00:00   | L                | Limited Liability Company | 01             | GENERAL            |                |                    | 602683088 | BARBER, MARK D            | A          | ACTIVE                  |                              | 
```