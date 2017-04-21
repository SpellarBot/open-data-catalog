# GTOPS 2015 Performance Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gtops-2015-performance-measures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/i8u6-gqak) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/i8u6-gqak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/i8u6-gqak/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | i8u6-gqak |
| Name | GTOPS 2015 Performance Measures |
| Attribution | City of Austin Office of Telecommunications & Regulatory Affairs - Digital Inclusion Program |
| Category | Government |
| Tags | digital inclusion, technology, grant, performance, outputs, outcomes, community, impact |
| Created | 2015-11-17T21:02:53Z |
| Publication Date | 2015-11-17T21:14:24Z |

## Description

Grant for Technology Opportunities Program (GTOPS) 2015 Performance Measures. View the Outputs an Outputs from the 2015 GTOPs awardees to measure digital inclusion community impact.

## Columns

```ls
| Included | Schema Type | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | =========== | =========================================== | =========================================== | ========= | =========== |
| Yes      | series tag  | total_number_of_unduplicated_clients_served | Total Number of Unduplicated Clients Served | text      | text        |
| No       |             | q1                                          | Q1                                          | text      | text        |
| No       |             | q2                                          | Q2                                          | text      | text        |
| No       |             | q3                                          | Q3                                          | text      | text        |
| No       |             | q4                                          | Q4                                          | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = q1,q2,q3,q4
```

## Data Commands

```ls
series e:i8u6-gqak d:2015-01-01T00:00:00.000Z t:total_number_of_unduplicated_clients_served="Austin Free-Net" m:row_number.i8u6-gqak=1

series e:i8u6-gqak d:2015-01-01T00:00:00.000Z t:total_number_of_unduplicated_clients_served="Austin Achieve Public School, Inc." m:row_number.i8u6-gqak=2

series e:i8u6-gqak d:2015-01-01T00:00:00.000Z t:total_number_of_unduplicated_clients_served=Breakthrough m:row_number.i8u6-gqak=3
```

## Meta Commands

```ls
metric m:row_number.i8u6-gqak p:long l:"Row Number"

entity e:i8u6-gqak l:"GTOPS 2015 Performance Measures" t:attribution="City of Austin Office of Telecommunications & Regulatory Affairs - Digital Inclusion Program" t:url=https://data.austintexas.gov/api/views/i8u6-gqak

property e:i8u6-gqak t:meta.view v:id=i8u6-gqak v:category=Government v:attributionLink=http://austintexas.gov/department/grant-technology-opportunities-program v:averageRating=0 v:name="GTOPS 2015 Performance Measures" v:attribution="City of Austin Office of Telecommunications & Regulatory Affairs - Digital Inclusion Program"

property e:i8u6-gqak t:meta.view.license v:name="Public Domain"

property e:i8u6-gqak t:meta.view.owner v:id=yczp-v4p4 v:screenName="Sharla Chamberlain" v:displayName="Sharla Chamberlain"

property e:i8u6-gqak t:meta.view.tableauthor v:id=yczp-v4p4 v:screenName="Sharla Chamberlain" v:roleName=editor v:displayName="Sharla Chamberlain"
```

## Top Records

```ls
| total_number_of_unduplicated_clients_served | q1  | q2 | q3 | q4 | 
| =========================================== | === | == | == | == | 
| Austin Free-Net                             |     |    |    |    | 
| Austin Achieve Public School, Inc.          | 283 |    |    |    | 
| Breakthrough                                | 516 |    |    |    | 
| The Arc of the Capital Area                 | 46  |    |    |    | 
| The Housing Authority of the City of Austin | TBD |    |    |    | 
| Skillpoint Alliance                         | 47  |    |    |    | 
| Knowbility, Inc.                            | 28  |    |    |    | 
| Capitol Area Council, Boy Scouts of America | 52  |    |    |    | 
| Texas Folklife Resources                    | 51  |    |    |    | 
| Austin Children's Museum                    | 20  |    |    |    | 
```