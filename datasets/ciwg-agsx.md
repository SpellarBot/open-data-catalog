# L&I Contractor License Data - Insurance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-contractor-license-data-insurance) |
| Metadata | [Link](https://data.wa.gov/api/views/ciwg-agsx) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ciwg-agsx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ciwg-agsx/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ciwg-agsx |
| Name | L&I Contractor License Data - Insurance |
| Attribution | Labor & Industries |
| Category | Labor |
| Tags | l&i, lni, labor & industries, contractor, license |
| Created | 2016-04-18T23:22:29Z |
| Publication Date | 2016-04-27T15:51:35Z |

## Description

State of Washington, Labor & Industries contractor license and insurance data

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
| Yes      | series tag     | insurancecompany              | InsuranceCompany              | text          | text          |
| Yes      | series tag     | insurancepolicyno             | InsurancePolicyNo             | text          | text          |
| Yes      | numeric metric | insuranceamt                  | InsuranceAmt                  | number        | number        |
| Yes      | time           | effectivedate                 | EffectiveDate                 | calendar_date | calendar_date |
| No       |                | expirationdate                | ExpirationDate                | calendar_date | calendar_date |
| No       |                | canceldate                    | CancelDate                    | calendar_date | calendar_date |
| No       |                | createdate                    | CreateDate                    | calendar_date | calendar_date |
| Yes      | series tag     | createdby_waoic_id            | CreatedBy_WAOIC_ID            | text          | text          |
| No       |                | lastupdatedate                | LastUpdateDate                | calendar_date | calendar_date |
| Yes      | series tag     | updatedby_waoic_id            | UpdatedBy_WAOIC_ID            | text          | text          |
| Yes      | series tag     | insuranceagencyname           | InsuranceAgencyName           | text          | text          |
```

## Time Field

```ls
Value = effectivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expirationdate,canceldate,createdate,lastupdatedate
```

## Data Commands

```ls
series e:ciwg-agsx d:2017-01-02T00:00:00.000Z t:businessname="KARJALA INC" t:contractorlicensetypecode=CC t:contractorlicensenumber=KARJAI*971RN t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:insurancecompany="Truck Ins Exchange" t:licensestatus=A t:createdby_waoic_id="L&I Staff" t:updatedby_waoic_id="L&I Staff" t:licensestatusdesc=ACTIVE t:insurancepolicyno=606309488 m:ubi=602155116 m:insuranceamt=1000000

series e:ciwg-agsx d:2016-08-10T00:00:00.000Z t:businessname="C C & R" t:contractorlicensetypecode=CC t:contractorlicensenumber=CCR**R*931JF t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:insurancecompany="Builders & Tradesmens Ins Serv" t:insuranceagencyname="DAVID CONNOLLY INS AGENCY" t:licensestatus=A t:createdby_waoic_id=142234 t:updatedby_waoic_id=142234 t:licensestatusdesc=ACTIVE t:insurancepolicyno=NA116583200 m:ubi=604026319 m:insuranceamt=1000000

series e:ciwg-agsx d:2016-08-07T00:00:00.000Z t:businessname="AMERITIVE CONSTRUCTION LLC" t:contractorlicensetypecode=CC t:contractorlicensenumber=AMERICL951OR t:contractorlicensetypecodedesc="CONSTRUCTION CONTRACTOR" t:insurancecompany="Catlin Specialty Insurance Co" t:insuranceagencyname="AIA CORP" t:licensestatus=A t:createdby_waoic_id=174547 t:updatedby_waoic_id=174547 t:licensestatusdesc=ACTIVE t:insurancepolicyno=4600100980 m:ubi=602529484 m:insuranceamt=1000000
```

## Meta Commands

```ls
metric m:ubi p:integer l:UBI t:dataTypeName=number

metric m:insuranceamt p:double l:InsuranceAmt t:dataTypeName=number

entity e:ciwg-agsx l:"L&I Contractor License Data - Insurance" t:attribution="Labor & Industries" t:url=https://data.wa.gov/api/views/ciwg-agsx

property e:ciwg-agsx t:meta.view v:id=ciwg-agsx v:category=Labor v:attributionLink=http://www.lni.wa.gov/TradesLicensing/Contractors/HireCon/Verify v:averageRating=0 v:name="L&I Contractor License Data - Insurance" v:attribution="Labor & Industries"

property e:ciwg-agsx t:meta.view.license v:name="Public Domain"

property e:ciwg-agsx t:meta.view.owner v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:displayName=Estz235LI

property e:ciwg-agsx t:meta.view.tableauthor v:id=u5wz-eny8 v:profileImageUrlMedium=/api/users/u5wz-eny8/profile_images/THUMB v:profileImageUrlLarge=/api/users/u5wz-eny8/profile_images/LARGE v:screenName=Estz235LI v:profileImageUrlSmall=/api/users/u5wz-eny8/profile_images/TINY v:roleName=editor v:displayName=Estz235LI
```

## Top Records

```ls
| businessname                   | contractorlicensenumber | contractorlicensetypecode | contractorlicensetypecodedesc | licensestatus | licensestatusdesc | ubi       | insurancecompany               | insurancepolicyno  | insuranceamt | effectivedate       | expirationdate      | canceldate | createdate          | createdby_waoic_id | lastupdatedate      | updatedby_waoic_id | insuranceagencyname            | 
| ============================== | ======================= | ========================= | ============================= | ============= | ================= | ========= | ============================== | ================== | ============ | =================== | =================== | ========== | =================== | ================== | =================== | ================== | ============================== | 
| KARJALA INC                    | KARJAI*971RN            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 602155116 | Truck Ins Exchange             | 606309488          | 1000000      | 2017-01-02T00:00:00 | 2018-01-02T00:00:00 |            | 2017-03-06T00:00:00 | L&I Staff          | 2017-03-06T00:00:00 | L&I Staff          |                                | 
| C C & R                        | CCR**R*931JF            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 604026319 | Builders & Tradesmens Ins Serv | NA116583200        | 1000000      | 2016-08-10T00:00:00 | 2017-08-10T00:00:00 |            | 2016-08-11T00:00:00 | 142234             | 2016-08-11T00:00:00 | 142234             | DAVID CONNOLLY INS AGENCY      | 
| AMERITIVE CONSTRUCTION LLC     | AMERICL951OR            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 602529484 | Catlin Specialty Insurance Co  | 4600100980         | 1000000      | 2016-08-07T00:00:00 | 2017-08-07T00:00:00 |            | 2016-08-12T00:00:00 | 174547             | 2016-08-12T00:00:00 | 174547             | AIA CORP                       | 
| PATRICK ARCHER CONSTRUCT INC   | PATRIAC948DO            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 601461284 | Rockingham Casualty Company    | RO009456050        | 1000000      | 2016-03-15T00:00:00 | 2018-03-23T00:00:00 |            | 2016-03-15T00:00:00 | 701674             | 2017-03-13T00:00:00 | 701674             | Business Ins Management Inc    | 
| DEEPROOTS LNDSCPG/ NURSERY INC | DEEPRLN917RS            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 602320401 | Ohio Security Ins Co           | BKS(17)55086326    | 1000000      | 2016-10-08T00:00:00 | 2017-10-08T00:00:00 |            | 2016-08-22T00:00:00 | 255939             | 2016-08-22T00:00:00 | 255939             | EASTMAN INS INC                | 
| ELK RIDGE CUSTOM HOMES INC     | ELKRIRC849NK            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 603539615 | MESA UNDERWRITERS SPECIALTY IN | MP0046003005367    | 1000000      | 2016-08-11T00:00:00 | 2017-08-11T00:00:00 |            | 2016-08-12T00:00:00 | L&I Staff          | 2016-08-12T00:00:00 | L&I Staff          |                                | 
| FREED LLC                      | FREEDL*928NF            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 602558264 | INTERNATIONAL INSURANCE COMPAN | CDB16/YF16CP01/015 | 5000000      | 2016-07-24T00:00:00 | 2018-07-24T00:00:00 |            | 2016-08-04T00:00:00 | 0                  | 2016-08-04T00:00:00 | 0                  | HUB INTERNATIONAL Bothell      | 
| ASK RICH LLC                   | ASKRIRL883DO            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 603185106 | Security National Insurance    | NA113189301        | 1000000      | 2016-08-13T00:00:00 | 2017-08-13T00:00:00 |            | 2016-07-13T00:00:00 | 18227              | 2016-07-13T00:00:00 | 18227              | Magaly Brewton-Hight Ins Agncy | 
| R H RENOVATIONS                | RHRENR*933NP            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 602747266 | Developers Surety & Indem Co   | BIS00001401-08     | 1000000      | 2016-08-13T00:00:00 | 2017-08-13T00:00:00 |            | 2016-07-25T00:00:00 | 129022             | 2016-07-25T00:00:00 | 129022             | WAGNER INSURANCE               | 
| GOOD EARTH WORKS               | GOODEW*091PU            | CC                        | CONSTRUCTION CONTRACTOR       | A             | ACTIVE            | 601196057 | Red Shield Ins Co              | CNT018588          | 1000000      | 2016-08-15T00:00:00 | 2017-08-15T00:00:00 |            | 2016-08-11T00:00:00 | 763280             | 2016-08-11T00:00:00 | 763280             | MADRONA POINT INSURANCE        | 
```