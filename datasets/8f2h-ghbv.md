# Case Types Submitted Or Reopened To DSS In 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/case-types-submitted-or-reopened-to-dss-in-2011) |
| Metadata | [Link](https://data.ct.gov/api/views/8f2h-ghbv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/8f2h-ghbv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/8f2h-ghbv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 8f2h-ghbv |
| Name | Case Types Submitted Or Reopened To DSS In 2011 |
| Attribution | Department of Emergency Services and Public Protection |
| Category | Public Safety |
| Tags | offense, agency, 2011 |
| Created | 2014-11-21T20:13:25Z |
| Publication Date | 2014-11-25T15:53:10Z |

## Description

The cases submitted to the laboratory for the calendar year 2011 include information on which agency/PD submitted the cases, the towns of offenses for each case, the dates of the incidents and the dates that the cases were opened in the laboratory.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                       | Data Type     | Render Type   |
| ======== | =========== | ======================== | ========================== | ============= | ============= |
| Yes      | time        | date_time_of_case_opened | Date & Time of Case Opened | calendar_date | calendar_date |
| No       |             | date_of_offense          | Date of Offense            | calendar_date | calendar_date |
| Yes      | series tag  | offense_type             | Offense Type               | text          | text          |
| Yes      | series tag  | offense_city             | Offense City               | text          | text          |
| Yes      | series tag  | submitting_agency        | Submitting Agency          | text          | text          |
```

## Time Field

```ls
Value = date_time_of_case_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_of_offense
```

## Data Commands

```ls
series e:8f2h-ghbv d:2011-01-03T07:33:00.000Z t:offense_type="Driving Under the Influence" t:submitting_agency="Greenwich Police Department" t:offense_city=Greenwich m:row_number.8f2h-ghbv=1

series e:8f2h-ghbv d:2011-01-03T09:43:00.000Z t:offense_type="Possession of Controlled Substance" t:submitting_agency="New Britain Police Department" t:offense_city="New Britain" m:row_number.8f2h-ghbv=2

series e:8f2h-ghbv d:2011-01-03T10:06:00.000Z t:offense_type="Driving Under the Influence" t:submitting_agency="Berlin Police Department" t:offense_city=Kensington m:row_number.8f2h-ghbv=3
```

## Meta Commands

```ls
metric m:row_number.8f2h-ghbv p:long l:"Row Number"

entity e:8f2h-ghbv l:"Case Types Submitted Or Reopened To DSS In 2011" t:attribution="Department of Emergency Services and Public Protection" t:url=https://data.ct.gov/api/views/8f2h-ghbv

property e:8f2h-ghbv t:meta.view v:id=8f2h-ghbv v:category="Public Safety" v:averageRating=0 v:name="Case Types Submitted Or Reopened To DSS In 2011" v:attribution="Department of Emergency Services and Public Protection"

property e:8f2h-ghbv t:meta.view.license v:name="Public Domain"

property e:8f2h-ghbv t:meta.view.owner v:id=xg2v-up8w v:screenName="Sandy Sun" v:displayName="Sandy Sun"

property e:8f2h-ghbv t:meta.view.tableauthor v:id=xg2v-up8w v:screenName="Sandy Sun" v:roleName=editor v:displayName="Sandy Sun"
```

## Top Records

```ls
| date_time_of_case_opened | date_of_offense     | offense_type                       | offense_city | submitting_agency             | 
| ======================== | =================== | ================================== | ============ | ============================= | 
| 2011-01-03T07:33:00      |                     | Driving Under the Influence        | Greenwich    | Greenwich Police Department   | 
| 2011-01-03T09:43:00      |                     | Possession of Controlled Substance | New Britain  | New Britain Police Department | 
| 2011-01-03T10:06:00      |                     | Driving Under the Influence        | Kensington   | Berlin Police Department      | 
| 2011-01-03T10:55:00      | 2010-12-24T00:00:00 | Homicide - with gun                | Hartford     | Hartford Police Department    | 
| 2011-01-03T10:59:00      |                     | Homicide                           | Hartford     | Hartford Police Department    | 
| 2011-01-03T11:06:00      |                     | Driving Under the Influence        | Meriden      | Meriden Police Department     | 
| 2011-01-03T11:30:00      |                     | Possession of Controlled Substance | Groton       | Groton Town Police Department | 
| 2011-01-03T12:02:00      |                     | Driving Under the Influence        | Bridgeport   | Troop G                       | 
| 2011-01-03T12:53:00      | 2010-11-04T00:00:00 | Burglary                           | New Britain  | New Britain Police Department | 
| 2011-01-03T12:53:00      | 2010-10-28T00:00:00 | Larceny                            | New Britain  | New Britain Police Department | 
```