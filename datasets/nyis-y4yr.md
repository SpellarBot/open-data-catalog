# DOB Sign Application Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-sign-application-filings-bb06d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nyis-y4yr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nyis-y4yr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nyis-y4yr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nyis-y4yr |
| Name | DOB Sign Application Filings |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | signs, dob, buildings |
| Created | 2013-04-18T15:18:57Z |
| Publication Date | 2017-03-09T22:19:01Z |
| Rows Updated | 2017-03-09T22:18:45Z |

## Description

A list of sign applications filed for a particular day and associated data. Prior monthly reports are archived at DOB and are not available on NYC Open Data.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | job__                        | Job #                        | text          | text          |
| Yes      | series tag     | doc__                        | Doc #                        | text          | text          |
| Yes      | series tag     | borough                      | Borough                      | text          | text          |
| Yes      | series tag     | house__                      | House #                      | text          | text          |
| Yes      | series tag     | street_name                  | Street Name                  | text          | text          |
| Yes      | series tag     | block                        | Block                        | text          | text          |
| Yes      | series tag     | lot                          | Lot                          | text          | text          |
| Yes      | series tag     | bin__                        | Bin #                        | text          | text          |
| Yes      | series tag     | job_type                     | Job Type                     | text          | text          |
| Yes      | series tag     | job_status                   | Job Status                   | text          | text          |
| Yes      | series tag     | job_status_descrp            | Job Status Descrp            | text          | text          |
| Yes      | series tag     | latest_action_date           | Latest Action Date           | text          | text          |
| Yes      | series tag     | building_type                | Building Type                | text          | text          |
| Yes      | series tag     | community___board            | Community - Board            | text          | text          |
| Yes      | series tag     | landmarked                   | Landmarked                   | text          | text          |
| Yes      | series tag     | adult_estab                  | Adult Estab                  | text          | text          |
| Yes      | series tag     | property_city_owned          | Property City Owned          | text          | text          |
| Yes      | series tag     | little_e                     | Little e                     | text          | text          |
| Yes      | series tag     | efiling_filed                | eFiling Filed                | text          | text          |
| Yes      | series tag     | equipment                    | Equipment                    | text          | text          |
| Yes      | series tag     | other                        | Other                        | text          | text          |
| Yes      | series tag     | other_description            | Other Description            | text          | text          |
| Yes      | series tag     | applicant_s_first_name       | Applicant's First Name       | text          | text          |
| Yes      | series tag     | applicant_s_last_name        | Applicant's Last Name        | text          | text          |
| Yes      | series tag     | applicant_professional_title | Applicant Professional Title | text          | text          |
| Yes      | series tag     | applicant_license__          | Applicant License #          | text          | text          |
| Yes      | series tag     | professional_cert            | Professional Cert            | text          | text          |
| Yes      | time           | pre_filing_date              | Pre- Filing Date             | calendar_date | calendar_date |
| No       |                | paid                         | Paid                         | calendar_date | calendar_date |
| No       |                | fully_paid                   | Fully Paid                   | calendar_date | calendar_date |
| No       |                | plan_assigned_date           | Plan Assigned Date           | calendar_date | calendar_date |
| No       |                | approved                     | Approved                     | calendar_date | calendar_date |
| No       |                | fully_permitted              | Fully Permitted              | calendar_date | calendar_date |
| Yes      | numeric metric | initial_cost                 | Initial Cost                 | number        | number        |
| Yes      | numeric metric | total_est_fee                | Total Est. Fee               | number        | number        |
| Yes      | series tag     | fee_status                   | Fee Status                   | text          | text          |
| Yes      | series tag     | sign_illumination            | Sign Illumination            | text          | text          |
| Yes      | series tag     | sign_illumination_type       | Sign Illumination Type       | text          | text          |
| Yes      | series tag     | sign_type                    | Sign Type                    | text          | text          |
| Yes      | numeric metric | sign_height_roof             | Sign Height Roof             | number        | number        |
| Yes      | numeric metric | sign_height_curb             | Sign Height Curb             | number        | number        |
| Yes      | numeric metric | sign_weight                  | Sign Weight                  | number        | number        |
| Yes      | numeric metric | sign_projection              | Sign Projection              | number        | number        |
| Yes      | numeric metric | sign_sq_footage              | Sign SQ Footage              | number        | number        |
| Yes      | series tag     | sign_const_type              | Sign Const Type              | text          | text          |
| Yes      | series tag     | inside_building_line         | Inside Building Line         | text          | text          |
| Yes      | series tag     | sign_non_conforming          | Sign Non-Conforming          | text          | text          |
| Yes      | series tag     | sign_advertising             | Sign Advertising             | text          | text          |
| Yes      | series tag     | sign_changeable_copy         | Sign Changeable Copy         | text          | text          |
| Yes      | series tag     | sign_near_park               | Sign Near Park               | text          | text          |
| Yes      | series tag     | sign_near_highway            | Sign Near Highway            | text          | text          |
| Yes      | numeric metric | sign_dist_from_highway       | Sign Dist from Highway       | number        | number        |
| Yes      | numeric metric | sign_dist_from_park          | Sign Dist from Park          | number        | number        |
| Yes      | series tag     | sign_oac_no                  | Sign OAC No                  | text          | text          |
| Yes      | series tag     | sign_oac_registration        | Sign OAC Registration        | text          | text          |
| Yes      | series tag     | text_on_sign                 | Text on Sign                 | text          | text          |
| Yes      | series tag     | owner_type                   | Owner Type                   | text          | text          |
| Yes      | series tag     | non_profit                   | Non-Profit                   | text          | text          |
| Yes      | series tag     | owner_s_first_name           | Owner's First Name           | text          | text          |
| Yes      | series tag     | owner_s_last_name            | Owner's Last Name            | text          | text          |
| Yes      | series tag     | owner_s__house__             | Owner's House #              | text          | text          |
| Yes      | series tag     | owner_s__house_street        | Owner's House Street         | text          | text          |
| Yes      | series tag     | city                         | City                         | text          | text          |
| Yes      | series tag     | state                        | State                        | text          | text          |
| Yes      | series tag     | zip_code                     | Zip Code                     | text          | text          |
| Yes      | series tag     | owner_s__phone__             | Owner's Phone #              | text          | text          |
| Yes      | series tag     | zoning_distr_1               | Zoning Distr 1               | text          | text          |
| Yes      | series tag     | zoning_distr_2               | Zoning Distr 2               | text          | text          |
| Yes      | series tag     | zoning_distr_3               | Zoning Distr 3               | text          | text          |
| Yes      | series tag     | special_dist_name            | Special Dist Name            | text          | text          |
| Yes      | series tag     | job_description              | Job Description              | text          | text          |
| No       |                | dobrundate                   | DOBRunDate                   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = pre_filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = approved,plan_assigned_date,paid,dobrundate,fully_permitted,fully_paid
```

## Data Commands

```ls
series e:nyis-y4yr d:2013-04-25T00:00:00.000Z t:text_on_sign="THE UPS STORE(LOGO)" t:other=X t:zip_code=10012 t:owner_s_house_=430 t:street_name="MURRAY STREET" t:sign_type=WALL t:sign_changeable_copy=N t:owner_s_house_street="WEST BROADWAY" t:state=NY t:block=00124 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:fee_status=STANDARD t:building_type=OTHER t:job_status=R t:bin_=1001400 t:applicant_s_first_name=SOL t:other_description=SIGN t:latest_action_date="04/25/2013 00:00:00" t:city="NEW YORK" t:professional_cert=Y t:sign_illumination_type=D t:job_type=SG t:house_=14 t:applicant_professional_title=RA t:sign_advertising=BUSINESS t:doc_=01 t:owner_type=03 t:owner_s_first_name=JASON t:inside_building_line=Y t:owner_s_last_name=LABOZ t:special_dist_name=LM t:zoning_distr_1=C6-4 t:borough=MANHATTAN t:sign_near_park=N t:efiling_filed=Y t:applicant_license_=009114 t:community__board=101 t:job_=121601640 t:applicant_s_last_name=NIEGO t:lot=00007 t:sign_illumination=Y t:owner_s_phone_=2124317500 t:job_description="ERECT AN ILLUMINATED BUSINESS ACCESSORY WALL SIGN. NO CHANGE IN USE, EGRESS, OR  OCCUPANCY." m:sign_dist_from_highway=0 m:initial_cost=3861 m:sign_height_curb=144 m:total_est_fee=120 m:sign_weight=0 m:sign_sq_footage=33 m:sign_height_roof=0 m:sign_dist_from_park=0 m:sign_projection=0

series e:nyis-y4yr d:2013-04-25T00:00:00.000Z t:text_on_sign="YOUR 1ST STOP FOR SAVING?" t:other=X t:zip_code=11216 t:owner_s_house_=774 t:street_name="CLARKSON AVENUE" t:sign_type=WALL t:sign_changeable_copy=N t:owner_s_house_street=BROADWAY t:state=NY t:block=05066 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:building_type=OTHER t:job_status=R t:fee_status=STANDARD t:bin_=3116264 t:applicant_s_first_name=ERIK t:other_description=SIGN t:latest_action_date="04/25/2013 00:00:00" t:city=BROOKLYN t:professional_cert=Y t:job_type=SG t:house_=210 t:applicant_professional_title=RA t:sign_advertising=BUSINESS t:doc_=01 t:owner_type=01 t:owner_s_first_name=ALBERT t:inside_building_line=Y t:owner_s_last_name=SROUR t:zoning_distr_1=R7-1 t:borough=BROOKLYN t:sign_near_park=N t:efiling_filed=Y t:applicant_license_=032438 t:community__board=317 t:job_=320588734 t:applicant_s_last_name=BJORNEBY t:lot=00011 t:owner_s_phone_=7183889526 t:job_description="ERECT NON-ILLUMINATED NON-ADVERTISING SIGN ON WALL.  NOT WITHIN VIEW OF AN       ARTERIAL HIGHWAY OR PUBLIC PARK.  NO CHANGE IN USE, EGRESS OR OCCUPANCY." m:sign_dist_from_highway=0 m:initial_cost=2300 m:sign_height_curb=162 m:total_est_fee=100 m:sign_weight=0 m:sign_sq_footage=35 m:sign_height_roof=0 m:sign_dist_from_park=0 m:sign_projection=0

series e:nyis-y4yr d:2013-04-25T00:00:00.000Z t:text_on_sign="U.S. POLO ASSN. SINCE 1890" t:other=X t:zip_code=07652 t:owner_s_house_=210 t:street_name=BROADWAY t:sign_type=WALL t:sign_changeable_copy=N t:owner_s_house_street="RTE 4 EAST" t:state=NJ t:block=00998 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:fee_status=STANDARD t:building_type=OTHER t:job_status=R t:bin_=1076844 t:applicant_s_first_name=SOL t:other_description=SIGN t:latest_action_date="04/25/2013 00:00:00" t:city=PARAMUS t:professional_cert=Y t:sign_illumination_type=D t:job_type=SG t:house_=1540 t:applicant_professional_title=RA t:sign_advertising=BUSINESS t:doc_=01 t:owner_type=02 t:owner_s_first_name=JAMES t:owner_s_last_name=BRY t:special_dist_name=MID t:zoning_distr_1=C6-7T t:borough=MANHATTAN t:zoning_distr_2=C6-5.5 t:sign_near_park=N t:efiling_filed=Y t:applicant_license_=009114 t:community__board=105 t:job_=121601631 t:applicant_s_last_name=NIEGO t:lot=07501 t:sign_illumination=Y t:owner_s_phone_=2015871000 t:job_description="ERECT AN ILLUMINATED BUSINESS ACCESSORY WALL SIGN. NO CHANGE IN USE, EGRESS, OR  OCCUPANCY." m:sign_dist_from_highway=0 m:initial_cost=4095 m:sign_height_curb=182 m:total_est_fee=140 m:sign_weight=0 m:sign_sq_footage=35 m:sign_height_roof=0 m:sign_dist_from_park=0 m:sign_projection=5
```

## Meta Commands

```ls
metric m:initial_cost l:"Initial Cost" d:"Estimated cost of job" t:dataTypeName=number

metric m:total_est_fee l:"Total Est. Fee" d:"Estimated fee of job" t:dataTypeName=number

metric m:sign_height_roof l:"Sign Height Roof" d:"Sign Height Roof" t:dataTypeName=number

metric m:sign_height_curb l:"Sign Height Curb" d:"Sign Height Curb" t:dataTypeName=number

metric m:sign_weight l:"Sign Weight" d:"Sign Weight" t:dataTypeName=number

metric m:sign_projection l:"Sign Projection" d:"Sign Projection" t:dataTypeName=number

metric m:sign_sq_footage l:"Sign SQ Footage" d:"Sign SQ Footage" t:dataTypeName=number

metric m:sign_dist_from_highway l:"Sign Dist from Highway" d:"Sign Dist from Highway" t:dataTypeName=number

metric m:sign_dist_from_park l:"Sign Dist from Park" d:"Sign Dist from Park" t:dataTypeName=number

entity e:nyis-y4yr l:"DOB Sign Application Filings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/nyis-y4yr

property e:nyis-y4yr t:meta.view d:2017-03-10T14:30:31.400Z v:id=nyis-y4yr v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/codes_and_reference_materials/foilmonthly.shtml#sign v:averageRating=0 v:name="DOB Sign Application Filings" v:attribution="Department of Buildings (DOB)"

property e:nyis-y4yr t:meta.view.owner d:2017-03-10T14:30:31.400Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:nyis-y4yr t:meta.view.tableauthor d:2017-03-10T14:30:31.400Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```