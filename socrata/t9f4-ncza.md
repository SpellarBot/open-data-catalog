# Completed FAFSAs Reported to MDHE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/completed-fafsas-reported-to-mdhe) |
| Metadata | [Link](https://data.mo.gov/api/views/t9f4-ncza) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/t9f4-ncza/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/t9f4-ncza/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | t9f4-ncza |
| Name | Completed FAFSAs Reported to MDHE |
| Attribution | Missouri Department of Higher Education |
| Category | Education |
| Tags | fafsa |
| Created | 2015-06-04T20:12:38Z |
| Publication Date | 2017-04-21T07:25:25Z |

## Description

The Number of FAFSAs Completed column is updated daily. If no seniors are reported for a school, the school will not be listed.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | ncessch                | NCESSCH                | text          | text          |
| Yes      | series tag  | school_name            | School Name            | text          | text          |
| Yes      | series tag  | school_year            | School Year            | text          | text          |
| Yes      | series tag  | number_of_applications | Number of Applications | text          | text          |
| Yes      | time        | lastupdated            | lastUpdated            | calendar_date | calendar_date |
| Yes      | series tag  | recordid               | recordId               | text          | text          |
```

## Time Field

```ls
Value = lastupdated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:t9f4-ncza d:2015-06-04T15:51:00.000Z t:number_of_applications=19 t:school_name="MIDWAY HIGH" t:school_year=2016 t:ncessch=293180002224 t:recordid=2931800022242016 m:row_number.t9f4-ncza=1

series e:t9f4-ncza d:2015-11-05T02:07:00.000Z t:number_of_applications=* t:school_name="CURRENT RIVER CAREER CENTER" t:school_year=2016 t:ncessch=291092000370 t:recordid=2910920003702016 m:row_number.t9f4-ncza=2

series e:t9f4-ncza d:2015-11-05T02:07:00.000Z t:number_of_applications=* t:school_name="ESTHER MILLER BAIS YAAKOV" t:school_year=2016 t:ncessch=A9902668 t:recordid=A99026682016 m:row_number.t9f4-ncza=3
```

## Meta Commands

```ls
metric m:row_number.t9f4-ncza p:long l:"Row Number"

entity e:t9f4-ncza l:"Completed FAFSAs Reported to MDHE" t:attribution="Missouri Department of Higher Education" t:url=https://data.mo.gov/api/views/t9f4-ncza

property e:t9f4-ncza t:meta.view v:id=t9f4-ncza v:category=Education v:attributionLink=http://www.dhe.mo.gov v:averageRating=0 v:name="Completed FAFSAs Reported to MDHE" v:attribution="Missouri Department of Higher Education"

property e:t9f4-ncza t:meta.view.owner v:id=wt79-n3v6 v:screenName="Diane Prenger" v:displayName="Diane Prenger"

property e:t9f4-ncza t:meta.view.tableauthor v:id=wt79-n3v6 v:screenName="Diane Prenger" v:roleName=editor v:displayName="Diane Prenger"
```

## Top Records

```ls
| ncessch      | school_name                 | school_year | number_of_applications | lastupdated         | recordid         | 
| ============ | =========================== | =========== | ====================== | =================== | ================ | 
| 293180002224 | MIDWAY HIGH                 | 2016        | 19                     | 2015-06-04T15:51:00 | 2931800022242016 | 
| 291092000370 | CURRENT RIVER CAREER CENTER | 2016        | *                      | 2015-11-05T02:07:00 | 2910920003702016 | 
| A9902668     | ESTHER MILLER BAIS YAAKOV   | 2016        | *                      | 2015-11-05T02:07:00 | A99026682016     | 
| 290579000125 | 1050 ADAIR CO. HIGH         | 2016        | 7                      | 2016-01-07T02:15:00 | 2905790001252016 | 
| A1101347     | ACE LEARNING CENTERS        | 2016        | *                      | 2016-01-07T02:15:00 | A11013472016     | 
| 292298001315 | ADAIR CO. HIGH              | 2016        | 11                     | 2016-01-07T02:15:00 | 2922980013152016 | 
| 290285000002 | ADRIAN SR. HIGH             | 2016        | 25                     | 2016-01-07T02:15:00 | 2902850000022016 | 
| 290288000004 | ADVANCE HIGH                | 2016        | 10                     | 2016-01-07T02:15:00 | 2902880000042016 | 
| 290291000009 | AFFTON HIGH                 | 2016        | 103                    | 2016-01-07T02:15:00 | 2902910000092016 | 
| 290297000010 | ALBANY HIGH                 | 2016        | 15                     | 2016-01-07T02:15:00 | 2902970000102016 | 
```