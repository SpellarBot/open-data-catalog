# Appeals to the Rent Board

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/appeals-to-the-rent-board) |
| Metadata | [Link](https://data.sfgov.org/api/views/w2ze-eag5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/w2ze-eag5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/w2ze-eag5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | w2ze-eag5 |
| Name | Appeals to the Rent Board |
| Category | Housing and Buildings |
| Created | 2015-12-28T20:04:12Z |
| Publication Date | 2016-05-03T18:48:38Z |

## Description

Appeals are filed when parties are seeking review of decisions made by the Rent Board and are decided by the Rent Board Commission. Grounds for appeals include: substantive appeals, procedural problems and hardship appeals. For more information, please see: http://sfrb.org/fact-sheet-8-hearings-mediations-and-appeals.

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | =========== | ================================= | =================================== | ============= | ============= |
| Yes      | time        | date_filed                        | Date Filed                          | calendar_date | calendar_date |
| Yes      | series tag  | filing_party                      | Filing Party                        | text          | text          |
| Yes      | series tag  | appeal_id                         | Appeal ID                           | text          | text          |
| Yes      | series tag  | hardship_appeal                   | Hardship Appeal                     | checkbox      | checkbox      |
| Yes      | series tag  | interpreter_request               | Interpreter Request                 | checkbox      | checkbox      |
| No       |             | address                           | Address                             | text          | text          |
| Yes      | series tag  | appeal_source_zipcode             | Appeal Source Zipcode               | text          | text          |
| Yes      | series tag  | supervisor_district               | Supervisor District                 | text          | text          |
| Yes      | series tag  | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:w2ze-eag5 d:2010-10-05T00:00:00.000Z t:appeal_id=AT100092 t:neighborhoods_analysis_boundaries=Lakeshore t:filing_party=tenant t:appeal_source_zipcode=94132 t:hardship_appeal=true t:interpreter_request=false t:supervisor_district=7 m:row_number.w2ze-eag5=1

series e:w2ze-eag5 d:2014-04-04T00:00:00.000Z t:appeal_id=AL140034 t:neighborhoods_analysis_boundaries=Portola t:filing_party=landlord t:appeal_source_zipcode=94134 t:hardship_appeal=true t:interpreter_request=true t:supervisor_district=9 m:row_number.w2ze-eag5=2

series e:w2ze-eag5 d:2010-03-17T00:00:00.000Z t:appeal_id=AT100034 t:neighborhoods_analysis_boundaries=Lakeshore t:filing_party=tenant t:appeal_source_zipcode=94132 t:hardship_appeal=true t:interpreter_request=false t:supervisor_district=7 m:row_number.w2ze-eag5=3
```

## Meta Commands

```ls
metric m:row_number.w2ze-eag5 p:long l:"Row Number"

entity e:w2ze-eag5 l:"Appeals to the Rent Board" t:url=https://data.sfgov.org/api/views/w2ze-eag5

property e:w2ze-eag5 t:meta.view v:id=w2ze-eag5 v:category="Housing and Buildings" v:averageRating=0 v:name="Appeals to the Rent Board"

property e:w2ze-eag5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:w2ze-eag5 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:w2ze-eag5 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| date_filed          | filing_party | appeal_id | hardship_appeal | interpreter_request | address                         | appeal_source_zipcode | supervisor_district | neighborhoods_analysis_boundaries | 
| =================== | ============ | ========= | =============== | =================== | =============================== | ===================== | =================== | ================================= | 
| 2010-10-05T00:00:00 | tenant       | AT100092  | true            | false               | 500 Block Of John Muir Drive    | 94132                 | 7                   | Lakeshore                         | 
| 2014-04-04T00:00:00 | landlord     | AL140034  | true            | true                | 2900 Block Of San Bruno Avenue  | 94134                 | 9                   | Portola                           | 
| 2010-03-17T00:00:00 | tenant       | AT100034  | true            | false               | 600 Block Of John Muir Drive    | 94132                 | 7                   | Lakeshore                         | 
| 2014-09-22T00:00:00 | tenant       | AT140182  | true            | false               | 100 Block Of Point Lobos Avenue | 94121                 | 1                   | Outer Richmond                    | 
| 2013-07-24T00:00:00 | tenant       | AT130077  | true            | false               | 2300 Block Of Van Ness Avenue   | 94109                 | 3                   | Russian Hill                      | 
| 2012-07-10T00:00:00 | tenant       | AT120075  | true            | false               | 1700 Block Of Van Ness Avenue   | 94109                 | 2                   | Pacific Heights                   | 
| 2012-05-30T00:00:00 | tenant       | AT120059  | true            | false               | 1600 Block Of Broadway Street   | 94109                 |                     |                                   | 
| 2010-03-17T00:00:00 | tenant       | AT100035  | true            | false               | 600 Block Of John Muir Drive    | 94132                 | 7                   | Lakeshore                         | 
| 2011-04-05T00:00:00 | tenant       | AT110038  | true            | false               | 0 Block Of Terra Vista Avenue   | 94115                 | 2                   | Lone Mountain/USF                 | 
| 2010-05-13T00:00:00 | tenant       | AT100055  | true            | false               | 0 Block Of Chumasero Drive      | 94132                 | 7                   | Lakeshore                         | 
```