# Health Care Provider Credential Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-care-provider-credential-data) |
| Metadata | [Link](https://data.wa.gov/api/views/qxh8-f4bd) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qxh8-f4bd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qxh8-f4bd/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qxh8-f4bd |
| Name | Health Care Provider Credential Data |
| Attribution | Washington State Department of Health |
| Category | Health |
| Tags | washington, state, department, health, public, care, provider, credential |
| Created | 2016-01-20T23:20:45Z |
| Publication Date | 2016-01-25T17:39:10Z |

## Description

The Washington State Department of Health presents this information as a service to the public. True and correct copies of legal disciplinary actions taken after July 1998 are available on our Provider Credential Search site. These records are considered certified by the Department of Health. 

This includes information on health care providers.

Please contact our Customer Service Center at 360-236-4700 for information about actions before July 1998. 
The information on this site comes directly from our database and is updated daily at 10:00 a.m.. This data is a primary source for verification of credentials and is extracted from the primary database at 2:00 a.m. daily.

News releases about disciplinary actions taken against Washington State healthcare providers, agencies or facilities are on the agency's Newsroom webpage.

Disclaimer
The absence of information in the Provider Credential Search system doesn't imply any recommendation, endorsement or guarantee of competence of any healthcare professional. The presence of information in this system doesn't imply a provider isn't competent or qualified to practice. The reader is encouraged to carefully evaluate any information found in this data set.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | credentialnumber | CredentialNumber | text      | text        |
| Yes      | series tag     | lastname         | LastName         | text      | text        |
| Yes      | series tag     | firstname        | FirstName        | text      | text        |
| Yes      | series tag     | middlename       | MiddleName       | text      | text        |
| Yes      | series tag     | credentialtype   | CredentialType   | text      | text        |
| Yes      | series tag     | status           | Status           | text      | text        |
| Yes      | time           | birthyear        | BirthYear        | number    | text        |
| Yes      | numeric metric | ceduedate        | CEDueDate        | number    | text        |
| Yes      | numeric metric | firstissuedate   | FirstIssueDate   | number    | text        |
| Yes      | numeric metric | lastissuedate    | LastIssueDate    | number    | text        |
| Yes      | numeric metric | expirationdate   | ExpirationDate   | number    | text        |
| Yes      | series tag     | actiontaken      | ActionTaken      | text      | text        |
```

## Time Field

```ls
Value = birthyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qxh8-f4bd d:1985-01-01T00:00:00.000Z t:credentialnumber=VM60171312 t:middlename=Jean t:status=EXPIRED t:actiontaken=No t:lastname=Corcel t:firstname=Megan t:credentialtype="Veterinary Medication Clerk Registration" m:lastissuedate=20150407 m:expirationdate=20160430 m:firstissuedate=20141023

series e:qxh8-f4bd d:1991-01-01T00:00:00.000Z t:credentialnumber=RN60554847 t:middlename=Thomas t:status=EXPIRED t:actiontaken=No t:lastname=Paquin t:firstname=Stephen t:credentialtype="Registered Nurse License" m:lastissuedate=20150427 m:expirationdate=20160430 m:ceduedate=20180430 m:firstissuedate=20150427

series e:qxh8-f4bd d:1984-01-01T00:00:00.000Z t:credentialnumber=NC60255859 t:middlename=Lyubomirovich t:status=ACTIVE t:actiontaken=No t:lastname=Lakotiy t:firstname=Andriy t:credentialtype="Nursing Assistant Certification" m:lastissuedate=20160430 m:expirationdate=20170517 m:firstissuedate=20111130
```

## Meta Commands

```ls
metric m:ceduedate p:integer l:CEDueDate t:dataTypeName=number

metric m:firstissuedate p:integer l:FirstIssueDate t:dataTypeName=number

metric m:lastissuedate p:integer l:LastIssueDate t:dataTypeName=number

metric m:expirationdate p:integer l:ExpirationDate t:dataTypeName=number

entity e:qxh8-f4bd l:"Health Care Provider Credential Data" t:attribution="Washington State Department of Health" t:url=https://data.wa.gov/api/views/qxh8-f4bd

property e:qxh8-f4bd t:meta.view v:id=qxh8-f4bd v:category=Health v:attributionLink=https://fortress.wa.gov/doh/providercredentialsearch/ v:averageRating=60 v:name="Health Care Provider Credential Data" v:attribution="Washington State Department of Health"

property e:qxh8-f4bd t:meta.view.license v:name="Public Domain"

property e:qxh8-f4bd t:meta.view.owner v:id=ypwc-5ce7 v:profileImageUrlMedium=/api/users/ypwc-5ce7/profile_images/THUMB v:profileImageUrlLarge=/api/users/ypwc-5ce7/profile_images/LARGE v:screenName="Department of Health Open Data" v:profileImageUrlSmall=/api/users/ypwc-5ce7/profile_images/TINY v:displayName="Department of Health Open Data"

property e:qxh8-f4bd t:meta.view.tableauthor v:id=ypwc-5ce7 v:profileImageUrlMedium=/api/users/ypwc-5ce7/profile_images/THUMB v:profileImageUrlLarge=/api/users/ypwc-5ce7/profile_images/LARGE v:screenName="Department of Health Open Data" v:profileImageUrlSmall=/api/users/ypwc-5ce7/profile_images/TINY v:roleName=publisher v:displayName="Department of Health Open Data"
```

## Top Records

```ls
| credentialnumber | lastname    | firstname | middlename    | credentialtype                           | status  | birthyear | ceduedate | firstissuedate | lastissuedate | expirationdate | actiontaken | 
| ================ | =========== | ========= | ============= | ======================================== | ======= | ========= | ========= | ============== | ============= | ============== | =========== | 
| VM60171312       | Corcel      | Megan     | Jean          | Veterinary Medication Clerk Registration | EXPIRED | 1985      |           | 20141023       | 20150407      | 20160430       | No          | 
| RN60554847       | Paquin      | Stephen   | Thomas        | Registered Nurse License                 | EXPIRED | 1991      | 20180430  | 20150427       | 20150427      | 20160430       | No          | 
| NC60255859       | Lakotiy     | Andriy    | Lyubomirovich | Nursing Assistant Certification          | ACTIVE  | 1984      |           | 20111130       | 20160430      | 20170517       | No          | 
| RN60284217       | Park        | Do Yun    |               | Registered Nurse License                 | ACTIVE  | 1990      | 20190331  | 20120710       | 20170205      | 20180331       | No          | 
| PH00039907       | Ward        | David     | O             | Pharmacist License                       | ACTIVE  | 1968      | 20170512  | 20010620       | 20160430      | 20170512       | No          | 
| RN00152386       | Edwards     | Ruth      | Jessie        | Registered Nurse License                 | ACTIVE  | 1954      | 20200212  | 20031216       | 20170205      | 20180212       | No          | 
| RN60454035       | Brentlinger | Mary      | Ellen         | Registered Nurse License                 | ACTIVE  | 1960      | 20170709  | 20140304       | 20160430      | 20170709       | No          | 
| PA60558414       | Glissmeyer  | Margaret  | Law           | Physician Assistant License              | CLOSED  | 1965      |           |                |               |                | No          | 
| NC60062967       | Mercer      | Christina | Ann           | Nursing Assistant Certification          | ACTIVE  | 1983      |           | 20090223       | 20160430      | 20170502       | No          | 
| ML60655354       | Olson       | Valerie   | Gayle         | Physician And Surgeon Residency License  | ACTIVE  | 1973      |           | 20160430       | 20160624      | 20170731       | No          | 
```