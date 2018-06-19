# Park Evaluation Scores starting Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/park-evaluation-scores-starting-fiscal-year-2015) |
| Metadata | [Link](https://data.sfgov.org/api/views/r33y-seqv) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/r33y-seqv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/r33y-seqv/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | r33y-seqv |
| Name | Park Evaluation Scores starting Fiscal Year 2015 |
| Category | Culture and Recreation |
| Tags | evaluation, parks, rec and park |
| Created | 2016-03-18T18:39:59Z |
| Publication Date | 2016-03-22T20:34:11Z |

## Description

Since 2005, the San Francisco Park Evaluation Program (SFPEP) has regularly evaluated and assessed the conditions of all San Francisco civic plazas and squares, mini parks, neighborhood parks and playgrounds, parkways and regional parks. The City Services Auditor division of the Controller?s Office and Recreation & Parks Department (RPD) staff conduct quarterly evaluations and use the results to communicate the condition of San Francisco?s parks to RPD management and park staff, elected officials, and the public, and to improve park conditions by efficient resource allocation and improved maintenance. Starting with fiscal year 2015, the data are collected and maintained in a source system with the Contoller's office, prior historic data will be provided by Rec and Park.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | park                | Park                | text      | text        |
| Yes      | series tag     | park_type           | Park Type           | text      | text        |
| Yes      | numeric metric | park_site_score     | Park Site Score     | number    | number      |
| Yes      | series tag     | psa                 | PSA                 | text      | text        |
| Yes      | series tag     | supervisor_district | Supervisor District | text      | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r33y-seqv d:2015-01-01T00:00:00.000Z t:park="10th Avenue-Clement Mini Park" t:psa="PSA 1" t:park_type="Mini Park" t:supervisor_district=1 m:park_site_score=88.2

series e:r33y-seqv d:2015-01-01T00:00:00.000Z t:park="24th Street-York Mini Park" t:psa="PSA 6" t:park_type="Mini Park" t:supervisor_district=9 m:park_site_score=89.4

series e:r33y-seqv d:2015-01-01T00:00:00.000Z t:park="Adam Rogers Park" t:psa="PSA 3" t:park_type="Neighborhood Park or Playground" t:supervisor_district=10 m:park_site_score=88.4
```

## Meta Commands

```ls
metric m:park_site_score p:float l:"Park Site Score" d:"Park scores are generated using the methodology documented here: http://sfparkscores.weebly.com/about.html" t:dataTypeName=number

entity e:r33y-seqv l:"Park Evaluation Scores starting Fiscal Year 2015" t:url=https://data.sfgov.org/api/views/r33y-seqv

property e:r33y-seqv t:meta.view v:id=r33y-seqv v:category="Culture and Recreation" v:averageRating=0 v:name="Park Evaluation Scores starting Fiscal Year 2015"

property e:r33y-seqv t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:r33y-seqv t:meta.view.owner v:id=25jb-2mmy v:screenName="Claire Phillips" v:displayName="Claire Phillips"

property e:r33y-seqv t:meta.view.tableauthor v:id=25jb-2mmy v:screenName="Claire Phillips" v:roleName=editor v:displayName="Claire Phillips"
```

## Top Records

```ls
| park                          | park_type                       | park_site_score | psa   | supervisor_district | 
| ============================= | =============================== | =============== | ===== | =================== | 
| 10th Avenue-Clement Mini Park | Mini Park                       | 88.2            | PSA 1 | 1                   | 
| 24th Street-York Mini Park    | Mini Park                       | 89.4            | PSA 6 | 9                   | 
| Adam Rogers Park              | Neighborhood Park or Playground | 88.4            | PSA 3 | 10                  | 
| Alamo Square                  | Neighborhood Park or Playground | 85.0            | PSA 2 | 5                   | 
| Alice Chalmers Playground     | Neighborhood Park or Playground | 63.1            | PSA 3 | 11                  | 
| Alice Marble Tennis Courts    | Neighborhood Park or Playground | 93.9            | PSA 1 | 2                   | 
| Alioto Mini Park              | Mini Park                       | 90.6            | PSA 6 | 9                   | 
| Allyne Park                   | Neighborhood Park or Playground | 77.7            | PSA 1 | 2                   | 
| Alta Plaza                    | Neighborhood Park or Playground | 83.9            | PSA 1 | 2                   | 
| Angelo J. Rossi Playground    | Neighborhood Park or Playground | 89.0            | PSA 1 | 1                   | 
```