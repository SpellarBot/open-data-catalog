# L&I Affidavit Project Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-affidavit-project-details) |
| Metadata | [Link](https://data.wa.gov/api/views/9ncw-tqjn) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9ncw-tqjn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9ncw-tqjn/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9ncw-tqjn |
| Name | L&I Affidavit Project Details |
| Attribution | L&I |
| Category | Labor |
| Tags | contractor, affidavit, company, agency |
| Created | 2015-11-04T22:09:47Z |
| Publication Date | 2016-04-07T22:25:56Z |

## Description

Affidavit filed by an employer/contractor for work done on a public works project.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                              | Data Type     | Render Type   |
| ======== | ============== | ============================ | ================================= | ============= | ============= |
| No       |                | id                           | Affidavit ID Number               | text          | number        |
| Yes      | series tag     | agencyname                   | Awarding Agency Name              | text          | text          |
| No       |                | agencyaddress                | Awarding Agency Address           | text          | text          |
| Yes      | series tag     | agencycontact                | Awarding Agency Contact Person    | text          | text          |
| Yes      | series tag     | agencycontactphone           | Agency Phone Number               | text          | text          |
| Yes      | series tag     | primecompany                 | Prime Contractor Name             | text          | text          |
| Yes      | series tag     | primecompanyphone            | Contractor Phone Number           | text          | text          |
| Yes      | series tag     | primelicense                 | Contractor License                | text          | text          |
| Yes      | series tag     | primeubi                     | Contractor's UBI                  | text          | text          |
| No       |                | bidduedate                   | Project Bid Due Date              | calendar_date | calendar_date |
| No       |                | awarddate                    | Project Award Date                | calendar_date | calendar_date |
| Yes      | series tag     | contractname                 | Contract Name                     | text          | text          |
| Yes      | series tag     | contractnumber               | Contract Number                   | text          | text          |
| No       |                | projectlocation              | Project Site Address              | text          | text          |
| Yes      | numeric metric | amount                       | Amount                            | number        | number        |
| Yes      | numeric metric | intent                       | Intent ID                         | number        | number        |
| Yes      | time           | formreceiveddate             | Affidavit Received Date           | calendar_date | calendar_date |
| Yes      | series tag     | city                         | City                              | text          | text          |
| No       |                | projectcompletiondate        | Work Completion Date              | calendar_date | calendar_date |
| Yes      | numeric metric | contractamount               | Contract Amount                   | number        | number        |
| Yes      | series tag     | owner_operatorsworked        | Did Owner/Operators Perform Work? | text          | text          |
| Yes      | numeric metric | numberofowner_operatorworked | NumberOfOwnerWorked               | number        | number        |
| Yes      | series tag     | formfiledby                  | FormFiledBy                       | text          | text          |
| Yes      | series tag     | allworksubcontracted         | AllWorkSubcontracted?             | text          | text          |
| Yes      | series tag     | anysubcontractor             | AnySubContractor?                 | text          | text          |
| Yes      | series tag     | yourcompanyemployeesworked   | YourCompanyEmployeesWorked?       | text          | text          |
| Yes      | series tag     | anyapprentices               | AnyApprentices?                   | text          | text          |
| Yes      | series tag     | license                      | FilingCompanyLicense              | text          | text          |
| Yes      | series tag     | ubi                          | FilingCompanyUBI                  | text          | text          |
| Yes      | series tag     | name                         | FilingCompanyName                 | text          | text          |
| Yes      | series tag     | phone                        | FilingCompanyPhone                | text          | text          |
| Yes      | series tag     | phoneext                     | PhoneEXT                          | text          | text          |
| Yes      | series tag     | email                        | FilngCompanyEmail                 | text          | text          |
| No       |                | address1                     | FilingCompanyAddress1             | text          | text          |
| No       |                | address2                     | FilingCompanyAddress2             | text          | text          |
| Yes      | series tag     | companycity                  | FilingCompanyCity                 | text          | text          |
| Yes      | series tag     | state                        | FilingCompanyState                | text          | text          |
| Yes      | series tag     | zipcode                      | FilingCompanyZipCode              | text          | text          |
| Yes      | series tag     | insuranceaccount             | FilingCompanyInsuranceAccount     | text          | text          |
| No       |                | workstartdate                | Work Start Date                   | calendar_date | calendar_date |
| Yes      | series tag     | prime_sintentnumber          | Prime'sIntentNumber               | text          | number        |
| Yes      | series tag     | aarafundsused                | AARAFundsUsed?                    | text          | text          |
| Yes      | series tag     | weatherizationfundsused      | WeatherizationFundsUsed?          | text          | text          |
```

## Time Field

```ls
Value = formreceiveddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,agencyaddress,bidduedate,projectlocation,awarddate,projectcompletiondate,address1,address2,workstartdate
```

## Data Commands

```ls
series e:9ncw-tqjn d:2016-12-09T00:00:00.000Z t:owner_operatorsworked=No t:phone=3607343600 t:primeubi=371007502 t:state=WA t:allworksubcontracted=No t:anyapprentices=No t:prime_sintentnumber=767551 t:contractname="Heat Pump Replacement" t:city=Bellingham t:ubi=371007502 t:name="DIAMOND B CONSTRUCTORS INC" t:agencyname="BELLINGHAM SCHOOL DISTRICT #501" t:agencycontact=Purchasing t:license=DIAMOBC066KA t:primelicense=DIAMOBC066KA t:aarafundsused=No t:primecompany="DIAMOND B CONSTRUCTORS INC" t:zipcode=98226 t:anysubcontractor=No t:agencycontactphone=3606715951 t:formfiledby=Colon,Michelle t:primecompanyphone=3607343600 t:weatherizationfundsused=No t:email=mcolon@dbnw.com t:yourcompanyemployeesworked=Yes t:insuranceaccount=12644100 t:contractnumber=2001500138 t:companycity=BELLINGHAM m:amount=82367.43 m:numberofowner_operatorworked=0 m:contractamount=82367.43 m:intent=767551

series e:9ncw-tqjn d:2017-03-17T00:00:00.000Z t:owner_operatorsworked=Yes t:phone=2063352723 t:primeubi=578075342 t:state=WA t:allworksubcontracted=No t:anyapprentices=No t:prime_sintentnumber=818530 t:contractname="Admin Office, Dan Stevens' Office / 12706" t:city=Shoreline t:ubi=601770421 t:name="INTERIOR VISIONS" t:agencyname="SHORELINE SCHOOL DISTRICT #412" t:agencycontact="Kim Angel" t:license=INTERV*982C2 t:primelicense=CHARLHB296C6 t:aarafundsused=No t:primecompany="CHARLES H BERESFORD CO INC" t:zipcode=98087 t:anysubcontractor=No t:agencycontactphone=2063936111 t:formfiledby=Fischer,Aaron t:primecompanyphone=2062846658 t:weatherizationfundsused=No t:email=afischer@interiorvisionsnw.com t:yourcompanyemployeesworked=No t:insuranceaccount=17935600 t:companycity=LYNNWOOD m:amount=1208.07 m:numberofowner_operatorworked=1 m:contractamount=635.75 m:intent=819964

series e:9ncw-tqjn d:2016-07-24T00:00:00.000Z t:owner_operatorsworked=Yes t:phone=5099307470 t:primeubi=602556199 t:state=WA t:allworksubcontracted=No t:anyapprentices=No t:prime_sintentnumber=747290 t:contractname="Roosevelt Elementary Classroom and Commons Addition" t:city=granger t:ubi=602099341 t:name="THE GUTTER GUYS" t:agencyname="GRANGER SCHOOL DISTRICT #204" t:agencycontact="Margarita C. Lopez" t:license=GUTTEG*945O5 t:primelicense=BANLICL881CB t:aarafundsused=No t:primecompany="BANLIN CONSTRUCTION LLC" t:zipcode=98902 t:anysubcontractor=No t:agencycontactphone=509 t:formfiledby=kessler,kenneth t:primecompanyphone=5095862000 t:weatherizationfundsused=No t:email=thegutterguysofyakima@gmail.com t:yourcompanyemployeesworked=Yes t:insuranceaccount=12288600 t:contractnumber=14029 t:companycity=YAKIMA m:amount=3270732.78 m:numberofowner_operatorworked=1 m:contractamount=3065 m:intent=767152
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Estimated Contract Amount" t:dataTypeName=number

metric m:intent p:integer l:"Intent ID" d:"Intent ID Number" t:dataTypeName=number

metric m:contractamount p:double l:"Contract Amount" d:"Contract Amount" t:dataTypeName=number

metric m:numberofowner_operatorworked p:integer l:NumberOfOwnerWorked d:"Number Of Owner Operators Who Performed Work" t:dataTypeName=number

entity e:9ncw-tqjn l:"L&I Affidavit Project Details" t:attribution=L&I t:url=https://data.wa.gov/api/views/9ncw-tqjn

property e:9ncw-tqjn t:meta.view v:id=9ncw-tqjn v:category=Labor v:averageRating=0 v:name="L&I Affidavit Project Details" v:attribution=L&I

property e:9ncw-tqjn t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:9ncw-tqjn t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| id     | agencyname                                | agencyaddress                                  | agencycontact      | agencycontactphone | primecompany                | primecompanyphone | primelicense | primeubi  | bidduedate          | awarddate           | contractname                                        | contractnumber | projectlocation                                            | amount     | intent | formreceiveddate    | city        | projectcompletiondate | contractamount | owner_operatorsworked | numberofowner_operatorworked | formfiledby     | allworksubcontracted | anysubcontractor | yourcompanyemployeesworked | anyapprentices | license      | ubi       | name                       | phone      | phoneext | email                            | address1                       | address2 | companycity | state | zipcode | insuranceaccount | workstartdate       | prime_sintentnumber | aarafundsused | weatherizationfundsused | 
| ====== | ========================================= | ============================================== | ================== | ================== | =========================== | ================= | ============ | ========= | =================== | =================== | =================================================== | ============== | ========================================================== | ========== | ====== | =================== | =========== | ===================== | ============== | ===================== | ============================ | =============== | ==================== | ================ | ========================== | ============== | ============ | ========= | ========================== | ========== | ======== | ================================ | ============================== | ======== | =========== | ===== | ======= | ================ | =================== | =================== | ============= | ======================= | 
| 686737 | BELLINGHAM SCHOOL DISTRICT #501           | PO BOX 878 BELLINGHAM, WA - 98227              | Purchasing         | 3606715951         | DIAMOND B CONSTRUCTORS INC  | 3607343600        | DIAMOBC066KA | 371007502 | 2016-05-26T00:00:00 | 2016-05-31T00:00:00 | Heat Pump Replacement                               | 2001500138     |                                                            | 82367.43   | 767551 | 2016-12-09T00:00:00 | Bellingham  | 2016-11-04T00:00:00   | 82367.43       | No                    | 0                            | Colon,Michelle  | No                   | No               | Yes                        | No             | DIAMOBC066KA | 371007502 | DIAMOND B CONSTRUCTORS INC | 3607343600 |          | mcolon@dbnw.com                  | 3436 AIRPORT DR                |          | BELLINGHAM  | WA    | 98226   | 12644100         | 2016-01-01T00:00:00 | 767551              | No            | No                      | 
| 703996 | SHORELINE SCHOOL DISTRICT #412            | 18560 1ST AVE NE SHORELINE, WA - 98155         | Kim Angel          | 2063936111         | CHARLES H BERESFORD CO INC  | 2062846658        | CHARLHB296C6 | 578075342 | 2017-03-01T00:00:00 | 2017-03-01T00:00:00 | Admin Office, Dan Stevens' Office / 12706           |                |                                                            | 1208.07    | 819964 | 2017-03-17T00:00:00 | Shoreline   | 2017-03-07T00:00:00   | 635.75         | Yes                   | 1                            | Fischer,Aaron   | No                   | No               | No                         | No             | INTERV*982C2 | 601770421 | INTERIOR VISIONS           | 2063352723 |          | afischer@interiorvisionsnw.com   | 15720 Manor Way                | Suite J4 | LYNNWOOD    | WA    | 98087   | 17935600         | 2017-01-07T00:00:00 | 818530              | No            | No                      | 
| 655337 | GRANGER SCHOOL DISTRICT #204              | PO BOX 400 GRANGER, WA - 98932                 | Margarita C. Lopez | 509                | BANLIN CONSTRUCTION LLC     | 5095862000        | BANLICL881CB | 602556199 | 2016-01-26T00:00:00 | 2016-02-12T00:00:00 | Roosevelt Elementary Classroom and Commons Addition | 14029          |                                                            | 3270732.78 | 767152 | 2016-07-24T00:00:00 | granger     | 2016-07-22T00:00:00   | 3065           | Yes                   | 1                            | kessler,kenneth | No                   | No               | Yes                        | No             | GUTTEG*945O5 | 602099341 | THE GUTTER GUYS            | 5099307470 |          | thegutterguysofyakima@gmail.com  | 732 SUMMITVIEW AVE #722        |          | YAKIMA      | WA    | 98902   | 12288600         | 2016-01-12T00:00:00 | 747290              | No            | No                      | 
| 701459 | CLARK COUNTY PUBLIC UTILITY DISTRICT      | PO BOX 8900 VANCOUVER, WA - 98668              | Cathy Wannamaker   | 3609928834         | TEAM CONSTRUCTION LLC       | 3606991477        | TEAMCCL941RE | 602534878 | 2016-08-11T00:00:00 | 2016-08-23T00:00:00 | CPU Electric Center Renovation                      | 993            | 1200 Ft. Vancouver Way Vancouver, WA 98663                 | 523028.92  | 792751 | 2017-03-02T00:00:00 | Vancouver   | 2017-01-27T00:00:00   | 15645          | No                    | 0                            | Harrison,Nadine | No                   | No               | Yes                        | No             | SPEEDAG158JH | 600556588 | SPEEDY AUTO GLASS INC      | 6044312296 |          | nadine.harrison@tcgi.com         | 650 Pelham Boulevard - Ste 100 |          | SAINT PAUL  | MN    | 55114   | 47585301         | 2016-01-01T00:00:00 | 787991              | No            | No                      | 
| 636424 | CENTRAL PUGET SOUND REGIONAL TRANSIT AUTH | 401 S JACKSON ST SEATTLE, WA - 98104-2826      | Frank Swanson      | 2069037467         | TURNER CONSTRUCTION COMPANY | 2122296000        | TURNECC237D2 | 600205784 | 2011-10-19T00:00:00 | 2012-11-15T00:00:00 | Capitol Hill Station                                | U240           | 1830 Broadway, Seattle WA 98122                            | 104850276  | 617545 | 2016-04-20T00:00:00 | SEATTLE     | 2016-01-15T00:00:00   | 332559         | No                    | 0                            | GUTHMILLER,MARY | No                   | No               | Yes                        | No             | DBEELEI912PM | 602952513 | DBE ELECTRIC INC           | 2538878089 |          | danielle@dbeelectricinc.com      | PO BOX 9169                    |          | KENT        | WA    | 98042   | 88629702         | 2014-01-01T00:00:00 | 544499              | No            | No                      | 
| 670721 | CASCADE SCHOOL DISTRICT #228              | 330 EVANS STREET LEAVENWORTH, WA - 98826       | Linda Colasurdo    | 5098858804         | SMITH EXCAVATION            | 5097820446        | SMITHE*952B1 | 602455594 | 2016-03-24T00:00:00 | 2016-04-21T00:00:00 | Cascade High School Early Site Development          | N/A            | Cascade high School, 10190 Chumstick Road, Leavenworth, WA | 459252.86  | 793148 | 2016-10-04T00:00:00 | LEAVENWORTH | 2016-09-16T00:00:00   | 58120          | No                    | 0                            | Harmon,Kimberly | No                   | No               | Yes                        | No             | BECKSEI066PO | 601412409 | BECKSTEAD ELECTRIC INC     | 5096631148 |          | beinc@becksteadelectric.com      | 92 9TH ST C                    |          | WENATCHEE   | WA    | 98801   | 58771001         | 2016-01-09T00:00:00 | 769157              | No            | No                      | 
| 670853 | UNIVERSITY OF WASHINGTON                  | 1125 NE 180th STREET BOTHELL, WA - 98011-1713  | James Evans        | 2065432694         | C T S                       | 2066862000        | CTS**TS881BK | 602970115 | 2016-04-25T00:00:00 | 2016-05-10T00:00:00 | UW 2nd Floor TI AP Project                          | EI649184       | 18115 Campus Way NE Bothell, WA 98011                      | 3373.2     | 763644 | 2016-10-04T00:00:00 | Bothell     | 2016-07-15T00:00:00   | 3632.94        | No                    | 0                            | Sweatman,Carmen | No                   | No               | Yes                        | No             | CTS**TS881BK | 602970115 | C T S                      | 2066862000 |          | carmens@fgctacoma.com            | 2720 S ASH ST                  |          | TACOMA      | WA    | 98409   | 18652300         | 2016-01-16T00:00:00 | 763644              | No            | No                      | 
| 655226 | NORTH MASON SCHOOL DISTRICT #403          | 71 E CAMPUS DR BELFAIR, WA - 98528             | MICHELLE WALLER    | 3602772100         | BARGREEN ELLINGSON INC      | 2534759201        | BARGRE*336OJ | 278038615 | 2016-04-17T00:00:00 | 2016-04-18T00:00:00 | BELFAIR ELEMENTARY DISHWASHER                       | 7001500017     |                                                            | 23838.17   | 775087 | 2016-07-22T00:00:00 | BELFAIR     | 2016-06-16T00:00:00   | 23838.17       | No                    | 0                            | WILSON,KIM      | Yes                  | Yes              | No                         | No             | BARGRE*336OJ | 278038615 | BARGREEN ELLINGSON INC     | 2534759201 |          | kwilson@bargreen.com             | 2925 70TH AVE E                |          | TACOMA      | WA    | 98424   | 24220600         | 2016-01-01T00:00:00 | 775087              | No            | No                      | 
| 660614 | EDMONDS, CITY OF                          | 121 - 5TH AVE N EDMONDS, WA - 98020            | Ed Sibrel          | 4257710220         | RODARTE CONSTRUCTION INC    | 2539390532        | RODARI*225D9 | 600264803 | 2016-01-26T00:00:00 | 2016-02-16T00:00:00 | 105th and 106th Avenue West Low Impact Developement | E3FH/c430      |                                                            | 492275     | 782405 | 2016-08-22T00:00:00 | Edmonds     | 2016-08-12T00:00:00   | 3500           | Yes                   | 1                            | brooks,heather  | No                   | No               | Yes                        | No             | EVERGTE006DO | 601933587 | EVERGREEN TREE EXPERTS LLC | 2538759715 |          | heather@northwesttreeexperts.com | P O BOX 4142                   |          | SPANAWAY    | WA    | 98387   | 28109600         | 2016-01-12T00:00:00 | 769120              | No            | No                      | 
| 653009 | SHORELINE, CITY OF                        | 17500 MIDVALE AVE N SHORELINE, WA - 98133-4921 | Catherine Lander   | 2068012415         | GARY MERLINO CONST CO INC   | 2067629125        | GARYMCC150MW | 600584952 | 2013-10-09T00:00:00 | 2013-10-23T00:00:00 | Aurora Corridor Improvements                        | 7811           | North 192nd St. to North 205th                             | 26910578.7 | 738586 | 2016-07-11T00:00:00 | SHORELINE   | 2016-05-27T00:00:00   | 8250           | No                    | 0                            | JONES,KIMBERLEY | No                   | No               | Yes                        | No             | FAIRWMC171M9 | 600107328 | FAIRWEATHER MASONRY CO INC | 4257472000 |          | kim@fairweathermasonry.com       | 1400 140TH AVE NE              |          | BELLEVUE    | WA    | 98005   | 27217700         | 2016-01-22T00:00:00 | 608478              | No            | No                      | 
```