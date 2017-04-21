# Curb Ramps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/curb-ramps-ce87b) |
| Metadata | [Link](https://data.sfgov.org/api/views/ch9w-7kih) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ch9w-7kih/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ch9w-7kih/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ch9w-7kih |
| Name | Curb Ramps |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | curb, ramps, ada, disability, access |
| Created | 2012-09-24T22:50:47Z |
| Publication Date | 2016-03-15T17:40:46Z |

## Description

Curb ramp locations and attribute data. These data come from the Curb Ramp Information System (CRIS). Please be advised ? CRIS is a planning tool only. There is no guarantee of attribute accuracy. Also, while the data syncs nightly the underlying system only updates about once a quarter.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | locid                | locID                | text          | text          |
| Yes      | numeric metric | cnn                  | CNN                  | number        | number        |
| Yes      | numeric metric | xloc                 | xLoc                 | number        | number        |
| Yes      | numeric metric | yloc                 | yLoc                 | number        | number        |
| Yes      | series tag     | locationdescription  | LocationDescription  | text          | text          |
| Yes      | series tag     | curbreturnloc        | curbReturnLoc        | text          | text          |
| Yes      | series tag     | positiononreturn     | positionOnReturn     | text          | text          |
| No       |                | latitude             | Latitude             | number        | number        |
| No       |                | longitude            | Longitude            | number        | number        |
| Yes      | time           | lastupdate           | LastUpdate           | calendar_date | calendar_date |
| Yes      | series tag     | invenid              | InvenID              | text          | number        |
| Yes      | numeric metric | conditionscore       | conditionScore       | number        | number        |
| Yes      | numeric metric | detectablesurf       | detectableSurf       | number        | number        |
| Yes      | numeric metric | vitalfacilities      | vitalFacilities      | number        | number        |
| Yes      | numeric metric | heavytraffic         | heavyTraffic         | number        | number        |
| Yes      | numeric metric | liptoohigh           | lipTooHigh           | number        | number        |
| Yes      | series tag     | probstreetmeetcr     | probStreetMeetCR     | text          | number        |
| Yes      | numeric metric | possbasementobstacle | possBasementObstacle | number        | number        |
| Yes      | numeric metric | signalpoleinwing     | signalPoleInWing     | number        | number        |
| Yes      | numeric metric | catchbasinfrontofcr  | catchBasinFrontOfCR  | number        | number        |
| Yes      | numeric metric | insidecrosswalk      | insideCrosswalk      | number        | number        |
| Yes      | numeric metric | surfcond             | surfCond             | number        | number        |
| Yes      | numeric metric | slopewing            | slopeWing            | number        | number        |
| Yes      | numeric metric | flushtocorner        | flushToCorner        | number        | number        |
| Yes      | numeric metric | colorcontrast        | colorContrast        | number        | number        |
| Yes      | numeric metric | paintedred           | paintedRed           | number        | number        |
| Yes      | numeric metric | topclearance         | topClearance         | number        | number        |
| Yes      | numeric metric | sideclearance        | sideClearance        | number        | number        |
| Yes      | numeric metric | crtoonarrow          | CRTooNarrow          | number        | number        |
| Yes      | numeric metric | levellandtop         | levelLandTop         | number        | number        |
| Yes      | numeric metric | levellandbottom      | levelLandBottom      | number        | number        |
| Yes      | series tag     | sloperangeid         | slopeRangeID         | text          | number        |
| Yes      | series tag     | crpossible           | crPossible           | text          | text          |
| Yes      | numeric metric | crexist              | crExist              | number        | number        |
```

## Time Field

```ls
Value = lastupdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:ch9w-7kih d:2016-09-13T17:28:34.000Z t:curbreturnloc=NE t:locid=26784000-NE-Left t:sloperangeid=4 t:positiononreturn=Left t:locationdescription="FILLMORE ST: NORTH POINT ST intersection" t:invenid=37511 m:surfcond=1 m:levellandtop=1 m:colorcontrast=1 m:catchbasinfrontofcr=0 m:crtoonarrow=1 m:signalpoleinwing=0 m:liptoohigh=0 m:insidecrosswalk=0 m:cnn=26784000 m:crexist=1 m:conditionscore=57 m:xloc=6002171.11058 m:possbasementobstacle=0 m:yloc=2120889.2195 m:slopewing=1

series e:ch9w-7kih d:2016-09-13T17:28:34.000Z t:curbreturnloc=NE t:locid=23778000-NE-Left t:sloperangeid=2 t:positiononreturn=Left t:locationdescription="17TH ST: VERMONT ST intersection" t:invenid=20684 m:levellandbottom=1 m:surfcond=1 m:levellandtop=1 m:colorcontrast=1 m:catchbasinfrontofcr=0 m:crtoonarrow=1 m:signalpoleinwing=0 m:liptoohigh=0 m:insidecrosswalk=1 m:cnn=23778000 m:detectablesurf=1 m:crexist=1 m:conditionscore=100 m:xloc=6011219.59577 m:possbasementobstacle=0 m:yloc=2106518.52908 m:slopewing=1

series e:ch9w-7kih d:2016-09-13T17:28:34.000Z t:curbreturnloc=E t:locid=11496101-E-MB t:positiononreturn=MB t:locationdescription="SAN MARCOS AVE: END to END (201 - 325)" t:crpossible=Y44 t:invenid=50762 m:crexist=0 m:conditionscore=0 m:xloc=5993254.3584 m:possbasementobstacle=0 m:yloc=2100255.0193 m:cnn=11496101
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

metric m:xloc p:double l:xLoc t:dataTypeName=number

metric m:yloc p:double l:yLoc t:dataTypeName=number

metric m:conditionscore p:integer l:conditionScore t:dataTypeName=number

metric m:detectablesurf p:integer l:detectableSurf t:dataTypeName=number

metric m:vitalfacilities p:integer l:vitalFacilities t:dataTypeName=number

metric m:heavytraffic p:integer l:heavyTraffic t:dataTypeName=number

metric m:liptoohigh p:integer l:lipTooHigh t:dataTypeName=number

metric m:possbasementobstacle p:integer l:possBasementObstacle t:dataTypeName=number

metric m:signalpoleinwing p:integer l:signalPoleInWing t:dataTypeName=number

metric m:catchbasinfrontofcr p:integer l:catchBasinFrontOfCR t:dataTypeName=number

metric m:insidecrosswalk p:integer l:insideCrosswalk t:dataTypeName=number

metric m:surfcond p:integer l:surfCond t:dataTypeName=number

metric m:slopewing p:integer l:slopeWing t:dataTypeName=number

metric m:flushtocorner p:integer l:flushToCorner t:dataTypeName=number

metric m:colorcontrast p:integer l:colorContrast t:dataTypeName=number

metric m:paintedred p:integer l:paintedRed t:dataTypeName=number

metric m:topclearance p:integer l:topClearance t:dataTypeName=number

metric m:sideclearance p:integer l:sideClearance t:dataTypeName=number

metric m:crtoonarrow p:integer l:CRTooNarrow t:dataTypeName=number

metric m:levellandtop p:integer l:levelLandTop t:dataTypeName=number

metric m:levellandbottom p:integer l:levelLandBottom t:dataTypeName=number

metric m:crexist p:integer l:crExist t:dataTypeName=number

entity e:ch9w-7kih l:"Curb Ramps" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/ch9w-7kih

property e:ch9w-7kih t:meta.view v:id=ch9w-7kih v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Curb Ramps" v:attribution="San Francisco Department of Public Works"

property e:ch9w-7kih t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ch9w-7kih t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:ch9w-7kih t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| locid              | cnn      | xloc          | yloc          | locationdescription                              | curbreturnloc | positiononreturn | latitude         | longitude         | lastupdate          | invenid | conditionscore | detectablesurf | vitalfacilities | heavytraffic | liptoohigh | probstreetmeetcr | possbasementobstacle | signalpoleinwing | catchbasinfrontofcr | insidecrosswalk | surfcond | slopewing | flushtocorner | colorcontrast | paintedred | topclearance | sideclearance | crtoonarrow | levellandtop | levellandbottom | sloperangeid | crpossible | crexist | 
| ================== | ======== | ============= | ============= | ================================================ | ============= | ================ | ================ | ================= | =================== | ======= | ============== | ============== | =============== | ============ | ========== | ================ | ==================== | ================ | =================== | =============== | ======== | ========= | ============= | ============= | ========== | ============ | ============= | =========== | ============ | =============== | ============ | ========== | ======= | 
| 26784000-NE-Left   | 26784000 | 6002171.11058 | 2120889.2195  | FILLMORE ST: NORTH POINT ST intersection         | NE            | Left             | 37.8036793337208 | -122.436713218162 | 2016-09-13T17:28:34 | 37511   | 57             |                |                 |              | 0          |                  | 0                    | 0                | 0                   | 0               | 1        | 1         |               | 1             |            |              |               | 1           | 1            |                 | 4            |            | 1       | 
| 23778000-NE-Left   | 23778000 | 6011219.59577 | 2106518.52908 | 17TH ST: VERMONT ST intersection                 | NE            | Left             | 37.7647308732881 | -122.404388167886 | 2016-09-13T17:28:34 | 20684   | 100            | 1              |                 |              | 0          |                  | 0                    | 0                | 0                   | 1               | 1        | 1         |               | 1             |            |              |               | 1           | 1            | 1               | 2            |            | 1       | 
| 11496101-E-MB      | 11496101 | 5993254.3584  | 2100255.0193  | SAN MARCOS AVE: END to END (201 - 325)           | E             | MB               | 37.7465125813318 | -122.46606952497  | 2016-09-13T17:28:34 | 50762   | 0              |                |                 |              |            |                  | 0                    |                  |                     |                 |          |           |               |               |            |              |               |             |              |                 |              | Y44        | 0       | 
| 27911000-NW-Right  | 27911000 | 5982510.43567 | 2112431.68097 | 43RD AVE: GEARY BLVD intersection                | NW            | Right            | 37.7793205240404 | -122.504122015473 | 2016-09-13T17:28:34 | 45057   | 0              |                |                 |              |            |                  |                      |                  |                     |                 |          |           |               |               |            |              |               |             |              |                 |              | Y44        | 0       | 
| 22316000-SW-Right  | 22316000 | 6001297.29507 | 2100827.61329 | CLIPPER ST: DOUGLASS ST intersection             | SW            | Right            | 37.7485455207805 | -122.43829900468  | 2016-09-13T17:28:34 | 12293   | 65             |                |                 |              | 1          | 0                | 0                    | 0                | 0                   | 1               | 1        | 1         | 1             | 1             | 0          | 1            | 1             | 1           | 1            |                 | 3            |            | 1       | 
| 27857000-SW-Right  | 27857000 | 5985309.24405 | 2112438.35582 | 34TH AVE: GEARY BLVD intersection                | SW            | Right            | 37.7795030466795 | -122.494440403157 | 2016-09-13T17:28:34 | 44705   | 68             | 0              | 0               | 1            | 0          |                  | 0                    | 0                | 0                   | 1               | 1        | 1         |               | 0             |            |              |               | 1           | 1            | 0               | 3            |            | 1       | 
| 20625000-S-Left    | 20625000 | 6011858.29069 | 2094723.15241 | LEDYARD ST: MERCURY ST intersection              | S             | Left             | 37.7323789923823 | -122.401350089753 | 2016-09-13T17:28:34 | 3091    | -2             |                |                 |              |            |                  |                      |                  |                     |                 |          |           |               |               |            |              |               |             |              |                 |              | N04        | 0       | 
| 21116000-SE-Right  | 21116000 | 6010269.13081 | 2099812.96309 | MACEDONIA ST: MONTCALM ST intersection           | SE            | Right            | 37.7462657243814 | -122.407202871105 | 2016-09-13T17:28:34 | 5625    | 0              |                |                 |              |            |                  |                      |                  |                     |                 |          |           |               |               |            |              |               |             |              |                 |              | Y30        | 0       | 
| 20215000-N-Right   | 20215000 | 6016219.74915 | 2097078.34028 | HUDSON AVE: MENDELL ST intersection              | N             | Right            | 37.7390882398317 | -122.386435528003 | 2016-09-13T17:28:34 | 878     | 100            | 1              |                 |              | 0          |                  | 0                    | 0                | 0                   | 1               | 1        | 1         |               | 1             |            |              |               | 1           | 1            | 1               | 2            |            | 1       | 
| 26844000-NW-Center | 26844000 | 5999121.26071 | 2114637.62176 | MASONIC AVE: PINE ST \ PRESIDIO AVE intersection | NW            | Center           | 37.7863403142226 | -122.446817234171 | 2016-09-13T17:28:34 | 37933   | 79             | 0              | 0               | 1            | 0          |                  | 0                    | 0                | 0                   | 1               | 1        | 0         |               | 0             |            |              |               | 1           | 1            | 1               | 3            |            | 1       | 
```