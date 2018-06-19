# Liquor Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/liquor-licenses-5a0dc) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/xv8d-bwgi) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/xv8d-bwgi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/xv8d-bwgi/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | xv8d-bwgi |
| Name | Liquor Licenses |
| Attribution | Baltimore City Liquor License Board |
| Category | City Services |
| Tags | liquor, license, permit |
| Created | 2011-07-14T15:22:24Z |
| Publication Date | 2015-07-22T14:36:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | licenseclass      | LicenseClass      | text          | text          |
| Yes      | series tag     | subclass          | SubClass          | text          | text          |
| Yes      | series tag     | licensenumber     | LicenseNumber     | text          | text          |
| Yes      | time           | licensedate       | LicenseDate       | calendar_date | calendar_date |
| No       |                | licenseenddate    | LicenseEndDate    | calendar_date | calendar_date |
| No       |                | licenseyear       | LicenseYear       | number        | text          |
| Yes      | numeric metric | licensefee        | LicenseFee        | money         | money         |
| Yes      | series tag     | certificatenumber | CertificateNumber | text          | text          |
| Yes      | series tag     | licensestatus     | LicenseStatus     | text          | text          |
| Yes      | series tag     | licenseefirstname | LicenseeFirstName | text          | text          |
| Yes      | series tag     | licenseelastname  | LicenseeLastName  | text          | text          |
| Yes      | series tag     | tradename         | TradeName         | text          | text          |
| Yes      | series tag     | corpname          | CorpName          | text          | text          |
| Yes      | series tag     | establishmentdesc | EstablishmentDesc | text          | text          |
| No       |                | dayperweek        | DayPerWeek        | text          | text          |
| Yes      | series tag     | description       | Description       | text          | text          |
| Yes      | series tag     | addrstreet        | AddrStreet        | text          | text          |
| Yes      | series tag     | addrzip           | AddrZip           | text          | text          |
```

## Time Field

```ls
Value = licensedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = licenseenddate,dayperweek,licenseyear
```

## Data Commands

```ls
series e:xv8d-bwgi d:2014-07-01T00:00:00.000Z t:licensestatus=Renewed t:corpname="SCMD, LLC" t:establishmentdesc=Adult t:addrstreet="615 FALLSWAY" t:addrzip=21202 t:tradename="SCORES BALTIMORE" t:description=NULL t:subclass=AE t:licenseefirstname=BRIAN t:certificatenumber=1300 t:licensenumber=6 t:licenseclass=AE t:licenseelastname=SHULMAN m:licensefee=1000

series e:xv8d-bwgi d:2015-05-01T00:00:00.000Z t:licensestatus=Closed t:corpname="SPIRIT OF CHESAPEAKE LODGE #1107 IBPOEW" t:establishmentdesc="Non-Profits only" t:addrstreet="2009-11 FREDERICK AVENUE" t:addrzip=21223 t:tradename="SPIRIT OF CHESAPEAKE LODGE #1107 IBPOEW" t:description="Beer, Wine, & Liquor" t:subclass=BWL t:licenseefirstname="BERNARD C." t:certificatenumber=313 t:licensenumber=16 t:licenseclass=LC t:licenseelastname="GRAHAM, JR." m:licensefee=550

series e:xv8d-bwgi d:2015-05-01T00:00:00.000Z t:licensestatus=Renewed t:corpname="CHEN'S HONG KONG RESTAURANT AT BALTIMORE, INC." t:establishmentdesc=Restaurant t:addrstreet="2426-32 CHARLES STREET NORTH" t:addrzip=21218 t:tradename="PAUL CHEN HONG KONG RESTAURANT" t:description="Beer, Wine, & Liquor" t:subclass=BWL t:licenseefirstname="HOU YIN" t:certificatenumber=382 t:licensenumber=67 t:licenseclass=LB t:licenseelastname=CHEN m:licensefee=1320
```

## Meta Commands

```ls
metric m:licensefee p:integer l:LicenseFee t:dataTypeName=money

entity e:xv8d-bwgi l:"Liquor Licenses" t:attribution="Baltimore City Liquor License Board" t:url=https://data.baltimorecity.gov/api/views/xv8d-bwgi

property e:xv8d-bwgi t:meta.view v:id=xv8d-bwgi v:category="City Services" v:attributionLink=http://www.baltimorecity.gov/Government/BoardsandCommissions/LiquorBoard.aspx v:averageRating=0 v:name="Liquor Licenses" v:attribution="Baltimore City Liquor License Board"

property e:xv8d-bwgi t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:xv8d-bwgi t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:xv8d-bwgi t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| licenseclass | subclass | licensenumber | licensedate         | licenseenddate      | licenseyear | licensefee | certificatenumber | licensestatus | licenseefirstname | licenseelastname | tradename                               | corpname                                       | establishmentdesc | dayperweek | description          | addrstreet                    | addrzip | 
| ============ | ======== | ============= | =================== | =================== | =========== | ========== | ================= | ============= | ================= | ================ | ======================================= | ============================================== | ================= | ========== | ==================== | ============================= | ======= | 
| AE           | AE       | 6             | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 2014        | 1000       | 1300              | Renewed       | BRIAN             | SHULMAN          | SCORES BALTIMORE                        | SCMD, LLC                                      | Adult             | NULL       | NULL                 | 615 FALLSWAY                  | 21202   | 
| LC           | BWL      | 16            | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 550        | 313               | Closed        | BERNARD C.        | GRAHAM, JR.      | SPIRIT OF CHESAPEAKE LODGE #1107 IBPOEW | SPIRIT OF CHESAPEAKE LODGE #1107 IBPOEW        | Non-Profits only  | 7 days     | Beer, Wine, & Liquor | 2009-11 FREDERICK AVENUE      | 21223   | 
| LB           | BWL      | 67            | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 1320       | 382               | Renewed       | HOU YIN           | CHEN             | PAUL CHEN HONG KONG RESTAURANT          | CHEN'S HONG KONG RESTAURANT AT BALTIMORE, INC. | Restaurant        | 7 days     | Beer, Wine, & Liquor | 2426-32 CHARLES STREET NORTH  | 21218   | 
| LB           | BWL      | 95            | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 1820       | 462               | Renewed       | PAULINE           | SPILIADIS        | BLACK OLIVE                             | OLIVE GROVE CATERING, INC.                     | Restaurant        | 7 days     | Beer, Wine, & Liquor | 814-16 BOND STREET SOUTH      | 21231   | 
| LB           | BWL      | 190           | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 2300       | 883               | Renewed       | JOHN              | DURKIN           | MAD RIVER BAR & GRILLE                  | MAD RIVER BALTIMORE, LLC                       | Restaurant        | 7 days     | Beer, Wine, & Liquor | 1110-12 CHARLES STREET SOUTH  | 21230   | 
| LBD7         | BWL      | 437           | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 1320       | 1247              | Renewed       | PENSIRI           | RUNGRUJIPHAISAL  | MAYUREE THAI TAVERN                     | P & T COMPANY, LLC                             | Tavern            | 7 days     | Beer, Wine, & Liquor | 2318 FLEET STREET             | 21224   | 
| LB           | BWL      | 267           | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 1520       | 1101              | Renewed       | TOM               | CHIU             | CHIU'S SUSHI                            | CHIU'S SUSHI, INC.                             | Restaurant        | 7 days     | Beer, Wine, & Liquor | 608 EXETER STREET SOUTH       | 21202   | 
| LBD7         | BWL      | 276           | 2015-05-01T00:00:00 | 2016-04-30T00:00:00 | 2015        | 1320       | 747               | Renewed       | JONATHAN          | WALLACE          | CLUB 2300                               | CLUB 2300 SPIRITS, INC                         | Tavern            | 7 days     | Beer, Wine, & Liquor | 2300 BALTIMORE STREET WEST    | 21223   | 
| LB           | BWL      | 33            | 2014-05-01T00:00:00 | 2015-04-30T00:00:00 | 2014        | 2000       | 166               | Renewed       | ROBERT            | ZISSEL           | GORDON BIERSCH BREWERY AND RESTAURANT   | HARBOR EAST BREWERY, LLC                       | Restaurant        | 7 days     | Beer, Wine, & Liquor | 1000 LANCASTER STREET SUITE B | 21202   | 
| LBHM         | BWL      | 9             | 2014-05-01T00:00:00 | 2015-04-30T00:00:00 | 2014        | 6500       | 594               | Renewed       | PATRICIA          | YEVICE-EISENBERG | RESIDENCE INN BALTIMORE INNER HARBOR    | IA URBAN HOTELS BALTIMORE TRS, LLC             | Hotel/Motel       | 7 days     | Beer, Wine, & Liquor | 17 LIGHT STREET               | 21202   | 
```