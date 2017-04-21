# L&I Intent Project Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-intent-project-details) |
| Metadata | [Link](https://data.wa.gov/api/views/t9je-9qwa) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/t9je-9qwa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/t9je-9qwa/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | t9je-9qwa |
| Name | L&I Intent Project Details |
| Attribution | L&I |
| Category | Labor |
| Tags | contractor, project, company or agency |
| Created | 2015-11-10T20:04:04Z |
| Publication Date | 2016-04-07T20:32:31Z |

## Description

Intent filed by an employer/contractor for work on a public works project.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================================ | ============= | ============= |
| Yes      | series tag     | intent_id                      | Intent ID Number                             | text          | number        |
| Yes      | series tag     | agencyname                     | Awarding Agency Name                         | text          | text          |
| No       |                | awarding_agency_address        | Awarding Agency Address                      | text          | text          |
| Yes      | series tag     | agencycontact                  | Agency Contact                               | text          | text          |
| Yes      | series tag     | agencyphone                    | Agency Phone                                 | text          | text          |
| Yes      | series tag     | prime_company_name             | Prime Contractor Name                        | text          | text          |
| Yes      | series tag     | prime_phone_number             | Prime Contractor Phone                       | text          | text          |
| Yes      | series tag     | prime_contractor_reg_number    | Prime Contractor's License                   | text          | text          |
| Yes      | series tag     | prime_ubi_number               | Prime Contractor's UBI                       | text          | text          |
| No       |                | bid_due_date                   | Project Bid Due Date                         | calendar_date | calendar_date |
| No       |                | cntrct_award_dt                | Project Contract Award Date                  | calendar_date | calendar_date |
| Yes      | series tag     | contractname                   | Contract Name                                | text          | text          |
| Yes      | series tag     | contractnumber                 | Contract Number                              | text          | text          |
| Yes      | series tag     | projectlocation                | Project Location                             | text          | text          |
| Yes      | numeric metric | amount                         | Estimated Contract Amount                    | number        | number        |
| Yes      | time           | application_received_date      | Intent Received Date                         | calendar_date | calendar_date |
| Yes      | series tag     | city                           | City                                         | text          | text          |
| Yes      | series tag     | anysubcontractor               | Any Sub Contractor?                          | text          | text          |
| Yes      | series tag     | anyapprentices                 | Any Apprentices?                             | text          | text          |
| Yes      | numeric metric | cntrct_amt                     | Contract Amount                              | number        | number        |
| No       |                | time_matr_flg                  | Time And Materials used?                     | text          | text          |
| Yes      | series tag     | allworksubcontracted           | Was All Work Subcontracted Out?              | text          | text          |
| Yes      | series tag     | owner_operatorsworked          | Did Owner/Operators Perform Work?            | text          | text          |
| Yes      | numeric metric | numberofowner_operatorworked   | Number Of Owner Operators Who Performed Work | number        | number        |
| Yes      | series tag     | yourcompanyemployeesworked     | YourCompanyEmployeesWorked?                  | text          | text          |
| Yes      | series tag     | aarafundsused                  | AARAFundsUsed?                               | text          | text          |
| Yes      | series tag     | weatherizationfundsused        | WeatherizationFundsUsed?                     | text          | text          |
| Yes      | series tag     | license                        | License                                      | text          | text          |
| Yes      | series tag     | ubi                            | UBI                                          | text          | text          |
| Yes      | series tag     | companyname                    | Company Name                                 | text          | text          |
| Yes      | series tag     | phone                          | Phone                                        | text          | text          |
| Yes      | series tag     | email                          | Email                                        | text          | text          |
| No       |                | companyaddress1                | Company Address1                             | text          | text          |
| No       |                | companyaddress2                | Company Address2                             | text          | text          |
| Yes      | series tag     | companycity                    | Company City                                 | text          | text          |
| Yes      | series tag     | companystate                   | Company State                                | text          | text          |
| Yes      | series tag     | companyzip                     | Company Zip                                  | text          | text          |
| Yes      | series tag     | insuranceaccount               | Insurance Account                            | text          | text          |
| Yes      | series tag     | hiringcomapanylicense          | Hiring Comapany License                      | text          | text          |
| Yes      | series tag     | hiringcomapanyubi              | Hiring Comapany UBI                          | text          | text          |
| Yes      | series tag     | hiringcompanyname              | Hiring Company Name                          | text          | text          |
| Yes      | series tag     | hiringcomapanyinsuranceaccount | Hiring Company Insurance                     | text          | text          |
| No       |                | expected_start_dt              | Expected Work Start Date                     | calendar_date | calendar_date |
| Yes      | numeric metric | primeintent                    | Prime Intent                                 | number        | text          |
```

## Time Field

```ls
Value = application_received_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = awarding_agency_address,bid_due_date,cntrct_award_dt,time_matr_flg,companyaddress1,companyaddress2,expected_start_dt
```

## Data Commands

```ls
series e:t9je-9qwa d:2012-06-27T00:00:00.000Z t:owner_operatorsworked=No t:projectlocation="3045 16th Ave SW
Seattle   WA" t:companystate=WA t:phone=2538594444 t:intent_id=519259 t:prime_company_name="IMCO GENERAL CONSTRUCTION INC" t:allworksubcontracted=No t:anyapprentices=No t:companyzip=98032 t:agencyphone=2067283179 t:contractname="Port of Seattle Terminal 10 Utility Infrastructure Upgrade Project" t:city=seattle t:hiringcompanyname="VERSATILE DRILLING CONTRS INC" t:ubi=600630026 t:prime_contractor_reg_number=IMCOGI*215R1 t:agencyname="SEATTLE, PORT OF" t:agencycontact="Paul Powell" t:prime_ubi_number=600320655 t:aarafundsused=No t:anysubcontractor=No t:companyname="Brundage Bone Concrete Pumping, Inc." t:hiringcomapanylicense=VERSADC158CH t:weatherizationfundsused=No t:email=annieflanagan@brundagebone.com t:yourcompanyemployeesworked=Yes t:hiringcomapanyubi=600556269 t:insuranceaccount=50280300 t:contractnumber=MC-0316874 t:companycity=Kent t:prime_phone_number=3606713936 m:amount=4390000 m:cntrct_amt=10000 m:numberofowner_operatorworked=0 m:primeintent=458982

series e:t9je-9qwa d:2010-03-16T00:00:00.000Z t:owner_operatorsworked=No t:companystate=WA t:phone=5099221206 t:intent_id=281052 t:prime_company_name="HARCON INCORPORATED" t:allworksubcontracted=No t:anyapprentices=No t:companyzip=99211 t:agencyphone=5096844548 t:contractname="Barstow Bridge Replacement" t:city=N/A t:ubi=601603787 t:prime_contractor_reg_number=HARCOI*166M5 t:agencyname="STEVENS COUNTY PUBLIC WORKS" t:agencycontact="Jim Whitebread" t:prime_ubi_number=600534960 t:license=ROADPI*053DT t:aarafundsused=No t:anysubcontractor=No t:companyname="ROAD PRODUCTS INC" t:weatherizationfundsused=No t:email=denise@asphaltsupply.net t:yourcompanyemployeesworked=Yes t:insuranceaccount=51869001 t:contractnumber=TA-3049 t:companycity=SPOKANE t:prime_phone_number=5095368112 m:amount=13693.4 m:cntrct_amt=13693.4 m:numberofowner_operatorworked=0

series e:t9je-9qwa d:2013-11-26T00:00:00.000Z t:owner_operatorsworked=No t:companystate=WA t:phone=2538725395 t:intent_id=605322 t:prime_company_name="SKI'S PAINTING INC" t:allworksubcontracted=No t:anyapprentices=No t:companyzip=98032 t:agencyphone=4254524365 t:contractname="EAST GATE PARK SHED" t:city=BELLEVUE t:ubi=601128408 t:prime_contractor_reg_number=SKISPI*118PA t:agencyname="BELLEVUE, CITY OF" t:agencycontact="MICHAEL BOWERS" t:prime_ubi_number=601128408 t:license=SKISPI*118PA t:aarafundsused=No t:anysubcontractor=No t:companyname="SKI'S PAINTING INC" t:weatherizationfundsused=No t:email=ericam@skispainting.com t:yourcompanyemployeesworked=Yes t:insuranceaccount=51538101 t:contractnumber=FAC-30329 t:companycity=KENT t:prime_phone_number=2538725395 m:amount=2463.75 m:cntrct_amt=2463.75 m:numberofowner_operatorworked=0 m:primeintent=605322
```

## Meta Commands

```ls
metric m:amount p:double l:"Estimated Contract Amount" d:"Estimated Contract Amount" t:dataTypeName=number

metric m:cntrct_amt p:double l:"Contract Amount" d:"Estimated Contract Amount" t:dataTypeName=number

metric m:numberofowner_operatorworked p:integer l:"Number Of Owner Operators Who Performed Work" d:"Number Of Owner Operators Who Performed Work" t:dataTypeName=number

metric m:primeintent p:integer l:"Prime Intent" d:"Prime Contractor's Intent ID Number" t:dataTypeName=number

entity e:t9je-9qwa l:"L&I Intent Project Details" t:attribution=L&I t:url=https://data.wa.gov/api/views/t9je-9qwa

property e:t9je-9qwa t:meta.view v:id=t9je-9qwa v:category=Labor v:averageRating=0 v:name="L&I Intent Project Details" v:attribution=L&I

property e:t9je-9qwa t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:t9je-9qwa t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| intent_id | agencyname                                  | awarding_agency_address                  | agencycontact  | agencyphone    | prime_company_name               | prime_phone_number | prime_contractor_reg_number | prime_ubi_number | bid_due_date        | cntrct_award_dt     | contractname                                                                     | contractnumber | projectlocation                                                  | amount       | application_received_date | city       | anysubcontractor | anyapprentices | cntrct_amt | time_matr_flg | allworksubcontracted | owner_operatorsworked | numberofowner_operatorworked | yourcompanyemployeesworked | aarafundsused | weatherizationfundsused | license      | ubi       | companyname                          | phone      | email                          | companyaddress1         | companyaddress2 | companycity | companystate | companyzip | insuranceaccount | hiringcomapanylicense | hiringcomapanyubi | hiringcompanyname                | hiringcomapanyinsuranceaccount | expected_start_dt   | primeintent | 
| ========= | =========================================== | ======================================== | ============== | ============== | ================================ | ================== | =========================== | ================ | =================== | =================== | ================================================================================ | ============== | ================================================================ | ============ | ========================= | ========== | ================ | ============== | ========== | ============= | ==================== | ===================== | ============================ | ========================== | ============= | ======================= | ============ | ========= | ==================================== | ========== | ============================== | ======================= | =============== | =========== | ============ | ========== | ================ | ===================== | ================= | ================================ | ============================== | =================== | =========== | 
| 519259    | SEATTLE, PORT OF                            | PO Box 1209 SEATTLE, WA - 98111          | Paul Powell    | 2067283179     | IMCO GENERAL CONSTRUCTION INC    | 3606713936         | IMCOGI*215R1                | 600320655        | 2011-04-12T00:00:00 | 2011-05-12T00:00:00 | Port of Seattle Terminal 10 Utility Infrastructure Upgrade Project               | MC-0316874     | 3045 16th Ave SW Seattle WA                                      | 4390000      | 2012-06-27T00:00:00       | seattle    | No               | No             | 10000      | False         | No                   | No                    | 0                            | Yes                        | No            | No                      |              | 600630026 | Brundage Bone Concrete Pumping, Inc. | 2538594444 | annieflanagan@brundagebone.com | 1055 4th Avenue N       |                 | Kent        | WA           | 98032      | 50280300         | VERSADC158CH          | 600556269         | VERSATILE DRILLING CONTRS INC    |                                | 2011-08-01T00:00:00 | 458982      | 
| 281052    | STEVENS COUNTY PUBLIC WORKS                 | 185 E HAWTHORNE COLVILLE, WA 99114       | Jim Whitebread | 5096844548     | HARCON INCORPORATED              | 5095368112         | HARCOI*166M5                | 600534960        | 2010-01-25T00:00:00 | 2010-02-25T00:00:00 | Barstow Bridge Replacement                                                       | TA-3049        |                                                                  | 13693.4      | 2010-03-16T00:00:00       | N/A        | No               | No             | 13693.4    | False         | No                   | No                    | 0                            | Yes                        | No            | No                      | ROADPI*053DT | 601603787 | ROAD PRODUCTS INC                    | 5099221206 | denise@asphaltsupply.net       | PO BOX 11072            |                 | SPOKANE     | WA           | 99211      | 51869001         |                       |                   |                                  |                                | 2010-09-13T00:00:00 |             | 
| 605322    | BELLEVUE, CITY OF                           | PO BOX 90012 BELLEVUE, WA - 98009        | MICHAEL BOWERS | 4254524365     | SKI'S PAINTING INC               | 2538725395         | SKISPI*118PA                | 601128408        | 2013-11-07T00:00:00 | 2013-11-07T00:00:00 | EAST GATE PARK SHED                                                              | FAC-30329      |                                                                  | 2463.75      | 2013-11-26T00:00:00       | BELLEVUE   | No               | No             | 2463.75    | False         | No                   | No                    | 0                            | Yes                        | No            | No                      | SKISPI*118PA | 601128408 | SKI'S PAINTING INC                   | 2538725395 | ericam@skispainting.com        | 7235 S 227TH PL STE 103 |                 | KENT        | WA           | 98032      | 51538101         |                       |                   |                                  |                                | 2013-11-13T00:00:00 | 605322      | 
| 596921    | TRANSPORTATION, WASH STATE DEPT OF          | 1411 Rush Road Chehalis, WA 98532        | Colin Newell   | 3607408606     | CASCADE BRIDGE LLC               | 3607376576         | CASCABL990BQ                | 602086462        | 2012-04-25T00:00:00 | 2012-05-21T00:00:00 | Mellen Street to Blakeslee Junction - Stage 1                                    | 8272           |                                                                  | 21596149.85  | 2013-10-01T00:00:00       | Centralia  | No               | No             | 3000       | False         | No                   | No                    | 0                            | Yes                        | No            | No                      |              | 603164833 | Optimus Logistics Group, Inc.        | 3608070800 | marshall@gairservices.com      | 3623 Harrison Ave       |                 | Centralia   | WA           | 98531      | 22971100         | CASCABL990BQ          | 602086462         | CASCADE BRIDGE LLC               |                                | 2012-08-01T00:00:00 | 513692      | 
| 294417    | RIDGEFIELD SCHOOL DISTRICT #122             | 2720 S HILLHURST RD RIDGEFIELD, WA 98642 | Dave Newman    | (360) 619-1390 | KEYSTONE CONTRACTING INC         | 3608870868         | KEYSTCI132NS                | 601032411        | 2010-05-05T00:00:00 | 2010-05-17T00:00:00 | 100 Building Art Rm/Janitor Closet Conversion                                    | 2500900001     | Ridgefield High School~2724 S Hillhurst Road~Ridgefield WA 98642 | 2001.7       | 2010-06-15T00:00:00       | Ridgefield | No               | Yes            | 2001.7     | False         | No                   | No                    | 0                            | Yes                        | No            | No                      | KEYSTCI132NS | 601032411 | KEYSTONE CONTRACTING INC             | 3608870868 | keystone417@tds.net            | 417 NW 209TH ST         |                 | RIDGEFIELD  | WA           | 98642      | 57759301         |                       |                   |                                  |                                | 2010-06-21T00:00:00 |             | 
| 548596    | SEATTLE FIRE DEPARTMENT                     | 301 2ND AVE SEATTLE, WA - 98104          | Shelia Kelly   | 2063861461     | National Maintenance Contractors | 4258810500         |                             | 602604318        | 2005-07-21T00:00:00 | 2012-08-18T00:00:00 | Seattle Fire Department                                                          |                | 2nd Ave                                                          |              | 2012-09-13T00:00:00       | Seattle    | No               | No             |            | True          | No                   | Yes                   | 2                            | No                         | No            | No                      |              | 602344970 | Hilda's Cleaning Company             | 4258810500 | lisa.bennett@natmainco.com     | 2928 S Charlestown St   |                 | Seattle     | WA           | 98144      |                  |                       | 602604318         | National Maintenance Contractors |                                | 2012-09-01T00:00:00 | 509142      | 
| 643366    | SNOHOMISH COUNTY PUBLIC UTILITY DISTRICT #1 | PO BOX 1107 EVERETT, WA - 98206          | BARB IAMS      | 4257835562     | ASPLUNDH TREE EXPERT CO          | 2157844298         | ASPLUTE246DZ                | 409019409        | 2014-04-30T00:00:00 | 2014-05-01T00:00:00 | SWR - CIRCUITS 12-1811 - WOODS CREEK - DISTRIBUTION LINE CLEARANCE (RFP NO. 1561 | 77449          |                                                                  | 191030       | 2014-07-24T00:00:00       | Monroe     | No               | No             |            | True          | No                   | No                    | 0                            | Yes                        | No            | No                      | KDSERI*144BN | 600606705 | K & D SERVICES INC                   | 3606296103 | scountryman@kndservices.net    | PO BOX 12040            |                 | EVERETT     | WA           | 98206      | 82815000         | ASPLUTE246DZ          | 409019409         | ASPLUNDH TREE EXPERT CO          |                                | 2014-05-12T00:00:00 | 627640      | 
| 651318    | KENNEWICK PUBLIC HOSPITAL DISTRICT          | PO BOX 6128 KENNEWICK, WA - 99336        | Glenn Marshall | 5095865827     | C D SMITH CONSTRUCTION INC       | 9209242900         | CDSMICI963CR                | 603140786        | 2013-12-31T00:00:00 | 2013-12-31T00:00:00 | Trios Medical Office Building                                                    |                | 3730 Plaza Way, Kennewick, Wa 99338                              | 43549570     | 2014-08-28T00:00:00       | Kennewick  | No               | No             | 1917560    | False         | No                   | No                    | 0                            | Yes                        | No            | No                      | DRYWAI*091MA | 601255903 | DRYWALL INTERIORS                    | 5099439372 | drywallint@aol.com             | PO BOX 947              |                 | RICHLAND    | WA           | 99352      | 35445101         | CDSMICI963CR          | 603140786         | C D SMITH CONSTRUCTION INC       | 99767102                       | 2014-06-15T00:00:00 | 617105      | 
| 101679    | PUYALLUP SCHOOL DISTRICT #3                 | PO BOX 370 PUYALLUP, WA 98371            | Henry Hammond  | (253) 841-8775 | PACIFIC WEST CONTRACTORS INC     | 2067300344         | PACIFWC950D5                | 602467880        | 2005-09-15T00:00:00 | 2005-09-15T00:00:00 | PW-HOIST                                                                         | 060D0614       | 323-12th. St. NW~Puyallup WA 98371                               | 14450        | 2006-01-13T00:00:00       | Puyallup   | No               | No             | 14450      | False         | No                   | Yes                   | 2                            |                            |               |                         | PACIFWC950D5 | 602467880 | PACIFIC WEST CONTRACTORS INC         | 2067300344 | jlacherpacwest@msn.com         | PO BOX 4307             |                 | SPANAWAY    | WA           | 98387      |                  |                       |                   |                                  |                                | 2005-11-05T00:00:00 |             | 
| 484714    | TRANSPORTATION, WASH STATE DEPT OF          | PO BOX 47354 OLYMPIA, WA - 98504-7354    | Will Smith     | 5095771840     | GUY F ATKINSON CONST LLC         | 4252557551         | GUYFACL003R8                | 602085504        | 2011-07-27T00:00:00 | 2011-08-19T00:00:00 | Snowshed to Keechelus Dam Phase 1c-Replace snowshed and add lanes                | 8127           | 2.89 miles of I-90 in Kittitas Country, MP 57.34 to MP 60.23     | 177144342.66 | 2011-10-19T00:00:00       | HYAK       | No               | No             | 10000      | False         | No                   | Yes                   | 1                            | No                         | No            | No                      |              | 603138622 | RICHARDSON ROCKS                     | 5417845868 | richardsonrocks@msn.com        | PO Box 994              |                 | Canyonville | OR           | 97417      |                  | GUYFACL003R8          | 602085504         | GUY F ATKINSON CONST LLC         |                                | 2011-10-17T00:00:00 | 475928      | 
```