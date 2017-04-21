# Oregon Workers' Compensation Compensable Fatal Dataset, 2001 - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-workers-compensation-compensable-fatal-dataset-2001-2010-381c2) |
| Metadata | [Link](https://data.oregon.gov/api/views/7e2w-n5dn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7e2w-n5dn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7e2w-n5dn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7e2w-n5dn |
| Name | Oregon Workers' Compensation Compensable Fatal Dataset, 2001 - 2010 |
| Attribution | Oregon Department of Consumer & Business Services |
| Category | Public Safety |
| Tags | compensable, fatal, fatality, fatalities, work related, death, injury, industry, occupational, workers compensation, oregon osha |
| Created | 2011-09-22T14:33:37Z |
| Publication Date | 2011-11-22T18:10:36Z |

## Description

Compensable fatalities are workers' compensation claims that are accepted by insurers arising from a fatal occupational injury or disease.  Data excludes deaths of workers not subject to Oregon workers' compensation coverage, such as workers who were self-employed or who worked in Oregon for out-of-state employers, city of Portland police and fire employees, and federal employees.

Data are continually updated to be as accurate as possible, so reports may vary over time.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                     | Data Type     | Render Type   |
| ======== | ============== | ================== | ======================== | ============= | ============= |
| Yes      | series tag     | industry           | Industry                 | text          | text          |
| Yes      | numeric metric | naics              | NAICS                    | number        | number        |
| Yes      | time           | injury_month_year  | Injury month/year        | calendar_date | calendar_date |
| Yes      | series tag     | event_of_injury    | Injury Event             | text          | text          |
| Yes      | series tag     | injury_description | Injury description       | text          | text          |
| Yes      | series tag     | investigated       | Oregon OSHA Investigated | text          | text          |
| Yes      | numeric metric | age                | Age                      | number        | number        |
| Yes      | series tag     | sex                | Sex                      | text          | text          |
| Yes      | numeric metric | tenure             | Tenure in Months         | number        | number        |
| Yes      | series tag     | injury_county      | Injury county            | text          | text          |
```

## Time Field

```ls
Value = injury_month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7e2w-n5dn d:2008-02-01T00:00:00.000Z t:injury_county=Clackamas t:sex=M t:injury_description="Gas station owner shot by robber" t:event_of_injury=Homicide t:industry="Retail trade" m:naics=447110 m:age=59 m:tenure=134

series e:7e2w-n5dn d:2001-02-01T00:00:00.000Z t:injury_county=Polk t:sex=M t:injury_description="Fell 10 ft from ladder" t:event_of_injury=Fall t:investigated=+ t:industry=Manufacturing m:naics=325314 m:age=56 m:tenure=78

series e:7e2w-n5dn d:2006-12-01T00:00:00.000Z t:injury_county=Jackson t:sex=F t:injury_description="Shot by patient" t:event_of_injury=Homicide t:industry="Health care" m:naics=623312 m:age=51 m:tenure=133
```

## Meta Commands

```ls
metric m:naics p:integer l:NAICS d:"North American Industry Classification System, 2002 edition." t:dataTypeName=number

metric m:age p:integer l:Age d:"Represents the actual age of the worker at the time of the fatal injury or illness and may be different than the age at death." t:dataTypeName=number

metric m:tenure p:integer l:"Tenure in Months" d:"The length of time, in months, that the employee had been working for the employer at the time of the fatal injury or diagnosis of fatal illness. ""N/A"" - tenure is unknown; ""0"" - tenure is less than one month." t:dataTypeName=number

entity e:7e2w-n5dn l:"Oregon Workers' Compensation Compensable Fatal Dataset, 2001 - 2010" t:attribution="Oregon Department of Consumer & Business Services" t:url=https://data.oregon.gov/api/views/7e2w-n5dn

property e:7e2w-n5dn t:meta.view v:id=7e2w-n5dn v:category="Public Safety" v:attributionLink="http://www4.cbs.state.or.us/ex/imd/external/reports/index.cfm?fuseaction=dir&ItemID=1991" v:averageRating=0 v:name="Oregon Workers' Compensation Compensable Fatal Dataset, 2001 - 2010" v:attribution="Oregon Department of Consumer & Business Services"

property e:7e2w-n5dn t:meta.view.owner v:id=t33a-b3q4 v:screenName="Stacey Barnhart" v:displayName="Stacey Barnhart"

property e:7e2w-n5dn t:meta.view.tableauthor v:id=t33a-b3q4 v:screenName="Stacey Barnhart" v:displayName="Stacey Barnhart"
```

## Top Records

```ls
| industry                       | naics  | injury_month_year   | event_of_injury   | injury_description                          | investigated | age | sex | tenure | injury_county | 
| ============================== | ====== | =================== | ================= | =========================================== | ============ | === | === | ====== | ============= | 
| Retail trade                   | 447110 | 2008-02-01T00:00:00 | Homicide          | Gas station owner shot by robber            |              | 59  | M   | 134    | Clackamas     | 
| Manufacturing                  | 325314 | 2001-02-01T00:00:00 | Fall              | Fell 10 ft from ladder                      | +            | 56  | M   | 78     | Polk          | 
| Health care                    | 623312 | 2006-12-01T00:00:00 | Homicide          | Shot by patient                             |              | 51  | F   | 133    | Jackson       | 
| Transportation and warehousing | 484220 | 2010-02-01T00:00:00 | Highway accident  | Log truck went off road and hit tree        | +            | 51  | M   | 33     | Lane          | 
| Transportation and warehousing | 484220 | 2010-05-01T00:00:00 | Highway accident  | Truck driver in fuel truck went off highway | +            | 58  | M   | 60     | Deschutes     | 
| Agriculture and forestry       | 113310 | 2010-06-01T00:00:00 | Aircraft accident | Pilot died in helicopter crash              |              | 51  | M   | 21     | Out-of-state  | 
| Transport and warehousing      | 484121 | 2006-09-01T00:00:00 | Struck by         | Struck by falling pipes                     |              | 48  | M   | 5      | Out-of-state  | 
| Manufacturing                  | 321991 | 2001-01-01T00:00:00 | Fall              | Fell from a man-cage                        | +            | 54  | M   | 33     | Marion        | 
| Agriculture and forestry       | 113310 | 2000-03-01T00:00:00 | Struck by         | Struck by a falling tree                    |              | 34  | M   | 78     | Out-of-state  | 
| Retail trade                   | 441310 | 2002-04-01T00:00:00 | Highway accident  | Vehicle hit a tree                          |              | 42  | M   | 91     | Out-of-state  | 
```