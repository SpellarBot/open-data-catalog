# Parklet Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parklet-permits) |
| Metadata | [Link](https://data.sfgov.org/api/views/jczu-j2ku) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/jczu-j2ku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/jczu-j2ku/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | jczu-j2ku |
| Name | Parklet Permits |
| Attribution | San Francisco Public Works |
| Category | Culture and Recreation |
| Tags | parklet, sidewalk, permit, right, of, way, open, space, narrow, parking |
| Created | 2016-09-16T23:40:50Z |
| Publication Date | 2016-09-17T00:03:51Z |

## Description

A list of all permitted parklets in San Francisco. A parklet is a sidewalk extension that provides more space and amenities for people using the street. Usually parklets are installed on parking lanes and use several parking spaces.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | permit_number                      | Permit_Number                      | text      | text        |
| No       |                | permit_address                     | Permit_Address                     | text      | text        |
| Yes      | series tag     | street_name                        | Street_Name                        | text      | text        |
| Yes      | series tag     | cross_street_1                     | Cross_Street_1                     | text      | text        |
| Yes      | series tag     | cross_street_2                     | Cross_Street_2                     | text      | text        |
| Yes      | series tag     | permit_zipcode                     | Permit_ZipCode                     | text      | text        |
| Yes      | series tag     | applicant                          | Applicant                          | text      | text        |
| Yes      | series tag     | permit_purpose                     | Permit_Purpose                     | text      | text        |
| Yes      | time           | permit_approval_date               | Permit_Approval_Date               | text      | text        |
| No       |                | permit_end_date                    | Permit_End_Date                    | text      | text        |
| Yes      | series tag     | permit_status                      | Permit_Status                      | text      | text        |
| No       |                | x                                  | X                                  | number    | number      |
| No       |                | y                                  | Y                                  | number    | number      |
| No       |                | latitude                           | Latitude                           | number    | number      |
| No       |                | longitude                          | Longitude                          | number    | number      |
| Yes      | numeric metric | cnn                                | cnn                                | number    | number      |
| Yes      | series tag     | envista_project_id                 | envista_project_id                 | text      | text        |
| Yes      | series tag     | envista_project_name_full          | envista_project_name_full          | text      | text        |
| Yes      | series tag     | envista_facility_type              | envista_facility_type              | text      | text        |
| No       |                | envista_start_date                 | envista_start_date                 | text      | text        |
| No       |                | envista_end_date                   | envista_end_date                   | text      | text        |
| Yes      | series tag     | envista_description                | envista_description                | text      | text        |
| Yes      | series tag     | envista_moratoriums_opportunities  | envista_moratoriums_opportunities  | text      | text        |
| Yes      | series tag     | envista_facility_indicator         | envista_facility_indicator         | text      | text        |
| Yes      | series tag     | envista_facility_subindicator      | envista_facility_subindicator      | text      | text        |
| Yes      | series tag     | envista_project_type               | envista_project_type               | text      | text        |
| Yes      | series tag     | envista_location_type              | envista_location_type              | text      | text        |
| Yes      | series tag     | envista_intermediate_location_text | envista_intermediate_location_text | text      | text        |
```

## Time Field

```ls
Value = permit_approval_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = permit_address,permit_end_date,x,y,latitude,longitude,envista_start_date,envista_end_date
```

## Data Commands

```ls
series e:jczu-j2ku d:2016-06-27T00:00:00.000Z t:envista_description="262 DIVISADERO ST" t:envista_facility_indicator=Parking t:street_name="DIVISADERO ST" t:permit_purpose=Parklet t:envista_facility_type=Roadway t:cross_street_2="PAGE ST" t:cross_street_1="HAIGHT ST" t:envista_facility_subindicator=Sidewalks t:permit_number=16PKT-0054 t:permit_zipcode=94117 t:envista_location_type=Point t:permit_status=APPROVED t:envista_project_name_full="Parklet at Repose Coffee Bar and Gallery" t:envista_intermediate_location_text="262 DIVISADERO ST, San Francisco, CA 94117" t:applicant="Repose Coffee Bar and Gallery" t:envista_project_id=16PKT-0054 t:envista_moratoriums_opportunities="No Excavation" t:envista_project_type=Maintenance m:cnn=4799201

series e:jczu-j2ku d:2017-01-17T00:00:00.000Z t:envista_description="423 COLUMBUS AVE" t:envista_facility_indicator=Parking t:street_name="COLUMBUS AVE" t:permit_purpose=Parklet t:envista_facility_type=Roadway t:cross_street_2="GREEN ST \ STOCKTON ST" t:cross_street_1="VALLEJO ST" t:envista_facility_subindicator=Sidewalks t:permit_number=17PKT-0001 t:permit_zipcode=94133 t:envista_location_type=Point t:permit_status=APPROVED t:envista_project_name_full="Parklet at CAFFE' GRECO" t:envista_intermediate_location_text="423 COLUMBUS AVE, San Francisco, CA 94133" t:applicant="CAFFE' GRECO" t:envista_project_id=17PKT-0001 t:envista_moratoriums_opportunities="No Excavation" t:envista_project_type=Maintenance m:cnn=4294000

series e:jczu-j2ku d:2017-01-19T00:00:00.000Z t:envista_description="3434 BALBOA ST" t:envista_facility_indicator=Parking t:street_name="BALBOA ST" t:permit_purpose=Parklet t:envista_facility_type=Roadway t:cross_street_2="36TH AVE" t:cross_street_1="35TH AVE" t:envista_facility_subindicator=Sidewalks t:permit_number=17PKT-0002 t:permit_zipcode=94121 t:envista_location_type=Point t:permit_status=APPROVED t:envista_project_name_full="Parklet at SIMPLE PLEASURES CAF?" t:envista_intermediate_location_text="3434 BALBOA ST, San Francisco, CA 94121" t:applicant="SIMPLE PLEASURES CAF?" t:envista_project_id=17PKT-0002 t:envista_moratoriums_opportunities="No Excavation" t:envista_project_type=Maintenance m:cnn=2680000
```

## Meta Commands

```ls
metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:jczu-j2ku l:"Parklet Permits" t:attribution="San Francisco Public Works" t:url=https://data.sfgov.org/api/views/jczu-j2ku

property e:jczu-j2ku t:meta.view v:id=jczu-j2ku v:category="Culture and Recreation" v:attributionLink=http://sfpublicworks.org/ v:averageRating=0 v:name="Parklet Permits" v:attribution="San Francisco Public Works"

property e:jczu-j2ku t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jczu-j2ku t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:jczu-j2ku t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| permit_number | permit_address     | street_name   | cross_street_1 | cross_street_2         | permit_zipcode | applicant                                      | permit_purpose | permit_approval_date | permit_end_date | permit_status | x             | y             | latitude         | longitude         | cnn      | envista_project_id | envista_project_name_full                                 | envista_facility_type | envista_start_date | envista_end_date | envista_description | envista_moratoriums_opportunities | envista_facility_indicator | envista_facility_subindicator | envista_project_type | envista_location_type | envista_intermediate_location_text          | 
| ============= | ================== | ============= | ============== | ====================== | ============== | ============================================== | ============== | ==================== | =============== | ============= | ============= | ============= | ================ | ================= | ======== | ================== | ========================================================= | ===================== | ================== | ================ | =================== | ================================= | ========================== | ============================= | ==================== | ===================== | =========================================== | 
| 16PKT-0054    | 262 DIVISADERO ST  | DIVISADERO ST | HAIGHT ST      | PAGE ST                | 94117          | Repose Coffee Bar and Gallery                  | Parklet        | 6/27/2016            | 8/15/2017       | APPROVED      | 6001873.01636 | 2109185.67204 | 37.771527449986  | -122.436906435278 | 4799201  | 16PKT-0054         | Parklet at Repose Coffee Bar and Gallery                  | Roadway               | 6/27/2016          | 8/15/2017        | 262 DIVISADERO ST   | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 262 DIVISADERO ST, San Francisco, CA 94117  | 
| 17PKT-0001    | 423 COLUMBUS AVE   | COLUMBUS AVE  | VALLEJO ST     | GREEN ST \ STOCKTON ST | 94133          | CAFFE' GRECO                                   | Parklet        | 1/17/2017            | 2/15/2018       | APPROVED      | 6010289.04546 | 2118999.33253 | 37.7989481680788 | -122.408487162809 | 4294000  | 17PKT-0001         | Parklet at CAFFE' GRECO                                   | Roadway               | 1/17/2017          | 2/15/2018        | 423 COLUMBUS AVE    | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 423 COLUMBUS AVE, San Francisco, CA 94133   | 
| 17PKT-0002    | 3434 BALBOA ST     | BALBOA ST     | 35TH AVE       | 36TH AVE               | 94121          | SIMPLE PLEASURES CAF?                          | Parklet        | 1/19/2017            | 2/15/2018       | APPROVED      | 5984886.07308 | 2111149.1633  | 37.7759385201735 | -122.49580918509  | 2680000  | 17PKT-0002         | Parklet at SIMPLE PLEASURES CAF?                          | Roadway               | 1/19/2017          | 2/15/2018        | 3434 BALBOA ST      | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 3434 BALBOA ST, San Francisco, CA 94121     | 
| 17PKT-0004    | 2001 POLK ST       | PACIFIC AVE   | POLK ST        | VAN NESS AVE           | 94109          | Cheese Plus                                    | Parklet        | 1/20/2017            | 2/15/2018       | APPROVED      | 6006425.0696  | 2117735.31996 | 37.7952603590802 | -122.421767991747 | 10147000 | 17PKT-0004         | Parklet at Cheese Plus                                    | Roadway               | 1/20/2017          | 2/15/2018        | 2001 POLK ST        | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 2001 POLK ST, San Francisco, CA 94109       | 
| 17PKT-0005    | 2410 CALIFORNIA ST | CALIFORNIA ST | FILLMORE ST    | STEINER ST             | 94115          | Pizzeria Due, LLC dba: Delfina                 | Parklet        | 1/20/2017            | 2/15/2018       | APPROVED      | 6002732.53958 | 2115520.04684 | 37.7889688677795 | -122.434386260392 | 3558000  | 17PKT-0005         | Parklet at Pizzeria Due, LLC dba: Delfina                 | Roadway               | 1/20/2017          | 2/15/2018        | 2410 CALIFORNIA ST  | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 2410 CALIFORNIA ST, San Francisco, CA 94115 | 
| 17PKT-0007    | 436 BALBOA ST      | BALBOA ST     | 05TH AVE       | 06TH AVE               | 94118          | CINDERELLA BAKERY INC.                         | Parklet        | 1/23/2017            | 2/15/2018       | APPROVED      | 5994172.80673 | 2111474.38044 | 37.7773709746424 | -122.463707816523 | 2649000  | 17PKT-0007         | Parklet at CINDERELLA BAKERY INC.                         | Roadway               | 1/23/2017          | 2/15/2018        | 436 BALBOA ST       | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 436 BALBOA ST, San Francisco, CA 94118      | 
| 17PKT-0006    | 988 VALENCIA ST    | VALENCIA ST   | LIBERTY ST     | 21ST ST                | 94110          | Blue Fig Cafe                                  | Parklet        | 1/23/2017            | 2/15/2018       | APPROVED      | 6006263.20225 | 2103863.99585 | 37.7571639251618 | -122.421342540038 | 13068000 | 17PKT-0006         | Parklet at Blue Fig Cafe                                  | Roadway               | 1/23/2017          | 2/15/2018        | 988 VALENCIA ST     | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 988 VALENCIA ST, San Francisco, CA 94110    | 
| 17PKT-0008    | 533 JONES ST       | JONES ST      | OFARRELL ST    | GEARY ST               | 94102          | Usama Shahbaz and Ali Amin dba Karachi Chicken | Parklet        | 1/25/2017            | 2/15/2018       | APPROVED      | 6008819.27478 | 2114416.55889 | 37.786282572627  | -122.413248829754 | 7570000  | 17PKT-0008         | Parklet at Usama Shahbaz and Ali Amin dba Karachi Chicken | Roadway               | 1/25/2017          | 2/15/2018        | 533 JONES ST        | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 533 JONES ST, San Francisco, CA 94102       | 
| 17PKT-0012    | 1331 09TH AVE      | 09TH AVE      | IRVING ST      | JUDAH ST               | 94122          | ARIZMENDI BAKERY - 9TH AVE                     | Parklet        | 1/30/2017            | 2/15/2018       | APPROVED      | 5993275.5631  | 2106407.37117 | 37.7634065728777 | -122.466443284387 | 432000   | 17PKT-0012         | Parklet at ARIZMENDI BAKERY - 9TH AVE                     | Roadway               | 1/30/2017          | 2/15/2018        | 1331 09TH AVE       | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 1331 09TH AVE, San Francisco, CA 94122      | 
| 17PKT-0013    | 740 VALENCIA ST    | VALENCIA ST   | 18TH ST        | 19TH ST                | 94110          | Dandelion Chocolate                            | Parklet        | 1/31/2017            | 2/15/2018       | APPROVED      | 6006197.25247 | 2105252.74224 | 37.7609733804633 | -122.421669254993 | 13064000 | 17PKT-0013         | Parklet at Dandelion Chocolate                            | Roadway               | 1/31/2017          | 2/15/2018        | 740 VALENCIA ST     | No Excavation                     | Parking                    | Sidewalks                     | Maintenance          | Point                 | 740 VALENCIA ST, San Francisco, CA 94110    | 
```