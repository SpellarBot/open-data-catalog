# LCB Local Authority Letters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lcb-local-authority-letters) |
| Metadata | [Link](https://data.wa.gov/api/views/vgcw-qfjm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/vgcw-qfjm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/vgcw-qfjm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | vgcw-qfjm |
| Name | LCB Local Authority Letters |
| Category | Public Safety |
| Created | 2014-10-31T18:54:25Z |
| Publication Date | 2015-07-01T08:02:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                   | Data Type | Render Type |
| ======== | ============== | ================= | ====================== | ========= | =========== |
| Yes      | series tag     | license           | License#               | text      | text        |
| Yes      | series tag     | ubi               | UBI                    | text      | text        |
| Yes      | series tag     | designatedsignee  | DesignatedSignee       | text      | text        |
| Yes      | numeric metric | applicationdate   | ApplicationDate        | number    | text        |
| Yes      | series tag     | countycode        | CountyCode             | text      | text        |
| Yes      | series tag     | countyname        | CountyName             | text      | text        |
| Yes      | series tag     | citycode          | CityCode               | text      | text        |
| Yes      | series tag     | cityname          | CityName               | text      | text        |
| Yes      | series tag     | corrected_amended | CORRECTED L/A /UPDATED | text      | text        |
| Yes      | series tag     | dayphone          | DayPhone               | text      | text        |
| Yes      | series tag     | contact           | Contact                | text      | text        |
| Yes      | series tag     | l_a_type          | L/A Type               | text      | text        |
| Yes      | series tag     | licenseename      | LicenseeName           | text      | text        |
| Yes      | series tag     | tradename         | Tradename              | text      | text        |
| Yes      | series tag     | streetaddress     | StreetAddress          | text      | text        |
| Yes      | series tag     | roomnumber        | RoomNumber             | text      | text        |
| Yes      | series tag     | city              | City                   | text      | text        |
| Yes      | series tag     | state             | State                  | text      | text        |
| Yes      | series tag     | zipcode           | ZipCode                | text      | text        |
| No       |                | mailaddress       | MailAddress            | text      | text        |
| Yes      | series tag     | mailroom          | MailRoom               | text      | text        |
| Yes      | series tag     | mailcity          | MailCity               | text      | text        |
| Yes      | series tag     | mailstate         | MailState              | text      | text        |
| Yes      | series tag     | mailzip           | MailZip                | text      | text        |
| Yes      | series tag     | privdesc01        | PrivDesc01             | text      | text        |
| Yes      | series tag     | privdesc02        | PrivDesc02             | text      | text        |
| Yes      | series tag     | privdesc03        | PrivDesc03             | text      | text        |
| Yes      | series tag     | privdesc04        | PrivDesc04             | text      | text        |
| Yes      | series tag     | privdesc05        | PrivDesc05             | text      | text        |
| Yes      | series tag     | privdesc06        | PrivDesc06             | text      | text        |
| Yes      | series tag     | privdesc07        | PrivDesc07             | text      | text        |
| Yes      | series tag     | privdesc08        | PrivDesc08             | text      | text        |
| Yes      | series tag     | applicants        | Applicants             | text      | text        |
| Yes      | time           | la_posted_date    | LA Posted Date         | text      | text        |
| No       |                | la_posted_time    | LA Posted Time         | number    | text        |
| Yes      | numeric metric | systemdate        | SystemDate             | number    | text        |
| Yes      | numeric metric | systemtime        | SystemTime             | number    | text        |
```

## Time Field

```ls
Value = la_posted_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = mailaddress,la_posted_time
```

## Data Commands

```ls
series e:vgcw-qfjm d:2017-04-17T00:00:00.000Z t:applicants="EL BARAK LLC                                        PAOTHONG, ARNUT                                     SUKTINTHAI, PIMJAI" t:mailcity=EVERETT t:zipcode=982013520 t:mailzip=982013520 t:state=WA t:licenseename="MEN ZONE L.L.C." t:designatedsignee="LT. JIM DUFFY" t:contact="ARNUT PAOTHONG" t:city=EVERETT t:ubi=6040945450010001 t:citycode=5 t:streetaddress="1707 HEWITT AVE" t:countyname=SNOHOMISH t:tradename="SANAE THAI CUISINE" t:dayphone=8134512668 t:mailstate=WA t:privdesc01="BEER/WINE REST - BEER/WINE" t:l_a_type=ASSUMPTION t:countycode=31 t:cityname=EVERETT t:license=088403 m:systemdate=20170411 m:applicationdate=20170405 m:systemtime=23124

series e:vgcw-qfjm d:2017-04-17T00:00:00.000Z t:applicants="GREEN & GOLDEN LLC                                  SCHWARTZ, KATHERINE                                 SCHWARTZ, JAMES" t:mailcity=SEATTLE t:zipcode=984091000 t:mailzip=981164219 t:state=WA t:designatedsignee="TACOMA POLICE DEPARTMENT" t:roomnumber="STE C" t:contact="KATHERINE SCHWARTZ" t:city=TACOMA t:ubi=6040694540010002 t:citycode=17 t:streetaddress="7457 S MADISON ST" t:countyname=PIERCE t:tradename="GREEN & GOLDEN" t:dayphone=2067905025 t:mailstate=WA t:privdesc01="MARIJUANA PROCESSOR" t:l_a_type=ASSUMPTION t:countycode=27 t:cityname=TACOMA t:license=415710 m:systemdate=20170408 m:applicationdate=20170223 m:systemtime=51801

series e:vgcw-qfjm d:2017-04-17T00:00:00.000Z t:applicants="CHIPOTLE MEXICAN GRILL, INC.                        ELLIS, MATTHEW  STEVEN                              HARTUNG, JOHN  ROBERT" t:mailcity=DENVER t:zipcode=981254426 t:mailzip=802021729 t:state=WA t:licenseename="ELLIS, MATTHEW  STEVEN" t:designatedsignee="SEATTLE CITY ATTORNEY'S OFFICE" t:contact="JAMES EDWARDS" t:city=SEATTLE t:ubi=6022519720010038 t:citycode=26 t:streetaddress="12725 LAKE CITY WAY NE" t:countyname=KING t:tradename="CHIPOTLE MEXICAN GRILL" t:dayphone=2064071585 t:mailstate=CO t:privdesc01="SNACK BAR" t:l_a_type="NEW APPLICATION" t:countycode=17 t:cityname=SEATTLE t:license=355409 m:systemdate=20170413 m:applicationdate=20170411 m:systemtime=23123
```

## Meta Commands

```ls
metric m:applicationdate p:integer l:ApplicationDate t:dataTypeName=number

metric m:systemdate p:integer l:SystemDate t:dataTypeName=number

metric m:systemtime p:integer l:SystemTime t:dataTypeName=number

entity e:vgcw-qfjm l:"LCB Local Authority Letters" t:url=https://data.wa.gov/api/views/vgcw-qfjm

property e:vgcw-qfjm t:meta.view v:id=vgcw-qfjm v:category="Public Safety" v:averageRating=0 v:name="LCB Local Authority Letters"

property e:vgcw-qfjm t:meta.view.owner v:id=v3pq-y2y4 v:screenName="Cameron McGee" v:displayName="Cameron McGee"

property e:vgcw-qfjm t:meta.view.tableauthor v:id=v3pq-y2y4 v:screenName="Cameron McGee" v:roleName=publisher v:displayName="Cameron McGee"
```

## Top Records

```ls
| license | ubi              | designatedsignee               | applicationdate | countycode | countyname | citycode | cityname        | corrected_amended | dayphone   | contact            | l_a_type                   | licenseename                            | tradename                       | streetaddress            | roomnumber | city          | state | zipcode   | mailaddress               | mailroom    | mailcity  | mailstate | mailzip   | privdesc01                          | privdesc02                  | privdesc03 | privdesc04 | privdesc05 | privdesc06 | privdesc07 | privdesc08 | applicants                                                                      | la_posted_date | la_posted_time | systemdate | systemtime | 
| ======= | ================ | ============================== | =============== | ========== | ========== | ======== | =============== | ================= | ========== | ================== | ========================== | ======================================= | =============================== | ======================== | ========== | ============= | ===== | ========= | ========================= | =========== | ========= | ========= | ========= | =================================== | =========================== | ========== | ========== | ========== | ========== | ========== | ========== | =============================================================================== | ============== | ============== | ========== | ========== | 
| 088403  | 6040945450010001 | LT. JIM DUFFY                  | 20170405        | 31         | SNOHOMISH  | 5        | EVERETT         |                   | 8134512668 | ARNUT PAOTHONG     | ASSUMPTION                 | MEN ZONE L.L.C.                         | SANAE THAI CUISINE              | 1707 HEWITT AVE          |            | EVERETT       | WA    | 982013520 | 1707 HEWITT AVE           |             | EVERETT   | WA        | 982013520 | BEER/WINE REST - BEER/WINE          |                             |            |            |            |            |            |            | EL BARAK LLC PAOTHONG, ARNUT SUKTINTHAI, PIMJAI                                 | 20170417       | 16494505       | 20170411   | 23124      | 
| 415710  | 6040694540010002 | TACOMA POLICE DEPARTMENT       | 20170223        | 27         | PIERCE     | 17       | TACOMA          |                   | 2067905025 | KATHERINE SCHWARTZ | ASSUMPTION                 |                                         | GREEN & GOLDEN                  | 7457 S MADISON ST        | STE C      | TACOMA        | WA    | 984091000 | 4434 41ST AVE SW          |             | SEATTLE   | WA        | 981164219 | MARIJUANA PROCESSOR                 |                             |            |            |            |            |            |            | GREEN & GOLDEN LLC SCHWARTZ, KATHERINE SCHWARTZ, JAMES                          | 20170417       | 15032821       | 20170408   | 51801      | 
| 355409  | 6022519720010038 | SEATTLE CITY ATTORNEY'S OFFICE | 20170411        | 17         | KING       | 26       | SEATTLE         |                   | 2064071585 | JAMES EDWARDS      | NEW APPLICATION            | ELLIS, MATTHEW STEVEN                   | CHIPOTLE MEXICAN GRILL          | 12725 LAKE CITY WAY NE   |            | SEATTLE       | WA    | 981254426 | 1401 WYNKOOP ST STE 500   |             | DENVER    | CO        | 802021729 | SNACK BAR                           |                             |            |            |            |            |            |            | CHIPOTLE MEXICAN GRILL, INC. ELLIS, MATTHEW STEVEN HARTUNG, JOHN ROBERT         | 20170417       | 10185839       | 20170413   | 23123      | 
| 417169  | 6033582700010001 | MAYOR OF SPOKANE               | 20131224        | 32         | SPOKANE    | 10       | SPOKANE (CITY)  |                   | 2063510236 | NELS BORSHCOWA     | NEW APPLICATION            | BORSCHOWA, NELS ALEXANDER               | SUGARLEAF                       | 220 E JACKSON AVE        |            | SPOKANE       | WA    | 992072153 | 14751 NORTH KELSEY ST     | STE 105 200 | MONROE    | WA        | 982720000 | MARIJUANA PRODUCER TIER 3           | MARIJUANA PROCESSOR         |            |            |            |            |            |            | BORSCHOWA, NELS ALEXANDER JENNINGS, NICHOLAS STANLEY RO                         | 20170417       | 10512700       | 20160318   | 103803     | 
| 405648  | 6035354250010002 | MAYOR OF GRANITE FALLS         | 20160727        | 31         | SNOHOMISH  | 7        | GRANITE FALLS   |                   | 4257871928 | STEVEN KIM         | APP. IN LIEU OF CUR. PRIV. | CASCADIA INTERNATIONAL DISTRIBUTION LLC | GO MART                         | 503 W STANLEY ST         |            | GRANITE FALLS | WA    | 982528749 | 15332 HWY 99 STE 11       |             | LYNNWOOD  | WA        | 980872390 | BEER/WINE SPECIALTY SHOP            |                             |            |            |            |            |            |            | YUBANG LLC CHO, YOUNG OH                                                        | 20170417       | 11382909       | 20170417   | 113829     | 
| 423461  | 6031874620010002 | LT. JIM DUFFY                  | 20161122        | 31         | SNOHOMISH  | 5        | EVERETT         |                   | 4252129704 | JUAN ROCHA-ACEDO   | NEW APPLICATION            | ROCHA-ACEDO, JUAN GABRIEL               | EL SINALOENSE                   | 9610 EVERGREEN WAY STE A |            | EVERETT       | WA    | 982047102 | 9610 EVERGREEN WAY STE A  |             | EVERETT   | WA        | 982047102 | GROCERY STORE - BEER/WINE           |                             |            |            |            |            |            |            | ROCHA-ACEDO, JUAN GABRIEL ROCHA-ACEDO, JUAN GABRIEL                             | 20170417       | 15433988       | 20170407   | 23125      | 
| 356063  | 6041040310010001 | MAYOR OF CAMAS                 | 20170329        | 6          | CLARK      | 2        | CAMAS           |                   | 2062346372 | TISH LESTER        | NEW APPLICATION            | LESTER, CRAIG DAVID                     | THE PICK-ME-UP MODERN TAKE-AWAY | 3510 NE EVERETT ST       |            | CAMAS         | WA    | 986079196 | 3510 NE EVERETT ST        |             | CAMAS     | WA        | 986079196 | DIRECT SHIPMENT RECEIVER-IN WA ONLY | BEER/WINE REST - BEER       |            |            |            |            |            |            | CAMAS PMU LLC LESTER, LETITIA LESTER, CRAIG DAVID                               | 20170417       | 11483408       | 20170401   | 51759      | 
| 086688  | 6035382610010001 | SEATTLE CITY ATTORNEY'S OFFICE | 20170405        | 17         | KING       | 26       | SEATTLE         |                   | 9288532666 | ABE PRALLE         | NEW APPLICATION            | SPAULDING, AUMAWAN                      | KATI VEGAN THAI                 | 1190 THOMAS ST           |            | SEATTLE       | WA    | 981095331 | 1190 THOMAS ST            |             | SEATTLE   | WA        | 981095331 | DIRECT SHIPMENT RECEIVER-IN WA ONLY | SPIRITS/BR/WN REST LOUNGE + |            |            |            |            |            |            | KATI VEGAN THAI LLC PRALLE, ABRAHAM SPAULDING, AUMAWAN SPAULDING, ANDREW HOWARD | 20170417       | 16220611       | 20170408   | 51801      | 
| 416965  | 6035126850010002 | BENTON COUNTY COMMISSIONERS    | 20170407        | 3          | BENTON     | 0        | UNINCORP. AREAS |                   | 5094406214 |                    | CHANGE OF LOCATION         |                                         | SAPPHIRE MEADOWS                | 15505 N WEBBER CANYON RD | STE F      | BENTON CITY   | WA    | 993206508 | 2205 W CANAL DR           |             | KENNEWICK | WA        | 993362569 | MARIJUANA PRODUCER TIER 2           | MARIJUANA PROCESSOR         |            |            |            |            |            |            | SAPPHIRE MEADOWS, LLC MCGUFFIN, MICHAEL WILLIAM                                 | 20170417       | 12355938       | 20170411   | 94144      | 
| 412629  | 6033505470010001 | CITY OF SEATTLE                | 20131119        | 17         | KING       | 26       | SEATTLE         |                   | 4256775203 |                    | NEW APPLICATION            | MAC 1 LLC                               | MAC1                            | 2700 4TH AVE S           | STE E-3    | SEATTLE       | WA    | 981341942 | 1813 130TH AVE NE STE 112 |             | BELLEVUE  | WA        | 980052226 | MARIJUANA PROCESSOR                 |                             |            |            |            |            |            |            | MAC 1 LLC SHELTON, DAMON SHELTON, JENNIFER                                      | 20170417       | 11384323       | 20131123   | 44845      | 
```