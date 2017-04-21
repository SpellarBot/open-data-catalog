# Labor Quick Facts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/labor-quick-facts-9d0b5) |
| Metadata | [Link](https://data.mo.gov/api/views/ymz7-guyk) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/ymz7-guyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/ymz7-guyk/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | ymz7-guyk |
| Name | Labor Quick Facts |
| Category | Labor |
| Created | 2013-03-15T13:36:30Z |
| Publication Date | 2013-12-04T15:48:28Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type     | Render Type   |
| ======== | ============== | =================================================== | =================================================== | ============= | ============= |
| Yes      | time           | date                                                | Date                                                | calendar_date | calendar_date |
| Yes      | numeric metric | unemployment_rate                                   | Unemployment Rate                                   | percent       | percent       |
| Yes      | numeric metric | initial_unemployment_claims_filed                   | Initial Unemployment Claims Filed                   | number        | number        |
| Yes      | numeric metric | minimum_wage                                        | Minimum Wage                                        | money         | money         |
| Yes      | numeric metric | potential_osha_fines_avoided_by_missouri_businesses | Potential OSHA Fines Avoided by Missouri Businesses | money         | money         |
| Yes      | numeric metric | workers_compensation_injuries_filed                 | Workers' Compensation Injuries Filed                | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ymz7-guyk d:2009-08-01T00:00:00.000Z m:unemployment_rate=9.7 m:initial_unemployment_claims_filed=43377 m:minimum_wage=7.25 m:potential_osha_fines_avoided_by_missouri_businesses=289948 m:workers_compensation_injuries_filed=9687

series e:ymz7-guyk d:2009-09-01T00:00:00.000Z m:unemployment_rate=9.7 m:initial_unemployment_claims_filed=40247 m:minimum_wage=7.25 m:potential_osha_fines_avoided_by_missouri_businesses=338948 m:workers_compensation_injuries_filed=9859

series e:ymz7-guyk d:2009-10-01T00:00:00.000Z m:unemployment_rate=9.7 m:initial_unemployment_claims_filed=59944 m:minimum_wage=7.25 m:potential_osha_fines_avoided_by_missouri_businesses=204140 m:workers_compensation_injuries_filed=9629
```

## Meta Commands

```ls
metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=percent

metric m:initial_unemployment_claims_filed p:integer l:"Initial Unemployment Claims Filed" t:dataTypeName=number

metric m:minimum_wage p:double l:"Minimum Wage" t:dataTypeName=money

metric m:potential_osha_fines_avoided_by_missouri_businesses p:integer l:"Potential OSHA Fines Avoided by Missouri Businesses" t:dataTypeName=money

metric m:workers_compensation_injuries_filed p:integer l:"Workers' Compensation Injuries Filed" t:dataTypeName=number

entity e:ymz7-guyk l:"Labor Quick Facts" t:url=https://data.mo.gov/api/views/ymz7-guyk

property e:ymz7-guyk t:meta.view v:id=ymz7-guyk v:category=Labor v:averageRating=0 v:name="Labor Quick Facts"

property e:ymz7-guyk t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:ymz7-guyk t:meta.view.tableauthor v:id=eb88-upz2 v:screenName=DOLIR v:roleName=editor v:displayName=DOLIR
```

## Top Records

```ls
| date                | unemployment_rate | initial_unemployment_claims_filed | minimum_wage | potential_osha_fines_avoided_by_missouri_businesses | workers_compensation_injuries_filed | 
| =================== | ================= | ================================= | ============ | =================================================== | =================================== | 
| 2009-08-01T00:00:00 | 9.7               | 43377                             | 7.25         | 289948                                              | 9687                                | 
| 2009-09-01T00:00:00 | 9.7               | 40247                             | 7.25         | 338948                                              | 9859                                | 
| 2009-10-01T00:00:00 | 9.7               | 59944                             | 7.25         | 204140                                              | 9629                                | 
| 2009-11-01T00:00:00 | 9.6               | 54815                             | 7.25         | 206908                                              | 8703                                | 
| 2009-12-01T00:00:00 | 9.6               | 68372                             | 7.25         | 218672                                              | 8851                                | 
| 2010-01-01T00:00:00 | 9.4               | 57493                             | 7.25         | 215904                                              | 8910                                | 
| 2010-02-01T00:00:00 | 9.4               | 39453                             | 7.25         | 310708                                              | 9511                                | 
| 2010-03-01T00:00:00 | 9.5               | 44139                             | 7.25         | 249812                                              | 9872                                | 
| 2010-04-01T00:00:00 | 9.5               | 38102                             | 7.25         | 495472                                              | 9208                                | 
| 2010-05-01T00:00:00 | 9.3               | 37138                             | 7.25         | 366068                                              | 9748                                | 
```