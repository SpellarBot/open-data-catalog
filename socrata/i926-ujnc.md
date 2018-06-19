# Large Utility Excavation Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/large-utility-excavation-permits) |
| Metadata | [Link](https://data.sfgov.org/api/views/i926-ujnc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/i926-ujnc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/i926-ujnc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | i926-ujnc |
| Name | Large Utility Excavation Permits |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | excavation, paving, utilities, 5, year, plan, permits, utility, large |
| Created | 2015-06-09T19:32:36Z |
| Publication Date | 2015-06-12T16:58:43Z |

## Description

Large utility excavation permits (>=1000 square feet total size) issued in the last year. Compiled for Dig Once program.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | permit_number                     | Permit_Number                     | text          | text          |
| Yes      | series tag     | street_name                       | Street_Name                       | text          | text          |
| Yes      | series tag     | cross_street_1                    | Cross_Street_1                    | text          | text          |
| Yes      | series tag     | cross_street_2                    | Cross_Street_2                    | text          | text          |
| Yes      | numeric metric | cnn                               | cnn                               | number        | number        |
| Yes      | series tag     | agent                             | Agent                             | text          | text          |
| Yes      | series tag     | permit_purpose                    | Permit_Purpose                    | text          | text          |
| Yes      | series tag     | permit_reason                     | Permit_Reason                     | text          | text          |
| Yes      | series tag     | permit_status                     | Permit_Status                     | text          | text          |
| Yes      | time           | permit_start_date                 | Permit_Start_Date                 | calendar_date | calendar_date |
| No       |                | permit_end_date                   | Permit_End_Date                   | calendar_date | calendar_date |
| Yes      | series tag     | permit_renewed_from_permit_number | Permit_Renewed_From_Permit_Number | text          | text          |
| No       |                | x                                 | X                                 | number        | number        |
| No       |                | y                                 | Y                                 | number        | number        |
| No       |                | latitude                          | latitude                          | number        | number        |
| No       |                | longitude                         | longitude                         | number        | number        |
```

## Time Field

```ls
Value = permit_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_end_date,x,y,latitude,longitude
```

## Data Commands

```ls
series e:i926-ujnc d:2016-09-12T00:00:00.000Z t:permit_number=16EXC-4574 t:permit_status=APPROVED t:permit_reason="Reconstruct Pavement" t:street_name="POLK ST" t:permit_purpose="Polk Streetscape Project (Contract No. 2126J)" t:agent="M Squared Construction" t:permit_renewed_from_permit_number=16EXC-4574 t:cross_street_2="SUTTER ST" t:cross_street_1="HEMLOCK ST" m:cnn=10564000

series e:i926-ujnc d:2014-01-27T00:00:00.000Z t:permit_number=14EXC-0540 t:permit_status=APPROVED t:permit_reason=Other t:street_name="SACRAMENTO ST" t:permit_purpose="Central Subway - Chinatown Station (Contract No. 1254)" t:agent="Tutor Perini Corporation" t:permit_renewed_from_permit_number=14EXC-0540 t:cross_street_1="WAVERLY PL" m:cnn=24988000

series e:i926-ujnc d:2015-11-20T00:00:00.000Z t:permit_number=15EXC-6425 t:permit_status=APPROVED t:permit_reason="Reconstruct Pavement" t:street_name="POTRERO AVE" t:permit_purpose="Potrero Avenue Roadway Improvements (Contract No. 2127J)Construction Work: Sewer, Water, Curb Ramps, Bus Pads, Paving, Concrete Base, AWSS, Bulb Out, Catch Basins, Man Holes, Electric, Landscape, and other.Affected Areas: On Potrero Street from Alameda St to Highway 101/Cesar Chavez and Around SF General Hospital (22nd St to Vermont // Vermont between 22nd and 23rd // 23rd St between Vermont and Potrero" t:agent="A. Ruiz Construction Co." t:permit_renewed_from_permit_number=15EXC-6425 t:cross_street_2="19TH ST" t:cross_street_1="18TH ST" m:cnn=10664101
```

## Meta Commands

```ls
metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:i926-ujnc l:"Large Utility Excavation Permits" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/i926-ujnc

property e:i926-ujnc t:meta.view v:id=i926-ujnc v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Large Utility Excavation Permits" v:attribution="San Francisco Department of Public Works"

property e:i926-ujnc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:i926-ujnc t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:i926-ujnc t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| permit_number | street_name   | cross_street_1 | cross_street_2 | cnn      | agent                           | permit_purpose                                                                                                                                                                                                                                                                                                                                                                                                         | permit_reason        | permit_status | permit_start_date   | permit_end_date     | permit_renewed_from_permit_number | x             | y             | latitude         | longitude         | 
| ============= | ============= | ============== | ============== | ======== | =============================== | ====================================================================================================================================================================================================================================================================================================================================================================================================================== | ==================== | ============= | =================== | =================== | ================================= | ============= | ============= | ================ | ================= | 
| 16EXC-4574    | POLK ST       | HEMLOCK ST     | SUTTER ST      | 10564000 | M Squared Construction          | Polk Streetscape Project (Contract No. 2126J)                                                                                                                                                                                                                                                                                                                                                                          | Reconstruct Pavement | APPROVED      | 2016-09-12T00:00:00 | 2018-09-11T00:00:00 | 16EXC-4574                        | 6006858.38304 | 2114906.78358 | 37.7875183256613 | -122.420067824472 | 
| 14EXC-0540    | SACRAMENTO ST | WAVERLY PL     |                | 24988000 | Tutor Perini Corporation        | Central Subway - Chinatown Station (Contract No. 1254)                                                                                                                                                                                                                                                                                                                                                                 | Other                | APPROVED      | 2014-01-27T00:00:00 | 2018-12-31T00:00:00 | 14EXC-0540                        | 6010779.89325 | 2116937.6875  | 37.7933148667767 | -122.406643294267 | 
| 15EXC-6425    | POTRERO AVE   | 18TH ST        | 19TH ST        | 10664101 | A. Ruiz Construction Co.        | Potrero Avenue Roadway Improvements (Contract No. 2127J)Construction Work: Sewer, Water, Curb Ramps, Bus Pads, Paving, Concrete Base, AWSS, Bulb Out, Catch Basins, Man Holes, Electric, Landscape, and other.Affected Areas: On Potrero Street from Alameda St to Highway 101/Cesar Chavez and Around SF General Hospital (22nd St to Vermont // Vermont between 22nd and 23rd // 23rd St between Vermont and Potrero | Reconstruct Pavement | APPROVED      | 2015-11-20T00:00:00 | 2018-02-16T00:00:00 | 15EXC-6425                        | 6010421.59484 | 2105285.70791 | 37.7613011990087 | -122.40706135367  | 
| 15EXC-6425    | POTRERO AVE   | 24TH ST        | 25TH ST        | 10672000 | A. Ruiz Construction Co.        | Potrero Avenue Roadway Improvements (Contract No. 2127J)Construction Work: Sewer, Water, Curb Ramps, Bus Pads, Paving, Concrete Base, AWSS, Bulb Out, Catch Basins, Man Holes, Electric, Landscape, and other.Affected Areas: On Potrero Street from Alameda St to Highway 101/Cesar Chavez and Around SF General Hospital (22nd St to Vermont // Vermont between 22nd and 23rd // 23rd St between Vermont and Potrero | Reconstruct Pavement | APPROVED      | 2015-11-20T00:00:00 | 2018-02-16T00:00:00 | 15EXC-6425                        | 6010581.77236 | 2102027.95784 | 37.752365106117  | -122.40627782501  | 
| 16EXC-7635    | 22ND ST       | IOWA ST        |                | 23624000 | Disney Construction, Inc.       | San Francisco Roadway Bridges Replacement ProjectPeninsula Corridor Joint Powers Board (Contract No. 13-PCJPB-C-036)22nd St., 23rd St. & Paul Ave. Bridges                                                                                                                                                                                                                                                             | Other                | APPROVED      | 2016-11-21T00:00:00 | 2017-05-31T00:00:00 | 15EXC-2407                        | 6014709.4688  | 2103890.84387 | 37.7577102229954 | -122.392133733746 | 
| 16EXC-1246    | ELLIS ST      | TAYLOR ST      | JONES ST       | 5173000  | M Squared Construction          | 12-inch Ductile Iron Water Main Replacement on 6th Street from Market to Howard Streets and on Taylor from Market to Pine Streets (Contract No. WD-2737)                                                                                                                                                                                                                                                               | Install New Main     | ACTIVE        | 2016-04-25T00:00:00 | 2017-05-20T00:00:00 | 16EXC-1246                        | 6009181.60013 | 2113931.26595 | 37.7849704098166 | -122.411960966002 | 
| 16EXC-2736    | BRAZIL AVE    | LISBON ST      |                | 21716000 | Esquivel Grading & Paving, Inc. | Various Locations Pavement Renovation and Sewer Replacement No. 22 (Contract No. 2503J)                                                                                                                                                                                                                                                                                                                                | Reconstruct Pavement | APPROVED      | 2016-08-15T00:00:00 | 2018-01-26T00:00:00 | 16EXC-2736                        | 6002805.28685 | 2091693.03201 | 37.7235497101161 | -122.43243206095  | 
| 16EXC-1246    | TAYLOR ST     | TURK ST        |                | 24924000 | M Squared Construction          | 12-inch Ductile Iron Water Main Replacement on 6th Street from Market to Howard Streets and on Taylor from Market to Pine Streets (Contract No. WD-2737)                                                                                                                                                                                                                                                               | Install New Main     | ACTIVE        | 2016-04-25T00:00:00 | 2017-05-20T00:00:00 | 16EXC-1246                        | 6009514.13642 | 2113284.90176 | 37.7832142991472 | -122.410764827881 | 
| 16EXC-4574    | OFARRELL ST   | LARKIN ST      | POLK ST        | 9734000  | M Squared Construction          | Polk Streetscape Project (Contract No. 2126J)                                                                                                                                                                                                                                                                                                                                                                          | Reconstruct Pavement | APPROVED      | 2016-09-12T00:00:00 | 2018-09-11T00:00:00 | 16EXC-4574                        | 6007228.12372 | 2114005.23773 | 37.7850637263457 | -122.418724633329 | 
| 16EXC-4574    | GREENWICH ST  | POLK ST        | GRENARD TER    | 6509000  | M Squared Construction          | Polk Streetscape Project (Contract No. 2126J)                                                                                                                                                                                                                                                                                                                                                                          | Reconstruct Pavement | APPROVED      | 2016-09-12T00:00:00 | 2018-09-11T00:00:00 | 16EXC-4574                        | 6006165.97754 | 2119689.9496  | 37.8006126636609 | -122.422803472413 | 
```