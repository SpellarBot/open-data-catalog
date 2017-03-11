# 2014 Employee Wage Detail By Type

## Dataset

* [Dataset URL](https://data.srcity.org/api/views/4xtp-hh3v/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/2014-employee-wage-detail-by-type)
* Id = 4xtp-hh3v
* Name = 2014 Employee Wage Detail By Type
* Attribution = California State Controllers Office
* Attribution Link = http://publicpay.ca.gov/Reports/Cities/City.aspx?entityid=497&fiscalyear=2014
* Category = Finances
* Tags = [salary, pay, compensation]
* Created = 2016-02-10T01:04:09Z
* Publication Date = 2016-02-10T01:14:42Z
* Rows Updated = 2016-02-10T01:13:34Z

## Description

Calendar year 2014 City of Santa Rosa employee wage data from the State of CA Controller's Office Government Compensation in California website.

http://publicpay.ca.gov/Reports/Cities/City.aspx?entityid=497&fiscalyear=2014

## Columns

```ls
| Name                           | Field Name                   | Data Type | Render Type | Schema Type    | Included | 
| ============================== | ============================ | ========= | =========== | ============== | ======== | 
| updated_at                     | :updated_at                  | meta_data | meta_data   | time           | Yes      | 
| Position                       | position                     | text      | text        | series tag     | Yes      | 
| Department                     | department                   | text      | text        | series tag     | Yes      | 
| Total Wages                    | total_wages                  | money     | money       | numeric metric | Yes      | 
| Total Retirement & Health Cost | total_retirement_health_cost | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:4xtp-hh3v d:2016-02-09T17:04:11.000Z t:position="Activity Specialist" t:department="Recreation And Parks" m:total_retirement_health_cost=7 m:total_wages=12

series e:4xtp-hh3v d:2016-02-09T17:04:11.000Z t:position="Activity Specialist" t:department="Recreation And Parks" m:total_retirement_health_cost=133 m:total_wages=706

series e:4xtp-hh3v d:2016-02-09T17:04:11.000Z t:position="Police Technician" t:department="Police Department" m:total_retirement_health_cost=169 m:total_wages=1506
```

## Meta Commands

```ls
entity e:4xtp-hh3v l:"2014 Employee Wage Detail By Type" t:attribution="California State Controllers Office" t:url=https://data.srcity.org/api/views/4xtp-hh3v

property e:4xtp-hh3v t:meta.view d:2017-03-03T14:14:26.558Z v:id=4xtp-hh3v v:category=Finances v:attributionLink="http://publicpay.ca.gov/Reports/Cities/City.aspx?entityid=497&fiscalyear=2014" v:averageRating=0 v:name="2014 Employee Wage Detail By Type" v:attribution="California State Controllers Office"

property e:4xtp-hh3v t:meta.view.owner d:2017-03-03T14:14:26.558Z v:id=xdif-r3mr v:screenName=Admin v:roleName=administrator v:displayName=Admin

property e:4xtp-hh3v t:meta.view.tableauthor d:2017-03-03T14:14:26.558Z v:id=xdif-r3mr v:screenName=Admin v:roleName=administrator v:displayName=Admin
```