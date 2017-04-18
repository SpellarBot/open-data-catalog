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
| Publication Date | 2017-04-14T20:34:08Z |

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
| No       |                | latest_action_date           | Latest Action Date           | text          | text          |
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
Excluded Fields = latest_action_date,paid,fully_paid,plan_assigned_date,approved,fully_permitted,dobrundate
```

## Data Commands

```ls
series e:nyis-y4yr d:2013-04-25T00:00:00.000Z t:text_on_sign="THE UPS STORE(LOGO)" t:other=X t:zip_code=10012 t:owner_s_house_=430 t:street_name="MURRAY STREET" t:sign_type=WALL t:sign_changeable_copy=N t:owner_s_house_street="WEST BROADWAY" t:state=NY t:block=00124 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:fee_status=STANDARD t:building_type=OTHER t:job_status=R t:bin_=1001400 t:applicant_s_first_name=SOL t:other_description=SIGN t:city="NEW YORK" t:professional_cert=Y t:sign_illumination_type=D t:job_type=SG t:house_=14 t:applicant_professional_title=RA t:sign_advertising=BUSINESS t:doc_=01 t:owner_type=03 t:owner_s_first_name=JASON t:inside_building_line=Y t:owner_s_last_name=LABOZ t:special_dist_name=LM t:zoning_distr_1=C6-4 t:borough=MANHATTAN t:sign_near_park=N t:efiling_filed=Y t:applicant_license_=009114 t:community__board=101 t:job_=121601640 t:applicant_s_last_name=NIEGO t:lot=00007 t:sign_illumination=Y t:owner_s_phone_=2124317500 t:job_description="ERECT AN ILLUMINATED BUSINESS ACCESSORY WALL SIGN. NO CHANGE IN USE, EGRESS, OR  OCCUPANCY." m:sign_dist_from_highway=0 m:initial_cost=3861 m:sign_height_curb=144 m:total_est_fee=120 m:sign_weight=0 m:sign_sq_footage=33 m:sign_height_roof=0 m:sign_dist_from_park=0 m:sign_projection=0

series e:nyis-y4yr d:2013-04-25T00:00:00.000Z t:text_on_sign="YOUR 1ST STOP FOR SAVING?" t:other=X t:zip_code=11216 t:owner_s_house_=774 t:street_name="CLARKSON AVENUE" t:sign_type=WALL t:sign_changeable_copy=N t:owner_s_house_street=BROADWAY t:state=NY t:block=05066 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:building_type=OTHER t:job_status=R t:fee_status=STANDARD t:bin_=3116264 t:applicant_s_first_name=ERIK t:other_description=SIGN t:city=BROOKLYN t:professional_cert=Y t:job_type=SG t:house_=210 t:applicant_professional_title=RA t:sign_advertising=BUSINESS t:doc_=01 t:owner_type=01 t:owner_s_first_name=ALBERT t:inside_building_line=Y t:owner_s_last_name=SROUR t:zoning_distr_1=R7-1 t:borough=BROOKLYN t:sign_near_park=N t:efiling_filed=Y t:applicant_license_=032438 t:community__board=317 t:job_=320588734 t:applicant_s_last_name=BJORNEBY t:lot=00011 t:owner_s_phone_=7183889526 t:job_description="ERECT NON-ILLUMINATED NON-ADVERTISING SIGN ON WALL.  NOT WITHIN VIEW OF AN       ARTERIAL HIGHWAY OR PUBLIC PARK.  NO CHANGE IN USE, EGRESS OR OCCUPANCY." m:sign_dist_from_highway=0 m:initial_cost=2300 m:sign_height_curb=162 m:total_est_fee=100 m:sign_weight=0 m:sign_sq_footage=35 m:sign_height_roof=0 m:sign_dist_from_park=0 m:sign_projection=0

series e:nyis-y4yr d:2013-04-25T00:00:00.000Z t:text_on_sign="U.S. POLO ASSN. SINCE 1890" t:other=X t:zip_code=07652 t:owner_s_house_=210 t:street_name=BROADWAY t:sign_type=WALL t:sign_changeable_copy=N t:owner_s_house_street="RTE 4 EAST" t:state=NJ t:block=00998 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:fee_status=STANDARD t:building_type=OTHER t:job_status=R t:bin_=1076844 t:applicant_s_first_name=SOL t:other_description=SIGN t:city=PARAMUS t:professional_cert=Y t:sign_illumination_type=D t:job_type=SG t:house_=1540 t:applicant_professional_title=RA t:sign_advertising=BUSINESS t:doc_=01 t:owner_type=02 t:owner_s_first_name=JAMES t:owner_s_last_name=BRY t:special_dist_name=MID t:zoning_distr_1=C6-7T t:borough=MANHATTAN t:zoning_distr_2=C6-5.5 t:sign_near_park=N t:efiling_filed=Y t:applicant_license_=009114 t:community__board=105 t:job_=121601631 t:applicant_s_last_name=NIEGO t:lot=07501 t:sign_illumination=Y t:owner_s_phone_=2015871000 t:job_description="ERECT AN ILLUMINATED BUSINESS ACCESSORY WALL SIGN. NO CHANGE IN USE, EGRESS, OR  OCCUPANCY." m:sign_dist_from_highway=0 m:initial_cost=4095 m:sign_height_curb=182 m:total_est_fee=140 m:sign_weight=0 m:sign_sq_footage=35 m:sign_height_roof=0 m:sign_dist_from_park=0 m:sign_projection=5
```

## Meta Commands

```ls
metric m:initial_cost p:float l:"Initial Cost" d:"Estimated cost of job" t:dataTypeName=number

metric m:total_est_fee p:float l:"Total Est. Fee" d:"Estimated fee of job" t:dataTypeName=number

metric m:sign_height_roof p:integer l:"Sign Height Roof" d:"Sign Height Roof" t:dataTypeName=number

metric m:sign_height_curb p:integer l:"Sign Height Curb" d:"Sign Height Curb" t:dataTypeName=number

metric m:sign_weight p:integer l:"Sign Weight" d:"Sign Weight" t:dataTypeName=number

metric m:sign_projection p:integer l:"Sign Projection" d:"Sign Projection" t:dataTypeName=number

metric m:sign_sq_footage p:integer l:"Sign SQ Footage" d:"Sign SQ Footage" t:dataTypeName=number

metric m:sign_dist_from_highway p:integer l:"Sign Dist from Highway" d:"Sign Dist from Highway" t:dataTypeName=number

metric m:sign_dist_from_park p:integer l:"Sign Dist from Park" d:"Sign Dist from Park" t:dataTypeName=number

entity e:nyis-y4yr l:"DOB Sign Application Filings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/nyis-y4yr

property e:nyis-y4yr t:meta.view v:id=nyis-y4yr v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/codes_and_reference_materials/foilmonthly.shtml#sign v:averageRating=0 v:name="DOB Sign Application Filings" v:attribution="Department of Buildings (DOB)"

property e:nyis-y4yr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nyis-y4yr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| job__     | doc__ | borough       | house__ | street_name            | block | lot   | bin__   | job_type | job_status | job_status_descrp               | latest_action_date  | building_type | community___board | landmarked | adult_estab | property_city_owned | little_e | efiling_filed | equipment | other | other_description | applicant_s_first_name | applicant_s_last_name | applicant_professional_title | applicant_license__ | professional_cert | pre_filing_date     | paid                | fully_paid          | plan_assigned_date  | approved            | fully_permitted     | initial_cost | total_est_fee | fee_status | sign_illumination | sign_illumination_type | sign_type | sign_height_roof | sign_height_curb | sign_weight | sign_projection | sign_sq_footage | sign_const_type | inside_building_line | sign_non_conforming | sign_advertising | sign_changeable_copy | sign_near_park | sign_near_highway | sign_dist_from_highway | sign_dist_from_park | sign_oac_no | sign_oac_registration | text_on_sign                                 | owner_type | non_profit | owner_s_first_name | owner_s_last_name | owner_s__house__ | owner_s__house_street | city       | state | zip_code | owner_s__phone__ | zoning_distr_1 | zoning_distr_2 | zoning_distr_3 | special_dist_name | job_description                                                                                                                                                   | dobrundate          | 
| ========= | ===== | ============= | ======= | ====================== | ===== | ===== | ======= | ======== | ========== | =============================== | =================== | ============= | ================= | ========== | =========== | =================== | ======== | ============= | ========= | ===== | ================= | ====================== | ===================== | ============================ | =================== | ================= | =================== | =================== | =================== | =================== | =================== | =================== | ============ | ============= | ========== | ================= | ====================== | ========= | ================ | ================ | =========== | =============== | =============== | =============== | ==================== | =================== | ================ | ==================== | ============== | ================= | ====================== | =================== | =========== | ===================== | ============================================ | ========== | ========== | ================== | ================= | ================ | ===================== | ========== | ===== | ======== | ================ | ============== | ============== | ============== | ================= | ================================================================================================================================================================= | =================== | 
| 121601640 | 01    | MANHATTAN     | 14      | MURRAY STREET          | 00124 | 00007 | 1001400 | SG       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 101               |            |             |                     |          | Y             |           | X     | SIGN              | SOL                    | NIEGO                 | RA                           | 009114              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 3861.00      | 120.00        | STANDARD   | Y                 | D                      | WALL      | 0                | 144              | 0           | 0               | 33              |                 | Y                    |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | THE UPS STORE(LOGO)                          | 03         |            | JASON              | LABOZ             | 430              | WEST BROADWAY         | NEW YORK   | NY    | 10012    | 2124317500       | C6-4           |                |                | LM                | ERECT AN ILLUMINATED BUSINESS ACCESSORY WALL SIGN. NO CHANGE IN USE, EGRESS, OR OCCUPANCY.                                                                        | 2013-04-26T00:00:00 | 
| 320588734 | 01    | BROOKLYN      | 210     | CLARKSON AVENUE        | 05066 | 00011 | 3116264 | SG       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 317               |            |             |                     |          | Y             |           | X     | SIGN              | ERIK                   | BJORNEBY              | RA                           | 032438              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2300.00      | 100.00        | STANDARD   |                   |                        | WALL      | 0                | 162              | 0           | 0               | 35              |                 | Y                    |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | YOUR 1ST STOP FOR SAVING?                    | 01         |            | ALBERT             | SROUR             | 774              | BROADWAY              | BROOKLYN   | NY    | 11216    | 7183889526       | R7-1           |                |                |                   | ERECT NON-ILLUMINATED NON-ADVERTISING SIGN ON WALL. NOT WITHIN VIEW OF AN ARTERIAL HIGHWAY OR PUBLIC PARK. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                 | 2013-04-26T00:00:00 | 
| 121601631 | 01    | MANHATTAN     | 1540    | BROADWAY               | 00998 | 07501 | 1076844 | SG       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 105               |            |             |                     |          | Y             |           | X     | SIGN              | SOL                    | NIEGO                 | RA                           | 009114              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 4095.00      | 140.00        | STANDARD   | Y                 | D                      | WALL      | 0                | 182              | 0           | 5               | 35              |                 |                      |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | U.S. POLO ASSN. SINCE 1890                   | 02         |            | JAMES              | BRY               | 210              | RTE 4 EAST            | PARAMUS    | NJ    | 07652    | 2015871000       | C6-7T          | C6-5.5         |                | MID               | ERECT AN ILLUMINATED BUSINESS ACCESSORY WALL SIGN. NO CHANGE IN USE, EGRESS, OR OCCUPANCY.                                                                        | 2013-04-26T00:00:00 | 
| 520129272 | 01    | STATEN ISLAND | 4106    | HYLAN BOULEVARD        | 05307 | 00006 | 5146811 | SG       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 503               |            |             |                     |          | Y             |           | X     | SIGN              | MICHAEL                | FASNACHT              | PE                           | 057352              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 4212.00      | 140.00        | STANDARD   | Y                 | D                      | WALL      | 0                | 162              | 0           | 0               | 36              |                 | Y                    |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | M&T BANK WITH LOGO                           | 03         |            | MICHAEL            | VITARELLI         | 144              | 21ST STREET           | BROOKLYN   | NY    | 11232    | 7183693434       | R3-1           |                |                |                   | ERECT ILLUMINATED ACCESSORY BUSINESS SIGN ON WALL. NOT WITHIN VIEW OF ARTERIAL HIGHWAY OR PUBLIC PARK 1/2 ACRE OR MORE.NO CHANGE IN USE, EGRESS OR OCCUPANCY.     | 2013-04-26T00:00:00 | 
| 320575695 | 01    | BROOKLYN      | 4902    | KINGS HIGHWAY          | 07733 | 00008 | 3213511 | SG       | D          | APPLICATION PROCESSED - ENTIRE  | 04/25/2013 00:00:00 | OTHER         | 318               |            |             |                     |          | Y             |           | X     | SIGN              | ROBERT                 | SCHWARTZ              | RA                           | 015049              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     |                     |                     | 12000.00     | 247.10        | STANDARD   |                   |                        | GROUND    | 0                | 660              | 0           | 0               | 237             |                 | Y                    |                     | ADVERTISING      | Y                    | N              |                   | 0                      | 0                   |             | 1018                  |                                              | 01         |            | PETER              | COSTANZA          | 437              | 5 AVENUE              | NEW YORK   | NY    | 10016    | 2126446147       | M1-1           |                |                |                   | NON-ILLUMINATED ADVERTISING GROUND SIGN #2 (10.4' X 22.75') DESIGNED FOR CHANGEABLE COPY. ALL AS PER PLANS FILED HEREWITH.                                        | 2013-04-26T00:00:00 | 
| 320575720 | 01    | BROOKLYN      | 4902    | KINGS HIGHWAY          | 07733 | 00008 | 3213511 | SG       | D          | APPLICATION PROCESSED - ENTIRE  | 04/25/2013 00:00:00 | OTHER         | 318               |            |             |                     |          | Y             |           | X     | SIGN              | ROBERT                 | SCHWARTZ              | RA                           | 015049              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     |                     |                     | 12000.00     | 247.10        | STANDARD   |                   |                        | GROUND    | 0                | 510              | 0           | 0               | 237             |                 | Y                    |                     | ADVERTISING      | Y                    | N              |                   | 0                      | 0                   |             | 1018                  |                                              | 01         |            | PETER              | COSTANZA          | 437              | 5 AVENUE              | NEW YORK   | NY    | 10016    | 2126446147       | M1-1           |                |                |                   | NON-ILLUMINATED ADVERTISING GROUND SIGN #4 (10.4' X 22.75') DESIGNED FOR CHANGEABLE COPY. ALL AS PER PLANS FILED HEREWITH.                                        | 2013-04-26T00:00:00 | 
| 220286367 | 01    | BRONX         | 122     | WESTCHESTER SQUARE     | 03859 | 00011 | 2027311 | SG       | P          | PLAN EXAM - APPROVED            | 04/25/2013 00:00:00 | OTHER         | 210               |            |             |                     |          | Y             |           |       |                   | JUNG                   | CHOI                  | RA                           | 031839              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     | 2013-04-25T00:00:00 |                     | 1638.00      | 100.00        | STANDARD   | Y                 | D                      | WALL      | 0                | 180              | 0           | 6               | 14              |                 |                      |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | VERIZON WIRELESS                             | 02         |            | RAM                | GUPTA             | 2123             | WILLIAMSBRIDGE ROAD   | BRONX      | NY    | 10461    | 7188245001       | R6             |                |                |                   | INSTALLATION OF AN ILLUMINATED SIGN. NO CHANGE IN USE, EGRESS OR CERTIFICATE OF OCCUPANCY.                                                                        | 2013-04-26T00:00:00 | 
| 121541322 | 01    | MANHATTAN     | 51      | EAST 97 STREET         | 01603 | 00020 | 1051462 | SG       | P          | PLAN EXAM - APPROVED            | 04/25/2013 00:00:00 | OTHER         | 111               |            |             |                     |          | Y             |           | X     | SIGNS             | JOHN                   | CAPAZZI               | RA                           | 310491              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     | 2013-04-25T00:00:00 |                     | 100.00       | 100.00        | STANDARD   |                   |                        | WALL      | 0                | 116              | 0           | 18              | 3               |                 |                      |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | LE PAIN QUOTIDIEN (LOGO AND RELATED WORDING) | 02         |            | THOMAS             | AHN               | 1249             | PARK AVENUE           | NEW YORK   | NY    | 10029    | 2123691207       | R7-2           |                |                |                   | INSTALL NON ILLUMINATED ACCESSORY BUSINESS SIGN ON THE MADISON AVENUE SIDE OF BUILDING.(LE PAIN QUOTIDIEN) NO CHANGE TO USE, EGRESS OR OCCPANCY IS INVOLVED.      | 2013-04-26T00:00:00 | 
| 121600286 | 01    | MANHATTAN     | 1290    | AVENUE OF THE AMERICAS | 01267 | 00001 | 1034510 | SG       | P          | PLAN EXAM - APPROVED            | 04/25/2013 00:00:00 | OTHER         | 105               |            |             |                     |          | Y             |           | X     | SIGN              | JOSEPH                 | DEAL                  | PE                           | 087122              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 |                     | 2013-04-25T00:00:00 |                     | 396.00       | 100.00        | STANDARD   |                   |                        | WALL      | 0                | 144              | 0           | 0               | 9               |                 | Y                    |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | OPEN 7 DAYS                                  | 01         |            | ROBERT             | WALSH             | 12000            | HORIZON WAY           | MT. LAUREL | NJ    | 08054    | 6319622813       | C5-2.5         | C5-3           |                | MID               | FILING HEREWITH SIGN APPLICATION FOR THE INSTALLATION OF A 8.75SF WALL SIGN. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                               | 2013-04-26T00:00:00 | 
| 520129254 | 01    | STATEN ISLAND | 4106    | HYLAN BOULEVARD        | 05307 | 00006 | 5146811 | SG       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 503               |            |             |                     |          | Y             |           | X     | SIGN              | MICHAEL                | FASNACHT              | PE                           | 057352              | Y                 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 2013-04-25T00:00:00 | 528.00       | 100.00        | STANDARD   |                   |                        | WALL      | 0                | 141              | 0           | 0               | 12              |                 | Y                    |                     | BUSINESS         | N                    | N              |                   | 0                      | 0                   |             |                       | M&T BANK WITH LOGO                           | 03         |            | MICHAEL            | VITARELLI         | 144              | 21ST STREET           | BROOKLYN   | NY    | 11232    | 7183693434       | R3-1           |                |                |                   | ERECT NON-ILLUMINATED ACCESSORY BUSINESS SIGN ON WALL. NOT WITHIN VIEW OF ARTERIAL HIGHWAY OR PUBLIC PARK 1/2 ACRE OR MORE.NO CHANGE IN USE, EGRESS OR OCCUPANCY. | 2013-04-26T00:00:00 | 
```