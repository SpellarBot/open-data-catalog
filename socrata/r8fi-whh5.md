# Benefit Corporation Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/benefit-corporation-data) |
| Metadata | [Link](https://data.ct.gov/api/views/r8fi-whh5) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/r8fi-whh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/r8fi-whh5/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | r8fi-whh5 |
| Name | Benefit Corporation Data |
| Attribution | Secretary of State, Denise Merrill |
| Category | Business |
| Tags | corporations, benefit corporation, usdocensus |
| Created | 2015-07-19T23:47:56Z |
| Publication Date | 2015-08-27T18:29:35Z |

## Description

Benefit corporations are a type of for-profit corporate entity legally obligated through their charter to provide a positive impact on society and/or the environment. Connecticut?s legislation allowing the creation of benefit corporations went into effect October 1, 2014

Updated Monthly.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type     | Render Type   |
| ======== | ============== | ================ | ================= | ============= | ============= |
| Yes      | numeric metric | businessid       | Business Id       | number        | number        |
| Yes      | series tag     | businessname     | Business Name     | text          | text          |
| No       |                | businessaddress1 | Business Address1 | text          | text          |
| No       |                | businessaddress2 | Business Address2 | text          | text          |
| Yes      | series tag     | businesscity     | Business City     | text          | text          |
| Yes      | series tag     | businessstate    | Business State    | text          | text          |
| Yes      | series tag     | businesszip4     | Business Zip4     | text          | text          |
| Yes      | series tag     | businesszip5     | Business Zip5     | text          | text          |
| No       |                | mailingaddress1  | Mailing Address1  | text          | text          |
| No       |                | mailingaddress2  | Mailing Address2  | text          | text          |
| Yes      | series tag     | mailingzip4      | Mailing Zip4      | text          | text          |
| Yes      | series tag     | mailingzip5      | Mailing Zip5      | text          | text          |
| Yes      | series tag     | mailingcity      | Mailing City      | text          | text          |
| Yes      | series tag     | mailingstate     | Mailing State     | text          | text          |
| Yes      | series tag     | emailid          | Email Id          | text          | text          |
| Yes      | time           | dateincorporated | Date Incorporated | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dateincorporated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = businessaddress1,businessaddress2,mailingaddress1,mailingaddress2
```

## Data Commands

```ls
series e:r8fi-whh5 d:2004-03-26T00:00:00.000Z t:businessname="THE ART OF TAO LABOSSIERE, INC." t:mailingstate=CT t:emailid=amylalala11@yahoo.com m:businessid=779572

series e:r8fi-whh5 d:2014-10-01T00:00:00.000Z t:businessname="GOODSTREETS, INC." m:businessid=1156168

series e:r8fi-whh5 d:2014-09-08T00:00:00.000Z t:businessname="DONATIONEASE INC." t:emailid=ANDY.QUINN@DONATIONEASE.COM m:businessid=1153823
```

## Meta Commands

```ls
metric m:businessid p:integer l:"Business Id" d:"Unique Id" t:dataTypeName=number

entity e:r8fi-whh5 l:"Benefit Corporation Data" t:attribution="Secretary of State, Denise Merrill" t:url=https://data.ct.gov/api/views/r8fi-whh5

property e:r8fi-whh5 t:meta.view v:id=r8fi-whh5 v:category=Business v:attributionLink=http://www.concord-sots.ct.gov/CONCORD v:averageRating=0 v:name="Benefit Corporation Data" v:attribution="Secretary of State, Denise Merrill"

property e:r8fi-whh5 t:meta.view.license v:name="Public Domain"

property e:r8fi-whh5 t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:r8fi-whh5 t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| businessid | businessname                      | businessaddress1 | businessaddress2 | businesscity | businessstate | businesszip4 | businesszip5 | mailingaddress1     | mailingaddress2 | mailingzip4 | mailingzip5 | mailingcity   | mailingstate | emailid                      | dateincorporated    | 
| ========== | ================================= | ================ | ================ | ============ | ============= | ============ | ============ | =================== | =============== | =========== | =========== | ============= | ============ | ============================ | =================== | 
| 779572     | THE ART OF TAO LABOSSIERE, INC.   |                  |                  |              |               |              |              |                     |                 |             |             |               | CT           | amylalala11@yahoo.com        | 2004-03-26T00:00:00 | 
| 1156168    | GOODSTREETS, INC.                 |                  |                  |              |               |              |              |                     |                 |             |             |               |              |                              | 2014-10-01T00:00:00 | 
| 1153823    | DONATIONEASE INC.                 |                  |                  |              |               |              |              |                     |                 |             |             |               |              | ANDY.QUINN@DONATIONEASE.COM  | 2014-09-08T00:00:00 | 
| 1178043    | META-E INC.                       | 257 GULF STREET  |                  | MILFOR       | CT            |              | 06460        |                     |                 |             |             |               |              | phmcvoy@gmail.com            | 2015-06-02T00:00:00 | 
| 1037395    | STILL WATERS RETREAT CENTER, INC. | NONE             |                  | X            | CT            |              | 06384        |                     |                 |             |             |               |              | amy@stillwaterspond.com      | 2011-05-09T00:00:00 | 
| 1159460    | GLOBUS FAMILY DENTAL INC          | 96 E MAIN ST     |                  | NEW BRITAIN  | CT            |              | 06051        | 55 FOX HOLLOW DRIVE |                 |             | 06096       | WINDSOR LOCKS | CT           | lakshmi.bethi@gmail.com      | 2014-11-10T00:00:00 | 
| 1170550    | D.J PARK PC                       | 207 GEORGE ST    | APT. 134         | MIDDLETOWN   | CT            |              | 06457        |                     |                 |             |             |               |              | ehdwls1102@gmail.com         | 2015-03-20T00:00:00 | 
| 1122906    | GENIUS BOX, INC.                  | 7 QUAIL COURT    |                  | SHELTON      | CT            |              | 06484        |                     |                 |             |             |               |              | info@geniusbox.me            | 2013-10-28T00:00:00 | 
| 1170908    | GREENWELL FINANCIAL, INC.         | 7 ZINN RD.       |                  | DANBURY      | CT            |              | 06811        |                     |                 |             |             |               |              | NIKKI@GREENWELLFINANCIAL.COM | 2015-03-13T00:00:00 | 
| 1091100    | WEST CORNWALL PUBLISHING COMPANY  |                  |                  |              |               |              |              |                     |                 |             |             |               |              |                              | 2012-12-06T00:00:00 | 
```