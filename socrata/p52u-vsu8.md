# Case Types Submitted Or Reopened To DSS In 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/case-types-submitted-or-reopened-to-dss-in-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/p52u-vsu8) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/p52u-vsu8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/p52u-vsu8/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | p52u-vsu8 |
| Name | Case Types Submitted Or Reopened To DSS In 2013 |
| Attribution | Department of Emergency Services & Public Protection |
| Category | Public Safety |
| Tags | offense, agency, 2013 |
| Created | 2014-11-19T16:20:20Z |
| Publication Date | 2014-11-25T16:07:44Z |

## Description

The cases submitted to the laboratory for the calendar year 2013 include information on which agency/PD submitted the cases, the towns of offenses for each case, the dates of the incidents and the dates that the cases were opened in the laboratory.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                       | Data Type     | Render Type   |
| ======== | =========== | ======================== | ========================== | ============= | ============= |
| Yes      | time        | date_time_of_case_opened | Date & Time of Case Opened | calendar_date | calendar_date |
| No       |             | date_of_offense          | Date Of Offense            | calendar_date | calendar_date |
| Yes      | series tag  | offense                  | Offense                    | text          | text          |
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
series e:p52u-vsu8 d:2013-01-02T08:11:00.000Z t:submitting_agency="Stratford Police Department" t:offense_city=Stratford t:offense="Possession of Controlled Substance" m:row_number.p52u-vsu8=1

series e:p52u-vsu8 d:2013-01-02T09:13:00.000Z t:submitting_agency="Clinton Police Department" t:offense_city=Clinton t:offense=Larceny m:row_number.p52u-vsu8=2

series e:p52u-vsu8 d:2013-01-02T09:30:00.000Z t:submitting_agency="Waterbury Police Department" t:offense_city=Waterbury t:offense=Burglary m:row_number.p52u-vsu8=3
```

## Meta Commands

```ls
metric m:row_number.p52u-vsu8 p:long l:"Row Number"

entity e:p52u-vsu8 l:"Case Types Submitted Or Reopened To DSS In 2013" t:attribution="Department of Emergency Services & Public Protection" t:url=https://data.ct.gov/api/views/p52u-vsu8

property e:p52u-vsu8 t:meta.view v:id=p52u-vsu8 v:category="Public Safety" v:averageRating=0 v:name="Case Types Submitted Or Reopened To DSS In 2013" v:attribution="Department of Emergency Services & Public Protection"

property e:p52u-vsu8 t:meta.view.license v:name="Public Domain"

property e:p52u-vsu8 t:meta.view.owner v:id=xg2v-up8w v:screenName="Sandy Sun" v:displayName="Sandy Sun"

property e:p52u-vsu8 t:meta.view.tableauthor v:id=xg2v-up8w v:screenName="Sandy Sun" v:roleName=editor v:displayName="Sandy Sun"
```

## Top Records

```ls
| date_time_of_case_opened | date_of_offense     | offense                            | offense_city | submitting_agency           | 
| ======================== | =================== | ================================== | ============ | =========================== | 
| 2013-01-02T08:11:00      | 2012-08-03T00:00:00 | Possession of Controlled Substance | Stratford    | Stratford Police Department | 
| 2013-01-02T09:13:00      | 2012-12-07T00:00:00 | Larceny                            | Clinton      | Clinton Police Department   | 
| 2013-01-02T09:30:00      | 2012-12-19T00:00:00 | Burglary                           | Waterbury    | Waterbury Police Department | 
| 2013-01-02T09:33:00      | 2012-12-19T00:00:00 | Burglary                           | Waterbury    | Waterbury Police Department | 
| 2013-01-02T09:48:00      | 2012-12-28T00:00:00 | Liquor law violation               | Middletown   | CSP - TROOP F               | 
| 2013-01-02T09:53:00      | 2012-12-30T00:00:00 | Liquor law violation               | Old Lyme     | CSP - TROOP F               | 
| 2013-01-02T09:57:00      | 2012-12-31T00:00:00 | Burglary                           | Killingworth | CSP - TROOP F               | 
| 2013-01-02T10:02:00      | 2012-12-08T00:00:00 | Larceny - motor vehicle            | Old Lyme     | CSP - TROOP F               | 
| 2013-01-02T10:12:00      |                     | Driving Under the Influence        | Litchfield   | Troop L                     | 
| 2013-01-02T10:13:00      | 2012-12-30T00:00:00 | Larceny                            | Ledyard      | CSP - Casino Unit           | 
```