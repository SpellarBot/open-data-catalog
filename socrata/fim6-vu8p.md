# Case Types Submitted Or Reopened To DSS In 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/case-types-submitted-or-reopened-to-dss-in-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/fim6-vu8p) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fim6-vu8p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fim6-vu8p/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fim6-vu8p |
| Name | Case Types Submitted Or Reopened To DSS In 2012 |
| Attribution | Department of Emergency Services & Public Protection |
| Category | Public Safety |
| Tags | offense, agency, 2012 |
| Created | 2014-11-20T19:13:30Z |
| Publication Date | 2014-11-25T15:55:11Z |

## Description

The cases submitted to the laboratory for the calendar year 2012 include information on which agency/PD submitted the cases, the towns of offenses for each case, the dates of the incidents and the dates that the cases were opened in the laboratory.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                   | Data Type     | Render Type   |
| ======== | =========== | ===================== | ====================== | ============= | ============= |
| Yes      | time        | date_time_case_opened | Date& Time Case Opened | calendar_date | calendar_date |
| No       |             | date_of_offense       | Date of Offense        | calendar_date | calendar_date |
| Yes      | series tag  | offense_type          | Offense Type           | text          | text          |
| Yes      | series tag  | offense_city          | Offense City           | text          | text          |
| Yes      | series tag  | submitting_agency     | Submitting Agency      | text          | text          |
```

## Time Field

```ls
Value = date_time_case_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_of_offense
```

## Data Commands

```ls
series e:fim6-vu8p d:2012-01-03T09:38:00.000Z t:offense_type="Driving Under the Influence" t:submitting_agency="East Hampton Police Department" t:offense_city="East Hampton" m:row_number.fim6-vu8p=1

series e:fim6-vu8p d:2012-01-03T09:55:00.000Z t:offense_type="Driving Under the Influence" t:submitting_agency="Troop K" t:offense_city=Colchester m:row_number.fim6-vu8p=2

series e:fim6-vu8p d:2012-01-03T10:02:00.000Z t:offense_type="Driving Under the Influence" t:submitting_agency="Troop K" t:offense_city=Colchester m:row_number.fim6-vu8p=3
```

## Meta Commands

```ls
metric m:row_number.fim6-vu8p p:long l:"Row Number"

entity e:fim6-vu8p l:"Case Types Submitted Or Reopened To DSS In 2012" t:attribution="Department of Emergency Services & Public Protection" t:url=https://data.ct.gov/api/views/fim6-vu8p

property e:fim6-vu8p t:meta.view v:id=fim6-vu8p v:category="Public Safety" v:averageRating=0 v:name="Case Types Submitted Or Reopened To DSS In 2012" v:attribution="Department of Emergency Services & Public Protection"

property e:fim6-vu8p t:meta.view.owner v:id=xg2v-up8w v:screenName="Sandy Sun" v:displayName="Sandy Sun"

property e:fim6-vu8p t:meta.view.tableauthor v:id=xg2v-up8w v:screenName="Sandy Sun" v:roleName=editor v:displayName="Sandy Sun"
```

## Top Records

```ls
| date_time_case_opened | date_of_offense     | offense_type                       | offense_city | submitting_agency              | 
| ===================== | =================== | ================================== | ============ | ============================== | 
| 2012-01-03T09:38:00   |                     | Driving Under the Influence        | East Hampton | East Hampton Police Department | 
| 2012-01-03T09:55:00   |                     | Driving Under the Influence        | Colchester   | Troop K                        | 
| 2012-01-03T10:02:00   |                     | Driving Under the Influence        | Colchester   | Troop K                        | 
| 2012-01-03T10:14:00   |                     | Driving Under the Influence        | Bridgeport   | Troop G                        | 
| 2012-01-03T10:16:00   | 2011-12-23T00:00:00 | Driving Under the Influence        | Norwalk      | Troop G                        | 
| 2012-01-03T10:20:00   |                     | Driving Under the Influence        | Bridgeport   | Troop G                        | 
| 2012-01-03T10:31:00   | 2012-01-01T00:00:00 | Homicide - with gun                | Bridgeport   | Bridgeport Police Department   | 
| 2012-01-03T10:46:00   | 2011-06-06T00:00:00 | Other Offense                      | Watertown    | Watertown Police Department    | 
| 2012-01-03T11:08:00   |                     | Driving Under the Influence        | Bloomfield   | Bloomfield Police Department   | 
| 2012-01-03T11:09:00   | 2011-12-28T00:00:00 | Possession of Controlled Substance | Bloomfield   | Bloomfield Police Department   | 
```