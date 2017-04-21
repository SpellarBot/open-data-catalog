# Candidates - August, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/candidates-august-2012-d6655) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/xub4-frcu) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/xub4-frcu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/xub4-frcu/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | xub4-frcu |
| Name | Candidates - August, 2012 |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | election, candidates |
| Created | 2012-08-28T20:29:56Z |
| Publication Date | 2012-08-28T20:53:03Z |

## Description

Candidates for Primary election, 2012

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | contest_id     | contest_id     | text      | number      |
| Yes      | series tag     | ballot_title_1 | ballot_title_1 | text      | text        |
| Yes      | series tag     | ballot_title_2 | ballot_title_2 | text      | text        |
| Yes      | series tag     | ballot_title_3 | ballot_title_3 | text      | text        |
| Yes      | series tag     | name_1         | name_1         | text      | text        |
| Yes      | series tag     | name_2         | name_2         | text      | text        |
| Yes      | series tag     | candidate_id   | candidate_id   | text      | number      |
| Yes      | series tag     | party_id       | party_id       | text      | number      |
| Yes      | series tag     | party          | party          | text      | text        |
| Yes      | series tag     | districtname1  | districtname1  | text      | text        |
| Yes      | series tag     | district_id    | district_id    | text      | number      |
| Yes      | series tag     | heading_1      | heading_1      | text      | text        |
| Yes      | series tag     | heading_2      | heading_2      | text      | text        |
| Yes      | series tag     | group_type     | group_type     | text      | text        |
| Yes      | series tag     | partisan       | partisan       | text      | text        |
| Yes      | series tag     | facsimile_id   | facsimile_id   | text      | text        |
| Yes      | numeric metric | sequence       | sequence       | number    | number      |
| Yes      | series tag     | stm_id         | stm_id         | text      | number      |
| Yes      | series tag     | measure        | measure        | text      | text        |
| Yes      | series tag     | final          | final          | text      | text        |
| Yes      | series tag     | status         | status         | text      | text        |
| Yes      | series tag     | full_name      | full_name      | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xub4-frcu d:2012-01-01T00:00:00.000Z t:ballot_title_1="Precinct Committee Officer" t:group_type=PCO t:final=N t:districtname1="PRECINCT SHL 32-0001 PCO" t:partisan=N t:measure=N t:status=A t:contest_id=42962 t:district_id=11437 t:party_id=18 t:facsimile_id=X0001 t:party=DPC t:name_1="Corey Murata" t:candidate_id=18290 t:ballot_title_2="SHL 32-0001 PCO" t:full_name="I affirm I am a Democrat." m:sequence=0

series e:xub4-frcu d:2012-01-01T00:00:00.000Z t:ballot_title_1="Precinct Committee Officer" t:group_type=PCO t:final=N t:districtname1="PRECINCT LFP 46-0003 PCO" t:partisan=N t:measure=N t:status=A t:contest_id=42963 t:district_id=11438 t:party_id=18 t:facsimile_id=X0003 t:party=DPC t:name_1="Myra Gamburg" t:candidate_id=18254 t:ballot_title_2="LFP 46-0003 PCO" t:full_name="I affirm I am a Democrat." m:sequence=0

series e:xub4-frcu d:2012-01-01T00:00:00.000Z t:ballot_title_1="Precinct Committee Officer" t:group_type=PCO t:final=N t:districtname1="PRECINCT ALDERWOOD PCO" t:partisan=N t:measure=N t:status=A t:contest_id=42965 t:district_id=11440 t:party_id=19 t:facsimile_id=X0010 t:party=RPC t:name_1="Kristina Shaffer" t:candidate_id=18619 t:ballot_title_2="ALDERWOOD PCO" t:full_name="I affirm I am a Republican." m:sequence=0
```

## Meta Commands

```ls
metric m:sequence p:integer l:sequence t:dataTypeName=number

entity e:xub4-frcu l:"Candidates - August, 2012" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/xub4-frcu

property e:xub4-frcu t:meta.view v:id=xub4-frcu v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="Candidates - August, 2012" v:attribution="King County Elections"

property e:xub4-frcu t:meta.view.license v:name="Public Domain"

property e:xub4-frcu t:meta.view.owner v:id=bkmh-fhfb v:screenName="Asera Khatun" v:displayName="Asera Khatun"

property e:xub4-frcu t:meta.view.tableauthor v:id=bkmh-fhfb v:screenName="Asera Khatun" v:roleName=publisher v:displayName="Asera Khatun"
```

## Top Records

```ls
| contest_id | ballot_title_1             | ballot_title_2  | ballot_title_3 | name_1                 | name_2 | candidate_id | party_id | party | districtname1            | district_id | heading_1 | heading_2 | group_type | partisan | facsimile_id | sequence | stm_id | measure | final | status | full_name                   | 
| ========== | ========================== | =============== | ============== | ====================== | ====== | ============ | ======== | ===== | ======================== | =========== | ========= | ========= | ========== | ======== | ============ | ======== | ====== | ======= | ===== | ====== | =========================== | 
| 42962      | Precinct Committee Officer | SHL 32-0001 PCO |                | Corey Murata           |        | 18290        | 18       | DPC   | PRECINCT SHL 32-0001 PCO | 11437       |           |           | PCO        | N        | X0001        | 0        |        | N       | N     | A      | I affirm I am a Democrat.   | 
| 42963      | Precinct Committee Officer | LFP 46-0003 PCO |                | Myra Gamburg           |        | 18254        | 18       | DPC   | PRECINCT LFP 46-0003 PCO | 11438       |           |           | PCO        | N        | X0003        | 0        |        | N       | N     | A      | I affirm I am a Democrat.   | 
| 42964      | Precinct Committee Officer | BUR 33-0009 PCO |                |                        |        |              |          |       | PRECINCT BUR 33-0009 PCO | 11439       |           |           | PCO        | N        | X0009        |          |        | N       |       |        |                             | 
| 42965      | Precinct Committee Officer | ALDERWOOD PCO   |                | Kristina Shaffer       |        | 18619        | 19       | RPC   | PRECINCT ALDERWOOD PCO   | 11440       |           |           | PCO        | N        | X0010        | 0        |        | N       | N     | A      | I affirm I am a Republican. | 
| 42966      | Precinct Committee Officer | BEL 41-0011 PCO |                |                        |        |              |          |       | PRECINCT BEL 41-0011 PCO | 11441       |           |           | PCO        | N        | X0011        |          |        | N       |       |        |                             | 
| 42967      | Precinct Committee Officer | SHL 32-0012 PCO |                |                        |        |              |          |       | PRECINCT SHL 32-0012 PCO | 11442       |           |           | PCO        | N        | X0012        |          |        | N       |       |        |                             | 
| 42968      | Precinct Committee Officer | ALG 30-0013 PCO |                | Autumn Davis - Rep     |        | 18154        | 19       | RPC   | PRECINCT ALG 30-0013 PCO | 11443       |           |           | PCO        | N        | X0013        | 0        |        | N       | Y     | A      | I affirm I am a Republican. | 
| 42968      | Precinct Committee Officer | ALG 30-0013 PCO |                | Deidre N. Lorenz - Rep |        | 17171        | 19       | RPC   | PRECINCT ALG 30-0013 PCO | 11443       |           |           | PCO        | N        | X0013        | 0        |        | N       | Y     | A      | I affirm I am a Republican. | 
| 42969      | Precinct Committee Officer | ALG 30-0014 PCO |                |                        |        |              |          |       | PRECINCT ALG 30-0014 PCO | 11444       |           |           | PCO        | N        | X0014        |          |        | N       |       |        |                             | 
| 42970      | Precinct Committee Officer | DES 33-0016 PCO |                |                        |        |              |          |       | PRECINCT DES 33-0016 PCO | 11445       |           |           | PCO        | N        | X0016        |          |        | N       |       |        |                             | 
```