# State Licensing and Credentialing Organizations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-licensing-and-credentialing-organizations) |
| Metadata | [Link](https://data.ct.gov/api/views/hips-b95a) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/hips-b95a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/hips-b95a/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | hips-b95a |
| Name | State Licensing and Credentialing Organizations |
| Attribution | DAS/BEST |
| Category | Business |
| Tags | license, credential |
| Created | 2015-04-13T20:20:08Z |
| Publication Date | 2015-05-06T17:56:22Z |

## Description

Administrating agencies for Licenses and Credentials in the eLicensing system.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | credentialdefinitionid | CredentialDefinitionId | text      | number      |
| Yes      | series tag  | credentialtypeprefix   | CredentialTypePrefix   | text      | text        |
| Yes      | series tag  | credentialsubcategory  | CredentialSubCategory  | text      | text        |
| Yes      | series tag  | credentialname         | CredentialName         | text      | text        |
| Yes      | series tag  | agencyname             | AgencyName             | text      | text        |
| Yes      | series tag  | zipcode                | ZipCode                | text      | text        |
| No       |             | address2               | Address2               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address2
```

## Data Commands

```ls
series e:hips-b95a d:2017-04-01T09:00:07.000Z t:credentialname="Medical School Faculty License" t:zipcode=06134 t:agencyname="Department of Public Health" t:credentialsubcategory=MSF t:credentialdefinitionid=481 t:credentialtypeprefix=1 m:row_number.hips-b95a=1

series e:hips-b95a d:2017-04-01T09:00:09.000Z t:credentialname="MEDICAL MARIJUANA RESEARCH PROGRAM EMPLOYEE" t:zipcode=06103 t:agencyname="Department of Consumer Protection" t:credentialdefinitionid=835 t:credentialtypeprefix=MMRE m:row_number.hips-b95a=2

series e:hips-b95a d:2017-04-01T09:00:07.000Z t:credentialname=Audiologist t:zipcode=06134 t:agencyname="Department of Public Health" t:credentialdefinitionid=424 t:credentialtypeprefix=17 m:row_number.hips-b95a=3
```

## Meta Commands

```ls
metric m:row_number.hips-b95a p:long l:"Row Number"

entity e:hips-b95a l:"State Licensing and Credentialing Organizations" t:attribution=DAS/BEST t:url=https://data.ct.gov/api/views/hips-b95a

property e:hips-b95a t:meta.view v:id=hips-b95a v:category=Business v:averageRating=0 v:name="State Licensing and Credentialing Organizations" v:attribution=DAS/BEST

property e:hips-b95a t:meta.view.license v:name="Public Domain"

property e:hips-b95a t:meta.view.owner v:id=cb78-zcxy v:screenName="Matt Shea" v:displayName="Matt Shea"

property e:hips-b95a t:meta.view.tableauthor v:id=cb78-zcxy v:screenName="Matt Shea" v:roleName=publisher v:displayName="Matt Shea"
```

## Top Records

```ls
| :updated_at | credentialdefinitionid | credentialtypeprefix | credentialsubcategory | credentialname                                                       | agencyname                        | zipcode | address2 | 
| =========== | ====================== | ==================== | ===================== | ==================================================================== | ================================= | ======= | ======== | 
| 1491037207  | 481                    | 1                    | MSF                   | Medical School Faculty License                                       | Department of Public Health       | 06134   |          | 
| 1491037209  | 835                    | MMRE                 |                       | MEDICAL MARIJUANA RESEARCH PROGRAM EMPLOYEE                          | Department of Consumer Protection | 06103   |          | 
| 1491037207  | 424                    | 17                   |                       | Audiologist                                                          | Department of Public Health       | 06134   |          | 
| 1491037208  | 830                    | ECM                  |                       | MANUFACTURER OF ELECTRONIC NICOTINE DELIVERY SYSTEM OR VAPOR PRODUCT | Department of Consumer Protection | 06103   |          | 
| 1491037208  | 177                    | ELV                  |                       | ELEVATOR TRAINEE                                                     | Department of Consumer Protection | 06106   | Room 110 | 
| 1491037207  | 443                    | 38                   |                       | Optician                                                             | Department of Public Health       | 06134   |          | 
| 1491037207  | 463                    | 39                   |                       | Asbestos Consultant-Inspector                                        | Department of Public Health       | 06134   |          | 
| 1491037208  | 393                    | HTG                  | HPG1                  | HEATING, PIPING & COOLING LIMITED CONTRACTOR                         | Department of Consumer Protection | 06106   | Room 110 | 
| 1491037208  | 188                    | HTG                  | B1                    | HEATING, PIPING & COOLING LIMITED CONTRACTOR                         | Department of Consumer Protection | 06106   | Room 110 | 
| 1491037208  | 547                    | HHHA                 |                       | Homemaker Home Health Care                                           | Department of Public Health       | 06134   |          | 
```