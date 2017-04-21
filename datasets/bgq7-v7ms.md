# Procurement - Intent to Award

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-intent-to-award) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/bgq7-v7ms) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/bgq7-v7ms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/bgq7-v7ms/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | bgq7-v7ms |
| Name | Procurement - Intent to Award |
| Attribution | Office of the Chief Procurement Officer |
| Category | Finance & Administration |
| Tags | procurement, purchase, contract, bid, rfp, rfi, award |
| Created | 2016-05-31T20:18:58Z |
| Publication Date | 2017-04-07T22:59:41Z |

## Description

This dataset provides the list of vendors to be recommended for award at the Cook County Board Meetings and are posted below for public viewing.

M/W/DBE Participation Types
MBE = Minority Business Enterprise
WBE = Women Business Enterprise
DBE = Disadvantaged Business Enterprise
Native American (4)
African American (5)
Female (7)
Asian (8)
Hispanic (9)

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | time           | posting_date              | Posting Date              | calendar_date | calendar_date |
| Yes      | series tag     | contract_number           | Contract Number           | text          | text          |
| Yes      | series tag     | description               | Description               | text          | text          |
| Yes      | series tag     | department                | Department                | text          | text          |
| Yes      | series tag     | recommended_action        | Recommended Action        | text          | text          |
| Yes      | series tag     | recommended_vendor        | Recommended Vendor        | text          | text          |
| Yes      | numeric metric | contract_amount           | Contract Amount           | money         | money         |
| Yes      | series tag     | mbe_wbe_dbe_participation | MBE/WBE/DBE Participation | text          | text          |
| Yes      | series tag     | mbe_wbe_dbe_type          | MBE/WBE/DBE type          | text          | text          |
| Yes      | numeric metric | direct_participation      | Direct Participation      | percent       | percent       |
| Yes      | numeric metric | indirect_participation    | Indirect Participation    | percent       | percent       |
| Yes      | numeric metric | of_bids_received          | # of Bids Received        | number        | number        |
| Yes      | numeric metric | of_m_wbe_bids_received    | # of M/WBE Bids Received  | number        | number        |
| Yes      | series tag     | cca_concurs               | CCA Concurs               | checkbox      | checkbox      |
| Yes      | series tag     | link                      | Link                      | url           | url           |
```

## Time Field

```ls
Value = posting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bgq7-v7ms d:2016-06-03T00:00:00.000Z t:description="Insurance Brokerage Services" t:department="Risk Management - 008" t:link=http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf t:recommended_vendor="Mesirow Insurance Services, Inc." t:cca_concurs=true t:contract_number=1590-14938 t:recommended_action=Award t:mbe_wbe_dbe_type=DNA m:of_bids_received=2 m:contract_amount=30114455

series e:bgq7-v7ms d:2016-06-03T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf t:contract_number=1590-14938 t:mbe_wbe_dbe_participation="CS Insurance Strategies, Inc." t:mbe_wbe_dbe_type="MBE (6)" m:direct_participation=25

series e:bgq7-v7ms d:2016-06-03T00:00:00.000Z t:link=http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf t:contract_number=1590-14938 t:mbe_wbe_dbe_participation="Risks & Insurance Management Services, Inc." t:mbe_wbe_dbe_type="WBE (7)" m:direct_participation=10
```

## Meta Commands

```ls
metric m:contract_amount p:double l:"Contract Amount" t:dataTypeName=money

metric m:direct_participation p:float l:"Direct Participation" t:dataTypeName=percent

metric m:indirect_participation p:float l:"Indirect Participation" t:dataTypeName=percent

metric m:of_bids_received p:integer l:"# of Bids Received" t:dataTypeName=number

metric m:of_m_wbe_bids_received p:integer l:"# of M/WBE Bids Received" t:dataTypeName=number

entity e:bgq7-v7ms l:"Procurement - Intent to Award" t:attribution="Office of the Chief Procurement Officer" t:url=https://datacatalog.cookcountyil.gov/api/views/bgq7-v7ms

property e:bgq7-v7ms t:meta.view v:id=bgq7-v7ms v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/procurement v:averageRating=0 v:name="Procurement - Intent to Award" v:attribution="Office of the Chief Procurement Officer"

property e:bgq7-v7ms t:meta.view.license v:name="Public Domain"

property e:bgq7-v7ms t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:bgq7-v7ms t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| posting_date        | contract_number | description                                        | department                          | recommended_action | recommended_vendor               | contract_amount | mbe_wbe_dbe_participation                   | mbe_wbe_dbe_type    | direct_participation | indirect_participation | of_bids_received | of_m_wbe_bids_received | cca_concurs | link                                                                                             | 
| =================== | =============== | ================================================== | =================================== | ================== | ================================ | =============== | =========================================== | =================== | ==================== | ====================== | ================ | ====================== | =========== | ================================================================================================ | 
| 2016-06-03T00:00:00 | 1590-14938      | Insurance Brokerage Services                       | Risk Management - 008               | Award              | Mesirow Insurance Services, Inc. | 30114455.00     |                                             | DNA                 |                      |                        | 2                |                        | true        | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1590-14938      |                                                    |                                     |                    |                                  |                 | CS Insurance Strategies, Inc.               | MBE (6)             | 25.0                 |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1590-14938      |                                                    |                                     |                    |                                  |                 | Risks & Insurance Management Services, Inc. | WBE (7)             | 10.0                 |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1515-14998R     | Continuous and Multi-Event Sequential Air Monitors | Depart. of Environmental Ctrl - 161 | Award              | Met One Instruments, Inc.        | 162487.25       |                                             | Full Waiver Granted |                      |                        | 2                |                        | true        | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1685-15562      | CDBG-DR Program                                    | Planning & Development - 013        | Award              | CDM Smith, Inc.                  | 1997184.00      |                                             | DNA                 |                      |                        |                  |                        | true        | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1685-15562      |                                                    |                                     |                    |                                  |                 | B2B Strategic Solutions, Inc.               | WBE (6)             | 9.0                  |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1685-15562      |                                                    |                                     |                    |                                  |                 | Tandem Ventures, LLC                        | WBE (6)             | 6.5                  |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1685-15562      |                                                    |                                     |                    |                                  |                 | Environmental Design International          | MBE (6)             | 14.3                 |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1685-15562      |                                                    |                                     |                    |                                  |                 | PCG International, Inc.                     | MBE (6)             | 3.1                  |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
| 2016-06-03T00:00:00 | 1685-15562      |                                                    |                                     |                    |                                  |                 | Panacea Group, LLC                          | MBE (6)             | 2.1                  |                        |                  |                        |             | [http://opendocs.cookcountyil.gov/procurement/intent-award/160608-Intent_to_Award_EDS.pdf, null] | 
```