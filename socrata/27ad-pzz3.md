# BOE Capital Improvement Projects Points [lahub_rest_services_Public_Way_Reservations_MapServer_9]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boe-capital-improvement-projects-points-lahub-rest-services-public-way-reservations-mapser) |
| Metadata | [Link](https://data.lacity.org/api/views/27ad-pzz3) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/27ad-pzz3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/27ad-pzz3/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 27ad-pzz3 |
| Name | BOE Capital Improvement Projects Points [lahub_rest_services_Public_Way_Reservations_MapServer_9] |
| Created | 2016-04-13T20:21:01Z |
| Publication Date | 2016-04-13T20:26:47Z |

## Description

https://maps.lacity.org/lahub/rest/services/Public_Way_Reservations/MapServer/9

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | geotype                     | Geotype                     | text      | text        |
| Yes      | series tag     | geocodingid                 | GeocodingID                 | text      | number      |
| Yes      | time           | geocodedate                 | GeocodeDate                 | date      | date        |
| Yes      | series tag     | projectid                   | PROJECTID                   | text      | number      |
| Yes      | numeric metric | navla_cip                   | NavLA_CIP                   | number    | number      |
| Yes      | numeric metric | navla_archive               | NavLA_Archive               | number    | number      |
| Yes      | series tag     | programid                   | ProgramID                   | text      | number      |
| Yes      | series tag     | programname                 | ProgramName                 | text      | text        |
| Yes      | series tag     | projecttitle                | ProjectTitle                | text      | text        |
| Yes      | series tag     | wo_status                   | WO_Status                   | text      | text        |
| Yes      | series tag     | pm_name                     | PM_Name                     | text      | text        |
| Yes      | series tag     | pm_phone                    | PM_Phone                    | text      | text        |
| Yes      | series tag     | pm_email                    | PM_EMail                    | text      | text        |
| Yes      | numeric metric | projectactive               | ProjectActive               | number    | number      |
| Yes      | numeric metric | projectvalid                | ProjectValid                | number    | number      |
| No       |                | consstartdate               | ConsStartDate               | date      | date        |
| No       |                | consenddate                 | ConsEndDate                 | date      | date        |
| No       |                | scheduleddesignstart        | ScheduledDesignStart        | date      | date        |
| Yes      | series tag     | lastvisited                 | LastVisited                 | text      | text        |
| Yes      | series tag     | primaryworkorder            | PrimaryWorkOrder            | text      | text        |
| Yes      | series tag     | councildistrict             | CouncilDistrict             | text      | text        |
| Yes      | numeric metric | constructioncost            | ConstructionCost            | number    | number      |
| Yes      | series tag     | projectnumber               | ProjectNumber               | text      | text        |
| Yes      | series tag     | currentphasedescription     | CurrentPhaseDescription     | text      | text        |
| Yes      | numeric metric | currentphasepercentcomplete | CurrentPhasePercentComplete | number    | number      |
| Yes      | series tag     | activephasename             | ActivePhaseName             | text      | text        |
| Yes      | numeric metric | activephasepercent          | ActivePhasePercent          | number    | number      |
| Yes      | series tag     | lastvisitedby               | LastVisitedBy               | text      | text        |
| Yes      | numeric metric | constperccomp               | ConstPercComp               | number    | number      |
| Yes      | series tag     | tooltip                     | TOOLTIP                     | text      | text        |
| Yes      | series tag     | nla_url                     | NLA_URL                     | text      | text        |
| No       |                | startdate                   | StartDate                   | date      | date        |
| No       |                | enddate                     | EndDate                     | date      | date        |
| No       |                | id                          | ID                          | text      | number      |
```

## Time Field

```ls
Value = geocodedate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = consstartdate,consenddate,scheduleddesignstart,startdate,enddate,id
```

## Data Commands

```ls
series e:27ad-pzz3 d:2003-12-22T00:00:00.000Z t:geotype=pt t:lastvisitedby="Sean Phan" t:geocodingid=276 t:councildistrict="14 - Jos? Huizar" t:programid=44 t:pm_email=sean.phan@lacity.org t:currentphasedescription=Design t:primaryworkorder=E170192A t:pm_name="Sean Phan" t:projectnumber=K062 t:projecttitle="Boyle Heights Sports Center" t:projectid=294 t:programname="Municipal Facilities R and P" t:lastvisited=04/19/2017 t:nla_url="navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=294" t:activephasename=Design t:tooltip="Project: Boyle Heights Sports Center\nProgram: Municipal Facilities R and P\nProject Phase: Design\nProject Number: K062\nWork Order: E170192A\nStartDate: 1/28/2019\nEnd Date: 7/28/2020" t:pm_phone="(213) 847-4706" t:wo_status=Active m:projectvalid=1 m:navla_archive=0 m:projectactive=1 m:navla_cip=1 m:activephasepercent=9 m:constructioncost=7100000 m:currentphasepercentcomplete=9 m:constperccomp=0

series e:27ad-pzz3 d:2003-12-31T00:00:00.000Z t:geotype=pt t:lastvisitedby="Jaime Contreras" t:geocodingid=476 t:councildistrict="2 - Paul Krekorian" t:programid=44 t:pm_email=jaime.contreras@lacity.org t:currentphasedescription=Construction t:primaryworkorder=E170406F t:pm_name="Jaime Contreras" t:projectnumber=K129 t:projecttitle="Los Angeles Riverfront Park Phase II" t:projectid=2605 t:programname="Municipal Facilities R and P" t:lastvisited=04/10/2017 t:nla_url="navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2605" t:activephasename=Construction t:tooltip="Project: Los Angeles Riverfront Park Phase II\nProgram: Municipal Facilities R and P\nProject Phase: Construction\nProject Number: K129\nWork Order: E170406F\nStartDate: 8/16/2013\nEnd Date: 6/1/2017" t:pm_phone="(213) 847-4710" t:wo_status=Active m:projectvalid=1 m:navla_archive=0 m:projectactive=1 m:navla_cip=1 m:activephasepercent=96 m:constructioncost=6000000 m:currentphasepercentcomplete=96 m:constperccomp=96

series e:27ad-pzz3 d:2004-01-07T00:00:00.000Z t:geotype=pt t:lastvisitedby="Mariet Ohanian" t:geocodingid=704 t:councildistrict="12 - Mitchell Englander" t:programid=44 t:pm_email=Rebecca.Abano@lacity.org t:currentphasedescription=Construction t:primaryworkorder=E170331A t:pm_name="Rebecca Abano" t:projectnumber=K134 t:projecttitle="Chatsworth Park South - Park Improvements" t:projectid=2642 t:programname="Municipal Facilities R and P" t:lastvisited=04/03/2017 t:nla_url="navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2642" t:activephasename=Construction t:tooltip="Project: Chatsworth Park South - Park Improvements\nProgram: Municipal Facilities R and P\nProject Phase: Construction\nProject Number: K134\nWork Order: E170331A\nStartDate: 8/14/2015\nEnd Date: 6/30/2017" t:pm_phone="(213) 847-4711" t:wo_status=Active m:projectvalid=1 m:navla_archive=0 m:projectactive=1 m:navla_cip=1 m:activephasepercent=81 m:constructioncost=6295000 m:currentphasepercentcomplete=81 m:constperccomp=81
```

## Meta Commands

```ls
metric m:navla_cip p:integer l:NavLA_CIP d:NavLA_CIP t:dataTypeName=number

metric m:navla_archive p:integer l:NavLA_Archive d:NavLA_Archive t:dataTypeName=number

metric m:projectactive p:integer l:ProjectActive d:ProjectActive t:dataTypeName=number

metric m:projectvalid p:integer l:ProjectValid d:ProjectValid t:dataTypeName=number

metric m:constructioncost p:integer l:ConstructionCost d:ConstructionCost t:dataTypeName=number

metric m:currentphasepercentcomplete p:integer l:CurrentPhasePercentComplete d:CurrentPhasePercentComplete t:dataTypeName=number

metric m:activephasepercent p:integer l:ActivePhasePercent d:ActivePhasePercent t:dataTypeName=number

metric m:constperccomp p:integer l:ConstPercComp d:ConstPercComp t:dataTypeName=number

entity e:27ad-pzz3 l:"BOE Capital Improvement Projects Points [lahub_rest_services_Public_Way_Reservations_MapServer_9]" t:url=https://data.lacity.org/api/views/27ad-pzz3

property e:27ad-pzz3 t:meta.view v:id=27ad-pzz3 v:averageRating=0 v:name="BOE Capital Improvement Projects Points [lahub_rest_services_Public_Way_Reservations_MapServer_9]"

property e:27ad-pzz3 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:27ad-pzz3 t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:27ad-pzz3 t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| geotype | geocodingid | geocodedate | projectid | navla_cip | navla_archive | programid | programname                  | projecttitle                                    | wo_status | pm_name          | pm_phone       | pm_email                    | projectactive | projectvalid | consstartdate | consenddate | scheduleddesignstart | lastvisited | primaryworkorder | councildistrict                         | constructioncost | projectnumber | currentphasedescription | currentphasepercentcomplete | activephasename | activephasepercent | lastvisitedby     | constperccomp | tooltip                                                                                                                                                                                                       | nla_url                                                           | startdate  | enddate    | id  | 
| ======= | =========== | =========== | ========= | ========= | ============= | ========= | ============================ | =============================================== | ========= | ================ | ============== | =========================== | ============= | ============ | ============= | =========== | ==================== | =========== | ================ | ======================================= | ================ | ============= | ======================= | =========================== | =============== | ================== | ================= | ============= | ============================================================================================================================================================================================================= | ================================================================= | ========== | ========== | === | 
| pt      | 276         | 1072051200  | 294       | 1         | 0             | 44        | Municipal Facilities R and P | Boyle Heights Sports Center                     | Active    | Sean Phan        | (213) 847-4706 | sean.phan@lacity.org        | 1             | 1            | 1548633600    | 1595894400  | 1488412800           | 04/19/2017  | E170192A         | 14 - Jos? Huizar                        | 7100000          | K062          | Design                  | 9                           | Design          | 9                  | Sean Phan         | 0             | Project: Boyle Heights Sports Center\nProgram: Municipal Facilities R and P\nProject Phase: Design\nProject Number: K062\nWork Order: E170192A\nStartDate: 1/28/2019\nEnd Date: 7/28/2020                     | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=294  | 1548633600 | 1595894400 | 35  | 
| pt      | 476         | 1072828800  | 2605      | 1         | 0             | 44        | Municipal Facilities R and P | Los Angeles Riverfront Park Phase II            | Active    | Jaime Contreras  | (213) 847-4710 | jaime.contreras@lacity.org  | 1             | 1            | 1376611200    | 1496275200  | 1138752000           | 04/10/2017  | E170406F         | 2 - Paul Krekorian                      | 6000000          | K129          | Construction            | 96                          | Construction    | 96                 | Jaime Contreras   | 96            | Project: Los Angeles Riverfront Park Phase II\nProgram: Municipal Facilities R and P\nProject Phase: Construction\nProject Number: K129\nWork Order: E170406F\nStartDate: 8/16/2013\nEnd Date: 6/1/2017       | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2605 | 1376611200 | 1496275200 | 109 | 
| pt      | 704         | 1073433600  | 2642      | 1         | 0             | 44        | Municipal Facilities R and P | Chatsworth Park South - Park Improvements       | Active    | Rebecca Abano    | (213) 847-4711 | Rebecca.Abano@lacity.org    | 1             | 1            | 1439510400    | 1498780800  | 1391040000           | 04/03/2017  | E170331A         | 12 - Mitchell Englander                 | 6295000          | K134          | Construction            | 81                          | Construction    | 81                 | Mariet Ohanian    | 81            | Project: Chatsworth Park South - Park Improvements\nProgram: Municipal Facilities R and P\nProject Phase: Construction\nProject Number: K134\nWork Order: E170331A\nStartDate: 8/14/2015\nEnd Date: 6/30/2017 | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2642 | 1439510400 | 1498780800 | 117 | 
| pt      | 717         | 1073433600  | 2647      | 1         | 0             | 44        | Municipal Facilities R and P | Sepulveda Basin Lake Balboa (Irrigation System) | Active    | Richard Campbell | (213) 847-4715 | Richard.Campbell@lacity.org | 1             | 1            | 1527897600    | 1559433600  | 1483228800           | 04/03/2017  | E170219A         | 6 - Nury Martinez                       | 1300000          | K139          | Design                  | 18                          | Design          | 18                 | Sean Phan         | 0             | Project: Sepulveda Basin Lake Balboa (Irrigation System)\nProgram: Municipal Facilities R and P\nProject Phase: Design\nProject Number: K139\nWork Order: E170219A\nStartDate: 6/2/2018\nEnd Date: 6/2/2019   | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2647 | 1527897600 | 1559433600 | 121 | 
| pt      | 1113        | 1074038400  | 1846      | 1         | 0             | 25        | Wastewater - TPP             | HTP- Digester Gas Desulfurization Fac.Improv.   | Active    | Amy So           | 310-648-6239   | amy.so@lacity.org           | 1             | 1            | 1368835200    | 1493337600  | 1293926400           | 04/18/2017  | SZH11591         | 11 - Mike Bonin                         | 5285000          | 1027          | Construction            | 99                          | Construction    | 99                 | Amy So            | 99            | Project: HTP- Digester Gas Desulfurization Fac.Improv.\nProgram: Wastewater - TPP\nProject Phase: Construction\nProject Number: 1027\nWork Order: SZH11591\nStartDate: 5/18/2013\nEnd Date: 4/28/2017         | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=1846 | 1368835200 | 1493337600 | 144 | 
| pt      | 1114        | 1074038400  | 1846      | 1         | 0             | 25        | Wastewater - TPP             | HTP- Digester Gas Desulfurization Fac.Improv.   | Active    | Amy So           | 310-648-6239   | amy.so@lacity.org           | 1             | 1            | 1368835200    | 1493337600  | 1293926400           | 04/18/2017  | SZH11591         | 11 - Mike Bonin                         | 5285000          | 1027          | Construction            | 99                          | Construction    | 99                 | Amy So            | 99            | Project: HTP- Digester Gas Desulfurization Fac.Improv.\nProgram: Wastewater - TPP\nProject Phase: Construction\nProject Number: 1027\nWork Order: SZH11591\nStartDate: 5/18/2013\nEnd Date: 4/28/2017         | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=1846 | 1368835200 | 1493337600 | 145 | 
| pt      | 1439        | 1074124800  | 1991      | 1         | 0             | 25        | Wastewater - TPP             | HWRP- IPS Odor Control Improvements             | Active    | Sean Zahedi      | (310)648-6197  | sean.zahedi@lacity.org      | 1             | 1            | 1522627200    | 1559347200  | 1477872000           | 04/18/2017  | SZH11859         | 11 - Mike Bonin                         | 5100000          | 2253          | Design                  | 51                          | Design          | 51                 | Massoud Chadorchi | 0             | Project: HWRP- IPS Odor Control Improvements\nProgram: Wastewater - TPP\nProject Phase: Design\nProject Number: 2253\nWork Order: SZH11859\nStartDate: 4/2/2018\nEnd Date: 6/1/2019                           | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=1991 | 1522627200 | 1559347200 | 180 | 
| pt      | 15556       | 1074470400  | 2626      | 1         | 0             | 25        | Wastewater - TPP             | TIWRP- Aeration System Replacement              | Active    | Amy So           | 310-648-6239   | amy.so@lacity.org           | 1             | 1            | 1443657600    | 1498953600  | 1382486400           | 04/18/2017  | SZT11315         | 15 - Joe Buscaino                       | 12785500         | 5159          | Construction            | 88                          | Construction    | 88                 | Sinh Pham         | 88            | Project: TIWRP- Aeration System Replacement\nProgram: Wastewater - TPP\nProject Phase: Construction\nProject Number: 5159\nWork Order: SZT11315\nStartDate: 10/1/2015\nEnd Date: 7/2/2017                     | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2626 | 1443657600 | 1498953600 | 274 | 
| pt      | 15568       | 1074470400  | 2268      | 1         | 0             | 25        | Wastewater - TPP             | DCT- Backup Power                               | Active    | Sean Zahedi      | (310)648-6197  | sean.zahedi@lacity.org      | 1             | 1            | 1538352000    | 1593475200  | 1467244800           | 04/18/2017  | SZD11134         | 6 - Nury Martinez                       | 7712900          | 6145          | Design                  | 46                          | Design          | 46                 | Massoud Chadorchi | 0             | Project: DCT- Backup Power \nProgram: Wastewater - TPP\nProject Phase: Design\nProject Number: 6145\nWork Order: SZD11134\nStartDate: 10/1/2018\nEnd Date: 6/30/2020                                          | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=2268 | 1538352000 | 1593475200 | 285 | 
| pt      | 16705       | 1105660800  | 1583      | 1         | 0             | 60        | Wastewater - CSP             | Wilshire Area System Swr Rehab                  | Active    | Jin Wen          | 213-485-4594   | Jin.Wen@lacity.org          | 1             | 1            | 1517443200    | 1548892800  | 1459468800           | 04/03/2017  | SZC13027         | 4 - David Ryu, 10 - Herb J. Wesson, Jr. | 4842600          | C279          | Design                  | 76                          | Design          | 76                 | Thomas Woo        | 0             | Project: Wilshire Area System Swr Rehab\nProgram: Wastewater - CSP\nProject Phase: Design\nProject Number: C279\nWork Order: SZC13027\nStartDate: 2/1/2018\nEnd Date: 1/31/2019                               | navigatela/reports/uprs_report.cfm?nla_win=p,75,75&projectid=1583 | 1517443200 | 1548892800 | 768 | 
```