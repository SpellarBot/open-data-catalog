# Position Status Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/position-status-report) |
| Metadata | [Link](https://data.ct.gov/api/views/cjb2-fkhn) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/cjb2-fkhn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/cjb2-fkhn/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | cjb2-fkhn |
| Name | Position Status Report |
| Category | Government |
| Tags | opm, positions |
| Created | 2014-09-10T17:00:23Z |
| Publication Date | 2015-02-10T15:12:57Z |

## Description

OPM compiles a monthly list of position data for executive branch agencies. The data, by fund, includes authorized position count, and filled and vacant positions.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | agency_title            | Agency Title            | text      | text        |
| Yes      | numeric metric | year_month              | Year Month              | number    | text        |
| Yes      | series tag     | position_description    | Position Description    | text      | text        |
| Yes      | numeric metric | general_fund            | General Fund            | number    | number      |
| Yes      | numeric metric | transportation_fund     | Transportation Fund     | number    | number      |
| Yes      | numeric metric | other_apropriated_funds | Other Apropriated Funds | number    | number      |
| Yes      | numeric metric | nonapropriated_funds    | NonApropriated Funds    | number    | number      |
| Yes      | numeric metric | federal_funds           | Federal Funds           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cjb2-fkhn d:2014-11-06T10:50:15.000Z t:position_description=Filled t:agency_title="African-American Affairs Commission" m:transportation_fund=0 m:other_apropriated_funds=0 m:general_fund=2 m:year_month=201211 m:federal_funds=0 m:nonapropriated_funds=0

series e:cjb2-fkhn d:2014-11-06T10:50:15.000Z t:position_description=Filled t:agency_title="African-American Affairs Commission" m:transportation_fund=0 m:other_apropriated_funds=0 m:general_fund=2 m:year_month=201204 m:federal_funds=0 m:nonapropriated_funds=0

series e:cjb2-fkhn d:2014-11-06T10:50:15.000Z t:position_description=Filled t:agency_title="African-American Affairs Commission" m:transportation_fund=0 m:other_apropriated_funds=0 m:general_fund=2 m:year_month=201307 m:federal_funds=0 m:nonapropriated_funds=0
```

## Meta Commands

```ls
metric m:year_month p:integer l:"Year Month" t:dataTypeName=number

metric m:general_fund p:double l:"General Fund" t:dataTypeName=number

metric m:transportation_fund p:float l:"Transportation Fund" t:dataTypeName=number

metric m:other_apropriated_funds p:double l:"Other Apropriated Funds" t:dataTypeName=number

metric m:nonapropriated_funds p:double l:"NonApropriated Funds" t:dataTypeName=number

metric m:federal_funds p:double l:"Federal Funds" t:dataTypeName=number

entity e:cjb2-fkhn l:"Position Status Report" t:url=https://data.ct.gov/api/views/cjb2-fkhn

property e:cjb2-fkhn t:meta.view v:id=cjb2-fkhn v:category=Government v:averageRating=0 v:name="Position Status Report"

property e:cjb2-fkhn t:meta.view.owner v:id=9ksm-yr8w v:screenName="Olivia Knighton" v:displayName="Olivia Knighton"

property e:cjb2-fkhn t:meta.view.tableauthor v:id=9ksm-yr8w v:screenName="Olivia Knighton" v:roleName=editor v:displayName="Olivia Knighton"
```

## Top Records

```ls
| :updated_at | agency_title                        | year_month | position_description | general_fund | transportation_fund | other_apropriated_funds | nonapropriated_funds | federal_funds | 
| =========== | =================================== | ========== | ==================== | ============ | =================== | ======================= | ==================== | ============= | 
| 1415271015  | African-American Affairs Commission | 201211     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201204     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201307     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201201     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201301     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201309     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201111     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201209     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201112     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
| 1415271015  | African-American Affairs Commission | 201202     | Filled               | 2            | 0                   | 0                       | 0                    | 0             | 
```