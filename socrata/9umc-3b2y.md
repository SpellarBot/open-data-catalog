# Capital Grants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-grants-29a80) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9umc-3b2y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9umc-3b2y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9umc-3b2y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9umc-3b2y |
| Name | Capital Grants |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | capital grants, mbp, manhattan borough president (mbp) |
| Created | 2014-03-06T17:30:41Z |
| Publication Date | 2014-03-06T17:33:08Z |

## Description

This list contains information on capital grants

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | agency               | Agency               | text      | text        |
| Yes      | series tag     | organization_name    | Organization Name    | text      | text        |
| No       |                | organization_address | Organization Address | text      | text        |
| Yes      | series tag     | city                 | City                 | text      | text        |
| Yes      | series tag     | state                | State                | text      | text        |
| Yes      | series tag     | zip                  | Zip                  | text      | text        |
| Yes      | series tag     | building_number      | Building Number      | text      | text        |
| Yes      | series tag     | school_number        | School Number        | text      | text        |
| Yes      | series tag     | community_board      | Community Board      | text      | text        |
| Yes      | series tag     | council_district     | Council District     | text      | text        |
| Yes      | series tag     | project_title        | Project Title        | text      | text        |
| Yes      | series tag     | project_description  | Project Description  | text      | text        |
| Yes      | series tag     | amnt_requested       | Amnt Requested       | text      | text        |
| Yes      | numeric metric | funded_amount        | Funded Amount        | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = organization_address
```

## Data Commands

```ls
series e:9umc-3b2y d:2014-03-06T09:30:44.000Z t:zip=10010 t:project_title="Subotnick Center Display System Project" t:state=NY t:agency=CUNY t:council_district=CD02 t:community_board=CB6 t:amnt_requested="* 140,000.00" t:organization_name=BaruchCollege/CUNY t:project_description="Upgrade the Subotnick Center/Trading Floor Simulator LED Ticker, LED wall boards and CRT televisions with new, modern, energy-efficient equipment that supports the College's pedagogical needs." t:city="New York" m:funded_amount=0

series e:9umc-3b2y d:2014-03-06T09:30:44.000Z t:zip=10010 t:project_title="Baruch College Welcome Center Project" t:state=NY t:agency=CUNY t:council_district=CD02 t:community_board=CB6 t:amnt_requested="* 275,000.00" t:organization_name=BaruchCollege/CUNY t:project_description="Renovation of Welcome Center space, additional space for for the various activities, add offices and event space with new furniture, lighting and signage." t:city="New York" m:funded_amount=275000

series e:9umc-3b2y d:2014-03-06T09:30:44.000Z t:zip=10007 t:project_title="Instructional Spaces Upgrade, HVAC Upgrades to IT Closets, Replacement of Rooftop AC Unit" t:state=NY t:agency=CUNY t:council_district=CD01 t:community_board=CB1 t:amnt_requested="$1, 075, 000.00" t:organization_name="Borough of Manhattan Community College" t:project_description="(1)Reconfiguration of space to create additional classrooms and non-science instructional lab.  (2)Installation of air-conditioning units for the college's 17 IT closets on each floor of the North and South Towers. (3) Installation of new 350-ton rooftop air-conditioning unit on the South  tower penthouse, current unit has not functioned for years." t:city="New York" m:funded_amount=750000
```

## Meta Commands

```ls
metric m:funded_amount p:integer l:"Funded Amount" t:dataTypeName=money

entity e:9umc-3b2y l:"Capital Grants" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/9umc-3b2y

property e:9umc-3b2y t:meta.view v:id=9umc-3b2y v:category="City Government" v:averageRating=0 v:name="Capital Grants" v:attribution="Manhattan Borough President (MBP)"

property e:9umc-3b2y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9umc-3b2y t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | organization_name                      | organization_address  | city     | state | zip   | building_number | school_number | community_board | council_district | project_title                                                                             | project_description                                                                                                                                                                                                                                                                                                                                          | amnt_requested  | funded_amount | 
| =========== | ====== | ====================================== | ===================== | ======== | ===== | ===== | =============== | ============= | =============== | ================ | ========================================================================================= | ============================================================================================================================================================================================================================================================================================================================================================ | =============== | ============= | 
| 1394098244  | CUNY   | BaruchCollege/CUNY                     | 1 Bernard Baruch Way  | New York | NY    | 10010 |                 |               | CB6             | CD02             | Subotnick Center Display System Project                                                   | Upgrade the Subotnick Center/Trading Floor Simulator LED Ticker, LED wall boards and CRT televisions with new, modern, energy-efficient equipment that supports the College's pedagogical needs.                                                                                                                                                             | * 140,000.00    | 0             | 
| 1394098244  | CUNY   | BaruchCollege/CUNY                     | 1 Bernard Baruch Way  | New York | NY    | 10010 |                 |               | CB6             | CD02             | Baruch College Welcome Center Project                                                     | Renovation of Welcome Center space, additional space for for the various activities, add offices and event space with new furniture, lighting and signage.                                                                                                                                                                                                   | * 275,000.00    | 275000        | 
| 1394098244  | CUNY   | Borough of Manhattan Community College | 199 Chambers Street   | New York | NY    | 10007 |                 |               | CB1             | CD01             | Instructional Spaces Upgrade, HVAC Upgrades to IT Closets, Replacement of Rooftop AC Unit | (1)Reconfiguration of space to create additional classrooms and non-science instructional lab. (2)Installation of air-conditioning units for the college's 17 IT closets on each floor of the North and South Towers. (3) Installation of new 350-ton rooftop air-conditioning unit on the South tower penthouse, current unit has not functioned for years. | $1, 075, 000.00 | 750000        | 
| 1394098244  | CUNY   | CUNY Graduate Center                   | 365 5th Avenue        | New York | NY    | 10016 |                 |               | CB5             | CD03             | Audio Visual Technology Upgrade for Large-group Venues.                                   | Purchase and Installation of audio-visual equipment (computer control systems and software, (20 overhead video projection systems (including hidden screens and ceiling mounted projectors), ans ouund equipment (including amplifiers, pre-amplifiers, mixers,                                                                                              | * 200,000.00    | 200000        | 
| 1394098244  | CUNY   | Hunter College                         | 695 Park Avenue       | New York | NY    | 10065 |                 |               | CB8             | CD04             | Library and Learning Center Upgrades                                                      | Phase II of Main Campus Library Renovation - Construction/transformation of 6th and 7th floors of library into a technology-enhanced student success center, as well as; areas for studying and gathering.                                                                                                                                                   | * 1,500,000.00  | 0             | 
| 1394098244  | CUNY   | John Jay College of Criminal Justice   | 899 - 10th Avenue     | New York | NY    | 10019 |                 |               | CB4             | CD06             | Green It Upgrades Phase II                                                                | Implement more green technologiess in Student Computer Lab such as storage space, 25 servers, VDI Software, and smart classroom technology equipment and replacements.                                                                                                                                                                                       | * 900,000.00    | 300000        | 
| 1394098244  | CUNY   | The City College of New York           | 160 Convent Avenue    | New York | NY    | 10031 |                 |               | CB9             | CD07             | Network Infrastructure Modernization; Max Bond Center; Wingate Pool Restoration           | (1) Redesign the campus network to optimize computing. (2) Build/Create a home for the Max Bond Centerthat facilitates collaboration and exchange both within and outside The City College of New York. (3) Renovate/restore the Wingate Pool mechanical infras                                                                                              | * 4,000,000.00  | 0             | 
| 1394098244  | DCA    | ABC No Rio                             | 156 Rivington Street  | New York | NY    | 10002 |                 |               | CB3             | CD01             | Multi Use Arts Center Project                                                             | Demolition of existing building to double the size of gallery and performance space, install insulation and soundproofing, install an elevator and make building ADA compliant, install new energy-and-water-efficient building-wide systems.                                                                                                                | * 250,000.00    | 125000        | 
| 1394098244  | DCA    | American Museum of Natural History     | 200 Central Park West | New York | NY    | 10024 |                 |               | CB7             | CD06             | Historic Skylights and Dormers Project                                                    | Replacement and reconstruction of roof dormers and skylights on historic red slate roofs along Columbus Avenue, 77th Street and / or Central Park West that are past their useful life and are actively leaking.                                                                                                                                             | * 750,000.00    | 500000        | 
| 1394098244  | DCA    | Amigos Del Museo Del Barrio, Inc.      | 1230 Fifth Avenue     | New York | NY    | 10029 |                 |               | CB11            | CD08             | Gallery Environmental Stabilization Project                                               | Cleaning and/or replacement of their expansive duct system; change out of the sump pump and heater incorporating the cooling tower into the automation system; installation of an additional set of double fire proof glass doors at their Caf? entrance; insta                                                                                              | * 250,000.00    | 250000        | 
```