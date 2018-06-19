# 2012 Primary - Elections Results (final daily)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-format-august-2012-primary-results-king-county-f1ef2) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ax8b-wymb) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ax8b-wymb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ax8b-wymb/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ax8b-wymb |
| Name | 2012 Primary - Elections Results (final daily) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 primary, primary, elections, results |
| Created | 2012-08-28T21:05:10Z |
| Publication Date | 2012-08-28T21:09:51Z |

## Description

August 2012 primary election; final daily results report.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | contest_name      | Contest Name      | text      | text        |
| Yes      | series tag     | nameonballot      | NameOnBallot      | text      | text        |
| Yes      | series tag     | party             | Party             | text      | text        |
| Yes      | numeric metric | votes             | Votes             | number    | number      |
| Yes      | numeric metric | percent           | Percent           | number    | number      |
| Yes      | numeric metric | votes_cast        | Votes Cast        | number    | number      |
| Yes      | numeric metric | registered_voters | Registered Voters | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ax8b-wymb d:2012-01-01T00:00:00.000Z t:contest_name="King County Proposition No. 1" t:nameonballot=Approved m:percent=55.42 m:registered_voters=1110063 m:votes_cast=432049 m:votes=226544

series e:ax8b-wymb d:2012-01-01T00:00:00.000Z t:contest_name="King County Proposition No. 1" t:nameonballot=Rejected m:percent=44.57 m:registered_voters=1110063 m:votes_cast=432049 m:votes=182205

series e:ax8b-wymb d:2012-01-01T00:00:00.000Z t:contest_name="U.S. Senator  partisan office" t:nameonballot="Michael Baumgartner" t:party="(Prefers Republican Party)" m:percent=22.53 m:registered_voters=1110063 m:votes_cast=432049 m:votes=95062
```

## Meta Commands

```ls
metric m:votes p:integer l:Votes t:dataTypeName=number

metric m:percent p:float l:Percent t:dataTypeName=number

metric m:votes_cast p:integer l:"Votes Cast" t:dataTypeName=number

metric m:registered_voters p:integer l:"Registered Voters" t:dataTypeName=number

entity e:ax8b-wymb l:"2012 Primary - Elections Results (final daily)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/ax8b-wymb

property e:ax8b-wymb t:meta.view v:id=ax8b-wymb v:category="Election results" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="2012 Primary - Elections Results (final daily)" v:attribution="King County Elections"

property e:ax8b-wymb t:meta.view.license v:name="Public Domain"

property e:ax8b-wymb t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:ax8b-wymb t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| contest_name                  | nameonballot               | party                      | votes  | percent | votes_cast | registered_voters | 
| ============================= | ========================== | ========================== | ====== | ======= | ========== | ================= | 
| King County Proposition No. 1 | Approved                   |                            | 226544 | 55.42   | 432049     | 1110063           | 
| King County Proposition No. 1 | Rejected                   |                            | 182205 | 44.57   | 432049     | 1110063           | 
| U.S. Senator partisan office  | Michael Baumgartner        | (Prefers Republican Party) | 95062  | 22.53   | 432049     | 1110063           | 
| U.S. Senator partisan office  | Will Baker                 | (Prefers Reform Party)     | 2156   | 0.51    | 432049     | 1110063           | 
| U.S. Senator partisan office  | Chuck Jackson              | (Prefers Republican Party) | 4230   | 1       | 432049     | 1110063           | 
| U.S. Senator partisan office  | Timmy (Doc) Wilson         | (Prefers Democratic Party) | 7415   | 1.75    | 432049     | 1110063           | 
| U.S. Senator partisan office  | Art Coday                  | (Prefers Republican Party) | 20543  | 4.87    | 432049     | 1110063           | 
| U.S. Senator partisan office  | Maria Cantwell             | (Prefers Democratic Party) | 284999 | 67.56   | 432049     | 1110063           | 
| U.S. Senator partisan office  | Glen (Stocky) R. Stockwell | (Prefers Republican Party) | 3802   | 0.9     | 432049     | 1110063           | 
| U.S. Senator partisan office  | Mike the Mover             | (Prefers Republican Party) | 3176   | 0.75    | 432049     | 1110063           | 
```