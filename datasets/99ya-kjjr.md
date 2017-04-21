# Maryland Public Information Act (MPIA) Request Responses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-public-information-act-mpia-request-responses-a6ba4) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/99ya-kjjr) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/99ya-kjjr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/99ya-kjjr/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 99ya-kjjr |
| Name | Maryland Public Information Act (MPIA) Request Responses |
| Category | Government |
| Tags | maryland public information act, mpia, request, responses |
| Created | 2013-09-04T14:54:04Z |
| Publication Date | 2016-03-17T12:44:10Z |

## Description

The MPIA dataset will contain a list of MPIA requests that contain information about the MPIA request as well as a web link to the MPIA response packet created by the owning departments.  Each request will contain the following information:

Requestor First Name
Requestor Last Name
Requestor Organization
Description
Intake (ie email)
Lead Department
Data Owning Departments
Date Response Posted
Who Published the Response
Link to the Response Document(s) on a public Web Site

Update Frequency:  Daily

## Columns

```ls
| Included | Schema Type | Field Name            | Name                     | Data Type     | Render Type   |
| ======== | =========== | ===================== | ======================== | ============= | ============= |
| Yes      | series tag  | sequence_id           | Sequence Number          | text          | text          |
| Yes      | series tag  | first_name            | Requestor First Name     | text          | text          |
| Yes      | series tag  | last_name             |  Requestor Last Name     | text          | text          |
| Yes      | series tag  | requestororganization | Requestor Organization   | text          | text          |
| Yes      | series tag  | requestdescription    |  Description             | text          | text          |
| Yes      | series tag  | requestintake         |  Intake                  | text          | text          |
| Yes      | series tag  | leaddepartment        |  Lead Department         | text          | text          |
| Yes      | series tag  | dataowningdepartments |  Data Owning Departments | text          | text          |
| Yes      | time        | publishdate           |  Date Response Posted    | calendar_date | calendar_date |
| Yes      | series tag  | publishedby           |  Published By            | text          | text          |
| Yes      | series tag  | responsedocumentation | Response Documentation   | url           | url           |
```

## Time Field

```ls
Value = publishdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:99ya-kjjr d:2015-02-05T00:00:00.000Z t:first_name=Kathyrn t:dataowningdepartments=FIN t:requestdescription="Request for records of unclaimed tax sale surplus." t:last_name=Clinton t:publishedby="CAUTHORN, JERI" t:responsedocumentation=http://www2.montgomerycountymd.gov/MPIA/2015-FIN-170.zip t:leaddepartment=FIN t:sequence_id=2015-FIN-170 t:requestintake=Email m:row_number.99ya-kjjr=1

series e:99ya-kjjr d:2015-02-05T00:00:00.000Z t:first_name=Mike t:dataowningdepartments=FIN t:requestdescription="Request for Montgomery County's Certificate of General Liability." t:last_name=Murphy t:publishedby="CAUTHORN, JERI" t:responsedocumentation=http://www2.montgomerycountymd.gov/MPIA/2015-FIN-171.zip t:leaddepartment=FIN t:sequence_id=2015-FIN-171 t:requestintake=Email m:row_number.99ya-kjjr=2

series e:99ya-kjjr d:2014-08-28T00:00:00.000Z t:first_name=Chuck t:dataowningdepartments=DEP t:requestdescription="Request for 2013 Biological Data and Index of Biotic Integrity (IBI)  Scores for the Ten-Mile Creek Watershed (in the Clarksburg Special Protection Area (SPA).
[NOTE:  Agreement to prepay search and retrieval fees received on July 15, 2014.]" t:last_name=Pace t:requestororganization=Newfields t:publishedby="BROGLIE, WILLIAM" t:responsedocumentation=http://www2.montgomerycountymd.gov/MPIA/2014-DEP-108.zip t:leaddepartment=DEP t:sequence_id=2014-DEP-108 t:requestintake=Email m:row_number.99ya-kjjr=3
```

## Meta Commands

```ls
metric m:row_number.99ya-kjjr p:long l:"Row Number"

entity e:99ya-kjjr l:"Maryland Public Information Act  (MPIA)  Request Responses" t:url=https://data.montgomerycountymd.gov/api/views/99ya-kjjr

property e:99ya-kjjr t:meta.view v:id=99ya-kjjr v:category=Government v:averageRating=0 v:name="Maryland Public Information Act  (MPIA)  Request Responses"

property e:99ya-kjjr t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:99ya-kjjr t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| sequence_id  | first_name | last_name | requestororganization             | requestdescription                                                                                                                                                                                                                              | requestintake | leaddepartment | dataowningdepartments | publishdate         | publishedby      | responsedocumentation                                            | 
| ============ | ========== | ========= | ================================= | =============================================================================================================================================================================================================================================== | ============= | ============== | ===================== | =================== | ================ | ================================================================ | 
| 2015-FIN-170 | Kathyrn    | Clinton   |                                   | Request for records of unclaimed tax sale surplus.                                                                                                                                                                                              | Email         | FIN            | FIN                   | 2015-02-05T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2015-FIN-170.zip, null] | 
| 2015-FIN-171 | Mike       | Murphy    |                                   | Request for Montgomery County's Certificate of General Liability.                                                                                                                                                                               | Email         | FIN            | FIN                   | 2015-02-05T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2015-FIN-171.zip, null] | 
| 2014-DEP-108 | Chuck      | Pace      | Newfields                         | Request for 2013 Biological Data and Index of Biotic Integrity (IBI) Scores for the Ten-Mile Creek Watershed (in the Clarksburg Special Protection Area (SPA). [NOTE: Agreement to prepay search and retrieval fees received on July 15, 2014.] | Email         | DEP            | DEP                   | 2014-08-28T00:00:00 | BROGLIE, WILLIAM | [http://www2.montgomerycountymd.gov/MPIA/2014-DEP-108.zip, null] | 
| 2014-DEP-124 | David      | Sobers    |                                   | Montgomery County contracts and agreements for the processing of solid waste materials and recycling                                                                                                                                            | Email         | DEP            | DEP                   | 2014-10-06T00:00:00 | BROGLIE, WILLIAM | [http://www2.montgomerycountymd.gov/MPIA/2014-DEP-124.zip, null] | 
| 2015-FIN-174 | Jeffrey    | Falbo     | Segment Returns LLC               | Request for all uncashed checks and funds.                                                                                                                                                                                                      | Email         | FIN            | FIN                   | 2015-02-12T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2015-FIN-174.zip, null] | 
| 2015-FIN-163 | Rachelle   | Lozano    |                                   | Record of unclaimed checks.                                                                                                                                                                                                                     | Email         | FIN            | FIN                   | 2015-01-02T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2015-FIN-163.zip, null] | 
| 2015-FIN-157 | Abraham    | Payton    | American Bridge 21st Century      | Records of Property Tax Payments, delinquent property tax records, and warning notices for 6212 Maiden Ln., Bethesda, MD from Dec. 2006 to May 2010.                                                                                            | Other         | FIN            | FIN                   | 2015-01-02T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2015-FIN-157.zip, null] | 
| 2015-FIN-162 | Linda      | Mericle   | Linda S. Mericle, Attorney at Law | Information regarding Citation #00000002PODPD                                                                                                                                                                                                   | USmail        | FIN            | FIN                   | 2015-01-02T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2015-FIN-162.zip, null] | 
| 2014-FIN-141 | Phil       | Walker    | Ultimate Source America           | Request for Montgomery County Government Purchase Card (P-Card) Holders' names, addresses, phone numbers and emails.                                                                                                                            | Email         | FIN            | FIN                   | 2014-10-27T00:00:00 | CAUTHORN, JERI   | [http://www2.montgomerycountymd.gov/MPIA/2014-FIN-141.zip, null] | 
| 2014-DEP-154 | Chaz       | Miller    | Waste Recycling                   | Requested data tracking the composition of recyclables Montgomery County has collected and processed over the last decade (2002-2012).                                                                                                          | Email         | DEP            | DEP                   | 2014-12-23T00:00:00 | BROGLIE, WILLIAM | [http://www2.montgomerycountymd.gov/MPIA/2014-DEP-154.zip, null] | 
```