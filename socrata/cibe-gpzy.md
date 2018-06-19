# EMS - Patient Contacts by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-patient-contacts-by-month) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cibe-gpzy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cibe-gpzy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cibe-gpzy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cibe-gpzy |
| Name | EMS - Patient Contacts by Month |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, patient contacts, atcems, workload, patients, patient transports, patient transport rate, patient care, city, county, coa, tc, city of austin, travis county |
| Created | 2014-10-16T13:41:42Z |
| Publication Date | 2016-08-18T16:40:52Z |

## Description

This table contains data that describes monthly patient contacts. It includes all incidents with a response priority between 1 and 5, inclusive.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ========================================== | ============= | ============= |
| Yes      | numeric metric | month_key                             | Month Key                                  | number        | number        |
| Yes      | time           | month_start_date                      | Month-Year                                 | calendar_date | calendar_date |
| Yes      | numeric metric | count_patient_contacts_all            | Total Patient Contacts                     | number        | number        |
| Yes      | numeric metric | count_patient_contacts_coa            | Austin Patient Contacts                    | number        | number        |
| Yes      | numeric metric | count_patient_contacts_tc             | Travis County Patient Contacts             | number        | number        |
| Yes      | numeric metric | count_patient_contacts_other          | Other Area Patient Contacts                | number        | number        |
| Yes      | numeric metric | count_patient_contacts_coa_and_tc     | Combined COA and TC Patient Contacts       | number        | number        |
| Yes      | numeric metric | count_patient_transports_all          | Total Patient Transports                   | number        | number        |
| Yes      | numeric metric | count_patient_transports_coa          | Austin Patient Transports                  | number        | number        |
| Yes      | numeric metric | count_patient_transports_tc           | Travis County Patient Transports           | number        | number        |
| Yes      | numeric metric | count_patient_transports_other        | Other Area Patient Transports              | number        | number        |
| Yes      | numeric metric | count_patient_transports_coa_and_tc   | Combined COA and TC Patient Transports     | number        | number        |
| Yes      | numeric metric | percent_patient_transports_all        | Overall Patient Transport Rate             | percent       | percent       |
| Yes      | numeric metric | percent_patient_transports_coa        | Austin Patient Transport Rate              | percent       | percent       |
| Yes      | numeric metric | percent_patient_transports_tc         | Travis County Patient Transport Rate       | percent       | percent       |
| Yes      | numeric metric | percent_patient_transports_other      | Other Area Patient Transport Rate          | percent       | percent       |
| Yes      | numeric metric | percent_patient_transports_coa_and_tc | Combined COA and TC Patient Transport Rate | percent       | percent       |
| Yes      | numeric metric | percent_patient_transports_target     | Patient Transport Rate Target              | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cibe-gpzy d:2010-10-01T00:00:00.000Z m:percent_patient_transports_coa=79.746632456 m:count_patient_transports_coa=4973 m:percent_patient_transports_coa_and_tc=79.499387838 m:count_patient_transports_tc=871 m:count_patient_contacts_coa_and_tc=7424 m:percent_patient_transports_tc=78.116591928 m:count_patient_contacts_tc=1132 m:percent_patient_transports_all=79.480907732 m:count_patient_transports_coa_and_tc=5844 m:count_patient_transports_other=5 m:count_patient_transports_all=5849 m:count_patient_contacts_all=7432 m:month_key=201010 m:percent_patient_transports_target=80 m:count_patient_contacts_coa=6292 m:count_patient_contacts_other=8 m:percent_patient_transports_other=62.5

series e:cibe-gpzy d:2010-11-01T00:00:00.000Z m:percent_patient_transports_coa=81.7233809 m:count_patient_transports_coa=4467 m:percent_patient_transports_coa_and_tc=80.991101564 m:count_patient_transports_tc=812 m:count_patient_contacts_coa_and_tc=6593 m:percent_patient_transports_tc=77.186311787 m:count_patient_contacts_tc=1064 m:percent_patient_transports_all=81.006270071 m:count_patient_transports_coa_and_tc=5279 m:count_patient_transports_other=18 m:count_patient_transports_all=5297 m:count_patient_contacts_all=6614 m:month_key=201011 m:percent_patient_transports_target=80 m:count_patient_contacts_coa=5529 m:count_patient_contacts_other=21 m:percent_patient_transports_other=85.714285714

series e:cibe-gpzy d:2010-12-01T00:00:00.000Z m:percent_patient_transports_coa=82.677853522 m:count_patient_transports_coa=4730 m:percent_patient_transports_coa_and_tc=82.471645308 m:count_patient_transports_tc=869 m:count_patient_contacts_coa_and_tc=6874 m:percent_patient_transports_tc=81.367041198 m:count_patient_contacts_tc=1087 m:percent_patient_transports_all=82.488614661 m:count_patient_transports_coa_and_tc=5599 m:count_patient_transports_other=16 m:count_patient_transports_all=5615 m:count_patient_contacts_all=6892 m:month_key=201012 m:percent_patient_transports_target=80 m:count_patient_contacts_coa=5787 m:count_patient_contacts_other=18 m:percent_patient_transports_other=88.888888888
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Year and month for record in <yyyymm> format (e.g. 201407)." t:dataTypeName=number

metric m:count_patient_contacts_all p:integer l:"Total Patient Contacts" d:"Count of all patients contacted by ATCEMS units." t:dataTypeName=number

metric m:count_patient_contacts_coa p:integer l:"Austin Patient Contacts" d:"Count of all patients contacted by ATCEMS units within the City of Austin." t:dataTypeName=number

metric m:count_patient_contacts_tc p:integer l:"Travis County Patient Contacts" d:"Count of all patients contacted by ATCEMS units within the Travis County service area, outside the City of Austin." t:dataTypeName=number

metric m:count_patient_contacts_other p:integer l:"Other Area Patient Contacts" d:"Count of patients contacted by ATCEMS units outside the primary ATCEMS service area." t:dataTypeName=number

metric m:count_patient_contacts_coa_and_tc p:integer l:"Combined COA and TC Patient Contacts" d:"Total count of patients contacted by ATCEMS units in the City of Austin and Travis County service areas." t:dataTypeName=number

metric m:count_patient_transports_all p:integer l:"Total Patient Transports" d:"Count of all patients transported by ATCEMS units to an approved receiving facility." t:dataTypeName=number

metric m:count_patient_transports_coa p:integer l:"Austin Patient Transports" d:"Count of all patients transported by ATCEMS units to an approved receiving facility when responding into the City of Austin." t:dataTypeName=number

metric m:count_patient_transports_tc p:integer l:"Travis County Patient Transports" d:"Count of all patients transported by ATCEMS units to an approved receiving facility when responding into the Travis County service area, outside the City of Austin." t:dataTypeName=number

metric m:count_patient_transports_other p:integer l:"Other Area Patient Transports" d:"Count of patients transported by ATCEMS units from incidents occurring outside the ATCEMS primary service area." t:dataTypeName=number

metric m:count_patient_transports_coa_and_tc p:integer l:"Combined COA and TC Patient Transports" d:"Count of patients transported from incidents occurring within the City of Austin and Travis County, combined." t:dataTypeName=number

metric m:percent_patient_transports_all p:double l:"Overall Patient Transport Rate" d:"Portion of patients contacted by ATCEMS who are transported by ATCEMS units to receiving facilities" t:dataTypeName=percent

metric m:percent_patient_transports_coa p:double l:"Austin Patient Transport Rate" d:"Portion of patients contacted by ATCEMS within the City of Austin who are transported by ATCEMS units to receiving facilities." t:dataTypeName=percent

metric m:percent_patient_transports_tc p:double l:"Travis County Patient Transport Rate" d:"Portion of patients contacted by ATCEMS within the Travis County service area and outside the City of Austin who are transported by ATCEMS units to receiving facilities." t:dataTypeName=percent

metric m:percent_patient_transports_other p:float l:"Other Area Patient Transport Rate" d:"Portion of patients contacted outside the primary ATCEMS service area who are transported to a receiving facility." t:dataTypeName=percent

metric m:percent_patient_transports_coa_and_tc p:double l:"Combined COA and TC Patient Transport Rate" d:"Portion of patients contacted in the City of Austin or Travis County who are transported by ATCEMS units to receiving facilities." t:dataTypeName=percent

metric m:percent_patient_transports_target p:float l:"Patient Transport Rate Target" d:"Target for portion of patients contacted by ATCEMS who are transported by ATCEMS units to receiving facilities. Deceased patients are excluded from this calculation." t:dataTypeName=percent

entity e:cibe-gpzy l:"EMS - Patient Contacts by Month" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/cibe-gpzy

property e:cibe-gpzy t:meta.view v:id=cibe-gpzy v:category="Public Safety" v:attributionLink=http://www.austintexas.gov/department/ems v:averageRating=0 v:name="EMS - Patient Contacts by Month" v:attribution="Austin-Travis County EMS"

property e:cibe-gpzy t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:cibe-gpzy t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | count_patient_contacts_all | count_patient_contacts_coa | count_patient_contacts_tc | count_patient_contacts_other | count_patient_contacts_coa_and_tc | count_patient_transports_all | count_patient_transports_coa | count_patient_transports_tc | count_patient_transports_other | count_patient_transports_coa_and_tc | percent_patient_transports_all | percent_patient_transports_coa | percent_patient_transports_tc | percent_patient_transports_other | percent_patient_transports_coa_and_tc | percent_patient_transports_target | 
| ========= | =================== | ========================== | ========================== | ========================= | ============================ | ================================= | ============================ | ============================ | =========================== | ============================== | =================================== | ============================== | ============================== | ============================= | ================================ | ===================================== | ================================= | 
| 201010    | 2010-10-01T00:00:00 | 7432                       | 6292                       | 1132                      | 8                            | 7424                              | 5849                         | 4973                         | 871                         | 5                              | 5844                                | 79.48090773200                 | 79.74663245600                 | 78.11659192800                | 62.50000000000                   | 79.49938783800                        | 80.00                             | 
| 201011    | 2010-11-01T00:00:00 | 6614                       | 5529                       | 1064                      | 21                           | 6593                              | 5297                         | 4467                         | 812                         | 18                             | 5279                                | 81.00627007100                 | 81.72338090000                 | 77.18631178700                | 85.71428571400                   | 80.99110156400                        | 80.00                             | 
| 201012    | 2010-12-01T00:00:00 | 6892                       | 5787                       | 1087                      | 18                           | 6874                              | 5615                         | 4730                         | 869                         | 16                             | 5599                                | 82.48861466100                 | 82.67785352200                 | 81.36704119800                | 88.88888888800                   | 82.47164530800                        | 80.00                             | 
| 201101    | 2011-01-01T00:00:00 | 7056                       | 6024                       | 1015                      | 17                           | 7039                              | 5889                         | 5048                         | 828                         | 13                             | 5876                                | 84.63638976700                 | 84.91169049600                 | 83.13253012000                | 76.47058823500                   | 84.65638956900                        | 80.00                             | 
| 201102    | 2011-02-01T00:00:00 | 6866                       | 5802                       | 1057                      | 7                            | 6859                              | 5697                         | 4852                         | 838                         | 7                              | 5690                                | 83.90279823200                 | 84.50017415500                 | 80.49951969200                | 100.00000000000                  | 83.88618605300                        | 80.00                             | 
| 201103    | 2011-03-01T00:00:00 | 7380                       | 6257                       | 1116                      | 7                            | 7373                              | 6031                         | 5102                         | 924                         | 5                              | 6026                                | 82.50341997200                 | 82.30359735400                 | 83.69565217300                | 71.42857142800                   | 82.51403532700                        | 80.00                             | 
| 201104    | 2011-04-01T00:00:00 | 7364                       | 6237                       | 1109                      | 18                           | 7346                              | 5940                         | 5070                         | 856                         | 14                             | 5926                                | 81.48148148100                 | 82.10526315700                 | 78.03099361800                | 77.77777777700                   | 81.49064906400                        | 80.00                             | 
| 201105    | 2011-05-01T00:00:00 | 7563                       | 6329                       | 1213                      | 21                           | 7542                              | 6135                         | 5155                         | 963                         | 17                             | 6118                                | 81.90921228300                 | 82.13830465200                 | 80.65326633100                | 85.00000000000                   | 81.90093708100                        | 80.00                             | 
| 201106    | 2011-06-01T00:00:00 | 7524                       | 6368                       | 1145                      | 11                           | 7513                              | 6089                         | 5199                         | 881                         | 9                              | 6080                                | 81.85239951600                 | 82.51071258500                 | 78.10283687900                | 90.00000000000                   | 81.84143222500                        | 80.00                             | 
| 201107    | 2011-07-01T00:00:00 | 7605                       | 6466                       | 1132                      | 7                            | 7598                              | 6152                         | 5284                         | 864                         | 4                              | 6148                                | 81.60233452700                 | 82.34377434900                 | 77.48878923700                | 57.14285714200                   | 81.62506638300                        | 80.00                             | 
```