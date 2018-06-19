# DOB Cellular Antenna Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-cellular-antenna-filings-72123) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/iz2q-9x8d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/iz2q-9x8d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/iz2q-9x8d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | iz2q-9x8d |
| Name | DOB Cellular Antenna Filings |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | cellular antenna, dob, buildings |
| Created | 2013-04-18T15:19:14Z |
| Publication Date | 2017-04-20T20:04:50Z |

## Description

A list of cellular antenna filings and associated data. Prior weekly reports are archived at DOB and are not available on NYC Open Data.

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
| Yes      | series tag     | little_e                     | Little e                     | text          | text          |
| Yes      | series tag     | pc_filed                     | PC Filed                     | text          | text          |
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
| No       |                | assigned                     | Assigned                     | calendar_date | calendar_date |
| No       |                | approved                     | Approved                     | calendar_date | calendar_date |
| No       |                | fully_permitted              | Fully Permitted              | calendar_date | calendar_date |
| Yes      | numeric metric | initial_cost                 | Initial Cost                 | number        | number        |
| Yes      | numeric metric | total_est_fee                | Total Est. Fee               | number        | number        |
| Yes      | series tag     | fee_status                   | Fee Status                   | text          | text          |
| Yes      | series tag     | existing_occupancy           | Existing Occupancy           | text          | text          |
| Yes      | series tag     | proposed_occupancy           | Proposed Occupancy           | text          | text          |
| Yes      | series tag     | zoning_distr_1               | Zoning Distr 1               | text          | text          |
| Yes      | series tag     | zoning_distr_2               | Zoning Distr 2               | text          | text          |
| Yes      | series tag     | zoning_distr_3               | Zoning Distr 3               | text          | text          |
| Yes      | series tag     | special_distr_1              | Special Distr 1              | text          | text          |
| Yes      | series tag     | special_distr_2_             | Special Distr 2              | text          | text          |
| Yes      | series tag     | owner_type                   | Owner Type                   | text          | text          |
| Yes      | series tag     | owner_type_description       | Owner Type Description       | text          | text          |
| Yes      | series tag     | non_profit                   | Non-Profit                   | text          | text          |
| Yes      | series tag     | owner_s_first_name           | Owner's First Name           | text          | text          |
| Yes      | series tag     | owner_s_last_name            | Owner's Last Name            | text          | text          |
| Yes      | series tag     | owner_s_business_name        | Owner's Business Name        | text          | text          |
| Yes      | series tag     | owner_s__house__             | Owner's House #              | text          | text          |
| Yes      | series tag     | owner_s__house_street        | Owner's House Street         | text          | text          |
| Yes      | series tag     | city                         | City                         | text          | text          |
| Yes      | series tag     | state                        | State                        | text          | text          |
| Yes      | series tag     | zip_code                     | Zip Code                     | text          | text          |
| Yes      | series tag     | owner_s__phone__             | Owner's Phone #              | text          | text          |
| No       |                | first_permit_date            | First Permit Date            | calendar_date | calendar_date |
| Yes      | series tag     | job_description              | Job Description              | text          | text          |
| No       |                | dobrundate                   | DOBRunDate                   | text          | text          |
```

## Time Field

```ls
Value = pre_filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latest_action_date,paid,fully_paid,assigned,approved,fully_permitted,first_permit_date,dobrundate
```

## Data Commands

```ls
series e:iz2q-9x8d d:2013-04-03T00:00:00.000Z t:other=X t:proposed_occupancy=RES t:zip_code=10031 t:owner_s_house_=740 t:street_name="NOBLE AVENUE" t:owner_s_house_street="ST. NICHOLAS AVENUE" t:state=NY t:block=03894 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:building_type=OTHER t:job_status=R t:fee_status=STANDARD t:bin_=2028123 t:other_description=ANTENNA t:applicant_s_first_name=STEPHEN t:city="NEW YORK" t:owner_type_description=PARTNERSHIP t:job_type=A3 t:house_=1420 t:owner_s_business_name="1420 NOBLE AVE REALTY LLC C/O ED" t:applicant_professional_title=PE t:existing_occupancy=RES t:doc_=01 t:owner_type=03 t:owner_s_first_name=ADEN t:owner_s_last_name=SERAILE t:borough=2 t:zoning_distr_1=R5 t:applicant_license_=086064 t:non_profit=N t:community__board=209 t:job_=220282575 t:applicant_s_last_name=BRAY t:lot=00011 t:owner_s_phone_=2129267200 t:job_description="MODIFICATION TO EXISTING SITE. RETROFIT EXISTING AND INSTALL A NEW               TELECOMMUNICATIONS CABINET ON ROOF. REPLACE AND ADD ANTENNAS ON ROOF. ALL IN     CONFORMANCE WITH TPPN # 5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY." m:initial_cost=33100 m:total_est_fee=533.7

series e:iz2q-9x8d d:2013-01-25T00:00:00.000Z t:other=X t:proposed_occupancy=RES t:zip_code=10007 t:owner_s_house_=90 t:street_name="KISSENA BOULEVARD" t:owner_s_house_street="CHURCH STREET, 12TH FLOOR" t:state=NY t:block=06792 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:building_type=OTHER t:job_status=R t:fee_status=STANDARD t:bin_=4455435 t:other_description=ANTENNA t:applicant_s_first_name=GLEN t:city="NEW YORK" t:owner_type_description=NYCHA t:job_type=A3 t:house_=67-45 t:owner_s_business_name="NYC HOUSING AUTHORITY" t:applicant_professional_title=PE t:existing_occupancy=RES t:doc_=01 t:owner_type=08 t:owner_s_first_name=SCOTT t:owner_s_last_name=GORDON t:borough=4 t:zoning_distr_1=R6 t:applicant_license_=075376 t:non_profit=N t:community__board=408 t:job_=420803928 t:applicant_s_last_name=SCHERER t:lot=00030 t:owner_s_phone_=2123066936 t:job_description="INSTALL TELECOMMUNICATIONS ANTENNAS ON ROOF IN CONFROMANCE WITH TPPN# 5/98.      NO CHANGE IN USE, EGRESS OR OCCUPANCY. NO CHANGE IN USE, EGRESS OR OCCUPANCY." m:initial_cost=20000 m:total_est_fee=389.5

series e:iz2q-9x8d d:2013-04-09T00:00:00.000Z t:other=X t:proposed_occupancy=COM t:zip_code=11101 t:owner_s_house_=43-10 t:street_name="23 STREET" t:owner_s_house_street="23 STREET" t:state=NY t:special_distr_2_=IBZ t:block=00440 t:job_status_descrp="PERMIT ISSUED - ENTIRE JOB/WORK" t:building_type=OTHER t:job_status=R t:fee_status=STANDARD t:bin_=4005193 t:applicant_s_first_name=JAMES t:other_description=ANTENNA t:city=L.I.C. t:owner_type_description=PARTNERSHIP t:job_type=A3 t:house_=43-10 t:owner_s_business_name="KASSABIAN REALTY, LLC" t:applicant_professional_title=PE t:existing_occupancy=COM t:doc_=01 t:owner_type=03 t:owner_s_first_name=LEON t:owner_s_last_name=KASSABIAN t:borough=4 t:zoning_distr_1=M1-4 t:applicant_license_=078939 t:non_profit=N t:community__board=402 t:job_=420819430 t:applicant_s_last_name=FAHEY t:lot=00001 t:owner_s_phone_=7187847800 t:job_description="INSTALL NEW TELECOMMUNICATIONS CABINETS, RELATED DUNNAGE AND RELATED ANTENNAS ON ROOF IN CONFORMANCE WITH TPPN # 5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY." m:initial_cost=97000 m:total_est_fee=1182.6
```

## Meta Commands

```ls
metric m:initial_cost p:long l:"Initial Cost" d:"Estimated cost of job" t:dataTypeName=number

metric m:total_est_fee p:long l:"Total Est. Fee" d:"Estimated fee of job" t:dataTypeName=number

entity e:iz2q-9x8d l:"DOB Cellular Antenna Filings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/iz2q-9x8d

property e:iz2q-9x8d t:meta.view v:id=iz2q-9x8d v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/codes_and_reference_materials/weekly.shtml#cell v:averageRating=0 v:name="DOB Cellular Antenna Filings" v:attribution="Department of Buildings (DOB)"

property e:iz2q-9x8d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:iz2q-9x8d t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| job__     | doc__ | borough | house__ | street_name         | block | lot   | bin__   | job_type | job_status | job_status_descrp               | latest_action_date  | building_type | community___board | landmarked | little_e | pc_filed | other | other_description | applicant_s_first_name | applicant_s_last_name | applicant_professional_title | applicant_license__ | professional_cert | pre_filing_date     | paid                | fully_paid          | assigned            | approved            | fully_permitted     | initial_cost | total_est_fee | fee_status | existing_occupancy | proposed_occupancy | zoning_distr_1 | zoning_distr_2 | zoning_distr_3 | special_distr_1 | special_distr_2_ | owner_type | owner_type_description | non_profit | owner_s_first_name | owner_s_last_name | owner_s_business_name            | owner_s__house__ | owner_s__house_street     | city          | state | zip_code | owner_s__phone__ | first_permit_date   | job_description                                                                                                                                                                                                                                 | dobrundate          | 
| ========= | ===== | ======= | ======= | =================== | ===== | ===== | ======= | ======== | ========== | =============================== | =================== | ============= | ================= | ========== | ======== | ======== | ===== | ================= | ====================== | ===================== | ============================ | =================== | ================= | =================== | =================== | =================== | =================== | =================== | =================== | ============ | ============= | ========== | ================== | ================== | ============== | ============== | ============== | =============== | ================ | ========== | ====================== | ========== | ================== | ================= | ================================ | ================ | ========================= | ============= | ===== | ======== | ================ | =================== | =============================================================================================================================================================================================================================================== | =================== | 
| 220282575 | 01    | 2       | 1420    | NOBLE AVENUE        | 03894 | 00011 | 2028123 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 209               |            |          |          | X     | ANTENNA           | STEPHEN                | BRAY                  | PE                           | 086064              |                   | 2013-04-03T00:00:00 | 2013-04-03T00:00:00 | 2013-04-03T00:00:00 | 2013-04-05T00:00:00 | 2013-04-18T00:00:00 | 2013-04-25T00:00:00 | 33100.00     | 533.70        | STANDARD   | RES                | RES                | R5             |                |                |                 |                  | 03         | PARTNERSHIP            | N          | ADEN               | SERAILE           | 1420 NOBLE AVE REALTY LLC C/O ED | 740              | ST. NICHOLAS AVENUE       | NEW YORK      | NY    | 10031    | 2129267200       | 2013-04-25T00:00:00 | MODIFICATION TO EXISTING SITE. RETROFIT EXISTING AND INSTALL A NEW TELECOMMUNICATIONS CABINET ON ROOF. REPLACE AND ADD ANTENNAS ON ROOF. ALL IN CONFORMANCE WITH TPPN # 5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                            | 04/26/2013 00:00:00 | 
| 420803928 | 01    | 4       | 67-45   | KISSENA BOULEVARD   | 06792 | 00030 | 4455435 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 408               |            |          |          | X     | ANTENNA           | GLEN                   | SCHERER               | PE                           | 075376              |                   | 2013-01-25T00:00:00 | 2013-01-30T00:00:00 | 2013-01-30T00:00:00 | 2013-02-04T00:00:00 | 2013-02-28T00:00:00 | 2013-04-25T00:00:00 | 20000.00     | 389.50        | STANDARD   | RES                | RES                | R6             |                |                |                 |                  | 08         | NYCHA                  | N          | SCOTT              | GORDON            | NYC HOUSING AUTHORITY            | 90               | CHURCH STREET, 12TH FLOOR | NEW YORK      | NY    | 10007    | 2123066936       | 2013-04-25T00:00:00 | INSTALL TELECOMMUNICATIONS ANTENNAS ON ROOF IN CONFROMANCE WITH TPPN# 5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                                                                       | 04/26/2013 00:00:00 | 
| 420819430 | 01    | 4       | 43-10   | 23 STREET           | 00440 | 00001 | 4005193 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 04/25/2013 00:00:00 | OTHER         | 402               |            |          |          | X     | ANTENNA           | JAMES                  | FAHEY                 | PE                           | 078939              |                   | 2013-04-09T00:00:00 | 2013-04-09T00:00:00 | 2013-04-09T00:00:00 | 2013-04-10T00:00:00 | 2013-04-17T00:00:00 | 2013-04-25T00:00:00 | 97000.00     | 1182.60       | STANDARD   | COM                | COM                | M1-4           |                |                |                 | IBZ              | 03         | PARTNERSHIP            | N          | LEON               | KASSABIAN         | KASSABIAN REALTY, LLC            | 43-10            | 23 STREET                 | L.I.C.        | NY    | 11101    | 7187847800       | 2013-04-25T00:00:00 | INSTALL NEW TELECOMMUNICATIONS CABINETS, RELATED DUNNAGE AND RELATED ANTENNAS ON ROOF IN CONFORMANCE WITH TPPN # 5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                                                                   | 04/26/2013 00:00:00 | 
| 121160830 | 01    | 1       | 2       | WOOSTER STREET      | 00229 | 00006 | 1002970 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/01/2013 00:00:00 | OTHER         | 102               | Y          |          |          | X     | ANTENNA           | PETER                  | TARDY                 | PE                           | 079612              |                   | 2012-08-06T00:00:00 | 2012-08-06T00:00:00 | 2012-08-06T00:00:00 | 2012-08-08T00:00:00 | 2013-04-30T00:00:00 | 2013-05-01T00:00:00 | 30400.00     | 502.80        | STANDARD   | RES                | RES                | M1-5B          |                |                |                 |                  | 03         | PARTNERSHIP            | N          | BERNARD            | SENCER            | TUNNEL HOLDING LLC               | 2                | WOOSTER STREET            | NEW YORK      | NY    | 10013    | 2129661126       | 2013-05-01T00:00:00 | INSTALLING ADDITIONAL CABINETS ON PLATFORM ON ROOF.INSTALLING ANTENNAS ON THE ROOF. ALL WORK IS IN CONFORMANCE WITH TPPN #5/98. NO CHANGE IN USE, EGRESS, OR OCCUPANCY.                                                                         | 05/02/2013 00:00:00 | 
| 121048231 | 01    | 1       | 370     | MANHATTAN AVENUE    | 01848 | 00036 | 1055850 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/01/2013 00:00:00 | OTHER         | 110               |            |          |          | X     | ANTENNA           | STEPHEN                | BRAY                  | PE                           | 086064              |                   | 2013-01-02T00:00:00 | 2013-01-02T00:00:00 | 2013-02-20T00:00:00 | 2013-02-22T00:00:00 | 2013-04-17T00:00:00 | 2013-05-01T00:00:00 | 10000.00     | 286.50        | STANDARD   | RES                | RES                | R7A            |                |                |                 |                  | 03         | PARTNERSHIP            | N          | ROBERTO            | CIAGLIA           | T-MOBILE                         | 4                | SYLVAN WAY                | PARSIPPANY    | NJ    | 07004    | 9733924814       | 2013-05-01T00:00:00 | INSTALLATION OF ANTENNA COMPONENTS AND REINFORCEMENT OF EXISTING ANTENNAS ON ROOF. ALL WORK IN COMPLIANCE WITH TPPN #5/98. NO CHANGE TO USE, EGRESS OR OCCUPANCY.                                                                               | 05/02/2013 00:00:00 | 
| 420816166 | 01    | 4       | 36-36   | 33RD ST             | 00601 | 00001 | 4007923 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/01/2013 00:00:00 | OTHER         | 401               |            |          |          | X     | ANTENNA           | JAMES                  | FAHEY                 | PE                           | 078939              |                   | 2013-02-25T00:00:00 | 2013-02-25T00:00:00 | 2013-02-25T00:00:00 | 2013-02-27T00:00:00 | 2013-05-01T00:00:00 | 2013-05-01T00:00:00 | 77000.00     | 976.60        | STANDARD   | B-2                | B-2                | M1-2/R6A       | M1-2/R5B       |                | LIC             |                  | 03         | PARTNERSHIP            | N          | EFSTATHIOS         | VALIOTIS          | CITYVIEW PLAZA, LLC              | 31-10            | 37TH AVENUE               | LIC           | NY    | 11101    | 7182670300       | 2013-05-01T00:00:00 | INSTALL NEW TELECOMMUNICATIONS CABINETS, RELATED DUNNAGE AND RELATED ANTENNAS ON ROOF IN CONFORMANCE WITH TPPN # 5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                                                                   | 05/02/2013 00:00:00 | 
| 121391975 | 01    | 1       | 26      | JEFFERSON STREET    | 00271 | 00047 | 1003235 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/02/2013 00:00:00 | OTHER         | 103               |            |          |          | X     | ANTENNA           | LUIS                   | MOGLINO               | RA                           | 028992              |                   | 2012-09-26T00:00:00 | 2012-09-26T00:00:00 | 2012-09-26T00:00:00 | 2012-10-03T00:00:00 | 2013-04-26T00:00:00 | 2013-05-02T00:00:00 | 10000.00     | 286.50        | STANDARD   | RES                | RES                | R7-2           |                |                |                 |                  | 03         | PARTNERSHIP            | N          | KWONG              | YEUNG             | YEUNG'S BROTHER REALTY           | 14               | MONROE STREET-APT. 7A     | NEW YORK      | NY    | 10002    | 9179221212       | 2013-05-02T00:00:00 | INSTALLATION OF ANTENNA COMPONENTS AND REINFORCEMENT OF EXISTING ANTENNAS AS PER PLANS. ALL WORK IN COMPLIANCE WITH TPPN 5/98. NO CHANGE TO USE, EGRESS OR OCCUPANCY.                                                                           | 05/03/2013 00:00:00 | 
| 121378446 | 01    | 1       | 15      | MONROE STREET       | 00276 | 00007 | 1003291 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/02/2013 00:00:00 | OTHER         | 103               |            |          |          | X     | ANTENNA           | ROBERT                 | TOMS                  | PE                           | 007538              |                   | 2012-10-03T00:00:00 | 2012-10-05T00:00:00 | 2012-10-09T00:00:00 | 2012-10-10T00:00:00 | 2013-04-17T00:00:00 | 2013-05-02T00:00:00 | 19500.00     | 389.50        | STANDARD   | RES                | RES                | R7-2           |                |                |                 |                  | 03         | PARTNERSHIP            | N          | KONG GUANG         | WANG              | 15 MONROE REALTY INC.            | 39               | BOWERY                    | NEW YORK      | NY    | 10002    | 6463258628       | 2013-05-02T00:00:00 | INSTALLATION OF ANTENNAS COMPONENTS AND REINFORCEMENT OF EXISTING ANTENNAS AS PER PLANS. ALL WORK IN COMPLIANCE WITH TPPN 5/98. NO CHANGE TO USE, EGRESS OR OCCUPANCY.                                                                          | 05/03/2013 00:00:00 | 
| 420821542 | 01    | 4       | 7-07    | BEACH 9 STREET      | 15572 | 00001 | 4298444 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/03/2013 00:00:00 | OTHER         | 414               |            |          |          | X     | ANTENNA           | NEIL                   | MACDONALD             | RA                           | 026944              |                   | 2013-03-15T00:00:00 | 2013-03-19T00:00:00 | 2013-03-19T00:00:00 | 2013-03-20T00:00:00 | 2013-04-30T00:00:00 | 2013-05-03T00:00:00 | 25000.00     | 441.00        | STANDARD   | RES                | RES                | R5             |                |                |                 |                  | 03         | PARTNERSHIP            | N          | JOSHUA             | EISENBERG         | KINGS & QUEENS LLC               | 590              | 56TH STREET               | WEST NEW YORK | NJ    | 08741    | 2015539800       | 2013-05-03T00:00:00 | REPLACE EXISTING ANTENNAS ON ROOF IN CONFORMANCE WITH TPPN #5/98. NO CHANGE IN USE, EGRESS OR OCCUPANCY                                                                                                                                         | 05/04/2013 00:00:00 | 
| 420812197 | 01    | 4       | 38-20   | BEACH CHANNEL DRIVE | 15955 | 00003 | 4302129 | A3       | R          | PERMIT ISSUED - ENTIRE JOB/WORK | 05/03/2013 00:00:00 | OTHER         | 414               |            |          |          | X     | ANTENNA           | JOHN                   | ADELY                 | PE                           | 063658              |                   | 2013-02-11T00:00:00 | 2013-02-11T00:00:00 | 2013-02-11T00:00:00 | 2013-02-12T00:00:00 | 2013-05-02T00:00:00 | 2013-05-03T00:00:00 | 76800.00     | 976.60        | STANDARD   | RES                | RES                | R5             |                |                |                 |                  | 08         | NYCHA                  | N          | SCOTT              | GROOM             | NYCHA                            | 90               | CHURCH STREET             | NEW YORK      | NY    | 10007    | 2123065160       | 2013-05-03T00:00:00 | NEW EQUIPMENT INSTALLATION. INSTALLING TELECOMMUNICATION EXTERIOR CABINETS ON NEW STEEL PLATFORM ON ROOF. RELATED THREE SECTOR OF ANTENNAS ARE ON THE ROOF. ALL WORK IS IN CONFORMANCE WITH TPPN #5/98. NO CHANGE IN USE, EGRESS, OR OCCUPANCY. | 05/04/2013 00:00:00 | 
```