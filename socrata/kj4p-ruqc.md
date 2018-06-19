# Buildings Subject to HPD Jurisdiction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/buildings-subject-to-hpd-jurisdiction-1a67c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kj4p-ruqc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kj4p-ruqc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kj4p-ruqc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kj4p-ruqc |
| Name | Buildings Subject to HPD Jurisdiction |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | buildings, department of housing preservation and development, hpd |
| Created | 2013-11-18T18:50:33Z |
| Publication Date | 2017-04-02T19:47:21Z |

## Description

Pursuant to New York City?s Housing Maintenance Code, the Department of Housing 
Preservation and Development (HPD) collects information on multiple dwellings in New York 
City, and other buildings that fall under its jurisdiction. HPD?s Buildings Open Data covers all 
buildings which meet any of the following criteria: 
 
a. HPD has required the owner to register the building under the Housing Maintenance 
Code (HMC) 
b. HPD has initiated a litigation action under the HMC 
c. HPD has received a complaint for the building 
d. HPD has initiated a work order for the purposes of emergency repair, demolition, or 
the Alternative Enforcement Program (AEP) for the building 
e. HPD has added the property to the AEP program

Buildings are identified by a BuildingID.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | buildingid         | BuildingID         | text      | number      |
| Yes      | series tag     | boroid             | BoroID             | text      | number      |
| Yes      | series tag     | boro               | Boro               | text      | text        |
| Yes      | series tag     | housenumber        | HouseNumber        | text      | text        |
| Yes      | series tag     | lowhousenumber     | LowHouseNumber     | text      | text        |
| Yes      | series tag     | highhousenumber    | HighHouseNumber    | text      | text        |
| Yes      | series tag     | streetname         | StreetName         | text      | text        |
| Yes      | series tag     | zip                | Zip                | text      | text        |
| Yes      | series tag     | block              | Block              | text      | number      |
| Yes      | series tag     | lot                | Lot                | text      | number      |
| Yes      | numeric metric | bin                | BIN                | number    | number      |
| Yes      | numeric metric | communityboard     | CommunityBoard     | number    | number      |
| Yes      | numeric metric | censustract        | CensusTract        | number    | text        |
| Yes      | series tag     | managementprogram  | ManagementProgram  | text      | text        |
| Yes      | series tag     | dobbuildingclassid | DoBBuildingClassID | text      | number      |
| Yes      | series tag     | dobbuildingclass   | DoBBuildingClass   | text      | text        |
| Yes      | numeric metric | legalstories       | LegalStories       | number    | number      |
| Yes      | numeric metric | legalclassa        | LegalClassA        | number    | number      |
| Yes      | numeric metric | legalclassb        | LegalClassB        | number    | number      |
| Yes      | series tag     | registrationid     | RegistrationID     | text      | number      |
| Yes      | series tag     | lifecycle          | LifeCycle          | text      | text        |
| Yes      | series tag     | recordstatusid     | RecordStatusID     | text      | number      |
| Yes      | series tag     | recordstatus       | RecordStatus       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kj4p-ruqc d:2017-04-02T19:43:49.000Z t:zip=10003 t:boro=MANHATTAN t:buildingid=328 t:recordstatus=Active t:block=452 t:housenumber=173 t:recordstatusid=1 t:dobbuildingclassid=1 t:managementprogram=PVT t:boroid=1 t:lifecycle=Building t:lowhousenumber=173 t:lot=32 t:registrationid=132391 t:dobbuildingclass="OLD  LAW TENEMENT" t:highhousenumber=173 t:streetname="1 AVENUE" m:legalclassb=0 m:legalclassa=8 m:communityboard=3 m:bin=1006451 m:legalstories=5 m:censustract=4000

series e:kj4p-ruqc d:2017-04-02T19:43:49.000Z t:zip=10128 t:boro=MANHATTAN t:buildingid=329 t:recordstatus=Active t:block=1552 t:housenumber=1733 t:recordstatusid=1 t:dobbuildingclassid=1 t:managementprogram=PVT t:boroid=1 t:lifecycle=Building t:lowhousenumber=1733 t:lot=29 t:registrationid=101342 t:dobbuildingclass="OLD  LAW TENEMENT" t:highhousenumber=1735 t:streetname="1 AVENUE" m:legalclassb=0 m:legalclassa=41 m:communityboard=8 m:bin=1050120 m:legalstories=6 m:censustract=15400

series e:kj4p-ruqc d:2017-04-02T19:43:49.000Z t:zip=10009 t:boro=MANHATTAN t:buildingid=330 t:recordstatus=Active t:block=438 t:housenumber=174 t:recordstatusid=1 t:dobbuildingclassid=1 t:managementprogram=PVT t:boroid=1 t:lifecycle=Building t:lowhousenumber=174 t:lot=6 t:registrationid=128480 t:dobbuildingclass="OLD  LAW TENEMENT" t:highhousenumber=174 t:streetname="1 AVENUE" m:legalclassb=0 m:legalclassa=5 m:communityboard=3 m:bin=1082526 m:legalstories=4 m:censustract=3400
```

## Meta Commands

```ls
metric m:bin p:integer l:BIN d:"DCP Building Identification Number for building" t:dataTypeName=number

metric m:communityboard p:integer l:CommunityBoard d:"Unique number identifying a Community District/Board, which is a political geographical area within a borough of the City of NY" t:dataTypeName=number

metric m:censustract p:integer l:CensusTract d:"Geographic area defined by the U.S. Census Bureau for the various decennial censuses" t:dataTypeName=number

metric m:legalstories p:integer l:LegalStories d:"Number of legal stories in building" t:dataTypeName=number

metric m:legalclassa p:integer l:LegalClassA d:"The number of apartments in a multiple dwelling" t:dataTypeName=number

metric m:legalclassb p:integer l:LegalClassB d:"The number of rooms in a multiple dwelling without individual baths and kitchens" t:dataTypeName=number

entity e:kj4p-ruqc l:"Buildings Subject to HPD Jurisdiction" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/kj4p-ruqc

property e:kj4p-ruqc t:meta.view v:id=kj4p-ruqc v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Buildings Subject to HPD Jurisdiction" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:kj4p-ruqc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kj4p-ruqc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | buildingid | boroid | boro      | housenumber | lowhousenumber | highhousenumber | streetname | zip   | block | lot | bin     | communityboard | censustract | managementprogram | dobbuildingclassid | dobbuildingclass | legalstories | legalclassa | legalclassb | registrationid | lifecycle | recordstatusid | recordstatus | 
| =========== | ========== | ====== | ========= | =========== | ============== | =============== | ========== | ===== | ===== | === | ======= | ============== | =========== | ================= | ================== | ================ | ============ | =========== | =========== | ============== | ========= | ============== | ============ | 
| 1491162229  | 328        | 1      | MANHATTAN | 173         | 173            | 173             | 1 AVENUE   | 10003 | 452   | 32  | 1006451 | 3              | 4000        | PVT               | 1                  | OLD LAW TENEMENT | 5            | 8           | 0           | 132391         | Building  | 1              | Active       | 
| 1491162229  | 329        | 1      | MANHATTAN | 1733        | 1733           | 1735            | 1 AVENUE   | 10128 | 1552  | 29  | 1050120 | 8              | 15400       | PVT               | 1                  | OLD LAW TENEMENT | 6            | 41          | 0           | 101342         | Building  | 1              | Active       | 
| 1491162229  | 330        | 1      | MANHATTAN | 174         | 174            | 174             | 1 AVENUE   | 10009 | 438   | 6   | 1082526 | 3              | 3400        | PVT               | 1                  | OLD LAW TENEMENT | 4            | 5           | 0           | 128480         | Building  | 1              | Active       | 
| 1491162229  | 331        | 1      | MANHATTAN | 1740        | 1740           | 1740            | 1 AVENUE   | 10128 | 1570  | 1   | 1050719 | 8              | 15200       | PVT               | 1                  | OLD LAW TENEMENT | 5            | 13          | 0           | 111736         | Building  | 1              | Active       | 
| 1491162229  | 332        | 1      | MANHATTAN | 1741        | 1741           | 1741            | 1 AVENUE   | 10128 | 1553  | 23  | 1050184 | 8              | 15400       | PVT               | 1                  | OLD LAW TENEMENT | 5            | 16          | 0           | 104532         | Building  | 1              | Active       | 
| 1491162229  | 333        | 1      | MANHATTAN | 1742        | 1742           | 1742            | 1 AVENUE   | 10128 | 1570  | 2   | 1050720 | 8              | 15200       | PVT               | 1                  | OLD LAW TENEMENT | 6            | 22          | 0           | 122194         | Building  | 1              | Active       | 
| 1491162229  | 334        | 1      | MANHATTAN | 1743        | 1743           | 1743            | 1 AVENUE   | 10128 | 1553  | 24  | 1050185 | 8              | 15400       | PVT               | 1                  | OLD LAW TENEMENT | 11           | 21          | 0           | 121461         | Building  | 1              | Active       | 
| 1491162229  | 335        | 1      | MANHATTAN | 1744        | 1744           | 1744            | 1 AVENUE   | 10128 | 1570  | 3   | 1050721 | 8              | 15200       | PVT               | 1                  | OLD LAW TENEMENT | 5            | 10          | 0           | 112794         | Building  | 1              | Active       | 
| 1491162229  | 337        | 1      | MANHATTAN | 1746        | 1746           | 1746            | 1 AVENUE   | 10128 | 1570  | 4   | 1050722 | 8              | 15200       | PVT               | 1                  | OLD LAW TENEMENT | 5            | 10          | 0           | 106877         | Building  | 1              | Active       | 
| 1491162229  | 338        | 1      | MANHATTAN | 1748        | 1748           | 1748            | 1 AVENUE   | 10128 | 1570  | 50  | 1050745 | 8              | 15200       | PVT               | 1                  | OLD LAW TENEMENT | 5            | 17          | 0           | 107002         | Building  | 1              | Active       | 
```