# Active Assumed Business Name Registrations (ABN)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-assumed-business-name-registrations-abn) |
| Metadata | [Link](https://data.oregon.gov/api/views/vt5w-tv2x) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vt5w-tv2x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vt5w-tv2x/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vt5w-tv2x |
| Name | Active Assumed Business Name Registrations (ABN) |
| Category | Administrative |
| Tags | abn, registration, business |
| Created | 2016-05-19T19:44:33Z |
| Publication Date | 2017-04-19T15:23:30Z |

## Description

Updated 04/19/2017. List of Active ABN registrations

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag  | registry_number             | Registry Number             | text      | text        |
| Yes      | series tag  | business_name               | Business Name               | text      | text        |
| Yes      | series tag  | entity_type                 | Entity Type                 | text      | text        |
| Yes      | time        | registry_date               | Registry Date               | text      | text        |
| Yes      | series tag  | associated_name_type        | Associated Name Type        | text      | text        |
| Yes      | series tag  | first_name                  | First Name                  | text      | text        |
| Yes      | series tag  | middle_name                 | Middle Name                 | text      | text        |
| Yes      | series tag  | last_name                   | Last Name                   | text      | text        |
| Yes      | series tag  | suffix                      | Suffix                      | text      | text        |
| Yes      | series tag  | not_of_record_entity        | Not of Record Entity        | text      | text        |
| Yes      | series tag  | entity_of_record_reg_number | Entity of Record Reg Number | text      | number      |
| Yes      | series tag  | entity_of_record_name       | Entity of Record Name       | text      | text        |
| No       |             | address                     | Address                     | text      | text        |
| No       |             | address_continued           | Address Continued           | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | state                       | State                       | text      | text        |
| Yes      | series tag  | zip                         | Zip                         | text      | text        |
| Yes      | series tag  | business_details            | Business Details            | url       | url         |
```

## Time Field

```ls
Value = registry_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = address,address_continued
```

## Data Commands

```ls
series e:vt5w-tv2x d:1964-03-04T00:00:00.000Z t:business_name="NEWPORT BAR & HARBOR PILOT" t:associated_name_type="AUTHORIZED REPRESENTATIVE" t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=73304553&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:first_name=JOHN t:zip=97420 t:middle_name=S t:last_name=BURLES t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city="COOS BAY" t:registry_number=73304553 m:row_number.vt5w-tv2x=1

series e:vt5w-tv2x d:1964-03-04T00:00:00.000Z t:business_name="NEWPORT BAR & HARBOR PILOT" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=73304553&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:zip=97420 t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city="COOS BAY" t:registry_number=73304553 m:row_number.vt5w-tv2x=2

series e:vt5w-tv2x d:1964-07-01T00:00:00.000Z t:business_name="""83"" RANCH" t:associated_name_type="AUTHORIZED REPRESENTATIVE" t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=70969952&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:first_name=CONNIE t:zip=97868 t:last_name=MCCALL t:state=OR t:entity_type="ASSUMED BUSINESS NAME" t:city="PILOT ROCK" t:registry_number=70969952 m:row_number.vt5w-tv2x=3
```

## Meta Commands

```ls
metric m:row_number.vt5w-tv2x p:long l:"Row Number"

entity e:vt5w-tv2x l:"Active Assumed Business Name Registrations (ABN)" t:url=https://data.oregon.gov/api/views/vt5w-tv2x

property e:vt5w-tv2x t:meta.view v:id=vt5w-tv2x v:category=Administrative v:averageRating=0 v:name="Active Assumed Business Name Registrations (ABN)"

property e:vt5w-tv2x t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:vt5w-tv2x t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | business_name                     | entity_type           | registry_date | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name | address              | address_continued | city       | state | zip   | business_details                                                                                                                                           | 
| =============== | ================================= | ===================== | ============= | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ===================== | ==================== | ================= | ========== | ===== | ===== | ========================================================================================================================================================== | 
| 73304553        | NEWPORT BAR & HARBOR PILOT        | ASSUMED BUSINESS NAME | 3/4/1964      | AUTHORIZED REPRESENTATIVE   | JOHN       | S           | BURLES    |        |                      |                             |                       | 686 N FRONT ST       |                   | COOS BAY   | OR    | 97420 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=73304553&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 73304553        | NEWPORT BAR & HARBOR PILOT        | ASSUMED BUSINESS NAME | 3/4/1964      | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 686 N FRONT ST       |                   | COOS BAY   | OR    | 97420 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=73304553&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 70969952        | "83" RANCH                        | ASSUMED BUSINESS NAME | 7/1/1964      | AUTHORIZED REPRESENTATIVE   | CONNIE     |             | MCCALL    |        |                      |                             |                       | 64565 BEAR CK RD     |                   | PILOT ROCK | OR    | 97868 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=70969952&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 70969952        | "83" RANCH                        | ASSUMED BUSINESS NAME | 7/1/1964      | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 64565 BEAR CK RD     |                   | PILOT ROCK | OR    | 97868 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=70969952&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 71230859        | A-1 JANITORIAL & DOMESTIC SERVICE | ASSUMED BUSINESS NAME | 7/1/1964      | AUTHORIZED REPRESENTATIVE   | PATRICIA   | L           | BEEMER    |        |                      |                             |                       | 3732 KENDRA          |                   | EUGENE     | OR    | 97404 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=71230859&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 71230859        | A-1 JANITORIAL & DOMESTIC SERVICE | ASSUMED BUSINESS NAME | 7/1/1964      | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 3732 KENDRA          |                   | EUGENE     | OR    | 97404 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=71230859&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 70022158        | ACE ROOFING CO.                   | ASSUMED BUSINESS NAME | 7/1/1964      | AUTHORIZED REPRESENTATIVE   | JAMES      | R           | LEICHTON  |        |                      |                             |                       | 6335 NE 35TH PL      |                   | PORTLAND   | OR    | 97221 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=70022158&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 70022158        | ACE ROOFING CO.                   | ASSUMED BUSINESS NAME | 7/1/1964      | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 6335 NE 35TH PL      |                   | PORTLAND   | OR    | 97211 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=70022158&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 71127550        | ACE SEPTIC TANK SERVICE           | ASSUMED BUSINESS NAME | 7/1/1964      | AUTHORIZED REPRESENTATIVE   | CARRIE     |             | DARRAS    |        |                      |                             |                       | PO BOX 9177          |                   | BROOKS     | OR    | 97305 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=71127550&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 71127550        | ACE SEPTIC TANK SERVICE           | ASSUMED BUSINESS NAME | 7/1/1964      | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 10980 PORTLAND RD NE |                   | SALEM      | OR    | 97305 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=71127550&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
```