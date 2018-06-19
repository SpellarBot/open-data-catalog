# Street Acceptance Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-acceptance-data) |
| Metadata | [Link](https://data.sfgov.org/api/views/abvp-arbf) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/abvp-arbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/abvp-arbf/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | abvp-arbf |
| Name | Street Acceptance Data |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | acceptance, jurisdiction, caltrans, maintenance, right, of, way, paving, accepted, streets |
| Created | 2015-11-14T23:26:26Z |
| Publication Date | 2016-03-22T19:21:24Z |

## Description

List of streets by block (street segment) accepted for maintenance

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | numeric metric | cnn                   | CNN                   | number        | number        |
| Yes      | series tag     | streetname            | Streetname            | text          | text          |
| Yes      | series tag     | limits                | Limits                | text          | text          |
| Yes      | series tag     | ordinancenumber       | OrdinanceNumber       | text          | text          |
| Yes      | time           | dateaccepted          | DateAccepted          | calendar_date | calendar_date |
| Yes      | series tag     | bosfilenumber         | BOSFileNumber         | text          | text          |
| Yes      | series tag     | dpwordernumber        | DPWOrderNumber        | text          | text          |
| Yes      | numeric metric | length_ft             | Length_ft             | number        | number        |
| Yes      | series tag     | jurisdiction          | Jurisdiction          | text          | text          |
| Yes      | series tag     | cadot_maint_agreement | CADOT_Maint_Agreement | text          | text          |
| Yes      | series tag     | ma_link               | MA_link               | url           | url           |
| No       |                | x                     | X                     | number        | number        |
| No       |                | y                     | Y                     | number        | number        |
| No       |                | latitude              | Latitude              | number        | number        |
| No       |                | longitude             | Longitude             | number        | number        |
```

## Time Field

```ls
Value = dateaccepted
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = x,y,latitude,longitude
```

## Data Commands

```ls
series e:abvp-arbf d:1998-05-01T00:00:00.000Z t:limits="RUSSIA AVE to FRANCE AVE (600 - 699)" t:ordinancenumber=138-98 t:dpwordernumber=170,718 t:bosfilenumber=9-97-3 t:jurisdiction=DPW t:streetname="VIENNA ST" m:length_ft=659.798220209397 m:cnn=13303000

series e:abvp-arbf d:1998-05-01T00:00:00.000Z t:limits="LANCASTER LN to OCEAN AVE (390 - 499)" t:ordinancenumber=138-98 t:dpwordernumber=170,718 t:bosfilenumber=9-97-3 t:jurisdiction=DPW t:streetname="LAKESHORE DR" m:length_ft=1134.3647055269 m:cnn=8059000

series e:abvp-arbf d:1998-05-01T00:00:00.000Z t:limits="MCKINNON AVE to NEWCOMB AVE (1200 - 1299)" t:ordinancenumber=138-98 t:dpwordernumber=170,718 t:bosfilenumber=9-97-3 t:jurisdiction=DPW t:streetname="NEWHALL ST" m:length_ft=277.458713858745 m:cnn=9572000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

metric m:length_ft p:double l:Length_ft t:dataTypeName=number

entity e:abvp-arbf l:"Street Acceptance Data" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/abvp-arbf

property e:abvp-arbf t:meta.view v:id=abvp-arbf v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Street Acceptance Data" v:attribution="San Francisco Department of Public Works"

property e:abvp-arbf t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:abvp-arbf t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:abvp-arbf t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| cnn      | streetname   | limits                                             | ordinancenumber | dateaccepted        | bosfilenumber | dpwordernumber | length_ft        | jurisdiction | cadot_maint_agreement | ma_link      | x             | y             | latitude         | longitude         | 
| ======== | ============ | ================================================== | =============== | =================== | ============= | ============== | ================ | ============ | ===================== | ============ | ============= | ============= | ================ | ================= | 
| 13303000 | VIENNA ST    | RUSSIA AVE to FRANCE AVE (600 - 699)               | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 659.798220209397 | DPW          |                       | [null, null] | 6002840.56147 | 2089721.41639 | 37.7181380916714 | -122.432169388906 | 
| 8059000  | LAKESHORE DR | LANCASTER LN to OCEAN AVE (390 - 499)              | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 1134.3647055269  | DPW          |                       | [null, null] | 5984884.92193 | 2095569.20267 | 37.7331601859642 | -122.494664293786 | 
| 9572000  | NEWHALL ST   | MCKINNON AVE to NEWCOMB AVE (1200 - 1299)          | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 277.458713858745 | DPW          |                       | [null, null] | 6014775.56616 | 2096200.34088 | 37.7365973840641 | -122.39136753496  | 
| 11626000 | SANTIAGO ST  | 35TH AVE to 36TH AVE (2400 - 2499)                 | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 310.083672759689 | DPW          |                       | [null, null] | 5985305.79832 | 2099558.74171 | 37.7441390174873 | -122.493503081909 | 
| 3862000  | CENTRAL AVE  | PAGE ST to OAK ST (200 - 299)                      | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 345.552001479575 | DPW          |                       | [null, null] | 5999845.59462 | 2109336.69737 | 37.771826687772  | -122.443930227216 | 
| 758000   | 17TH AVE     | IRVING ST to JUDAH ST (1300 - 1399)                | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 678.908667483987 | DPW          |                       | [null, null] | 5990820.51653 | 2106210.82978 | 37.7627249536596 | -122.47492006191  | 
| 7950000  | LAGUNA ST    | HAYES ST to IVY ST (600 - 627)                     | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 171.875390759165 | DPW          |                       | [null, null] | 6004973.50439 | 2111004.49635 | 37.7766972314014 | -122.426311189715 | 
| 13610000 | WHITNEY ST   | FAIRMOUNT ST to CHENERY ST \ MIGUEL ST (200 - 299) | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 630.313785565272 | DPW          |                       | [null, null] | 6004376.59121 | 2096927.94022 | 37.7380125742519 | -122.427373080401 | 
| 7868000  | KIRKHAM ST   | 30TH AVE to 31ST AVE (2600 - 2699)                 | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 310.988601968198 | DPW          |                       | [null, null] | 5986671.26738 | 2105047.17641 | 37.7592885528456 | -122.489185089731 | 
| 11008000 | RICHARDS CIR | END to MABREY CT \ WHITNEY YOUNG CIR (1 - 99)      | 138-98          | 1998-05-01T00:00:00 | 9-97-3        | 170,718        | 69.9074174695262 | DPW          |                       | [null, null] | 6016354.2571  | 2095859.22818 | 37.7357482489151 | -122.385885502542 | 
```