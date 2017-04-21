# 2016 Solid Waste Permit Fee Rulemaking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-solid-waste-permit-fee-rulemaking) |
| Metadata | [Link](https://data.oregon.gov/api/views/j3rx-7bui) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/j3rx-7bui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/j3rx-7bui/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | j3rx-7bui |
| Name | 2016 Solid Waste Permit Fee Rulemaking |
| Created | 2015-10-14T22:38:57Z |
| Publication Date | 2015-10-15T16:18:19Z |

## Description

Comment period is from 10/15/15 to 11/23/15

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email               | Email               | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j3rx-7bui d:2016-01-01T00:00:00.000Z t:first_name=Charlotte t:email=csahnow@uoregon.edu t:state=Oregon t:last_name=Sahnow t:comment="I highly approve the new rule changes!!" m:row_number.j3rx-7bui=1

series e:j3rx-7bui d:2016-01-01T00:00:00.000Z t:first_name=Theresa t:organization="Washington County" t:state=Oregon t:last_name=Koppang t:comment="Division 83
Materials Management Grant and Distressed County Rebates
OAR 340-083-0010

Washington County suggests that language be added to the proposed Grant Rules that:

Affected local governments will be notified, prior to the time of award, that a proposal from an applicant within the local government&acirc;&euro;&trade;s boundaries has been submitted to DEQ.

Notification of grant project proposals, within Washington County, will provide county staff the opportunity to leverage its messaging and education efforts." m:row_number.j3rx-7bui=2

series e:j3rx-7bui d:2016-01-01T00:00:00.000Z t:first_name=Pamela t:email=alleepa@gmail.com t:state=Oregon t:last_name=Allee t:comment="Proof of deconstruction (rather than pure destruction) could earn a reduction in tipping fees.  This would encourage conservation of materials and landfill space.  

I am interested in knowing if any other person or organization has suggested this, and if so, what is DEQ's response." m:row_number.j3rx-7bui=3
```

## Meta Commands

```ls
metric m:row_number.j3rx-7bui p:long l:"Row Number"

entity e:j3rx-7bui l:"2016 Solid Waste Permit Fee Rulemaking" t:url=https://data.oregon.gov/api/views/j3rx-7bui

property e:j3rx-7bui t:meta.view v:id=j3rx-7bui v:averageRating=0 v:name="2016 Solid Waste Permit Fee Rulemaking"

property e:j3rx-7bui t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:j3rx-7bui t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| first_name | last_name | email                      | organization      | state  | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | additional_document                                                                                                       | 
| ========== | ========= | ========================== | ================= | ====== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========================================================================================================================= | 
| Charlotte  | Sahnow    | csahnow@uoregon.edu        |                   | Oregon | I highly approve the new rule changes!!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | [null, null, null, null]                                                                                                  | 
| Theresa    | Koppang   |                            | Washington County | Oregon | Division 83 Materials Management Grant and Distressed County Rebates OAR 340-083-0010 Washington County suggests that language be added to the proposed Grant Rules that: Affected local governments will be notified, prior to the time of award, that a proposal from an applicant within the local government???s boundaries has been submitted to DEQ. Notification of grant project proposals, within Washington County, will provide county staff the opportunity to leverage its messaging and education efforts. | [null, null, null, null]                                                                                                  | 
| Pamela     | Allee     | alleepa@gmail.com          |                   | Oregon | Proof of deconstruction (rather than pure destruction) could earn a reduction in tipping fees. This would encourage conservation of materials and landfill space. I am interested in knowing if any other person or organization has suggested this, and if so, what is DEQ's response.                                                                                                                                                                                                                                  | [null, null, null, null]                                                                                                  | 
| Jody       | Snyder    | Jodys@wcnx.org             | Waste Connections | Oregon | Thank you for the opportunity to submit comments on the proposed update to the 2016 Solid Waste Permit Fee Rules. Waste Connections is a multi faceted solid waste management company and as such is an owner/operator of several disposal facilities. We have followed this process with interest and are in support of the phased in approach set forth in the draft for the collection of fees.                                                                                                                       | [null, null, null, null]                                                                                                  | 
| Kim        | Kaminski  | kshanle1@wm.com            | Waste Management  | Oregon | Please see attached document for comments.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | [application/pdf, IxEN0w6c-BCR-r3m_i-hzGgByr_KSYbv3StQ9IDkTbQ, WMO Ltr to DEQ re SB 245 Rulemaking 11 23 15.pdf, 1169142] | 
| Kirk       | Hamrick   | villagerecycle01@yahoo.com | Village Recycling | Oregon | We at Village Recycling believe that a new bolder approach to reuse, recycling, waste prevention and toxic reduction will be effective to increase annual recovery rates and reduce the use of toxic subtances. Funding should be made available to address the Oregon 2020 Intrim Roadmap Goals of Material Management to any person's on the right path to manage material increases.                                                                                                                                  | [application/pdf, qt5Ta-vBWZKrw7UpQP3BZltFGXyecRQ7aLnNad4LHxs, SKMBT_C28015042417480.pdf, 252309]                         | 
| Tacy       | Rutten    | trutten@orcities.org       | LOC               | Oregon |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | [application/pdf, G46uUSDUwKmmJTYjBvfe5ztCDepqhGATeUVoRn50glo, LOC comments - materials management.pdf, 222294]           | 
```