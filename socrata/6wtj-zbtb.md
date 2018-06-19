# Austin Code Complaint Cases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-code-complaint-cases) |
| Metadata | [Link](https://data.austintexas.gov/api/views/6wtj-zbtb) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/6wtj-zbtb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/6wtj-zbtb/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 6wtj-zbtb |
| Name | Austin Code Complaint Cases |
| Attribution | Austin Code Department |
| Category | Government |
| Created | 2015-04-30T19:19:28Z |
| Publication Date | 2017-01-11T13:12:40Z |

## Description

This data represents Austin Code Department complaint cases.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | case_id      | CASE_ID      | text          | text          |
| No       |             | address      | ADDRESS_LONG | text          | text          |
| Yes      | series tag  | house_number | HOUSE_NUMBER | text          | text          |
| Yes      | series tag  | street_name  | STREET_NAME  | text          | text          |
| Yes      | series tag  | city         | CITY         | text          | text          |
| Yes      | series tag  | state        | STATE        | text          | text          |
| Yes      | series tag  | zip_code     | ZIP_CODE     | text          | number        |
| No       |             | x            | X            | number        | number        |
| No       |             | y            | Y            | number        | number        |
| Yes      | time        | opened_date  | OPENED_DATE  | calendar_date | calendar_date |
| No       |             | closed_date  | CLOSED_DATE  | calendar_date | calendar_date |
| Yes      | series tag  | department   | DEPARTMENT   | text          | text          |
| Yes      | series tag  | case_type    | CASE_TYPE    | text          | text          |
| Yes      | series tag  | description  | DESCRIPTION  | text          | text          |
| Yes      | series tag  | case_contact | CASE_CONTACT | text          | text          |
| Yes      | series tag  | case_manager | CASE_MANAGER | text          | text          |
| No       |             | date_updated | DATE_UPDATED | calendar_date | calendar_date |
| No       |             | latitude     | LATITUDE     | number        | number        |
| No       |             | longitude    | LONGITUDE    | number        | number        |
```

## Time Field

```ls
Value = opened_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,x,y,closed_date,date_updated,latitude,longitude
```

## Data Commands

```ls
series e:6wtj-zbtb d:2015-12-01T00:00:00.000Z t:case_contact="JULIEN DANIEL G & FRANCIS FRANCIS JULIEN" t:house_number=2018 t:zip_code=78757 t:description="Structure Condition Violation(s)" t:department="Code Enforcement" t:street_name="BRENTWOOD ST" t:state=TX t:case_id="2015-143619 CC" t:case_type=Complaints t:case_manager="Brian Eberwine|512-974-9814" t:city=AUSTIN m:row_number.6wtj-zbtb=1

series e:6wtj-zbtb d:2015-12-01T00:00:00.000Z t:case_contact="SAWH LALIT  LMK INVESTMENTS" t:house_number=6205 t:zip_code=78617 t:description="Structure Condition Violation(s)" t:department="Code Enforcement" t:street_name="VIDA NUEVA AVE" t:state=TX t:case_id="2015-143641 CC" t:case_type=Complaints t:case_manager="Dedric Knox|512-974-9811" t:city=AUSTIN m:row_number.6wtj-zbtb=2

series e:6wtj-zbtb d:2015-12-01T00:00:00.000Z t:house_number=7200 t:zip_code=78745 t:description="Work Without Permit" t:department="Code Enforcement" t:street_name="ALBERT RD" t:state=TX t:case_id="2015-143693 CC" t:case_type=Complaints t:case_manager="Alicia Tovar|512-974-3048" t:city=AUSTIN m:row_number.6wtj-zbtb=3
```

## Meta Commands

```ls
metric m:row_number.6wtj-zbtb p:long l:"Row Number"

entity e:6wtj-zbtb l:"Austin Code Complaint Cases" t:attribution="Austin Code Department" t:url=https://data.austintexas.gov/api/views/6wtj-zbtb

property e:6wtj-zbtb t:meta.view v:id=6wtj-zbtb v:category=Government v:averageRating=60 v:name="Austin Code Complaint Cases" v:attribution="Austin Code Department"

property e:6wtj-zbtb t:meta.view.license v:name="Public Domain"

property e:6wtj-zbtb t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:6wtj-zbtb t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| case_id        | address                     | house_number | street_name    | city   | state | zip_code | x           | y           | opened_date         | closed_date         | department       | case_type  | description                      | case_contact                             | case_manager                    | date_updated        | latitude    | longitude    | 
| ============== | =========================== | ============ | ============== | ====== | ===== | ======== | =========== | =========== | =================== | =================== | ================ | ========== | ================================ | ======================================== | =============================== | =================== | =========== | ============ | 
| 2015-143619 CC | 2018 BRENTWOOD ST           | 2018         | BRENTWOOD ST   | AUSTIN | TX    | 78757    | 3115778.25  | 10097409    | 2015-12-01T00:00:00 | 2015-12-05T00:00:00 | Code Enforcement | Complaints | Structure Condition Violation(s) | JULIEN DANIEL G & FRANCIS FRANCIS JULIEN | Brian Eberwine|512-974-9814     | 2015-12-05T00:00:00 | 30.34124404 | -97.73619534 | 
| 2015-143641 CC | 6205 VIDA NUEVA AVE         | 6205         | VIDA NUEVA AVE | AUSTIN | TX    | 78617    | 3152541.305 | 10034731.56 | 2015-12-01T00:00:00 | 2015-12-17T00:00:00 | Code Enforcement | Complaints | Structure Condition Violation(s) | SAWH LALIT LMK INVESTMENTS               | Dedric Knox|512-974-9811        | 2015-12-17T00:00:00 | 30.16654549 | -97.62452638 | 
| 2015-143693 CC | 7200 ALBERT RD              | 7200         | ALBERT RD      | AUSTIN | TX    | 78745    | 3096019.25  | 10044639    | 2015-12-01T00:00:00 | 2015-12-02T00:00:00 | Code Enforcement | Complaints | Work Without Permit              |                                          | Alicia Tovar|512-974-3048       | 2015-12-02T00:00:00 | 30.19743879 | -97.80262182 | 
| 2015-143699 CC | 7200 TEABERRY DR            | 7200         | TEABERRY DR    | AUSTIN | TX    | 78745    | 3100056     | 10042513    | 2015-12-01T00:00:00 | 2016-01-29T00:00:00 | Code Enforcement | Complaints | Work Without Permit              | COX LOU RAYNIE                           | Alicia Tovar|512-974-3048       | 2016-01-29T00:00:00 | 30.19134160 | -97.79000128 | 
| 2015-137590 CC | 13005 HEINEMANN DR Unit 612 | 13005        | HEINEMANN DR   | AUSTIN | TX    | 78727    | 3112215     | 10133423    | 2015-11-16T00:00:00 | 2015-11-19T00:00:00 | Code Enforcement | Complaints | Property Abatement               | MFT-LAUREL RIDGE LLC                     | Ronald Union|512-974-6428       | 2015-11-19T00:00:00 | 30.44046982 | -97.74483168 | 
| 2015-138470 CC | 5503 COVENTRY LN            | 5503         | COVENTRY LN    | AUSTIN | TX    | 78723    | 3132473.5   | 10084216    | 2015-11-18T00:00:00 | 2015-12-03T00:00:00 | Code Enforcement | Complaints | Property Abatement               | TERRELL CURTIS BRANDON                   | Michael Harrington|512-974-5617 | 2015-12-03T00:00:00 | 30.30389630 | -97.68428116 | 
| 2015-138533 CC | 1706 W 6TH ST               | 1706         | W 6TH ST       | AUSTIN | TX    | 78703    | 3107041.25  | 10073736    | 2015-11-18T00:00:00 | 2015-12-04T00:00:00 | Code Enforcement | Complaints | Property Abatement               | 1706 WEST 6TH STREE JOINT VENTURE        | James Paxton|512-974-3018       | 2015-12-08T00:00:00 | 30.27672800 | -97.76561689 | 
| 2015-138667 CC | S LAMAR BLVD & MANCHACA RD  |              |                |        |       |          |             |             | 2015-11-18T00:00:00 | 2015-12-03T00:00:00 | Code Enforcement | Complaints | Land Use Violation(s)            | LYRIC AT MUELLER LTD                     | Mario Ruiz|512-974-6781         | 2015-12-09T00:00:00 |             |              | 
| 2015-137623 CC | 3200 SILK OAK DR            |              |                |        |       |          |             |             | 2015-11-16T00:00:00 | 2015-12-29T00:00:00 | Code Enforcement | Complaints | Land Use Violation(s)            | LYRIC AT MUELLER LTD                     | Farah Presley|(512) 974-3602    | 2015-12-29T00:00:00 |             |              | 
| 2015-137705 CC | 3506 E 12TH ST              |              |                |        |       |          |             |             | 2015-11-16T00:00:00 | 2015-11-24T00:00:00 | Code Enforcement | Complaints | Property Abatement               | LYRIC AT MUELLER LTD                     | Luis M Gonzales|512-974-6334    | 2015-11-30T00:00:00 |             |              | 
```