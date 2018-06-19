# 2010 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-aug-2010-primary-election-1fff3) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4h7u-3cfs) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4h7u-3cfs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4h7u-3cfs/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4h7u-3cfs |
| Name | 2010 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2010, 2010 primary, primary, elections, results, precinct, ecanvass |
| Created | 2010-09-22T17:58:44Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

August 2010 primary election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | race                 | RACE                 | text      | text        |
| Yes      | series tag     | precinct             | PRECINCT             | text      | text        |
| Yes      | series tag     | legislative_district | LEGISLATIVE DISTRICT | text      | number      |
| Yes      | numeric metric | county_council       | COUNTY COUNCIL       | number    | number      |
| Yes      | numeric metric | congressional        | CONGRESSIONAL        | number    | number      |
| Yes      | series tag     | candidate            | Candidate            | text      | text        |
| Yes      | numeric metric | count                | COUNT                | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4h7u-3cfs d:2010-01-01T00:00:00.000Z t:precinct="FED 30-2988" t:legislative_district=30 t:candidate="Jim Ferrell" t:race="City of Federal Way Mayor initial 3-year term nonpartisan office" m:count=55 m:congressional=9 m:county_council=7

series e:4h7u-3cfs d:2010-01-01T00:00:00.000Z t:precinct="FED 30-2988" t:legislative_district=30 t:candidate="Linda Kochmar" t:race="City of Federal Way Mayor initial 3-year term nonpartisan office" m:count=51 m:congressional=9 m:county_council=7

series e:4h7u-3cfs d:2010-01-01T00:00:00.000Z t:precinct="FED 30-2988" t:legislative_district=30 t:candidate="Mike Park" t:race="City of Federal Way Mayor initial 3-year term nonpartisan office" m:count=49 m:congressional=9 m:county_council=7
```

## Meta Commands

```ls
metric m:county_council p:integer l:"COUNTY COUNCIL" t:dataTypeName=number

metric m:congressional p:integer l:CONGRESSIONAL t:dataTypeName=number

metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:4h7u-3cfs l:"2010 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/4h7u-3cfs

property e:4h7u-3cfs t:meta.view v:id=4h7u-3cfs v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections/results v:averageRating=100 v:name="2010 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:4h7u-3cfs t:meta.view.license v:name="Public Domain"

property e:4h7u-3cfs t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:4h7u-3cfs t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                                                             | precinct    | legislative_district | county_council | congressional | candidate         | count | 
| ================================================================ | =========== | ==================== | ============== | ============= | ================= | ===== | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Jim Ferrell       | 55    | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Linda Kochmar     | 51    | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Mike Park         | 49    | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Registered Voters | 464   | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Skip Priest       | 55    | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Times Blank Voted | 12    | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Times Counted     | 222   | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Times Over Voted  | 0     | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2988 | 30                   | 7              | 9             | Write-in          | 0     | 
| City of Federal Way Mayor initial 3-year term nonpartisan office | FED 30-2990 | 30                   | 7              | 9             | Jim Ferrell       | 22    | 
```