# DOB ECB Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-ecb-violations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6bgk-3dad) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6bgk-3dad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6bgk-3dad/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6bgk-3dad |
| Name | DOB ECB Violations |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | dob, buildings, violation ecb, nov |
| Created | 2015-11-24T20:49:53Z |
| Publication Date | 2015-11-24T20:51:43Z |

## Description

ECB Violations ? A list of active ECB violations.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | numeric metric | isn_dob_bis_extract       | ISN_DOB_BIS_EXTRACT       | number    | text        |
| Yes      | series tag     | ecb_violation_number      | ECB_VIOLATION_NUMBER      | text      | text        |
| Yes      | series tag     | ecb_violation_status      | ECB_VIOLATION_STATUS      | text      | text        |
| Yes      | series tag     | dob_violation_number      | DOB_VIOLATION_NUMBER      | text      | text        |
| Yes      | series tag     | bin                       | BIN                       | text      | text        |
| Yes      | numeric metric | boro                      | BORO                      | number    | text        |
| Yes      | series tag     | block                     | BLOCK                     | text      | text        |
| Yes      | series tag     | lot                       | LOT                       | text      | text        |
| No       |                | hearing_date              | HEARING_DATE              | text      | text        |
| No       |                | hearing_time              | HEARING_TIME              | number    | text        |
| No       |                | served_date               | SERVED_DATE               | text      | text        |
| Yes      | time           | issue_date                | ISSUE_DATE                | text      | text        |
| Yes      | series tag     | severity                  | SEVERITY                  | text      | text        |
| Yes      | series tag     | violation_type            | VIOLATION_TYPE            | text      | text        |
| Yes      | series tag     | respondent_name           | RESPONDENT_NAME           | text      | text        |
| Yes      | series tag     | respondent_house_number   | RESPONDENT_HOUSE_NUMBER   | text      | text        |
| Yes      | series tag     | respondent_street         | RESPONDENT_STREET         | text      | text        |
| Yes      | series tag     | respondent_city           | RESPONDENT_CITY           | text      | text        |
| Yes      | series tag     | respondent_zip            | RESPONDENT_ZIP            | text      | text        |
| Yes      | series tag     | violation_description     | VIOLATION_DESCRIPTION     | text      | text        |
| Yes      | numeric metric | penality_imposed          | PENALITY_IMPOSED          | number    | text        |
| Yes      | series tag     | amount_paid               | AMOUNT_PAID               | text      | text        |
| Yes      | numeric metric | balance_due               | BALANCE_DUE               | number    | text        |
| Yes      | series tag     | infraction_code1          | INFRACTION_CODE1          | text      | text        |
| Yes      | series tag     | section_law_description1  | SECTION_LAW_DESCRIPTION1  | text      | text        |
| Yes      | series tag     | infraction_code2          | INFRACTION_CODE2          | text      | text        |
| Yes      | series tag     | section_law_description2  | SECTION_LAW_DESCRIPTION2  | text      | text        |
| Yes      | series tag     | infraction_code3          | INFRACTION_CODE3          | text      | text        |
| Yes      | series tag     | section_law_description3  | SECTION_LAW_DESCRIPTION3  | text      | text        |
| Yes      | series tag     | infraction_code4          | INFRACTION_CODE4          | text      | text        |
| Yes      | series tag     | section_law_description4  | SECTION_LAW_DESCRIPTION4  | text      | text        |
| Yes      | series tag     | infraction_code5          | INFRACTION_CODE5          | text      | text        |
| Yes      | series tag     | section_law_description5  | SECTION_LAW_DESCRIPTION5  | text      | text        |
| Yes      | series tag     | infraction_code6          | INFRACTION_CODE6          | text      | text        |
| Yes      | series tag     | section_law_description6  | SECTION_LAW_DESCRIPTION6  | text      | text        |
| Yes      | series tag     | infraction_code7          | INFRACTION_CODE7          | text      | text        |
| Yes      | series tag     | section_law_description7  | SECTION_LAW_DESCRIPTION7  | text      | text        |
| Yes      | series tag     | infraction_code8          | INFRACTION_CODE8          | text      | text        |
| Yes      | series tag     | section_law_description8  | SECTION_LAW_DESCRIPTION8  | text      | text        |
| Yes      | series tag     | infraction_code9          | INFRACTION_CODE9          | text      | text        |
| Yes      | series tag     | section_law_description9  | SECTION_LAW_DESCRIPTION9  | text      | text        |
| Yes      | series tag     | infraction_code10         | INFRACTION_CODE10         | text      | text        |
| Yes      | series tag     | section_law_description10 | SECTION_LAW_DESCRIPTION10 | text      | text        |
| Yes      | series tag     | aggravated_level          | AGGRAVATED_LEVEL          | text      | text        |
| Yes      | series tag     | hearing_status            | HEARING_STATUS            | text      | text        |
| Yes      | series tag     | certification_status      | CERTIFICATION_STATUS      | text      | text        |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = hearing_date,hearing_time,served_date
```

## Data Commands

```ls
series e:6bgk-3dad d:2010-01-29T00:00:00.000Z t:ecb_violation_status=RESOLVE t:section_law_description1="AC 28-204.4                                                                 FAIL TO COMPLY W/COMMISSIONER ORDER TO FILE CERT OF CORRECTION W/DOB" t:respondent_house_number=1920 t:respondent_street="HARMAN STREET" t:hearing_status=DEFAULT t:block=03388 t:severity=Unknown t:violation_description="FAILURE TO COMPLY EITH COMM ORDER TO FILE A CERT OF CORRECTION WITH THE DEPT OF BLDGS.NOTED:RESPONDENT FAILED TO COMPLY WITH THE COMMISSIONERS ORDER TO CORRECT THE VIOLATIING CONDITONS AND FILE A CERT OF CORR" t:dob_violation_number=012910STFJH04 t:respondent_zip=11385 t:amount_paid=937.89 t:violation_type=Unknown t:ecb_violation_number=34830294Z t:respondent_city=FLUSHING t:respondent_name="THE HARMAN GROUP" t:aggravated_level=NO t:lot=0022 t:infraction_code1=263 t:bin=4080791 t:certification_status="CERTIFICATE ACCEPTED" m:boro=4 m:penality_imposed=4000 m:balance_due=0 m:isn_dob_bis_extract=758705

series e:6bgk-3dad d:2005-02-28T00:00:00.000Z t:ecb_violation_status=RESOLVE t:section_law_description1="27-987                                                                      FAILURE TO MAINTAIN ELEVATOR" t:respondent_house_number=4 t:respondent_street="NEW YORK PLAZA" t:hearing_status=CURED/IN-VIO t:block=00033 t:severity=Non-Hazardous t:violation_description="51O02 (51) HOIST ROPES DIRTY, CLEAN FOR PROPER INSPECTION." t:dob_violation_number=022805E2171A3 t:respondent_zip=10004 t:amount_paid=.00 t:violation_type=Elevators t:ecb_violation_number=38151068L t:respondent_city=NY t:respondent_name="CUSHMAN AND WAKEFIELD" t:lot=00011 t:infraction_code1=BP7 t:bin=1000864 t:certification_status="CURE ACCEPTED" m:boro=1 m:penality_imposed=0 m:balance_due=0 m:isn_dob_bis_extract=486151

series e:6bgk-3dad d:2009-05-26T00:00:00.000Z t:ecb_violation_status=RESOLVE t:section_law_description1="28-301.1                                                                    FAILURE TO MAINTAIN BUILDING IN CODE COMPLIANT MANNER: SERVICE EQUIPME" t:respondent_house_number=696 t:respondent_street="EAST  141 STREET" t:hearing_status="IN VIOLATION" t:block=02568 t:severity=Unknown t:violation_description="97X10.97X10 IRCNY 11-02 ONLY ELEVATOR IN BLDG OUT OF SERVICE RESTORE  TO SERVICE. HAZARDOUS" t:dob_violation_number=052609E2178B01 t:respondent_zip=10454 t:amount_paid=1000.00 t:violation_type=Elevators t:ecb_violation_number=38203404N t:respondent_city=NY t:respondent_name="DIEGO BEEKMAN MUTAL HOUSI" t:aggravated_level=NO t:lot=0057 t:infraction_code1=151 t:bin=2003818 t:certification_status="CERTIFICATE ACCEPTED" m:boro=2 m:penality_imposed=5000 m:balance_due=0 m:isn_dob_bis_extract=453910
```

## Meta Commands

```ls
metric m:isn_dob_bis_extract p:integer l:ISN_DOB_BIS_EXTRACT t:dataTypeName=number

metric m:boro p:integer l:BORO t:dataTypeName=number

metric m:penality_imposed p:float l:PENALITY_IMPOSED t:dataTypeName=number

metric m:balance_due p:float l:BALANCE_DUE t:dataTypeName=number

entity e:6bgk-3dad l:"DOB ECB Violations" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/6bgk-3dad

property e:6bgk-3dad t:meta.view v:id=6bgk-3dad v:category="Housing & Development" v:averageRating=0 v:name="DOB ECB Violations" v:attribution="Department of Buildings (DOB)"

property e:6bgk-3dad t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6bgk-3dad t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| isn_dob_bis_extract | ecb_violation_number | ecb_violation_status | dob_violation_number | bin     | boro | block | lot   | hearing_date | hearing_time | served_date | issue_date | severity      | violation_type  | respondent_name           | respondent_house_number | respondent_street | respondent_city | respondent_zip | violation_description                                                                                                                                                                                              | penality_imposed | amount_paid | balance_due | infraction_code1 | section_law_description1                                                         | infraction_code2 | section_law_description2 | infraction_code3 | section_law_description3 | infraction_code4 | section_law_description4 | infraction_code5 | section_law_description5 | infraction_code6 | section_law_description6 | infraction_code7 | section_law_description7 | infraction_code8 | section_law_description8 | infraction_code9 | section_law_description9 | infraction_code10 | section_law_description10 | aggravated_level | hearing_status | certification_status | 
| =================== | ==================== | ==================== | ==================== | ======= | ==== | ===== | ===== | ============ | ============ | =========== | ========== | ============= | =============== | ========================= | ======================= | ================= | =============== | ============== | ================================================================================================================================================================================================================== | ================ | =========== | =========== | ================ | ================================================================================ | ================ | ======================== | ================ | ======================== | ================ | ======================== | ================ | ======================== | ================ | ======================== | ================ | ======================== | ================ | ======================== | ================ | ======================== | ================= | ========================= | ================ | ============== | ==================== | 
| 758705              | 34830294Z            | RESOLVE              | 012910STFJH04        | 4080791 | 4    | 03388 | 0022  | 20100525     | 1030         | 20100401    | 20100129   | Unknown       | Unknown         | THE HARMAN GROUP          | 1920                    | HARMAN STREET     | FLUSHING        | 11385          | FAILURE TO COMPLY EITH COMM ORDER TO FILE A CERT OF CORRECTION WITH THE DEPT OF BLDGS.NOTED:RESPONDENT FAILED TO COMPLY WITH THE COMMISSIONERS ORDER TO CORRECT THE VIOLATIING CONDITONS AND FILE A CERT OF CORR   | 4000.00          | 937.89      | .00         | 263              | AC 28-204.4 FAIL TO COMPLY W/COMMISSIONER ORDER TO FILE CERT OF CORRECTION W/DOB |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           | NO               | DEFAULT        | CERTIFICATE ACCEPTED | 
| 486151              | 38151068L            | RESOLVE              | 022805E2171A3        | 1000864 | 1    | 00033 | 00011 | 20050414     | 1030         | 20050228    | 20050228   | Non-Hazardous | Elevators       | CUSHMAN AND WAKEFIELD     | 4                       | NEW YORK PLAZA    | NY              | 10004          | 51O02 (51) HOIST ROPES DIRTY, CLEAN FOR PROPER INSPECTION.                                                                                                                                                         | .00              | .00         | .00         | BP7              | 27-987 FAILURE TO MAINTAIN ELEVATOR                                              |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           |                  | CURED/IN-VIO   | CURE ACCEPTED        | 
| 453910              | 38203404N            | RESOLVE              | 052609E2178B01       | 2003818 | 2    | 02568 | 0057  | 20090724     | 1030         | 20090526    | 20090526   | Unknown       | Elevators       | DIEGO BEEKMAN MUTAL HOUSI | 696                     | EAST 141 STREET   | NY              | 10454          | 97X10.97X10 IRCNY 11-02 ONLY ELEVATOR IN BLDG OUT OF SERVICE RESTORE TO SERVICE. HAZARDOUS                                                                                                                         | 5000.00          | 1000.00     | .00         | 151              | 28-301.1 FAILURE TO MAINTAIN BUILDING IN CODE COMPLIANT MANNER: SERVICE EQUIPME  |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           | NO               | IN VIOLATION   | CERTIFICATE ACCEPTED | 
| 534749              | 34650064P            | RESOLVE              | 052208C3TM02         | 1004967 | 1    | 00398 | 0018  | 20100617     | 900          | 20080527    | 20080527   | Non-Hazardous | Construction    | 176 EAST 3RD REALTY LLC   | 176                     | EAST 3 STREET     | NY              | 10009          | WORK DOES NOT CONFORM TO APPROVED PLANS LAYOUT OF THE KITCHEN & LIVING ROOM AREA ARE CONTRARY TO THE APPROVED PLANS #104859887 REM: CONFORM TO APPROVED PLANS                                                      | 2500.00          | 250.00      | .00         | B25              | 27-201 WORK DOES NOT CONFORM TO APPROVED PLANS                                   |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           |                  | DEFAULT        | CERTIFICATE ACCEPTED | 
| 257974              | 38087901Z            | RESOLVE              | 062599E5Y825A6       | 1073089 | 1    | 01517 | 07501 | 19991007     | 830          | 19990625    | 19910625   | Non-Hazardous | Elevators       | R.A. COHEN & ASSOCIATION  | 60                      | EAST 42 STREET    | MANHATTAN       | 10017          | 75B5,15M7. -75 PERFORM REQ. 5YR TESTS, -15 REPLACE MISSING FASCIA PLATE UNDER LOBBY.                                                                                                                               | 350.00           | 350.00      | .00         | BP7              | 27-987 FAILURE TO MAINTAIN ELEVATOR                                              |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           |                  | IN VIOLATION   | CERTIFICATE ACCEPTED | 
| 82371               | 34080927J            | RESOLVE              | 102292C12R1          | 4268676 | 4    | 12398 | 00227 | 19930126     | 830          | 19921204    | 19921022   | Non-Hazardous | Construction    | JUTE MARTIN               |                         |                   |                 |                | OCCUPANCY OF GARAGE CONTRARY TO THAT ALLOWED BY DEPT OF BUILDINGS RECORDS FROM PRKING FOR ONE CAR IN GARAGE TO STORAGE OF CAR SKELETON UNREGISTERED CHEVEY VAN AND TOYATA ILLEGAL. REMEDY:REMOVE UNREGISTERED      | 175.00           | 175.00      | .00         | B03              | 27-217 OCCUPANCY CONTRARY TO THAT ALLOWED BY THE C OF O BLDG DEPT RECORDS        |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           |                  | IN VIOLATION   | CERTIFICATE ACCEPTED | 
| 861952              | 34785403Z            | RESOLVE              | 052109C13MT03        | 4180026 | 4    | 08798 | 0036  | 20110125     | 800          | 20090521    | 20090521   | Unknown       | Construction    | 983 REALTY CORP           | 85-52                   | 256 STREET        | QNS             | 11001          | FAILURE TO SAFEGUARD ALL PERSONS AND PROPERTY AFFECTED BY CONT OPERATIONS DEFECTS NOTED AT TIME OF INSPECTION JOB SITE FENCE HAS OPEN SECTIONS ALLOWING ACCESS TO AN OPEN JOB SITE WITH OPENINGS AT ALL FLRS WITH  | 2400.00          | 2720.75     | .00         | 109              | BC 3301.2,27-1009(A) FAIL TO SAFEGUARD PERS/PROPERTY AFFECTED BY CONSTRUCTION OP |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           | NO               | IN VIOLATION   | CERTIFICATE ACCEPTED | 
| 424711              | 34021927J            | RESOLVE              | 032389C13D1          | 4180719 | 4    | 08830 | 00052 | 19890606     | 830          | 19890323    | 19890323   | Non-Hazardous | Construction    | TURNPIKE AUTO LAUNDRY INC | 255-39                  | JAMAICA AVENUE    | QUEENS          | 11001          | WORK WITHOUT A PERMIT WORK NOTED CEMENT BLOCK WALL AND WOOD FRAMED ROOF EXTENSION AT REAR OF BLDG. APPROX SIZE 50'X12'X20' WIDE. REMEDY; OBTAIN A PERMIT OR RETURN TO PRIOR LEGAL CONDITION.                       | 625.00           | 625.00      | .00         | B04              | 27-147 WORK WITHOUT A PERMIT                                                     |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           | MULTIPLE OFFENSE | IN VIOLATION   | CERTIFICATE ACCEPTED | 
| 340929              | 34283807P            | RESOLVE              | 061001C12CP07        | 4206710 | 4    | 09675 | 00004 | 20011030     | 830          | 20010610    | 20010610   | Hazardous     | Quality of Life | RAMPATTIE HEMRAJ          | 89-07                   | 145 STREET        | QU              | 11435          | WORK W/O PERMIT.WRK.NOTED:CELLAR WALL ERECTED CREATING RMS.(BDRM,3PC.BATH,TOILET,SINK & SHOWER)KITCHEN W/GAS STOVE & SINK ALSO AT REAR OF PREMISES BETWEEN HOUSE & GARAGE,ERECTED WOODEN SHED MADE BY 2' X 10' COV | 800.00           | 800.00      | .00         | BQ2              | 27-147 WORK WITHOUT PERMIT                                                       |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           |                  | IN VIOLATION   | CERTIFICATE ACCEPTED | 
| 1074626             | 35153310K            | RESOLVE              | 120314C08RG01        | 1078714 | 1    | 01578 | 0006  | 20150122     | 830          | 20141203    | 20141203   | Unknown       | Unknown         | VULCAN 81COLLC            | 66                      | MARBLEDALE ROAD   | TUCKAHOE        | 10707          | FAILURE TO MAINTAIN BLDG IN CODE COMPLIANT MANNER. DEFECTS NOTED:1-REAR CONCRETE PATIO SURFACE IS UNEVEN AND NOT PLUMB AND FLUSH AND LEVEL CAUSING POLKERS AND POOLS OF STANDING WATER TO ACCUMULATE;2-LEADER PIPE | .00              | .00         | .00         | 302              | 28-301.1 FAILURE TO MAINTAIN BLDG IN CODE-COMPLIANT MANNER                       |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                  |                          |                   |                           | NO               | CURED/IN-VIO   | CURE ACCEPTED        | 
```