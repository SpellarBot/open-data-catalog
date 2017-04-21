# 2010 General - Election results - State Senator LD 41 recount

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-state-senator-legislative-district-41-recount-nov-2-2010-general-95387) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/a29e-gcic) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/a29e-gcic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/a29e-gcic/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | a29e-gcic |
| Name | 2010 General - Election results - State Senator LD 41 recount |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2010, 2010 general, general, elections, results, precinct, ecanvass, recount |
| Created | 2010-12-04T00:35:32Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

November 2010 general election - recount dataset for the State Senator Legislative District 41

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | race                    | Race                    | text      | text        |
| Yes      | series tag     | precinct                | Precinct                | text      | text        |
| Yes      | series tag     | legislative_district    | Legislative District    | text      | number      |
| Yes      | series tag     | county_council_district | County Council District | text      | number      |
| Yes      | series tag     | congressional_district  | Congressional District  | text      | number      |
| Yes      | series tag     | party_preference        | Party preference        | text      | text        |
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
series e:a29e-gcic d:2010-01-01T00:00:00.000Z t:precinct=ALLEN t:legislative_district=41 t:county_council_district=6 t:candidate="Randy Gordon" t:congressional_district=8 t:race="State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office" t:party_preference=Dem m:sumofcount=132

series e:a29e-gcic d:2010-01-01T00:00:00.000Z t:precinct=ALLEN t:legislative_district=41 t:county_council_district=6 t:candidate="Registered Voters" t:congressional_district=8 t:race="State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office" t:party_preference=NP m:sumofcount=352

series e:a29e-gcic d:2010-01-01T00:00:00.000Z t:precinct=ALLEN t:legislative_district=41 t:county_council_district=6 t:candidate="Times Blank Voted" t:congressional_district=8 t:race="State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office" t:party_preference=NP m:sumofcount=10
```

## Meta Commands

```ls
metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:a29e-gcic l:"2010 General - Election results - State Senator LD 41 recount" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/a29e-gcic

property e:a29e-gcic t:meta.view v:id=a29e-gcic v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2010 General - Election results - State Senator LD 41 recount" v:attribution="King County Elections"

property e:a29e-gcic t:meta.view.license v:name="Public Domain"

property e:a29e-gcic t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:a29e-gcic t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                                                                         | precinct    | legislative_district | county_council_district | congressional_district | party_preference | candidate         | sumofcount | 
| ============================================================================ | =========== | ==================== | ======================= | ====================== | ================ | ================= | ========== | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | Dem              | Randy Gordon      | 132.00     | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | NP               | Registered Voters | 352.00     | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | NP               | Times Blank Voted | 10.00      | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | NP               | Times Counted     | 241.00     | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | NP               | Times Over Voted  | 1.00       | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | NP               | Write-in          | 0.00       | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | ALLEN       | 41                   | 6                       | 8                      | Rep              | Steve Litzow      | 98.00      | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | BEA 41-0099 | 41                   | 6                       | 8                      | Dem              | Randy Gordon      | 83.00      | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | BEA 41-0099 | 41                   | 6                       | 8                      | NP               | Registered Voters | 213.00     | 
| State Senator Legislative Dist No. 41 unexpired 2-year term, partisan office | BEA 41-0099 | 41                   | 6                       | 8                      | NP               | Times Blank Voted | 6.00       | 
```