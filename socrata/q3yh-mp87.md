# ISD Building Permit Daily Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/isd-building-permit-daily-applications) |
| Metadata | [Link](https://data.somervillema.gov/api/views/q3yh-mp87) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/q3yh-mp87/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/q3yh-mp87/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | q3yh-mp87 |
| Name | ISD Building Permit Daily Applications |
| Attribution | Citizenserve |
| Category | City Services |
| Tags | building permits, construction, isd, residential, commercial |
| Created | 2015-10-08T14:22:33Z |
| Publication Date | 2016-02-16T17:10:48Z |

## Description

All building permits are submitted online via the Citizenserve software. You can see detailed information here about these applications. Online submitter of building applications began on May of 2014.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | file               | File.              | text          | text          |
| Yes      | series tag     | permit             | Permit.            | text          | text          |
| Yes      | series tag     | permittype         | PermitType         | text          | text          |
| No       |                | address            | Address            | text          | text          |
| Yes      | series tag     | applicant          | Applicant          | text          | text          |
| No       |                | applicantaddress   | ApplicantAddress   | text          | text          |
| Yes      | series tag     | applicantcitystzip | ApplicantCityStZip | text          | text          |
| Yes      | series tag     | projectname        | ProjectName        | text          | text          |
| Yes      | time           | applicationdate    | ApplicationDate    | calendar_date | calendar_date |
| No       |                | issuedate          | IssueDate          | calendar_date | calendar_date |
| No       |                | expirationdate     | ExpirationDate     | calendar_date | calendar_date |
| Yes      | series tag     | status             | Status             | text          | text          |
| No       |                | closedate          | CloseDate          | calendar_date | calendar_date |
| Yes      | numeric metric | permitamount       | PermitAmount       | money         | money         |
| Yes      | numeric metric | amountpaid         | AmountPaid         | money         | money         |
| No       |                | latitude           | Latitude           | number        | number        |
| No       |                | longitude          | Longitude          | number        | number        |
| Yes      | series tag     | permittypedetail   | PermitTypeDetail   | text          | text          |
```

## Time Field

```ls
Value = applicationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,applicantaddress,issuedate,expirationdate,closedate,latitude,longitude
```

## Data Commands

```ls
series e:q3yh-mp87 d:2014-05-21T00:00:00.000Z t:status=Issued t:file=14-000002 t:permit=B14-000001 t:permittype="Residential Addition" t:applicant="Paul Tabajonda" t:permittypedetail=Building t:projectname="DECK CONSTRUCTIOn" t:applicantcitystzip="Somerville  MA 02145" m:permitamount=107 m:amountpaid=107

series e:q3yh-mp87 d:2014-05-21T00:00:00.000Z t:status=Issued t:file=14-000004 t:permit=E14-000001 t:permittype=Residential t:applicant="frank iannuzzi electric" t:permittypedetail=Electrical t:projectname="KITCHEN REMODEL" t:applicantcitystzip="revere ma 02151" m:permitamount=137 m:amountpaid=137

series e:q3yh-mp87 d:2014-05-21T00:00:00.000Z t:status=Withdrawn t:file=14-000007 t:permit=P14-000001 t:permittype="Residential - Existing" t:applicant="ZUCK JULIANNE" t:permittypedetail=Plumbing t:projectname="Water heater install" t:applicantcitystzip="SOMERVILLE MA 0" m:permitamount=60 m:amountpaid=0
```

## Meta Commands

```ls
metric m:permitamount p:integer l:PermitAmount t:dataTypeName=money

metric m:amountpaid p:integer l:AmountPaid t:dataTypeName=money

entity e:q3yh-mp87 l:"ISD Building Permit Daily Applications" t:attribution=Citizenserve t:url=https://data.somervillema.gov/api/views/q3yh-mp87

property e:q3yh-mp87 t:meta.view v:id=q3yh-mp87 v:category="City Services" v:averageRating=0 v:name="ISD Building Permit Daily Applications" v:attribution=Citizenserve

property e:q3yh-mp87 t:meta.view.license v:name="Public Domain"

property e:q3yh-mp87 t:meta.view.owner v:id=ta4g-utcf v:profileImageUrlMedium=/api/users/ta4g-utcf/profile_images/THUMB v:profileImageUrlLarge=/api/users/ta4g-utcf/profile_images/LARGE v:screenName="Steve Craig" v:profileImageUrlSmall=/api/users/ta4g-utcf/profile_images/TINY v:displayName="Steve Craig"

property e:q3yh-mp87 t:meta.view.tableauthor v:id=ta4g-utcf v:profileImageUrlMedium=/api/users/ta4g-utcf/profile_images/THUMB v:profileImageUrlLarge=/api/users/ta4g-utcf/profile_images/LARGE v:screenName="Steve Craig" v:profileImageUrlSmall=/api/users/ta4g-utcf/profile_images/TINY v:roleName=administrator v:displayName="Steve Craig"
```

## Top Records

```ls
| file      | permit     | permittype             | address                 | applicant                              | applicantaddress            | applicantcitystzip  | projectname                                                                                                                                                                                                                                                     | applicationdate     | issuedate           | expirationdate      | status    | closedate           | permitamount | amountpaid | latitude         | longitude         | permittypedetail | 
| ========= | ========== | ====================== | ======================= | ====================================== | =========================== | =================== | =============================================================================================================================================================================================================================================================== | =================== | =================== | =================== | ========= | =================== | ============ | ========== | ================ | ================= | ================ | 
| 14-000002 | B14-000001 | Residential Addition   | 99 GOVERNOR WINTHROP RD | Paul Tabajonda                         | 99 Govenor Winthrop Road    | Somerville MA 02145 | DECK CONSTRUCTIOn                                                                                                                                                                                                                                               | 2014-05-21T00:00:00 | 2014-05-23T00:00:00 | 2015-09-17T00:00:00 | Issued    |                     | 107          | 107        | 42.3973633       | -71.0889865       | Building         | 
| 14-000004 | E14-000001 | Residential            | 143 SUMMER ST           | frank iannuzzi electric                | 647 park ave                | revere ma 02151     | KITCHEN REMODEL                                                                                                                                                                                                                                                 | 2014-05-21T00:00:00 | 2014-05-28T00:00:00 | 2014-11-27T00:00:00 | Issued    | 2014-07-16T00:00:00 | 137          | 137        | 42.386019        | -71.1044189       | Electrical       | 
| 14-000007 | P14-000001 | Residential - Existing | 15 LESLEY AVE           | ZUCK JULIANNE                          | 13 LESLEY AVE               | SOMERVILLE MA 0     | Water heater install                                                                                                                                                                                                                                            | 2014-05-21T00:00:00 | 2014-06-04T00:00:00 | 2014-12-04T00:00:00 | Withdrawn | 2014-07-18T00:00:00 | 60           | 0          | 42.3936500549316 | -71.1153869628906 | Plumbing         | 
| 14-000008 | P14-000002 | Residential - Existing | 15 LESLEY AVE           | ZUCK JULIANNE                          | 13 LESLEY AVE               | SOMERVILLE MA 0     | Water heater install                                                                                                                                                                                                                                            | 2014-05-21T00:00:00 | 2014-05-21T00:00:00 | 2014-11-21T00:00:00 | Withdrawn | 2014-07-18T00:00:00 | 60           | 0          | 42.3936500549316 | -71.1153869628906 | Plumbing         | 
| 14-000012 | B14-000002 | Residential Repair     | 89 NEWTON ST            | NEWELL CONTRACTING                     | 450 CAMBRIDGE ST, SUITE 201 | BOSTON MA 02134     | STRUCTURAL REPAIRS IN BASEMENT. EXCAVATE AND POUR CONCRETE IN 6 NEW FOOTINGS AND NEW CONCRETE SHORING WALL. INSTALL 6 NEW LALLY COLUMNS. INSTALL NEW P.T LEDGERS AND 3 NEW BRACING RODS. STRUCTUAL ENGINEER WILL VISIT SITE, VERIFY ALL DETAILS, PROVIDE AF     | 2014-05-21T00:00:00 | 2014-05-22T00:00:00 | 2014-12-12T00:00:00 | Issued    |                     | 529          | 529        | 42.377104        | -71.097813        | Building         | 
| 14-000013 | B14-000003 | Residential Repair     | 51 PURITAN RD           | wILLIAM LOPEZ                          | 49 PURITAN RD               | SOMERVILLE MA 02145 | REMOVE OLD PLASTER AND RE SHEETROCK                                                                                                                                                                                                                             | 2014-05-21T00:00:00 | 2014-05-22T00:00:00 | 2015-01-31T00:00:00 | Issued    |                     | 100          | 50         | 42.3969383239746 | -71.0872039794922 | Building         | 
| 14-000014 | B14-000004 | Residential Addition   | 739 SOMERVILLE AVE      | allen and sons holding inc             | po 240173                   | boston ma 02124     | remove existing 3rd floor per plans and approved variance and construct new mansard per plans. add full bath to 3rd floor, renovate existing kitchen and bath on 2nd floor, above in unit 2, construct first floor and second floor rear decks per plan and var | 2014-05-21T00:00:00 | 2014-06-26T00:00:00 | 2015-10-10T00:00:00 | Issued    |                     | 3480         | 3360       | 42.386659        | -71.115172        | Building         | 
| 14-000018 | E14-000002 | Commercial             | 331 great river RD      | Cavicchi Audio Video LLC               | 547 Franklin Street         | Framingham MA 01702 | Cavicchi Audio Video LLC is installing low voltage audio, video and surveillance in the new Papagayo Restaurant located at 331 Great River RoadSomerville, MA 02145 in Assembly Square.                                                                         | 2014-05-21T00:00:00 | 2014-05-22T00:00:00 | 2014-11-22T00:00:00 | Issued    |                     | 60           | 60         | 42.3930156       | -71.0809757       | Electrical       | 
| 14-000020 | B14-000008 | Residential Repair     | 137 ALBION ST           | LaPointe Construction Board up Service | 11 Middlesex Rd Suite 6     | Wilmington MA 01877 | Emergency Service removed a gutter and fascia board off of power line                                                                                                                                                                                           | 2014-05-21T00:00:00 | 2014-05-22T00:00:00 | 2014-11-22T00:00:00 | Issued    |                     | 100          | 50         | 42.392458        | -71.1092748       | Building         | 
| 14-000021 | B14-000009 | Residential Repair     | 16 STERLING ST          | DAVID KALOUSTIAN                       | 30 FAIRVIEW AVE             | ARLINGTON MA 02474  | FRONT FIRST FLOOR PORCH SIDING AND REPLACE 6 STORM WINDOWS AND 1 STORM DOOR                                                                                                                                                                                     | 2014-05-21T00:00:00 | 2014-05-21T00:00:00 | 2014-11-21T00:00:00 | Issued    |                     | 107          | 107        | 42.4103546142578 | -71.1288452148438 | Building         | 
```