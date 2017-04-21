# ECB Citations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ecb-citations-5370d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ywty-nmtg) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ywty-nmtg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ywty-nmtg/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ywty-nmtg |
| Name | ECB Citations |
| Attribution | Baltimore City Environmental Control Board (ECB) |
| Category | City Services |
| Tags | citations, environmental |
| Created | 2012-01-13T14:48:46Z |
| Publication Date | 2016-01-22T14:55:05Z |

## Description

The Environmental Control Board is a regulatory agency with an administrative court charged with the responsibility of adjudicating civil citations in accordance with Article 1, Section 40 of the Baltimore City Code.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type | Render Type |
| ======== | ============== | ======================== | ========================== | ========= | =========== |
| Yes      | series tag     | citation                 | CitationNo                 | text      | text        |
| Yes      | series tag     | liencode                 | LienCode                   | text      | text        |
| Yes      | time           | violdate                 | ViolationDate              | date      | date        |
| No       |                | duedate                  | DueDate                    | date      | date        |
| Yes      | series tag     | agency                   | Agency                     | text      | text        |
| Yes      | numeric metric | fineamount               | FineAmount                 | money     | money       |
| Yes      | series tag     | violdesc                 | Description                | text      | text        |
| Yes      | numeric metric | balance                  | Balance                    | money     | money       |
| No       |                | lastpaiddate             | LastPaidDate               | date      | date        |
| Yes      | numeric metric | lastpaidamount           | LastPaidAmount             | money     | money       |
| No       |                | heardate                 | HearingDate                | date      | date        |
| No       |                | hearingrequesteddate     | HearingRequestReceivedDate | date      | date        |
| Yes      | series tag     | citationstatus           | CitationStatus             | text      | text        |
| Yes      | series tag     | violationarticle         | ViolationCodeArticle       | text      | text        |
| Yes      | series tag     | violationsection         | ViolationCodeSection       | text      | text        |
| Yes      | series tag     | violationlocation        | ViolationLocation          | text      | text        |
| Yes      | series tag     | block                    | Block                      | text      | text        |
| Yes      | series tag     | lot                      | Lot                        | text      | text        |
| Yes      | series tag     | officerid                | OfficerID                  | text      | text        |
| Yes      | series tag     | officerpresencerequested | OfficerPresenceRequested   | text      | text        |
| Yes      | series tag     | hearingstatus            | HearingStatus              | text      | text        |
| Yes      | series tag     | heartime                 | HearTime                   | text      | text        |
| Yes      | numeric metric | totalpaid                | TotalPaid                  | money     | money       |
| Yes      | numeric metric | totalabated              | TotalAbated                | money     | money       |
| Yes      | numeric metric | totalvoided              | TotalVoided                | money     | money       |
| Yes      | series tag     | neighborhood             | Neighborhood               | text      | text        |
| Yes      | series tag     | policedistrict           | PoliceDistrict             | text      | text        |
| Yes      | series tag     | councildistrict          | CouncilDistrict            | text      | text        |
| Yes      | series tag     | location                 | Location                   | text      | text        |
```

## Time Field

```ls
Value = violdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = duedate,lastpaiddate,heardate,hearingrequesteddate
```

## Data Commands

```ls
series e:ywty-nmtg d:2015-12-16T00:00:00.000Z t:citation=54219688 t:violdesc="FAILURE TO FILE A COMPLETED ANNUAL REGISTRATION" t:location=(39.25138751,-76.62508814) t:councildistrict=10 t:violationsection=4-5 t:neighborhood="Cherry Hill" t:block=7646 t:agency="DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT" t:violationarticle=13 t:violationlocation="2464 TERRA FIRMA ROAD" t:officerid=541 t:liencode=L t:lot=024 t:policedistrict=Southern t:citationstatus=P m:balance=0 m:fineamount=100 m:totalvoided=0 m:totalabated=0 m:lastpaidamount=300 m:totalpaid=300

series e:ywty-nmtg d:2011-02-10T00:00:00.000Z t:citation=51822278 t:violdesc="FAILURE TO PROVIDE SUFFICIENT NUMBER OF STORAGE RECEPTACLES" t:location=(39.34853211,-76.68555643) t:councildistrict=5 t:violationsection=306.4 t:neighborhood=Arlington t:block=4511H t:agency="DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT" t:violationarticle=PM t:violationlocation="5401 NELSON AVE" t:officerid=058 t:liencode=N t:lot=077 t:policedistrict=Northwestern t:citationstatus=O m:balance=150 m:fineamount=50 m:totalvoided=0 m:totalabated=0 m:lastpaidamount=0 m:totalpaid=0

series e:ywty-nmtg d:2013-10-10T00:00:00.000Z t:citation=53151098 t:violdesc="CONSTRUCTION AND MAINTENANCE OF STORAGE RECEPTACLES" t:location=(39.31845310,-76.64919694) t:councildistrict=7 t:violationsection=306.6 t:neighborhood=Parkview/Woodbrook t:block=3236 t:agency="DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT" t:violationarticle=PM t:violationlocation="3401 HOLMES AVE" t:officerid=074 t:liencode=N t:lot=036 t:policedistrict=Western t:citationstatus=O m:balance=150 m:fineamount=50 m:totalvoided=0 m:totalabated=0 m:lastpaidamount=0 m:totalpaid=0
```

## Meta Commands

```ls
metric m:fineamount p:double l:FineAmount t:dataTypeName=money

metric m:balance p:double l:Balance t:dataTypeName=money

metric m:lastpaidamount p:double l:LastPaidAmount t:dataTypeName=money

metric m:totalpaid p:double l:TotalPaid t:dataTypeName=money

metric m:totalabated p:double l:TotalAbated t:dataTypeName=money

metric m:totalvoided p:double l:TotalVoided t:dataTypeName=money

entity e:ywty-nmtg l:"ECB Citations" t:attribution="Baltimore City Environmental Control Board (ECB)" t:url=https://data.baltimorecity.gov/api/views/ywty-nmtg

property e:ywty-nmtg t:meta.view v:id=ywty-nmtg v:category="City Services" v:attributionLink=http://www.baltimorecity.gov/Government/BoardsandCommissions/EnvironmentalControlBoard.aspx v:averageRating=0 v:name="ECB Citations" v:attribution="Baltimore City Environmental Control Board (ECB)"

property e:ywty-nmtg t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ywty-nmtg t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:ywty-nmtg t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| citation | liencode | violdate   | duedate    | agency                                        | fineamount | violdesc                                                    | balance   | lastpaiddate | lastpaidamount | heardate | hearingrequesteddate | citationstatus | violationarticle | violationsection | violationlocation     | block | lot | officerid | officerpresencerequested | hearingstatus | heartime | totalpaid | totalabated | totalvoided | neighborhood        | policedistrict | councildistrict | location                   | 
| ======== | ======== | ========== | ========== | ============================================= | ========== | =========================================================== | ========= | ============ | ============== | ======== | ==================== | ============== | ================ | ================ | ===================== | ===== | === | ========= | ======================== | ============= | ======== | ========= | =========== | =========== | =================== | ============== | =============== | ========================== | 
| 54219688 | L        | 1450224000 | 1452816000 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 100.0000   | FAILURE TO FILE A COMPLETED ANNUAL REGISTRATION             | 0.0000    | 1461628800   | 300.0000       |          |                      | P              | 13               | 4-5              | 2464 TERRA FIRMA ROAD | 7646  | 024 | 541       |                          |               |          | 300.0000  | 0.0000      | 0.0000      | Cherry Hill         | Southern       | 10              | (39.25138751,-76.62508814) | 
| 51822278 | N        | 1297296000 | 1299888000 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | FAILURE TO PROVIDE SUFFICIENT NUMBER OF STORAGE RECEPTACLES | 150.0000  |              | 0.0000         |          |                      | O              | PM               | 306.4            | 5401 NELSON AVE       | 4511H | 077 | 058       |                          |               |          | 0.0000    | 0.0000      | 0.0000      | Arlington           | Northwestern   | 5               | (39.34853211,-76.68555643) | 
| 53151098 | N        | 1381363200 | 1383955200 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | CONSTRUCTION AND MAINTENANCE OF STORAGE RECEPTACLES         | 150.0000  |              | 0.0000         |          |                      | O              | PM               | 306.6            | 3401 HOLMES AVE       | 3236  | 036 | 074       |                          |               |          | 0.0000    | 0.0000      | 0.0000      | Parkview/Woodbrook  | Western        | 7               | (39.31845310,-76.64919694) | 
| 53151106 | N        | 1381363200 | 1383955200 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 60.0000    | HIGH GRASS AND WEEDS                                        | 180.0000  |              | 0.0000         |          |                      | O              | PM               | 305.2.2          | 3401 HOLMES AVE       | 3236  | 036 | 074       |                          |               |          | 0.0000    | 0.0000      | 0.0000      | Parkview/Woodbrook  | Western        | 7               | (39.31845310,-76.64919694) | 
| 53151155 | N        | 1381190400 | 1383782400 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 500.0000   | DUMPING UNDER 25 LBS OF WASTE ON PRIVATE PROPERTY           | 1500.0000 |              | 0.0000         |          |                      | O              | HE               | 7-609            | 2701 LEHMAN ST        | 2138  | 030 | 509       |                          |               |          | 0.0000    | 0.0000      | 0.0000      | Millhill            | Southwestern   | 9               | (39.27971899,-76.65898297) | 
| 54512355 | L        | 1473638400 | 1476489600 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | UNREGISTERED OR INOPERABLE VEHICLE                          | 50.0000   |              | 0.0000         |          |                      | O              | PM               | 305.5.1A         | 3221 WOODHOME AVE     | 5552  | 011 | 115       |                          |               |          | 0.0000    | 0.0000      | 0.0000      | North Harford Road  | Notheastern    | 3               | (39.36383951,-76.54257674) | 
| 54512413 | L        | 1473724800 | 1476489600 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | PLACEMENT FOR COLLECTION STORAGE ON NON-COLLECTION DAYS     | 50.0000   | 1477440000   | 50.0000        |          |                      | P              | PM               | 306.7            | 0245 S REGESTER ST    | 1753  | 127 | 095       |                          |               |          | 50.0000   | 0.0000      | 0.0000      | Upper Fells Point   | Southeastern   | 1               | (39.28817636,-76.59222137) | 
| 53839569 | L        | 1431561600 | 1434153600 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | HIGH GRASS AND WEEDS                                        | 0.0000    | 1439251200   | 150.0000       |          |                      | P              | PM               | 305.2.2          | 1713 GUILFORD AVE     | 1103  | 007 | 120       |                          |               |          | 150.0000  | 0.0000      | 0.0000      | Greenmount West     | Eastern        | 12              | (39.30931486,-76.61202014) | 
| 53844726 | L        | 1431907200 | 1434499200 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | BULK TRASH                                                  | 0.0000    | 1461888000   | 150.0000       |          |                      | P              | PM               | 306.2            | 1027 N FULTON AVE     | 0060  | 046 | 240       |                          |               |          | 150.0000  | 0.0000      | 0.0000      | Sandtown-Winchester | Western        | 9               | (39.30051039,-76.64555094) | 
| 53844734 | L        | 1431907200 | 1434499200 | DEPARTMENT OF HOUSING & COMMUNITY DEVELOPMENT | 50.0000    | CONSTRUCTION AND MAINTENANCE OF STORAGE RECEPTACLES         | 0.0000    | 1461888000   | 150.0000       |          |                      | P              | PM               | 306.6            | 1027 N FULTON AVE     | 0060  | 046 | 240       |                          |               |          | 150.0000  | 0.0000      | 0.0000      | Sandtown-Winchester | Western        | 9               | (39.30051039,-76.64555094) | 
```