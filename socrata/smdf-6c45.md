# Utility Excavation Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-excavation-permits-8264f) |
| Metadata | [Link](https://data.sfgov.org/api/views/smdf-6c45) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/smdf-6c45/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/smdf-6c45/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | smdf-6c45 |
| Name | Utility Excavation Permits |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | excavation, paving, utilities, 5, year, plan, permits |
| Created | 2012-09-24T23:34:47Z |
| Publication Date | 2015-07-17T15:16:39Z |

## Description

Active Utility Excavation permits issued by DPW

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | permit_number      | permit_number      | text          | text          |
| Yes      | series tag     | streetname         | StreetName         | text          | text          |
| Yes      | series tag     | cross_street_1     | Cross Street 1     | text          | text          |
| Yes      | series tag     | cross_street_2     | Cross Street 2     | text          | text          |
| Yes      | series tag     | utility_contractor | Utility Contractor | text          | text          |
| Yes      | series tag     | permit_reason      | Permit Reason      | text          | text          |
| Yes      | series tag     | utility_type       | Utility Type       | text          | text          |
| Yes      | time           | effective_date     | Effective Date     | calendar_date | calendar_date |
| No       |                | expiration_date    | Expiration Date    | calendar_date | calendar_date |
| Yes      | series tag     | status             | Status             | text          | text          |
| Yes      | numeric metric | cnn                | cnn                | number        | number        |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:smdf-6c45 d:2017-03-23T00:00:00.000Z t:permit_number=17EXC-0581 t:utility_type="Electric:Curb Ramp:Traffic Signal" t:status=APPROVED t:permit_reason="Place Conduit" t:utility_contractor="Bay Area Lightworks" t:cross_street_1="32ND AVE" t:streetname="FULTON ST" m:cnn=27817000

series e:smdf-6c45 d:2017-03-23T00:00:00.000Z t:permit_number=17EXC-0581 t:utility_type="Electric:Curb Ramp:Traffic Signal" t:status=APPROVED t:permit_reason="Place Conduit" t:cross_street_2="BAY ST" t:utility_contractor="Bay Area Lightworks" t:cross_street_1="COLUMBUS AVE" t:streetname="JONES ST" m:cnn=7599000

series e:smdf-6c45 d:2017-03-22T00:00:00.000Z t:permit_number=17EXC-1519 t:utility_type=Gas t:status=APPROVED t:permit_reason="Replace Main" t:utility_contractor="Pacific Gas & Electric" t:cross_street_1="LELAND AVE" t:streetname="LOEHR ST" m:cnn=20392000
```

## Meta Commands

```ls
metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:smdf-6c45 l:"Utility Excavation Permits" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/smdf-6c45

property e:smdf-6c45 t:meta.view v:id=smdf-6c45 v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Utility Excavation Permits" v:attribution="San Francisco Department of Public Works"

property e:smdf-6c45 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:smdf-6c45 t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:smdf-6c45 t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| permit_number | streetname  | cross_street_1 | cross_street_2  | utility_contractor              | permit_reason        | utility_type                                               | effective_date      | expiration_date     | status   | cnn      | 
| ============= | =========== | ============== | =============== | =============================== | ==================== | ========================================================== | =================== | =================== | ======== | ======== | 
| 17EXC-0581    | FULTON ST   | 32ND AVE       |                 | Bay Area Lightworks             | Place Conduit        | Electric:Curb Ramp:Traffic Signal                          | 2017-03-23T00:00:00 | 2018-03-22T00:00:00 | APPROVED | 27817000 | 
| 17EXC-0581    | JONES ST    | COLUMBUS AVE   | BAY ST          | Bay Area Lightworks             | Place Conduit        | Electric:Curb Ramp:Traffic Signal                          | 2017-03-23T00:00:00 | 2018-03-22T00:00:00 | APPROVED | 7599000  | 
| 17EXC-1519    | LOEHR ST    | LELAND AVE     |                 | Pacific Gas & Electric          | Replace Main         | Gas                                                        | 2017-03-22T00:00:00 | 2017-04-30T00:00:00 | APPROVED | 20392000 | 
| 16EXC-5007    | 11TH ST     | NATOMA ST      |                 | Precision Engineering, Inc.     | Reconstruct Pavement | Street / Roadway:Curb Ramp:Sewer                           | 2016-09-07T00:00:00 | 2017-08-02T00:00:00 | APPROVED | 24355000 | 
| 17EXC-1559    | 18TH AVE    | ORTEGA ST      |                 | Pacific Gas & Electric          | Replace Pole         | Electric                                                   | 2017-06-07T00:00:00 | 2017-06-12T00:00:00 | APPROVED | 27318000 | 
| 17EXC-0581    | DETROIT ST  | MONTEREY BLVD  |                 | Bay Area Lightworks             | Place Conduit        | Electric:Curb Ramp:Traffic Signal                          | 2017-03-23T00:00:00 | 2018-03-22T00:00:00 | APPROVED | 22156000 | 
| 17EXC-1519    | ELLIOT ST   | RAYMOND AVE    | LELAND AVE      | Pacific Gas & Electric          | Replace Main         | Gas                                                        | 2017-03-22T00:00:00 | 2017-04-30T00:00:00 | APPROVED | 5168000  | 
| 16EXC-2736    | AVALON AVE  | NAPLES ST      | VIENNA ST       | Esquivel Grading & Paving, Inc. | Reconstruct Pavement | Catch Basin:Street / Roadway:Sidewalk/Curb:Curb Ramp:Sewer | 2016-08-15T00:00:00 | 2018-01-26T00:00:00 | APPROVED | 2561000  | 
| 16EXC-7893    | CAPITOL AVE | HOLLOWAY AVE   | DE MONTFORT AVE | Precision Engineering, Inc.     | Reconstruct Pavement | Street / Roadway:Curb Ramp                                 | 2016-12-19T00:00:00 | 2017-06-11T00:00:00 | APPROVED | 3669000  | 
| 17EXC-0581    | RUSS ST     | HOWARD ST      | FOLSOM ST       | Bay Area Lightworks             | Place Conduit        | Electric:Curb Ramp:Traffic Signal                          | 2017-03-23T00:00:00 | 2018-03-22T00:00:00 | APPROVED | 11186000 | 
```