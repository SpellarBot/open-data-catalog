# Individual Landmarks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/individual-landmarks-ec916) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tdab-kixi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tdab-kixi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tdab-kixi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tdab-kixi |
| Name | Individual Landmarks |
| Attribution | City of Chicago |
| Category | Historic Preservation |
| Tags | landmarks, tourism, gis |
| Created | 2010-04-28T22:47:06Z |
| Publication Date | 2012-08-23T14:34:56Z |

## Description

This dataset is a list of individual Chicago Landmarks designated by City Council upon recommendation of the Commission on Chicago Landmarks. It contains the name of each landmark property along with the date of its construction (if known), the name of its architect/designer (if known), and the date of Chicago Landmark designation. Additional information about each individual Chicago Landmark can be found on the Chicago Landmarks home page at http://j.mp/lRJVnh. Properties which have been proposed for landmark designation by the Commission on Chicago Landmarks and remain under consideration are not included. This information is for illustrative purposes only; the legal descriptions are as identified by the respective landmark designation ordinances. A dataset containing Chicago Landmark Districts is available separately. Data updated quarterly.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | landmark_name             | LANDMARK NAME             | text      | text        |
| No       |             | id                        | ID                        | text      | text        |
| No       |             | address                   | ADDRESS                   | text      | text        |
| No       |             | date_built                | DATE BUILT                | text      | text        |
| Yes      | series tag  | architect                 | ARCHITECT                 | text      | text        |
| Yes      | time        | landmark_designation_date | LANDMARK DESIGNATION DATE | date      | date        |
| No       |             | latitude                  | LATITUDE                  | number    | number      |
| No       |             | longitude                 | LONGITUDE                 | number    | number      |
```

## Time Field

```ls
Value = landmark_designation_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,address,date_built,latitude,longitude
```

## Data Commands

```ls
series e:tdab-kixi d:2012-06-06T07:00:00.000Z t:architect="Karl M. Vitzthum" t:landmark_name="(Former) Pioneer Trust and Savings Bank Building" m:row_number.tdab-kixi=1

series e:tdab-kixi d:2012-06-06T07:00:00.000Z t:architect="R. Bernard Kurzon" t:landmark_name="Riviera Motor Sales Company Building" m:row_number.tdab-kixi=2

series e:tdab-kixi d:2012-05-09T07:00:00.000Z t:architect="Graham, Anderson, Probst and White" t:landmark_name="Wrigley Building" m:row_number.tdab-kixi=3
```

## Meta Commands

```ls
metric m:row_number.tdab-kixi p:long l:"Row Number"

entity e:tdab-kixi l:"Individual Landmarks" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/tdab-kixi

property e:tdab-kixi t:meta.view v:id=tdab-kixi v:category="Historic Preservation" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Individual Landmarks" v:attribution="City of Chicago"

property e:tdab-kixi t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:tdab-kixi t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| landmark_name                                     | id    | address                          | date_built | architect                                         | landmark_designation_date | latitude       | longitude       | 
| ================================================= | ===== | ================================ | ========== | ================================================= | ========================= | ============== | =============== | 
| (Former) Pioneer Trust and Savings Bank Building  | L-318 | 4000 W. North Ave.               | 1924       | Karl M. Vitzthum                                  | 1338966000                | 41.91019210540 | -87.72661734150 | 
| Riviera Motor Sales Company Building              | L-319 | 5948-60 N. Braodway              | 1925-26    | R. Bernard Kurzon                                 | 1338966000                | 41.99064508690 | -87.66070277950 | 
| Wrigley Building                                  | L-320 | 400-410 North Michigan Avenue    | 1921       | Graham, Anderson, Probst and White                | 1336546800                | 41.88972563150 | -87.62485292230 | 
| (Former) Sheridan Trust and Savings Bank Building | L-271 | 4753 N Broadway                  | 1924-28    | Marshall & Fox, Huszagh & Hill                    | 1223449200                | 41.96862254450 | -87.65913012000 | 
| Chicago & North Western Railway Powerhouse        | L- 16 | 211 N Clinton St                 | 1909-11    | Frost & Granger                                   | 1136966400                | 41.88618881540 | -87.64090956540 | 
| Haskell-Barker-Atwater Buildings                  | L-109 | 18-28 S Wabash Av                | 1875-77    | Wheelock & Thomas and John M. Van Osdel           | 847872000                 | 41.88136175490 | -87.62665807950 | 
| F. R. Schock House                                | L-223 | 5804 W Midway Park               | 1886       | Frederick Schock                                  | 916819200                 | 41.88932169350 | -87.77022252260 | 
| Site of the Sauganash Hotel/Wigwam                | L-188 | SE corner of Lake St & Wacker Dr | 1831       |                                                   | 1036569600                | 41.88536539840 | -87.63647274840 | 
| Abraham Lincoln Monument ("Standing Lincoln")     | L-107 | Lincoln Park at Dearborn Parkway | 1887       | A Saint-Gaudens,Sculptor & S White,Architect      | 1008144000                | 41.91260405620 | -87.63025541950 | 
| Humboldt Park Boathouse Pavilion                  | L-116 | 1301 N Humboldt Blvd             | 1907       | Richard E. Schmidt,Garden & Martin w/ Jens Jenson | 847872000                 | 41.90562148020 | -87.70080444180 | 
```