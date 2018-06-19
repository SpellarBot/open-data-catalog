# 2012 Bond Program Voter Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-bond-program-voter-results) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qmwp-kjjs) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qmwp-kjjs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qmwp-kjjs/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qmwp-kjjs |
| Name | 2012 Bond Program Voter Results |
| Attribution | City of Austin |
| Category | Capital Planning |
| Tags | 2012 bond, election, votes |
| Created | 2013-08-23T20:20:22Z |
| Publication Date | 2013-08-23T21:14:45Z |

## Description

2012 Bond Election Voter Results

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | 2012_bond_program_proposition_number | 2012 Bond Program Proposition Number | text      | text        |
| Yes      | series tag     | voter_response                       | Voter Response                       | text      | text        |
| Yes      | numeric metric | number_of_responses                  | Number of Responses                  | number    | number      |
| Yes      | numeric metric | percentage_of_responses              | Percentage of Responses              | percent   | percent     |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qmwp-kjjs d:2012-01-01T00:00:00.000Z t:voter_response=Yes t:2012_bond_program_proposition_number="Proposition 12: Transportation" m:percentage_of_responses=55 m:number_of_responses=131577

series e:qmwp-kjjs d:2012-01-01T00:00:00.000Z t:voter_response=No t:2012_bond_program_proposition_number="Proposition 12: Transportation" m:percentage_of_responses=45 m:number_of_responses=107233

series e:qmwp-kjjs d:2012-01-01T00:00:00.000Z t:voter_response=Yes t:2012_bond_program_proposition_number="Proposition 13: Open Space" m:percentage_of_responses=56 m:number_of_responses=133204
```

## Meta Commands

```ls
metric m:number_of_responses p:integer l:"Number of Responses" t:dataTypeName=number

metric m:percentage_of_responses p:integer l:"Percentage of Responses" t:dataTypeName=percent

entity e:qmwp-kjjs l:"2012 Bond Program Voter Results" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/qmwp-kjjs

property e:qmwp-kjjs t:meta.view v:id=qmwp-kjjs v:category="Capital Planning" v:attributionLink=http://www.data.austintexas.gov v:averageRating=0 v:name="2012 Bond Program Voter Results" v:attribution="City of Austin"

property e:qmwp-kjjs t:meta.view.license v:name="Public Domain"

property e:qmwp-kjjs t:meta.view.owner v:id=k6xj-wrjq v:screenName="Ashley Parsons" v:displayName="Ashley Parsons"

property e:qmwp-kjjs t:meta.view.tableauthor v:id=k6xj-wrjq v:screenName="Ashley Parsons" v:roleName=editor v:displayName="Ashley Parsons"
```

## Top Records

```ls
| 2012_bond_program_proposition_number | voter_response | number_of_responses | percentage_of_responses | 
| ==================================== | ============== | =================== | ======================= | 
| Proposition 12: Transportation       | Yes            | 131577              | 55                      | 
| Proposition 12: Transportation       | No             | 107233              | 45                      | 
| Proposition 13: Open Space           | Yes            | 133204              | 56                      | 
| Proposition 13: Open Space           | No             | 104853              | 44                      | 
| Proposition 14: Parks & Recreation   | Yes            | 142553              | 59                      | 
| Proposition 14: Parks & Recreation   | No             | 98038               | 41                      | 
| Proposition 15: Housing              | Yes            | 114749              | 49                      | 
| Proposition 15: Housing              | No             | 121470              | 51                      | 
| Proposition 16: Public Safety        | Yes            | 131066              | 55                      | 
| Proposition 16: Public Safety        | No             | 106078              | 45                      | 
```