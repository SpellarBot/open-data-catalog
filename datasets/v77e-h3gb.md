# Proposed State Regulations - Time in Process

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-state-regulations-time-in-process) |
| Metadata | [Link](https://data.ct.gov/api/views/v77e-h3gb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/v77e-h3gb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/v77e-h3gb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | v77e-h3gb |
| Name | Proposed State Regulations - Time in Process |
| Attribution | Secretary of the State |
| Category | Government |
| Tags | regulations |
| Created | 2015-08-03T15:47:27Z |
| Publication Date | 2016-08-23T16:07:34Z |

## Description

As of March 13, 2015, all proposed state regulations must be written in the new eRegulations System. The primary purpose of the system is to improve public accessibility and transparency in the regulations process. A secondary goal, however, is to streamline the process by automating certain steps. This tracker will demonstrate the speed at which regulations historically went through the process vs. how quickly proposed regulations are moving through the process through the eRegulations System.  Regulations are now available at eregulations.ct.gov.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name            | Data Type     | Render Type   |
| ======== | ============== | ================== | =============== | ============= | ============= |
| Yes      | numeric metric | file               | File #          | number        | number        |
| Yes      | series tag     | agency             | Agency          | text          | text          |
| Yes      | series tag     | short_name         | Short Name      | text          | text          |
| Yes      | time           | public_notice_date | Notice Date     | calendar_date | calendar_date |
| No       |                | posted_date        | Date Filed      | calendar_date | calendar_date |
| Yes      | numeric metric | days_in_process    | Days in Process | number        | number        |
```

## Time Field

```ls
Value = public_notice_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = posted_date
```

## Data Commands

```ls
series e:v77e-h3gb d:2014-04-04T00:00:00.000Z t:agency="Public Health" t:short_name="Public Drinking Water Quality Standards" m:file=6203 m:days_in_process=622

series e:v77e-h3gb d:2014-09-25T00:00:00.000Z t:agency="Consumer Protection" t:short_name="Real Estate Appraisal" m:file=6202 m:days_in_process=440

series e:v77e-h3gb d:2012-10-30T00:00:00.000Z t:agency="Consumer Protection" t:short_name="Appraisal Management Companies" m:file=6200 m:days_in_process=1105
```

## Meta Commands

```ls
metric m:file p:integer l:"File #" t:dataTypeName=number

metric m:days_in_process p:integer l:"Days in Process" t:dataTypeName=number

entity e:v77e-h3gb l:"Proposed State Regulations - Time in Process" t:attribution="Secretary of the State" t:url=https://data.ct.gov/api/views/v77e-h3gb

property e:v77e-h3gb t:meta.view v:id=v77e-h3gb v:category=Government v:attributionLink=http://eregulations.ct.gov v:averageRating=0 v:name="Proposed State Regulations - Time in Process" v:attribution="Secretary of the State"

property e:v77e-h3gb t:meta.view.owner v:id=7mrw-hjv3 v:screenName="Chris Drake" v:displayName="Chris Drake"

property e:v77e-h3gb t:meta.view.tableauthor v:id=7mrw-hjv3 v:screenName="Chris Drake" v:roleName=publisher v:displayName="Chris Drake"
```

## Top Records

```ls
| file | agency                                   | short_name                                                                                                                                                | public_notice_date  | posted_date         | days_in_process | 
| ==== | ======================================== | ========================================================================================================================================================= | =================== | =================== | =============== | 
| 6203 | Public Health                            | Public Drinking Water Quality Standards                                                                                                                   | 2014-04-04T00:00:00 | 2015-12-17T00:00:00 | 622             | 
| 6202 | Consumer Protection                      | Real Estate Appraisal                                                                                                                                     | 2014-09-25T00:00:00 | 2015-12-09T00:00:00 | 440             | 
| 6200 | Consumer Protection                      | Appraisal Management Companies                                                                                                                            | 2012-10-30T00:00:00 | 2015-11-09T00:00:00 | 1105            | 
| 6199 | Consumer Protection                      | Motor Fuel Pricing                                                                                                                                        | 2014-05-25T00:00:00 | 2015-11-10T00:00:00 | 534             | 
| 6198 | Emergency Services and Public Protection | Boxing and Mixed Martial Arts                                                                                                                             | 2014-07-09T00:00:00 | 2015-11-06T00:00:00 | 485             | 
| 6196 | Energy and Environmental Protection      | Extension of Squantz Cove (Candlewood Lake) Slow-No-Wake Zone                                                                                             | 2014-10-09T00:00:00 | 2015-09-22T00:00:00 | 348             | 
| 6195 | Education                                | Administration of Medications by School Personnel and Administration of Medication During Before- and After-School Programs and School Readiness Programs | 2014-10-09T00:00:00 | 2015-08-11T00:00:00 | 306             | 
| 6194 | Labor                                    | Cranes and Derricks in Construction: Operator Certification (Occupational Safety and Health)                                                              | 2015-02-20T00:00:00 | 2015-08-11T00:00:00 | 172             | 
| 6193 | Energy and Environmental Protection      | State Board of Examiners of Environmental Professionals                                                                                                   | 2010-10-12T00:00:00 | 2015-08-05T00:00:00 | 1758            | 
| 6192 | Energy and Environmental Protection      | Endangered, Threatened, and Species of Special Concern                                                                                                    | 2015-02-10T00:00:00 | 2015-08-05T00:00:00 | 176             | 
```