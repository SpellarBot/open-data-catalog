# 2010 General - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-november-2-2010-general-election-88508) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/jet5-cigp) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/jet5-cigp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/jet5-cigp/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | jet5-cigp |
| Name | 2010 General - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2010, 2010 general, general, elections, results, precinct, ecanvass |
| Created | 2010-11-30T00:36:40Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

November 2010 election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | race                    | Race                    | text      | text        |
| Yes      | series tag     | precinct                | Precinct                | text      | text        |
| Yes      | series tag     | legislative_district    | Legislative District    | text      | number      |
| Yes      | series tag     | county_council_district | County Council District | text      | number      |
| Yes      | series tag     | congressional_district  | Congressional District  | text      | number      |
| Yes      | series tag     | party                   | Party                   | text      | text        |
| Yes      | series tag     | candidate               | Candidate               | text      | text        |
| Yes      | numeric metric | sumofcount              | SumOfCount              | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jet5-cigp d:2010-01-01T00:00:00.000Z t:precinct=KAMIAKIN t:legislative_district=45 t:county_council_district=3 t:candidate="Times Blank Voted" t:party=NP t:congressional_district=1 t:race="State Supreme Court Justice Position No. 5 nonpartisan office" m:sumofcount=173

series e:jet5-cigp d:2010-01-01T00:00:00.000Z t:precinct=KAMIAKIN t:legislative_district=45 t:county_council_district=3 t:candidate="Times Counted" t:party=NP t:congressional_district=1 t:race="State Supreme Court Justice Position No. 5 nonpartisan office" m:sumofcount=401

series e:jet5-cigp d:2010-01-01T00:00:00.000Z t:precinct=KAMIAKIN t:legislative_district=45 t:county_council_district=3 t:candidate="Times Over Voted" t:party=NP t:congressional_district=1 t:race="State Supreme Court Justice Position No. 5 nonpartisan office" m:sumofcount=0
```

## Meta Commands

```ls
metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:jet5-cigp l:"2010 General - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/jet5-cigp

property e:jet5-cigp t:meta.view v:id=jet5-cigp v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2010 General - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:jet5-cigp t:meta.view.license v:name="Public Domain"

property e:jet5-cigp t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:jet5-cigp t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                                                          | precinct | legislative_district | county_council_district | congressional_district | party | candidate          | sumofcount | 
| ============================================================= | ======== | ==================== | ======================= | ====================== | ===== | ================== | ========== | 
| State Supreme Court Justice Position No. 5 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Times Blank Voted  | 173.00     | 
| State Supreme Court Justice Position No. 5 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Times Counted      | 401.00     | 
| State Supreme Court Justice Position No. 5 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Times Over Voted   | 0.00       | 
| State Supreme Court Justice Position No. 5 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Write-in           | 2.00       | 
| State Supreme Court Justice Position No. 6 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Charlie Wiggins    | 133.00     | 
| State Supreme Court Justice Position No. 6 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Registered Voters  | 577.00     | 
| State Supreme Court Justice Position No. 6 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Richard B. Sanders | 150.00     | 
| State Supreme Court Justice Position No. 6 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Times Blank Voted  | 117.00     | 
| State Supreme Court Justice Position No. 6 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Times Counted      | 401.00     | 
| State Supreme Court Justice Position No. 6 nonpartisan office | KAMIAKIN | 45                   | 3                       | 1                      | NP    | Times Over Voted   | 0.00       | 
```