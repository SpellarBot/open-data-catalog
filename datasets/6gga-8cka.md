# Rec And Parks Permits Since 2015-10-01

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rec-and-parks-permits-since-2015-10-01) |
| Metadata | [Link](https://data.srcity.org/api/views/6gga-8cka) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/6gga-8cka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/6gga-8cka/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | 6gga-8cka |
| Name | Rec And Parks Permits Since 2015-10-01 |
| Category | Recreation and Culture |
| Created | 2016-02-11T05:27:41Z |
| Publication Date | 2016-02-11T06:12:45Z |

## Description

Accela Automation Rec and Parks Permits Since October 1, 2015

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
| Yes      | series tag     | units                 | Units                 | text          | text          |
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
| Yes      | series tag     | proposeduse           | ProposedUse           | text          | text          |
| Yes      | numeric metric | estprojectcost        | EstProjectCost        | money         | money         |
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
Excluded Fields = applieddate,issueddate,completeddate,originaladdress1,statusdate,contractoraddress1,contractoraddress2
```

## Data Commands

```ls
series e:6gga-8cka d:2017-04-21T00:50:03.000Z t:permitclass="Special Event" t:description="Street closure for safety during 4th of July. Gordon Lane will be blocked at intersections with Cooper Dr. using City barricades." t:statuscurrent=Issued t:permittype="Special Event Permit" t:permitnum=SP16-037 m:fee=75 m:estprojectcost=0

series e:6gga-8cka d:2017-04-21T00:50:03.000Z t:parcelnumber=034400013 t:originalcity="SANTA ROSA" t:permitclass="Street Tree" t:originalstate=CA t:originalzip=95403 t:statuscurrent="In Review" t:permittype="Street Tree Permit" t:permitnum=STR17-034 m:fee=0 m:estprojectcost=0

series e:6gga-8cka d:2017-04-21T00:50:03.000Z t:parcelnumber=049590004 t:originalcity="SANTA ROSA" t:permitclass="Street Tree" t:originalstate=CA t:originalzip=95405 t:statuscurrent=Denied t:permittype="Street Tree Permit" t:permitnum=STR17-030 m:fee=0 m:estprojectcost=0
```

## Meta Commands

```ls
metric m:contractorlicnum p:integer l:ContractorLicNum t:dataTypeName=number

metric m:estprojectcost p:integer l:EstProjectCost t:dataTypeName=money

metric m:fee p:double l:Fee t:dataTypeName=money

entity e:6gga-8cka l:"Rec And Parks Permits Since 2015-10-01" t:url=https://data.srcity.org/api/views/6gga-8cka

property e:6gga-8cka t:meta.view v:id=6gga-8cka v:category="Recreation and Culture" v:averageRating=0 v:name="Rec And Parks Permits Since 2015-10-01"

property e:6gga-8cka t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:6gga-8cka t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum | description                                                                                                                                                                                                                                                                                                  | applieddate | issueddate | completeddate | originaladdress1    | originalcity | originalstate | originalzip | permitclass   | statuscurrent | permittype           | statusdate | units | parcelnumber | contractorcompanyname | contractortrade | contractorlicnum | contractorstatelic | contractorphone | contractoraddress1 | contractoraddress2 | contractorcity | contractorstate | contractorzip | contractoremail | proposeduse | estprojectcost | fee | lastupdated         | 
| ========= | ============================================================================================================================================================================================================================================================================================================ | =========== | ========== | ============= | =================== | ============ | ============= | =========== | ============= | ============= | ==================== | ========== | ===== | ============ | ===================== | =============== | ================ | ================== | =============== | ================== | ================== | ============== | =============== | ============= | =============== | =========== | ============== | === | =================== | 
| SP16-037  | Street closure for safety during 4th of July. Gordon Lane will be blocked at intersections with Cooper Dr. using City barricades.                                                                                                                                                                            | 2016-06-06  | 2016-06-22 |               |                     |              |               |             | Special Event | Issued        | Special Event Permit | 2016-06-22 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 75  | 2017-04-21T00:50:03 | 
| STR17-034 |                                                                                                                                                                                                                                                                                                              | 2017-04-17  |            |               | 2204 SPRINGWOOD CT  | SANTA ROSA   | CA            | 95403       | Street Tree   | In Review     | Street Tree Permit   | 2017-04-17 |       | 034400013    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 0   | 2017-04-21T00:50:03 | 
| STR17-030 |                                                                                                                                                                                                                                                                                                              | 2017-03-22  |            |               | 2128 SAN ANTONIO DR | SANTA ROSA   | CA            | 95405       | Street Tree   | Denied        | Street Tree Permit   | 2017-03-24 |       | 049590004    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 0   | 2017-04-21T00:50:03 | 
| FP17-006  | Going to be taking pictures of our Zorb Balls and track as well as new Double slide for website.                                                                                                                                                                                                             | 2017-04-17  |            |               |                     |              |               |             | Filming       | Approved      | Film Permit          | 2017-04-19 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 75  | 2017-04-21T00:50:03 | 
| SP17-011  | Easter Dinner for community's homeless distribution of blessing bags; possible live music and Easter Service of some kind.Set up begins about 1pm, Event 4-6 pm. Clean up till 7pm. Other Possible Services: foot washing, haircuts and manicures.                                                           | 2017-02-21  | 2017-04-13 |               |                     |              |               |             | Special Event | Issued        | Special Event Permit | 2017-04-13 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 75  | 2017-04-21T00:50:03 | 
| SP16-065  | Victory Outreach (Alcance Victoria) will be holding a Code Red march along the sidewalk on Sebastopol Rd between Stony Point and Dutton to evangelize to the community about the issues of drugs, alcohol and prostitution. The times are 1-3pm and 9-11pm, but the amplified sound will only be from 1-3pm. | 2016-05-27  |            |               |                     |              |               |             | Special Event | Withdrawn     | Special Event Permit | 2016-10-27 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 0   | 2017-04-21T00:50:03 | 
| STR17-035 |                                                                                                                                                                                                                                                                                                              | 2017-04-19  |            |               | 217 GAREFFA WAY     | SANTA ROSA   | CA            | 95401       | Street Tree   | In Review     | Street Tree Permit   | 2017-04-19 |       | 146051005    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 0   | 2017-04-21T00:50:03 | 
| STR17-029 |                                                                                                                                                                                                                                                                                                              | 2017-03-22  | 2017-04-05 |               | 1929 WATERFORD ST   | SANTA ROSA   | CA            | 95403       | Street Tree   | Issued        | Street Tree Permit   | 2017-04-05 |       | 034473002    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 0   | 2017-04-21T00:50:03 | 
| STR16-007 |                                                                                                                                                                                                                                                                                                              | 2016-12-07  | 2016-12-07 |               | 4738 PARKTRAIL DR   | SANTA ROSA   | CA            | 95405       | Street Tree   | Issued        | Street Tree Permit   | 2016-12-07 |       | 049553030    |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 0   | 2017-04-21T00:50:03 | 
| SP16-016  | We Provide a meal, clothes, toiletries, bike repair, music, and more to the homeless people of Santa Rosa.                                                                                                                                                                                                   | 2016-03-01  | 2016-04-13 |               |                     |              |               |             | Special Event | Closed        | Special Event Permit | 2016-04-27 |       |              |                       |                 |                  |                    |                 |                    |                    |                |                 |               |                 |             | 0              | 135 | 2017-04-21T00:50:03 | 
```