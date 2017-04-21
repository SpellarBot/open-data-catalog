# Active Businesses - excluding ABNs and LLCs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-businesses-excluding-abns-and-llcs) |
| Metadata | [Link](https://data.oregon.gov/api/views/vd6m-2vq9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vd6m-2vq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vd6m-2vq9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vd6m-2vq9 |
| Name | Active Businesses - excluding ABNs and LLCs |
| Category | Administrative |
| Tags | business |
| Created | 2016-05-19T19:51:55Z |
| Publication Date | 2017-04-19T15:14:57Z |

## Description

Updated 04/19/2017. List of Active Businesses, excluding Assumed Business Name (ABN) registrations and Limited Liability Company (LLC) registrations

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | registry_number             | Registry Number             | text      | text        |
| Yes      | series tag  | business_name               | Business Name               | text      | text        |
| Yes      | series tag  | entity_type                 | Entity Type                 | text      | text        |
| Yes      | series tag  | registry_date               | Registry Date               | html      | html        |
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
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_continued
```

## Data Commands

```ls
series e:vd6m-2vq9 d:2017-04-19T15:09:46.000Z t:business_name="UNITED METHODIST CHURCH, OREGON CITY, OREGON" t:associated_name_type="MAILING ADDRESS" t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=299818&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:zip=97045 t:registry_date="1850-05-17 00:00:00" t:state=OR t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=299818 m:row_number.vd6m-2vq9=1

series e:vd6m-2vq9 d:2017-04-19T15:09:46.000Z t:business_name="UNITED METHODIST CHURCH, OREGON CITY, OREGON" t:associated_name_type="PRINCIPAL PLACE OF BUSINESS" t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=299818&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:zip=97045 t:registry_date="1850-05-17 00:00:00" t:state=OR t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=299818 m:row_number.vd6m-2vq9=2

series e:vd6m-2vq9 d:2017-04-19T15:09:46.000Z t:business_name="UNITED METHODIST CHURCH, OREGON CITY, OREGON" t:associated_name_type="REGISTERED AGENT" t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=299818&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:first_name=MIKE t:zip=97045 t:registry_date="1850-05-17 00:00:00" t:last_name=BENISCHEK t:state=OR t:entity_type="DOMESTIC NONPROFIT CORPORATION" t:city="OREGON CITY" t:registry_number=299818 m:row_number.vd6m-2vq9=3
```

## Meta Commands

```ls
metric m:row_number.vd6m-2vq9 p:long l:"Row Number"

entity e:vd6m-2vq9 l:"Active Businesses - excluding ABNs and  LLCs" t:url=https://data.oregon.gov/api/views/vd6m-2vq9

property e:vd6m-2vq9 t:meta.view v:id=vd6m-2vq9 v:category=Administrative v:averageRating=0 v:name="Active Businesses - excluding ABNs and  LLCs"

property e:vd6m-2vq9 t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:vd6m-2vq9 t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| :updated_at | registry_number | business_name                                              | entity_type                    | registry_date       | associated_name_type        | first_name | middle_name | last_name | suffix | not_of_record_entity | entity_of_record_reg_number | entity_of_record_name | address              | address_continued | city         | state | zip   | business_details                                                                                                                                           | 
| =========== | =============== | ========================================================== | ============================== | =================== | =========================== | ========== | =========== | ========= | ====== | ==================== | =========================== | ===================== | ==================== | ================= | ============ | ===== | ===== | ========================================================================================================================================================== | 
| 1492614586  | 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON               | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY  | OR    | 97045 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=299818&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
| 1492614586  | 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON               | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY  | OR    | 97045 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=299818&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
| 1492614586  | 299818          | UNITED METHODIST CHURCH, OREGON CITY, OREGON               | DOMESTIC NONPROFIT CORPORATION | 1850-05-17 00:00:00 | REGISTERED AGENT            | MIKE       |             | BENISCHEK |        |                      |                             |                       | 18955 S SOUTH END RD |                   | OREGON CITY  | OR    | 97045 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=299818&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
| 1492614586  | 574418          | WILLAMETTE UNIVERSITY                                      | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 900 STATE ST         |                   | SALEM        | OR    | 97301 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=574418&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
| 1492614586  | 574418          | WILLAMETTE UNIVERSITY                                      | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 900 STATE ST         |                   | SALEM        | OR    | 97301 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=574418&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
| 1492614586  | 574418          | WILLAMETTE UNIVERSITY                                      | DOMESTIC NONPROFIT CORPORATION | 1853-01-21 00:00:00 | REGISTERED AGENT            | MONICA     |             | RIMAI     |        |                      |                             |                       | 900 STATE ST         |                   | SALEM        | OR    | 97301 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=574418&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
| 1492614586  | 74612087        | PACIFIC UNIVERSITY                                         | DOMESTIC NONPROFIT CORPORATION | 1854-01-10 00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | 2043 COLLEGE WAY     |                   | FOREST GROVE | OR    | 97116 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=74612087&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 1492614586  | 74612087        | PACIFIC UNIVERSITY                                         | DOMESTIC NONPROFIT CORPORATION | 1854-01-10 00:00:00 | PRINCIPAL PLACE OF BUSINESS |            |             |           |        |                      |                             |                       | 2043 COLLEGE WAY     |                   | FOREST GROVE | OR    | 97116 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=74612087&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 1492614586  | 74612087        | PACIFIC UNIVERSITY                                         | DOMESTIC NONPROFIT CORPORATION | 1854-01-10 00:00:00 | REGISTERED AGENT            | MICHAEL    | D           | MALLERY   |        |                      |                             |                       | PACIFIC UNIVERSITY   | 2043 COLLEGE WAY  | FOREST GROVE | OR    | 97116 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=74612087&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 1492614586  | 355214          | OREGON LODGE NUMBER THREE INDEPENDENT ORDER OF ODD FELLOWS | DOMESTIC NONPROFIT CORPORATION | 1854-01-30 00:00:00 | MAILING ADDRESS             |            |             |           |        |                      |                             |                       | PO BOX 446           |                   | OREGON CITY  | OR    | 97045 | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=355214&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null]   | 
```