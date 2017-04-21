# LADWP Service Center Addresses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-service-center-addresses-a23c5) |
| Metadata | [Link](https://data.lacity.org/api/views/uh2b-55sv) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/uh2b-55sv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/uh2b-55sv/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | uh2b-55sv |
| Name | LADWP Service Center Addresses |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | ladwp service center, customer center |
| Created | 2014-05-12T23:10:46Z |
| Publication Date | 2014-05-30T03:29:39Z |

## Description

Location of LADWP Service Center

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                        | Data Type | Render Type |
| ======== | =========== | ============================= | =========================== | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | ladwp_service_center          | LADWP Service Center        | text      | text        |
| Yes      | series tag  | street_address                | Street Address              | text      | text        |
| Yes      | series tag  | customer_service_phone_number | Residential CS Phone Number | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uh2b-55sv d:2014-05-29T20:15:34.000Z t:ladwp_service_center="Boyle Heights CSC" t:phone_number=1-800-342-5397 t:street_address="919 S. Soto Street #10" m:row_number.uh2b-55sv=1

series e:uh2b-55sv d:2014-05-29T20:15:47.000Z t:ladwp_service_center="Central CSC" t:phone_number=1-800-342-5397 t:street_address="4619 S. Central Avenue" m:row_number.uh2b-55sv=2

series e:uh2b-55sv d:2014-05-29T20:15:50.000Z t:ladwp_service_center="Crenshaw CSC" t:phone_number=1-800-342-5397 t:street_address="4030 Crenshaw Boulevard" m:row_number.uh2b-55sv=3
```

## Meta Commands

```ls
metric m:row_number.uh2b-55sv p:long l:"Row Number"

entity e:uh2b-55sv l:"LADWP Service Center Addresses" t:attribution=LADWP t:url=https://data.lacity.org/api/views/uh2b-55sv

property e:uh2b-55sv t:meta.view v:id=uh2b-55sv v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Service Center Addresses" v:attribution=LADWP

property e:uh2b-55sv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uh2b-55sv t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:uh2b-55sv t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| :updated_at | ladwp_service_center | street_address          | customer_service_phone_number | 
| =========== | ==================== | ======================= | ============================= | 
| 1401394534  | Boyle Heights CSC    | 919 S. Soto Street #10  | [1-800-342-5397, null]        | 
| 1401394547  | Central CSC          | 4619 S. Central Avenue  | [1-800-342-5397, null]        | 
| 1401394550  | Crenshaw CSC         | 4030 Crenshaw Boulevard | [1-800-342-5397, null]        | 
| 1401394552  | JFB Lobby CSC        | 111 N. Hope Street      | [1-800-342-5397, null]        | 
| 1401394554  | Hollywood CSC        | 6547-B Sunset Boulevard | [1-800-342-5397, null]        | 
| 1401394555  | Lincoln Heights CSC  | 2417 Daly Street        | [1-800-342-5397, null]        | 
| 1401394557  | Slauson/Vermont CSC  | 5928 S. Vermont Avenue  | [1-800-342-5397, null]        | 
| 1401394558  | Watts CSC            | 1686 E. 103rd Street    | [1-800-342-5397, null]        | 
| 1401394559  | San Pedro CSC        | 535 W. 9th Street       | [1-800-342-5397, null]        | 
| 1401394560  | Wilmington CSC       | 931 N. Avalon Boulevard | [1-800-342-5397, null]        | 
```