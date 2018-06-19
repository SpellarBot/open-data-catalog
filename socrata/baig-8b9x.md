# Active Benefit Companies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/benefit-companies-9e825) |
| Metadata | [Link](https://data.oregon.gov/api/views/baig-8b9x) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/baig-8b9x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/baig-8b9x/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | baig-8b9x |
| Name | Active Benefit Companies |
| Category | Business |
| Tags | business, registration, benefit |
| Created | 2014-01-02T22:27:08Z |
| Publication Date | 2017-04-19T15:26:56Z |

## Description

(Updated 04/19/2017) Corporations and Limited Liability Companies designated as benefit companies.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | registry_number          | Registry Number          | text          | text          |
| Yes      | series tag  | entity_type              | Entity Type              | text          | text          |
| Yes      | series tag  | business_name            | Business Name            | text          | text          |
| Yes      | time        | benefit_designation_date | Benefit Designation Date | calendar_date | calendar_date |
| Yes      | series tag  | business_details         | Business Details         | url           | url           |
```

## Time Field

```ls
Value = benefit_designation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:baig-8b9x d:2016-11-08T00:00:00.000Z t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=126519099&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:business_name="#KOLDST FOODS LLC" t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:registry_number=126519099 m:row_number.baig-8b9x=1

series e:baig-8b9x d:2014-12-08T00:00:00.000Z t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=106727290&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:business_name="10 BOTANICALS, LLC" t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:registry_number=106727290 m:row_number.baig-8b9x=2

series e:baig-8b9x d:2017-01-26T00:00:00.000Z t:business_details="http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=128729399&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA" t:business_name="10660 SE DIVISION LLC" t:entity_type="DOMESTIC LIMITED LIABILITY COMPANY" t:registry_number=128729399 m:row_number.baig-8b9x=3
```

## Meta Commands

```ls
metric m:row_number.baig-8b9x p:long l:"Row Number"

entity e:baig-8b9x l:"Active Benefit Companies" t:url=https://data.oregon.gov/api/views/baig-8b9x

property e:baig-8b9x t:meta.view v:id=baig-8b9x v:category=Business v:averageRating=0 v:name="Active Benefit Companies"

property e:baig-8b9x t:meta.view.license v:name="Public Domain"

property e:baig-8b9x t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:baig-8b9x t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registry_number | entity_type                        | business_name                            | benefit_designation_date | business_details                                                                                                                                            | 
| =============== | ================================== | ======================================== | ======================== | =========================================================================================================================================================== | 
| 126519099       | DOMESTIC LIMITED LIABILITY COMPANY | #KOLDST FOODS LLC                        | 2016-11-08T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=126519099&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 106727290       | DOMESTIC LIMITED LIABILITY COMPANY | 10 BOTANICALS, LLC                       | 2014-12-08T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=106727290&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 128729399       | DOMESTIC LIMITED LIABILITY COMPANY | 10660 SE DIVISION LLC                    | 2017-01-26T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=128729399&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 119775294       | DOMESTIC LIMITED LIABILITY COMPANY | 2000 SE 10TH AVENUE LLC                  | 2016-03-14T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=119775294&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 119746394       | DOMESTIC LIMITED LIABILITY COMPANY | 3 RIVERS GAME BIRDS & HUNTING GUIDES LLC | 2016-03-14T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=119746394&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 108612490       | DOMESTIC LIMITED LIABILITY COMPANY | 360 CARPENTRY LLC                        | 2015-02-11T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=108612490&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 113162093       | DOMESTIC LIMITED LIABILITY COMPANY | 3RD CHANCE RANCH AND REHAB, LLC          | 2015-07-24T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=113162093&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 117473694       | DOMESTIC LIMITED LIABILITY COMPANY | 4 TRAILS ENDEAVORS, LLC                  | 2016-01-04T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=117473694&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 112647995       | DOMESTIC LIMITED LIABILITY COMPANY | 4W PROPERTIES, LLC                       | 2015-07-06T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=112647995&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
| 119087195       | DOMESTIC LIMITED LIABILITY COMPANY | 8 DOLLAR FARM LLC                        | 2016-02-23T00:00:00      | [http://egov.sos.state.or.us/br/pkg_web_name_srch_inq.do_name_srch?p_name=&p_regist_nbr=119087195&p_srch=PHASE1&p_print=FALSE&p_entity_status=ACTINA, null] | 
```